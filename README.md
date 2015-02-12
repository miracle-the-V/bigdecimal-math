# bigdecimal-math
This repository is made to make [Richard J. Mathar's](http://www2.mpia-hd.mpg.de/~mathar/)
 "[Java Math.BigDecimal Implementation of Core Mathematical Functions](http://arxiv.org/abs/0908.3030v2)" 
 library available as maven dependency. <br>
I'm not the author, but code is licensed under 
[LGPL v3.0](http://www.gnu.org/copyleft/lesser.html),  so use and modification 
in basically any application is supported/allowed with no further support or any 
sort of warranty attached.<br>
Package is renamed from original org.nevec.rjm to io.github.miraclefoxx.math 
to preserve the possibility of improving the library.

Add the following tags to your pom.xml: <br>
```xml
<repositories>
 <repository>
  <id>BigDecimalMath-mvn-repo</id>
  <url>https://raw.github.com/miraclefoxx/BigDecimalMath/mvn-repo/</url>
  <snapshots>
   <enabled>true</enabled>
   <updatePolicy>always</updatePolicy>
  </snapshots>
 </repository>
</repositories>

<dependency>
 <groupId>io.github.miraclefoxx</groupId>
 <artifactId>bigdecimal-math</artifactId>
 <version>1.0</version>
</dependency>
```
