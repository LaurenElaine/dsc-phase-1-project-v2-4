![Microsoft%20Studio%20Logo-2.png](attachment:Microsoft%20Studio%20Logo-2.png)

# Microsoft Movie Studio Recommendations

Author: [Lauren Brown](mailto:lauren.elaine86@gmail.com?subject=Microsoft%20Studios%20Project)

## Overview
This project uses data analysis to understand the performance of movie productions through various performance metrics in an effort to inform Microsoft executives about the most financially viable opportunities to enter the movie industry.

## Business Understanding
In 2019, prior to the pandemic, movie box office sales was at $11B, and in that same year there were over 1 billion tickets sold to the various films released at the time. The industry is recovering as we grow in our understanding of how to navigate the current environment with the coronavirus still prevalent. This year, box office sales are projected to be in excess of $6B with almost 750M tickets sold. (The numbers - https://www.the-numbers.com/market/)
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
     * Principals: This dataset relationally connects to the other datasets from IMDB through movie ID, and person ID. This data set also include information particular to a persons role (e.g. if an actress is listed the category column shares the name of their character). This dataset has 1,028,186 entries
     * Known for: This data set provides a list of each person available from the principals dataset and connects them to a movie that they are known for. In total this dataset has 1,638,259 entries.
     * Directors | Writers: These data sets house information for the writers and directors of films and what films they are associated with. Directors has 291,174 entries and writers has 255,873 entries.
     * Persons: This dataset includes personal identifiable information such a persons birth and death year along with their profession. This dataset includes 606,648 entries.
     * Movie Basics: This dataset includes information to identify a movie's foundational details such as the year it was released, the runtime and the genre of the film. This dataset has 146,144 entries. 
     * Movie Ratings: This dataset includes information about movie rating and the number of votes received by reviewers. This dataset includes 73,856 entries.
     * Movie Akas: This dataset includes information about the movie region, language, type and attribute. This dataset includes 331,703 entries.

The analysis will further explore the information available from the datasets that will be used to better understand the critical metrics of performance that will inform the Microsoft executive teams next steps.

### Data Exploration and Interpretation

![ROI](/Users/laurenbrown/Documents/Flatiron/Phase_1/Project/dsc-phase-1-project-v2-4/Images/ROI.png)

![July](/Users/laurenbrown/Documents/Flatiron/Phase_1/Project/dsc-phase-1-project-v2-4/Images/Month.png)

![Day](/Users/laurenbrown/Documents/Flatiron/Phase_1/Project/dsc-phase-1-project-v2-4/Images/Day.png)


## Conculsion

 - From the information available, it appears that musical films provide the highest return for the committed budget. Music and animation films also provides higher profit. As Microsoft continues to evaluate their approach towards movie production, aligning with these genres could prove financially beneficial.
 - As explored above, the musical, music, and animation genres as it relates to directors and writers profitability is high compared to other genres. As Microsoft explores their approach towards entering the movie industry they should consider working with the following directors.
     - Musical
         - Steven Spielberg
         - Zane Burden
         - Bill Condon
         - Marilyn Barnes
         - Razvan Dinca
         - Brad Dalton
         - Chance Taylor
     - Music
         - Damien Chazelle
         - Anthony Nardolillo
         - Elizabeth Banks
         - Vanja Kovacevic
         - Geoffrey Cox
         - Stephen Daldry
         - Brett Sullivan
         - Bryan Singer
         - Vanja Kovacevic
     - Animation
         - Karthik Chandan
         - Jon Favreau
         - Yarrow Cheney
         - Greg Tiernan
         - Phil Lord
         - Kyle Balda
         - Tatsuya Nagamine
         - Eric Guillon
 - As Microsoft explores their approach towards entering the movie industry they should consider working with the following writers.
     - Musical
         - Tony Kushner
         - Stephen Chbosky
         - Evan Spiliotopoulos
         - Linda Woolverton
         - Ernest Fazekas
         - Paul Gordon
     - Music
         - Fred Lozano
         - Ahmadu Garba
         - Corey Deshon
         - Heidi McLaughlin
         - Gayle Forman
         - Anthony McCarten
         - Peter Morgan
         - Reid Carolin
     - Animation
         - Linda Woolverton
         - Brenda Chapman
         - Jeff Nathanson
         - Evan Goldberg
         - Ariel Shaffir
         - Akira Toriyama
         - Jonathan Roberts
- Given the above analysis we can pinpoint an exact date of the year that lends itself to being profitable. July 10 would be a great day to target a release of a movie. More broadly focusing on having movies released in July would be beneficial. The months leading up to the holidays could also be considered as a more profitable time to release movies.

## For More Informaiton
Below you wilol find links to imporatant materials to support this analysis
 - [Jupyter Notebook](https://github.com/LaurenElaine/dsc-phase-1-project-v2-4/blob/master/Microsoft%20Movie%20Studio%20Reommendations.ipynb)
 - Link to PDF
 - Link to presentation

I welcome the ability to connect with you regarding any questions or further conversation regarding this analysis. You can contact me at the information provided below.
 - [Email](mailto:lauren.elaine86@gmail.com?subject=Microsoft%20Studios%20Project)
 - [LinkedIn](https://www.linkedin.com/in/lauren-brown-97944722a/)

## Repository Structure
This repository's strucutre is outlined below for ease of access. The images and data files are available for reference. The readme file and presentation file provide a summary of the indepth analysis outlined in the jupyter notebook file. 

├── ZippedData
├── Images
├── README.md
├── Microsoft Movie Studio Recommendations.pdf
└── Microsoft Movie Studio Recommendations.ipynb