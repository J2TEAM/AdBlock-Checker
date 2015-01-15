# AdBlock Checker
Detect AdBlock and show a message to users.

## Demo
Works well on both most popular browser :white_check_mark:

![AdBlock Checker](http://i.imgur.com/nY0OOdj.png)

## How to use

### Step 1: CSS

Add before `</head>`:
```html
<link rel="stylesheet" href="adblock-checker.css" />
```

### Step 2: Javascript

Add before `</body>`:

```javascript
<script src="advertisement.js"></script>
<script src="adblock-checker.js"></script>
<script type="text/javascript">
	adb_checker({
		url: 'http://www.afreesms.com/adblock/disabling/', // Link to help users disable AdBlock
		redirect: false, // True to redirect user to the above url
		warning: {
			text: 'Please disable AdBlock!', // Message to the users
			button: 'Help me to disable!'
		}
	});
</script>
```

## Contact

If you have an ideas or want to report a bug, please contact me:

* Email: junookyo@gmail.com
* Blog: http://junookyo.blogspot.com/
* Facebook: https://www.facebook.com/JunoOkyoBlog
* Twitter: https://twitter.com/juno_okyo
