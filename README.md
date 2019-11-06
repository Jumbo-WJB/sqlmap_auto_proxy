# sqlmap_auto_proxy
 <br>
### vi ips.txt
 <br>
1.1.1.1:1080 <br>
2.2.2.2:9988  <br>
3.3.3.3:1100 <br>
...
 <br>
### python sqlmap_auto_proxy.py
 <br>
### sqlmap -u "http://www.chinabaiker.com/index.php?id=inject" --proxy=http://127.0.0.1:50007
 <br>
enjoy:)
