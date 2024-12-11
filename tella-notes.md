
- if not installed, install npm:   
`sudo aptitude install npm`
- create repository in Github:   
...
- clone to local machine:   
`git clone https://github.com/lyapschaff/test_website.git`
- change directory:   
`cd test_website/`
- initialize a hugo website (https://discourse.gohugo.io/t/deploying-to-github/50190/9):   
`hugo new site . --force`
- change directory to themes:   
`cd themes`
- add theme:   
`git submodule add https://github.com/opera7133/tella.git`
- change directory to the theme's example site:   
`cd tella/exampleSite/`
- copy a few files to the site's root folder (https://themes.gohugo.io/themes/tella/):   
`cp config.toml package.json postcss.config.js tailwind.config.js ../../../`
- deal with the javascript thing:   
`npm install`

