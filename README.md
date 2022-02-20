# Bench Mark Testing

A Machine Learning model to test the GPU and CPU benchmark

## Language & OS
1. **Python 3.9.1**
2. **Windows 10 home**
## GPU Support
Please check [Tensorflow](https://www.tensorflow.org/install/) official website to get the correct\
version of [CUDA](https://developer.nvidia.com/cuda-toolkit-archive) & [cuDNN](https://developer.nvidia.com/cudnn) to avoid mismatch with your tensorflow version


## Modules
1. [Numpy](https://numpy.org/)
2. [Tensorflow](https://docs.opencv.org/4.5.5/)
3. [Keras]()
4. [Pickle]()
## Installtion
Just run the below command which installs all the necessary python modules you will need 
```bash
pip install -r requirement.txt
```

## Execution
Run the ```Getting_dataset``` which will generate two ```pickle``` files one is for training another is for testing
```bash
python Getting_Dataset.ipynb
```
```bash
python benchmark.ipynb
```


## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)