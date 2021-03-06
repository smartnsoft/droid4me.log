# droid4me.log
Extension of the droid4me framework which contains logger implementation

Available implementations :

* logEntries
* logmatic
* log4j

**Note :** a default Android logger implementation is available into the droid4me framework.

## Usage

### From JCenter

Library releases are available on Jcenter

**Gradle**

```groovy
compile 'com.smartnsoft:log4j:1.1'
compile 'com.smartnsoft:logentries:4.4.1.3'
compile 'com.smartnsoft:logmatic:0.1.1'
```

**Maven**

```xml
<dependency>
  <groupId>com.smartnsoft</groupId>
  <artifactId>log4j</artifactId>
  <version>1.1</version>
  <type>aar</type>
</dependency>
<dependency>
  <groupId>com.smartnsoft</groupId>
  <artifactId>logentries</artifactId>
  <version>4.4.1.3</version>
  <type>aar</type>
</dependency>
<dependency>
  <groupId>com.smartnsoft</groupId>
  <artifactId>logmatic</artifactId>
  <version>0.1.1</version>
  <type>aar</type>
</dependency>
```
### As Library Project

Check out this repository and add it as a library project.

Import the project into your favorite IDE and add `android.library.reference.1=/path/to/droid4me.log/the_choosen_module` to your `project.properties`.

### Generate an aar file

Library releases are not available on Maven Central or JCenter but you can generate an aar file by your owned :

```console
gradle clean choosen_module:assembleRelease
```

or

```console
gradle -b choosen_module/build.gradle clean assembleRelease
```

## Author

The Android Team @Smart&Soft, software agency http://www.smartnsoft.com

## License

droid4me.log is available under the MIT license. See the LICENSE file for more info.
