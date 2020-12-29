# Network Calculator
This is a simple implementation of a network calculator developed in Python.

## Description
It will take an IP address and network mask and show information about the network like hosts addresses, broadcast address, wildcard mask, etc.

All methods are Class methods, and can be used without instantiating the class itself.

## Installing
The package is available at PyPi. Just run `pip install spts-netcalc`

## Executing program

The class network can be instantiated as below and some methods can be used without instantiation.

`Network(address, mask)`: Class to calculate all parameters of a network given an address and network mask

These are the methods currently available:

`calculate_net_address()`: calculates the network address based on any address and mask given

`calculate_net_broadcast()`: calculates the network broadcast address based on any address and mask given

`calculate_host_addresses()`: returns all addresses of a network given the network address and a mask

`calculate_class()`: returns the class of the network

`calculate_cidr_mask()`: calculates the network mask in CIDR format given a dot-decimal format mask

`calculate_dot_decimal_mask()`: returns the network mask in dot-decimal format given a CIDR mask

`calculate_wildcard_mask()`: returns the wildcard equivalent of the network mask

`is_mask_valid()`: verifies if the given network mask is valid

`is_address_valid()`: verifies if the network address is valid

`convert_to_int()`: converts a network address or mask in an int number

`convert_to_string()`: converts a netwirk address or mask from it to dot-decimal string format 

`split_to_octets()`: split a network address or mask in dot-decimal format in a list of octets in int format

## Help

Use the folowing to obtain more information about the above methods, such as arguments and return types:

```python
import spts_netcalc
help(spts_netcalc.network)
```

## Authors

Santiago Soares <santiagosoares@gmail.com>

## Version History

    0.2
        Minor fixes, not related to funcionality
    0.1
        Initial Release

## License

This project is licensed under the MIT License - see the license.txt file for details
