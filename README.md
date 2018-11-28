# git-reset-proxy
when you get a fatal error when trying to push, try this method

```
git config --global --unset http.proxy
git config --global --unset https.proxy
restart your terminal
```
