# docker-osslsigncode
osslsigncode Dockerfile

Run [osslsigncode](http://sourceforge.net/projects/osslsigncode/) in docker

## Usage:
```
docker run -v `pwd`:/files sporsh/osslsigncode sign -pkcs12 <certfile> -pass <password> -n "<program name>" -i http://yourdomain.com -in /files/original.exe -out /files/signed.exe
```
