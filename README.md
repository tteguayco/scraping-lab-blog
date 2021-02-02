# Scraping Lab Blog

This blog is built using the static site generator provided by [Hugo](https://gohugo.io/getting-started/quick-start/).

### Deployment on GitHub Pages

The site can be reach from this URL: https://tteguayco.github.io/scraping-lab-blog/

### Command cheatsheet

All commands displayed here must be executed from the root folder of the project.

#### Create new site

```
hugo new site scraping-lab-blog
```

#### Create new post

```
hugo new posts/<post_name>.md
```

#### Generate static assets

```
hugo -t <theme_name>
```

**Note**: static assets will be generated inside the folder specified in the ```publishDir``` attribute in the ```config.toml``` file.

#### Run local development server

```
hugo server
```