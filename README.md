# What Is A DDos Attack
A Distributed Denial of Service (DDoS) attack is an attempt to make an online service unavailable

### botnet topology
* C&C
* peer to peer

### type of attacks
* volume based attacks
  * saturate bandwidth
  * measured in Bit Per Second (BPS)
  * UDF Flood, ICMP Flood
* protocol attacks
  * consumes actual server resources
  * Measured in Packet per second (PPS)
  * SYN Flood, Ping of Death, Smurf
  * Amplification
  * DNS Amplification, Memcached, LDAP
* application layer attacks
  * the goal of this attacks is to crash the web server
  * Measure in Requests per second (RPS)
  * low and slow attacks, GET/POST Flooads,...
  * SMTP, FTP


### volume based attacks Regulator solution
  * Null Routing
  * Iran Access

### preventionMethods
* self hosted DDos protection
  * Arbor Networks, Huawei, Cisco
  * IPtables, PF,...
* Scrubing Center
  * GRE Tunnels/ BGP Routing
  * L4 Proxy
  * XDP/eBPF
* Cloud Security

* l7 protection
  * set cookie method
  * js method
  * re captcha
  * rate limit

* Cloud Security platform
  * firewall
  * waf
  * DDos protection
  * rate limit







