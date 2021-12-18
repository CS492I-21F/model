# model
> Training codes and pre-trained models used in the project

[![GitHub Super-Linter](https://github.com/CS492I-21F/model/workflows/Lint/badge.svg)](https://github.com/marketplace/actions/super-linter)


## Project Information
* Topic: Korean local dialects to standard language machine translation model
  * Final Presentation: [PDF](https://drive.google.com/file/d/1bFfAXERQBlN82GLXLIlQhL07AeB0M3uZ/view?usp=sharing)
  * Final Report: TBA

* Team 43
  * 20140330 Seokchan Ahn
  * 20190581 Mingeun Jung
  * 20215011 Hyebin Kang

## How to Run
* Use [Google's Colab](https://colab.research.google.com/)
> All code is guaranteed to run in the latest Google Colab environment. (As of December 19, 2021)

## Classification

### Training Codes

* `single.ipynb`: classifies into standard language and 5 regional dialects

* `multi_standard.ipynb`: classifies whether or not it is a standard language, a.k.a binary classification

* `multi_dialects.ipynb`: classifies into standard language and 5 regional dialects
  * NOTE: The input to this model is sentences classified as non-standard language by the `multi_standard` model

### Pre-trained Models
> Each `.pt` file is a pre-trained model of a model with the same name

* `single.pt`: [link](https://drive.google.com/file/d/1-TGjLEVx6bgRhAaKGMI9ajQvZjBAWccm/view?usp=sharing)

* `multi_standard.pt`: [link](https://drive.google.com/file/d/1-64VFX8QTXRKVSOCJlZ2HaUVPmwF8ZQ7/view?usp=sharing)

* `multi_dialects.pt`: [link](https://drive.google.com/file/d/1-IxZ-oESM6t70Y-wwF_uYsBSjbga_6_F/view?usp=sharing)
