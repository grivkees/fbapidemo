1. Clone the repository.
2. `git submodule init`
3. `python -m SimpleHTTPServer 5000`
4. Open 'http://localhost:5000' in web browser.

Note:

* You'll want to change the app ID to your own app ID
* Create a new 'www' app on [developers.facebook.com](developers.facebook.com)
* Enter your localhost url (for local development) or website url (for deployment).
* Update `APP_ID` in `index.html` with your app id


To publish fresh `gh-pages`:

> git branch -D gh-pages
> git push origin --delete gh-pages
> git checkout --orphan gh-pages
> git commit -a -m "Publish gh-pages"
> git push origin gh-pages