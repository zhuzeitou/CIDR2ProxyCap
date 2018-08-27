# CIDR-Parser
将CIDR列表转换为ProxyCap或Proxifier配置文件片段，包含[CIDR2ProxyCap](#cidr2proxycap)和[CIDR2Proxifier](#cidr2proxifier)两部分

# CIDR2ProxyCap
将CIDR列表转换为ProxyCap配置文件片段

使用方法：
`CIDR2ProxyCap <input path> <output path>`

输入文件为CIDR列表，如[cn-aggregated.zone](http://www.ipdeny.com/ipblocks/data/aggregated/cn-aggregated.zone)，转换为ProxyCap配置文件片段写入输出路径

配合[xml2prs102.zip](http://www.proxycap.com/download/xml2prs102.zip)，将xml转换为prs后导入ProxyCap中使用

# CIDR2Proxifier
将CIDR列表转换为Proxifier配置文件片段

使用方法：
`CIDR2Proxifier <input path> <output path>`

输入文件为CIDR列表，如[cn-aggregated.zone](http://www.ipdeny.com/ipblocks/data/aggregated/cn-aggregated.zone)，转换为Proxifier配置文件片段写入输出路径
