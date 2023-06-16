# PyWren

Forked from [PyWren](https://github.com/pywren/pywren) to allow execution in Python 3.7.


> The wrens are mostly small, brownish passerine birds in the mainly New World family Troglodytidae. ... Most wrens are small and rather inconspicuous, except for their loud and often complex songs. - Wikipedia

PyWren -- it's like a mini condor, in the cloud, for often-complex calls. You can get up to 40 TFLOPS peak from AWS Lambda:

![Benchmark](https://raw.githubusercontent.com/pywren/pywren/master/pywren.gflops.png)

# Setup

To setup PyWren3.7, first build and push your runtime using [Runtimes](https://github.com/Tratori/runtimes).
Install this repo by executing `pip install .` in this project's base directory.
Call `pywren-setup` for an automated setup script.

Other commands can be seen using `pywren --help`.
