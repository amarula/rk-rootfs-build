.PHONY: all

all:
	docker build --network=host -t rk-rootfs-build --build-arg UID=$(shell id -u) --build-arg GID=$(shell id -g) .
