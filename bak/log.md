# 20230219 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24124
self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24647.6, self.close=24646.7, self.high=24650.0, self.low=24639.5, self.vol=267.272, self.amt=6586816.93 
2023-02-19 08:20:01,569:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230219   075500    075959  ...         0.0        0.0       0
5856  20230219   080000    080459  ...         0.0        0.0       0
5857  20230219   080500    080959  ...         0.0        0.0       0
5858  20230219   081000    081459  ...         0.0        0.0       0
5859  20230219   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 08:20:01,584:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24647.6, self.close=24646.7, self.high=24650.0, self.low=24639.5, self.vol=267.272, self.amt=6586816.93, ukdf['pct'].iloc[-1]=-3.7e-05 , ukdf['amount'].iloc[-1]=6586816.93, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-488464.14682022352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24646.55848877', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24125
self.closeSec=1676766299, self.tradeDate='20230219', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24646.7, self.close=24687.2, self.high=24700.0, self.low=24646.7, self.vol=1196.183, self.amt=29521977.7334 
127.0.0.1 - - [19/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-19 08:25:01,542:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230219   080000    080459  ...         0.0        0.0       0
5857  20230219   080500    080959  ...         0.0        0.0       0
5858  20230219   081000    081459  ...         0.0        0.0       0
5859  20230219   081500    081959  ...         0.0        0.0       0
5860  20230219   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 08:25:01,543:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676766299, self.tradeDate='20230219', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24646.7, self.close=24687.2, self.high=24700.0, self.low=24646.7, self.vol=1196.183, self.amt=29521977.7334, ukdf['pct'].iloc[-1]=0.001643 , ukdf['amount'].iloc[-1]=29521977.7334, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-490848.8332523352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24686.18701895', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24647.6, self.close=24646.7, self.high=24650.0, self.low=24639.5 
127.0.0.1 - - [19/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 08:20:01,518:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24647.6, self.close=24646.7, self.high=24650.0, self.low=24639.5   
2023-02-19 08:20:01,571:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230219   075500    075959  1676764799  ...  24636.7 -0.000556   1535    5
1536  20230219   080000    080459  1676765099  ...  24626.5  0.000166   1536    0
1537  20230219   080500    080959  1676765399  ...  24636.4  0.000069   1537    1
1538  20230219   081000    081459  1676765699  ...  24642.6  0.000199   1538    2
1539  20230219   081500    081959  1676765999  ...  24639.5 -0.000037   1539    3

[5 rows x 11 columns]
2023-02-19 08:20:01,573:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=199, self.factor=0.4177794963596439, self.count=24691 

self.closeSec=1676766299, self.tradeDate='20230219', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24646.7, self.close=24687.2, self.high=24700.0, self.low=24646.7 
2023-02-19 08:25:01,489:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676766299, self.tradeDate='20230219', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24646.7, self.close=24687.2, self.high=24700.0, self.low=24646.7   
2023-02-19 08:25:01,567:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230219   080000    080459  1676765099  ...  24626.5  0.000166   1536    0
1537  20230219   080500    080959  1676765399  ...  24636.4  0.000069   1537    1
1538  20230219   081000    081459  1676765699  ...  24642.6  0.000199   1538    2
1539  20230219   081500    081959  1676765999  ...  24639.5 -0.000037   1539    3
1540  20230219   082000    082459  1676766299  ...  24646.7  0.001643   1540    4

[5 rows x 11 columns]
2023-02-19 08:25:01,567:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-19 08:00:34,523:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230219    052959  24597.5  ...  52.083333  0.547906  0.400149
5771  20230219    055959  24638.7  ...  52.083333  0.544736  0.412256
5772  20230219    062959  24621.7  ...  52.500000  0.552032  0.416712
5773  20230219    065959  24668.7  ...  52.083333  0.544794  0.426430
5774  20230219    072959  24630.4  ...  52.083333  0.546292  0.434129

[5 rows x 33 columns]
0.5083179297597042
acc is : 0.5083179297597042
2023-02-19 08:00:34,691:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498347  0.501653       0  ...  1.102671   1.0    0.0  1.075493
537     1  0.491143  0.508857       1  ...  1.104772   1.0    0.0  1.077542
538     0  0.512573  0.487427       0  ...  1.103066   1.0    0.0  1.075878
539     1  0.496284  0.503716       1  ...  1.103486   1.0    0.0  1.076288
540     0  0.509702  0.490298       0  ...  1.103352   1.0    0.0  1.076157

[5 rows x 10 columns]
2023-02-19 08:00:34,701:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497902  0.502098       0  ...  1.102671   1.0    0.0  1.075240
46     1  0.491191  0.508809       1  ...  1.104772   1.0    0.0  1.075775
47     0  0.512050  0.487950       0  ...  1.103066   1.0    0.0  1.072243
48     1  0.497270  0.502730       1  ...  1.068316   1.0    0.0  1.076288
49     0  0.509702  0.490298       0  ...  1.103352   1.0    0.0  1.076157

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.459', 'enterprice': '24163.6', 'countrevence': '0', 'unrealprofit': '16447.66826355978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24627.45031342', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230219   075000    075959  1676764799  24629.9  24636.9  0.000280
2023-02-19 08:00:02,321:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12344 

self.closeSec=1676765399, self.tradeDate='20230219', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24636.8', self.close='24642.7'
2023-02-19 08:10:01,610:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676765399, self.tradeDate='20230219', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24636.8', self.close='24642.7'
2023-02-19 08:10:01,684:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230219   072000    072959  1676762999  24643.3  24639.9 -0.000138
621  20230219   073000    073959  1676763599    24640  24638.4 -0.000061
622  20230219   074000    074959  1676764199  24638.5    24630 -0.000341
623  20230219   075000    075959  1676764799  24629.9  24636.9  0.000280
624  20230219   080000    080959  1676765399  24636.8  24642.7  0.000235
2023-02-19 08:10:01,684:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12345 

self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24642.7', self.close='24646.7'
2023-02-19 08:20:01,600:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24642.7', self.close='24646.7'
127.0.0.1 - - [19/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 08:20:01,646:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230219   073000    073959  1676763599    24640  24638.4 -0.000061
622  20230219   074000    074959  1676764199  24638.5    24630 -0.000341
623  20230219   075000    075959  1676764799  24629.9  24636.9  0.000280
624  20230219   080000    080959  1676765399  24636.8  24642.7  0.000235
625  20230219   081000    081959  1676765999  24642.7  24646.7  0.000162
2023-02-19 08:20:01,646:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 07:00:01] "POST / HTTP/1.1" 200 -
2023-02-19 07:00:03,103:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 04:30:00  043000  24597.5  ...     NaN     NaN       0
145  2023/02/19 05:00:00  050000  24638.7  ...     NaN     NaN       0
146  2023/02/19 05:30:00  053000  24621.7  ...     NaN     NaN       0
147  2023/02/19 06:00:00  060000  24668.6  ...     NaN     NaN       0
148  2023/02/19 06:30:00  063000  24630.5  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [19/Feb/2023 07:30:01] "POST / HTTP/1.1" 200 -
2023-02-19 07:30:02,835:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 05:00:00  050000  24638.7  ...     NaN     NaN       0
145  2023/02/19 05:30:00  053000  24621.7  ...     NaN     NaN       0
146  2023/02/19 06:00:00  060000  24668.6  ...     NaN     NaN       0
147  2023/02/19 06:30:00  063000  24630.5  ...     NaN     NaN       0
148  2023/02/19 07:00:00  070000  24639.9  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [19/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-19 08:00:03,403:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/19 05:30:00  053000  24621.7  ...     NaN     NaN       0
145  2023/02/19 06:00:00  060000  24668.6  ...     NaN     NaN       0
146  2023/02/19 06:30:00  063000  24630.5  ...     NaN     NaN       0
147  2023/02/19 07:00:00  070000  24639.9  ...     NaN     NaN       0
148  2023/02/19 07:30:00  073000  24636.9  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230219   075000    075959  1676764799  24629.9  24636.9
2023-02-19 08:00:02,384:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12345 

self.closeSec=1676765399, self.tradeDate='20230219', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24636.8', self.close='24642.7'
2023-02-19 08:10:01,638:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676765399, self.tradeDate='20230219', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24636.8', self.close='24642.7'
2023-02-19 08:10:01,697:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230219   072000    072959  1676762999  24643.3  24639.9
17469  20230219   073000    073959  1676763599    24640  24638.4
17470  20230219   074000    074959  1676764199  24638.5    24630
17471  20230219   075000    075959  1676764799  24629.9  24636.9
17472  20230219   080000    080959  1676765399  24636.8  24642.7
2023-02-19 08:10:01,697:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12346 

self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24642.7', self.close='24646.7'
2023-02-19 08:20:01,622:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24642.7', self.close='24646.7'
2023-02-19 08:20:01,659:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230219   073000    073959  1676763599    24640  24638.4
17470  20230219   074000    074959  1676764199  24638.5    24630
17471  20230219   075000    075959  1676764799  24629.9  24636.9
17472  20230219   080000    080959  1676765399  24636.8  24642.7
17473  20230219   081000    081959  1676765999  24642.7  24646.7
2023-02-19 08:20:01,659:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230219   075000    075959  1676764799  24629.9  24636.9
2023-02-19 08:00:02,398:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12345 

self.closeSec=1676765399, self.tradeDate='20230219', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24636.8', self.close='24642.7'
2023-02-19 08:10:01,637:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676765399, self.tradeDate='20230219', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24636.8', self.close='24642.7'
2023-02-19 08:10:01,687:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230219   072000    072959  1676762999  24643.3  24639.9
12141  20230219   073000    073959  1676763599    24640  24638.4
12142  20230219   074000    074959  1676764199  24638.5    24630
12143  20230219   075000    075959  1676764799  24629.9  24636.9
12144  20230219   080000    080959  1676765399  24636.8  24642.7
2023-02-19 08:10:01,692:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12346 

self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24642.7', self.close='24646.7'
2023-02-19 08:20:01,615:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24642.7', self.close='24646.7'
127.0.0.1 - - [19/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 08:20:01,655:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230219   073000    073959  1676763599    24640  24638.4
12142  20230219   074000    074959  1676764199  24638.5    24630
12143  20230219   075000    075959  1676764799  24629.9  24636.9
12144  20230219   080000    080959  1676765399  24636.8  24642.7
12145  20230219   081000    081959  1676765999  24642.7  24646.7
2023-02-19 08:20:01,655:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20122
self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24647.6, self.close=24646.7, self.high=24650.0, self.low=24639.5, self.vol=267.272, self.amt=6586816.93 
2023-02-19 08:20:01,623:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230219   075500    075959  ...         0.0        0.0       0
5856  20230219   080000    080459  ...         0.0        0.0       0
5857  20230219   080500    080959  ...         0.0        0.0       0
5858  20230219   081000    081459  ...         0.0        0.0       0
5859  20230219   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 08:20:01,623:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676765999, self.tradeDate='20230219', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24647.6, self.close=24646.7, self.high=24650.0, self.low=24639.5, self.vol=267.272, self.amt=6586816.93, ukdf['pct'].iloc[-1]=-3.7e-05 , ukdf['amount'].iloc[-1]=6586816.93, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20123
self.closeSec=1676766299, self.tradeDate='20230219', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24646.7, self.close=24687.2, self.high=24700.0, self.low=24646.7, self.vol=1196.183, self.amt=29521977.7334 
2023-02-19 08:25:01,611:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230219   080000    080459  ...         0.0        0.0       0
5857  20230219   080500    080959  ...         0.0        0.0       0
5858  20230219   081000    081459  ...         0.0        0.0       0
5859  20230219   081500    081959  ...         0.0        0.0       0
5860  20230219   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 08:25:01,612:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676766299, self.tradeDate='20230219', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24646.7, self.close=24687.2, self.high=24700.0, self.low=24646.7, self.vol=1196.183, self.amt=29521977.7334, ukdf['pct'].iloc[-1]=0.001643 , ukdf['amount'].iloc[-1]=29521977.7334, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230218   200000    235959  1676735999  ...    719  0.941629  0.757507     1.0
720  20230219   000000    035959  1676750399  ...    720  0.985311  0.869136     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '47228.7294', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24611.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=514
self.closeSec=1676764799, self.tradeDate='20230219', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24610.0, self.close=24636.9, self.high=24673.4, self.low=24516.7, self.vol=22736.718, self.amt=559563643.5706 
127.0.0.1 - - [19/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-02-19 08:00:02,057:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676764799, self.tradeDate='20230219', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24610.0, self.close=24636.9, self.high=24673.4, self.low=24516.7, self.vol=22736.718, self.amt=559563643.5706 
2023-02-19 08:00:02,117:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230218   120000    155959  ...  34345.925  8.447181e+08 -0.003944
718  20230218   160000    195959  ...  36886.129  9.047125e+08  0.000114
719  20230218   200000    235959  ...  55533.683  1.368031e+09  0.005888
720  20230219   000000    035959  ...  61293.542  1.514293e+09 -0.002428
721  20230219   040000    075959  ...  22736.718  5.595636e+08  0.001089

[5 rows x 11 columns]
2023-02-19 08:00:04,736:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230218   120000    155959  1676707199  ...    717  1.082603  1.179174     1.0
718  20230218   160000    195959  1676721599  ...    718  1.004289  0.942814     1.0
719  20230218   200000    235959  1676735999  ...    719  0.941629  0.757507     1.0
720  20230219   000000    035959  1676750399  ...    720  0.985311  0.869136     1.0
721  20230219   040000    075959  1676764799  ...    721  0.922795  0.690896     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '48156.2866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24636.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


