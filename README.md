All C Source files are in the Turner_Web.tgz under cgi-bin folder and in the Xilinx script files under src/linux_software

Start by unzipping the Turner_Web.tgz file using "tar -xvf Turner_web.tgz"
Change directory "cd /home/student/web/"

NOTE: navigate to "cd /home/student/web/cgi-bin/setup_all.sh" and change the IP Address on line 12 to your Host machine IP. This where the UDP packets will be sent

Setup the web page by typing "sudo httpd -p 8080"
press the initialize PL/Radio (This will also start the UDP_Streamer and FIFO_Reader and give a PID)

Play with the radio and demos.
