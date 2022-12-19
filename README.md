# Positional-encoding Image Prior (PIP)

## [Project page](https://nimrodshabtay.github.io/PIP/)

Code for more tasks will be added soon

## Installation
-------------
We tested the demo with Python 3.6
For installation please run
```
pip install -r requirements.txt
```

## Denoising example
------------------
Run
```
python3 denoising.py
```
or for running on your own image
```
python3 denoising.py --input_img_path <path/to/your/image>
```
The output will be saved in the root directory as `<filename>_denoising_fixed_ff.png`

## SR example
------------------
Run
```
python3 SR.py
```
or for running on your own image
```
python3 SR.py --input_img_path <path/to/your/image>
```
The output will be saved in the root directory as ```<filename>_sr_learned_ff.png```

## Inpainting example
------------------
Run
```
python3 Inpainting.py
```
or for running on your own image
```
python3 Inpainting.py --input_img_path <path/to/your/image>
```
The output will be saved in the root directory as ```<filename>_inpainting_learned_ff.png```

## Video Denoising example
------------------
Run
```
python3  denoising_video.py --input_vid_path <path/to/your/video>
```
The outputs will be saved in the `output` directory ```<filename>/*.png``` for images and ```<filename>/psnr.csv``` for psnr (gt) evaluation values.
##
If you find our work useful in your research or publication, please cite it:
```
@article{shabtay2022pip,
  title={PIP: Positional-encoding Image Prior},
  author={Shabtay, Nimrod and Schwartz, Eli and Giryes, Raja},
  journal={arXiv preprint arXiv:2211.14298},
  year={2022}
}
```
