# docker-minecraft-alpine
Lightweight Automated build for Minecraft's Craftbukkit

On an AWS Free Tier:
	- docker run --restart=always -d -p 25565:25565 -u 1001:1001 --memory=880M --memory-swap="5g" -v $PWD/craftbukkit-1.8.8:/data --name mcbukkit mluis/minecraft-alpine
