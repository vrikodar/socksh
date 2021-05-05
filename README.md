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

![Capture](https://github.com/SxNade/socksh/blob/main/extras/running.gif)

# Common options
            -d --> is the display option that displays the discovered proxies on the terminal
            -s --> is the silent does not display the discovered proxies

# Assistance For Proxychains

*socksh can add first 4 discovered poxies to proxychains.conf file allowing you to use them all on the go.!*

*you may also change the number of proxies to add*

                -fl --> file local adds the first 4 discovered proxies to local proxychains.conf file in current directory
                -fg --> file global adds the first 4 discovered proxies to global /etc/proxychains.conf file

                # PLEASE REFER TO THE man.txt FILE PRESENT IN extras FOLDER IN THE REPOSITORY FOR MORE INFO

*the gif below shows the proxies scraped by socksh in action with proxychains*


