Cost Function
=============

We can measure the accuracy of our hypothesis function by using a **cost function**. This takes an average difference (actually a fancier version of an average) of all the results of the hypothesis with inputs from x's and the actual output y's.

![](https://lh3.googleusercontent.com/OrnEzpo5mYzYehRr-K_Goc2t2vyz9yUro5-d2drtNk0grPhye6pSQNbJkFDdBdgqlhsgNqZjoCUc-Yj_ixUOWIvImHBFAVdq-TVO0zACMRfg8HB-U3qpGSx7-ZyOekGQEeb_hWU4nGo636hoemVSPFBgs14BxL_00u70b6i8-_Acxk642lxQg9MIj1iIn19C21hsS765o7H3ie2Mb1TMx1ETkUfjOmSOnY72ZaguPysKKZrvdgJBSru4Hn36I0X4mSzPGryNa_mMHdlAd_JBeO8xORw3YsEdpVfYjTEKiA8LFVto9V2LVDOlW_oaFq3JCo4KYbz6W6b8wtwYj_kVxiKG6DDiMS0oOmMUnSZ83o3g0nprzQ7UnzU9_C8cY28966VNuLf5u8q-pyqNcS9zgT5qjha9qI4Rw-ZB-V93i_j1kht6BEf0LTeUK_jd6LHqKhmOAhAzhAJBugXiJ6rrzUco7Q4ZvF5SsfN0AyH6pIOhzzKwOBauBQ8KYpVjaX99t54PPySU6pFG0-6Yjm6MKc_5wJiV4Ems7RPapCKo54_aE0Hios4AaSdWvWqEfJwhVLJ1FnPJk9VykkCfWELDFLett5L5qMnGYAY7bowi56K_vG_pqeKqosvvMxB5U7WNRV2C6mBgN3A9RDE81X9ZcFiS-6lt5rwN61kyvOIQXFmt1fmPBfov5XeKHcNr8g=w909-h137-no?authuser=0)

This function is otherwise called the `Squared error function`, or `Mean squared error`. The mean is `halved (1/2)` as a convenience for the computation of the gradient descent, as the derivative term of the square function will `cancel out` the `(1/2)` term. The following image summarizes what the cost function does:

![](https://d3c33hcgiwev3.cloudfront.net/imageAssetProxy.v1/R2YF5Lj3EeajLxLfjQiSjg_110c901f58043f995a35b31431935290_Screen-Shot-2016-12-02-at-5.23.31-PM.png?expiry=1598400000000&hmac=7tuT-Q_8Rn6n2wBFWV8HUgAsNXcgDPNW8S1x3ZMw2wY)


