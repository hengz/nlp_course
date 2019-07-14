# 作业01-基础理论

0. Can you come up out 3 sceneraies which use AI methods?

    Ans: 
   - 自动驾驶
   - 语音识别
   - 人机对话

1. How do we use Github; Why do we use Jupyter and Pycharm;

    Ans:

   - 通过使用Github进行统一代码管理，课程Github进行作业和相关资料发布，个人Github进行作业提交
   - 使用Jupyter进行简单演示代码开发。Pycharm进行工程性项目开发。

2. What's the Probability Model?
    Ans: 概率模型是指能够输出文本概率的模型，通过概率，判断文本的合理程度。

3. Can you came up with some sceneraies at which we could use Probability Model?
    Ans: 比如人机对话，机器通过选择概率最高的生成语言进行回复，使得机器人的语言表达更加逼真，也更加符合情理。

4. Why do we use probability and what's the difficult points for programming based on parsing and pattern match?
    Ans: 因为概率模型和语义分析相比，计算量更小。

5. What's the Language Model;
    Ans: 语言模型是指通过计算，能将自然语言文本转化为向量或者概率。

6. Can you came up with some sceneraies at which we could use Language Model?
    Ans: 比如相似文本匹配，需要使用语言模型将文本进行转换，然后将转换得到的结果比如向量进行计算，来得到文本的相似度。

7. What's the 1-gram language model;
    Ans: 1-gram语言模型是指计算当前词临近的1个词的概率模型。
    公式为：$P(w_1w_2)=P(w_1)*P(w_1|w_2)$

8. What's the disadvantages and advantages of 1-gram language model;
    Ans: 1-gram语言模型的优势是计算较为简单，缺点是只考虑了临近的一个词，会丢失较多语义，导致模型判断出的结果不够准确。

9. What't the 2-gram models;
    Ans: 2-gram模型是指计算当前词临近的2个词的概率模型。
    公式为：$P(w_1w_2w_3)=P(w_1|w_2w_3w_4)*P(w_1|w_2w_3)*P(w_2|w_3w_4)*P(w_3|w_4)$
