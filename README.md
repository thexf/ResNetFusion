# Infrared and visible image fusion via detail preserving adversarial learning

## 环境配置

```
# 创建conda环境
conda env create -f environment.yml
```

## 数据

数据已经处理成模型需要的格式存在 `data` 文件夹中

## 训练

```
# 如果想设置训练轮数则要加上 `--num_epochs` 参数，默认4000轮
python3 train.py --num_epochs 4000
```

- 训练过程保存在 `result/training_results/SRF_1/`

- 训练完成后，模型权重保存在 `result/epochs/`


## 测试

```
python3 image_test.py
```

- 测试结果保存在 `result/test_resultss/SRF_1/`
