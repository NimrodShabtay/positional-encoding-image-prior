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
The output will be saved in the root directory as ```<filename>_denoising_fixed_ff.png```

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

