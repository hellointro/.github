# hello glad to meet you!
[html](http://hellointro.net) |
[npm](https://www.npmjs.com/package/hellointro) |
[quay](https://quay.io/hellointro) 

## tools
### [git](https://git-scm.com/docs)
`man git`
<!-- ![git](https://git-scm.com/images/logo@2x.png) -->
```
git config --global init.defaultBranch customer
git config --global user.name "j0hnniewa1ker"
git config --global user.email email@j0hnniewa1ker.com
```

### [ssh](https://www.ssh.com/academy/ssh/keygen)
`man ssh`
<!-- ![ssh](https://www.ssh.com/hubfs/raw_assets/public/everblox/assets/images/logo.svg) -->
```
ssh-keygen
echo new ssh key: at https://github.com/settings/keys `cat ~/.ssh/id_rsa.pub` 
python3 -m webbrowser https://github.com/settings/keys
```

### [curl](https://curl.se) | [grep](https://www.gnu.org/software/grep/manual/grep.html)
`man curl`

`man grep`
<!-- ![curl](https://curl.se/logo/curl-logo.svg) -->
```
curl -sH "Accept: application/vnd.github.v3+json" https://api.github.com/orgs/hellointro/repos | grep "full_name"
```
```
    "full_name": "hellointro/api",
    "full_name": "hellointro/html",
    "full_name": "hellointro/react",
    "full_name": "hellointro/mariadb",
    "full_name": "hellointro/.github",
    "full_name": "hellointro/containers",
    "full_name": "hellointro/ocp",
    "full_name": "hellointro/hellointro",
```
### [node](https://nodejs.org/en/docs/)
```
node hellointro.js
```
```
Server running at http://127.0.0.1:3000/
```
```
curl http://127.0.0.1:3000/
```
```
hellointro
```