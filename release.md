# To release a new version

I forget if I don't see this code in a month

1. Create a new tag

```bash
git tag -a <version> -m 'new features and credits'
git push origin <version>
```

The tag must match the version in `manifest.json` prefixed with `v`
