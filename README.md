# The effectiveness of feature attribution methods and its correlation with automatic evaluation scores

Official Implementation for the paper [The effectiveness of feature attribution methods and its correlation with automatic evaluation scores (NeurIPS2021)](https://proceedings.neurips.cc/paper/2021/file/de043a5e421240eb846da8effe472ff1-Paper.pdf) by Giang Nguyen, Daeyoung Kim and Anh Nguyen.

The paper presentation can be found [here](https://youtu.be/jpbnX6M4Rxc).

# Dataset

* Images used in Instructions, Training phase and Validation phase of all tested method can be found [here](https://drive.google.com/file/d/1eqF6NJpXyl7UlAiTntbWvgbmR2gP2jBj/view?usp=sharing).
* Datasets (Natural/Adversarial ImageNet + Dog) and visualizations can be found [here](https://drive.google.com/file/d/1573_rsKtO3nP2QCsZNkmamPA3hTaQsJ8/view?usp=sharing).
* The data collected from online users and expert users via [Gorilla.sc](https://gorilla.sc/) can be found in [here](https://github.com/anguyen8/effectiveness-attribution-maps/tree/main/src/users_data). 
  * The folders `Data` and `Data-v2` were used to generate the statistics reported in Fig. 1b, Fig. 4, Table. A1, A2, A3, A4, A5, A8, A9 in [here](https://arxiv.org/pdf/2105.14944.pdf). Run `ImageNet_analyze_spreadsheet.ipynb` and `Dogs_analyze_spreadsheet.ipynb` to see the statistics.
  * The folder `Expert_Data` was used to generate the statistics reported in Table. 1 in [here](https://arxiv.org/pdf/2105.14944.pdf). Run `Expert_ImageNet_analyze_spreadsheet.ipynb` to see the statistics.

# User interface
- This [video](https://youtu.be/4W1fYdx1-mU) is a demo of using the experiment interface used in this paper.

# Citation
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

# License
[MIT](https://github.com/anguyen8/effectiveness-attribution-maps/blob/main/LICENSE)

