# 20230205 00:35:53

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19998
self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23395.1, self.close=23427.5, self.high=23429.0, self.low=23395.0, self.vol=1159.383, self.amt=27146792.5557 
127.0.0.1 - - [05/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:30:00,869:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230205   000500    000959  ...         0.0        0.0       0
5762  20230205   001000    001459  ...         0.0        0.0       0
5763  20230205   001500    001959  ...         0.0        0.0       0
5764  20230205   002000    002459  ...         0.0        0.0       0
5765  20230205   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 00:30:00,870:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23395.1, self.close=23427.5, self.high=23429.0, self.low=23395.0, self.vol=1159.383, self.amt=27146792.5557, ukdf['pct'].iloc[-1]=0.001385 , ukdf['amount'].iloc[-1]=27146792.5557, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-415106.0832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23427.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19999
self.closeSec=1675528499, self.tradeDate='20230205', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23427.5, self.close=23439.0, self.high=23457.0, self.low=23427.4, self.vol=1442.903, self.amt=33824109.7526 
127.0.0.1 - - [05/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:35:00,516:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230205   001000    001459  ...         0.0        0.0       0
5763  20230205   001500    001959  ...         0.0        0.0       0
5764  20230205   002000    002459  ...         0.0        0.0       0
5765  20230205   002500    002959  ...         0.0        0.0       0
5766  20230205   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 00:35:00,518:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675528499, self.tradeDate='20230205', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23427.5, self.close=23439.0, self.high=23457.0, self.low=23427.4, self.vol=1442.903, self.amt=33824109.7526, ukdf['pct'].iloc[-1]=0.000491 , ukdf['amount'].iloc[-1]=33824109.7526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-415890.63356606432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23440.53759582', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1445  20230205   002500    002959  1675528199  ...  23395.0  0.001385   1445    5

[5 rows x 11 columns]
2023-02-05 00:30:00,818:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-05 00:30:00,890:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230204   222500    222959  1675520999  ...  0.001089   1709    5  0.658861
198  20230204   225500    225959  1675522799  ...  0.000606   1715    5  0.650025
199  20230204   232500    232959  1675524599  ... -0.001335   1721    5  0.645432
200  20230204   235500    235959  1675526399  ... -0.000209   1727    5  0.640631
201  20230205   002500    002959  1675528199  ...  0.001385   1445    5  0.635305

[5 rows x 12 columns]
2023-02-05 00:30:00,915:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2050030, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230205, closeTime:002959, close:23427.5, total:928613.5591976999, factor:0.6353049215351675, factorCnt:0, side:buy 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6353049215351675, self.count=20565 

self.closeSec=1675528499, self.tradeDate='20230205', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23427.5, self.close=23439.0, self.high=23457.0, self.low=23427.4 
2023-02-05 00:35:00,437:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675528499, self.tradeDate='20230205', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23427.5, self.close=23439.0, self.high=23457.0, self.low=23427.4   
127.0.0.1 - - [05/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:35:00,486:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230205   001000    001459  1675527299  ...  23400.9 -0.000120   1442    2
1443  20230205   001500    001959  1675527599  ...  23399.4 -0.000269   1443    3
1444  20230205   002000    002459  1675527899  ...  23355.0 -0.000252   1444    4
1445  20230205   002500    002959  1675528199  ...  23395.0  0.001385   1445    5
1446  20230205   003000    003459  1675528499  ...  23427.4  0.000491   1446    0

[5 rows x 11 columns]
2023-02-05 00:35:00,486:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-05 00:30:33,381:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230204    215959  23537.0  ...  47.083333  0.517008  0.649506
5756  20230204    222959  23503.1  ...  46.666667  0.501577  0.631376
5757  20230204    225959  23444.0  ...  46.666667  0.506291  0.611296
5758  20230204    232959  23462.5  ...  46.666667  0.494399  0.600427
5759  20230204    235959  23416.5  ...  47.083333  0.495370  0.589650

[5 rows x 33 columns]
0.5417439703153989
acc is : 0.5417439703153989
2023-02-05 00:30:33,562:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     0  0.504038  0.495962       0  ...  0.991447  -1.0    0.0  1.023885
535     1  0.492815  0.507185       1  ...  0.990664  -1.0    0.0  1.024693
536     0  0.508002  0.491998       0  ...  0.992611  -1.0    0.0  1.022680
537     1  0.489397  0.510603       1  ...  0.992454  -1.0    0.0  1.022841
538     1  0.488139  0.511861       1  ...  0.992140  -1.0    0.0  1.023165

[5 rows x 10 columns]
2023-02-05 00:30:33,581:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502293  0.497707       0  ...  0.991447  -1.0    0.0  1.015239
46     1  0.491338  0.508662       1  ...  0.990664  -1.0    0.0  1.016040
47     0  0.506887  0.493113       0  ...  0.992611  -1.0    0.0  1.014140
48     1  0.489214  0.510786       1  ...  0.992454  -1.0    0.0  1.015955
49     1  0.488139  0.511861       1  ...  0.992140  -1.0    0.0  1.023165

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '7890.5571', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23433.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230205   000000    000959  1675526999  23420.1  23410.1 -0.000427
2023-02-05 00:10:01,768:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10281 

self.closeSec=1675527599, self.tradeDate='20230205', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23410.1', self.close='23401'
2023-02-05 00:20:00,720:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675527599, self.tradeDate='20230205', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23410.1', self.close='23401'
127.0.0.1 - - [05/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:20:00,745:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230204   233000    233959  1675525199  23416.5  23394.3 -0.000944
574  20230204   234000    234959  1675525799  23394.3  23411.5  0.000735
575  20230204   235000    235959  1675526399  23411.4  23420.1  0.000367
576  20230205   000000    000959  1675526999  23420.1  23410.1 -0.000427
577  20230205   001000    001959  1675527599  23410.1    23401 -0.000389
2023-02-05 00:20:00,745:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10282 

self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23401.1', self.close='23427.5'
2023-02-05 00:30:01,194:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23401.1', self.close='23427.5'
127.0.0.1 - - [05/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-05 00:30:01,209:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230204   234000    234959  1675525799  23394.3  23411.5  0.000735
575  20230204   235000    235959  1675526399  23411.4  23420.1  0.000367
576  20230205   000000    000959  1675526999  23420.1  23410.1 -0.000427
577  20230205   001000    001959  1675527599  23410.1    23401 -0.000389
578  20230205   002000    002959  1675528199  23401.1  23427.5  0.001132
2023-02-05 00:30:01,211:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230205   000000    000959  1675526999  23420.1  23410.1
2023-02-05 00:10:01,775:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10282 

self.closeSec=1675527599, self.tradeDate='20230205', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23410.1', self.close='23401'
2023-02-05 00:20:00,734:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675527599, self.tradeDate='20230205', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23410.1', self.close='23401'
127.0.0.1 - - [05/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:20:00,760:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230204   233000    233959  1675525199  23416.5  23394.3
17422  20230204   234000    234959  1675525799  23394.3  23411.5
17423  20230204   235000    235959  1675526399  23411.4  23420.1
17424  20230205   000000    000959  1675526999  23420.1  23410.1
17425  20230205   001000    001959  1675527599  23410.1    23401
2023-02-05 00:20:00,760:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10283 

self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23401.1', self.close='23427.5'
2023-02-05 00:30:01,197:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23401.1', self.close='23427.5'
2023-02-05 00:30:01,244:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230204   234000    234959  1675525799  23394.3  23411.5
17423  20230204   235000    235959  1675526399  23411.4  23420.1
17424  20230205   000000    000959  1675526999  23420.1  23410.1
17425  20230205   001000    001959  1675527599  23410.1    23401
17426  20230205   002000    002959  1675528199  23401.1  23427.5
2023-02-05 00:30:01,244:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230205   000000    000959  1675526999  23420.1  23410.1
2023-02-05 00:10:01,740:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10282 

self.closeSec=1675527599, self.tradeDate='20230205', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23410.1', self.close='23401'
2023-02-05 00:20:00,732:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675527599, self.tradeDate='20230205', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23410.1', self.close='23401'
127.0.0.1 - - [05/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:20:00,753:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230204   233000    233959  1675525199  23416.5  23394.3
12238  20230204   234000    234959  1675525799  23394.3  23411.5
12239  20230204   235000    235959  1675526399  23411.4  23420.1
12240  20230205   000000    000959  1675526999  23420.1  23410.1
12241  20230205   001000    001959  1675527599  23410.1    23401
2023-02-05 00:20:00,753:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [05/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10283 

self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23401.1', self.close='23427.5'
2023-02-05 00:30:01,210:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23401.1', self.close='23427.5'
2023-02-05 00:30:01,228:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230204   234000    234959  1675525799  23394.3  23411.5
12239  20230204   235000    235959  1675526399  23411.4  23420.1
12240  20230205   000000    000959  1675526999  23420.1  23410.1
12241  20230205   001000    001959  1675527599  23410.1    23401
12242  20230205   002000    002959  1675528199  23401.1  23427.5
2023-02-05 00:30:01,228:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15996
self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23395.1, self.close=23427.5, self.high=23429.0, self.low=23395.0, self.vol=1159.383, self.amt=27146792.5557 
127.0.0.1 - - [05/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:30:00,862:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230205   000500    000959  ...         0.0        0.0       0
5762  20230205   001000    001459  ...         0.0        0.0       0
5763  20230205   001500    001959  ...         0.0        0.0       0
5764  20230205   002000    002459  ...         0.0        0.0       0
5765  20230205   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 00:30:00,866:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675528199, self.tradeDate='20230205', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23395.1, self.close=23427.5, self.high=23429.0, self.low=23395.0, self.vol=1159.383, self.amt=27146792.5557, ukdf['pct'].iloc[-1]=0.001385 , ukdf['amount'].iloc[-1]=27146792.5557, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15997
self.closeSec=1675528499, self.tradeDate='20230205', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23427.5, self.close=23439.0, self.high=23457.0, self.low=23427.4, self.vol=1442.903, self.amt=33824109.7526 
127.0.0.1 - - [05/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-05 00:35:00,513:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230205   001000    001459  ...         0.0        0.0       0
5763  20230205   001500    001959  ...         0.0        0.0       0
5764  20230205   002000    002459  ...         0.0        0.0       0
5765  20230205   002500    002959  ...         0.0        0.0       0
5766  20230205   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-05 00:35:00,516:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675528499, self.tradeDate='20230205', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23427.5, self.close=23439.0, self.high=23457.0, self.low=23427.4, self.vol=1442.903, self.amt=33824109.7526, ukdf['pct'].iloc[-1]=0.000491 , ukdf['amount'].iloc[-1]=33824109.7526, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230204   120000    155959  1675497599  ...    723  0.743165  0.596458     NaN
724  20230204   160000    195959  1675511999  ...    724  0.675291  0.369137     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-13144.9692742128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23362.7380948', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [05/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=428
self.closeSec=1675526399, self.tradeDate='20230204', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23359.2, self.close=23420.1, self.high=23591.4, self.low=23335.4, self.vol=70032.864, self.amt=1643729247.8242 
2023-02-05 00:00:01,593:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675526399, self.tradeDate='20230204', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23359.2, self.close=23420.1, self.high=23591.4, self.low=23335.4, self.vol=70032.864, self.amt=1643729247.8242 
2023-02-05 00:00:01,631:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230204   040000    075959  ...  51798.392  1.209502e+09  0.004998
722  20230204   080000    115959  ...  26184.717  6.126349e+08 -0.003582
723  20230204   120000    155959  ...  28301.188  6.598631e+08 -0.000788
724  20230204   160000    195959  ...  19759.758  4.610801e+08  0.001578
725  20230204   200000    235959  ...  70032.864  1.643729e+09  0.002607

[5 rows x 11 columns]
2023-02-05 00:00:03,487:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230204   040000    075959  1675468799  ...    721  0.846087  0.951234     1.0
722  20230204   080000    115959  1675483199  ...    722  0.814592  0.834734     1.0
723  20230204   120000    155959  1675497599  ...    723  0.743165  0.596458     NaN
724  20230204   160000    195959  1675511999  ...    724  0.675291  0.369137     NaN
725  20230204   200000    235959  1675526399  ...    725  0.606331  0.137386     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-10909.92', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23420.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


