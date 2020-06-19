###  В данных есть пустые заказы, но их мало

    количество пустых заказов:  29

<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th></th>
      <th>Unnamed: 0</th>
      <th>id</th>
      <th>user_id</th>
      <th>total_cost</th>
      <th>cost</th>
      <th>item_total</th>
      <th>promo_total</th>
      <th>total_weight</th>
      <th>total_quantity</th>
      <th>state</th>
      <th>...</th>
      <th>item_total_class</th>
      <th>in_time</th>
      <th>delta_t</th>
      <th>promo_count</th>
      <th>order_count</th>
      <th>old_client</th>
      <th>item_total_avg</th>
      <th>user_class</th>
      <th>total_quantity_class</th>
      <th>total_weight_class</th>
    </tr>
    <tr>
      <th>retailer_id</th>
      <th>store_id</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="11" valign="top">1.0</th>
      <th>1</th>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>2</th>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>3</th>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>...</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
    </tr>
    <tr>
      <th>8</th>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>...</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
      <td>6</td>
    </tr>
    <tr>
      <th>10</th>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>11</th>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>12</th>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>...</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
      <td>3</td>
    </tr>
    <tr>
      <th>14</th>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>18</th>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>...</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
      <td>1</td>
    </tr>
    <tr>
      <th>21</th>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>...</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
      <td>2</td>
    </tr>
    <tr>
      <th>98</th>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>...</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
      <td>4</td>
    </tr>
  </tbody>
</table>
<p>11 rows × 37 columns</p>
</div>


    распределение пустых заказов по магазинам





    627       10
    31719     14
    47726      1
    68400     58
    168660     8
    169944    18
    183126    14
    211247    18
    216071    14
    224511    12
    224880    12
    250659    21
    252205    14
    Name: store_id, dtype: int64




    распределение пустых заказов по ритейлерам





    627       1.0
    31719     1.0
    47726     1.0
    68400     NaN
    168660    1.0
    169944    1.0
    183126    1.0
    211247    1.0
    216071    1.0
    224511    1.0
    224880    1.0
    250659    1.0
    252205    1.0
    Name: retailer_id, dtype: float64



они все у одного ритейлера, но по нему самая большая статистика, так что неудивительно


### Посчитаем квантили по выручке, чееку, делям отмены и замены, числу товаров


<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>retailer_id</th>
      <th>1.0</th>
      <th>8.0</th>
      <th>15.0</th>
      <th>16.0</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="4" valign="top">total_cost</th>
      <th>count</th>
      <td>323398.000000</td>
      <td>1436.000000</td>
      <td>7574.000000</td>
      <td>192.000000</td>
    </tr>
    <tr>
      <th>q10</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>199.000000</td>
      <td>290.000000</td>
      <td>199.000000</td>
      <td>158.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>447.000000</td>
      <td>398.000000</td>
      <td>398.000000</td>
      <td>299.000000</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">item_total</th>
      <th>count</th>
      <td>323398.000000</td>
      <td>1436.000000</td>
      <td>7574.000000</td>
      <td>192.000000</td>
    </tr>
    <tr>
      <th>q10</th>
      <td>1684.000000</td>
      <td>1076.500000</td>
      <td>1365.600000</td>
      <td>1059.800000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>3912.000000</td>
      <td>2817.000000</td>
      <td>2986.500000</td>
      <td>2843.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>11483.150000</td>
      <td>7025.500000</td>
      <td>7091.700000</td>
      <td>6023.500000</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">cancel_freq</th>
      <th>count</th>
      <td>323398.000000</td>
      <td>1436.000000</td>
      <td>7574.000000</td>
      <td>192.000000</td>
    </tr>
    <tr>
      <th>q10</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>0.020000</td>
      <td>0.075000</td>
      <td>0.046512</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>0.200000</td>
      <td>0.400000</td>
      <td>0.303030</td>
      <td>0.222500</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">replace_freq</th>
      <th>count</th>
      <td>323398.000000</td>
      <td>1436.000000</td>
      <td>7574.000000</td>
      <td>192.000000</td>
    </tr>
    <tr>
      <th>q10</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>0.000000</td>
      <td>0.028992</td>
      <td>0.030303</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>0.133333</td>
      <td>0.250000</td>
      <td>0.181818</td>
      <td>0.234722</td>
    </tr>
    <tr>
      <th rowspan="4" valign="top">total_quantity</th>
      <th>count</th>
      <td>323398.000000</td>
      <td>1436.000000</td>
      <td>7574.000000</td>
      <td>192.000000</td>
    </tr>
    <tr>
      <th>q10</th>
      <td>9.000000</td>
      <td>9.000000</td>
      <td>12.000000</td>
      <td>5.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>31.000000</td>
      <td>22.000000</td>
      <td>28.000000</td>
      <td>14.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>112.000000</td>
      <td>63.250000</td>
      <td>75.000000</td>
      <td>36.900000</td>
    </tr>
  </tbody>
</table>
</div>



### у ритейлеров 8 и 15 достаточно много замен и отмен по сравнению с 1 (у ритейлера 16 мало статистики)



<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>store_id</th>
      <th>1</th>
      <th>2</th>
      <th>3</th>
      <th>6</th>
      <th>8</th>
      <th>9</th>
      <th>10</th>
      <th>11</th>
      <th>12</th>
      <th>14</th>
      <th>...</th>
      <th>95</th>
      <th>98</th>
      <th>99</th>
      <th>100</th>
      <th>105</th>
      <th>108</th>
      <th>112</th>
      <th>113</th>
      <th>118</th>
      <th>120</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="3" valign="top">total_cost</th>
      <th>count</th>
      <td>26758.00000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>249.00000</td>
      <td>249.000000</td>
      <td>199.000000</td>
      <td>278.000000</td>
      <td>249.000000</td>
      <td>199.000000</td>
      <td>199.000000</td>
      <td>224.000000</td>
      <td>249.000000</td>
      <td>249.000000</td>
      <td>...</td>
      <td>99.000000</td>
      <td>99.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>99.000000</td>
      <td>99.000000</td>
      <td>158.000000</td>
      <td>158.000000</td>
      <td>99.000000</td>
      <td>158.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>459.00000</td>
      <td>479.000000</td>
      <td>404.000000</td>
      <td>388.000000</td>
      <td>448.000000</td>
      <td>409.000000</td>
      <td>414.000000</td>
      <td>448.000000</td>
      <td>489.000000</td>
      <td>469.000000</td>
      <td>...</td>
      <td>319.000000</td>
      <td>158.000000</td>
      <td>199.000000</td>
      <td>199.000000</td>
      <td>158.000000</td>
      <td>158.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>178.400000</td>
      <td>158.000000</td>
    </tr>
    <tr>
      <th rowspan="3" valign="top">item_total</th>
      <th>count</th>
      <td>26758.00000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>4033.50000</td>
      <td>4058.000000</td>
      <td>3598.000000</td>
      <td>2837.000000</td>
      <td>3865.000000</td>
      <td>3887.000000</td>
      <td>4017.000000</td>
      <td>4128.000000</td>
      <td>4276.000000</td>
      <td>4091.000000</td>
      <td>...</td>
      <td>3736.000000</td>
      <td>3144.000000</td>
      <td>2069.000000</td>
      <td>2163.500000</td>
      <td>3152.000000</td>
      <td>3088.500000</td>
      <td>3050.500000</td>
      <td>3093.000000</td>
      <td>3349.000000</td>
      <td>2368.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>11745.45000</td>
      <td>11977.800000</td>
      <td>9689.500000</td>
      <td>8156.000000</td>
      <td>10649.000000</td>
      <td>10468.000000</td>
      <td>11159.000000</td>
      <td>11208.000000</td>
      <td>14197.000000</td>
      <td>11567.000000</td>
      <td>...</td>
      <td>9946.500000</td>
      <td>7694.600000</td>
      <td>4967.000000</td>
      <td>4668.150000</td>
      <td>7757.300000</td>
      <td>7809.000000</td>
      <td>6127.500000</td>
      <td>5647.250000</td>
      <td>8956.800000</td>
      <td>4597.650000</td>
    </tr>
    <tr>
      <th rowspan="3" valign="top">cancel_freq</th>
      <th>count</th>
      <td>26758.00000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>0.02000</td>
      <td>0.016129</td>
      <td>0.030303</td>
      <td>0.062112</td>
      <td>0.023256</td>
      <td>0.023256</td>
      <td>0.022727</td>
      <td>0.027523</td>
      <td>0.000000</td>
      <td>0.021739</td>
      <td>...</td>
      <td>0.009662</td>
      <td>0.035714</td>
      <td>0.071429</td>
      <td>0.052632</td>
      <td>0.038462</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.002370</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>0.18750</td>
      <td>0.166667</td>
      <td>0.250000</td>
      <td>0.309524</td>
      <td>0.222222</td>
      <td>0.205882</td>
      <td>0.208333</td>
      <td>0.206897</td>
      <td>0.173913</td>
      <td>0.210526</td>
      <td>...</td>
      <td>0.182997</td>
      <td>0.307692</td>
      <td>0.363636</td>
      <td>0.241855</td>
      <td>0.250000</td>
      <td>0.187500</td>
      <td>0.174020</td>
      <td>0.210227</td>
      <td>0.142857</td>
      <td>0.333333</td>
    </tr>
    <tr>
      <th rowspan="3" valign="top">replace_freq</th>
      <th>count</th>
      <td>26758.00000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>0.00000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.046512</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.136364</td>
      <td>0.109610</td>
      <td>0.000000</td>
      <td>0.017241</td>
      <td>0.000000</td>
      <td>0.050000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q95</th>
      <td>0.12766</td>
      <td>0.117647</td>
      <td>0.125992</td>
      <td>0.181818</td>
      <td>0.133333</td>
      <td>0.115385</td>
      <td>0.142857</td>
      <td>0.130435</td>
      <td>0.132843</td>
      <td>0.125000</td>
      <td>...</td>
      <td>0.106649</td>
      <td>0.130435</td>
      <td>0.375000</td>
      <td>0.281818</td>
      <td>0.111111</td>
      <td>0.148148</td>
      <td>0.195455</td>
      <td>0.232955</td>
      <td>0.100000</td>
      <td>0.335417</td>
    </tr>
  </tbody>
</table>
<p>12 rows × 33 columns</p>
</div>



### Магазинов много, поэтому можно посчитать среднее и дисперсию и посмотреть отклонение больше одного стандартного

* replace_freq


    total_cost    count    10127.757576
                  q50        168.484848
                  q95        329.140909
    item_total    count    10127.757576
                  q50       3326.939394
                  q95       8766.627273
    cancel_freq   count    10127.757576
                  q50          0.028053
                  q95          0.231953
    replace_freq  count    10127.757576
                  q50          0.020162
                  q95          0.169612
    dtype: float64 total_cost    count    12177.019496
                  q50         83.696670
                  q95        122.791413
    item_total    count    12177.019496
                  q50        636.276580
                  q95       2550.155990
    cancel_freq   count    12177.019496
                  q50          0.022284
                  q95          0.071296
    replace_freq  count    12177.019496
                  q50          0.032472
                  q95          0.068534
    dtype: float64





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th colspan="3" halign="left">total_cost</th>
      <th colspan="3" halign="left">item_total</th>
      <th colspan="3" halign="left">cancel_freq</th>
      <th colspan="3" halign="left">replace_freq</th>
    </tr>
    <tr>
      <th></th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
    </tr>
    <tr>
      <th>store_id</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>56</th>
      <td>558</td>
      <td>199.0</td>
      <td>304.55</td>
      <td>558</td>
      <td>2456.0</td>
      <td>6199.45</td>
      <td>558</td>
      <td>0.071946</td>
      <td>0.386923</td>
      <td>558</td>
      <td>0.058824</td>
      <td>0.277778</td>
    </tr>
    <tr>
      <th>99</th>
      <td>41</td>
      <td>0.0</td>
      <td>199.00</td>
      <td>41</td>
      <td>2069.0</td>
      <td>4967.00</td>
      <td>41</td>
      <td>0.071429</td>
      <td>0.363636</td>
      <td>41</td>
      <td>0.136364</td>
      <td>0.375000</td>
    </tr>
    <tr>
      <th>100</th>
      <td>58</td>
      <td>0.0</td>
      <td>199.00</td>
      <td>58</td>
      <td>2163.5</td>
      <td>4668.15</td>
      <td>58</td>
      <td>0.052632</td>
      <td>0.241855</td>
      <td>58</td>
      <td>0.109610</td>
      <td>0.281818</td>
    </tr>
  </tbody>
</table>
</div>



### Магазин 56 часто заменяет товары

* cancel_freq


    total_cost    count    10127.757576
                  q50        168.484848
                  q95        329.140909
    item_total    count    10127.757576
                  q50       3326.939394
                  q95       8766.627273
    cancel_freq   count    10127.757576
                  q50          0.028053
                  q95          0.231953
    replace_freq  count    10127.757576
                  q50          0.020162
                  q95          0.169612
    dtype: float64 total_cost    count    12177.019496
                  q50         83.696670
                  q95        122.791413
    item_total    count    12177.019496
                  q50        636.276580
                  q95       2550.155990
    cancel_freq   count    12177.019496
                  q50          0.022284
                  q95          0.071296
    replace_freq  count    12177.019496
                  q50          0.032472
                  q95          0.068534
    dtype: float64





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th colspan="3" halign="left">total_cost</th>
      <th colspan="3" halign="left">item_total</th>
      <th colspan="3" halign="left">cancel_freq</th>
      <th colspan="3" halign="left">replace_freq</th>
    </tr>
    <tr>
      <th></th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
      <th>count</th>
      <th>q50</th>
      <th>q95</th>
    </tr>
    <tr>
      <th>store_id</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>6</th>
      <td>541</td>
      <td>278.0</td>
      <td>388.00</td>
      <td>541</td>
      <td>2837.0</td>
      <td>8156.00</td>
      <td>541</td>
      <td>0.062112</td>
      <td>0.309524</td>
      <td>541</td>
      <td>0.046512</td>
      <td>0.181818</td>
    </tr>
    <tr>
      <th>18</th>
      <td>542</td>
      <td>299.0</td>
      <td>499.00</td>
      <td>542</td>
      <td>3221.0</td>
      <td>7644.85</td>
      <td>542</td>
      <td>0.027778</td>
      <td>0.095022</td>
      <td>542</td>
      <td>0.027778</td>
      <td>0.083114</td>
    </tr>
    <tr>
      <th>56</th>
      <td>558</td>
      <td>199.0</td>
      <td>304.55</td>
      <td>558</td>
      <td>2456.0</td>
      <td>6199.45</td>
      <td>558</td>
      <td>0.071946</td>
      <td>0.386923</td>
      <td>558</td>
      <td>0.058824</td>
      <td>0.277778</td>
    </tr>
    <tr>
      <th>57</th>
      <td>1337</td>
      <td>299.0</td>
      <td>398.00</td>
      <td>1337</td>
      <td>2856.0</td>
      <td>7376.20</td>
      <td>1337</td>
      <td>0.076923</td>
      <td>0.400000</td>
      <td>1337</td>
      <td>0.019608</td>
      <td>0.222222</td>
    </tr>
    <tr>
      <th>58</th>
      <td>517</td>
      <td>0.0</td>
      <td>382.00</td>
      <td>517</td>
      <td>2635.0</td>
      <td>6851.60</td>
      <td>517</td>
      <td>0.062500</td>
      <td>0.308654</td>
      <td>517</td>
      <td>0.045455</td>
      <td>0.222222</td>
    </tr>
    <tr>
      <th>70</th>
      <td>6574</td>
      <td>249.0</td>
      <td>429.00</td>
      <td>6574</td>
      <td>3064.0</td>
      <td>7251.70</td>
      <td>6574</td>
      <td>0.047619</td>
      <td>0.312500</td>
      <td>6574</td>
      <td>0.027027</td>
      <td>0.176471</td>
    </tr>
    <tr>
      <th>98</th>
      <td>5013</td>
      <td>99.0</td>
      <td>158.00</td>
      <td>5013</td>
      <td>3144.0</td>
      <td>7694.60</td>
      <td>5013</td>
      <td>0.035714</td>
      <td>0.307692</td>
      <td>5013</td>
      <td>0.000000</td>
      <td>0.130435</td>
    </tr>
    <tr>
      <th>118</th>
      <td>2113</td>
      <td>99.0</td>
      <td>178.40</td>
      <td>2113</td>
      <td>3349.0</td>
      <td>8956.80</td>
      <td>2113</td>
      <td>0.002370</td>
      <td>0.142857</td>
      <td>2113</td>
      <td>0.000000</td>
      <td>0.100000</td>
    </tr>
  </tbody>
</table>
</div>



### 118, 12, 108 почти не отменяют
### 6, 56, 57, 58 много отменяют

## Посмотрим на delta_t (величина, которая показывает отклонение времени доставки от окна доставки)





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>store_id</th>
      <th>1</th>
      <th>2</th>
      <th>3</th>
      <th>6</th>
      <th>8</th>
      <th>9</th>
      <th>10</th>
      <th>11</th>
      <th>12</th>
      <th>14</th>
      <th>...</th>
      <th>95</th>
      <th>98</th>
      <th>99</th>
      <th>100</th>
      <th>105</th>
      <th>108</th>
      <th>112</th>
      <th>113</th>
      <th>118</th>
      <th>120</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="3" valign="top">total_cost</th>
      <th>count</th>
      <td>26758.000000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>249.000000</td>
      <td>249.000000</td>
      <td>199.000000</td>
      <td>278.000000</td>
      <td>249.000000</td>
      <td>199.000000</td>
      <td>199.000000</td>
      <td>224.000000</td>
      <td>249.000000</td>
      <td>249.000000</td>
      <td>...</td>
      <td>99.000000</td>
      <td>99.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>99.000000</td>
      <td>99.000000</td>
      <td>158.000000</td>
      <td>158.000000</td>
      <td>99.000000</td>
      <td>158.000000</td>
    </tr>
    <tr>
      <th>q75</th>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>299.000000</td>
      <td>...</td>
      <td>299.000000</td>
      <td>149.000000</td>
      <td>199.000000</td>
      <td>199.000000</td>
      <td>149.000000</td>
      <td>149.000000</td>
      <td>299.000000</td>
      <td>188.750000</td>
      <td>158.000000</td>
      <td>158.000000</td>
    </tr>
    <tr>
      <th rowspan="3" valign="top">item_total</th>
      <th>count</th>
      <td>26758.000000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>4033.500000</td>
      <td>4058.000000</td>
      <td>3598.000000</td>
      <td>2837.000000</td>
      <td>3865.000000</td>
      <td>3887.000000</td>
      <td>4017.000000</td>
      <td>4128.000000</td>
      <td>4276.000000</td>
      <td>4091.000000</td>
      <td>...</td>
      <td>3736.000000</td>
      <td>3144.000000</td>
      <td>2069.000000</td>
      <td>2163.500000</td>
      <td>3152.000000</td>
      <td>3088.500000</td>
      <td>3050.500000</td>
      <td>3093.000000</td>
      <td>3349.000000</td>
      <td>2368.000000</td>
    </tr>
    <tr>
      <th>q75</th>
      <td>6011.750000</td>
      <td>6029.000000</td>
      <td>5258.000000</td>
      <td>4419.000000</td>
      <td>5720.000000</td>
      <td>5664.500000</td>
      <td>6042.000000</td>
      <td>6066.750000</td>
      <td>6574.500000</td>
      <td>6110.500000</td>
      <td>...</td>
      <td>5479.750000</td>
      <td>4508.000000</td>
      <td>2906.000000</td>
      <td>2830.250000</td>
      <td>4449.000000</td>
      <td>4417.250000</td>
      <td>4511.000000</td>
      <td>4270.000000</td>
      <td>4903.000000</td>
      <td>2924.750000</td>
    </tr>
    <tr>
      <th rowspan="3" valign="top">cancel_freq</th>
      <th>count</th>
      <td>26758.000000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>0.020000</td>
      <td>0.016129</td>
      <td>0.030303</td>
      <td>0.062112</td>
      <td>0.023256</td>
      <td>0.023256</td>
      <td>0.022727</td>
      <td>0.027523</td>
      <td>0.000000</td>
      <td>0.021739</td>
      <td>...</td>
      <td>0.009662</td>
      <td>0.035714</td>
      <td>0.071429</td>
      <td>0.052632</td>
      <td>0.038462</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.002370</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q75</th>
      <td>0.064516</td>
      <td>0.057692</td>
      <td>0.086957</td>
      <td>0.125000</td>
      <td>0.074074</td>
      <td>0.069767</td>
      <td>0.071429</td>
      <td>0.075000</td>
      <td>0.052632</td>
      <td>0.071429</td>
      <td>...</td>
      <td>0.057143</td>
      <td>0.100000</td>
      <td>0.133333</td>
      <td>0.142857</td>
      <td>0.096774</td>
      <td>0.058824</td>
      <td>0.043247</td>
      <td>0.052451</td>
      <td>0.054054</td>
      <td>0.114583</td>
    </tr>
    <tr>
      <th rowspan="3" valign="top">replace_freq</th>
      <th>count</th>
      <td>26758.000000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.046512</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.136364</td>
      <td>0.109610</td>
      <td>0.000000</td>
      <td>0.017241</td>
      <td>0.000000</td>
      <td>0.050000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q75</th>
      <td>0.042216</td>
      <td>0.037037</td>
      <td>0.038462</td>
      <td>0.093750</td>
      <td>0.043478</td>
      <td>0.037037</td>
      <td>0.047619</td>
      <td>0.046512</td>
      <td>0.039216</td>
      <td>0.040000</td>
      <td>...</td>
      <td>0.037736</td>
      <td>0.040000</td>
      <td>0.250000</td>
      <td>0.156883</td>
      <td>0.040000</td>
      <td>0.062500</td>
      <td>0.090909</td>
      <td>0.121528</td>
      <td>0.037037</td>
      <td>0.082692</td>
    </tr>
    <tr>
      <th rowspan="3" valign="top">delta_t</th>
      <th>count</th>
      <td>26758.000000</td>
      <td>34537.000000</td>
      <td>19411.000000</td>
      <td>541.000000</td>
      <td>28271.000000</td>
      <td>13387.000000</td>
      <td>22911.000000</td>
      <td>21430.000000</td>
      <td>34331.000000</td>
      <td>34740.000000</td>
      <td>...</td>
      <td>1994.000000</td>
      <td>5013.000000</td>
      <td>41.000000</td>
      <td>58.000000</td>
      <td>6662.000000</td>
      <td>3936.000000</td>
      <td>126.000000</td>
      <td>26.000000</td>
      <td>2113.000000</td>
      <td>40.000000</td>
    </tr>
    <tr>
      <th>q50</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
    </tr>
    <tr>
      <th>q75</th>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>...</td>
      <td>0.000000</td>
      <td>0.197222</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.167153</td>
      <td>0.000000</td>
      <td>0.000000</td>
      <td>0.203819</td>
    </tr>
  </tbody>
</table>
<p>15 rows × 33 columns</p>
</div>





    средний 0.5 квантиль:  -0.05869528619528619 
    отклонение 0.5 квантиля:  0.3371787486053004





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th colspan="3" halign="left">total_cost</th>
      <th colspan="3" halign="left">item_total</th>
      <th colspan="3" halign="left">cancel_freq</th>
      <th colspan="3" halign="left">replace_freq</th>
      <th colspan="3" halign="left">delta_t</th>
    </tr>
    <tr>
      <th></th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
    </tr>
    <tr>
      <th>store_id</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>18</th>
      <td>542</td>
      <td>299.0</td>
      <td>299.0</td>
      <td>542</td>
      <td>3221.0</td>
      <td>4677.5</td>
      <td>542</td>
      <td>0.027778</td>
      <td>0.055556</td>
      <td>542</td>
      <td>0.027778</td>
      <td>0.055556</td>
      <td>542</td>
      <td>-1.936944</td>
      <td>-1.789792</td>
    </tr>
  </tbody>
</table>
</div>



### 18 магазин привозит на 2 часа раньше в половине случаев


    средний 0.75 квантиль:  0.013705808080808084 
    отклонение 0.75 квантиля:  0.41007701020949144





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th colspan="3" halign="left">total_cost</th>
      <th colspan="3" halign="left">item_total</th>
      <th colspan="3" halign="left">cancel_freq</th>
      <th colspan="3" halign="left">replace_freq</th>
      <th colspan="3" halign="left">delta_t</th>
    </tr>
    <tr>
      <th></th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
      <th>count</th>
      <th>q50</th>
      <th>q75</th>
    </tr>
    <tr>
      <th>store_id</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>18</th>
      <td>542</td>
      <td>299.0</td>
      <td>299.0</td>
      <td>542</td>
      <td>3221.0</td>
      <td>4677.5</td>
      <td>542</td>
      <td>0.027778</td>
      <td>0.055556</td>
      <td>542</td>
      <td>0.027778</td>
      <td>0.055556</td>
      <td>542</td>
      <td>-1.936944</td>
      <td>-1.789792</td>
    </tr>
    <tr>
      <th>57</th>
      <td>1337</td>
      <td>299.0</td>
      <td>299.0</td>
      <td>1337</td>
      <td>2856.0</td>
      <td>4148.0</td>
      <td>1337</td>
      <td>0.076923</td>
      <td>0.163636</td>
      <td>1337</td>
      <td>0.019608</td>
      <td>0.092105</td>
      <td>1337</td>
      <td>0.000000</td>
      <td>1.417778</td>
    </tr>
  </tbody>
</table>
</div>



### 57 магазин привозит на 1.41 часа позже в 1/4 случаев





    retailer_id  in_time
    1.0          earlier    0.095331
                 in_time    0.745595
                 later      0.159073
    8.0          earlier    0.113510
                 in_time    0.486072
                 later      0.400418
    15.0         earlier    0.136784
                 in_time    0.776076
                 later      0.087140
    16.0         earlier    0.093750
                 in_time    0.593750
                 later      0.312500
    Name: id, dtype: float64



### 8 ритейлер в 40% случаев опаздывает





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th>in_time</th>
      <th colspan="10" halign="left">earlier</th>
      <th>...</th>
      <th colspan="10" halign="left">later</th>
    </tr>
    <tr>
      <th>store_id</th>
      <th>1</th>
      <th>2</th>
      <th>3</th>
      <th>6</th>
      <th>8</th>
      <th>9</th>
      <th>10</th>
      <th>11</th>
      <th>12</th>
      <th>14</th>
      <th>...</th>
      <th>95</th>
      <th>98</th>
      <th>99</th>
      <th>100</th>
      <th>105</th>
      <th>108</th>
      <th>112</th>
      <th>113</th>
      <th>118</th>
      <th>120</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>id</th>
      <td>0.057553</td>
      <td>0.0745</td>
      <td>0.111535</td>
      <td>0.460259</td>
      <td>0.079587</td>
      <td>0.149249</td>
      <td>0.086683</td>
      <td>0.072795</td>
      <td>0.110804</td>
      <td>0.093408</td>
      <td>...</td>
      <td>0.168004</td>
      <td>0.309595</td>
      <td>0.097561</td>
      <td>0.034483</td>
      <td>0.205944</td>
      <td>0.241108</td>
      <td>0.333333</td>
      <td>0.115385</td>
      <td>0.098438</td>
      <td>0.375</td>
    </tr>
  </tbody>
</table>
<p>1 rows × 99 columns</p>
</div>






    {'earlier': [6, 18, 100, 113],
     'later': [57, 58, 98, 112, 120],
     'in_time': [118]}



### Статистика по магазинам:
### 6, 18, 100, 113 часто привозят раньше
### 57, 58, 98, 112, 120 часто привозят позже
### 118 привозит вовремя

## Посмотрим на прибыль




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>mean</th>
      <th>q10</th>
      <th>q50</th>
      <th>q75</th>
      <th>q95</th>
    </tr>
    <tr>
      <th>retailer_id</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>1.0</th>
      <td>189.734721</td>
      <td>0.0</td>
      <td>199.0</td>
      <td>299.0</td>
      <td>447.0</td>
    </tr>
    <tr>
      <th>8.0</th>
      <td>183.738858</td>
      <td>0.0</td>
      <td>290.0</td>
      <td>299.0</td>
      <td>398.0</td>
    </tr>
    <tr>
      <th>15.0</th>
      <td>167.676129</td>
      <td>0.0</td>
      <td>199.0</td>
      <td>299.0</td>
      <td>398.0</td>
    </tr>
    <tr>
      <th>16.0</th>
      <td>161.468750</td>
      <td>0.0</td>
      <td>158.0</td>
      <td>299.0</td>
      <td>299.0</td>
    </tr>
  </tbody>
</table>
</div>





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th></th>
      <th>mean</th>
      <th>q10</th>
      <th>q50</th>
      <th>q75</th>
      <th>q95</th>
    </tr>
    <tr>
      <th>city</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>201.207188</td>
      <td>0.0</td>
      <td>249.0</td>
      <td>299.0</td>
      <td>448.0</td>
    </tr>
    <tr>
      <th>1</th>
      <td>85.863355</td>
      <td>0.0</td>
      <td>99.0</td>
      <td>149.0</td>
      <td>158.0</td>
    </tr>
    <tr>
      <th>2</th>
      <td>85.978354</td>
      <td>0.0</td>
      <td>99.0</td>
      <td>149.0</td>
      <td>158.0</td>
    </tr>
    <tr>
      <th>3</th>
      <td>124.963794</td>
      <td>0.0</td>
      <td>149.0</td>
      <td>199.0</td>
      <td>227.0</td>
    </tr>
    <tr>
      <th>4</th>
      <td>233.428571</td>
      <td>0.0</td>
      <td>294.5</td>
      <td>299.0</td>
      <td>455.1</td>
    </tr>
    <tr>
      <th>5</th>
      <td>89.691905</td>
      <td>0.0</td>
      <td>99.0</td>
      <td>149.0</td>
      <td>178.0</td>
    </tr>
    <tr>
      <th>6</th>
      <td>97.879202</td>
      <td>0.0</td>
      <td>99.0</td>
      <td>149.0</td>
      <td>160.0</td>
    </tr>
    <tr>
      <th>7</th>
      <td>320.700000</td>
      <td>268.3</td>
      <td>290.0</td>
      <td>299.0</td>
      <td>501.3</td>
    </tr>
  </tbody>
</table>
</div>



### Прибыль по Москве выше, чем по другим городам

## Посмотрим, как показатели меняются со временем




<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th colspan="2" halign="left">total_cost</th>
      <th colspan="2" halign="left">replace_freq</th>
      <th colspan="2" halign="left">cancel_freq</th>
      <th colspan="2" halign="left">is_in_time</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>count</th>
      <th>mean</th>
      <th>count</th>
      <th>mean</th>
      <th>count</th>
      <th>mean</th>
      <th>count</th>
      <th>mean</th>
    </tr>
    <tr>
      <th>retailer_id</th>
      <th>month</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="20" valign="top">1.0</th>
      <th>2018-01</th>
      <td>7959</td>
      <td>189.913431</td>
      <td>7959</td>
      <td>0.016723</td>
      <td>7959</td>
      <td>0.053174</td>
      <td>7959</td>
      <td>0.664028</td>
    </tr>
    <tr>
      <th>2018-02</th>
      <td>7299</td>
      <td>183.153172</td>
      <td>7299</td>
      <td>0.016472</td>
      <td>7299</td>
      <td>0.053449</td>
      <td>7299</td>
      <td>0.723250</td>
    </tr>
    <tr>
      <th>2018-03</th>
      <td>8136</td>
      <td>211.961406</td>
      <td>8136</td>
      <td>0.019177</td>
      <td>8136</td>
      <td>0.054575</td>
      <td>8136</td>
      <td>0.747788</td>
    </tr>
    <tr>
      <th>2018-04</th>
      <td>10088</td>
      <td>213.740979</td>
      <td>10088</td>
      <td>0.028527</td>
      <td>10088</td>
      <td>0.062482</td>
      <td>10088</td>
      <td>0.700634</td>
    </tr>
    <tr>
      <th>2018-05</th>
      <td>13071</td>
      <td>185.166246</td>
      <td>13071</td>
      <td>0.037246</td>
      <td>13071</td>
      <td>0.068616</td>
      <td>13071</td>
      <td>0.691684</td>
    </tr>
    <tr>
      <th>2018-06</th>
      <td>11675</td>
      <td>224.008651</td>
      <td>11675</td>
      <td>0.039128</td>
      <td>11675</td>
      <td>0.063790</td>
      <td>11675</td>
      <td>0.674004</td>
    </tr>
    <tr>
      <th>2018-07</th>
      <td>11666</td>
      <td>238.239585</td>
      <td>11666</td>
      <td>0.040953</td>
      <td>11666</td>
      <td>0.065713</td>
      <td>11666</td>
      <td>0.731442</td>
    </tr>
    <tr>
      <th>2018-08</th>
      <td>11707</td>
      <td>221.657935</td>
      <td>11707</td>
      <td>0.059928</td>
      <td>11707</td>
      <td>0.096052</td>
      <td>11707</td>
      <td>0.743999</td>
    </tr>
    <tr>
      <th>2018-09</th>
      <td>15905</td>
      <td>195.752133</td>
      <td>15905</td>
      <td>0.044654</td>
      <td>15905</td>
      <td>0.067272</td>
      <td>15905</td>
      <td>0.736624</td>
    </tr>
    <tr>
      <th>2018-10</th>
      <td>18513</td>
      <td>196.738277</td>
      <td>18513</td>
      <td>0.042730</td>
      <td>18513</td>
      <td>0.063138</td>
      <td>18513</td>
      <td>0.761789</td>
    </tr>
    <tr>
      <th>2018-11</th>
      <td>18584</td>
      <td>197.361268</td>
      <td>18584</td>
      <td>0.028238</td>
      <td>18584</td>
      <td>0.050282</td>
      <td>18584</td>
      <td>0.772277</td>
    </tr>
    <tr>
      <th>2018-12</th>
      <td>16181</td>
      <td>191.384338</td>
      <td>16181</td>
      <td>0.028780</td>
      <td>16181</td>
      <td>0.052818</td>
      <td>16181</td>
      <td>0.731908</td>
    </tr>
    <tr>
      <th>2019-01</th>
      <td>18250</td>
      <td>194.434621</td>
      <td>18250</td>
      <td>0.029344</td>
      <td>18250</td>
      <td>0.057084</td>
      <td>18250</td>
      <td>0.723726</td>
    </tr>
    <tr>
      <th>2019-02</th>
      <td>16722</td>
      <td>195.610094</td>
      <td>16722</td>
      <td>0.031023</td>
      <td>16722</td>
      <td>0.053988</td>
      <td>16722</td>
      <td>0.770901</td>
    </tr>
    <tr>
      <th>2019-03</th>
      <td>18038</td>
      <td>200.191252</td>
      <td>18038</td>
      <td>0.030241</td>
      <td>18038</td>
      <td>0.051849</td>
      <td>18038</td>
      <td>0.790165</td>
    </tr>
    <tr>
      <th>2019-04</th>
      <td>22048</td>
      <td>187.473149</td>
      <td>22048</td>
      <td>0.030266</td>
      <td>22048</td>
      <td>0.050508</td>
      <td>22048</td>
      <td>0.749683</td>
    </tr>
    <tr>
      <th>2019-05</th>
      <td>25571</td>
      <td>187.481697</td>
      <td>25571</td>
      <td>0.026407</td>
      <td>25571</td>
      <td>0.041262</td>
      <td>25571</td>
      <td>0.757069</td>
    </tr>
    <tr>
      <th>2019-06</th>
      <td>30210</td>
      <td>171.950215</td>
      <td>30210</td>
      <td>0.024574</td>
      <td>30210</td>
      <td>0.034560</td>
      <td>30210</td>
      <td>0.774379</td>
    </tr>
    <tr>
      <th>2019-07</th>
      <td>37786</td>
      <td>149.169745</td>
      <td>37786</td>
      <td>0.021172</td>
      <td>37786</td>
      <td>0.028109</td>
      <td>37786</td>
      <td>0.763007</td>
    </tr>
    <tr>
      <th>2019-08</th>
      <td>3989</td>
      <td>128.240035</td>
      <td>3989</td>
      <td>0.029392</td>
      <td>3989</td>
      <td>0.043029</td>
      <td>3989</td>
      <td>0.695914</td>
    </tr>
    <tr>
      <th rowspan="13" valign="top">8.0</th>
      <th>2018-01</th>
      <td>76</td>
      <td>149.723684</td>
      <td>76</td>
      <td>0.077788</td>
      <td>76</td>
      <td>0.066452</td>
      <td>76</td>
      <td>0.684211</td>
    </tr>
    <tr>
      <th>2018-02</th>
      <td>73</td>
      <td>140.369863</td>
      <td>73</td>
      <td>0.062478</td>
      <td>73</td>
      <td>0.072587</td>
      <td>73</td>
      <td>0.726027</td>
    </tr>
    <tr>
      <th>2018-03</th>
      <td>128</td>
      <td>190.039062</td>
      <td>128</td>
      <td>0.045575</td>
      <td>128</td>
      <td>0.084876</td>
      <td>128</td>
      <td>0.703125</td>
    </tr>
    <tr>
      <th>2018-04</th>
      <td>125</td>
      <td>197.976000</td>
      <td>125</td>
      <td>0.056599</td>
      <td>125</td>
      <td>0.141310</td>
      <td>125</td>
      <td>0.440000</td>
    </tr>
    <tr>
      <th>2018-05</th>
      <td>166</td>
      <td>134.740964</td>
      <td>166</td>
      <td>0.051156</td>
      <td>166</td>
      <td>0.151474</td>
      <td>166</td>
      <td>0.427711</td>
    </tr>
    <tr>
      <th>2018-06</th>
      <td>235</td>
      <td>212.961702</td>
      <td>235</td>
      <td>0.029239</td>
      <td>235</td>
      <td>0.152146</td>
      <td>235</td>
      <td>0.476596</td>
    </tr>
    <tr>
      <th>2018-07</th>
      <td>121</td>
      <td>210.206612</td>
      <td>121</td>
      <td>0.034977</td>
      <td>121</td>
      <td>0.119371</td>
      <td>121</td>
      <td>0.694215</td>
    </tr>
    <tr>
      <th>2018-08</th>
      <td>83</td>
      <td>191.939759</td>
      <td>83</td>
      <td>0.103457</td>
      <td>83</td>
      <td>0.124483</td>
      <td>83</td>
      <td>0.084337</td>
    </tr>
    <tr>
      <th>2018-09</th>
      <td>94</td>
      <td>175.893617</td>
      <td>94</td>
      <td>0.082641</td>
      <td>94</td>
      <td>0.126642</td>
      <td>94</td>
      <td>0.117021</td>
    </tr>
    <tr>
      <th>2018-10</th>
      <td>93</td>
      <td>218.032258</td>
      <td>93</td>
      <td>0.071565</td>
      <td>93</td>
      <td>0.151686</td>
      <td>93</td>
      <td>0.215054</td>
    </tr>
    <tr>
      <th>2018-11</th>
      <td>61</td>
      <td>235.114754</td>
      <td>61</td>
      <td>0.101950</td>
      <td>61</td>
      <td>0.105480</td>
      <td>61</td>
      <td>0.688525</td>
    </tr>
    <tr>
      <th>2018-12</th>
      <td>148</td>
      <td>147.743243</td>
      <td>148</td>
      <td>0.123252</td>
      <td>148</td>
      <td>0.103306</td>
      <td>148</td>
      <td>0.554054</td>
    </tr>
    <tr>
      <th>2019-01</th>
      <td>33</td>
      <td>192.515152</td>
      <td>33</td>
      <td>0.080614</td>
      <td>33</td>
      <td>0.077755</td>
      <td>33</td>
      <td>0.575758</td>
    </tr>
    <tr>
      <th rowspan="16" valign="top">15.0</th>
      <th>2018-05</th>
      <td>37</td>
      <td>244.756757</td>
      <td>37</td>
      <td>0.081054</td>
      <td>37</td>
      <td>0.156123</td>
      <td>37</td>
      <td>0.567568</td>
    </tr>
    <tr>
      <th>2018-06</th>
      <td>526</td>
      <td>227.342205</td>
      <td>526</td>
      <td>0.057812</td>
      <td>526</td>
      <td>0.102467</td>
      <td>526</td>
      <td>0.788973</td>
    </tr>
    <tr>
      <th>2018-07</th>
      <td>569</td>
      <td>219.942004</td>
      <td>569</td>
      <td>0.050793</td>
      <td>569</td>
      <td>0.079388</td>
      <td>569</td>
      <td>0.804921</td>
    </tr>
    <tr>
      <th>2018-08</th>
      <td>635</td>
      <td>216.618898</td>
      <td>635</td>
      <td>0.062022</td>
      <td>635</td>
      <td>0.106850</td>
      <td>635</td>
      <td>0.781102</td>
    </tr>
    <tr>
      <th>2018-09</th>
      <td>660</td>
      <td>183.313636</td>
      <td>660</td>
      <td>0.052452</td>
      <td>660</td>
      <td>0.145039</td>
      <td>660</td>
      <td>0.786364</td>
    </tr>
    <tr>
      <th>2018-10</th>
      <td>759</td>
      <td>189.096179</td>
      <td>759</td>
      <td>0.045098</td>
      <td>759</td>
      <td>0.116955</td>
      <td>759</td>
      <td>0.816864</td>
    </tr>
    <tr>
      <th>2018-11</th>
      <td>723</td>
      <td>168.381743</td>
      <td>723</td>
      <td>0.051260</td>
      <td>723</td>
      <td>0.082472</td>
      <td>723</td>
      <td>0.822960</td>
    </tr>
    <tr>
      <th>2018-12</th>
      <td>488</td>
      <td>183.327869</td>
      <td>488</td>
      <td>0.049786</td>
      <td>488</td>
      <td>0.061864</td>
      <td>488</td>
      <td>0.727459</td>
    </tr>
    <tr>
      <th>2019-01</th>
      <td>403</td>
      <td>229.369727</td>
      <td>403</td>
      <td>0.042873</td>
      <td>403</td>
      <td>0.070118</td>
      <td>403</td>
      <td>0.761787</td>
    </tr>
    <tr>
      <th>2019-02</th>
      <td>309</td>
      <td>232.611650</td>
      <td>309</td>
      <td>0.052024</td>
      <td>309</td>
      <td>0.066493</td>
      <td>309</td>
      <td>0.796117</td>
    </tr>
    <tr>
      <th>2019-03</th>
      <td>301</td>
      <td>216.800664</td>
      <td>301</td>
      <td>0.052464</td>
      <td>301</td>
      <td>0.079353</td>
      <td>301</td>
      <td>0.754153</td>
    </tr>
    <tr>
      <th>2019-04</th>
      <td>370</td>
      <td>208.037838</td>
      <td>370</td>
      <td>0.059668</td>
      <td>370</td>
      <td>0.085644</td>
      <td>370</td>
      <td>0.810811</td>
    </tr>
    <tr>
      <th>2019-05</th>
      <td>386</td>
      <td>200.448187</td>
      <td>386</td>
      <td>0.058863</td>
      <td>386</td>
      <td>0.060976</td>
      <td>386</td>
      <td>0.676166</td>
    </tr>
    <tr>
      <th>2019-06</th>
      <td>560</td>
      <td>33.944643</td>
      <td>560</td>
      <td>0.044346</td>
      <td>560</td>
      <td>0.046497</td>
      <td>560</td>
      <td>0.739286</td>
    </tr>
    <tr>
      <th>2019-07</th>
      <td>741</td>
      <td>0.000000</td>
      <td>741</td>
      <td>0.045294</td>
      <td>741</td>
      <td>0.045995</td>
      <td>741</td>
      <td>0.762483</td>
    </tr>
    <tr>
      <th>2019-08</th>
      <td>107</td>
      <td>0.000000</td>
      <td>107</td>
      <td>0.043580</td>
      <td>107</td>
      <td>0.050550</td>
      <td>107</td>
      <td>0.738318</td>
    </tr>
    <tr>
      <th rowspan="5" valign="top">16.0</th>
      <th>2019-04</th>
      <td>9</td>
      <td>219.222222</td>
      <td>9</td>
      <td>0.164900</td>
      <td>9</td>
      <td>0.145574</td>
      <td>9</td>
      <td>1.000000</td>
    </tr>
    <tr>
      <th>2019-05</th>
      <td>65</td>
      <td>210.353846</td>
      <td>65</td>
      <td>0.049681</td>
      <td>65</td>
      <td>0.043175</td>
      <td>65</td>
      <td>0.753846</td>
    </tr>
    <tr>
      <th>2019-06</th>
      <td>48</td>
      <td>115.291667</td>
      <td>48</td>
      <td>0.063031</td>
      <td>48</td>
      <td>0.032802</td>
      <td>48</td>
      <td>0.541667</td>
    </tr>
    <tr>
      <th>2019-07</th>
      <td>60</td>
      <td>138.366667</td>
      <td>60</td>
      <td>0.047217</td>
      <td>60</td>
      <td>0.046870</td>
      <td>60</td>
      <td>0.466667</td>
    </tr>
    <tr>
      <th>2019-08</th>
      <td>10</td>
      <td>152.000000</td>
      <td>10</td>
      <td>0.086640</td>
      <td>10</td>
      <td>0.040278</td>
      <td>10</td>
      <td>0.200000</td>
    </tr>
  </tbody>
</table>
</div>



### не сильно меняются

## Посмотрим, как клиенты используют промокоды

### Процент клиентов, использующих промокоды от времени





    month
    2018-01    0.000489
    2018-02    0.001060
    2018-03    0.001400
    2018-04    0.002835
    2018-05    0.003416
    2018-06    0.007314
    2018-07    0.039738
    2018-08    0.047485
    2018-09    0.050003
    2018-10    0.135657
    2018-11    0.401900
    2018-12    0.364869
    2019-01    0.273948
    2019-02    0.234925
    2019-03    0.217242
    2019-04    0.453382
    2019-05    0.437899
    2019-06    0.534168
    2019-07    0.690854
    2019-08    0.714564
    Name: is_promo, dtype: float64



### Как часто пользуются промокодами новые и постоянные клиенты?



### Какая доля постоянных клиентов пользовалась промокодом при первом заказе?





    0.3333048164941398



###  Какая доля клиентов, которые больше не заказывали, пользовалась промоколом при своем единственном заказе?





    0.4302516829865361



### Процент заказов, сделанных непостоянными клиентами





    0.2261142494674103



## Посмотрим на распределение времени доставки и размера заказа по дням недели

### дни недели заказа:






<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th colspan="2" halign="left">total_quantity</th>
      <th colspan="2" halign="left">total_cost</th>
      <th colspan="2" halign="left">is_in_time</th>
    </tr>
    <tr>
      <th></th>
      <th>mean</th>
      <th>count</th>
      <th>mean</th>
      <th>count</th>
      <th>mean</th>
      <th>count</th>
    </tr>
    <tr>
      <th>day_of_week</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>46.590113</td>
      <td>46747</td>
      <td>195.306775</td>
      <td>46747</td>
      <td>0.751877</td>
      <td>46747</td>
    </tr>
    <tr>
      <th>1</th>
      <td>46.718581</td>
      <td>46532</td>
      <td>185.775556</td>
      <td>46532</td>
      <td>0.738288</td>
      <td>46532</td>
    </tr>
    <tr>
      <th>2</th>
      <td>44.229718</td>
      <td>45791</td>
      <td>189.442074</td>
      <td>45791</td>
      <td>0.739163</td>
      <td>45791</td>
    </tr>
    <tr>
      <th>3</th>
      <td>45.240063</td>
      <td>49941</td>
      <td>190.144007</td>
      <td>49941</td>
      <td>0.740994</td>
      <td>49941</td>
    </tr>
    <tr>
      <th>4</th>
      <td>45.219906</td>
      <td>51563</td>
      <td>190.818901</td>
      <td>51563</td>
      <td>0.740415</td>
      <td>51563</td>
    </tr>
    <tr>
      <th>5</th>
      <td>40.766651</td>
      <td>48991</td>
      <td>185.160608</td>
      <td>48991</td>
      <td>0.749730</td>
      <td>48991</td>
    </tr>
    <tr>
      <th>6</th>
      <td>40.442745</td>
      <td>44651</td>
      <td>186.734564</td>
      <td>44651</td>
      <td>0.749546</td>
      <td>44651</td>
    </tr>
  </tbody>
</table>
</div>



### дни недели доставки:






<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th colspan="2" halign="left">total_quantity</th>
      <th colspan="2" halign="left">total_cost</th>
      <th colspan="2" halign="left">is_in_time</th>
    </tr>
    <tr>
      <th></th>
      <th>mean</th>
      <th>count</th>
      <th>mean</th>
      <th>count</th>
      <th>mean</th>
      <th>count</th>
    </tr>
    <tr>
      <th>day_of_week_shipped</th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th>0</th>
      <td>46.680609</td>
      <td>46861</td>
      <td>194.772511</td>
      <td>46861</td>
      <td>0.754849</td>
      <td>46861</td>
    </tr>
    <tr>
      <th>1</th>
      <td>45.328850</td>
      <td>46617</td>
      <td>191.257993</td>
      <td>46617</td>
      <td>0.747538</td>
      <td>46617</td>
    </tr>
    <tr>
      <th>2</th>
      <td>46.379258</td>
      <td>45800</td>
      <td>188.953577</td>
      <td>45800</td>
      <td>0.741550</td>
      <td>45800</td>
    </tr>
    <tr>
      <th>3</th>
      <td>44.354244</td>
      <td>45813</td>
      <td>186.923536</td>
      <td>45813</td>
      <td>0.738524</td>
      <td>45813</td>
    </tr>
    <tr>
      <th>4</th>
      <td>45.292255</td>
      <td>49361</td>
      <td>189.717997</td>
      <td>49361</td>
      <td>0.735621</td>
      <td>49361</td>
    </tr>
    <tr>
      <th>5</th>
      <td>41.631864</td>
      <td>50101</td>
      <td>187.678048</td>
      <td>50101</td>
      <td>0.742520</td>
      <td>50101</td>
    </tr>
    <tr>
      <th>6</th>
      <td>40.129694</td>
      <td>49663</td>
      <td>184.549523</td>
      <td>49663</td>
      <td>0.749069</td>
      <td>49663</td>
    </tr>
  </tbody>
</table>
</div>



### По выходным заказов больше, но они меньше. Но на то, доставляются ли они вовремя, день недели не влияет

## Рассмотрим заказы клиентов различных классов





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th colspan="2" halign="left">is_in_time</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>mean</th>
      <th>count</th>
    </tr>
    <tr>
      <th>user_class</th>
      <th>day_of_week_shipped</th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="7" valign="top">high</th>
      <th>0</th>
      <td>0.749773</td>
      <td>9923</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0.745360</td>
      <td>9967</td>
    </tr>
    <tr>
      <th>2</th>
      <td>0.728921</td>
      <td>9820</td>
    </tr>
    <tr>
      <th>3</th>
      <td>0.729045</td>
      <td>9592</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0.721332</td>
      <td>10299</td>
    </tr>
    <tr>
      <th>5</th>
      <td>0.742618</td>
      <td>8738</td>
    </tr>
    <tr>
      <th>6</th>
      <td>0.745886</td>
      <td>8508</td>
    </tr>
    <tr>
      <th rowspan="7" valign="top">low</th>
      <th>0</th>
      <td>0.748485</td>
      <td>9073</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0.737287</td>
      <td>9341</td>
    </tr>
    <tr>
      <th>2</th>
      <td>0.729876</td>
      <td>9603</td>
    </tr>
    <tr>
      <th>3</th>
      <td>0.730331</td>
      <td>9393</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0.729205</td>
      <td>9786</td>
    </tr>
    <tr>
      <th>5</th>
      <td>0.725069</td>
      <td>9737</td>
    </tr>
    <tr>
      <th>6</th>
      <td>0.734613</td>
      <td>9895</td>
    </tr>
    <tr>
      <th rowspan="7" valign="top">middle</th>
      <th>0</th>
      <td>0.758730</td>
      <td>27865</td>
    </tr>
    <tr>
      <th>1</th>
      <td>0.751840</td>
      <td>27309</td>
    </tr>
    <tr>
      <th>2</th>
      <td>0.750502</td>
      <td>26377</td>
    </tr>
    <tr>
      <th>3</th>
      <td>0.744782</td>
      <td>26828</td>
    </tr>
    <tr>
      <th>4</th>
      <td>0.742793</td>
      <td>29276</td>
    </tr>
    <tr>
      <th>5</th>
      <td>0.747866</td>
      <td>31626</td>
    </tr>
    <tr>
      <th>6</th>
      <td>0.754511</td>
      <td>31260</td>
    </tr>
  </tbody>
</table>
</div>



### Клиенты, делающие дорогие заказы, на выходных делают их меньше
### Клиенты, делающие средние по величине заказы, на выходных делают их больше
### Клиенты, делающие дешевые заказы, примерно стабильно ведут себя всю неделю





    user_class
    high      0.262390
    low       0.402331
    middle    0.273999
    Name: is_promo, dtype: float64



### Клиенты, делающие средние заказы, чаще пользуются промокодами





<div>
<style scoped>
    .dataframe tbody tr th:only-of-type {
        vertical-align: middle;
    }

    .dataframe tbody tr th {
        vertical-align: top;
    }

    .dataframe thead tr th {
        text-align: left;
    }

    .dataframe thead tr:last-of-type th {
        text-align: right;
    }
</style>
<table border="1" class="dataframe">
  <thead>
    <tr>
      <th></th>
      <th></th>
      <th colspan="2" halign="left">is_promo</th>
    </tr>
    <tr>
      <th></th>
      <th></th>
      <th>count</th>
      <th>mean</th>
    </tr>
    <tr>
      <th>user_class</th>
      <th>old_client</th>
      <th></th>
      <th></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th rowspan="2" valign="top">high</th>
      <th>False</th>
      <td>10152</td>
      <td>0.666470</td>
    </tr>
    <tr>
      <th>True</th>
      <td>56695</td>
      <td>0.190034</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">low</th>
      <th>False</th>
      <td>33615</td>
      <td>0.563141</td>
    </tr>
    <tr>
      <th>True</th>
      <td>33213</td>
      <td>0.239575</td>
    </tr>
    <tr>
      <th rowspan="2" valign="top">middle</th>
      <th>False</th>
      <td>31804</td>
      <td>0.612502</td>
    </tr>
    <tr>
      <th>True</th>
      <td>168737</td>
      <td>0.210197</td>
    </tr>
  </tbody>
</table>
</div>



### Среди клиентов, делающих средние и дорогие заказы, больше постоянных

# Конечно, можно было посмотреть на большее количество распределений и обосновать все более строго.
