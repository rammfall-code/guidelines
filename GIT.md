# Guide about git and github

## Go to ```Actions``` tab in your repository and be sure that actions was activated. If no enable github actions

### From this
![Non active workflow](https://github.com/rammfall-code/guidelines/blob/main/images/nonActiveWorkflow.png?raw=true)
### To this
![Active workflow](https://github.com/rammfall-code/guidelines/blob/main/images/activeWorkflow.png?raw=true)

## Clone repository with task to your local machine or use github codespaces

## The task description located in README.md in every repository

## Before work, create in your cloned repo branch ```develop```

```bash
git branch -b develop
```

## Install dependencies(install additional programs which help with checking code quality)

```bash
npm i
```
## When you finish work commit your changes and push (in develop branch of course)

## In github repository go to ```Pull requests``` tab and create from develop to main

## All checks should be passed here

## After this you can move it to review
