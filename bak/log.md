# 20230203 16:35:51

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [03/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19614
self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23374.7, self.close=23397.1, self.high=23400.0, self.low=23358.0, self.vol=1381.098, self.amt=32290834.9164 
2023-02-03 16:30:01,267:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230203   160500    160959  ...         0.0        0.0       0
5954  20230203   161000    161459  ...         0.0        0.0       0
5955  20230203   161500    161959  ...         0.0        0.0       0
5956  20230203   162000    162459  ...         0.0        0.0       0
5957  20230203   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 16:30:01,267:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23374.7, self.close=23397.1, self.high=23400.0, self.low=23358.0, self.vol=1381.098, self.amt=32290834.9164, ukdf['pct'].iloc[-1]=0.000958 , ukdf['amount'].iloc[-1]=32290834.9164, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-413187.38299319024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23395.61519199', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19615
self.closeSec=1675413299, self.tradeDate='20230203', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23397.0, self.close=23410.0, self.high=23422.8, self.low=23397.0, self.vol=1388.301, self.amt=32501826.3098 
2023-02-03 16:35:00,516:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230203   161000    161459  ...         0.0        0.0       0
5955  20230203   161500    161959  ...         0.0        0.0       0
5956  20230203   162000    162459  ...         0.0        0.0       0
5957  20230203   162500    162959  ...         0.0        0.0       0
5958  20230203   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 16:35:00,518:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675413299, self.tradeDate='20230203', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23397.0, self.close=23410.0, self.high=23422.8, self.low=23397.0, self.vol=1388.301, self.amt=32501826.3098, ukdf['pct'].iloc[-1]=0.000551 , ukdf['amount'].iloc[-1]=32501826.3098, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-414053.0032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23410', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230203   162000    162459  1675412699  ...  23352.0 -0.001329   1636    4
1637  20230203   162500    162959  1675412999  ...  23358.0  0.000958   1637    5

[5 rows x 11 columns]
2023-02-03 16:30:01,217:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-03 16:30:01,284:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230203   142500    142959  1675405799  ...  0.000455   1613    5  0.550983
230  20230203   145500    145959  1675407599  ...  0.000102   1619    5  0.558270
231  20230203   152500    152959  1675409399  ... -0.002236   1625    5  0.566654
232  20230203   155500    155959  1675411199  ... -0.000401   1631    5  0.575508
233  20230203   162500    162959  1675412999  ...  0.000958   1637    5  0.584839

[5 rows x 12 columns]
127.0.0.1 - - [03/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=83, self.factor=0.58483924933157, self.count=20181 

self.closeSec=1675413299, self.tradeDate='20230203', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23397.0, self.close=23410.0, self.high=23422.8, self.low=23397.0 
2023-02-03 16:35:00,428:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675413299, self.tradeDate='20230203', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23397.0, self.close=23410.0, self.high=23422.8, self.low=23397.0   
2023-02-03 16:35:00,495:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230203   161000    161459  1675412099  ...  23328.8 -0.000786   1634    2
1635  20230203   161500    161959  1675412399  ...  23377.0  0.000551   1635    3
1636  20230203   162000    162459  1675412699  ...  23352.0 -0.001329   1636    4
1637  20230203   162500    162959  1675412999  ...  23358.0  0.000958   1637    5
1638  20230203   163000    163459  1675413299  ...  23397.0  0.000551   1638    0

[5 rows x 11 columns]
2023-02-03 16:35:00,495:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-03 16:30:32,363:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230203    135959  23515.8  ...  48.750000  0.496487  0.688758
5788  20230203    142959  23526.8  ...  48.750000  0.495344  0.696259
5789  20230203    145959  23520.9  ...  48.750000  0.494017  0.703872
5790  20230203    152959  23513.6  ...  48.750000  0.487194  0.714116
5791  20230203    155959  23476.6  ...  48.333333  0.483574  0.725343

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-02-03 16:30:32,512:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493329  0.506671       0  ...  0.926698  -1.0    0.0  1.032343
538     1  0.487483  0.512517       0  ...  0.926982  -1.0    0.0  1.032027
539     1  0.489988  0.510012       0  ...  0.928436  -1.0    0.0  1.030407
540     1  0.482476  0.517524       0  ...  0.929212  -1.0    0.0  1.029547
541     1  0.483565  0.516435       0  ...  0.931588  -1.0    0.0  1.026914

[5 rows x 10 columns]
2023-02-03 16:30:32,549:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495858  0.504142       0  ...  0.926698  -1.0    0.0  1.036963
46     1  0.488751  0.511249       0  ...  0.926982  -1.0    0.0  1.035595
47     1  0.490080  0.509920       0  ...  0.928436  -1.0    0.0  1.030991
48     1  0.483683  0.516317       0  ...  0.929212  -1.0    0.0  1.031399
49     1  0.483565  0.516435       0  ...  0.931588  -1.0    0.0  1.026914

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '8834.9821568278', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23402.6430046', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230203   160000    160959  1675411799  23457.1  23411.3 -0.001953
2023-02-03 16:10:01,632:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10089 

self.closeSec=1675412399, self.tradeDate='20230203', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23411.2', self.close='23405.8'
2023-02-03 16:20:00,490:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675412399, self.tradeDate='20230203', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23411.2', self.close='23405.8'
2023-02-03 16:20:00,575:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230203   153000    153959  1675409999  23476.6  23467.2 -0.000405
526  20230203   154000    154959  1675410599  23467.1  23479.5  0.000524
527  20230203   155000    155959  1675411199  23479.5  23457.1 -0.000954
528  20230203   160000    160959  1675411799  23457.1  23411.3 -0.001953
529  20230203   161000    161959  1675412399  23411.2  23405.8 -0.000235
2023-02-03 16:20:00,575:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10090 

self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23405.7', self.close='23397.1'
2023-02-03 16:30:01,636:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23405.7', self.close='23397.1'
2023-02-03 16:30:01,690:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230203   154000    154959  1675410599  23467.1  23479.5  0.000524
527  20230203   155000    155959  1675411199  23479.5  23457.1 -0.000954
528  20230203   160000    160959  1675411799  23457.1  23411.3 -0.001953
529  20230203   161000    161959  1675412399  23411.2  23405.8 -0.000235
530  20230203   162000    162959  1675412999  23405.7  23397.1 -0.000372
2023-02-03 16:30:01,690:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230203   160000    160959  1675411799  23457.1  23411.3
2023-02-03 16:10:01,637:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10090 

self.closeSec=1675412399, self.tradeDate='20230203', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23411.2', self.close='23405.8'
2023-02-03 16:20:00,520:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675412399, self.tradeDate='20230203', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23411.2', self.close='23405.8'
2023-02-03 16:20:00,584:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230203   153000    153959  1675409999  23476.6  23467.2
17518  20230203   154000    154959  1675410599  23467.1  23479.5
17519  20230203   155000    155959  1675411199  23479.5  23457.1
17520  20230203   160000    160959  1675411799  23457.1  23411.3
17521  20230203   161000    161959  1675412399  23411.2  23405.8
2023-02-03 16:20:00,584:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10091 

self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23405.7', self.close='23397.1'
2023-02-03 16:30:01,619:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23405.7', self.close='23397.1'
127.0.0.1 - - [03/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-03 16:30:01,702:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230203   154000    154959  1675410599  23467.1  23479.5
17519  20230203   155000    155959  1675411199  23479.5  23457.1
17520  20230203   160000    160959  1675411799  23457.1  23411.3
17521  20230203   161000    161959  1675412399  23411.2  23405.8
17522  20230203   162000    162959  1675412999  23405.7  23397.1
2023-02-03 16:30:01,702:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230203   160000    160959  1675411799  23457.1  23411.3
2023-02-03 16:10:01,631:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10090 

self.closeSec=1675412399, self.tradeDate='20230203', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23411.2', self.close='23405.8'
2023-02-03 16:20:00,550:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675412399, self.tradeDate='20230203', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23411.2', self.close='23405.8'
2023-02-03 16:20:00,594:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230203   153000    153959  1675409999  23476.6  23467.2
12190  20230203   154000    154959  1675410599  23467.1  23479.5
12191  20230203   155000    155959  1675411199  23479.5  23457.1
12192  20230203   160000    160959  1675411799  23457.1  23411.3
12193  20230203   161000    161959  1675412399  23411.2  23405.8
2023-02-03 16:20:00,594:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10091 

self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23405.7', self.close='23397.1'
2023-02-03 16:30:01,612:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23405.7', self.close='23397.1'
127.0.0.1 - - [03/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-03 16:30:01,645:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230203   154000    154959  1675410599  23467.1  23479.5
12191  20230203   155000    155959  1675411199  23479.5  23457.1
12192  20230203   160000    160959  1675411799  23457.1  23411.3
12193  20230203   161000    161959  1675412399  23411.2  23405.8
12194  20230203   162000    162959  1675412999  23405.7  23397.1
2023-02-03 16:30:01,645:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15612
self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23374.7, self.close=23397.1, self.high=23400.0, self.low=23358.0, self.vol=1381.098, self.amt=32290834.9164 
127.0.0.1 - - [03/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-03 16:30:01,240:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230203   160500    160959  ...         0.0        0.0       0
5954  20230203   161000    161459  ...         0.0        0.0       0
5955  20230203   161500    161959  ...         0.0        0.0       0
5956  20230203   162000    162459  ...         0.0        0.0       0
5957  20230203   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 16:30:01,240:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675412999, self.tradeDate='20230203', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23374.7, self.close=23397.1, self.high=23400.0, self.low=23358.0, self.vol=1381.098, self.amt=32290834.9164, ukdf['pct'].iloc[-1]=0.000958 , ukdf['amount'].iloc[-1]=32290834.9164, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15613
self.closeSec=1675413299, self.tradeDate='20230203', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23397.0, self.close=23410.0, self.high=23422.8, self.low=23397.0, self.vol=1388.301, self.amt=32501826.3098 
2023-02-03 16:35:00,511:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230203   161000    161459  ...         0.0        0.0       0
5955  20230203   161500    161959  ...         0.0        0.0       0
5956  20230203   162000    162459  ...         0.0        0.0       0
5957  20230203   162500    162959  ...         0.0        0.0       0
5958  20230203   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-03 16:35:00,513:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675413299, self.tradeDate='20230203', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23397.0, self.close=23410.0, self.high=23422.8, self.low=23397.0, self.vol=1388.301, self.amt=32501826.3098, ukdf['pct'].iloc[-1]=0.000551 , ukdf['amount'].iloc[-1]=32501826.3098, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230203   040000    075959  1675382399  ...    721  0.727334  0.683564     1.0
722  20230203   080000    115959  1675396799  ...    722  0.700479  0.587199     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-6325.73514245304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23537.75180314', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=420
self.closeSec=1675411199, self.tradeDate='20230203', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23535.0, self.close=23457.1, self.high=23568.5, self.low=23450.0, self.vol=25571.08, self.amt=601272748.3297 
2023-02-03 16:00:02,345:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675411199, self.tradeDate='20230203', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23535.0, self.close=23457.1, self.high=23568.5, self.low=23450.0, self.vol=25571.08, self.amt=601272748.3297 
127.0.0.1 - - [03/Feb/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-02-03 16:00:02,389:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230202   200000    235959  ...  152792.644  3.629087e+09  0.000684
720  20230203   000000    035959  ...  131578.698  3.146825e+09 -0.001611
721  20230203   040000    075959  ...  111289.486  2.630096e+09 -0.013098
722  20230203   080000    115959  ...   53873.247  1.266839e+09  0.001779
723  20230203   120000    155959  ...   25571.080  6.012727e+08 -0.003306

[5 rows x 11 columns]
2023-02-03 16:00:04,337:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230202   200000    235959  1675353599  ...    719  0.692199  0.611737     1.0
720  20230203   000000    035959  1675367999  ...    720  0.734255  0.721104     1.0
721  20230203   040000    075959  1675382399  ...    721  0.727334  0.683564     1.0
722  20230203   080000    115959  1675396799  ...    722  0.700479  0.587199     NaN
723  20230203   120000    155959  1675411199  ...    723  0.675625  0.497663     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-9464.3556', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23457.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


