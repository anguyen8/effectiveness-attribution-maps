# The effectiveness of feature attribution methods and its correlation with automatic evaluation scores

Official Implementation for the paper [The effectiveness of feature attribution methods and its correlation with automatic evaluation scores (NeurIPS2021)](https://arxiv.org/abs/2105.14944) by [Giang Nguyen](https://giangnguyen2412.github.io/), [Daeyoung Kim](https://www.resl.kaist.ac.kr/members) and [Anh Nguyen](https://anhnguyen.me/).

**NeurIPS**: Video presentation of the paper is [here](https://youtu.be/jpbnX6M4Rxc) | Reviews [(6,6,7,7)](https://openreview.net/forum?id=OKPS9YdZ8Va)

## Dataset
* Images used in Instructions, Training phase and Validation phase of all tested method can be found in `Stimuli_Natural` and`Stimuli_Dog` in [Human_experiments.tar.gz](https://drive.google.com/file/d/1-MWWy0i39vNbz_-vo_Gor_dwt5vGYDaT/view?usp=sharing).
* Datasets (Natural/Adversarial ImageNet + Dog) described in Sec. 2.4.3 [here](https://arxiv.org/pdf/2105.14944.pdf) and their visualizations using the tested methods can be found in `Dataset` and `Visualization` in [Human_experiments.tar.gz](https://drive.google.com/file/d/1-MWWy0i39vNbz_-vo_Gor_dwt5vGYDaT/view?usp=sharing).
* The data collected from online users and expert users via [Gorilla.sc](https://gorilla.sc/) can be found in [here](https://github.com/anguyen8/effectiveness-attribution-maps/tree/main/src/users_data). 
  * The folders `Data` and `Data-v2` were used to generate the statistics reported in Fig. 1b, Fig. 4, Table. A1, A2, A3, A4, A5, A8, A9 in [here](https://arxiv.org/pdf/2105.14944.pdf). Run `ImageNet_analyze_spreadsheet.ipynb` and `Dogs_analyze_spreadsheet.ipynb` to see the statistics.
  * The folder `Expert_Data` was used to generate the statistics reported in Table. 1 in [here](https://arxiv.org/pdf/2105.14944.pdf). Run `Expert_ImageNet_analyze_spreadsheet.ipynb` to see the statistics.

## User interface
- This [video](https://youtu.be/4W1fYdx1-mU) walks you through one entire Gorilla.sc experiment run on a single user. We hope sharing all screens we carefully designed for this study could help future research.

## Citation
If you find our work useful in your research, please consider citing:

```
@article{nguyen2021effectiveness,
  title={The effectiveness of feature attribution methods and its correlation with automatic evaluation scores},
  author={Nguyen, Giang and Kim, Daeyoung and Nguyen, Anh},
  journal={Advances in Neural Information Processing Systems},
  volume={34},
  year={2021}
}
```

## License
[MIT](https://github.com/anguyen8/effectiveness-attribution-maps/blob/main/LICENSE)

