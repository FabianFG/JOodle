# JOodle

####Oodle dll bindings for the jvm
#### Usage
	Oodle.decompress(compressedData : ByteArray, uncompressedLength : Int) returns ByteArray
	Oodle.compress(uncompressedData : ByteArray, compressor : Int, compressionLevel : Int) returns ByteArray
####Dependency
##### Maven
- Add the repository
		<repositories>
			<repository>
				<id>bintray-fungamesleaks-mavenRepo</id>
				<name>bintray</name>
				<url>https://dl.bintray.com/fungamesleaks/mavenRepo</url>
			</repository>
		</repositories>
- Add the dependency
		<dependency>
			<groupId>me.fungames</groupId>
			<artifactId>JOodle</artifactId>
			<version>1.0</version>
		</dependency>
##### Gradle
- Add the repository
		repositories {
    		maven {
        		url  "https://dl.bintray.com/fungamesleaks/mavenRepo"
   				}
		}
- Add the dependency
		implementation 'me.fungames:JOodle:1.0'