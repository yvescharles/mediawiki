https://bertt.wordpress.com/2016/12/01/play-with-docker-in-the-browser/
git clone https://github.com/notmyname/swift-durability-calculator.git
docker run --name docker-nginx -p 80:80 -d -v /root/swift-durability-calculator/:/usr/share/nginx/html nginx
docker run -ti jpetazzo/ngrok http 192.168.0.47:80
