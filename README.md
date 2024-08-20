# Hotel-Booking-Analysis-Dashboard

![Dashboard](https://github.com/ANURUDRA-JENA/Travel-Hospitality-Analysis/blob/7dd4df8f31dbfeff8c3340330b4b4074771c7e9e/Assets/Dashboard.png)

<a href="https://public.tableau.com/views/Viz1_17158474394310/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link"> Click here to view the Dashboard</a>

<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>This repo contains a dashboard made for the Hotel boking Analysis EDA out of the famous AirBnb&rsquo;s Hotel Bookings Dataset.</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Suppose, <strong>if someone performed EDA on Airbnb operations</strong> then the following steps need to be followed for building an adequate dashboard through which one can analyze the performance of the company to take necessary actions.</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Problem Statement:</strong></p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>In the context of Airbnb operations, how can the utilization of Tableau Desktop/Tableau Public/PowerBI facilitate a comprehensive comparative examination between Chicago and New Orleans, two diverse urban environments?</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>This inquiry seeks to leverage Tableau Desktop/Tableau Public/PowerBI&apos;s visual analytics capabilities to uncover and illustrate the shared attributes, disparities, and distinctive patterns inherent to Airbnb&apos;s presence in these cities, thus elevating the depth and insightfulness of the study.</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Dataset Selection:</strong></p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>For this EDA project, we have chosen the &quot;Airbnb Listings Data&quot; dataset from 2 major cities: Chicago and New Orleans. This dataset provides a comprehensive snapshot of various attributes related to Airbnb listings, such as property type, neighborhood, pricing, availability, and more. The dataset is ideal for conducting an in-depth exploration of the local Airbnb market and deriving actionable insights.</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Why Airbnb:</strong></p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Airbnb, a prominent online platform, enables individuals to reserve accommodations spanning a spectrum from beds and rooms to apartments and entire homes across global locales. This user-centric platform serves as a conduit for seamless property rentals, negating the need for intricate intermediaries or substantial capital outlays. Notably, users can secure lodgings at significantly competitive rates relative to traditional hotels. Distinctively, Airbnb extends its reach to regions where convectional hotel presence might be limited, offering an avenue for lodging acquisition in underserved locales. Moreover, the inclination towards immersive local experiences often steers individuals towards selecting accommodations embedded within native communities, fostering a distinctive preference for authenticity and cultural engagement.</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Airbnb Statistics &bull; Over 4 million listings worldwide &bull; 150 million users in 191 countries &bull; Worldwide value is $32 billion &bull; Global growth rate since 2009 - 153%</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Dataset Details:</strong></p>
<ul style="margin-bottom:0in;margin-top:0in;" type="disc">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Dataset Name: Airbnb Listings Data</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Source: <a href="http://insideairbnb.com/get-the-data/">Link to dataset</a></li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Cities: Chicago &amp; New Orleans</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Description: The Airbnb Listings Data contains information about different properties available for rent on Airbnb in a specific city. Each record represents a unique listing and includes attributes such as property type, neighborhood, number of bedrooms, pricing, availability, host information, and more.</li>
</ul>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Key Attributes</strong>:</p>
<ol style="margin-bottom:0in;margin-top:0in;" start="1" type="1">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>id: Unique identifier for each listing.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>name: The title or name of the listing.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>host_id: Unique identifier for the host of the property.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>host_name: Name of the host.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>neighbourhood_group: The broader area or group that the neighbourhood belongs to.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>neighbourhood: Specific neighbourhood where the property is located.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>latitude: Latitude coordinate of the property.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>longitude: Longitude coordinate of the property.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>room_type: Type of room (e.g., Private room, Entire home/apt, Shared room).</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>price: Price of the listing per night.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>minimum_nights: Minimum number of nights required for booking.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>number_of_reviews: Total number of reviews received for the listing.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>last_review: Date of the last review.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>reviews_per_month: Average number of reviews per month.</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>availability_365: Number of days the listing is available for booking in a year.</li>
</ol>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Problem Areas to Explore:</strong></p>
<ol style="margin-bottom:0in;margin-top:0in;" start="1" type="1">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Which are the popular neighborhoods, their average prices and no. of listings?</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>What is the percent share of different property types and room types?</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>How the pricing is varying with location, property type, and reviews?</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>What are the different correlations between type of hosts and factors like- reviews &amp; price?</li>
</ol>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Divide the visualization findings into 4 categories:</p>
<ul style="margin-bottom:0in;margin-top:0in;" type="disc">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Overview of Airbnb</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Property analysis</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Pricing analysis</li>
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Host analysis</li>
</ul>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>How to proceed with the dashboard:</strong></p>
<ol style="margin-bottom:0in;margin-top:0in;" start="1" type="1">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Data Cleaning</strong></li>
</ol>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Begin by addressing the disorder and inconsistency within the dataset. Utilise Jupyter Notebook and Tableau Desktop/Tableau Public/PowerBI Prep to systematically cleanse the data, rectifying discrepancies, eliminating duplicates, and standardising formats.</p>
<ol style="margin-bottom:0in;margin-top:0in;" start="1" type="1">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Data Transformation</strong></li>
</ol>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Generate supplementary columns by utilising pre-existing categorical data. These columns will be derived from extensive descriptive text, which, in its original form, proved arduous to comprehend and unsuitable for visualisation purposes. The extra columns that we created gave a much clear sense of how to approach and make an effective visualisation.</p>
<ol style="margin-bottom:0in;margin-top:0in;" start="1" type="1">
    <li style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'><strong>Tableau Desktop/Tableau Public/PowerBI</strong></li>
</ol>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Employ Tableau Desktop/Tableau Public/PowerBI Prep to leverage its distinctive &quot;Group and Replace&quot; feature. Under the column denoted as Neighbourhood there are instances where identical entities are variably represented due to disparities in letter casing, spelling variations, or phonetic similarity. The &quot;Group and Replace&quot; algorithm inherent to Tableau Desktop/Tableau Public/PowerBI Prep proved instrumental in mitigating this issue.</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>&nbsp;</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>&nbsp;</p>
<a href="https://public.tableau.com/views/Viz1_17158474394310/Dashboard1?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link"> Click here to view the Dashboard</a>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Please make sure to check it out.</p>
<p style='margin-top:0in;margin-right:0in;margin-bottom:8.0pt;margin-left:0in;font-size:11.0pt;font-family:"Calibri",sans-serif;'>Thanks</p>
