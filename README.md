# LOCO: Logistics Objects in Context

LOCO is the first scene understanding dataset for logistics covering the problem of detecting logistics-specific objects. Images are captured while walking through a logistics setting using low-cost cameras. We currently provide 37,988 images captured in 5 logistics environments, of which 4882 images are manually annotated, resulting in 153,238 annotations. Annotated classes include forklifts, pallet trucks, pallets, small load carriers and stillages (v1). Recently, we also added people annotations (v2). Moreover, version 3 adds 7315 synthetic images of forklifts, pallet trucks, pallets, small load carriers and stillages using [this](https://mediatum.ub.tum.de/doc/1554870/1554870.pdf) approach.

<div style="text-align:center"><img src="./assets/loco_sample_images.png" /></div>

For more details, we refer to our [paper](https://mediatum.ub.tum.de/doc/1578845/1578845.pdf). If you use LOCO for your research, please consider citeing our work ([Bibtex](https://mediatum.ub.tum.de/export/1578845/bibtex)).

### Quick Start
This repository is tested using Python 3.8 & pip3.
- Clone the repo `git clone https://github.com/tum-fml/loco`
- Download the dataset manually or use the provided [script]('utils/download.sh')
- Unzip annotation files
- Install the dependencies `pip3 install -r requirements.txt`
- Spin up [Jupyter Lab](https://jupyter.org/) and run the demo notebook.

## Dataset
### Data
The annotated dataset can be downloaded [here](https://go.mytum.de/239870). Furthermore, we also provide additional data (not annotated) [here](http://go.mytum.de/928009).
### Annotations 
Annotations are stored in [COCO format](https://cocodataset.org/#format-data) under `annotations/loco-all-v2.json`. For ease of use, we also provide seperate annotation files for train and validation set. 

## Credits & How to cite
This project would not have been possible without the amazing team including Dimitrij-Marian Holm, Benjamin Molter, Nikolai Ruof and Mubashir Hanif as well as all the hardworking annotators.

The dataset in this repository is maintained by [Christopher Mayershofer](https://mayershofer.com/). 

If you use the dataset contained in this repository for your research, please cite the following publication:
>LOCO: Logistics Objects in Context    
>Mayershofer, C., Holm, D.-M., Molter, B., Fottner, J.     
>IEEE International Conference on Machine Learning and Applications (ICMLA) 2020

## License
The person who associated a work with this deed has dedicated the work to the public domain by waiving all of his or her rights to the work worldwide under copyright law, including all related and neighboring rights, to the extent allowed by law.

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission. See [License](./License) for details.

