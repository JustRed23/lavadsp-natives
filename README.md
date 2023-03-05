# lavadsp-natives
Compiled native files for https://github.com/natanbc/lavadsp

This `original` branch can be used with the existing native loader in lavaplayer.

## Installation
Latest version (replace **@TAG@** with this):
[![](https://jitpack.io/v/JustRed23/lavadsp-natives.svg)](https://jitpack.io/#JustRed23/lavadsp-natives)

Using gradle:
```gradle
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    implementation 'com.github.JustRed23:lavadsp-natives:@TAG@'
}
```

Using maven:
```xml
<repositories>
	<repository>
	    <id>jitpack.io</id>
	    <url>https://jitpack.io</url>
	</repository>
</repositories>

<dependency>
    <groupId>com.github.JustRed23</groupId>
    <artifactId>lavadsp-natives</artifactId>
    <version>@TAG@</version>
</dependency>
```