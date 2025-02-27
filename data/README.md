# Data

If using an external dataset (that doesn't come in an R package), place data file(s) in this folder.

Then, include metadata about your dataset including information on provenance, data dictionary, etc.

The data dictionary for your data file(s) using the following format.

## NYC-Airbnb-2023.csv

| Variable                          | Description                                                                    |
|:----------------------------------|:-------------------------------------------------------------------------------|
| **id**                            | Unique identifier assigned to each Airbnb listing.                             |
| **name**                          | Title or name of the Airbnb listing, provided by the host.                     |
| **host_id**                       | Unique identifier for the host who owns/manages the listing.                   |
| **host_name**                     | Name of the host.                                                              |
| **neighbourhood_group**           | Borough (e.g., Manhattan, Brooklyn, Queens, etc.) to which the listing belongs.|
| **neighbourhood**                 | More granular neighborhood within the borough.                                 |
| **latitude**                      | Geographical coordinate (latitude) of the listing’s location.                  |
| **longitude**                     | Geographical coordinate (longitude) of the listing’s location.                 |
| **room_type**                     | Type of room being offered (e.g., Entire home/apt, Private room, Shared room). |
| **price**                         | Nightly price in USD.                                                          |
| **minimum_nights**                | Minimum number of nights required for booking.                                 |
| **number_of_reviews**             | Total number of reviews received by the listing.                               |
| **last_review**                   | Date of the most recent review.                                                |
| **reviews_per_month**             | Average number of reviews the listing receives per month.                      |
| **calculated_host_listings_count**| Number of total listings posted by the host (may indicate whether the host is an individual or a business).|
| **availability_365**              | Number of days in a year that the listing is available for booking.            |
| **number_of_reviews_ltm**         | Number of reviews received by the listing in the last 12 months.               |
| **license (empty column)**        | License information for the listing (if provided).                             |
