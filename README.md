# git-reset-proxy
when you get a fatal error while trying to <code>git push</code>, try this method

```
git config --global --unset http.proxy
git config --global --unset https.proxy
restart your terminal
```
Download the script so you don't have to come back here everytime ...

## Make it executable
```
chmod +x git-unset-proxy.sh
```

## Run it :
```
sh ./git-unset-proxy.sh
```
OR
```
./git-unset-proxy.sh
```

## Alias for your shell configuration file :
```
alias git-proxy-broken="sh ~/git-reset-proxy/git-unset-proxy.sh"
```
