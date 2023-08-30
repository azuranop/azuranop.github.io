# azuranop.github.io


# Instructions:

1. Install hugo

2. Create a repo githubuser.github.io

3. Clone the repo

4. cd in the repo and run:

```
hugo new site --force .
```

5. Clone hugo theme 

```commandline
git clone https://github.com/roninro/hugo-theme-puppet.git themes/puppet

```

6. Copy config.toml from the theme:

```commandline
cp -p themes/pupet/exampleSite/config.toml .
```

7. Edit the config.toml

- Replace:
baseURL = "http://localhost:1313/subdir" by "https://azuranop.github.io" 

and other configuration variables (linkedin, github, etc.)

8. Test that everything works as expected:

```commandline
hugo server
```

All previous has to be executed from the same location, root folder in the repo. From step 4 onwards there are no changes 
directory

# Hosting and deployment

https://gohugo.io/hosting-and-deployment/hosting-on-github/


