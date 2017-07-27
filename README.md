# Base JRE image
Version openjdk:8u141-jre

#### Versiyonlar ubuntuya göre değiştirildi.
ENV JAVA_VERSION 8u131

ENV JAVA_UBUNTU_VERSION 8u131-b11-2ubuntu1.16.04.2

#### Sertifika ubuntuya göre değiştirildi.
ENV CA_CERTIFICATES_JAVA_VERSION 20160321


## Build

  <pre><code>
  docker build -t mental/jre .
  </code></pre>
  

## Push docker

> Login

``` 
docker login
```
Result
```
Username (coskundeniz1989): coskundeniz1989
Password: 
Login Succeeded
```

> Push

``` 
docker push mental/jre
```
Result

```
c920e43f77ca: Pushed 
d6ef77c14c7b: Pushing [==>                                                ]  6.512MB/136.3MB
171d37ccaf8f: Layer already exists 
2350b4ac2b87: Layer already exists 
5dde57d0859d: Layer already exists 
64c68267c60a: Layer already exists 
26b126eb8632: Layer already exists 
220d34b5f6c9: Layer already exists 
8a5132998025: Layer already exists 
aca233ed29c3: Layer already exists 
e5d2f035d7a4: Layer already exists 
```