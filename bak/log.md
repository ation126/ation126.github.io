# 20230815 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26656
self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29626.2, self.close=29637.9, self.high=29650.0, self.low=29626.1, self.vol=919.159, self.amt=27245573.3863 
127.0.0.1 - - [15/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 00:20:06,928:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230814   235500    235959  ...         0.0        0.0       0
5760  20230815   000000    000459  ...         0.0        0.0       0
5761  20230815   000500    000959  ...         0.0        0.0       0
5762  20230815   001000    001459  ...         0.0        0.0       0
5763  20230815   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 00:20:06,950:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29626.2, self.close=29637.9, self.high=29650.0, self.low=29626.1, self.vol=919.159, self.amt=27245573.3863, ukdf['pct'].iloc[-1]=0.000395 , ukdf['amount'].iloc[-1]=27245573.3863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-38656.73297912712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29640.76765612', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26657
self.closeSec=1692030299, self.tradeDate='20230815', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29637.8, self.close=29613.6, self.high=29650.8, self.low=29605.9, self.vol=997.219, self.amt=29543526.2793 
127.0.0.1 - - [15/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-15 00:25:00,753:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230815   000000    000459  ...         0.0        0.0       0
5761  20230815   000500    000959  ...         0.0        0.0       0
5762  20230815   001000    001459  ...         0.0        0.0       0
5763  20230815   001500    001959  ...         0.0        0.0       0
5764  20230815   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 00:25:00,753:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692030299, self.tradeDate='20230815', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29637.8, self.close=29613.6, self.high=29650.8, self.low=29605.9, self.vol=997.219, self.amt=29543526.2793, ukdf['pct'].iloc[-1]=-0.00082 , ukdf['amount'].iloc[-1]=29543526.2793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-38288.30945540832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29614.31185232', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29626.2, self.close=29637.9, self.high=29650.0, self.low=29626.1 
127.0.0.1 - - [15/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 00:20:04,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29626.2, self.close=29637.9, self.high=29650.0, self.low=29626.1   
2023-08-15 00:20:05,940:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230814   235500    235959  1692028799  ...  29589.0 -0.000037   1727    5
1440  20230815   000000    000459  1692029099  ...  29592.8  0.000456   1440    0
1441  20230815   000500    000959  1692029399  ...  29595.8  0.000969   1441    1
1442  20230815   001000    001459  1692029699  ...  29620.8 -0.000300   1442    2
1443  20230815   001500    001959  1692029999  ...  29626.1  0.000395   1443    3

[5 rows x 11 columns]
2023-08-15 00:20:05,950:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=21, self.factor=0.41875007212440485, self.count=26659 

self.closeSec=1692030299, self.tradeDate='20230815', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29637.8, self.close=29613.6, self.high=29650.8, self.low=29605.9 
127.0.0.1 - - [15/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-15 00:25:00,721:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692030299, self.tradeDate='20230815', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29637.8, self.close=29613.6, self.high=29650.8, self.low=29605.9   
2023-08-15 00:25:00,733:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230815   000000    000459  1692029099  ...  29592.8  0.000456   1440    0
1441  20230815   000500    000959  1692029399  ...  29595.8  0.000969   1441    1
1442  20230815   001000    001459  1692029699  ...  29620.8 -0.000300   1442    2
1443  20230815   001500    001959  1692029999  ...  29626.1  0.000395   1443    3
1444  20230815   002000    002459  1692030299  ...  29605.9 -0.000820   1444    4

[5 rows x 11 columns]
2023-08-15 00:25:00,733:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-15 00:00:18,255:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230814    212959  29372.1  ...  46.666667  0.473175  0.304304
5803  20230814    215959  29338.8  ...  47.083333  0.493444  0.301662
5804  20230814    222959  29376.0  ...  47.083333  0.525480  0.288971
5805  20230814    225959  29439.8  ...  47.500000  0.562599  0.277768
5806  20230814    232959  29523.6  ...  47.916667  0.604276  0.260864

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-08-15 00:00:18,331:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.488417  0.511583       1  ...  1.005049  -1.0    0.0  1.011776
540     0  0.510337  0.489663       1  ...  1.002866  -1.0    0.0  1.013973
541     0  0.521490  0.478510       1  ...  1.000008  -1.0    0.0  1.016863
542     0  0.534941  0.465059       1  ...  0.996258  -1.0    0.0  1.020676
543     0  0.549563  0.450437       0  ...  0.997650  -1.0    0.0  1.019250

[5 rows x 10 columns]
2023-08-15 00:00:18,345:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489531  0.510469       1  ...  1.005049  -1.0    0.0  1.008923
46     0  0.511400  0.488600       1  ...  1.002866  -1.0    0.0  1.012477
47     0  0.522491  0.477509       1  ...  1.000008  -1.0    0.0  1.015363
48     0  0.535034  0.464966       1  ...  0.996258  -1.0    0.0  1.020883
49     0  0.549563  0.450437       0  ...  0.997650  -1.0    0.0  1.019250

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '-2893.0947', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29600', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [15/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-15 00:00:04,319:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42861F1692028803549I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1692028803958779, 'quantity': '24.587', 'price': '29592.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1692028802647, 'updatetime': 1692028803958, 'tradetype': 'usdt', 'selfid': 42861, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1692028803958, 'clientorderid': '42861F1692028803549I0L59', 'price': '29592.8', 'quantity': '24.587', 'commission': '727.5981736', 'commissionasset': 'USDT', 'tradetime': 1692028803958, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1692028803958}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13328 

self.closeSec=1692029399, self.tradeDate='20230815', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29592.8', self.close='29635.1'
127.0.0.1 - - [15/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-15 00:10:01,147:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692029399, self.tradeDate='20230815', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29592.8', self.close='29635.1'
2023-08-15 00:10:01,160:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230814   232000    232959  1692026999  29528.7  29634.3  0.003573
573  20230814   233000    233959  1692027599  29634.2  29617.9 -0.000553
574  20230814   234000    234959  1692028199  29616.6  29604.7 -0.000446
575  20230814   235000    235959  1692028799  29604.7  29592.9 -0.000399
576  20230815   000000    000959  1692029399  29592.8  29635.1  0.001426
2023-08-15 00:10:01,160:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13329 

self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29635', self.close='29637.9'
127.0.0.1 - - [15/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 00:20:07,118:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29635', self.close='29637.9'
2023-08-15 00:20:07,799:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230814   233000    233959  1692027599  29634.2  29617.9 -0.000553
574  20230814   234000    234959  1692028199  29616.6  29604.7 -0.000446
575  20230814   235000    235959  1692028799  29604.7  29592.9 -0.000399
576  20230815   000000    000959  1692029399  29592.8  29635.1  0.001426
577  20230815   001000    001959  1692029999    29635  29637.9  0.000094
2023-08-15 00:20:07,799:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-15 00:00:04,113:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42860F1692028803475I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1692028803948606, 'quantity': '33.204', 'price': '29592.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1692028802555, 'updatetime': 1692028803948, 'tradetype': 'usdt', 'selfid': 42860, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1692028803948, 'clientorderid': '42860F1692028803475I0L57', 'price': '29592.8', 'quantity': '33.204', 'commission': '982.5993312', 'commissionasset': 'USDT', 'tradetime': 1692028803948, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1692028803948}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13331 

self.closeSec=1692029399, self.tradeDate='20230815', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29592.8', self.close='29635.1'
2023-08-15 00:10:01,142:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692029399, self.tradeDate='20230815', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29592.8', self.close='29635.1'
2023-08-15 00:10:01,150:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230814   232000    232959  1692026999  29528.7  29634.3
17421  20230814   233000    233959  1692027599  29634.2  29617.9
17422  20230814   234000    234959  1692028199  29616.6  29604.7
17423  20230814   235000    235959  1692028799  29604.7  29592.9
17424  20230815   000000    000959  1692029399  29592.8  29635.1
2023-08-15 00:10:01,150:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13332 

self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29635', self.close='29637.9'
127.0.0.1 - - [15/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 00:20:08,790:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29635', self.close='29637.9'
2023-08-15 00:20:08,880:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230814   233000    233959  1692027599  29634.2  29617.9
17422  20230814   234000    234959  1692028199  29616.6  29604.7
17423  20230814   235000    235959  1692028799  29604.7  29592.9
17424  20230815   000000    000959  1692029399  29592.8  29635.1
17425  20230815   001000    001959  1692029999    29635  29637.9
2023-08-15 00:20:08,880:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-08-15 00:00:04,453:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42862F1692028803579I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1692028803985258, 'quantity': '36.628', 'price': '29592.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1692028802632, 'updatetime': 1692028803985, 'tradetype': 'usdt', 'selfid': 42862, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1692028803985, 'clientorderid': '42862F1692028803579I0L2', 'price': '29592.9', 'quantity': '36.628', 'commission': '1083.9287412', 'commissionasset': 'USDT', 'tradetime': 1692028803985, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1692028803985}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13331 

self.closeSec=1692029399, self.tradeDate='20230815', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29592.8', self.close='29635.1'
2023-08-15 00:10:01,140:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692029399, self.tradeDate='20230815', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29592.8', self.close='29635.1'
2023-08-15 00:10:01,155:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230814   232000    232959  1692026999  29528.7  29634.3
12237  20230814   233000    233959  1692027599  29634.2  29617.9
12238  20230814   234000    234959  1692028199  29616.6  29604.7
12239  20230814   235000    235959  1692028799  29604.7  29592.9
12240  20230815   000000    000959  1692029399  29592.8  29635.1
2023-08-15 00:10:01,155:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13332 

self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29635', self.close='29637.9'
127.0.0.1 - - [15/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 00:20:08,590:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29635', self.close='29637.9'
2023-08-15 00:20:08,769:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230814   233000    233959  1692027599  29634.2  29617.9
12238  20230814   234000    234959  1692028199  29616.6  29604.7
12239  20230814   235000    235959  1692028799  29604.7  29592.9
12240  20230815   000000    000959  1692029399  29592.8  29635.1
12241  20230815   001000    001959  1692029999    29635  29637.9
2023-08-15 00:20:08,769:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26656
self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29626.2, self.close=29637.9, self.high=29650.0, self.low=29626.1, self.vol=919.159, self.amt=27245573.3863 
127.0.0.1 - - [15/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 00:20:06,750:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230814   235500    235959  ...         0.0        0.0       0
5760  20230815   000000    000459  ...         0.0        0.0       0
5761  20230815   000500    000959  ...         0.0        0.0       0
5762  20230815   001000    001459  ...         0.0        0.0       0
5763  20230815   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 00:20:06,780:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692029999, self.tradeDate='20230815', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29626.2, self.close=29637.9, self.high=29650.0, self.low=29626.1, self.vol=919.159, self.amt=27245573.3863, ukdf['pct'].iloc[-1]=0.000395 , ukdf['amount'].iloc[-1]=27245573.3863, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '103878.69668542743', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29640.87398523', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26657
self.closeSec=1692030299, self.tradeDate='20230815', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29637.8, self.close=29613.6, self.high=29650.8, self.low=29605.9, self.vol=997.219, self.amt=29543526.2793 
2023-08-15 00:25:00,763:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230815   000000    000459  ...         0.0        0.0       0
5761  20230815   000500    000959  ...         0.0        0.0       0
5762  20230815   001000    001459  ...         0.0        0.0       0
5763  20230815   001500    001959  ...         0.0        0.0       0
5764  20230815   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 00:25:00,763:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692030299, self.tradeDate='20230815', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29637.8, self.close=29613.6, self.high=29650.8, self.low=29605.9, self.vol=997.219, self.amt=29543526.2793, ukdf['pct'].iloc[-1]=-0.00082 , ukdf['amount'].iloc[-1]=29543526.2793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '102892.15250701712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29614.31185232', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230814   120000    155959  1691999999  ...    723  0.015864 -1.133319    -1.0
724  20230814   160000    195959  1692014399  ...    724  0.004699 -1.152454    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '1682.0606673794', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29399.86744245', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [15/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=555
self.closeSec=1692028799, self.tradeDate='20230814', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29399.8, self.close=29592.9, self.high=29665.0, self.low=29319.9, self.vol=80846.779, self.amt=2385466139.06796 
2023-08-15 00:00:01,643:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692028799, self.tradeDate='20230814', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29399.8, self.close=29592.9, self.high=29665.0, self.low=29319.9, self.vol=80846.779, self.amt=2385466139.06796 
2023-08-15 00:00:01,659:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230814   040000    075959  ...  24677.795  7.239654e+08 -0.004513
722  20230814   080000    115959  ...  68307.498  1.998169e+09  0.003301
723  20230814   120000    155959  ...  22168.394  6.520981e+08  0.000698
724  20230814   160000    195959  ...  24534.443  7.217591e+08 -0.000364
725  20230814   200000    235959  ...  80846.779  2.385466e+09  0.006568

[5 rows x 11 columns]
2023-08-15 00:00:02,600:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230814   040000    075959  1691971199  ...    721  0.104590 -0.935304    -1.0
722  20230814   080000    115959  1691985599  ...    722  0.050683 -1.058488    -1.0
723  20230814   120000    155959  1691999999  ...    723  0.015864 -1.133319    -1.0
724  20230814   160000    195959  1692014399  ...    724  0.004699 -1.152454    -1.0
725  20230814   200000    235959  1692028799  ...    725  0.000513 -1.156555    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '-8237.4964', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29592.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


