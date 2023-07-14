# 20230715 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17728
self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=31210.1, self.close=31246.9, self.high=31247.8, self.low=31203.1, self.vol=818.36, self.amt=25554088.8902 
127.0.0.1 - - [15/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 00:20:06,450:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230714   235500    235959  ...         0.0        0.0       0
5760  20230715   000000    000459  ...         0.0        0.0       0
5761  20230715   000500    000959  ...         0.0        0.0       0
5762  20230715   001000    001459  ...         0.0        0.0       0
5763  20230715   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 00:20:06,479:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=31210.1, self.close=31246.9, self.high=31247.8, self.low=31203.1, self.vol=818.36, self.amt=25554088.8902, ukdf['pct'].iloc[-1]=0.001182 , ukdf['amount'].iloc[-1]=25554088.8902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-61023.732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31246.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17729
self.closeSec=1689351899, self.tradeDate='20230715', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31247.0, self.close=31238.2, self.high=31252.2, self.low=31229.9, self.vol=334.626, self.amt=10455039.0997 
127.0.0.1 - - [15/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-15 00:25:00,830:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230715   000000    000459  ...         0.0        0.0       0
5761  20230715   000500    000959  ...         0.0        0.0       0
5762  20230715   001000    001459  ...         0.0        0.0       0
5763  20230715   001500    001959  ...         0.0        0.0       0
5764  20230715   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 00:25:00,830:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689351899, self.tradeDate='20230715', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31247.0, self.close=31238.2, self.high=31252.2, self.low=31229.9, self.vol=334.626, self.amt=10455039.0997, ukdf['pct'].iloc[-1]=-0.000278 , ukdf['amount'].iloc[-1]=10455039.0997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-60959.3594730318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31242.2775293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=31210.1, self.close=31246.9, self.high=31247.8, self.low=31203.1 
127.0.0.1 - - [15/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 00:20:04,318:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=31210.1, self.close=31246.9, self.high=31247.8, self.low=31203.1   
2023-07-15 00:20:05,669:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230714   235500    235959  1689350399  ...  31214.2  0.000525   1727    5
1440  20230715   000000    000459  1689350699  ...  31229.7 -0.000016   1440    0
1441  20230715   000500    000959  1689350999  ...  31212.4  0.000419   1441    1
1442  20230715   001000    001459  1689351299  ...  31207.5 -0.001251   1442    2
1443  20230715   001500    001959  1689351599  ...  31203.1  0.001182   1443    3

[5 rows x 11 columns]
2023-07-15 00:20:05,688:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.46247916949576207, self.count=17731 

self.closeSec=1689351899, self.tradeDate='20230715', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31247.0, self.close=31238.2, self.high=31252.2, self.low=31229.9 
2023-07-15 00:25:00,730:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689351899, self.tradeDate='20230715', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31247.0, self.close=31238.2, self.high=31252.2, self.low=31229.9   
127.0.0.1 - - [15/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-15 00:25:00,795:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230715   000000    000459  1689350699  ...  31229.7 -0.000016   1440    0
1441  20230715   000500    000959  1689350999  ...  31212.4  0.000419   1441    1
1442  20230715   001000    001459  1689351299  ...  31207.5 -0.001251   1442    2
1443  20230715   001500    001959  1689351599  ...  31203.1  0.001182   1443    3
1444  20230715   002000    002459  1689351899  ...  31229.9 -0.000278   1444    4

[5 rows x 11 columns]
2023-07-15 00:25:00,795:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-15 00:00:20,076:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230714    212959  31122.6  ...  52.916667  0.538993  0.455563
5803  20230714    215959  31148.8  ...  53.333333  0.556262  0.471840
5804  20230714    222959  31251.0  ...  53.333333  0.546271  0.490839
5805  20230714    225959  31202.6  ...  53.333333  0.561490  0.501362
5806  20230714    232959  31294.1  ...  53.333333  0.567043  0.508481

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-07-15 00:00:20,181:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.525979  0.474021       1  ...  0.951188  -1.0  0.0000  1.019180
540     0  0.553221  0.446779       0  ...  0.948178   1.0 -0.0016  1.017585
541     0  0.513329  0.486671       1  ...  0.950992   1.0  0.0000  1.020605
542     0  0.562715  0.437285       1  ...  0.952046   1.0  0.0000  1.021736
543     0  0.556497  0.443503       0  ...  0.949226   1.0  0.0000  1.018710

[5 rows x 10 columns]
2023-07-15 00:00:20,205:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.526353  0.473647       1  ...  0.951188  -1.0  0.0000  1.020164
46     0  0.551927  0.448073       0  ...  0.968638   1.0 -0.0016  1.018269
47     0  0.513334  0.486666       1  ...  0.950992   1.0  0.0000  1.021291
48     0  0.562169  0.437831       1  ...  0.952046   1.0  0.0000  1.020242
49     0  0.556497  0.443503       0  ...  0.949226   1.0  0.0000  1.018710

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.986', 'enterprice': '31199.5', 'countrevence': '0', 'unrealprofit': '771.54219846566', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31231.66635531', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [15/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-15 00:00:04,774:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42636F1689350403866I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689350404236297, 'quantity': '23.581', 'price': '31236.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689350402847, 'updatetime': 1689350404236, 'tradetype': 'usdt', 'selfid': 42636, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689350404236, 'clientorderid': '42636F1689350403866I0L59', 'price': '31236.5', 'quantity': '23.581', 'commission': '736.5879065', 'commissionasset': 'USDT', 'tradetime': 1689350404236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689350404236}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8864 

self.closeSec=1689350999, self.tradeDate='20230715', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31236.6', self.close='31249.1'
2023-07-15 00:10:01,103:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689350999, self.tradeDate='20230715', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31236.6', self.close='31249.1'
2023-07-15 00:10:01,123:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230714   232000    232959  1689348599  31343.4  31329.3 -0.000533
573  20230714   233000    233959  1689349199  31329.3    31300 -0.000935
574  20230714   234000    234959  1689349799    31300    31230 -0.002236
575  20230714   235000    235959  1689350399  31229.9  31236.5  0.000208
576  20230715   000000    000959  1689350999  31236.6  31249.1  0.000403
2023-07-15 00:10:01,124:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8865 

self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='31249.2', self.close='31246.9'
127.0.0.1 - - [15/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 00:20:06,840:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='31249.2', self.close='31246.9'
2023-07-15 00:20:07,479:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230714   233000    233959  1689349199  31329.3    31300 -0.000935
574  20230714   234000    234959  1689349799    31300    31230 -0.002236
575  20230714   235000    235959  1689350399  31229.9  31236.5  0.000208
576  20230715   000000    000959  1689350999  31236.6  31249.1  0.000403
577  20230715   001000    001959  1689351599  31249.2  31246.9 -0.000070
2023-07-15 00:20:07,479:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [15/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-15 00:00:04,516:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42635F1689350403850I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689350404232877, 'quantity': '32.342', 'price': '31236.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689350402860, 'updatetime': 1689350404232, 'tradetype': 'usdt', 'selfid': 42635, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689350404232, 'clientorderid': '42635F1689350403850I0L57', 'price': '31236.5', 'quantity': '32.342', 'commission': '1010.250883', 'commissionasset': 'USDT', 'tradetime': 1689350404232, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689350404232}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8867 

self.closeSec=1689350999, self.tradeDate='20230715', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31236.6', self.close='31249.1'
2023-07-15 00:10:01,105:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689350999, self.tradeDate='20230715', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31236.6', self.close='31249.1'
2023-07-15 00:10:01,111:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230714   232000    232959  1689348599  31343.4  31329.3
17421  20230714   233000    233959  1689349199  31329.3    31300
17422  20230714   234000    234959  1689349799    31300    31230
17423  20230714   235000    235959  1689350399  31229.9  31236.5
17424  20230715   000000    000959  1689350999  31236.6  31249.1
2023-07-15 00:10:01,111:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8868 

self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='31249.2', self.close='31246.9'
127.0.0.1 - - [15/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 00:20:08,321:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='31249.2', self.close='31246.9'
2023-07-15 00:20:08,502:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230714   233000    233959  1689349199  31329.3    31300
17422  20230714   234000    234959  1689349799    31300    31230
17423  20230714   235000    235959  1689350399  31229.9  31236.5
17424  20230715   000000    000959  1689350999  31236.6  31249.1
17425  20230715   001000    001959  1689351599  31249.2  31246.9
2023-07-15 00:20:08,503:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [15/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-15 00:00:04,985:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42637F1689350403886I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689350404250498, 'quantity': '36.35', 'price': '31236.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689350402870, 'updatetime': 1689350404250, 'tradetype': 'usdt', 'selfid': 42637, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689350404250, 'clientorderid': '42637F1689350403886I0L2', 'price': '31236.5', 'quantity': '36.35', 'commission': '1135.446775', 'commissionasset': 'USDT', 'tradetime': 1689350404250, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689350404250}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8867 

self.closeSec=1689350999, self.tradeDate='20230715', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31236.6', self.close='31249.1'
127.0.0.1 - - [15/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-15 00:10:01,092:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689350999, self.tradeDate='20230715', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31236.6', self.close='31249.1'
2023-07-15 00:10:01,099:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230714   232000    232959  1689348599  31343.4  31329.3
12237  20230714   233000    233959  1689349199  31329.3    31300
12238  20230714   234000    234959  1689349799    31300    31230
12239  20230714   235000    235959  1689350399  31229.9  31236.5
12240  20230715   000000    000959  1689350999  31236.6  31249.1
2023-07-15 00:10:01,100:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8868 

self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='31249.2', self.close='31246.9'
127.0.0.1 - - [15/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-15 00:20:08,152:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='31249.2', self.close='31246.9'
2023-07-15 00:20:08,389:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230714   233000    233959  1689349199  31329.3    31300
12238  20230714   234000    234959  1689349799    31300    31230
12239  20230714   235000    235959  1689350399  31229.9  31236.5
12240  20230715   000000    000959  1689350999  31236.6  31249.1
12241  20230715   001000    001959  1689351599  31249.2  31246.9
2023-07-15 00:20:08,390:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17728
self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=31210.1, self.close=31246.9, self.high=31247.8, self.low=31203.1, self.vol=818.36, self.amt=25554088.8902 
127.0.0.1 - - [15/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-15 00:20:06,439:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230714   235500    235959  ...         0.0        0.0       0
5760  20230715   000000    000459  ...         0.0        0.0       0
5761  20230715   000500    000959  ...         0.0        0.0       0
5762  20230715   001000    001459  ...         0.0        0.0       0
5763  20230715   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 00:20:06,459:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689351599, self.tradeDate='20230715', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=31210.1, self.close=31246.9, self.high=31247.8, self.low=31203.1, self.vol=818.36, self.amt=25554088.8902, ukdf['pct'].iloc[-1]=0.001182 , ukdf['amount'].iloc[-1]=25554088.8902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '163531.823', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31247', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17729
self.closeSec=1689351899, self.tradeDate='20230715', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31247.0, self.close=31238.2, self.high=31252.2, self.low=31229.9, self.vol=334.626, self.amt=10455039.0997 
2023-07-15 00:25:00,826:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230715   000000    000459  ...         0.0        0.0       0
5761  20230715   000500    000959  ...         0.0        0.0       0
5762  20230715   001000    001459  ...         0.0        0.0       0
5763  20230715   001500    001959  ...         0.0        0.0       0
5764  20230715   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-15 00:25:00,827:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689351899, self.tradeDate='20230715', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31247.0, self.close=31238.2, self.high=31252.2, self.low=31229.9, self.vol=334.626, self.amt=10455039.0997, ukdf['pct'].iloc[-1]=-0.000278 , ukdf['amount'].iloc[-1]=10455039.0997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '163356.4257157313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31242.2775293', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230714   120000    155959  1689321599  ...    723  0.884779  2.157640     1.0
724  20230714   160000    195959  1689335999  ...    724  0.725703  1.521613     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '36500.7867', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31209.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=369
self.closeSec=1689350399, self.tradeDate='20230714', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=31206.4, self.close=31236.5, self.high=31364.9, self.low=31037.4, self.vol=60181.765, self.amt=1878755987.4852 
2023-07-15 00:00:01,907:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689350399, self.tradeDate='20230714', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=31206.4, self.close=31236.5, self.high=31364.9, self.low=31037.4, self.vol=60181.765, self.amt=1878755987.4852 
2023-07-15 00:00:01,944:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230714   040000    075959  ...  113138.840  3.544202e+09 -0.005028
722  20230714   080000    115959  ...   60468.943  1.901094e+09  0.000118
723  20230714   120000    155959  ...   47214.511  1.477015e+09 -0.011111
724  20230714   160000    195959  ...   43894.191  1.368772e+09  0.003550
725  20230714   200000    235959  ...   60181.765  1.878756e+09  0.000965

[5 rows x 11 columns]
2023-07-15 00:00:03,432:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230714   040000    075959  1689292799  ...    721  1.170617  3.472242     1.0
722  20230714   080000    115959  1689307199  ...    722  0.915208  2.355026     1.0
723  20230714   120000    155959  1689321599  ...    723  0.884779  2.157640     1.0
724  20230714   160000    195959  1689335999  ...    724  0.725703  1.521613     1.0
725  20230714   200000    235959  1689350399  ...    725  0.665636  1.274415     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '37896.14026962743', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31236.50993223', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


