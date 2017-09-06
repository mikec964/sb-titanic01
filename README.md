# Springboard course
Mike Combs

The [HTML version](http://htmlpreview.github.io/?https://github.com/mikec964/sb-titanic01/blob/master/README.html) of this Markdown file renders embedded LaTeX correctly.

## 4. Exploratory Data Analysis
Exploratory Data Analysis (EDA) is an approach for summarizing and visualizing the important characteristics and statistical properties of a data set. Before getting into any formal methods, it helps one form an intuition about the data. Lets start applying the different types of statistical analyses we encountered in the previous section to real data sets.

### 4.2 Titanic exercise
R code from the Titanic exercise in the ggplot2 tutorial: [titanic.R](titanic.R)

### 4.4 CHIS exercise
R code from the CHIS exercise in the ggplot2 tutorial: [CHIS.R](CHIS.R)

### 5.1 Probability
General multiplication rule:
\begin{align}
  P(A \ and \ B) &= P(A) • P(B \mid A) \\
  P(A \ and \ B) &= P(B) • P(A \mid B) \\
  P(A \mid B) • P(B) &= P(B \mid A) • P(A) \\
  P(A \mid B) &= \frac{P(A \ and \ B)}
                      {P(B)}
\end{align}
