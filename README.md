# Digital-Marketing-Optimization

**Data Description**

Performance Data

_Google Ads_

Google Ads is an online advertising platform where ads appear on Google Search results, YouTube, and various partner sites across the Google Display Network. Its purpose is to drive targeted traffic and achieve specific marketing goals through various ad formats. Here is a breakdown of the fields and data structure for Google Ads:
1.	Date:
a.	Definition: The specific day when the ad impressions were received.
b.	Format: YYYY-MM-DD (e.g., 2023-07-01)
2.	Network:
a.	Definition: The specific platform or channel within Google Ads where the ads were served. This includes different types of networks:
i.	Cross-network: A combination of Search, Display, and YouTube networks, optimized to maximize performance across all.
ii.	Display Network: Includes Google partner sites and apps that show ads in formats like banners, text, and video.
iii.	Search Network: Includes Google Search and other search partners, where ads appear as text ads.
iv.	YouTube: Includes ads shown on YouTube videos and YouTube partner videos.
3.	Impressions:
a.	Definition: The total number of times an ad is displayed to users.
b.	Unit: Count
c.	Example: 181,822 impressions on Cross-network mean the ads were shown 181,822 times on Cross-network.
4.	Clicks:
a.	Definition: The total number of times users clicked on the ad.
b.	Unit: Count
c.	Example: 1,307 clicks on Cross-network indicate that 1,307 clicks were recorded on Cross-network.
5.	Cost:
a.	Definition: The total amount of money spent on the ads.
b.	Unit: Currency (usually USD, but may vary based on account settings)
c.	Example: A cost of 1,845.1 on Cross-network means $1,845.10 was spent on Cross-network ads.
6.	Conversions:
a.	Definition: The total number of desired actions completed by users after interacting with the ad, such as purchases, sign-ups, or downloads.
b.	Unit: Count
c.	Example: 14.98 conversions on Cross-network indicate that 14.98 actions (e.g., purchases) were completed on Cross-network. Note: The fractional value might result from conversion tracking settings or attribution models.
7.	Total Conversion Value:
a.	Definition: The total monetary value attributed to the conversions. This is often calculated by assigning a value to each conversion action.
b.	Unit: Currency (matching the Cost unit)
c.	Example: A total conversion value of 6,179.8 on Cross-network means that the conversions generated $6,179.80 in value on Cross-network.

_Microsoft Ads_

Microsoft Ads (MS Ads) is an advertising platform where ads are displayed on Bing search results and across Microsoft's network of partner sites and apps. Its purpose is to capture search intent and drive conversions through targeted ad placements. Here is a breakdown of the fields and data structure for Microsoft Ads:
1.	Date:
a.	Definition: The specific day when the ad impressions were received.
b.	Format: YYYY-MM-DD (e.g., 2023-07-01)
c.	Purpose: To track and analyze performance over time.
2.	Campaign Type:
a.	Definition: The type of campaign used in Microsoft Ads. Each campaign type targets different networks or uses specific strategies:
i.	Audience: Targets ads to specific audience groups based on demographics, interests, or behaviors.
ii.	Performance Max: A campaign type that uses machine learning to optimize ads across all Microsoft channels.
iii.	Search & Content: Includes text ads on the search network and display ads on content partner sites.
iv.	Shopping: Focuses on promoting products by showing ads that include product details like image, price, and description.
3.	Impressions:
a.	Definition: The number of times ads were shown to users.
b.	Unit: Count
c.	Example: 15,586 impressions for Audience campaigns indicate the ads were displayed 15,586 times for Audience campaigns.
4.	Clicks:
a.	Definition: The number of times users clicked on the ads.
b.	Unit: Count
c.	Example: 89 clicks on Audience campaigns show that 89 interactions were recorded for Audience campaigns.
5.	Cost:
a.	Definition: The total spending on the ads within a specific period.
b.	Unit: Currency (e.g., USD)
c.	Example: A cost of $63.18 for Audience campaigns means $63.18 was spent on Audience campaigns.
6.	Conversions:
a.	Definition: The number of desired actions (like purchases, sign-ups, etc.) taken by users after clicking the ads.
b.	Unit: Count
c.	Example: 100 conversions for Audience campaigns indicate 100 desired actions were tracked for Audience campaigns.
7.	Revenue:
a.	Definition: The total income generated from the conversions tracked by the ads.
b.	Unit: Currency (e.g., USD)
c.	Example: A revenue of $1,316.34 from Search & Content campaigns means the actions taken by users (such as purchases) resulted in this amount of revenue.

_Meta Ads_
Meta Ads (formerly Facebook Ads) is an online advertising platform where ads appear on Facebook, Instagram, Messenger, and the Audience Network. Its purpose is to reach targeted audiences based on their interests, behaviors, and demographics to drive engagement and conversions. Here is a breakdown of the fields and data structure for Meta Ads:
1.	Date:
a.	Definition: The specific day when the ad metrics were recorded.
b.	Format: YYYY-MM-DD (e.g., 2023-08-10)
c.	Purpose: To track and analyze the performance of ads over specific time periods.
2.	Impressions:
a.	Definition: The total number of times ads were shown to users.
b.	Unit: Count
c.	Example: 7,104 impressions mean the ads were displayed 7,104 times.
3.	Reach:
a.	Definition: The number of unique users who saw the ads at least once.
b.	Unit: Count
c.	Example: A reach of 6,578 indicates that 6,578 unique users were exposed to the ads.
4.	Cost:
a.	Definition: The total amount spent on the ads.
b.	Unit: Currency (e.g., USD)
c.	Example: A cost of $42.04 means $42.04 was spent on ads.
5.	Link Clicks:
a.	Definition: The total number of clicks on links within the ads, leading to websites or other destinations.
b.	Unit: Count
c.	Example: 79 link clicks indicate that users clicked on the ad's link 79 times.
6.	Website Purchases:
a.	Definition: The number of purchase transactions completed on the website after users clicked on the ads.
b.	Unit: Count
c.	Example: 25 website purchases, indicate that twenty-five purchases were tracked as originating from ad interactions.
7.	Purchase Conversion Value:
a.	Definition: The total monetary value of the purchases made after users clicked on the ads.
b.	Unit: Currency (e.g., USD)
c.	Example: A purchase conversion value of $668.89 means that the purchases from ad clicks generated $668.89 in revenue.






_Website Landing Data_
1.	User Id
2.	Website Landing Time
3.	Is Converted
4.	Source
5.	Channel
6.	Campaign Type


_Website Landing Data_

The Website Landing Data from the LXRInsights tool typically consists of several fields that help track and analyze user interactions with a website. These fields capture information about the user's visit, the source of the visit, and whether a conversion occurred. Here is a breakdown of the fields and data structure:
1.	User Id:
a.	Definition: A unique identifier assigned to each visitor to the website. This could be an anonymized string or number that uniquely identifies a visitor session.
b.	Purpose: To track individual users across sessions and measure user behavior, conversions, and interactions on the website.
2.	Website Landing Time:
a.	Definition: The exact date and time when a user landed on the website.
b.	Format: Date and time format, typically in YYYY-MM-DD HH:MM
(e.g., 2023-07-01 14:35:20)
c.	Purpose: To understand when users visit the site, analyze peak times, and correlate with campaign performance.
3.	Source:
a.	Definition: The specific origin from where the user arrived at the website. This could be a search engine, social media platform, email campaign, or direct visit.
b.	Example: "Google", "Facebook", "Email", "Direct"
c.	Purpose: To attribute traffic to specific origins and assess the effectiveness of different sources.
4.	Channel:
a.	Definition: The broad category of the source, describing the type of medium used to reach the website. Common channels include Organic Search, Paid Search, Social Media, Email, Direct, and Referral.
b.	Example: "Organic Search", "Paid Search", "Social Media"
c.	Purpose: To categorize and analyze traffic sources by the channel, aiding in understanding overall marketing channel performance.
5.	Campaign Type:
a.	Definition: The specific marketing campaign or strategy that led the user to the website. This could be a seasonal sale, a specific product promotion, or a brand awareness campaign.
b.	Example: "Summer Sale", "Product Launch", "Retargeting"
c.	Purpose: To track and measure the effectiveness of specific campaigns, facilitating performance comparisons and optimization.
6.	Is Converted:
a.	Definition: A binary indicator showing whether the user completed a desired action or conversion on the website, such as making a purchase, signing up for a newsletter, or downloading a resource.
b.	Values: 1 for converted, 0 for not converted
c.	Purpose: To measure the success of website visits in achieving business goals, enabling the calculation of conversion rates.




