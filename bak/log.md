# 20230601 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5056
self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26952.4, self.close=26951.2, self.high=26957.3, self.low=26935.5, self.vol=1190.598, self.amt=32084195.5173 
127.0.0.1 - - [01/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 00:20:06,913:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230531   235500    235959  ...         0.0        0.0       0
5760  20230601   000000    000459  ...         0.0        0.0       0
5761  20230601   000500    000959  ...         0.0        0.0       0
5762  20230601   001000    001459  ...         0.0        0.0       0
5763  20230601   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 00:20:06,931:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26952.4, self.close=26951.2, self.high=26957.3, self.low=26935.5, self.vol=1190.598, self.amt=32084195.5173, ukdf['pct'].iloc[-1]=-4.8e-05 , ukdf['amount'].iloc[-1]=32084195.5173, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1250.5548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26954.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5057
self.closeSec=1685550299, self.tradeDate='20230601', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26951.1, self.close=26937.5, self.high=26954.7, self.low=26908.2, self.vol=1449.617, self.amt=39036007.2285 
2023-06-01 00:25:00,837:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230601   000000    000459  ...         0.0        0.0       0
5761  20230601   000500    000959  ...         0.0        0.0       0
5762  20230601   001000    001459  ...         0.0        0.0       0
5763  20230601   001500    001959  ...         0.0        0.0       0
5764  20230601   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 00:25:00,839:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685550299, self.tradeDate='20230601', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26951.1, self.close=26937.5, self.high=26954.7, self.low=26908.2, self.vol=1449.617, self.amt=39036007.2285, ukdf['pct'].iloc[-1]=-0.000508 , ukdf['amount'].iloc[-1]=39036007.2285, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-931.78417276428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26931.80967778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26952.4, self.close=26951.2, self.high=26957.3, self.low=26935.5 
127.0.0.1 - - [01/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 00:20:04,650:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26952.4, self.close=26951.2, self.high=26957.3, self.low=26935.5   
2023-06-01 00:20:06,030:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230531   235500    235959  1685548799  ...  26878.7 -0.000966   1727    5
1440  20230601   000000    000459  1685549099  ...  26891.1 -0.000100   1440    0
1441  20230601   000500    000959  1685549399  ...  26826.0  0.000877   1441    1
1442  20230601   001000    001459  1685549699  ...  26912.1  0.001170   1442    2
1443  20230601   001500    001959  1685549999  ...  26935.5 -0.000048   1443    3

[5 rows x 11 columns]
2023-06-01 00:20:06,031:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7248978885957953, self.count=5059 

self.closeSec=1685550299, self.tradeDate='20230601', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26951.1, self.close=26937.5, self.high=26954.7, self.low=26908.2 
2023-06-01 00:25:00,737:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685550299, self.tradeDate='20230601', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26951.1, self.close=26937.5, self.high=26954.7, self.low=26908.2   
2023-06-01 00:25:00,789:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230601   000000    000459  1685549099  ...  26891.1 -0.000100   1440    0
1441  20230601   000500    000959  1685549399  ...  26826.0  0.000877   1441    1
1442  20230601   001000    001459  1685549699  ...  26912.1  0.001170   1442    2
1443  20230601   001500    001959  1685549999  ...  26935.5 -0.000048   1443    3
1444  20230601   002000    002459  1685550299  ...  26908.2 -0.000508   1444    4

[5 rows x 11 columns]
2023-06-01 00:25:00,789:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-01 00:00:33,444:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230531    212959  27064.1  ...  49.166667  0.415346  0.776767
5803  20230531    215959  27145.5  ...  48.750000  0.407652  0.779679
5804  20230531    222959  27103.9  ...  48.333333  0.370619  0.790725
5805  20230531    225959  26890.8  ...  48.750000  0.404669  0.792353
5806  20230531    232959  27022.9  ...  48.333333  0.389327  0.800071

[5 rows x 33 columns]
0.5220588235294118
acc is : 0.5220588235294118
2023-06-01 00:00:33,593:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.529349  0.470651       0  ...  1.026537  -1.0    0.0  1.009806
540     0  0.500935  0.499065       0  ...  1.034646  -1.0    0.0  1.001829
541     1  0.455143  0.544857       1  ...  1.029563  -1.0    0.0  1.006751
542     0  0.526147  0.473853       0  ...  1.033156  -1.0    0.0  1.003237
543     1  0.481211  0.518789       0  ...  1.034253  -1.0    0.0  1.002172

[5 rows x 10 columns]
2023-06-01 00:00:33,617:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.529872  0.470128       0  ...  1.026537  -1.0    0.0  1.009535
46     0  0.501501  0.498499       0  ...  1.034646  -1.0    0.0  1.001874
47     1  0.455743  0.544257       1  ...  1.029563  -1.0    0.0  1.006796
48     0  0.526258  0.473742       0  ...  1.033156  -1.0    0.0  1.003529
49     1  0.481211  0.518789       0  ...  1.034253  -1.0    0.0  1.002172

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '26570.1871', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26907.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-06-01 00:00:04,430:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42295F1685548803766I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685548804135333, 'quantity': '25.138', 'price': '26897', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685548802847, 'updatetime': 1685548804135, 'tradetype': 'usdt', 'selfid': 42295, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685548804135, 'clientorderid': '42295F1685548803766I0L59', 'price': '26897', 'quantity': '25.138', 'commission': '676.136786', 'commissionasset': 'USDT', 'tradetime': 1685548804135, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685548804135}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2528 

self.closeSec=1685549399, self.tradeDate='20230601', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26900', self.close='26921'
2023-06-01 00:10:01,123:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685549399, self.tradeDate='20230601', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26900', self.close='26921'
2023-06-01 00:10:01,164:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230531   232000    232959  1685546999  26939.3  26928.7 -0.000397
573  20230531   233000    233959  1685547599  26928.6  26919.2 -0.000353
574  20230531   234000    234959  1685548199  26919.1  26893.5 -0.000955
575  20230531   235000    235959  1685548799  26893.5  26900.1  0.000245
576  20230601   000000    000959  1685549399    26900    26921  0.000777
2023-06-01 00:10:01,164:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2529 

self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26921.6', self.close='26951.2'
127.0.0.1 - - [01/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 00:20:07,031:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26921.6', self.close='26951.2'
2023-06-01 00:20:07,820:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230531   233000    233959  1685547599  26928.6  26919.2 -0.000353
574  20230531   234000    234959  1685548199  26919.1  26893.5 -0.000955
575  20230531   235000    235959  1685548799  26893.5  26900.1  0.000245
576  20230601   000000    000959  1685549399    26900    26921  0.000777
577  20230601   001000    001959  1685549999  26921.6  26951.2  0.001122
2023-06-01 00:20:07,821:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-01 00:00:02,315:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-01 00:00:02,438:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6010000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230531, closeTime:235959, close:26900.1, total:971927.4245254, pct_pre:-0.02071936419211462, thd:-0.39212359412460684, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2531 

self.closeSec=1685549399, self.tradeDate='20230601', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26900', self.close='26921'
2023-06-01 00:10:01,117:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685549399, self.tradeDate='20230601', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26900', self.close='26921'
127.0.0.1 - - [01/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-01 00:10:01,128:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230531   232000    232959  1685546999  26939.3  26928.7
17421  20230531   233000    233959  1685547599  26928.6  26919.2
17422  20230531   234000    234959  1685548199  26919.1  26893.5
17423  20230531   235000    235959  1685548799  26893.5  26900.1
17424  20230601   000000    000959  1685549399    26900    26921
2023-06-01 00:10:01,128:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2532 

self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26921.6', self.close='26951.2'
127.0.0.1 - - [01/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 00:20:08,918:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26921.6', self.close='26951.2'
2023-06-01 00:20:09,086:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230531   233000    233959  1685547599  26928.6  26919.2
17422  20230531   234000    234959  1685548199  26919.1  26893.5
17423  20230531   235000    235959  1685548799  26893.5  26900.1
17424  20230601   000000    000959  1685549399    26900    26921
17425  20230601   001000    001959  1685549999  26921.6  26951.2
2023-06-01 00:20:09,087:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-06-01 00:00:04,637:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42296F1685548803848I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685548804221222, 'quantity': '44.644', 'price': '26897', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685548802999, 'updatetime': 1685548804221, 'tradetype': 'usdt', 'selfid': 42296, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685548804221, 'clientorderid': '42296F1685548803848I0L2', 'price': '26897', 'quantity': '44.644', 'commission': '1200.789668', 'commissionasset': 'USDT', 'tradetime': 1685548804221, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685548804221}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2531 

self.closeSec=1685549399, self.tradeDate='20230601', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26900', self.close='26921'
2023-06-01 00:10:01,133:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685549399, self.tradeDate='20230601', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26900', self.close='26921'
2023-06-01 00:10:01,172:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230531   232000    232959  1685546999  26939.3  26928.7
12237  20230531   233000    233959  1685547599  26928.6  26919.2
12238  20230531   234000    234959  1685548199  26919.1  26893.5
12239  20230531   235000    235959  1685548799  26893.5  26900.1
12240  20230601   000000    000959  1685549399    26900    26921
2023-06-01 00:10:01,172:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2532 

self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26921.6', self.close='26951.2'
127.0.0.1 - - [01/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 00:20:08,660:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26921.6', self.close='26951.2'
2023-06-01 00:20:08,936:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230531   233000    233959  1685547599  26928.6  26919.2
12238  20230531   234000    234959  1685548199  26919.1  26893.5
12239  20230531   235000    235959  1685548799  26893.5  26900.1
12240  20230601   000000    000959  1685549399    26900    26921
12241  20230601   001000    001959  1685549999  26921.6  26951.2
2023-06-01 00:20:08,936:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5056
self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26952.4, self.close=26951.2, self.high=26957.3, self.low=26935.5, self.vol=1190.598, self.amt=32084195.5173 
127.0.0.1 - - [01/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 00:20:06,940:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230531   235500    235959  ...         0.0        0.0       0
5760  20230601   000000    000459  ...         0.0        0.0       0
5761  20230601   000500    000959  ...         0.0        0.0       0
5762  20230601   001000    001459  ...         0.0        0.0       0
5763  20230601   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 00:20:06,970:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685549999, self.tradeDate='20230601', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26952.4, self.close=26951.2, self.high=26957.3, self.low=26935.5, self.vol=1190.598, self.amt=32084195.5173, ukdf['pct'].iloc[-1]=-4.8e-05 , ukdf['amount'].iloc[-1]=32084195.5173, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '4033.5126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26952.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5057
self.closeSec=1685550299, self.tradeDate='20230601', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26951.1, self.close=26937.5, self.high=26954.7, self.low=26908.2, self.vol=1449.617, self.amt=39036007.2285 
127.0.0.1 - - [01/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-01 00:25:00,833:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230601   000000    000459  ...         0.0        0.0       0
5761  20230601   000500    000959  ...         0.0        0.0       0
5762  20230601   001000    001459  ...         0.0        0.0       0
5763  20230601   001500    001959  ...         0.0        0.0       0
5764  20230601   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 00:25:00,834:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685550299, self.tradeDate='20230601', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26951.1, self.close=26937.5, self.high=26954.7, self.low=26908.2, self.vol=1449.617, self.amt=39036007.2285, ukdf['pct'].iloc[-1]=-0.000508 , ukdf['amount'].iloc[-1]=39036007.2285, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '3261.33924242698', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26931.80967778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230531   120000    155959  1685519999  ...    723  1.026520  1.580231     1.0
724  20230531   160000    195959  1685534399  ...    724  0.979737  1.406118     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '52766.70151369509', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27083.27070741', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=105127.0.0.1 - - [01/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -

self.closeSec=1685548799, self.tradeDate='20230531', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27087.9, self.close=26900.1, self.high=27219.6, self.low=26835.5, self.vol=119487.274, self.amt=3226958258.24778 
2023-06-01 00:00:01,847:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685548799, self.tradeDate='20230531', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27087.9, self.close=26900.1, self.high=27219.6, self.low=26835.5, self.vol=119487.274, self.amt=3226958258.24778 
2023-06-01 00:00:01,871:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230531   040000    075959  ...   29233.913  8.106674e+08 -0.005547
722  20230531   080000    115959  ...   39039.737  1.080384e+09 -0.001214
723  20230531   120000    155959  ...  156776.296  4.265625e+09 -0.017944
724  20230531   160000    195959  ...   56728.662  1.536835e+09 -0.002302
725  20230531   200000    235959  ...  119487.274  3.226958e+09 -0.006933

[5 rows x 11 columns]
2023-06-01 00:00:03,743:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230531   040000    075959  1685491199  ...    721  1.202865  2.249407     1.0
722  20230531   080000    115959  1685505599  ...    722  1.168339  2.062901     1.0
723  20230531   120000    155959  1685519999  ...    723  1.026520  1.580231     1.0
724  20230531   160000    195959  1685534399  ...    724  0.979737  1.406118     1.0
725  20230531   200000    235959  1685548799  ...    725  0.890645  1.114161     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '42475.4312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26897', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


