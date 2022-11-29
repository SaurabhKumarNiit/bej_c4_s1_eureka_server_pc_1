FROM openjdk
WORKDIR usr/lib

ENV MONGO_DATABASE="product_service"
ENV MONGO_URL="mongodb://localhost:27017/product_service"

ADD ./target/UserProductService-0.0.1-SNAPSHOT.jar /usr/lib/UserProductService-0.0.1-SNAPSHOT.jar

ENTRYPOINT ["java","-jar","UserProductService-0.0.1-SNAPSHOT.jar"]