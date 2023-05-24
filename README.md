# RICOH THETA Camera for Automotive Interiors

[https://automotive.theta360.guide](https://automotive.theta360.guide)

## development workflow

`npm start`

## publish workflow

```text
npm run live
git branch -D gh-pages
npm run gh-branch
git add .
git commit -m "message"
git checkout gh-pages
git pull origin gh-pages
git push origin gh-pages
```