# UFOs

## Project Overview:

The Purpose of this project is to build a webpage and dynamic table are working as intended, with more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time, such as the event date, city, state, country, and shape, the source of data [](). To do this we use the following technologies:
- Chrome De vTools
- JavaScript:
- HTML
- CSS
- VS Code 
- BootStrap 4.0.0.

## Results

Using JavaScript and HTML, we build the webpage and create the dynamic table that contains all the information needed. In addition, we use multiple criteria to filters the table, the event of date, city, state, country, and shape. Filter UFO sightings on multiple criteria:
This task is done through the following steps:
- There are five list elements for filtering in the index.html file.

![image](https://user-images.githubusercontent.com/62036983/144352366-a4ad4da3-37ee-4472-98d4-795e3a63e297.png)

- The event listener is modified to detect changes to each filter in the app.js file. 

![image](https://user-images.githubusercontent.com/62036983/144351993-328da3f8-d5cf-424f-b829-0e0109676b32.png)

- The updateFilters() function saves the element, value, and the id of the filter that was changed. 

![image](https://user-images.githubusercontent.com/62036983/144352027-e3e04e00-1961-4fec-8179-1f968a31e9be.png)

- The filterTable() function loops through all of the filters and keeps any data that matches the filter values.

![image](https://user-images.githubusercontent.com/62036983/144352059-ae1ca2bd-90e8-4eaf-829f-3a17f2419ed3.png)

- The webpage filters the table correctly based on user.

![image](https://user-images.githubusercontent.com/62036983/144352109-646ffb60-7969-429f-8877-ea7ec4ed5bfc.png)

 
## Summary:
### Drawbacks
- The drawback of this webpage it is defficult for the user to find what parameter to use for filtering.
### Recommended Actions
- Use drop-down lists including all filter values in place of the input fields.
- Add button to clear the filters at the botton.

