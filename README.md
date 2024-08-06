# libcgal.a
iOS build for [libcgal](https://www.cgal.org)

## Dependencies

    * xcode
    * brew install git


## Build

    ./build-all.sh release

    ./build.sh build release arm64-apple-ios14.0


## Reference in Swift Module

``` swift

    .binaryTarget(
        name: "libcgal.a",
        url: "https://github.com/Sitelink-Spatial/libcgal.a/releases/download/r3/libcgal.a.xcframework.zip",
        checksum: "83cf15cc035e6f5f873d725d1e8a8d2406b55f330007fe61681f4c9150579b21"
    )

```

## References

    * https://www.cgal.org