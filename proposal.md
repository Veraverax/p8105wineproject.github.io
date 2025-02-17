Final Project Proposal
================
Vera Xu (yx2578), Tianheng Hu (th2533), Helen Zhang (hlz2108), Yuanxin
Zhang (yz3736)

#### The tentative project title

*Wine Rating - What’s behind great wines?*

#### The motivation for this project

This dataset offers us a great opportunity to explore what factors are
associated with wine ratings. We hope to conduct regression analysis of
the wine rating and price based on location/grape type/notes/region and
see if there are significant difference among these categorical
predictors. The regression model would help customers estimate and
predict wine rating with a series of wine characteristics. We also want
to provide people with a interactive website to visualize wine ratings
and prices.

#### The intended final products

There will be four main sections in the final website. The first would
be a descriptive statistics and static visualization page. The second
part will be the regression analysis results. The third part will be
interactive plots showing detailed information of wine characteristics.
The fourth part will be a world map with wine rating information.

#### The anticipated data sources

The data for this project is downloaded from
<https://www.kaggle.com/zynicide/wine-reviews>. It was scraped on
November 22nd, 2017 from the [WineEnthusiast Rating
database](https://www.winemag.com/?s=&drink_type=wine). It contains 130k
wine reviews with variety, location, winery, price, description and
reviewer information.

#### The planned analyses / visualizations / coding challenges

##### Data Cleaning

1\) Work with NA variables；2) Categorize white/red/other wine type; 3)
Extracting flavor/notes info from the text description; 4) Recode
categorical variables for regression analysis

##### Visualization

  - Static plot: 1) Distribution of price/rating by region; 2)
    Distribution of price/rating by grape typ; 3) Distribution of rating
    by reviewer (TBD)

  - Interactive Map: 1) Generate coordinate data from city/region; 2)
    Use shiny for user preference specific viewing; 3) Plot the wine
    info within a global map

##### Regresssion Analysis

  - Outcome variable - rating: Run a multiple linear regression model
    with wine rating on several predictors (price/grape
    type/winery/flavor/region) and conduct regression diagnostics

  - Outcome variable - price: Run a multiple linear regression model
    with wine price on several predictors (rating/grape
    type/winery/flavor/region) and conduct regression diagnostics

##### Coding Challenges:

1\) Extract notes information from text description; 2) Generate
coordinates using packages; 3) Level of significance of the regression
model; 4) Dealing with missing/duplicate data

#### The planned timeline

| Phase    | Deliverables/Milestone | Date        |
| -------- | ---------------------- | ----------- |
| 0        | Project Proposal       | 11/07       |
| 1.1      | Data Cleaning          | 11/08-11/10 |
| 1.2      | Exploratory Analysis   | 11/10-11/18 |
| 1.3      | Visualization          | 11/10-11/18 |
| check-in | Review Meeting         | **TBD**     |
| 1.4      | Statistical Modeling   | 11/10-11/25 |
| 1.5      | Interactive Map        | 11/19-11/25 |
| 2.1      | Finalize Report        | 11/30-11/04 |
| 2.2      | Finalize Webpage       | 11/30-12/04 |
| 2.3      | Record Screencast      | 12/02-12/04 |
| 3        | Peer Assessment        | 12/04       |
| 4        | In-class Discussion    | **TBD**     |
