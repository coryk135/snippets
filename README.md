# Snippets

This repository contains useful code snippets, e.g. useful cli commands.

## Replace string with `sed`

```
echo $PATH | sed 's/:/\n/g'
```

sed syntax is `sec 's/${replace this string}/${with this string}/g'`

The `g` at the end means everyone. Without it only the first match will be replaced.

