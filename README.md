# Countcode
### Simple bash script to count code

```
countcode [--files --lines --chars] -p [path] -d [number] -t "[type] [type]" -v -h
    -p [path] - path to the directory
    -d [number] - depth of the tree
    -t "[type] [type]" - the types of files to consider
    -v - verbose output
    -h - help
```

### Example
```
countcode --files -t "cpp hpp"
```

This call will show the number of files with "cpp" and "hpp" extensions in the current directory.
