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

### Table : categories_list

| category_id |    category   | language | number_of_channels | price |
|:-----------:|:-------------:|:--------:|:------------------:|:-----:|
|     1ta     | entertainment |   tamil  |          2         | 42.48 |
|     2te     |     movies    |  telugu  |          2         | 31.86 |
|     3en     |     sports    |  english |          1         | 22.42 |
|     4ta     |   knowledge   |   tamil  |          2         |  8.26 |
|     5hi     |      news     |   hindi  |          2         |  1.30 |
|     6ta     |      kids     |   tamil  |          1         |  7.08 |
|     7en     |     music     |  english |          2         |  4.72 |

### Table : special_packs

| pack_id |      pack_name     | number_of_channels |  price |
|:-------:|:------------------:|:------------------:|:------:|
|   p2p3  | south special pack |         21         | 207.68 |
|    p2   |     tamil basic    |         11         | 112.10 |
|    p3   |    telugu basic    |         10         |  95.58 |
|    p4   |     hindi basic    |          7         |  57.06 |
|    p5   |    english basic   |         12         |  90.86 

### Table : channel_categories_list

| channel_id | channel_name | language | price_amount | category_id | special_pack_id |
|:----------:|:------------:|:--------:|:------------:|:-----------:|:---------------:|
|    1518    |  star vijay  |   tamil  |     20.06    |     1ta     |        p2       |
|    1423    |   star maa   |  telugu  |     22.42    |     1te     |        p3       | 
|     206    |  star world  |  english |     9.44     |     1en     |        p5       |
|     314    |   sony max   |   hindi  |     17.72    |     2hi     |        p4       |
|     714    |   discovery  |  english |     4.72     |     4en     |        p5       |
|     670    |     pogo     |   hindi  |     5.02     |     6hi     |        p4       |
|     690    |   chutti tv  |   tamil  |     7.08     |     6ta     |        p2       |

### Table : user_subscribed_list

| selection_id | user_id | category_id | pack_id | number_of_channels | price_amount | active_date | deactive_date | payment_status |
|:------------:|:-------:|:-----------:|:-------:|:------------------:|:------------:|:-----------:|:-------------:|:--------------:|
|       1      |   101   |     6en     |    p2   |         12         |    123.90    |  12-JAN-20  |   10-FEB-20   |    Completed   |
|       2      |   102   |     5hi     |    p5   |         14         |     92.16    |  11-JAN-20  |   09-FEB-20   |    Completed   |
|       3      |   103   |     5en     |    p3   |         12         |    100.30    |  10-JAN-20  |   08-FEB-20   |    Completed   |

