# Macpyoui
A tool to find the vendor of a MAC address.

Write up of tool on dev.to


# Prerequisites
* Python 3 - [Click here for website](https://www.python.org)
* Requests - [Click here for repo](https://github.com/psf/requests)



# How to
To run the tool, save the macpy.py file to your device and run it with Python.


```
~ ❯ python3 macpy.py                                                                                                                                  
Please enter the MAC address:
```

# Successful search
```
~ ❯ python3 macpy.py                                                                                                                                   
Please enter the MAC address: F4BD9E
Cisco Systems, Inc
```
# Unsuccessful Search
```
~ ❯ python3 macpy.py
Please enter the MAC address:
MAC address not found.
```

# Missing entry
```
~ ❯ macpy.py                                                                                                                                   
Please enter the MAC address:
No MAC address entered
