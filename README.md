create one node directory and then create the files inside it Dockerfile,index.js and package.json
docker build -t custom_node_img .
docker run -d --name node_container -p3000:3000 custom_node_image
Visit http://localhost:3000/ in your browser.
