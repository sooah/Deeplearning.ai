---

layout: post

title: "Introduction to deep learning [Quiz. Course 1 - Week 1]"

---

## Introduction to deep learning

1 ) What dose the analogy "AI is the new electricity" refer to?
- [ ] AI is powering personal devices in our homes and offices, similar to electricity.
- [x] **Similar to electricity starting about 100 years ago, AI is transforming multiple inductries.**
>	AI is transforming many fields from the car inductry to supply-chain

- [ ] Through the "smanrt grid", AI is delivering a new wave of electricity.
- [ ] AI runs on computers and is thus powered by electricity, but it is letting computers do things not possible before.

2 ) Which of these are reasons for Deep Learning recently taking off? (Check the three options that apply.)
- [ ] Neural Networks are a brand new field.
- [x] **We have access to a lot more data.**
>	The digitalization of our society has played a huge role in this.
- [x] **We have acess to a lot more computational power.**
>	The development of hardware, perhaps especially GPU computing, has significantly improved deep learning algorithms' performance.
- [x] **Deep learning has resulted in significantly improvements in important applications such as online advertising, speech recognition, and image recognition.**
>	There were all examples discussed in lecture 3.
	
3 ) Recall this diagram of iterating over different ML ideas. Which of the statements below are true? (Check all that apply.)
![](https://user-images.githubusercontent.com/43035503/48545711-e887ee00-e909-11e8-9815-94c53cbd1dac.png)
- [x] **Being able to try out ideas quickly allows deep learning engineers to iterate more quickly.**
>	as discussed in Lecture 4.
- [x] **Faster computation can help speed up how long a team takes to iterate to a good idea.**
>	as discussed in Lecture 4.
- [ ] It it faster to train on a big dataset than a small dataset.
>	Training on a big dataset is usually slower than training on a small dataset.
- [x] **Recent progress in deep learning algorithms has allowed us to train good models faster(even without changing the CPU/GPU hardware).**

4 ) When an experienced deep learning engineer works on a new problem, they can usually use insight from previous problems to train a good model on the first try, without needing to iterate multiple times through different models. True/False?
- [ ] True
- [x] **False**
> Finding the characteristics of a model is key to have good performance. Although experience can help, it requires multiple iterations to build a good model.

5 ) Which one of these plots represents a ReLU activation function?
- [ ] Figure 1:
![](https://user-images.githubusercontent.com/43035503/48546246-36512600-e90b-11e8-86fe-7a34fa3e8208.png)
- [ ] Figure 2:
![](https://user-images.githubusercontent.com/43035503/48546283-4b2db980-e90b-11e8-9342-8c71e4908a92.png)
- [x] Figure 3:
![](https://user-images.githubusercontent.com/43035503/48546320-6b5d7880-e90b-11e8-9e66-8413af420aac.png)
> This is the ReLU activation function, the most used in neural networks.
- [ ] Figure 4:
![](https://user-images.githubusercontent.com/43035503/48546380-8f20be80-e90b-11e8-9786-0eac715cbd1f.png)

6 ) Images for cat recognitions is an example or "structured" data, because it is represented as a structured array in a computer. True/False?
- [ ] True
- [x] **False**
> Images for cat recognition is an example of "unstructured" data.

7 ) A demographic dataset with statistics on different cities' population, GDP per capita, economic growth is an example of "unstructured" data because it contains data coming from different sources. True/False?
- [ ] True
- [x] False
> A demographic dataset with statistics on different cites' population, GDP per capita, economic growth is an example of "structured" data by opposition to image, audio or text datasets.

8 ) Why is an RNN(Recurrent Neural Network) used for machine translation, say translating English to French?(Check all that apply.)
- [x] **It can be trained as a supervised learning problem.**
> We can train it on many pairs of sentences x(English) and y(French).
- [ ] It is strictly more powerful than a Convolutional Neural Network(CNN).
- [x] **It is applicable when the input/output is a sequence(e.g., a sequence of words).**
> An RNN can map from a sequence of english words to a sequence of french words.
- [ ] RNNs represent the recurrent process of Idea->Code->Experiment->Idea->...

9 ) In this diagram which we hand-drew in lecture, what do the horizontal axis(x-axis) and vertical axis(y-axis) represent?
![](https://user-images.githubusercontent.com/43035503/48546926-d78cac00-e90c-11e8-9d22-1edbdc78bece.png)
- [ ] x-axis is input to the algorithm
	 y-axis is ouputs
- [ ] x-axis is the performance of the algorithm.
	 y-axis(vertical axis) is the amount of data.
- [ ] x-axis is the amount of data
	 y-axis is the size of the model you train.
- [x] x-axis is the amount of data
	 y-axis(vertical axis) is the performance of the algorithm.

10 ) Assuming the trends described in the previous question's figure are accurate (and hoping you got the axis labels right), which of the following are true?(Check all that apply.)
- [ ] Decreasing the training set size generally does not hurt an algorithm's performance, and it may help significantly.
- [ ] Decresing the size of a neural network generally does not hurt an algorithm's performance, and it may help significantly.
- [x] Increasing the size of a neural network generally does not hurt an algorithm's performance, and it may help significantly.
> According to the trends in the figure above, big networks usually perform better than small networks.
- [x] Increasing the training set size generally does not hurt an algorithm's performance, and it may help significantly.
> Bringing more data to a model is almost always beneficial.