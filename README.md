# leiden_public

Welcome to my repository showcasing academic projects from my MSc in Statistics &amp; Data Science program.

# SCwR Projects

The two projects presented below are part of the [Statistical Computing with R](https://studiegids.universiteitleiden.nl/en/courses/121707/statistical-computing-with-r) module.

Feel free to explore each project folder for more details.

## Project 1: Custom Expectation-Maximisation Algorithm Implementation

### Tweet: Crafted Complex Algorithm from Scratch
<img src="./img/convergence.png" width=75%, alt = "Algorithm Preview">

- **Please open:**
  - [SCwR_A3](https://github.com/ValentinK214/leiden_public/blob/main/SCwR-EM_algo/kodderitzsch_valentin_SCwR_A3.pdf) - The project report

- **Description:**
  - Detailed information about this project can be found in the file called [assignment.pdf](https://github.com/ValentinK214/leiden_public/blob/main/SCwR-EM_algo/Assignment.pdf). In summary, the goal was to develop the Expectation-Maximization (EM) algorithm from scratch for mixed model parameters estimation, using only the lecture slides.
  - Key Technology: R (base, ggplot2)

- **Achievements:**
  - Implemented using Test Driven Development (TDD) strategies, ensuring high code quality and correctness.
  - Achieved an impressive 99% accuracy on simulated data, validating the robustness of the Expectation-Maximization (EM) algorithm.
  - Demonstrated 52% accuracy on the provided dataset, showcasing the algorithm's real-world applicability.

- **Key Learnings:**
  1. Utilized re-parameterized optimization to address challenges with constrained optimization, preventing issues with parameter estimates.
  2. Employed print statements as a debugging tool, adapting strategies to overcome limitations in R Studio's debugging tools.
  3. Recognized the importance of maintaining the original order of factor variables for accurate encoding.
  4. Navigated challenges with limited precision in floating-point arithmetic by using the `round` function for accurate comparisons.


- **Interesting Sections from the Report**
    - Ex 2, part 3, log-likelihood function implementation
    - Ex 2, part 4, EM algorithm implementation
    - Ex 2, part 6, EM convergence check
    - Ex 2, part 7, EM comparing estimates to observed parameters
    - Ex 2, part 10 with 12, EM classification accuracy
    - Testing, log-likelihood test using parametric bootstrap
    - Testing, EM algorithm convergence check & classification accuracy (99%)
    - Learnings 


