    
### Part 1 – EC2 Setup

[![Screenshot-2025-10-17-165754.png](https://i.postimg.cc/NG8961Q2/Screenshot-2025-10-17-165754.png)](https://postimg.cc/0rQyxKM9)

##  Part 2 – File Transfer

* Download any image file (e.g., machine. .png , .jpg ) from the internet onto your local
* Copy the downloaded image from your local machine to the Amazon Linux EC2 instance
 [![Screenshot-2025-10-17-170106.png](https://i.postimg.cc/qMSTg5WY/Screenshot-2025-10-17-170106.png)](https://postimg.cc/KRPVHJGr)

* From the Amazon Linux EC2 instance, transfer the same image to the Ubuntu EC2 instance.


*  Connect to the Ubuntu EC2 instance and verify that the image has been successfully transferred. 

[![Screenshot-2025-10-17-171222.png](https://i.postimg.cc/x16FcJkN/Screenshot-2025-10-17-171222.png)](https://postimg.cc/RWnTY0Lv)


##  Part 3 – Directory Structure (Ubuntu Instance)

[![Screenshot-2025-10-17-171446.png](https://i.postimg.cc/y8GtL3Vz/Screenshot-2025-10-17-171446.png)](https://postimg.cc/68dM332H)

##  Part 4 – Web Server on Ubuntu

*  Install the Apache HTTP Server on the Ubuntu instance 

[![Screenshot-2025-10-17-171724.png](https://i.postimg.cc/Gp1J3bKT/Screenshot-2025-10-17-171724.png)](https://postimg.cc/dh4T4PzJ)

* Copy the EC2 image file into the default Apache web directory ( /var/www/html/ ). 

[![Screenshot-2025-10-17-171938.png](https://i.postimg.cc/RC8tVMCk/Screenshot-2025-10-17-171938.png)](https://postimg.cc/pyfrsMFC)

*  Rename the image file to: 
[![Screenshot-2025-10-17-172201.png](https://i.postimg.cc/5jdj526f/Screenshot-2025-10-17-172201.png)](https://postimg.cc/fSCwDZcP)

* Verify the setup by accessing the image from your browser using the public IP of the Ubuntu instance:
 http:///ec2.png

 [![Screenshot-2025-10-17-173255.png](https://i.postimg.cc/mgVC47P3/Screenshot-2025-10-17-173255.png)](https://postimg.cc/DSJ8dJdm)

##  Part 5 – Web Server on Amazon Linux

 1. Install the Nginx server on the Amazon Linux instance.

 [![Screenshot-2025-10-17-173638.png](https://i.postimg.cc/VNCfg8PX/Screenshot-2025-10-17-173638.png)](https://postimg.cc/Y4tB2T9S)

 [![Screenshot-2025-10-17-173734.png](https://i.postimg.cc/zBNrkHjB/Screenshot-2025-10-17-173734.png)](https://postimg.cc/sBTqjXbd)

 2. Deploy a simple HTML or application page on the Nginx server.
 3. Configure Nginx to serve the application on port 81.
 4. Open your browser and access the application using the instanceʼs public IP and port 81 http://:81

 [![Screenshot-2025-10-17-173945.png](https://i.postimg.cc/0QnLdWjj/Screenshot-2025-10-17-173945.png)](https://postimg.cc/njsRn1vf)

 [![Screenshot-2025-10-17-180438.png](https://i.postimg.cc/85Z0r7Xh/Screenshot-2025-10-17-180438.png)](https://postimg.cc/BL1grn06)

 [![Screenshot-2025-10-17-180717.png](https://i.postimg.cc/5t3PZHJc/Screenshot-2025-10-17-180717.png)](https://postimg.cc/jWDQfSCv)

 



