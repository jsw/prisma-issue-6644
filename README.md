See https://github.com/prisma/prisma/issues/6644#issuecomment-839322436

Run `serverless package` and then inspect contents...

```
➜  prisma-package git:(master) unzip -l .serverless/test.zip| grep query-engine
 45213280  01-01-1980 00:00   node_modules/.prisma/client/query-engine-rhel-openssl-1.0.x
 37170408  01-01-1980 00:00   node_modules/@prisma/engines/query-engine-darwin
 37170408  01-01-1980 00:00   node_modules/prisma/query-engine-darwin
 45213280  01-01-1980 00:00   node_modules/prisma/query-engine-rhel-openssl-1.0.x
 ```
