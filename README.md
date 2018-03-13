# Dynet tutorials

[Dynet](https://github.com/clab/dynet) is an automatic differentiation toolkit used mainly to train neural networks. 

This repository contains a few tutorials in the form of jupyter notebooks to get familiar with dynet's API and workflow through simple and (hopefully) fun examples not necessarily related to machine learning.

## Notebooks

1. [Approximating `sqrt(2)` with gradient descent](notebooks/1-sqrt_2.ipynb): basic workflow and objects
2. [Visualizing the Mandelbrot fractal](notebooks/2-mandebrot.ipynb): example of simple operations
3. [Visualizing the Barnsley fern fractal](notebooks/3-Barnley_fern.ipynb): affine transforms, gumbel trick

This list will be updated as I add notebooks

## Installing dynet

You should be able to install the latest version of dynet by running

```bash
pip install git+https://github.com/clab/dynet#egg=dynet
```
on unix systems. Alternatively you might want to perform a manual install (see the [related documentation](http://dynet.readthedocs.io/en/latest/python.html#manual-installation)).

## Documentation

For a more exhaustive overview of the dynet API please refer to the [official documentation](http://dynet.readthedocs.io/en/latest/index.html). In particular you might be interested in the [python API](http://dynet.readthedocs.io/en/latest/python_ref.html) and the various [examples](http://dynet.readthedocs.io/en/latest/examples.html) there.

## License

This repository is under the [MIT](LICENSE) license (so basically you can use the code for anything you want). If you end up using dynet in one of your research projects, please consider citing the relevant publication:

```
@article{dynet,
  title={DyNet: The Dynamic Neural Network Toolkit},
  author={Graham Neubig and Chris Dyer and Yoav Goldberg and Austin Matthews and Waleed Ammar and Antonios Anastasopoulos and Miguel Ballesteros and David Chiang and Daniel Clothiaux and Trevor Cohn and Kevin Duh and Manaal Faruqui and Cynthia Gan and Dan Garrette and Yangfeng Ji and Lingpeng Kong and Adhiguna Kuncoro and Gaurav Kumar and Chaitanya Malaviya and Paul Michel and Yusuke Oda and Matthew Richardson and Naomi Saphra and Swabha Swayamdipta and Pengcheng Yin},
  journal={arXiv preprint arXiv:1701.03980},
  year={2017}
}
```
