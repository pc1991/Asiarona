# Latest COVID-19 Data in Asia
(Courtesy: Anandhu H of Kaggle)

>Please take note that this model done was performed around mid-August of 2021. The case numbers are currently higher as we speak and Mr. Anandhu is currently updating his Excel sheet on this matter daily.

# Content
Covid-19 Data of Asian Countries as on September 02, 2021

# Attribute Information

Country - Name of Asian Countries

Total Cases - Total number of Covid cases

Total Deaths - Total number of Covid deaths

Total Recovered - Total number of recovered cases

Active Cases - Total number of active cases

Total Cases/1M population - Total cases per 1 million population

Deaths per 1M population - Total deaths per 1 million population

Total Tests - Total covid tests done

Tests/1M population - Tests per 1 million of the population

Population - Population in each country

# Searching for the P-values of the correlation tests
> atp <- at$p.value
> btp <- bt$p.value
> ctp <- ct$p.value
> dtp <- dt$p.value
> 
> atp
[1] 1.526644e-07
> btp
[1] 1.374775e-07
> ctp
[1] 1.59374e-07
> dtp
[1] 0.001594646

![GG Plot On Relationship between Total Cases   Population](https://user-images.githubusercontent.com/87962854/132267208-79d1c98a-edeb-4921-b21f-5e02856354d3.png)

![Fitted vs  Residuals Graph of Asia Coronavirus Linear Model](https://user-images.githubusercontent.com/87962854/132267137-0d1bfe58-2049-4331-a5ed-81df15586032.png)

![QQ Plot of Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267239-103ed02b-c979-4c4b-8d15-38e48f80a16a.png)

![Half-Norm Plot of Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267674-e43a5fea-7969-4bf7-92f8-260acfd56b54.png)

![Shapiro Test of Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267712-54b9f2b7-d776-42b8-9713-80c70a91adfc.png)

![Prediction Plot for Asiarona](https://user-images.githubusercontent.com/87962854/132267741-f1f472a6-bb5e-4dd2-966e-efc0f2e99459.png)

![Model Output Plot for Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267756-a6986a98-dff6-447f-b2b5-225f89ab204a.png)

![Logarithmic Prediction for Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267779-fe515ad5-a67b-4d05-a963-50dbac71e70a.png)

![Logarithmic Model Output Plot for Asiarona Linear Mode](https://user-images.githubusercontent.com/87962854/132267787-67c7e82d-08d9-44e8-80dd-4d07c67217bf.png)

![Plotted Relationship between Logarithmic Prediction   Logarithmic Model Output](https://user-images.githubusercontent.com/87962854/132267807-88f65401-3e31-4a84-8752-4994d8d830a2.png)

![Fitted vs  Residuals of Logarithmic Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267825-5d67ec5e-72a6-43f0-9192-567f3c2dc7dd.png)

![QQ Plot of Logarithmic Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267856-f26a3344-38a3-4212-84d2-b843b1f8a553.png)

![Half-Norm of Logarithmic Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267916-d9adee2f-2790-4adb-b152-c5a9ec778d8a.png)


# Citations

Link : https://www.worldometers.info/coronavirus/#countries

Upvote if you find it useful

Copyright (c) 2021 Robert (Christian) Paul & Anandhu H

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
