# freepbx
VoIP Container With Freepbx

Copying Docker-compose
```
clone https://github.com/otnamrehus/freepbx.git
cd freepbx
```

Build Image
```
docker-compose -p 'freepbx' up --build
```

Browser

- Add Extension
- Add New IP Address  
```
ip_address:2000/admin/config.php
```

Client [Android: PortSIP/Zoiper/3CX-Lite/Linphone]
```
username : <number_extension>
password : <number_extension>
SIP Domain :   IP_Address:5160 
```
