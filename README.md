# README #

## Antibody-GAN ##

A python implementation of Antibody-GAN: a Generative Adversarial Network (GAN) for full variable framework antibody generation.

BioRxiv Preprint:
https://www.biorxiv.org/content/10.1101/2020.04.12.024844v1

Code is currently password protected. To be released upon journal acceptance.

### System Requirements ###

* All software dependencies and versions provided in antibodygan.yml

* Example hardware requirements: AWS EC2 Instance - g3.8xlarge


### Installation guide ###

* Clone AntibodyGAN repository
* Create a new Python 3.6 virtual environment using antibodygan.yml

	'conda-env create -n antibodygan -f=antibodygan.yml'
	
	'source activate antibodygan'


### Demo ###

* Demo training data provided in /data
* Run "python example.py" to train a HV3-30/KV3-20 model
* View example model snapshots in /results 
* 100 generated example hv and kv sequences will also appear in /results


### Licensed Use ###

Antibody-GAN: a Generative Adversarial Network (GAN) for full variable framework antibody generation.

Copyright (C) 2020 Just-Evotec Biologics, Inc.

Just-Evotec Biologics, Inc.
401 Terry Avenue North, Seattle WA 98109

Email: info@just.bio
 
Limited License

1. License Grant. The Antibody-GAN program is proprietary software of Just-Evotec Biologics, Inc., for which a fully paid-up, royalty-free license is hereby granted to you to use, modify to create derivative works, copy, distribute copies, and publish, for peer-review, academic and research purposes only; any commercial use of the Antibody-GAN program and modified derivatives thereof is not authorized.

2. Copyright Notice. Each copy of the Antibody-GAN program and derivatives created by a user under this Limited License shall include the full copyright notice and contact information above and a copy of this Limited License in its entirety.  

3. Disclaimers. Use of the Antibody-GAN program may require the use of additional software libraries. These libraries are not included in the Antibody-GAN software, and additional licenses from third parties may need to be obtained by the user for a given purpose.
  
THE SOFTWARE IS PROVIDED "AS IS," WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

4. Further Notices and Acknowledgments. The ANTIBODY-GAN program incorporates extensive derivative modifications of the following software components and may be used only in compliance with all applicable licenses:
____________________________________________________________________________

Keras-GAN, wgan-gp code 
   - url: https://github.com/eriklindernoren/Keras-GAN/blob/master/wgan_gp/wgan_gp.py
   - license: MIT

You should have received a copy of the MIT license provided herewith or, if not, a copy can be obtained at: 
https://opensource.org/licenses/MIT
  
_____________________________________________________________________________

The MIT License (MIT)
Copyright (c) <year> <copyright holders>
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:
The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.



### Contact ###

Just-Evotec Biologics, Inc.
401 Terry Avenue North, Seattle WA 98109

Email: tileli.amimeur@just.bio
Email: info@just.bio
