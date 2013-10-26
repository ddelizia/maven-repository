repository
==========

To include artifacts from this repository add the following repository to your pom.xml in your project.

```xml
<repositories>
    <repository>
        <id>ddeliziaSnapshotsRepository</id>
        <url>https://github.com/ddelizia/repository/raw/master/snapshots/</url>
        <snapshots>
            <enabled>true</enabled>
            <updatePolicy>always</updatePolicy>
            <checksumPolicy>fail</checksumPolicy>
        </snapshots>
    </repository>
    <repository>
        <id>ddeliziaReleasesRepository</id>
        <url>https://github.com/ddelizia/repository/raw/master/releases/</url>
    </repository>
</repositories>
```
