# ShellyCloud
Public project

Homepage [Shelly Cloud](https://shelly.cloud/) - by Allterco Robotics EOOD, Bulgaria, Sofia  
Homepage [Current Product Catalogue](https://shelly.cloud/documents/catalogues/catalogue.pdf)  

Shelly **Forum** [Deutsch](https://www.shelly-support.eu/forum/)

## API description
Shelly [Common HTTP API](https://shelly-api-docs.shelly.cloud/#common-http-api)

### API example (Initial Configuration)
http://192.168.33.1 (Access Point)

### API examples (Application)  
AF104:  
http://192.168.0.222/shelly    
http://192.168.0.222/status    
http://192.168.0.222/settings   
http://192.168.0.222/ota/check   
http://192.168.0.222/debug/log   
MPS3:  
http://192.168.178.70/status    

#### Shelly 1
http://192.168.0.251/relay/0?turn=on  
http://192.168.0.251/relay/0?turn=off  
http://192.168.0.251/relay/0?turn=toggle  

#### Shelly Plug S
AF104:  
http://192.168.0.222/relay/0?turn=toggle  
MPS3:  
http://192.168.178.65/relay/0?turn=toggle  

#### Shelly Duo
AF104:  
http://192.168.0.136/light/0?turn=toggle  
MPS3:  
http://192.168.178.70/light/0?turn=toggle   
http://192.168.178.70/light/0?turn=on    
http://192.168.178.70/light/0?turn=off    

## Projects

Public [Node-RED flow Shelly](https://github.com/griemide/Node-RED/blob/main/flows/readme.md)  
Private [Shelly](https://github.com/griemide/Shelly)

[]()  
[]()  
[]()  
