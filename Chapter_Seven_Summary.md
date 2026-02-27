# Summarizing Measuring Interest Risk With Duration

Duration is a straightforward and valuable metric for gauging interest rate risk. However, it has two key limitations:

1. It relies solely on the yield to maturity, overlooking more complex shifts in the term structure, such as changes in shape or slope.  
2. As a measure derived from the first derivative of the present value function with respect to the yield to maturity, it is only accurate for small changes in interest rates.

Despite these drawbacks, duration remains a widely accepted and useful tool for assessing the interest rate risk of bonds. It is important to note that duration is influenced by both the bond's characteristics (maturity and coupon rates) and the prevailing level of interest rates.

Historical data from the FRED database illustrates the impact of par yields and implied yield to maturity on duration:

| Bond | Date | Minimum Duration | Par Yield | Yield To Maturity | Date | Maximum Duration | Par Yield | Yield To Maturity |
| ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| Ten-Year | May 1990 | 6.78 | 9.08% | 8.88% | August 2020 | 9.74 | 0.56 | 0.56 |
| Thirty-Year | May 1990 | 10.75 | 9.04% | 8.84% | August 2020 | 25.18 | 1.23 | 1.23 |

By holding the coupon rate constant, it was shown that the duration of the thirty-year bond exhibits much greater sensitivity to changes in the yield to maturity—a characteristic known as higher convexity.


| Maturity | Duration: 4% Yield To Maturity | Duration: 5% Yield To Maturity   | Duration: 6% Yield To Maturity |
| :---- | :---- | :---- | :---- |
| Ten Years | 8.08 | 7.98 | 7.89 |
| Thirty Years | 16.89 | 15.77 | 14.67 |
