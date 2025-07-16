# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

    > Who is your intended audience? 
    
    > What information or message are you trying to convey with your visualization? 
    
    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    
    > How did you ensure that your data visualization is accessible?  
    
    > Who are the individuals and communities who might be impacted by your visualization?  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    
    > What ‘underwater labour’ contributed to your final data visualization product?

Data Visualization Final Project
Dataset Chosen:
City of Toronto Open Data Portal – Toronto 311 Contact Centre Service Requests
(https://open.toronto.ca/dataset/311-contact-centre-service-requests/)

This dataset provides records of non-emergency requests of 2025 from residents, such as noise complaints, pothole reports, and waste collection inquiries. It offers insights into public concerns and city service demands across time and location.

Visualization 1: Monthly Volume of 311 Requests by Category 2025 (Bar Chart)

What software did you use to create your data visualization?
I used Python with the libraries pandas for data manipulation, matplotlib and seaborn for creating the data visualization. The dataset was downloaded from the City of Toronto’s Open Data Portal.

Who is your intended audience?
The intended audience includes municipal government analysts, city planners, and public policy makers who need to understand the volume and types of service requests made by Toronto residents over time. It could also be useful for community organizations interested in civic engagement trends.

What information or message are you trying to convey with your visualization?
The visualization shows the monthly volume of the top 10 most frequent 311 service request types in Toronto. This highlights trends and seasonality in the types of issues residents report to the city, which can inform resource allocation and policy decisions.

What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
I chose a grouped bar chart to compare volumes across categories by month, enabling side-by-side comparisons.

I used a colorblind-friendly palette from seaborn to improve accessibility.

Axis labels and titles were clearly added for context.

The x-axis labels (months) were rotated 45 degrees to improve readability.

A legend placed outside the plot area prevents clutter.

The plot size was chosen to balance visibility and layout.

How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
The entire data processing and visualization pipeline is contained in a Python Jupyter Notebook, including code for data cleaning, aggregation, and plotting. The notebook includes clear instructions and comments. Additionally, I documented the source and download link of the dataset, and the required Python packages are listed in a requirements.txt file. This ensures anyone can reproduce the visualization by running the notebook on the same dataset.

How did you ensure that your data visualization is accessible?
I used a color palette that is friendly for people with color vision deficiencies. I included clear labels and titles to help screen readers and users understand the plot. The figure size and font sizes were chosen to be legible on common screens.

Who are the individuals and communities who might be impacted by your visualization?
Toronto residents, especially those living in neighborhoods with high volumes of certain complaints, may benefit from increased awareness and better city services.

City departments and public officials can use the insights for improved service delivery.

Community organizations advocating for quality-of-life improvements may leverage this information.

How did you choose which features of your chosen dataset to include or exclude from your visualization?
I focused on the ‘Creation Date’ and ‘Service Request Type’ columns because these directly relate to the timing and nature of requests. Other fields such as postal code fragments, intersection data, or status were excluded to maintain clarity and focus on temporal trends by category.

What ‘underwater labour’ contributed to your final data visualization product?
Significant data cleaning was required, including:

Converting date fields to datetime format and handling missing or malformed dates.

Filtering and selecting the top 10 most frequent service request categories.

Grouping data by month and category for accurate aggregation.

Handling encoding issues in the CSV file to correctly read special characters.

Iterative design choices to improve readability and accessibility of the chart.


Visualization 2:

What software did you use to create your data visualization?
I used Microsoft Excel to filter, summarize, and visualize the dataset. Specifically, I used Excel’s Pivot Table functionality and Conditional Formatting to create a heatmap showing the number of noise complaints by ward in Toronto.

Who is your intended audience?
The intended audience includes city officials, municipal service managers, and community organizations who are interested in understanding how noise complaints are distributed across Toronto's wards. It is also useful for residents or local advocacy groups focused on urban livability and bylaw enforcement.

What information or message are you trying to convey with your visualization?
The visualization highlights the spatial distribution of noise-related 311 service requests, showing which wards have the highest number of complaints. This can help prioritize enforcement, identify hotspots, and inform decisions around noise regulations or public engagement.

What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?
I used a heatmap color scale to emphasize differences in complaint volume — wards with more complaints are shaded in darker colors, making the trend immediately visible. I kept the layout clean with labels and titles for clarity. I also ensured that each ward had equal visual weight by sorting and aligning values in the pivot table.

How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
Although Excel is less reproducible than Python, I ensured reproducibility by:

Documenting all steps taken: filtering by “Noise” complaints, creating a pivot table, and applying conditional formatting.

Saving the final Excel file with filtered and summarized data.
Anyone with the raw dataset and these instructions can recreate the visualization manually. However, minor differences in Excel versions or user actions may still introduce variability.

How did you ensure that your data visualization is accessible?
I used a high-contrast color scale for the heatmap, and made sure the text (ward names and values) was clearly legible. Since Excel visuals are easy to export into PDF or images, this also improves accessibility across different formats. Additionally, users can sort, zoom, or interact with the table directly in Excel.

Who are the individuals and communities who might be impacted by your visualization?
Toronto residents experiencing frequent noise disruptions.

City enforcement teams who need to know which areas to monitor more closely.

Urban policy makers who evaluate the effectiveness of existing bylaws.

Local advocacy groups who work to improve livability in high-complaint areas.

How did you choose which features of your chosen dataset to include or exclude from your visualization?
I focused on just two columns: “Service Request Type” and “Ward”. I filtered to include only rows related to noise complaints, and excluded other columns (e.g., intersection details or status) to keep the focus on the geographic distribution of complaints.

What ‘underwater labour’ contributed to your final data visualization product?
Although Excel appears simple on the surface, there was considerable effort in:

Filtering and understanding the raw dataset

Selecting relevant complaint types

Structuring a Pivot Table for meaningful aggregation

Designing a clear and interpretable heatmap

Verifying that formatting and values matched the filtered data
This background work ensured the final product is both informative and accurate.


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
