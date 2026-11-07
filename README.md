# bnan430-portfolio
Portfolio of projects from my Data Visualization course. This will include the completion of assignments in Excel, Tableau, PowerBI through DataCamp, Adobe Express, and various AI tools. 

This dashboard shows E-commerce profitabilities across different categories and subcategories of Southwest Office Solutions product line. https://public.tableau.com/views/AdvancinginExcelandTableau_17894412290380/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 

Power BI Business Intelligence Training, BNAN 430, September 28, 2026 https://public.tableau.com/views/PowerBIStory1/PowerBIStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
https://www.datacamp.com/completed/statement-of-accomplishment/course/dd8c1627f6a87991a5af77c5ecfe4c674e1a88d9 

DAX in Power BI: Moving Profit Analysis from PivotTables to Measures, BNAN 430, October 05, 2026
https://public.tableau.com/views/PowerBIStory1/PowerBIStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link
https://www.datacamp.com/completed/statement-of-accomplishment/course/dcc3e1494b48dbdc87ae323bfe435e3671012372 
In Flex 3, I helped choose which subcategory Anita should put on a margin recovery plan by building an Excel PivotTable that averaged the Profit column for each subcategory, dividing total profit by the number of order lines. Tables came out lowest, at –$54.99 per line. In Power BI, I would build this as a measure rather than a calculated column, because average profit per line is not a fixed property of any single row. It only means something once it is calculated over the group of orders the reader is looking at. Written once as a measure, it would recalculate automatically whenever the report is filtered by region, segment, ship mode, or year, while in my workbook, each of those views would have meant building another PivotTable by hand. For Anita, that means she can check during the meeting whether Tables lose money everywhere or only in certain regions, and see the answer on screen instead of waiting for me to rerun the analysis.

Data Visualization in Power BI: Choosing the Right Tool for the Job, BNAN 430, October 12, 2026
https://public.tableau.com/views/PowerBIStory1/PowerBIStory?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
https://www.datacamp.com/completed/statement-of-accomplishment/course/1a74779d65ce45f9cdcc93e1248e971d61844856?utm_medium=organic_social&utm_campaign=sharewidget&utm_content=soa 

I think I’m ready for BI work at Southwest because I’ve already done some of it. For the e-commerce profitability analysis, I built an Excel PivotTable that averaged profit per order line by subcategory. Tables came out worst at -$54.99 per line, and Bookcases and Supplies were the only others below zero. In Power BI, I would rebuild it as a matrix with conditional formatting, so Anita could spot the money-losing subcategories in the table she already uses. Since average profit would be a measure, the highlighting would stay correct when she filters by region or year. For Marcus, I pulled year and month out of the order date by hand. Power BI creates that date hierarchy automatically, so he could go from yearly trends to one month.

I’d still use the other tools. I’d use Excel for one-time cleanup, like reconciling three source sheets with different record counts, because I need to see each row. Tableau works well for exploring data and building one focused chart for a meeting. Power BI fits reports that come out regularly, that several people filter themselves, and that need to refresh without being rebuilt. My biggest gap is that I’ve only used Power BI in DataCamp’s browser exercises, never in Power BI Desktop with real company data. To fix that, I plan to rebuild my subcategory analysis in Power BI Desktop and publish it to the Power BI Service, since I already know what the numbers should be.

I used Claude (Anthropic) to help edit this entry from my own Flex 3-6 work. I reviewed and verified all content. 

Card Portfolio Review, BNAN 430, October 19, 2026
Card Portfolio Review – Contactless Readiness: Which non-contactless cards should Bear Down Bank replace early this quarter without wasting money on cards it will reissue anyway? 
https://public.tableau.com/views/CardPortfolioReview-ContactlessReadiness_17924811701990/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
If I did it again, I’d break the batch down by card type to see whether prepaid cards, which make up 128 of the 440, need a different fix with the card vendor.


Advancing in Excel & Tableau – Pt. 4 (Wildcat Rewards), BNAN 430, November 4, 2026
Which single customer group should receive the Wildcat Rewards pre-approved pilot mailing? 
View the Tableau workbook here: https://public.tableau.com/views/CardGrowthAnalysis-WildcatsRewardsOffer/ExploratoryDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link 
If I did it again, I would test whether low credit card ownership in the Southwest comes from the Sagebrush Pay acquisition before scaling the offer.

Nov 6, 2026. Data Storytelling with Adobe Express. 
Work sample for Jordan Ellis, VP of Card Growth at Bear Down Bank: send the Wildcat Rewards pilot mailing to customers in Texas, Colorado, New Mexico, Nevada and Utah, where 97 customers qualify.

Work sample: https://github.com/inshatkhan/bnan430-portfolio/blob/main/khan-data-storytelling%20(1).pdf 
Adobe Express link: https://express.adobe.com/publishedV2/urn:aaid:sc:VA6C2:d4a9ef81-0095-59ee-9073-00c5cea1d99c?promoid=Y69SGM5H&sdid=C4SZ2FYJ&mv=other 

Design choice: I used a two-bar chart because Jordan's decision rests on one comparison: 43.9% of customers in the five Southwest states qualify for the offer, compared with 17.4% everywhere else, and a state map would have made him judge four states with fewer than 25 customers each one at a time. I removed the grouped guardrail bar chart from my Tableau draft and replaced it with a three-row table. Six bars made him decode lengths that were nearly equal, while the table lets him see at a glance that only card ownership differs (69% vs. 33%).

Adobe Express training completed on Nov 6, 2026. 
