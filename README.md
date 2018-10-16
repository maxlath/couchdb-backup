couchdb-backup
============

This repo is used to make `couchdb-backup.sh` from [couchdb-dump](https://github.com/danielebailo/couchdb-dump) easily installable in a NodeJS project:
```sh
npm install couchdb-backup
# See https://github.com/danielebailo/couchdb-dump for options documentation
./node_modules/.bin/couchdb-backup b -H "$host" -P "$port" -u "$username" -p "$password" -d "$db_name" -f "$output_file"
```

[![NPM](https://nodei.co/npm/couchdb-backup.png?stars&downloads&downloadRank)](https://npmjs.com/package/couchdb-backup/)
