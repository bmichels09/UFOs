# UFOs

## Overview of Project
This project is to create a website that displays data on UFO sightings, with various filters available.

## Results
To use the site, scroll down to the bottom and view the data table.  By default, all the data is shown.

![Default Table](/static/images/DefaultTable.png)

You can narrow down the results by using the filters on the left side of the page.  To apply a filter, type a value into the appropriate text box, then press Enter, press Tab, or click anywhere outside of the text box.

For example, filtering the results to only show those from 1/5/2010 looks like this:

![Table Filtered By Date](/static/images/TableWithDateFilter.png)

You can repeat the process in other fields to apply multiple filters at once.  If you want only results from 1/5/2010 with a cigar shape, it would look like this:

![Table With Multiple Filters](/static/images/TableWithMultipleFilters.png)

To clear a filter, remove the text from the appropriate text box, then press Enter, press Tab, or click anywhere outside of the text box.

## Summary

One drawback of this design is that you need to remove focus from the text box in order to apply the filter, and that's less intuitive than clicking an Apply Filter button.

Further development could include a filter for Duration, or formatting the data so city, state, country, and shape are capitalized.