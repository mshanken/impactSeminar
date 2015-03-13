#[ImpactSeminar](http://www.impactseminar.com/)

Impact Seminar site is build using harp-js for rapid static HTML generation

##How it works

There's two ways to do this either in your desktop or in our QA machine. To start you need the following installed (QA's already installed)

1. Node
2. NPM
3. Grunt
4. [Harpjs](http://harpjs.com/)

This is a static page site build with [Harpjs]. Once you have the requirements installed you can now clone this repo or git pull to update. You can start working on it, a list of commads at your dispose. Enjoy it!

##```npm install```
To install grunt task runner dependencies, NPM was added recently so you might want to run it now, not need to run it after that, unless you start by clonning the project again.

##```npm run server```
Runs harp server from your harpjs working directory (usually _site), once you run this command open your browser with this location http://localhost:9000 to preview your working site. Use ```ctrl+c``` to turn off the server.

##```npm  run compile```
Runs harp compile, this command will generate the HTML of your working project that harpjs had created, check harp project if it generates errors.

##```npm run static```
Like ```npm run server``` it turns on a server but this one serves all generated HTML, this can help you to preview if all generated HTML site works well and have updated correctly if any update

##```npm run gh-pages```
**NOTE:** this command should only be ran at the **_gh-pages branch_** only and after you run ```npm run compile``` at the same gh-pages branch.

This command will copy the compiled (HTML generated) version fo your working site in the root folder so it can be generated by github gh-pages site as a normal web-site.
