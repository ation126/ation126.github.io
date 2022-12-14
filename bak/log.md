# 20221214 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [14/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4922
self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17807.9, self.close=17799.0, self.high=17807.9, self.low=17796.3, self.vol=459.84, self.amt=8184934.6268 
2022-12-14 16:10:01,458:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221214   154500    154959  ...         0.0        0.0       0
5950  20221214   155000    155459  ...         0.0        0.0       0
5951  20221214   155500    155959  ...         0.0        0.0       0
5952  20221214   160000    160459  ...         0.0        0.0       0
5953  20221214   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-14 16:10:01,459:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17807.9, self.close=17799.0, self.high=17807.9, self.low=17796.3, self.vol=459.84, self.amt=8184934.6268, ukdf['pct'].iloc[-1]=-0.000494 , ukdf['amount'].iloc[-1]=8184934.6268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-76444.41323838368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17799.64720218', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [14/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4923
self.closeSec=1671005699, self.tradeDate='20221214', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17799.0, self.close=17802.3, self.high=17805.1, self.low=17799.0, self.vol=343.86, self.amt=6121515.8733 
2022-12-14 16:15:00,611:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221214   155000    155459  ...         0.0        0.0       0
5951  20221214   155500    155959  ...         0.0        0.0       0
5952  20221214   160000    160459  ...         0.0        0.0       0
5953  20221214   160500    160959  ...         0.0        0.0       0
5954  20221214   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-14 16:15:00,611:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671005699, self.tradeDate='20221214', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17799.0, self.close=17802.3, self.high=17805.1, self.low=17799.0, self.vol=343.86, self.amt=6121515.8733, ukdf['pct'].iloc[-1]=0.000185 , ukdf['amount'].iloc[-1]=6121515.8733, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-76660.4989491424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17803.2380974', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17807.9, self.close=17799.0, self.high=17807.9, self.low=17796.3 
2022-12-14 16:10:01,417:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17807.9, self.close=17799.0, self.high=17807.9, self.low=17796.3   
127.0.0.1 - - [14/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-14 16:10:01,445:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221214   154500    154959  1671004199  ...  17793.5  0.000287   1629    3
1630  20221214   155000    155459  1671004499  ...  17798.3  0.000230   1630    4
1631  20221214   155500    155959  1671004799  ...  17805.3  0.000095   1631    5
1632  20221214   160000    160459  1671005099  ...  17794.5  0.000039   1632    0
1633  20221214   160500    160959  1671005399  ...  17796.3 -0.000494   1633    1

[5 rows x 11 columns]
2022-12-14 16:10:01,445:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.25398406780470345, self.count=5489 

self.closeSec=1671005699, self.tradeDate='20221214', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17799.0, self.close=17802.3, self.high=17805.1, self.low=17799.0 
2022-12-14 16:15:00,554:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671005699, self.tradeDate='20221214', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17799.0, self.close=17802.3, self.high=17805.1, self.low=17799.0   
2022-12-14 16:15:00,583:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221214   155000    155459  1671004499  ...  17798.3  0.000230   1630    4
1631  20221214   155500    155959  1671004799  ...  17805.3  0.000095   1631    5
1632  20221214   160000    160459  1671005099  ...  17794.5  0.000039   1632    0
1633  20221214   160500    160959  1671005399  ...  17796.3 -0.000494   1633    1
1634  20221214   161000    161459  1671005699  ...  17799.0  0.000185   1634    2

[5 rows x 11 columns]
2022-12-14 16:15:00,583:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-14 16:00:19,997:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5786  20221214    132959  17772.1  ...     52.5  0.633819  0.316650
5787  20221214    135959  17782.7  ...     52.5  0.635703  0.323447
5788  20221214    142959  17789.4  ...     52.5  0.630736  0.331298
5789  20221214    145959  17779.4  ...     52.5  0.632982  0.338104
5790  20221214    152959  17787.2  ...     52.5  0.639403  0.342908

[5 rows x 33 columns]
0.5811808118081181
acc is : 0.5811808118081181
2022-12-14 16:00:20,152:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491056  0.508944       1  ...  1.016259   1.0    0.0  1.043801
538     1  0.490814  0.509186       0  ...  1.015694   1.0    0.0  1.043220
539     1  0.489311  0.510689       1  ...  1.016128   1.0    0.0  1.043666
540     1  0.494494  0.505506       1  ...  1.017373   1.0    0.0  1.044945
541     1  0.499131  0.500869       0  ...  1.017270   1.0    0.0  1.044840

[5 rows x 10 columns]
2022-12-14 16:00:20,178:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491050  0.508950       1  ...  1.016259   1.0    0.0  1.044267
46     1  0.490539  0.509461       0  ...  1.015694   1.0    0.0  1.042615
47     1  0.488752  0.511248       1  ...  1.016128   1.0    0.0  1.041216
48     1  0.493945  0.506055       1  ...  1.017373   1.0    0.0  1.044406
49     1  0.499131  0.500869       0  ...  1.017270   1.0    0.0  1.044840

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '22512.65240773459', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17808.54618031', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221214   154000    154959  1671004199  17800.7  17801.3  0.000034
2022-12-14 15:50:00,624:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2743 

self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17801.3', self.close='17807.1'
127.0.0.1 - - [14/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-14 16:00:01,154:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17801.3', self.close='17807.1'
2022-12-14 16:00:01,200:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221214   151000    151959  1671002399  17790.9  17796.9  0.000337
524  20221214   152000    152959  1671002999  17796.9  17808.9  0.000674
525  20221214   153000    153959  1671003599    17809  17800.7 -0.000460
526  20221214   154000    154959  1671004199  17800.7  17801.3  0.000034
527  20221214   155000    155959  1671004799  17801.3  17807.1  0.000326
2022-12-14 16:00:01,200:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2744 

self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17807.1', self.close='17799.1'
2022-12-14 16:10:01,545:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17807.1', self.close='17799.1'
2022-12-14 16:10:01,571:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221214   152000    152959  1671002999  17796.9  17808.9  0.000674
525  20221214   153000    153959  1671003599    17809  17800.7 -0.000460
526  20221214   154000    154959  1671004199  17800.7  17801.3  0.000034
527  20221214   155000    155959  1671004799  17801.3  17807.1  0.000326
528  20221214   160000    160959  1671005399  17807.1  17799.1 -0.000449
2022-12-14 16:10:01,572:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221214   154000    154959  1671004199  17800.7  17801.3
2022-12-14 15:50:00,640:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2744 

self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17801.3', self.close='17807.1'
127.0.0.1 - - [14/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-14 16:00:01,185:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17801.3', self.close='17807.1'
2022-12-14 16:00:01,209:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221214   151000    151959  1671002399  17790.9  17796.9
17516  20221214   152000    152959  1671002999  17796.9  17808.9
17517  20221214   153000    153959  1671003599    17809  17800.7
17518  20221214   154000    154959  1671004199  17800.7  17801.3
17519  20221214   155000    155959  1671004799  17801.3  17807.1
2022-12-14 16:00:01,209:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2745 

self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17807.1', self.close='17799.1'
2022-12-14 16:10:01,558:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17807.1', self.close='17799.1'
2022-12-14 16:10:01,578:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221214   152000    152959  1671002999  17796.9  17808.9
17517  20221214   153000    153959  1671003599    17809  17800.7
17518  20221214   154000    154959  1671004199  17800.7  17801.3
17519  20221214   155000    155959  1671004799  17801.3  17807.1
17520  20221214   160000    160959  1671005399  17807.1  17799.1
2022-12-14 16:10:01,578:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221214   154000    154959  1671004199  17800.7  17801.3
2022-12-14 15:50:00,630:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2744 

self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17801.3', self.close='17807.1'
2022-12-14 16:00:01,180:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17801.3', self.close='17807.1'
2022-12-14 16:00:01,206:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221214   151000    151959  1671002399  17790.9  17796.9
12188  20221214   152000    152959  1671002999  17796.9  17808.9
12189  20221214   153000    153959  1671003599    17809  17800.7
12190  20221214   154000    154959  1671004199  17800.7  17801.3
12191  20221214   155000    155959  1671004799  17801.3  17807.1
2022-12-14 16:00:01,206:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2745 

self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17807.1', self.close='17799.1'
2022-12-14 16:10:01,552:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17807.1', self.close='17799.1'
2022-12-14 16:10:01,575:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221214   152000    152959  1671002999  17796.9  17808.9
12189  20221214   153000    153959  1671003599    17809  17800.7
12190  20221214   154000    154959  1671004199  17800.7  17801.3
12191  20221214   155000    155959  1671004799  17801.3  17807.1
12192  20221214   160000    160959  1671005399  17807.1  17799.1
2022-12-14 16:10:01,576:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [14/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=920
self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17807.9, self.close=17799.0, self.high=17807.9, self.low=17796.3, self.vol=459.84, self.amt=8184934.6268 
2022-12-14 16:10:01,479:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221214   154500    154959  ...    0.351960   0.301306       0
5950  20221214   155000    155459  ...    0.351733   0.301407       0
5951  20221214   155500    155959  ...    0.351505   0.301507       0
5952  20221214   160000    160459  ...    0.351277   0.301607       0
5953  20221214   160500    160959  ...    0.351049   0.301707       0

[5 rows x 18 columns]
2022-12-14 16:10:01,483:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671005399, self.tradeDate='20221214', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17807.9, self.close=17799.0, self.high=17807.9, self.low=17796.3, self.vol=459.84, self.amt=8184934.6268, ukdf['pct'].iloc[-1]=-0.000494 , ukdf['amount'].iloc[-1]=8184934.6268, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.3510485708319745, signal=0, value_std=0.3017070742680287 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [14/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=921
self.closeSec=1671005699, self.tradeDate='20221214', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17799.0, self.close=17802.3, self.high=17805.1, self.low=17799.0, self.vol=343.86, self.amt=6121515.8733 
2022-12-14 16:15:00,611:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221214   155000    155459  ...    0.351733   0.301407       0
5951  20221214   155500    155959  ...    0.351505   0.301507       0
5952  20221214   160000    160459  ...    0.351277   0.301607       0
5953  20221214   160500    160959  ...    0.351049   0.301707       0
5954  20221214   161000    161459  ...    0.350820   0.301807       0

[5 rows x 18 columns]
2022-12-14 16:15:00,612:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671005699, self.tradeDate='20221214', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17799.0, self.close=17802.3, self.high=17805.1, self.low=17799.0, self.vol=343.86, self.amt=6121515.8733, ukdf['pct'].iloc[-1]=0.000185 , ukdf['amount'].iloc[-1]=6121515.8733, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.35082039225658246, signal=0, value_std=0.3018067998503823 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221214   040000    075959  1670975999  ...    721  1.139591  1.922200     1.0
722  20221214   080000    115959  1670990399  ...    722  1.019275  1.475146     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '1489.62531160428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17784.17681173', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=947876.8211532, self.flagDict['side']='buy', self.tradeCount=6, self.count=114
self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17782.4, self.close=17807.1, self.high=17816.7, self.low=17734.8, self.vol=22263.865, self.amt=395858865.5116 
2022-12-14 16:00:01,033:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671004799, self.tradeDate='20221214', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17782.4, self.close=17807.1, self.high=17816.7, self.low=17734.8, self.vol=22263.865, self.amt=395858865.5116 
127.0.0.1 - - [14/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-14 16:00:01,102:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221213   200000    235959  ...  263218.863  4.674095e+09  0.017933
720  20221214   000000    035959  ...   85131.142  1.509010e+09 -0.000501
721  20221214   040000    075959  ...   33535.147  5.955503e+08  0.002057
722  20221214   080000    115959  ...   30721.609  5.467234e+08  0.000298
723  20221214   120000    155959  ...   22263.865  3.958589e+08  0.001389

[5 rows x 11 columns]
2022-12-14 16:00:02,792:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221213   200000    235959  1670947199  ...    719  1.615970  3.841313     1.0
720  20221214   000000    035959  1670961599  ...    720  1.401853  2.892232     1.0
721  20221214   040000    075959  1670975999  ...    721  1.139591  1.922200     1.0
722  20221214   080000    115959  1670990399  ...    722  1.019275  1.475146     1.0
723  20221214   120000    155959  1671004799  ...    723  0.955077  1.230219     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.436', 'enterprice': '17756.3', 'countrevence': '0', 'unrealprofit': '2795.70221404236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17808.61870301', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


