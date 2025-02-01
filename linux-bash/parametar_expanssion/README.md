# Parameter Expansion

## ${parameter:-word}

If parameter is **unset or null**, use word as the default value.

```bash
# HACK: 1) ${parameter:-world}

var=""
echo ${var:-"default"}  # Output: default
```
