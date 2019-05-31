This is a quick prototype of a theming tooling for Plone.
Warning it assumes you have Docker installed.
## Usage
The following command will generate a theme called `my.theme`
```
bash scripts/gloss_init my.theme
```
The theme is placed under resources > theme

To serve the theme, run the following command:
```
bash scripts/gloss_serve
```

This will launch Zope/Plone on port 8080

Visit `localhost:8080`
and create a new plone site.
When promoted use the credentials: admin/admin

You will see your theme available under `Site Settings > Theming`


