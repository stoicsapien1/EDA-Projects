# Kolmogorov–Smirnov Test (K–S Test)

The **Kolmogorov–Smirnov test (K–S test)** is a statistical method used to assess the similarity between two probability distributions. Here are the key points about this test:

1. **Purpose**:
   - The K–S test is a **nonparametric** test, meaning that it makes no assumptions about the underlying distribution of the data.
   - It is commonly used to compare two samples or to test whether a sample came from a specific reference probability distribution.

2. **One-Sample K–S Test**:
   - In the **one-sample K–S test**, we compare a sample distribution to a known reference distribution (e.g., normal, exponential, uniform).
   - The test quantifies the distance between the empirical distribution function of the sample and the cumulative distribution function of the reference distribution.
   - It answers the question: "How likely is it that the sample came from the reference distribution?"

3. **Two-Sample K–S Test**:
   - In the **two-sample K–S test**, we compare two independent samples to determine if they come from the same distribution.
   - It is sensitive to differences in both location and shape of the empirical cumulative distribution functions of the two samples.
   - The null hypothesis assumes that the samples are drawn from the same (but unknown) distribution.

4. **Goodness of Fit Test**:
   - The K–S test can also serve as a **goodness of fit test**.
   - For testing normality, samples are standardized and compared with a standard normal distribution.
   - This modification changes the null distribution of the test statistic.

5. **Named After**:
   - The test is named after mathematicians **Andrey Kolmogorov** and **Nikolai Smirnov**.

In summary, the K–S test provides a way to assess whether observed data aligns with a specific distribution or if two samples share the same underlying distribution. It is widely used in various fields for hypothesis testing and model validation.
