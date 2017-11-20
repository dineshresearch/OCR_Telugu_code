# CNN based approach to Telugu OCR

<p align="center">
  <img src="example.png">
</p>

Here the code for CNN based approach to Telugu OCR paper is avalilable.

Tested on 64 bit Linux.

## Usage
```bash
git clone https://github.com/GayamTrishal/OCR_Telugu_code.git
cd OCR_Telugu_code/vattu_gunintam/ours/
unzip model_v_g_weights.hdf5.zip
cd ../../..
cd OCR_Telugu_code/code
python OCR.py
```

## Training 
### Main Character
- Set file name training_testing/main_character/model_code.py, h5_file_location = 'YOURPATH/final_dataset.hdf5'
```bash
cd OCR_Telugu_code/training_testing/main_character
python model_code.py
```

### Vattu Gunintam
- Set file name in training_testing/vattu_gunintam/model_code.py, h5_file_location = 'YOURPATH/final_dataset.hdf5'
```bash
cd OCR_Telugu_code/training_testing/vattu_gunintam
python model_code.py
```

## Trained Models
Information on trained models can be found [here](https://github.com/GayamTrishal/OCR_Telugu_code/tree/master/models).

## Requirements
- Keras
- OpenCV 3.0.0 version (currently only supports this.)
- Skimage
- Numpy
