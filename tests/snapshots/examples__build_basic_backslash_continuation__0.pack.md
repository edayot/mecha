# Lectern snapshot

## Data pack

`@data_pack pack.mcmeta`

```json
{
  "pack": {
    "pack_format": 71,
    "description": ""
  }
}
```

### demo

`@function demo:foo`

```mcfunction
execute as @a[tag=blob] run function demo:foo
say hello
```
