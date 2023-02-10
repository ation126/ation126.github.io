# 20230210 16:35:51

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [10/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21630
self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21880.1, self.close=21875.2, self.high=21885.8, self.low=21872.5, self.vol=427.372, self.amt=9351283.8569 
2023-02-10 16:30:00,635:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230210   160500    160959  ...         0.0        0.0       0
5954  20230210   161000    161459  ...         0.0        0.0       0
5955  20230210   161500    161959  ...         0.0        0.0       0
5956  20230210   162000    162459  ...         0.0        0.0       0
5957  20230210   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 16:30:00,635:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21880.1, self.close=21875.2, self.high=21885.8, self.low=21872.5, self.vol=427.372, self.amt=9351283.8569, ukdf['pct'].iloc[-1]=-0.000224 , ukdf['amount'].iloc[-1]=9351283.8569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-321676.8256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21874.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=21631
self.closeSec=1676018099, self.tradeDate='20230210', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21874.9, self.close=21868.6, self.high=21891.0, self.low=21868.5, self.vol=932.435, self.amt=20399089.4606 
127.0.0.1 - - [10/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:35:00,496:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230210   161000    161459  ...         0.0        0.0       0
5955  20230210   161500    161959  ...         0.0        0.0       0
5956  20230210   162000    162459  ...         0.0        0.0       0
5957  20230210   162500    162959  ...         0.0        0.0       0
5958  20230210   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 16:35:00,496:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676018099, self.tradeDate='20230210', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21874.9, self.close=21868.6, self.high=21891.0, self.low=21868.5, self.vol=932.435, self.amt=20399089.4606, ukdf['pct'].iloc[-1]=-0.000302 , ukdf['amount'].iloc[-1]=20399089.4606, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-321360.98867226496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21869.65144696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

1637  20230210   162500    162959  1676017799  ...  21872.5 -0.000224   1637    5

[5 rows x 11 columns]
2023-02-10 16:30:00,576:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
2023-02-10 16:30:00,633:INFO:factorcheck2:main.py:145:handleKline:185239: df_panel.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...       pct  index  idx    factor
229  20230210   142500    142959  1676010599  ...  0.000041   1613    5  0.736205
230  20230210   145500    145959  1676012399  ...  0.000352   1619    5  0.738898
231  20230210   152500    152959  1676014199  ... -0.000334   1625    5  0.742488
232  20230210   155500    155959  1676015999  ...  0.000041   1631    5  0.744292
233  20230210   162500    162959  1676017799  ... -0.000224   1637    5  0.746682

[5 rows x 12 columns]
2023-02-10 16:30:00,679:INFO:factorcheck2:main.py:201:insertFactor:185239: curDateTime:2101630, name:factorcheck2, symbol:BTCUSDT, tradeDate:20230210, closeTime:162959, close:21875.2, total:909224.3076578999, factor:0.7466818972746954, factorCnt:0, side:buy 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7466818972746954, self.count=22197 

self.closeSec=1676018099, self.tradeDate='20230210', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21874.9, self.close=21868.6, self.high=21891.0, self.low=21868.5 
2023-02-10 16:35:00,431:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676018099, self.tradeDate='20230210', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21874.9, self.close=21868.6, self.high=21891.0, self.low=21868.5   
127.0.0.1 - - [10/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:35:00,477:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20230210   161000    161459  1676016899  ...  21875.9  0.000265   1634    2
1635  20230210   161500    161959  1676017199  ...  21873.0  0.000132   1635    3
1636  20230210   162000    162459  1676017499  ...  21879.2 -0.000484   1636    4
1637  20230210   162500    162959  1676017799  ...  21872.5 -0.000224   1637    5
1638  20230210   163000    163459  1676018099  ...  21868.5 -0.000302   1638    0

[5 rows x 11 columns]
2023-02-10 16:35:00,477:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-10 16:30:31,534:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20230210    135959  21754.7  ...  44.583333  0.354398  0.819347
5788  20230210    142959  21790.7  ...  45.000000  0.367898  0.818220
5789  20230210    145959  21841.7  ...  45.000000  0.375568  0.815598
5790  20230210    152959  21870.9  ...  45.000000  0.369172  0.815348
5791  20230210    155959  21829.8  ...  45.416667  0.387878  0.811251

[5 rows x 33 columns]
0.4797047970479705
acc is : 0.4797047970479705
2023-02-10 16:30:31,726:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.492543  0.507457       1  ...  1.033626  -1.0    0.0  0.922135
538     0  0.505173  0.494827       1  ...  1.032239  -1.0    0.0  0.923372
539     0  0.505044  0.494956       0  ...  1.034174  -1.0    0.0  0.921641
540     1  0.491370  0.508630       1  ...  1.030758  -1.0    0.0  0.924685
541     0  0.521886  0.478114       0  ...  1.032020  -1.0    0.0  0.923554

[5 rows x 10 columns]
2023-02-10 16:30:31,758:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491714  0.508286       1  ...  1.033626  -1.0    0.0  0.919418
46     0  0.504737  0.495263       1  ...  1.032239  -1.0    0.0  0.921256
47     0  0.505044  0.494956       0  ...  1.034174  -1.0    0.0  0.920786
48     1  0.491113  0.508887       1  ...  1.030758  -1.0    0.0  0.922085
49     0  0.521886  0.478114       0  ...  1.032020  -1.0    0.0  0.923554

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.252', 'enterprice': '22924.6', 'countrevence': '0', 'unrealprofit': '33819.4472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21876', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

528  20230210   160000    160959  1676016599    21902    21882 -0.000913
2023-02-10 16:10:01,859:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [10/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11097 

self.closeSec=1676017199, self.tradeDate='20230210', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21880.8', self.close='21890.7'
2023-02-10 16:20:00,854:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676017199, self.tradeDate='20230210', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21880.8', self.close='21890.7'
2023-02-10 16:20:00,913:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230210   153000    153959  1676014799  21829.8  21857.2  0.001251
526  20230210   154000    154959  1676015399  21857.2  21881.9  0.001130
527  20230210   155000    155959  1676015999    21882    21902  0.000919
528  20230210   160000    160959  1676016599    21902    21882 -0.000913
529  20230210   161000    161959  1676017199  21880.8  21890.7  0.000398
2023-02-10 16:20:00,913:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11098 

self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21894.4', self.close='21874.9'
2023-02-10 16:30:00,755:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21894.4', self.close='21874.9'
127.0.0.1 - - [10/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:30:00,775:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20230210   154000    154959  1676015399  21857.2  21881.9  0.001130
527  20230210   155000    155959  1676015999    21882    21902  0.000919
528  20230210   160000    160959  1676016599    21902    21882 -0.000913
529  20230210   161000    161959  1676017199  21880.8  21890.7  0.000398
530  20230210   162000    162959  1676017799  21894.4  21874.9 -0.000722
2023-02-10 16:30:00,775:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17520  20230210   160000    160959  1676016599    21902    21882
2023-02-10 16:10:01,867:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11098 

self.closeSec=1676017199, self.tradeDate='20230210', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21880.8', self.close='21890.7'
2023-02-10 16:20:00,867:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676017199, self.tradeDate='20230210', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21880.8', self.close='21890.7'
127.0.0.1 - - [10/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:20:00,906:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230210   153000    153959  1676014799  21829.8  21857.2
17518  20230210   154000    154959  1676015399  21857.2  21881.9
17519  20230210   155000    155959  1676015999    21882    21902
17520  20230210   160000    160959  1676016599    21902    21882
17521  20230210   161000    161959  1676017199  21880.8  21890.7
2023-02-10 16:20:00,907:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11099 

self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21894.4', self.close='21874.9'
2023-02-10 16:30:00,765:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21894.4', self.close='21874.9'
127.0.0.1 - - [10/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:30:00,785:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20230210   154000    154959  1676015399  21857.2  21881.9
17519  20230210   155000    155959  1676015999    21882    21902
17520  20230210   160000    160959  1676016599    21902    21882
17521  20230210   161000    161959  1676017199  21880.8  21890.7
17522  20230210   162000    162959  1676017799  21894.4  21874.9
2023-02-10 16:30:00,785:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12192  20230210   160000    160959  1676016599    21902    21882
2023-02-10 16:10:01,863:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11098 

self.closeSec=1676017199, self.tradeDate='20230210', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='21880.8', self.close='21890.7'
2023-02-10 16:20:00,854:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676017199, self.tradeDate='20230210', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='21880.8', self.close='21890.7'
127.0.0.1 - - [10/Feb/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:20:00,902:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230210   153000    153959  1676014799  21829.8  21857.2
12190  20230210   154000    154959  1676015399  21857.2  21881.9
12191  20230210   155000    155959  1676015999    21882    21902
12192  20230210   160000    160959  1676016599    21902    21882
12193  20230210   161000    161959  1676017199  21880.8  21890.7
2023-02-10 16:20:00,902:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11099 

self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='21894.4', self.close='21874.9'
2023-02-10 16:30:00,743:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='21894.4', self.close='21874.9'
2023-02-10 16:30:00,786:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20230210   154000    154959  1676015399  21857.2  21881.9
12191  20230210   155000    155959  1676015999    21882    21902
12192  20230210   160000    160959  1676016599    21902    21882
12193  20230210   161000    161959  1676017199  21880.8  21890.7
12194  20230210   162000    162959  1676017799  21894.4  21874.9
2023-02-10 16:30:00,786:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17628
self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162500', self.closeTime='162959', self.symbol='BTCUSDT', self.open=21880.1, self.close=21875.2, self.high=21885.8, self.low=21872.5, self.vol=427.372, self.amt=9351283.8569 
127.0.0.1 - - [10/Feb/2023 16:30:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:30:00,644:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5953  20230210   160500    160959  ...         0.0        0.0       0
5954  20230210   161000    161459  ...         0.0        0.0       0
5955  20230210   161500    161959  ...         0.0        0.0       0
5956  20230210   162000    162459  ...         0.0        0.0       0
5957  20230210   162500    162959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 16:30:00,646:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676017799, self.tradeDate='20230210', self.openTime='162500', self.closeTime='162959',self.symbol='BTCUSDT',self.open=21880.1, self.close=21875.2, self.high=21885.8, self.low=21872.5, self.vol=427.372, self.amt=9351283.8569, ukdf['pct'].iloc[-1]=-0.000224 , ukdf['amount'].iloc[-1]=9351283.8569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5957, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=17629
self.closeSec=1676018099, self.tradeDate='20230210', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=21874.9, self.close=21868.6, self.high=21891.0, self.low=21868.5, self.vol=932.435, self.amt=20399089.4606 
127.0.0.1 - - [10/Feb/2023 16:35:00] "POST / HTTP/1.1" 200 -
2023-02-10 16:35:00,498:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20230210   161000    161459  ...         0.0        0.0       0
5955  20230210   161500    161959  ...         0.0        0.0       0
5956  20230210   162000    162459  ...         0.0        0.0       0
5957  20230210   162500    162959  ...         0.0        0.0       0
5958  20230210   163000    163459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-10 16:35:00,500:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676018099, self.tradeDate='20230210', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=21874.9, self.close=21868.6, self.high=21891.0, self.low=21868.5, self.vol=932.435, self.amt=20399089.4606, ukdf['pct'].iloc[-1]=-0.000302 , ukdf['amount'].iloc[-1]=20399089.4606, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230210   040000    075959  1675987199  ...    721  0.389329 -0.397613     NaN
722  20230210   080000    115959  1676001599  ...    722  0.528172  0.231654     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '40408.0425', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21817.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=888768.4643774999, self.flagDict['side']='sell', self.tradeCount=17, self.count=462
self.closeSec=1676015999, self.tradeDate='20230210', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21817.5, self.close=21902.0, self.high=21914.0, self.low=21595.8, self.vol=68529.707, self.amt=1493235010.6546 
127.0.0.1 - - [10/Feb/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-02-10 16:00:01,169:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676015999, self.tradeDate='20230210', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21817.5, self.close=21902.0, self.high=21914.0, self.low=21595.8, self.vol=68529.707, self.amt=1493235010.6546 
2023-02-10 16:00:01,203:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230209   200000    235959  ...  112744.024  2.557579e+09 -0.003246
720  20230210   000000    035959  ...  212764.619  4.742705e+09 -0.025323
721  20230210   040000    075959  ...  165794.930  3.626204e+09 -0.010907
722  20230210   080000    115959  ...   45873.626  1.002400e+09  0.001212
723  20230210   120000    155959  ...   68529.707  1.493235e+09  0.003873

[5 rows x 11 columns]
2023-02-10 16:00:02,915:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230209   200000    235959  1675958399  ...    719  0.282399 -0.875070    -1.0
720  20230210   000000    035959  1675972799  ...    720  0.222654 -1.148003    -1.0
721  20230210   040000    075959  1675987199  ...    721  0.389329 -0.397613     NaN
722  20230210   080000    115959  1676001599  ...    722  0.528172  0.231654     NaN
723  20230210   120000    155959  1676015999  ...    723  0.608215  0.590645     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.925', 'enterprice': '22855.7', 'countrevence': '0', 'unrealprofit': '37122.7725', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


