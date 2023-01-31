# 20230131 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [31/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18746
self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22953.0, self.close=22931.0, self.high=22955.0, self.low=22921.9, self.vol=1471.497, self.amt=33754367.6286 
2023-01-31 16:10:01,744:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230131   154500    154959  ...         0.0        0.0       0
5950  20230131   155000    155459  ...         0.0        0.0       0
5951  20230131   155500    155959  ...         0.0        0.0       0
5952  20230131   160000    160459  ...         0.0        0.0       0
5953  20230131   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 16:10:01,745:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22953.0, self.close=22931.0, self.high=22955.0, self.low=22921.9, self.vol=1471.497, self.amt=33754367.6286, ukdf['pct'].iloc[-1]=-0.000954 , ukdf['amount'].iloc[-1]=33754367.6286, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-385222.6816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22930.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18747
self.closeSec=1675152899, self.tradeDate='20230131', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22930.9, self.close=22921.0, self.high=22936.1, self.low=22917.2, self.vol=1202.013, self.amt=27557998.5897 
127.0.0.1 - - [31/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-31 16:15:00,974:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230131   155000    155459  ...         0.0        0.0       0
5951  20230131   155500    155959  ...         0.0        0.0       0
5952  20230131   160000    160459  ...         0.0        0.0       0
5953  20230131   160500    160959  ...         0.0        0.0       0
5954  20230131   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 16:15:00,975:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675152899, self.tradeDate='20230131', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22930.9, self.close=22921.0, self.high=22936.1, self.low=22917.2, self.vol=1202.013, self.amt=27557998.5897, ukdf['pct'].iloc[-1]=-0.000436 , ukdf['amount'].iloc[-1]=27557998.5897, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-384658.30854140848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22921.52129323', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22953.0, self.close=22931.0, self.high=22955.0, self.low=22921.9 
2023-01-31 16:10:01,664:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22953.0, self.close=22931.0, self.high=22955.0, self.low=22921.9   
127.0.0.1 - - [31/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 16:10:01,705:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230131   154500    154959  1675151399  ...  22900.3  0.002795   1629    3
1630  20230131   155000    155459  1675151699  ...  22951.1  0.000039   1630    4
1631  20230131   155500    155959  1675151999  ...  22937.2  0.000070   1631    5
1632  20230131   160000    160459  1675152299  ...  22950.6 -0.000644   1632    0
1633  20230131   160500    160959  1675152599  ...  22921.9 -0.000954   1633    1

[5 rows x 11 columns]
2023-01-31 16:10:01,705:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6647644693599797, self.count=19313 

self.closeSec=1675152899, self.tradeDate='20230131', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22930.9, self.close=22921.0, self.high=22936.1, self.low=22917.2 
2023-01-31 16:15:00,877:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675152899, self.tradeDate='20230131', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22930.9, self.close=22921.0, self.high=22936.1, self.low=22917.2   
127.0.0.1 - - [31/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-31 16:15:00,947:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230131   155000    155459  1675151699  ...  22951.1  0.000039   1630    4
1631  20230131   155500    155959  1675151999  ...  22937.2  0.000070   1631    5
1632  20230131   160000    160459  1675152299  ...  22950.6 -0.000644   1632    0
1633  20230131   160500    160959  1675152599  ...  22921.9 -0.000954   1633    1
1634  20230131   161000    161459  1675152899  ...  22917.2 -0.000436   1634    2

[5 rows x 11 columns]
2023-01-31 16:15:00,947:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-31 16:00:33,462:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230131    132959  22856.9  ...  51.666667  0.435703  0.721408
5787  20230131    135959  22849.7  ...  51.666667  0.417519  0.718536
5788  20230131    142959  22748.2  ...  52.083333  0.425150  0.713279
5789  20230131    145959  22779.8  ...  52.083333  0.431242  0.706026
5790  20230131    152959  22805.9  ...  52.500000  0.443398  0.695043

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-01-31 16:00:33,624:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.513446  0.486554       0  ...  0.977915  -1.0    0.0  1.080536
538     1  0.487773  0.512227       1  ...  0.976552  -1.0    0.0  1.082042
539     0  0.514636  0.485364       1  ...  0.975463  -1.0    0.0  1.083249
540     0  0.516382  0.483618       1  ...  0.973269  -1.0    0.0  1.085685
541     0  0.523798  0.476202       1  ...  0.968534  -1.0    0.0  1.090967

[5 rows x 10 columns]
2023-01-31 16:00:33,657:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513885  0.486115       0  ...  0.977915  -1.0    0.0  1.080034
46     1  0.488667  0.511333       1  ...  0.976552  -1.0    0.0  1.081698
47     0  0.515031  0.484969       1  ...  0.975463  -1.0    0.0  1.082441
48     0  0.515849  0.484151       1  ...  0.973269  -1.0    0.0  1.083216
49     0  0.523798  0.476202       1  ...  0.968534  -1.0    0.0  1.090967

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.741', 'enterprice': '23173.4', 'countrevence': '0', 'unrealprofit': '6082.57464686376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22975.53478264', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230131   154000    154959  1675151399  22896.5  22965.2  0.003000
2023-01-31 15:50:00,574:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Jan/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9655 

self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22970', self.close='22967.7'
2023-01-31 16:00:02,747:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22970', self.close='22967.7'
2023-01-31 16:00:02,770:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230131   151000    151959  1675149599  22859.4    22844 -0.000674
524  20230131   152000    152959  1675150199  22844.1  22856.5  0.000547
525  20230131   153000    153959  1675150799  22856.6  22896.5  0.001750
526  20230131   154000    154959  1675151399  22896.5  22965.2  0.003000
527  20230131   155000    155959  1675151999    22970  22967.7  0.000109
2023-01-31 16:00:02,776:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9656 

self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22967.7', self.close='22931'
2023-01-31 16:10:01,773:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22967.7', self.close='22931'
127.0.0.1 - - [31/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 16:10:01,799:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230131   152000    152959  1675150199  22844.1  22856.5  0.000547
525  20230131   153000    153959  1675150799  22856.6  22896.5  0.001750
526  20230131   154000    154959  1675151399  22896.5  22965.2  0.003000
527  20230131   155000    155959  1675151999    22970  22967.7  0.000109
528  20230131   160000    160959  1675152599  22967.7    22931 -0.001598
2023-01-31 16:10:01,799:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230131   154000    154959  1675151399  22896.5  22965.2
2023-01-31 15:50:00,589:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Jan/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9656 

self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22970', self.close='22967.7'
2023-01-31 16:00:02,749:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22970', self.close='22967.7'
2023-01-31 16:00:02,775:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230131   151000    151959  1675149599  22859.4    22844
17516  20230131   152000    152959  1675150199  22844.1  22856.5
17517  20230131   153000    153959  1675150799  22856.6  22896.5
17518  20230131   154000    154959  1675151399  22896.5  22965.2
17519  20230131   155000    155959  1675151999    22970  22967.7
2023-01-31 16:00:02,775:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9657 

self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22967.7', self.close='22931'
2023-01-31 16:10:01,787:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22967.7', self.close='22931'
2023-01-31 16:10:01,814:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230131   152000    152959  1675150199  22844.1  22856.5
17517  20230131   153000    153959  1675150799  22856.6  22896.5
17518  20230131   154000    154959  1675151399  22896.5  22965.2
17519  20230131   155000    155959  1675151999    22970  22967.7
17520  20230131   160000    160959  1675152599  22967.7    22931
2023-01-31 16:10:01,817:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230131   154000    154959  1675151399  22896.5  22965.2
2023-01-31 15:50:00,597:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [31/Jan/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9656 

self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='22970', self.close='22967.7'
2023-01-31 16:00:02,789:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='22970', self.close='22967.7'
2023-01-31 16:00:02,826:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230131   151000    151959  1675149599  22859.4    22844
12188  20230131   152000    152959  1675150199  22844.1  22856.5
12189  20230131   153000    153959  1675150799  22856.6  22896.5
12190  20230131   154000    154959  1675151399  22896.5  22965.2
12191  20230131   155000    155959  1675151999    22970  22967.7
2023-01-31 16:00:02,826:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9657 

self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22967.7', self.close='22931'
2023-01-31 16:10:01,795:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22967.7', self.close='22931'
127.0.0.1 - - [31/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 16:10:01,822:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230131   152000    152959  1675150199  22844.1  22856.5
12189  20230131   153000    153959  1675150799  22856.6  22896.5
12190  20230131   154000    154959  1675151399  22896.5  22965.2
12191  20230131   155000    155959  1675151999    22970  22967.7
12192  20230131   160000    160959  1675152599  22967.7    22931
2023-01-31 16:10:01,823:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14744
self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=22953.0, self.close=22931.0, self.high=22955.0, self.low=22921.9, self.vol=1471.497, self.amt=33754367.6286 
127.0.0.1 - - [31/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-31 16:10:01,750:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230131   154500    154959  ...         0.0        0.0       0
5950  20230131   155000    155459  ...         0.0        0.0       0
5951  20230131   155500    155959  ...         0.0        0.0       0
5952  20230131   160000    160459  ...         0.0        0.0       0
5953  20230131   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 16:10:01,751:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675152599, self.tradeDate='20230131', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=22953.0, self.close=22931.0, self.high=22955.0, self.low=22921.9, self.vol=1471.497, self.amt=33754367.6286, ukdf['pct'].iloc[-1]=-0.000954 , ukdf['amount'].iloc[-1]=33754367.6286, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [31/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14745
self.closeSec=1675152899, self.tradeDate='20230131', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=22930.9, self.close=22921.0, self.high=22936.1, self.low=22917.2, self.vol=1202.013, self.amt=27557998.5897 
2023-01-31 16:15:00,952:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230131   155000    155459  ...         0.0        0.0       0
5951  20230131   155500    155959  ...         0.0        0.0       0
5952  20230131   160000    160459  ...         0.0        0.0       0
5953  20230131   160500    160959  ...         0.0        0.0       0
5954  20230131   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-31 16:15:00,952:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675152899, self.tradeDate='20230131', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=22930.9, self.close=22921.0, self.high=22936.1, self.low=22917.2, self.vol=1202.013, self.amt=27557998.5897, ukdf['pct'].iloc[-1]=-0.000436 , ukdf['amount'].iloc[-1]=27557998.5897, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230131   040000    075959  1675123199  ...    721  0.537706  0.174729     NaN
722  20230131   080000    115959  1675137599  ...    722  0.569731  0.278332     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-33928.34977135464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22829.33853374', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=402
self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=22826.6, self.close=22967.7, self.high=22980.0, self.low=22735.5, self.vol=43431.989, self.amt=992384857.9143 
2023-01-31 16:00:02,373:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675151999, self.tradeDate='20230131', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=22826.6, self.close=22967.7, self.high=22980.0, self.low=22735.5, self.vol=43431.989, self.amt=992384857.9143 
127.0.0.1 - - [31/Jan/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-01-31 16:00:02,410:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230130   200000    235959  ...  114367.727  2.644439e+09  0.004481
720  20230131   000000    035959  ...  110669.265  2.538005e+09 -0.017037
721  20230131   040000    075959  ...   82595.410  1.875681e+09  0.001589
722  20230131   080000    115959  ...   45917.886  1.048036e+09  0.000298
723  20230131   120000    155959  ...   43431.989  9.923849e+08  0.006177

[5 rows x 11 columns]
2023-01-31 16:00:04,184:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230130   200000    235959  1675094399  ...    719  0.618886  0.372043     NaN
720  20230131   000000    035959  1675108799  ...    720  0.513624  0.094729     NaN
721  20230131   040000    075959  1675123199  ...    721  0.537706  0.174729     NaN
722  20230131   080000    115959  1675137599  ...    722  0.569731  0.278332     NaN
723  20230131   120000    155959  1675151999  ...    723  0.655813  0.534550     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-28472.58746869596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22969.35912461', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


