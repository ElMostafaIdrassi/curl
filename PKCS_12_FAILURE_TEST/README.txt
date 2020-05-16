Untar curl_build.tar.gz
	/Library/MyOrg/
Copy content into "/Library"
Run : 
	/Library/MyOrg/bin/curl --cert /ABSOLUTE/PATH/TO/MyCert.p12 --pass pass https://github.com
Result : 
	curl: (58) SSL: Can't find the certificate "/ABSOLUTE/PATH/TO/MyCert.p12" and its private key in the Keychain.