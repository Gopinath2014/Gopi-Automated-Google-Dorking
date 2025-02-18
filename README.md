The OSINT project, the main idea of which is to collect all the possible Google dorks search combinations and to find the information about the specific web-site: common admin panels, the widespread file types and path traversal. The 100% automated.

Installation Steps:
```
git clone https://github.com/Gopinath2014/Gopi-Automated-Google-Dorking.git
```
Next
```
cd Gopi-Automated-Google-Dorking
chmod +x GAGD.sh
```
Usage example
```
./GAGD.sh megacorp.one
```

or
```
bash ./GAGD.sh megacorp.one
```

with proxy
```
bash ./GAGD.sh megacorp.one 192.168.1.1 8080
```

This will work beatifully on Kali but an ultimately universal way is through Docker. Just run
```
docker build -t FOO .
```
and then run it with your argument for the URL such as this:
```

docker run -it --rm FOO mysite.com
```

LICENCED BY 
GOPINATH R 
