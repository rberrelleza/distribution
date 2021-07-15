dev:
	go run main.go serve /etc/docker/registry/config.yml

debug:
	dlv debug --headless --listen=:2345 --log --api-version=2 -- serve /etc/docker/registry/config.yml