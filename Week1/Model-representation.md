Model Representation
====================

Let's use some example of predicting
housing prices. We're going to use a data set of housing prices from the city of
Portland, Oregon.

And here I'm gonna `plot` my data set of a number of houses
that were `different sizes` that were sold for a range of `different prices` Let's say
that given this `data set` , you have a friend that's trying to sell a house and
let's see if friend's house is size of 1250 square feet and you want to tell them
how much they might be able to sell the house for. 

To establish notation for future use, we'll use <b>x<sup>(i)</sup></b> to denote the `input variables` (living area in this example), also called `input features`, and <b>y<sup>(i)</sup></b> to denote the `output or target variable` that we are trying to predict (price). 


A pair <b>(x<sup>(i)</sup>,y<sup>(i)</sup>)</b>. is called a `training example`, and the dataset that we'll be using to learn a list of m training examples <b>(x<sup>(i)</sup>,y<sup>(i)</sup>);i=1,...,m )</b>is called a training set. Note that the superscript "(i)" in the notation is simply an index into the training set, and has nothing to do with exponentiation. We will also use <b>X</b> to denote the `space of input values`, and <b>Y</b> to denote the `space of output values`. In this example, X = Y = ℝ.

To describe the supervised learning problem slightly more formally, our goal is, given a training set, to learn a function `h : X → Y` so that `h(x)` is a "good" predictor for the corresponding value of `y`. For historical reasons, this function h is called a `hypothesis`. Seen pictorially, the process is therefore like this:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/H6qTdZmYEeaagxL7xdFKxA_2f0f671110e8f7446bb2b5b2f75a8874_Screenshot-2016-10-23-20.14.58.png?expiry=1598313600000&hmac=JSNoq9DIKcaBIwQN7gwwooaG_0Pmh_8Esqgegea5vyI)

When the `target variable` that we're trying to predict is `continuous`, such as in our housing example, we call the learning problem a `regression problem`.

When `y` can take on only `a small number of discrete values` (such as if, given the living area, we wanted to predict if a dwelling is a house or an apartment, say), we call it a `classification problem`.
