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
> 
> btp <- bt$p.value
> 
> ctp <- ct$p.value
> 
> dtp <- dt$p.value
> 
> atp
> 
[1] 1.526644e-07

> btp
> 
[1] 1.374775e-07

> ctp
> 
[1] 1.59374e-07

> dtp
> 
[1] 0.001594646

# GG Scatter Plot on Relationship b/w Total Cases & Population

![GG Plot On Relationship between Total Cases   Population](https://user-images.githubusercontent.com/87962854/132267208-79d1c98a-edeb-4921-b21f-5e02856354d3.png)

# Finding Our Root Mean Square Error For Original Linear Model

>rmse(g$fitted.values,asiarona$Population)
>
>[1] 1314151

# Fitted vs. Residuals Graph of Asia Coronavirus Linear Model

![Fitted vs  Residuals Graph of Asia Coronavirus Linear Model](https://user-images.githubusercontent.com/87962854/132267137-0d1bfe58-2049-4331-a5ed-81df15586032.png)

# Quantile-Quantile Plot of Original Asiarona Linear Model

![QQ Plot of Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267239-103ed02b-c979-4c4b-8d15-38e48f80a16a.png)

# Half-Normal Plot of Original Asiarona Linear Model

![Half-Norm Plot of Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267674-e43a5fea-7969-4bf7-92f8-260acfd56b54.png)

# Shapiro Test of Asiarona Linear Model

![Shapiro Test of Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267712-54b9f2b7-d776-42b8-9713-80c70a91adfc.png)

# Prediction Plot For Original Asiarona Linear Model

![Prediction Plot for Asiarona](https://user-images.githubusercontent.com/87962854/132267741-f1f472a6-bb5e-4dd2-966e-efc0f2e99459.png)

# Model Output Plot For Original Asiarona Linear Model

![Model Output Plot for Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267756-a6986a98-dff6-447f-b2b5-225f89ab204a.png)

# Logarithmic Prediction Plot For Original Asiarona Linear Model

![Logarithmic Prediction for Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267779-fe515ad5-a67b-4d05-a963-50dbac71e70a.png)

# Logarithmic Model Output Plot For Original Asiarona Linear Model

![Logarithmic Model Output Plot for Asiarona Linear Mode](https://user-images.githubusercontent.com/87962854/132267787-67c7e82d-08d9-44e8-80dd-4d07c67217bf.png)

# Plotted Relationship b/w the Logarithmic Prediction Plot & the Logarithmic Model Output Plot of the Original Asiarona Linear Model

![Plotted Relationship between Logarithmic Prediction   Logarithmic Model Output](https://user-images.githubusercontent.com/87962854/132267807-88f65401-3e31-4a84-8752-4994d8d830a2.png)

# Fitted vs. Residuals Graph of the Logarithmic Asiarona Linear Model

![Fitted vs  Residuals of Logarithmic Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267825-5d67ec5e-72a6-43f0-9192-567f3c2dc7dd.png)

# Quantile-Quantile Plot of the Logarithmic Asiarona Linear Model

![QQ Plot of Logarithmic Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267856-f26a3344-38a3-4212-84d2-b843b1f8a553.png)

# Half-Normal Plot of the Logarithmic Asiarona Linear Model

![Half-Norm of Logarithmic Asiarona Linear Model](https://user-images.githubusercontent.com/87962854/132267916-d9adee2f-2790-4adb-b152-c5a9ec778d8a.png)


# Citations

Link : https://www.worldometers.info/coronavirus/#countries

Upvote if you find it useful

> citation(package = 'readr')

To cite package ‘readr’ in publications use:

  Hadley Wickham and Jim Hester (2020). readr: Read
  Rectangular Text Data. R package version 1.4.0.
  https://CRAN.R-project.org/package=readr

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {readr: Read Rectangular Text Data},
    author = {Hadley Wickham and Jim Hester},
    year = {2020},
    note = {R package version 1.4.0},
    url = {https://CRAN.R-project.org/package=readr},
  }

> citation(package = 'corrplot')

To cite corrplot in publications use:

  Taiyun Wei and Viliam Simko (2021). R package
  'corrplot': Visualization of a Correlation Matrix
  (Version 0.90). Available from
  https://github.com/taiyun/corrplot

A BibTeX entry for LaTeX users is

  @Manual{corrplot2021,
    title = {R package 'corrplot': Visualization of a Correlation Matrix},
    author = {Taiyun Wei and Viliam Simko},
    year = {2021},
    note = {(Version 0.90)},
    url = {https://github.com/taiyun/corrplot},
  }

> citation(package = 'faraway')

To cite package ‘faraway’ in publications use:

  Julian Faraway (2016). faraway: Functions and
  Datasets for Books by Julian Faraway. R package
  version 1.0.7.
  https://CRAN.R-project.org/package=faraway

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {faraway: Functions and Datasets for Books by Julian Faraway},
    author = {Julian Faraway},
    year = {2016},
    note = {R package version 1.0.7},
    url = {https://CRAN.R-project.org/package=faraway},
  }

ATTENTION: This citation information has been
auto-generated from the package DESCRIPTION file and
may need manual editing, see ‘help("citation")’.

> citation(package = 'tidyverse')

  Wickham et al., (2019). Welcome to the tidyverse.
  Journal of Open Source Software, 4(43), 1686,
  https://doi.org/10.21105/joss.01686

A BibTeX entry for LaTeX users is

  @Article{,
    title = {Welcome to the {tidyverse}},
    author = {Hadley Wickham and Mara Averick and Jennifer Bryan and Winston Chang and Lucy D'Agostino McGowan and Romain François and Garrett Grolemund and Alex Hayes and Lionel Henry and Jim Hester and Max Kuhn and Thomas Lin Pedersen and Evan Miller and Stephan Milton Bache and Kirill Müller and Jeroen Ooms and David Robinson and Dana Paige Seidel and Vitalie Spinu and Kohske Takahashi and Davis Vaughan and Claus Wilke and Kara Woo and Hiroaki Yutani},
    year = {2019},
    journal = {Journal of Open Source Software},
    volume = {4},
    number = {43},
    pages = {1686},
    doi = {10.21105/joss.01686},
  }

> citation(package = 'broom')

To cite package ‘broom’ in publications use:

  David Robinson, Alex Hayes and Simon Couch (2021).
  broom: Convert Statistical Objects into Tidy
  Tibbles. R package version 0.7.8.
  https://CRAN.R-project.org/package=broom

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {broom: Convert Statistical Objects into Tidy Tibbles},
    author = {David Robinson and Alex Hayes and Simon Couch},
    year = {2021},
    note = {R package version 0.7.8},
    url = {https://CRAN.R-project.org/package=broom},
  }

> citation(package = 'psych')

To cite the psych package in publications use:

  Revelle, W. (2021) psych: Procedures for
  Personality and Psychological Research,
  Northwestern University, Evanston, Illinois, USA,
  https://CRAN.R-project.org/package=psych Version =
  2.1.6,.

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {psych: Procedures for Psychological, Psychometric, and Personality Research},
    author = {William Revelle},
    organization = { Northwestern University},
    address = { Evanston, Illinois},
    year = {2021},
    note = {R package version 2.1.6},
    url = {https://CRAN.R-project.org/package=psych},
  }

> citation(package = 'skimr')

To cite package ‘skimr’ in publications use:

  Elin Waring, Michael Quinn, Amelia McNamara,
  Eduardo Arino de la Rubia, Hao Zhu and Shannon
  Ellis (2021). skimr: Compact and Flexible Summaries
  of Data. R package version 2.1.3.
  https://CRAN.R-project.org/package=skimr

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {skimr: Compact and Flexible Summaries of Data},
    author = {Elin Waring and Michael Quinn and Amelia McNamara and Eduardo {Arino de la Rubia} and Hao Zhu and Shannon Ellis},
    year = {2021},
    note = {R package version 2.1.3},
    url = {https://CRAN.R-project.org/package=skimr},
  }

> citation(package = 'jmv')

To cite package ‘jmv’ in publications use:

  Ravi Selker, Jonathon Love and Damian Dropmann
  (2020). jmv: The 'jamovi' Analyses. R package
  version 1.2.23.
  https://CRAN.R-project.org/package=jmv

A BibTeX entry for LaTeX users is

  @Manual{,
    title = {jmv: The 'jamovi' Analyses},
    author = {Ravi Selker and Jonathon Love and Damian Dropmann},
    year = {2020},
    note = {R package version 1.2.23},
    url = {https://CRAN.R-project.org/package=jmv},
  }

ATTENTION: This citation information has been
auto-generated from the package DESCRIPTION file and
may need manual editing, see ‘help("citation")’.

> citation(package = 'MASS')

To cite the MASS package in publications use:

  Venables, W. N. & Ripley, B. D. (2002) Modern
  Applied Statistics with S. Fourth Edition.
  Springer, New York. ISBN 0-387-95457-0

A BibTeX entry for LaTeX users is

  @Book{,
    title = {Modern Applied Statistics with S},
    author = {W. N. Venables and B. D. Ripley},
    publisher = {Springer},
    edition = {Fourth},
    address = {New York},
    year = {2002},
    note = {ISBN 0-387-95457-0},
    url = {https://www.stats.ox.ac.uk/pub/MASS4/},
  }

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
