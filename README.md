# rime-dict

Rime 输入法词库 - 字典仓库(自动采集更新)


字典简述：

|字典名称|字典类别|
|---|---|
|pinyin.ext|词典主列表文件|
|luna_pinyin|拼音基础库|
|||
|pinyin.counties|行政区划|
|pinyin.films|电影|
|pinyin.hwxnet|现代汉语词典|
|pinyin.soaps|电视剧|
|pinyin.stocks|证券|



数据来源：

$luna\underline{}pinyin$
- - [x] [朙月拼音](https://github.com/rime/rime-luna-pinyin)

$pinyin.counties$
- - [x] [全国行政区划信息查询平台](http://xzqh.mca.gov.cn/map)(县级及以上) - 中华人民共和国民政部
- - [ ] 县级以下

$pinyin.films$
- - [x] ~~[中国电影数据信息网](https://www.zgdypw.cn/) - 国家电影专资办~~(Github Actions 的 IP 段可能被目标服务器的 WAF 拉黑了，短期内可能无法自动采集更新了)

$pinyin.hwxnet$
- - [x] 现代汉语词典 - [汉文学网](https://cd.hwxnet.com/)

$pinyin.soaps$
- - [x] [电视剧电子政务平台](https://dsj.nrta.gov.cn/index.shanty) - 国家广播电影电视总局

$pinyin.stocks$
- - [x] 上海证券交易所 - [SSE](http://www.sse.com.cn/)
- - [x] 深圳证券交易所 - [SZSE](http://www.szse.cn/)
- - [ ] 香港交易所 - [HKEX](https://www.hkex.com.hk/)
- - [ ] 台湾证券交易所 -[TWSE](https://www.twse.com.tw/)
