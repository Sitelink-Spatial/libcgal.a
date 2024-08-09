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
        url: "https://github.com/Sitelink-Spatial/libcgal.a/releases/download/r4/libcgal.a.xcframework.zip",
        checksum: "e06db8be640592df7f3363bb807e7b35f8bfddd3e282027ff7968d7761eb61b0"
    )

```

## References

    * https://www.cgal.org
