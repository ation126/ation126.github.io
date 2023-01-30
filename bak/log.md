# 20230130 16:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18458
self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23655.5, self.close=23667.7, self.high=23667.7, self.low=23646.6, self.vol=813.628, self.amt=19248786.2238 
127.0.0.1 - - [30/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 16:10:01,516:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230130   154500    154959  ...         0.0        0.0       0
5950  20230130   155000    155459  ...         0.0        0.0       0
5951  20230130   155500    155959  ...         0.0        0.0       0
5952  20230130   160000    160459  ...         0.0        0.0       0
5953  20230130   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 16:10:01,517:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23655.5, self.close=23667.7, self.high=23667.7, self.low=23646.6, self.vol=813.628, self.amt=19248786.2238, ukdf['pct'].iloc[-1]=0.00052 , ukdf['amount'].iloc[-1]=19248786.2238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-429517.51357301856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23666.98800806', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18459
self.closeSec=1675066499, self.tradeDate='20230130', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23667.7, self.close=23670.1, self.high=23678.6, self.low=23660.6, self.vol=1101.119, self.amt=26062855.8427 
2023-01-30 16:15:00,982:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230130   155000    155459  ...         0.0        0.0       0
5951  20230130   155500    155959  ...         0.0        0.0       0
5952  20230130   160000    160459  ...         0.0        0.0       0
5953  20230130   160500    160959  ...         0.0        0.0       0
5954  20230130   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 16:15:00,982:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675066499, self.tradeDate='20230130', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23667.7, self.close=23670.1, self.high=23678.6, self.low=23660.6, self.vol=1101.119, self.amt=26062855.8427, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=26062855.8427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-429704.7808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23670.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23655.5, self.close=23667.7, self.high=23667.7, self.low=23646.6 
2023-01-30 16:10:01,466:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23655.5, self.close=23667.7, self.high=23667.7, self.low=23646.6   
127.0.0.1 - - [30/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 16:10:01,498:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230130   154500    154959  1675064999  ...  23623.8 -0.000702   1629    3
1630  20230130   155000    155459  1675065299  ...  23620.8  0.000791   1630    4
1631  20230130   155500    155959  1675065599  ...  23634.0  0.000178   1631    5
1632  20230130   160000    160459  1675065899  ...  23634.8  0.000241   1632    0
1633  20230130   160500    160959  1675066199  ...  23646.6  0.000520   1633    1

[5 rows x 11 columns]
2023-01-30 16:10:01,498:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=461, self.factor=0.31695188025770143, self.count=19025 

self.closeSec=1675066499, self.tradeDate='20230130', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23667.7, self.close=23670.1, self.high=23678.6, self.low=23660.6 
2023-01-30 16:15:00,916:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675066499, self.tradeDate='20230130', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23667.7, self.close=23670.1, self.high=23678.6, self.low=23660.6   
2023-01-30 16:15:00,947:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230130   155000    155459  1675065299  ...  23620.8  0.000791   1630    4
1631  20230130   155500    155959  1675065599  ...  23634.0  0.000178   1631    5
1632  20230130   160000    160459  1675065899  ...  23634.8  0.000241   1632    0
1633  20230130   160500    160959  1675066199  ...  23646.6  0.000520   1633    1
1634  20230130   161000    161459  1675066499  ...  23660.6  0.000101   1634    2

[5 rows x 11 columns]
2023-01-30 16:15:00,948:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-30 16:00:24,363:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230130    132959  23716.3  ...  52.083333  0.572914  0.292232
5787  20230130    135959  23690.6  ...  52.500000  0.581562  0.294688
5788  20230130    142959  23733.7  ...  52.083333  0.580310  0.297411
5789  20230130    145959  23729.2  ...  51.666667  0.571440  0.302999
5790  20230130    152959  23697.4  ...  51.250000  0.553390  0.318996

[5 rows x 33 columns]
0.5369003690036901
acc is : 0.5369003690036901
2023-01-30 16:00:24,524:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509899  0.490101       1  ...  1.034984   1.0    0.0  1.146611
538     0  0.524967  0.475033       0  ...  1.034788   1.0    0.0  1.146394
539     0  0.512792  0.487208       0  ...  1.033401   1.0    0.0  1.144857
540     0  0.502323  0.497677       0  ...  1.030501   1.0    0.0  1.141645
541     1  0.494989  0.505011       1  ...  1.031321   1.0    0.0  1.142553

[5 rows x 10 columns]
2023-01-30 16:00:24,542:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508387  0.491613       1  ...  1.034984   1.0    0.0  1.140396
46     0  0.523870  0.476130       0  ...  1.034788   1.0    0.0  1.143791
47     0  0.512735  0.487265       0  ...  1.033401   1.0    0.0  1.145909
48     0  0.501603  0.498397       0  ...  1.030501   1.0    0.0  1.140752
49     1  0.494989  0.505011       1  ...  1.031321   1.0    0.0  1.142553

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.8', 'enterprice': '23035.8', 'countrevence': '0', 'unrealprofit': '18618.6', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23640.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230130   154000    154959  1675064999  23654.6  23626.8 -0.001179
2023-01-30 15:50:00,790:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9511 

self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23626.8', self.close='23648.1'
2023-01-30 16:00:01,917:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23626.8', self.close='23648.1'
2023-01-30 16:00:01,935:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230130   151000    151959  1675063199    23700  23654.1 -0.001916
524  20230130   152000    152959  1675063799  23654.1  23630.9 -0.000981
525  20230130   153000    153959  1675064399  23630.9  23654.7  0.001007
526  20230130   154000    154959  1675064999  23654.6  23626.8 -0.001179
527  20230130   155000    155959  1675065599  23626.8  23648.1  0.000902
2023-01-30 16:00:01,936:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9512 

self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23648', self.close='23667.7'
2023-01-30 16:10:01,554:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23648', self.close='23667.7'
2023-01-30 16:10:01,574:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230130   152000    152959  1675063799  23654.1  23630.9 -0.000981
525  20230130   153000    153959  1675064399  23630.9  23654.7  0.001007
526  20230130   154000    154959  1675064999  23654.6  23626.8 -0.001179
527  20230130   155000    155959  1675065599  23626.8  23648.1  0.000902
528  20230130   160000    160959  1675066199    23648  23667.7  0.000829
2023-01-30 16:10:01,574:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230130   154000    154959  1675064999  23654.6  23626.8
2023-01-30 15:50:00,796:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9512 

self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23626.8', self.close='23648.1'
2023-01-30 16:00:01,962:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23626.8', self.close='23648.1'
2023-01-30 16:00:02,013:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230130   151000    151959  1675063199    23700  23654.1
17516  20230130   152000    152959  1675063799  23654.1  23630.9
17517  20230130   153000    153959  1675064399  23630.9  23654.7
17518  20230130   154000    154959  1675064999  23654.6  23626.8
17519  20230130   155000    155959  1675065599  23626.8  23648.1
2023-01-30 16:00:02,015:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9513 

self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23648', self.close='23667.7'
2023-01-30 16:10:01,545:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23648', self.close='23667.7'
127.0.0.1 - - [30/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-30 16:10:01,578:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230130   152000    152959  1675063799  23654.1  23630.9
17517  20230130   153000    153959  1675064399  23630.9  23654.7
17518  20230130   154000    154959  1675064999  23654.6  23626.8
17519  20230130   155000    155959  1675065599  23626.8  23648.1
17520  20230130   160000    160959  1675066199    23648  23667.7
2023-01-30 16:10:01,579:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230130   154000    154959  1675064999  23654.6  23626.8
2023-01-30 15:50:00,798:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9512 

self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23626.8', self.close='23648.1'
2023-01-30 16:00:01,940:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23626.8', self.close='23648.1'
2023-01-30 16:00:01,978:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230130   151000    151959  1675063199    23700  23654.1
12188  20230130   152000    152959  1675063799  23654.1  23630.9
12189  20230130   153000    153959  1675064399  23630.9  23654.7
12190  20230130   154000    154959  1675064999  23654.6  23626.8
12191  20230130   155000    155959  1675065599  23626.8  23648.1
2023-01-30 16:00:01,978:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9513 

self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='23648', self.close='23667.7'
2023-01-30 16:10:01,563:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='23648', self.close='23667.7'
2023-01-30 16:10:01,580:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230130   152000    152959  1675063799  23654.1  23630.9
12189  20230130   153000    153959  1675064399  23630.9  23654.7
12190  20230130   154000    154959  1675064999  23654.6  23626.8
12191  20230130   155000    155959  1675065599  23626.8  23648.1
12192  20230130   160000    160959  1675066199    23648  23667.7
2023-01-30 16:10:01,580:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [30/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14456
self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23655.5, self.close=23667.7, self.high=23667.7, self.low=23646.6, self.vol=813.628, self.amt=19248786.2238 
2023-01-30 16:10:01,515:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230130   154500    154959  ...         0.0        0.0       0
5950  20230130   155000    155459  ...         0.0        0.0       0
5951  20230130   155500    155959  ...         0.0        0.0       0
5952  20230130   160000    160459  ...         0.0        0.0       0
5953  20230130   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 16:10:01,516:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675066199, self.tradeDate='20230130', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23655.5, self.close=23667.7, self.high=23667.7, self.low=23646.6, self.vol=813.628, self.amt=19248786.2238, ukdf['pct'].iloc[-1]=0.00052 , ukdf['amount'].iloc[-1]=19248786.2238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14457
self.closeSec=1675066499, self.tradeDate='20230130', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23667.7, self.close=23670.1, self.high=23678.6, self.low=23660.6, self.vol=1101.119, self.amt=26062855.8427 
127.0.0.1 - - [30/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-30 16:15:00,958:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230130   155000    155459  ...         0.0        0.0       0
5951  20230130   155500    155959  ...         0.0        0.0       0
5952  20230130   160000    160459  ...         0.0        0.0       0
5953  20230130   160500    160959  ...         0.0        0.0       0
5954  20230130   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-30 16:15:00,959:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675066499, self.tradeDate='20230130', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23667.7, self.close=23670.1, self.high=23678.6, self.low=23660.6, self.vol=1101.119, self.amt=26062855.8427, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=26062855.8427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-01-30 12:00:09,060:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41634F1675051203804I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675051203898990, 'quantity': '41.738', 'price': '23704.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675051203527, 'updatetime': 1675051203898, 'tradetype': 'usdt', 'selfid': 41634, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675051203898, 'clientorderid': '41634F1675051203804I0L65', 'price': '23704.8', 'quantity': '41.738', 'commission': '989.3909424', 'commissionasset': 'USDT', 'tradetime': 1675051203898, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675051203898}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-30 12:00:09,060:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41634F1675051203804I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675051203898990, 'quantity': '41.738', 'price': '23704.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675051203527, 'updatetime': 1675051203898, 'tradetype': 'usdt', 'selfid': 41634, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675051203898, 'clientorderid': '41634F1675051203804I0L65', 'price': '23704.8', 'quantity': '41.738', 'commission': '989.3909424', 'commissionasset': 'USDT', 'tradetime': 1675051203898, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675051203898}], 'gatetype': 'simulator', 'handletime': 0}
2023-01-30 12:00:09,372:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41635F1675051209040I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675051209333768, 'quantity': '38.964', 'price': '23700.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675051208887, 'updatetime': 1675051209333, 'tradetype': 'usdt', 'selfid': 41635, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675051209333, 'clientorderid': '41635F1675051209040I0L65', 'price': '23700.1', 'quantity': '38.964', 'commission': '923.4506964', 'commissionasset': 'USDT', 'tradetime': 1675051209333, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675051209333}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jan/2023 12:00:09] "POST / HTTP/1.1" 200 -
2023-01-30 12:00:09,500:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41635F1675051209040I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1675051209333768, 'quantity': '38.964', 'price': '23700.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1675051208887, 'updatetime': 1675051209333, 'tradetype': 'usdt', 'selfid': 41635, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1675051209333, 'clientorderid': '41635F1675051209040I0L65', 'price': '23700.1', 'quantity': '38.964', 'commission': '923.4506964', 'commissionasset': 'USDT', 'tradetime': 1675051209333, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1675051209333}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Jan/2023 12:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=396
self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23700.8, self.close=23648.1, self.high=23767.0, self.low=23600.0, self.vol=35817.696, self.amt=848605568.2551 
2023-01-30 16:00:01,580:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675065599, self.tradeDate='20230130', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23700.8, self.close=23648.1, self.high=23767.0, self.low=23600.0, self.vol=35817.696, self.amt=848605568.2551 
2023-01-30 16:00:01,612:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230129   200000    235959  ...   88615.332  2.084092e+09  0.003956
720  20230130   000000    035959  ...  134522.960  3.190306e+09  0.015895
721  20230130   040000    075959  ...   71846.477  1.708220e+09 -0.006541
722  20230130   080000    115959  ...   50623.845  1.198734e+09 -0.001664
723  20230130   120000    155959  ...   35817.696  8.486056e+08 -0.002224

[5 rows x 11 columns]
2023-01-30 16:00:02,994:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230129   200000    235959  1675007999  ...    719  0.200960 -0.816995    -1.0
720  20230130   000000    035959  1675022399  ...    720  0.333661 -0.460132     NaN
721  20230130   040000    075959  1675036799  ...    721  0.355328 -0.386449     NaN
722  20230130   080000    115959  1675051199  ...    722  0.734259  0.636107     1.0
723  20230130   120000    155959  1675065599  ...    723  0.699296  0.560167     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-2231.03216101332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23642.84119287', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


