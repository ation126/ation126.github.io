# 20230204 00:35:52

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19710
self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23663.2, self.close=23670.6, self.high=23673.9, self.low=23642.0, self.vol=1228.594, self.amt=29064316.4386 
127.0.0.1 - - [04/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-04 00:30:01,056:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230204   000500    000959  ...         0.0        0.0       0
5762  20230204   001000    001459  ...         0.0        0.0       0
5763  20230204   001500    001959  ...         0.0        0.0       0
5764  20230204   002000    002459  ...         0.0        0.0       0
5765  20230204   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 00:30:01,058:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23663.2, self.close=23670.6, self.high=23673.9, self.low=23642.0, self.vol=1228.594, self.amt=29064316.4386, ukdf['pct'].iloc[-1]=0.000313 , ukdf['amount'].iloc[-1]=29064316.4386, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-429783.0096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23671.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19711
self.closeSec=1675442099, self.tradeDate='20230204', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23670.5, self.close=23664.5, self.high=23719.9, self.low=23621.6, self.vol=4270.65, self.amt=101082504.5854 
2023-02-04 00:35:00,513:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230204   001000    001459  ...         0.0        0.0       0
5763  20230204   001500    001959  ...         0.0        0.0       0
5764  20230204   002000    002459  ...         0.0        0.0       0
5765  20230204   002500    002959  ...         0.0        0.0       0
5766  20230204   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 00:35:00,513:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675442099, self.tradeDate='20230204', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23670.5, self.close=23664.5, self.high=23719.9, self.low=23621.6, self.vol=4270.65, self.amt=101082504.5854, ukdf['pct'].iloc[-1]=-0.000258 , ukdf['amount'].iloc[-1]=101082504.5854, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-429367.7952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23664.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1445  20230204   002500    002959  1675441799  ...  23642.0  0.000313   1445    5

[5 rows x 11 columns]
2023-02-04 00:30:01,029:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-04 00:30:01,081:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230203   222500    222959  1675434599  ...  0.000399   1709    5  0.662780
198  20230203   225500    225959  1675436399  ... -0.000315   1715    5  0.660001
199  20230203   232500    232959  1675438199  ... -0.003065   1721    5  0.653647
200  20230203   235500    235959  1675439999  ...  0.000127   1727    5  0.647868
201  20230204   002500    002959  1675441799  ...  0.000313   1445    5  0.639585

[5 rows x 12 columns]
2023-02-04 00:30:01,134:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2040030, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230204, closeTime:002959, close:23670.6, total:928613.5591976999, factor:0.6395853129021142, factorCnt:0, side:buy 
127.0.0.1 - - [04/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6395853129021142, self.count=20277 

self.closeSec=1675442099, self.tradeDate='20230204', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23670.5, self.close=23664.5, self.high=23719.9, self.low=23621.6 
2023-02-04 00:35:00,427:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675442099, self.tradeDate='20230204', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23670.5, self.close=23664.5, self.high=23719.9, self.low=23621.6   
2023-02-04 00:35:00,456:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230204   001000    001459  1675440899  ...  23584.5  0.002153   1442    2
1443  20230204   001500    001959  1675441199  ...  23618.8 -0.000783   1443    3
1444  20230204   002000    002459  1675441499  ...  23600.0  0.001731   1444    4
1445  20230204   002500    002959  1675441799  ...  23642.0  0.000313   1445    5
1446  20230204   003000    003459  1675442099  ...  23621.6 -0.000258   1446    0

[5 rows x 11 columns]
2023-02-04 00:35:00,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-04 00:30:32,406:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230203    215959  23505.0  ...  47.083333  0.464708  0.786445
5756  20230203    222959  23348.8  ...  47.083333  0.459389  0.793376
5757  20230203    225959  23320.2  ...  47.083333  0.499562  0.784069
5758  20230203    232959  23516.9  ...  47.500000  0.517437  0.761922
5759  20230203    235959  23612.3  ...  47.083333  0.515298  0.742273

[5 rows x 33 columns]
0.5287569573283859
acc is : 0.5287569573283859
2023-02-04 00:30:32,557:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.454009  0.545991       0  ...  0.934590  -1.0    0.0  1.017954
535     1  0.468790  0.531210       1  ...  0.926739  -1.0    0.0  1.026505
536     0  0.522284  0.477716       1  ...  0.922967  -1.0    0.0  1.030682
537     0  0.513028  0.486972       0  ...  0.923393  -1.0    0.0  1.030206
538     1  0.496700  0.503300       1  ...  0.920674  -1.0    0.0  1.033240

[5 rows x 10 columns]
2023-02-04 00:30:32,592:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.456572  0.543428       0  ...  0.934590  -1.0    0.0  1.024019
46     1  0.471978  0.528022       1  ...  0.926739  -1.0    0.0  1.032621
47     0  0.525858  0.474142       1  ...  0.922967  -1.0    0.0  1.041075
48     0  0.514944  0.485056       0  ...  0.923393  -1.0    0.0  1.040044
49     1  0.496700  0.503300       1  ...  0.920674  -1.0    0.0  1.033240

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '576.99865722457', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23669.83113349', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230204   000000    000959  1675440599  23601.1    23590 -0.000470
2023-02-04 00:10:01,554:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10137 

self.closeSec=1675441199, self.tradeDate='20230204', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23590', self.close='23622.3'
2023-02-04 00:20:00,728:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675441199, self.tradeDate='20230204', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23590', self.close='23622.3'
2023-02-04 00:20:00,769:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230203   233000    233959  1675438799  23612.3  23672.3  0.002554
574  20230203   234000    234959  1675439399  23669.6  23650.6 -0.000917
575  20230203   235000    235959  1675439999  23650.6  23601.1 -0.002093
576  20230204   000000    000959  1675440599  23601.1    23590 -0.000470
577  20230204   001000    001959  1675441199    23590  23622.3  0.001369
2023-02-04 00:20:00,770:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10138 

self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23622.3', self.close='23670.6'
2023-02-04 00:30:01,599:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23622.3', self.close='23670.6'
2023-02-04 00:30:01,618:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230203   234000    234959  1675439399  23669.6  23650.6 -0.000917
575  20230203   235000    235959  1675439999  23650.6  23601.1 -0.002093
576  20230204   000000    000959  1675440599  23601.1    23590 -0.000470
577  20230204   001000    001959  1675441199    23590  23622.3  0.001369
578  20230204   002000    002959  1675441799  23622.3  23670.6  0.002045
2023-02-04 00:30:01,618:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230204   000000    000959  1675440599  23601.1    23590
2023-02-04 00:10:01,562:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10138 

self.closeSec=1675441199, self.tradeDate='20230204', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23590', self.close='23622.3'
2023-02-04 00:20:00,691:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675441199, self.tradeDate='20230204', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23590', self.close='23622.3'
2023-02-04 00:20:00,701:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230203   233000    233959  1675438799  23612.3  23672.3
17422  20230203   234000    234959  1675439399  23669.6  23650.6
17423  20230203   235000    235959  1675439999  23650.6  23601.1
17424  20230204   000000    000959  1675440599  23601.1    23590
17425  20230204   001000    001959  1675441199    23590  23622.3
2023-02-04 00:20:00,701:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10139 

self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23622.3', self.close='23670.6'
2023-02-04 00:30:01,562:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23622.3', self.close='23670.6'
2023-02-04 00:30:01,583:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230203   234000    234959  1675439399  23669.6  23650.6
17423  20230203   235000    235959  1675439999  23650.6  23601.1
17424  20230204   000000    000959  1675440599  23601.1    23590
17425  20230204   001000    001959  1675441199    23590  23622.3
17426  20230204   002000    002959  1675441799  23622.3  23670.6
2023-02-04 00:30:01,583:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230204   000000    000959  1675440599  23601.1    23590
2023-02-04 00:10:01,556:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [04/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10138 

self.closeSec=1675441199, self.tradeDate='20230204', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23590', self.close='23622.3'
2023-02-04 00:20:00,741:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675441199, self.tradeDate='20230204', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23590', self.close='23622.3'
2023-02-04 00:20:00,778:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230203   233000    233959  1675438799  23612.3  23672.3
12238  20230203   234000    234959  1675439399  23669.6  23650.6
12239  20230203   235000    235959  1675439999  23650.6  23601.1
12240  20230204   000000    000959  1675440599  23601.1    23590
12241  20230204   001000    001959  1675441199    23590  23622.3
2023-02-04 00:20:00,779:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10139 

self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23622.3', self.close='23670.6'
2023-02-04 00:30:01,591:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23622.3', self.close='23670.6'
127.0.0.1 - - [04/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-04 00:30:01,623:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230203   234000    234959  1675439399  23669.6  23650.6
12239  20230203   235000    235959  1675439999  23650.6  23601.1
12240  20230204   000000    000959  1675440599  23601.1    23590
12241  20230204   001000    001959  1675441199    23590  23622.3
12242  20230204   002000    002959  1675441799  23622.3  23670.6
2023-02-04 00:30:01,623:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [04/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15708
self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23663.2, self.close=23670.6, self.high=23673.9, self.low=23642.0, self.vol=1228.594, self.amt=29064316.4386 
2023-02-04 00:30:01,045:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230204   000500    000959  ...         0.0        0.0       0
5762  20230204   001000    001459  ...         0.0        0.0       0
5763  20230204   001500    001959  ...         0.0        0.0       0
5764  20230204   002000    002459  ...         0.0        0.0       0
5765  20230204   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 00:30:01,045:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675441799, self.tradeDate='20230204', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23663.2, self.close=23670.6, self.high=23673.9, self.low=23642.0, self.vol=1228.594, self.amt=29064316.4386, ukdf['pct'].iloc[-1]=0.000313 , ukdf['amount'].iloc[-1]=29064316.4386, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15709
self.closeSec=1675442099, self.tradeDate='20230204', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23670.5, self.close=23664.5, self.high=23719.9, self.low=23621.6, self.vol=4270.65, self.amt=101082504.5854 
2023-02-04 00:35:00,474:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230204   001000    001459  ...         0.0        0.0       0
5763  20230204   001500    001959  ...         0.0        0.0       0
5764  20230204   002000    002459  ...         0.0        0.0       0
5765  20230204   002500    002959  ...         0.0        0.0       0
5766  20230204   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 00:35:00,474:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675442099, self.tradeDate='20230204', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23670.5, self.close=23664.5, self.high=23719.9, self.low=23621.6, self.vol=4270.65, self.amt=101082504.5854, ukdf['pct'].iloc[-1]=-0.000258 , ukdf['amount'].iloc[-1]=101082504.5854, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230203   120000    155959  1675411199  ...    723  0.675625  0.497663     NaN
724  20230203   160000    195959  1675425599  ...    724  0.691835  0.532151     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-6529.75939815708', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23532.51557853', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [04/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=422
self.closeSec=1675439999, self.tradeDate='20230203', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23532.9, self.close=23601.1, self.high=23712.7, self.low=23222.0, self.vol=189870.022, self.amt=4455431541.06062 
2023-02-04 00:00:01,925:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675439999, self.tradeDate='20230203', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23532.9, self.close=23601.1, self.high=23712.7, self.low=23222.0, self.vol=189870.022, self.amt=4455431541.06062 
2023-02-04 00:00:01,955:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230203   040000    075959  ...  111289.486  2.630096e+09 -0.013098
722  20230203   080000    115959  ...   53873.247  1.266839e+09  0.001779
723  20230203   120000    155959  ...   25571.080  6.012727e+08 -0.003306
724  20230203   160000    195959  ...   57784.896  1.353723e+09  0.003231
725  20230203   200000    235959  ...  189870.022  4.455432e+09  0.002898

[5 rows x 11 columns]
2023-02-04 00:00:04,209:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230203   040000    075959  1675382399  ...    721  0.727334  0.683564     1.0
722  20230203   080000    115959  1675396799  ...    722  0.700479  0.587199     NaN
723  20230203   120000    155959  1675411199  ...    723  0.675625  0.497663     NaN
724  20230203   160000    195959  1675425599  ...    724  0.691835  0.532151     NaN
725  20230203   200000    235959  1675439999  ...    725  0.735980  0.650313     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-3826.85821353756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23601.88477021', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


