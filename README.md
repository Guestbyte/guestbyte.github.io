# guestbyte.github.io
https://gohugo.io/hosting-and-deployment/hosting-on-github/

https://daily.dev/posts/making-an-awesome-developer-portfolio

docker-compose run -p 1313:1313 hugo

docker-compose run -p 1313:1313 hugo serve

docker-compose run -p 1313:1313 hugo shell

docker-compose run -p 1313:1313 hugo config

docker-compose run -p 1313:1313 hugo config mounts

docker run -v $(pwd):/src -p 1313:1313 klakegg/hugo:ext-alpine serve