
![](../image/branding/netplay-logo.gif)

## Getting Started

### Configuring Nickname
- Navigate to **Settings**
- Navigate to **User**
- Select **Username**
- Configure your preferred nickname

![Screenshot](../image/retroarch/netplay/nickname.png)

### Configure Netplay Server

If you are gonna host a game you don't need to scan content or to build databases. The only thing you need to do is to configure your network parameters and "Start Hosting" from the netplay menu. After doing that just load the content you want to netplay and wait for players.

![Screenshot](../image/retroarch/netplay/netplay.jpg)

#### Check your lobby

Once you start hosting you can check to see if your lobby is visible [at lobby.libretro.com](http://lobby.libretro.com/).

!!! tip
    If your router doesn't support UPnP or you can't forward your ports or you are uncertain, enable the **Use Relay Server** option. This routes both sides of the connection through our man-in-the-middle server.

!!! tip
    If you want to run a private game you can setup a **Server Password** to prevent random people from connecting. Alternatively you can disable the **Publicly Announce Netplay** option. The clients will need to enter your IP address or hostname directly.

!!! Warning
    RetroArch doesn't check if you managed to open your ports manually, the lobby server doesn't either so make sure you do that properly or enable the Relay Server or people won't be able to connect to your session. You can use [this tool](http://www.yougetsignal.com/tools/open-ports/), enter your **Netplay TCP Port** once you are hosting and it will tell you if the port is open or not.


### Configure Netplay Clients

You don't need to configure anything to connect to netplay rooms. Browse to the netplay menu, Select **Refresh** and then select the room you want to connect to.

![Screenshot](../image/retroarch/netplay/rooms.png)

You will be asked for a password if one is required, and if you have matching content scanned or in the **Content History** it will connect right away. Otherwise it will tell you to load the core and content manually and it will attempt to connect right away.


#### Video Tutorial

[![Quick Video Demonstration](http://img.youtube.com/vi/Z3CTuTx0nnc/0.jpg)](http://www.youtube.com/watch?v=Z3CTuTx0nnc)