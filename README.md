# Circuit4ML
# Digital Circuits Design For Machine Learning
## 개인 연구 정리를 위한 사이트입니다.

1. Read: Designing Energy-Efficient Convolutional Neural Networks using Energy-Aware Pruning
         Tien-Ju Yang, Yu-Hsin Chen, Vivienne Sze

기존에 prunning을 통해서 memory 및 연산의 양을 크게 줄이고 있으나, 이러한 최적화가 직접적으로 energy reduction으로 유도되지 않을 수 있다.
따라서, energy reduction을 고려한 prunning이 필요하다.

기존의 magnitude 많을 고려하여 prunning 하는 것은 문제가 있음.

>To sparsify the filters without impacting the accuracy, the simplest method is pruning weights with magnitudes smaller than a threshold, which is referred to as magnitudebased pruning [6–10]. The advantage of this approach is that it is fast, and works well when a few weights are removed, and thus the correlation between weights only has a minor impact on the output. However, as more weights are pruned, this method introduces a large output error as the correlation between weights becomes more critical. For example, if most of the small-magnitude weights are negative, **the output error will become large once many of these small negative weights are removed using the magnitude-based pruning**. In this case, it would be desirable to remove a large positive weight to compensate for the introduced error instead of removing more smaller negative weights.

이부분은 좀 의외이다. magnitude 방식의 prunning이 단순 threshold 값을 가지고 이루어지다...


  - 생각해볼 것.
    - Energy-Aware Pruning.
         
         





