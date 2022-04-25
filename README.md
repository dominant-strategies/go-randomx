# go-randomx
Go bindings for librandomx.

## Build
Run the build script to download and compile librandomx.
```
./build.sh
```
The module should now build normally
```
go build
```

# Usage
You can import this module as usual, with:
```
import("github.com/spruce-solutions/go-randomx")
```

See `TestAllocDataset()` in `randomx_test.go` for an example of how to setup a RandomX vm and compute a hash.