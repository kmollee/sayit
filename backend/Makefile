build:
	# https://stackoverflow.com/questions/34729748/installed-go-binary-not-found-in-path-on-alpine-linux-docker
	GOOS=linux GOARCH=amd64 CGO_ENABLED=0 go build -o app
	docker build -t kmollee/sayit .
	rm -f app
