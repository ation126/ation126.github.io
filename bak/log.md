# 20221223 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [23/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7514
self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16845.5, self.close=16823.1, self.high=16845.5, self.low=16805.2, self.vol=2349.142, self.amt=39513810.5798 
2022-12-23 16:10:01,470:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221223   154500    154959  ...         0.0        0.0       0
5950  20221223   155000    155459  ...         0.0        0.0       0
5951  20221223   155500    155959  ...         0.0        0.0       0
5952  20221223   160000    160459  ...         0.0        0.0       0
5953  20221223   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 16:10:01,471:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16845.5, self.close=16823.1, self.high=16845.5, self.low=16805.2, self.vol=2349.142, self.amt=39513810.5798, ukdf['pct'].iloc[-1]=-0.001324 , ukdf['amount'].iloc[-1]=39513810.5798, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17679.7088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16823.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7515
self.closeSec=1671783299, self.tradeDate='20221223', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16823.1, self.close=16828.5, self.high=16831.2, self.low=16814.3, self.vol=997.748, self.amt=16783348.6232 
2022-12-23 16:15:00,631:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221223   155000    155459  ...         0.0        0.0       0
5951  20221223   155500    155959  ...         0.0        0.0       0
5952  20221223   160000    160459  ...         0.0        0.0       0
5953  20221223   160500    160959  ...         0.0        0.0       0
5954  20221223   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 16:15:00,631:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671783299, self.tradeDate='20221223', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16823.1, self.close=16828.5, self.high=16831.2, self.low=16814.3, self.vol=997.748, self.amt=16783348.6232, ukdf['pct'].iloc[-1]=0.000321 , ukdf['amount'].iloc[-1]=16783348.6232, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-18004.6592', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16828.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16845.5, self.close=16823.1, self.high=16845.5, self.low=16805.2 
2022-12-23 16:10:01,417:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16845.5, self.close=16823.1, self.high=16845.5, self.low=16805.2   
127.0.0.1 - - [23/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-23 16:10:01,434:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221223   154500    154959  1671781799  ...  16834.7  0.000261   1629    3
1630  20221223   155000    155459  1671782099  ...  16836.1  0.000356   1630    4
1631  20221223   155500    155959  1671782399  ...  16840.1 -0.000220   1631    5
1632  20221223   160000    160459  1671782699  ...  16842.0  0.000202   1632    0
1633  20221223   160500    160959  1671782999  ...  16805.2 -0.001324   1633    1

[5 rows x 11 columns]
2022-12-23 16:10:01,456:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=102, self.factor=0.3617431474854889, self.count=8081 

self.closeSec=1671783299, self.tradeDate='20221223', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16823.1, self.close=16828.5, self.high=16831.2, self.low=16814.3 
2022-12-23 16:15:00,563:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671783299, self.tradeDate='20221223', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16823.1, self.close=16828.5, self.high=16831.2, self.low=16814.3   
127.0.0.1 - - [23/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-23 16:15:00,609:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221223   155000    155459  1671782099  ...  16836.1  0.000356   1630    4
1631  20221223   155500    155959  1671782399  ...  16840.1 -0.000220   1631    5
1632  20221223   160000    160459  1671782699  ...  16842.0  0.000202   1632    0
1633  20221223   160500    160959  1671782999  ...  16805.2 -0.001324   1633    1
1634  20221223   161000    161459  1671783299  ...  16814.3  0.000321   1634    2

[5 rows x 11 columns]
2022-12-23 16:15:00,609:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-23 16:00:18,746:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221223    132959  16832.0  ...  49.166667  0.520801  0.323709
5787  20221223    135959  16821.8  ...  49.166667  0.515734  0.318358
5788  20221223    142959  16812.6  ...  49.166667  0.513760  0.314071
5789  20221223    145959  16809.0  ...  49.166667  0.527202  0.304916
5790  20221223    152959  16835.1  ...  49.166667  0.532884  0.294149

[5 rows x 33 columns]
0.5387453874538746
acc is : 0.5387453874538746
2022-12-23 16:00:18,859:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493802  0.506198       0  ...  1.098738   1.0    0.0  0.992274
538     1  0.494051  0.505949       0  ...  1.098503   1.0    0.0  0.992062
539     1  0.496654  0.503346       1  ...  1.100215   1.0    0.0  0.993608
540     0  0.507233  0.492767       1  ...  1.100954   1.0    0.0  0.994275
541     0  0.503551  0.496449       0  ...  1.100673   1.0    0.0  0.994021

[5 rows x 10 columns]
2022-12-23 16:00:18,883:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493424  0.506576       0  ...  1.098738   1.0    0.0  0.983659
46     1  0.493572  0.506428       0  ...  1.098503   1.0    0.0  0.983339
47     1  0.496347  0.503653       1  ...  1.100215   1.0    0.0  0.985800
48     0  0.507255  0.492745       1  ...  1.100954   1.0    0.0  0.992746
49     0  0.503551  0.496449       0  ...  1.100673   1.0    0.0  0.994021

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '5984.13876117312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16842.21056154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221223   154000    154959  1671781799  16844.1  16839.6 -0.000261
2022-12-23 15:50:00,549:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4039 

self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16839.7', self.close='16842'
2022-12-23 16:00:01,298:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16839.7', self.close='16842'
2022-12-23 16:00:01,354:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221223   151000    151959  1671779999  16836.9  16837.3  0.000024
524  20221223   152000    152959  1671780599  16837.4  16846.2  0.000529
525  20221223   153000    153959  1671781199  16846.3    16844 -0.000131
526  20221223   154000    154959  1671781799  16844.1  16839.6 -0.000261
527  20221223   155000    155959  1671782399  16839.7    16842  0.000143
2022-12-23 16:00:01,354:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4040 

self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16842', self.close='16823.1'
2022-12-23 16:10:01,532:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16842', self.close='16823.1'
2022-12-23 16:10:01,558:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221223   152000    152959  1671780599  16837.4  16846.2  0.000529
525  20221223   153000    153959  1671781199  16846.3    16844 -0.000131
526  20221223   154000    154959  1671781799  16844.1  16839.6 -0.000261
527  20221223   155000    155959  1671782399  16839.7    16842  0.000143
528  20221223   160000    160959  1671782999    16842  16823.1 -0.001122
2022-12-23 16:10:01,558:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221223   154000    154959  1671781799  16844.1  16839.6
2022-12-23 15:50:00,536:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4040 

self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16839.7', self.close='16842'
127.0.0.1 - - [23/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-23 16:00:01,311:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16839.7', self.close='16842'
2022-12-23 16:00:01,363:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221223   151000    151959  1671779999  16836.9  16837.3
17516  20221223   152000    152959  1671780599  16837.4  16846.2
17517  20221223   153000    153959  1671781199  16846.3    16844
17518  20221223   154000    154959  1671781799  16844.1  16839.6
17519  20221223   155000    155959  1671782399  16839.7    16842
2022-12-23 16:00:01,365:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4041 

self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16842', self.close='16823.1'
2022-12-23 16:10:01,540:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16842', self.close='16823.1'
2022-12-23 16:10:01,576:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221223   152000    152959  1671780599  16837.4  16846.2
17517  20221223   153000    153959  1671781199  16846.3    16844
17518  20221223   154000    154959  1671781799  16844.1  16839.6
17519  20221223   155000    155959  1671782399  16839.7    16842
17520  20221223   160000    160959  1671782999    16842  16823.1
2022-12-23 16:10:01,578:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221223   154000    154959  1671781799  16844.1  16839.6
2022-12-23 15:50:00,566:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--: 127.0.0.1 - - [23/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4040 

self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16839.7', self.close='16842'
2022-12-23 16:00:01,307:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16839.7', self.close='16842'
2022-12-23 16:00:01,359:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221223   151000    151959  1671779999  16836.9  16837.3
12188  20221223   152000    152959  1671780599  16837.4  16846.2
12189  20221223   153000    153959  1671781199  16846.3    16844
12190  20221223   154000    154959  1671781799  16844.1  16839.6
12191  20221223   155000    155959  1671782399  16839.7    16842
2022-12-23 16:00:01,361:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4041 

self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16842', self.close='16823.1'
2022-12-23 16:10:01,545:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16842', self.close='16823.1'
127.0.0.1 - - [23/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-23 16:10:01,565:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221223   152000    152959  1671780599  16837.4  16846.2
12189  20221223   153000    153959  1671781199  16846.3    16844
12190  20221223   154000    154959  1671781799  16844.1  16839.6
12191  20221223   155000    155959  1671782399  16839.7    16842
12192  20221223   160000    160959  1671782999    16842  16823.1
2022-12-23 16:10:01,567:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3512
self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16845.5, self.close=16823.1, self.high=16845.5, self.low=16805.2, self.vol=2349.142, self.amt=39513810.5798 
127.0.0.1 - - [23/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-23 16:10:01,484:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221223   154500    154959  ...         0.0        0.0       0
5950  20221223   155000    155459  ...         0.0        0.0       0
5951  20221223   155500    155959  ...         0.0        0.0       0
5952  20221223   160000    160459  ...         0.0        0.0       0
5953  20221223   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 16:10:01,484:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671782999, self.tradeDate='20221223', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16845.5, self.close=16823.1, self.high=16845.5, self.low=16805.2, self.vol=2349.142, self.amt=39513810.5798, ukdf['pct'].iloc[-1]=-0.001324 , ukdf['amount'].iloc[-1]=39513810.5798, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [23/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3513
self.closeSec=1671783299, self.tradeDate='20221223', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16823.1, self.close=16828.5, self.high=16831.2, self.low=16814.3, self.vol=997.748, self.amt=16783348.6232 
2022-12-23 16:15:00,626:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221223   155000    155459  ...         0.0        0.0       0
5951  20221223   155500    155959  ...         0.0        0.0       0
5952  20221223   160000    160459  ...         0.0        0.0       0
5953  20221223   160500    160959  ...         0.0        0.0       0
5954  20221223   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-23 16:15:00,626:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671783299, self.tradeDate='20221223', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16823.1, self.close=16828.5, self.high=16831.2, self.low=16814.3, self.vol=997.748, self.amt=16783348.6232, ukdf['pct'].iloc[-1]=0.000321 , ukdf['amount'].iloc[-1]=16783348.6232, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221223   040000    075959  1671753599  ...    721  0.047321 -1.558658    -1.0
722  20221223   080000    115959  1671767999  ...    722  0.048847 -1.513796    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5395.06004827768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16824.18408994', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [23/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=168
self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16823.5, self.close=16842.0, self.high=16849.0, self.low=16801.0, self.vol=24891.267, self.amt=418832083.7704 
2022-12-23 16:00:01,198:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671782399, self.tradeDate='20221223', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16823.5, self.close=16842.0, self.high=16849.0, self.low=16801.0, self.vol=24891.267, self.amt=418832083.7704 
2022-12-23 16:00:01,235:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221222   200000    235959  ...  98813.975  1.650437e+09 -0.011653
720  20221223   000000    035959  ...  63297.216  1.051686e+09  0.001611
721  20221223   040000    075959  ...  77053.704  1.293023e+09  0.009431
722  20221223   080000    115959  ...  40208.220  6.764735e+08  0.000482
723  20221223   120000    155959  ...  24891.267  4.188321e+08  0.001100

[5 rows x 11 columns]
2022-12-23 16:00:02,689:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221222   200000    235959  1671724799  ...    719  0.035780 -1.677523    -1.0
720  20221223   000000    035959  1671739199  ...    720  0.047576 -1.601173    -1.0
721  20221223   040000    075959  1671753599  ...    721  0.047321 -1.558658    -1.0
722  20221223   080000    115959  1671767999  ...    722  0.048847 -1.513796    -1.0
723  20221223   120000    155959  1671782399  ...    723  0.044734 -1.484985    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-6345.9308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


