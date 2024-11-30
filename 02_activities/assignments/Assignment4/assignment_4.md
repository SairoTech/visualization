# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 
    > What software did you use to create your data visualization?

     data visualization 1 : Python
     data visualization 2 : Excel

    > Who is your intended audience? 

    City of Toronto Parks, Forestry & Recreation officials, government agenices responsible for enhancing and maintaining public amenities, city planners and general public. 

    
    > What information or message are you trying to convey with your visualization? 
      The visualization conveys the current status of washroom facilities, highlighting the number of portable and washroom buildings available along with their statuses(Open, Closed or need service) across Toronto. This information emphasizes the importance of thoroughly studying the locations that require immediate attention as well as making improvements in public restoom accessibility and management. Further data study is possible with this dataset.

    > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots? 
      Substantative :I focused on key metrics that clearly show the status of washroom facilities and the count for each washroom type.
      Perceptual : I used different colors to make it easy to read and undderstand.
      Aesthetic : I tried to keep the layout simple and labelled the axeses for better clarity.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
      The use of Python ensures reproducibility because the code can be run multiple times with the same dataset, generating consistent results. In Excel, the charts can be easily updated by refreshing the data or altering input ranges. If a tool is non-reproducible, it could hinder the ability to validate or update visualizations over time, causing potential discrepancies in the presented information.

    > How did you ensure that your data visualization is accessible?  
      I made the visualizations accessible by using clear labels and contrasting colors that accommodate color vision deficiencies.  In Python, I ensured proper font size and type for readability. 
      In Excel, I used descriptive titles and distinct colors for easy differentiation on what is presented.

    > Who are the individuals and communities who might be impacted by your visualization?  
      The primary individuals affected include local residents, city planners, and park management staff who need to assess and plan public restroom facilities.

    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
      I focused on essential features directly related to the status of washroom facilities— the Type and Status columns and excluded less critical data (like Comments, reasons etc) to streamline the visualizations. The goal was to present clear metrics that aid in understanding patterns in restroom availability. There is more potential to obtain useful information from the dataset that can add value to the present findings like which location needs immediate attention or maintenance, which area has least washrtoom facilities etc.

    > What ‘underwater labour’ contributed to your final data visualization product?
      The ‘underwater labour’ involved data preprocessing and cleaning steps in Python. There were missing values in the dataset but after analyzing the importance of those features I decided to keep them as there were not critical to the visualization. 
      In Excel, I experiemneted with multiple options for formating that helped refine the final plots for visualization.

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
