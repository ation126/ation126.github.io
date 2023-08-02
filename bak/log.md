# 20230802 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23008
self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29701.1, self.close=29691.0, self.high=29726.7, self.low=29678.2, self.vol=4049.318, self.amt=120255009.6048 
127.0.0.1 - - [02/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 08:20:06,509:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230802   075500    075959  ...         0.0        0.0       0
5856  20230802   080000    080459  ...         0.0        0.0       0
5857  20230802   080500    080959  ...         0.0        0.0       0
5858  20230802   081000    081459  ...         0.0        0.0       0
5859  20230802   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 08:20:06,529:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29701.1, self.close=29691.0, self.high=29726.7, self.low=29678.2, self.vol=4049.318, self.amt=120255009.6048, ukdf['pct'].iloc[-1]=-0.00034 , ukdf['amount'].iloc[-1]=120255009.6048, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-39466.30402182798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29698.90143773', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23009
self.closeSec=1690935899, self.tradeDate='20230802', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29691.0, self.close=29724.9, self.high=29753.2, self.low=29688.3, self.vol=2860.744, self.amt=85007968.4314 
127.0.0.1 - - [02/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-02 08:25:00,755:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230802   080000    080459  ...         0.0        0.0       0
5857  20230802   080500    080959  ...         0.0        0.0       0
5858  20230802   081000    081459  ...         0.0        0.0       0
5859  20230802   081500    081959  ...         0.0        0.0       0
5860  20230802   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 08:25:00,755:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690935899, self.tradeDate='20230802', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29691.0, self.close=29724.9, self.high=29753.2, self.low=29688.3, self.vol=2860.744, self.amt=85007968.4314, ukdf['pct'].iloc[-1]=0.001142 , ukdf['amount'].iloc[-1]=85007968.4314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-39826.9674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29724.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29701.1, self.close=29691.0, self.high=29726.7, self.low=29678.2 
127.0.0.1 - - [02/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 08:20:04,508:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29701.1, self.close=29691.0, self.high=29726.7, self.low=29678.2   
2023-08-02 08:20:05,759:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230802   075500    075959  1690934399  ...  29628.8  0.001622   1535    5
1536  20230802   080000    080459  1690934699  ...  29673.6  0.001950   1536    0
1537  20230802   080500    080959  1690934999  ...  29747.6  0.001257   1537    1
1538  20230802   081000    081459  1690935299  ...  29701.0 -0.003128   1538    2
1539  20230802   081500    081959  1690935599  ...  29678.2 -0.000340   1539    3

[5 rows x 11 columns]
2023-08-02 08:20:05,769:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.5298949315163329, self.count=23011 

self.closeSec=1690935899, self.tradeDate='20230802', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29691.0, self.close=29724.9, self.high=29753.2, self.low=29688.3 
2023-08-02 08:25:00,729:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690935899, self.tradeDate='20230802', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29691.0, self.close=29724.9, self.high=29753.2, self.low=29688.3   
2023-08-02 08:25:00,758:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230802   080000    080459  1690934699  ...  29673.6  0.001950   1536    0
1537  20230802   080500    080959  1690934999  ...  29747.6  0.001257   1537    1
1538  20230802   081000    081459  1690935299  ...  29701.0 -0.003128   1538    2
1539  20230802   081500    081959  1690935599  ...  29678.2 -0.000340   1539    3
1540  20230802   082000    082459  1690935899  ...  29688.3  0.001142   1540    4

[5 rows x 11 columns]
2023-08-02 08:25:00,758:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-02 08:00:15,816:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230802    052959  29221.2  ...  45.833333  0.536119  0.460198
5771  20230802    055959  29254.9  ...  45.416667  0.530561  0.437638
5772  20230802    062959  29235.1  ...  45.000000  0.523574  0.418727
5773  20230802    065959  29209.8  ...  45.416667  0.531845  0.398257
5774  20230802    072959  29242.9  ...  45.833333  0.570338  0.376338

[5 rows x 33 columns]
0.5637707948243993
acc is : 0.5637707948243993
2023-08-02 08:00:15,873:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.505620  0.494380       0  ...  0.917693   1.0    0.0  0.978374
537     1  0.494906  0.505094       0  ...  0.916905   1.0    0.0  0.977534
538     1  0.488085  0.511915       1  ...  0.917941   1.0    0.0  0.978639
539     0  0.511529  0.488471       1  ...  0.923180   1.0    0.0  0.984224
540     0  0.556027  0.443973       1  ...  0.932327   1.0    0.0  0.993976

[5 rows x 10 columns]
2023-08-02 08:00:15,884:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505350  0.494650       0  ...  0.956344   1.0    0.0  0.979331
46     1  0.494870  0.505130       0  ...  0.916905   1.0    0.0  0.979488
47     1  0.488199  0.511801       1  ...  0.917941   1.0    0.0  0.980920
48     0  0.511529  0.488471       1  ...  0.923180   1.0    0.0  0.984224
49     0  0.556027  0.443973       1  ...  0.932327   1.0    0.0  0.993976

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.268', 'enterprice': '29229.9', 'countrevence': '0', 'unrealprofit': '11482.758', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29723.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230802   075000    075959  1690934399  29458.2  29701.2  0.008246
2023-08-02 08:00:02,130:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11504 

self.closeSec=1690934999, self.tradeDate='20230802', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29701.2', self.close='29794.3'
2023-08-02 08:10:01,162:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690934999, self.tradeDate='20230802', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29701.2', self.close='29794.3'
2023-08-02 08:10:01,176:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230802   072000    072959  1690932599  29328.3  29407.9  0.002714
621  20230802   073000    073959  1690933199  29407.9  29434.7  0.000911
622  20230802   074000    074959  1690933799  29434.7  29458.3  0.000802
623  20230802   075000    075959  1690934399  29458.2  29701.2  0.008246
624  20230802   080000    080959  1690934999  29701.2  29794.3  0.003135
2023-08-02 08:10:01,176:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11505 

self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29791.2', self.close='29691'
127.0.0.1 - - [02/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 08:20:06,869:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29791.2', self.close='29691'
2023-08-02 08:20:07,308:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230802   073000    073959  1690933199  29407.9  29434.7  0.000911
622  20230802   074000    074959  1690933799  29434.7  29458.3  0.000802
623  20230802   075000    075959  1690934399  29458.2  29701.2  0.008246
624  20230802   080000    080959  1690934999  29701.2  29794.3  0.003135
625  20230802   081000    081959  1690935599  29791.2    29691 -0.003467
2023-08-02 08:20:07,318:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230802   075000    075959  1690934399  29458.2  29701.2
2023-08-02 08:00:02,127:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11507 

self.closeSec=1690934999, self.tradeDate='20230802', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29701.2', self.close='29794.3'
2023-08-02 08:10:01,168:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690934999, self.tradeDate='20230802', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29701.2', self.close='29794.3'
127.0.0.1 - - [02/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-02 08:10:01,178:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230802   072000    072959  1690932599  29328.3  29407.9
17469  20230802   073000    073959  1690933199  29407.9  29434.7
17470  20230802   074000    074959  1690933799  29434.7  29458.3
17471  20230802   075000    075959  1690934399  29458.2  29701.2
17472  20230802   080000    080959  1690934999  29701.2  29794.3
2023-08-02 08:10:01,179:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11508 

self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29791.2', self.close='29691'
127.0.0.1 - - [02/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 08:20:08,460:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29791.2', self.close='29691'
2023-08-02 08:20:08,575:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230802   073000    073959  1690933199  29407.9  29434.7
17470  20230802   074000    074959  1690933799  29434.7  29458.3
17471  20230802   075000    075959  1690934399  29458.2  29701.2
17472  20230802   080000    080959  1690934999  29701.2  29794.3
17473  20230802   081000    081959  1690935599  29791.2    29691
2023-08-02 08:20:08,576:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230802   075000    075959  1690934399  29458.2  29701.2
2023-08-02 08:00:02,127:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11507 

self.closeSec=1690934999, self.tradeDate='20230802', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29701.2', self.close='29794.3'
2023-08-02 08:10:01,164:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690934999, self.tradeDate='20230802', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29701.2', self.close='29794.3'
127.0.0.1 - - [02/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-02 08:10:01,169:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230802   072000    072959  1690932599  29328.3  29407.9
12141  20230802   073000    073959  1690933199  29407.9  29434.7
12142  20230802   074000    074959  1690933799  29434.7  29458.3
12143  20230802   075000    075959  1690934399  29458.2  29701.2
12144  20230802   080000    080959  1690934999  29701.2  29794.3
2023-08-02 08:10:01,170:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11508 

self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29791.2', self.close='29691'
127.0.0.1 - - [02/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 08:20:08,260:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29791.2', self.close='29691'
2023-08-02 08:20:08,470:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230802   073000    073959  1690933199  29407.9  29434.7
12142  20230802   074000    074959  1690933799  29434.7  29458.3
12143  20230802   075000    075959  1690934399  29458.2  29701.2
12144  20230802   080000    080959  1690934999  29701.2  29794.3
12145  20230802   081000    081959  1690935599  29791.2    29691
2023-08-02 08:20:08,471:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23008
self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29701.1, self.close=29691.0, self.high=29726.7, self.low=29678.2, self.vol=4049.318, self.amt=120255009.6048 
127.0.0.1 - - [02/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 08:20:06,508:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230802   075500    075959  ...         0.0        0.0       0
5856  20230802   080000    080459  ...         0.0        0.0       0
5857  20230802   080500    080959  ...         0.0        0.0       0
5858  20230802   081000    081459  ...         0.0        0.0       0
5859  20230802   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 08:20:06,529:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690935599, self.tradeDate='20230802', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29701.1, self.close=29691.0, self.high=29726.7, self.low=29678.2, self.vol=4049.318, self.amt=120255009.6048, ukdf['pct'].iloc[-1]=-0.00034 , ukdf['amount'].iloc[-1]=120255009.6048, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '106033.89429872993', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29698.90143773', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23009
self.closeSec=1690935899, self.tradeDate='20230802', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29691.0, self.close=29724.9, self.high=29753.2, self.low=29688.3, self.vol=2860.744, self.amt=85007968.4314 
2023-08-02 08:25:00,770:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230802   080000    080459  ...         0.0        0.0       0
5857  20230802   080500    080959  ...         0.0        0.0       0
5858  20230802   081000    081459  ...         0.0        0.0       0
5859  20230802   081500    081959  ...         0.0        0.0       0
5860  20230802   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 08:25:00,770:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690935899, self.tradeDate='20230802', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29691.0, self.close=29724.9, self.high=29753.2, self.low=29688.3, self.vol=2860.744, self.amt=85007968.4314, ukdf['pct'].iloc[-1]=0.001142 , ukdf['amount'].iloc[-1]=85007968.4314, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '106995.7928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29724.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230801   200000    235959  1690905599  ...    719  0.160942 -0.470313     NaN
720  20230802   000000    035959  1690919999  ...    720  0.128275 -0.612325    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-1372.2096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29273.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=479
self.closeSec=1690934399, self.tradeDate='20230802', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29263.5, self.close=29701.2, self.high=29735.0, self.low=29170.0, self.vol=97454.977, self.amt=2867118555.21145 
127.0.0.1 - - [02/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-02 08:00:01,675:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690934399, self.tradeDate='20230802', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29263.5, self.close=29701.2, self.high=29735.0, self.low=29170.0, self.vol=97454.977, self.amt=2867118555.21145 
2023-08-02 08:00:01,691:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230801   120000    155959  ...  38804.577  1.120812e+09  0.003511
718  20230801   160000    195959  ...  26312.292  7.608170e+08 -0.002358
719  20230801   200000    235959  ...  92928.505  2.677332e+09  0.003133
720  20230802   000000    035959  ...  98360.420  2.861812e+09  0.011060
721  20230802   040000    075959  ...  97454.977  2.867119e+09  0.014957

[5 rows x 11 columns]
2023-08-02 08:00:02,555:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230801   120000    155959  1690876799  ...    717  0.056256 -0.989586    -1.0
718  20230801   160000    195959  1690891199  ...    718  0.111456 -0.720589    -1.0
719  20230801   200000    235959  1690905599  ...    719  0.160942 -0.470313     NaN
720  20230802   000000    035959  1690919999  ...    720  0.128275 -0.612325    -1.0
721  20230802   040000    075959  1690934399  ...    721  0.106051 -0.705412    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-25002.54526161816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29710.80440659', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


