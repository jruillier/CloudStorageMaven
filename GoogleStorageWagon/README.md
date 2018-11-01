# GoogleStorageWagon

The GoogleStorageWagon project enables you to download/upload your artifacts to a google cloud storage bucket.

Downloading the "parent" artifact is also supported. 

${maven.projectBasedir}/.mvn/extensions.xml :
```
<extensions xmlns="http://maven.apache.org/EXTENSIONS/1.0.0" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
  xsi:schemaLocation="http://maven.apache.org/EXTENSIONS/1.0.0 http://maven.apache.org/xsd/core-extensions-1.0.0.xsd">
    <extension>
        <groupId>eu.aronnax.maven.cloud</groupId>
        <artifactId>google-storage-noshade-wagon</artifactId>
        <version>1.5</version>
    </extension>
</extensions>
```


Full guide on https://egkatzioura.com/2018/04/09/host-your-maven-artifacts-using-google-cloud-storage/
