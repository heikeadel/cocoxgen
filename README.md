# COCOXGEN

This repository provides the benchmark dataset COCOXGEN for evaluating image fake detection performance.
COCOXGEN has been presented in the paper "Human vs. AI: A Novel Benchmark and a Comparative Study on the Detection of Generated Images and the Impact of Prompts".

## Usage
The dataset is provided in three different directories, indicating the source of the corresponding images: Real COCO images, images generated with FOOCUS and images generated with SDXL.
The COCO images are not included in the directory due to License reasons but can be extracted from the official COCO dataset using the provided image ids.

In addition, the file prompts.json provides the long and short prompts that were used to generate the fake images. Besides reproducibility aspects, these prompts can be used in the future to extend the set of fake images using additional text-to-image generation models.

## Citation
If you use this dataset, please cite the following paper:

```
@inproceedings{moessner-2024-cocoxgen,
    title = "Human vs. AI: A Novel Benchmark and a Comparative Study on the
Detection of Generated Images and the Impact of Prompts",
    author = "Moe{\ss}ner, Philipp and Adel, Heike",
    booktitle = "Proceedings of the Workshop on Detecting AI Generated Content @ COLING 2025",
    month = january,
    year = "2025",
    address = "Abu Dhabi, UAE"
}
```
