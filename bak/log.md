# 20230211 00:35:59

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [11/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21726
self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21635.5, self.close=21624.6, self.high=21645.1, self.low=21589.3, self.vol=3236.173, self.amt=69960232.9171 
2023-02-11 00:30:01,057:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230211   000500    000959  ...         0.0        0.0       0
5762  20230211   001000    001459  ...         0.0        0.0       0
5763  20230211   001500    001959  ...         0.0        0.0       0
5764  20230211   002000    002459  ...         0.0        0.0       0
5765  20230211   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 00:30:01,059:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21635.5, self.close=21624.6, self.high=21645.1, self.low=21589.3, self.vol=3236.173, self.amt=69960232.9171, ukdf['pct'].iloc[-1]=-0.000499 , ukdf['amount'].iloc[-1]=69960232.9171, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-306921.6704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21629.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21727
self.closeSec=1676046899, self.tradeDate='20230211', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21624.5, self.close=21624.9, self.high=21659.8, self.low=21588.2, self.vol=3151.485, self.amt=68136525.8795 
2023-02-11 00:35:00,520:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230211   001000    001459  ...         0.0        0.0       0
5763  20230211   001500    001959  ...         0.0        0.0       0
5764  20230211   002000    002459  ...         0.0        0.0       0
5765  20230211   002500    002959  ...         0.0        0.0       0
5766  20230211   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 00:35:00,525:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676046899, self.tradeDate='20230211', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21624.5, self.close=21624.9, self.high=21659.8, self.low=21588.2, self.vol=3151.485, self.amt=68136525.8795, ukdf['pct'].iloc[-1]=1.4e-05 , ukdf['amount'].iloc[-1]=68136525.8795, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-306638.8432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21625', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1445  20230211   002500    002959  1676046599  ...  21589.3 -0.000499   1445    5

[5 rows x 11 columns]
2023-02-11 00:30:00,983:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-11 00:30:01,046:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
197  20230210   222500    222959  1676039399  ... -0.000449   1709    5  0.788018
198  20230210   225500    225959  1676041199  ...  0.000600   1715    5  0.787457
199  20230210   232500    232959  1676042999  ... -0.000490   1721    5  0.783202
200  20230210   235500    235959  1676044799  ...  0.001337   1727    5  0.784873
201  20230211   002500    002959  1676046599  ... -0.000499   1445    5  0.787809

[5 rows x 12 columns]
2023-02-11 00:30:01,085:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2110030, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230211, closeTime:002959, close:21624.6, total:909224.3076578999, factor:0.7878092048424449, factorCnt:0, side:buy 
127.0.0.1 - - [11/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7878092048424449, self.count=22293 

self.closeSec=1676046899, self.tradeDate='20230211', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21624.5, self.close=21624.9, self.high=21659.8, self.low=21588.2 
2023-02-11 00:35:00,422:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676046899, self.tradeDate='20230211', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21624.5, self.close=21624.9, self.high=21659.8, self.low=21588.2   
2023-02-11 00:35:00,450:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1442  20230211   001000    001459  1676045699  ...  21657.9 -0.000802   1442    2
1443  20230211   001500    001959  1676045999  ...  21651.3 -0.000895   1443    3
1444  20230211   002000    002459  1676046299  ...  21614.4 -0.001136   1444    4
1445  20230211   002500    002959  1676046599  ...  21589.3 -0.000499   1445    5
1446  20230211   003000    003459  1676046899  ...  21588.2  0.000014   1446    0

[5 rows x 11 columns]
2023-02-11 00:35:00,450:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-11 00:30:32,578:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5755  20230210    215959  21786.8  ...  45.000000  0.381169  0.818591
5756  20230210    222959  21760.3  ...  45.000000  0.392142  0.816744
5757  20230210    225959  21801.2  ...  45.416667  0.401332  0.811757
5758  20230210    232959  21835.9  ...  45.416667  0.400513  0.797092
5759  20230210    235959  21832.7  ...  45.416667  0.369962  0.792002

[5 rows x 33 columns]
0.5064935064935064
acc is : 0.5064935064935064
2023-02-11 00:30:32,761:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
534     1  0.497564  0.502436       1  ...  1.014700  -1.0    0.0  0.937880
535     0  0.518634  0.481366       1  ...  1.013085  -1.0    0.0  0.939372
536     0  0.518839  0.481161       0  ...  1.013298  -1.0    0.0  0.939175
537     0  0.513767  0.486233       0  ...  1.021765  -1.0    0.0  0.931328
538     1  0.458556  0.541444       0  ...  1.022911  -1.0    0.0  0.930282

[5 rows x 10 columns]
2023-02-11 00:30:32,792:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495524  0.504476       1  ...  1.024410  -1.0    0.0  0.919983
46     0  0.516727  0.483273       1  ...  1.022780  -1.0    0.0  0.921447
47     0  0.517597  0.482403       0  ...  1.022995  -1.0    0.0  0.923845
48     0  0.512088  0.487912       0  ...  1.031543  -1.0    0.0  0.915399
49     1  0.458556  0.541444       0  ...  1.022911  -1.0    0.0  0.930282

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '41089.048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21650.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

576  20230211   000000    000959  1676045399  21648.9  21698.3  0.002277
2023-02-11 00:10:01,874:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11145 

self.closeSec=1676045999, self.tradeDate='20230211', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21698.3', self.close='21660'
2023-02-11 00:20:00,593:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676045999, self.tradeDate='20230211', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21698.3', self.close='21660'
2023-02-11 00:20:00,637:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230210   233000    233959  1676043599  21832.7  21792.2 -0.001791
574  20230210   234000    234959  1676044199  21792.2  21636.6 -0.007140
575  20230210   235000    235959  1676044799    21638    21649  0.000573
576  20230211   000000    000959  1676045399  21648.9  21698.3  0.002277
577  20230211   001000    001959  1676045999  21698.3    21660 -0.001765
2023-02-11 00:20:00,637:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11146 

self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21660', self.close='21624.6'
2023-02-11 00:30:01,341:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21660', self.close='21624.6'
127.0.0.1 - - [11/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -
2023-02-11 00:30:01,358:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
574  20230210   234000    234959  1676044199  21792.2  21636.6 -0.007140
575  20230210   235000    235959  1676044799    21638    21649  0.000573
576  20230211   000000    000959  1676045399  21648.9  21698.3  0.002277
577  20230211   001000    001959  1676045999  21698.3    21660 -0.001765
578  20230211   002000    002959  1676046599    21660  21624.6 -0.001634
2023-02-11 00:30:01,358:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17424  20230211   000000    000959  1676045399  21648.9  21698.3
2023-02-11 00:10:01,886:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11146 

self.closeSec=1676045999, self.tradeDate='20230211', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21698.3', self.close='21660'
127.0.0.1 - - [11/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-02-11 00:20:00,630:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676045999, self.tradeDate='20230211', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21698.3', self.close='21660'
2023-02-11 00:20:00,656:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230210   233000    233959  1676043599  21832.7  21792.2
17422  20230210   234000    234959  1676044199  21792.2  21636.6
17423  20230210   235000    235959  1676044799    21638    21649
17424  20230211   000000    000959  1676045399  21648.9  21698.3
17425  20230211   001000    001959  1676045999  21698.3    21660
2023-02-11 00:20:00,674:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11147 

self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21660', self.close='21624.6'
2023-02-11 00:30:01,354:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21660', self.close='21624.6'
2023-02-11 00:30:01,385:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17422  20230210   234000    234959  1676044199  21792.2  21636.6
17423  20230210   235000    235959  1676044799    21638    21649
17424  20230211   000000    000959  1676045399  21648.9  21698.3
17425  20230211   001000    001959  1676045999  21698.3    21660
17426  20230211   002000    002959  1676046599    21660  21624.6
2023-02-11 00:30:01,385:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12240  20230211   000000    000959  1676045399  21648.9  21698.3
2023-02-11 00:10:01,883:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [11/Feb/2023 00:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11146 

self.closeSec=1676045999, self.tradeDate='20230211', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='21698.3', self.close='21660'
2023-02-11 00:20:00,622:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676045999, self.tradeDate='20230211', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='21698.3', self.close='21660'
2023-02-11 00:20:00,653:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230210   233000    233959  1676043599  21832.7  21792.2
12238  20230210   234000    234959  1676044199  21792.2  21636.6
12239  20230210   235000    235959  1676044799    21638    21649
12240  20230211   000000    000959  1676045399  21648.9  21698.3
12241  20230211   001000    001959  1676045999  21698.3    21660
2023-02-11 00:20:00,662:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [11/Feb/2023 00:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11147 

self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002000', self.closeTime='002959', self.symbol='BTCUSDT', self.open='21660', self.close='21624.6'
2023-02-11 00:30:01,337:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002000', self.closeTime='002959',self.symbol='BTCUSDT',self.open='21660', self.close='21624.6'
2023-02-11 00:30:01,384:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12238  20230210   234000    234959  1676044199  21792.2  21636.6
12239  20230210   235000    235959  1676044799    21638    21649
12240  20230211   000000    000959  1676045399  21648.9  21698.3
12241  20230211   001000    001959  1676045999  21698.3    21660
12242  20230211   002000    002959  1676046599    21660  21624.6
2023-02-11 00:30:01,384:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17724
self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002500', self.closeTime='002959', self.symbol='BTCUSDT', self.open=21635.5, self.close=21624.6, self.high=21645.1, self.low=21589.3, self.vol=3236.173, self.amt=69960232.9171 
127.0.0.1 - - [11/Feb/2023 00:30:00] "POST / HTTP/1.1" 200 -
2023-02-11 00:30:01,011:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5761  20230211   000500    000959  ...         0.0        0.0       0
5762  20230211   001000    001459  ...         0.0        0.0       0
5763  20230211   001500    001959  ...         0.0        0.0       0
5764  20230211   002000    002459  ...         0.0        0.0       0
5765  20230211   002500    002959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 00:30:01,018:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676046599, self.tradeDate='20230211', self.openTime='002500', self.closeTime='002959',self.symbol='BTCUSDT',self.open=21635.5, self.close=21624.6, self.high=21645.1, self.low=21589.3, self.vol=3236.173, self.amt=69960232.9171, ukdf['pct'].iloc[-1]=-0.000499 , ukdf['amount'].iloc[-1]=69960232.9171, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5765, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17725
self.closeSec=1676046899, self.tradeDate='20230211', self.openTime='003000', self.closeTime='003459', self.symbol='BTCUSDT', self.open=21624.5, self.close=21624.9, self.high=21659.8, self.low=21588.2, self.vol=3151.485, self.amt=68136525.8795 
127.0.0.1 - - [11/Feb/2023 00:35:00] "POST / HTTP/1.1" 200 -
2023-02-11 00:35:00,527:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5762  20230211   001000    001459  ...         0.0        0.0       0
5763  20230211   001500    001959  ...         0.0        0.0       0
5764  20230211   002000    002459  ...         0.0        0.0       0
5765  20230211   002500    002959  ...         0.0        0.0       0
5766  20230211   003000    003459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-11 00:35:00,529:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676046899, self.tradeDate='20230211', self.openTime='003000', self.closeTime='003459',self.symbol='BTCUSDT',self.open=21624.5, self.close=21624.9, self.high=21659.8, self.low=21588.2, self.vol=3151.485, self.amt=68136525.8795, ukdf['pct'].iloc[-1]=1.4e-05 , ukdf['amount'].iloc[-1]=68136525.8795, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5766, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-02-10 20:00:09,658:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41703F1676030404272I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676030404582482, 'quantity': '38.925', 'price': '21730.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676030403906, 'updatetime': 1676030404582, 'tradetype': 'usdt', 'selfid': 41703, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676030404582, 'clientorderid': '41703F1676030404272I0L65', 'price': '21730.2', 'quantity': '38.925', 'commission': '845.848035', 'commissionasset': 'USDT', 'tradetime': 1676030404582, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676030404582}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Feb/2023 20:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/Feb/2023 20:00:09] "POST / HTTP/1.1" 200 -
2023-02-10 20:00:09,752:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41704F1676030409608I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676030409710982, 'quantity': '42.94', 'price': '21730.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676030409439, 'updatetime': 1676030409710, 'tradetype': 'usdt', 'selfid': 41704, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676030409710, 'clientorderid': '41704F1676030409608I0L65', 'price': '21730.2', 'quantity': '42.94', 'commission': '933.094788', 'commissionasset': 'USDT', 'tradetime': 1676030409710, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676030409710}], 'gatetype': 'simulator', 'handletime': 0}
2023-02-10 20:00:10,058:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41704F1676030409608I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676030409710982, 'quantity': '42.94', 'price': '21730.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676030409439, 'updatetime': 1676030409710, 'tradetype': 'usdt', 'selfid': 41704, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676030409710, 'clientorderid': '41704F1676030409608I0L65', 'price': '21730.2', 'quantity': '42.94', 'commission': '933.094788', 'commissionasset': 'USDT', 'tradetime': 1676030409710, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676030409710}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Feb/2023 20:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [11/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=932161.693212, self.flagDict['side']='buy', self.tradeCount=18, self.count=464
self.closeSec=1676044799, self.tradeDate='20230210', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=21726.7, self.close=21649.0, self.high=21897.0, self.low=21484.0, self.vol=120581.027, self.amt=2621304951.92274 
2023-02-11 00:00:01,597:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676044799, self.tradeDate='20230210', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=21726.7, self.close=21649.0, self.high=21897.0, self.low=21484.0, self.vol=120581.027, self.amt=2621304951.92274 
2023-02-11 00:00:01,633:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230210   040000    075959  ...  165794.930  3.626204e+09 -0.010907
722  20230210   080000    115959  ...   45873.626  1.002400e+09  0.001212
723  20230210   120000    155959  ...   68529.707  1.493235e+09  0.003873
724  20230210   160000    195959  ...   48365.698  1.055254e+09 -0.008008
725  20230210   200000    235959  ...  120581.027  2.621305e+09 -0.003572

[5 rows x 11 columns]
2023-02-11 00:00:03,690:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230210   040000    075959  1675987199  ...    721  0.389329 -0.397613     NaN
722  20230210   080000    115959  1676001599  ...    722  0.528172  0.231654     NaN
723  20230210   120000    155959  1676015999  ...    723  0.608215  0.590645     NaN
724  20230210   160000    195959  1676030399  ...    724  0.674292  0.884227     1.0
725  20230210   200000    235959  1676044799  ...    725  0.696660  0.969925     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.94', 'enterprice': '21730.2', 'countrevence': '0', 'unrealprofit': '-3770.201889144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21642.3983724', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


