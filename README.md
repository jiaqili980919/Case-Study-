# Case-Study
This file is a case study exploring residents' attitudes in CA 90005 and predicting occupancy rate in CA 90005.

Basic Information about CA 90005:
Explore the basic information in 90005:
90005 is in LA. 
Majority of the population is young (25-34) Asian.
From the 2 points above, it’s a possible target for Tripalink, so 90005 is worth deeper exploring.
Refer to https://www.unitedstateszipcodes.org/90005/ 
Note: most of rented room are studio and one bedroom
          Neighborhood: Koreatown|Wilshire|Mid-Wilshire

Task 1: 
Q: Residents’ attitude and needs 

Most people rent houses/apartments based on counties instead of zip code, so instead of studying industry based on zip code, I study the neighborhood covered by zip code 90005. Since CA 90005 covers : Koreatown, Mid-Wilshire. I collect the articles based on these different neighborhoods. However, since most of 90005 is covered by Koreatown, I collect more articles of real estate in Koreatown than Mid-Wilshire. Also, since residents will be most likely to take a look at toppest real estate from websites, these apartments are the top 10 from real estate websites. Furthermore, since there is no time for me to collect all reviews for each apartment, I collected most useful reviews voted by residents from each apartment
Note: Our post/reviews are from google/ApartmentRatings/Reddit/yelp

Basic Information about Dataset:
Our dataset include reviews from following apartments:
Koreatown( from apartments.com): select top 5 from the website
The Harper
Kurve
The Hana
The Pearl
Avana on Wilshire
Berkshire K2LA
Chalfonte Apartments
Ardmore

Wilshire:
Windsor Square Villas
744 S Windsor Blvd #no reviews
Windsor terrace


Algorithms:

Step 1: find residents’ reviews and developers’ post for each apartment

Step 2: Visualize negative and positive emotions frequency for zip 90005, and find 10 most frequent words for 90005.


2nd task 
Basic Information about Dataset:
Data is collected from Datafinity

Step 1: clean data: delete rows with 50% missing values and replace missing values with info from closed houses (add some data visualizations)

Step 2: create columns of occupancy and calculate occupancy rate

Step 3: Split training and test data and predict prices ranges with linear regression twice


