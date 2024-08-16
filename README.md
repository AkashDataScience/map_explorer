[![LinkedIn][linkedin-shield]][linkedin-url]

## :jigsaw: Objective

- Create a new map of some other city for the code shared above
- Add a DNN with 1 more FC layer.
- Your map must have 3 targets A1>A2>A3 and your car/robot/object must target these alternatively. 
- Train your best model upload a video on YouTube and share the URL

## Prerequisites
* [![Python][Python.py]][python-url]
* [![Pytorch][PyTorch.tensor]][torch-url]

## :open_file_folder: Files
- [**ai.py**](ai.py)
    - This file contains class for model and dqn
- [**map.py**](map.py)
    - This is the main file of this project
    - It uses function available in `ai.py`
    - It contains functions to move object, calculate reward and display.

## Installation

1. Clone the repo
```
git clone https://github.com/AkashDataScience/map_explorer
```
2. Go inside folder
```
 cd map_explorer
```
3. Install dependencies
```
pip install -r requirements.txt
```

## Training

```
# Start exploring with:
python map.py

```

## :video_camera: Demo
[Exploring SVNIT campus using Reinforcement Learning](https://www.youtube.com/watch?v=CnlHAsDeTIo)

## Contact

Akash Shah - akashmshah19@gmail.com  
Project Link - [ERA V2](https://github.com/AkashDataScience/ERA-V2/tree/master)


[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/akash-m-shah/
[Python.py]:https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[python-url]: https://www.python.org/
[PyTorch.tensor]: https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white
[torch-url]: https://pytorch.org/
[HuggingFace.transformers]: https://img.shields.io/badge/%F0%9F%A4%97-Hugging%20Face-orange
[huggingface-url]: https://huggingface.co/