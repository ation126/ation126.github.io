# 20230321 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32668
self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27593.5, self.close=27547.1, self.high=27660.8, self.low=27525.0, self.vol=4602.988, self.amt=127043968.9367 
127.0.0.1 - - [21/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-21 00:20:04,040:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230320   235500    235959  ...         0.0        0.0       0
5760  20230321   000000    000459  ...         0.0        0.0       0
5761  20230321   000500    000959  ...         0.0        0.0       0
5762  20230321   001000    001459  ...         0.0        0.0       0
5763  20230321   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 00:20:04,050:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27593.5, self.close=27547.1, self.high=27660.8, self.low=27525.0, self.vol=4602.988, self.amt=127043968.9367, ukdf['pct'].iloc[-1]=-0.001852 , ukdf['amount'].iloc[-1]=127043968.9367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-663337.23586808688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27552.58562663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32669
self.closeSec=1679329499, self.tradeDate='20230321', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27549.2, self.close=27547.0, self.high=27580.0, self.low=27445.0, self.vol=8379.452, self.amt=230509152.6808 
127.0.0.1 - - [21/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-21 00:25:01,584:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230321   000000    000459  ...         0.0        0.0       0
5761  20230321   000500    000959  ...         0.0        0.0       0
5762  20230321   001000    001459  ...         0.0        0.0       0
5763  20230321   001500    001959  ...         0.0        0.0       0
5764  20230321   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 00:25:01,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679329499, self.tradeDate='20230321', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27549.2, self.close=27547.0, self.high=27580.0, self.low=27445.0, self.vol=8379.452, self.amt=230509152.6808, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=230509152.6808, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-662796.5168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27543.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27593.5, self.close=27547.1, self.high=27660.8, self.low=27525.0 
127.0.0.1 - - [21/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-21 00:20:02,080:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27593.5, self.close=27547.1, self.high=27660.8, self.low=27525.0   
2023-03-21 00:20:02,841:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230320   235500    235959  1679327999  ...  27570.0 -0.007110   1727    5
1440  20230321   000000    000459  1679328299  ...  27656.3  0.001438   1440    0
1441  20230321   000500    000959  1679328599  ...  27593.2 -0.004452   1441    1
1442  20230321   001000    001459  1679328899  ...  27529.3  0.000076   1442    2
1443  20230321   001500    001959  1679329199  ...  27525.0 -0.001852   1443    3

[5 rows x 11 columns]
2023-03-21 00:20:02,841:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=156, self.factor=0.3561001830435298, self.count=33235 

self.closeSec=1679329499, self.tradeDate='20230321', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27549.2, self.close=27547.0, self.high=27580.0, self.low=27445.0 
127.0.0.1 - - [21/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-21 00:25:01,545:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679329499, self.tradeDate='20230321', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27549.2, self.close=27547.0, self.high=27580.0, self.low=27445.0   
2023-03-21 00:25:01,578:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230321   000000    000459  1679328299  ...  27656.3  0.001438   1440    0
1441  20230321   000500    000959  1679328599  ...  27593.2 -0.004452   1441    1
1442  20230321   001000    001459  1679328899  ...  27529.3  0.000076   1442    2
1443  20230321   001500    001959  1679329199  ...  27525.0 -0.001852   1443    3
1444  20230321   002000    002459  1679329499  ...  27445.0 -0.000004   1444    4

[5 rows x 11 columns]
2023-03-21 00:25:01,578:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-21 00:00:34,348:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230320    212959  28214.9  ...  50.000000  0.564814  0.323064
5803  20230320    215959  28072.1  ...  50.000000  0.533251  0.334571
5804  20230320    222959  27807.8  ...  50.416667  0.549771  0.336994
5805  20230320    225959  27977.8  ...  50.833333  0.556052  0.335996
5806  20230320    232959  28041.4  ...  50.833333  0.552943  0.336352

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-03-21 00:00:34,501:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.462417  0.537583       0  ...  1.225865   1.0  0.0000  1.282594
540     1  0.383267  0.616733       1  ...  1.216409  -1.0 -0.0016  1.290435
541     0  0.535432  0.464568       1  ...  1.213513  -1.0  0.0000  1.293507
542     0  0.514130  0.485870       0  ...  1.214651  -1.0  0.0000  1.292294
543     1  0.479799  0.520201       0  ...  1.229322  -1.0  0.0000  1.276686

[5 rows x 10 columns]
2023-03-21 00:00:34,540:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.463102  0.536898       0  ...  1.212416   1.0  0.0000  1.280162
46     1  0.382857  0.617143       1  ...  1.216409  -1.0 -0.0016  1.287235
47     0  0.536945  0.463055       1  ...  1.200200  -1.0  0.0000  1.290299
48     0  0.514032  0.485968       0  ...  1.214651  -1.0  0.0000  1.291026
49     1  0.479799  0.520201       0  ...  1.229322  -1.0  0.0000  1.276686

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [21/Mar/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-03-21 00:00:04,560:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42029F1679328003963I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679328004141167, 'quantity': '28.859', 'price': '27685.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679328003373, 'updatetime': 1679328004141, 'tradetype': 'usdt', 'selfid': 42029, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679328004141, 'clientorderid': '42029F1679328003963I0L59', 'price': '27685.8', 'quantity': '28.859', 'commission': '798.9845022', 'commissionasset': 'USDT', 'tradetime': 1679328004141, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679328004141}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16616 

self.closeSec=1679328599, self.tradeDate='20230321', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27679.7', self.close='27596.1'
2023-03-21 00:10:01,622:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679328599, self.tradeDate='20230321', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27679.7', self.close='27596.1'
127.0.0.1 - - [21/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-21 00:10:01,689:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230320   232000    232959  1679326199  27907.7  28018.1  0.003963
573  20230320   233000    233959  1679326799  28018.2  27897.9 -0.004290
574  20230320   234000    234959  1679327399  27897.8  27892.8 -0.000183
575  20230320   235000    235959  1679327999  27892.8  27679.7 -0.007640
576  20230321   000000    000959  1679328599  27679.7  27596.1 -0.003020
2023-03-21 00:10:01,690:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16617 

self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27596', self.close='27547.1'
127.0.0.1 - - [21/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 00:20:03,530:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27596', self.close='27547.1'
2023-03-21 00:20:03,762:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230320   233000    233959  1679326799  28018.2  27897.9 -0.004290
574  20230320   234000    234959  1679327399  27897.8  27892.8 -0.000183
575  20230320   235000    235959  1679327999  27892.8  27679.7 -0.007640
576  20230321   000000    000959  1679328599  27679.7  27596.1 -0.003020
577  20230321   001000    001959  1679329199    27596  27547.1 -0.001776
2023-03-21 00:20:03,763:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-21 00:00:03,619:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42027F1679328003249I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679328003394680, 'quantity': '37.378', 'price': '27685.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679328002878, 'updatetime': 1679328003394, 'tradetype': 'usdt', 'selfid': 42027, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679328003394, 'clientorderid': '42027F1679328003249I0L57', 'price': '27685.7', 'quantity': '37.378', 'commission': '1034.8360946', 'commissionasset': 'USDT', 'tradetime': 1679328003394, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679328003394}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16617 

self.closeSec=1679328599, self.tradeDate='20230321', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27679.7', self.close='27596.1'
2023-03-21 00:10:01,678:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679328599, self.tradeDate='20230321', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27679.7', self.close='27596.1'
2023-03-21 00:10:01,706:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230320   232000    232959  1679326199  27907.7  28018.1
17421  20230320   233000    233959  1679326799  28018.2  27897.9
17422  20230320   234000    234959  1679327399  27897.8  27892.8
17423  20230320   235000    235959  1679327999  27892.8  27679.7
17424  20230321   000000    000959  1679328599  27679.7  27596.1
2023-03-21 00:10:01,706:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16618 

self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27596', self.close='27547.1'
127.0.0.1 - - [21/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 00:20:04,471:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27596', self.close='27547.1'
2023-03-21 00:20:04,507:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230320   233000    233959  1679326799  28018.2  27897.9
17422  20230320   234000    234959  1679327399  27897.8  27892.8
17423  20230320   235000    235959  1679327999  27892.8  27679.7
17424  20230321   000000    000959  1679328599  27679.7  27596.1
17425  20230321   001000    001959  1679329199    27596  27547.1
2023-03-21 00:20:04,508:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [21/Mar/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-03-21 00:00:04,350:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42028F1679328003864I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679328004109724, 'quantity': '38.717', 'price': '27685.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679328003094, 'updatetime': 1679328004109, 'tradetype': 'usdt', 'selfid': 42028, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679328004109, 'clientorderid': '42028F1679328003864I0L2', 'price': '27685.8', 'quantity': '38.717', 'commission': '1071.9111186', 'commissionasset': 'USDT', 'tradetime': 1679328004109, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679328004109}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16617 

self.closeSec=1679328599, self.tradeDate='20230321', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27679.7', self.close='27596.1'
2023-03-21 00:10:01,675:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679328599, self.tradeDate='20230321', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27679.7', self.close='27596.1'
2023-03-21 00:10:01,702:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230320   232000    232959  1679326199  27907.7  28018.1
12237  20230320   233000    233959  1679326799  28018.2  27897.9
12238  20230320   234000    234959  1679327399  27897.8  27892.8
12239  20230320   235000    235959  1679327999  27892.8  27679.7
12240  20230321   000000    000959  1679328599  27679.7  27596.1
2023-03-21 00:10:01,702:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16618 

self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27596', self.close='27547.1'
127.0.0.1 - - [21/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-21 00:20:04,249:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27596', self.close='27547.1'
2023-03-21 00:20:04,403:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230320   233000    233959  1679326799  28018.2  27897.9
12238  20230320   234000    234959  1679327399  27897.8  27892.8
12239  20230320   235000    235959  1679327999  27892.8  27679.7
12240  20230321   000000    000959  1679328599  27679.7  27596.1
12241  20230321   001000    001959  1679329199    27596  27547.1
2023-03-21 00:20:04,403:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28666
self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27593.5, self.close=27547.1, self.high=27660.8, self.low=27525.0, self.vol=4602.988, self.amt=127043968.9367 
127.0.0.1 - - [21/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-21 00:20:01,712:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230320   235500    235959  ...         0.0        0.0       0
5760  20230321   000000    000459  ...         0.0        0.0       0
5761  20230321   000500    000959  ...         0.0        0.0       0
5762  20230321   001000    001459  ...         0.0        0.0       0
5763  20230321   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 00:20:01,717:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679329199, self.tradeDate='20230321', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27593.5, self.close=27547.1, self.high=27660.8, self.low=27525.0, self.vol=4602.988, self.amt=127043968.9367, ukdf['pct'].iloc[-1]=-0.001852 , ukdf['amount'].iloc[-1]=127043968.9367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [21/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28667
self.closeSec=1679329499, self.tradeDate='20230321', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27549.2, self.close=27547.0, self.high=27580.0, self.low=27445.0, self.vol=8379.452, self.amt=230509152.6808 
2023-03-21 00:25:01,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230321   000000    000459  ...         0.0        0.0       0
5761  20230321   000500    000959  ...         0.0        0.0       0
5762  20230321   001000    001459  ...         0.0        0.0       0
5763  20230321   001500    001959  ...         0.0        0.0       0
5764  20230321   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-21 00:25:01,572:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679329499, self.tradeDate='20230321', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27549.2, self.close=27547.0, self.high=27580.0, self.low=27445.0, self.vol=8379.452, self.amt=230509152.6808, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=230509152.6808, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230320   120000    155959  1679299199  ...    723  0.997496  0.896116     1.0
724  20230320   160000    195959  1679313599  ...    724  0.958243  0.773173     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '41776.9498636182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28176.59540596', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [21/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=692
self.closeSec=1679327999, self.tradeDate='20230320', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28176.8, self.close=27679.7, self.high=28254.3, self.low=27570.0, self.vol=185779.965, self.amt=5191857456.67352 
2023-03-21 00:00:02,441:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679327999, self.tradeDate='20230320', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28176.8, self.close=27679.7, self.high=28254.3, self.low=27570.0, self.vol=185779.965, self.amt=5191857456.67352 
2023-03-21 00:00:02,482:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230320   040000    075959  ...  146620.436  4.111874e+09 -0.010253
722  20230320   080000    115959  ...  154695.612  4.262960e+09 -0.024732
723  20230320   120000    155959  ...  139390.542  3.864202e+09  0.033164
724  20230320   160000    195959  ...  202307.208  5.701327e+09  0.000295
725  20230320   200000    235959  ...  185779.965  5.191857e+09 -0.017642

[5 rows x 11 columns]
2023-03-21 00:00:04,941:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230320   040000    075959  1679270399  ...    721  1.027322  1.009618     1.0
722  20230320   080000    115959  1679284799  ...    722  1.020162  0.973997     1.0
723  20230320   120000    155959  1679299199  ...    723  0.997496  0.896116     1.0
724  20230320   160000    195959  1679313599  ...    724  0.958243  0.773173     1.0
725  20230320   200000    235959  1679327999  ...    725  0.950938  0.740984     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '15408.3052970567', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27686.42634626', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


