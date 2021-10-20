# tomcat10-alpine-jre12-openj9

Dockerfile for creating an docker image with:
  * Tomcat 10.0.12
  * Alpine Linux 3.10
  * JRE 12.0.2
  * OpenJ9 JVM 0.15.1

## License

The Dockerfile found in this project is licensed under the Apache License 2.0.

## Running

````bash
docker pull nirmata/tomcat10-alpine-jre12-openj9
````

## Extending

````dockerfile
FROM nirmata/tomcat10-alpine-jre12-openj9

   ...

````

The image sets the user to `tomcat`. To operate as `root` switch the user to root before your build instructions, and then back to `tomcat`. 

## References

  * [AdoptOpenJDK](https://github.com/AdoptOpenJDK/openjdk-docker)




