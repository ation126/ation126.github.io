# 20230622 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11104
self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29917.3, self.close=30145.7, self.high=30237.4, self.low=29908.4, self.vol=23104.444, self.amt=695473986.90638 
127.0.0.1 - - [22/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-22 00:20:07,836:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230621   235500    235959  ...         0.0        0.0       0
5760  20230622   000000    000459  ...         0.0        0.0       0
5761  20230622   000500    000959  ...         0.0        0.0       0
5762  20230622   001000    001459  ...         0.0        0.0       0
5763  20230622   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 00:20:07,876:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29917.3, self.close=30145.7, self.high=30237.4, self.low=29908.4, self.vol=23104.444, self.amt=695473986.90638, ukdf['pct'].iloc[-1]=0.007203 , ukdf['amount'].iloc[-1]=695473986.90638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-45757.2005487663', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30150.63894505', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11105
self.closeSec=1687364699, self.tradeDate='20230622', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30151.1, self.close=30309.8, self.high=30316.4, self.low=30055.0, self.vol=16030.938, self.amt=483907629.69249 
2023-06-22 00:25:00,781:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230622   000000    000459  ...         0.0        0.0       0
5761  20230622   000500    000959  ...         0.0        0.0       0
5762  20230622   001000    001459  ...         0.0        0.0       0
5763  20230622   001500    001959  ...         0.0        0.0       0
5764  20230622   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 00:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687364699, self.tradeDate='20230622', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30151.1, self.close=30309.8, self.high=30316.4, self.low=30055.0, self.vol=16030.938, self.amt=483907629.69249, ukdf['pct'].iloc[-1]=0.005444 , ukdf['amount'].iloc[-1]=483907629.69249, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48082.20476748942', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30317.59314717', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29917.3, self.close=30145.7, self.high=30237.4, self.low=29908.4 
127.0.0.1 - - [22/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-22 00:20:05,096:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29917.3, self.close=30145.7, self.high=30237.4, self.low=29908.4   
2023-06-22 00:20:06,705:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230621   235500    235959  1687363199  ...  29813.7 -0.000616   1727    5
1440  20230622   000000    000459  1687363499  ...  29745.5  0.001170   1440    0
1441  20230622   000500    000959  1687363799  ...  29843.4  0.001634   1441    1
1442  20230622   001000    001459  1687364099  ...  29839.1  0.000314   1442    2
1443  20230622   001500    001959  1687364399  ...  29908.4  0.007203   1443    3

[5 rows x 11 columns]
2023-06-22 00:20:06,707:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=229, self.factor=0.1544692472106504, self.count=11107 

self.closeSec=1687364699, self.tradeDate='20230622', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30151.1, self.close=30309.8, self.high=30316.4, self.low=30055.0 
2023-06-22 00:25:00,771:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687364699, self.tradeDate='20230622', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30151.1, self.close=30309.8, self.high=30316.4, self.low=30055.0   
2023-06-22 00:25:00,804:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230622   000000    000459  1687363499  ...  29745.5  0.001170   1440    0
1441  20230622   000500    000959  1687363799  ...  29843.4  0.001634   1441    1
1442  20230622   001000    001459  1687364099  ...  29839.1  0.000314   1442    2
1443  20230622   001500    001959  1687364399  ...  29908.4  0.007203   1443    3
1444  20230622   002000    002459  1687364699  ...  30055.0  0.005444   1444    4

[5 rows x 11 columns]
2023-06-22 00:25:00,805:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-22 00:00:18,854:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230621    212959  28875.8  ...  57.916667  0.672461  0.121880
5803  20230621    215959  29036.3  ...  58.333333  0.694346  0.118240
5804  20230621    222959  29296.6  ...  58.333333  0.694362  0.116223
5805  20230621    225959  29297.0  ...  58.333333  0.711606  0.111004
5806  20230621    232959  29520.7  ...  58.333333  0.738108  0.104650

[5 rows x 33 columns]
0.5496323529411765
acc is : 0.5496323529411765
2023-06-22 00:00:18,944:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.534397  0.465603       1  ...  1.095183   1.0    0.0  1.142737
540     0  0.563886  0.436114       1  ...  1.095190   1.0    0.0  1.142745
541     0  0.525227  0.474773       1  ...  1.103557   1.0    0.0  1.151475
542     0  0.562108  0.437892       1  ...  1.118263   1.0    0.0  1.166819
543     0  0.627416  0.372584       0  ...  1.115381   1.0    0.0  1.163812

[5 rows x 10 columns]
2023-06-22 00:00:18,956:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.534087  0.465913       1  ...  1.095183   1.0    0.0  1.143505
46     0  0.563628  0.436372       1  ...  1.095190   1.0    0.0  1.147737
47     0  0.525329  0.474671       1  ...  1.103557   1.0    0.0  1.156504
48     0  0.562075  0.437925       1  ...  1.118263   1.0    0.0  1.164789
49     0  0.627416  0.372584       0  ...  1.115381   1.0    0.0  1.163812

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.893', 'enterprice': '27229', 'countrevence': '0', 'unrealprofit': '70635.39541141434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29855.53461538', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [22/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-22 00:00:04,190:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42434F1687363203519I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687363203932220, 'quantity': '25.484', 'price': '29836.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687363202579, 'updatetime': 1687363203932, 'tradetype': 'usdt', 'selfid': 42434, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687363203932, 'clientorderid': '42434F1687363203519I0L59', 'price': '29836.9', 'quantity': '25.484', 'commission': '760.3635596', 'commissionasset': 'USDT', 'tradetime': 1687363203932, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687363203932}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5552 

self.closeSec=1687363799, self.tradeDate='20230622', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29836.9', self.close='29920.7'
127.0.0.1 - - [22/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-22 00:10:01,135:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687363799, self.tradeDate='20230622', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29836.9', self.close='29920.7'
2023-06-22 00:10:01,148:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230621   232000    232959  1687361399  29715.7  29914.1  0.006680
573  20230621   233000    233959  1687361999    29914  29812.1 -0.003410
574  20230621   234000    234959  1687362599    29812  29798.7 -0.000449
575  20230621   235000    235959  1687363199  29798.8    29837  0.001285
576  20230622   000000    000959  1687363799  29836.9  29920.7  0.002805
2023-06-22 00:10:01,148:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5553 

self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29929.2', self.close='30145.7'
127.0.0.1 - - [22/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 00:20:07,496:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29929.2', self.close='30145.7'
2023-06-22 00:20:08,246:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230621   233000    233959  1687361999    29914  29812.1 -0.003410
574  20230621   234000    234959  1687362599    29812  29798.7 -0.000449
575  20230621   235000    235959  1687363199  29798.8    29837  0.001285
576  20230622   000000    000959  1687363799  29836.9  29920.7  0.002805
577  20230622   001000    001959  1687364399  29929.2  30145.7  0.007520
2023-06-22 00:20:08,255:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-22 00:00:02,091:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-22 00:00:02,168:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6220000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230621, closeTime:235959, close:29837, total:972975.8716388, pct_pre:0.06942872152301471, thd:-0.89433183698029, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5555 

self.closeSec=1687363799, self.tradeDate='20230622', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29836.9', self.close='29920.7'
2023-06-22 00:10:01,131:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687363799, self.tradeDate='20230622', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29836.9', self.close='29920.7'
127.0.0.1 - - [22/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-22 00:10:01,151:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230621   232000    232959  1687361399  29715.7  29914.1
17421  20230621   233000    233959  1687361999    29914  29812.1
17422  20230621   234000    234959  1687362599    29812  29798.7
17423  20230621   235000    235959  1687363199  29798.8    29837
17424  20230622   000000    000959  1687363799  29836.9  29920.7
2023-06-22 00:10:01,151:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5556 

self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29929.2', self.close='30145.7'
127.0.0.1 - - [22/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 00:20:09,510:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29929.2', self.close='30145.7'
2023-06-22 00:20:09,639:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230621   233000    233959  1687361999    29914  29812.1
17422  20230621   234000    234959  1687362599    29812  29798.7
17423  20230621   235000    235959  1687363199  29798.8    29837
17424  20230622   000000    000959  1687363799  29836.9  29920.7
17425  20230622   001000    001959  1687364399  29929.2  30145.7
2023-06-22 00:20:09,639:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-22 00:00:04,367:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42435F1687363203574I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687363203953873, 'quantity': '46.557', 'price': '29837', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687363202661, 'updatetime': 1687363203953, 'tradetype': 'usdt', 'selfid': 42435, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687363203953, 'clientorderid': '42435F1687363203574I0L2', 'price': '29837', 'quantity': '46.557', 'commission': '1389.121209', 'commissionasset': 'USDT', 'tradetime': 1687363203953, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687363203953}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5555 

self.closeSec=1687363799, self.tradeDate='20230622', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29836.9', self.close='29920.7'
2023-06-22 00:10:01,138:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687363799, self.tradeDate='20230622', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29836.9', self.close='29920.7'
2023-06-22 00:10:01,168:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230621   232000    232959  1687361399  29715.7  29914.1
12237  20230621   233000    233959  1687361999    29914  29812.1
12238  20230621   234000    234959  1687362599    29812  29798.7
12239  20230621   235000    235959  1687363199  29798.8    29837
12240  20230622   000000    000959  1687363799  29836.9  29920.7
2023-06-22 00:10:01,168:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5556 

self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29929.2', self.close='30145.7'
127.0.0.1 - - [22/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-22 00:20:09,039:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29929.2', self.close='30145.7'
2023-06-22 00:20:09,336:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230621   233000    233959  1687361999    29914  29812.1
12238  20230621   234000    234959  1687362599    29812  29798.7
12239  20230621   235000    235959  1687363199  29798.8    29837
12240  20230622   000000    000959  1687363799  29836.9  29920.7
12241  20230622   001000    001959  1687364399  29929.2  30145.7
2023-06-22 00:20:09,337:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11104
self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29917.3, self.close=30145.7, self.high=30237.4, self.low=29908.4, self.vol=23104.444, self.amt=695473986.90638 
127.0.0.1 - - [22/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-22 00:20:07,826:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230621   235500    235959  ...         0.0        0.0       0
5760  20230622   000000    000459  ...         0.0        0.0       0
5761  20230622   000500    000959  ...         0.0        0.0       0
5762  20230622   001000    001459  ...         0.0        0.0       0
5763  20230622   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 00:20:07,857:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687364399, self.tradeDate='20230622', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29917.3, self.close=30145.7, self.high=30237.4, self.low=29908.4, self.vol=23104.444, self.amt=695473986.90638, ukdf['pct'].iloc[-1]=0.007203 , ukdf['amount'].iloc[-1]=695473986.90638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '122555.8327182449', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30143.7450989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11105
self.closeSec=1687364699, self.tradeDate='20230622', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30151.1, self.close=30309.8, self.high=30316.4, self.low=30055.0, self.vol=16030.938, self.amt=483907629.69249 
2023-06-22 00:25:00,818:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230622   000000    000459  ...         0.0        0.0       0
5761  20230622   000500    000959  ...         0.0        0.0       0
5762  20230622   001000    001459  ...         0.0        0.0       0
5763  20230622   001500    001959  ...         0.0        0.0       0
5764  20230622   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-22 00:25:00,819:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687364699, self.tradeDate='20230622', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30151.1, self.close=30309.8, self.high=30316.4, self.low=30055.0, self.vol=16030.938, self.amt=483907629.69249, ukdf['pct'].iloc[-1]=0.005444 , ukdf['amount'].iloc[-1]=483907629.69249, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '129012.72307904097', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30317.59314717', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230621   120000    155959  1687334399  ...    723  1.191168  3.252635     1.0
724  20230621   160000    195959  1687348799  ...    724  1.195252  3.080212     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '50175.3664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28918.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [22/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=231
self.closeSec=1687363199, self.tradeDate='20230621', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28913.5, self.close=29837.0, self.high=30018.3, self.low=28858.2, self.vol=322372.247, self.amt=9486851852.10095 
2023-06-22 00:00:01,642:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687363199, self.tradeDate='20230621', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28913.5, self.close=29837.0, self.high=30018.3, self.low=28858.2, self.vol=322372.247, self.amt=9486851852.10095 
2023-06-22 00:00:01,665:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230621   040000    075959  ...  124303.400  3.498796e+09  0.011357
722  20230621   080000    115959  ...  169807.166  4.868144e+09  0.014634
723  20230621   120000    155959  ...   75606.358  2.179678e+09  0.005428
724  20230621   160000    195959  ...  108461.131  3.137990e+09  0.001840
725  20230621   200000    235959  ...  322372.247  9.486852e+09  0.031940

[5 rows x 11 columns]
2023-06-22 00:00:03,106:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230621   040000    075959  1687305599  ...    721  1.222639  4.235218     1.0
722  20230621   080000    115959  1687319999  ...    722  1.430877  4.638883     1.0
723  20230621   120000    155959  1687334399  ...    723  1.191168  3.252635     1.0
724  20230621   160000    195959  1687348799  ...    724  1.195252  3.080212     1.0
725  20230621   200000    235959  1687363199  ...    725  1.341041  3.423802     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '99388.0632352528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29840.85355495', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


