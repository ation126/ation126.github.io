# 20230126 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17306
self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23012.4, self.close=23001.6, self.high=23014.3, self.low=22974.9, self.vol=921.287, self.amt=21187601.0677 
127.0.0.1 - - [26/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-26 16:10:01,532:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230126   154500    154959  ...         0.0        0.0       0
5950  20230126   155000    155459  ...         0.0        0.0       0
5951  20230126   155500    155959  ...         0.0        0.0       0
5952  20230126   160000    160459  ...         0.0        0.0       0
5953  20230126   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 16:10:01,532:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23012.4, self.close=23001.6, self.high=23014.3, self.low=22974.9, self.vol=921.287, self.amt=21187601.0677, ukdf['pct'].iloc[-1]=-0.000465 , ukdf['amount'].iloc[-1]=21187601.0677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-389541.79788847776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23002.67473226', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Jan/2023 16:15:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=17307
self.closeSec=1674720899, self.tradeDate='20230126', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23001.5, self.close=23011.8, self.high=23020.5, self.low=22997.5, self.vol=834.244, self.amt=19196267.5647 
2023-01-26 16:15:01,155:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230126   155000    155459  ...         0.0        0.0       0
5951  20230126   155500    155959  ...         0.0        0.0       0
5952  20230126   160000    160459  ...         0.0        0.0       0
5953  20230126   160500    160959  ...         0.0        0.0       0
5954  20230126   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 16:15:01,156:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674720899, self.tradeDate='20230126', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23001.5, self.close=23011.8, self.high=23020.5, self.low=22997.5, self.vol=834.244, self.amt=19196267.5647, ukdf['pct'].iloc[-1]=0.000443 , ukdf['amount'].iloc[-1]=19196267.5647, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-390183.93166143392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23013.34566042', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23012.4, self.close=23001.6, self.high=23014.3, self.low=22974.9 
2023-01-26 16:10:01,432:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23012.4, self.close=23001.6, self.high=23014.3, self.low=22974.9   
127.0.0.1 - - [26/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-26 16:10:01,507:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230126   154500    154959  1674719399  ...  22953.0  0.001040   1629    3
1630  20230126   155000    155459  1674719699  ...  22984.8 -0.000039   1630    4
1631  20230126   155500    155959  1674719999  ...  22952.8 -0.001648   1631    5
1632  20230126   160000    160459  1674720299  ...  22956.8  0.002221   1632    0
1633  20230126   160500    160959  1674720599  ...  22974.9 -0.000465   1633    1

[5 rows x 11 columns]
2023-01-26 16:10:01,507:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jan/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=269, self.factor=0.4570586072064399, self.count=17873 

self.closeSec=1674720899, self.tradeDate='20230126', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23001.5, self.close=23011.8, self.high=23020.5, self.low=22997.5 
2023-01-26 16:15:01,124:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674720899, self.tradeDate='20230126', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23001.5, self.close=23011.8, self.high=23020.5, self.low=22997.5   
2023-01-26 16:15:01,155:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230126   155000    155459  1674719699  ...  22984.8 -0.000039   1630    4
1631  20230126   155500    155959  1674719999  ...  22952.8 -0.001648   1631    5
1632  20230126   160000    160459  1674720299  ...  22956.8  0.002221   1632    0
1633  20230126   160500    160959  1674720599  ...  22974.9 -0.000465   1633    1
1634  20230126   161000    161459  1674720899  ...  22997.5  0.000443   1634    2

[5 rows x 11 columns]
2023-01-26 16:15:01,155:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-26 16:00:18,503:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230126    132959  23172.1  ...  52.916667  0.544851  0.433108
5787  20230126    135959  23163.9  ...  52.916667  0.541418  0.434906
5788  20230126    142959  23142.6  ...  52.500000  0.518627  0.443011
5789  20230126    145959  22996.5  ...  52.500000  0.530741  0.446713
5790  20230126    152959  23084.4  ...  52.083333  0.521362  0.452875

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-01-26 16:00:18,578:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.519385  0.480615       0  ...  1.003182   1.0    0.0  1.113980
538     0  0.515075  0.484925       0  ...  0.996871   1.0    0.0  1.106971
539     1  0.480476  0.519524       1  ...  1.000664   1.0    0.0  1.111183
540     0  0.528012  0.471988       0  ...  0.998007   1.0    0.0  1.108233
541     1  0.491338  0.508662       0  ...  0.995323   1.0    0.0  1.105253

[5 rows x 10 columns]
2023-01-26 16:00:18,590:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518177  0.481823       0  ...  0.990029   1.0    0.0  1.101798
46     0  0.513470  0.486530       0  ...  0.983800   1.0    0.0  1.091089
47     1  0.478705  0.521295       1  ...  0.987543   1.0    0.0  1.101213
48     0  0.526984  0.473016       0  ...  0.984921   1.0    0.0  1.100151
49     1  0.491338  0.508662       0  ...  0.995323   1.0    0.0  1.105253

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.682', 'enterprice': '23079.5', 'countrevence': '0', 'unrealprofit': '-3605.4116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '22965.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230126   154000    154959  1674719399  22977.8  23000.1  0.000992
2023-01-26 15:50:00,555:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8935 

self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23000', self.close='22961.3'
127.0.0.1 - - [26/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-26 16:00:01,597:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23000', self.close='22961.3'
2023-01-26 16:00:01,630:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230126   151000    151959  1674717599  23033.2  23023.8 -0.000391
524  20230126   152000    152959  1674718199  23023.9  23023.2 -0.000026
525  20230126   153000    153959  1674718799  23023.1  22977.3 -0.001994
526  20230126   154000    154959  1674719399  22977.8  23000.1  0.000992
527  20230126   155000    155959  1674719999    23000  22961.3 -0.001687
2023-01-26 16:00:01,630:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8936 

self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22961.3', self.close='23001.6'
2023-01-26 16:10:01,557:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22961.3', self.close='23001.6'
2023-01-26 16:10:01,589:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230126   152000    152959  1674718199  23023.9  23023.2 -0.000026
525  20230126   153000    153959  1674718799  23023.1  22977.3 -0.001994
526  20230126   154000    154959  1674719399  22977.8  23000.1  0.000992
527  20230126   155000    155959  1674719999    23000  22961.3 -0.001687
528  20230126   160000    160959  1674720599  22961.3  23001.6  0.001755
2023-01-26 16:10:01,589:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230126   154000    154959  1674719399  22977.8  23000.1
2023-01-26 15:50:00,559:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8936 

self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23000', self.close='22961.3'
127.0.0.1 - - [26/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-26 16:00:01,627:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23000', self.close='22961.3'
2023-01-26 16:00:01,658:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230126   151000    151959  1674717599  23033.2  23023.8
17516  20230126   152000    152959  1674718199  23023.9  23023.2
17517  20230126   153000    153959  1674718799  23023.1  22977.3
17518  20230126   154000    154959  1674719399  22977.8  23000.1
17519  20230126   155000    155959  1674719999    23000  22961.3
2023-01-26 16:00:01,658:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8937 

self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22961.3', self.close='23001.6'
2023-01-26 16:10:01,568:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22961.3', self.close='23001.6'
2023-01-26 16:10:01,592:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230126   152000    152959  1674718199  23023.9  23023.2
17517  20230126   153000    153959  1674718799  23023.1  22977.3
17518  20230126   154000    154959  1674719399  22977.8  23000.1
17519  20230126   155000    155959  1674719999    23000  22961.3
17520  20230126   160000    160959  1674720599  22961.3  23001.6
2023-01-26 16:10:01,592:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230126   154000    154959  1674719399  22977.8  23000.1
2023-01-26 15:50:00,533:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8936 

self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='23000', self.close='22961.3'
127.0.0.1 - - [26/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-26 16:00:01,608:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='23000', self.close='22961.3'
2023-01-26 16:00:01,642:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230126   151000    151959  1674717599  23033.2  23023.8
12188  20230126   152000    152959  1674718199  23023.9  23023.2
12189  20230126   153000    153959  1674718799  23023.1  22977.3
12190  20230126   154000    154959  1674719399  22977.8  23000.1
12191  20230126   155000    155959  1674719999    23000  22961.3
2023-01-26 16:00:01,642:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8937 

self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='22961.3', self.close='23001.6'
2023-01-26 16:10:01,563:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='22961.3', self.close='23001.6'
2023-01-26 16:10:01,590:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230126   152000    152959  1674718199  23023.9  23023.2
12189  20230126   153000    153959  1674718799  23023.1  22977.3
12190  20230126   154000    154959  1674719399  22977.8  23000.1
12191  20230126   155000    155959  1674719999    23000  22961.3
12192  20230126   160000    160959  1674720599  22961.3  23001.6
2023-01-26 16:10:01,590:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13304
self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=23012.4, self.close=23001.6, self.high=23014.3, self.low=22974.9, self.vol=921.287, self.amt=21187601.0677 
127.0.0.1 - - [26/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-26 16:10:01,531:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230126   154500    154959  ...         0.0        0.0       0
5950  20230126   155000    155459  ...         0.0        0.0       0
5951  20230126   155500    155959  ...         0.0        0.0       0
5952  20230126   160000    160459  ...         0.0        0.0       0
5953  20230126   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 16:10:01,531:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674720599, self.tradeDate='20230126', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=23012.4, self.close=23001.6, self.high=23014.3, self.low=22974.9, self.vol=921.287, self.amt=21187601.0677, ukdf['pct'].iloc[-1]=-0.000465 , ukdf['amount'].iloc[-1]=21187601.0677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [26/Jan/2023 16:15:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=13305
self.closeSec=1674720899, self.tradeDate='20230126', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=23001.5, self.close=23011.8, self.high=23020.5, self.low=22997.5, self.vol=834.244, self.amt=19196267.5647 
2023-01-26 16:15:01,115:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230126   155000    155459  ...         0.0        0.0       0
5951  20230126   155500    155959  ...         0.0        0.0       0
5952  20230126   160000    160459  ...         0.0        0.0       0
5953  20230126   160500    160959  ...         0.0        0.0       0
5954  20230126   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-26 16:15:01,115:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674720899, self.tradeDate='20230126', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=23001.5, self.close=23011.8, self.high=23020.5, self.low=22997.5, self.vol=834.244, self.amt=19196267.5647, ukdf['pct'].iloc[-1]=0.000443 , ukdf['amount'].iloc[-1]=19196267.5647, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230126   040000    075959  1674691199  ...    721  0.164732 -1.395258    -1.0
722  20230126   080000    115959  1674705599  ...    722  0.176898 -1.335582    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-8510.3782', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23131.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=955999.3862573999, self.flagDict['side']='sell', self.tradeCount=15, self.count=372
self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=23129.5, self.close=22961.3, self.high=23189.3, self.low=22885.7, self.vol=50565.793, self.amt=1165545135.3597 
127.0.0.1 - - [26/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-26 16:00:01,484:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1674719999, self.tradeDate='20230126', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=23129.5, self.close=22961.3, self.high=23189.3, self.low=22885.7, self.vol=50565.793, self.amt=1165545135.3597 
2023-01-26 16:00:01,497:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230125   200000    235959  ...  127913.984  2.885108e+09 -0.001000
720  20230126   000000    035959  ...   64912.437  1.469489e+09  0.007535
721  20230126   040000    075959  ...  309662.086  7.186402e+09  0.013903
722  20230126   080000    115959  ...   61160.892  1.416929e+09  0.003027
723  20230126   120000    155959  ...   50565.793  1.165545e+09 -0.007268

[5 rows x 11 columns]
2023-01-26 16:00:02,991:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230125   200000    235959  1674662399  ...    719  0.256658 -1.252734    -1.0
720  20230126   000000    035959  1674676799  ...    720  0.239021 -1.262655    -1.0
721  20230126   040000    075959  1674691199  ...    721  0.164732 -1.395258    -1.0
722  20230126   080000    115959  1674705599  ...    722  0.176898 -1.335582    -1.0
723  20230126   120000    155959  1674719999  ...    723  0.185886 -1.284585    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.738', 'enterprice': '22927.7', 'countrevence': '0', 'unrealprofit': '-1500.46289513654', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22963.64956383', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


