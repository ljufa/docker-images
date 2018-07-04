TAG ?= latest
PREFIX ?= ljufa/kafka-manager

build:
	docker build --no-cache -t $(PREFIX):$(TAG) .

push: build
	docker push $(PREFIX):$(TAG)

smokerun:
	docker run --rm $(PREFIX):$(TAG)