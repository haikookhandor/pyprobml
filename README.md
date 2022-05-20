# pyprobml

<img src="https://img.shields.io/github/stars/probml/pyprobml?style=social">


Python 3 code to reproduce the figures in the book series [Probabilistic Machine Learning](https://probml.github.io/pml-book/) by Kevin Patrick Murphy.
This is work in progress, so expect rough edges.

See also [probml-utils](https://github.com/probml/probml-utils) for some utility code,
and  [JSL](https://github.com/probml/JSL) for some code for state-space models.) 

## Running the notebooks

The notebooks needed to make all the figures are available at the following locations.

* [Volume 1 figure notebooks](https://github.com/probml/pyprobml/tree/master/notebooks/book1)
* [Volume 2 figure notebooks](https://github.com/probml/pyprobml/tree/master/notebooks/book2). 

Notebooks are saved in chapter-wise folders. For example, a notebook for figure 2.3 from book 1 is saved in the folder `notebooks/book1/02/`.

In addition to the figure notebooks, there are a series of notebooks which provide supplementary material for the book. These are stored in the [`notebooks/misc` folder](https://github.com/probml/pyprobml/tree/master/notebooks/misc).

### Running notebooks in colab

[Colab](https://colab.research.google.com/notebooks/intro.ipynb) has most of the libraries you will need (e.g., scikit-learn,  JAX) pre-installed, and gives you access to a free GPU and TPU. We have a created a 
[colab intro](https://colab.research.google.com/github/probml/pyprobml/blob/master/notebooks/misc/colab_intro.ipynb)
notebook with more details. To run the notebooks on colab in any browser, you can go to a particular notebook on GitHub and change the domain from `github.com` to `githubtocolab.com` as suggeted [here](https://stackoverflow.com/a/67344477/13330701). If you are using Google Chrome browser, you can use ["Open in Colab" Chrome extension](https://chrome.google.com/webstore/detail/open-in-colab/iogfkhleblhcpcekbiedikdehleodpjo) to do the same with a single click.

## Running the noteboks locally 

We assume you have already installed [JAX](https://github.com/google/jax#installation) and
[Tensorflow](https://www.tensorflow.org/install) and [Torch](https://pytorch.org/),
since the details on how to do this depend on whether you have a CPU, GPU, etc.

You can use any of the following options to install the other requirements.

* Option 1

```bash
pip install -r https://raw.githubusercontent.com/probml/pyprobml/master/requirements.txt
```

* Option 2

Download [requirements.txt](https://github.com/probml/pyprobml/blob/master/requirements.txt) locally to your path and run

```bash
pip install -r requirements.txt
```

## GCP, TPUs, and all that

When you want more power or control than colab gives you, you should get a Google Cloud Platform (GCP) account, and get access to a TPU VM. You can then use this as a virtual desktop which you can access via ssh from inside VScode. We have created [a short tutorial on Colab, GCP and TPUs](https://github.com/probml/pyprobml/blob/master/tutorials/colab_gcp_tpu_tutorial.md) with more information.


## How to contribute

See [this guide](https://github.com/probml/pyprobml/blob/master/CONTRIBUTING.md) for how to contribute code. Please follow [these guidelines](https://github.com/probml/pyprobml/blob/master/notebooks/README.md) to contribute new notebooks to the notebooks directory.


## Metrics

[![Stargazers over time](https://starchart.cc/probml/pyprobml.svg)](https://starchart.cc/probml/pyprobml)

## GSOC 

For a summary of some of the contributions to this codebase during Google Summer of Code (GSOC) 2021,
see [this link](https://probml.github.io/pml-book/gsoc2021.html).
Stay tuned for GSOC 2022.





<h2><a id="acknowledgements"></a>Acknowledgements</h2>

I would like to thank the following people for contributing to the code
(list autogenerated from [this script](internal/contributors/contributors.py) with [this configuration](internal/contributors/contributors.toml)):

|  <img width="50" alt="image" src="https://github.com/Abdelrahman350.png"> | <img width="50" alt="image" src="https://github.com/alenm10.png"> | <img width="50" alt="image" src="https://github.com/always-newbie161.png"> | <img width="50" alt="image" src="https://github.com/AnandShegde.png"> | <img width="50" alt="image" src="https://github.com/andrewnc.png"> | <img width="50" alt="image" src="https://github.com/animesh-007.png"> | <img width="50" alt="image" src="https://github.com/AnkitaKumariJain14.png"> | <img width="50" alt="image" src="https://github.com/ashishpapanai.png"> | <img width="50" alt="image" src="https://github.com/Drishttii.png"> | <img width="50" alt="image" src="https://github.com/Duane321.png"> | <img width="50" alt="image" src="https://github.com/firatoncel.png"> | <img width="50" alt="image" src="https://github.com/Garvit9000c.png"> | <img width="50" alt="image" src="https://github.com/gerdm.png"> | <img width="50" alt="image" src="https://github.com/jdf22.png"> | <img width="50" alt="image" src="https://github.com/karalleyna.png"> | <img width="50" alt="image" src="https://github.com/karm-patel.png"> | <img width="50" alt="image" src="https://github.com/khanshehjad.png"> | <img width="50" alt="image" src="https://github.com/kzymgch.png"> | <img width="50" alt="image" src="https://github.com/mjsML.png"> | <img width="50" alt="image" src="https://github.com/murphyk.png"> | <img width="50" alt="image" src="https://github.com/nalzok.png"> | <img width="50" alt="image" src="https://github.com/nappaillav.png"> | <img width="50" alt="image" src="https://github.com/Neoanarika.png"> | <img width="50" alt="image" src="https://github.com/Nirzu97.png"> | <img width="50" alt="image" src="https://github.com/nitish1295.png"> | <img width="50" alt="image" src="https://github.com/nouranali.png"> | <img width="50" alt="image" src="https://github.com/patel-zeel.png"> | <img width="50" alt="image" src="https://github.com/patrickmineault.png"> | <img width="50" alt="image" src="https://github.com/raymondyeh07.png"> | <img width="50" alt="image" src="https://github.com/rohit-khoiwal-30.png"> | <img width="50" alt="image" src="https://github.com/shivaditya-meduri.png"> | <img width="50" alt="image" src="https://github.com/shobro.png"> | <img width="50" alt="image" src="https://github.com/susnato.png"> | <img width="50" alt="image" src="https://github.com/thvasilo.png"> |
| :------------------------------------------------------------------------:|:-----------------------------------------------------------------:|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------:|:------------------------------------------------------------------:|:---------------------------------------------------------------------:|:----------------------------------------------------------------------------:|:-----------------------------------------------------------------------:|:-------------------------------------------------------------------:|:------------------------------------------------------------------:|:--------------------------------------------------------------------:|:---------------------------------------------------------------------:|:---------------------------------------------------------------:|:---------------------------------------------------------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|:---------------------------------------------------------------:|:-----------------------------------------------------------------:|:----------------------------------------------------------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:-----------------------------------------------------------------:|:--------------------------------------------------------------------:|:-------------------------------------------------------------------:|:--------------------------------------------------------------------:|:-------------------------------------------------------------------------:|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|:----------------------------------------------------------------:|:-----------------------------------------------------------------:|:------------------------------------------------------------------:|
|  [Abdelrahman350](https://github.com/Abdelrahman350)                      | [alenm10](https://github.com/alenm10)                             | [always-newbie161](https://github.com/always-newbie161)                    | [AnandShegde](https://github.com/AnandShegde)                         | [andrewnc](https://github.com/andrewnc)                            | [animesh-007](https://github.com/animesh-007)                         | [AnkitaKumariJain14](https://github.com/AnkitaKumariJain14)                  | [ashishpapanai](https://github.com/ashishpapanai)                       | [Drishttii](https://github.com/Drishttii)                           | [Duane321](https://github.com/Duane321)                            | [firatoncel](https://github.com/firatoncel)                          | [Garvit9000c](https://github.com/Garvit9000c)                         | [gerdm](https://github.com/gerdm)                               | [jdf22](https://github.com/jdf22)                               | [karalleyna](https://github.com/karalleyna)                          | [karm-patel](https://github.com/karm-patel)                          | [khanshehjad](https://github.com/khanshehjad)                         | [kzymgch](https://github.com/kzymgch)                             | [mjsML](https://github.com/mjsML)                               | [murphyk](https://github.com/murphyk)                             | [nalzok](https://github.com/nalzok)                              | [nappaillav](https://github.com/nappaillav)                          | [Neoanarika](https://github.com/Neoanarika)                          | [Nirzu97](https://github.com/Nirzu97)                             | [nitish1295](https://github.com/nitish1295)                          | [nouranali](https://github.com/nouranali)                           | [patel-zeel](https://github.com/patel-zeel)                          | [patrickmineault](https://github.com/patrickmineault)                     | [raymondyeh07](https://github.com/raymondyeh07)                        | [rohit-khoiwal-30](https://github.com/rohit-khoiwal-30)                    | [shivaditya-meduri](https://github.com/shivaditya-meduri)                   | [shobro](https://github.com/shobro)                              | [susnato](https://github.com/susnato)                             | [thvasilo](https://github.com/thvasilo)                            |