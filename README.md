# Bank-of-China-Exchange-Quotation
公开信息-中国银行-外汇牌价-数据
数据源 中国银行 外汇牌价，开始日期2008.12.16，终止日期2019.12.18
数据格式是用 管道符| 作为 分隔符 的 utf-8字符编码的 csv 文件。
数据列名称 货币名称|现汇买入价|现钞买入价|现汇卖出价|现钞卖出价|中行折算价|发布时间
数据源为空的用0填充。 
du -sm whpj.*
37      whpj.sort.uniq.sort_time.csv.bz2
52      whpj.sort.uniq.sort_time.csv.gz
34      whpj.sort.uniq.sort_time.csv.lz
26      whpj.sort.uniq.sort_time.csv.xz
