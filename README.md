docker build -t ghcr.io/theezr/atmoz-sftp2 .

docker push ghcr.io/theezr/atmoz-sftp2

docker buildx build --platform linux/amd64,linux/arm64,linux/arm/v7 -t ghcr.io/theezr/atmoz-sftp2:latest --push .