# Final-Project-Airbnb-Asia-Pacific-APAC-Market-Analysis

Programmatic data science pipeline and exploratory analytics architecture evaluating over 29,000 Airbnb listings across 113 Asia-Pacific cities to isolate pricing dynamics, capacity optimization thresholds, and operational host performance drivers.


🌅The Asia-Pacific Tourism Boom


The Asia-Pacific region is a massive global tourism hotspot known for its beautiful tropical islands and busy cities. Recently, more travelers are choosing local Airbnb properties over traditional luxury hotels. This creates huge earning opportunities for property hosts. However, it also means the market is very competitive. Success depends heavily on how hosts set up their rentals and price their rooms.
This Python project explores the vacation rental market across major Asia-Pacific destinations. Using real data, the analysis looks past the postcards to study the actual numbers. By analyzing how properties are listed, priced, and booked, this project shows how to successfully run a vacation rental business in a top holiday market.


🎯 Project Objectives ¶
Find and Clean Data Errors: Detect and remove impossible listings—like 41 bedrooms or 999-night stay rules—before starting the analysis.
Analyze Pricing Factors: Find out which property traits (like bedrooms, beds, and size) affect the nightly price the most.
Study Cleaning Fees: Check how much hosts charge for cleaning and find out if higher fees affect overall bookings.
Map Out Supply & Demand: Identify which property sizes and layout styles are most common and popular in the market.
Compare City Differences: Contrast pricing and occupancy rates across different cities to locate the most profitable areas.
Track Room Types: Investigate whether entire homes, private rooms, or shared rooms perform best financially.
Review Superhost Value: Test if having a "Superhost" badge leads to higher nightly rates and better overall ratings.


📊Dataset Info
Target File Source: listings.csv
Total Volume: 29,153 total listings across the dataset
Geographic Distribution: Spans across 113 individual cities in the Asia-Pacific region
Listing Capping: Built with up to 300 representative listings per tracked city
Dataset Columns Breakdown:
Listing Core Details: listing_id, listing_type, room_type, cover_photo_url, photos_count, host_id, superhost
Geographic Location: latitude, longitude, city, state, country
Capacity & Layout: guests, bedrooms, beds, baths, amenities
Booking Rules & Fees: registration, instant_book, professional_management, min_nights, cancellation_policy, currency, cleaning_fee, extra_guest_fee
Review Scores: num_reviews, rating_overall, rating_accuracy, rating_checkin, rating_cleanliness, rating_communication, rating_location, rating_value
TTM Performance (Trailing Twelve Months): ttm_revenue, ttm_revenue_native, ttm_avg_rate, ttm_avg_rate_native, ttm_occupancy, ttm_adjusted_occupancy, ttm_revpar, ttm_revpar_native, ttm_adjusted_revpar, ttm_adjusted_revpar_native, ttm_reserved_days, ttm_blocked_days, ttm_available_days, ttm_total_days
L90D Performance (Last 90 Days): l90d_revenue, l90d_revenue_native, l90d_avg_rate, l90d_avg_rate_native, l90d_occupancy, l90d_adjusted_occupancy, l90d_revpar, l90d_revpar_native, l90d_adjusted_revpar, l90d_adjusted_revpar_native, l90d_reserved_days, l90d_blocked_days, l90d_available_days, l90d_total_days
