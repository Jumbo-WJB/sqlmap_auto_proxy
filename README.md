# sqlmap_auto_proxy
### vi ips.txt
1.1.1.1:1080
2.2.2.2:9988
3.3.3.3:1100
...
### python sqlmap_auto_proxy.py

### sqlmap -u "http://www.chinabaiker.com/index.php?id=inject" --proxy=http://127.0.0.1:50007

enjoy:)
