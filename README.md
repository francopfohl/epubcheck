[![Current Release](https://img.shields.io/github/release/w3c/epubcheck.svg)](https://github.com/w3c/epubcheck/releases/latest) [![Github All Releases Downloads](https://img.shields.io/github/downloads/w3c/epubcheck/total.svg?colorB=A9A9A9)](https://github.com/w3c/epubcheck/releases/) [![Build Status](https://travis-ci.org/w3c/epubcheck.svg?branch=master)](https://travis-ci.org/w3c/epubcheck/)


EPUBCheck
=========

EPUBCheck is a tool to validate the conformance of EPUB publications against the EPUB specifications.
EPUBCheck can be run as a standalone command-line tool or used as a Java library.

EPUBCheck is open source software, maintained by the [DAISY Consortium](http://www.daisy.org) for the [W3C](https://www.w3.org/publishing/epubcheck_fundraising).


**We Need Your Support!!**  
Financial support is critical to the development of EPUBCheck, the tool we all use to validate EPUB files.
We need to make sure that the resources are adequate to both update the tool and provide for its continued maintenance over the next two years;
please [help us fund and support EPUBCheck](https://www.w3.org/publishing/epubcheck_fundraising), and join the [list of donators](#donators)!


## Downloads

Check the [releases page](https://github.com/w3c/epubcheck/releases) to get the latest distribution.

[EPUBCheck 4.1.0](https://github.com/w3c/epubcheck/releases/tag/v4.1.0) is the latest recommended version to validate both EPUB 2 and 3 files.


## Documentation

Documentation on how to **use** EPUBCheck, to **contribute** to the project or to **translate** messages is available on the [EPUBCheck wiki](https://github.com/w3c/epubcheck/wiki).

Technical discussions are held on our public [mailing list](https://lists.w3.org/Archives/Public/public-epubcheck/). To subscribe to the mailing list, send an email with subject `subscribe` to [public-epubcheck-request@w3.org](mailto:public-epubcheck-request@w3.org?subject=subscribe). To participate in the discussion, simply send an email to [public-epubcheck@w3.org](mailto:public-epubcheck-request@w3.org).

Historical archives of discussions prior to October 2017 are stored at the old [EPUBCheck Google Group](https://groups.google.com/forum/#!forum/epubcheck).

## Building EPUBCheck

To build epubcheck from the sources you need Java Development Kit (JDK) 1.7 or above and [Apache Maven](http://maven.apache.org/) 3.0 or above installed.

You will also need Python to be able to run the BookReporter and related tools.

Build and run tests:

```
$ mvn install
```
Will copy `.*jar` files and packages to `target/` folder...

## Credits

Most of the EPUBCheck functionality comes from the schema validation tool [Jing](http://www.thaiopensource.com/relaxng/jing.html) and schemas that were developed by [IDPF](http://www.idpf.org/) and [DAISY](http://www.daisy.org/). Initial EPUBCheck development was largely done at [Adobe Systems](http://www.adobe.com/).

Initial (pre 2012) authors and contributors to EPUBCheck include: Peter Sorotokin, Garth Conboy, Markus Gylling, Piotr Kula, Paul Norton, Jessica Hekman, Liza Daly, George Bina, Bogdan Iordache, Ionut-Maxim Margelatu

EPUBCheck 4.0 was largely developed by
* [DAISY](http://www.daisy.org/), namely: Romain Deltour, Markus Gylling
* [Barnes & Noble](https://www.barnesandnoble.com), namely: Steve Antoch, Arwen Pond

Regular contributors between 2012 and 2017 include: Romain Deltour, Tobias Fischer, Markus Gylling, Satoshi KOJIMA, Thomas Ledoux, Masayoshi Takahashi

Many thanks are also extended to the numerous people who have contributed to the evolution of EPUBCheck through bug reports and patches!

## Donators

The following organizations are supporting the development of EPUBCheck by their contribution to the [fundraising initiative](https://www.w3.org/publishing/epubcheck_fundraising):

<p float="left">
  <a href="http://daisy.org"><img alt="DAISY" src="https://github.com/w3c/publishing/blob/master/donators_logos/daisy_high.jpg?raw=true" width="100" hspace="20" align="middle"/></a>
  <a href="https://pubhub.dk"><img alt="Publizon A/S" src="https://github.com/w3c/publishing/blob/master/donators_logos/publizon-logo.jpg?raw=true" width="100" hspace="20" align="middle"/></a>
  <a href="https://www.wiley.com"><img alt="Wiley" src="https://github.com/w3c/publishing/blob/master/donators_logos/Wiley_Wordmark_black.png?raw=true" width="200" hspace="20" align="middle"/></a>
  <a href="https://www.hachette.com"><img alt="Hachette Livre" src="https://github.com/w3c/publishing/blob/master/donators_logos/Hachette%20Livre.jpg?raw=true" width="300" hspace="20" align="middle"/></a>
  <a href="https://www.learningmate.com"><img alt="LearningMate Solutions Inc" src="https://github.com/w3c/publishing/blob/master/donators_logos/LearningMate%20Logo.png?raw=true" width="100" hspace="20" align="middle"/></a>
  <a href="https://www.voyager.co.jp"><img alt="Voyager Japan, Inc." src="https://github.com/w3c/publishing/blob/master/donators_logos/rectangle_VJstar_logo_512.jpg?raw=true" width="100" hspace="20" align="middle"/></a>
  <a href="https://wwnorton.com"><img alt="W. W. Norton" src="https://github.com/w3c/publishing/blob/master/donators_logos/NortonLogo_notagline.jpg?raw=true" width="100" hspace="20" align="middle"/></a>
  <a href="https://luminadatamatics.com"><img alt="Lumina Datamatics, Inc." src="https://github.com/w3c/publishing/blob/master/donators_logos/Datamatics_logo.jpg?raw=true" width="100" hspace="20" align="middle"/></a>
</p>

## License

EPUBCheck is made available under the terms of the [New BSD License](http://opensource.org/licenses/BSD-3-Clause)
