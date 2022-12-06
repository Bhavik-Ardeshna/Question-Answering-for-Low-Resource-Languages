# Cascading Adaptors to Leverage English Data to Improve Performance of Question Answering for Low-Resource Languages

Our  work  contributes  by  evaluat-ing cross-lingual performance in seven languages- Hindi, Arabic, German, Spanish, English, Viet-namese and Simplified Chinese.  Our models areevaluated on the combination of XQuAD and datasets which  are  similar  to  SQuAD.

For more details on how the models were created, please refer to our paper, [Cascading Adaptors to Leverage English Data to Improve Performance ofQuestion Answering for Low-Resource Languages](https://aclanthology.org/2021.icon-main.66/)

<br>
<p align="center">
  <img src="https://github.com/Bhavik-Ardeshna/Question-Answering-for-Low-Resource-Languages/blob/main/assests/FlowChart.jpeg" alt="FLowchart"  width="80%"/>
</p>
<br>

This repository contains both links to models at Huggin Face 🤗, and Langauge/Task Adapter in [Task and Language Adapter with all configurations](https://github.com/Bhavik-Ardeshna/Question-Answering-for-Low-Resource-Languages/tree/main/Adapter%20Models).

## Fine-Tuned Model at Hugging Face  🤗


| Language     |      mBERT      |  XLM-RoBERTa |
|:----------:|:-------------:|:-------------:|
|  Arabic (ar) | [multilingual-bert-base-cased-arabic](https://huggingface.co/bhavikardeshna/multilingual-bert-base-cased-arabic) | [xlm-roberta-base-arabic](https://huggingface.co/bhavikardeshna/xlm-roberta-base-arabic) |
|  German (de) | [multilingual-bert-base-cased-german](https://huggingface.co/bhavikardeshna/multilingual-bert-base-cased-german) | [xlm-roberta-base-german](https://huggingface.co/bhavikardeshna/xlm-roberta-base-german) |
|  Spanish (es) | [multilingual-bert-base-cased-spanish](https://huggingface.co/bhavikardeshna/multilingual-bert-base-cased-spanish) | [xlm-roberta-base-spanish](https://huggingface.co/bhavikardeshna/xlm-roberta-base-spanish) |
|  Arabic (ar) | [multilingual-bert-base-cased-arabic](https://huggingface.co/bhavikardeshna/multilingual-bert-base-cased-arabic) | [xlm-roberta-base-arabic](https://huggingface.co/bhavikardeshna/xlm-roberta-base-arabic) |
|  Chinese (zh) | [multilingual-bert-base-cased-chinese](https://huggingface.co/bhavikardeshna/multilingual-bert-base-cased-chinese) | [xlm-roberta-base-chinese](https://huggingface.co/bhavikardeshna/xlm-roberta-base-chinese) |
|  Vietnamese (vi) | [multilingual-bert-base-cased-vietnamese](https://huggingface.co/bhavikardeshna/multilingual-bert-base-cased-vietnamese) | [xlm-roberta-base-vietnamese](https://huggingface.co/bhavikardeshna/xlm-roberta-base-vietnamese) |
|  English (en) | [multilingual-bert-base-cased-english](https://huggingface.co/bhavikardeshna/multilingual-bert-base-cased-english) | - |

## Dataset Size

The following table shows how much data is in each language:

Split | en | de | es | ar | zh| vi | hi | 
|:---: |:---:  |:---: | :---: |:---: | :---: | :---: | :---: | 
train    | 12780  | 5707  | 6443   | 6525  |  6327  | 6685   |  6854  |
test   | 1148 | 512 | 500  | 517 |  504 | 511  | 507  |


## Conclusion

We have investigated the efficacy of cascading adapters with transformer models to leverage high-resource language to improve the performance of low-resource languages on the question answering task. We trained four variants of adapter combinations for - Hindi, Arabic, German, Spanish, English, Vietnamese, and Simplified Chinese languages. We demonstrated that by using the transformer model with the multi-task adapters, the performance can be improved for the downstream task. Our results and analysis provide new insights into the generalization abilities of multilingual models for cross-lingual transfer on question answering tasks. 





[1] Hariom A. Pandya, Bhavik Ardeshna, Dr. Brijesh S. Bhatt [*Cascading Adaptors to Leverage English Data to Improve Performance ofQuestion Answering for Low-Resource Languages*](https://aclanthology.org/2021.icon-main.66/)


```
@inproceedings{pandya-etal-2021-cascading,
    title = "Cascading Adaptors to Leverage {E}nglish Data to Improve Performance of Question Answering for Low-Resource Languages",
    author = "Pandya, Hariom  and
      Ardeshna, Bhavik  and
      Bhatt, Brijesh",
    booktitle = "Proceedings of the 18th International Conference on Natural Language Processing (ICON)",
    month = dec,
    year = "2021",
    address = "National Institute of Technology Silchar, Silchar, India",
    publisher = "NLP Association of India (NLPAI)",
    url = "https://aclanthology.org/2021.icon-main.66",
    pages = "544--549",
    abstract = "Transformer based architectures have shown notable results on many down streaming tasks including question answering. The availability of data, on the other hand, impedes obtaining legitimate performance for low-resource languages. In this paper, we investigate the applicability of pre-trained multilingual models to improve the performance of question answering in low-resource languages. We tested four combinations of language and task adapters using multilingual transformer architectures on seven languages similar to MLQA dataset. Additionally, we have also proposed zero-shot transfer learning of low-resource question answering using language and task adapters. We observed that stacking the language and the task adapters improves the multilingual transformer models{'} performance significantly for low-resource languages. Our code and trained models are available at: https://github.com/CALEDIPQALL/",
}
```

