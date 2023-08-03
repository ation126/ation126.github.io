# 20230804 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23488
self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29246.3, self.close=29239.8, self.high=29250.8, self.low=29221.6, self.vol=837.401, self.amt=24482512.7018 
127.0.0.1 - - [04/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 00:20:05,898:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230803   235500    235959  ...         0.0        0.0       0
5760  20230804   000000    000459  ...         0.0        0.0       0
5761  20230804   000500    000959  ...         0.0        0.0       0
5762  20230804   001000    001459  ...         0.0        0.0       0
5763  20230804   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 00:20:05,928:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29246.3, self.close=29239.8, self.high=29250.8, self.low=29221.6, self.vol=837.401, self.amt=24482512.7018, ukdf['pct'].iloc[-1]=-0.000222 , ukdf['amount'].iloc[-1]=24482512.7018, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33178.695', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29247.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23489
self.closeSec=1691079899, self.tradeDate='20230804', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29239.9, self.close=29267.1, self.high=29267.1, self.low=29239.8, self.vol=2504.362, self.amt=73268135.8442 
127.0.0.1 - - [04/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-04 00:25:00,799:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230804   000000    000459  ...         0.0        0.0       0
5761  20230804   000500    000959  ...         0.0        0.0       0
5762  20230804   001000    001459  ...         0.0        0.0       0
5763  20230804   001500    001959  ...         0.0        0.0       0
5764  20230804   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 00:25:00,800:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691079899, self.tradeDate='20230804', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29239.9, self.close=29267.1, self.high=29267.1, self.low=29239.8, self.vol=2504.362, self.amt=73268135.8442, ukdf['pct'].iloc[-1]=0.000934 , ukdf['amount'].iloc[-1]=73268135.8442, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33453.0372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29267.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29246.3, self.close=29239.8, self.high=29250.8, self.low=29221.6 
127.0.0.1 - - [04/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 00:20:03,986:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29246.3, self.close=29239.8, self.high=29250.8, self.low=29221.6   
2023-08-04 00:20:05,149:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230803   235500    235959  1691078399  ...  29243.1 -0.000297   1727    5
1440  20230804   000000    000459  1691078699  ...  29202.0 -0.001296   1440    0
1441  20230804   000500    000959  1691078999  ...  29203.0  0.000397   1441    1
1442  20230804   001000    001459  1691079299  ...  29213.1  0.000969   1442    2
1443  20230804   001500    001959  1691079599  ...  29221.6 -0.000222   1443    3

[5 rows x 11 columns]
2023-08-04 00:20:05,158:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=12, self.factor=0.535764980359155, self.count=23491 

self.closeSec=1691079899, self.tradeDate='20230804', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29239.9, self.close=29267.1, self.high=29267.1, self.low=29239.8 
2023-08-04 00:25:00,781:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691079899, self.tradeDate='20230804', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29239.9, self.close=29267.1, self.high=29267.1, self.low=29239.8   
2023-08-04 00:25:00,804:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230804   000000    000459  1691078699  ...  29202.0 -0.001296   1440    0
1441  20230804   000500    000959  1691078999  ...  29203.0  0.000397   1441    1
1442  20230804   001000    001459  1691079299  ...  29213.1  0.000969   1442    2
1443  20230804   001500    001959  1691079599  ...  29221.6 -0.000222   1443    3
1444  20230804   002000    002459  1691079899  ...  29239.8  0.000934   1444    4

[5 rows x 11 columns]
2023-08-04 00:25:00,804:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-04 00:00:17,705:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230803    212959  29097.2  ...  46.250000  0.481953  0.601674
5803  20230803    215959  29145.8  ...  46.666667  0.492083  0.580070
5804  20230803    222959  29184.9  ...  46.666667  0.494969  0.557556
5805  20230803    225959  29196.0  ...  47.083333  0.538873  0.528640
5806  20230803    232959  29380.0  ...  46.666667  0.503397  0.521751

[5 rows x 33 columns]
0.5496323529411765
acc is : 0.5496323529411765
2023-08-04 00:00:17,770:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.499742  0.500258       1  ...  0.980703   1.0    0.0  0.976054
540     0  0.504284  0.495716       1  ...  0.981079   1.0    0.0  0.976429
541     0  0.502500  0.497500       1  ...  0.987259   1.0    0.0  0.982579
542     0  0.560834  0.439166       0  ...  0.982350   1.0    0.0  0.977693
543     1  0.472413  0.527587       1  ...  0.982699   1.0    0.0  0.978041

[5 rows x 10 columns]
2023-08-04 00:00:17,781:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500043  0.499957       1  ...  0.980703   1.0    0.0  0.976476
46     0  0.504258  0.495742       1  ...  0.981079   1.0    0.0  0.976194
47     0  0.502760  0.497240       1  ...  0.987259   1.0    0.0  0.982343
48     0  0.560953  0.439047       0  ...  0.982350   1.0    0.0  0.978046
49     1  0.472413  0.527587       1  ...  0.982699   1.0    0.0  0.978041

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '2688.1259737242', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29243.22593407', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [04/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-04 00:00:04,184:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42800F1691078403478I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691078403900150, 'quantity': '24.918', 'price': '29242.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691078402589, 'updatetime': 1691078403900, 'tradetype': 'usdt', 'selfid': 42800, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691078403900, 'clientorderid': '42800F1691078403478I0L59', 'price': '29242.5', 'quantity': '24.918', 'commission': '728.664615', 'commissionasset': 'USDT', 'tradetime': 1691078403900, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691078403900}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [04/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11744 

self.closeSec=1691078999, self.tradeDate='20230804', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29244.4', self.close='29218'
2023-08-04 00:10:01,117:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691078999, self.tradeDate='20230804', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29244.4', self.close='29218'
2023-08-04 00:10:01,126:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230803   232000    232959  1691076599  29303.6  29233.9 -0.002379
573  20230803   233000    233959  1691077199  29233.9  29271.9  0.001300
574  20230803   234000    234959  1691077799    29272  29253.9 -0.000615
575  20230803   235000    235959  1691078399  29253.9  29244.4 -0.000325
576  20230804   000000    000959  1691078999  29244.4    29218 -0.000903
2023-08-04 00:10:01,126:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11745 

self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29218.1', self.close='29239.8'
127.0.0.1 - - [04/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 00:20:06,508:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29218.1', self.close='29239.8'
2023-08-04 00:20:07,050:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230803   233000    233959  1691077199  29233.9  29271.9  0.001300
574  20230803   234000    234959  1691077799    29272  29253.9 -0.000615
575  20230803   235000    235959  1691078399  29253.9  29244.4 -0.000325
576  20230804   000000    000959  1691078999  29244.4    29218 -0.000903
577  20230804   001000    001959  1691079599  29218.1  29239.8  0.000746
2023-08-04 00:20:07,058:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-04 00:00:02,058:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-04 00:00:02,129:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8040000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230803, closeTime:235959, close:29244.4, total:991132.0255179, pct_pre:-0.006183007472128743, thd:0.2557263421436479, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11747 

self.closeSec=1691078999, self.tradeDate='20230804', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29244.4', self.close='29218'
2023-08-04 00:10:01,110:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691078999, self.tradeDate='20230804', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29244.4', self.close='29218'
127.0.0.1 - - [04/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-04 00:10:01,125:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230803   232000    232959  1691076599  29303.6  29233.9
17421  20230803   233000    233959  1691077199  29233.9  29271.9
17422  20230803   234000    234959  1691077799    29272  29253.9
17423  20230803   235000    235959  1691078399  29253.9  29244.4
17424  20230804   000000    000959  1691078999  29244.4    29218
2023-08-04 00:10:01,126:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11748 

self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29218.1', self.close='29239.8'
127.0.0.1 - - [04/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 00:20:08,020:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29218.1', self.close='29239.8'
2023-08-04 00:20:08,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230803   233000    233959  1691077199  29233.9  29271.9
17422  20230803   234000    234959  1691077799    29272  29253.9
17423  20230803   235000    235959  1691078399  29253.9  29244.4
17424  20230804   000000    000959  1691078999  29244.4    29218
17425  20230804   001000    001959  1691079599  29218.1  29239.8
2023-08-04 00:20:08,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [04/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-04 00:00:04,023:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42799F1691078403432I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691078403854609, 'quantity': '37.212', 'price': '29242.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1691078402563, 'updatetime': 1691078403854, 'tradetype': 'usdt', 'selfid': 42799, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691078403854, 'clientorderid': '42799F1691078403432I0L2', 'price': '29242.4', 'quantity': '37.212', 'commission': '1088.1681888', 'commissionasset': 'USDT', 'tradetime': 1691078403854, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691078403854}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11747 

self.closeSec=1691078999, self.tradeDate='20230804', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29244.4', self.close='29218'
127.0.0.1 - - [04/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-04 00:10:01,109:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691078999, self.tradeDate='20230804', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29244.4', self.close='29218'
2023-08-04 00:10:01,118:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230803   232000    232959  1691076599  29303.6  29233.9
12237  20230803   233000    233959  1691077199  29233.9  29271.9
12238  20230803   234000    234959  1691077799    29272  29253.9
12239  20230803   235000    235959  1691078399  29253.9  29244.4
12240  20230804   000000    000959  1691078999  29244.4    29218
2023-08-04 00:10:01,118:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11748 

self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29218.1', self.close='29239.8'
127.0.0.1 - - [04/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 00:20:07,769:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29218.1', self.close='29239.8'
2023-08-04 00:20:08,018:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230803   233000    233959  1691077199  29233.9  29271.9
12238  20230803   234000    234959  1691077799    29272  29253.9
12239  20230803   235000    235959  1691078399  29253.9  29244.4
12240  20230804   000000    000959  1691078999  29244.4    29218
12241  20230804   001000    001959  1691079599  29218.1  29239.8
2023-08-04 00:20:08,019:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23488
self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29246.3, self.close=29239.8, self.high=29250.8, self.low=29221.6, self.vol=837.401, self.amt=24482512.7018 
127.0.0.1 - - [04/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 00:20:05,899:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230803   235500    235959  ...         0.0        0.0       0
5760  20230804   000000    000459  ...         0.0        0.0       0
5761  20230804   000500    000959  ...         0.0        0.0       0
5762  20230804   001000    001459  ...         0.0        0.0       0
5763  20230804   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 00:20:05,929:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691079599, self.tradeDate='20230804', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29246.3, self.close=29239.8, self.high=29250.8, self.low=29221.6, self.vol=837.401, self.amt=24482512.7018, ukdf['pct'].iloc[-1]=-0.000222 , ukdf['amount'].iloc[-1]=24482512.7018, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89264.6794', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29247.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23489
self.closeSec=1691079899, self.tradeDate='20230804', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29239.9, self.close=29267.1, self.high=29267.1, self.low=29239.8, self.vol=2504.362, self.amt=73268135.8442 
2023-08-04 00:25:00,811:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230804   000000    000459  ...         0.0        0.0       0
5761  20230804   000500    000959  ...         0.0        0.0       0
5762  20230804   001000    001459  ...         0.0        0.0       0
5763  20230804   001500    001959  ...         0.0        0.0       0
5764  20230804   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 00:25:00,812:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691079899, self.tradeDate='20230804', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29239.9, self.close=29267.1, self.high=29267.1, self.low=29239.8, self.vol=2504.362, self.amt=73268135.8442, ukdf['pct'].iloc[-1]=0.000934 , ukdf['amount'].iloc[-1]=73268135.8442, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89996.3571', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29267.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230803   120000    155959  1691049599  ...    723  0.370799  0.605461     1.0
724  20230803   160000    195959  1691063999  ...    724  0.409624  0.789930     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '5557.046943357', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29136.25224908', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=489
self.closeSec=1691078399, self.tradeDate='20230803', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29134.1, self.close=29244.4, self.high=29440.0, self.low=29068.0, self.vol=78353.291, self.amt=2291477941.10498 
127.0.0.1 - - [04/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-04 00:00:01,629:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691078399, self.tradeDate='20230803', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29134.1, self.close=29244.4, self.high=29440.0, self.low=29068.0, self.vol=78353.291, self.amt=2291477941.10498 
2023-08-04 00:00:01,649:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230803   040000    075959  ...  23823.330  6.945151e+08  0.000971
722  20230803   080000    115959  ...  24131.103  7.042569e+08  0.000000
723  20230803   120000    155959  ...  28883.917  8.400553e+08 -0.004666
724  20230803   160000    195959  ...  39270.953  1.142696e+09  0.003451
725  20230803   200000    235959  ...  78353.291  2.291478e+09  0.003782

[5 rows x 11 columns]
2023-08-04 00:00:02,489:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230803   040000    075959  1691020799  ...    721  0.304316  0.283613     NaN
722  20230803   080000    115959  1691035199  ...    722  0.332634  0.420824     NaN
723  20230803   120000    155959  1691049599  ...    723  0.370799  0.605461     1.0
724  20230803   160000    195959  1691063999  ...    724  0.409624  0.789930     1.0
725  20230803   200000    235959  1691078399  ...    725  0.426334  0.858964     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '11490.617883059', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29244.57850996', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


