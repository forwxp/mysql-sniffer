Overview
========

<p>A small but useful tool to sniffer mysql query</p>
<p>contact: qingqibai@gmail.com</p>

Usage summary
=============

<p> You need to install python-pypcap and python-dpkt to run this tool</p>
<p>you may:</p>
    + apt-get install python-pypcap
    + apt-get install python-dpkt
<p>or:</p>
    + pip install python-pypcap
    + pip install python-dpkt

<p> How to use mysql-sniffer to sniffer query:: </P>
<p>You can get help with ./mysql-sniffer -h or ./mysql-sniffer --help</p>
    + ./mysql -ieth1 -p3306 -r0.2
    + -i or --interface: the interface you want to siniffer
    + -p or --port: the mysql port you use
    + -f or --filter: filter, defalut None, would use "dst you host and tcp dst port you port 
    + -r or --radio: filter radio, from 0 to 1, default 1 means sniffer all query
    + -o or --output-file: output file, if set it will print the query to this file instead of stdout, defult None.
