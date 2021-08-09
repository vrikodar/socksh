# socksh

socksh automatically scrapes socks5 proxies from spyones list and can then also add alive proxies to proxychains.conf file in matter of seconds...
    
![Capture](https://github.com/SxNade/socksh/blob/main/socksh.png)


    socksh is multithreaded

# Installing socksh on your Linux system


                $ git clone https://github.com/SxNade/socksh
                $ cd socksh
                $ chmod +x setup
                $ ./setup

![Capture](https://github.com/SxNade/socksh/blob/main/extras/install.gif)

# Running socksh for scraping sock5 proxies

                $ cd socksh
                $ ./socksh -d or -s -options

![Capture](https://github.com/SxNade/socksh/blob/main/extras/socksh.gif)

# Common options
            -d --> is the display option that displays the discovered proxies on the terminal
            -s --> is the silent does not display the discovered proxies

# Assistance For Proxychains

*socksh can add first 2 discovered poxies to proxychains.conf file allowing you to use them all on the go.!*

*you may also change the number of proxies to add*

                -fl --> file local adds the first 2 discovered proxies to local proxychains.conf file in current directory
                -fg --> file global adds the first 2 discovered proxies to global /etc/proxychains.conf file

                # PLEASE REFER TO THE man.txt FILE PRESENT IN extras FOLDER IN THE REPOSITORY FOR MORE INFO

*the gif below shows the proxies scraped by socksh in action with proxychains ....don't bother speed I am running on 10G...just kidding my internet is very slow!*

![Capture](https://github.com/SxNade/socksh/blob/main/extras/proxy.gif)

```
[+] socksh(v3.0) execution started at  03:20:38 

[+] scraping sock5 proxies now......


[+] Initiating multithreaded filtering now..
[!] this might take some time :: sleeping for 2 seconds...

[+] 171 threads have been spawned..!
[+] all threads have been successfully completed...
===================================================================================
Number of alive SOCK5 proxies Found:  20
[+] discovered proxies have been to saved to file sock5_live_proxies_2021-08-09 

--> 103.120.162.153:1080
--> 109.193.195.2:1080
--> 112.218.231.43:1080
--> 134.209.29.120:1080
--> 139.162.78.109:1080
--> 154.16.63.16:1080
--> 159.203.61.169:1080
--> 167.71.5.83:1080
--> 174.75.211.222:4145
--> 176.9.119.170:1080
--> 181.6.24.186:1080
--> 18.179.39.248:1080
--> 184.179.216.130:4145
--> 201.40.122.152:9050
--> 46.4.96.137:1080
--> 46.5.252.70:1080
--> 5.252.161.48:1080
--> 72.221.172.203:4145
--> 85.216.127.190:1080
--> 98.184.33.205:4145
[+] adding first 2 discovered proxies to local proxychains.conf file

[+] proxies have been successfully added...
[+] socksh execution finished at 03:20:52
```
