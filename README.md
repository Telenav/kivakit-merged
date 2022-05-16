[//]: # (start-user-text)



[//]: # (end-user-text)

# kivakit-merged &nbsp;&nbsp; <img src="https://www.kivakit.org/images/convert-32.png" srcset="https://www.kivakit.org/images/convert-32-2x.png 2x"/>

This module contains JAR files that have been merged to eliminate split packages

<img src="https://www.kivakit.org/images/horizontal-line-512.png" srcset="https://www.kivakit.org/images/horizontal-line-512-2x.png 2x"/>

[//]: # (start-user-text)

### Releasing to Maven Central

It should rarely be necessary to deploy the projects in this repository
to Maven Central, but when it becomes necessary to push a change, the
following command will build the projects and copy the result to a 
staging repository on OSSRH:

```
mvn -p release clean deploy
```

> *You must have the PGP key to sign the release or it will be rejected.*  
> 
> Contact Jonathan Locke (jon@thanlocke.com, jonathanl@telenav.com) 
> for the PGP key.

The OSSRH staging repository is at:

```
https://s01.oss.sonatype.org/
```

> Contact Jonathan Locke (jon@thanlocke.com, jonathanl@telenav.com) 
> for the username and password.

[//]: # (end-user-text)

### Projects <a name = "projects"></a> &nbsp; <img src="https://www.kivakit.org/images/gears-32.png" srcset="https://www.kivakit.org/images/gears-32-2x.png 2x"/>

[**kivakit-merged-grpc**](grpc/README.md)  
[**kivakit-merged-prometheus**](prometheus/README.md)  
[**kivakit-merged-protostuff**](protostuff/README.md)  
[**kivakit-merged-zookeeper**](zookeeper/README.md)  

<img src="https://www.kivakit.org/images/horizontal-line-128.png" srcset="https://www.kivakit.org/images/horizontal-line-128-2x.png 2x"/>

### Javadoc Coverage <a name = "javadoc-coverage"></a> &nbsp; <img src="https://www.kivakit.org/images/bargraph-32.png" srcset="https://www.kivakit.org/images/bargraph-32-2x.png 2x"/>

&nbsp; <img src="https://www.kivakit.org/images/meter-50-96.png" srcset="https://www.kivakit.org/images/meter-50-96-2x.png 2x"/>
 &nbsp; &nbsp; [**kivakit-merged-grpc**](grpc/README.md)  
&nbsp; <img src="https://www.kivakit.org/images/meter-50-96.png" srcset="https://www.kivakit.org/images/meter-50-96-2x.png 2x"/>
 &nbsp; &nbsp; [**kivakit-merged-prometheus**](prometheus/README.md)  
&nbsp; <img src="https://www.kivakit.org/images/meter-50-96.png" srcset="https://www.kivakit.org/images/meter-50-96-2x.png 2x"/>
 &nbsp; &nbsp; [**kivakit-merged-protostuff**](protostuff/README.md)  
&nbsp; <img src="https://www.kivakit.org/images/meter-50-96.png" srcset="https://www.kivakit.org/images/meter-50-96-2x.png 2x"/>
 &nbsp; &nbsp; [**kivakit-merged-zookeeper**](zookeeper/README.md)

[//]: # (start-user-text)



[//]: # (end-user-text)

<img src="https://www.kivakit.org/images/horizontal-line-512.png" srcset="https://www.kivakit.org/images/horizontal-line-512-2x.png 2x"/>

<sub>Copyright &#169; 2011-2021 [Telenav](https://telenav.com), Inc. Distributed under [Apache License, Version 2.0](LICENSE)</sub>  
<sub>This documentation was generated by [Lexakai](https://www.lexakai.org). UML diagrams courtesy of [PlantUML](https://plantuml.com).</sub>
