## Malc0de

Malc0de database is run by a security researcher.

### Malware

An updated database of domains hosting malicious executables.

#### Domain Name
>
* Website
 - `http://malc0de.com/bl/`
* Source
 - `http://malc0de.com/bl/BOOT`
* Data
 - Domain Name
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

##### Sample Output of IntelMQ

```javascript
{
  "time": {
    "observation": "2016-07-07T13:02:52+00:00"
  },
  "classification": {
    "type": "malware"
  },
  "source": {
    "fqdn": "2biking.com"
  },
  "raw": "UFJJTUFSWSAyYmlraW5nLmNvbSBibG9ja2VkZG9tYWluLmhvc3Rz",
  "feed": {
    "accuracy": 100.0,
    "url": "https://malc0de.com/bl/BOOT",
    "name": "Malc0de"
  }
}
```

#### IP Address
>
* Website
 - `http://malc0de.com/bl/`
* Source
 - `https://malc0de.com/bl/IP_Blacklist.txt`
* Data
 - IP Address
* Format
 - Text
* API/Token
 - None
* Status
 - Ok
* Comments
 - No comment

##### Sample Output of IntelMQ

```javascript
{
  "source": {
    "ip": "192.254.235.178"
  },
  "raw": "MTkyLjI1NC4yMzUuMTc4",
  "feed": {
    "accuracy": 100.0,
    "url": "https://malc0de.com/bl/IP_Blacklist.txt",
    "name": "Malc0de"
  },
  "classification": {
    "type": "malware"
  },
  "time": {
    "observation": "2016-07-07T13:11:35+00:00"
  }
}
```

----

There's only Domain information in  in http://malc0de.com/bl/BOOT. It looks like:

    // This file will be automatically updated daily and populated with the last 30 days of malicious domains.
    // It will return 127.0.0.1 for all domains found to be distributing malware
    // Additional information to get this working can be found http://www.malwaredomains.com/wordpress/?page_id=6
    // Last updated 2016-08-28  

    PRIMARY 2biking.com blockeddomain.hosts
    PRIMARY antalyanalburiye.com blockeddomain.hosts
    PRIMARY bellefonte.net blockeddomain.hosts
    PRIMARY fssblangenlois.ac.at blockeddomain.hosts
    PRIMARY gasparini.com.br blockeddomain.hosts

There's only IP information in http://malc0de.com/bl/IP_Blacklist.txt
It looks like:

	// This file will be automatically updated daily and populated with the last 30 days of malicious IP addresses.
	// Last updated 2016-08-29	

	198.57.247.219
	94.73.147.76
	199.30.57.225

But there's more information in http://malc0de.com/database/:

* Domain
* IP
* CC
* ASN
* Autonomous System Name
* Click Md5 for VirusTotal Report