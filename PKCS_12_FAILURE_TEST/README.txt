Untar curl-current.tar.gz
	/Library/MyOrg/
Copy content into "/Library"
Copy "alice.Exchange.p12" into "/Library/MyOrg/"
Run : 
	/Library/MyOrg/bin/curl --cert /Library/MyOrg/alice.Exchange.p12 --pass pass https://github.com
Result : 
	curl: (58) SSL: Can't find the certificate "/Library/MyOrg/alice.Exchange.p12" and its private key in the Keychain.