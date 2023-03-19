# 20230320 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32380
self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27526.2, self.close=27618.4, self.high=27649.6, self.low=27512.7, self.vol=4838.523, self.amt=133422522.1683 
127.0.0.1 - - [20/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 00:20:04,265:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230319   235500    235959  ...         0.0        0.0       0
5760  20230320   000000    000459  ...         0.0        0.0       0
5761  20230320   000500    000959  ...         0.0        0.0       0
5762  20230320   001000    001459  ...         0.0        0.0       0
5763  20230320   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 00:20:04,276:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27526.2, self.close=27618.4, self.high=27649.6, self.low=27512.7, self.vol=4838.523, self.amt=133422522.1683, ukdf['pct'].iloc[-1]=0.00335 , ukdf['amount'].iloc[-1]=133422522.1683, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-667285.6464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27618.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=32381
self.closeSec=1679243099, self.tradeDate='20230320', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27618.3, self.close=27615.1, self.high=27628.0, self.low=27566.0, self.vol=2977.066, self.amt=82173796.7932 
127.0.0.1 - - [20/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-20 00:25:01,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230320   000000    000459  ...         0.0        0.0       0
5761  20230320   000500    000959  ...         0.0        0.0       0
5762  20230320   001000    001459  ...         0.0        0.0       0
5763  20230320   001500    001959  ...         0.0        0.0       0
5764  20230320   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 00:25:01,577:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679243099, self.tradeDate='20230320', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27618.3, self.close=27615.1, self.high=27628.0, self.low=27566.0, self.vol=2977.066, self.amt=82173796.7932, ukdf['pct'].iloc[-1]=-0.000119 , ukdf['amount'].iloc[-1]=82173796.7932, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-666966.7136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27612.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27526.2, self.close=27618.4, self.high=27649.6, self.low=27512.7 
127.0.0.1 - - [20/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 00:20:01,779:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27526.2, self.close=27618.4, self.high=27649.6, self.low=27512.7   
2023-03-20 00:20:02,005:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230319   235500    235959  1679241599  ...  27450.4 -0.001099   1727    5
1440  20230320   000000    000459  1679241899  ...  27456.0  0.003679   1440    0
1441  20230320   000500    000959  1679242199  ...  27535.0 -0.003289   1441    1
1442  20230320   001000    001459  1679242499  ...  27501.1 -0.000672   1442    2
1443  20230320   001500    001959  1679242799  ...  27512.7  0.003350   1443    3

[5 rows x 11 columns]
2023-03-20 00:20:02,006:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=108, self.factor=0.4748611885997266, self.count=32947 

self.closeSec=1679243099, self.tradeDate='20230320', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27618.3, self.close=27615.1, self.high=27628.0, self.low=27566.0 
127.0.0.1 - - [20/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-20 00:25:01,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679243099, self.tradeDate='20230320', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27618.3, self.close=27615.1, self.high=27628.0, self.low=27566.0   
2023-03-20 00:25:01,555:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230320   000000    000459  1679241899  ...  27456.0  0.003679   1440    0
1441  20230320   000500    000959  1679242199  ...  27535.0 -0.003289   1441    1
1442  20230320   001000    001459  1679242499  ...  27501.1 -0.000672   1442    2
1443  20230320   001500    001959  1679242799  ...  27512.7  0.003350   1443    3
1444  20230320   002000    002459  1679243099  ...  27566.0 -0.000119   1444    4

[5 rows x 11 columns]
2023-03-20 00:25:01,555:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-20 00:00:41,103:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230319    212959  27232.0  ...  47.916667  0.546392  0.479678
5803  20230319    215959  27203.1  ...  47.916667  0.541102  0.476485
5804  20230319    222959  27166.8  ...  47.916667  0.560455  0.457242
5805  20230319    225959  27328.7  ...  47.916667  0.558657  0.440499
5806  20230319    232959  27316.5  ...  48.333333  0.576749  0.424168

[5 rows x 33 columns]
0.5441176470588235
acc is : 0.5441176470588235
2023-03-20 00:00:41,302:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.529501  0.470499       0  ...  1.128433   1.0    0.0  1.236984
540     0  0.526242  0.473758       1  ...  1.135154   1.0    0.0  1.244352
541     0  0.592530  0.407470       0  ...  1.134651   1.0    0.0  1.243801
542     0  0.533229  0.466771       1  ...  1.141214   1.0    0.0  1.250995
543     0  0.596291  0.403709       1  ...  1.143694   1.0    0.0  1.253713

[5 rows x 10 columns]
2023-03-20 00:00:41,345:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.529215  0.470785       0  ...  1.128433   1.0    0.0  1.234562
46     0  0.525766  0.474234       1  ...  1.135154   1.0    0.0  1.241362
47     0  0.592916  0.407084       0  ...  1.134651   1.0    0.0  1.240812
48     0  0.532991  0.467009       1  ...  1.141214   1.0    0.0  1.250181
49     0  0.596291  0.403709       1  ...  1.143694   1.0    0.0  1.253713

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-20 00:00:03,683:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42022F1679241603006I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679241603179709, 'quantity': '29.367', 'price': '27529.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679241602495, 'updatetime': 1679241603179, 'tradetype': 'usdt', 'selfid': 42022, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679241603179, 'clientorderid': '42022F1679241603006I0L59', 'price': '27529.8', 'quantity': '29.367', 'commission': '808.4676366', 'commissionasset': 'USDT', 'tradetime': 1679241603179, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679241603179}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16472 

self.closeSec=1679242199, self.tradeDate='20230320', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27533.7', self.close='27544.7'
2023-03-20 00:10:01,879:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679242199, self.tradeDate='20230320', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27533.7', self.close='27544.7'
2023-03-20 00:10:01,932:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230319   232000    232959  1679239799    27496  27474.6 -0.000778
573  20230319   233000    233959  1679240399  27474.6  27505.3  0.001117
574  20230319   234000    234959  1679240999  27505.2  27544.3  0.001418
575  20230319   235000    235959  1679241599  27544.3  27534.3 -0.000363
576  20230320   000000    000959  1679242199  27533.7  27544.7  0.000378
2023-03-20 00:10:01,932:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [20/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16473 

self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27544.7', self.close='27618.4'
2023-03-20 00:20:02,646:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27544.7', self.close='27618.4'
2023-03-20 00:20:03,005:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230319   233000    233959  1679240399  27474.6  27505.3  0.001117
574  20230319   234000    234959  1679240999  27505.2  27544.3  0.001418
575  20230319   235000    235959  1679241599  27544.3  27534.3 -0.000363
576  20230320   000000    000959  1679242199  27533.7  27544.7  0.000378
577  20230320   001000    001959  1679242799  27544.7  27618.4  0.002676
2023-03-20 00:20:03,005:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-20 00:00:02,302:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-20 00:00:02,435:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3200000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230319, closeTime:235959, close:27534.3, total:1054769.6042238, pct_pre:-0.010256185006643381, thd:0.12862241754963866, side:sell 
127.0.0.1 - - [20/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16473 

self.closeSec=1679242199, self.tradeDate='20230320', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27533.7', self.close='27544.7'
2023-03-20 00:10:01,880:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679242199, self.tradeDate='20230320', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27533.7', self.close='27544.7'
2023-03-20 00:10:01,893:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230319   232000    232959  1679239799    27496  27474.6
17421  20230319   233000    233959  1679240399  27474.6  27505.3
17422  20230319   234000    234959  1679240999  27505.2  27544.3
17423  20230319   235000    235959  1679241599  27544.3  27534.3
17424  20230320   000000    000959  1679242199  27533.7  27544.7
2023-03-20 00:10:01,895:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16474 

self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27544.7', self.close='27618.4'
127.0.0.1 - - [20/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 00:20:04,547:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27544.7', self.close='27618.4'
2023-03-20 00:20:04,759:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230319   233000    233959  1679240399  27474.6  27505.3
17422  20230319   234000    234959  1679240999  27505.2  27544.3
17423  20230319   235000    235959  1679241599  27544.3  27534.3
17424  20230320   000000    000959  1679242199  27533.7  27544.7
17425  20230320   001000    001959  1679242799  27544.7  27618.4
2023-03-20 00:20:04,760:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-20 00:00:03,490:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42023F1679241603077I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679241603164178, 'quantity': '41.436', 'price': '27529.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1679241602510, 'updatetime': 1679241603164, 'tradetype': 'usdt', 'selfid': 42023, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679241603164, 'clientorderid': '42023F1679241603077I0L2', 'price': '27529.8', 'quantity': '41.436', 'commission': '1140.7247928', 'commissionasset': 'USDT', 'tradetime': 1679241603164, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679241603164}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16473 

self.closeSec=1679242199, self.tradeDate='20230320', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27533.7', self.close='27544.7'
2023-03-20 00:10:01,902:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679242199, self.tradeDate='20230320', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27533.7', self.close='27544.7'
2023-03-20 00:10:01,939:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230319   232000    232959  1679239799    27496  27474.6
12237  20230319   233000    233959  1679240399  27474.6  27505.3
12238  20230319   234000    234959  1679240999  27505.2  27544.3
12239  20230319   235000    235959  1679241599  27544.3  27534.3
12240  20230320   000000    000959  1679242199  27533.7  27544.7
2023-03-20 00:10:01,939:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16474 

self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27544.7', self.close='27618.4'
127.0.0.1 - - [20/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-20 00:20:03,945:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27544.7', self.close='27618.4'
2023-03-20 00:20:04,355:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230319   233000    233959  1679240399  27474.6  27505.3
12238  20230319   234000    234959  1679240999  27505.2  27544.3
12239  20230319   235000    235959  1679241599  27544.3  27534.3
12240  20230320   000000    000959  1679242199  27533.7  27544.7
12241  20230320   001000    001959  1679242799  27544.7  27618.4
2023-03-20 00:20:04,355:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [20/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28378
self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27526.2, self.close=27618.4, self.high=27649.6, self.low=27512.7, self.vol=4838.523, self.amt=133422522.1683 
2023-03-20 00:20:01,620:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230319   235500    235959  ...         0.0        0.0       0
5760  20230320   000000    000459  ...         0.0        0.0       0
5761  20230320   000500    000959  ...         0.0        0.0       0
5762  20230320   001000    001459  ...         0.0        0.0       0
5763  20230320   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 00:20:01,622:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679242799, self.tradeDate='20230320', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27526.2, self.close=27618.4, self.high=27649.6, self.low=27512.7, self.vol=4838.523, self.amt=133422522.1683, ukdf['pct'].iloc[-1]=0.00335 , ukdf['amount'].iloc[-1]=133422522.1683, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [20/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=28379
self.closeSec=1679243099, self.tradeDate='20230320', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27618.3, self.close=27615.1, self.high=27628.0, self.low=27566.0, self.vol=2977.066, self.amt=82173796.7932 
2023-03-20 00:25:01,626:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230320   000000    000459  ...         0.0        0.0       0
5761  20230320   000500    000959  ...         0.0        0.0       0
5762  20230320   001000    001459  ...         0.0        0.0       0
5763  20230320   001500    001959  ...         0.0        0.0       0
5764  20230320   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-20 00:25:01,627:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679243099, self.tradeDate='20230320', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27618.3, self.close=27615.1, self.high=27628.0, self.low=27566.0, self.vol=2977.066, self.amt=82173796.7932, ukdf['pct'].iloc[-1]=-0.000119 , ukdf['amount'].iloc[-1]=82173796.7932, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230319   120000    155959  1679212799  ...    723  1.010286  1.019974     1.0
724  20230319   160000    195959  1679227199  ...    724  0.969619  0.885534     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '-13018.39', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27158', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1472509.017, self.flagDict['side']='buy', self.tradeCount=26, self.count=686
self.closeSec=1679241599, self.tradeDate='20230319', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27152.2, self.close=27534.3, self.high=27799.9, self.low=27090.0, self.vol=164948.133, self.amt=4515100858.27038 
127.0.0.1 - - [20/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-03-20 00:00:02,082:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679241599, self.tradeDate='20230319', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27152.2, self.close=27534.3, self.high=27799.9, self.low=27090.0, self.vol=164948.133, self.amt=4515100858.27038 
2023-03-20 00:00:02,125:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230319   040000    075959  ...   95750.566  2.590727e+09 -0.015222
722  20230319   080000    115959  ...   54712.469  1.481492e+09  0.010692
723  20230319   120000    155959  ...   62219.778  1.681303e+09 -0.008505
724  20230319   160000    195959  ...   69530.397  1.879203e+09  0.007002
725  20230319   200000    235959  ...  164948.133  4.515101e+09  0.014073

[5 rows x 11 columns]
2023-03-20 00:00:05,098:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230319   040000    075959  1679183999  ...    721  0.986827  0.991055     1.0
722  20230319   080000    115959  1679198399  ...    722  1.015500  1.054881     1.0
723  20230319   120000    155959  1679212799  ...    723  1.010286  1.019974     1.0
724  20230319   160000    195959  1679227199  ...    724  0.969619  0.885534     1.0
725  20230319   200000    235959  1679241599  ...    725  0.978582  0.898154     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '7517.95342445735', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27539.75189933', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


