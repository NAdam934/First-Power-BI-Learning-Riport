# First-Power-BI-Learning-Riport
My very first report, created during my first Power BI course
During this course I learned how to use most of the features of Power BI.

First of all the Power Query editor was presented. In Power Query, I learned how to transform data, append and merge tables, and generate new columns and new tables, such as calendar table.

Then I got to know about the DAX language, some important functions like IF(), SWITCH(), SUMX(), FILTER(). Moreover I made different measures, which I could use in the visualisations on the reports.

Last but not least I learned advanced reporting tools for example Bookmarks, Action buttons, Unique tooltips.

-------------------------------------------------------------------------------------------------------------
Report structure

First page called, "Osszesito" (English: 'Summary') is sat as landing page of the report. Its contains data from all regions.
The second tab called "Belfold" (in English 'Domestic') and the third one is named "Kulfold" (in English 'International'). The last two pages "TT1" and "TT2" are used for tooltips only and these are set as hidden.

On the first three pages you can find the main KPIs as Sum Revenue, Sum Expense and Profit. Below it there is a treemap with product categories and their size is depend on their Sum Revenue. The treemap interactions on other visuals are set to filter mode, and not highlight.
On the left there is a filter icon which connected with a Bookmark, and here are a grey transparent rectangle, because the filter panel has been separated from the other side of the report. The user can filter by paying method or region or customer.
There are three different visualisation which are showing the total revenue filtered by products, regions, and comparison between domestic and international revenue. Finally there is a matrix table which is showing the revenue, expense and profit by customers

If the user hoover the cursor over a bar from the bar chart or over a slice from the donut chart, one of the two tooltips will be appear next to the cursor. Also in the TT1 the title of the ÖsszErtekesites and the Profit will change depending on which category has been pointed on.

The second and third pages are similar to the main page, but the Legends of the donut chart are set to the domestic cities on the second page and a filter for the countries has been set to Hungary on this page. And on the 'International' page also the legends of the donut chart has been set to country names, and a filter for the countries has been set to not Hungary. Moreover I sat a year filter on 2022 on both pages.
