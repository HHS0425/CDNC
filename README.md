# CDNC

## Setup:
```
cd CDNC/
conda env create -f conda_requirements.yml
```
## Inference:
### Inference on PHOENIX2014 
```
python main.py --features_path {FEATURES_PATH} --info_file_path {INFO_FILE_PATH} --pelt_model l2 --initial_pen 20 --beta 2 --setname eval
```
