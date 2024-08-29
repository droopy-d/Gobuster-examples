Directory scan:</br>
`
$ gobuster dir -u <url> -w <wordlist>
`
</br></br>
Extensions scan:</br>

`
gobuster dir -u [IP_address]:[port] -w /usr/share/wordlists/dirb/common.txt -x jpg,png,jpeg
`
</br></br>
DNS scan:</br>

`
gobuster dns -d mydomain.com -w /usr/share/wordlists/dirb/common.txt
`
</br></br>

Subdomains:</br>
`
gobuster s3 -h
`
