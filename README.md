This is a redirection for the github pages at this location to another page as a test.

https://apnielsen.com/redirect --> https://apnielsen.com/high-altitude-balloon

## Steps:

### Create repo to host redirection on github

### Create `index.html` file

``` html
<!DOCTYPE html>
<meta charset="utf-8">
<title>Redirecting to https://apnielsen.com/high-altitude-balloon/</title>
<meta http-equiv="refresh" content="0; URL=https://apnielsen.com/high-altitude-balloon/">
<link rel="canonical" href="https://apnielsen.com/high-altitude-balloon/">
```

### Create `_config.yml` file 

This step may no longer be necessary, but does not hurt

``` yaml
theme: jekyll-theme-cayman
```

### Set up the `gh-pages` branch in the repo

The `gh-pages` branch in the repo is what gets published to `github.io` to publish the page, rename or create a new branch with the name `gh-pages` and push `gh-pages` to github. 

The redirection will appear after a few minutes. 

## References

https://dev.to/steveblue/setup-a-redirect-on-github-pages-1ok7
