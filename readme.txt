#!/bin/sh

docker run --rm -it -v "$PWD"/server.properties:/opt/kafka/config/server.properties -p 9092:9092 chenq/kafka
