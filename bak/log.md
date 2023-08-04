# 20230805 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23776
self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29262.0, self.close=29240.0, self.high=29262.0, self.low=29237.5, self.vol=444.973, self.amt=13015131.3926 
127.0.0.1 - - [05/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 00:20:06,263:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230804   235500    235959  ...         0.0        0.0       0
5760  20230805   000000    000459  ...         0.0        0.0       0
5761  20230805   000500    000959  ...         0.0        0.0       0
5762  20230805   001000    001459  ...         0.0        0.0       0
5763  20230805   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 00:20:06,292:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29262.0, self.close=29240.0, self.high=29262.0, self.low=29237.5, self.vol=444.973, self.amt=13015131.3926, ukdf['pct'].iloc[-1]=-0.000752 , ukdf['amount'].iloc[-1]=13015131.3926, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33089.1730862814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29240.9715989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23777
self.closeSec=1691166299, self.tradeDate='20230805', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29240.0, self.close=29241.1, self.high=29246.9, self.low=29237.1, self.vol=395.738, self.amt=11571642.0019 
2023-08-05 00:25:00,760:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230805   000000    000459  ...         0.0        0.0       0
5761  20230805   000500    000959  ...         0.0        0.0       0
5762  20230805   001000    001459  ...         0.0        0.0       0
5763  20230805   001500    001959  ...         0.0        0.0       0
5764  20230805   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 00:25:00,760:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691166299, self.tradeDate='20230805', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29240.0, self.close=29241.1, self.high=29246.9, self.low=29237.1, self.vol=395.738, self.amt=11571642.0019, ukdf['pct'].iloc[-1]=3.8e-05 , ukdf['amount'].iloc[-1]=11571642.0019, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33090.9612', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29241.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29262.0, self.close=29240.0, self.high=29262.0, self.low=29237.5 
127.0.0.1 - - [05/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 00:20:04,372:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29262.0, self.close=29240.0, self.high=29262.0, self.low=29237.5   
2023-08-05 00:20:05,523:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230804   235500    235959  1691164799  ...  29253.1 -0.000109   1727    5
1440  20230805   000000    000459  1691165099  ...  29254.2  0.000379   1440    0
1441  20230805   000500    000959  1691165399  ...  29238.7 -0.001063   1441    1
1442  20230805   001000    001459  1691165699  ...  29235.1  0.000793   1442    2
1443  20230805   001500    001959  1691165999  ...  29237.5 -0.000752   1443    3

[5 rows x 11 columns]
2023-08-05 00:20:05,532:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=11, self.factor=0.5526194637686813, self.count=23779 

self.closeSec=1691166299, self.tradeDate='20230805', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29240.0, self.close=29241.1, self.high=29246.9, self.low=29237.1 
2023-08-05 00:25:00,736:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691166299, self.tradeDate='20230805', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29240.0, self.close=29241.1, self.high=29246.9, self.low=29237.1   
2023-08-05 00:25:00,763:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230805   000000    000459  1691165099  ...  29254.2  0.000379   1440    0
1441  20230805   000500    000959  1691165399  ...  29238.7 -0.001063   1441    1
1442  20230805   001000    001459  1691165699  ...  29235.1  0.000793   1442    2
1443  20230805   001500    001959  1691165999  ...  29237.5 -0.000752   1443    3
1444  20230805   002000    002459  1691166299  ...  29237.1  0.000038   1444    4

[5 rows x 11 columns]
2023-08-05 00:25:00,763:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-05 00:00:17,638:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230804    212959  29208.7  ...  45.833333  0.499378  0.619499
5803  20230804    215959  29206.0  ...  46.250000  0.505301  0.609333
5804  20230804    222959  29225.0  ...  46.250000  0.506711  0.598745
5805  20230804    225959  29229.5  ...  46.250000  0.510163  0.586199
5806  20230804    232959  29240.4  ...  46.250000  0.517059  0.569162

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-08-05 00:00:17,703:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.511952  0.488048       1  ...  0.974469   1.0    0.0  0.980165
540     0  0.519095  0.480905       1  ...  0.974619   1.0    0.0  0.980316
541     0  0.514503  0.485497       1  ...  0.974983   1.0    0.0  0.980682
542     0  0.513580  0.486420       1  ...  0.975709   1.0    0.0  0.981413
543     0  0.515722  0.484278       0  ...  0.975596   1.0    0.0  0.981299

[5 rows x 10 columns]
2023-08-05 00:00:17,714:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512132  0.487868       1  ...  0.974469   1.0    0.0  0.981367
46     0  0.519412  0.480588       1  ...  0.974619   1.0    0.0  0.982009
47     0  0.514809  0.485191       1  ...  0.974983   1.0    0.0  0.982375
48     0  0.513719  0.486281       1  ...  0.975709   1.0    0.0  0.982019
49     0  0.515722  0.484278       0  ...  0.975596   1.0    0.0  0.981299

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '3113.364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29260.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-05 00:00:04,367:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42805F1691164803691I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691164804095254, 'quantity': '24.82', 'price': '29258.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691164802707, 'updatetime': 1691164804095, 'tradetype': 'usdt', 'selfid': 42805, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691164804095, 'clientorderid': '42805F1691164803691I0L59', 'price': '29258.8', 'quantity': '24.82', 'commission': '726.203416', 'commissionasset': 'USDT', 'tradetime': 1691164804095, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691164804095}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11888 

self.closeSec=1691165399, self.tradeDate='20230805', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29258.8', self.close='29238.8'
2023-08-05 00:10:01,111:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691165399, self.tradeDate='20230805', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29258.8', self.close='29238.8'
2023-08-05 00:10:01,128:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230804   232000    232959  1691162999  29228.8  29262.2  0.001146
573  20230804   233000    233959  1691163599  29262.2  29256.2 -0.000205
574  20230804   234000    234959  1691164199  29256.2  29283.6  0.000937
575  20230804   235000    235959  1691164799  29283.7  29258.8 -0.000847
576  20230805   000000    000959  1691165399  29258.8  29238.8 -0.000684
2023-08-05 00:10:01,128:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11889 

self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29238.6', self.close='29239.9'
127.0.0.1 - - [05/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 00:20:06,493:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29238.6', self.close='29239.9'
2023-08-05 00:20:07,132:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230804   233000    233959  1691163599  29262.2  29256.2 -0.000205
574  20230804   234000    234959  1691164199  29256.2  29283.6  0.000937
575  20230804   235000    235959  1691164799  29283.7  29258.8 -0.000847
576  20230805   000000    000959  1691165399  29258.8  29238.8 -0.000684
577  20230805   001000    001959  1691165999  29238.6  29239.9  0.000038
2023-08-05 00:20:07,132:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-05 00:00:02,165:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-05 00:00:02,222:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8050000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230804, closeTime:235959, close:29258.8, total:991132.0255179, pct_pre:-0.0009275104387705957, thd:0.1590957262942912, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11891 

self.closeSec=1691165399, self.tradeDate='20230805', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29258.8', self.close='29238.8'
127.0.0.1 - - [05/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-05 00:10:01,121:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691165399, self.tradeDate='20230805', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29258.8', self.close='29238.8'
2023-08-05 00:10:01,128:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230804   232000    232959  1691162999  29228.8  29262.2
17421  20230804   233000    233959  1691163599  29262.2  29256.2
17422  20230804   234000    234959  1691164199  29256.2  29283.6
17423  20230804   235000    235959  1691164799  29283.7  29258.8
17424  20230805   000000    000959  1691165399  29258.8  29238.8
2023-08-05 00:10:01,128:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11892 

self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29238.6', self.close='29239.9'
127.0.0.1 - - [05/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 00:20:08,296:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29238.6', self.close='29239.9'
2023-08-05 00:20:08,404:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230804   233000    233959  1691163599  29262.2  29256.2
17422  20230804   234000    234959  1691164199  29256.2  29283.6
17423  20230804   235000    235959  1691164799  29283.7  29258.8
17424  20230805   000000    000959  1691165399  29258.8  29238.8
17425  20230805   001000    001959  1691165999  29238.6  29239.9
2023-08-05 00:20:08,404:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-05 00:00:04,251:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42804F1691164803678I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691164804079634, 'quantity': '37.202', 'price': '29258.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691164802747, 'updatetime': 1691164804079, 'tradetype': 'usdt', 'selfid': 42804, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691164804079, 'clientorderid': '42804F1691164803678I0L2', 'price': '29258.8', 'quantity': '37.202', 'commission': '1088.4858776', 'commissionasset': 'USDT', 'tradetime': 1691164804079, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691164804079}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11891 

self.closeSec=1691165399, self.tradeDate='20230805', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29258.8', self.close='29238.8'
127.0.0.1 - - [05/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-05 00:10:01,109:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691165399, self.tradeDate='20230805', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29258.8', self.close='29238.8'
2023-08-05 00:10:01,115:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230804   232000    232959  1691162999  29228.8  29262.2
12237  20230804   233000    233959  1691163599  29262.2  29256.2
12238  20230804   234000    234959  1691164199  29256.2  29283.6
12239  20230804   235000    235959  1691164799  29283.7  29258.8
12240  20230805   000000    000959  1691165399  29258.8  29238.8
2023-08-05 00:10:01,116:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11892 

self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29238.6', self.close='29239.9'
127.0.0.1 - - [05/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 00:20:08,095:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29238.6', self.close='29239.9'
2023-08-05 00:20:08,293:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230804   233000    233959  1691163599  29262.2  29256.2
12238  20230804   234000    234959  1691164199  29256.2  29283.6
12239  20230804   235000    235959  1691164799  29283.7  29258.8
12240  20230805   000000    000959  1691165399  29258.8  29238.8
12241  20230805   001000    001959  1691165999  29238.6  29239.9
2023-08-05 00:20:08,294:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23776
self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29262.0, self.close=29240.0, self.high=29262.0, self.low=29237.5, self.vol=444.973, self.amt=13015131.3926 
127.0.0.1 - - [05/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 00:20:06,232:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230804   235500    235959  ...         0.0        0.0       0
5760  20230805   000000    000459  ...         0.0        0.0       0
5761  20230805   000500    000959  ...         0.0        0.0       0
5762  20230805   001000    001459  ...         0.0        0.0       0
5763  20230805   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 00:20:06,254:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691165999, self.tradeDate='20230805', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29262.0, self.close=29240.0, self.high=29262.0, self.low=29237.5, self.vol=444.973, self.amt=13015131.3926, ukdf['pct'].iloc[-1]=-0.000752 , ukdf['amount'].iloc[-1]=13015131.3926, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89025.9221547449', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29240.9715989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23777
self.closeSec=1691166299, self.tradeDate='20230805', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29240.0, self.close=29241.1, self.high=29246.9, self.low=29237.1, self.vol=395.738, self.amt=11571642.0019 
2023-08-05 00:25:00,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230805   000000    000459  ...         0.0        0.0       0
5761  20230805   000500    000959  ...         0.0        0.0       0
5762  20230805   001000    001459  ...         0.0        0.0       0
5763  20230805   001500    001959  ...         0.0        0.0       0
5764  20230805   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 00:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691166299, self.tradeDate='20230805', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29240.0, self.close=29241.1, self.high=29246.9, self.low=29237.1, self.vol=395.738, self.amt=11571642.0019, ukdf['pct'].iloc[-1]=3.8e-05 , ukdf['amount'].iloc[-1]=11571642.0019, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89030.6911', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29241.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230804   120000    155959  1691135999  ...    723  0.406703  0.700907     1.0
724  20230804   160000    195959  1691150399  ...    724  0.428782  0.798047     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '6847.88261899', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29159.8183956', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=495
self.closeSec=1691164799, self.tradeDate='20230804', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29157.2, self.close=29258.8, self.high=29323.8, self.low=29116.0, self.vol=53716.396, self.amt=1569762074.03848 
127.0.0.1 - - [05/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-05 00:00:01,701:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691164799, self.tradeDate='20230804', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29157.2, self.close=29258.8, self.high=29323.8, self.low=29116.0, self.vol=53716.396, self.amt=1569762074.03848 
2023-08-05 00:00:01,716:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230804   040000    075959  ...  32069.536  9.381274e+08 -0.002942
722  20230804   080000    115959  ...  24448.761  7.130760e+08 -0.000942
723  20230804   120000    155959  ...  18873.441  5.509091e+08  0.001681
724  20230804   160000    195959  ...  22514.238  6.569968e+08 -0.001520
725  20230804   200000    235959  ...  53716.396  1.569762e+09  0.003485

[5 rows x 11 columns]
2023-08-05 00:00:02,565:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230804   040000    075959  1691107199  ...    721  0.429670  0.843415     1.0
722  20230804   080000    115959  1691121599  ...    722  0.424128  0.801254     1.0
723  20230804   120000    155959  1691135999  ...    723  0.406703  0.700907     1.0
724  20230804   160000    195959  1691150399  ...    724  0.428782  0.798047     1.0
725  20230804   200000    235959  1691164799  ...    725  0.461738  0.942720     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '12275.0775', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29258.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


