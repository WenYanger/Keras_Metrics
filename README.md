# Keras_Metrics
Some Metric Implementation in Keras (Such as Pearsons Correlation Coefficient, MRE)

Now Including:
- Pearsons Correlation Coefficient
- Mean Relative Error
- Jaccard Loss (**Derivable**, can be used as LOSS for training in Keras)
- Jaccard Index
- Dice Similarity Coefficient (aka. DSC)

----

# Relative Formula
- Pearsons Correlation Coefficient
> ![这里写图片描述](https://www.zhihu.com/equation?tex=%5Crho%28X%2CY%29%3D%5Cfrac%7BE%5B%28X-%5Cmu_%7BX%7D%29%28Y-%5Cmu_%7BY%7D%29%5D%7D%7B%5Csigma_X%5Csigma_Y%7D+%3D%5Cfrac%7BE%5B%28X-%5Cmu_%7BX%7D%29%28Y-%5Cmu_%7BY%7D%29%5D%7D%7B%5Csqrt%7B%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%7B%28X_i-%5Cmu_X%29%5E2%7D%7D%5Csqrt%7B%5Csum_%7Bi%3D1%7D%5E%7Bn%7D%7B%28Y_i-%5Cmu_Y%29%5E2%7D%7D%7D)

- Jaccard Loss
>![这里写图片描述](https://upload.wikimedia.org/math/1/8/6/186c7f4e83da32e889d606140fae25a0.png)

- Dice Similarity Coefficient
>![这里写图片描述](https://upload.wikimedia.org/math/2/3/5/2354a9c697d2bf4ae114b8f1f72d5090.png)

- Mean Relative Error
See [here](http://akademikpersonel.kocaeli.edu.tr/hmertunc/sci/hmertunc09.10.2015_14.07.20sci.pdf)
> Sayin C, Ertunc H M, Hosoz M, et al. Performance and exhaust emissions of a gasoline engine using artificial neural network[J]. Applied Thermal Engineering, 2007, 27(1):46-54.
