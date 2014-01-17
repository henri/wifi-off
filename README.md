# Wi-Fi Off  #

<h1><img src="http://images.apple.com/support/assets/images/products/airport/hero_airport_wifi.png" valign="middle"/></h1>

About
--------

This is an open source (Apache 2.0) script and package build system which is designed to turn off wi-fi on a Mac OS X system(s).

License: [Apache 2.0 License][1]


Usage Instructions
---------

- Ensure you have the developer tools and command line tools installed. Of particular importance is the `pkgbuild` command which is used in order to build the package.
- Duplicate (copy) the build script to a file in the same direcotry with an approriate name (eg. my_build.bash)
- Edit your copy of the build script setting the *package_identifier*, *package_output_name* and *package_version* varibles to suite you requirments.
- Run the build script and with all things going well collect your output package from the build_output directory


Notes relating to using the core script within another system
---------
 
Finally, should you wish to use this script it is important that you adhear to the licence agreement.


  [1]: http://www.apache.org/licenses/LICENSE-2.0

