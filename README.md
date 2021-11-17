# Sharepoint Change Column Grouping Order
Change the order of Column Grouping in a SharePoint List
![Screen Shot 2021-11-17 at 12 38 27 PM](https://user-images.githubusercontent.com/33647356/142253347-dd9dd39d-c8f8-428a-ab09-c6c970de6715.png)

Normally in Sharepoint when you group by a column you can only choose from Ascending or Descending.

I had the need to group by a Status but I wanted New at the top followed by Pending, Completed and then Rejected

To accomplish this I created a Status column with various statuses and a calculated column to assign a number value to each status in the order I would like to view them.

I group by the calculated column and then format the JSON to change the numbers back to text in the group headings.

(This is just for my own memory - In case someone actually sees this just message me and I will provide actual instructions :) )
