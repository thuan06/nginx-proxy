* Config file for one domain. 
* With each domain, you shoud created a nginx config file.
* This sample for domain: Server0.testdomain.com on Server0
* For other domain you shoud modified some parameter:
  * cp Server0.testdomain.com.conf --> Server1.testdomain.com.conf 
  * sed -i 's/Server0/Server1/' Server1.testdomain.com.conf
  * sed -i 's/192.168.1.10/192.168.1.20/' Server1.testdomain.com.conf
  * Edit location of Letsencryt cert if fase, defaul = /etc/letsencrypt/live/domain_name
 
* Make sure that you have all SSL certificated domain named: Server0.testdomain.com, Server1.testdomain.com, Server3.testdomain.com

