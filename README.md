# Various notes

The easiest way to run Jupyter Lab to edit the notebooks is with Nix
installed. Then you can do

```
$ cachix use jupyterwith
$ nix-shell --command "jupyter lab"
```

It's going to take a while though. I'm not sure that we actually
install anything that is cached by Cachix.
