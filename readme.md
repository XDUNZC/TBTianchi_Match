# Siamese Networks with resnet18

## requirement
- pytorch
- torchvision
- python3.5+
- python-gflags

See requirements.txt 

## run step
- download dataset trainset_demo
```
git clone https://github.com/brendenlake/omniglot.git
unzip trainset_demo.zip
# setup directory for saving models
mkdir models
```
- train and test by running
```shell
python3 train.py --train_path trainset_demo/train \
                 --test_path  trainset_demo/train \
                 --gpu_ids 1 \
                 --model_path models
```


