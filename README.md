
notam-decoder
=======

notam-decoder is JavaScript library for parsing and decoding NOTAMs (Notices to Airmen).

Most code was written based on a interpretation of documentation available from 
[ICAO](https://www.icao.int)'s [Aeronautical Information Services Manual]((https://www.icao.int/NACC/Documents/Meetings/2014/ECARAIM/REF09-Doc8126.pdf)) and [EUROCONTROL](https://www.eurocontrol.int)'s 
[Guidelines Operating Procedures for AIS Dynamic Data (OPADD)](https://www.eurocontrol.int/sites/default/files/publication/files/OPADD_Ed4.0_v01.00.pdf)


You can read about notice to airmen in the [NOTAM article on Wikipedia](https://en.wikipedia.org/wiki/NOTAM).


## Usage example

```javascript
// get decoded notam as json Object
var notam = notamDecoder.decode(input);
```


## Run the example

Install http-server
```bash
npm install http-server -g
```

Now you can run the demo

```bash
$ http-server
Starting up http-server, serving ./

http-server version: 14.0.0

http-server settings: 
CORS: disabled
Cache: 3600 seconds
Connection Timeout: 120 seconds
Directory Listings: visible
AutoIndex: visible
Serve GZIP Files: false
Serve Brotli Files: false
Default File Extension: none

Available on:
  http://127.0.0.1:8080
  http://192.168.1.36:8080
Hit CTRL-C to stop the server

