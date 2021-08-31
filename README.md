# room-impulse-responses
A list of publicly available acoustic/room impulse response (AIR/RIR) datasets. Currently this repo only tracks real-world recorded room impulse responses. Datasets included here may contain other data (e.g., speech, noise) in addition to RIRs. But this repo only describes the datasets about their RIR contents below. While there may be other webpages (if not outdated) that list some of the RIR datasets, this repo provides a brief description about the content of each dataset so you don't have to download and inspect them one by one before realizing it is not what you desire.

This repo also provides some scripts for downloading datasets if possible. Some dataset may require registration to download, which we may not provide download links directly. Only rows marked with a :heavy_check_mark: are directly downloadable by running `./get_all_rirs.sh [destination folder]`.

| Name |  Content          | Year | Paper/Document   | In script |
| :----------------- | :------------- | :----- | :----- | :-----: |
| [MeshRIR](https://sh01k.github.io/MeshRIR/) | 4410 mono RIRs recorded in very dense grids in a moderately reverberant room with accurate coordinates. | 2021 | [MeshRIR: A Dataset of Room Impulse Responses on Meshed Grid Points For Evaluating Sound Field Analysis and Synthesis Methods](https://arxiv.org/abs/2106.10801) |
| [BUT Reverb Database](https://speech.fit.vutbr.cz/software/but-speech-fit-reverb-database) | 1300+ mono channel RIRs recorded in 8 rooms | 2019 | [Building and evaluation of a real room impulse response dataset](https://ieeexplore.ieee.org/document/8717722) | :heavy_check_mark:
| [MIT IR Survey](https://mcdermottlab.mit.edu/Reverb/IR_Survey.html) | 271 mono channel RIRs all recorded in distinct places | 2016 | [Statistics of natural reverberation enable perceptual separation of sound and space](https://www.pnas.org/content/113/48/E7856) | :heavy_check_mark:
| [ACE Challenge](http://www.ee.ic.ac.uk/naylor/ACEweb/index.html) | {1,2,3,5,8,32} channel RIRs recorded in 7 rooms | 2015 | [The ACE challenge — Corpus description and performance evaluation](https://ieeexplore.ieee.org/document/7336912) |
| [Multichannel Impulse Response Database](https://www.eng.biu.ac.il/gannot/downloads/) | 234 8-channel RIRs recorded in the same room with 3 levels of reverberation and different microphone array spacings | 2014 | [Multichannel audio database in various acoustic environments](https://ieeexplore.ieee.org/document/6954309) | :heavy_check_mark:
| [REVERB Challenge](https://reverb2014.dereverberation.com/) | 24 8-channel RIRs recorded in small, medium, and large rooms | 2013 | [The reverb challenge: A common evaluation framework for dereverberation and recognition of reverberant speech](https://ieeexplore.ieee.org/document/6701894) | :heavy_check_mark:
| [OpenAIR](https://www.openairlib.net/) | Ambisonic B format RIRs recorded in over 46 (still increasing) environments | 2010 | [Openair: An interactive auralization web resource and database](https://www.aes.org/e-lib/browse.cfm?elib=15648) | :heavy_check_mark:
| [C4DM RIR database](http://isophonics.net/content/room-impulse-response-data-set) | 468 mono or ambisonic B format RIRs recorded in 3 large environments | 2010 | [Database of Omnidirectional and B-Format Impulse Responses](https://ieeexplore.ieee.org/document/5496083) 
| [Aachen impulse response database](http://www.iks.rwth-aachen.de/en/research/tools-downloads/databases/aachen-impulse-response-database/) | 344 binaural RIRs measured with a dummy head in 5 environments including a church | 2009 | [A Binaural Room Impulse Response Database for the Evaluation of Dereverberation Algorithms](https://ieeexplore.ieee.org/abstract/document/5201259) | :heavy_check_mark:
| [RWCP Sound Scene Database](http://research.nii.ac.jp/src/en/RWCP-SSD.html) | 143 multi-channel RIRs recorded in 14 rooms | 2000 | [Sound scene data collection in real acoustical environments](https://library.naist.jp/dspace/bitstream/handle/10061/7746/JourAcouSocJaE_20_3_225.pdf?sequence=1) | :heavy_check_mark:

# Contribute
Collecting real-world impulse responses is not easy. This repo tries to keep up with new real-world datasets available through volunteers. If you know publicly available datasets that are not listed here, you are welcome to create a pull request by adding a new entry to the list (and optionally the script to download & organize it). When writing the description, please highlight how many IRs and environments and what channel format are invovled in this dataset.

# Reference
Please properly cite whichever datasets you use in your paper. It would be great if you can also provide a link to this page (e.g., as a footnote, not a citation) so that others may find it useful.
