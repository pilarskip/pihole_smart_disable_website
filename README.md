# pihole_smart_disable
Quick disable or enable Pihole from any device

Condition:
Pihole is your DNS Server

Steps: 
1. go to your pihole admin page -> Settings -> API/ Web Interface - Show API token
2. copy and paste it to the index.html -> head -> script -> token
3. create a Local DNS Record
    admin page -> Local DNS -> DNS Records 
                  Domain:    ad.block.off	
                  IP Adress: <"Pihole-IP"> e.g. 192.168.X.X
    *this is necessary for mobile devices*
4. upload the index.html to /var/www/html/ (or your pihole webbrowsers root)

Simple buttons for computers and mobiles

![grafik](https://user-images.githubusercontent.com/10209780/118378495-93a9b900-b5d4-11eb-8e21-8404b54c23e9.png)


Android Browser Shortcut, feels like an app
![grafik](https://user-images.githubusercontent.com/10209780/118378553-f307c900-b5d4-11eb-85c7-a351a42ec628.png)

