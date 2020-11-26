# Camouflaged Object Detection, accepted by oral presentation in CVPR-2020.

> Deng-Ping Fan, Ge-Peng Ji, Guolei Sun, Ming-Ming Cheng, Jianbing Shen, Ling Shao.


### 0. :fire: NEWS :fire:
- [2020/11/26] :boom: Updating one bug in main.m file to ensure the max value is less than 1. 
``threshold =  2* mean(sal(:)); -》 threshold = min(2 * mean2(sal), 1);'' 

1. **S**earch and **I**dentification **Net**work (**SINet**)

2. Project Website: http://dpfan.net/Camouflage/

3. Code: https://github.com/DengPingFan/SINet

4. Any question please contact to me: _gepengai.ji@gmail.com_ or open new issue in the GitHub)

5. Evaluation Configuration

    Require: Matlab <br>
    Just Run main.m

# Citation

    @inproceedings{Fan2020Camouflage,
    title={Camouflaged Object Detection},
    author={Fan, Deng-Ping and Ji, Ge-Peng and Sun, Guolei and Cheng, Ming-Ming and Shen, Jianbing and Shao Ling},
    booktitle={IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year={2020}
    }

