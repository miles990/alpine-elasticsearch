# alpine-elasticsearch
Elasticsearch docker image of smaller than official version.

## Base Image
- anapsix/alpine-java:jdk8

## Environment
- Alpine Linux 3.4
- Oracle Java 8 JDK
- Elasticsearch 2.3.3

## Run
`
docker run -p 9200:9200 -p 9300:9300 -d miles990/alpine-elasticsearch
`

`
docker run -p 9200:9200 -p 9300:9300 -v $(pwd):/data -d miles990/alpine-elasticsearch
`


## License

[MIT](http://opensource.org/licenses/MIT)