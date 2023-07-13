# Mark Avenue MTA-STS Policy

## Updating

After updated policy is deployed, don't forget to update `id` field in `_mta-sts` TXT DNS record to the output of:

```console
$ git hash-object public/.well-known/mta-sts.txt | head -c 32
```
