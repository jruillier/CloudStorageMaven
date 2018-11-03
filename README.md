# CloudStorageMaven
[![GitHub version](https://d25lcipzij17d.cloudfront.net/badge.svg?id=gh&type=6&v=1.5.1&x2=0)](http://badge.fury.io/gh/boennemann%2Fbadges)

This is a fork of [gkatzioura/CloudStorageMaven](https://github.com/gkatzioura/CloudStorageMaven).

The CloudStorageMaven projects aims to provide an easy way to host your java artificats on the cloud without having to set up a maven repository.

Cloud storage options supported by this fork :
* [Google Cloud Storage](https://github.com/jruillier/CloudStorageMaven/tree/master/GoogleStorageWagon)

The goals of this fork are :
* to support the use of google-storage-wagon in ${maven.projectBasedir}/.mvn/extensions.xml.
(required for downloading a "parent" artifact stored on a GS bucket) 
* to support Java 7