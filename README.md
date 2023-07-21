# BizBoost Project

This is the starter project for the **BizBoost** Assignment project.

This project is mobile-first focused.

### Install

Checkout the project

```
https://github.com/jorgecarmona/bizboost-mobile-first.git
```

Change directory to project

```
cd bizboost-mobile-first
```

Verify current repo url. This is currently pointing to the original repository.

```
  git remote -v
```

## Create New Project in Your Personal Github Account

1. Create a new project with the name `bizboost-mobile-first`
2. Remove original repository from project.

```
  rm -rf .git
```

3. Initialize your new repository

```
  git init
```

4. Run the following git commands from your newly created github project in [htt://github.com](htt://github.com)

   Add your new repository. Replace url with your git repository.

   ```
   git remote add origin https://github.com/<your-repository>/bizboost-mobile-first.git
   ```

   Create new develop branch

   ```
   git branch -M develop
   ```

   Add all files to your new repo

   ```
   git add .
   ```

   Create first commit

   ```
   git commit -m "initial commit"
   ```

   Push changes to your branch

   ```
   git push -u origin develop
   ```

To start working, create your first branch to create layout for the hero section.

```
git checkout -b feat/hero-section-layout
```
