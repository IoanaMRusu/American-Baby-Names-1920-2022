# American Baby Names 1920-2022
An open data of Popular Baby Names made by the United States Social Security Administration (SSA) that provides insights on naming trends among time.

![BabyNamesProjectOverview](https://github.com/IoanaMRusu/American-Baby-Names-1920-2022/assets/144055123/be467f61-c1b1-46cd-ac0d-9482721a8266)

# Data
*https://www.ssa.gov/oact/babynames/*

We'll be working with data provided by the United States Social Security Administration, which lists first names along with the number and sex of babies they were given to in each year. For processing speed purposes, we've limited the dataset to first names which were given to over 5,000 American babies in a given year. Our data spans 101 years, from 1920 through 2020.

<h3 id="Baby Names"><code>baby_names</code></h3>
<table>
<thead>
<tr>
<th style="text-align:left;">column</th>
<th>type</th>
<th>meaning</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;"><code>year</code></td>
<td>int</td>
<td>Year</td>
</tr>
<tr>
<td style="text-align:left;"><code>first_name</code></td>
<td>varchar</td>
<td>First Name</td>
</tr>
<tr>
<td style="text-align:left;"><code>sex</code></td>
<td>varchar</td>
<td>Sex of babies given first_name</td>
</tr>
<tr>
<td style="text-align:left;"><code>num</code></td>
<td>int</td>
<td>Number of babies of sex given first_name in that year</td>
</tr>
</tbody>
</table>

# Key Findings

- Throughout 103 years most popular names given to babies were: James, John, William, David, Joseph, Thomas, Charles and Elizabeth.
- Top 5 boys names in 2022: Liam, Noah, Oliver, James, Elijah.
- Top 5 girls names in 2022: Olivia, Emma, Charlotte, Amelia, Sophia.

# Visualization
*https://public.tableau.com/app/profile/ioana.rusu2529/viz/BabyNameTrendsinU_S_A/BabyTrendsName*
