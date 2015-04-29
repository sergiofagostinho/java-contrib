# Invisible Objects Java contrib
This repository is my humble contribution for Java developers out there, including myself in the future, in the form of a library.

##Purpose
I currently don't have the ambition to actually distribute this as a library _per se_ (i.e. as a Maven package), there are some projects out there to do that, such as the Apache Commons (https://commons.apache.org/components.html) or Google's Guava (https://code.google.com/p/guava-libraries/). I'm currently more focused on sharing my developer experience on good practices, and hopefully getting some feedback. This is also a support tool to my blog (http://sergioagostinho-dev.blogspot.pt/).

##Structure
There are currently two major packages:
* `pt.invisibleobjects.contrib.util`: classes that you could use in production code.
* `pt.invisibleobjects.contrib.test`: classes that you could use in test code.

Each sub-package will be added according dependencies on other libraries.

In any case, packages _may_ change in the future.

##What do I need to build or use this code?

All the code _should_ run on JDK 7, but I'm using the compiler and runtime from JDK 8.
