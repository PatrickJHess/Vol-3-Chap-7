# **Measuring Interest Rate Risk With Duration**

**Key Topics Covered**

* **What is  duration and how is it calculated**  
    
  * Defining duration  
  * How does it measure interest risk  
  * The characteristics of bonds that affect interest rate risk  
  * How market conditions affect interest rate risk  
  * Using historical data to document the variation of interest rate risk.


* **Python concepts:**  
    
  * NumPy arrays  
  * Pandas  
  * Accessing FRED data with pandas data reader  
  * Custom modules.  
    * bond\_pay\_data  
    * calc\_ytm  
    * bond\_pv  
    * accrued\_interest  
    * One\_y\_axis  
  * calc\_duration developed in the chapter and added to the custom module

## ***Background***

This chapter's examples and discussions rely on the **Pandas** and **NumPy** libraries.

* **Pandas** is introduced in [*A Quick Introduction to Pandas*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_Pandas.html#a-quick-introduction-to-pandas).  
* **NumPy** is introduced in [*A Quick Introduction to NumPy*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/An_Introduction_To_NumPy.html#a-quick-introduction-to-numpy).  
* The bond\_pay\_data function is imported from [Chapter Three](https://patrickjhess.github.io/Imported-Functions/bond_pay_data.html#bond-pay-data-helper-function)  
* The calcc\_ytn function is imported from [Chapter Six](https://patrickjhess.github.io/Imported-Functions/calc_ytm.html)   
* The accrued\_interest function is imported from [Chapter Two](https://patrickjhess.github.io/Imported-Functions/accrued_interest.html)  
* The create\_payoff\_matrix function is imported from [Chapter Four](https://patrickjhess.github.io/Vol-3-Chap-4/Creating_The_Payoff_Matrix.html#creating-the-payoff-matrix)  
* The one\_y\_axis function is imported from [Chapter One](https://patrickjhess.github.io/Imported-Functions/one_y_axis.html)  
* Additional relevant Python concepts can be found in the introductory volume, [*Background Material: An Introduction to Python for Financial Python*](https://patrickjhess.github.io/Introduction-To-Python-For-Financial-Python/intro.html), that relate to this and other chapters of *Basic Concepts of Fixed Income*.

**The chapter includes Five  sections:**

1. *What Is Duration  and Why It Matters*  
   * defines duration.  
   * compares duration with continuous and discrete compounding  
     * Macaulay's duration  
     * modified duration  
   * the term structure and duration.  
2. The  Jupyter notebook *FRED Example*  
   * introduces the database of the Federal Reserve Bank Of St. Louis- FRED  
   * uses pandas reader to extract data from FRED  
   * an application to access data  
   * three  questions to ask Gemini to improve your ability to use FRED  

3. The jupyter notebook *Measuring Interest Rate Risk With Duration*  
*  develops the function calc\_duration that calculates duration.  
* downloads data for 304 bonds from DropBox and calculates their duration  
* uses historical par yields from FRED to analyze the relation between duration, coupon rates, and yield to maturity  
* demonstrates how durations of ten and thirty year bonds have varied over time.  
*  inverse relation between duration and yield to maturity is identified as convexity  
* an exercise comparing duration forecasts versus actual results  
* four questions to ask Gemini about how duration is used and relates to investment strategies  
4. *Summarizing the results of calculating and using duration*  
5. *Functions Imported by Chapter Seven* describes the function imported from DropBox (*module\_basic\_concepts\_fixed\_income*).
