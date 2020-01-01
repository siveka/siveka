# tatasky channel selection app

### Table : chaneel_list

| channel_name | channel_id | language | free_or_pay | price | price_with_tax |
|--------------|------------|----------|-------------|-------|----------------|
| star vijay   | 1518       | tamil    | pay         | 17.00 | 20.06          |
| star maa     | 1423       | telugu   | pay         | 19.00 | 22.42          |
| india today  | 609        | english  | free        | 00.00 | 00.00          |
| zee hindi    | 1104       | hindi    | pay         | 1.00  | 1.18           |


### Table : user_list

| user_id | user_name |     email_id     | phone_number |
|:-------:|:---------:|:----------------:|:------------:|
|   101   |   suresh  | suresh@gmail.com |  9887766543  |
|   102   |    john   |  john@gmail.com  |  9876434523  |
|   103   |    jeni   |  jeni@gmail.com  |  9976542354  |


### Table : user_subscribed_list

| selection_id | user_id | channel_id | price_amount | active_date | deactive_date | payment_status |
|:------------:|:-------:|:----------:|:------------:|:-----------:|:-------------:|:--------------:|
|       1      |   101   |    1518    |     20.06    |  01-jan-20  |   30-jan-20   |    completed   |
|       2      |   101   |    1423    |     22.42    |  01-jan-20  |   30-jan-20   |    completed   |
|       3      |   102   |     609    |     00.00    |  01-jan-20  |   30-jan-20   |    completed   |
|       4      |   103   |     609    |     00.00    |  01-jan-20  |   30-jan-20   |    completed   |
|       5      |   103   |    1518    |     20.06    |  01-jan-20  |   30-jan-20   |    completed   |

