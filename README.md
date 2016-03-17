#Hosting a webpage on Github

Some of my Data Science projects contain notebooks as html pages. A github repo can store the code of an html page. Here is how to do it from an existing repo

###Create an independant branch in the same repo

`git checkout --orphan gh-pages`

`git rm -rf`

The second command remove the content of the `gh-pages` that was containing the files from the master.

To switch back and forth:
`git checkout master / gh-pages`

###Add html file to the gh-page

`git commit -a -m "Ading pages"`

`git push origin gh-pages`
