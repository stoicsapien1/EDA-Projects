# Anderson-Darling Test

The **Anderson-Darling test** is a statistical test used to assess whether a given sample of data follows a specific theoretical probability distribution. Here are the key points:

1. **Purpose and Hypotheses**:
   - The test allows us to control the hypothesis that the distribution of a random variable observed in a sample corresponds to a certain theoretical distribution (e.g., normal distribution).
   - The null hypothesis assumes that the data follows the specified distribution.

2. **Test Statistic**:
   - The test statistic measures the distance between the empirical cumulative distribution function (CDF) of the data and the hypothesized CDF.
   - It places more weight on observations in the tails of the distribution.

3. **Basic Formulation**:
   - Given a hypothesized underlying distribution, the test calculates the test statistic based on the ordered data points.
   - The formula for the test statistic is:
     $$ A^2 = -n - \frac{1}{n} \sum_{i=1}^{n} \left[ \frac{2i - 1}{2n} \cdot \ln(F(x_i)) + \frac{2(n - i) + 1}{2n} \cdot \ln(1 - F(x_i)) \right] $$
     where:
     - \(n\) is the number of elements in the sample.
     - \(F(x_i)\) is the empirical CDF evaluated at the \(i\)-th ordered data point.

4. **Interpretation**:
   - Compare the test statistic against critical values from the theoretical distribution.
   - If the test statistic exceeds the critical value, reject the null hypothesis (indicating departure from the specified distribution).

5. **Inventors**:
   - The test is named after Theodore Wilbur Anderson and Donald A. Darling, who introduced it in 1952.



