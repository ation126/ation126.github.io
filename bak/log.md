# 20230203 00:35:50

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [03/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19422
self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23841.9, self.close=23857.9, self.high=23865.9, self.low=23822.6, self.vol=1851.312, self.amt=44152476.806 
2023-02-03 00:30:01,009:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230203   000500    000959  ...         0.0        0.0       0
5762  20230203   001000    001459  ...         0.0        0.0       0
5763  20230203   001500    001959  ...         0.0        0.0       0
5764  20230203   002000    002459  ...         0.0        0.0       0
5765  20230203   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 00:30:01,011:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23841.9, self.close=23857.9, self.high=23865.9, self.low=23822.6, self.vol=1851.312, self.amt=44152476.806, ukdf['pct'].iloc[-1]=0.000675 , ukdf['amount'].iloc[-1]=44152476.806, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-441011.8512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23858', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19423
self.closeSec=1675355699, self.tradeDate='20230203', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23857.9, self.close=23900.0, self.high=23900.0, self.low=23857.4, self.vol=2163.534, self.amt=51662244.1353 
2023-02-03 00:35:00,497:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230203   001000    001459  ...         0.0        0.0       0
5763  20230203   001500    001959  ...         0.0        0.0       0
5764  20230203   002000    002459  ...         0.0        0.0       0
5765  20230203   002500    002959  ...         0.0        0.0       0
5766  20230203   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 00:35:00,497:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675355699, self.tradeDate='20230203', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23857.9, self.close=23900.0, self.high=23900.0, self.low=23857.4, self.vol=2163.534, self.amt=51662244.1353, ukdf['pct'].iloc[-1]=0.001765 , ukdf['amount'].iloc[-1]=51662244.1353, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-443503.1376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23899.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230203   002000    002459  1675355099  ...  23772.9  0.002789   1444    4
1445  20230203   002500    002959  1675355399  ...  23822.6  0.000675   1445    5

[5 rows x 11 columns]
2023-02-03 00:30:00,930:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-03 00:30:00,985:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230202   222500    222959  1675348199  ... -0.000682   1709    5  0.338412
198  20230202   225500    225959  1675349999  ... -0.005358   1715    5  0.342477
199  20230202   232500    232959  1675351799  ...  0.000528   1721    5  0.349256
200  20230202   235500    235959  1675353599  ... -0.001930   1727    5  0.352248
201  20230203   002500    002959  1675355399  ...  0.000675   1445    5  0.356051

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=51, self.factor=0.35605080869353267, self.count=19989 

self.closeSec=1675355699, self.tradeDate='20230203', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23857.9, self.close=23900.0, self.high=23900.0, self.low=23857.4 
2023-02-03 00:35:00,429:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675355699, self.tradeDate='20230203', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23857.9, self.close=23900.0, self.high=23900.0, self.low=23857.4   
127.0.0.1 - - [03/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-03 00:35:00,480:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230203   001000    001459  1675354499  ...  23784.4 -0.002205   1442    2
1443  20230203   001500    001959  1675354799  ...  23772.2 -0.001180   1443    3
1444  20230203   002000    002459  1675355099  ...  23772.9  0.002789   1444    4
1445  20230203   002500    002959  1675355399  ...  23822.6  0.000675   1445    5
1446  20230203   003000    003459  1675355699  ...  23857.4  0.001765   1446    0

[5 rows x 11 columns]
2023-02-03 00:35:00,480:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-03 00:30:33,212:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230202    215959  23803.5  ...  47.916667  0.565061  0.298687
5756  20230202    222959  23773.5  ...  47.916667  0.586717  0.295311
5757  20230202    225959  23902.0  ...  47.916667  0.526142  0.304703
5758  20230202    232959  23612.1  ...  47.916667  0.537681  0.310498
5759  20230202    235959  23680.5  ...  47.916667  0.563513  0.320170

[5 rows x 33 columns]
0.5231910946196661
acc is : 0.5231910946196661
2023-02-03 00:30:33,383:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
534     1  0.472308  0.527692       1  ...  0.942005   1.0  0.0000  1.044953
535     0  0.507307  0.492693       0  ...  0.930626   1.0  0.0000  1.032331
536     1  0.418783  0.581217       1  ...  0.926441  -1.0 -0.0016  1.035322
537     1  0.482987  0.517013       1  ...  0.920068  -1.0  0.0000  1.042444
538     0  0.508670  0.491330       1  ...  0.919509  -1.0  0.0000  1.043078

[5 rows x 10 columns]
2023-02-03 00:30:33,408:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.472996  0.527004       1  ...  0.942005   1.0  0.0000  1.042733
46     0  0.508823  0.491177       0  ...  0.930626   1.0  0.0000  1.030138
47     1  0.420492  0.579508       1  ...  0.926441  -1.0 -0.0016  1.033429
48     1  0.486219  0.513781       1  ...  0.920068  -1.0  0.0000  1.041506
49     0  0.508670  0.491330       1  ...  0.919509  -1.0  0.0000  1.043078

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '-5711.51809767907', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23873.29691001', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230203   000000    000959  1675354199  23843.4  23856.2  0.000541
2023-02-03 00:10:01,535:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9993 

self.closeSec=1675354799, self.tradeDate='20230203', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23855.3', self.close='23773.4'
2023-02-03 00:20:00,557:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675354799, self.tradeDate='20230203', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23855.3', self.close='23773.4'
127.0.0.1 - - [03/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-03 00:20:00,585:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230202   233000    233959  1675352399  23680.5  23749.2  0.002901
574  20230202   234000    234959  1675352999  23749.1  23803.2  0.002274
575  20230202   235000    235959  1675353599  23804.5  23843.3  0.001685
576  20230203   000000    000959  1675354199  23843.4  23856.2  0.000541
577  20230203   001000    001959  1675354799  23855.3  23773.4 -0.003471
2023-02-03 00:20:00,585:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9994 

self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23775.4', self.close='23857.9'
2023-02-03 00:30:01,499:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23775.4', self.close='23857.9'
127.0.0.1 - - [03/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-03 00:30:01,516:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230202   234000    234959  1675352999  23749.1  23803.2  0.002274
575  20230202   235000    235959  1675353599  23804.5  23843.3  0.001685
576  20230203   000000    000959  1675354199  23843.4  23856.2  0.000541
577  20230203   001000    001959  1675354799  23855.3  23773.4 -0.003471
578  20230203   002000    002959  1675355399  23775.4  23857.9  0.003554
2023-02-03 00:30:01,516:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230203   000000    000959  1675354199  23843.4  23856.2
2023-02-03 00:10:01,542:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9994 

self.closeSec=1675354799, self.tradeDate='20230203', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23855.3', self.close='23773.4'
2023-02-03 00:20:00,543:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675354799, self.tradeDate='20230203', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23855.3', self.close='23773.4'
2023-02-03 00:20:00,604:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230202   233000    233959  1675352399  23680.5  23749.2
17422  20230202   234000    234959  1675352999  23749.1  23803.2
17423  20230202   235000    235959  1675353599  23804.5  23843.3
17424  20230203   000000    000959  1675354199  23843.4  23856.2
17425  20230203   001000    001959  1675354799  23855.3  23773.4
2023-02-03 00:20:00,604:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9995 

self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23775.4', self.close='23857.9'
2023-02-03 00:30:01,488:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23775.4', self.close='23857.9'
2023-02-03 00:30:01,519:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230202   234000    234959  1675352999  23749.1  23803.2
17423  20230202   235000    235959  1675353599  23804.5  23843.3
17424  20230203   000000    000959  1675354199  23843.4  23856.2
17425  20230203   001000    001959  1675354799  23855.3  23773.4
17426  20230203   002000    002959  1675355399  23775.4  23857.9
2023-02-03 00:30:01,519:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230203   000000    000959  1675354199  23843.4  23856.2
2023-02-03 00:10:01,568:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [03/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9994 

self.closeSec=1675354799, self.tradeDate='20230203', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23855.3', self.close='23773.4'
2023-02-03 00:20:00,537:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675354799, self.tradeDate='20230203', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23855.3', self.close='23773.4'
2023-02-03 00:20:00,593:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230202   233000    233959  1675352399  23680.5  23749.2
12238  20230202   234000    234959  1675352999  23749.1  23803.2
12239  20230202   235000    235959  1675353599  23804.5  23843.3
12240  20230203   000000    000959  1675354199  23843.4  23856.2
12241  20230203   001000    001959  1675354799  23855.3  23773.4
2023-02-03 00:20:00,593:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9995 

self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23775.4', self.close='23857.9'
127.0.0.1 - - [03/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-03 00:30:01,517:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23775.4', self.close='23857.9'
2023-02-03 00:30:01,549:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230202   234000    234959  1675352999  23749.1  23803.2
12239  20230202   235000    235959  1675353599  23804.5  23843.3
12240  20230203   000000    000959  1675354199  23843.4  23856.2
12241  20230203   001000    001959  1675354799  23855.3  23773.4
12242  20230203   002000    002959  1675355399  23775.4  23857.9
2023-02-03 00:30:01,549:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [03/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15420
self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23841.9, self.close=23857.9, self.high=23865.9, self.low=23822.6, self.vol=1851.312, self.amt=44152476.806 
2023-02-03 00:30:00,941:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230203   000500    000959  ...         0.0        0.0       0
5762  20230203   001000    001459  ...         0.0        0.0       0
5763  20230203   001500    001959  ...         0.0        0.0       0
5764  20230203   002000    002459  ...         0.0        0.0       0
5765  20230203   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 00:30:00,950:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675355399, self.tradeDate='20230203', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23841.9, self.close=23857.9, self.high=23865.9, self.low=23822.6, self.vol=1851.312, self.amt=44152476.806, ukdf['pct'].iloc[-1]=0.000675 , ukdf['amount'].iloc[-1]=44152476.806, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15421
self.closeSec=1675355699, self.tradeDate='20230203', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23857.9, self.close=23900.0, self.high=23900.0, self.low=23857.4, self.vol=2163.534, self.amt=51662244.1353 
127.0.0.1 - - [03/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-03 00:35:00,483:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230203   001000    001459  ...         0.0        0.0       0
5763  20230203   001500    001959  ...         0.0        0.0       0
5764  20230203   002000    002459  ...         0.0        0.0       0
5765  20230203   002500    002959  ...         0.0        0.0       0
5766  20230203   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 00:35:00,484:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675355699, self.tradeDate='20230203', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23857.9, self.close=23900.0, self.high=23900.0, self.low=23857.4, self.vol=2163.534, self.amt=51662244.1353, ukdf['pct'].iloc[-1]=0.001765 , ukdf['amount'].iloc[-1]=51662244.1353, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230202   120000    155959  1675324799  ...    723  0.707133  0.686136     1.0
724  20230202   160000    195959  1675339199  ...    724  0.662503  0.537956     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '4886.55978135972', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23825.51216973', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [03/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=416
self.closeSec=1675353599, self.tradeDate='20230202', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23827.0, self.close=23843.3, self.high=23950.0, self.low=23520.0, self.vol=152792.644, self.amt=3629087099.9247 
2023-02-03 00:00:02,304:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675353599, self.tradeDate='20230202', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23827.0, self.close=23843.3, self.high=23950.0, self.low=23520.0, self.vol=152792.644, self.amt=3629087099.9247 
2023-02-03 00:00:02,335:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230202   040000    075959  ...  160059.153  3.779794e+09  0.014974
722  20230202   080000    115959  ...  136849.095  3.284367e+09  0.005150
723  20230202   120000    155959  ...   48942.495  1.165257e+09 -0.002734
724  20230202   160000    195959  ...   34286.886  8.163629e+08  0.001682
725  20230202   200000    235959  ...  152792.644  3.629087e+09  0.000684

[5 rows x 11 columns]
2023-02-03 00:00:04,659:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230202   040000    075959  1675295999  ...    721  0.558106  0.277750     NaN
722  20230202   080000    115959  1675310399  ...    722  0.690950  0.654160     1.0
723  20230202   120000    155959  1675324799  ...    723  0.707133  0.686136     1.0
724  20230202   160000    195959  1675339199  ...    724  0.662503  0.537956     NaN
725  20230202   200000    235959  1675353599  ...    725  0.692199  0.611737     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '5445.39912979272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23839.85462298', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


