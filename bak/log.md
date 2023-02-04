# 20230204 16:35:49

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19902
self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23307.4, self.close=23318.9, self.high=23318.9, self.low=23300.4, self.vol=518.24, self.amt=12078721.8674 
127.0.0.1 - - [04/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-04 16:30:01,013:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230204   160500    160959  ...         0.0        0.0       0
5954  20230204   161000    161459  ...         0.0        0.0       0
5955  20230204   161500    161959  ...         0.0        0.0       0
5956  20230204   162000    162459  ...         0.0        0.0       0
5957  20230204   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 16:30:01,026:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23307.4, self.close=23318.9, self.high=23318.9, self.low=23300.4, self.vol=518.24, self.amt=12078721.8674, ukdf['pct'].iloc[-1]=0.000493 , ukdf['amount'].iloc[-1]=12078721.8674, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-408564.952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23318.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=19903
self.closeSec=1675499699, self.tradeDate='20230204', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23318.8, self.close=23301.5, self.high=23321.5, self.low=23300.0, self.vol=424.008, self.amt=9882903.1925 
127.0.0.1 - - [04/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-04 16:35:00,701:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230204   161000    161459  ...         0.0        0.0       0
5955  20230204   161500    161959  ...         0.0        0.0       0
5956  20230204   162000    162459  ...         0.0        0.0       0
5957  20230204   162500    162959  ...         0.0        0.0       0
5958  20230204   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 16:35:00,701:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675499699, self.tradeDate='20230204', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23318.8, self.close=23301.5, self.high=23321.5, self.low=23300.0, self.vol=424.008, self.amt=9882903.1925, ukdf['pct'].iloc[-1]=-0.000746 , ukdf['amount'].iloc[-1]=9882903.1925, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-407656.85064768768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23303.70924368', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1637  20230204   162500    162959  1675499399  ...  23300.4  0.000493   1637    5

[5 rows x 11 columns]
2023-02-04 16:30:00,956:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-04 16:30:01,024:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230204   142500    142959  1675492199  ... -0.000236   1613    5  0.660132
230  20230204   145500    145959  1675493999  ... -0.000189   1619    5  0.662831
231  20230204   152500    152959  1675495799  ... -0.000056   1625    5  0.665992
232  20230204   155500    155959  1675497599  ... -0.000351   1631    5  0.669222
233  20230204   162500    162959  1675499399  ...  0.000493   1637    5  0.672554

[5 rows x 12 columns]
2023-02-04 16:30:01,062:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2041630, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230204, closeTime:162959, close:23318.9, total:928613.5591976999, factor:0.6725544865828803, factorCnt:0, side:buy 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6725544865828803, self.count=20469 

self.closeSec=1675499699, self.tradeDate='20230204', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23318.8, self.close=23301.5, self.high=23321.5, self.low=23300.0 
2023-02-04 16:35:00,662:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675499699, self.tradeDate='20230204', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23318.8, self.close=23301.5, self.high=23321.5, self.low=23300.0   
127.0.0.1 - - [04/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-04 16:35:00,680:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230204   161000    161459  1675498499  ...  23331.8  0.000373   1634    2
1635  20230204   161500    161959  1675498799  ...  23317.0 -0.000938   1635    3
1636  20230204   162000    162459  1675499099  ...  23303.1 -0.000485   1636    4
1637  20230204   162500    162959  1675499399  ...  23300.4  0.000493   1637    5
1638  20230204   163000    163459  1675499699  ...  23300.0 -0.000746   1638    0

[5 rows x 11 columns]
2023-02-04 16:35:00,680:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-04 16:30:33,378:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230204    135959  23276.5  ...  46.250000  0.465362  0.685762
5788  20230204    142959  23314.2  ...  46.666667  0.467961  0.690806
5789  20230204    145959  23324.9  ...  47.083333  0.470660  0.694100
5790  20230204    152959  23335.8  ...  47.083333  0.468368  0.698511
5791  20230204    155959  23325.4  ...  46.666667  0.467697  0.703013

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-02-04 16:30:33,505:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497569  0.502431       1  ...  0.996563  -1.0    0.0  1.016548
538     1  0.495694  0.504306       1  ...  0.996093  -1.0    0.0  1.017028
539     1  0.496549  0.503451       0  ...  0.996537  -1.0    0.0  1.016574
540     1  0.492671  0.507329       0  ...  0.996666  -1.0    0.0  1.016444
541     1  0.498860  0.501140       0  ...  0.996815  -1.0    0.0  1.016291

[5 rows x 10 columns]
2023-02-04 16:30:33,545:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497506  0.502494       1  ...  0.996563  -1.0    0.0  1.017542
46     1  0.495884  0.504116       1  ...  0.996093  -1.0    0.0  1.018448
47     1  0.495775  0.504225       0  ...  0.996537  -1.0    0.0  1.015282
48     1  0.490966  0.509034       0  ...  0.937740  -1.0    0.0  1.014878
49     1  0.498860  0.501140       0  ...  0.996815  -1.0    0.0  1.016291

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.907', 'enterprice': '23688.5', 'countrevence': '0', 'unrealprofit': '11342.869', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23321.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230204   160000    160959  1675498199  23322.4  23331.9  0.000407
2023-02-04 16:10:01,564:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10233 

self.closeSec=1675498799, self.tradeDate='20230204', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23331.9', self.close='23318.7'
2023-02-04 16:20:00,563:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675498799, self.tradeDate='20230204', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23331.9', self.close='23318.7'
127.0.0.1 - - [04/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-04 16:20:00,609:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230204   153000    153959  1675496399  23325.4  23297.8 -0.001179
526  20230204   154000    154959  1675496999  23297.9  23344.5  0.002004
527  20230204   155000    155959  1675497599  23344.4  23322.4 -0.000947
528  20230204   160000    160959  1675498199  23322.4  23331.9  0.000407
529  20230204   161000    161959  1675498799  23331.9  23318.7 -0.000566
2023-02-04 16:20:00,609:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10234 

self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23318.7', self.close='23318.9'
127.0.0.1 - - [04/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-04 16:30:01,282:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23318.7', self.close='23318.9'
2023-02-04 16:30:01,311:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230204   154000    154959  1675496999  23297.9  23344.5  0.002004
527  20230204   155000    155959  1675497599  23344.4  23322.4 -0.000947
528  20230204   160000    160959  1675498199  23322.4  23331.9  0.000407
529  20230204   161000    161959  1675498799  23331.9  23318.7 -0.000566
530  20230204   162000    162959  1675499399  23318.7  23318.9  0.000009
2023-02-04 16:30:01,318:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230204   160000    160959  1675498199  23322.4  23331.9
2023-02-04 16:10:01,581:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10234 

self.closeSec=1675498799, self.tradeDate='20230204', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23331.9', self.close='23318.7'
2023-02-04 16:20:00,634:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675498799, self.tradeDate='20230204', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23331.9', self.close='23318.7'
2023-02-04 16:20:00,659:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230204   153000    153959  1675496399  23325.4  23297.8
17518  20230204   154000    154959  1675496999  23297.9  23344.5
17519  20230204   155000    155959  1675497599  23344.4  23322.4
17520  20230204   160000    160959  1675498199  23322.4  23331.9
17521  20230204   161000    161959  1675498799  23331.9  23318.7
2023-02-04 16:20:00,659:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10235 

self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23318.7', self.close='23318.9'
127.0.0.1 - - [04/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -
2023-02-04 16:30:01,291:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23318.7', self.close='23318.9'
2023-02-04 16:30:01,341:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230204   154000    154959  1675496999  23297.9  23344.5
17519  20230204   155000    155959  1675497599  23344.4  23322.4
17520  20230204   160000    160959  1675498199  23322.4  23331.9
17521  20230204   161000    161959  1675498799  23331.9  23318.7
17522  20230204   162000    162959  1675499399  23318.7  23318.9
2023-02-04 16:30:01,345:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230204   160000    160959  1675498199  23322.4  23331.9
2023-02-04 16:10:01,574:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10234 

self.closeSec=1675498799, self.tradeDate='20230204', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23331.9', self.close='23318.7'
2023-02-04 16:20:00,599:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675498799, self.tradeDate='20230204', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23331.9', self.close='23318.7'
2023-02-04 16:20:00,655:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230204   153000    153959  1675496399  23325.4  23297.8
12190  20230204   154000    154959  1675496999  23297.9  23344.5
12191  20230204   155000    155959  1675497599  23344.4  23322.4
12192  20230204   160000    160959  1675498199  23322.4  23331.9
12193  20230204   161000    161959  1675498799  23331.9  23318.7
2023-02-04 16:20:00,655:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Feb/2023 16:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10235 

self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23318.7', self.close='23318.9'
2023-02-04 16:30:01,321:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23318.7', self.close='23318.9'
2023-02-04 16:30:01,357:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230204   154000    154959  1675496999  23297.9  23344.5
12191  20230204   155000    155959  1675497599  23344.4  23322.4
12192  20230204   160000    160959  1675498199  23322.4  23331.9
12193  20230204   161000    161959  1675498799  23331.9  23318.7
12194  20230204   162000    162959  1675499399  23318.7  23318.9
2023-02-04 16:30:01,357:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15900
self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23307.4, self.close=23318.9, self.high=23318.9, self.low=23300.4, self.vol=518.24, self.amt=12078721.8674 
127.0.0.1 - - [04/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-04 16:30:01,018:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230204   160500    160959  ...         0.0        0.0       0
5954  20230204   161000    161459  ...         0.0        0.0       0
5955  20230204   161500    161959  ...         0.0        0.0       0
5956  20230204   162000    162459  ...         0.0        0.0       0
5957  20230204   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 16:30:01,018:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675499399, self.tradeDate='20230204', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23307.4, self.close=23318.9, self.high=23318.9, self.low=23300.4, self.vol=518.24, self.amt=12078721.8674, ukdf['pct'].iloc[-1]=0.000493 , ukdf['amount'].iloc[-1]=12078721.8674, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [04/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=15901
self.closeSec=1675499699, self.tradeDate='20230204', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23318.8, self.close=23301.5, self.high=23321.5, self.low=23300.0, self.vol=424.008, self.amt=9882903.1925 
2023-02-04 16:35:00,755:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230204   161000    161459  ...         0.0        0.0       0
5955  20230204   161500    161959  ...         0.0        0.0       0
5956  20230204   162000    162459  ...         0.0        0.0       0
5957  20230204   162500    162959  ...         0.0        0.0       0
5958  20230204   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-04 16:35:00,756:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675499699, self.tradeDate='20230204', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23318.8, self.close=23301.5, self.high=23321.5, self.low=23300.0, self.vol=424.008, self.amt=9882903.1925, ukdf['pct'].iloc[-1]=-0.000746 , ukdf['amount'].iloc[-1]=9882903.1925, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230204   040000    075959  1675468799  ...    721  0.846087  0.951234     1.0
722  20230204   080000    115959  1675483199  ...    722  0.814592  0.834734     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-14003.6616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23340.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=426
self.closeSec=1675497599, self.tradeDate='20230204', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23340.8, self.close=23322.4, self.high=23358.2, self.low=23250.0, self.vol=28301.188, self.amt=659863097.7127 
127.0.0.1 - - [04/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-04 16:00:01,868:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675497599, self.tradeDate='20230204', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23340.8, self.close=23322.4, self.high=23358.2, self.low=23250.0, self.vol=28301.188, self.amt=659863097.7127 
2023-02-04 16:00:01,894:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230203   200000    235959  ...  189870.022  4.455432e+09  0.002898
720  20230204   000000    035959  ...   91933.801  2.160911e+09 -0.012410
721  20230204   040000    075959  ...   51798.392  1.209502e+09  0.004998
722  20230204   080000    115959  ...   26184.717  6.126349e+08 -0.003582
723  20230204   120000    155959  ...   28301.188  6.598631e+08 -0.000788

[5 rows x 11 columns]
2023-02-04 16:00:03,846:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230203   200000    235959  1675439999  ...    719  0.735980  0.650313     1.0
720  20230204   000000    035959  1675454399  ...    720  0.744472  0.659472     1.0
721  20230204   040000    075959  1675468799  ...    721  0.846087  0.951234     1.0
722  20230204   080000    115959  1675483199  ...    722  0.814592  0.834734     1.0
723  20230204   120000    155959  1675497599  ...    723  0.743165  0.596458     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-14655.21434788212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23323.97808367', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


