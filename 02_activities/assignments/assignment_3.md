# Data Visualization

## Assignment 3: Data Visualization Ethics

### Requirements:
- Let’s return to the data visualizations we evaluated for Assignment 2.  
- For each visualization: 
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) whether or not you think this data visualization is accessible, reproducible, and equitable. 
        ```
        Your answer...
Viz 1 : https://public.tableau.com/app/profile/arpita.pal/viz/ClimateChangeGlobalLandSurfaceTemperatureAnomalies/Globallandtemp Global land surface temperature anomalies:


The color choices are not user-friendly, as it is difficult to differentiate between certain colors (red/orange, blue/dark blue) at certain points. The visualization should use color palettes that are accessible to colorblind users, ensuring that differences in temperature anomalies can be distinguished without confusion.

The legend includes all the color codes along with minimum and maximum values. However, it is unclear at what stage the color transition occurs in the plot.

The plot is easily reproducible, and others can replicate the work, but it does not provide the source of the data used to create it. It could be a sample dataset, and hence the accuracy of the temperature values used cannot be confirmed.

The plot is not highly equitable because equitable visualizations are those that ensure all users, regardless of their background or expertise, have equal access to understanding the presented data. Its equitability can be enhanced by providing more context and emphasizing the different impacts of climate change across regions. Making these connections can allow for a clearer and more equitable understanding of the data presented to the target audience.

Viz 2: https://public.tableau.com/app/profile/matt.sorenson/viz/CollegeFootballFollowerMap/CollegeFootballMap  America's Favorite College Football Teams, Determine by nukmber of Twitter followers 


This map analyzes data from over 20 million Twitter followers of Division 1 college football teams and displays the most-followed team per county.

The choice of colors in the map is not aesthetically pleasing, as it uses too many colors, making it visually cluttered. Additionally, the map is crowded with information, and the team logos appear overlapped. The color palette used is not friendly for colorblind users, as it includes color pairs that are difficult to differentiate, which could hinder accessibility.

The team logos and follower counts are not clear or readable. The follower count text is too small, limiting accessibility for users with visual impairments.

When hovering over the states, the top 5 teams in each state are displayed in a pop-up window. However, the color choices in the pop-up are problematic, as they again use a large number of colors. The information in the pop-up could also be simplified for better readability.

The visualization does not specify where the Twitter follower data was sourced from, nor does it provide an option for users to export the underlying data or any scripts used to create it. As a result, it is not possible to replicate the analysis.

There is also a lack of context regarding the year considered for analysis, as well as the significance of the follower numbers and how they relate to team popularity. This absence of context results in a lack of equity in the presentation.


    - How could this data visualization have been improved (in terms of accessibility, reproducibility, equity)?  
        ```
        Your answer...

    By using colors and text that are easy for everyone to see, including people with visual impairment or colorblindness ( choose colors focusing the target audience).
    Provide alt+ text to describe charts for screen reader users. Also, ensure instructions are clear if there is an interactive element.

    Share the data source used to create the visualization. Need to provide options to download and reuse the code for others to recreate it.

    Provide the context behind the data and what year or group it represents. Also make sure the context is easily readable and understandable by individuals with any background.

    Use clear and simple labels, legends and layouts to avoid confusion and maintain clarity and simplicity.



        ```

- Word count should not exceed (as a maximum) 300 words for each visualization. 

### Why am I doing this assignment?:
- This ongoing assignment ensures active participation in the course, and assesses learning outcomes 2 and 3:  
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:
| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * This markdown file (assignment_3.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
