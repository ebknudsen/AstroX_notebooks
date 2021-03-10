# Howto
To run this notebook - the simplest way is to clone the git repository directly, and then start it from the repo directory (or copy the .ipnb and the set of data files to a working directory) by issuing the follwing command:
```
jupyter notebook NuSTAR.inpnb
```
This shold open a brwoser window automatically from which you may run the notebook.
In order to actually run the McXtrace compiler toolchain, you also need to download an extra files to the notebook directory.
Unfortunately, for licensing reasons that have yet to be resolved, these filee has to reside in a different repository elswehere.
The needed file is the file containing the component code for the conical Shell component which may be found here:
1. [Shell_c.comp](https://gitlab.com/athena2/AstroX/-/raw/master/mcxtrace-astrox-comps/optics/Shell_c.comp)
2. [Primary optics data](https://gitlab.com/athena2/AstroX/-/raw/master/mcxtrace-astrox-comps/optics/Shell_c.comp)
3. [Secondary optics data](https://www.nytimes.com)

If you don't know what that means there are plenty of jupyter "getting started" guides around the internet. We are working on solutions using Binder and/or Colab or similar, but for now we are limited to running locally.
