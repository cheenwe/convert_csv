# excel 转 csv 工具
批量将目录下 exce文件转换成 csv 格式

-   支持转换 xlsx 和 xls 两种文件类型


## ubuntu 下环境准备:

```sh
sudo apt install ruby2.3-dev  zlib1g-dev libxml2-dev
sudo gem install roo spreadsheet
```

##  测试:

1. git clone https://github.com/cheenwe/convert_csv.git
2. 进入 `convert_csv` 目录,  执行 ./convert
3. 在目录 `csv_result` 能看到转换后的 CSV 文件


## 使用步骤:

1. 删除 `csv_result` 和  `xlsx` 中测试数据
2. 将要转换的文件 复制到 `xlsx` 目录中
3. 执行 ./convert
4. 在目录 `csv_result` 能看到转换后的 CSV 文件
