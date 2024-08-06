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
        url: "https://github.com/Sitelink-Spatial/libcgal.a/releases/download/r2/libcgal.a.xcframework.zip",
        checksum: "04673aea5ef9d0f8f802d82824d61361dbf43502d1437c5dac4943059be04c6d"
    )

```

## References

    * https://www.cgal.org