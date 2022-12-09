# UFOs

## Analysis
### Overview
The purpose of this project was to create a webpage with filtering capabilites to store and view UFO sighting data. This project used HTML, Javascript, Bootstrap, & CSS.

### Results
There are 5 filters to choose from: Date, City, State, Country, and Shape. One can use a single filter or mutliple to change the view of the data table.

- Homepage (unfiltered)
  - ![homepage](Resources/unfiltered_homepage.png)

Below are some examples of filter use:
- Date
  - ![date](Resources/filtered_date.png)
- City
  - ![city](Resources/filtered_city.png)
- State
  - ![state](Resources/filtered_state.png)
- Country
  - ![country](Resources/filtered_country.png)
- Shape
  - ![shape](Resources/filtered_shape.png)
- Multiple filters
  - ![multiple_filters](Resources/filtered_multiple.png)

### Summary
- Drawbacks: 
  - The filters take any input, even if it is not in the data, resulting in empty tables if the user does not choose correctly. The filters are also case sensitive, which will return 0 results, even if the filter chosen has data.
    - For example, if I search "los angeles" under the city filter, I will get 0 results.
- Recommendations:
  - Make the filter bars, not case sensitive to improve user experience & reduce potential frustrations.
  - Adjust the filters to show only possible outcomes in the data via some kind of auto-fill function or drop down menu option.