https://github.com/Dreamacro/clash/releases

step 1: install clash
gunzip clash-linux-amd64-v1.11.8.gz
mv clash-linux-amd64-v1.11.8 clash
mkdir Clash
mv clash ./Clash

step 2: get config.yaml
cd Clash
wget -O config.yaml  [subscribe link]
wget -O Country.mmdb https://www.sub-speeder.com/client-download/Country.mmdb

step 3: start clash
./clash -d .

step 4: Enable system proxy
HTTP  127.0.0.1:7890
HTTPS 127.0.0.1:7890
Socks 127.0.0.1:7891

Clash Dashboard:
http://clash.razord.top/
Host: 127.0.0.1  
Port: 9090
