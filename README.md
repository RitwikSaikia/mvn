## MVN repo ##

Maven repository for all build artifacts

```xml
<repositories>
    <repository>
        <id>ritwik-mvn</id>
        <url>http://ritwik.net/mvn/releases/</url>
    </repository>
</repositories>
```


For development snapshots. 
(This is only to verify newly fixed issues, don't use it for long time, as old artifacts are periodically trashed).
```xml
<repositories>
    <repository>
        <id>ritwik-mvn-snapshots</id>
        <url>http://ritwik.net/mvn/snapshots/</url>
    </repository>
</repositories>
```


If you want to browse, the artifacts are stored under [gh-pages](https://github.com/RitwikSaikia/mvn/tree/gh-pages) branch.
