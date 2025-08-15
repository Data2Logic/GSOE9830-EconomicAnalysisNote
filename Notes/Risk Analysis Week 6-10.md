![[NPV sensitivity Table 2.png]]
## Key input parameters: 
### Cost estimation:
Fluctuations in materials, labours, and overhead cost. Major issue is cost overrun (projects expended exceed budget). Caused by Poor planning, Scope changes, Unexpected challenges ( technical, supply chain disruption), Inflation 
### Revenue Projections (Estimate profit): 
Variability in sales forecasts, and market demand
![[Uncertainty Economic.png]]
### Interest Rates: 
Change in borrowing costs and investment return
### Inflation Rates:
Unpredictable shifts in purchasing power and price level

## Type of Risk Analysis Tools: 

![[Risk Analysis.png]]
### _Sensitivity Analysis_: 

Help to understand how the incorrect estimation affect the original estimate. Example : If we predict 20% offset then the price will change by 1mil $. 

Help determine different values of an independent variable affect a particular dependant variable under a given set of assumptions. It is also known as what if analysis.

![[NPV sensitivity Example Zn-Lead mining project table.png]]![[NPV sensitivity Table 2.png]]![[NPV sensitivity analysis table.png]]
#### Learning activities: 
 
 Acme Delivery is considering a proposal for new package tracking technology. The system has an Estimated initial cost of $1.9 million and will require maintenance of Estimated $140,000 each year. Acme estimates that improved tracking will save approximately $680,000 per year, after system operating expenses. Consider a 6 years study period. 

Determine how sensitive the decision to invest in the system is to the estimates of initial investment and maintenance cost, annual savings.

#### How to calculate : 

1. Calculate the total amount of cost NPV for 6 years without any changes :  $$ 6\ Years\ cost = Capex + Opex - Saving $$
2. Apply the Sensitivity % for each of the variable
3. Plot the line 

![[Sensibility Analysis　Problem.png]]

### _Probability distribution_

Make it easier to see exactly how many observations are in each category. Proportion in each category maybe interested. Proportion of observation in each category is called **relative frequency**:
$$ Relative\ Frequency = \frac{Frequency}{Sum\ of\ all\ frequency}
$$
Constructing frequency distribution: 
***Step1:*** Choose a class width 
***Step2:*** Chooser a lower class limit for the first class. This should be a convenient number that is slightly less than the minimum data value
***Step3:*** Compute the lower limit for the second class, by adding the class width to the lower limit for the first class : Lower limit for the second class = lower limit for the first class + class width
***Step4:*** compute the lower limits for each of the remaining classes, by adding the class width to the lower limit of the preceding class. Stop when the largest data value is included in a class
***Step5:*** Count the number of observations in each class, and construct the frequency distribution, 

**Example :** 
![[Frequency distribution Zinc_Lead_Silver.png]]
![[Distribution Occurence.png]]

#### Key calculations and characteristics:

1. Mean (Centre moment) : often referred to as the average, represents the central tendency of a dataset $$Mean = \frac{Sum\ of\ all}{Total\ number\ of\ apperance}$$ Or $$Mean = \sum Probability\ *\ values $$

2.  Variance (Measure of dispersion) : a measure of how spread out a set of numbers is, indicating the degree to which individual data points deviate from the mean (average) of the data set $$Variance = \left(Distance\ from\ mean \right)^2*Probability $$ 
3.  Standard deviation: a measure of how spread out a set of values is, relative to its mean (average) $$Standard\ deviation = \sqrt{Variance} $$
4. Mode: Value that appear more frequently in the dataset 

#### Optimistic-Most Likely-Pessimistic: 

Deal with multiple variable in distribution: 
**Step1:** Establish optimistic (the most favorable), most likely, and pessimistic (the least favorable) estimates for each factor.
**Step2:** Perform analysis under each condition for insight into the sensitivity of the solution.
**Step3:** The results can be seen on a spider plot for further insight.

*Example:* 
![[Pasted image 20250815032228.png]]
![[Pasted image 20250815032236.png]]
***Correlation***  : Two factor can have a correlation relationship to each other or not
- Positive correlations:
![[Pasted image 20250815032535.png]]
![[Pasted image 20250815032717.png]]
- Negative correlations: 
![[Pasted image 20250815032543.png]]
![[Pasted image 20250815032735.png]]
- Independence: 
![[Pasted image 20250815032817.png]]
![[Pasted image 20250815032853.png]]
### Monte Carlo Simulations : 

Deal with multiple factors in Distribution calculators. 

Monte Carlo simulation is a statistical technique that uses random sampling and repeated computation to model and analyse complex systems or processes. 
It helps understanding the impact of risk and uncertainty in economic forecasts and decision-making
![[Pasted image 20250815033345.png]]
Example: 


### Expected Value Calculation :

A tool to help choose between each choices (lottery). A lottery consists of number of possible outcomes with assossiated probability : $$ q  = (x_1, p_1, x_i, p_i;...x_n,p_n)$$
With : 
- $x_i:$ present the i th outcome
- $p_i$ : present the probability of the i th outcome 

***Step1:***  Define outcome and possibility 
***Step2:*** Determine Payoffs (amount of money loss or win with certain choice)
***Step3:*** Calculated expected value $$EV = \sum(Probability * Pay\ off)$$
***Step4:*** Calculate the break even probability of success point which EV = 0 
***Step5:*** Draw expected value line 
#### Minimum probability of success for indifference

The minimum probability of success for indifference is a key concept in decision-making under uncertainty, particularly in scenarios involving risk and investment choices. 

It represents the probability at which a ***decision-maker is indifferent*** between two options: one with a risky payoff and another with a guaranteed (certain) payoff. 

The minimum probability of success is the **threshold probability at which the expected value of the risky option equals the value of a sure (certain) outcome.** Most often is equal to the no ***investment, EV=0. no gain, no loss***  

Example : 

#### Farm-out agreement : 
An entity (the farmor) agrees to provide a working interest in a mining property to a third party (the farmee), provided that the farmee makes a cash payment to the farmor and/or incurs certain expenditures on the property to earn that interest.

**Key feature:** 
- Farmor : The party that owns the rights to the property and is looking to reduce its financial exposure or share the risk 
- Farmer : The party that takes on the interest and associated responsibilities, usually in exchange for convering some costs
- Interest Transfer: Specifics the percentage of the interest being transferred from the farmor to the framee
- Cost Sharing: Details on how costs will be allocated between the parties, e.g. all upfront payments or some of it being paid by farmee.
**Formula** : 
$$EV_{farm\ out}=EV_{normal}$$
Assume maximize working interested : 
$$EV_{farm\ out} = (Success+Failure)*P_{success}*(1-share\ of\ farmee)+(0 * P_{failure})$$
Usually have to find share of farmee

**Example 1 :** 
Farmout agreements are very popular with smaller oil and gas producers who own or have rights to oil fields that are expensive or difficult to develop. One company that makes frequent use of this type of arrangement is Kosmos Energy (NYSE: [KOS](https://www.investopedia.com/markets/quote?tvwidgetsymbol=kos)). Kosmos has rights to acreage off the coast of Ghana, but the cost and risks to develop these resources are high because they are underwater.

To help reduce these risks, Kosmos "farms out" its acreage to third parties like Hess ([HES](https://www.investopedia.com/markets/quote?tvwidgetsymbol=hes)), Tullow Oil, and British Petroleum (BP). Doing so allows these offshore blocks to be developed and generate cash flow for all the parties involved. A farmee like Hess takes on the obligation to develop the field and, in return, has the right to sell oil that is produced there. Kosmos, as the farmor, earns a royalty payment from Hess for supplying the acreage and the natural resource.

#### Fiscal relief :

Overall tax cut for the projects without it the cost of failure will be increase. 

$$Cost\ before\ tax\ cut = \frac{Cost\ after\ tax\ cut}{1-Tax\ rate}$$

*Example : COVID-19 stimulus packages provided fiscal relief to businesses and individuals.*

#### With more than two outcomes: 

![[Pasted image 20250815185508.png]]

![[Pasted image 20250815185606.png]]

#### Exercise : 
1.  Calculate the expected value of a mining project with following NPV outcomes and
their conditional probabilities
	- Success: (0.15, 120)
	- Failure: (0.85, -5)
2.  Find the break even probability point
3. Find the farmout value that provides same EV for the original company?
4.  Recalculate the values of question 1-3 without fiscal relief when the overall rate of tax
is 50%. Compare the results with calculated values in questions 1-3.
***Attempt Answer***: 
1/ Expected value: 
$$EV = (0.15*120)-(0.85*5) = 13.75$$
2/ Break out even
We have : $$EV = 120*P_{success}-5*(1-P_{success})$$
$$EV =125*P_{success}-5$$
When EV = 0 : 
	$$P_{success} = \frac{5}{125}=4\%$$
3/ Farmout value : 
$$EV_{frameout}=EV = 13.75 = (Success+Failure)*P_{success}*(1-farmout)$$
$$farm\ out = 0.26 = 26\%$$
4/ Without fiscal relief : 
Loss will increase severity : $$Loss = \frac{Loss\ with\ fiscal}{1-50\%}=10$$
Expected value : $$EV = 0.15*120-0.85*10 = 9.5$$  Break even : 
$$EV = 0 = Success*P_{success}-Failure*(1-P_{success})$$
Break even probability point : 
$$P_{success\ break\ even} = 0.073 = 7.3\%$$
Farmout value : 
$$EV_{Farmout} = EV = 9.5 = (Success+Failure)*P_{success}*(1-Farmout)$$
$$EV_{Farmout} = 0.51 =51\%\ of\ farmee\ share$$

### Decision Tree: 

A flowchart-like structure used to visually represent decisions and their potential outcomes, costs, and consequences
#### Example: 
##### Problems: 
![[Pasted image 20250815233007.png]]
##### Analysis with decision tree: 
![[Pasted image 20250815233040.png]]
![[Pasted image 20250815233213.png]]
![[Pasted image 20250815233254.png]]
#### Binomial model : 

Can use binomial model to solve the problems : 

![[Pasted image 20250815234558.png]]
Pascal triangle is used to expand binomial equation : 
$$(x+a)^2 = x^2 + 2ax + a^2$$
$$(x+a)^3 = (x^3 + 3ax^2 + 3a^2x+a^3)$$
Etc.....
Value of position S, row N can be found with formula : 
$$C(N,S) = \frac{N!}{S!*(N-S)!}$$
This can be used to calculate the Probability of S success in N events with the following formula : 
$$P(S) = C(N,S)*p^S*p^{N-S}$$
#### Analysing Decision Tree: 

![[Pasted image 20250816002101.png]]

![[Pasted image 20250816002608.png]]
![[Pasted image 20250816002751.png]]
![[Pasted image 20250816002806.png]]
![[Pasted image 20250816002902.png]]![[Pasted image 20250816002908.png]]
![[Pasted image 20250816002925.png]]
![[Pasted image 20250816002933.png]]
#### Supply chain applications of Decision Tree:

More often the decision must be evaluate as net cash flows over time. Using Discounted net cash flow to analysing the decisions. Only look at present value of the cash flow (remove any interested) - Net present value (NPV) 
$$ NPV = C_0 + \sum_{t=1}^{T}{\frac{1}{1+k}^tC_t}$$
With : 
$C_n$ : is stream of cash flows over T periods
NPV : Net present value
K = internal rate of return

##### Analysing Methodology : 
1. Identify the duration of each period and the number of period T over which decision is to be evaluated
2. Identify factors whose fluctuation will be considered
3. Identify representations of uncertainty for each factor
4. Identify the periodic discount rate k for each period
5. Represent the decision tree with defined states in each period as well as the transition probabilities between states in successive periods
6. Starting at period T, work back to Period 0, identifying the optimal decision and the expected cash flows at each step

***Example :*** **Trips Logistic**
• Trips Logistics, a third-party logistics firm that provides warehousing and other
logistics services, is facing a decision regarding the amount of space to lease
for the upcoming three-year period. The general manager has forecast that
Trips Logistics will need to ==**handle a demand of 100,000 units**== for each of the
**==next three years==**. Historically, Trips Logistics has ==**required 1 ,000 square feet of**==
==**warehouse space for every 1 ,000 units of demand**==. For the purposes of this
discussion, the only cost Trips Logistics faces is the cost for the warehouse.
• Trips Logistics ==**receives revenue of $1.22 for each unit of demand**==. The general
manager must decide whether to sign a three-year lease or obtain ware house
space on the spot market each year. The three-year lease will cost ==**$1 per==**
**==square foot per year, and the spot market rate is expected to be $1.20 per==**
**==square foot per year for each of the three years**==. Trips Logistics has a discount
rate of **==k = 0.1==**. Should the general manager sign a lease?

***Step1:***
Two assumption : 
1/  Spot prices can go up by 10% with p = 0.5 or down by 10% with 1 − p = 0.5
2/  Binomial uncertainty: Demand can go up by 20% with p = 0.5 or down by 20% with 1 − p = 0.5
Two options : 
1/Lease the ware house space $1\$$
2/Get space from spot market as needed
***Step2:***
Make decision tree of one period: 
With two variables there are 4 options: 

***Step3:***
***Step4:***
***Step5:***
***Step6:***
