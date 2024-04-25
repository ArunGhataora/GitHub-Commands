### GitHub-Commands
Common Github Commands

#### Change Directory into the desired GIT folder
```
cd C:\Users\Arun Ghataora\Documents\GitHub\financialsdb 
```

#### Checking Status
- Provides the current status of your GIT repository compared to master
```
git status
```

#### Hard Resetting To Master
- If you're in trouble and want to abandon what you have in favour of master then: 
```
git reset --hard origin/master
```

#### Checking Out New Branches
- Typically we name our branches after a corresponding JIRA ticket
```
git checkout -b ＜new-branch＞
```

#### Commit From A Branch
- If you're comfortable with the changes made you can commit and push
```
git commit
git push
```

#### GIT Squashing (For Pull Requests)
- To get all changes from multiple commits summarised in a single commit message + will update the pull request where changes have been made subsequently to the pull request being made.

- The process is:
  -- CHECKOUT Main Branch
  -- PULL New Changes
  -- MERGE main branch to target branch
  -- RESET to main branch
  -- FORCE PUSH branch

Code: 
  ```
git checkout prelive
git pull
git checkout [your branch]
git merge prelive
git reset prelive
git push -f
```

#### Changing A Branch Name (For Pull Requests)
```
branch -m DM-270/EQ-Card-Summary-Dashboard DM-277/EQ-Card-Summary-Dashboard
```

#### Once Changes Committed You Will Have To Raise A Pull Request
- To finally marge onto the master branch you then raise a pull request via Github.com


