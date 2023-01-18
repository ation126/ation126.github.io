# 20230118 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15002
self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21301.6, self.close=21290.8, self.high=21302.2, self.low=21278.4, self.vol=857.109, self.amt=18246679.6643 
127.0.0.1 - - [18/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 16:10:01,546:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230118   154500    154959  ...         0.0        0.0       0
5950  20230118   155000    155459  ...         0.0        0.0       0
5951  20230118   155500    155959  ...         0.0        0.0       0
5952  20230118   160000    160459  ...         0.0        0.0       0
5953  20230118   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 16:10:01,546:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21301.6, self.close=21290.8, self.high=21302.2, self.low=21278.4, self.vol=857.109, self.amt=18246679.6643, ukdf['pct'].iloc[-1]=-0.000502 , ukdf['amount'].iloc[-1]=18246679.6643, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-286538.88631499984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21290.98050909', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=15003
self.closeSec=1674029699, self.tradeDate='20230118', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=21290.8, self.close=21290.6, self.high=21293.4, self.low=21271.6, self.vol=510.725, self.amt=10869597.707 
127.0.0.1 - - [18/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 16:15:00,776:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230118   155000    155459  ...         0.0        0.0       0
5951  20230118   155500    155959  ...         0.0        0.0       0
5952  20230118   160000    160459  ...         0.0        0.0       0
5953  20230118   160500    160959  ...         0.0        0.0       0
5954  20230118   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 16:15:00,777:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674029699, self.tradeDate='20230118', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=21290.8, self.close=21290.6, self.high=21293.4, self.low=21271.6, self.vol=510.725, self.amt=10869597.707, ukdf['pct'].iloc[-1]=-9e-06 , ukdf['amount'].iloc[-1]=10869597.707, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-286515.9888', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21290.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21301.6, self.close=21290.8, self.high=21302.2, self.low=21278.4 
127.0.0.1 - - [18/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 16:10:01,430:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21301.6, self.close=21290.8, self.high=21302.2, self.low=21278.4   
2023-01-18 16:10:01,450:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230118   154500    154959  1674028199  ...  21267.1  0.000719   1629    3
1630  20230118   155000    155459  1674028499  ...  21285.0  0.000864   1630    4
1631  20230118   155500    155959  1674028799  ...  21286.9  0.000197   1631    5
1632  20230118   160000    160459  1674029099  ...  21297.4 -0.000291   1632    0
1633  20230118   160500    160959  1674029399  ...  21278.4 -0.000502   1633    1

[5 rows x 11 columns]
2023-01-18 16:10:01,450:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=511, self.factor=0.5149812740216821, self.count=15569 

self.closeSec=1674029699, self.tradeDate='20230118', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=21290.8, self.close=21290.6, self.high=21293.4, self.low=21271.6 
2023-01-18 16:15:00,643:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674029699, self.tradeDate='20230118', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=21290.8, self.close=21290.6, self.high=21293.4, self.low=21271.6   
2023-01-18 16:15:00,714:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230118   155000    155459  1674028499  ...  21285.0  0.000864   1630    4
1631  20230118   155500    155959  1674028799  ...  21286.9  0.000197   1631    5
1632  20230118   160000    160459  1674029099  ...  21297.4 -0.000291   1632    0
1633  20230118   160500    160959  1674029399  ...  21278.4 -0.000502   1633    1
1634  20230118   161000    161459  1674029699  ...  21271.6 -0.000009   1634    2

[5 rows x 11 columns]
2023-01-18 16:15:00,716:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

16       alpha47  0.000184
2023-01-18 16:00:33,195:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230118    132959  21279.7  ...  51.666667  0.540825  0.563238
5787  20230118    135959  21290.3  ...  52.083333  0.544449  0.561691
5788  20230118    142959  21307.5  ...  51.666667  0.537478  0.563247
5789  20230118    145959  21279.8  ...  51.250000  0.531809  0.567146
5790  20230118    152959  21257.1  ...  51.666667  0.533453  0.569984

[5 rows x 33 columns]
0.533210332103321
acc is : 0.533210332103321
2023-01-18 16:00:33,354:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.506870  0.493130       1  ...  1.056950   1.0    0.0  1.255598
538     0  0.506854  0.493146       0  ...  1.055576   1.0    0.0  1.253966
539     0  0.501749  0.498251       0  ...  1.054455   1.0    0.0  1.252634
540     1  0.496903  0.503097       1  ...  1.054822   1.0    0.0  1.253070
541     0  0.504241  0.495759       1  ...  1.056960   1.0    0.0  1.255610

[5 rows x 10 columns]
2023-01-18 16:00:33,380:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
   pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
0     0  0.506828  0.493172       0  ...  1.055576   1.0    0.0  1.254757
1     0  0.501825  0.498175       0  ...  1.054455   1.0    0.0  1.254571
2     1  0.496816  0.503184       1  ...  1.054822   1.0    0.0  1.255341
3     0  0.504241  0.495759       1  ...  1.056960   1.0    0.0  1.255610

[4 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.369', 'enterprice': '21276.8', 'countrevence': '0', 'unrealprofit': '1148.65757700861', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21310.22132669', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230118   154000    154959  1674028199  21275.6  21285.1  0.000451
2023-01-18 15:50:00,593:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [18/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7783 

self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21285', self.close='21307.7'
2023-01-18 16:00:01,469:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21285', self.close='21307.7'
2023-01-18 16:00:01,533:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230118   151000    151959  1674026399  21256.7  21281.4  0.001157
524  20230118   152000    152959  1674026999  21281.2  21264.6 -0.000789
525  20230118   153000    153959  1674027599  21264.5  21275.5  0.000513
526  20230118   154000    154959  1674028199  21275.6  21285.1  0.000451
527  20230118   155000    155959  1674028799    21285  21307.7  0.001062
2023-01-18 16:00:01,533:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7784 

self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21307.8', self.close='21290.8'
2023-01-18 16:10:01,537:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21307.8', self.close='21290.8'
127.0.0.1 - - [18/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 16:10:01,567:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230118   152000    152959  1674026999  21281.2  21264.6 -0.000789
525  20230118   153000    153959  1674027599  21264.5  21275.5  0.000513
526  20230118   154000    154959  1674028199  21275.6  21285.1  0.000451
527  20230118   155000    155959  1674028799    21285  21307.7  0.001062
528  20230118   160000    160959  1674029399  21307.8  21290.8 -0.000793
2023-01-18 16:10:01,578:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230118   154000    154959  1674028199  21275.6  21285.1
2023-01-18 15:50:00,581:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7784 

self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21285', self.close='21307.7'
2023-01-18 16:00:01,489:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21285', self.close='21307.7'
2023-01-18 16:00:01,539:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230118   151000    151959  1674026399  21256.7  21281.4
17516  20230118   152000    152959  1674026999  21281.2  21264.6
17517  20230118   153000    153959  1674027599  21264.5  21275.5
17518  20230118   154000    154959  1674028199  21275.6  21285.1
17519  20230118   155000    155959  1674028799    21285  21307.7
2023-01-18 16:00:01,539:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7785 

self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21307.8', self.close='21290.8'
2023-01-18 16:10:01,556:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21307.8', self.close='21290.8'
2023-01-18 16:10:01,577:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230118   152000    152959  1674026999  21281.2  21264.6
17517  20230118   153000    153959  1674027599  21264.5  21275.5
17518  20230118   154000    154959  1674028199  21275.6  21285.1
17519  20230118   155000    155959  1674028799    21285  21307.7
17520  20230118   160000    160959  1674029399  21307.8  21290.8
2023-01-18 16:10:01,577:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230118   154000    154959  1674028199  21275.6  21285.1
2023-01-18 15:50:00,609:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7784 

self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21285', self.close='21307.7'
127.0.0.1 - - [18/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-18 16:00:01,471:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21285', self.close='21307.7'
2023-01-18 16:00:01,483:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230118   151000    151959  1674026399  21256.7  21281.4
12188  20230118   152000    152959  1674026999  21281.2  21264.6
12189  20230118   153000    153959  1674027599  21264.5  21275.5
12190  20230118   154000    154959  1674028199  21275.6  21285.1
12191  20230118   155000    155959  1674028799    21285  21307.7
2023-01-18 16:00:01,483:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7785 

self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21307.8', self.close='21290.8'
2023-01-18 16:10:01,559:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21307.8', self.close='21290.8'
2023-01-18 16:10:01,570:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230118   152000    152959  1674026999  21281.2  21264.6
12189  20230118   153000    153959  1674027599  21264.5  21275.5
12190  20230118   154000    154959  1674028199  21275.6  21285.1
12191  20230118   155000    155959  1674028799    21285  21307.7
12192  20230118   160000    160959  1674029399  21307.8  21290.8
2023-01-18 16:10:01,579:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [18/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11000
self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21301.6, self.close=21290.8, self.high=21302.2, self.low=21278.4, self.vol=857.109, self.amt=18246679.6643 
2023-01-18 16:10:01,547:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230118   154500    154959  ...         0.0        0.0       0
5950  20230118   155000    155459  ...         0.0        0.0       0
5951  20230118   155500    155959  ...         0.0        0.0       0
5952  20230118   160000    160459  ...         0.0        0.0       0
5953  20230118   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 16:10:01,548:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674029399, self.tradeDate='20230118', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21301.6, self.close=21290.8, self.high=21302.2, self.low=21278.4, self.vol=857.109, self.amt=18246679.6643, ukdf['pct'].iloc[-1]=-0.000502 , ukdf['amount'].iloc[-1]=18246679.6643, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=11001
self.closeSec=1674029699, self.tradeDate='20230118', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=21290.8, self.close=21290.6, self.high=21293.4, self.low=21271.6, self.vol=510.725, self.amt=10869597.707 
127.0.0.1 - - [18/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 16:15:00,756:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230118   155000    155459  ...         0.0        0.0       0
5951  20230118   155500    155959  ...         0.0        0.0       0
5952  20230118   160000    160459  ...         0.0        0.0       0
5953  20230118   160500    160959  ...         0.0        0.0       0
5954  20230118   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 16:15:00,756:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674029699, self.tradeDate='20230118', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=21290.8, self.close=21290.6, self.high=21293.4, self.low=21271.6, self.vol=510.725, self.amt=10869597.707, ukdf['pct'].iloc[-1]=-9e-06 , ukdf['amount'].iloc[-1]=10869597.707, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230118   040000    075959  1673999999  ...    721  0.123877 -1.893662    -1.0
722  20230118   080000    115959  1674014399  ...    722  0.005990 -2.167398    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-4580.1517698768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21256.6136656', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=324
self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21254.1, self.close=21307.7, self.high=21317.9, self.low=21226.6, self.vol=26297.724, self.amt=559517551.2374 
127.0.0.1 - - [18/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-18 16:00:01,316:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674028799, self.tradeDate='20230118', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21254.1, self.close=21307.7, self.high=21317.9, self.low=21226.6, self.vol=26297.724, self.amt=559517551.2374 
2023-01-18 16:00:01,379:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230117   200000    235959  ...  233118.482  4.958880e+09 -0.002022
720  20230118   000000    035959  ...   86362.443  1.834486e+09  0.007627
721  20230118   040000    075959  ...   56117.691  1.193678e+09 -0.009795
722  20230118   080000    115959  ...   58477.632  1.242592e+09  0.005959
723  20230118   120000    155959  ...   26297.724  5.595176e+08  0.002522

[5 rows x 11 columns]
2023-01-18 16:00:03,517:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230117   200000    235959  1673971199  ...    719  0.515810 -0.841899    -1.0
720  20230118   000000    035959  1673985599  ...    720  0.363703 -1.263897    -1.0
721  20230118   040000    075959  1673999999  ...    721  0.123877 -1.893662    -1.0
722  20230118   080000    115959  1674014399  ...    722  0.005990 -2.167398    -1.0
723  20230118   120000    155959  1674028799  ...    723  0.179287 -1.690226    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-7193.3677', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21307.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


