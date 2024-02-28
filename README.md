# Used Cars Dataset

## Overview

This dataset contains information on used cars from eBay Kleinanzeigen, the classifieds section of the German eBay website. The dataset, available on Kaggle, consists of 50,000 data points, simulating a less-cleaned version.

## Data Dictionary

- `dateCrawled`: Date of the first crawl.
- `name`: Car name.
- `seller`: Private or dealer seller.
- `offerType`: Type of listing.
- `price`: Advertised car price.
- ...

## Dataset Overview

The dataset comprises 20 columns, mostly stored as strings. There are a few columns with null values, and some columns store date information as strings.

## Data Cleaning Approach

### Column Name Standardization

We started by cleaning the column names for better usability:
- Converted all names to lowercase.
- Adjusted wordings for clarity.

### Initial Observations

We identified and addressed the following issues:
- Dropped columns with constant values: `seller`, `offer_type`.
- Investigated and handled issues with `num_photos`.
- Removed rows with $0 prices (1,421 entries).
- Addressed unusual maximum price ($100 million).

## Feedback

Your feedback is highly appreciated. Feel free to provide comments or suggestions. Thank you!
