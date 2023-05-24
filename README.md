# RICOH THETA Camera for Automotive Interiors

[https://automotive.theta360.guide](https://automotive.theta360.guide)

## development workflow

`npm start`

## publish workflow

```text
git checkout main
git branch -D gh-pages
npm run live
git add .
git commit -m "message"
npm run gh-branch
git checkout gh-pages
git pull origin gh-pages
git push origin gh-pages
```
