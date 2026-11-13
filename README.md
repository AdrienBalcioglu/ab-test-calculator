# A/B Test Calculator

Plan the sample size and duration of an A/B test, then check whether the result is significant.
**[Try it live](https://adrienbalcioglu.github.io/ab-test-calculator/)**


## Features

- Sample size per variant from baseline rate, minimum detectable effect, confidence and power
- Test duration from your daily traffic, rounded up to whole weeks
- Bonferroni correction when there are more than two variants
- Significance check: uplift, p-value and 95% interval from visitors and conversions

## Usage

Open `index.html` in a browser. There is nothing to install and nothing to build.

The maths: a two-sided z-test on two proportions, with the normal quantile computed in the page.

## Stack

HTML, CSS and JavaScript in a single file. No dependency.

## License

[MIT](LICENSE) © 2026 Adrien Balcioglu
