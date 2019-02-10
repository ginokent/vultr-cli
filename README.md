# vultr-cli

[Vultr](https://www.vultr.com/?ref=7845607-4F) Command Line Interface written in shell script.

### Dependencies

- `curl`
- [`jq`](https://stedolan.github.io/jq/)

### Install

```console
$ curl -LRsS https://raw.githubusercontent.com/djeeno/vultr-cli/master/vultr -o /tmp/vultr
$ chmod +x /tmp/vultr
$ sudo mv /tmp/vultr /usr/local/bin/vultr
```

### Tab completion

```console
$ eval "$(vultr completion)"

$ vultr  # <tab>
account        configure      firewall       network        os             plans          regions        server         startupscript  tools          version
```

### Set Credentials

```console
$ vultr configure
ref. https://my.vultr.com/settings/#settingsapi
Vultr API key: ************************************
```

### Run

```console
$ vultr server list
  ...
```
