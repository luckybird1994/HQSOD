## Code for ACCV2020 submission100
## Update in 2020/08/29!

## SOC results
saliency maps of SOC can be downloaded at: [Google](https://drive.google.com/file/d/1ArD6OEQiwXL7svVfIMeU0RWAekbhqLan/view?usp=sharing)
![Aaron Swartz](https://github.com/ACCV2020Submission100/code/blob/master/Fig/Fig2.png)


## More comparison experiments
Becasuse the limit of rebutal, we add fully comparison experiment with F3N and MINet in Gibhub.
![Aaron Swartz](https://github.com/ACCV2020Submission100/code/blob/master/Fig/Fig1.png)




## Prerequisites
- [Python 3.6](https://www.python.org/)
- [Pytorch 1.1 or 1.3](http://pytorch.org/)
- [OpenCV 4.0](https://opencv.org/)
- [Numpy 1.15](https://numpy.org/)

## Clone repository
```shell
https://github.com/ACCV2020Submission100/code.git
cd code/classnet/
```

## Download dataset

Download the following datasets, and unzip images into `data/val/imgs` folder, groundtruths
to `data/val/gts` folder.

- [PASCAL-S](http://cbi.gatech.edu/salobj/)
- [ECSSD](http://www.cse.cuhk.edu.hk/leojia/projects/hsaliency/dataset.html)
- [HKU-IS](https://i.cs.hku.hk/~gbli/deep_saliency.html)
- [DUT-OMRON](http://saliencydetection.net/dut-omron/)
- [DUTS](http://saliencydetection.net/duts/)

## Download model
- please download the [model](https://drive.google.com/file/d/1d18GHNeaR_Hg91LlNJQNL_HNkyoW-5qs/view?usp=sharing), then put it into `model` folder.

## Testing

```shell
    python main.py
```
- After testing, saliency maps of `PASCAL-S`, `ECSSD`, `HKU-IS`, `DUT-OMRON`, `DUTS-TE` will be saved in `salmap/` folder.

## Saliency maps 
- saliency maps: [Google](https://drive.google.com/file/d/1onVgaG-5GUuudLGMGOuscV6iiOFg3O6e/view?usp=sharing)

## Evaluation
- To evaluate the performace of our network, please use MATLAB to run `main.m`
```shell
    cd code/eval
    matlab
    main.m
```

## Contact
- If you have any problems in running the code or downloading models and saliency maps, please ask a question in `Issues`.
we will reply as soon as possible!
