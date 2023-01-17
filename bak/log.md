# 20230117 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14714
self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21141.0, self.close=21131.4, self.high=21143.2, self.low=21130.4, self.vol=621.808, self.amt=13141820.1357 
2023-01-17 16:10:01,524:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230117   154500    154959  ...         0.0        0.0       0
5950  20230117   155000    155459  ...         0.0        0.0       0
5951  20230117   155500    155959  ...         0.0        0.0       0
5952  20230117   160000    160459  ...         0.0        0.0       0
5953  20230117   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 16:10:01,525:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21141.0, self.close=21131.4, self.high=21143.2, self.low=21130.4, self.vol=621.808, self.amt=13141820.1357, ukdf['pct'].iloc[-1]=-0.000459 , ukdf['amount'].iloc[-1]=13141820.1357, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-276982.95573147856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21132.18081181', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14715
self.closeSec=1673943299, self.tradeDate='20230117', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=21131.4, self.close=21163.8, self.high=21169.8, self.low=21131.0, self.vol=1027.833, self.amt=21744193.6232 
127.0.0.1 - - [17/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-17 16:15:00,698:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230117   155000    155459  ...         0.0        0.0       0
5951  20230117   155500    155959  ...         0.0        0.0       0
5952  20230117   160000    160459  ...         0.0        0.0       0
5953  20230117   160500    160959  ...         0.0        0.0       0
5954  20230117   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 16:15:00,701:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673943299, self.tradeDate='20230117', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=21131.4, self.close=21163.8, self.high=21169.8, self.low=21131.0, self.vol=1027.833, self.amt=21744193.6232, ukdf['pct'].iloc[-1]=0.001533 , ukdf['amount'].iloc[-1]=21744193.6232, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-278776.94598875776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21161.99319976', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=463, self.factor=0.44550723289103983, self.count=15280 

self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21141.0, self.close=21131.4, self.high=21143.2, self.low=21130.4 
2023-01-17 16:10:01,422:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21141.0, self.close=21131.4, self.high=21143.2, self.low=21130.4   
2023-01-17 16:10:01,474:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230117   154500    154959  1673941799  ...  21077.2  0.000750   1629    3
1630  20230117   155000    155459  1673942099  ...  21092.9  0.001560   1630    4
1631  20230117   155500    155959  1673942399  ...  21119.5  0.000417   1631    5
1632  20230117   160000    160459  1673942699  ...  21130.7  0.000303   1632    0
1633  20230117   160500    160959  1673942999  ...  21130.4 -0.000459   1633    1

[5 rows x 11 columns]
2023-01-17 16:10:01,475:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=463, self.factor=0.44550723289103983, self.count=15281 

self.closeSec=1673943299, self.tradeDate='20230117', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=21131.4, self.close=21163.8, self.high=21169.8, self.low=21131.0 
2023-01-17 16:15:00,594:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673943299, self.tradeDate='20230117', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=21131.4, self.close=21163.8, self.high=21169.8, self.low=21131.0   
2023-01-17 16:15:00,659:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230117   155000    155459  1673942099  ...  21092.9  0.001560   1630    4
1631  20230117   155500    155959  1673942399  ...  21119.5  0.000417   1631    5
1632  20230117   160000    160459  1673942699  ...  21130.7  0.000303   1632    0
1633  20230117   160500    160959  1673942999  ...  21130.4 -0.000459   1633    1
1634  20230117   161000    161459  1673943299  ...  21131.0  0.001533   1634    2

[5 rows x 11 columns]
2023-01-17 16:15:00,661:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-17 16:00:36,280:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230117    132959  21160.1  ...  55.000000  0.543699  0.421001
5787  20230117    135959  21138.0  ...  55.416667  0.546397  0.418692
5788  20230117    142959  21153.7  ...  55.000000  0.539904  0.418862
5789  20230117    145959  21122.6  ...  54.583333  0.530614  0.422379
5790  20230117    152959  21077.7  ...  54.583333  0.535122  0.423807

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-01-17 16:00:36,458:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502011  0.497989       1  ...  1.050688   1.0    0.0  1.255250
538     0  0.511355  0.488645       0  ...  1.049144   1.0    0.0  1.253405
539     1  0.495840  0.504160       0  ...  1.046913   1.0    0.0  1.250740
540     1  0.479600  0.520400       1  ...  1.048145   1.0    0.0  1.252212
541     0  0.501360  0.498640       1  ...  1.049749   1.0    0.0  1.254129

[5 rows x 10 columns]
2023-01-17 16:00:36,496:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.501916  0.498084       1  ...  1.050688   1.0    0.0  1.256906
46     0  0.511220  0.488780       0  ...  1.049144   1.0    0.0  1.255722
47     1  0.495316  0.504684       0  ...  1.046913   1.0    0.0  1.252844
48     1  0.479577  0.520423       1  ...  1.048145   1.0    0.0  1.253476
49     0  0.501360  0.498640       1  ...  1.049749   1.0    0.0  1.254129

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230117   154000    154959  1673941799  21075.3    21093  0.000840
2023-01-17 15:50:00,541:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7639 

self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21093.1', self.close='21134.7'
2023-01-17 16:00:01,433:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21093.1', self.close='21134.7'
2023-01-17 16:00:01,480:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230117   151000    151959  1673939999    21114  21166.7  0.002496
524  20230117   152000    152959  1673940599  21168.8  21102.4 -0.003038
525  20230117   153000    153959  1673941199  21102.3  21075.3 -0.001284
526  20230117   154000    154959  1673941799  21075.3    21093  0.000840
527  20230117   155000    155959  1673942399  21093.1  21134.7  0.001977
2023-01-17 16:00:01,480:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7640 

self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21134.8', self.close='21131.4'
2023-01-17 16:10:01,560:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21134.8', self.close='21131.4'
127.0.0.1 - - [17/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-17 16:10:01,586:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230117   152000    152959  1673940599  21168.8  21102.4 -0.003038
525  20230117   153000    153959  1673941199  21102.3  21075.3 -0.001284
526  20230117   154000    154959  1673941799  21075.3    21093  0.000840
527  20230117   155000    155959  1673942399  21093.1  21134.7  0.001977
528  20230117   160000    160959  1673942999  21134.8  21131.4 -0.000156
2023-01-17 16:10:01,588:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230117   154000    154959  1673941799  21075.3    21093
2023-01-17 15:50:00,554:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7640 

self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21093.1', self.close='21134.7'
127.0.0.1 - - [17/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-17 16:00:01,446:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21093.1', self.close='21134.7'
2023-01-17 16:00:01,487:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230117   151000    151959  1673939999    21114  21166.7
17516  20230117   152000    152959  1673940599  21168.8  21102.4
17517  20230117   153000    153959  1673941199  21102.3  21075.3
17518  20230117   154000    154959  1673941799  21075.3    21093
17519  20230117   155000    155959  1673942399  21093.1  21134.7
2023-01-17 16:00:01,488:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7641 

self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21134.8', self.close='21131.4'
2023-01-17 16:10:01,555:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21134.8', self.close='21131.4'
127.0.0.1 - - [17/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-17 16:10:01,598:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230117   152000    152959  1673940599  21168.8  21102.4
17517  20230117   153000    153959  1673941199  21102.3  21075.3
17518  20230117   154000    154959  1673941799  21075.3    21093
17519  20230117   155000    155959  1673942399  21093.1  21134.7
17520  20230117   160000    160959  1673942999  21134.8  21131.4
2023-01-17 16:10:01,598:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230117   154000    154959  1673941799  21075.3    21093
2023-01-17 15:50:00,622:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7640 

self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='21093.1', self.close='21134.7'
127.0.0.1 - - [17/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-01-17 16:00:01,424:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='21093.1', self.close='21134.7'
2023-01-17 16:00:01,441:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230117   151000    151959  1673939999    21114  21166.7
12188  20230117   152000    152959  1673940599  21168.8  21102.4
12189  20230117   153000    153959  1673941199  21102.3  21075.3
12190  20230117   154000    154959  1673941799  21075.3    21093
12191  20230117   155000    155959  1673942399  21093.1  21134.7
2023-01-17 16:00:01,441:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7641 

self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='21134.8', self.close='21131.4'
2023-01-17 16:10:01,543:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='21134.8', self.close='21131.4'
2023-01-17 16:10:01,589:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230117   152000    152959  1673940599  21168.8  21102.4
12189  20230117   153000    153959  1673941199  21102.3  21075.3
12190  20230117   154000    154959  1673941799  21075.3    21093
12191  20230117   155000    155959  1673942399  21093.1  21134.7
12192  20230117   160000    160959  1673942999  21134.8  21131.4
2023-01-17 16:10:01,592:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10712
self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=21141.0, self.close=21131.4, self.high=21143.2, self.low=21130.4, self.vol=621.808, self.amt=13141820.1357 
127.0.0.1 - - [17/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-17 16:10:01,488:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230117   154500    154959  ...         0.0        0.0       0
5950  20230117   155000    155459  ...         0.0        0.0       0
5951  20230117   155500    155959  ...         0.0        0.0       0
5952  20230117   160000    160459  ...         0.0        0.0       0
5953  20230117   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 16:10:01,488:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673942999, self.tradeDate='20230117', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=21141.0, self.close=21131.4, self.high=21143.2, self.low=21130.4, self.vol=621.808, self.amt=13141820.1357, ukdf['pct'].iloc[-1]=-0.000459 , ukdf['amount'].iloc[-1]=13141820.1357, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10713
self.closeSec=1673943299, self.tradeDate='20230117', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=21131.4, self.close=21163.8, self.high=21169.8, self.low=21131.0, self.vol=1027.833, self.amt=21744193.6232 
127.0.0.1 - - [17/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-17 16:15:00,687:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230117   155000    155459  ...         0.0        0.0       0
5951  20230117   155500    155959  ...         0.0        0.0       0
5952  20230117   160000    160459  ...         0.0        0.0       0
5953  20230117   160500    160959  ...         0.0        0.0       0
5954  20230117   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-17 16:15:00,687:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673943299, self.tradeDate='20230117', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=21131.4, self.close=21163.8, self.high=21169.8, self.low=21131.0, self.vol=1027.833, self.amt=21744193.6232, ukdf['pct'].iloc[-1]=0.001533 , ukdf['amount'].iloc[-1]=21744193.6232, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230117   040000    075959  1673913599  ...    721  0.897750  0.242217     NaN
722  20230117   080000    115959  1673927999  ...    722  0.876839  0.169505     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '201483.82001007104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21128.35605464', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [17/Jan/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=318
self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=21129.6, self.close=21134.7, self.high=21237.0, self.low=21062.1, self.vol=40393.627, self.amt=853912275.0964 
2023-01-17 16:00:01,315:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673942399, self.tradeDate='20230117', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=21129.6, self.close=21134.7, self.high=21237.0, self.low=21062.1, self.vol=40393.627, self.amt=853912275.0964 
2023-01-17 16:00:01,358:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230116   200000    235959  ...  114395.111  2.386427e+09  0.008592
720  20230117   000000    035959  ...  133530.799  2.828000e+09  0.014942
721  20230117   040000    075959  ...   85257.322  1.810116e+09 -0.005916
722  20230117   080000    115959  ...   81669.204  1.722050e+09 -0.002770
723  20230117   120000    155959  ...   40393.627  8.539123e+08  0.000241

[5 rows x 11 columns]
2023-01-17 16:00:03,165:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230116   200000    235959  1673884799  ...    719  0.815950  0.078361     NaN
720  20230117   000000    035959  1673899199  ...    720  0.793669  0.003926     NaN
721  20230117   040000    075959  1673913599  ...    721  0.897750  0.242217     NaN
722  20230117   080000    115959  1673927999  ...    722  0.876839  0.169505     NaN
723  20230117   120000    155959  1673942399  ...    723  0.774235 -0.117167     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '201843.7902743552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '21135.3955232', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


