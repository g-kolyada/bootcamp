# Parameter Expansion

## ${parameter:-word}

If parameter is **unset or null**, use word as the default value.

```bash
# HACK: 1) ${parameter:-world}

var=""
echo ${var:-"default"}  # Output: default
```

## ${parameter:=word}

If parameter is unset or null, assign word to parameter and use it.

```bash
# HACK: 2) ${parameter:=word}

unset var
echo ${var:="default"}  # Output: default
echo $var               # Output: default
```
