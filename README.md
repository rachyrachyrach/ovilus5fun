Ovilus5 fun
=================
Want to see how the Ovilus5 works? There are different versions of the Ovilus.  Some do not have wifi built in. 

March 3, 2022: This is a work in progress.  Not complete. 

May 26: 2024: Check out my repo [Obivous](https://github.com/rachyrachyrach/obvious) to set up your own open source Ovilus with the ENTIRE dictionary! 

 

[OvilusV Product Guide](https://www.digitaldowsing.com/product-guides/ovilus-5/setup/) 

![Setup](/docs/images/curl.jpg)



## What You Need

![Raspberry Pi](/docs/images/raspberrypi.jpg)

Raspberry Pi can be optional. I used this to connect via wifi.

1. Find the ip address to your Ovilus 5. 

2. Use nmap to see what ports are open.  Port 80 for http is open.

``` 
nmap -p 80,22,443  http://ovilous5-ipaddress
```

3. Use curl to check it out. It displays the html that is stored on the Ovilus 5.

```
curl http://ovilous5-ipaddress
```

4. Now for the fun!  Open a web browswer to access your Ovilus 5. Enter the ip address plus the r.htm?m=1  Now try different numbers behind the `=`  You'll get some weird reactions of the Ovilus 5 screen.  For example this Ovilus 5 does not have bluetooth but will show bluetooth icons.
![browser](/docs/images/IMG_0324.jpg)

```
http://ovilus5-ipaddress/r.htm?m=1
```

![Results](/docs/images/IMG_0323.jpg)

