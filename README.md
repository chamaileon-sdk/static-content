# Chamaileon SDK Static files
**Real Time Editor** Image content for Chamaileon SDK partners. 

You can use your own images as the **social element** images and **image element** placeholder image in the **Real Time Editor** or host Chamaileon's package in your own domain.

## Host Chamaileon's images in your domain

Clone this repository and copy its \img folder to your store. 
It is important to keep the \img folder and the images, but you can over write any of them with your own image.

## Add baseUrl to the settings object

During Real Time Editor initialization you can pass down a settings object to the plugin, you can add a baseUrl field. 
As a value add the full Url of the \img forlder. 

For example if your host the \img folder at "https://www.yourdomain.com/.../img" you have to add "https://www.yourdomain.com/.../" as a value. 
Pls don't forget about the closing "/". 
 
