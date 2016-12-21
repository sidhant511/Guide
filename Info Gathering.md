# Info Gathering
The more info we have, the more likely of success

## Passive Info Gathering
* 1st phase of pentesting
* Consists of using publicly available information

### Target servers/websites

* How well is the website designed?
* How clean is the code?

### Google Search

* All the sites
`site:"example.com"`

* Remove any related to www
`site:"example.com" -site:"www.example.com"`

* Search for Powerpoint files with exact term
`site:"example.com" filetype:ppt "penetation testing"`

### Google Hacking
* Single out specific pages with this in title
`intitle:"VNC viewer for Java"`

* Example - Webcam
`inurl:"/control/userimage.html"`

* Specific host authentication signature - PHP
`inurl:php? intext:CHARACTER_SETS,COLLATIONS intitle:phpmyadmin`

* Searching for compromised machines for known PHP vuln
`intitle:"-N3t" filetype:php undetectable`

### GHDB "Google Hacking Database"
http://www.exploit-db.com/google-dorks/

## Active Info Gathering
