# 20230208 00:35:57

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [08/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20862
self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22876.0, self.close=22930.7, self.high=22935.9, self.low=22875.0, self.vol=2320.811, self.amt=53181071.9582 
2023-02-08 00:30:00,791:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230208   000500    000959  ...         0.0        0.0       0
5762  20230208   001000    001459  ...         0.0        0.0       0
5763  20230208   001500    001959  ...         0.0        0.0       0
5764  20230208   002000    002459  ...         0.0        0.0       0
5765  20230208   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 00:30:00,791:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22876.0, self.close=22930.7, self.high=22935.9, self.low=22875.0, self.vol=2320.811, self.amt=53181071.9582, ukdf['pct'].iloc[-1]=0.002339 , ukdf['amount'].iloc[-1]=53181071.9582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-385336.9322380168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22932.79860805', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20863
self.closeSec=1675787699, self.tradeDate='20230208', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22931.1, self.close=22994.8, self.high=23023.0, self.low=22928.7, self.vol=4119.331, self.amt=94663890.8305 
127.0.0.1 - - [08/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:35:00,541:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230208   001000    001459  ...         0.0        0.0       0
5763  20230208   001500    001959  ...         0.0        0.0       0
5764  20230208   002000    002459  ...         0.0        0.0       0
5765  20230208   002500    002959  ...         0.0        0.0       0
5766  20230208   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 00:35:00,542:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675787699, self.tradeDate='20230208', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22931.1, self.close=22994.8, self.high=23023.0, self.low=22928.7, self.vol=4119.331, self.amt=94663890.8305, ukdf['pct'].iloc[-1]=0.002795 , ukdf['amount'].iloc[-1]=94663890.8305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-389130.64027217232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22995.84214757', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230208   002000    002459  1675787099  ...  22860.1 -0.000904   1444    4
1445  20230208   002500    002959  1675787399  ...  22875.0  0.002339   1445    5

[5 rows x 11 columns]
2023-02-08 00:30:00,742:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-08 00:30:00,817:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230207   222500    222959  1675780199  ... -0.001773   1709    5  0.468893
198  20230207   225500    225959  1675781999  ... -0.000500   1715    5  0.463938
199  20230207   232500    232959  1675783799  ... -0.002109   1721    5  0.462214
200  20230207   235500    235959  1675785599  ...  0.000253   1727    5  0.460403
201  20230208   002500    002959  1675787399  ...  0.002339   1445    5  0.456446

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=48, self.factor=0.4564455301032881, self.count=21429 

self.closeSec=1675787699, self.tradeDate='20230208', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22931.1, self.close=22994.8, self.high=23023.0, self.low=22928.7 
2023-02-08 00:35:00,456:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675787699, self.tradeDate='20230208', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22931.1, self.close=22994.8, self.high=23023.0, self.low=22928.7   
127.0.0.1 - - [08/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:35:00,516:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230208   001000    001459  1675786499  ...  22908.6 -0.000362   1442    2
1443  20230208   001500    001959  1675786799  ...  22895.7 -0.000921   1443    3
1444  20230208   002000    002459  1675787099  ...  22860.1 -0.000904   1444    4
1445  20230208   002500    002959  1675787399  ...  22875.0  0.002339   1445    5
1446  20230208   003000    003459  1675787699  ...  22928.7  0.002795   1446    0

[5 rows x 11 columns]
2023-02-08 00:35:00,517:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-08 00:30:31,688:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230207    215959  22966.6  ...  46.666667  0.496491  0.398103
5756  20230207    222959  22973.5  ...  46.250000  0.494154  0.392432
5757  20230207    225959  22963.8  ...  46.666667  0.495124  0.386684
5758  20230207    232959  22968.3  ...  46.250000  0.475587  0.385888
5759  20230207    235959  22896.5  ...  46.250000  0.476148  0.384799

[5 rows x 33 columns]
0.5009276437847866
acc is : 0.5009276437847866
2023-02-08 00:30:31,831:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.488844  0.511156       0  ...  1.020253  -1.0    0.0  1.000959
535     1  0.488435  0.511565       1  ...  1.020102  -1.0    0.0  1.001107
536     1  0.489155  0.510845       0  ...  1.023273  -1.0    0.0  0.997995
537     1  0.466634  0.533366       1  ...  1.023188  -1.0    0.0  0.998078
538     1  0.483211  0.516789       1  ...  1.021750  -1.0    0.0  0.999481

[5 rows x 10 columns]
2023-02-08 00:30:31,864:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486280  0.513720       0  ...  1.020253  -1.0    0.0  0.998800
46     1  0.485813  0.514187       1  ...  1.020102  -1.0    0.0  0.998947
47     1  0.487363  0.512637       0  ...  1.023273  -1.0    0.0  0.996458
48     1  0.463848  0.536152       1  ...  1.023188  -1.0    0.0  0.992661
49     1  0.483211  0.516789       1  ...  1.021750  -1.0    0.0  0.999481

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.436', 'enterprice': '22744.1', 'countrevence': '0', 'unrealprofit': '-6256.9044', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22937', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230208   000000    000959  1675786199  22898.9  22927.3  0.001245
2023-02-08 00:10:01,618:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10713 

self.closeSec=1675786799, self.tradeDate='20230208', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22927.4', self.close='22897.9'
2023-02-08 00:20:00,527:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675786799, self.tradeDate='20230208', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22927.4', self.close='22897.9'
127.0.0.1 - - [08/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:20:00,552:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230207   233000    233959  1675784399  22896.5  22932.1  0.001537
574  20230207   234000    234959  1675784999  22932.1  22909.8 -0.000972
575  20230207   235000    235959  1675785599  22909.8  22898.8 -0.000480
576  20230208   000000    000959  1675786199  22898.9  22927.3  0.001245
577  20230208   001000    001959  1675786799  22927.4  22897.9 -0.001282
2023-02-08 00:20:00,552:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10714 

self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22897.9', self.close='22931'
127.0.0.1 - - [08/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:30:00,888:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22897.9', self.close='22931'
2023-02-08 00:30:00,932:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230207   234000    234959  1675784999  22932.1  22909.8 -0.000972
575  20230207   235000    235959  1675785599  22909.8  22898.8 -0.000480
576  20230208   000000    000959  1675786199  22898.9  22927.3  0.001245
577  20230208   001000    001959  1675786799  22927.4  22897.9 -0.001282
578  20230208   002000    002959  1675787399  22897.9    22931  0.001446
2023-02-08 00:30:00,932:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230208   000000    000959  1675786199  22898.9  22927.3
2023-02-08 00:10:01,628:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10714 

self.closeSec=1675786799, self.tradeDate='20230208', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22927.4', self.close='22897.9'
127.0.0.1 - - [08/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:20:00,554:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675786799, self.tradeDate='20230208', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22927.4', self.close='22897.9'
2023-02-08 00:20:00,570:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230207   233000    233959  1675784399  22896.5  22932.1
17422  20230207   234000    234959  1675784999  22932.1  22909.8
17423  20230207   235000    235959  1675785599  22909.8  22898.8
17424  20230208   000000    000959  1675786199  22898.9  22927.3
17425  20230208   001000    001959  1675786799  22927.4  22897.9
2023-02-08 00:20:00,570:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10715 

self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22897.9', self.close='22931'
127.0.0.1 - - [08/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:30:00,891:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22897.9', self.close='22931'
2023-02-08 00:30:00,909:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230207   234000    234959  1675784999  22932.1  22909.8
17423  20230207   235000    235959  1675785599  22909.8  22898.8
17424  20230208   000000    000959  1675786199  22898.9  22927.3
17425  20230208   001000    001959  1675786799  22927.4  22897.9
17426  20230208   002000    002959  1675787399  22897.9    22931
2023-02-08 00:30:00,909:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230208   000000    000959  1675786199  22898.9  22927.3
2023-02-08 00:10:01,623:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10714 

self.closeSec=1675786799, self.tradeDate='20230208', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22927.4', self.close='22897.9'
2023-02-08 00:20:00,532:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675786799, self.tradeDate='20230208', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22927.4', self.close='22897.9'
127.0.0.1 - - [08/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:20:00,559:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230207   233000    233959  1675784399  22896.5  22932.1
12238  20230207   234000    234959  1675784999  22932.1  22909.8
12239  20230207   235000    235959  1675785599  22909.8  22898.8
12240  20230208   000000    000959  1675786199  22898.9  22927.3
12241  20230208   001000    001959  1675786799  22927.4  22897.9
2023-02-08 00:20:00,562:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [08/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10715 

self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22897.9', self.close='22931'
2023-02-08 00:30:00,921:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22897.9', self.close='22931'
2023-02-08 00:30:00,939:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230207   234000    234959  1675784999  22932.1  22909.8
12239  20230207   235000    235959  1675785599  22909.8  22898.8
12240  20230208   000000    000959  1675786199  22898.9  22927.3
12241  20230208   001000    001959  1675786799  22927.4  22897.9
12242  20230208   002000    002959  1675787399  22897.9    22931
2023-02-08 00:30:00,939:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [08/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16860
self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22876.0, self.close=22930.7, self.high=22935.9, self.low=22875.0, self.vol=2320.811, self.amt=53181071.9582 
2023-02-08 00:30:00,807:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230208   000500    000959  ...         0.0        0.0       0
5762  20230208   001000    001459  ...         0.0        0.0       0
5763  20230208   001500    001959  ...         0.0        0.0       0
5764  20230208   002000    002459  ...         0.0        0.0       0
5765  20230208   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 00:30:00,815:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675787399, self.tradeDate='20230208', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22876.0, self.close=22930.7, self.high=22935.9, self.low=22875.0, self.vol=2320.811, self.amt=53181071.9582, ukdf['pct'].iloc[-1]=0.002339 , ukdf['amount'].iloc[-1]=53181071.9582, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16861
self.closeSec=1675787699, self.tradeDate='20230208', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22931.1, self.close=22994.8, self.high=23023.0, self.low=22928.7, self.vol=4119.331, self.amt=94663890.8305 
127.0.0.1 - - [08/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 00:35:00,485:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230208   001000    001459  ...         0.0        0.0       0
5763  20230208   001500    001959  ...         0.0        0.0       0
5764  20230208   002000    002459  ...         0.0        0.0       0
5765  20230208   002500    002959  ...         0.0        0.0       0
5766  20230208   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 00:35:00,485:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675787699, self.tradeDate='20230208', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22931.1, self.close=22994.8, self.high=23023.0, self.low=22928.7, self.vol=4119.331, self.amt=94663890.8305, ukdf['pct'].iloc[-1]=0.002795 , ukdf['amount'].iloc[-1]=94663890.8305, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230207   120000    155959  1675756799  ...    723  0.552062  0.189306     NaN
724  20230207   160000    195959  1675771199  ...    724  0.573397  0.297555     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-28382.254046475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22971.67750625', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=446
self.closeSec=1675785599, self.tradeDate='20230207', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22970.4, self.close=22898.8, self.high=23032.1, self.low=22869.0, self.vol=52655.269, self.amt=1208872158.7456 
127.0.0.1 - - [08/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-08 00:00:01,318:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675785599, self.tradeDate='20230207', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22970.4, self.close=22898.8, self.high=23032.1, self.low=22869.0, self.vol=52655.269, self.amt=1208872158.7456 
2023-02-08 00:00:01,352:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230207   040000    075959  ...  67427.476  1.538921e+09 -0.011661
722  20230207   080000    115959  ...  36711.889  8.380403e+08  0.004974
723  20230207   120000    155959  ...  30655.972  7.023361e+08  0.001517
724  20230207   160000    195959  ...  48654.335  1.117097e+09  0.002829
725  20230207   200000    235959  ...  52655.269  1.208872e+09 -0.003117

[5 rows x 11 columns]
2023-02-08 00:00:03,660:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230207   040000    075959  1675727999  ...    721  0.528222  0.049603     NaN
722  20230207   080000    115959  1675742399  ...    722  0.536839  0.106405     NaN
723  20230207   120000    155959  1675756799  ...    723  0.552062  0.189306     NaN
724  20230207   160000    195959  1675771199  ...    724  0.573397  0.297555     NaN
725  20230207   200000    235959  1675785599  ...    725  0.575800  0.331884     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-31190.53142790804', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22899.60386439', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


