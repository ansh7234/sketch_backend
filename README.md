# sketch_backend
this is simple backend written for uploading sketches that can be used by websites as svg's/images to create a sexy landing page . this is for my brother maintaining frontend @anmol2004 at github .



**   Now you can run that simply  by the docker command :

		docker run -d -p 5000:5000 -e link=http://flyploader.live -v $PWD:/project/ kumarnitesh2000/sketch_backend:1.0.1
**
Now link is the enviroment variable in this after the POST request function will return to the link page .

In command we use volume as well to edit and make changes in the code .


backend is running AT https://sketchapi.me/api

at this link is returning the json content and there is a field of image link so to see that image you can visit :

https://sketchapi.me/static/[IMAGE_LINK]
example :
https://sketchapi.me/default.jpeg


