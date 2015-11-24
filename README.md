#Swagger UI Themes:

Swagger Docs are awesome. Why not make them look better! Below is a collection of themes for [Swagger UI](http://swagger.io/swagger-ui/).
You can find the Swagger UI project on GitHub [here](https://github.com/swagger-api/swagger-ui).

### Flattop
![Flattop Screenshot](https://github.com/ostranme/swagger-ui-themes/blob/master/screenshots/flattop.png)

### Muted
![Muted Screenshot](https://github.com/ostranme/swagger-ui-themes/blob/master/screenshots/muted.png)

### Newspaper
![Newspaper Screenshot](https://github.com/ostranme/swagger-ui-themes/blob/master/screenshots/newspaper.png)

### Outline
![Outline Screenshot](https://github.com/ostranme/swagger-ui-themes/blob/master/screenshots/outline.png)

### Monokai
![Monokai Screenshot](https://github.com/ostranme/swagger-ui-themes/blob/master/screenshots/monokai.png)

###Installation
---
Simply just add one of the above stylesheets in the `themes` folder to the source of swagger-ui theme html page. Make sure to either remove/comment out the link to `screen.css` or load the desired theme after it to override the Swagger UI styles.

###Demo
---
The [Swagger Petstore](http://petstore.swagger.io/#/) was used as the example to showcase different themes. In the demo folder, open the index.html file and add a link to the desired theme you want by adding `<link href='PATH TO THEME' media='screen' rel='stylesheet' type='text/css'/>`. Next, either remove or comment out the `<link href='css/screen.css' media='screen' rel='stylesheet' type='text/css'/>` in the `<head>` tags. Serve up the index.html locally to view theme.

Feel free to open an issue or suggest more themes!

###License
---

The MIT License. Read [LICENSE](LICENSE) for further information.