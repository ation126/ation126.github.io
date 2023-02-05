# 20230206 00:35:52

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [06/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20286
self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23109.9, self.close=23137.5, self.high=23147.1, self.low=23095.8, self.vol=2530.887, self.amt=58523692.001 
2023-02-06 00:30:00,962:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230206   000500    000959  ...         0.0        0.0       0
5762  20230206   001000    001459  ...         0.0        0.0       0
5763  20230206   001500    001959  ...         0.0        0.0       0
5764  20230206   002000    002459  ...         0.0        0.0       0
5765  20230206   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 00:30:00,964:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23109.9, self.close=23137.5, self.high=23147.1, self.low=23095.8, self.vol=2530.887, self.amt=58523692.001, ukdf['pct'].iloc[-1]=0.001199 , ukdf['amount'].iloc[-1]=58523692.001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-397824.29903047648', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23140.31267998', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=20287
self.closeSec=1675614899, self.tradeDate='20230206', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23137.4, self.close=23118.6, self.high=23155.5, self.low=23117.4, self.vol=2428.743, self.amt=56197314.6837 
127.0.0.1 - - [06/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-06 00:35:00,893:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230206   001000    001459  ...         0.0        0.0       0
5763  20230206   001500    001959  ...         0.0        0.0       0
5764  20230206   002000    002459  ...         0.0        0.0       0
5765  20230206   002500    002959  ...         0.0        0.0       0
5766  20230206   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 00:35:00,893:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675614899, self.tradeDate='20230206', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23137.4, self.close=23118.6, self.high=23155.5, self.low=23117.4, self.vol=2428.743, self.amt=56197314.6837, ukdf['pct'].iloc[-1]=-0.000817 , ukdf['amount'].iloc[-1]=56197314.6837, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-396630.30521321808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23120.47098533', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1444  20230206   002000    002459  1675614299  ...  22982.0  0.003043   1444    4
1445  20230206   002500    002959  1675614599  ...  23095.8  0.001199   1445    5

[5 rows x 11 columns]
2023-02-06 00:30:00,920:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-06 00:30:01,018:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230205   222500    222959  1675607399  ...  0.001788   1709    5  0.560752
198  20230205   225500    225959  1675609199  ... -0.000790   1715    5  0.562619
199  20230205   232500    232959  1675610999  ... -0.000923   1721    5  0.564799
200  20230205   235500    235959  1675612799  ...  0.001322   1727    5  0.570264
201  20230206   002500    002959  1675614599  ...  0.001199   1445    5  0.573103

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.5731028234600312, self.count=20853 

self.closeSec=1675614899, self.tradeDate='20230206', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23137.4, self.close=23118.6, self.high=23155.5, self.low=23117.4 
2023-02-06 00:35:00,777:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675614899, self.tradeDate='20230206', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23137.4, self.close=23118.6, self.high=23155.5, self.low=23117.4   
127.0.0.1 - - [06/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-06 00:35:00,795:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230206   001000    001459  1675613699  ...  23050.3 -0.002275   1442    2
1443  20230206   001500    001959  1675613999  ...  23022.6 -0.001136   1443    3
1444  20230206   002000    002459  1675614299  ...  22982.0  0.003043   1444    4
1445  20230206   002500    002959  1675614599  ...  23095.8  0.001199   1445    5
1446  20230206   003000    003459  1675614899  ...  23117.4 -0.000817   1446    0

[5 rows x 11 columns]
2023-02-06 00:35:00,795:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-06 00:30:31,772:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230205    215959  23146.9  ...  45.000000  0.422489  0.557575
5756  20230205    222959  23164.2  ...  45.416667  0.432747  0.559156
5757  20230205    225959  23190.9  ...  45.000000  0.423738  0.565106
5758  20230205    232959  23159.9  ...  44.583333  0.421535  0.571536
5759  20230205    235959  23152.3  ...  44.583333  0.404902  0.586145

[5 rows x 33 columns]
0.5139146567717996
acc is : 0.5139146567717996
2023-02-06 00:30:31,921:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.474380  0.525620       1  ...  0.982862  -1.0    0.0  1.025933
535     1  0.480405  0.519595       0  ...  0.984155  -1.0    0.0  1.024584
536     1  0.468523  0.531477       0  ...  0.984473  -1.0    0.0  1.024252
537     1  0.487372  0.512628       0  ...  0.986944  -1.0    0.0  1.021682
538     1  0.475227  0.524773       1  ...  0.985093  -1.0    0.0  1.023597

[5 rows x 10 columns]
2023-02-06 00:30:31,957:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.473782  0.526218       1  ...  0.982862  -1.0    0.0  1.021275
46     1  0.479653  0.520347       0  ...  0.984155  -1.0    0.0  1.019932
47     1  0.466833  0.533167       0  ...  0.984473  -1.0    0.0  1.019193
48     1  0.486630  0.513370       0  ...  0.986944  -1.0    0.0  1.017191
49     1  0.475227  0.524773       1  ...  0.985093  -1.0    0.0  1.023597

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '16805.20860130273', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23144.76529261', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230206   000000    000959  1675613399  23094.2  23118.5  0.001052
2023-02-06 00:10:01,596:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10425 

self.closeSec=1675613999, self.tradeDate='20230206', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23117.1', self.close='23039.7'
2023-02-06 00:20:00,860:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675613999, self.tradeDate='20230206', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23117.1', self.close='23039.7'
127.0.0.1 - - [06/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-06 00:20:00,940:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230205   233000    233959  1675611599  23152.3  23132.7 -0.000847
574  20230205   234000    234959  1675612199  23132.8  23095.2 -0.001621
575  20230205   235000    235959  1675612799  23095.1  23094.2 -0.000043
576  20230206   000000    000959  1675613399  23094.2  23118.5  0.001052
577  20230206   001000    001959  1675613999  23117.1  23039.7 -0.003409
2023-02-06 00:20:00,940:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10426 

self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23035', self.close='23137.5'
127.0.0.1 - - [06/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-06 00:30:01,515:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23035', self.close='23137.5'
2023-02-06 00:30:01,563:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230205   234000    234959  1675612199  23132.8  23095.2 -0.001621
575  20230205   235000    235959  1675612799  23095.1  23094.2 -0.000043
576  20230206   000000    000959  1675613399  23094.2  23118.5  0.001052
577  20230206   001000    001959  1675613999  23117.1  23039.7 -0.003409
578  20230206   002000    002959  1675614599    23035  23137.5  0.004245
2023-02-06 00:30:01,563:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230206   000000    000959  1675613399  23094.2  23118.5
2023-02-06 00:10:01,602:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10426 

self.closeSec=1675613999, self.tradeDate='20230206', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23117.1', self.close='23039.7'
2023-02-06 00:20:00,906:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675613999, self.tradeDate='20230206', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23117.1', self.close='23039.7'
2023-02-06 00:20:00,938:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230205   233000    233959  1675611599  23152.3  23132.7
17422  20230205   234000    234959  1675612199  23132.8  23095.2
17423  20230205   235000    235959  1675612799  23095.1  23094.2
17424  20230206   000000    000959  1675613399  23094.2  23118.5
17425  20230206   001000    001959  1675613999  23117.1  23039.7
2023-02-06 00:20:00,938:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10427 

self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23035', self.close='23137.5'
2023-02-06 00:30:01,542:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23035', self.close='23137.5'
2023-02-06 00:30:01,577:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230205   234000    234959  1675612199  23132.8  23095.2
17423  20230205   235000    235959  1675612799  23095.1  23094.2
17424  20230206   000000    000959  1675613399  23094.2  23118.5
17425  20230206   001000    001959  1675613999  23117.1  23039.7
17426  20230206   002000    002959  1675614599    23035  23137.5
2023-02-06 00:30:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230206   000000    000959  1675613399  23094.2  23118.5
2023-02-06 00:10:01,604:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [06/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10426 

self.closeSec=1675613999, self.tradeDate='20230206', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23117.1', self.close='23039.7'
2023-02-06 00:20:00,897:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675613999, self.tradeDate='20230206', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23117.1', self.close='23039.7'
2023-02-06 00:20:00,957:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230205   233000    233959  1675611599  23152.3  23132.7
12238  20230205   234000    234959  1675612199  23132.8  23095.2
12239  20230205   235000    235959  1675612799  23095.1  23094.2
12240  20230206   000000    000959  1675613399  23094.2  23118.5
12241  20230206   001000    001959  1675613999  23117.1  23039.7
2023-02-06 00:20:00,957:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [06/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10427 

self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='23035', self.close='23137.5'
2023-02-06 00:30:01,482:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='23035', self.close='23137.5'
2023-02-06 00:30:01,507:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230205   234000    234959  1675612199  23132.8  23095.2
12239  20230205   235000    235959  1675612799  23095.1  23094.2
12240  20230206   000000    000959  1675613399  23094.2  23118.5
12241  20230206   001000    001959  1675613999  23117.1  23039.7
12242  20230206   002000    002959  1675614599    23035  23137.5
2023-02-06 00:30:01,507:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [06/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16284
self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=23109.9, self.close=23137.5, self.high=23147.1, self.low=23095.8, self.vol=2530.887, self.amt=58523692.001 
2023-02-06 00:30:00,913:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230206   000500    000959  ...         0.0        0.0       0
5762  20230206   001000    001459  ...         0.0        0.0       0
5763  20230206   001500    001959  ...         0.0        0.0       0
5764  20230206   002000    002459  ...         0.0        0.0       0
5765  20230206   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 00:30:00,914:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675614599, self.tradeDate='20230206', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=23109.9, self.close=23137.5, self.high=23147.1, self.low=23095.8, self.vol=2530.887, self.amt=58523692.001, ukdf['pct'].iloc[-1]=0.001199 , ukdf['amount'].iloc[-1]=58523692.001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [06/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=16285
self.closeSec=1675614899, self.tradeDate='20230206', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=23137.4, self.close=23118.6, self.high=23155.5, self.low=23117.4, self.vol=2428.743, self.amt=56197314.6837 
2023-02-06 00:35:00,909:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230206   001000    001459  ...         0.0        0.0       0
5763  20230206   001500    001959  ...         0.0        0.0       0
5764  20230206   002000    002459  ...         0.0        0.0       0
5765  20230206   002500    002959  ...         0.0        0.0       0
5766  20230206   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-06 00:35:00,911:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675614899, self.tradeDate='20230206', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=23137.4, self.close=23118.6, self.high=23155.5, self.low=23117.4, self.vol=2428.743, self.amt=56197314.6837, ukdf['pct'].iloc[-1]=-0.000817 , ukdf['amount'].iloc[-1]=56197314.6837, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230205   120000    155959  1675583999  ...    723  0.579785  0.060318     NaN
724  20230205   160000    195959  1675598399  ...    724  0.502495 -0.173977     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-13477.6476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23354.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=434
self.closeSec=1675612799, self.tradeDate='20230205', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23354.2, self.close=23094.2, self.high=23373.6, self.low=23000.0, self.vol=103064.491, self.amt=2387031213.14554 
2023-02-06 00:00:01,911:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675612799, self.tradeDate='20230205', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23354.2, self.close=23094.2, self.high=23373.6, self.low=23000.0, self.vol=103064.491, self.amt=2387031213.14554 
127.0.0.1 - - [06/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-06 00:00:01,957:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230205   040000    075959  ...   27115.818  6.335307e+08 -0.004469
722  20230205   080000    115959  ...   34347.877  8.003898e+08  0.000892
723  20230205   120000    155959  ...   20096.361  4.697797e+08  0.001439
724  20230205   160000    195959  ...   20554.304  4.805312e+08 -0.000980
725  20230205   200000    235959  ...  103064.491  2.387031e+09 -0.011129

[5 rows x 11 columns]
2023-02-06 00:00:04,196:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230205   040000    075959  1675555199  ...    721  0.548186 -0.055113     NaN
722  20230205   080000    115959  1675569599  ...    722  0.640686  0.249238     NaN
723  20230205   120000    155959  1675583999  ...    723  0.579785  0.060318     NaN
724  20230205   160000    195959  1675598399  ...    724  0.502495 -0.173977     NaN
725  20230205   200000    235959  1675612799  ...    725  0.412451 -0.451433     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-23581.29294882216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23094.89281006', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


