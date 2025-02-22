# Disney_Movie_Analysis

In this work, I analyzed the  `Disney`  dataset to answer the following research questions:

-   (1) In which  `decade`  (e.g., 1990, 2000, etc.) was the  **most Disney movies released**?
    -   Data-permitting, what was the  **most common**  `genre`  of Disney movie in that  `decade`?
-   (2) In which  `decade`  (e.g., 1990, 2000, etc.) was the  **highest inflation-adjusted gross revenue**  from Disney movies?
    -   Data-permitting, what  `genre`  of Disney movie generated the  **most revenue**  in that  `decade`?

### Primary Analysis

Exploratory analysis of the  `disney_movies_total_gross.csv`  dataset was conducted to identify in which decade the most Disney movies were released (_Figure 4_). This was followed by identifying the decade with the highest grossing revenue (_Figures 5, 7_). For both,  `1990`  was identified, generating over $17 billion across  `236`  movies in that decade. In fact, the  `1990s`  (1989 to 1999) was a period in the company's history referred to as the  **"Disney Renaissance"**. During this time, Walt Disney Feature Animation proceeded to produce some of its most critically acclaimed and commercially successful movies compared to past Disney movies. The studio turned back to making more musical animated films that were mostly based on well-known stories, including  `Beauty and the Beast`  (`1991`),  `Aladdin`  (`1992`), and  `The Lion King`  (`1994`). These movies were in fact the top grossing (inflation-adjusted) movies of the  `1990s`  within the  `Musical`,  `Comedy`, and  `Adventure`  genres, respectively (_Tables 9, 11-12_).

### Future Work

When viewing the distribution of total inflation-adjusted gross revenue in  `movie_revenue_plot`, there initially appeared to be a decreasing trend in gross revenue between  `1930`  and  `1970`  (_Figure 3_), which was contrary to the increasing trend of movies released within that timeframe (_Figure 2_). However, between  `1970`  up until  `1990`, we see a sharp upward trend in both the number of movies released as well as gross revenue. While the  **Disney Renaissance**  explains the historical significance of the trends we observed in the  `1990s`, further analyses is required to understand the trends between  `1930`  and  `1970`. For instance, insights could be derived from exploring whether the genre type of movies varied significantly throughout that time. Repeating the analyses of this work within that timeframe will provide further insight on the number of movies, type of genres, and gross revenue generated in those periods. Comparisons can then be drawn to this work to see the differences between time periods that marked the  `1990s`  **"Renaissance"**  period of Disney's rise as its most successful era.

### Limitations

A limitation of this dataset was that the  **release dates**  for  `2010`  span until  `Dec-16-2016`. Thus, the  **total inflation-adjusted gross revenue**  in the  `2010s`  may be underreported as the  **movie_revenue**  table does not contain the list of movies released between then and  `2020`.

# References

Not all the work in this notebook is original. Some parts were borrowed from online resources where specified. I take no credit for parts that are not mine. They were soley used for illustration purposes.

## Resources used

-   [Data Source](https://data.world/kgarrett/disney-character-success-00-16)
    
    -   This Disney database used in this work was curated by  **Kelly Garrett**.
-   [Altair Documentation](https://altair-viz.github.io/gallery/bar_chart_with_labels.html)
    
    -   This example shows a basic horizontal bar chart with labels created with altair.
-   [Stack Overflow Inquiry](https://stackoverflow.com/questions/17764619/pandas-dataframe-group-year-index-by-decade)
    
    -   The adapted approach described in this page is by user  **DSM**.
-   [Stack Overflow Inquiry](https://stackoverflow.com/questions/66603854/futurewarning-the-default-value-of-regex-will-change-from-true-to-false-in-a-fu)
    
    -   The adapted approach described in this page is by user  **Ryszard Czech**.
-   [Stack Overflow Inquiry](https://stackoverflow.com/questions/66603854/futurewarning-the-default-value-of-regex-will-change-from-true-to-false-in-a-fu)
    
    -   This example shows how the order encoding for a scatter plot can be used to draw a custom path.
