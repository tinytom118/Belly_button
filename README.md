A Plotly dashboard within a Flask app deployed to Heroku at https://belly-button-diversity-thomasl.herokuapp.com/. This dashboard was created to visualize the Belly Button Diversity Dataset. This full stack application was created using a SQLite/Flask/Python backend combined with an HTML frontend and Javascript as a middle layer to connect the two ends. Users can select a sample number from the drop down menu to select the participant in the study and view the dashboard changing with respect to the participant's measurements.

The following plots are included in the dashboard using the Plotly.js framework:

  - A pie chart to view the proportion of the top 10 samples and their OTU ID and bacteria info on hover
  - A bubble chart to see OTU_IDs vs. the sample value with the size of the bubble determined by the sample value
  - A gauge chart to show the amount of belly button scrubs per week for the participant sample


### About the Data

Hulcr, J. et al.(2012) _A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable_. Retrieved from: [http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/](http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/)

- - -


