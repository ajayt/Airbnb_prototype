# Airbnb

###DIrectory Structure :

```
AirBnb:
	|- routes:		
		|- users: (user specific api)
			|- user.filename.js
			|- user.filename1.js		
		|- host: (host specific api)
			|- host.filename.js
			|- host.filename1.js		
		|-admin: (admin specifc api)
			|- admin.filename.js
			|- admin.filename1.js		
		|-utils: (all utilities like database connectivites, crons etc.)
			|- utils.filename.js
			|- utils.filename1.js
	|- public:      (For stylesheet, templates and scripts, keep the name of the file same. Like home, let's just use prefix and extesion to identify the type)
		|- stylesheet:
				|- style.home.css
				|- style.user.css		
		|- templates:
				|- view.home.html
				|- view.user.html		
		|- scripts:
				|- controller.home.js
				|- controller.user.js		
		|- images:
				|- <images_name>.png/jpg		
		|- libabries:(mostly CDN will be used, incase required)
				|- <library.js>
	|- view:
		|- index.js
		|- user.js
	|- app.js	
	|- package.json
  ```
