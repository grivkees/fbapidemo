To publish fresh `gh-pages`:
```
> git branch -D gh-pages
> git push origin --delete gh-pages
> git checkout --orphan gh-pages
> git commit -a -m "Publish gh-pages"
> git push origin gh-pages
```
