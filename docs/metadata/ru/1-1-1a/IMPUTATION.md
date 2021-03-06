---
title: "Field: IMPUTATION"
layout: field
parent: OTHER_METHOD
language: ru
indicator: 1-1-1a
slug: IMPUTATION
---
## Treatment of missing values

* **At country level**

    There is no “imputation” in the traditional sense for missing country data. However, to generate regional and global aggregates for reference years, country-level data are imputed for the years when surveys are not conducted. These imputed data are to be used for aggregation, but not for replacing the actual survey data. The subsequent section on the treatment of missing values at the regional and global levels provide more details on the imputation method.
* **At regional and global levels**

    To compare the poverty rates across countries and compute regional aggregates, country estimates must be “lined up” first to a common reference year, interpolating for countries in which survey data are not available in the reference year but are available either before, after, or both. The more survey data are available (that is, the more data for different years), the more accurate the interpolation.

    The process requires adjusting the mean income or expenditure observed in the survey year by a growth factor to infer the unobserved level in the reference year. Thus, two assumptions are required to implement this process: distribution-neutral growth and a real rate of growth between the survey and reference year.

    Distribution-neutral growth implies that income or expenditure levels are adjusted for growth assuming that the underlying relative distribution of income or expenditure observed in survey years remains unchanged. Under this assumption, it is straightforward to interpolate the poverty estimate in a given reference year implied by a given rate of growth in income or expenditure. Rates of change in real consumption per capita should be based on the change in real consumption measured by comparing country survey data across different years. In practice, however, survey data in most countries are not available on an annual basis. Therefore, the change in private consumption per capita as measured from the national accounts is used instead. While, there can be no guarantee that the survey-based measure of income or consumption change at exactly the same rate as private consumption in the national accounts, this appears to be the best available option.

    When the reference year falls between two survey years, an estimate of mean consumption at the reference year is constructed by extrapolating the means obtained from the surveys forward and backward to the reference year. The second step is to compute the headcount poverty rate at the reference year after normalizing the distributions observed in the two survey years by the reference year mean. This yields two estimates of the headcount poverty rates in the reference year. The final reported poverty headcount rate for the reference years is the linear interpolation of the two. When data from only one survey year are available, the reference year mean is based on the survey mean by applying the growth rate in private consumption per capita from the national accounts. The reference year poverty estimate is then based on this mean and on the distribution observed in the one survey year. The better data coverage is in terms of number and frequency of available surveys, the more accurate this lining-up process is and the more reliable the regional estimates will be.

    The aggregate headcount ratio for a region is the population-weighted mean of the headcount indices across the countries in that region. The number of poor in each region is the product of the region’s headcount index and total regional population. This assumes that the poverty rate for a country without a household survey is the regional average.