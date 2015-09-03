# AndroidDevLab

Android developer laboratory setup, documentation available [here](https://github.com/stefanprodan/AndroidDevLab/wiki)

Workstations boxstarter script [here](https://gist.github.com/stefanprodan/eee6e815156cb440dffb)

```
START http://boxstarter.org/package/nr/url?https://gist.githubusercontent.com/stefanprodan/eee6e815156cb440dffb/raw/8cfdc450ecf182d97ef0db769dbf4efb6f266c00/Boxstarter.ps1
```

GitLab Certificate gen:

```bash
sudo openssl req -x509 -nodes -days 1800 -newkey rsa:2048 -keyout "/etc/gitlab/ssl/git.lab.key" -out "/etc/gitlab/ssl/git.lab.crt"
```
