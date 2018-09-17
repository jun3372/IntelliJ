# IntelliJ 代理

## Use:

	docker pull jun3/IntelliJ

	docker run -d -p 8888:8888 jun3/IntelliJ

	docker run -d -p 9999:8888 -e "r=http://blog.lanyus.com" -e "l=0.0.0.0:8888" jun3/IntelliJ
