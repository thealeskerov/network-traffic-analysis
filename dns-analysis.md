# DNS Analysis

## Objective

To analyze DNS traffic using Wireshark and understand how domain names are resolved into IP addresses.

## Method

Wireshark filter used:
dns

## Observations

* DNS queries were sent from the client to the DNS server
* DNS responses contained IP addresses of requested domains
* Communication used UDP port 53

## Example

Domain: google.com
Resolved IP: 142.251.x.x

## Conclusion

DNS successfully resolves domain names to IP addresses.
If DNS fails, websites cannot be accessed using domain names.
