### Install GPG suite from gpgtools.com
https://gpgtools.org/

### ~/.bash_profile
https://gist.github.com/thomxc/9ec219abbab09dcbe0effefecd265364

```
# alias for filezilla through cmd line because gpg - https://superuser.com/questions/1383380/filezilla-on-mac-yubikey-authentication
alias filezilla="/Applications/FileZilla.app/Contents/MacOS/filezilla"
```

### ~/.gnupg/gpg-agent.conf
```
default-cache-ttl 600
max-cache-ttl 7200
enable-ssh-support
```
### ~/.gnupg/gpg.conf
https://github.com/drduh/config/blob/master/gpg.conf

### other resources:
* https://github.com/drduh/YubiKey-Guide
* https://www.isi.edu/~calvin/yubikeyssh.htm#configure-gpg-agent-and-add-your-ssh-keys
* https://ocramius.github.io/blog/yubikey-for-ssh-gpg-git-and-local-login/
