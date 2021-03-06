### v0.2 Released!

v0.2 is a complete re-write.  Please see
[the docs for details](http://nilmtk.github.io/nilmtk/master/index.html).
The old v0.1 code is still available in the v0.1 branch and the [old
docs are in v0.1.1](http://nilmtk.github.io/nilmtk/v0.1.1/index.html).


nilmtk: Non-Intrusive Load Monitoring Toolkit
======

Non-Intrusive Load Monitoring (NILM) is the process of estimating the energy consumed by individual
appliances given just a whole-house power meter
reading.  In other words, it produces an (estimated) itemised
energy bill from just a single, whole-house power meter.

NILM is sometimes called:

* "non-intrusive appliance load monitoring (NALM or NIALM)"
* "[electriciy | energy | smart meter] disaggregation"

Below is an illustration<sup>1</sup> of what NILM, in general, can do.

<img src="https://dl.dropboxusercontent.com/u/75845627/misc/after_disagg.png" alt="Drawing" style="width: 40% height: 40%;"/>

##### NILMTK Documentation

http://nilmtk.github.io/nilmtk/

##### Academic paper on NILMTK

Batra, N., Kelly, J., Parson, O., Dutta, H., Knottenbelt, W., Rogers, A., Singh, A., Srivastava, M. (2014). NILMTK: An Open Source Toolkit for Non-intrusive Load Monitoring. In Fifth International Conference on Future Energy Systems (ACM e-Energy). Cambridge, UK. arXiv:[1404.3878](http://arxiv.org/abs/1404.3878) DOI:[10.1145/2602044.2602051](http://dx.doi.org/10.1145/2602044.2602051)

Bibtex:

```
@inproceedings{NILMTK,
   title = {{NILMTK: An Open Source Toolkit for Non-intrusive Load Monitoring}},
   year = {2014},
   author = {Batra, Nipun and Kelly, Jack and Parson, Oliver and Dutta, Haimonti and Knottenbelt, William and Rogers, Alex  and Singh, Amarjeet and Srivastava, Mani},
   booktitle = {Fifth International Conference on Future Energy Systems (ACM e-Energy)},
   address = {Cambridge, UK},
   archivePrefix = {arXiv},
   arxivId = {1404.3878},
   doi = {10.1145/2602044.2602051},
   eprint = {1404.3878}
}
```

Please note that the paper was submitted back in Jan 2014 and the code
has evolved *a lot* since then!  Please do not use the paper as a
guide to the current API.  Instead please use the [online docs](http://nilmtk.github.io/nilmtk/master/index.html).

##### Keeping up to date with NILMTK

Please sign up to the [NILMTK-Announce mailing list](https://groups.google.com/forum/#!forum/nilmtk-announce) to be kept up to speed on NILMTK.  It will be a fairly low-traffic mailing list.  We'll just announce new versions, new docs etc.

[NILMTK is also on Twitter](https://twitter.com/nilmtk).

##### Current state of the project

The project is in its early stages.

Please note that NILMTK is currently a research tool.  It is not yet
ready for use by end-users, although we certainly hope that NILMTK
will be capable of doing 'plug and play' disaggregation in the future.

Please see the docs for more info.

##### Installing

First, please install [NILM Metadata](https://github.com/nilmtk/nilm_metadata).

If you just want to use the code without modifying it then:

`python setup.py install`

(you may have to run as `sudo`)

If you want to get involved in development then:

`python setup.py develop`


##### Notes

1. The image is from the following paper and since the main author is contributing to nilmtk, so no permission issues.
The reference is: Nipun Batra, Haimonti Dutta, Amarjeet Singh, “INDiC: Improved Non-Intrusive load monitoring using load Division and     Calibration”, to appear at the 12th International Conference on Machine Learning and Applications (ICMLA’13) will be     held in Miami, Florida, USA, December 4 – December 7, 2013 
    [Preprint](http://nipunbatra.files.wordpress.com/2013/09/icmla.pdf).  [IPython notebook](http://www.iiitd.edu.in/~amarjeet/Research/indic.html)

