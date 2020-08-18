# 论文题目

This repository provides code and trained models for our paper [[Link]](https://github.com/FengTaoAI/test/) <br>

![baidu](https://github.com/Fonnn/test/blob/master/images/test_image1.png)

Current version provides:  
* Trained models <br>
* Test dataset <br>
* Visualization code <br>

### Dependencies

This code is tested on a Ubuntu 16.04 machine with a GTX 2080Ti GPU, with the following dependencies,

* Python 3.7 <br>
* PyTorch=1.3.0 <br>
* astropy=4.0 <br>
* matplotlib, numpy <br>

Install enviroment by running:

```
bash requirements.sh
```

### Training/Testing Split

* The folder ```./input``` are testing set
* All others are training set
* No subject appears in both training and testing set. They are completely seperate

### Training and Testing

Testing on XXX dataset using model,run

```
python XXX.py
```

We use XXX dataset to train,run

```
python XXX.py
```

## Citation

Please cite our paper if you find anything helpful,please cite with:

```
@article{XXXXXX,
  title={论文题目},
  author={XXX XXX, XXX XX, XXX X and XXXX XXXX},
  journal={XXXX},
  volume={XXXX},
  year={XXXX}
}
```

## License

This project is licensed under the XXX License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
