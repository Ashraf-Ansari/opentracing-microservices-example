# opentracing-microservices-example

Example application for [A minimalistic guide to distributed tracing with OpenTracing and Jaeger](https://shekhargulati.com/2019/04/08/a-minimalistic-guide-to-distributed-tracing-with-opentracing-and-jaeger/) post.


1st run jayeger application
docker run -p5775:5775/udp -p6831:6831/udp -p6832:6832/udp -p16686:16686 jaegertracing/all-in-one:latest --log-level=debug


links for this project
https://medium.com/xebia-engineering/jaeger-integration-with-spring-boot-application-3c6ec4a96a6f
https://shekhargulati.com/2019/04/08/a-minimalistic-guide-to-distributed-tracing-with-opentracing-and-jaeger/
