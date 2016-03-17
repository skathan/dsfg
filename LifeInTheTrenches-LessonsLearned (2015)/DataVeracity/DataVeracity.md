Data Veracity
==============
*We’re Data Scientists, not data alchemists. We can’t make analytic gold from the lead of data.*

While most people associate data volume, velocity, and variety with big data, there is an equally important yet often overlooked dimension – data veracity. Data veracity refers to the overall quality and correctness of the data. You must assess the truthfulness and accuracy of the data as well as identify missing or incomplete information. As the saying goes, “Garbage in, garbage out.” If your data is inaccurate or missing information, you can’t hope to make analytic gold.
Assessing data truthfulness is often subjective. You must rely on your experience and an understanding of the data origins and context. Domain expertise is particularly critical for the latter. Although data accuracy assessment may also be subjective, there are times when quantitative methods may be used. You may be able to re-sample from the population and conduct a statistical comparison against the stored values, thereby providing measures of accuracy.
The most common issues you will encounter are missing or incomplete information. There are two basic strategies for dealing with missing values – deletion and imputation. In the former, entire observations are excluded from analysis, reducing sample size and potentially introducing bias. Imputation, or replacement of missing or erroneous values, uses a variety of techniques such as random sampling (hot deck imputation) or replacement using the mean, statistical distributions or models.

(TIP: Find an approach that works, implement it, and move on. You can worry about optimization and tuning your approaches later during incremental improvement.)
