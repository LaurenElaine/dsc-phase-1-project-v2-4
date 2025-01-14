<img src='Images/Microsoft Studio Logo.png'>

# Microsoft Movie Studio Recommendations

Author: [Lauren Brown](mailto:lauren.elaine86@gmail.com?subject=Microsoft%20Studios%20Project)

## Overview
This project uses data analysis to understand the performance of movie productions through various performance metrics in an effort to inform Microsoft executives about the most financially viable opportunities to enter the movie industry.

## Business Understanding
In 2019, prior to the pandemic, movie box office sales were at $11B, and in that same year there were over 1 billion tickets sold to the various films released at the time. The industry is recovering as we grow in our understanding of how to navigate the current environment with the coronavirus still prevalent. This year, box office sales are projected to be in excess of $6B with almost 750M tickets sold. (The numbers - https://www.the-numbers.com/market/)

The leadership of Microsoft is eager to learn about the potential to enter the movie industry with financial success in the near term. This analysis works to provide insight into important metrics of financial and public interest performance within the movie industry to better inform the Microsoft executive team as they determine their clear path forward to be a new entrant into the well established movie industry.

## Data Understanding & Analysis
The information necessary to complete this detailed data analysis is gathered by various respected industry organizations. The datasets available for this analysis were sourced from the resources listed below:

### Data Source & Description
 - [Box Office Mojo](https://www.boxofficemojo.com)
     * This dataset includes information about movie financial performance with gross domestic and foreign box office sales. The dataset includes information for 3,387 different titles.
 - [Rotten Tomatoes](https://www.rottentomatoes.com)
     * Movie info dataset: This dataset includes information regarding a synopsis, runtime, the director and writer team, release date (Theater and DVD), the production studio, genre, and the rating of the film. Altogether, the dataset includes information for 1,560 different titles.
     * Reviews dataset: This dataset includes information for movie reviews and ratings, along with the critic who is reviewing. In total, this data set provides information for 54,432 entries.
 - [TheMovieDB](https://www.themoviedb.org)
     * This dataset includes information about the genre, language, popularity, and release date of the various movies represented. The dataset includes 26,517 entries.
 - [The Numbers](https://www.the-numbers.com)
     * This dataset includes information about the release date, production budget, and the domestic and international gross sales. The dataset includes 5,782 entries.
 - [IMDB](https://www.imdb.com)
     * Principals: This dataset relationally connects to the other datasets from IMDB through movie ID, and person ID. This data set also includes information particular to a person's role (e.g. if an actress is listed the category column shares the name of their character). This dataset has 1,028,186 entries.
     * Known for: This data set provides a list of each person available from the principals dataset and connects them to a movie that they are known for. In total this dataset has 1,638,259 entries.
     * Directors | Writers: These data sets house information for the writers and directors of films and what films they are associated with. Directors has 291,174 entries and writers has 255,873 entries.
     * Persons: This dataset includes personal identifiable information such as a persons birth and death year along with their profession. This dataset includes 606,648 entries.
     * Movie Basics: This dataset includes information to identify a movie's foundational details such as the year it was released, the runtime and the genre of the film. This dataset has 146,144 entries. 
     * Movie Ratings: This dataset includes information about movie rating and the number of votes received by reviewers. This dataset includes 73,856 entries.
     * Movie Akas: This dataset includes information about the movie region, language, type and attribute. This dataset includes 331,703 entries.

The analysis will further explore the information available from the datasets that will be used to better understand the critical metrics of performance that will inform the Microsoft executive teams next steps.

### Data Exploration and Interpretation

#### Profitability by Genre
This analysis worked to explore the profitability of genres within the movie industry. As Microsoft looks to enter the movie industry, pursuing films that have proven their profitability over time offers the potential for Mircosoft to pursue profitability more readily. In the visualization below we can see that the most profitable movie genres, in terms of average return on investment, are Musical, Music, and Animation films. 

Top Genre ROI:
 - Musical 471%
 - Music 307%
 - Animation 274%

As another layer of pursuing proven paths toward successful movie industry entry we will explore writers and directors who have proven profitability.

<img src='Images/ROI.png'>

#### Profitability by Directors and Writers
In an effort to mitigate risk, and possibly increase the likelihood of future profitability through return on investment, this analysis looked into which writers and directors in the most profitable genres had a portfolio that was also quite profitable. As you can see in the graphical representations below, within the Musical, Music, and Animation genres, the top writers and directors have return on investments of incredible measure. Aligning with these partners who have a proven track record for success could lend itself to great market entry.

<img src='Images/All_Directors_Global.png'>
<img src='Images/All_Writers_Global.png'>

As illistrated above, and particular to directos, Zane Burden, Bill Condon, and Marilyn Barnes have over a 900% ROI for Musical films, Stephen Daldry and Brett Sullivan have over a 2000% ROI for music films, and Kathik Candan has over a 12000% ROI for Animation films. Additionally, particular to writers, Stephen Chbosky, Evan Spiliotopoulos, and Linda Wollverton have over a 900% ROI for Musical films, Anthony McCarten and Peter Morgan have over a 1500% ROI for music films, and Akira Toriyama has over a 13000% ROI for Animation films. Partnership with these directors could be quite beneficial to explore.

#### Profitability by Release Date
Another aspect of the successful launch of Microsoft's entry into the movie industry is to understand, with confidence, when to release a film. As can be expected, there are seasonal impacts to a film's success. This analysis worked to understand what time of year is more ideal than others to release a film. As represented above, we now understand that the most profitable month that a film can be released, in terms of average return on investment, is in October. The visualization below helps us understand with greater awareness that October proves to have the highest potential for return on investment. In total, October boasts an ROI of 511%. 

<img src='Images/Month.png'>

As we learned from further analysis, of all days in October, the 1st day of the month has proved to be the most profitable day to release a film. In total, October 1st boasts an ROI of 3801%. 

<img src='Images/Day.png'>

## Conclusion
 1. From the information available, it appears that musical films provide the highest return for the committed budget. Music and animation films also provide higher profit. As Microsoft continues to evaluate their approach towards movie production, aligning with these genres could prove financially beneficial.
 2. As explored above, the musical, music, and animation genres as it relates to directors and writers profitability is high compared to other genres. 
     - As Microsoft explores their approach towards entering the movie industry they should consider working with the following directors.
         - Musical
             - Zane Burden
             - Bill Condon
             - Marilyn Barnes
         - Music
             - Stephen Daldry
             - Brett Sullivan
             - Damien Chazelle
         - Animation
             - Karthik Chandan
             - Kyle Balda
             - Tatsuya Nagamine
     - As Microsoft explores their approach towards entering the movie industry they should consider working with the following writers.
         - Musical
             - Stephen Chbosky
             - Evan Spiliotopoulos
             - Linda Woolverton
         - Music
             - Anthony McCarten
             - Peter Morgan
             - Reid Carolin
         - Animation
             - Akira Toriyama
             - Brenda Chapman
             - Jeff Nathanson
 3. Given the above analysis we can pinpoint an exact date of the year that lends itself to being profitable. October 1 would be a great day to target a release of a movie. More broadly focusing on having movies released in October would be beneficial. The months leading up to the holidays could also be considered as a more profitable time to release movies.

## For More Information
Below you will find links to important materials to support this analysis
 - [Jupyter Notebook](https://github.com/LaurenElaine/dsc-phase-1-project-v2-4/blob/master/Microsoft%20Movie%20Studio%20Recommendations.ipynb)
 - [Presentation](https://github.com/LaurenElaine/dsc-phase-1-project-v2-4/blob/master/PDFs/Presentation.pdf)

I welcome the ability to connect with you regarding any questions or further conversation regarding this analysis. You can contact me at the information provided below.
 - [Email](mailto:lauren.elaine86@gmail.com?subject=Microsoft%20Studios%20Project)
 - [LinkedIn](https://www.linkedin.com/in/lauren-brown-97944722a/)

## Repository Structure
This repository's structure is outlined below for ease of access. The images and data files are available for reference. The .gitignore files maintains a list of files that are to be ignored for this repository due to irrelavance or the files large size. The PDFs folder holds renderings of the GitHub repository, jupyter notebook, readme file, and presentation in a more accessible and readable format. The readme file along with the materials in the PDFs folder provide a summary of the in depth analysis outlined in the jupyter notebook file. 

```bash
├── Images
├── PDFs
├── zippedData
├── .gitignore
├── Microsoft Movie Studio Recommendations.ipynb
├── Microsoft Movie Studio Recommendations.pdf
└── README.md
```