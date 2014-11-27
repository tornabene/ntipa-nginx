### To build:

	Spostarsi nella directory e lanciare il comando
    sudo docker build -t tornabene/ntipa-nginx .
    
### To run:
    sudo docker pull tornabene/ntipa-nginx
    
     sudo docker run  --rm  --dns 10.10.130.5  -p 8080:80 -i  -t  tornabene/ntipa-nginx /bin/bash
     sudo docker run  -d  -p 80:80   tornabene/ntipa-nginx
    
