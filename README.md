## Approach taken

Initially, I collected data from the provided Microsoft website and analysed it using Excel to familiarise myself with the dataset. After importing all Excel sheets into my project, I performed data transformation by identifying and removing null values, duplicates, and unnecessary white spaces. Subsequently, I verified the data types, ensuring that any currency values were formatted correctly as US dollars.

In the model view, I examined existing relationships within the data, noting several that appeared repetitive. These were addressed appropriately. I then proceeded with further data transformation per the guidelines outlined in Section 1. 

The model design had largely been established during the data preprocessing phase in Section 1, apart from creating hierarchies based on specific requirements. New relationships were formed as additional tables and columns were introduced, particularly concerning a data table where two relationships were established. The cleaning and establishment of data relations were effectively completed.

The generation of visuals was relatively straightforward, as the required visuals had been specified, while I was also encouraged to explore additional options. Formatting and creating new measures for the KPI card visual necessitated careful attention to detail and some time to fine-tune.

Once all visuals were developed, I focused on organising them for optimal space usage and logical flow. I placed the visuals on their respective pages and made the decision to include complementary visuals beyond those originally requested to enhance the depth of the dashboard.

Next, I implemented page navigation and slicers. To maximise the available space, I opted for a slide-out sidebar to house the slicers and page navigation buttons. This included a home button and a sidebar open button, allowing for a user-friendly interface.

Following that, I created user roles based on country and corporate headquarters. This was a new feature for me; however, the implementation process was simplified by Power BI's user-friendly wizard. After creating these roles, I tested their functionality to ensure everything was operating as intended.

To support the creation of the KPI cards, I developed custom measures, including target, profit margin, and total sales measures. I also added a sales variance measure to analyse the discrepancies between sales figures and targets.

Subsequently, I focused on text formatting, centring titles with a consistent font style, and establishing a cohesive colour scheme. I ensured that text values were easily readable. A mobile layout view was created and tested for accessibility on mobile devices.

In the final stages, I utilised the automatic generation feature to create the mobile layout page, making necessary adjustments before saving and verifying its functionality on my phone.

Lastly, I compiled screenshots and organised them into their respective folders before uploading them to the README file. While on GitHub, I took the time to structure the repository to meet established standards.




## Challenges faced and how they were tackled
The first challenge encountered in the project was the presence of redundant tables. Upon importing all tables from the Excel file, the relationships became disorganised due to duplicate tables that had the same name and contained identical data. To streamline the process, these duplicate tables were hidden from view.

Following this cleanup, the focus shifted to establishing relationships among the tables. New tables were created, necessitating the inclusion of new relationships. A key aspect of this process involved determining which relationship for the data table should be active. After experimenting with various visuals, a decision was made on which relationship to designate as active.

Next, attention was directed toward the KPI visual. Initial experimentation with the KPI visual card caused some confusion; however, after adjusting measures and defining a target, it functioned correctly. This visual also provides insights into whether the target was met in the previous year, utilising a colour gradient of green, orange, and red to indicate performance.

The sizing of all visuals on the page proved to be a meticulous task. Achieving balance was essential; visuals that were too small compromised readability, while those that were too large detracted from others. Furthermore, placing visuals inappropriately disrupted the logical flow of the page. After considerable reshaping and scaling, an effective layout was achieved on the visual gallery page.

The next challenge involved the implementation of a prediction line, which was initially problematic because it was not available for line charts. To address this, the data was adjusted by incorporating the date hierarchy instead of using months alone. This change provided a partial solution, allowing for a trend line to be generated for year and day, but not for month. Ultimately, the decision was made to abandon the idea of a month-based trend line, as it became apparent that the available tools in Power BI did not yield sufficient insights for this particular timeframe.



## Key insights 
Accessories emerged as the top-selling category across all countries, accounting for an impressive 33% of total sales and generating a substantial profit of $634,467. Among these, water bottles stole the spotlight, surprisingly becoming the best-selling product with a remarkable total of 1,139 orders.

When it comes to colour preferences, black proved to be the most sought-after and profitable choice across all categories. Australia led the charge with a staggering 2,515 orders, translating into an impressive profit of $1.22 million. Sales trends in this region show a steady upward trajectory, indicating growing popularity and demand.

In terms of customer demographics, the most lucrative segment comprises predominantly female buyers who favour items in black and hail from the United States. This trend is underscored by the fact that the most profitable cities for sales are concentrated in this country, highlighting a distinctive and thriving market for these products.



## Assumptions and limitations
The assumptions made in this analysis included the presumption that the currency in use is the United States dollar. Additionally, it was assumed that the corporate headquarters is located in the country specified, despite discrepancies in data files where it is represented otherwise. Furthermore, it was assumed that the profit margin is intended to be 30% of total sales, with the budget set at 1.2 times the amount of sales.

The limitations of this analysis stem from the absence of a clearly defined objective for the dashboard. This lack of clarity hinders the development of insightful and targeted visual representations. As a result, the current dashboard remains somewhat generalised.


## Dashboard 


##
