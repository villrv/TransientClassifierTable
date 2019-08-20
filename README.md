|Name |	Author | Public? |	Goal |	Training Set |	Feature extraction |	Selection bias correction |	Classifier |	Redshft? |	Notes |
| --- | ------ | ------- | ----- | ------------- | ------------------- | ---------------------------- | ---------- | ----------- | ------ |
| PELICAN	| [Pasquet et al (2019)](https://www.aanda.org/articles/aa/pdf/2019/07/aa34473-18.pdf) |	No 	|	Ia-nonIa |	SPCC/SDSS	|	denoising autoencoder	|	"Contrastive CNN"	|CNN |	yes/ no | |
| | [Lochner et al (2016)](https://arxiv.org/pdf/1603.00882.pdf) | No | Ia, II, Ibc|SPCC|Various (Best: SALT2/wavelet)|None|Various (Best: boosted decision trees)|No | |
| PSNID	| [Link Missing](https://researchportal.port.ac.uk/portal/files/1299008/0004_637X_738_2_162.pdf) |Yes (SNANA)|Ia, II, Ibc|SDSS|None|None?|Template matching|no| |
| | [Ishida & Souza (2013)](https://academic.oup.com/mnras/article/430/1/509/985966) |	No |	Ia-nonIa|	SPCC |	kernel PCA | no	| |  |
| | [Jones + (2017)](https://archive.stsci.edu/prepds/ps1cosmo/) | No? | Ia-nonIa | PS1-MDS	| SALT2 | 	BEAMS	| BEAMS | 	no	| [BEAMS reference](https://arxiv.org/abs/1111.5328) | 
|SuperNNova | [Moller & Boissiere (2019)](hi)	Yes	General SN	SPCC	LC itself	None	RNN	yes/no		 |
|avocado| [Boon (2019)](https://arxiv.org/pdf/1907.04690.pdf) |Yes |General Transients | plasticc|hand-selected; Gaussian Process	|uniform redshift resampling | boosted RF | no	| 
|RAPID | [Muthukrishna + (2019)](https://arxiv.org/pdf/1904.00014.pdf ) |Yes | General Transients | plasticc | LC itself | None | RNN | 	yes/no | 
| |	[Villar + (2019)](https://arxiv.org/pdf/1905.07422.pdf) | No | General SN | PS1-MDS | Various (Best: PCA) | None | Various (Best: RF) | yes |  
| |	[Charnock & Moss (2017)](https://arxiv.org/pdf/1606.07442.pdf) | No? | Ia, II, Ibc | SPCC | Lc itself | None | RNN | yes/no	|  
|GalSNID |	[Foley & Mandel (2013)](https://arxiv.org/pdf/1309.2630.pdf%C3%82%C2%A0>) | Yes | Ia-nonIa | LOSS, SDSS, PTF | host properties | None |	Naive Bayes | yes | 
| | Cambell + (2013)			SDSS						https://arxiv.org/pdf/1211.4480.pdf |
