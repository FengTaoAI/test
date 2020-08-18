# Paper Title

This repo is the official implementation for our paper: Paper Title Paper Title Paper Title. [[Paper]](https://github.com/FengTaoAI/test/) <br>

![image](https://github.com/Fonnn/test/blob/master/images/test_image0.png)

The repo is still under construction, current version provides, 

* Trained models <br>
* The full test and inference <br>
* Visualization code <br>

### Dependencies

This code is tested on a Ubuntu 16.04 machine with a GTX 2080Ti GPU, with the following dependencies,

* Python 3.7 <br>
* PyTorch=1.3.0 <br>
* astropy=4.0 <br>
* matplotlib, numpy <br>

This repo may be able to be used in the CPU environment, but the inference is relatively slow

### Training/Testing Split

* The folder ```./input``` are testing set
* The folder ```./target``` are ground truth for visualization
* All others are training set
* No subject appears in both training and testing set. They are completely seperate

### Usage

Testing on XXX dataset using model,run

```
python demo.py
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
