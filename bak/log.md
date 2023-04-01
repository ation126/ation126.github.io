# 20230402 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36124
self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28429.0, self.close=28421.1, self.high=28430.0, self.low=28409.7, self.vol=1174.118, self.amt=33369036.0026 
127.0.0.1 - - [02/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-02 00:20:08,994:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230401   235500    235959  ...         0.0        0.0       0
5760  20230402   000000    000459  ...         0.0        0.0       0
5761  20230402   000500    000959  ...         0.0        0.0       0
5762  20230402   001000    001459  ...         0.0        0.0       0
5763  20230402   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 00:20:09,015:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28429.0, self.close=28421.1, self.high=28430.0, self.low=28409.7, self.vol=1174.118, self.amt=33369036.0026, ukdf['pct'].iloc[-1]=-0.000274 , ukdf['amount'].iloc[-1]=33369036.0026, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-715594.9392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28421', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36125
self.closeSec=1680366299, self.tradeDate='20230402', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28421.0, self.close=28405.3, self.high=28423.8, self.low=28400.0, self.vol=888.236, self.amt=25232673.4617 
2023-04-02 00:25:01,631:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230402   000000    000459  ...         0.0        0.0       0
5761  20230402   000500    000959  ...         0.0        0.0       0
5762  20230402   001000    001459  ...         0.0        0.0       0
5763  20230402   001500    001959  ...         0.0        0.0       0
5764  20230402   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 00:25:01,631:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680366299, self.tradeDate='20230402', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28421.0, self.close=28405.3, self.high=28423.8, self.low=28400.0, self.vol=888.236, self.amt=25232673.4617, ukdf['pct'].iloc[-1]=-0.000556 , ukdf['amount'].iloc[-1]=25232673.4617, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714650.176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28405.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28429.0, self.close=28421.1, self.high=28430.0, self.low=28409.7 
127.0.0.1 - - [02/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-02 00:20:05,784:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28429.0, self.close=28421.1, self.high=28430.0, self.low=28409.7   
2023-04-02 00:20:07,134:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230401   235500    235959  1680364799  ...  28340.2  0.000959   1727    5
1440  20230402   000000    000459  1680365099  ...  28370.1 -0.000602   1440    0
1441  20230402   000500    000959  1680365399  ...  28367.4  0.000976   1441    1
1442  20230402   001000    001459  1680365699  ...  28397.8  0.001095   1442    2
1443  20230402   001500    001959  1680365999  ...  28409.7 -0.000274   1443    3

[5 rows x 11 columns]
2023-04-02 00:20:07,134:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=5, self.factor=0.43983814596395626, self.count=36691 

self.closeSec=1680366299, self.tradeDate='20230402', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28421.0, self.close=28405.3, self.high=28423.8, self.low=28400.0 
2023-04-02 00:25:01,531:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680366299, self.tradeDate='20230402', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28421.0, self.close=28405.3, self.high=28423.8, self.low=28400.0   
2023-04-02 00:25:01,604:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230402   000000    000459  1680365099  ...  28370.1 -0.000602   1440    0
1441  20230402   000500    000959  1680365399  ...  28367.4  0.000976   1441    1
1442  20230402   001000    001459  1680365699  ...  28397.8  0.001095   1442    2
1443  20230402   001500    001959  1680365999  ...  28409.7 -0.000274   1443    3
1444  20230402   002000    002459  1680366299  ...  28400.0 -0.000556   1444    4

[5 rows x 11 columns]
2023-04-02 00:25:01,604:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-02 00:00:35,946:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230401    212959  28413.1  ...  51.666667  0.519539  0.505661
5803  20230401    215959  28414.7  ...  51.666667  0.518183  0.520987
5804  20230401    222959  28407.5  ...  51.666667  0.507723  0.543442
5805  20230401    225959  28351.8  ...  51.666667  0.498180  0.568797
5806  20230401    232959  28299.9  ...  51.666667  0.506871  0.580749

[5 rows x 33 columns]
0.5220588235294118
acc is : 0.5220588235294118
2023-04-02 00:00:36,106:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.515449  0.484551       0  ...  1.013082   1.0    0.0  1.033342
540     0  0.515142  0.484858       0  ...  1.011096   1.0    0.0  1.031316
541     0  0.506811  0.493189       0  ...  1.009248   1.0    0.0  1.029432
542     0  0.502067  0.497933       1  ...  1.010946   1.0    0.0  1.031163
543     0  0.523284  0.476716       1  ...  1.012358   1.0    0.0  1.032604

[5 rows x 10 columns]
2023-04-02 00:00:36,142:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512890  0.487110       0  ...  1.013082   1.0    0.0  1.025841
46     0  0.513514  0.486486       0  ...  1.011096   1.0    0.0  1.026447
47     0  0.505175  0.494825       0  ...  1.009248   1.0    0.0  1.024572
48     0  0.501328  0.498672       1  ...  1.010946   1.0    0.0  1.031122
49     0  0.523284  0.476716       1  ...  1.012358   1.0    0.0  1.032604

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [02/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-02 00:00:03,396:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42095F1680364802783I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680364802900419, 'quantity': '25.343', 'price': '28387.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680364802301, 'updatetime': 1680364802900, 'tradetype': 'usdt', 'selfid': 42095, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680364802900, 'clientorderid': '42095F1680364802783I0L59', 'price': '28387.1', 'quantity': '25.343', 'commission': '719.4142753', 'commissionasset': 'USDT', 'tradetime': 1680364802900, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680364802900}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18344 

self.closeSec=1680365399, self.tradeDate='20230402', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28387.2', self.close='28397.8'
2023-04-02 00:10:01,587:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680365399, self.tradeDate='20230402', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28387.2', self.close='28397.8'
2023-04-02 00:10:01,617:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230401   232000    232959  1680362999  28318.3  28347.6  0.001035
573  20230401   233000    233959  1680363599  28347.6    28345 -0.000092
574  20230401   234000    234959  1680364199  28344.9  28354.7  0.000342
575  20230401   235000    235959  1680364799  28354.7  28387.2  0.001146
576  20230402   000000    000959  1680365399  28387.2  28397.8  0.000373
2023-04-02 00:10:01,618:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18345 

self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28397.9', self.close='28421.1'
127.0.0.1 - - [02/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 00:20:07,565:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28397.9', self.close='28421.1'
2023-04-02 00:20:08,434:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230401   233000    233959  1680363599  28347.6    28345 -0.000092
574  20230401   234000    234959  1680364199  28344.9  28354.7  0.000342
575  20230401   235000    235959  1680364799  28354.7  28387.2  0.001146
576  20230402   000000    000959  1680365399  28387.2  28397.8  0.000373
577  20230402   001000    001959  1680365999  28397.9  28421.1  0.000820
2023-04-02 00:20:08,434:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-04-02 00:00:02,034:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-04-02 00:00:02,171:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:4020000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230401, closeTime:235959, close:28387.2, total:1007412.9805239, pct_pre:-0.0013813319836348814, thd:0.009876576094217937, side:sell 
127.0.0.1 - - [02/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18345 

self.closeSec=1680365399, self.tradeDate='20230402', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28387.2', self.close='28397.8'
2023-04-02 00:10:01,615:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680365399, self.tradeDate='20230402', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28387.2', self.close='28397.8'
2023-04-02 00:10:01,652:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230401   232000    232959  1680362999  28318.3  28347.6
17421  20230401   233000    233959  1680363599  28347.6    28345
17422  20230401   234000    234959  1680364199  28344.9  28354.7
17423  20230401   235000    235959  1680364799  28354.7  28387.2
17424  20230402   000000    000959  1680365399  28387.2  28397.8
2023-04-02 00:10:01,652:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18346 

self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28397.9', self.close='28421.1'
127.0.0.1 - - [02/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 00:20:11,055:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28397.9', self.close='28421.1'
2023-04-02 00:20:11,214:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230401   233000    233959  1680363599  28347.6    28345
17422  20230401   234000    234959  1680364199  28344.9  28354.7
17423  20230401   235000    235959  1680364799  28354.7  28387.2
17424  20230402   000000    000959  1680365399  28387.2  28397.8
17425  20230402   001000    001959  1680365999  28397.9  28421.1
2023-04-02 00:20:11,215:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [02/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-02 00:00:03,213:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42094F1680364802653I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680364802887392, 'quantity': '45.868', 'price': '28387.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680364802335, 'updatetime': 1680364802887, 'tradetype': 'usdt', 'selfid': 42094, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680364802887, 'clientorderid': '42094F1680364802653I0L2', 'price': '28387.2', 'quantity': '45.868', 'commission': '1302.0640896', 'commissionasset': 'USDT', 'tradetime': 1680364802887, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680364802887}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18345 

self.closeSec=1680365399, self.tradeDate='20230402', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28387.2', self.close='28397.8'
2023-04-02 00:10:01,609:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680365399, self.tradeDate='20230402', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28387.2', self.close='28397.8'
127.0.0.1 - - [02/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-02 00:10:01,629:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230401   232000    232959  1680362999  28318.3  28347.6
12237  20230401   233000    233959  1680363599  28347.6    28345
12238  20230401   234000    234959  1680364199  28344.9  28354.7
12239  20230401   235000    235959  1680364799  28354.7  28387.2
12240  20230402   000000    000959  1680365399  28387.2  28397.8
2023-04-02 00:10:01,629:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18346 

self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28397.9', self.close='28421.1'
127.0.0.1 - - [02/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-02 00:20:10,486:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28397.9', self.close='28421.1'
2023-04-02 00:20:10,816:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230401   233000    233959  1680363599  28347.6    28345
12238  20230401   234000    234959  1680364199  28344.9  28354.7
12239  20230401   235000    235959  1680364799  28354.7  28387.2
12240  20230402   000000    000959  1680365399  28387.2  28397.8
12241  20230402   001000    001959  1680365999  28397.9  28421.1
2023-04-02 00:20:10,816:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32122
self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28429.0, self.close=28421.1, self.high=28430.0, self.low=28409.7, self.vol=1174.118, self.amt=33369036.0026 
127.0.0.1 - - [02/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-02 00:20:08,114:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230401   235500    235959  ...         0.0        0.0       0
5760  20230402   000000    000459  ...         0.0        0.0       0
5761  20230402   000500    000959  ...         0.0        0.0       0
5762  20230402   001000    001459  ...         0.0        0.0       0
5763  20230402   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 00:20:08,134:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680365999, self.tradeDate='20230402', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28429.0, self.close=28421.1, self.high=28430.0, self.low=28409.7, self.vol=1174.118, self.amt=33369036.0026, ukdf['pct'].iloc[-1]=-0.000274 , ukdf['amount'].iloc[-1]=33369036.0026, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32123
self.closeSec=1680366299, self.tradeDate='20230402', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28421.0, self.close=28405.3, self.high=28423.8, self.low=28400.0, self.vol=888.236, self.amt=25232673.4617 
2023-04-02 00:25:01,629:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230402   000000    000459  ...         0.0        0.0       0
5761  20230402   000500    000959  ...         0.0        0.0       0
5762  20230402   001000    001459  ...         0.0        0.0       0
5763  20230402   001500    001959  ...         0.0        0.0       0
5764  20230402   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-02 00:25:01,629:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680366299, self.tradeDate='20230402', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28421.0, self.close=28405.3, self.high=28423.8, self.low=28400.0, self.vol=888.236, self.amt=25232673.4617, ukdf['pct'].iloc[-1]=-0.000556 , ukdf['amount'].iloc[-1]=25232673.4617, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230401   120000    155959  1680335999  ...    723  0.730416  0.849276     1.0
724  20230401   160000    195959  1680350399  ...    724  0.624758  0.539265     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-7024.36732812932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28361.31230556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1484665.736112, self.flagDict['side']='buy', self.tradeCount=28, self.count=764
self.closeSec=1680364799, self.tradeDate='20230401', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28365.4, self.close=28387.2, self.high=28430.0, self.low=28180.0, self.vol=49661.974, self.amt=1407624279.53011 
2023-04-02 00:00:01,828:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680364799, self.tradeDate='20230401', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28365.4, self.close=28387.2, self.high=28430.0, self.low=28180.0, self.vol=49661.974, self.amt=1407624279.53011 
127.0.0.1 - - [02/Apr/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-04-02 00:00:01,925:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230401   040000    075959  ...  51498.288  1.466608e+09  0.000228
722  20230401   080000    115959  ...  65781.338  1.879983e+09  0.002710
723  20230401   120000    155959  ...  46755.745  1.330723e+09 -0.004062
724  20230401   160000    195959  ...  28874.662  8.206232e+08 -0.001781
725  20230401   200000    235959  ...  49661.974  1.407624e+09  0.000765

[5 rows x 11 columns]
2023-04-02 00:00:04,997:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230401   040000    075959  1680307199  ...    721  0.816670  1.124941     1.0
722  20230401   080000    115959  1680321599  ...    722  0.792670  1.040657     1.0
723  20230401   120000    155959  1680335999  ...    723  0.730416  0.849276     1.0
724  20230401   160000    195959  1680350399  ...    724  0.624758  0.539265     NaN
725  20230401   200000    235959  1680364799  ...    725  0.553578  0.328353     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.153', 'enterprice': '28496', 'countrevence': '0', 'unrealprofit': '-5597.16654247845', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28388.67795635', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


