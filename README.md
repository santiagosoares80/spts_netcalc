# Network Calculator
This is a simple implementation of a network calculator implemented in Python.

## Description
It will take an IP address and network mask and show information about the network like hosts addresses, broadcast address, wildcard mask, etc.

All methods are Class methods, and can be used without instantiating the class itself.

## Installing
The package is available at PyPi. Just run `pip install spts-netcalc`

## Executing program

`calculate_net_address()`: calculates the network address based on any address and mask given
`calculate_net_broadcast()`: calculates the network broadcast address based on any address and mask given
`calculate_host_addresses()`: returns all addresses of a network given the network address and a mask
`calculate_class()`: returns the class of the network
`calculate_cidr_mask()`: calculates the network mask in CIDR format given a dot-decimal format mask
`calculate_dot_decimal_mask()`: returns the network mask in dot-decimal format given a CIDR mask

## Authors

Santiago Soares <santiagosoares@gmail.com>

## Version History

    0.2
        Various bug fixes and optimizations
        See commit change or See release history
    0.1
        Initial Release
