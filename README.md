# Fork status

1.  Now launching PM2 properly
1.  Command line interface changed, but not implemented
1.  Configuration not implemented

# dokku-pm2

Dokku plugin to utilize the power of pm2.

## Installation

Browse to dokku plugins folder and clone `dokku-pm2`,

```bash
$ cd /var/lib/dokku/plugins
$ git clone https://github.com/likeastore/dokku-pm2
```

## Configuration  (TODO)

Plugin folder contains `default.yaml` file defaults `pm2` configuration for application:

```
mode: cluster
instances: max
```

This would run the application in cluster mode utilizing maximum available CPU's.

## Commands

The list of `pm2` commands exposed by `dokku` interace:

```plain
	dokku pm2 app command
```

## License

MIT Licensed

Copyright (c) 2014s, Likeastore.com info@likeastore.com
