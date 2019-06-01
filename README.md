This is a quick prototype of a theming tooling for Plone.
Warning it assumes you have Docker installed.
## Usage
1. Start by checking out the gloss.docker repo
```
git clone https://github.com/GlossProject/gloss.docker
```

2. initialize your new theme 
```
bash gloss.docker/scripts/init my.theme
```
The theme is placed under resources > theme

3. Serve the site with your theme by running the following command:
```
bash gloss.docker/scripts/serve
```

This will launch Zope/Plone on port 8080

Visit `localhost:8080`
and create a new plone site.
When promoted use the credentials: admin/admin

You will see your theme available under `Site Settings > Theming`


