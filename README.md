# YAML/TOML to JSON Converter

Simple tools to convert YAML and TOML files to JSON.

Example: `test.yaml`:
```yaml
some-key:
  a: 1
  b: 2
```

```json
❯ yaml2json test.yaml
{
  "some-key": {
    "a": 1,
    "b": 2
  }
}
```

Example: `test.toml`:
```toml
[some-key]
a = 1
b = 2
```

```json
❯ toml2json test.toml
{
  "some-key": {
    "a": 1,
    "b": 2
  }
}
```
