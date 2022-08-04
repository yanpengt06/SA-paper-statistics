# SA-paper-statistics

## 仓库目录

│  generate_paper_list_with_arxiv_link.ipynb
│  README.md
│  word-cloud.ipynb
│
├─data
│      file_to_read.bib
│
├─figure
│      output_img.png
│
└─output
        output.txt

## 仓库说明

代码主要功能：

1. 从bib文件中抽取各会议paper标题（已完成18-22EMNLP,NAACL,ACL,COLING main, long, short, findings抽取）
2. 对标题做Sentiment Analysis领域相关工作的过滤
3. 统计SA领域近五年关键词频率分布，据此绘制word-cloud图
4. 用前一年的逆词频进行加权，调整词频分布，以体现新研究方向，绘制word-cloud图

## 鸣谢

主要参考roomylee's [nlp-papers-with-arxiv](https://github.com/roomylee/nlp-papers-with-arxiv)
