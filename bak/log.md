# 20221229 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [29/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9242
self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16552.0, self.close=16548.9, self.high=16563.2, self.low=16548.9, self.vol=648.314, self.amt=10733830.8515 
2022-12-29 16:10:01,502:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221229   154500    154959  ...         0.0        0.0       0
5950  20221229   155000    155459  ...         0.0        0.0       0
5951  20221229   155500    155959  ...         0.0        0.0       0
5952  20221229   160000    160459  ...         0.0        0.0       0
5953  20221229   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 16:10:01,502:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16552.0, self.close=16548.9, self.high=16563.2, self.low=16548.9, self.vol=648.314, self.amt=10733830.8515, ukdf['pct'].iloc[-1]=-0.000187 , ukdf['amount'].iloc[-1]=10733830.8515, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1199.79858918864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16549.23815789', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=9243
self.closeSec=1672301699, self.tradeDate='20221229', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16548.9, self.close=16552.0, self.high=16558.1, self.low=16548.9, self.vol=376.204, self.amt=6227873.5251 
127.0.0.1 - - [29/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-29 16:15:00,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221229   155000    155459  ...         0.0        0.0       0
5951  20221229   155500    155959  ...         0.0        0.0       0
5952  20221229   160000    160459  ...         0.0        0.0       0
5953  20221229   160500    160959  ...         0.0        0.0       0
5954  20221229   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 16:15:00,627:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672301699, self.tradeDate='20221229', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16548.9, self.close=16552.0, self.high=16558.1, self.low=16548.9, self.vol=376.204, self.amt=6227873.5251, ukdf['pct'].iloc[-1]=0.000187 , ukdf['amount'].iloc[-1]=6227873.5251, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-1431.49653168544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16553.08849594', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.683767484808682, self.count=9808 

self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16552.0, self.close=16548.9, self.high=16563.2, self.low=16548.9 
2022-12-29 16:10:01,414:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16552.0, self.close=16548.9, self.high=16563.2, self.low=16548.9   
2022-12-29 16:10:01,472:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221229   154500    154959  1672300199  ...  16543.5  0.000024   1629    3
1630  20221229   155000    155459  1672300499  ...  16541.1  0.000091   1630    4
1631  20221229   155500    155959  1672300799  ...  16545.4  0.000459   1631    5
1632  20221229   160000    160459  1672301099  ...  16552.0 -0.000060   1632    0
1633  20221229   160500    160959  1672301399  ...  16548.9 -0.000187   1633    1

[5 rows x 11 columns]
2022-12-29 16:10:01,472:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.683767484808682, self.count=9809 

self.closeSec=1672301699, self.tradeDate='20221229', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16548.9, self.close=16552.0, self.high=16558.1, self.low=16548.9 
2022-12-29 16:15:00,519:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672301699, self.tradeDate='20221229', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16548.9, self.close=16552.0, self.high=16558.1, self.low=16548.9   
127.0.0.1 - - [29/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-29 16:15:00,592:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221229   155000    155459  1672300499  ...  16541.1  0.000091   1630    4
1631  20221229   155500    155959  1672300799  ...  16545.4  0.000459   1631    5
1632  20221229   160000    160459  1672301099  ...  16552.0 -0.000060   1632    0
1633  20221229   160500    160959  1672301399  ...  16548.9 -0.000187   1633    1
1634  20221229   161000    161459  1672301699  ...  16548.9  0.000187   1634    2

[5 rows x 11 columns]
2022-12-29 16:15:00,592:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-29 16:00:19,450:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221229    132959  16564.3  ...  42.916667  0.442064  0.707399
5787  20221229    135959  16553.1  ...  42.916667  0.452633  0.703169
5788  20221229    142959  16570.6  ...  42.916667  0.445613  0.702133
5789  20221229    145959  16556.4  ...  43.333333  0.447967  0.700382
5790  20221229    152959  16560.1  ...  42.916667  0.434392  0.704408

[5 rows x 33 columns]
0.5092250922509225
acc is : 0.5092250922509225
2022-12-29 16:00:19,562:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.497533  0.502467       1  ...  0.989892   1.0    0.0  0.989804
538     0  0.502773  0.497227       0  ...  0.989050   1.0    0.0  0.988961
539     1  0.495419  0.504581       1  ...  0.989277   1.0    0.0  0.989188
540     1  0.499430  0.500570       0  ...  0.987640   1.0    0.0  0.987552
541     1  0.489263  0.510737       1  ...  0.988847   1.0    0.0  0.988758

[5 rows x 10 columns]
2022-12-29 16:00:19,587:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497585  0.502415       1  ...  0.989892   1.0    0.0  0.990330
46     0  0.503003  0.496997       0  ...  0.989050   1.0    0.0  0.988082
47     1  0.495416  0.504584       1  ...  0.989277   1.0    0.0  0.987607
48     1  0.499787  0.500213       0  ...  0.987640   1.0    0.0  0.988154
49     1  0.489263  0.510737       1  ...  0.988847   1.0    0.0  0.988758

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-6315.408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16553', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221229   154000    154959  1672300199  16555.3  16543.9 -0.000683
2022-12-29 15:50:00,532:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4903 

self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16544', self.close='16553'
2022-12-29 16:00:01,328:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16544', self.close='16553'
2022-12-29 16:00:01,369:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221229   151000    151959  1672298399  16556.3  16539.1 -0.001039
524  20221229   152000    152959  1672298999  16539.1  16532.8 -0.000381
525  20221229   153000    153959  1672299599  16532.9  16555.2  0.001355
526  20221229   154000    154959  1672300199  16555.3  16543.9 -0.000683
527  20221229   155000    155959  1672300799    16544    16553  0.000550
2022-12-29 16:00:01,370:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4904 

self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16553', self.close='16548.9'
2022-12-29 16:10:01,544:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16553', self.close='16548.9'
2022-12-29 16:10:01,576:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221229   152000    152959  1672298999  16539.1  16532.8 -0.000381
525  20221229   153000    153959  1672299599  16532.9  16555.2  0.001355
526  20221229   154000    154959  1672300199  16555.3  16543.9 -0.000683
527  20221229   155000    155959  1672300799    16544    16553  0.000550
528  20221229   160000    160959  1672301399    16553  16548.9 -0.000248
2022-12-29 16:10:01,578:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221229   154000    154959  1672300199  16555.3  16543.9
2022-12-29 15:50:00,572:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4904 

self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16544', self.close='16553'
2022-12-29 16:00:01,366:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16544', self.close='16553'
2022-12-29 16:00:01,400:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221229   151000    151959  1672298399  16556.3  16539.1
17516  20221229   152000    152959  1672298999  16539.1  16532.8
17517  20221229   153000    153959  1672299599  16532.9  16555.2
17518  20221229   154000    154959  1672300199  16555.3  16543.9
17519  20221229   155000    155959  1672300799    16544    16553
2022-12-29 16:00:01,400:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4905 

self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16553', self.close='16548.9'
2022-12-29 16:10:01,564:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16553', self.close='16548.9'
127.0.0.1 - - [29/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-29 16:10:01,588:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221229   152000    152959  1672298999  16539.1  16532.8
17517  20221229   153000    153959  1672299599  16532.9  16555.2
17518  20221229   154000    154959  1672300199  16555.3  16543.9
17519  20221229   155000    155959  1672300799    16544    16553
17520  20221229   160000    160959  1672301399    16553  16548.9
2022-12-29 16:10:01,589:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221229   154000    154959  1672300199  16555.3  16543.9
2022-12-29 15:50:00,538:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4904 

self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16544', self.close='16553'
2022-12-29 16:00:01,351:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16544', self.close='16553'
127.0.0.1 - - [29/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-29 16:00:01,396:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221229   151000    151959  1672298399  16556.3  16539.1
12188  20221229   152000    152959  1672298999  16539.1  16532.8
12189  20221229   153000    153959  1672299599  16532.9  16555.2
12190  20221229   154000    154959  1672300199  16555.3  16543.9
12191  20221229   155000    155959  1672300799    16544    16553
2022-12-29 16:00:01,396:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4905 

self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16553', self.close='16548.9'
2022-12-29 16:10:01,536:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16553', self.close='16548.9'
127.0.0.1 - - [29/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-29 16:10:01,545:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221229   152000    152959  1672298999  16539.1  16532.8
12189  20221229   153000    153959  1672299599  16532.9  16555.2
12190  20221229   154000    154959  1672300199  16555.3  16543.9
12191  20221229   155000    155959  1672300799    16544    16553
12192  20221229   160000    160959  1672301399    16553  16548.9
2022-12-29 16:10:01,545:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5240
self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16552.0, self.close=16548.9, self.high=16563.2, self.low=16548.9, self.vol=648.314, self.amt=10733830.8515 
127.0.0.1 - - [29/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-29 16:10:01,482:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221229   154500    154959  ...         0.0        0.0       0
5950  20221229   155000    155459  ...         0.0        0.0       0
5951  20221229   155500    155959  ...         0.0        0.0       0
5952  20221229   160000    160459  ...         0.0        0.0       0
5953  20221229   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 16:10:01,483:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672301399, self.tradeDate='20221229', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16552.0, self.close=16548.9, self.high=16563.2, self.low=16548.9, self.vol=648.314, self.amt=10733830.8515, ukdf['pct'].iloc[-1]=-0.000187 , ukdf['amount'].iloc[-1]=10733830.8515, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [29/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=5241
self.closeSec=1672301699, self.tradeDate='20221229', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16548.9, self.close=16552.0, self.high=16558.1, self.low=16548.9, self.vol=376.204, self.amt=6227873.5251 
2022-12-29 16:15:00,617:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221229   155000    155459  ...         0.0        0.0       0
5951  20221229   155500    155959  ...         0.0        0.0       0
5952  20221229   160000    160459  ...         0.0        0.0       0
5953  20221229   160500    160959  ...         0.0        0.0       0
5954  20221229   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-29 16:15:00,618:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672301699, self.tradeDate='20221229', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16548.9, self.close=16552.0, self.high=16558.1, self.low=16548.9, self.vol=376.204, self.amt=6227873.5251, ukdf['pct'].iloc[-1]=0.000187 , ukdf['amount'].iloc[-1]=6227873.5251, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221229   040000    075959  1672271999  ...    721  0.368737 -0.107683     NaN
722  20221229   080000    115959  1672286399  ...    722  0.439850  0.066642     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '9067.9028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16553.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=204
self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16553.1, self.close=16553.0, self.high=16575.3, self.low=16529.5, self.vol=22366.398, self.amt=370252861.0156 
2022-12-29 16:00:01,247:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672300799, self.tradeDate='20221229', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16553.1, self.close=16553.0, self.high=16575.3, self.low=16529.5, self.vol=22366.398, self.amt=370252861.0156 
127.0.0.1 - - [29/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-29 16:00:01,297:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221228   200000    235959  ...  96230.923  1.604563e+09 -0.006040
720  20221229   000000    035959  ...  48646.340  8.078613e+08  0.001110
721  20221229   040000    075959  ...  73829.964  1.219722e+09 -0.003056
722  20221229   080000    115959  ...  34024.879  5.627557e+08  0.000859
723  20221229   120000    155959  ...  22366.398  3.702529e+08 -0.000012

[5 rows x 11 columns]
2022-12-29 16:00:02,901:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221228   200000    235959  1672243199  ...    719  0.235238 -0.435767     NaN
720  20221229   000000    035959  1672257599  ...    720  0.303751 -0.268507     NaN
721  20221229   040000    075959  1672271999  ...    721  0.368737 -0.107683     NaN
722  20221229   080000    115959  1672286399  ...    722  0.439850  0.066642     NaN
723  20221229   120000    155959  1672300799  ...    723  0.516441  0.253051     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '9073.24', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16553.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


