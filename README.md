# Chamaileon SDK Static files
**Real Time Editor** Image content for Chamaileon SDK partners. 

You can use your own icon package as **social element** images, change the placeholder of the **image element** or host Chamaileon's package on your own domain.

## Host Chamaileon's images in your domain

Clone this repository and copy its \img folder to your domain. 
It is important to keep the \img folder and the file structure, but you can over write any of them with your own image.

## Add baseUrl to the settings object

During Real Time Editor initialization you can pass down a settings object to the plugin, and you can add a "staticAssetsBaseUrl" field.

As a value add the full Url of the \img forlder.

```
chamaileonPlugins.editEmail({
	document: {},
	settings: {
		buttons: { ... },
		elements: { ... },
		blockLibraries: [ ... ],
		addons: { ... },
		staticAssetsBaseUrl: "https://www.yourdomain.com/.../",
	},
	hooks: { ... }
})
```

For example if your host the \img folder at "https://www.yourdomain.com/.../img" you have to add "https://www.yourdomain.com/.../" as a value.

Pls don't forget about the closing "/". 
 
