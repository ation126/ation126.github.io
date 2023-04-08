# 20230409 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38140
self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28004.3, self.close=28009.4, self.high=28009.4, self.low=28002.5, self.vol=217.35, self.amt=6087135.4076 
127.0.0.1 - - [09/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-09 00:20:09,667:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230408   235500    235959  ...         0.0        0.0       0
5760  20230409   000000    000459  ...         0.0        0.0       0
5761  20230409   000500    000959  ...         0.0        0.0       0
5762  20230409   001000    001459  ...         0.0        0.0       0
5763  20230409   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 00:20:09,697:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28004.3, self.close=28009.4, self.high=28009.4, self.low=28002.5, self.vol=217.35, self.amt=6087135.4076, ukdf['pct'].iloc[-1]=0.000186 , ukdf['amount'].iloc[-1]=6087135.4076, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-690896.86288856304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28010.56932479', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=38141
self.closeSec=1680971099, self.tradeDate='20230409', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28009.4, self.close=28003.1, self.high=28009.4, self.low=28003.0, self.vol=114.771, self.amt=3214105.638 
127.0.0.1 - - [09/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-09 00:25:01,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230409   000000    000459  ...         0.0        0.0       0
5761  20230409   000500    000959  ...         0.0        0.0       0
5762  20230409   001000    001459  ...         0.0        0.0       0
5763  20230409   001500    001959  ...         0.0        0.0       0
5764  20230409   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 00:25:01,578:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680971099, self.tradeDate='20230409', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28009.4, self.close=28003.1, self.high=28009.4, self.low=28003.0, self.vol=114.771, self.amt=3214105.638, ukdf['pct'].iloc[-1]=-0.000225 , ukdf['amount'].iloc[-1]=3214105.638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-690447.3888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28003.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28004.3, self.close=28009.4, self.high=28009.4, self.low=28002.5 
127.0.0.1 - - [09/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-09 00:20:07,078:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28004.3, self.close=28009.4, self.high=28009.4, self.low=28002.5   
2023-04-09 00:20:08,427:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230408   235500    235959  1680969599  ...  27995.0  0.000332   1727    5
1440  20230409   000000    000459  1680969899  ...  27999.7 -0.000164   1440    0
1441  20230409   000500    000959  1680970199  ...  27999.7  0.000168   1441    1
1442  20230409   001000    001459  1680970499  ...  28001.6 -0.000007   1442    2
1443  20230409   001500    001959  1680970799  ...  28002.5  0.000186   1443    3

[5 rows x 11 columns]
2023-04-09 00:20:08,428:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=40, self.factor=0.45508815929880964, self.count=38707 

self.closeSec=1680971099, self.tradeDate='20230409', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28009.4, self.close=28003.1, self.high=28009.4, self.low=28003.0 
2023-04-09 00:25:01,495:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680971099, self.tradeDate='20230409', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28009.4, self.close=28003.1, self.high=28009.4, self.low=28003.0   
2023-04-09 00:25:01,537:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230409   000000    000459  1680969899  ...  27999.7 -0.000164   1440    0
1441  20230409   000500    000959  1680970199  ...  27999.7  0.000168   1441    1
1442  20230409   001000    001459  1680970499  ...  28001.6 -0.000007   1442    2
1443  20230409   001500    001959  1680970799  ...  28002.5  0.000186   1443    3
1444  20230409   002000    002459  1680971099  ...  28003.0 -0.000225   1444    4

[5 rows x 11 columns]
2023-04-09 00:25:01,537:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-09 00:00:35,171:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230408    212959  27977.5  ...  45.416667  0.493913  0.402907
5803  20230408    215959  27965.4  ...  45.416667  0.506834  0.405278
5804  20230408    222959  28008.6  ...  45.833333  0.515023  0.401845
5805  20230408    225959  28036.6  ...  45.833333  0.506924  0.403964
5806  20230408    232959  28010.2  ...  45.416667  0.500867  0.409953

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-04-09 00:00:35,348:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.509595  0.490405       1  ...  0.957663   1.0    0.0  1.039149
540     0  0.521355  0.478645       1  ...  0.958621   1.0    0.0  1.040188
541     0  0.522360  0.477640       0  ...  0.957718   1.0    0.0  1.039208
542     0  0.508110  0.491890       0  ...  0.957038   1.0    0.0  1.038470
543     0  0.509759  0.490241       1  ...  0.957516   1.0    0.0  1.038990

[5 rows x 10 columns]
2023-04-09 00:00:35,389:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508749  0.491251       1  ...  0.951593   1.0    0.0  1.034757
46     0  0.521066  0.478934       1  ...  0.958621   1.0    0.0  1.036259
47     0  0.522004  0.477996       0  ...  0.957718   1.0    0.0  1.035283
48     0  0.507692  0.492308       0  ...  0.957038   1.0    0.0  1.035807
49     0  0.509759  0.490241       1  ...  0.957516   1.0    0.0  1.038990

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [09/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-09 00:00:03,802:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42135F1680969602914I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680969603047484, 'quantity': '24.353', 'price': '28004.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680969602384, 'updatetime': 1680969603047, 'tradetype': 'usdt', 'selfid': 42135, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680969603047, 'clientorderid': '42135F1680969602914I0L59', 'price': '28004.3', 'quantity': '24.353', 'commission': '681.9887179', 'commissionasset': 'USDT', 'tradetime': 1680969603047, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680969603047}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19352 

self.closeSec=1680970199, self.tradeDate='20230409', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28004.3', self.close='28004.4'
2023-04-09 00:10:01,614:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680970199, self.tradeDate='20230409', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28004.3', self.close='28004.4'
2023-04-09 00:10:01,679:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230408   232000    232959  1680967799  27997.6  27990.3 -0.000261
573  20230408   233000    233959  1680968399  27990.3  27978.8 -0.000411
574  20230408   234000    234959  1680968999  27978.9  28001.8  0.000822
575  20230408   235000    235959  1680969599  28001.8  28004.3  0.000089
576  20230409   000000    000959  1680970199  28004.3  28004.4  0.000004
2023-04-09 00:10:01,679:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19353 

self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28004.4', self.close='28009.4'
127.0.0.1 - - [09/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 00:20:08,158:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28004.4', self.close='28009.4'
2023-04-09 00:20:09,099:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230408   233000    233959  1680968399  27990.3  27978.8 -0.000411
574  20230408   234000    234959  1680968999  27978.9  28001.8  0.000822
575  20230408   235000    235959  1680969599  28001.8  28004.3  0.000089
576  20230409   000000    000959  1680970199  28004.3  28004.4  0.000004
577  20230409   001000    001959  1680970799  28004.4  28009.4  0.000179
2023-04-09 00:20:09,099:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-04-09 00:00:02,005:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-04-09 00:00:02,135:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:4090000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230408, closeTime:235959, close:28004.3, total:978039.764104, pct_pre:0.003344649277355227, thd:-0.2486252956876896, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19353 

self.closeSec=1680970199, self.tradeDate='20230409', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28004.3', self.close='28004.4'
2023-04-09 00:10:01,630:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680970199, self.tradeDate='20230409', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28004.3', self.close='28004.4'
127.0.0.1 - - [09/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-09 00:10:01,693:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230408   232000    232959  1680967799  27997.6  27990.3
17421  20230408   233000    233959  1680968399  27990.3  27978.8
17422  20230408   234000    234959  1680968999  27978.9  28001.8
17423  20230408   235000    235959  1680969599  28001.8  28004.3
17424  20230409   000000    000959  1680970199  28004.3  28004.4
2023-04-09 00:10:01,693:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19354 

self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28004.4', self.close='28009.4'
127.0.0.1 - - [09/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 00:20:11,773:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28004.4', self.close='28009.4'
2023-04-09 00:20:11,924:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230408   233000    233959  1680968399  27990.3  27978.8
17422  20230408   234000    234959  1680968999  27978.9  28001.8
17423  20230408   235000    235959  1680969599  28001.8  28004.3
17424  20230409   000000    000959  1680970199  28004.3  28004.4
17425  20230409   001000    001959  1680970799  28004.4  28009.4
2023-04-09 00:20:11,924:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-09 00:00:03,464:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42134F1680969602825I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680969602978031, 'quantity': '46.423', 'price': '28004.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680969602301, 'updatetime': 1680969602978, 'tradetype': 'usdt', 'selfid': 42134, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680969602978, 'clientorderid': '42134F1680969602825I0L2', 'price': '28004.4', 'quantity': '46.423', 'commission': '1300.0482612', 'commissionasset': 'USDT', 'tradetime': 1680969602978, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680969602978}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19353 

self.closeSec=1680970199, self.tradeDate='20230409', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28004.3', self.close='28004.4'
2023-04-09 00:10:01,601:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680970199, self.tradeDate='20230409', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28004.3', self.close='28004.4'
2023-04-09 00:10:01,625:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230408   232000    232959  1680967799  27997.6  27990.3
12237  20230408   233000    233959  1680968399  27990.3  27978.8
12238  20230408   234000    234959  1680968999  27978.9  28001.8
12239  20230408   235000    235959  1680969599  28001.8  28004.3
12240  20230409   000000    000959  1680970199  28004.3  28004.4
2023-04-09 00:10:01,625:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19354 

self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28004.4', self.close='28009.4'
127.0.0.1 - - [09/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-09 00:20:11,209:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28004.4', self.close='28009.4'
2023-04-09 00:20:11,525:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230408   233000    233959  1680968399  27990.3  27978.8
12238  20230408   234000    234959  1680968999  27978.9  28001.8
12239  20230408   235000    235959  1680969599  28001.8  28004.3
12240  20230409   000000    000959  1680970199  28004.3  28004.4
12241  20230409   001000    001959  1680970799  28004.4  28009.4
2023-04-09 00:20:11,525:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34138
self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28004.3, self.close=28009.4, self.high=28009.4, self.low=28002.5, self.vol=217.35, self.amt=6087135.4076 
127.0.0.1 - - [09/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-09 00:20:09,336:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230408   235500    235959  ...         0.0        0.0       0
5760  20230409   000000    000459  ...         0.0        0.0       0
5761  20230409   000500    000959  ...         0.0        0.0       0
5762  20230409   001000    001459  ...         0.0        0.0       0
5763  20230409   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 00:20:09,359:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680970799, self.tradeDate='20230409', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28004.3, self.close=28009.4, self.high=28009.4, self.low=28002.5, self.vol=217.35, self.amt=6087135.4076, ukdf['pct'].iloc[-1]=0.000186 , ukdf['amount'].iloc[-1]=6087135.4076, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=34139
self.closeSec=1680971099, self.tradeDate='20230409', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28009.4, self.close=28003.1, self.high=28009.4, self.low=28003.0, self.vol=114.771, self.amt=3214105.638 
2023-04-09 00:25:01,580:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230409   000000    000459  ...         0.0        0.0       0
5761  20230409   000500    000959  ...         0.0        0.0       0
5762  20230409   001000    001459  ...         0.0        0.0       0
5763  20230409   001500    001959  ...         0.0        0.0       0
5764  20230409   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-09 00:25:01,580:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680971099, self.tradeDate='20230409', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28009.4, self.close=28003.1, self.high=28009.4, self.low=28003.0, self.vol=114.771, self.amt=3214105.638, ukdf['pct'].iloc[-1]=-0.000225 , ukdf['amount'].iloc[-1]=3214105.638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230408   120000    155959  1680940799  ...    723  0.257239  0.065334     NaN
724  20230408   160000    195959  1680955199  ...    724  0.245706 -0.000154     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '20724.22762912056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28000.93047863', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [09/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=806
self.closeSec=1680969599, self.tradeDate='20230408', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27997.7, self.close=28004.3, self.high=28047.9, self.low=27925.1, self.vol=23432.442, self.amt=655930099.56328 
2023-04-09 00:00:01,798:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680969599, self.tradeDate='20230408', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27997.7, self.close=28004.3, self.high=28047.9, self.low=27925.1, self.vol=23432.442, self.amt=655930099.56328 
2023-04-09 00:00:01,877:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230408   040000    075959  ...  21815.597  6.086249e+08  0.000154
722  20230408   080000    115959  ...  26709.114  7.463568e+08  0.004130
723  20230408   120000    155959  ...  38189.946  1.072169e+09  0.002424
724  20230408   160000    195959  ...  22421.507  6.284661e+08 -0.002711
725  20230408   200000    235959  ...  23432.442  6.559301e+08  0.000236

[5 rows x 11 columns]
2023-04-09 00:00:05,230:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230408   040000    075959  1680911999  ...    721  0.124757 -0.517900     NaN
722  20230408   080000    115959  1680926399  ...    722  0.297441  0.263230     NaN
723  20230408   120000    155959  1680940799  ...    723  0.257239  0.065334     NaN
724  20230408   160000    195959  1680955199  ...    724  0.245706 -0.000154     NaN
725  20230408   200000    235959  1680969599  ...    725  0.255298  0.032437     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '20543.5072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28004.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


