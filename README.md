# DeepFake Classification

This repository was based on the [FaceForensics++ dataset](https://github.com/ondyari/FaceForensics). Besides the full image models, all models were trained on slightly enlarged face crops with a scale factor of 1.3.

You can find my trained models under [this link](https://drive.google.com/drive/folders/1TvNujQ8Aar-j4hF1HyOqXKucULjMsi3C?usp=sharing).   

Setup:
- Install required modules via `requirement.txt` file
- Run detection from a single video file or folder with:

```shell
python detect_from_video.py
-i <path to input video or folder of videos with extenstion '.mp4' or '.avi'>
-m <path to model file, default is imagenet model
-o <path to output folder, will contain output video(s)
```  
from the classification folder. Enable cuda with ```--cuda```  or see parameters with ```python detect_from_video.py -h```.


# Requirements

- python 3.7
- requirements.txt
