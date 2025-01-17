<img src="logo/logo_640.png" width="240" height="240">

### dyconnmap
A neuroimaging module for dynamic connectome mapping.
 
<table>
 <tr>
  <td>build & code</td>
  <td><br/>
   
[![Build Status](https://travis-ci.org/makism/dyconnmap.svg?branch=master)](https://travis-ci.org/makism/dyconnmap) [![Coverage Status](https://coveralls.io/repos/github/makism/dyconnmap/badge.svg?branch=master)](https://coveralls.io/github/makism/dyconnmap?branch=master) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/10f434822c3a4bdb89dd0bf43f524970)](https://www.codacy.com/gh/makism/dyconnmap/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=makism/dyconnmap&amp;utm_campaign=Badge_Grade)
   </td>
 </tr>
 <tr>
  <td>package</td>
  <td><br/>
 
 [![PyPI version](https://badge.fury.io/py/dyconnmap.svg)](https://badge.fury.io/py/dyconnmap) 
 [![Anaconda-Server Badge](https://anaconda.org/makism/dyconnmap/badges/version.svg)](https://anaconda.org/makism/dyconnmap)
 ![Whenenver a new tag is pushed; a wheel distribution is uploaded on the Test PyPI index.](https://github.com/makism/dyconnmap/workflows/publish-test-pypi/badge.svg)
 [![Libraries.io dependency status for latest release](https://img.shields.io/librariesio/release/pypi/dyconnmap)](https://libraries.io/github/makism/dyconnmap)   
 [![Downloads](https://pepy.tech/badge/dyconnmap)](https://pepy.tech/project/dyconnmap)
 </td>
 </tr>
 <tr>
 <td>release</td>
 <td><br/>

![python-versions](https://img.shields.io/pypi/pyversions/dyconnmap)
[![Licence](https://img.shields.io/badge/Licence-BSD-blue.svg)](https://opensource.org/licenses/BSD-3-Clause) 
[![Documentation Status](https://readthedocs.org/projects/dyconnmap/badge/?version=latest)](https://dyconnmap.readthedocs.io/?badge=latest)
 </td>
 <tr>
 <td>tutorials</td>
 <td><br/>
  
   [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/makism/dyconnmap/master?filepath=tutorials)
</td>
</tr>

<tr>
 <td>social & updates</td>
 <td><br/>
  
   [![RG](https://img.shields.io/badge/RG%20Project-Python%20tools%20for%20Brain%20Network%20Analysis-%2300ccbb)](https://www.researchgate.net/project/Python-tools-for-Brain-Network-Analysis)
  </td>
</tr>
</table>

_dyconnmap_ (abbreviated from “dynamic connectome mapping”), a neuroimaging python module specifically designed for estimating the dynamic connectivity and analyzing complex brain networks; from neurophysiological data such as electroencephalogram (EEG), magnetoencephalography (MEG) and functional magnetic resonance imaging (fMRI) recordings. It includes numerous submodules to work with, such as chronnectomics and graph-theoretical algorithms, (symbolic) time series and statistical methods.

This is an ongoing effort to develop the module further and extend it by adding more algorithms related to graph analysis and statistical approaches. Considering the increasing acceptance and usage of python in analyzing neuroimaging data, we firmly believe that the module will be a great addition in every practitioner's toolbox engaged in brain connectivity analysis.

Built on [NumPy](http://www.numpy.org/), [SciPy](http://www.scipy.org/), [matplotlib](http://matplotlib.org/) and [networkx](https://networkx.github.io/).

#### Workflow outline

![workflow](docs/v2_pipeline.png)


#### Publications


* [ Marimpis, A. D., Dimitriadis, S. I., & Goebel, R. (2021). Dyconnmap: Dynamic connectome mapping—A neuroimaging python module. Human Brain Mapping, 1– 31. https://doi.org/10.1002/hbm.25589](https://onlinelibrary.wiley.com/doi/10.1002/hbm.25589) [![DOI](https://img.shields.io/badge/DOI-10.1002/hbm.25589-blue.svg)](https://doi.org/10.1002/hbm.25589)

* [poster presented @ 13th International Conference for Cognitive Neuroscience in Amsterdam \(ICON2017\)](https://f1000research.com/posters/6-1638) [![DOI](https://img.shields.io/badge/DOI-10.7490%2Ff1000research.1114652.1-blue.svg)](https://dx.doi.org/10.7490/f1000research.1114652.1) [under the previous name "dyfunconn"]

#### Resources

* [Installation](https://github.com/makism/dyconnmap/blob/master/INSTALL.md)

* [API Documentation](http://dyconnmap.readthedocs.io/?badge=latest)

* [Tutorials](https://github.com/makism/dyconnmap/tree/master/tutorials)

* [Examples](https://github.com/makism/dyconnmap/tree/master/examples)


#### Citation

If you use _dyconnmap_ or _dyfunconn_ in a published work, please consider citing.

<table align="center">
    <tr>
        <td align="left">1.</td>
        <td align="left"> Marimpis, A. D., Dimitriadis, S. I., & Goebel, R. (2021). Dyconnmap: Dynamic connectome mapping—A neuroimaging python module. Human Brain Mapping, 42( 15), 4909– 4939. https://doi.org/10.1002/hbm.25589</td>
    </tr>
    <tr>
        <td align="left">2.</td>
        <td align="left">Marimpis, A. D., & Dimitriadis, S. I. (2017). dyfunncon: dynamic functional connectivity–a neuroimaging Python module. F1000Research, 6. https://doi.org/10.7490/f1000research.1114652.1</td>
    </tr>
</table>

#### Sponsors

<table>
 <tr>
  <td align="left" width="200px">Nov 2017 - Apr 2021</td>
  <td>Brain Innovation B.V.</td>
 </tr>
 <tr>
  <td align="left" width="200px">Sept 2017</td>
  <td>BRAINTRAIN (Taking imaging into the therapeutic domain: Self-regulation of brain systems for mental disorders) research project (FP7-HEALTH).</td>
 </tr>
</table>
