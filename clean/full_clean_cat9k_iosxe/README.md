## pyATS Clean for IOSXE CAT9K

This folder contains the following sample files:

- clean.yaml file for IOSXE CAT9K platform
- testbed.yaml file for IOSXE CAT9K platform

These files can be used as a template to execute a full end-to-end clean on an
IOSXE CAT9K device. It performs the following steps in order:

- connects to IOSXE CAT9K device
- (Optional) pings execution servers to verify connectivity
- (Optional) copies necessary images to intermediate server
- copies images to device
- changes boot variables
- executes 'write erase'
- reload device
- apply base configuration after reload
- verifies the running image matches what was specified

Please substitute your device IP addresses, credentials and image directories in
the templates provided before use.