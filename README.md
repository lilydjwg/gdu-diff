Use [gdu](https://github.com/dundee/gdu) to diff and compare directory usages.

## Usage

Run:

```sh
gdu-diffdir /directory/a /directory/b
```

Or you can do steps manually (and optionally save intermediate results.

Export two scan results:

```sh
gdu -o old.gdu /some/directory
gdu -o new.gdu /some/directory
```

Generate diff:
```sh
gdu-diff old.gdu new.gdu > diff.gdu
```

Load and view the diff:
```sh
gdu -f diff.gdu
```
