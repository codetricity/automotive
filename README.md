# RICOH THETA Camera for Automotive Interiors

[https://automotive.theta360.guide](https://automotive.theta360.guide)

## development workflow

```text
git checkout -b name-of-branch
npm start
```

* change files
* add changed files with git
* push up to branch
* make pull request

## publish workflow

```text
git checkout main
git pull
git branch -D gh-pages
npm run live
git add .
git commit -m "message"
npm run gh-branch
git checkout gh-pages
git pull --rebase origin gh-pages
git push origin gh-pages
```

## file structure

Detail pages for each automotive partner.
`src/pug/pages/`

## package installation

```text
npm install -g gulp-cli
npm install
```
