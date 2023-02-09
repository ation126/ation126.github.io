# 20230210 00:36:00

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21438
self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22529.4, self.close=22542.4, self.high=22547.3, self.low=22495.0, self.vol=5892.415, self.amt=132694662.5594 
127.0.0.1 - - [10/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-10 00:30:00,787:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230210   000500    000959  ...         0.0        0.0       0
5762  20230210   001000    001459  ...         0.0        0.0       0
5763  20230210   001500    001959  ...         0.0        0.0       0
5764  20230210   002000    002459  ...         0.0        0.0       0
5765  20230210   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 00:30:00,788:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22529.4, self.close=22542.4, self.high=22547.3, self.low=22495.0, self.vol=5892.415, self.amt=132694662.5594, ukdf['pct'].iloc[-1]=0.000577 , ukdf['amount'].iloc[-1]=132694662.5594, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-362133.1504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22547.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21439
self.closeSec=1675960499, self.tradeDate='20230210', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22548.7, self.close=22498.0, self.high=22554.0, self.low=22477.0, self.vol=4593.322, self.amt=103400166.9831 
127.0.0.1 - - [10/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-10 00:35:00,515:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230210   001000    001459  ...         0.0        0.0       0
5763  20230210   001500    001959  ...         0.0        0.0       0
5764  20230210   002000    002459  ...         0.0        0.0       0
5765  20230210   002500    002959  ...         0.0        0.0       0
5766  20230210   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 00:35:00,515:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675960499, self.tradeDate='20230210', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22548.7, self.close=22498.0, self.high=22554.0, self.low=22477.0, self.vol=4593.322, self.amt=103400166.9831, ukdf['pct'].iloc[-1]=-0.00197 , ukdf['amount'].iloc[-1]=103400166.9831, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-359214.891751184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22498.704609', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230210   002000    002459  1675959899  ...  22520.0 -0.001405   1444    4
1445  20230210   002500    002959  1675960199  ...  22495.0  0.000577   1445    5

[5 rows x 11 columns]
2023-02-10 00:30:00,805:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-10 00:30:00,879:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230209   222500    222959  1675952999  ...  0.001021   1709    5  0.558799
198  20230209   225500    225959  1675954799  ... -0.000467   1715    5  0.559661
199  20230209   232500    232959  1675956599  ... -0.001995   1721    5  0.563891
200  20230209   235500    235959  1675958399  ...  0.000491   1727    5  0.568619
201  20230210   002500    002959  1675960199  ...  0.000577   1445    5  0.576219

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=95, self.factor=0.5762193389913652, self.count=22005 

self.closeSec=1675960499, self.tradeDate='20230210', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22548.7, self.close=22498.0, self.high=22554.0, self.low=22477.0 
2023-02-10 00:35:00,464:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675960499, self.tradeDate='20230210', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22548.7, self.close=22498.0, self.high=22554.0, self.low=22477.0   
127.0.0.1 - - [10/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-10 00:35:00,528:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230210   001000    001459  1675959299  ...  22585.6 -0.000354   1442    2
1443  20230210   001500    001959  1675959599  ...  22555.8 -0.001717   1443    3
1444  20230210   002000    002459  1675959899  ...  22520.0 -0.001405   1444    4
1445  20230210   002500    002959  1675960199  ...  22495.0  0.000577   1445    5
1446  20230210   003000    003459  1675960499  ...  22477.0 -0.001970   1446    0

[5 rows x 11 columns]
2023-02-10 00:35:00,530:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-10 00:30:31,915:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230209    215959  22684.1  ...  46.666667  0.462876  0.566553
5756  20230209    222959  22740.0  ...  47.083333  0.466352  0.554222
5757  20230209    225959  22751.2  ...  46.666667  0.451316  0.549472
5758  20230209    232959  22685.9  ...  46.666667  0.436529  0.551999
5759  20230209    235959  22615.4  ...  46.250000  0.433944  0.555597

[5 rows x 33 columns]
0.48608534322820035
acc is : 0.48608534322820035
2023-02-10 00:30:32,077:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     0  0.507784  0.492216       1  ...  0.992665  -1.0    0.0  0.970423
535     0  0.501874  0.498126       0  ...  0.995614  -1.0    0.0  0.967539
536     1  0.483984  0.516016       0  ...  0.998668  -1.0    0.0  0.964571
537     1  0.472283  0.527717       0  ...  0.999216  -1.0    0.0  0.964042
538     1  0.482838  0.517162       0  ...  1.001656  -1.0    0.0  0.961688

[5 rows x 10 columns]
2023-02-10 00:30:32,113:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511088  0.488912       1  ...  0.982061  -1.0    0.0  0.980911
46     0  0.504972  0.495028       0  ...  0.984979  -1.0    0.0  0.977996
47     1  0.487410  0.512590       0  ...  0.988001  -1.0    0.0  0.975673
48     1  0.474966  0.525034       0  ...  0.988543  -1.0    0.0  0.974285
49     1  0.482838  0.517162       0  ...  1.001656  -1.0    0.0  0.961688

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '12577.62962938944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22534.62016528', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230210   000000    000959  1675958999  22603.8  22607.9  0.000181
2023-02-10 00:10:01,829:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11001 

self.closeSec=1675959599, self.tradeDate='20230210', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22607.9', self.close='22561.1'
2023-02-10 00:20:00,536:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675959599, self.tradeDate='20230210', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22607.9', self.close='22561.1'
2023-02-10 00:20:00,542:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230209   233000    233959  1675957199  22615.4  22574.2 -0.001857
574  20230209   234000    234959  1675957799  22574.3  22632.4  0.002578
575  20230209   235000    235959  1675958399  22633.5  22603.8 -0.001264
576  20230210   000000    000959  1675958999  22603.8  22607.9  0.000181
577  20230210   001000    001959  1675959599  22607.9  22561.1 -0.002070
2023-02-10 00:20:00,543:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11002 

self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22561.1', self.close='22548.6'
2023-02-10 00:30:01,421:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22561.1', self.close='22548.6'
2023-02-10 00:30:01,469:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230209   234000    234959  1675957799  22574.3  22632.4  0.002578
575  20230209   235000    235959  1675958399  22633.5  22603.8 -0.001264
576  20230210   000000    000959  1675958999  22603.8  22607.9  0.000181
577  20230210   001000    001959  1675959599  22607.9  22561.1 -0.002070
578  20230210   002000    002959  1675960199  22561.1  22548.6 -0.000554
2023-02-10 00:30:01,469:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230210   000000    000959  1675958999  22603.8  22607.9
2023-02-10 00:10:01,828:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11002 

self.closeSec=1675959599, self.tradeDate='20230210', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22607.9', self.close='22561.1'
2023-02-10 00:20:00,511:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675959599, self.tradeDate='20230210', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22607.9', self.close='22561.1'
127.0.0.1 - - [10/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-10 00:20:00,533:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230209   233000    233959  1675957199  22615.4  22574.2
17422  20230209   234000    234959  1675957799  22574.3  22632.4
17423  20230209   235000    235959  1675958399  22633.5  22603.8
17424  20230210   000000    000959  1675958999  22603.8  22607.9
17425  20230210   001000    001959  1675959599  22607.9  22561.1
2023-02-10 00:20:00,533:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11003 

self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22561.1', self.close='22548.6'
2023-02-10 00:30:01,410:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22561.1', self.close='22548.6'
127.0.0.1 - - [10/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-10 00:30:01,439:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230209   234000    234959  1675957799  22574.3  22632.4
17423  20230209   235000    235959  1675958399  22633.5  22603.8
17424  20230210   000000    000959  1675958999  22603.8  22607.9
17425  20230210   001000    001959  1675959599  22607.9  22561.1
17426  20230210   002000    002959  1675960199  22561.1  22548.6
2023-02-10 00:30:01,440:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230210   000000    000959  1675958999  22603.8  22607.9
2023-02-10 00:10:01,833:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [10/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11002 

self.closeSec=1675959599, self.tradeDate='20230210', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22607.9', self.close='22561.1'
2023-02-10 00:20:00,509:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675959599, self.tradeDate='20230210', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22607.9', self.close='22561.1'
2023-02-10 00:20:00,550:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230209   233000    233959  1675957199  22615.4  22574.2
12238  20230209   234000    234959  1675957799  22574.3  22632.4
12239  20230209   235000    235959  1675958399  22633.5  22603.8
12240  20230210   000000    000959  1675958999  22603.8  22607.9
12241  20230210   001000    001959  1675959599  22607.9  22561.1
2023-02-10 00:20:00,550:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11003 

self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='22561.1', self.close='22548.6'
2023-02-10 00:30:01,416:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='22561.1', self.close='22548.6'
127.0.0.1 - - [10/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-10 00:30:01,438:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230209   234000    234959  1675957799  22574.3  22632.4
12239  20230209   235000    235959  1675958399  22633.5  22603.8
12240  20230210   000000    000959  1675958999  22603.8  22607.9
12241  20230210   001000    001959  1675959599  22607.9  22561.1
12242  20230210   002000    002959  1675960199  22561.1  22548.6
2023-02-10 00:30:01,438:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [10/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17436
self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=22529.4, self.close=22542.4, self.high=22547.3, self.low=22495.0, self.vol=5892.415, self.amt=132694662.5594 
2023-02-10 00:30:00,859:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230210   000500    000959  ...         0.0        0.0       0
5762  20230210   001000    001459  ...         0.0        0.0       0
5763  20230210   001500    001959  ...         0.0        0.0       0
5764  20230210   002000    002459  ...         0.0        0.0       0
5765  20230210   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 00:30:00,860:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675960199, self.tradeDate='20230210', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=22529.4, self.close=22542.4, self.high=22547.3, self.low=22495.0, self.vol=5892.415, self.amt=132694662.5594, ukdf['pct'].iloc[-1]=0.000577 , ukdf['amount'].iloc[-1]=132694662.5594, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17437
self.closeSec=1675960499, self.tradeDate='20230210', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=22548.7, self.close=22498.0, self.high=22554.0, self.low=22477.0, self.vol=4593.322, self.amt=103400166.9831 
2023-02-10 00:35:00,496:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230210   001000    001459  ...         0.0        0.0       0
5763  20230210   001500    001959  ...         0.0        0.0       0
5764  20230210   002000    002459  ...         0.0        0.0       0
5765  20230210   002500    002959  ...         0.0        0.0       0
5766  20230210   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 00:35:00,506:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675960499, self.tradeDate='20230210', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=22548.7, self.close=22498.0, self.high=22554.0, self.low=22477.0, self.vol=4593.322, self.amt=103400166.9831, ukdf['pct'].iloc[-1]=-0.00197 , ukdf['amount'].iloc[-1]=103400166.9831, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230209   120000    155959  1675929599  ...    723  0.269893 -0.917045    -1.0
724  20230209   160000    195959  1675943999  ...    724  0.271249 -0.923900    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '7084.35', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22673.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [10/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=888768.4643774999, self.flagDict['side']='sell', self.tradeCount=17, self.count=458
self.closeSec=1675958399, self.tradeDate='20230209', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22677.5, self.close=22603.8, self.high=22840.0, self.low=22550.0, self.vol=112744.024, self.amt=2557579284.45845 
2023-02-10 00:00:01,470:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675958399, self.tradeDate='20230209', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22677.5, self.close=22603.8, self.high=22840.0, self.low=22550.0, self.vol=112744.024, self.amt=2557579284.45845 
2023-02-10 00:00:01,495:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230209   040000    075959  ...   42038.652  9.621964e+08  0.003879
722  20230209   080000    115959  ...  114797.338  2.601294e+09 -0.019359
723  20230209   120000    155959  ...   83990.686  1.895751e+09  0.006979
724  20230209   160000    195959  ...   42168.627  9.572935e+08  0.000384
725  20230209   200000    235959  ...  112744.024  2.557579e+09 -0.003246

[5 rows x 11 columns]
2023-02-10 00:00:03,672:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230209   040000    075959  1675900799  ...    721  0.326246 -0.642327    -1.0
722  20230209   080000    115959  1675915199  ...    722  0.234313 -1.064918    -1.0
723  20230209   120000    155959  1675929599  ...    723  0.269893 -0.917045    -1.0
724  20230209   160000    195959  1675943999  ...    724  0.271249 -0.923900    -1.0
725  20230209   200000    235959  1675958399  ...    725  0.282399 -0.875070    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '9805.2075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22603.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


