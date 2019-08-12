(README-ubuntu-fp) What is Zing? ![Zulu Duke in a Box][1]
======================================

Azul Zing is a runtime platform that uses the Zing Virtual Machine to run Java™ technology-based applications for Linux operating systems. The Zing Virtual Machine (ZVM) allows existing Java applications to elastically scale to dozens of CPU cores and hundreds of gigabytes of memory, meaning resources can also scale up and down based on real-time demands, and without garbage collection pauses present in other Java runtimes.

Azul Zing is compliant with the Java SE standard. 

Zing is built, tested, supported, and delivered by [Azul Systems][2].

Check out [Zing Overview][3] for more information.

Azul provides access to feature previews of Zing® in order to collect early feedback and enable testing of various applications in development environments. The Zing preview package is updated on a weekly basis and is an in-development feature preview version that might be unstable or not performing. Azul undertakes reasonable effort to ensure acceptable quality of the bits. Zing preview builds are not supported and must not be used in production.

At any time you can post your questions at the [Zing Community Forum][8].


Centos, Debian, and Ubuntu Docker images of Zing are available in the following repositories:

  * [azul/fp-zing/feature-preview/zing-centos][5]
  * [azul/fp-zing/feature-preview/zing-debian][6]
  * [azul/fp-zing/feature-preview/zing-ubuntu][7]

Tags and `Dockerfile` links
===========================

Most Recent
-----------

The Zing azul/fp-zing/feature-preview/zing-ubuntu repository provides various Ubuntu Docker image tags. The most recent Zing versions of OpenJDK 11 and 8 are listed below:

 * [ `11` (*Dockerfile*)][84]

 * [ `8` (*Dockerfile*)][53]


Usage
=====

This Zing repository supports numerous versions of OpenJDK-based Java SE JDKs. Versions 11 and 8 of Zing are compliant with Java SE 11 and 8 respectively.

To run a container of your choice, use commands below as an example.

For a Zing 11 container, enter:

    docker run -it --rm azul/zing-fp/ubuntu:11 java -version

For a Zing 8 container, enter:

    docker run -it --rm azul/zing-fp/ubuntu:8 java -version


  [1]: https://www.azul.com/files/ZuluDocker60.gif
  [2]: http://www.azul.com/zulu
  [3]: https://www.azul.com/products/zing/
  [5]: https://hub.docker.com/r/azul/fp-zing/feature-preview/zing-centos
  [6]: https://hub.docker.com/r/azul/fp-zing/feature-preview/zing-debian
  [7]: https://hub.docker.com/r/azul/fp-zing/feature-preview/zing-ubuntu
  [8]: https://support.azul.com/hc/en-us/community/topics/200490266-Zing-Downloads-and-Evaluations
  
  [53]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/8u222-8.40.0.25/Dockerfile
  [84]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/11.0.4-11.33/Dockerfile
