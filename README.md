# APR-VolumeRenderer

Viewer app that utilize [jogl-minimal](https://github.com/tpietzsch/jogl-minimal.git) and [LibAPR-java-wrapper](https://github.com/krzysg/LibAPR-java-wrapper) to show Adaptive Particle Representation (APR) files. Thanks to reconstruction 'on the fly' it allows to open bigger files that memory available on the machine.

## How to download and build
* clone repository
```
git clone --recurse https://github.com/krzysg/APR-VolumeRenderer.git
```
* build java app
```
cd APR-VolumeRenderer
mvn pakcage -Dmaven.test.skip=true -Dmaven.javadoc.skip=true
```
* run app
```
./run.sh <your APR file>
```

## Output
<img src="./doc/movieSmallNormalized.gif?raw=true">

![skull and head images](doc/example.png/?raw=true)


## Contact us

If anything is not working as you think it should, or would like it to, please get in touch with us!!!


Java 8 required (does not workt with 1.9 or 1.10)


[![Join the chat at https://gitter.im/LibAPR](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/LibAPR/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
