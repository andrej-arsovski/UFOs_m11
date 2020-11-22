# UFO Sighting Database

## Project Overview
This project aims to provide an accessible repository of UFO sightings, empowering citizen scientists with the ability to study, research, and visualize data that has already been gathered. The sightings data is able to be filtered on 5 parameters: Date, City, State, Country, and Shape. JavaScript is used to filter the data on the html page. 

## Results

The following is a brief description of how to use this website efficiently and what to expect from the filtered results.

### 1. Landing Page
When first landing on the page the user is greeted by the title "UFO Sightings: Fact or Fancy? Ufologists Weigh In" and short description of the site. The filters and data take up the majority of the rest of the page. By default the entire data table is loaded.

![landing_page.png](https://github.com/andrej-arsovski/UFOs_m11/blob/main/landing_page.png)

### 2. Data and Filters
Below the title and description the user can find the five filters (yellow) and data table (red). The filters have empty fiels (green) which have placeholders that diplay the correct input form for each filter.

![filter_table.png](https://github.com/andrej-arsovski/UFOs_m11/blob/main/filter_table.png)

### 3. Filtering

The data can be filtered in any order, the user simply inputs information into the desired filter(s) and hits 'enter' and the page will refresh, filtering the data table for the desired parameter. In this example the first filtering is done by state. To see all the sighting in California, the user enters the 2 letter state code (in theis case 'ca') in the State filter. The data table will then show only those sightings that took place in California.

![state.png](https://github.com/andrej-arsovski/UFOs_m11/blob/main/state.png)

In this example the data is further filtered based on the shape of the sighting ('light'). Now the data is filtered for sightings that occurred in California and whose shape was described as 'light'.

![state_shape.png](https://github.com/andrej-arsovski/UFOs_m11/blob/main/state_shape.png)

Finally, the data in this example is filtered by the date ("1/4/2010") and the data subsequnetly narrows down the data further to show only those sightings that occured on January 4th, 2010.

![state_shape_date](https://github.com/andrej-arsovski/UFOs_m11/blob/main/state_shape_date.png)

The user does not have to enter filter fields one at a time. All filter fields can be filled in before the table is filtered.

## Conclusion

### Webpage drawback 
While this page will no doubt prove useful to UFO enthusiasts one drawback is that each filter field can only take in a single entry. For example, the date filter cannot filter for a range of years. Similarly, we cannot view results for multiple states simultaneously. 

### Future improvements

1. Improving the shape filter: to maximize the utility of this filter a reference list of possible 'shapes' in the data need to be provided otherwise the user may find it difficult to find shape matches by simple phrase trial and error.


2. Adding a user submission field: Allowing users to input sightings into the data will prove a valuable resource for the community. Of course these submissions would have to be appropriately vetted before becoming part of the data.
