Normal Equation
===============


Gradient descent gives one way of minimizing J. Let's discuss a second way of doing so, this time performing the minimization explicitly and without resorting to an iterative algorithm.

In the **Normal Equation method**, we will minimize J by explicitly taking its `derivatives with respect to the θj 's, and setting them to zero` . This allows us to `find the optimum theta without iteration` .

The normal equation formula is given below:

θ = ( X<sup>T</sup>X)<sup>-1</sup>X<sup>T</sup>Y

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/dykma6dwEea3qApInhZCFg_333df5f11086fee19c4fb81bc34d5125_Screenshot-2016-11-10-10.06.16.png?expiry=1599609600000&hmac=EZnZ70cl-Oy4f4Or0HSld_UUaP0yWJwfGo1vPSOQwIk)

There is **no need** to do feature scaling with the normal equation.

The following is a comparison of gradient descent and the normal equation:

|        Command        |                  Explanation & Links                 |
|:---------------------:|:----------------------------------------------------:|
|    Gradient Descent   |                    Normal Equation                   |
| Need to choose alpha  | No need to choose alpha                              |
| Needs many iterations | No need to iterate                                   |
| O (kn2kn^2kn2)        | O (n3n^3n3), need to calculate inverse of XTXX^TXXTX |


With the normal equation, computing the inversion has complexity **O(n<sup>3</sup>)**.

So if we have a very large number of features, the normal equation will be slow. In practice, when n exceeds 10,000 it might be a good time to go from a normal solution to an iterative process.
