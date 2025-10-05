# Summary
This research project examines how alterations to the design of the "SHOP NOW" button influences user engagement as measured through Click-Through Rate (CTR). The purpose of this project is to increase the quantity of users clicking the button by testing color and wording variations. Additionally, this research project is designed to assess the best-performing combination of color and wording.

Four different versions of the button were evaluated:

Variant A (Control): Black, “SHOP NOW”

Variant B: Red, “SHOP NOW”

Variant C: Black, “SEE DEALS”

Variant D: Red, “SEE DEALS”

Multivariate A/B testing is best for optimization of multiple components of a webpage, app, or a campaign, and finding out how those components work together. It works best with high-traffic properties where you sufficiently have enough data collection for meaningful results.
# Objective
To discover which button design generates the largest conversion (CTR) and what effect color and text changes have on user engagement.
Precisely:
1) Determine if the changes in text or color have a stronger influence on clicks
2) Compare CTRs for all four button designs
3) Ensure the results have statistically significance (not due to chance)

Version	Button Color	Text	Type
A	Black	SHOP NOW	Control
B	Red	SHOP NOW	Treatment 1
C	Black	SEE DEALS	Treatment 2
D	Red	SEE DEALS	Treatment 3

# Test Variant
| Variant  |  Button Color | Text  | Type  |
| ------------ | ------------ | ------------ | ------------ |
| A  |  black | SHOP NOW  | Control  |
| B |  red | SHOP NOW  | Variant1  |
|  C | black  | SEE DEALS  | Variant2   |
| D  |  red |  SEE DEALS |Variant3   |

# Programming Languages and Libraries Utilized
- Python: Pandas, NumPy, Matplotlib, Scipy
- Google Optimize / Colab
- Google Analytics / Mixpanel
Explain visualization tools [Variant to be evaluated](https://docs.google.com/presentation/d/1o7IVqCHncEDNNdTXymbj13d_NCGw7e4pyu3UKa-bp5A/edit?slide=id.g384af54f1b3_0_1244#slide=id.g384af54f1b3_0_1244 "Variant to be evaluated") [Notebook/A/B Testing Computations](https://colab.research.google.com/drive/1qpZDLpxBm1sitLoAFfFk_xgmUICiguwv?usp=sharing "Notebook/A/B Testing Computations")

# Main Insights
- Understood how changes to color and text can impact user behavior.
- Gained experience with A/B and multivariate testing.
- Practiced randomization, data logging, and decision techniques like CTR calculation.
- Learned the importance of statistical significance in these experiment results.

# Obstacles Overcome
- Guaranteeing the equal random allocation of users to each condition.

- Managing the number of subjects to maintain statistical power.

- Eliminating the confounding factor by controlling one variable in each test.

- Translating the results of technical tests into clear marketing terms.
- 
# Further Insights
> This project illustrated the strength of using data to inform design decisions. Sometimes, simply changing color or text contributes to measurable increases in user engagement.

>  A Well Defined A/B Test Not Only Improves Conversion, But Also Creates A Culture Of Experimentation While Ensuring That Design And Marketing Teams Are Working In Tandem For Measurable Business Growth.

# Strategy Outline 
Implement a multivariate A/B test using four buttons.  Capture the CTR for each button.  Carry out significance testing. Proceed with the button that performs the best. Plan for further A/B tests on other elements of the site in the future.


