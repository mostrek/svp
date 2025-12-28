# SVP — Stable Video Portraits

Mirela Ostrek and Justus Thies  

Published at **European Conference on Computer Vision (ECCV) 2024**, Milan, Italy.

Official project page: https://svp.is.tue.mpg.de/

---

## 📌 Overview

SVP (Stable Video Portraits) is a hybrid 2D/3D generative method for producing photorealistic videos of talking faces.
It combines advances in 2D text-to-image generative AI with 3D face reconstruction (3D Morphable Models, 3DMM) to generate temporally smooth and controllable video portraits.

Key features include:

Person-specific fine-tuning of a general 2D stable diffusion model

3DMM-based temporal conditioning to lift 2D image generation to video

A temporal denoising procedure to ensure smooth motion across frames

Editable facial appearance, allowing morphing to text-defined celebrities without additional test-time fine-tuning

The result is a high-quality, temporally consistent person-specific avatar controllable via 3DMM parameters. SVP outperforms prior monocular head avatar methods in both quantitative and qualitative evaluations.

This repository contains the code, models, and scripts used for training and evaluation.

---

## Contents
- WIP -


## Data
- WIP -


## Training
- WIP -


## Inference
- WIP -


## License
This code is provided for non-commercial scientific research use only. See the official [LICENSE](https://svp.is.tue.mpg.de/license.html) for details.


## Contact
For questions, please open an issue on GitHub or reach out to the authors.


## Citation
If you use this code or dataset, please cite our paper:


```bibtex
@inproceedings{svp,
  title = {Stable Video Portraits},
  author = {Ostrek, Mirela and Thies, Justus},
  booktitle = {European Conference on Computer Vision (ECCV) 2024},
  month = {October},
  year = {2024}
}

