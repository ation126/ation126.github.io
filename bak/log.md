# 20221212 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [12/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4346
self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16916.5, self.close=16909.6, self.high=16922.7, self.low=16909.5, self.vol=461.99, self.amt=7815193.1016 
2022-12-12 16:10:01,777:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221212   154500    154959  ...         0.0        0.0       0
5950  20221212   155000    155459  ...         0.0        0.0       0
5951  20221212   155500    155959  ...         0.0        0.0       0
5952  20221212   160000    160459  ...         0.0        0.0       0
5953  20221212   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-12 16:10:01,778:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16916.5, self.close=16909.6, self.high=16922.7, self.low=16909.5, self.vol=461.99, self.amt=7815193.1016, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=7815193.1016, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-22903.37033706128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16909.90639353', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4347
self.closeSec=1670832899, self.tradeDate='20221212', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16909.6, self.close=16907.0, self.high=16915.2, self.low=16907.0, self.vol=478.408, self.amt=8090174.7592 
127.0.0.1 - - [12/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-12 16:15:00,602:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221212   155000    155459  ...         0.0        0.0       0
5951  20221212   155500    155959  ...         0.0        0.0       0
5952  20221212   160000    160459  ...         0.0        0.0       0
5953  20221212   160500    160959  ...         0.0        0.0       0
5954  20221212   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-12 16:15:00,602:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670832899, self.tradeDate='20221212', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16909.6, self.close=16907.0, self.high=16915.2, self.low=16907.0, self.vol=478.408, self.amt=8090174.7592, ukdf['pct'].iloc[-1]=-0.000154 , ukdf['amount'].iloc[-1]=8090174.7592, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-22734.4928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16907.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6629600912305573, self.count=4912 

self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16916.5, self.close=16909.6, self.high=16922.7, self.low=16909.5 
2022-12-12 16:10:01,679:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16916.5, self.close=16909.6, self.high=16922.7, self.low=16909.5   
2022-12-12 16:10:01,713:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221212   154500    154959  1670831399  ...  16918.6 -0.000071   1629    3
1630  20221212   155000    155459  1670831699  ...  16918.0  0.000053   1630    4
1631  20221212   155500    155959  1670831999  ...  16916.1 -0.000201   1631    5
1632  20221212   160000    160459  1670832299  ...  16913.1  0.000024   1632    0
1633  20221212   160500    160959  1670832599  ...  16909.5 -0.000414   1633    1

[5 rows x 11 columns]
2022-12-12 16:10:01,713:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6629600912305573, self.count=4913 

self.closeSec=1670832899, self.tradeDate='20221212', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16909.6, self.close=16907.0, self.high=16915.2, self.low=16907.0 
2022-12-12 16:15:00,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670832899, self.tradeDate='20221212', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16909.6, self.close=16907.0, self.high=16915.2, self.low=16907.0   
127.0.0.1 - - [12/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-12 16:15:00,592:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221212   155000    155459  1670831699  ...  16918.0  0.000053   1630    4
1631  20221212   155500    155959  1670831999  ...  16916.1 -0.000201   1631    5
1632  20221212   160000    160459  1670832299  ...  16913.1  0.000024   1632    0
1633  20221212   160500    160959  1670832599  ...  16909.5 -0.000414   1633    1
1634  20221212   161000    161459  1670832899  ...  16907.0 -0.000154   1634    2

[5 rows x 11 columns]
2022-12-12 16:15:00,592:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-12 16:00:22,198:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221212    132959  16924.5  ...  53.750000  0.377879  0.755113
5787  20221212    135959  16917.9  ...  53.750000  0.394645  0.759272
5788  20221212    142959  16938.1  ...  53.750000  0.390003  0.764604
5789  20221212    145959  16929.3  ...  54.166667  0.391430  0.769297
5790  20221212    152959  16930.9  ...  54.166667  0.383776  0.776044

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2022-12-12 16:00:22,371:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.491668  0.508332       1  ...  0.961320   1.0    0.0  0.987425
538     1  0.498685  0.501315       0  ...  0.960826   1.0    0.0  0.986918
539     1  0.491089  0.508911       1  ...  0.960923   1.0    0.0  0.987017
540     1  0.492424  0.507576       0  ...  0.960117   1.0    0.0  0.986190
541     1  0.487169  0.512831       0  ...  0.960083   1.0    0.0  0.986155

[5 rows x 10 columns]
2022-12-12 16:00:22,411:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491699  0.508301       1  ...  0.961320   1.0    0.0  0.987748
46     1  0.498396  0.501604       0  ...  0.960826   1.0    0.0  0.986154
47     1  0.491117  0.508883       1  ...  0.960923   1.0    0.0  0.987040
48     1  0.492136  0.507864       0  ...  0.960117   1.0    0.0  0.984359
49     1  0.487169  0.512831       0  ...  0.960083   1.0    0.0  0.986155

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-11135.32232906218', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16918.12900238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221212   154000    154959  1670831399  16914.6  16918.6  0.000236
2022-12-12 15:50:00,556:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2455 

self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16918.6', self.close='16916.2'
2022-12-12 16:00:01,600:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16918.6', self.close='16916.2'
2022-12-12 16:00:01,650:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221212   151000    151959  1670829599  16928.7  16914.8 -0.000821
524  20221212   152000    152959  1670830199  16914.8  16916.8  0.000118
525  20221212   153000    153959  1670830799  16916.8  16914.6 -0.000130
526  20221212   154000    154959  1670831399  16914.6  16918.6  0.000236
527  20221212   155000    155959  1670831999  16918.6  16916.2 -0.000142
2022-12-12 16:00:01,651:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2456 

self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16916.2', self.close='16909.6'
2022-12-12 16:10:01,769:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16916.2', self.close='16909.6'
127.0.0.1 - - [12/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 16:10:01,823:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221212   152000    152959  1670830199  16914.8  16916.8  0.000118
525  20221212   153000    153959  1670830799  16916.8  16914.6 -0.000130
526  20221212   154000    154959  1670831399  16914.6  16918.6  0.000236
527  20221212   155000    155959  1670831999  16918.6  16916.2 -0.000142
528  20221212   160000    160959  1670832599  16916.2  16909.6 -0.000390
2022-12-12 16:10:01,823:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221212   154000    154959  1670831399  16914.6  16918.6
2022-12-12 15:50:00,570:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2456 

self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16918.6', self.close='16916.2'
127.0.0.1 - - [12/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-12 16:00:01,637:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16918.6', self.close='16916.2'
2022-12-12 16:00:01,677:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221212   151000    151959  1670829599  16928.7  16914.8
17516  20221212   152000    152959  1670830199  16914.8  16916.8
17517  20221212   153000    153959  1670830799  16916.8  16914.6
17518  20221212   154000    154959  1670831399  16914.6  16918.6
17519  20221212   155000    155959  1670831999  16918.6  16916.2
2022-12-12 16:00:01,677:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2457 

self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16916.2', self.close='16909.6'
127.0.0.1 - - [12/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 16:10:01,782:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16916.2', self.close='16909.6'
2022-12-12 16:10:01,835:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221212   152000    152959  1670830199  16914.8  16916.8
17517  20221212   153000    153959  1670830799  16916.8  16914.6
17518  20221212   154000    154959  1670831399  16914.6  16918.6
17519  20221212   155000    155959  1670831999  16918.6  16916.2
17520  20221212   160000    160959  1670832599  16916.2  16909.6
2022-12-12 16:10:01,837:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221212   154000    154959  1670831399  16914.6  16918.6
2022-12-12 15:50:00,570:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2456 

self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16918.6', self.close='16916.2'
127.0.0.1 - - [12/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-12 16:00:01,584:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16918.6', self.close='16916.2'
2022-12-12 16:00:01,630:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221212   151000    151959  1670829599  16928.7  16914.8
12188  20221212   152000    152959  1670830199  16914.8  16916.8
12189  20221212   153000    153959  1670830799  16916.8  16914.6
12190  20221212   154000    154959  1670831399  16914.6  16918.6
12191  20221212   155000    155959  1670831999  16918.6  16916.2
2022-12-12 16:00:01,630:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2457 

self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16916.2', self.close='16909.6'
2022-12-12 16:10:01,764:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16916.2', self.close='16909.6'
127.0.0.1 - - [12/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 16:10:01,830:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221212   152000    152959  1670830199  16914.8  16916.8
12189  20221212   153000    153959  1670830799  16916.8  16914.6
12190  20221212   154000    154959  1670831399  16914.6  16918.6
12191  20221212   155000    155959  1670831999  16918.6  16916.2
12192  20221212   160000    160959  1670832599  16916.2  16909.6
2022-12-12 16:10:01,831:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=344
self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16916.5, self.close=16909.6, self.high=16922.7, self.low=16909.5, self.vol=461.99, self.amt=7815193.1016 
127.0.0.1 - - [12/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-12 16:10:01,749:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221212   154500    154959  ...    0.531002   0.207353       0
5950  20221212   155000    155459  ...    0.530774   0.207696       0
5951  20221212   155500    155959  ...    0.530545   0.208039       0
5952  20221212   160000    160459  ...    0.530315   0.208381       0
5953  20221212   160500    160959  ...    0.530085   0.208722       0

[5 rows x 18 columns]
2022-12-12 16:10:01,749:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670832599, self.tradeDate='20221212', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16916.5, self.close=16909.6, self.high=16922.7, self.low=16909.5, self.vol=461.99, self.amt=7815193.1016, ukdf['pct'].iloc[-1]=-0.000414 , ukdf['amount'].iloc[-1]=7815193.1016, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.5300848573442897, signal=0, value_std=0.20872210531564536 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--: 127.0.0.1 - - [12/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=345
self.closeSec=1670832899, self.tradeDate='20221212', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16909.6, self.close=16907.0, self.high=16915.2, self.low=16907.0, self.vol=478.408, self.amt=8090174.7592 
2022-12-12 16:15:00,603:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221212   155000    155459  ...    0.530774   0.207696       0
5951  20221212   155500    155959  ...    0.530545   0.208039       0
5952  20221212   160000    160459  ...    0.530315   0.208381       0
5953  20221212   160500    160959  ...    0.530085   0.208722       0
5954  20221212   161000    161459  ...    0.529856   0.209062       0

[5 rows x 18 columns]
2022-12-12 16:15:00,603:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670832899, self.tradeDate='20221212', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16909.6, self.close=16907.0, self.high=16915.2, self.low=16907.0, self.vol=478.408, self.amt=8090174.7592, ukdf['pct'].iloc[-1]=-0.000154 , ukdf['amount'].iloc[-1]=8090174.7592, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.5298559049381623, signal=0, value_std=0.20906206820719803 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221212   040000    075959  1670803199  ...    721  0.507540 -0.038979     NaN
722  20221212   080000    115959  1670817599  ...    722  0.404512 -0.433041     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-23032.5838', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16908.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [12/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=102
self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16909.0, self.close=16916.1, self.high=16939.0, self.low=16894.3, self.vol=27433.054, self.amt=464177744.3694 
2022-12-12 16:00:01,484:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670831999, self.tradeDate='20221212', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16909.0, self.close=16916.1, self.high=16939.0, self.low=16894.3, self.vol=27433.054, self.amt=464177744.3694 
2022-12-12 16:00:01,509:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221211   200000    235959  ...  19880.891  3.408058e+08 -0.000892
720  20221212   000000    035959  ...  46356.060  7.967647e+08  0.001400
721  20221212   040000    075959  ...  52598.599  8.996990e+08 -0.005353
722  20221212   080000    115959  ...  93215.464  1.579861e+09 -0.009873
723  20221212   120000    155959  ...  27433.054  4.641777e+08  0.000420

[5 rows x 11 columns]
2022-12-12 16:00:03,366:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221211   200000    235959  1670774399  ...    719  0.578351  0.236847     NaN
720  20221212   000000    035959  1670788799  ...    720  0.571626  0.203078     NaN
721  20221212   040000    075959  1670803199  ...    721  0.507540 -0.038979     NaN
722  20221212   080000    115959  1670817599  ...    722  0.404512 -0.433041     NaN
723  20221212   120000    155959  1670831999  ...    723  0.378032 -0.551198     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-22532.21529281806', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16917.13550727', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


