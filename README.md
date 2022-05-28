Vanity Phone Number generator

Project Preview
I used serverless cloudformation for all my resource creations.  Project resources include a lambda function and a DynamoDB database table

1. Lambda function
- This function takes a seven digit phone number as a parameter and returns x number of possible vanity phone numbers.  It also saves five posibile vanity phone numbers to the DynamoDB table.

2.  DynamoDB Table
- This table has an ID, a phone number and a column containing multiple vanity phone numbers based on the single phone number used as input from the calling Lambda function.