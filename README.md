|Name |	Author | Public? |	Goal |	Training Set |	Feature extraction |	Selection bias correction |	Classifier |	Redshft? |	Notes |
| --- | ------ | ------- | ----- | ------------- | ------------------- | ---------------------------- | ---------- | ----------- | ------ |
| PSNID	| [Sako et al. (2011)](https://researchportal.port.ac.uk/portal/files/1299008/0004_637X_738_2_162.pdf) |Yes (SNANA)|Ia, II, Ibc|SDSS|None|None?|Template matching|No| |
|GalSNID |	[Foley & Mandel (2013)](https://arxiv.org/pdf/1309.2630.pdf%C3%82%C2%A0>) | Yes | Ia-nonIa | LOSS, SDSS, PTF | host properties | None |	Naive Bayes | Yes | 
| | [Ishida & Souza (2013)](https://academic.oup.com/mnras/article/430/1/509/985966) |	No |	Ia-nonIa|	SPCC |	kernel PCA | None	| Nearest Neighbor | No  | |
| | [Lochner et al. (2016)](https://arxiv.org/pdf/1603.00882.pdf) | No | Ia, II, Ibc|SPCC|Various (Best: SALT2/wavelet)|None|Various (Best: boosted decision trees)|No | |
| | [Jones et al. (2017)](https://archive.stsci.edu/prepds/ps1cosmo/) | No? | Ia-nonIa | PS1-MDS	| SALT2 | 	BEAMS	| BEAMS | 	No	| [BEAMS reference](https://arxiv.org/abs/1111.5328) | 
| |	[Charnock & Moss (2017)](https://arxiv.org/pdf/1606.07442.pdf) | No? | Ia, II, Ibc | SPCC | Lc itself | None | RNN | Yes/No	|  
|avocado| [Boon (2019)](https://arxiv.org/pdf/1907.04690.pdf) |Yes |General Transients | plasticc|hand-selected; Gaussian Process	|uniform redshift resampling | boosted RF | No	| 
|SuperNNova | [Moller & de Boissiere (2019)](https://arxiv.org/pdf/1901.06384.pdf) | Yes |	General SN |SPCC|LC itself | None |RNN | Yes/No |		 |
|RAPID | [Muthukrishna et al. (2019)](https://arxiv.org/pdf/1904.00014.pdf ) |Yes | General Transients | plasticc | LC itself | None | RNN | 	Yes/No | 
| PELICAN	| [Pasquet et al (2019)](https://www.aanda.org/articles/aa/pdf/2019/07/aa34473-18.pdf) |	No 	|	Ia-nonIa |	SPCC/SDSS	|	denoising autoencoder	|	"Contrastive CNN"	|CNN |	Yes/ No | |
| |	[Villar et al. (2019)](https://arxiv.org/pdf/1905.07422.pdf) | No | General SN | PS1-MDS | Various (Best: PCA) | None | Various (Best: RF) | Yes |  