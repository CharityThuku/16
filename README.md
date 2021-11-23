# Overview of the Project.
- The overview was to create a database using the AWS server. Amazon makes their vine review datasets public, for this project,I reviewed sports reviews using [Sport Reviews Dataset]( https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Sports_v1_00.tsv.gz). The process of extracting, transforming and loading was done using PySpark on Google Colabs.

## Results.
- How many Vine reviews and non-Vine reviews were there?

![reviews total](https://user-images.githubusercontent.com/85714314/142979124-6da6f43b-508a-4cab-bf70-155fbc534640.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

![5 star](https://user-images.githubusercontent.com/85714314/142979235-63fb6cdf-421f-4252-bb5d-8b246d97700b.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

![%](https://user-images.githubusercontent.com/85714314/142979340-a307a2a3-4be8-4034-9c9e-4174abace829.png)

## Summary.
- The results displayed there are only 41.6% Vine reviews as opposed to 53% Non-Vine reviews. This suggests a lack of bias among viewers.However, the reviews include 334 vine reviews as opposed to 61614 non-vine reviews which is a significant difference.

# Resources.
- AWS, Google Colab, PySpark, PostgreSQL
