# MIS-561-Portfolio
This is a github repository for my MIS 561 Data Visualization course.
I am very excited to learn advanced visualiation techniques!

**Initial E-Commerce Profitability Analysis**

Here I did data analysis to find the best and worst performing subcategories at Southwest Office Solutions, where Anita Reyes, VP of Merchandising, will use ut to determine what product will be given a recovery plan and what product(s) will be retired.

One thing I would change about this assignment would likely be the use of a some different visuals and more advanced analysis on specific products.

https://public.tableau.com/app/profile/sean.dubois/viz/SeanDuBoisFlex3-AdvancinginExcelandTableau-PT1/ExploratoryDashboard#2


**Southwest Office Solutions: Account Profitability and Service Tiers**

Here I analyzed account profitability at Southwest Office Solutions, where Marcus Reyes, VP of Sales, will use it to decide which one change to make in the FY2026 account service policy: how accounts are tiered, what it costs to serve them, or how Southwest discounts.  My analysis found that accounts with an average discount of 20% or more lost $67,756 after cost to serve, so I recommended capping discounts at 20%.

One thing I would change about this assignment is how I measured discounts.  I used the simple average of each account's discounts, and a revenue-weighted average would be more accurate. I would also test different cutoffs, like 15% and 25%, to make sure the 20% cap holds up.

https://public.tableau.com/views/SouthwestOfficeSolutionsAccountProfitabilityandServiceTiers/AccountPortfolioDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

### Update:  Certifications Have been moved to /Ceritificates
**Datacamp Introduction to Power BI (09/28/2026)**
In my earlier order and account analyses, I used XLOOKUP in Excel to pull customer details from a separate customer sheet into the order sheet by matching on CustomerID, building one combined table before I could bring anything into Tableau. When I loaded data into Power BI, it recognized that the tables shared that ID column and linked them automatically, so I could chart customer and order fields together without building the combined sheet first. For analyses that have to be rerun every month, like the margin and account reviews, I would choose Power BI, because the link between tables stays accurate as new orders come in, while my XLOOKUP columns had to be filled down and rechecked every time rows were added. For a quick one-time lookup, I would still use Excel, since a single formula is faster than setting up a data model.
Check out my certificate in the **Certificates** folder, or click on this link that will lead you to my Tableau page!

https://public.tableau.com/views/SeanDuBoissDatacampIntroductiontoPowerBICertificate/CertificateStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**Datacamp Introduction to DAX in Power BI (10/04/2026)**
In my account profitability analysis, I calculated each account's average discount rate by dividing its total discount dollars by its gross revenue before discount, and I used that number to find the accounts at or above 20% that lost money after cost to serve. In Power BI, I would build this as a measure instead of a fixed column in the data, because a discount rate has to be recalculated for whatever group of accounts you are looking at. If it were a fixed column, filtering to Managed accounts or a single quarter would add up or average each account's percentage, which gives you the wrong rate for that group. As a measure, it divides total discount by total revenue for exactly the accounts on your screen. That means you can filter by tier, region, or quarter during a meeting and see right away which accounts cross 20%, without waiting for me to rebuild the workbook, and everyone on your team sees the same number because it comes from one shared definition.
Check out my certificate in the **Certificates** folder, or click on this link that will lead you to my Tableau page!

https://public.tableau.com/views/SeanDuBoissDatacampCertificates/CertificateIntroductiontoDAXinPowerBI?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

**Datacamp Data Visualization in Power BI (10/06/2026)**
Sarah,

In my profitability dashboard, a sorted bar chart showed the three subcategories losing money: Tables, Bookcases, and Supplies.  For Anita's monthly margin report, I would rebuild it in Power BI as a matrix of subcategories by month.  In my Power BI training, I used rule-based conditional formatting to turn every product below average red, and that approach would make losses stand out in the table Anita already reads, so she can tell a one-month dip from a pattern.  I would leave out the gauge I built against a 70% margin target, since a KPI visual shows the same target plus the trend.  I calculated each account's discount rate as a fixed number, but in Power BI I would build it as a measure, so Marcus can filter by tier or quarter and still get the correct rate.

I would still use Excel for quick, one-time checks and Tableau for exploring data when I am still figuring out the story.  Power BI is for monthly reports other people rely on, because one data model and shared measures keep everyone on the same numbers.  My gap is that I have built reports in Power BI Desktop, but I have never published to the Power BI Service or maintained a report others depend on.  To close it, I would publish the margin report, set up its monthly refresh, and support it for a full quarter with Anita as its first user. 
Check out my certificate in the **Certificates** folder, or click on this link that will lead you to my Tableau page!

https://public.tableau.com/app/profile/sean.dubois/viz/SeanDuBoissDatacampCertificates/CertificateIntroductiontoPowerBI?publish=yes

