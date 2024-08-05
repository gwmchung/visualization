# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.
 For visualization shown in the "dangerous_dog_viz1" jupyter notebook, 
    > What software did you use to create your data visualization?
    Python was used along with the panda and seaborn libraries.

    > Who is your intended audience? 
    
    Anyone interested in knowing how many dog bite incidents are reported in Toronto.
    
    > What information or message are you trying to convey with your visualization? 
    
    The number of dog bite incidents isn't that high for a big city like Toronto.
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
    
    I believe my visualization is substantive, as it accurately and honestly showed the number of dog bite incidents per month during the specified period.  I have chosen a histogram to show this information because I believe it is familiar to most people and shows the data most clearly.  

    I also took into consideration of the aesthetic, by making sure the x-axis tick labels are rotated 90 degrees and with a bigger font size so they are legible.  
    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    My code is well-documented.  Because I only took a subset of the data available from the data source, I have clearly commented that in the code, and also explained how we converted the original exact dates (from the column Date_of_Dangerous_Act) to the month and year formatted dates for easy aggregation.
    
    > How did you ensure that your data visualization is accessible?  

    I made sure the colors of the bars and the color of the bars and the edge color are a good contrast, so that it is accessible to most people.  I also made sure the font size are big enough. 
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    I hope the visualization will bring awareness to dog owners that dog bite incidents happen more in the summer, so that they will be more mindful when taking their dogs out.  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    I wanted to see if the time of the year affects the number of dog bite incidents, so naturally I was looking at the date column.  But I needed to aggregate the counts for easier visualization.  
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    For the people who reported the incidents and those who kept track of the data and summarize them in the CSV file.  

- For the Power BI visualization shown in dangerous_dog_viz2 PowerBI file and in dangerous_dog_viz2.pdf: 
    > What software did you use to create your data visualization?

    The software I use is Power BI desktop.  

    > Who is your intended audience? 

    My intended audience is people who are considering getting a dog as a pet.  
    
    > What information or message are you trying to convey with your visualization? 

    I would like to show that certain dog breeds are indeed more agressive and will cause biting incidents.  
    
    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 

    I have chosen to use a treemap to show the distribution of dog breeds relative to the number of dog bite incidents.  The relative size that is used by each color of the breed shows clearly the relative number of incidents each breed is associated with.  That is perceptual.  And by hovering over each of the box, it shows the number of incidents and severity of the incident, which is substantive.  

    
    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

    It is not reproduceable since it is created with Power BI.  It may impact the substantiveness of the visual.  However, since the data source is public, it may allow some kind of reproduceability.  
    
    > How did you ensure that your data visualization is accessible?  

    The colors of each block and the neighbouring blocks are a good contrast.  
    
    > Who are the individuals and communities who might be impacted by your visualization?  

    Potential dog owners who are looking for a dog may reconsider their decision for a breed, if that breed is shown with a large number of incidents.  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

    Since I mostly want to show which breeds are more agressive, other information such as the date and location are excluded from the viz.  I am mostly interested in the aggregated count of each breed and also grouping by the severity of the incident, that's why those are the columns used.  
    
    > What ‘underwater labour’ contributed to your final data visualization product?

    For the people who reported the incidents and those who kept track of the data and summarize them in the CSV file.  

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
