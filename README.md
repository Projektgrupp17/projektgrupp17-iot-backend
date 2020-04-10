# projektgrupp17-iot-backend
Collects data from iot devices
Implemented in rust with rocket

![Rust](https://github.com/krummelur/projektgrupp17-iot-backend/workflows/Rust/badge.svg?branch=master&event=push)

## endpoints
* /register/station_id/tracker_id (post)

registers that a specific device has been seen by a transceiver station, both the device and the station must exist.

# build
* switch to nightly "rustup override set nightly"
* cargo run|build|test to run build or test
