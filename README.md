# Deep Metric Learning

The deep metri learning project for 2020 Summer Intern in Nokia Bell Labs, advised by Dr. Fangzhe Chang.

## Acknowledgement
This repo mainly borrows the architecture design and codes from [classification_metric_learning](https://github.com/azgo14/classification_metric_learning).

We also refer to the codes in [Deep_Metric](https://github.com/bnu-wangxun/Deep_Metric).

## To Do
 - [ ] Rebuild code structure
 - [ ] Multi-GPU
 - [ ] Half precision/ mix precision training.
 - [ ] DALI for Data procecssing
 - [ ] Enclose more losses as a module, like triplet, contrastive ...
 - [ ] Sampling schems as a module
 - [ ] New logger system
 - [ ] Backbone as a module
 - [ ] Object detection 
 
 
## Results

Backbone: pretrained Resnet50; dim: 2048; epochs: 30;

### CUB_200_2011

| Recall@1 | Recall@2 | Recall@4 | Recall@8 | Download|
|----------|----------|----------|----------|---------|
|   60.45  |   71.51  | 81.33    |  88.66   |[[model]](https://drive.google.com/file/d/1bHqmQoNexenoSH92N3Wn0XCdjGWIxnZS/view?usp=sharing) [[log]](https://drive.google.com/file/d/10PXhTzZY-9MvnuiL-hfOwI7MgHSDMk-C/view?usp=sharing)|


### Stanford Online Products

| Recall@1 | Recall@10 | Recall@100 | Recall@1000 | Download|
|----------|----------|----------|----------|---------|
|   79.33  |   91.38  | 96.58    |  98.92   |[[model]](https://drive.google.com/file/d/1EMMFj56G74QJneqYEgnHdhcm7Z0NvK6v/view?usp=sharing) [[log]](https://drive.google.com/file/d/1dvAF8baGyZn2Gu4xd00-AJ5iWZhhY0XA/view?usp=sharing)|


## Progress
More results and codes reconstruction are in progress.
