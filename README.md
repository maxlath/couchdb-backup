couchdb-backup
============

This repo is used to make `couchdb-backup.sh` from [couchdb-dump](https://github.com/danielebailo/couchdb-dump) easily installable in a NodeJS project:
```sh
npm install -g couchdb-backup
```

## Backup
```sh
couchdb-backup -b -H "$host" -P "$port" -u "$username" -p "$password" -d "$db_name" -f "$output_file"
```

## Restore
```sh
couchdb-backup -r -H "$host" -P "$port" -u "$username" -p "$password" -d "$db_name" -f "$input_file"
```

See [danielebailo/couchdb-dump](https://github.com/danielebailo/couchdb-dump) for options documentation

[![NPM](https://nodei.co/npm/couchdb-backup.png?stars&downloads&downloadRank)](https://npmjs.com/package/couchdb-backup/)
