# ogbl

## Requirements
```
Python==3.7
Pytorch==1.8.1+cu101
dgl-cu101==0.8.1
torch-cluster==1.5.9
torch-geometric==2.0.1
torch-scatter==2.0.6
torch-sparse==0.6.12
ogb==1.3.4
```

## Reproduce
```
sh collab.sh
```

## Performance

|  Model   | Test Hits@50 (%) | Validation Hits@50 (%) |
|  ----  | ----  | ----  |
| AGDN | 44.80±5.42 | 45.70±10.15 |
| PLNLP | 70.59±0.29 | 100.00±0.00 |
| GIDN@YITU | 70.96±0.55 | 96.20±0.40 |


## Reference
- https://ogb.stanford.edu/
- https://github.com/skepsun/Adaptive-Graph-Diffusion-Networks/
