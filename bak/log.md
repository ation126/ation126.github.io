# 20230714 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17440
self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30903.0, self.close=30888.7, self.high=30935.0, self.low=30875.0, self.vol=4881.835, self.amt=150887045.6918 
127.0.0.1 - - [14/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 00:20:06,863:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230713   235500    235959  ...         0.0        0.0       0
5760  20230714   000000    000459  ...         0.0        0.0       0
5761  20230714   000500    000959  ...         0.0        0.0       0
5762  20230714   001000    001459  ...         0.0        0.0       0
5763  20230714   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 00:20:06,893:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30903.0, self.close=30888.7, self.high=30935.0, self.low=30875.0, self.vol=4881.835, self.amt=150887045.6918, ukdf['pct'].iloc[-1]=-0.00046 , ukdf['amount'].iloc[-1]=150887045.6918, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-55904.29432662228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30879.28276078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17441
self.closeSec=1689265499, self.tradeDate='20230714', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30887.5, self.close=30889.9, self.high=30914.3, self.low=30828.0, self.vol=4828.597, self.amt=149048479.939 
127.0.0.1 - - [14/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-14 00:25:00,837:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230714   000000    000459  ...         0.0        0.0       0
5761  20230714   000500    000959  ...         0.0        0.0       0
5762  20230714   001000    001459  ...         0.0        0.0       0
5763  20230714   001500    001959  ...         0.0        0.0       0
5764  20230714   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 00:25:00,838:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689265499, self.tradeDate='20230714', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30887.5, self.close=30889.9, self.high=30914.3, self.low=30828.0, self.vol=4828.597, self.amt=149048479.939, ukdf['pct'].iloc[-1]=3.9e-05 , ukdf['amount'].iloc[-1]=149048479.939, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-56153.63209337772', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30897.18723922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30903.0, self.close=30888.7, self.high=30935.0, self.low=30875.0 
127.0.0.1 - - [14/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 00:20:04,782:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30903.0, self.close=30888.7, self.high=30935.0, self.low=30875.0   
2023-07-14 00:20:05,964:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230713   235500    235959  1689263999  ...  30855.0  0.001176   1727    5
1440  20230714   000000    000459  1689264299  ...  30815.1 -0.002145   1440    0
1441  20230714   000500    000959  1689264599  ...  30818.8  0.000999   1441    1
1442  20230714   001000    001459  1689264899  ...  30860.0  0.000894   1442    2
1443  20230714   001500    001959  1689265199  ...  30875.0 -0.000460   1443    3

[5 rows x 11 columns]
2023-07-14 00:20:05,982:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.5229021483354204, self.count=17443 

self.closeSec=1689265499, self.tradeDate='20230714', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30887.5, self.close=30889.9, self.high=30914.3, self.low=30828.0 
127.0.0.1 - - [14/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-14 00:25:00,771:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689265499, self.tradeDate='20230714', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30887.5, self.close=30889.9, self.high=30914.3, self.low=30828.0   
2023-07-14 00:25:00,815:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230714   000000    000459  1689264299  ...  30815.1 -0.002145   1440    0
1441  20230714   000500    000959  1689264599  ...  30818.8  0.000999   1441    1
1442  20230714   001000    001459  1689264899  ...  30860.0  0.000894   1442    2
1443  20230714   001500    001959  1689265199  ...  30875.0 -0.000460   1443    3
1444  20230714   002000    002459  1689265499  ...  30828.0  0.000039   1444    4

[5 rows x 11 columns]
2023-07-14 00:25:00,815:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-14 00:00:20,286:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230713    212959  30501.4  ...  53.333333  0.518721  0.558911
5803  20230713    215959  30522.1  ...  53.750000  0.552372  0.526557
5804  20230713    222959  30646.7  ...  53.333333  0.520002  0.510945
5805  20230713    225959  30537.8  ...  53.750000  0.525685  0.493452
5806  20230713    232959  30559.7  ...  53.750000  0.582856  0.461850

[5 rows x 33 columns]
0.5514705882352942
acc is : 0.5514705882352942
2023-07-14 00:00:20,435:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.500249  0.499751       1  ...  1.027362   1.0    0.0  1.004655
540     0  0.540247  0.459753       0  ...  1.023715   1.0    0.0  1.001088
541     1  0.476470  0.523530       1  ...  1.024446   1.0    0.0  1.001803
542     0  0.511122  0.488878       1  ...  1.032736   1.0    0.0  1.009910
543     0  0.593935  0.406065       1  ...  1.036216   1.0    0.0  1.013313

[5 rows x 10 columns]
2023-07-14 00:00:20,470:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500580  0.499420       1  ...  1.027362   1.0    0.0  1.004504
46     0  0.541098  0.458902       0  ...  1.023715   1.0    0.0  1.002038
47     1  0.477357  0.522643       1  ...  1.024446   1.0    0.0  1.002753
48     0  0.511545  0.488455       1  ...  1.032736   1.0    0.0  1.009973
49     0  0.593935  0.406065       1  ...  1.036216   1.0    0.0  1.013313

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '10926.03987258427', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30934.80072069', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [14/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-14 00:00:04,557:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42609F1689264003846I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689264004240840, 'quantity': '25.027', 'price': '30921.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689264002852, 'updatetime': 1689264004240, 'tradetype': 'usdt', 'selfid': 42609, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689264004240, 'clientorderid': '42609F1689264003846I0L59', 'price': '30921.2', 'quantity': '25.027', 'commission': '773.8648724', 'commissionasset': 'USDT', 'tradetime': 1689264004240, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689264004240}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8720 

self.closeSec=1689264599, self.tradeDate='20230714', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30915.5', self.close='30875.3'
2023-07-14 00:10:01,203:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689264599, self.tradeDate='20230714', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30915.5', self.close='30875.3'
2023-07-14 00:10:01,223:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230713   232000    232959  1689262199  30558.4    30807  0.008135
573  20230713   233000    233959  1689262799  30802.4  30794.1 -0.000419
574  20230713   234000    234959  1689263399  30795.7  30948.6  0.005017
575  20230713   235000    235959  1689263999  30947.2  30915.4 -0.001073
576  20230714   000000    000959  1689264599  30915.5  30875.3 -0.001297
2023-07-14 00:10:01,223:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8721 

self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30877.2', self.close='30888.7'
127.0.0.1 - - [14/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 00:20:06,913:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30877.2', self.close='30888.7'
2023-07-14 00:20:07,674:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230713   233000    233959  1689262799  30802.4  30794.1 -0.000419
574  20230713   234000    234959  1689263399  30795.7  30948.6  0.005017
575  20230713   235000    235959  1689263999  30947.2  30915.4 -0.001073
576  20230714   000000    000959  1689264599  30915.5  30875.3 -0.001297
577  20230714   001000    001959  1689265199  30877.2  30888.7  0.000434
2023-07-14 00:20:07,674:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-14 00:00:04,366:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42608F1689264003683I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689264004094849, 'quantity': '32.657', 'price': '30921.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689264002756, 'updatetime': 1689264004094, 'tradetype': 'usdt', 'selfid': 42608, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689264004094, 'clientorderid': '42608F1689264003683I0L57', 'price': '30921.1', 'quantity': '32.657', 'commission': '1009.7903627', 'commissionasset': 'USDT', 'tradetime': 1689264004094, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689264004094}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8723 

self.closeSec=1689264599, self.tradeDate='20230714', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30915.5', self.close='30875.3'
2023-07-14 00:10:01,214:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689264599, self.tradeDate='20230714', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30915.5', self.close='30875.3'
127.0.0.1 - - [14/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-14 00:10:01,227:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230713   232000    232959  1689262199  30558.4    30807
17421  20230713   233000    233959  1689262799  30802.4  30794.1
17422  20230713   234000    234959  1689263399  30795.7  30948.6
17423  20230713   235000    235959  1689263999  30947.2  30915.4
17424  20230714   000000    000959  1689264599  30915.5  30875.3
2023-07-14 00:10:01,227:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8724 

self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30877.2', self.close='30888.7'
127.0.0.1 - - [14/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 00:20:08,708:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30877.2', self.close='30888.7'
2023-07-14 00:20:08,900:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230713   233000    233959  1689262799  30802.4  30794.1
17422  20230713   234000    234959  1689263399  30795.7  30948.6
17423  20230713   235000    235959  1689263999  30947.2  30915.4
17424  20230714   000000    000959  1689264599  30915.5  30875.3
17425  20230714   001000    001959  1689265199  30877.2  30888.7
2023-07-14 00:20:08,900:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [14/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-14 00:00:04,790:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42610F1689264003861I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689264004260296, 'quantity': '36.823', 'price': '30921.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689264002880, 'updatetime': 1689264004260, 'tradetype': 'usdt', 'selfid': 42610, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689264004260, 'clientorderid': '42610F1689264003861I0L2', 'price': '30921.1', 'quantity': '36.823', 'commission': '1138.6076653', 'commissionasset': 'USDT', 'tradetime': 1689264004260, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689264004260}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8723 

self.closeSec=1689264599, self.tradeDate='20230714', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30915.5', self.close='30875.3'
2023-07-14 00:10:01,208:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689264599, self.tradeDate='20230714', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30915.5', self.close='30875.3'
2023-07-14 00:10:01,233:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230713   232000    232959  1689262199  30558.4    30807
12237  20230713   233000    233959  1689262799  30802.4  30794.1
12238  20230713   234000    234959  1689263399  30795.7  30948.6
12239  20230713   235000    235959  1689263999  30947.2  30915.4
12240  20230714   000000    000959  1689264599  30915.5  30875.3
2023-07-14 00:10:01,233:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8724 

self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30877.2', self.close='30888.7'
127.0.0.1 - - [14/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 00:20:08,494:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30877.2', self.close='30888.7'
2023-07-14 00:20:08,782:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230713   233000    233959  1689262799  30802.4  30794.1
12238  20230713   234000    234959  1689263399  30795.7  30948.6
12239  20230713   235000    235959  1689263999  30947.2  30915.4
12240  20230714   000000    000959  1689264599  30915.5  30875.3
12241  20230714   001000    001959  1689265199  30877.2  30888.7
2023-07-14 00:20:08,785:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17440
self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30903.0, self.close=30888.7, self.high=30935.0, self.low=30875.0, self.vol=4881.835, self.amt=150887045.6918 
127.0.0.1 - - [14/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 00:20:06,862:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230713   235500    235959  ...         0.0        0.0       0
5760  20230714   000000    000459  ...         0.0        0.0       0
5761  20230714   000500    000959  ...         0.0        0.0       0
5762  20230714   001000    001459  ...         0.0        0.0       0
5763  20230714   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 00:20:06,892:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689265199, self.tradeDate='20230714', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30903.0, self.close=30888.7, self.high=30935.0, self.low=30875.0, self.vol=4881.835, self.amt=150887045.6918, ukdf['pct'].iloc[-1]=-0.00046 , ukdf['amount'].iloc[-1]=150887045.6918, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '149874.43701812998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30879.28276078', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17441
self.closeSec=1689265499, self.tradeDate='20230714', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30887.5, self.close=30889.9, self.high=30914.3, self.low=30828.0, self.vol=4828.597, self.amt=149048479.939 
127.0.0.1 - - [14/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-14 00:25:00,837:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230714   000000    000459  ...         0.0        0.0       0
5761  20230714   000500    000959  ...         0.0        0.0       0
5762  20230714   001000    001459  ...         0.0        0.0       0
5763  20230714   001500    001959  ...         0.0        0.0       0
5764  20230714   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 00:25:00,839:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689265499, self.tradeDate='20230714', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30887.5, self.close=30889.9, self.high=30914.3, self.low=30828.0, self.vol=4828.597, self.amt=149048479.939, ukdf['pct'].iloc[-1]=3.9e-05 , ukdf['amount'].iloc[-1]=149048479.939, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '150539.42725187002', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30897.18723922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230713   120000    155959  1689235199  ...    723  0.333767  0.235954     NaN
724  20230713   160000    195959  1689249599  ...    724  0.333067  0.231303     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '1530.6613', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30540.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=363
self.closeSec=1689263999, self.tradeDate='20230713', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30530.6, self.close=30915.4, self.high=31205.3, self.low=30446.4, self.vol=176453.536, self.amt=5430610016.88916 
127.0.0.1 - - [14/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-14 00:00:01,804:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689263999, self.tradeDate='20230713', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30530.6, self.close=30915.4, self.high=31205.3, self.low=30446.4, self.vol=176453.536, self.amt=5430610016.88916 
2023-07-14 00:00:01,838:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230713   040000    075959  ...   29246.963  8.867321e+08  0.003330
722  20230713   080000    115959  ...   25819.244  7.831939e+08 -0.002806
723  20230713   120000    155959  ...   29140.810  8.836811e+08  0.002354
724  20230713   160000    195959  ...   59604.531  1.818564e+09  0.005785
725  20230713   200000    235959  ...  176453.536  5.430610e+09  0.012604

[5 rows x 11 columns]
2023-07-14 00:00:03,405:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230713   040000    075959  1689206399  ...    721  0.367737  0.396680     NaN
722  20230713   080000    115959  1689220799  ...    722  0.333764  0.239931     NaN
723  20230713   120000    155959  1689235199  ...    723  0.333767  0.235954     NaN
724  20230713   160000    195959  1689249599  ...    724  0.333067  0.231303     NaN
725  20230713   200000    235959  1689263999  ...    725  0.416175  0.597722     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '21717.08513994019', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30926.80959859', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


