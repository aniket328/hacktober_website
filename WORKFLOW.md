## Recommended work flow when contributing to the open source projects:

1. Look for projects that you would be interested in contribute to by looking up:
- [Explore](https://github.com/explore)
- Query for projects in the search box on the top left corner. For example, 
> is:open is:issue label:good-first-issue,"good first issue","hacktober" language: (your programming language) no:assignee

2. Communicate with the project owners about the feature or issue that you would like to work on before starting.

3. Fork and clone the project into your local machine:

` $ git clone (HTTPS_URL) ` 

4. For big projects, make sure you run the test script and only work on the project after all test cases have been passed.

5. Set up a remote to the upstream branch

` $ git remote add (name-of-remote)  (suggested upstream for name)  (upstream git repo) `

Check all the remote branches using:

` $ $ git remote -v `

6. If you did not work on the project over a period, make sure your project is up to date with the upstream branch using:

` $ git pull (remote_name) `

7.  **Caution: Do not work on the main branch**. Create a topic branch for yourself  to either on a feature or an issue

` $ git checkout -b (topic-branch-name) `

8. When you are ready to show your work

` $ git push origin (topic-branch-name) `