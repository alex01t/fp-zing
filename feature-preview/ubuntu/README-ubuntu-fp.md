(README-ubuntu-fp) What is Zing? ![Zulu Duke in a Box][1]
======================================

Azul Zing is a runtime platform that uses the Zing Virtual Machine to run Java™ technology-based applications for Linux operating systems. The Zing Virtual Machine (ZVM) allows existing Java applications to elastically scale to dozens of CPU cores and hundreds of gigabytes of memory, meaning resources can also scale up and down based on real-time demands, and without garbage collection pauses present in other Java runtimes.

Azul Zing is compliant with the Java SE standard. 

Zing is built, tested, supported, and delivered by [Azul Systems][2].

Check out [Zing Overview][3] for more information.

Azul provides access to feature previews of Zing® in order to collect early feedback and enable testing of various applications in development environments. The Zing preview package is updated on a weekly basis and is an in-development feature preview version that might be unstable or not performing. Azul undertakes reasonable effort to ensure acceptable quality of the bits. Zing preview builds are not supported and must not be used in production.

At any time you can post your questions at the [Zing Community Forum][8].


Centos, Debian, and Ubuntu Docker images of Zing are available in the following repositories:

  * [azulfeaturepreview/zing-fp-centos][5]
  * [azulfeaturepreview/zing-fp-debian][6]
  * [azulfeaturepreview/zing-fp][7]

Tags and `Dockerfile` links
===========================

Most Recent
-----------

The Zing azulfeaturepreview/zing-fp repository provides various Ubuntu Docker image tags. The most recent Zing versions of OpenJDK 11 and 8 are listed below:

 * [ `11` (*Dockerfile*)][84]

 * [ `8` (*Dockerfile*)][53]


Usage
=====

This Zing repository supports numerous versions of OpenJDK-based Java SE JDKs. Versions 11 and 8 of Zing are compliant with Java SE 11 and 8 respectively.

To run a container of your choice, use commands below as an example.

For a Zing 11 container, enter:

    docker run -it --rm azulfeaturepreview/zing-fp:11 /opt/zing/zing-jdk11-fp/bin/java -version

For a Zing 8 container, enter:

    docker run -it --rm azulfeaturepreview/zing-fp:8 /opt/zing/zing-jdk8-fp/bin/java -version


  [1]: https://www.azul.com/files/ZuluDocker60.gif
  [2]: http://www.azul.com/zing
  [3]: https://www.azul.com/products/zing/
  [5]: https://hub.docker.com/r/azulfeaturepreview/zing-fp-centos
  [6]: https://hub.docker.com/r/azulfeaturepreview/zing-fp-debian
  [7]: https://hub.docker.com/r/azulfeaturepreview/zing-fp
  [8]: https://support.azul.com/hc/en-us/community/topics/200490266-Zing-Downloads-and-Evaluations
  
  [53]: https://github.com/alex01t/fp-zing/blob/master/feature-preview/ubuntu/8/Dockerfile
  [84]: https://github.com/alex01t/fp-zing/blob/master/feature-preview/ubuntu/11/Dockerfile
