# 20230723 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20032
self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29850.4, self.close=29861.5, self.high=29861.5, self.low=29847.5, self.vol=311.637, self.amt=9303169.254 
127.0.0.1 - - [23/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 00:20:05,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230722   235500    235959  ...         0.0        0.0       0
5760  20230723   000000    000459  ...         0.0        0.0       0
5761  20230723   000500    000959  ...         0.0        0.0       0
5762  20230723   001000    001459  ...         0.0        0.0       0
5763  20230723   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 00:20:05,808:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29850.4, self.close=29861.5, self.high=29861.5, self.low=29847.5, self.vol=311.637, self.amt=9303169.254, ukdf['pct'].iloc[-1]=0.000372 , ukdf['amount'].iloc[-1]=9303169.254, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41739.71877779682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29862.15109707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20033
self.closeSec=1690043099, self.tradeDate='20230723', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29861.4, self.close=29865.6, self.high=29865.6, self.low=29861.4, self.vol=147.728, self.amt=4411803.3911 
2023-07-23 00:25:00,785:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230723   000000    000459  ...         0.0        0.0       0
5761  20230723   000500    000959  ...         0.0        0.0       0
5762  20230723   001000    001459  ...         0.0        0.0       0
5763  20230723   001500    001959  ...         0.0        0.0       0
5764  20230723   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 00:25:00,785:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690043099, self.tradeDate='20230723', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29861.4, self.close=29865.6, self.high=29865.6, self.low=29861.4, self.vol=147.728, self.amt=4411803.3911, ukdf['pct'].iloc[-1]=0.000137 , ukdf['amount'].iloc[-1]=4411803.3911, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-41787.7482', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29865.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29850.4, self.close=29861.5, self.high=29861.5, self.low=29847.5 
127.0.0.1 - - [23/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 00:20:04,134:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29850.4, self.close=29861.5, self.high=29861.5, self.low=29847.5   
2023-07-23 00:20:05,209:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230722   235500    235959  1690041599  ...  29883.9 -0.000003   1727    5
1440  20230723   000000    000459  1690041899  ...  29883.9  0.000288   1440    0
1441  20230723   000500    000959  1690042199  ...  29889.1 -0.000040   1441    1
1442  20230723   001000    001459  1690042499  ...  29849.4 -0.001368   1442    2
1443  20230723   001500    001959  1690042799  ...  29847.5  0.000372   1443    3

[5 rows x 11 columns]
2023-07-23 00:20:05,219:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=124, self.factor=0.5019222802117337, self.count=20035 

self.closeSec=1690043099, self.tradeDate='20230723', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29861.4, self.close=29865.6, self.high=29865.6, self.low=29861.4 
127.0.0.1 - - [23/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-23 00:25:00,748:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690043099, self.tradeDate='20230723', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29861.4, self.close=29865.6, self.high=29865.6, self.low=29861.4   
2023-07-23 00:25:00,760:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230723   000000    000459  1690041899  ...  29883.9  0.000288   1440    0
1441  20230723   000500    000959  1690042199  ...  29889.1 -0.000040   1441    1
1442  20230723   001000    001459  1690042499  ...  29849.4 -0.001368   1442    2
1443  20230723   001500    001959  1690042799  ...  29847.5  0.000372   1443    3
1444  20230723   002000    002459  1690043099  ...  29861.4  0.000137   1444    4

[5 rows x 11 columns]
2023-07-23 00:25:00,760:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-23 00:00:18,136:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230722    212959  29826.8  ...  50.833333  0.483803  0.535092
5803  20230722    215959  29846.6  ...  50.416667  0.480226  0.549317
5804  20230722    222959  29836.0  ...  50.416667  0.478897  0.563478
5805  20230722    225959  29832.2  ...  50.416667  0.492639  0.560585
5806  20230722    232959  29869.6  ...  50.416667  0.490381  0.568884

[5 rows x 33 columns]
0.5091911764705882
acc is : 0.5091911764705882
2023-07-23 00:00:18,221:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.509519  0.490481       0  ...  0.969443   1.0    0.0  0.977316
540     0  0.505108  0.494892       0  ...  0.969316   1.0    0.0  0.977189
541     0  0.504398  0.495602       1  ...  0.970531   1.0    0.0  0.978414
542     0  0.519543  0.480457       0  ...  0.970323   1.0    0.0  0.978204
543     0  0.511157  0.488843       1  ...  0.970999   1.0    0.0  0.978885

[5 rows x 10 columns]
2023-07-23 00:00:18,240:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509376  0.490624       0  ...  0.969731   1.0    0.0  0.977271
46     0  0.504620  0.495380       0  ...  0.969316   1.0    0.0  0.974211
47     0  0.504037  0.495963       1  ...  0.970531   1.0    0.0  0.975433
48     0  0.519339  0.480661       0  ...  0.970323   1.0    0.0  0.977004
49     0  0.511157  0.488843       1  ...  0.970999   1.0    0.0  0.978885

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '1047.9468', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29884', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-07-23 00:00:04,286:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42713F1690041603573I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690041603965682, 'quantity': '24.835', 'price': '29883.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690041602704, 'updatetime': 1690041603965, 'tradetype': 'usdt', 'selfid': 42713, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690041603965, 'clientorderid': '42713F1690041603573I0L59', 'price': '29883.9', 'quantity': '24.835', 'commission': '742.1666565', 'commissionasset': 'USDT', 'tradetime': 1690041603965, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690041603965}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10016 

self.closeSec=1690042199, self.tradeDate='20230723', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29883.9', self.close='29891.3'
2023-07-23 00:10:01,102:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690042199, self.tradeDate='20230723', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29883.9', self.close='29891.3'
2023-07-23 00:10:01,114:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230722   232000    232959  1690039799  29844.1  29863.1  0.000640
573  20230722   233000    233959  1690040399    29863  29862.8 -0.000010
574  20230722   234000    234959  1690040999  29862.9  29884.1  0.000713
575  20230722   235000    235959  1690041599  29884.1  29883.9 -0.000007
576  20230723   000000    000959  1690042199  29883.9  29891.3  0.000248
2023-07-23 00:10:01,114:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10017 

self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29891.3', self.close='29861.5'
127.0.0.1 - - [23/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 00:20:05,989:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29891.3', self.close='29861.5'
2023-07-23 00:20:06,519:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230722   233000    233959  1690040399    29863  29862.8 -0.000010
574  20230722   234000    234959  1690040999  29862.9  29884.1  0.000713
575  20230722   235000    235959  1690041599  29884.1  29883.9 -0.000007
576  20230723   000000    000959  1690042199  29883.9  29891.3  0.000248
577  20230723   001000    001959  1690042799  29891.3  29861.5 -0.000997
2023-07-23 00:20:06,519:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [23/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-23 00:00:04,183:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42712F1690041603533I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690041603903351, 'quantity': '33.69', 'price': '29883.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690041602656, 'updatetime': 1690041603903, 'tradetype': 'usdt', 'selfid': 42712, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690041603903, 'clientorderid': '42712F1690041603533I0L57', 'price': '29883.9', 'quantity': '33.69', 'commission': '1006.788591', 'commissionasset': 'USDT', 'tradetime': 1690041603903, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690041603903}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10019 

self.closeSec=1690042199, self.tradeDate='20230723', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29883.9', self.close='29891.3'
2023-07-23 00:10:01,100:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690042199, self.tradeDate='20230723', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29883.9', self.close='29891.3'
2023-07-23 00:10:01,118:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230722   232000    232959  1690039799  29844.1  29863.1
17421  20230722   233000    233959  1690040399    29863  29862.8
17422  20230722   234000    234959  1690040999  29862.9  29884.1
17423  20230722   235000    235959  1690041599  29884.1  29883.9
17424  20230723   000000    000959  1690042199  29883.9  29891.3
2023-07-23 00:10:01,118:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10020 

self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29891.3', self.close='29861.5'
127.0.0.1 - - [23/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 00:20:07,221:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29891.3', self.close='29861.5'
2023-07-23 00:20:07,435:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230722   233000    233959  1690040399    29863  29862.8
17422  20230722   234000    234959  1690040999  29862.9  29884.1
17423  20230722   235000    235959  1690041599  29884.1  29883.9
17424  20230723   000000    000959  1690042199  29883.9  29891.3
17425  20230723   001000    001959  1690042799  29891.3  29861.5
2023-07-23 00:20:07,437:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-23 00:00:04,040:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42711F1690041603523I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690041603897084, 'quantity': '37.884', 'price': '29883.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690041602680, 'updatetime': 1690041603897, 'tradetype': 'usdt', 'selfid': 42711, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690041603897, 'clientorderid': '42711F1690041603523I0L2', 'price': '29883.9', 'quantity': '37.884', 'commission': '1132.1216676', 'commissionasset': 'USDT', 'tradetime': 1690041603897, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690041603897}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10019 

self.closeSec=1690042199, self.tradeDate='20230723', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29883.9', self.close='29891.3'
2023-07-23 00:10:01,104:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690042199, self.tradeDate='20230723', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29883.9', self.close='29891.3'
2023-07-23 00:10:01,110:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230722   232000    232959  1690039799  29844.1  29863.1
12237  20230722   233000    233959  1690040399    29863  29862.8
12238  20230722   234000    234959  1690040999  29862.9  29884.1
12239  20230722   235000    235959  1690041599  29884.1  29883.9
12240  20230723   000000    000959  1690042199  29883.9  29891.3
2023-07-23 00:10:01,110:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10020 

self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29891.3', self.close='29861.5'
127.0.0.1 - - [23/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 00:20:07,111:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29891.3', self.close='29861.5'
2023-07-23 00:20:07,341:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230722   233000    233959  1690040399    29863  29862.8
12238  20230722   234000    234959  1690040999  29862.9  29884.1
12239  20230722   235000    235959  1690041599  29884.1  29883.9
12240  20230723   000000    000959  1690042199  29883.9  29891.3
12241  20230723   001000    001959  1690042799  29891.3  29861.5
2023-07-23 00:20:07,342:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20032
self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29850.4, self.close=29861.5, self.high=29861.5, self.low=29847.5, self.vol=311.637, self.amt=9303169.254 
127.0.0.1 - - [23/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 00:20:05,809:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230722   235500    235959  ...         0.0        0.0       0
5760  20230723   000000    000459  ...         0.0        0.0       0
5761  20230723   000500    000959  ...         0.0        0.0       0
5762  20230723   001000    001459  ...         0.0        0.0       0
5763  20230723   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 00:20:05,828:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690042799, self.tradeDate='20230723', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29850.4, self.close=29861.5, self.high=29861.5, self.low=29847.5, self.vol=311.637, self.amt=9303169.254, ukdf['pct'].iloc[-1]=0.000372 , ukdf['amount'].iloc[-1]=9303169.254, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112097.14989627687', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29862.15109707', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20033
self.closeSec=1690043099, self.tradeDate='20230723', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29861.4, self.close=29865.6, self.high=29865.6, self.low=29861.4, self.vol=147.728, self.amt=4411803.3911 
127.0.0.1 - - [23/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-23 00:25:00,786:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230723   000000    000459  ...         0.0        0.0       0
5761  20230723   000500    000959  ...         0.0        0.0       0
5762  20230723   001000    001459  ...         0.0        0.0       0
5763  20230723   001500    001959  ...         0.0        0.0       0
5764  20230723   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 00:25:00,787:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690043099, self.tradeDate='20230723', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29861.4, self.close=29865.6, self.high=29865.6, self.low=29861.4, self.vol=147.728, self.amt=4411803.3911, ukdf['pct'].iloc[-1]=0.000137 , ukdf['amount'].iloc[-1]=4411803.3911, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '112225.2456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29865.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230722   120000    155959  1690012799  ...    723  0.092641 -1.205199    -1.0
724  20230722   160000    195959  1690027199  ...    724  0.080624 -1.227083    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-81.62486068992', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29872.16441392', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [23/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=417
self.closeSec=1690041599, self.tradeDate='20230722', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29874.1, self.close=29883.9, self.high=29895.0, self.low=29806.6, self.vol=24285.778, self.amt=724941814.2061 
2023-07-23 00:00:01,819:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690041599, self.tradeDate='20230722', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29874.1, self.close=29883.9, self.high=29895.0, self.low=29806.6, self.vol=24285.778, self.amt=724941814.2061 
2023-07-23 00:00:01,836:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230722   040000    075959  ...  17712.508  5.293798e+08  0.000881
722  20230722   080000    115959  ...  18181.062  5.440819e+08 -0.000161
723  20230722   120000    155959  ...  26673.540  7.974821e+08  0.001553
724  20230722   160000    195959  ...  22981.220  6.872208e+08 -0.001968
725  20230722   200000    235959  ...  24285.778  7.249418e+08  0.000328

[5 rows x 11 columns]
2023-07-23 00:00:02,547:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230722   040000    075959  1689983999  ...    721  0.140332 -1.050430    -1.0
722  20230722   080000    115959  1689998399  ...    722  0.115788 -1.133400    -1.0
723  20230722   120000    155959  1690012799  ...    723  0.092641 -1.205199    -1.0
724  20230722   160000    195959  1690027199  ...    724  0.080624 -1.227083    -1.0
725  20230722   200000    235959  1690041599  ...    725  0.072097 -1.233408    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-704.7203042064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29884.1065989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


