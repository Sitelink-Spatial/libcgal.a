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
        url: "https://github.com/Sitelink-Spatial/libcgal.a/releases/download/r1/libcgal.a.xcframework.zip",
        checksum: "82a1219fd84ff08ffa884da52e6026d58a5dfaa883a21f3abcb3bf0e58b5629b"
    )

```

## References

    * https://www.cgal.org