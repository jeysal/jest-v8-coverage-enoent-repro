Repro:
Link the Jest v8 coverage branch into this folder.
`yarn jest --v8-coverage` results in

```
ENOENT: no such file or directory, open '/private/var/folders/nh/_6t8lz3913q6z9346w579mj00000gp/T/jest_dy/jest-transform-cache-21e4d813dbc8331364de90d0bbe9fde2-ee2f6998f80ad1ca60bb674d9b0eef67/8f/x_8f0ecc0acaaccd558f2dec5ac223b0d0.map'
```

while regular `--coverage` works.
