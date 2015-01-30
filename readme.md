TO INSTALL
sudo npm install

TO POST
curl -X POST 0.0.0.0:3000/post --data "title=1&slug=a&text=test1"
can choose a different title and text for the blog

TO EDIT A POST
curl -X  PUT 0.0.0.0:3000/api/articles/:id --data "title=changedto2&slug=b&text=test2"

TO SHOW ALL POSTS
curl -X  GET 0.0.0.0:3000/api/articles

TO DELETE
curl -X DELETE 0.0.0.0:3000/api/articles/:id

Note: change "0.0.0.0:3000" to "http://localhost:3000" if it doesn't work