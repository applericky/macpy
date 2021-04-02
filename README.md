# Macpyoui
A tool to find the vendor of a MAC address.

# Prerequisites
* Python 3 - [Click here for website](https://www.python.org)
* Requests - [Click here for repo](https://github.com/psf/requests)

# Install
To install the tool you will need to download it.
cd into directory where the setup.py is. 
run pip3 install .

# How to

```
~ ❯ macpy                                                                                                                                   
Please enter the MAC address:
```

# Successful search
```
~ ❯ macpy                                                                                                                                   
Please enter the MAC address: F4BD9E
Cisco Systems, Inc
```
# Unsuccessful Search
```
~ ❯ macpy
Please enter the MAC address:
MAC address not found.
```

# Missing entry
```
~ ❯ macpy                                                                                                                                   
Please enter the MAC address:
No MAC address entered
