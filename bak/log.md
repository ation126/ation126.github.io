# 20221220 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6650
self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16796.5, self.close=16797.0, self.high=16797.5, self.low=16782.0, self.vol=585.143, self.amt=9824932.7756 
2022-12-20 16:10:01,581:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221220   154500    154959  ...         0.0        0.0       0
5950  20221220   155000    155459  ...         0.0        0.0       0
5951  20221220   155500    155959  ...         0.0        0.0       0
5952  20221220   160000    160459  ...         0.0        0.0       0
5953  20221220   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 16:10:01,582:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16796.5, self.close=16797.0, self.high=16797.5, self.low=16782.0, self.vol=585.143, self.amt=9824932.7756, ukdf['pct'].iloc[-1]=3e-05 , ukdf['amount'].iloc[-1]=9824932.7756, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16109.1152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16797', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=6651
self.closeSec=1671524099, self.tradeDate='20221220', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16797.0, self.close=16785.5, self.high=16802.6, self.low=16781.0, self.vol=615.928, self.amt=10342882.4885 
2022-12-20 16:15:00,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221220   155000    155459  ...         0.0        0.0       0
5951  20221220   155500    155959  ...         0.0        0.0       0
5952  20221220   160000    160459  ...         0.0        0.0       0
5953  20221220   160500    160959  ...         0.0        0.0       0
5954  20221220   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 16:15:00,577:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671524099, self.tradeDate='20221220', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16797.0, self.close=16785.5, self.high=16802.6, self.low=16781.0, self.vol=615.928, self.amt=10342882.4885, ukdf['pct'].iloc[-1]=-0.000685 , ukdf['amount'].iloc[-1]=10342882.4885, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15485.40595044336', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16786.63524911', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5160443850026833, self.count=7216 

self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16796.5, self.close=16797.0, self.high=16797.5, self.low=16782.0 
2022-12-20 16:10:01,420:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16796.5, self.close=16797.0, self.high=16797.5, self.low=16782.0   
2022-12-20 16:10:01,519:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221220   154500    154959  1671522599  ...  16773.5  0.000793   1629    3
1630  20221220   155000    155459  1671522899  ...  16785.6  0.000846   1630    4
1631  20221220   155500    155959  1671523199  ...  16791.4 -0.000292   1631    5
1632  20221220   160000    160459  1671523499  ...  16784.6  0.000024   1632    0
1633  20221220   160500    160959  1671523799  ...  16782.0  0.000030   1633    1

[5 rows x 11 columns]
2022-12-20 16:10:01,519:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=7, self.factor=0.5160443850026833, self.count=7217 

self.closeSec=1671524099, self.tradeDate='20221220', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16797.0, self.close=16785.5, self.high=16802.6, self.low=16781.0 
2022-12-20 16:15:00,523:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671524099, self.tradeDate='20221220', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16797.0, self.close=16785.5, self.high=16802.6, self.low=16781.0   
127.0.0.1 - - [20/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-20 16:15:00,558:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221220   155000    155459  1671522899  ...  16785.6  0.000846   1630    4
1631  20221220   155500    155959  1671523199  ...  16791.4 -0.000292   1631    5
1632  20221220   160000    160459  1671523499  ...  16784.6  0.000024   1632    0
1633  20221220   160500    160959  1671523799  ...  16782.0  0.000030   1633    1
1634  20221220   161000    161459  1671524099  ...  16781.0 -0.000685   1634    2

[5 rows x 11 columns]
2022-12-20 16:15:00,558:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-20 16:00:17,872:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221220    132959  16783.6  ...  47.916667  0.526850  0.489484
5787  20221220    135959  16755.0  ...  47.916667  0.535737  0.466928
5788  20221220    142959  16778.9  ...  47.500000  0.530102  0.447189
5789  20221220    145959  16765.7  ...  47.916667  0.553656  0.422310
5790  20221220    152959  16830.7  ...  47.500000  0.538877  0.402552

[5 rows x 33 columns]
0.5645756457564576
acc is : 0.5645756457564576
2022-12-20 16:00:17,970:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497220  0.502780       1  ...  1.096543   1.0    0.0  0.975682
538     0  0.511772  0.488228       0  ...  1.095680   1.0    0.0  0.974914
539     0  0.500791  0.499209       1  ...  1.099921   1.0    0.0  0.978688
540     0  0.523739  0.476261       0  ...  1.097647   1.0    0.0  0.976665
541     1  0.494019  0.505981       0  ...  1.097667   1.0    0.0  0.976682

[5 rows x 10 columns]
2022-12-20 16:00:17,993:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497672  0.502328       1  ...  1.096543   1.0    0.0  0.975807
46     0  0.512105  0.487895       0  ...  1.095680   1.0    0.0  0.974184
47     0  0.500844  0.499156       1  ...  1.099921   1.0    0.0  0.977614
48     0  0.525076  0.474924       0  ...  1.097647   1.0    0.0  0.977386
49     1  0.494019  0.505981       0  ...  1.097667   1.0    0.0  0.976682

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '4278.3168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16802.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221220   154000    154959  1671522599  16783.7  16786.8  0.000185
2022-12-20 15:50:00,568:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3607 

self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16786.7', self.close='16796.1'
2022-12-20 16:00:01,299:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16786.7', self.close='16796.1'
2022-12-20 16:00:01,350:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221220   151000    151959  1671520799  16810.1  16803.8 -0.000428
524  20221220   152000    152959  1671521399  16803.9  16795.7 -0.000482
525  20221220   153000    153959  1671521999  16795.7  16783.7 -0.000714
526  20221220   154000    154959  1671522599  16783.7  16786.8  0.000185
527  20221220   155000    155959  1671523199  16786.7  16796.1  0.000554
2022-12-20 16:00:01,350:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3608 

self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16796.2', self.close='16797'
2022-12-20 16:10:01,549:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16796.2', self.close='16797'
2022-12-20 16:10:01,558:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221220   152000    152959  1671521399  16803.9  16795.7 -0.000482
525  20221220   153000    153959  1671521999  16795.7  16783.7 -0.000714
526  20221220   154000    154959  1671522599  16783.7  16786.8  0.000185
527  20221220   155000    155959  1671523199  16786.7  16796.1  0.000554
528  20221220   160000    160959  1671523799  16796.2    16797  0.000054
2022-12-20 16:10:01,558:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [20/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221220   154000    154959  1671522599  16783.7  16786.8
2022-12-20 15:50:00,580:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3608 

self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16786.7', self.close='16796.1'
127.0.0.1 - - [20/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-20 16:00:01,319:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16786.7', self.close='16796.1'
2022-12-20 16:00:01,363:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221220   151000    151959  1671520799  16810.1  16803.8
17516  20221220   152000    152959  1671521399  16803.9  16795.7
17517  20221220   153000    153959  1671521999  16795.7  16783.7
17518  20221220   154000    154959  1671522599  16783.7  16786.8
17519  20221220   155000    155959  1671523199  16786.7  16796.1
2022-12-20 16:00:01,363:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3609 

self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16796.2', self.close='16797'
2022-12-20 16:10:01,540:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16796.2', self.close='16797'
127.0.0.1 - - [20/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-20 16:10:01,560:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221220   152000    152959  1671521399  16803.9  16795.7
17517  20221220   153000    153959  1671521999  16795.7  16783.7
17518  20221220   154000    154959  1671522599  16783.7  16786.8
17519  20221220   155000    155959  1671523199  16786.7  16796.1
17520  20221220   160000    160959  1671523799  16796.2    16797
2022-12-20 16:10:01,560:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221220   154000    154959  1671522599  16783.7  16786.8
2022-12-20 15:50:00,575:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3608 

self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16786.7', self.close='16796.1'
2022-12-20 16:00:01,278:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16786.7', self.close='16796.1'
2022-12-20 16:00:01,325:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221220   151000    151959  1671520799  16810.1  16803.8
12188  20221220   152000    152959  1671521399  16803.9  16795.7
12189  20221220   153000    153959  1671521999  16795.7  16783.7
12190  20221220   154000    154959  1671522599  16783.7  16786.8
12191  20221220   155000    155959  1671523199  16786.7  16796.1
2022-12-20 16:00:01,327:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3609 

self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16796.2', self.close='16797'
2022-12-20 16:10:01,537:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16796.2', self.close='16797'
2022-12-20 16:10:01,570:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221220   152000    152959  1671521399  16803.9  16795.7
12189  20221220   153000    153959  1671521999  16795.7  16783.7
12190  20221220   154000    154959  1671522599  16783.7  16786.8
12191  20221220   155000    155959  1671523199  16786.7  16796.1
12192  20221220   160000    160959  1671523799  16796.2    16797
2022-12-20 16:10:01,570:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [20/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2648
self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16796.5, self.close=16797.0, self.high=16797.5, self.low=16782.0, self.vol=585.143, self.amt=9824932.7756 
2022-12-20 16:10:01,578:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221220   154500    154959  ...         0.0        0.0       0
5950  20221220   155000    155459  ...         0.0        0.0       0
5951  20221220   155500    155959  ...         0.0        0.0       0
5952  20221220   160000    160459  ...         0.0        0.0       0
5953  20221220   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 16:10:01,579:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671523799, self.tradeDate='20221220', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16796.5, self.close=16797.0, self.high=16797.5, self.low=16782.0, self.vol=585.143, self.amt=9824932.7756, ukdf['pct'].iloc[-1]=3e-05 , ukdf['amount'].iloc[-1]=9824932.7756, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [20/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=2649
self.closeSec=1671524099, self.tradeDate='20221220', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16797.0, self.close=16785.5, self.high=16802.6, self.low=16781.0, self.vol=615.928, self.amt=10342882.4885 
2022-12-20 16:15:00,574:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221220   155000    155459  ...         0.0        0.0       0
5951  20221220   155500    155959  ...         0.0        0.0       0
5952  20221220   160000    160459  ...         0.0        0.0       0
5953  20221220   160500    160959  ...         0.0        0.0       0
5954  20221220   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-20 16:15:00,574:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671524099, self.tradeDate='20221220', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16797.0, self.close=16785.5, self.high=16802.6, self.low=16781.0, self.vol=615.928, self.amt=10342882.4885, ukdf['pct'].iloc[-1]=-0.000685 , ukdf['amount'].iloc[-1]=10342882.4885, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2022-12-20 12:00:07,873:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41391F1671508802614I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671508802732496, 'quantity': '53.436', 'price': '16718.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671508802357, 'updatetime': 1671508802732, 'tradetype': 'usdt', 'selfid': 41391, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671508802732, 'clientorderid': '41391F1671508802614I0L65', 'price': '16718.3', 'quantity': '53.436', 'commission': '893.3590788', 'commissionasset': 'USDT', 'tradetime': 1671508802732, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671508802732}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 12:00:07] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Dec/2022 12:00:07] "POST / HTTP/1.1" 200 -
2022-12-20 12:00:07,999:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41392F1671508807851I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671508807947455, 'quantity': '53.372', 'price': '16723.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671508807689, 'updatetime': 1671508807947, 'tradetype': 'usdt', 'selfid': 41392, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671508807947, 'clientorderid': '41392F1671508807851I0L65', 'price': '16723.1', 'quantity': '53.372', 'commission': '892.5452932', 'commissionasset': 'USDT', 'tradetime': 1671508807947, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671508807947}], 'gatetype': 'simulator', 'handletime': 0}
2022-12-20 12:00:08,130:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41392F1671508807851I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1671508807947455, 'quantity': '53.372', 'price': '16723.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1671508807689, 'updatetime': 1671508807947, 'tradetype': 'usdt', 'selfid': 41392, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1671508807947, 'clientorderid': '41392F1671508807851I0L65', 'price': '16723.1', 'quantity': '53.372', 'commission': '892.5452932', 'commissionasset': 'USDT', 'tradetime': 1671508807947, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1671508807947}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [20/Dec/2022 12:00:08] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=150
self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16717.9, self.close=16796.1, self.high=16870.0, self.low=16682.3, self.vol=69915.337, self.amt=1173493065.7499 
2022-12-20 16:00:01,067:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671523199, self.tradeDate='20221220', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16717.9, self.close=16796.1, self.high=16870.0, self.low=16682.3, self.vol=69915.337, self.amt=1173493065.7499 
2022-12-20 16:00:01,093:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20221219   200000    235959  ...   54277.784  9.068502e+08 -0.003892
720  20221220   000000    035959  ...   97414.221  1.616079e+09 -0.006657
721  20221220   040000    075959  ...   87890.393  1.445146e+09 -0.007257
722  20221220   080000    115959  ...  109994.556  1.829875e+09  0.017578
723  20221220   120000    155959  ...   69915.337  1.173493e+09  0.004672

[5 rows x 11 columns]
2022-12-20 16:00:02,516:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221219   200000    235959  1671465599  ...    719  1.012876  0.847578     1.0
720  20221220   000000    035959  1671479999  ...    720  0.877226  0.363186     NaN
721  20221220   040000    075959  1671494399  ...    721  0.677568 -0.376910     NaN
722  20221220   080000    115959  1671508799  ...    722  0.483746 -1.110773    -1.0
723  20221220   120000    155959  1671523199  ...    723  0.424051 -1.325928    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-3896.156', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16796.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


