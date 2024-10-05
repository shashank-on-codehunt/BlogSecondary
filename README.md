[![Netlify Status](https://api.netlify.com/api/v1/badges/e162fc40-a49d-4808-9296-89a5948bed32/deploy-status)](https://app.netlify.com/sites/bucolic-rolypoly-8c22b1/deploys)

# Blogging project
## contains information about development and Technology
## List of projects
## About and Skills

## To Start project on local 
_make sure that ruby, gem and bundle are installed properly on system_


```bash
bundle exec jekyll serve --increment
```

- To Clean the `_site` folder

```bash
bundle exec jekyll clean
bundle exec jekyll build
```

- Some Gemfile.lock went wrong 

```bash
bundle clean --force    
rm -rf ./vendor/bundle
bundle install
```
