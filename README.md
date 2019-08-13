OpenLyrics Library for Java
===========================

Overview
--------
Generic library with OpenLyrics parser and writer for Java.
Library is used for parsing OpenLyrics XML into a complex Java POJO
and contains utilities to export the result back.

Usage
-----

**Maven**

    <dependency>
      <groupId>com.github.berry120.jopenlyrics</groupId>
      <artifactId>jopenlyrics</artifactId>
      <version>2.0</version>
    </dependency>
    
**Gradle**

    implementation 'com.github.berry120.jopenlyrics:jopenlyrics:2.0'

Limitations
-----------
Export and import still limited.
But if you find something missing, feel free to contribute patches. :-)


Further Direction
-----------------
This library is based on OpenLyrics v 0.8 specifications.
However the plans of 0.9 are not yet clear and OpenLyrics
is tightened to a particular project: OpenLP and thus its
functionality at first place.

Thefore future development may use own dialect, based on OpenLyrics,
although keeping backward compatibility with the current version.

Attribution
-----------
This library was forked from [ISBM's original version](https://github.com/isbm/jopenlyricslib). Various improvements and bugfixes have since been added.

