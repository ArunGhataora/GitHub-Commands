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
git checkout FR_X
```

#### Commit From A Branch
- If you're comfortable with the changes made you can commit and push
```
git commit
git push
```

#### Once Changes Committed You Will Have To Raise A Pull Request
- To have it marge tto the master branch you then raise a pull request via Github.com
