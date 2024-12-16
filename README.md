# Final-Project-Teaching-Kids-AI-with-Disney-Data
A fun project designed for grade school students to explore data about Disney World park attendance. Students will learn data cleaning, preprocessing, exploratory data analysis (EDA), and model training to discover patterns and make predictions using a simulated dataset. Perfect for introducing AI concepts in an engaging and hands-on way!

Finding a comprehensive dataset with daily attendance figures for Disney World can be challenging, as Disney does not publicly disclose detailed attendance data. However, there are several resources and strategies you can consider to approximate or simulate the data needed for your educational project:

## Project Set-Up:
### 1. Utilize Available Annual Attendance Figures
While daily attendance numbers are scarce, annual attendance statistics for Disney World parks are available from various sources. For instance, the Magic Kingdom reported over 17.7 million visitors in 2023 according to this link (https://www.statista.com/statistics/232966/attendance-at-the-walt-disney-world-magic-kingdom-theme-park/?utm_source=chatgpt.com) on Statista.

These annual figures can serve as a basis for estimating daily attendance.

### 2. Estimate Daily Attendance
You can divide the annual attendance by 365 days to approximate daily attendance. For example, with 17.7 million annual visitors, the average daily attendance would be approximately 48,493 guests. Keep in mind that actual daily attendance varies due to factors like holidays, weekends, and special events.

### 3. Incorporate Crowd Calendars and Wait Time Data
Websites such as Thrill Data provide crowd calendars that reflect historical wait times, indirectly indicating crowd levels on specific days.
Using data from this link (https://www.thrill-data.com/trip-planning/crowd-calendar/resort/wdw?utm_source=chatgpt.com) will not provide exact attendance numbers, but this information can help infer relative crowd sizes and trends over time.

### 4. Simulate Data for Educational Purposes
Given the lack of detailed public data, creating a simulated/estimated dataset can be an effective approach for your project. Generate a dataset with 2,500 rows and 10 columns, including variables such as:

-Date: Covering several years to provide a comprehensive view.
-Park Name: Identifying different parks within Disney World.
-Estimated Attendance: Using annual figures and known trends to estimate daily numbers.
-Day of the Week: To analyze patterns related to weekdays and weekends.
-Holiday Indicator: Marking major holidays and school vacation periods.
-Weather Conditions: Including variables like temperature and precipitation.
-Special Events: Noting days with parades, festivals, or extended hours.
-Ticket Prices: Reflecting any price changes over time.
-Marketing Campaigns: Indicating periods with significant promotions.
-Economic Indicators: Such as unemployment rates or consumer confidence indices.

By combining these variables, young students can engage in data cleaning, preprocessing, exploratory data analysis (EDA), and model training to identify factors influencing park attendance. This approach provides a realistic and educational experience in working with data, even in the absence of exact figures.
