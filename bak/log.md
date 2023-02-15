# 20230216 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23164
self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22830.0, self.close=22772.0, self.high=22880.0, self.low=22756.3, self.vol=6776.864, self.amt=154600828.2247 
2023-02-16 00:20:01,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230215   235500    235959  ...         0.0        0.0       0
5760  20230216   000000    000459  ...         0.0        0.0       0
5761  20230216   000500    000959  ...         0.0        0.0       0
5762  20230216   001000    001459  ...         0.0        0.0       0
5763  20230216   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 00:20:01,629:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22830.0, self.close=22772.0, self.high=22880.0, self.low=22756.3, self.vol=6776.864, self.amt=154600828.2247, ukdf['pct'].iloc[-1]=-0.002541 , ukdf['amount'].iloc[-1]=154600828.2247, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-375738.944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22773.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=23165
self.closeSec=1676478299, self.tradeDate='20230216', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22772.1, self.close=22777.4, self.high=22795.3, self.low=22752.9, self.vol=2676.786, self.amt=60959535.1354 
127.0.0.1 - - [16/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-16 00:25:01,662:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230216   000000    000459  ...         0.0        0.0       0
5761  20230216   000500    000959  ...         0.0        0.0       0
5762  20230216   001000    001459  ...         0.0        0.0       0
5763  20230216   001500    001959  ...         0.0        0.0       0
5764  20230216   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 00:25:01,663:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676478299, self.tradeDate='20230216', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22772.1, self.close=22777.4, self.high=22795.3, self.low=22752.9, self.vol=2676.786, self.amt=60959535.1354, ukdf['pct'].iloc[-1]=0.000237 , ukdf['amount'].iloc[-1]=60959535.1354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-375991.6832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22777.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.2355357498183322, self.count=23730 

self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22830.0, self.close=22772.0, self.high=22880.0, self.low=22756.3 
2023-02-16 00:20:01,553:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22830.0, self.close=22772.0, self.high=22880.0, self.low=22756.3   
2023-02-16 00:20:01,577:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230215   235500    235959  1676476799  ...  22790.0 -0.001778   1727    5
1440  20230216   000000    000459  1676477099  ...  22768.5  0.000434   1440    0
1441  20230216   000500    000959  1676477399  ...  22800.0  0.001228   1441    1
1442  20230216   001000    001459  1676477699  ...  22830.0 -0.000263   1442    2
1443  20230216   001500    001959  1676477999  ...  22756.3 -0.002541   1443    3

[5 rows x 11 columns]
2023-02-16 00:20:01,577:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=39, self.factor=0.2355357498183322, self.count=23731 

self.closeSec=1676478299, self.tradeDate='20230216', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22772.1, self.close=22777.4, self.high=22795.3, self.low=22752.9 
2023-02-16 00:25:01,592:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676478299, self.tradeDate='20230216', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22772.1, self.close=22777.4, self.high=22795.3, self.low=22752.9   
2023-02-16 00:25:01,648:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230216   000000    000459  1676477099  ...  22768.5  0.000434   1440    0
1441  20230216   000500    000959  1676477399  ...  22800.0  0.001228   1441    1
1442  20230216   001000    001459  1676477699  ...  22830.0 -0.000263   1442    2
1443  20230216   001500    001959  1676477999  ...  22756.3 -0.002541   1443    3
1444  20230216   002000    002459  1676478299  ...  22752.9  0.000237   1444    4

[5 rows x 11 columns]
2023-02-16 00:25:01,648:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-16 00:00:35,623:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230215    212959  22763.6  ...  48.750000  0.673309  0.211918
5803  20230215    215959  22759.3  ...  48.750000  0.651066  0.215608
5804  20230215    222959  22687.1  ...  48.750000  0.651773  0.218789
5805  20230215    225959  22691.7  ...  48.333333  0.647456  0.222825
5806  20230215    232959  22677.3  ...  48.750000  0.660466  0.220538

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-02-16 00:00:35,788:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.549008  0.450992       0  ...  1.072506   1.0    0.0  0.972760
540     0  0.528666  0.471334       1  ...  1.072714   1.0    0.0  0.972949
541     0  0.524115  0.475885       0  ...  1.072043   1.0    0.0  0.972340
542     1  0.491435  0.508565       1  ...  1.075848   1.0    0.0  0.975792
543     0  0.516956  0.483044       1  ...  1.077753   1.0    0.0  0.977519

[5 rows x 10 columns]
2023-02-16 00:00:35,822:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.548573  0.451427       0  ...  1.072506   1.0    0.0  0.972660
46     0  0.527819  0.472181       1  ...  1.072714   1.0    0.0  0.972390
47     0  0.523370  0.476630       0  ...  1.072043   1.0    0.0  0.971782
48     1  0.491224  0.508776       1  ...  1.075848   1.0    0.0  0.975666
49     0  0.516956  0.483044       1  ...  1.077753   1.0    0.0  0.977519

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.557', 'enterprice': '21695.5', 'countrevence': '0', 'unrealprofit': '39564.8969937566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22808.2175238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-02-16 00:00:04,281:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41739F1676476803515I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676476803901489, 'quantity': '41.834', 'price': '22794.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676476802954, 'updatetime': 1676476803901, 'tradetype': 'usdt', 'selfid': 41739, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676476803901, 'clientorderid': '41739F1676476803515I0L59', 'price': '22794.9', 'quantity': '41.834', 'commission': '953.6018466', 'commissionasset': 'USDT', 'tradetime': 1676476803901, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676476803901}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11864 

self.closeSec=1676477399, self.tradeDate='20230216', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22798', self.close='22836'
2023-02-16 00:10:01,644:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676477399, self.tradeDate='20230216', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22798', self.close='22836'
127.0.0.1 - - [16/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-16 00:10:01,651:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230215   232000    232959  1676474999  22739.6  22757.8  0.000800
573  20230215   233000    233959  1676475599  22757.9    22773  0.000668
574  20230215   234000    234959  1676476199    22773  22726.1 -0.002059
575  20230215   235000    235959  1676476799    22726  22798.1  0.003168
576  20230216   000000    000959  1676477399    22798    22836  0.001662
2023-02-16 00:10:01,651:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11865 

self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22836', self.close='22772'
2023-02-16 00:20:01,672:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22836', self.close='22772'
2023-02-16 00:20:01,694:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230215   233000    233959  1676475599  22757.9    22773  0.000668
574  20230215   234000    234959  1676476199    22773  22726.1 -0.002059
575  20230215   235000    235959  1676476799    22726  22798.1  0.003168
576  20230216   000000    000959  1676477399    22798    22836  0.001662
577  20230216   001000    001959  1676477999    22836    22772 -0.002803
2023-02-16 00:20:01,695:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [15/Feb/2023 23:00:02] "POST / HTTP/1.1" 200 -
2023-02-15 23:00:03,259:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 20:30:00  203000  22763.6  ...     NaN     NaN       0
145  2023/02/15 21:00:00  210000  22760.2  ...     NaN     NaN       0
146  2023/02/15 21:30:00  213000  22687.1  ...     NaN     NaN       0
147  2023/02/15 22:00:00  220000  22691.5  ...     NaN     NaN       0
148  2023/02/15 22:30:00  223000  22677.3  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [15/Feb/2023 23:30:01] "POST / HTTP/1.1" 200 -
2023-02-15 23:30:02,646:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 21:00:00  210000  22760.2  ...     NaN     NaN       0
145  2023/02/15 21:30:00  213000  22687.1  ...     NaN     NaN       0
146  2023/02/15 22:00:00  220000  22691.5  ...     NaN     NaN       0
147  2023/02/15 22:30:00  223000  22677.3  ...     NaN     NaN       0
148  2023/02/15 23:00:00  230000  22757.8  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [16/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-16 00:00:03,166:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/15 21:30:00  213000  22687.1  ...     NaN     NaN       0
145  2023/02/15 22:00:00  220000  22691.5  ...     NaN     NaN       0
146  2023/02/15 22:30:00  223000  22677.3  ...     NaN     NaN       0
147  2023/02/15 23:00:00  230000  22757.8  ...     NaN     NaN       0
148  2023/02/15 23:30:00  233000  22798.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-02-16 00:00:04,082:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41740F1676476803653I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676476803778528, 'quantity': '42.795', 'price': '22794.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676476803058, 'updatetime': 1676476803778, 'tradetype': 'usdt', 'selfid': 41740, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676476803778, 'clientorderid': '41740F1676476803653I0L57', 'price': '22794.9', 'quantity': '42.795', 'commission': '975.5077455', 'commissionasset': 'USDT', 'tradetime': 1676476803778, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676476803778}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Feb/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11865 

self.closeSec=1676477399, self.tradeDate='20230216', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22798', self.close='22836'
2023-02-16 00:10:01,653:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676477399, self.tradeDate='20230216', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22798', self.close='22836'
2023-02-16 00:10:01,663:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230215   232000    232959  1676474999  22739.6  22757.8
17421  20230215   233000    233959  1676475599  22757.9    22773
17422  20230215   234000    234959  1676476199    22773  22726.1
17423  20230215   235000    235959  1676476799    22726  22798.1
17424  20230216   000000    000959  1676477399    22798    22836
2023-02-16 00:10:01,664:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11866 

self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22836', self.close='22772'
127.0.0.1 - - [16/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 00:20:01,639:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22836', self.close='22772'
2023-02-16 00:20:01,686:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230215   233000    233959  1676475599  22757.9    22773
17422  20230215   234000    234959  1676476199    22773  22726.1
17423  20230215   235000    235959  1676476799    22726  22798.1
17424  20230216   000000    000959  1676477399    22798    22836
17425  20230216   001000    001959  1676477999    22836    22772
2023-02-16 00:20:01,687:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-02-16 00:00:04,591:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41741F1676476803779I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676476804219654, 'quantity': '50.352', 'price': '22794.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676476803261, 'updatetime': 1676476804219, 'tradetype': 'usdt', 'selfid': 41741, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676476804219, 'clientorderid': '41741F1676476803779I0L2', 'price': '22794.9', 'quantity': '50.352', 'commission': '1147.7688048', 'commissionasset': 'USDT', 'tradetime': 1676476804219, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676476804219}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11865 

self.closeSec=1676477399, self.tradeDate='20230216', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22798', self.close='22836'
2023-02-16 00:10:01,688:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676477399, self.tradeDate='20230216', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22798', self.close='22836'
2023-02-16 00:10:01,700:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230215   232000    232959  1676474999  22739.6  22757.8
12237  20230215   233000    233959  1676475599  22757.9    22773
12238  20230215   234000    234959  1676476199    22773  22726.1
12239  20230215   235000    235959  1676476799    22726  22798.1
12240  20230216   000000    000959  1676477399    22798    22836
2023-02-16 00:10:01,700:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11866 

self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22836', self.close='22772'
127.0.0.1 - - [16/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-16 00:20:01,659:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22836', self.close='22772'
2023-02-16 00:20:01,691:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230215   233000    233959  1676475599  22757.9    22773
12238  20230215   234000    234959  1676476199    22773  22726.1
12239  20230215   235000    235959  1676476799    22726  22798.1
12240  20230216   000000    000959  1676477399    22798    22836
12241  20230216   001000    001959  1676477999    22836    22772
2023-02-16 00:20:01,691:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19162
self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22830.0, self.close=22772.0, self.high=22880.0, self.low=22756.3, self.vol=6776.864, self.amt=154600828.2247 
2023-02-16 00:20:01,619:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230215   235500    235959  ...         0.0        0.0       0
5760  20230216   000000    000459  ...         0.0        0.0       0
5761  20230216   000500    000959  ...         0.0        0.0       0
5762  20230216   001000    001459  ...         0.0        0.0       0
5763  20230216   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 00:20:01,627:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676477999, self.tradeDate='20230216', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22830.0, self.close=22772.0, self.high=22880.0, self.low=22756.3, self.vol=6776.864, self.amt=154600828.2247, ukdf['pct'].iloc[-1]=-0.002541 , ukdf['amount'].iloc[-1]=154600828.2247, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [16/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=19163
self.closeSec=1676478299, self.tradeDate='20230216', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22772.1, self.close=22777.4, self.high=22795.3, self.low=22752.9, self.vol=2676.786, self.amt=60959535.1354 
2023-02-16 00:25:01,684:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230216   000000    000459  ...         0.0        0.0       0
5761  20230216   000500    000959  ...         0.0        0.0       0
5762  20230216   001000    001459  ...         0.0        0.0       0
5763  20230216   001500    001959  ...         0.0        0.0       0
5764  20230216   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-16 00:25:01,684:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676478299, self.tradeDate='20230216', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22772.1, self.close=22777.4, self.high=22795.3, self.low=22752.9, self.vol=2676.786, self.amt=60959535.1354, ukdf['pct'].iloc[-1]=0.000237 , ukdf['amount'].iloc[-1]=60959535.1354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230215   120000    155959  1676447999  ...    723  0.154039 -1.681050    -1.0
724  20230215   160000    195959  1676462399  ...    724  0.255446 -1.249438    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-36067.0419', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22440.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=925514.8695891, self.flagDict['side']='sell', self.tradeCount=19, self.count=494
self.closeSec=1676476799, self.tradeDate='20230215', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22433.0, self.close=22798.1, self.high=22924.9, self.low=22432.9, self.vol=207159.107, self.amt=4704555342.59668 
127.0.0.1 - - [16/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-16 00:00:02,443:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676476799, self.tradeDate='20230215', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22433.0, self.close=22798.1, self.high=22924.9, self.low=22432.9, self.vol=207159.107, self.amt=4704555342.59668 
2023-02-16 00:00:02,473:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230215   040000    075959  ...   49074.627  1.089328e+09 -0.000419
722  20230215   080000    115959  ...   35580.160  7.867157e+08 -0.004439
723  20230215   120000    155959  ...   23896.173  5.284312e+08  0.000389
724  20230215   160000    195959  ...   86066.327  1.918943e+09  0.015183
725  20230215   200000    235959  ...  207159.107  4.704555e+09  0.016275

[5 rows x 11 columns]
2023-02-16 00:00:04,911:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230215   040000    075959  1676419199  ...    721  0.097099 -2.015925    -1.0
722  20230215   080000    115959  1676433599  ...    722  0.141782 -1.779834    -1.0
723  20230215   120000    155959  1676447999  ...    723  0.154039 -1.681050    -1.0
724  20230215   160000    195959  1676462399  ...    724  0.255446 -1.249438    -1.0
725  20230215   200000    235959  1676476799  ...    725  0.558057 -0.052169     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.891', 'enterprice': '21599.9', 'countrevence': '0', 'unrealprofit': '-51414.55887973245', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22798.62604695', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


