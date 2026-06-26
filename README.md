# pumpfun-db

SQLite snapshot of pumpfun.db (gzip-compressed).

## Restore

```bash
gunzip pumpfun_snapshot.db.gz
sqlite3 pumpfun_snapshot.db ".tables"
```

MD5 of .gz: a041591d6bcf6af00e1279d784a9ffcf
