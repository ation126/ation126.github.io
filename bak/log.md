# 20230726 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20896
self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29237.5, self.close=29276.7, self.high=29287.9, self.low=29219.9, self.vol=2309.071, self.amt=67552740.2975 
127.0.0.1 - - [26/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 00:20:04,998:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230725   235500    235959  ...         0.0        0.0       0
5760  20230726   000000    000459  ...         0.0        0.0       0
5761  20230726   000500    000959  ...         0.0        0.0       0
5762  20230726   001000    001459  ...         0.0        0.0       0
5763  20230726   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 00:20:05,018:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29237.5, self.close=29276.7, self.high=29287.9, self.low=29219.9, self.vol=2309.071, self.amt=67552740.2975, ukdf['pct'].iloc[-1]=0.001341 , ukdf['amount'].iloc[-1]=67552740.2975, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33542.31108232818', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29273.51059043', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20897
self.closeSec=1690302299, self.tradeDate='20230726', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29276.6, self.close=29243.7, self.high=29276.7, self.low=29236.5, self.vol=1023.45, self.amt=29945338.5241 
2023-07-26 00:25:00,725:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230726   000000    000459  ...         0.0        0.0       0
5761  20230726   000500    000959  ...         0.0        0.0       0
5762  20230726   001000    001459  ...         0.0        0.0       0
5763  20230726   001500    001959  ...         0.0        0.0       0
5764  20230726   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 00:25:00,725:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690302299, self.tradeDate='20230726', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29276.6, self.close=29243.7, self.high=29276.7, self.low=29236.5, self.vol=1023.45, self.amt=29945338.5241, ukdf['pct'].iloc[-1]=-0.001127 , ukdf['amount'].iloc[-1]=29945338.5241, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33128.5614', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29243.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29237.5, self.close=29276.7, self.high=29287.9, self.low=29219.9 
127.0.0.1 - - [26/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 00:20:03,398:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29237.5, self.close=29276.7, self.high=29287.9, self.low=29219.9   
2023-07-26 00:20:04,429:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230725   235500    235959  1690300799  ...  29162.2 -0.000836   1727    5
1440  20230726   000000    000459  1690301099  ...  29165.5  0.000545   1440    0
1441  20230726   000500    000959  1690301399  ...  29183.1  0.001076   1441    1
1442  20230726   001000    001459  1690301699  ...  29213.6  0.000791   1442    2
1443  20230726   001500    001959  1690301999  ...  29219.9  0.001341   1443    3

[5 rows x 11 columns]
2023-07-26 00:20:04,438:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5867048615699731, self.count=20899 

self.closeSec=1690302299, self.tradeDate='20230726', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29276.6, self.close=29243.7, self.high=29276.7, self.low=29236.5 
2023-07-26 00:25:00,697:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690302299, self.tradeDate='20230726', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29276.6, self.close=29243.7, self.high=29276.7, self.low=29236.5   
2023-07-26 00:25:00,709:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230726   000000    000459  1690301099  ...  29165.5  0.000545   1440    0
1441  20230726   000500    000959  1690301399  ...  29183.1  0.001076   1441    1
1442  20230726   001000    001459  1690301699  ...  29213.6  0.000791   1442    2
1443  20230726   001500    001959  1690301999  ...  29219.9  0.001341   1443    3
1444  20230726   002000    002459  1690302299  ...  29236.5 -0.001127   1444    4

[5 rows x 11 columns]
2023-07-26 00:25:00,709:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-26 00:00:17,209:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230725    212959  29108.8  ...  50.000000  0.422508  0.500348
5803  20230725    215959  29134.9  ...  50.416667  0.469227  0.478137
5804  20230725    222959  29272.0  ...  50.416667  0.464110  0.463906
5805  20230725    225959  29253.6  ...  50.416667  0.439291  0.471268
5806  20230725    232959  29160.7  ...  50.416667  0.448076  0.472117

[5 rows x 33 columns]
0.5477941176470589
acc is : 0.5477941176470589
2023-07-26 00:00:17,276:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.495928  0.504072       1  ...  0.974340  -1.0    0.0  0.941343
540     0  0.537246  0.462754       0  ...  0.974949  -1.0    0.0  0.940754
541     0  0.504435  0.495565       0  ...  0.978045  -1.0    0.0  0.937767
542     1  0.476756  0.523244       1  ...  0.977136  -1.0    0.0  0.938638
543     0  0.508259  0.491741       0  ...  0.977832  -1.0    0.0  0.937969

[5 rows x 10 columns]
2023-07-26 00:00:17,287:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496191  0.503809       1  ...  0.956374  -1.0    0.0  0.934354
46     0  0.537288  0.462712       0  ...  0.974949  -1.0    0.0  0.935059
47     0  0.504697  0.495303       0  ...  0.978045  -1.0    0.0  0.932090
48     1  0.476698  0.523302       1  ...  0.977136  -1.0    0.0  0.933902
49     0  0.508259  0.491741       0  ...  0.977832  -1.0    0.0  0.937969

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '13723.86192968007', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29165.58535531', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [26/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-26 00:00:04,239:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42733F1690300803579I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690300803988707, 'quantity': '25.908', 'price': '29167.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690300802736, 'updatetime': 1690300803988, 'tradetype': 'usdt', 'selfid': 42733, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690300803988, 'clientorderid': '42733F1690300803579I0L59', 'price': '29167.1', 'quantity': '25.908', 'commission': '755.6612268', 'commissionasset': 'USDT', 'tradetime': 1690300803988, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690300803988}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10448 

self.closeSec=1690301399, self.tradeDate='20230726', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29167', self.close='29214.4'
127.0.0.1 - - [26/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-26 00:10:01,142:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690301399, self.tradeDate='20230726', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29167', self.close='29214.4'
2023-07-26 00:10:01,152:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230725   232000    232959  1690298999  29207.7  29187.8 -0.000678
573  20230725   233000    233959  1690299599  29187.9  29188.3  0.000017
574  20230725   234000    234959  1690300199  29188.2  29207.1  0.000644
575  20230725   235000    235959  1690300799  29207.2    29167 -0.001373
576  20230726   000000    000959  1690301399    29167  29214.4  0.001625
2023-07-26 00:10:01,154:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10449 

self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29214.4', self.close='29276.7'
127.0.0.1 - - [26/Jul/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-07-26 00:20:05,710:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29214.4', self.close='29276.7'
2023-07-26 00:20:06,099:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230725   233000    233959  1690299599  29187.9  29188.3  0.000017
574  20230725   234000    234959  1690300199  29188.2  29207.1  0.000644
575  20230725   235000    235959  1690300799  29207.2    29167 -0.001373
576  20230726   000000    000959  1690301399    29167  29214.4  0.001625
577  20230726   001000    001959  1690301999  29214.4  29276.7  0.002133
2023-07-26 00:20:06,100:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [26/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-26 00:00:04,071:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42732F1690300803461I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690300803853212, 'quantity': '34.499', 'price': '29167', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690300802624, 'updatetime': 1690300803853, 'tradetype': 'usdt', 'selfid': 42732, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690300803853, 'clientorderid': '42732F1690300803461I0L57', 'price': '29167', 'quantity': '34.499', 'commission': '1006.232333', 'commissionasset': 'USDT', 'tradetime': 1690300803853, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690300803853}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10451 

self.closeSec=1690301399, self.tradeDate='20230726', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29167', self.close='29214.4'
2023-07-26 00:10:01,143:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690301399, self.tradeDate='20230726', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29167', self.close='29214.4'
2023-07-26 00:10:01,157:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230725   232000    232959  1690298999  29207.7  29187.8
17421  20230725   233000    233959  1690299599  29187.9  29188.3
17422  20230725   234000    234959  1690300199  29188.2  29207.1
17423  20230725   235000    235959  1690300799  29207.2    29167
17424  20230726   000000    000959  1690301399    29167  29214.4
2023-07-26 00:10:01,157:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10452 

self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29214.4', self.close='29276.7'
127.0.0.1 - - [26/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 00:20:06,679:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29214.4', self.close='29276.7'
2023-07-26 00:20:06,775:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230725   233000    233959  1690299599  29187.9  29188.3
17422  20230725   234000    234959  1690300199  29188.2  29207.1
17423  20230725   235000    235959  1690300799  29207.2    29167
17424  20230726   000000    000959  1690301399    29167  29214.4
17425  20230726   001000    001959  1690301999  29214.4  29276.7
2023-07-26 00:20:06,775:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-26 00:00:04,331:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42734F1690300803595I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690300803964013, 'quantity': '37.643', 'price': '29167.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690300802705, 'updatetime': 1690300803964, 'tradetype': 'usdt', 'selfid': 42734, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690300803964, 'clientorderid': '42734F1690300803595I0L2', 'price': '29167.1', 'quantity': '37.643', 'commission': '1097.9371453', 'commissionasset': 'USDT', 'tradetime': 1690300803964, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690300803964}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10451 

self.closeSec=1690301399, self.tradeDate='20230726', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29167', self.close='29214.4'
2023-07-26 00:10:01,143:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690301399, self.tradeDate='20230726', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29167', self.close='29214.4'
2023-07-26 00:10:01,152:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230725   232000    232959  1690298999  29207.7  29187.8
12237  20230725   233000    233959  1690299599  29187.9  29188.3
12238  20230725   234000    234959  1690300199  29188.2  29207.1
12239  20230725   235000    235959  1690300799  29207.2    29167
12240  20230726   000000    000959  1690301399    29167  29214.4
2023-07-26 00:10:01,152:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10452 

self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29214.4', self.close='29276.7'
127.0.0.1 - - [26/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-26 00:20:06,578:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29214.4', self.close='29276.7'
2023-07-26 00:20:06,692:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230725   233000    233959  1690299599  29187.9  29188.3
12238  20230725   234000    234959  1690300199  29188.2  29207.1
12239  20230725   235000    235959  1690300799  29207.2    29167
12240  20230726   000000    000959  1690301399    29167  29214.4
12241  20230726   001000    001959  1690301999  29214.4  29276.7
2023-07-26 00:20:06,698:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20896
self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29237.5, self.close=29276.7, self.high=29287.9, self.low=29219.9, self.vol=2309.071, self.amt=67552740.2975 
127.0.0.1 - - [26/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-26 00:20:05,038:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230725   235500    235959  ...         0.0        0.0       0
5760  20230726   000000    000459  ...         0.0        0.0       0
5761  20230726   000500    000959  ...         0.0        0.0       0
5762  20230726   001000    001459  ...         0.0        0.0       0
5763  20230726   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 00:20:05,058:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690301999, self.tradeDate='20230726', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29237.5, self.close=29276.7, self.high=29287.9, self.low=29219.9, self.vol=2309.071, self.amt=67552740.2975, ukdf['pct'].iloc[-1]=0.001341 , ukdf['amount'].iloc[-1]=67552740.2975, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90234.45283916063', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29273.51059043', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20897
self.closeSec=1690302299, self.tradeDate='20230726', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29276.6, self.close=29243.7, self.high=29276.7, self.low=29236.5, self.vol=1023.45, self.amt=29945338.5241 
2023-07-26 00:25:00,734:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230726   000000    000459  ...         0.0        0.0       0
5761  20230726   000500    000959  ...         0.0        0.0       0
5762  20230726   001000    001459  ...         0.0        0.0       0
5763  20230726   001500    001959  ...         0.0        0.0       0
5764  20230726   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-26 00:25:00,734:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690302299, self.tradeDate='20230726', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29276.6, self.close=29243.7, self.high=29276.7, self.low=29236.5, self.vol=1023.45, self.amt=29945338.5241, ukdf['pct'].iloc[-1]=-0.001127 , ukdf['amount'].iloc[-1]=29945338.5241, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89127.2577', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29243.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-07-25 20:00:10,543:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42730F1690286405032I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690286405403872, 'quantity': '52.176', 'price': '29117.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690286404177, 'updatetime': 1690286405403, 'tradetype': 'usdt', 'selfid': 42730, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690286405403, 'clientorderid': '42730F1690286405032I0L65', 'price': '29117.6', 'quantity': '52.176', 'commission': '1519.2398976', 'commissionasset': 'USDT', 'tradetime': 1690286405403, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690286405403}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-25 20:00:10,544:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42730F1690286405032I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690286405403872, 'quantity': '52.176', 'price': '29117.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690286404177, 'updatetime': 1690286405403, 'tradetype': 'usdt', 'selfid': 42730, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690286405403, 'clientorderid': '42730F1690286405032I0L65', 'price': '29117.6', 'quantity': '52.176', 'commission': '1519.2398976', 'commissionasset': 'USDT', 'tradetime': 1690286405403, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690286405403}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jul/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-07-25 20:00:11,003:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42731F1690286410525I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690286410933621, 'quantity': '54.821', 'price': '29117.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690286410106, 'updatetime': 1690286410933, 'tradetype': 'usdt', 'selfid': 42731, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690286410933, 'clientorderid': '42731F1690286410525I0L65', 'price': '29117.6', 'quantity': '54.821', 'commission': '1596.2559496', 'commissionasset': 'USDT', 'tradetime': 1690286410933, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690286410933}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-25 20:00:11,095:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42731F1690286410525I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690286410933621, 'quantity': '54.821', 'price': '29117.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690286410106, 'updatetime': 1690286410933, 'tradetype': 'usdt', 'selfid': 42731, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690286410933, 'clientorderid': '42731F1690286410525I0L65', 'price': '29117.6', 'quantity': '54.821', 'commission': '1596.2559496', 'commissionasset': 'USDT', 'tradetime': 1690286410933, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690286410933}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jul/2023 20:00:11] "POST / HTTP/1.1" 200 -
--handleKline--:  127.0.0.1 - - [26/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=435
self.closeSec=1690300799, self.tradeDate='20230725', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29117.6, self.close=29167.0, self.high=29333.0, self.low=29058.0, self.vol=65595.464, self.amt=1916335937.10273 
2023-07-26 00:00:01,787:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690300799, self.tradeDate='20230725', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29117.6, self.close=29167.0, self.high=29333.0, self.low=29058.0, self.vol=65595.464, self.amt=1916335937.10273 
2023-07-26 00:00:01,828:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230725   040000    075959  ...  18811.829  5.482895e+08  0.001955
722  20230725   080000    115959  ...  27479.779  7.997241e+08 -0.002201
723  20230725   120000    155959  ...  17709.951  5.155998e+08  0.001124
724  20230725   160000    195959  ...  35393.284  1.032527e+09 -0.000505
725  20230725   200000    235959  ...  65595.464  1.916336e+09  0.001697

[5 rows x 11 columns]
2023-07-26 00:00:02,597:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230725   040000    075959  1690243199  ...    721  0.339939  0.031975     NaN
722  20230725   080000    115959  1690257599  ...    722  0.416269  0.327084     NaN
723  20230725   120000    155959  1690271999  ...    723  0.479340  0.567308     NaN
724  20230725   160000    195959  1690286399  ...    724  0.515390  0.696247     1.0
725  20230725   200000    235959  1690300799  ...    725  0.534944  0.754108     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '2708.1574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29167', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


