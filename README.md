# UFOs

Create a website for UFO enthusiasts with information about sightings of UFOs in January 2010 that can be filtered by date, city, state, country, and shape.


## Overview of the analysis

The goal of this project is to create a UFO webpage with a dynamic table that enables users to simultaneously filter for several parameters for a fictitious client named "Dana." HTML, CSS, and JavaScript were used to create this website.

## Resources 
### Data Sources: 
We used the following [data.js](/static/js/data.js) to create the website.

### Softwares:
![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/bootstrap-%23563D7C.svg?style=for-the-badge&logo=bootstrap&logoColor=white)


## Results

A glimpse of the completed website:

![website.png](/static/images/website.png)

### Navigating UFO Sights

- Filter your search by date, city, state, county, or shape

We will use the below filters to filter out the UFO Sightings in the United States and Canada.

![website_filters.png](/static/images/website_filters.png)

- Search Results

As we filtered for sighting in "CA" in the Province "ON" when we enter the data in the filter column, it updates the data automatically and displays the results as below.

![website_results.png](/static/images/website_results.png)

## Summary


#### Drawback
The flaw with this design is that the user must be aware of the filter's parameters before using it.

#### Recommendations
- Frst remomendation to address the above drawback is drop-down lists with value outputs in each filter.
- For the entry results, create multiple pages that can be filtered too as 25, 50, 100, etc.
- Added total number of filtered results from the total number of results from the [data.js](/static/js/data.js).

        <!-- recommendation-->
                            <!-- Info on number of elements of the table currently filtered -->
                            <li class="list-group-item bg-dark" style="font-family: inherit; font-size: 1rem;">
                                <p style="color:#FFFFFF"> Showing <span id='filter'></span> of <span id='total'></span> sightings.</p>                       
                            </li>
