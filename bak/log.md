# 20230325 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33820
self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27992.4, self.close=27952.4, self.high=27995.0, self.low=27936.0, self.vol=1321.935, self.amt=36964519.1708 
127.0.0.1 - - [25/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-25 00:20:08,085:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230324   235500    235959  ...         0.0        0.0       0
5760  20230325   000000    000459  ...         0.0        0.0       0
5761  20230325   000500    000959  ...         0.0        0.0       0
5762  20230325   001000    001459  ...         0.0        0.0       0
5763  20230325   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 00:20:08,104:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27992.4, self.close=27952.4, self.high=27995.0, self.low=27936.0, self.vol=1321.935, self.amt=36964519.1708, ukdf['pct'].iloc[-1]=-0.001368 , ukdf['amount'].iloc[-1]=36964519.1708, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-687546.9056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27954.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33821
self.closeSec=1679675099, self.tradeDate='20230325', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27952.4, self.close=27972.0, self.high=27983.9, self.low=27951.9, self.vol=1096.372, self.amt=30663818.4918 
2023-03-25 00:25:01,622:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230325   000000    000459  ...         0.0        0.0       0
5761  20230325   000500    000959  ...         0.0        0.0       0
5762  20230325   001000    001459  ...         0.0        0.0       0
5763  20230325   001500    001959  ...         0.0        0.0       0
5764  20230325   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 00:25:01,622:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679675099, self.tradeDate='20230325', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27952.4, self.close=27972.0, self.high=27983.9, self.low=27951.9, self.vol=1096.372, self.amt=30663818.4918, ukdf['pct'].iloc[-1]=0.000701 , ukdf['amount'].iloc[-1]=30663818.4918, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-688603.955305412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27972.46596825', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27992.4, self.close=27952.4, self.high=27995.0, self.low=27936.0 
127.0.0.1 - - [25/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-25 00:20:06,435:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27992.4, self.close=27952.4, self.high=27995.0, self.low=27936.0   
2023-03-25 00:20:07,575:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230324   235500    235959  1679673599  ...  27989.0 -0.000710   1727    5
1440  20230325   000000    000459  1679673899  ...  27965.6 -0.000947   1440    0
1441  20230325   000500    000959  1679674199  ...  27903.5 -0.002181   1441    1
1442  20230325   001000    001459  1679674499  ...  27909.7  0.002902   1442    2
1443  20230325   001500    001959  1679674799  ...  27936.0 -0.001368   1443    3

[5 rows x 11 columns]
2023-03-25 00:20:07,576:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=348, self.factor=0.43843180953223687, self.count=34387 

self.closeSec=1679675099, self.tradeDate='20230325', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27952.4, self.close=27972.0, self.high=27983.9, self.low=27951.9 
2023-03-25 00:25:01,556:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679675099, self.tradeDate='20230325', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27952.4, self.close=27972.0, self.high=27983.9, self.low=27951.9   
2023-03-25 00:25:01,597:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230325   000000    000459  1679673899  ...  27965.6 -0.000947   1440    0
1441  20230325   000500    000959  1679674199  ...  27903.5 -0.002181   1441    1
1442  20230325   001000    001459  1679674499  ...  27909.7  0.002902   1442    2
1443  20230325   001500    001959  1679674799  ...  27936.0 -0.001368   1443    3
1444  20230325   002000    002459  1679675099  ...  27951.9  0.000701   1444    4

[5 rows x 11 columns]
2023-03-25 00:25:01,597:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-25 00:00:35,843:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230324    212959  27965.6  ...  51.666667  0.491814  0.466059
5803  20230324    215959  27885.5  ...  52.083333  0.499026  0.463292
5804  20230324    222959  27963.9  ...  52.083333  0.510520  0.453413
5805  20230324    225959  28087.6  ...  52.083333  0.499875  0.450830
5806  20230324    232959  27976.6  ...  51.666667  0.497265  0.450056

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-03-25 00:00:36,040:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490007  0.509993       1  ...  1.072739   1.0    0.0  1.245519
540     0  0.541325  0.458675       1  ...  1.077492   1.0    0.0  1.251038
541     0  0.612198  0.387802       0  ...  1.073168   1.0    0.0  1.246018
542     1  0.492133  0.507867       0  ...  1.072102   1.0    0.0  1.244780
543     0  0.516885  0.483115       1  ...  1.074016   1.0    0.0  1.247002

[5 rows x 10 columns]
2023-03-25 00:00:36,068:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490199  0.509801       1  ...  1.085725   1.0    0.0  1.252824
46     0  0.541213  0.458787       1  ...  1.077492   1.0    0.0  1.255444
47     0  0.612252  0.387748       0  ...  1.073168   1.0    0.0  1.250407
48     1  0.492002  0.507998       0  ...  1.086647   1.0    0.0  1.250013
49     0  0.516885  0.483115       1  ...  1.074016   1.0    0.0  1.247002

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-25 00:00:03,534:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42051F1679673602827I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679673602941368, 'quantity': '26.683', 'price': '27998', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679673602434, 'updatetime': 1679673602941, 'tradetype': 'usdt', 'selfid': 42051, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679673602941, 'clientorderid': '42051F1679673602827I0L59', 'price': '27998', 'quantity': '26.683', 'commission': '747.070634', 'commissionasset': 'USDT', 'tradetime': 1679673602941, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679673602941}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17192 

self.closeSec=1679674199, self.tradeDate='20230325', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27997.2', self.close='27909.7'
2023-03-25 00:10:01,619:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679674199, self.tradeDate='20230325', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27997.2', self.close='27909.7'
2023-03-25 00:10:01,671:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230324   232000    232959  1679671799  27890.9  27947.3  0.002094
573  20230324   233000    233959  1679672399  27959.3  27959.7  0.000444
574  20230324   234000    234959  1679672999  27959.6  27997.2  0.001341
575  20230324   235000    235959  1679673599  27997.3  27997.2  0.000000
576  20230325   000000    000959  1679674199  27997.2  27909.7 -0.003125
2023-03-25 00:10:01,671:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17193 

self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27909.7', self.close='27952.4'
127.0.0.1 - - [25/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 00:20:07,345:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27909.7', self.close='27952.4'
2023-03-25 00:20:08,058:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230324   233000    233959  1679672399  27959.3  27959.7  0.000444
574  20230324   234000    234959  1679672999  27959.6  27997.2  0.001341
575  20230324   235000    235959  1679673599  27997.3  27997.2  0.000000
576  20230325   000000    000959  1679674199  27997.2  27909.7 -0.003125
577  20230325   001000    001959  1679674799  27909.7  27952.4  0.001530
2023-03-25 00:20:08,058:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-25 00:00:02,092:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-25 00:00:02,206:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3250000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230324, closeTime:235959, close:27997.2, total:1055364.7473673, pct_pre:-0.017739680181111606, thd:0.40404618647771773, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17193 

self.closeSec=1679674199, self.tradeDate='20230325', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27997.2', self.close='27909.7'
127.0.0.1 - - [25/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-25 00:10:01,632:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679674199, self.tradeDate='20230325', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27997.2', self.close='27909.7'
2023-03-25 00:10:01,691:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230324   232000    232959  1679671799  27890.9  27947.3
17421  20230324   233000    233959  1679672399  27959.3  27959.7
17422  20230324   234000    234959  1679672999  27959.6  27997.2
17423  20230324   235000    235959  1679673599  27997.3  27997.2
17424  20230325   000000    000959  1679674199  27997.2  27909.7
2023-03-25 00:10:01,691:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17194 

self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27909.7', self.close='27952.4'
127.0.0.1 - - [25/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 00:20:09,947:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27909.7', self.close='27952.4'
2023-03-25 00:20:10,055:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230324   233000    233959  1679672399  27959.3  27959.7
17422  20230324   234000    234959  1679672999  27959.6  27997.2
17423  20230324   235000    235959  1679673599  27997.3  27997.2
17424  20230325   000000    000959  1679674199  27997.2  27909.7
17425  20230325   001000    001959  1679674799  27909.7  27952.4
2023-03-25 00:20:10,056:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-25 00:00:03,201:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42050F1679673602805I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679673602921423, 'quantity': '41.656', 'price': '27998', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679673602433, 'updatetime': 1679673602921, 'tradetype': 'usdt', 'selfid': 42050, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679673602921, 'clientorderid': '42050F1679673602805I0L2', 'price': '27998', 'quantity': '41.656', 'commission': '1166.284688', 'commissionasset': 'USDT', 'tradetime': 1679673602921, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679673602921}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17193 

self.closeSec=1679674199, self.tradeDate='20230325', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27997.2', self.close='27909.7'
127.0.0.1 - - [25/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-25 00:10:01,628:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679674199, self.tradeDate='20230325', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27997.2', self.close='27909.7'
2023-03-25 00:10:01,679:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230324   232000    232959  1679671799  27890.9  27947.3
12237  20230324   233000    233959  1679672399  27959.3  27959.7
12238  20230324   234000    234959  1679672999  27959.6  27997.2
12239  20230324   235000    235959  1679673599  27997.3  27997.2
12240  20230325   000000    000959  1679674199  27997.2  27909.7
2023-03-25 00:10:01,680:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17194 

self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27909.7', self.close='27952.4'
127.0.0.1 - - [25/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 00:20:09,524:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27909.7', self.close='27952.4'
2023-03-25 00:20:09,780:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230324   233000    233959  1679672399  27959.3  27959.7
12238  20230324   234000    234959  1679672999  27959.6  27997.2
12239  20230324   235000    235959  1679673599  27997.3  27997.2
12240  20230325   000000    000959  1679674199  27997.2  27909.7
12241  20230325   001000    001959  1679674799  27909.7  27952.4
2023-03-25 00:20:09,780:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29818
self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27992.4, self.close=27952.4, self.high=27995.0, self.low=27936.0, self.vol=1321.935, self.amt=36964519.1708 
127.0.0.1 - - [25/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-25 00:20:06,305:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230324   235500    235959  ...         0.0        0.0       0
5760  20230325   000000    000459  ...         0.0        0.0       0
5761  20230325   000500    000959  ...         0.0        0.0       0
5762  20230325   001000    001459  ...         0.0        0.0       0
5763  20230325   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 00:20:06,326:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679674799, self.tradeDate='20230325', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27992.4, self.close=27952.4, self.high=27995.0, self.low=27936.0, self.vol=1321.935, self.amt=36964519.1708, ukdf['pct'].iloc[-1]=-0.001368 , ukdf['amount'].iloc[-1]=36964519.1708, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [25/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29819
self.closeSec=1679675099, self.tradeDate='20230325', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27952.4, self.close=27972.0, self.high=27983.9, self.low=27951.9, self.vol=1096.372, self.amt=30663818.4918 
2023-03-25 00:25:01,617:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230325   000000    000459  ...         0.0        0.0       0
5761  20230325   000500    000959  ...         0.0        0.0       0
5762  20230325   001000    001459  ...         0.0        0.0       0
5763  20230325   001500    001959  ...         0.0        0.0       0
5764  20230325   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 00:25:01,621:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679675099, self.tradeDate='20230325', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27952.4, self.close=27972.0, self.high=27983.9, self.low=27951.9, self.vol=1096.372, self.amt=30663818.4918, ukdf['pct'].iloc[-1]=0.000701 , ukdf['amount'].iloc[-1]=30663818.4918, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230324   120000    155959  1679644799  ...    723  0.015430 -2.159293    -1.0
724  20230324   160000    195959  1679659199  ...    724  0.016784 -2.093610    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '28641.4098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27557.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [25/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=716
self.closeSec=1679673599, self.tradeDate='20230324', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27558.4, self.close=27997.2, self.high=28260.0, self.low=27523.0, self.vol=208669.32, self.amt=5828416920.05298 
2023-03-25 00:00:01,941:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679673599, self.tradeDate='20230324', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27558.4, self.close=27997.2, self.high=28260.0, self.low=27523.0, self.vol=208669.32, self.amt=5828416920.05298 
2023-03-25 00:00:01,988:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230324   040000    075959  ...   89487.014  2.524258e+09 -0.002764
722  20230324   080000    115959  ...   44984.892  1.270352e+09 -0.002574
723  20230324   120000    155959  ...   45073.281  1.272364e+09  0.002077
724  20230324   160000    195959  ...  143929.417  4.016502e+09 -0.024567
725  20230324   200000    235959  ...  208669.320  5.828417e+09  0.015296

[5 rows x 11 columns]
2023-03-25 00:00:05,067:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230324   040000    075959  1679615999  ...    721  0.017394 -2.254048    -1.0
722  20230324   080000    115959  1679630399  ...    722  0.016544 -2.211430    -1.0
723  20230324   120000    155959  1679644799  ...    723  0.015430 -2.159293    -1.0
724  20230324   160000    195959  1679659199  ...    724  0.016784 -2.093610    -1.0
725  20230324   200000    235959  1679673599  ...    725  0.014419 -2.039357    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '4820.70639705408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28001.33896032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


