# π decimal digits / π 小数位数

English | 中文

## What this is / 内容说明

Decimal digits of π **after the decimal point** (no leading `3.`).  
π 小数点后的数字（不含整数位 `3.`）。

Computed with the **Chudnovsky** algorithm and cross-checked.  
使用 **Chudnovsky** 算法计算，并经过交叉校验。

## File format / 文件格式

- One file per **100,000** digits. / 每 **十万位** 一个文件。
- Each file contains **raw digit characters only** (no spaces, no newlines). / 每个文件仅含数字字符（无空格、无换行）。
- Naming: `digits_SSSSSSS-EEEEEEE.txt` — 7-digit zero-padded inclusive start and end positions after the decimal point.  
  命名：`digits_SSSSSSS-EEEEEEE.txt` — 小数点后起止位置，7 位零填充（含首尾）。

Examples / 示例:

| File | Digits |
|------|--------|
| `digits_0000001-0100000.txt` | 1st – 100,000th |
| `digits_0100001-0200000.txt` | 100,001st – 200,000th |
| `digits_0900001-1000000.txt` | 900,001st – 1,000,000th |

## Progress / 进度

See `progress.txt` for the total number of digits currently committed.  
当前已提交的总位数见 `progress.txt`。

New complete 100,000-digit blocks are **appended** as more digits are computed.  
随着计算推进，完整的十万位块会陆续追加。

## Local clone path (automation) / 本机克隆路径

On the compute box, the working clone is `/workspace/pi-repo`.  
计算环境中的工作克隆目录为 `/workspace/pi-repo`。
