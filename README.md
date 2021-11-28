# Cascading Adaptors to Leverage English Data to Improve Performance ofQuestion Answering for Low-Resource Languages

Our  work  contributes  by  evaluat-ing cross-lingual performance in seven languages- Hindi, Arabic, German, Spanish, English, Viet-namese and Simplified Chinese.  Our models areevaluated on the combination of XQuAD(Artetxeet al., 2020) and MLQA(Lewis et al., 2020) datasetswhich  are  similar  to  SQuAD  (Rajpurkar  et  al.,2016) .

This repository contains both links to models at Huggin Face 🤗, and Langauge/Task Adapter in [Task and Language Adapter with all configurations](https://github.com/Bhavik-Ardeshna/Question-Answering-for-Low-Resource-Languages/tree/main/Adapter%20Models).

<br>
<p align="center">
  <img src="https://dl.fbaipublicfiles.com/MLQA/logos.png" alt="Facebook AI Research and UCL NLP"  width="60%"/>
  <br>
</p>
<br>




<br>
<p align="center">
  <img src="https://dl.fbaipublicfiles.com/MLQA/examples.jpg" alt="Two Instances from MLQA"  width="80%"/>
  <br>
  Two Instances from MLQA
</p>
<br>

For more details on how the models were created, please refer to our paper, [Cascading Adaptors to Leverage English Data to Improve Performance ofQuestion Answering for Low-Resource Languages]()

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





[1] Hariom A. Pandya, Bhavik Ardeshna, Dr. Brijesh S. Bhatt [*Cascading Adaptors to Leverage English Data to Improve Performance ofQuestion Answering for Low-Resource Languages*]()

<!-- 
```
@article{lewis2019mlqa,
  title={MLQA: Evaluating Cross-lingual Extractive Question Answering},
  author={Lewis, Patrick and O\u{g}uz, Barlas and Rinott, Ruty and Riedel, Sebastian and Schwenk, Holger},
  journal={arXiv preprint arXiv:1910.07475},
  year={2019}
}
``` -->

