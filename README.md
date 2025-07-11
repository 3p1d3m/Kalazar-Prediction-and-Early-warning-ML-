# Kalazar Prediction Project

# Declining Kala-azar Cases: Hibernation for Resurgence or Journey towards True Extinction?  Exploring the Impact of Climate, Lankien, Republic of South Sudan. 

The prevalence of Kalazar/Visceral Leishmaniasis cases treated in Lankien hospital has been progressively decreasing, especially since the year 2020. While there was a notable frequent episode of flooding in the area, the reason behind the low number of VL cases remained uninvestigated.

**The possible scenarios could:**

*1) The climate change impact, for example, flooding has buried all the breeding sites of the sandflies.*

*2) The highest temperature has exceeded the previous temperature range, and adult sandflies cannot survive, so the transmission is low*

*3) Has the humidity and land surface temperature changed due to the temperature and flooding, and, hence, affected the Life cycle of Sandflies?*

*4) Kalazar has infected more people, and there is higher community-level immunity; hence, fewer severe cases seek treatment. False prevalence??*

*5) Most severe VL cases are seeking treatment in other facilities, hence false prevalence??*

*6) Has the community’s behaviour and way of living changed? Prevention methods applied? etc?*

**What is available for Lankien?**

*1) Seroprevalence survey?*

*2) Vector prevalence and behaviour study?*

*3) Kalazar and climate study?*

*4) Any other data available*

*Feb 2025, Juba, South Sudan*

[*Disclosure*]{.underline}*: This analysis was part of the routine deployment work in South Sudan, and hence it has not continued after 2023, due to lack of access to data. Yet this analysis is internal, with all the data protection and integrity for MSF respected.*

## Predicting KA cases using the historical KA cases 

![](images/paste-1.png)

![](images/paste-2.png)

## Climate variables and VL cases treated in Lankien Hospital

![](images/paste-3.png)

## Correlation between KA/VL cases and climate variables 

![](images/paste-4.png)

### Lagged variable and KA cases cross-correlation

![](images/paste-5.png)

### Climate variables and KA cases using the Granger Causality Test (GCT)

![](images/paste-6.png)

### Using Fourier transformation and seasonality

## Machine learning methods

Models without lagged time indicators

![](images/paste-8.png)

![](images/paste-9.png)

![](images/paste-10.png)

## Models with the variables with a lagged time

![](images/paste-11.png)

![](images/paste-12.png)

![](images/paste-13.png)

![](images/paste-14.png)

![](images/paste-15.png)

![](images/paste-16.png)

![](images/paste-17.png)

## **Partiall dependence plots** 

![](images/paste-20.png)

# Annexes 

#### 1. ARIMA time series predictions (train test 80, 20) 

![](images/paste-21.png)

#### 2. LSTM Predictions (train test 80, 20)

![](images/paste-22.png)

3.  **Random forest models fitted with the lagged KA cases autoregression**

    ![](images/paste-23.png)

4.  **XGBoost autoregression models**

![](images/paste-24.png)