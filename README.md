# actdr4kappa-x-desy3gamma-data
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a>

Data repository for Shaikh et al (2023) on ACT-DR4 CMB lensing x DES-Y3 cosmic shear.

## Contents:
`data/`

`UNBLINDED_ACTPlanck_tSZfree_ACTDR4-kappa_DESY3-gamma_data_simCov.fits`<br>
The data vector used in the work. Consisting of a [sacc format](https://sacc.readthedocs.io/en/latest/sacc.html) fits file with power spectrum band powers, band power window functions, binned covariance matrix and galaxy redshift distributions for the four DES tomographic bins. A summary plot is shown in Figure 16 of the paper.

`chains/`

The output of the Monte Carlo chains used for estimating the posterior on cosmological and nuisance parameters. Consisting of output text files from the [Cobaya mcmc sampler](https://cobaya.readthedocs.io/en/latest/sampler_mcmc.html), including a yaml format specification for re-running the chain. Readily readable and analysable as described [here](https://cobaya.readthedocs.io/en/latest/post.html) with the [GetDist package](https://getdist.readthedocs.io/en/latest/).

`UNBLINDED_ACTPlanck_tSZfree-s3-y1_ia-all_zbins-default_dzm-default_nu`<br>
The main results chain as displayed in Figures 17, 18, B3 of the paper.

`UNBLINDED_ACTPlanck_tSZfree-s3-y1_ia-highz_zbins-default_dzm-default_nu`<br>
The result using only the two highest redshift bins (3, 4) from DES, as displayed in Figure 19 of the paper.

`UNBLINDED_ACTPlanck_tSZfree-s3-y1_ia-lowz_zbins-default_dzm-default_nu`<br>
The result using only the two lowest redshift bins (1, 2) from DES, as displayed in Figure 19 of the paper.

`UNBLINDED_ACTPlanck_tSZfree-s3-fixed_ia-all_zbins-wide_dzm-default_nu`<br>
The result including only the highest redshift bin from DES (4) and varying only the galaxy weak lensing nuisance parameters $m$ and $\Delta z$, as displayed in Figure 20 of the paper.

## Citation
These data and chains were generated as part of the work:<br>
>*Cosmology from Cross-Correlation of ACT-DR4 CMB Lensing and  DES-Y3 Cosmic Shear*<br>
>S. Shaikh, I. Harrison, A. van Engelen, G. Marques et al. arXiv: [2309.XXXXX](https://arxiv.org/abs/2309.XXXXX). To be submitted to Monthly Notices of the Royal Astronomical Society.


The data vector in this analysis was formed by combining the ACT-DR4 lensing map:<br>
>*The Atacama Cosmology Telescope: A CMB lensing mass map over 2100 square degrees of sky and its cross-correlation with BOSS-CMASS galaxies*<br>
>O. Darwish et al. Monthly Notices of the Royal Astronomical Society 500 (2021) 2, 2250-2263. arXiv: [2004.01139](https://arxiv.org/abs/2004.01139), DOI: [10.1093/mnras/staa3438](https://doi.org/10.1093/mnras/staa3438)

with the DES-Y3 shear catalogue:<br>
>*Dark energy survey year 3 results: weak lensing shape catalogue*<br>
>M. Gatti & E. Sheldon  et al. Monthly Notices of the Royal Astronomical Society 504 (2021) 3, 4312-4336. arXiv: [2011.03408](https://arxiv.org/abs/2011.03408). DOI: [10.1093/mnras/stab918](https://doi.org/10.1093/mnras/stab918)

## License
<br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
