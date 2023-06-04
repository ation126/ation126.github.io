# 20230605 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6208
self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27182.0, self.close=27162.7, self.high=27187.3, self.low=27162.5, self.vol=464.92, self.amt=12633525.9458 
127.0.0.1 - - [05/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 00:20:07,127:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230604   235500    235959  ...         0.0        0.0       0
5760  20230605   000000    000459  ...         0.0        0.0       0
5761  20230605   000500    000959  ...         0.0        0.0       0
5762  20230605   001000    001459  ...         0.0        0.0       0
5763  20230605   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 00:20:07,145:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27182.0, self.close=27162.7, self.high=27187.3, self.low=27162.5, self.vol=464.92, self.amt=12633525.9458, ukdf['pct'].iloc[-1]=-0.00071 , ukdf['amount'].iloc[-1]=12633525.9458, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4164.64240576428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27163.95517778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6209
self.closeSec=1685895899, self.tradeDate='20230605', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27162.8, self.close=27190.2, self.high=27191.9, self.low=27160.0, self.vol=547.733, self.amt=14885977.2244 
2023-06-05 00:25:00,768:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230605   000000    000459  ...         0.0        0.0       0
5761  20230605   000500    000959  ...         0.0        0.0       0
5762  20230605   001000    001459  ...         0.0        0.0       0
5763  20230605   001500    001959  ...         0.0        0.0       0
5764  20230605   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 00:25:00,768:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685895899, self.tradeDate='20230605', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27162.8, self.close=27190.2, self.high=27191.9, self.low=27160.0, self.vol=547.733, self.amt=14885977.2244, ukdf['pct'].iloc[-1]=0.001012 , ukdf['amount'].iloc[-1]=14885977.2244, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4530.1278', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27190.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27182.0, self.close=27162.7, self.high=27187.3, self.low=27162.5 
127.0.0.1 - - [05/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 00:20:04,717:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27182.0, self.close=27162.7, self.high=27187.3, self.low=27162.5   
2023-06-05 00:20:06,217:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230604   235500    235959  1685894399  ...  27164.9 -0.000522   1727    5
1440  20230605   000000    000459  1685894699  ...  27159.8 -0.000136   1440    0
1441  20230605   000500    000959  1685894999  ...  27150.0  0.000666   1441    1
1442  20230605   001000    001459  1685895299  ...  27166.5  0.000026   1442    2
1443  20230605   001500    001959  1685895599  ...  27162.5 -0.000710   1443    3

[5 rows x 11 columns]
2023-06-05 00:20:06,227:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=67, self.factor=0.496146460128805, self.count=6211 

self.closeSec=1685895899, self.tradeDate='20230605', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27162.8, self.close=27190.2, self.high=27191.9, self.low=27160.0 
2023-06-05 00:25:00,742:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685895899, self.tradeDate='20230605', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27162.8, self.close=27190.2, self.high=27191.9, self.low=27160.0   
2023-06-05 00:25:00,822:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230605   000000    000459  1685894699  ...  27159.8 -0.000136   1440    0
1441  20230605   000500    000959  1685894999  ...  27150.0  0.000666   1441    1
1442  20230605   001000    001459  1685895299  ...  27166.5  0.000026   1442    2
1443  20230605   001500    001959  1685895599  ...  27162.5 -0.000710   1443    3
1444  20230605   002000    002459  1685895899  ...  27160.0  0.001012   1444    4

[5 rows x 11 columns]
2023-06-05 00:25:00,823:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-05 00:00:33,948:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230604    212959  27199.5  ...  47.083333  0.536446  0.436044
5803  20230604    215959  27215.9  ...  47.500000  0.541507  0.417009
5804  20230604    222959  27231.4  ...  47.500000  0.521752  0.408131
5805  20230604    225959  27179.3  ...  47.916667  0.535970  0.392529
5806  20230604    232959  27222.1  ...  47.500000  0.527446  0.381865

[5 rows x 33 columns]
0.5294117647058824
acc is : 0.5294117647058824
2023-06-05 00:00:34,115:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.500771  0.499229       1  ...  1.022128   1.0    0.0  1.021268
540     0  0.502242  0.497758       0  ...  1.020176   1.0    0.0  1.019318
541     1  0.487779  0.512221       1  ...  1.021783   1.0    0.0  1.020923
542     0  0.510655  0.489345       0  ...  1.020927   1.0    0.0  1.020068
543     1  0.493377  0.506623       0  ...  1.019711   1.0    0.0  1.018853

[5 rows x 10 columns]
2023-06-05 00:00:34,147:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501095  0.498905       1  ...  1.022128   1.0    0.0  1.018754
46     0  0.502337  0.497663       0  ...  1.020176   1.0    0.0  1.017955
47     1  0.487777  0.512223       1  ...  1.021783   1.0    0.0  1.019558
48     0  0.510589  0.489411       0  ...  1.060327   1.0    0.0  1.018719
49     1  0.493377  0.506623       0  ...  1.019711   1.0    0.0  1.018853

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '5182.0748', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27176.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [05/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-05 00:00:04,563:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42321F1685894403686I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685894404126582, 'quantity': '24.979', 'price': '27168.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685894402739, 'updatetime': 1685894404126, 'tradetype': 'usdt', 'selfid': 42321, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685894404126, 'clientorderid': '42321F1685894403686I0L59', 'price': '27168.7', 'quantity': '24.979', 'commission': '678.6469573', 'commissionasset': 'USDT', 'tradetime': 1685894404126, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685894404126}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3104 

self.closeSec=1685894999, self.tradeDate='20230605', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27167', self.close='27181.3'
127.0.0.1 - - [05/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-05 00:10:01,081:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685894999, self.tradeDate='20230605', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27167', self.close='27181.3'
2023-06-05 00:10:01,100:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230604   232000    232959  1685892599  27199.9  27199.4 -0.000022
573  20230604   233000    233959  1685893199  27199.3  27190.1 -0.000342
574  20230604   234000    234959  1685893799    27190  27192.2  0.000077
575  20230604   235000    235959  1685894399  27192.2  27166.9 -0.000930
576  20230605   000000    000959  1685894999    27167  27181.3  0.000530
2023-06-05 00:10:01,100:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3105 

self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27181.4', self.close='27162.7'
127.0.0.1 - - [05/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 00:20:07,185:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27181.4', self.close='27162.7'
2023-06-05 00:20:07,856:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230604   233000    233959  1685893199  27199.3  27190.1 -0.000342
574  20230604   234000    234959  1685893799    27190  27192.2  0.000077
575  20230604   235000    235959  1685894399  27192.2  27166.9 -0.000930
576  20230605   000000    000959  1685894999    27167  27181.3  0.000530
577  20230605   001000    001959  1685895599  27181.4  27162.7 -0.000684
2023-06-05 00:20:07,864:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-05 00:00:02,171:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-05 00:00:02,286:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6050000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230604, closeTime:235959, close:27166.9, total:975635.9291773, pct_pre:-0.0005914312268340272, thd:0.3774563192782957, side:sell 
127.0.0.1 - - [05/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3107 

self.closeSec=1685894999, self.tradeDate='20230605', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27167', self.close='27181.3'
2023-06-05 00:10:01,065:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685894999, self.tradeDate='20230605', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27167', self.close='27181.3'
2023-06-05 00:10:01,096:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230604   232000    232959  1685892599  27199.9  27199.4
17421  20230604   233000    233959  1685893199  27199.3  27190.1
17422  20230604   234000    234959  1685893799    27190  27192.2
17423  20230604   235000    235959  1685894399  27192.2  27166.9
17424  20230605   000000    000959  1685894999    27167  27181.3
2023-06-05 00:10:01,096:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3108 

self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27181.4', self.close='27162.7'
127.0.0.1 - - [05/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 00:20:08,706:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27181.4', self.close='27162.7'
2023-06-05 00:20:08,868:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230604   233000    233959  1685893199  27199.3  27190.1
17422  20230604   234000    234959  1685893799    27190  27192.2
17423  20230604   235000    235959  1685894399  27192.2  27166.9
17424  20230605   000000    000959  1685894999    27167  27181.3
17425  20230605   001000    001959  1685895599  27181.4  27162.7
2023-06-05 00:20:08,869:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [05/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-05 00:00:04,312:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42320F1685894403675I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685894404086232, 'quantity': '44.017', 'price': '27168.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685894402757, 'updatetime': 1685894404086, 'tradetype': 'usdt', 'selfid': 42320, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685894404086, 'clientorderid': '42320F1685894403675I0L2', 'price': '27168.6', 'quantity': '44.017', 'commission': '1195.8802662', 'commissionasset': 'USDT', 'tradetime': 1685894404086, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685894404086}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3107 

self.closeSec=1685894999, self.tradeDate='20230605', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27167', self.close='27181.3'
127.0.0.1 - - [05/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-05 00:10:01,067:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685894999, self.tradeDate='20230605', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27167', self.close='27181.3'
2023-06-05 00:10:01,077:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230604   232000    232959  1685892599  27199.9  27199.4
12237  20230604   233000    233959  1685893199  27199.3  27190.1
12238  20230604   234000    234959  1685893799    27190  27192.2
12239  20230604   235000    235959  1685894399  27192.2  27166.9
12240  20230605   000000    000959  1685894999    27167  27181.3
2023-06-05 00:10:01,078:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3108 

self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27181.4', self.close='27162.7'
127.0.0.1 - - [05/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 00:20:08,438:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27181.4', self.close='27162.7'
2023-06-05 00:20:08,666:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230604   233000    233959  1685893199  27199.3  27190.1
12238  20230604   234000    234959  1685893799    27190  27192.2
12239  20230604   235000    235959  1685894399  27192.2  27166.9
12240  20230605   000000    000959  1685894999    27167  27181.3
12241  20230605   001000    001959  1685895599  27181.4  27162.7
2023-06-05 00:20:08,667:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6208
self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27182.0, self.close=27162.7, self.high=27187.3, self.low=27162.5, self.vol=464.92, self.amt=12633525.9458 
127.0.0.1 - - [05/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 00:20:07,065:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230604   235500    235959  ...         0.0        0.0       0
5760  20230605   000000    000459  ...         0.0        0.0       0
5761  20230605   000500    000959  ...         0.0        0.0       0
5762  20230605   001000    001459  ...         0.0        0.0       0
5763  20230605   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 00:20:07,096:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685895599, self.tradeDate='20230605', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27182.0, self.close=27162.7, self.high=27187.3, self.low=27162.5, self.vol=464.92, self.amt=12633525.9458, ukdf['pct'].iloc[-1]=-0.00071 , ukdf['amount'].iloc[-1]=12633525.9458, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '11883.45525792698', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27163.95517778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6209
self.closeSec=1685895899, self.tradeDate='20230605', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27162.8, self.close=27190.2, self.high=27191.9, self.low=27160.0, self.vol=547.733, self.amt=14885977.2244 
2023-06-05 00:25:00,845:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230605   000000    000459  ...         0.0        0.0       0
5761  20230605   000500    000959  ...         0.0        0.0       0
5762  20230605   001000    001459  ...         0.0        0.0       0
5763  20230605   001500    001959  ...         0.0        0.0       0
5764  20230605   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 00:25:00,845:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685895899, self.tradeDate='20230605', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27162.8, self.close=27190.2, self.high=27191.9, self.low=27160.0, self.vol=547.733, self.amt=14885977.2244, ukdf['pct'].iloc[-1]=0.001012 , ukdf['amount'].iloc[-1]=14885977.2244, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '12858.2142', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27190.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230604   120000    155959  1685865599  ...    723  0.029091 -1.593836    -1.0
724  20230604   160000    195959  1685879999  ...    724  0.035998 -1.557238    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '-6318.07008392554', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27193.12833419', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=129
self.closeSec=1685894399, self.tradeDate='20230604', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27190.8, self.close=27166.9, self.high=27290.0, self.low=27150.0, self.vol=38245.649, self.amt=1040603296.2586 
127.0.0.1 - - [05/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-05 00:00:01,719:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685894399, self.tradeDate='20230604', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27190.8, self.close=27166.9, self.high=27290.0, self.low=27150.0, self.vol=38245.649, self.amt=1040603296.2586 
2023-06-05 00:00:01,744:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230604   040000    075959  ...  36463.540  9.851884e+08 -0.001108
722  20230604   080000    115959  ...  25275.090  6.832596e+08 -0.000240
723  20230604   120000    155959  ...  23617.719  6.399566e+08  0.003423
724  20230604   160000    195959  ...  29667.465  8.064795e+08  0.001839
725  20230604   200000    235959  ...  38245.649  1.040603e+09 -0.000883

[5 rows x 11 columns]
2023-06-05 00:00:03,870:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230604   040000    075959  1685836799  ...    721  0.276780 -0.862749    -1.0
722  20230604   080000    115959  1685851199  ...    722  0.160352 -1.213449    -1.0
723  20230604   120000    155959  1685865599  ...    723  0.029091 -1.593836    -1.0
724  20230604   160000    195959  1685879999  ...    724  0.035998 -1.557238    -1.0
725  20230604   200000    235959  1685894399  ...    725  0.040939 -1.528777    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '-5081.37254259154', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27170.71058519', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


