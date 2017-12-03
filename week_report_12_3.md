# Weekly Report
<sub>**Number: 2   
Adviser: Prof. Yang Wen  
Student: Cheng Wensheng   
Period: 2017.11.27-2017.12.3**</sub>
## Recap
This week I continue spending time doing ADSP project and finish this project thoroughly.
## Acoustic Echo Cancellation Ⅱ
* For echo cancellation, the criteria for evaluation can not be described with the filter output error like noise reduction anymore. Cause the error oscillates all the time and doesn't converge to a small range nearly 0.
* With the motivation of classmate's presentation, we'd like to use correlation coefficient to evaluate the performance. Obviously, the correlation of the pure input signal and the filter output is a reasonable criteria. The higher the correlation coefficient is, the better the filter does.
* To get the relationship between filter params, like filter orders, step size, forgetting factor, etc., I set the correlation coefficient as a multivariable function of these params. Then by double circulation can we get the best outcome with corresponding params.
## Next week plan
* Read the paper *Local Convolutional features with Unsupervised Training for Image Retrieval* in detail.
* Implement this idea in MATLAB with the resources author provided.