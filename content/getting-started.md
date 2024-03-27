+++
title = 'Getting Started'
date = 2024-03-27T12:58:40+05:30
+++

## Getting Started 

1. Follow **[Hugo Docs's - Quick Start](https://gohugo.io/getting-started/quick-start/)** guide to install Hugo.  
    (Make sure you install **Hugo >= v0.112.4**)
    
2. Create a new Hugo site
    
    ```shell
    hugo new site MyFreshWebsite --format yaml
    # replace MyFreshWebsite with name of your website
    ```
    
    Note:
    
    - Older versions of Hugo may not support `--format yaml`
    - Read more here about [Hugo Docs's - hugo new site command](https://gohugo.io/commands/hugo_new_site/#synopsis)

After you have created a new site, follow the below steps to add **MinimalBP**

## Installing/Updating MnimalBP
Themes reside in MyFreshWebsite/themes directory.

MinimalBP will be installed in MyFreshWebsite/themes/minimalbp

### Install using git clone

**INSTALL** : Inside the folder of your Hugo site MyFreshWebsite, run:

```shell
    git clone https://github.com/blackpiratelive/minimalbp.git themes/minimalbp 
```


**UPDATE:** Inside the folder of your Hugo site MyFreshWebsite, run:

```shell
cd themes/minimalbp
git pull
```

### Download and unzip
Download minimalbp as a zip from github and extract it inside the themes folder. 

## Finally set theme as minimalbp in your site config

In config.yml add:

```yml
theme: ["minimalbp"]
```

Or 

In hugo.toml add:

```toml
 theme = 'minimalbp'
 ```

 
