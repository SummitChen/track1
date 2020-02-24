# Track1

## *Setup*

Download and extract train.csv and submission.csv to the data folder from https://aistudio.baidu.com/aistudio/datasetDetail/19383

Loss function is:

\begin{equation*}
logloss = - \frac{1}{N}\sum_{i=1}^n(y_i * log(p_i) * 40.0023696656183 + (1 - y_i) * log(1 - p_i))
\end{equation*}