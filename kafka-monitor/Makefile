TAG ?= latest
PREFIX ?= ljufa/kafka-monitor

build:
	docker build -t $(PREFIX):$(TAG) .

buildnocache:
	docker build --no-cache -t $(PREFIX):$(TAG) .

push: build
	docker push $(PREFIX):$(TAG)

smokerun:
	docker run --rm $(PREFIX):$(TAG)