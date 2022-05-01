# UFOs

**Overview of Project** 

The purpose of this module is to effectively make any webpage interactive through the combination of JavaScript and HTML. By implementing filters on our webpage that displays UFO sightings around the world, users can quickly skim the site to get their desire dataset. The module shows how to do a simple filtering of the date followed by creating a functional button for the webiste so the results can properly update. The challenge is for the programmer to make a more sophisticated filter setup through use of functions and for loops.

**Results**

![Overall](https://user-images.githubusercontent.com/99565016/166168651-94ecb101-b6c3-45fc-aa29-5366e651739e.PNG)

***Figure 1: Overall unfiltered data with search bar***

As seen in Figure 1, we can see that the entire dataset is presented without any of the filters activated. Any user who is interested can filter through the data with ease by typing in the filter search, as seen on the left side. For ease of use, the website has pre-written words so that users know the format that should go in for proper use of the filter.  

![Filtered_data](https://user-images.githubusercontent.com/99565016/166168733-5f39fd32-a5c8-4292-9220-46d45da91399.PNG)

***Figure 2: Filtered data with filter search bar***

In Figure 2, the "Date" and "State" filter has been applied to the data set, which displays a total of 3 rows. Having filters save the user(s) time as they do not need to skim through the website when they can quickly grab what they need. The interactive website provides a dynamic experience for anyone interested in Dana's website as opposed to looking at a .JSON file. 

Instructions:
1. Type in the respective filter search bar of interest in the exact manner that is displayed in the raw dataset. The JavaScript is not smart enough to filter properly through autocorrect. 
2. When the filters have been properly typed in, click on the filter bar in order to execute the filter.
3. Viola! The website is presenting the exact dataset of interest to the user
4. To remove a filter, simply delete the keyword in the filter search bar and click on said filter search bar to refresh the page.


**Summary**

Drawback:
Though the webpage is functioning and provides users the properly filtered dataset, the page is not perfect. For example, the keyword in the filter search bar needs to be exactly as presented in the dataset. If there is a typo in the dataset, the JavaScript program will skip pass the dataset and therefore will not present the data in the results. 

Recommendations:
There is room for improvement on Dana's website. For starters, the programmer can add a drop-down menu to the search bar to ensure that the filter is properly displaying the data. 
Another recommendaiton for the website is to allow filters to have space in the filter search bar ignored. If the user types "1/4/2010   " instead of "1/4/2010", then the website will display a blank result page. 
Lastly, the filter button should return to ensure an easy way to update the filter as clicking on the filter search bar is not a very friendly experience.

Overall, this is a good start of a website and will need further updates as there is always room for improvement.





