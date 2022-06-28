# Hugo configurations

## Setup
Adding a new post
```bash
hugo new posts/"post name".md
```

To add new blog/news posts, simply create a new markdown file in the news folder under the content

## Usage
Running the server 
```bash
NPM Start
```

Building static pages
```bash
hugo serve 
```
Go to [http://localhost:1313/](http://localhost:1313) to view static page 


Design changes to be made in the config.toml file

## Templating

```list.html``` - home page
```single.html``` - each individual page format

## Accessing Photos
All images are stored in the ```static/photos``` folder at the app root level. At this level whenever you want to reference a specific image, simply put ```/"image type"```

## News format
All blog/news format shall be stored in the ```/i18n/en.yaml``` folder.

## Personal edits to page
Any edits that is outside of the theme will be added to the ```/layouts/_default``` folder (see exco.html for example). Adding new page to the ```config.toml``` will also require you to add the page name inside the contents folder. 



