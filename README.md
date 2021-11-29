# Macpyoui
A tool to find the vendor of a MAC address.

View the write up of this tool on [dev.to](https://dev.to/applericky/mac-address-lookup-using-python-and-an-api--59ba)


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
~ ❯ python3 macpy.py                                                                                                                                   
Please enter the MAC address:
No MAC address entered.
```

#### Todo
- Allow to be installed as a  CLI app and have a uodate tool. 
- Be available to install with Pip and Brew.  
