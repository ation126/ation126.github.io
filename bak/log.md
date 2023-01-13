# 20230114 00:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13658
self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=19177.8, self.close=19142.5, self.high=19203.9, self.low=19140.4, self.vol=4736.911, self.amt=90838497.6453 
127.0.0.1 - - [14/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-14 00:10:01,472:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230113   234500    234959  ...         0.0        0.0       0
5758  20230113   235000    235459  ...         0.0        0.0       0
5759  20230113   235500    235959  ...         0.0        0.0       0
5760  20230114   000000    000459  ...         0.0        0.0       0
5761  20230114   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 00:10:01,473:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=19177.8, self.close=19142.5, self.high=19203.9, self.low=19140.4, self.vol=4736.911, self.amt=90838497.6453, ukdf['pct'].iloc[-1]=-0.002023 , ukdf['amount'].iloc[-1]=90838497.6453, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-157615.54386561616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19148.54261941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13659
self.closeSec=1673626499, self.tradeDate='20230114', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=19142.5, self.close=19128.5, self.high=19160.0, self.low=19122.0, self.vol=6272.013, self.amt=120037306.9354 
127.0.0.1 - - [14/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
2023-01-14 00:15:00,640:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230113   235000    235459  ...         0.0        0.0       0
5759  20230113   235500    235959  ...         0.0        0.0       0
5760  20230114   000000    000459  ...         0.0        0.0       0
5761  20230114   000500    000959  ...         0.0        0.0       0
5762  20230114   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 00:15:00,641:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673626499, self.tradeDate='20230114', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=19142.5, self.close=19128.5, self.high=19160.0, self.low=19122.0, self.vol=6272.013, self.amt=120037306.9354, ukdf['pct'].iloc[-1]=-0.000731 , ukdf['amount'].iloc[-1]=120037306.9354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-156502.47108227984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19130.04566409', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=287, self.factor=0.22230580637432484, self.count=14224 

self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=19177.8, self.close=19142.5, self.high=19203.9, self.low=19140.4 
2023-01-14 00:10:01,436:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=19177.8, self.close=19142.5, self.high=19203.9, self.low=19140.4   
2023-01-14 00:10:01,585:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1437  20230113   234500    234959  1673624999  ...  19208.8  0.001686   1725    3
1438  20230113   235000    235459  1673625299  ...  19222.4 -0.000359   1726    4
1439  20230113   235500    235959  1673625599  ...  19239.0  0.000655   1727    5
1440  20230114   000000    000459  1673625899  ...  19175.4 -0.003698   1440    0
1441  20230114   000500    000959  1673626199  ...  19140.4 -0.002023   1441    1

[5 rows x 11 columns]
2023-01-14 00:10:01,589:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=287, self.factor=0.22230580637432484, self.count=14225 

self.closeSec=1673626499, self.tradeDate='20230114', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=19142.5, self.close=19128.5, self.high=19160.0, self.low=19122.0 
2023-01-14 00:15:00,581:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673626499, self.tradeDate='20230114', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=19142.5, self.close=19128.5, self.high=19160.0, self.low=19122.0   
2023-01-14 00:15:00,661:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230113   235000    235459  1673625299  ...  19222.4 -0.000359   1726    4
1439  20230113   235500    235959  1673625599  ...  19239.0  0.000655   1727    5
1440  20230114   000000    000459  1673625899  ...  19175.4 -0.003698   1440    0
1441  20230114   000500    000959  1673626199  ...  19140.4 -0.002023   1441    1
1442  20230114   001000    001459  1673626499  ...  19122.0 -0.000731   1442    2

[5 rows x 11 columns]
2023-01-14 00:15:00,661:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-14 00:00:35,996:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230113    212959  18855.1  ...  57.500000  0.610211  0.218938
5803  20230113    215959  18865.7  ...  57.500000  0.604899  0.240038
5804  20230113    222959  18845.8  ...  57.500000  0.617335  0.250397
5805  20230113    225959  18917.1  ...  57.500000  0.630349  0.257282
5806  20230113    232959  18990.0  ...  57.916667  0.669670  0.242247

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-01-14 00:00:36,179:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.488659  0.511341       0  ...  1.016383   1.0    0.0  1.127647
540     1  0.486396  0.513604       1  ...  1.020250   1.0    0.0  1.131937
541     0  0.519357  0.480643       1  ...  1.024489   1.0    0.0  1.136640
542     0  0.533538  0.466462       1  ...  1.039029   1.0    0.0  1.152772
543     0  0.606954  0.393046       0  ...  1.038317   1.0    0.0  1.151982

[5 rows x 10 columns]
2023-01-14 00:00:36,204:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488757  0.511243       0  ...  1.016383   1.0    0.0  1.132567
46     1  0.486464  0.513536       1  ...  1.020250   1.0    0.0  1.137388
47     0  0.519289  0.480711       1  ...  1.024489   1.0    0.0  1.142114
48     0  0.533314  0.466686       1  ...  1.039029   1.0    0.0  1.151683
49     0  0.606954  0.393046       0  ...  1.038317   1.0    0.0  1.151982

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-01-14 00:00:01,214:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
571  20230113   231000    231959  1673623199  19109.9    19148  0.001999
572  20230113   232000    232959  1673623799  19152.9  19270.9  0.006418
573  20230113   233000    233959  1673624399  19270.8  19241.2 -0.001541
574  20230113   234000    234959  1673624999  19241.1  19246.8  0.000291
575  20230113   235000    235959  1673625599  19246.9  19252.5  0.000296
2023-01-14 00:00:01,215:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '48.387', 'enterprice': '18854.1', 'countrevence': '0', 'unrealprofit': '19277.3808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19252.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-14 00:00:01,901:INFO:modifiedmom:main.py:267:closeBuy:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-14 00:00:01,901:INFO:modifiedmom:main.py:268:closeBuy:185213: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 48.387, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41524F1673625601899I0L59'}
2023-01-14 00:00:01,928:INFO:modifiedmom:main.py:206:insertFactor:185213: curDateTime:1140000, name:modifiedmom, symbol:BTCUSDT, tradeDate:20230113, closeTime:235959, close:19252.5, total:911381.0433633, mom:0.01920446077767668, thd:0.0, side:sell 
2023-01-14 00:00:02,566:INFO:modifiedmom:main.py:316:handleOrderNew:185213: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41524F1673625601899I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673625602016235, 'quantity': '48.387', 'price': '19252.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673625601466, 'updatetime': 1673625602016, 'tradetype': 'usdt', 'selfid': 41524, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673625602016, 'clientorderid': '41524F1673625601899I0L59', 'price': '19252.2', 'quantity': '48.387', 'commission': '931.5562014', 'commissionasset': 'USDT', 'tradetime': 1673625602016, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673625602016}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-14 00:00:02,755:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41524F1673625601899I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673625602016235, 'quantity': '48.387', 'price': '19252.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673625601466, 'updatetime': 1673625602016, 'tradetype': 'usdt', 'selfid': 41524, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673625602016, 'clientorderid': '41524F1673625601899I0L59', 'price': '19252.2', 'quantity': '48.387', 'commission': '931.5562014', 'commissionasset': 'USDT', 'tradetime': 1673625602016, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673625602016}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7112 

self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='19252.6', self.close='19142.5'
2023-01-14 00:10:01,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='19252.6', self.close='19142.5'
2023-01-14 00:10:01,591:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230113   232000    232959  1673623799  19152.9  19270.9  0.006418
573  20230113   233000    233959  1673624399  19270.8  19241.2 -0.001541
574  20230113   234000    234959  1673624999  19241.1  19246.8  0.000291
575  20230113   235000    235959  1673625599  19246.9  19252.5  0.000296
576  20230114   000000    000959  1673626199  19252.6  19142.5 -0.005714
2023-01-14 00:10:01,591:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-01-14 00:00:01,223:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17419  20230113   231000    231959  1673623199  19109.9    19148
17420  20230113   232000    232959  1673623799  19152.9  19270.9
17421  20230113   233000    233959  1673624399  19270.8  19241.2
17422  20230113   234000    234959  1673624999  19241.1  19246.8
17423  20230113   235000    235959  1673625599  19246.9  19252.5
2023-01-14 00:00:01,223:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
closeBuy: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '49.426', 'enterprice': '18901.5', 'countrevence': '0', 'unrealprofit': '17348.526', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19252.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-14 00:00:01,855:INFO:pyemd2:main.py:251:closeBuy:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-14 00:00:01,855:INFO:pyemd2:main.py:252:closeBuy:185189: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 49.426, sell ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41522F1673625601850I0L57'}
2023-01-14 00:00:01,896:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:1140000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230113, closeTime:235959, close:19252.5, total:933291.313461, pct_pre:0.0460507382728621, thd:0.4845439171472356, side:sell 
2023-01-14 00:00:02,313:INFO:pyemd2:main.py:300:handleOrderNew:185189: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41522F1673625601850I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673625602202165, 'quantity': '49.426', 'price': '19252.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673625601424, 'updatetime': 1673625602202, 'tradetype': 'usdt', 'selfid': 41522, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673625602202, 'clientorderid': '41522F1673625601850I0L57', 'price': '19252.2', 'quantity': '49.426', 'commission': '951.5592372', 'commissionasset': 'USDT', 'tradetime': 1673625602202, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673625602202}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-14 00:00:02,549:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41522F1673625601850I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673625602202165, 'quantity': '49.426', 'price': '19252.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1673625601424, 'updatetime': 1673625602202, 'tradetype': 'usdt', 'selfid': 41522, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673625602202, 'clientorderid': '41522F1673625601850I0L57', 'price': '19252.2', 'quantity': '49.426', 'commission': '951.5592372', 'commissionasset': 'USDT', 'tradetime': 1673625602202, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673625602202}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7113 

self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='19252.6', self.close='19142.5'
127.0.0.1 - - [14/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-01-14 00:10:01,546:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='19252.6', self.close='19142.5'
2023-01-14 00:10:01,585:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230113   232000    232959  1673623799  19152.9  19270.9
17421  20230113   233000    233959  1673624399  19270.8  19241.2
17422  20230113   234000    234959  1673624999  19241.1  19246.8
17423  20230113   235000    235959  1673625599  19246.9  19252.5
17424  20230114   000000    000959  1673626199  19252.6  19142.5
2023-01-14 00:10:01,585:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-01-14 00:00:01,217:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12235  20230113   231000    231959  1673623199  19109.9    19148
12236  20230113   232000    232959  1673623799  19152.9  19270.9
12237  20230113   233000    233959  1673624399  19270.8  19241.2
12238  20230113   234000    234959  1673624999  19241.1  19246.8
12239  20230113   235000    235959  1673625599  19246.9  19252.5
2023-01-14 00:00:01,217:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
closeSell: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '64.463', 'enterprice': '18906.1', 'countrevence': '0', 'unrealprofit': '-22329.9832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '19252.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-01-14 00:00:01,892:INFO:testStrategy:main.py:253:closeSell:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
2023-01-14 00:00:01,892:INFO:testStrategy:main.py:254:closeSell:185174: ret = self.client.insertMarketUOrder("simulator",  BTCUSDT, 64.463, buy ), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '41523F1673625601887I0L2'}
2023-01-14 00:00:01,931:INFO:testStrategy:main.py:172:insertFactor:185174: curDateTime:1140000, name:testStrategy, symbol:BTCUSDT, tradeDate:20230113, closeTime:235959, close:19252.5, total:1217525.1803757, corrDate:20221024, corrVal:0.8673151129480913, side:buy 
2023-01-14 00:00:02,079:INFO:testStrategy:main.py:305:handleOrderNew:185174: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41523F1673625601887I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673625602013318, 'quantity': '64.463', 'price': '19252.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673625601408, 'updatetime': 1673625602013, 'tradetype': 'usdt', 'selfid': 41523, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673625602013, 'clientorderid': '41523F1673625601887I0L2', 'price': '19252.3', 'quantity': '64.463', 'commission': '1241.0610149', 'commissionasset': 'USDT', 'tradetime': 1673625602013, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673625602013}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Jan/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-01-14 00:00:02,274:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41523F1673625601887I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1673625602013318, 'quantity': '64.463', 'price': '19252.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1673625601408, 'updatetime': 1673625602013, 'tradetype': 'usdt', 'selfid': 41523, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1673625602013, 'clientorderid': '41523F1673625601887I0L2', 'price': '19252.3', 'quantity': '64.463', 'commission': '1241.0610149', 'commissionasset': 'USDT', 'tradetime': 1673625602013, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1673625602013}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [14/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7113 

self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='19252.6', self.close='19142.5'
2023-01-14 00:10:01,534:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='19252.6', self.close='19142.5'
2023-01-14 00:10:01,575:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230113   232000    232959  1673623799  19152.9  19270.9
12237  20230113   233000    233959  1673624399  19270.8  19241.2
12238  20230113   234000    234959  1673624999  19241.1  19246.8
12239  20230113   235000    235959  1673625599  19246.9  19252.5
12240  20230114   000000    000959  1673626199  19252.6  19142.5
2023-01-14 00:10:01,575:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/Jan/2023 00:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9656
self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=19177.8, self.close=19142.5, self.high=19203.9, self.low=19140.4, self.vol=4736.911, self.amt=90838497.6453 
2023-01-14 00:10:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5757  20230113   234500    234959  ...         0.0        0.0       0
5758  20230113   235000    235459  ...         0.0        0.0       0
5759  20230113   235500    235959  ...         0.0        0.0       0
5760  20230114   000000    000459  ...         0.0        0.0       0
5761  20230114   000500    000959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 00:10:01,615:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673626199, self.tradeDate='20230114', self.openTime='000500', self.closeTime='000959',self.symbol='BTCUSDT',self.open=19177.8, self.close=19142.5, self.high=19203.9, self.low=19140.4, self.vol=4736.911, self.amt=90838497.6453, ukdf['pct'].iloc[-1]=-0.002023 , ukdf['amount'].iloc[-1]=90838497.6453, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5761, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--: 127.0.0.1 - - [14/Jan/2023 00:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9657
self.closeSec=1673626499, self.tradeDate='20230114', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=19142.5, self.close=19128.5, self.high=19160.0, self.low=19122.0, self.vol=6272.013, self.amt=120037306.9354 
2023-01-14 00:15:00,646:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5758  20230113   235000    235459  ...         0.0        0.0       0
5759  20230113   235500    235959  ...         0.0        0.0       0
5760  20230114   000000    000459  ...         0.0        0.0       0
5761  20230114   000500    000959  ...         0.0        0.0       0
5762  20230114   001000    001459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-14 00:15:00,646:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673626499, self.tradeDate='20230114', self.openTime='001000', self.closeTime='001459',self.symbol='BTCUSDT',self.open=19142.5, self.close=19128.5, self.high=19160.0, self.low=19122.0, self.vol=6272.013, self.amt=120037306.9354, ukdf['pct'].iloc[-1]=-0.000731 , ukdf['amount'].iloc[-1]=120037306.9354, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5762, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230113   120000    155959  1673596799  ...    723  1.171585  1.361232     1.0
724  20230113   160000    195959  1673611199  ...    724  1.132857  1.238241     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '88209.6', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18913.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [14/Jan/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=296
self.closeSec=1673625599, self.tradeDate='20230113', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=18911.7, self.close=19252.5, self.high=19299.2, self.low=18801.4, self.vol=200752.474, self.amt=3826630336.00713 
2023-01-14 00:00:01,053:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673625599, self.tradeDate='20230113', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=18911.7, self.close=19252.5, self.high=19299.2, self.low=18801.4, self.vol=200752.474, self.amt=3826630336.00713 
2023-01-14 00:00:01,155:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230113   040000    075959  ...  124572.563  2.353820e+09 -0.002077
722  20230113   080000    115959  ...   48452.132  9.110449e+08  0.001784
723  20230113   120000    155959  ...   30968.560  5.827712e+08 -0.002856
724  20230113   160000    195959  ...  102428.168  1.939314e+09  0.004995
725  20230113   200000    235959  ...  200752.474  3.826630e+09  0.018021

[5 rows x 11 columns]
2023-01-14 00:00:03,154:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230113   040000    075959  1673567999  ...    721  1.431327  2.104170     1.0
722  20230113   080000    115959  1673582399  ...    722  1.302623  1.722950     1.0
723  20230113   120000    155959  1673596799  ...    723  1.171585  1.361232     1.0
724  20230113   160000    195959  1673611199  ...    724  1.132857  1.238241     1.0
725  20230113   200000    235959  1673625599  ...    725  1.171959  1.306448     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '105567.25225505344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '19252.64094679', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


