SHELL := /usr/bin/env bash

start:
	docker-compose up

clean:
	docker-compose down --remove-orphans -v

deploy:
	surge -d apereovr.surge.sh