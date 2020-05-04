# Fradulent retail accounts
<br />
Below is a daily table for an active accounts at Shopify (an online ecommerce, retail platform).<br />
<br />
The table is called store_account and the columns are:<br />

| ColumnName        | DataType           | Description  |
| ------------- |:-------------:| -----:|
| store_id      | integer | a unique Shopify store id |
| date      | string |   date |
| status | string    |    Possible values are: [‘open’, 'closed’, ‘fraud’] |
| revenue | double      |    Amount of spend in USD |
 <br />
Here's some more information about the table: <br />
 <br />
The granularity of the table is store_id and day <br />
Assume “close” and “fraud” are permanent labels <br />
Active = daily revenue > 0 <br />
Accounts get labeled by Shopify as fraudulent and they no longer can sell product <br />
Every day of the table has every store_id that has ever been used by Shopify <br />
 <br />
Given the above, what percent of active stores were fraudulent by day? <br />
