# git-reset-proxy
when you get a fatal error while trying to <code>git push</code>, try this method

```
git config --global --unset http.proxy
git config --global --unset https.proxy
restart your terminal
```
Download the script so you don't have to come back here everytime ...
