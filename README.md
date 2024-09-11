# Introduction

![A soccer pitch for an international match.](soccer-pitch.jpg)

Extensive experience with both men's and women's international soccer matches leads to the gut instinct that more goals are scored in women's international football matches than in men's. This could form the basis of an interesting investigative article that subscribers are likely to appreciate, but a valid statistical hypothesis test is necessary to confirm this.

While scoping the project, it is acknowledged that the sport has evolved significantly over the years, and performances likely vary depending on the tournament. Therefore, the analysis is limited to only official FIFA World Cup matches (excluding qualifiers) since 2002-01-01.

Two datasets have been created, containing the results of every official men's and women's international football match since the 19th century, scraped from a reliable online source. The data is stored in two CSV files: women_results.csv and men_results.csv.

The question being investigated is:

Are more goals scored in women's international soccer matches than in men's?

A 10% significance level is assumed for the analysis, with the following null and alternative hypotheses:

H₀: The mean number of goals scored in women's international soccer matches is the same as in men's.

Hₐ: The mean number of goals scored in women's international soccer matches is greater than in men's.

# Conclusion 
The p-value is greater than 0.01, the alternative hypothesis—that the mean number of goals scored in women's international soccer matches exceeds that in men's—must be rejected
