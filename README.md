# bitsandbricks-defaults

Shared repository defaults for [bitsandbricks](https://github.com/bitsandbricks-ch/bitsandbricks-cli): which settings, rulesets and files each group of repos should have. `bnb doctor` compares your repos against `bitsandbricks.toml` here.

This is one example. Anyone can keep their own defaults repo and point `bnb` at it.

## Use it

```sh
bnb init bitsandbricks-ch/bitsandbricks-defaults
bnb doctor
```

`bitsandbricks.toml` names the orgs and the groups. The bitsandbricks-cli README explains every key.
