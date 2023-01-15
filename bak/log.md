# 20230115 10:37:23

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14070
self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102500', self.closeTime='102959', self.symbol='BTCUSDT', self.open=20762.1, self.close=20770.7, self.high=20780.0, self.low=20754.6, self.vol=659.875, self.amt=13703518.0632 
127.0.0.1 - - [15/Jan/2023 10:30:00] "POST / HTTP/1.1" 200 -
2023-01-15 10:30:00,906:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5881  20230115   100500    100959  ...         0.0        0.0       0
5882  20230115   101000    101459  ...         0.0        0.0       0
5883  20230115   101500    101959  ...         0.0        0.0       0
5884  20230115   102000    102459  ...         0.0        0.0       0
5885  20230115   102500    102959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 10:30:00,906:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102500', self.closeTime='102959',self.symbol='BTCUSDT',self.open=20762.1, self.close=20770.7, self.high=20780.0, self.low=20754.6, self.vol=659.875, self.amt=13703518.0632, ukdf['pct'].iloc[-1]=0.000409 , ukdf['amount'].iloc[-1]=13703518.0632, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5885, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-255178.98323711552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20769.84412452', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14071
self.closeSec=1673750099, self.tradeDate='20230115', self.openTime='103000', self.closeTime='103459', self.symbol='BTCUSDT', self.open=20770.7, self.close=20780.7, self.high=20797.3, self.low=20770.6, self.vol=871.707, self.amt=18119564.8188 
127.0.0.1 - - [15/Jan/2023 10:35:00] "POST / HTTP/1.1" 200 -
2023-01-15 10:35:00,555:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5882  20230115   101000    101459  ...         0.0        0.0       0
5883  20230115   101500    101959  ...         0.0        0.0       0
5884  20230115   102000    102459  ...         0.0        0.0       0
5885  20230115   102500    102959  ...         0.0        0.0       0
5886  20230115   103000    103459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 10:35:00,557:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673750099, self.tradeDate='20230115', self.openTime='103000', self.closeTime='103459',self.symbol='BTCUSDT',self.open=20770.7, self.close=20780.7, self.high=20797.3, self.low=20770.6, self.vol=871.707, self.amt=18119564.8188, ukdf['pct'].iloc[-1]=0.000481 , ukdf['amount'].iloc[-1]=18119564.8188, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5886, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-255790.1232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20780', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1564  20230115   102000    102459  1673749499  ...  20737.1  0.000771   1564    4
1565  20230115   102500    102959  1673749799  ...  20754.6  0.000409   1565    5

[5 rows x 11 columns]
2023-01-15 10:30:00,818:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-01-15 10:30:00,847:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
217  20230115   082500    082959  1673742599  ... -0.000645   1541    5  0.152264
218  20230115   085500    085959  1673744399  ...  0.000564   1547    5  0.158573
219  20230115   092500    092959  1673746199  ... -0.000705   1553    5  0.167083
220  20230115   095500    095959  1673747999  ... -0.000058   1559    5  0.172561
221  20230115   102500    102959  1673749799  ...  0.000409   1565    5  0.178493

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=356, self.factor=0.17849331648682476, self.count=14637 

self.closeSec=1673750099, self.tradeDate='20230115', self.openTime='103000', self.closeTime='103459', self.symbol='BTCUSDT', self.open=20770.7, self.close=20780.7, self.high=20797.3, self.low=20770.6 
2023-01-15 10:35:00,460:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673750099, self.tradeDate='20230115', self.openTime='103000', self.closeTime='103459',self.symbol='BTCUSDT',self.open=20770.7, self.close=20780.7, self.high=20797.3, self.low=20770.6   
127.0.0.1 - - [15/Jan/2023 10:35:00] "POST / HTTP/1.1" 200 -
2023-01-15 10:35:00,505:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1562  20230115   101000    101459  1673748899  ...  20731.0 -0.002012   1562    2
1563  20230115   101500    101959  1673749199  ...  20732.7  0.000545   1563    3
1564  20230115   102000    102459  1673749499  ...  20737.1  0.000771   1564    4
1565  20230115   102500    102959  1673749799  ...  20754.6  0.000409   1565    5
1566  20230115   103000    103459  1673750099  ...  20770.6  0.000481   1566    0

[5 rows x 11 columns]
2023-01-15 10:35:00,505:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-15 10:30:32,822:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5775  20230115    075959  21077.1  ...  56.666667  0.627802  0.323558
5776  20230115    082959  20962.8  ...  56.250000  0.621396  0.323310
5777  20230115    085959  20927.3  ...  55.833333  0.595989  0.333383
5778  20230115    092959  20774.7  ...  55.833333  0.584478  0.347649
5779  20230115    095959  20702.2  ...  56.250000  0.594160  0.355075

[5 rows x 33 columns]
0.5157116451016636
acc is : 0.5157116451016636
2023-01-15 10:30:32,985:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.490951  0.509049       0  ...  1.090208   1.0    0.0  1.257728
537     1  0.499039  0.500961       0  ...  1.082295   1.0    0.0  1.248598
538     1  0.462281  0.537719       0  ...  1.078559   1.0    0.0  1.244289
539     1  0.458715  0.541285       1  ...  1.083081   1.0    0.0  1.249506
540     1  0.488968  0.511032       0  ...  1.082133   1.0    0.0  1.248412

[5 rows x 10 columns]
2023-01-15 10:30:33,024:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491002  0.508998       0  ...  1.090208   1.0    0.0  1.258613
46     1  0.499082  0.500918       0  ...  1.082295   1.0    0.0  1.248095
47     1  0.462265  0.537735       0  ...  1.078559   1.0    0.0  1.244289
48     1  0.458491  0.541509       1  ...  1.083081   1.0    0.0  1.250174
49     1  0.488968  0.511032       0  ...  1.082133   1.0    0.0  1.248412

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

636  20230115   100000    100959  1673748599  20785.3  20776.7 -0.000587
2023-01-15 10:10:01,612:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7317 

self.closeSec=1673749199, self.tradeDate='20230115', self.openTime='101000', self.closeTime='101959', self.symbol='BTCUSDT', self.open='20776.7', self.close='20746.2'
2023-01-15 10:20:00,535:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673749199, self.tradeDate='20230115', self.openTime='101000', self.closeTime='101959',self.symbol='BTCUSDT',self.open='20776.7', self.close='20746.2'
127.0.0.1 - - [15/Jan/2023 10:20:00] "POST / HTTP/1.1" 200 -
2023-01-15 10:20:00,553:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
633  20230115   093000    093959  1673746799  20702.2    20752  0.002410
634  20230115   094000    094959  1673747399    20752  20780.1  0.001354
635  20230115   095000    095959  1673747999  20780.2  20788.9  0.000423
636  20230115   100000    100959  1673748599  20785.3  20776.7 -0.000587
637  20230115   101000    101959  1673749199  20776.7  20746.2 -0.001468
2023-01-15 10:20:00,553:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 10:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7318 

self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102000', self.closeTime='102959', self.symbol='BTCUSDT', self.open='20746.3', self.close='20770.7'
2023-01-15 10:30:01,263:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102000', self.closeTime='102959',self.symbol='BTCUSDT',self.open='20746.3', self.close='20770.7'
2023-01-15 10:30:01,319:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
634  20230115   094000    094959  1673747399    20752  20780.1  0.001354
635  20230115   095000    095959  1673747999  20780.2  20788.9  0.000423
636  20230115   100000    100959  1673748599  20785.3  20776.7 -0.000587
637  20230115   101000    101959  1673749199  20776.7  20746.2 -0.001468
638  20230115   102000    102959  1673749799  20746.3  20770.7  0.001181
2023-01-15 10:30:01,320:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17484  20230115   100000    100959  1673748599  20785.3  20776.7
2023-01-15 10:10:01,573:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7318 

self.closeSec=1673749199, self.tradeDate='20230115', self.openTime='101000', self.closeTime='101959', self.symbol='BTCUSDT', self.open='20776.7', self.close='20746.2'
127.0.0.1 - - [15/Jan/2023 10:20:00] "POST / HTTP/1.1" 200 -
2023-01-15 10:20:00,577:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673749199, self.tradeDate='20230115', self.openTime='101000', self.closeTime='101959',self.symbol='BTCUSDT',self.open='20776.7', self.close='20746.2'
2023-01-15 10:20:00,611:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17481  20230115   093000    093959  1673746799  20702.2    20752
17482  20230115   094000    094959  1673747399    20752  20780.1
17483  20230115   095000    095959  1673747999  20780.2  20788.9
17484  20230115   100000    100959  1673748599  20785.3  20776.7
17485  20230115   101000    101959  1673749199  20776.7  20746.2
2023-01-15 10:20:00,611:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 10:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7319 

self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102000', self.closeTime='102959', self.symbol='BTCUSDT', self.open='20746.3', self.close='20770.7'
2023-01-15 10:30:01,298:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102000', self.closeTime='102959',self.symbol='BTCUSDT',self.open='20746.3', self.close='20770.7'
2023-01-15 10:30:01,319:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17482  20230115   094000    094959  1673747399    20752  20780.1
17483  20230115   095000    095959  1673747999  20780.2  20788.9
17484  20230115   100000    100959  1673748599  20785.3  20776.7
17485  20230115   101000    101959  1673749199  20776.7  20746.2
17486  20230115   102000    102959  1673749799  20746.3  20770.7
2023-01-15 10:30:01,319:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12156  20230115   100000    100959  1673748599  20785.3  20776.7
2023-01-15 10:10:01,568:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jan/2023 10:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7318 

self.closeSec=1673749199, self.tradeDate='20230115', self.openTime='101000', self.closeTime='101959', self.symbol='BTCUSDT', self.open='20776.7', self.close='20746.2'
2023-01-15 10:20:00,567:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673749199, self.tradeDate='20230115', self.openTime='101000', self.closeTime='101959',self.symbol='BTCUSDT',self.open='20776.7', self.close='20746.2'
2023-01-15 10:20:00,610:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12153  20230115   093000    093959  1673746799  20702.2    20752
12154  20230115   094000    094959  1673747399    20752  20780.1
12155  20230115   095000    095959  1673747999  20780.2  20788.9
12156  20230115   100000    100959  1673748599  20785.3  20776.7
12157  20230115   101000    101959  1673749199  20776.7  20746.2
2023-01-15 10:20:00,610:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7319 

self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102000', self.closeTime='102959', self.symbol='BTCUSDT', self.open='20746.3', self.close='20770.7'
2023-01-15 10:30:01,269:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102000', self.closeTime='102959',self.symbol='BTCUSDT',self.open='20746.3', self.close='20770.7'
127.0.0.1 - - [15/Jan/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-01-15 10:30:01,315:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12154  20230115   094000    094959  1673747399    20752  20780.1
12155  20230115   095000    095959  1673747999  20780.2  20788.9
12156  20230115   100000    100959  1673748599  20785.3  20776.7
12157  20230115   101000    101959  1673749199  20776.7  20746.2
12158  20230115   102000    102959  1673749799  20746.3  20770.7
2023-01-15 10:30:01,315:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [15/Jan/2023 10:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10068
self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102500', self.closeTime='102959', self.symbol='BTCUSDT', self.open=20762.1, self.close=20770.7, self.high=20780.0, self.low=20754.6, self.vol=659.875, self.amt=13703518.0632 
2023-01-15 10:30:00,899:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5881  20230115   100500    100959  ...         0.0        0.0       0
5882  20230115   101000    101459  ...         0.0        0.0       0
5883  20230115   101500    101959  ...         0.0        0.0       0
5884  20230115   102000    102459  ...         0.0        0.0       0
5885  20230115   102500    102959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 10:30:00,900:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673749799, self.tradeDate='20230115', self.openTime='102500', self.closeTime='102959',self.symbol='BTCUSDT',self.open=20762.1, self.close=20770.7, self.high=20780.0, self.low=20754.6, self.vol=659.875, self.amt=13703518.0632, ukdf['pct'].iloc[-1]=0.000409 , ukdf['amount'].iloc[-1]=13703518.0632, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5885, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10069
self.closeSec=1673750099, self.tradeDate='20230115', self.openTime='103000', self.closeTime='103459', self.symbol='BTCUSDT', self.open=20770.7, self.close=20780.7, self.high=20797.3, self.low=20770.6, self.vol=871.707, self.amt=18119564.8188 
127.0.0.1 - - [15/Jan/2023 10:35:00] "POST / HTTP/1.1" 200 -
2023-01-15 10:35:00,556:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5882  20230115   101000    101459  ...         0.0        0.0       0
5883  20230115   101500    101959  ...         0.0        0.0       0
5884  20230115   102000    102459  ...         0.0        0.0       0
5885  20230115   102500    102959  ...         0.0        0.0       0
5886  20230115   103000    103459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 10:35:00,557:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673750099, self.tradeDate='20230115', self.openTime='103000', self.closeTime='103459',self.symbol='BTCUSDT',self.open=20770.7, self.close=20780.7, self.high=20797.3, self.low=20770.6, self.vol=871.707, self.amt=18119564.8188, ukdf['pct'].iloc[-1]=0.000481 , ukdf['amount'].iloc[-1]=18119564.8188, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5886, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230114   200000    235959  1673711999  ...    719  1.292952  1.376640     1.0
720  20230115   000000    035959  1673726399  ...    720  1.213180  1.171201     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '184335.0528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=304
self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20796.8, self.close=20962.8, self.high=21092.0, self.low=20773.9, self.vol=59647.002, self.amt=1249464723.83337 
2023-01-15 08:00:00,932:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20796.8, self.close=20962.8, self.high=21092.0, self.low=20773.9, self.vol=59647.002, self.amt=1249464723.83337 
2023-01-15 08:00:00,976:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230114   120000    155959  ...   75863.507  1.587466e+09 -0.003967
718  20230114   160000    195959  ...  208916.807  4.304202e+09 -0.008759
719  20230114   200000    235959  ...  186884.918  3.898285e+09  0.003072
720  20230115   000000    035959  ...   78646.183  1.636048e+09  0.000082
721  20230115   040000    075959  ...   59647.002  1.249465e+09  0.007890

[5 rows x 11 columns]
2023-01-15 08:00:02,930:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230114   120000    155959  1673683199  ...    717  1.289315  1.435970     1.0
718  20230114   160000    195959  1673697599  ...    718  1.303569  1.434301     1.0
719  20230114   200000    235959  1673711999  ...    719  1.292952  1.376640     1.0
720  20230115   000000    035959  1673726399  ...    720  1.213180  1.171201     1.0
721  20230115   040000    075959  1673740799  ...    721  1.161411  1.034070     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '192879.8784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20960.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


