All C Source files are in the Turner_Web.tgz under cgi-bin folder and in the Xilinx script files under src/linux_software

Start by unzipping the Turner_Web.tgz file using "tar -xvf Turner_web.tgz"

NOTE: navigate to "cd /home/student/web/cgi-bin/setup_all.sh" and change the IP Address on line 12 to your Host machine IP. This where the UDP packets will be sent

Change directory "cd /home/student/web/"

Setup the web page by typing "sudo httpd -p 8080".

Open a web page browser and type the FPGA's IP in the Address bar followed by :8080 (type ifconfig in the linux terminal to retrieve this information). 

EX: 192.168.1.47:8080

Press the initialize PL/Radio (This will also start the UDP_Streamer and FIFO_Reader and give a PID)

Play with the radio and demos.
