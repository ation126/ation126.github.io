# 20230208 16:36:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21054
self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23204.8, self.close=23183.3, self.high=23204.9, self.low=23183.3, self.vol=546.877, self.amt=12683792.5215 
127.0.0.1 - - [08/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-08 16:30:00,641:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230208   160500    160959  ...         0.0        0.0       0
5954  20230208   161000    161459  ...         0.0        0.0       0
5955  20230208   161500    161959  ...         0.0        0.0       0
5956  20230208   162000    162459  ...         0.0        0.0       0
5957  20230208   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 16:30:00,641:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23204.8, self.close=23183.3, self.high=23204.9, self.low=23183.3, self.vol=546.877, self.amt=12683792.5215, ukdf['pct'].iloc[-1]=-0.000927 , ukdf['amount'].iloc[-1]=12683792.5215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-400381.016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23182.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21055
self.closeSec=1675845299, self.tradeDate='20230208', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23182.0, self.close=23180.3, self.high=23191.8, self.low=23166.0, self.vol=1053.057, self.amt=24407503.0541 
127.0.0.1 - - [08/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 16:35:00,545:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230208   161000    161459  ...         0.0        0.0       0
5955  20230208   161500    161959  ...         0.0        0.0       0
5956  20230208   162000    162459  ...         0.0        0.0       0
5957  20230208   162500    162959  ...         0.0        0.0       0
5958  20230208   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 16:35:00,547:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675845299, self.tradeDate='20230208', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23182.0, self.close=23180.3, self.high=23191.8, self.low=23166.0, self.vol=1053.057, self.amt=24407503.0541, ukdf['pct'].iloc[-1]=-0.000129 , ukdf['amount'].iloc[-1]=24407503.0541, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-400297.84142602752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23181.41781152', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1636  20230208   162000    162459  1675844699  ...  23199.2 -0.000280   1636    4
1637  20230208   162500    162959  1675844999  ...  23183.3 -0.000927   1637    5

[5 rows x 11 columns]
2023-02-08 16:30:00,599:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-08 16:30:00,687:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230208   142500    142959  1675837799  ... -0.000065   1613    5  0.333649
230  20230208   145500    145959  1675839599  ... -0.000073   1619    5  0.331514
231  20230208   152500    152959  1675841399  ...  0.000228   1625    5  0.328044
232  20230208   155500    155959  1675843199  ...  0.000504   1631    5  0.324494
233  20230208   162500    162959  1675844999  ... -0.000927   1637    5  0.322999

[5 rows x 12 columns]

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=31, self.factor=0.32299941135884613, self.count=21621 

self.closeSec=1675845299, self.tradeDate='20230208', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23182.0, self.close=23180.3, self.high=23191.8, self.low=23166.0 
2023-02-08 16:35:00,444:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675845299, self.tradeDate='20230208', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23182.0, self.close=23180.3, self.high=23191.8, self.low=23166.0   
127.0.0.1 - - [08/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 16:35:00,524:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230208   161000    161459  1675844099  ...  23184.5 -0.000237   1634    2
1635  20230208   161500    161959  1675844399  ...  23183.7  0.000867   1635    3
1636  20230208   162000    162459  1675844699  ...  23199.2 -0.000280   1636    4
1637  20230208   162500    162959  1675844999  ...  23183.3 -0.000927   1637    5
1638  20230208   163000    163459  1675845299  ...  23166.0 -0.000129   1638    0

[5 rows x 11 columns]
2023-02-08 16:35:00,524:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-08 16:30:33,351:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230208    135959  23212.0  ...  47.083333  0.532744  0.301834
5788  20230208    142959  23217.2  ...  47.083333  0.527442  0.306469
5789  20230208    145959  23194.6  ...  47.083333  0.526947  0.310999
5790  20230208    152959  23192.4  ...  47.500000  0.533500  0.312243
5791  20230208    155959  23223.2  ...  47.916667  0.534291  0.313045

[5 rows x 33 columns]
0.5
acc is : 0.5
2023-02-08 16:30:33,515:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.481347  0.518653       0  ...  0.979252  -1.0    0.0  1.004426
538     1  0.476093  0.523907       0  ...  0.979341  -1.0    0.0  1.004335
539     1  0.477441  0.522559       1  ...  0.978040  -1.0    0.0  1.005669
540     1  0.488549  0.511451       1  ...  0.977884  -1.0    0.0  1.005829
541     1  0.485760  0.514240       0  ...  0.979720  -1.0    0.0  1.003941

[5 rows x 10 columns]
2023-02-08 16:30:33,547:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483031  0.516969       0  ...  0.979252  -1.0    0.0  1.005689
46     1  0.477120  0.522880       0  ...  0.979341  -1.0    0.0  1.005393
47     1  0.477583  0.522417       1  ...  0.978040  -1.0    0.0  1.004616
48     1  0.487990  0.512010       1  ...  0.977884  -1.0    0.0  1.003513
49     1  0.485760  0.514240       0  ...  0.979720  -1.0    0.0  1.003941

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '-8259.7372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23180.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230208   160000    160959  1675843799    23227  23196.7 -0.001300
2023-02-08 16:10:01,815:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10809 

self.closeSec=1675844399, self.tradeDate='20230208', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23196.6', self.close='23211.3'
2023-02-08 16:20:00,528:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675844399, self.tradeDate='20230208', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23196.6', self.close='23211.3'
2023-02-08 16:20:00,584:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230208   153000    153959  1675841999  23223.2  23204.4 -0.000810
526  20230208   154000    154959  1675842599  23204.3  23225.9  0.000927
527  20230208   155000    155959  1675843199  23225.9  23226.9  0.000043
528  20230208   160000    160959  1675843799    23227  23196.7 -0.001300
529  20230208   161000    161959  1675844399  23196.6  23211.3  0.000629
2023-02-08 16:20:00,585:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10810 

self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23212', self.close='23183.3'
2023-02-08 16:30:00,723:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23212', self.close='23183.3'
2023-02-08 16:30:00,804:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230208   154000    154959  1675842599  23204.3  23225.9  0.000927
527  20230208   155000    155959  1675843199  23225.9  23226.9  0.000043
528  20230208   160000    160959  1675843799    23227  23196.7 -0.001300
529  20230208   161000    161959  1675844399  23196.6  23211.3  0.000629
530  20230208   162000    162959  1675844999    23212  23183.3 -0.001206
2023-02-08 16:30:00,808:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230208   160000    160959  1675843799    23227  23196.7
2023-02-08 16:10:01,820:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10810 

self.closeSec=1675844399, self.tradeDate='20230208', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23196.6', self.close='23211.3'
2023-02-08 16:20:00,521:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675844399, self.tradeDate='20230208', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23196.6', self.close='23211.3'
127.0.0.1 - - [08/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-08 16:20:00,576:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230208   153000    153959  1675841999  23223.2  23204.4
17518  20230208   154000    154959  1675842599  23204.3  23225.9
17519  20230208   155000    155959  1675843199  23225.9  23226.9
17520  20230208   160000    160959  1675843799    23227  23196.7
17521  20230208   161000    161959  1675844399  23196.6  23211.3
2023-02-08 16:20:00,584:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10811 

self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23212', self.close='23183.3'
127.0.0.1 - - [08/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-08 16:30:00,764:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23212', self.close='23183.3'
2023-02-08 16:30:00,824:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230208   154000    154959  1675842599  23204.3  23225.9
17519  20230208   155000    155959  1675843199  23225.9  23226.9
17520  20230208   160000    160959  1675843799    23227  23196.7
17521  20230208   161000    161959  1675844399  23196.6  23211.3
17522  20230208   162000    162959  1675844999    23212  23183.3
2023-02-08 16:30:00,824:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230208   160000    160959  1675843799    23227  23196.7
2023-02-08 16:10:01,774:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10810 

self.closeSec=1675844399, self.tradeDate='20230208', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='23196.6', self.close='23211.3'
2023-02-08 16:20:00,527:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675844399, self.tradeDate='20230208', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='23196.6', self.close='23211.3'
2023-02-08 16:20:00,588:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230208   153000    153959  1675841999  23223.2  23204.4
12190  20230208   154000    154959  1675842599  23204.3  23225.9
12191  20230208   155000    155959  1675843199  23225.9  23226.9
12192  20230208   160000    160959  1675843799    23227  23196.7
12193  20230208   161000    161959  1675844399  23196.6  23211.3
2023-02-08 16:20:00,588:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [08/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10811 

self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='23212', self.close='23183.3'
2023-02-08 16:30:00,750:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='23212', self.close='23183.3'
2023-02-08 16:30:00,800:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230208   154000    154959  1675842599  23204.3  23225.9
12191  20230208   155000    155959  1675843199  23225.9  23226.9
12192  20230208   160000    160959  1675843799    23227  23196.7
12193  20230208   161000    161959  1675844399  23196.6  23211.3
12194  20230208   162000    162959  1675844999    23212  23183.3
2023-02-08 16:30:00,800:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [08/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17052
self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=23204.8, self.close=23183.3, self.high=23204.9, self.low=23183.3, self.vol=546.877, self.amt=12683792.5215 
2023-02-08 16:30:00,539:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230208   160500    160959  ...         0.0        0.0       0
5954  20230208   161000    161459  ...         0.0        0.0       0
5955  20230208   161500    161959  ...         0.0        0.0       0
5956  20230208   162000    162459  ...         0.0        0.0       0
5957  20230208   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 16:30:00,540:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675844999, self.tradeDate='20230208', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=23204.8, self.close=23183.3, self.high=23204.9, self.low=23183.3, self.vol=546.877, self.amt=12683792.5215, ukdf['pct'].iloc[-1]=-0.000927 , ukdf['amount'].iloc[-1]=12683792.5215, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17053
self.closeSec=1675845299, self.tradeDate='20230208', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=23182.0, self.close=23180.3, self.high=23191.8, self.low=23166.0, self.vol=1053.057, self.amt=24407503.0541 
127.0.0.1 - - [08/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-08 16:35:00,601:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230208   161000    161459  ...         0.0        0.0       0
5955  20230208   161500    161959  ...         0.0        0.0       0
5956  20230208   162000    162459  ...         0.0        0.0       0
5957  20230208   162500    162959  ...         0.0        0.0       0
5958  20230208   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-08 16:35:00,601:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675845299, self.tradeDate='20230208', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=23182.0, self.close=23180.3, self.high=23191.8, self.low=23166.0, self.vol=1053.057, self.amt=24407503.0541, ukdf['pct'].iloc[-1]=-0.000129 , ukdf['amount'].iloc[-1]=24407503.0541, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230208   040000    075959  1675814399  ...    721  0.400748 -0.347794     NaN
722  20230208   080000    115959  1675828799  ...    722  0.398882 -0.337792     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-17444.62603186488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23252.38862458', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=450
self.closeSec=1675843199, self.tradeDate='20230208', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23250.5, self.close=23226.9, self.high=23283.5, self.low=23173.7, self.vol=24681.986, self.amt=573048473.6235 
127.0.0.1 - - [08/Feb/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-02-08 16:00:00,899:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675843199, self.tradeDate='20230208', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23250.5, self.close=23226.9, self.high=23283.5, self.low=23173.7, self.vol=24681.986, self.amt=573048473.6235 
2023-02-08 16:00:00,919:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230207   200000    235959  ...   52655.269  1.208872e+09 -0.003117
720  20230208   000000    035959  ...  209737.864  4.833662e+09  0.008179
721  20230208   040000    075959  ...   68836.763  1.596656e+09  0.006497
722  20230208   080000    115959  ...   49143.645  1.145290e+09  0.000624
723  20230208   120000    155959  ...   24681.986  5.730485e+08 -0.001019

[5 rows x 11 columns]
2023-02-08 16:00:02,091:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230207   200000    235959  1675785599  ...    719  0.575800  0.331884     NaN
720  20230208   000000    035959  1675799999  ...    720  0.445139 -0.181049     NaN
721  20230208   040000    075959  1675814399  ...    721  0.400748 -0.347794     NaN
722  20230208   080000    115959  1675828799  ...    722  0.398882 -0.337792     NaN
723  20230208   120000    155959  1675843199  ...    723  0.382526 -0.392084     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-18398.62985947704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23227.90438714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


