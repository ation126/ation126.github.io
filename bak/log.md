# 20230618 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9952
self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26428.3, self.close=26464.6, self.high=26478.8, self.low=26428.3, self.vol=1608.248, self.amt=42553557.9999 
127.0.0.1 - - [18/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-18 00:20:07,360:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230617   235500    235959  ...         0.0        0.0       0
5760  20230618   000000    000459  ...         0.0        0.0       0
5761  20230618   000500    000959  ...         0.0        0.0       0
5762  20230618   001000    001459  ...         0.0        0.0       0
5763  20230618   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 00:20:07,390:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26428.3, self.close=26464.6, self.high=26478.8, self.low=26428.3, self.vol=1608.248, self.amt=42553557.9999, ukdf['pct'].iloc[-1]=0.00137 , ukdf['amount'].iloc[-1]=42553557.9999, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5570.0165503752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26464.9275348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9953
self.closeSec=1687019099, self.tradeDate='20230618', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26464.6, self.close=26458.0, self.high=26466.0, self.low=26438.0, self.vol=775.44, self.amt=20512372.1312 
2023-06-18 00:25:00,796:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230618   000000    000459  ...         0.0        0.0       0
5761  20230618   000500    000959  ...         0.0        0.0       0
5762  20230618   001000    001459  ...         0.0        0.0       0
5763  20230618   001500    001959  ...         0.0        0.0       0
5764  20230618   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 00:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687019099, self.tradeDate='20230618', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26464.6, self.close=26458.0, self.high=26466.0, self.low=26438.0, self.vol=775.44, self.amt=20512372.1312, ukdf['pct'].iloc[-1]=-0.000249 , ukdf['amount'].iloc[-1]=20512372.1312, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5666.4894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26458', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26428.3, self.close=26464.6, self.high=26478.8, self.low=26428.3 
127.0.0.1 - - [18/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-18 00:20:04,750:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26428.3, self.close=26464.6, self.high=26478.8, self.low=26428.3   
2023-06-18 00:20:06,320:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230617   235500    235959  1687017599  ...  26384.1  0.000227   1727    5
1440  20230618   000000    000459  1687017899  ...  26372.4 -0.000754   1440    0
1441  20230618   000500    000959  1687018199  ...  26364.3  0.000417   1441    1
1442  20230618   001000    001459  1687018499  ...  26391.0  0.001417   1442    2
1443  20230618   001500    001959  1687018799  ...  26428.3  0.001370   1443    3

[5 rows x 11 columns]
2023-06-18 00:20:06,330:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=37, self.factor=0.24413071786449397, self.count=9955 

self.closeSec=1687019099, self.tradeDate='20230618', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26464.6, self.close=26458.0, self.high=26466.0, self.low=26438.0 
127.0.0.1 - - [18/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-18 00:25:00,754:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687019099, self.tradeDate='20230618', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26464.6, self.close=26458.0, self.high=26466.0, self.low=26438.0   
2023-06-18 00:25:00,780:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230618   000000    000459  1687017899  ...  26372.4 -0.000754   1440    0
1441  20230618   000500    000959  1687018199  ...  26364.3  0.000417   1441    1
1442  20230618   001000    001459  1687018499  ...  26391.0  0.001417   1442    2
1443  20230618   001500    001959  1687018799  ...  26428.3  0.001370   1443    3
1444  20230618   002000    002459  1687019099  ...  26438.0 -0.000249   1444    4

[5 rows x 11 columns]
2023-06-18 00:25:00,780:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-18 00:00:20,758:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230617    212959  26511.3  ...  50.833333  0.604421  0.228978
5803  20230617    215959  26523.3  ...  51.250000  0.607338  0.246626
5804  20230617    222959  26540.0  ...  50.833333  0.586803  0.270539
5805  20230617    225959  26459.0  ...  50.833333  0.591478  0.290389
5806  20230617    232959  26485.6  ...  51.250000  0.593252  0.307984

[5 rows x 33 columns]
0.5551470588235294
acc is : 0.5551470588235294
2023-06-18 00:00:20,868:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495161  0.504839       1  ...  1.112476   1.0    0.0  1.032428
540     0  0.500292  0.499708       0  ...  1.109064   1.0    0.0  1.029261
541     1  0.481451  0.518549       1  ...  1.110196   1.0    0.0  1.030312
542     1  0.497203  0.502797       1  ...  1.110623   1.0    0.0  1.030708
543     1  0.497886  0.502114       0  ...  1.106604   1.0    0.0  1.026978

[5 rows x 10 columns]
2023-06-18 00:00:20,894:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495063  0.504937       1  ...  1.112476   1.0    0.0  1.030768
46     0  0.500635  0.499365       0  ...  1.109064   1.0    0.0  1.027415
47     1  0.481461  0.518539       1  ...  1.110196   1.0    0.0  1.028463
48     1  0.497296  0.502704       1  ...  1.110623   1.0    0.0  1.027766
49     1  0.497886  0.502114       0  ...  1.106604   1.0    0.0  1.026978

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '27332.59116050287', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26395.75636081', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [18/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-18 00:00:04,671:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42409F1687017603615I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687017604027758, 'quantity': '27.92', 'price': '26400', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687017602667, 'updatetime': 1687017604027, 'tradetype': 'usdt', 'selfid': 42409, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687017604027, 'clientorderid': '42409F1687017603615I0L59', 'price': '26400', 'quantity': '27.92', 'commission': '737.088', 'commissionasset': 'USDT', 'tradetime': 1687017604027, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687017604027}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4976 

self.closeSec=1687018199, self.tradeDate='20230618', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26399.9', self.close='26391'
2023-06-18 00:10:01,108:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687018199, self.tradeDate='20230618', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26399.9', self.close='26391'
2023-06-18 00:10:01,133:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230617   232000    232959  1687015799  26423.3  26495.8  0.002717
573  20230617   233000    233959  1687016399  26495.8    26437 -0.002219
574  20230617   234000    234959  1687016999    26437  26429.4 -0.000287
575  20230617   235000    235959  1687017599  26429.5  26399.9 -0.001116
576  20230618   000000    000959  1687018199  26399.9    26391 -0.000337
2023-06-18 00:10:01,133:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4977 

self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26391.1', self.close='26464.6'
127.0.0.1 - - [18/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 00:20:06,960:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26391.1', self.close='26464.6'
2023-06-18 00:20:07,721:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230617   233000    233959  1687016399  26495.8    26437 -0.002219
574  20230617   234000    234959  1687016999    26437  26429.4 -0.000287
575  20230617   235000    235959  1687017599  26429.5  26399.9 -0.001116
576  20230618   000000    000959  1687018199  26399.9    26391 -0.000337
577  20230618   001000    001959  1687018799  26391.1  26464.6  0.002789
2023-06-18 00:20:07,729:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [18/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-18 00:00:04,241:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42407F1687017603583I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687017603970441, 'quantity': '36.851', 'price': '26399.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687017602645, 'updatetime': 1687017603970, 'tradetype': 'usdt', 'selfid': 42407, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687017603970, 'clientorderid': '42407F1687017603583I0L57', 'price': '26399.9', 'quantity': '36.851', 'commission': '972.8627149', 'commissionasset': 'USDT', 'tradetime': 1687017603970, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687017603970}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4979 

self.closeSec=1687018199, self.tradeDate='20230618', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26399.9', self.close='26391'
2023-06-18 00:10:01,125:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687018199, self.tradeDate='20230618', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26399.9', self.close='26391'
2023-06-18 00:10:01,147:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230617   232000    232959  1687015799  26423.3  26495.8
17421  20230617   233000    233959  1687016399  26495.8    26437
17422  20230617   234000    234959  1687016999    26437  26429.4
17423  20230617   235000    235959  1687017599  26429.5  26399.9
17424  20230618   000000    000959  1687018199  26399.9    26391
2023-06-18 00:10:01,148:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4980 

self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26391.1', self.close='26464.6'
127.0.0.1 - - [18/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 00:20:09,075:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26391.1', self.close='26464.6'
2023-06-18 00:20:09,205:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230617   233000    233959  1687016399  26495.8    26437
17422  20230617   234000    234959  1687016999    26437  26429.4
17423  20230617   235000    235959  1687017599  26429.5  26399.9
17424  20230618   000000    000959  1687018199  26399.9    26391
17425  20230618   001000    001959  1687018799  26391.1  26464.6
2023-06-18 00:20:09,206:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [18/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-18 00:00:04,436:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42408F1687017603599I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687017604014730, 'quantity': '49.643', 'price': '26400', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687017602667, 'updatetime': 1687017604014, 'tradetype': 'usdt', 'selfid': 42408, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687017604014, 'clientorderid': '42408F1687017603599I0L2', 'price': '26400', 'quantity': '49.643', 'commission': '1310.5752', 'commissionasset': 'USDT', 'tradetime': 1687017604014, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687017604014}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4979 

self.closeSec=1687018199, self.tradeDate='20230618', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26399.9', self.close='26391'
127.0.0.1 - - [18/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-18 00:10:01,121:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687018199, self.tradeDate='20230618', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26399.9', self.close='26391'
2023-06-18 00:10:01,136:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230617   232000    232959  1687015799  26423.3  26495.8
12237  20230617   233000    233959  1687016399  26495.8    26437
12238  20230617   234000    234959  1687016999    26437  26429.4
12239  20230617   235000    235959  1687017599  26429.5  26399.9
12240  20230618   000000    000959  1687018199  26399.9    26391
2023-06-18 00:10:01,136:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4980 

self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26391.1', self.close='26464.6'
127.0.0.1 - - [18/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 00:20:08,735:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26391.1', self.close='26464.6'
2023-06-18 00:20:09,020:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230617   233000    233959  1687016399  26495.8    26437
12238  20230617   234000    234959  1687016999    26437  26429.4
12239  20230617   235000    235959  1687017599  26429.5  26399.9
12240  20230618   000000    000959  1687018199  26399.9    26391
12241  20230618   001000    001959  1687018799  26391.1  26464.6
2023-06-18 00:20:09,021:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9952
self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26428.3, self.close=26464.6, self.high=26478.8, self.low=26428.3, self.vol=1608.248, self.amt=42553557.9999 
127.0.0.1 - - [18/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-18 00:20:07,350:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230617   235500    235959  ...         0.0        0.0       0
5760  20230618   000000    000459  ...         0.0        0.0       0
5761  20230618   000500    000959  ...         0.0        0.0       0
5762  20230618   001000    001459  ...         0.0        0.0       0
5763  20230618   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 00:20:07,381:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687018799, self.tradeDate='20230618', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26428.3, self.close=26464.6, self.high=26478.8, self.low=26428.3, self.vol=1608.248, self.amt=42553557.9999, ukdf['pct'].iloc[-1]=0.00137 , ukdf['amount'].iloc[-1]=42553557.9999, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14079.1304299932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26464.9275348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9953
self.closeSec=1687019099, self.tradeDate='20230618', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26464.6, self.close=26458.0, self.high=26466.0, self.low=26438.0, self.vol=775.44, self.amt=20512372.1312 
2023-06-18 00:25:00,809:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230618   000000    000459  ...         0.0        0.0       0
5761  20230618   000500    000959  ...         0.0        0.0       0
5762  20230618   001000    001459  ...         0.0        0.0       0
5763  20230618   001500    001959  ...         0.0        0.0       0
5764  20230618   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 00:25:00,814:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687019099, self.tradeDate='20230618', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26464.6, self.close=26458.0, self.high=26466.0, self.low=26438.0, self.vol=775.44, self.amt=20512372.1312, ukdf['pct'].iloc[-1]=-0.000249 , ukdf['amount'].iloc[-1]=20512372.1312, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-14336.426', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26458', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230617   120000    155959  1686988799  ...    723  0.515413  0.637007     1.0
724  20230617   160000    195959  1687003199  ...    724  0.541351  0.787352     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-5417.50539304325', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26495.24695421', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=207
self.closeSec=1687017599, self.tradeDate='20230617', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26497.5, self.close=26399.9, self.high=26579.1, self.low=26288.5, self.vol=64566.845, self.amt=1708796941.5001 
127.0.0.1 - - [18/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-18 00:00:01,690:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687017599, self.tradeDate='20230617', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26497.5, self.close=26399.9, self.high=26579.1, self.low=26288.5, self.vol=64566.845, self.amt=1708796941.5001 
2023-06-18 00:00:01,717:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230617   040000    075959  ...   37660.921  9.924992e+08 -0.001233
722  20230617   080000    115959  ...   36661.055  9.628664e+08 -0.003136
723  20230617   120000    155959  ...  107938.264  2.873805e+09  0.012730
724  20230617   160000    195959  ...   43152.994  1.146774e+09 -0.003389
725  20230617   200000    235959  ...   64566.845  1.708797e+09 -0.003683

[5 rows x 11 columns]
2023-06-18 00:00:02,999:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230617   040000    075959  1686959999  ...    721  0.422262  0.120551     NaN
722  20230617   080000    115959  1686974399  ...    722  0.440066  0.231394     NaN
723  20230617   120000    155959  1686988799  ...    723  0.515413  0.637007     1.0
724  20230617   160000    195959  1687003199  ...    724  0.541351  0.787352     1.0
725  20230617   200000    235959  1687017599  ...    725  0.560629  0.902073     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-10868.9675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26399.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


