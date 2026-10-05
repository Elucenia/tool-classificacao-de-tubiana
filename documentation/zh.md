<!-- ELUCENIA technical documentation · classificacao-de-tubiana · zh · no clinical/professional/rights approval -->

# Tubiana 分级（Dupuytren 病）

[条件、来源与许可](https://elucenia.org/zh/tools/classificacao-de-tubiana)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 掌指关节（MCP）伸展受限

`mcf`

度 · 范围: 0–120

### 近端指间关节（PIP）伸展受限

`ifp`

度 · 范围: 0–130

### 远端指间关节伸展受限（或过伸）

`ifd`

度 · 范围: 0–100

### 是否可触及结节或条索？

`nodulo`

- `0` — 否
- `1` — 是

## 方法版本

Tubiana 1986：总伸展缺失，分级0/N/I–IV，阈值45/90/135度

## 已记录的公式

指列总缺失=MCP+PIP+DIP伸展缺失（DIP过伸也计为缺失）。分期： 0 无病变; N 结节但无挛缩; 1 ≤45°; 2 45–90°; 3 90–135°; 4 \>135°.

## 限制与适用人群

Tubiana 1986分类按指列描述Dupuytren挛缩畸形，并包含拇指、第一指蹼、皮肤及术后僵硬的补充信息。单独的伸直缺损总量不能再现完整评估。所用版本的截点与约定需要核对论文全文。

## 参考文献

- [Tubiana R. Evaluation des déformations dans la maladie de Dupuytren (Evaluation of deformities in Dupuytren disease). Ann Chir Main, 1986.](https://doi.org/10.1016/s0753-9053(86)80043-6)

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
