# Residual Energy-Based Models for Text Generation

This repo implements the Residual Energy-Based Model as described in [Residual Energy-Based Models for Text Generation](https://openreview.net/pdf?id=B1l4SgHKDH). Note that both data and model (generator+discriminator) are different from the original paper: the goal is just to show how the pipeline works, using much less computational resources.

The training and evaluation scripts can be found in [REBM.ipynb](REBM.ipynb). We suggest opening it using Google Colab with a GPU instance.

## Citation

```
@inproceedings{deng2019residual,
  title={Residual Energy-Based Models for Text Generation},
  author={Deng, Yuntian and Bakhtin, Anton and Ott, Myle and Szlam, Arthur and Ranzato, Marc'Aurelio},
  booktitle={International Conference on Learning Representations},
  year={2019}
}

@article{bakhtin2021residual,
  title={Residual Energy-Based Models for Text},
  author={Bakhtin, Anton and Deng, Yuntian and Gross, Sam and Ott, Myle and Ranzato, Marc'Aurelio and Szlam, Arthur},
  journal={Journal of Machine Learning Research},
  volume={22},
  number={40},
  pages={1--41},
  year={2021}
}
```
