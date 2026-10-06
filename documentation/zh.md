<!-- ELUCENIA technical documentation · contagem-absoluta-de-neutrofilos · zh · no clinical/professional/rights approval -->

# 中性粒细胞绝对计数

[条件、来源与许可](https://elucenia.org/zh/tools/contagem-absoluta-de-neutrofilos)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 白细胞总数

`leuco`

/µL · 范围: 10–500000

### 分叶核中性粒细胞

`seg`

% · 范围: 0–100

### 杆状核中性粒细胞（可选）

`bast`

% · 选填 · 范围: 0–100

## 方法版本

ANC：白细胞×(分叶核+杆状核)/100；IDSA更新2010/发表2011背景

## 已记录的公式

中性粒细胞绝对计数 = 白细胞（/µL）×（分叶核中性粒细胞% + 杆状核中性粒细胞%）÷100.

## 限制与适用人群

IDSA 2010/2011参考文献涉及癌症患者化疗所致的发热和中性粒细胞减少，风险分层取决于体征、症状、癌症、治疗和合并疾病。计算所得的绝对计数不能代替该评估。定义中的阈值和单位须核对完整指南；本次阅读的摘要未提供这些内容。

## 参考文献

- [Freifeld AG et al. Clinical practice guideline for the use of antimicrobial agents in neutropenic patients with cancer: 2010 update by the Infectious Diseases Society of America. Clin Infect Dis, 2011.](https://doi.org/10.1093/cid/cir073)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 已记录的结果

以下信息保留该方法对合成示例的输出，不构成独立的临床验证。

### 1

无中性粒细胞减少症

| 结果详情 | |
| --- | --- |
| 中性粒细胞（分叶核 + 杆状核） | 60.0% |


### 2

中度中性粒细胞减少（500至999/µL）

| 结果详情 | |
| --- | --- |
| 中性粒细胞（分叶核 + 杆状核） | 45.0% |


### 3

中度中性粒细胞减少（500至999/µL）

| 结果详情 | |
| --- | --- |
| 中性粒细胞（分叶核 + 杆状核） | 25.0% |


### 4

重度中性粒细胞减少（< 100/µL）

| 结果详情 | |
| --- | --- |
| 中性粒细胞（分叶核 + 杆状核） | 10.0% |

伴有发热（≥ 38,3 °C 或 ≥ 38,0 °C 持续 1 h）时，为发热性中性粒细胞减少症：1小时内经验性抗生素治疗。

