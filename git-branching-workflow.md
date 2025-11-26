# Basic Git Workflow

## Setup Project

1. create project
2. add some code
3. open terminal in project directory
   ```shell
   git init
   git add .
   git commit -m "commit message"
   git remote add origin [github url]
   git push origin main
   ```

## Ongoing Workflow

1. create a branch `git branch [branch name]`
   > Branch name should be lowercased
   > branch name examples 
      - `fix/issue-345-validation-incorrect`
      - `feature/api-customers`
2. switch to the branch 
      - `git checkout [branch name]` 
      - or 
      - `git switch [branch name]`
   > Steps one and two can be done with one command
      - `git checkout -b [branch name]`
      - `git switch -c [branch name]` 
1. update the code
2. run the commands
   ```shell
   git add .
   git commit -m "commit message"
   git push origin [branch name]
   ```
3. repeat these steps as many times as needed


## Merging

1. checkout the `main` branch
1. merge the `feature/my-feature` branch into the `main` branch
   ```shell
   git checkout main
   git merge [feature branch name]
   git push origin main
   ```



## Verification

- `git status`
- `git log --oneline`

## Tips

- this is your first tip
-



