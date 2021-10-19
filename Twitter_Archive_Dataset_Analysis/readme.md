
# Bolsa Familia Medical No-Show Appointment
Data Source: [WeRateDogs](https://en.wikipedia.org/wiki/WeRateDogs)
             [WeRateDogs Twitter Archive](https://twitter.com/dog_rates)

#### -- Project Status: [Completed]

## Project Intro/Objective
My goal with this project was to wrangle the WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations. The actual Twitter archive is great, but it only contains very basic tweet information. Additional gathering, then assessing, and then cleaning was required for more detailed, visually appealing analyses and visualizations.


### Methods Used
* Descriptive Statistics
* Inferential Statistics
* Data Visualization
* Data Wrangling
* API Querying
* Reporting

## Project Files Breakdown
* **Enhanced Twitter Archive**
> The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. One column the archive does contain though is each tweet's text, which was used to extract rating, dog name, and dog "stage" (i.e. doggo, floofer, pupper, and puppo) to make this Twitter archive enhanced. Of the 5000+ tweets, the tweets have been filtered with ratings only (there were 2356).

* **Image Predictions File**
>Every image in the WeRateDogs Twitter archive through a neural network that can classify breeds of dogs*. The results being a table full of image predictions (the top three only) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images)


### Technologies
* Python
* NumPy
* Pandas
* Jupyter Notebook
* Matplotlib
* JSON
* Requests
* Tweepy
* Twitter API
* Atom (Text Editor)
