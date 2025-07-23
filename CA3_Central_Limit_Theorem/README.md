<div align="center">
  <h1>
    📈 Engineering Statistics & Probability - Computer Assignment 3 🧠
  </h1>
  <h2>
    Central Limit Theorem & Parameter Estimation
  </h2>
  <p>
    This assignment provides a hands-on exploration of the <strong>Central Limit Theorem (CLT)</strong> and its practical applications, alongside methods for parameter estimation using <strong>Mean Squared Error (MSE)</strong>.
  </p>
</div>

<hr>

## 🚀 Problems Overview

<table>
  <tr>
    <td valign="top" width="50%">
      <h3>
        Problem 1: Sampling and the Central Limit Theorem
      </h3>
      <p>
        An empirical demonstration of the CLT. This section shows how the sampling distribution of the mean, derived from various non-normal distributions (<strong>Poisson, Exponential, Geometric</strong>), converges to a Normal distribution as the sample size increases. The analysis includes observing changes in the mean and standard error of the sampling distributions.
      </p>
    </td>
    <td valign="top" width="50%">
      <h3>
        Problem 2: Applications of Mean Squared Error (MSE)
      </h3>
      <p>
        This problem focuses on using the principle of minimizing MSE to estimate unknown parameters. It covers two key applications:
      </p>
      <ul>
        <li>
          <strong>Linear Regression</strong>: Estimating the slope and intercept of a linear function that best fits a set of data points.
        </li>
        <li>
          <strong>Geometric Center</strong>: Finding the central coordinate for a cluster of 2D points.
        </li>
      </ul>
      <p>
        The solutions are derived by finding the point where the partial derivatives of the MSE function equal zero.
      </p>
    </td>
  </tr>
  <tr>
    <td valign="top" width="100%" colspan="2">
      <h3>
        Problem 3: CLT Applied to the Bernoulli Distribution
      </h3>
      <p>
        A deep dive into how the <strong>Normal distribution serves as a powerful approximation for the Binomial distribution</strong>. This is a direct consequence of the CLT, as the Binomial distribution is a sum of independent Bernoulli trials.
      </p>
      <details>
        <summary>
          <strong>Key Analysis Steps</strong>
        </summary>
        <ul>
          <li>
            Plotting the PMF of a Binomial distribution and comparing its shape to a corresponding Normal PDF.
          </li>
          <li>
            Standardizing the Binomial distribution to visually align it with the standard Normal distribution.
          </li>
          <li>
            Deriving and applying a scaling factor (using a Riemann sum approximation) to account for the difference between a discrete PMF and a continuous PDF.
          </li>
          <li>
            Using the Normal approximation to calculate probabilities for specific Binomial events and comparing the results.
          </li>
        </ul>
      </details>
    </td>
  </tr>
</table>

<hr>
