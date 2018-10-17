# The Region-based CNN (R-CNN)

## What's the purpose?
R-CNNについてのあれこれを学ぶ(共同研究等への転用も視野に入れる)

## What's R_CNN??
入力画像内で, 物体の検出を行う機械学習手法の一つ. 物体の候補領域を抽出後, それぞれの領域にCNNを適用して特徴量を抽出する.

## How difference among several type of R_CNN?

- R-CNN ... ベーシックなR-CNN
- Faster R-CNN ... RolPoolingを適用したR-CNN
- Mask R-CNN ... RolAlignを適用し, mask headを取り付けた

## Reference

### 理論
[R-CNN原論](https://arxiv.org/pdf/1311.2524.pdf)  
[Fast R-CNN](https://arxiv.org/pdf/1504.08083.pdf)  
[Faster R-CNN](https://arxiv.org/pdf/1506.01497.pdf)  
[Mask R-CNN](https://arxiv.org/pdf/1703.06870.pdf)

### 実装
[Mask R-CNN(Keras)](https://github.com/shtamura/maskrcnn)
