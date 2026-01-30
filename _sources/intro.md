# ***Financial Python***

## ***Volume: Basic Concepts of Fixed Income***

### ***Chapter Seven: Measuring Interest Rate Risk With Duration***

Chapters Five and Six focus on the yields of bonds- either the coupon rates required to make a bond sell for its par value (**par yield)** or the internal rate of return that equates a bond's present value to its price (**yield to maturity**).   Because bond prices depend upon interest rates, one of the risks of owning a bond is unexpected changes in interest rates.  Increases and decreases of interest rates cause bond prices to fall and rise.

This and the next chapter analyze the impact and measurement of interest rate risk.  This chapter describes the calculation and characteristics of **duration**.  **Duration** is a simplified but useful measure of a bond's interest rate risk-a measurement of the sensitivity of bond prices relative to changes in their **yields to maturity**.  A measure that is directly related to the first derivative of the present formula with respect to the **yield to maturity**.  The same derivative used to calculate  **yields to maturity**.

**Demonstrating Duration With Data from the Federal Reserve Bank Of St. Louis Database**

This and future chapters access data from the FRED database that is maintained by the Federal Reserve Bank of St. Louis-one of the best sources for historical economic and financial data.  Duration depends upon characteristics of bonds as well as market conditions,  **Par yield** data is accessed from FRED and provides a natural experiment for examining what determines **duration**.  Between 1990 and 2025  **yields to maturity** and **par yields** of ten and thirty year bonds have varied between  0.5% and 9%. The result is many examples of low and high **par yields** and **yields to maturity**. Both variables affect **duration**.

### ***Leapfroggging into the chapter***

Like other chapters, there are no required dependencies between this and previous chapters. If you are unfamiliar with the material, you will benefit from reviewing previous chapters but you can begin here. As needed, the previously developed functions used in this chapter are imported from  a custom module. These functions are sufficient for you to benefit from the chapter.
