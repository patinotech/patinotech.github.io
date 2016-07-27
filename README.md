# Patino Site
## Local Set up
>From dev branch
 - npm install
 - bower install
## Serve files
 - From dev branch:
`gulp serve`
## Development
Development is done on the dev branch.
## Production
Final production version is pushed onto master branch. Don't develop locally on the master branch. Go to dev branch.
> Unlike gh-pages, organization pages on github are on the master branch (instead of the gh-pages branch)
> From dev branch, when ready to deploy new changes
  - `gulp build`
  - `git commit -m "Commit Message"`
  - `git subtree push --prefix dist origin master`
