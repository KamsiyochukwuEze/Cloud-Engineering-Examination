# Cloud-Engineering-Examination
Cloud Engineering Second Semester Examination Project


1. :white_check_mark: Created an Ubuntu 20.04 LTS AWS EC2 server. 

2. :package:Installed nginx on the EC2 server and made sure it was running. 

    ```bash   
    sudo apt update   
    sudo apt install nginx
    systemctl staatus nginx  
    ```
3. :sparkles: Created a Dyamic Landing Page : The Future of TechStack; a social media plaform where developers and designers
can connect and collaborate on projects.
   ``` bash
   sudo mkdir -p /var/www/index
   sudo nano /var/www/index/index.html
   ```
   <img src "">

5. :art: Added a stylesheet (style.css)
   ```bash
      sudo nano /var/www/index/style.css
   ``` 
6. :unlock: Allowed traffic from HTTP(Port 80) and HTTPS(Port 443) in Security groups    
   :globe_with_meridians: Public IP : http://13.42.32.193/
