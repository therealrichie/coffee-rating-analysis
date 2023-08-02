# coffee-rating-analysis
Tidy Tuesday Analysis

In the last two years, coffee has became a hobby and I really enjoy being able to taste the different flavor profiles of different beans while adjusting various variables in order to make the perfect cup of coffee. Today, we'll be diving into one of those variables and looking at the different ratings of beans from around the world from the weekly Tidy Tuesday data project. <https://github.com/rfordatascience/tidytuesday/blob/master/data/2020/2020-07-07/readme.md>.

This analysis will look at:
- Top 20 countries by cupping points
- Coffee quality between 2010 to 2018 based on the mean cupping points per year.
  - First time using extract function to get year from the full date the coffee was reviewed
- Altitude and quality of coffee
  - Using a correlation test to explore the relationship