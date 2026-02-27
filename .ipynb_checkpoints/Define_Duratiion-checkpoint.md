

# What is duration and why does it matter

Einstein observed that compound interest is the eighth wonder of the world elaborating that: 'He  who understands it, earns it; he who doesn't, pays it.'  A less pithy elaboration is that the value now of a future payment depends on its timing and the interest rate that may be earned between now and then.  Interest rate increases enhance the effects of compounding and diminish the current value of future payments. Decreases, the opposite.  The interest rate risk of bonds is due to the vagaries of interest rates.  Accounting for interest rate risk is key in developing financial strategies.  Duration is an effective way of measuring and managing interest rate risk.

## Defining duration
In Chapter Five of the volume yields to maturity are calculated by approximating  changes in bonds' values with the bonds' first derivatives multiplied by minus the assumed changes in their yields to maturity.

<br>

$$V(\text{ytm}+\Delta \text{ytm})-V(\text{ytm})\approx -\Delta \text{ytm}\times\sum_{i=1}^{N}t_i\times \text{Cash Flow}_{t_i} \times e^{-\text{ytm}\times t_i}$$

<br>

The yield to maturity (ytm) is an annualized rate.

The rate of change in the value of the bond equals the change in value divided by its initial value:

<br>

$$\frac{V(\text{ytm}+\Delta \text{ytm})-V(\text{ytm})}{V(\text{ytm})}\approx -\Delta \text{ytm}\times\frac{\sum_{i=1}^{N}t_i\times \text{Cash Flow}_{t_i} \times e^{-\text{ytm}\times t_i}}{\text{V(ytm)}}$$

<br>

The last term on the right-hand side of the equation is the bond's duration:

<br>

$$\text{Duration} = \frac{\sum_{i=1}^{N}t_i\times \text{Cash Flow}_{t_i} \times e^{-\text{ytm}\times t_i}}{\text{V(ytm)}}$$

<br>

Duration scales the effect of changes in yield to maturity on bond values Duration measures a bond's interest rate risk by showing how sensitive its price is to changes in the yield to maturity. Specifically, a duration of one forecast a percentage price change equal to the change in the yield to maturity. A qualification, however, is needed. Because duration is negatively related to the yield to maturity, forecasts of price changes will contain errors that are also negatively related to changes in yields to maturity-forecasts will be positive for decreases and negative for increases in yields to maturity.



## Duration Is Weighted Average Of A Bond's Payment Dates

Duration is a weighted average of a bond's payment dates. The weights are determined by dividing the present value of each payment by the bond's total present value. It is calculated by summing the products of each cash flow's present value and its payment date, and then dividing this sum by the bond's present value.

<br>

$$\text{Duration} = \sum_{i=1}^{N}t_i\times w_{t_i}$$

<br>

$$ w_{t_1} =\frac{\text{Cash Flow}_{t_i}\times e^{-\text{ytm}\times t_i}}{V(ytm)}$$

<br>

$$\sum_{i=1}^{N}w_{t_i} = 1$$

<br>

The duration of a bond that makes a single payment at T is its maturity.

<br>

$$\text{T}= \frac{\text{T}\times \text{Principal}_T\times e^{-\text{ytm}\times \text{T}}}{ \text{Principal}_T\times e^{-\text{ytm}\times \text{T}}}$$

<br>

The timing of bond payments before maturity reduces its duration, making it shorter than the maturity date. For bonds with multiple coupon payments, a higher coupon rate leads to a lower duration.

## Measuring duration with discrete compounding

Our discussion and calculations assume continuous compounding. With continuous compounding, duration is simply equal to the weighted average maturity. The weights used in this calculation are the present value of each payment divided by the present value of all payments.

For discrete compounding, two primary duration measures are used: Macaulay's Duration and Modified Duration.  Macaulay's Duration is a measure of the weighted average term to maturity of a bond's cash flows, defined by the formula:

<br>

$$\text{Macaulay's Duration} = \frac{\sum_{i=1}^{N}t_i \times \text{Cash Flow}_{t_i} \times (1+y)^{-t_i}}{\text{V(y)}}$$

<br>

This measure is closely related to the first derivative of the present value formula with discrete compounding:

<br>

$$\text{First Derivative} = \frac{\sum_{i=1}^{N}t_i \times \text{Cash Flow}_{t_i} \times (1+y)^{-t_i}}{(1+\text{y})}$$

<br>

Changed this version to match yield font in numerator, i.e., y without italics.

<br>

$$\text{First Derivative} = \frac{\sum_{i=1}^{N}t_i \times \text{Cash Flow}_{t_i} \times (1+\text{y})^{-t_i}}{(1+\text{y})}$$

<br>

Modified Duration adjusts Macaulay's Duration by dividing it by one plus the yield (1+y). This measure forecasts the relative change in present value for a given change in yield, similar to the continuous compounding definition of duration.

<br>

$$\text{Modified Duration} = \frac{1}{1+\text{y}} \times \frac{\sum_{i=1}^{N}t_i \times \text{Cash Flow}_{t_i} \times (1+y)^{-t_i}}{\text{V(y)}}$$

## What Interest Rates Risk Does Duration Measure

Using duration to gauge a bond's interest rate risk—specifically, its sensitivity to interest rate increases—leads to a key question: which interest rates? Because a coupon bond is essentially a portfolio of zero-coupon bonds, its yield to maturity is a complex blend of various spot rates. The yield depends on the bond's maturity, its coupon, and the entire sequence of spot rates.


A change in short-term spot rates (either up or down) can be entirely offset by an opposite change in long-term spot rates. This means the term structure of interest rates has three components: a level (the overall height), a direction (upward or downward shift), and a shape (its curvature). In the U.S., the level accounts for over 88% of the variation in the term structure, the direction accounts for about 8%, and the shape accounts for less than 2%.$^{1}$  In the U.S., duration has historically served as a reliable initial estimate for a bond's interest rate risk.



---

 $^{1}$ R. Litterman and J. Scheinkman, Common Factors Affecting Bond Returns, Journal Of Fixed Income, Summer 1991, pp. 54-61.



