# 评测代码使用说明

## 介绍

本评测代码用于评估 MMIVQA 比赛的三个任务，分别是 Task 1: mTAGSV, Task 2: mVCR 和 Task 3: mTAGVC。请确保在提交评测文件时与示例文件格式一致。

## 使用方法

### 参数说明

- `--task`: 任务编号 (1, 2 或 3)
- `--pred_file`: 预测结果文件路径
- `--target_file`: 标准答案文件路径

### 运行示例

#### 评测 Task 1

```bash
python eval.py --task 1 --pred_file path/to/pred.json --target_file path/to/target.json
```

#### 评测 Task 2

```bash
python eval.py --task 2 --pred_file path/to/pred.json --target_file path/to/target.json
```

#### 评测 Task 3

```bash
python eval.py --task 3 --pred_file path/to/pred.json --target_file path/to/target.json
```

### 输出结果

根据不同任务的评测，输出不同的指标：

#### Task 1

```text
R@1,IoU=0.3: xx.xx
R@1,IoU=0.5: xx.xx
R@1,IoU=0.7: xx.xx
mIoU: xx.xx
```

#### Task 2

```text
R1: xx.xx
R10: xx.xx
R50: xx.xx
MRR: xx.xx
```

#### Task 3

```text
R1: xx.xx
R10: xx.xx
R50: xx.xx
Avg: xx.xx
```

## 注意事项

请确保提交的预测文件格式与示例文件格式一致，示例文件分别为：

- Task 1: `MMIVQA_TEST_TASK1_sample.json`
- Task 2: `MMIVQA_TEST_TASK2_sample.json`
- Task 3: `MMIVQA_TEST_TASK3_sample.json`

祝你在 MMIVQA 比赛中取得好成绩！🏆
