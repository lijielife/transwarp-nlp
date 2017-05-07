# transwarp-nlp

深度自然语言处理工具

## 功能实现

- 中文分词(CRF 和 BILSTM + CRF)
- 中文序列化标注(LSTM或BILSTM)
- 中文命名实体识别(LSTM或BILSTM)
- 中文关键词抽取（实现中）
- 中文文本自动摘要(SEQ2SEQ ATTENTION)
- 情感分析(MEMORY NETWORK)
- 依存句法分析
- 中文文本分类(CNN和LSTM)
- 中文多标签文本分类（实现中）
- 中文自由写诗（实现中）
- 中文对话系统（实现中）
- 中文问答系统（实现中）
- 中英机器翻译（实现中）

## 依赖库

* python2.7
* tensorflow (>= r1.0)
* numpy
* pandas
* matplotlib
* pygtrie
* future
* cPickle

## 参考 

* [Aspect Level Sentiment Classification with Deep Memory Network](https://arxiv.org/abs/1605.08900) `paper`
* [Memory Network](https://arxiv.org/pdf/1410.3916.pdf) `paper`
* https://github.com/tensorflow/models/tree/master/tutorials/rnn/ptb  `code`
* https://github.com/tensorflow/models/tree/master/textsum `code`
* https://github.com/tensorflow/tensorflow/blob/master/tensorflow/contrib/legacy_seq2seq/python/ops/seq2seq.py `code`
* https://github.com/qhduan/Seq2Seq_Chatbot_QA `code`
* https://github.com/jinfagang/tensorflow_poems `code`
* https://github.com/ganeshjawahar/mem_absa `code`
* https://github.com/koth/kcws `code`
* https://github.com/rockingdingo/deepnlp `code`
* https://github.com/LambdaWx/CNN_sentence_tensorflow `code`

## LICENSE

MIT
