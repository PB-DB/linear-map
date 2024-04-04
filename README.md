![Rust CI](https://github.com/contain-rs/linear-map/workflows/Rust/badge.svg?branch=master) [![crates.io](https://img.shields.io/crates/v/linear-map.svg)](https://crates.io/crates/linear-map) [![](https://docs.rs/linear-map/badge.svg)](https://docs.rs/linear-map)

The project's official page is in maintenance mode due to insufficient resources.

This is my local fork in development; it adds ergonomic features which ease use.

A map implemented by searching linearly in a vector.

It adds:

1. `as_slice` functions, for viewing the container.
2. `into_inner`, for extracting the vector.

### Future work

1. Add `FromIterator` for ease of use.
2. Add set operations - union, difference, symmetric difference.
