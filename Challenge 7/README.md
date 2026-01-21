## challenge discription

to analyse PCAP file to get password 

## solution and explanation

used wireshark to open PCAP file

this one uses http instead of https

now filter by http

While reviewing the HTTP traffic, we observe:

POST /login HTTP/1.1
Content-Type: application/x-www-form-urlencoded

after streaming that packet we get username=isitadmin&password=iamtheadmin