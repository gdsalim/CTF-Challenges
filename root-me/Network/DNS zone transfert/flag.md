$ dig @212.129.38.224 -p 54011 axfr ch11.challenge01.root-me.org

; <<>> DiG 9.18.30-0ubuntu0.24.04.1-Ubuntu <<>> @212.129.38.224 -p 54011 axfr ch11.challenge01.root-me.org
; (1 server found)
;; global options: +cmd
ch11.challenge01.root-me.org. 604800 IN	SOA	ch11.challenge01.root-me.org. root.ch11.challenge01.root-me.org. 2 604800 86400 2419200 604800
ch11.challenge01.root-me.org. 604800 IN	TXT	"DNS transfer secret key : CBkFRwfNMMtRjHY"
ch11.challenge01.root-me.org. 604800 IN	NS	ch11.challenge01.root-me.org.
ch11.challenge01.root-me.org. 604800 IN	A	127.0.0.1
challenge01.ch11.challenge01.root-me.org. 604800 IN A 192.168.27.101
ch11.challenge01.root-me.org. 604800 IN	SOA	ch11.challenge01.root-me.org. root.ch11.challenge01.root-me.org. 2 604800 86400 2419200 604800
;; Query time: 34 msec
;; SERVER: 212.129.38.224#54011(212.129.38.224) (TCP)
;; WHEN: Mon Jan 27 11:15:15 CET 2025
;; XFR size: 6 records (messages 1, bytes 274)

