# Data-Analyst---Case-Study
SnapTravel Case Study: Data Analyst

Expected Time to complete: ~2-3.5 hours
In Person Presentation Time: 1 hour
 
We’re excited to have you completing the Case Study for the Data Analyst role at Clicksco!
 
Please review the outline of the case study below. The final response can be formatted however you’d like, such as using a word document, excel sheet, powerpoint presentation, or combination, etc. Please use whatever you think will be most effective to get your best work across. We will perform a quick review, provide some feedback, and then you will have the opportunity to present this case study in person.
 
Note: please do not put your name on the Case Study. This allows our leaders to review all case studies anonymously and formulate thoughts/opinions without the bias of knowing it was you that completed it.

What we are assessing:
1.	Data Analysis -- ability to dive into large sets of raw data to draw key analytics and insights that can be used to drive business decisions
2.	Problem Solving -- ability to approach a large problem and break it down and come up with working solutions
3.	Communication -- ability to communicate your insights clearly through storytelling and / or creating a business case
Context
 
SnapTravel is an online travel agency that sells hotel rooms to consumers through our automated chat-bot, accessible through Google Hotel Ads, Kayak, and other external meta channels. We constantly strive to make business changes at each stage of our business funnel that help users find the best deal in the easiest way possible. 
The data dictionary can be found at the end of this document. 


Question 1 
 
Using the attached data, find 1-2 things about our booking funnel that you think are important to track and then create 5 visualizations that would help you track that metric:
-	What other data sources would you add assuming they were available?
-	Please prepare your presentation for a business audience but be ready to answer technical questions (perhaps in an appendix).


Question 2
If you were tasked with expanding the snaptravel business into a new area of the world, how would you approach that problem? What data would you need? Who would you involve? Provide a brief description of your process (300 words or less).


Data Dictionary 

The below table has data on a subset of itineraries from a specific meta channel between the dates of July 1st 2019 and September 15th, 2019. For these purposes, Snaptravel’s booking funnel can be defined as:
1.	Impression on a Snaptravel ad 
2.	Transition page open 
3.	Booking form open 
4.	Booking 

Field	Data Type	Description
SEARCH_DATE	date	Date that the search occurred on.
HOTEL_ID	int	Unique identifier for a hotel
CHECK_IN_DATE	date	Date first night of the users hotel stay
ELIGIBLE_IMPRESSIONS	int	Number of total users that viewed that itinerary (not specific to Snaptravel)
IMPRESSIONS	int	Number of total users that viewed Snaptravel’s advertisement for the searched itinerary
TRANSITION_PAGE_OPENS	int	Number of times that the transition page that redirects and user to the Snaptravel platform was opened 
BOOKING_FORM OPENS	int	Number of times that the booking form that delineates all of the booking details before finalizing the booking
BOOKINGS	int	Number of completed bookings
 
