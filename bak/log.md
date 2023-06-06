# 20230607 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6784
self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26140.5, self.close=26133.0, self.high=26154.9, self.low=26107.5, self.vol=2438.694, self.amt=63719782.7397 
127.0.0.1 - - [07/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:20:03,357:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230606   235500    235959  ...         0.0        0.0       0
5760  20230607   000000    000459  ...         0.0        0.0       0
5761  20230607   000500    000959  ...         0.0        0.0       0
5762  20230607   001000    001459  ...         0.0        0.0       0
5763  20230607   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 00:20:03,369:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26140.5, self.close=26133.0, self.high=26154.9, self.low=26107.5, self.vol=2438.694, self.amt=63719782.7397, ukdf['pct'].iloc[-1]=-0.000168 , ukdf['amount'].iloc[-1]=63719782.7397, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10182.6912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26133.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6785
self.closeSec=1686068699, self.tradeDate='20230607', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26133.0, self.close=26210.8, self.high=26241.2, self.low=26129.9, self.vol=5811.92, self.amt=152302483.3997 
127.0.0.1 - - [07/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:25:04,200:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230607   000000    000459  ...         0.0        0.0       0
5761  20230607   000500    000959  ...         0.0        0.0       0
5762  20230607   001000    001459  ...         0.0        0.0       0
5763  20230607   001500    001959  ...         0.0        0.0       0
5764  20230607   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 00:25:04,213:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686068699, self.tradeDate='20230607', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26133.0, self.close=26210.8, self.high=26241.2, self.low=26129.9, self.vol=5811.92, self.amt=152302483.3997, ukdf['pct'].iloc[-1]=0.002977 , ukdf['amount'].iloc[-1]=152302483.3997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8898.714', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26225.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26140.5, self.close=26133.0, self.high=26154.9, self.low=26107.5 
127.0.0.1 - - [07/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:20:01,592:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26140.5, self.close=26133.0, self.high=26154.9, self.low=26107.5   
2023-06-07 00:20:02,517:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230606   235500    235959  1686067199  ...  26029.9  0.000814   1727    5
1440  20230607   000000    000459  1686067499  ...  26051.2  0.004034   1440    0
1441  20230607   000500    000959  1686067799  ...  26082.6  0.000226   1441    1
1442  20230607   001000    001459  1686068099  ...  26123.0 -0.000944   1442    2
1443  20230607   001500    001959  1686068399  ...  26107.5 -0.000168   1443    3

[5 rows x 11 columns]
2023-06-07 00:20:02,519:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6704669562950663, self.count=6787 

self.closeSec=1686068699, self.tradeDate='20230607', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26133.0, self.close=26210.8, self.high=26241.2, self.low=26129.9 
127.0.0.1 - - [07/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:25:03,006:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686068699, self.tradeDate='20230607', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26133.0, self.close=26210.8, self.high=26241.2, self.low=26129.9   
2023-06-07 00:25:03,731:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230607   000000    000459  1686067499  ...  26051.2  0.004034   1440    0
1441  20230607   000500    000959  1686067799  ...  26082.6  0.000226   1441    1
1442  20230607   001000    001459  1686068099  ...  26123.0 -0.000944   1442    2
1443  20230607   001500    001959  1686068399  ...  26107.5 -0.000168   1443    3
1444  20230607   002000    002459  1686068699  ...  26129.9  0.002977   1444    4

[5 rows x 11 columns]
2023-06-07 00:25:03,732:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-07 00:00:35,402:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230606    212959  25524.4  ...  46.250000  0.341118  0.721218
5803  20230606    215959  25528.1  ...  46.666667  0.395085  0.688971
5804  20230606    222959  25720.0  ...  47.083333  0.438214  0.659937
5805  20230606    225959  25902.7  ...  47.083333  0.462673  0.623290
5806  20230606    232959  26014.2  ...  46.666667  0.447516  0.596366

[5 rows x 33 columns]
0.5147058823529411
acc is : 0.5147058823529411
2023-06-07 00:00:35,549:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.487770  0.512230       1  ...  1.064545   1.0    0.0  0.971055
540     0  0.543581  0.456419       1  ...  1.071920   1.0    0.0  0.977781
541     0  0.557544  0.442456       1  ...  1.076534   1.0    0.0  0.981990
542     0  0.564540  0.435460       0  ...  1.073016   1.0    0.0  0.978782
543     0  0.522923  0.477077       1  ...  1.078065   1.0    0.0  0.983387

[5 rows x 10 columns]
2023-06-07 00:00:35,584:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487917  0.512083       1  ...  1.064545   1.0    0.0  0.974996
46     0  0.543690  0.456310       1  ...  1.071920   1.0    0.0  0.980268
47     0  0.557852  0.442148       1  ...  1.076534   1.0    0.0  0.984488
48     0  0.564624  0.435376       0  ...  1.073016   1.0    0.0  0.980992
49     0  0.522923  0.477077       1  ...  1.078065   1.0    0.0  0.983387

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.054', 'enterprice': '25722.1', 'countrevence': '0', 'unrealprofit': '9549.29981328024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26062.48995556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [07/Jun/2023 00:00:05] "POST / HTTP/1.1" 200 -
2023-06-07 00:00:05,088:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42334F1686067204003I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686067204401609, 'quantity': '26.931', 'price': '26057.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686067202952, 'updatetime': 1686067204401, 'tradetype': 'usdt', 'selfid': 42334, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686067204401, 'clientorderid': '42334F1686067204003I0L59', 'price': '26057.2', 'quantity': '26.931', 'commission': '701.7464532', 'commissionasset': 'USDT', 'tradetime': 1686067204401, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686067204401}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3392 

self.closeSec=1686067799, self.tradeDate='20230607', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26051.2', self.close='26163.7'
127.0.0.1 - - [07/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:10:01,136:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686067799, self.tradeDate='20230607', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26051.2', self.close='26163.7'
2023-06-07 00:10:01,160:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230606   232000    232959  1686065399    25945  25929.2 -0.000613
573  20230606   233000    233959  1686065999  25929.3    25968  0.001496
574  20230606   234000    234959  1686066599    25968  26031.1  0.002430
575  20230606   235000    235959  1686067199  26031.1  26051.2  0.000772
576  20230607   000000    000959  1686067799  26051.2  26163.7  0.004318
2023-06-07 00:10:01,160:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3393 

self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26162.1', self.close='26133'
127.0.0.1 - - [07/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-07 00:20:04,357:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26162.1', self.close='26133'
2023-06-07 00:20:04,779:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230606   233000    233959  1686065999  25929.3    25968  0.001496
574  20230606   234000    234959  1686066599    25968  26031.1  0.002430
575  20230606   235000    235959  1686067199  26031.1  26051.2  0.000772
576  20230607   000000    000959  1686067799  26051.2  26163.7  0.004318
577  20230607   001000    001959  1686068399  26162.1    26133 -0.001173
2023-06-07 00:20:04,779:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-07 00:00:02,351:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-07 00:00:02,498:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6070000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230606, closeTime:235959, close:26051.2, total:975635.9291773, pct_pre:-6.21552326935948e-05, thd:0.18454187186217258, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3395 

self.closeSec=1686067799, self.tradeDate='20230607', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26051.2', self.close='26163.7'
2023-06-07 00:10:01,152:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686067799, self.tradeDate='20230607', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26051.2', self.close='26163.7'
127.0.0.1 - - [07/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:10:01,173:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230606   232000    232959  1686065399    25945  25929.2
17421  20230606   233000    233959  1686065999  25929.3    25968
17422  20230606   234000    234959  1686066599    25968  26031.1
17423  20230606   235000    235959  1686067199  26031.1  26051.2
17424  20230607   000000    000959  1686067799  26051.2  26163.7
2023-06-07 00:10:01,173:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3396 

self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26162.1', self.close='26133'
127.0.0.1 - - [07/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-07 00:20:05,157:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26162.1', self.close='26133'
2023-06-07 00:20:05,245:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230606   233000    233959  1686065999  25929.3    25968
17422  20230606   234000    234959  1686066599    25968  26031.1
17423  20230606   235000    235959  1686067199  26031.1  26051.2
17424  20230607   000000    000959  1686067799  26051.2  26163.7
17425  20230607   001000    001959  1686068399  26162.1    26133
2023-06-07 00:20:05,245:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-07 00:00:04,781:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42333F1686067203917I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686067204363444, 'quantity': '48.541', 'price': '26057.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686067202927, 'updatetime': 1686067204363, 'tradetype': 'usdt', 'selfid': 42333, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686067204363, 'clientorderid': '42333F1686067203917I0L2', 'price': '26057.2', 'quantity': '48.541', 'commission': '1264.8425452', 'commissionasset': 'USDT', 'tradetime': 1686067204363, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686067204363}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3395 

self.closeSec=1686067799, self.tradeDate='20230607', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26051.2', self.close='26163.7'
127.0.0.1 - - [07/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:10:01,129:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686067799, self.tradeDate='20230607', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26051.2', self.close='26163.7'
2023-06-07 00:10:01,182:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230606   232000    232959  1686065399    25945  25929.2
12237  20230606   233000    233959  1686065999  25929.3    25968
12238  20230606   234000    234959  1686066599    25968  26031.1
12239  20230606   235000    235959  1686067199  26031.1  26051.2
12240  20230607   000000    000959  1686067799  26051.2  26163.7
2023-06-07 00:10:01,183:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3396 

self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26162.1', self.close='26133'
127.0.0.1 - - [07/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-07 00:20:05,070:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26162.1', self.close='26133'
2023-06-07 00:20:05,150:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230606   233000    233959  1686065999  25929.3    25968
12238  20230606   234000    234959  1686066599    25968  26031.1
12239  20230606   235000    235959  1686067199  26031.1  26051.2
12240  20230607   000000    000959  1686067799  26051.2  26163.7
12241  20230607   001000    001959  1686068399  26162.1    26133
2023-06-07 00:20:05,151:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6784
self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26140.5, self.close=26133.0, self.high=26154.9, self.low=26107.5, self.vol=2438.694, self.amt=63719782.7397 
127.0.0.1 - - [07/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:20:03,208:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230606   235500    235959  ...         0.0        0.0       0
5760  20230607   000000    000459  ...         0.0        0.0       0
5761  20230607   000500    000959  ...         0.0        0.0       0
5762  20230607   001000    001459  ...         0.0        0.0       0
5763  20230607   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 00:20:03,238:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686068399, self.tradeDate='20230607', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26140.5, self.close=26133.0, self.high=26154.9, self.low=26107.5, self.vol=2438.694, self.amt=63719782.7397, ukdf['pct'].iloc[-1]=-0.000168 , ukdf['amount'].iloc[-1]=63719782.7397, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-26518.674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26130', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6785
self.closeSec=1686068699, self.tradeDate='20230607', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26133.0, self.close=26210.8, self.high=26241.2, self.low=26129.9, self.vol=5811.92, self.amt=152302483.3997 
127.0.0.1 - - [07/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-07 00:25:04,122:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230607   000000    000459  ...         0.0        0.0       0
5761  20230607   000500    000959  ...         0.0        0.0       0
5762  20230607   001000    001459  ...         0.0        0.0       0
5763  20230607   001500    001959  ...         0.0        0.0       0
5764  20230607   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-07 00:25:04,131:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686068699, self.tradeDate='20230607', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26133.0, self.close=26210.8, self.high=26241.2, self.low=26129.9, self.vol=5811.92, self.amt=152302483.3997, ukdf['pct'].iloc[-1]=0.002977 , ukdf['amount'].iloc[-1]=152302483.3997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-22956.8521', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26225.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230606   120000    155959  1686038399  ...    723  0.625418  0.187076     NaN
724  20230606   160000    195959  1686052799  ...    724  0.677037  0.325372     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '77375.8316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25676', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [07/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=141
self.closeSec=1686067199, self.tradeDate='20230606', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25676.0, self.close=26051.2, self.high=26139.0, self.low=25321.6, self.vol=252404.577, self.amt=6498558552.35051 
2023-06-07 00:00:01,770:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686067199, self.tradeDate='20230606', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25676.0, self.close=26051.2, self.high=26139.0, self.low=25321.6, self.vol=252404.577, self.amt=6498558552.35051 
2023-06-07 00:00:01,830:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230606   040000    075959  ...   60134.637  1.543268e+09  0.003751
722  20230606   080000    115959  ...   45585.085  1.171164e+09  0.000202
723  20230606   120000    155959  ...   32812.859  8.451787e+08 -0.000521
724  20230606   160000    195959  ...   37440.876  9.624731e+08 -0.001183
725  20230606   200000    235959  ...  252404.577  6.498559e+09  0.014613

[5 rows x 11 columns]
2023-06-07 00:00:04,668:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230606   040000    075959  1686009599  ...    721  0.439634 -0.336106     NaN
722  20230606   080000    115959  1686023999  ...    722  0.537197 -0.060082     NaN
723  20230606   120000    155959  1686038399  ...    723  0.625418  0.187076     NaN
724  20230606   160000    195959  1686052799  ...    724  0.677037  0.325372     NaN
725  20230606   200000    235959  1686067199  ...    725  0.604946  0.090038     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '56352.069', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26057.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


