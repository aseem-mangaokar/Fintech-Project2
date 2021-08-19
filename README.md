# **Fintech-Project2**

 ## **Generating hourly and daily trade signals for SQ and XRP using select indicators**
--
#Technical Indicators used:
--
    - RELATIVE STRENGTH INDEX
    - AROON INDICATOR
    - MOVING AVERAGE CONVERGENCE / DIVERGENCE
    - AWESOME OSCILLATOR
    - BOLLINGER BANDS


##  Combining multiple trade signals using Random Forest Classifiers
--
- SQ
    - Buy and Hold strategy: 346.72% profit
    - Daily RFC: 290.33% profit/ ACC score 0.5274
    - Hourly RFC: 294.07% profit / ACC score 0.5221
    - Combo Daily/Hourly RFC: 554.08% profit / ACC score 0.5210

- XRP
    - Daily RFC: 1004.08% profit / ACC score 0.5418
    - Hourly RFC: 768.6% profit / ACC score 0.5097
    - Combo Daily/Hourly RFC: 

## Evaluating our combo daily/hourly models with Deep Neural Net
--
- SQ
    - Combo RFC: 50.2% accuracy
- XRP
    - Daily RFC: 50.5% accuracy