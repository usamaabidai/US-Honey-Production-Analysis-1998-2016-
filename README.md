# US Honey Production Analysis (1998-2016)

## Project Overview
This project analyzes trends in honey production across the United States from 1998 to 2016, a period marked by significant challenges including Colony Collapse Disorder. The analysis examines production yields, state-level trends, and the relationship between production volumes and market values to understand the changing landscape of American honey production.

## Background
In 2006, global concern was raised over the rapid decline in honeybee populations, which are vital to American agriculture. Large numbers of hives were lost to Colony Collapse Disorder—a phenomenon where worker bees disappear, causing entire colonies to collapse. While the exact causes remain debated (ranging from diseases to pesticides), the impact on honey production has been significant.

Historically, the U.S. produced over half of its honey consumption domestically. However, the landscape has shifted dramatically, with approximately 350 of the 400 million pounds of honey consumed annually now coming from overseas imports.

## Dataset Description
The analysis uses data on U.S. honey production from 1998 to 2016, with the following variables:

- **State**: U.S. states where honey is produced
- **year**: Year of production (1998-2016)
- **stocks**: Stocks held by producers (in pounds)
- **numcol**: Number of honey-producing colonies
- **yieldpercol**: Honey yield per colony (in pounds)
- **totalprod**: Total honey production (numcol × yieldpercol) in pounds
- **priceperlb**: Average price per pound (in dollars)
- **prodvalue**: Value of production (totalprod × priceperlb) in dollars

## Key Findings

### Production Trends
- Total honey production has declined significantly over the studied period (1998-2016)
- The decline in production is primarily attributed to decreasing yields per colony
- Despite fewer colonies, the impact on production has been compounded by reduced productivity per colony

### State-Level Analysis
- The major honey-producing states are California, Florida, North Dakota, South Dakota, and Montana
- Florida demonstrates particularly efficient honey marketing and sales strategies
- Regional variations show different adaptation rates to changing conditions

### Economic Patterns
- As production has declined, the value per pound of honey has increased substantially
- The inverse relationship between production and price suggests significant market adaptation
- The total value of production has remained more stable than production volumes, indicating price elasticity

## Methods Used
- Time series analysis
- Geospatial data visualization
- Statistical correlation analysis
- Trend decomposition
- Comparative state analysis

## Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## License
This project is licensed under the MIT License - see the LICENSE file for details.
