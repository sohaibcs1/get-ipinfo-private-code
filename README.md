This library get some useful information from IP address such as Country, Region, City, GPS ,ZIP and ISP. 

## Usage
- Make sure you have Python installed in your system
- run a command in CMD

 ```
 pip install get-ipinfo
 ```
You can get the details by entring the ip
## Example
 ```
# test.py
from get_ipinfo import ip_details

print(ip_details("192.158.11.38"))

  ```
## Run Script

 ```
python test.py
  ```

## Note
- Tested on Python 3.9
- You can search any public ip such as ipv4/ipv6.
- Internet Connection needed otherwise return Error Message
