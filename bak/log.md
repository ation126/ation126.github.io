# 20221211 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4058
self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17173.5, self.close=17163.8, self.high=17175.6, self.low=17163.7, self.vol=561.401, self.amt=9639978.3427 
127.0.0.1 - - [11/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-11 16:10:01,513:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221211   154500    154959  ...         0.0        0.0       0
5950  20221211   155000    155459  ...         0.0        0.0       0
5951  20221211   155500    155959  ...         0.0        0.0       0
5952  20221211   160000    160459  ...         0.0        0.0       0
5953  20221211   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-11 16:10:01,513:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17173.5, self.close=17163.8, self.high=17175.6, self.low=17163.7, self.vol=561.401, self.amt=9639978.3427, ukdf['pct'].iloc[-1]=-0.000559 , ukdf['amount'].iloc[-1]=9639978.3427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-38199.49316813376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17164.09615076', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=4059
self.closeSec=1670746499, self.tradeDate='20221211', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17163.8, self.close=17161.2, self.high=17166.3, self.low=17161.1, self.vol=419.626, self.amt=7201838.4402 
2022-12-11 16:15:00,604:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221211   155000    155459  ...         0.0        0.0       0
5951  20221211   155500    155959  ...         0.0        0.0       0
5952  20221211   160000    160459  ...         0.0        0.0       0
5953  20221211   160500    160959  ...         0.0        0.0       0
5954  20221211   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-11 16:15:00,604:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670746499, self.tradeDate='20221211', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17163.8, self.close=17161.2, self.high=17166.3, self.low=17161.1, self.vol=419.626, self.amt=7201838.4402, ukdf['pct'].iloc[-1]=-0.000151 , ukdf['amount'].iloc[-1]=7201838.4402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-38019.1968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17161.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17173.5, self.close=17163.8, self.high=17175.6, self.low=17163.7 
2022-12-11 16:10:01,451:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17173.5, self.close=17163.8, self.high=17175.6, self.low=17163.7   
127.0.0.1 - - [11/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-11 16:10:01,509:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221211   154500    154959  1670744999  ...  17169.1  0.000198   1629    3
1630  20221211   155000    155459  1670745299  ...  17172.7  0.000215   1630    4
1631  20221211   155500    155959  1670745599  ...  17169.7 -0.000146   1631    5
1632  20221211   160000    160459  1670745899  ...  17173.2 -0.000023   1632    0
1633  20221211   160500    160959  1670746199  ...  17163.7 -0.000559   1633    1

[5 rows x 11 columns]
2022-12-11 16:10:01,509:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=79, self.factor=0.5354279911432221, self.count=4625 

self.closeSec=1670746499, self.tradeDate='20221211', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17163.8, self.close=17161.2, self.high=17166.3, self.low=17161.1 
2022-12-11 16:15:00,530:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670746499, self.tradeDate='20221211', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17163.8, self.close=17161.2, self.high=17166.3, self.low=17161.1   
2022-12-11 16:15:00,591:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221211   155000    155459  1670745299  ...  17172.7  0.000215   1630    4
1631  20221211   155500    155959  1670745599  ...  17169.7 -0.000146   1631    5
1632  20221211   160000    160459  1670745899  ...  17173.2 -0.000023   1632    0
1633  20221211   160500    160959  1670746199  ...  17163.7 -0.000559   1633    1
1634  20221211   161000    161459  1670746499  ...  17161.1 -0.000151   1634    2

[5 rows x 11 columns]
2022-12-11 16:15:00,591:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-11 16:00:18,550:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20221211    132959  17161.0  ...  55.416667  0.519837  0.550774
5787  20221211    135959  17153.7  ...  55.833333  0.528022  0.543053
5788  20221211    142959  17164.4  ...  55.833333  0.532430  0.533227
5789  20221211    145959  17170.2  ...  55.833333  0.526205  0.527308
5790  20221211    152959  17163.0  ...  55.833333  0.529324  0.519977

[5 rows x 33 columns]
0.584870848708487
acc is : 0.584870848708487
2022-12-11 16:00:18,674:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.494261  0.505739       1  ...  0.978467   1.0    0.0  1.019191
538     1  0.497764  0.502236       1  ...  0.978798   1.0    0.0  1.019535
539     1  0.497519  0.502481       0  ...  0.978387   1.0    0.0  1.019108
540     1  0.493893  0.506107       1  ...  0.978615   1.0    0.0  1.019345
541     1  0.495642  0.504358       1  ...  0.978980   1.0    0.0  1.019725

[5 rows x 10 columns]
2022-12-11 16:00:18,689:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494278  0.505722       1  ...  0.978467   1.0    0.0  1.040935
46     1  0.499415  0.500585       1  ...  0.978798   1.0    0.0  1.043559
47     1  0.498328  0.501672       0  ...  0.978387   1.0    0.0  1.044410
48     1  0.494301  0.505699       1  ...  0.978615   1.0    0.0  1.043714
49     1  0.495642  0.504358       1  ...  0.978980   1.0    0.0  1.019725

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.789', 'enterprice': '17212.8', 'countrevence': '0', 'unrealprofit': '-1496.4444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17173.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221211   154000    154959  1670744999  17164.3  17172.6  0.000484
2022-12-11 15:50:00,758:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2311 

self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17172.7', self.close='17173.4'
2022-12-11 16:00:01,137:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17172.7', self.close='17173.4'
2022-12-11 16:00:01,224:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221211   151000    151959  1670743199  17158.9  17152.5 -0.000373
524  20221211   152000    152959  1670743799  17152.5    17167  0.000845
525  20221211   153000    153959  1670744399  17166.9  17164.3 -0.000157
526  20221211   154000    154959  1670744999  17164.3  17172.6  0.000484
527  20221211   155000    155959  1670745599  17172.7  17173.4  0.000047
2022-12-11 16:00:01,224:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2312 

self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17173.4', self.close='17163.8'
2022-12-11 16:10:01,539:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17173.4', self.close='17163.8'
2022-12-11 16:10:01,570:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221211   152000    152959  1670743799  17152.5    17167  0.000845
525  20221211   153000    153959  1670744399  17166.9  17164.3 -0.000157
526  20221211   154000    154959  1670744999  17164.3  17172.6  0.000484
527  20221211   155000    155959  1670745599  17172.7  17173.4  0.000047
528  20221211   160000    160959  1670746199  17173.4  17163.8 -0.000559
2022-12-11 16:10:01,570:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221211   154000    154959  1670744999  17164.3  17172.6
2022-12-11 15:50:00,772:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2312 

self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17172.7', self.close='17173.4'
2022-12-11 16:00:01,128:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17172.7', self.close='17173.4'
2022-12-11 16:00:01,155:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221211   151000    151959  1670743199  17158.9  17152.5
17516  20221211   152000    152959  1670743799  17152.5    17167
17517  20221211   153000    153959  1670744399  17166.9  17164.3
17518  20221211   154000    154959  1670744999  17164.3  17172.6
17519  20221211   155000    155959  1670745599  17172.7  17173.4
2022-12-11 16:00:01,155:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2313 

self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17173.4', self.close='17163.8'
2022-12-11 16:10:01,556:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17173.4', self.close='17163.8'
127.0.0.1 - - [11/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-11 16:10:01,574:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221211   152000    152959  1670743799  17152.5    17167
17517  20221211   153000    153959  1670744399  17166.9  17164.3
17518  20221211   154000    154959  1670744999  17164.3  17172.6
17519  20221211   155000    155959  1670745599  17172.7  17173.4
17520  20221211   160000    160959  1670746199  17173.4  17163.8
2022-12-11 16:10:01,575:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221211   154000    154959  1670744999  17164.3  17172.6
2022-12-11 15:50:00,782:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2312 

self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17172.7', self.close='17173.4'
2022-12-11 16:00:01,164:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17172.7', self.close='17173.4'
2022-12-11 16:00:01,207:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221211   151000    151959  1670743199  17158.9  17152.5
12188  20221211   152000    152959  1670743799  17152.5    17167
12189  20221211   153000    153959  1670744399  17166.9  17164.3
12190  20221211   154000    154959  1670744999  17164.3  17172.6
12191  20221211   155000    155959  1670745599  17172.7  17173.4
2022-12-11 16:00:01,207:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2313 

self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17173.4', self.close='17163.8'
2022-12-11 16:10:01,548:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17173.4', self.close='17163.8'
2022-12-11 16:10:01,573:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221211   152000    152959  1670743799  17152.5    17167
12189  20221211   153000    153959  1670744399  17166.9  17164.3
12190  20221211   154000    154959  1670744999  17164.3  17172.6
12191  20221211   155000    155959  1670745599  17172.7  17173.4
12192  20221211   160000    160959  1670746199  17173.4  17163.8
2022-12-11 16:10:01,575:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=56
self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17173.5, self.close=17163.8, self.high=17175.6, self.low=17163.7, self.vol=561.401, self.amt=9639978.3427 
127.0.0.1 - - [11/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-11 16:10:01,500:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221211   154500    154959  ...    0.545029   0.124152       0
5950  20221211   155000    155459  ...    0.545073   0.124166       0
5951  20221211   155500    155959  ...    0.545127   0.124180       0
5952  20221211   160000    160459  ...    0.545189   0.124200       0
5953  20221211   160500    160959  ...    0.545271   0.124216       0

[5 rows x 18 columns]
2022-12-11 16:10:01,500:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670746199, self.tradeDate='20221211', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17173.5, self.close=17163.8, self.high=17175.6, self.low=17163.7, self.vol=561.401, self.amt=9639978.3427, ukdf['pct'].iloc[-1]=-0.000559 , ukdf['amount'].iloc[-1]=9639978.3427, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.647756112438533, value_mean=0.5452709381893684, signal=0, value_std=0.12421555386571775 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=57
self.closeSec=1670746499, self.tradeDate='20221211', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17163.8, self.close=17161.2, self.high=17166.3, self.low=17161.1, self.vol=419.626, self.amt=7201838.4402 
127.0.0.1 - - [11/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-11 16:15:00,621:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221211   155000    155459  ...    0.545073   0.124166       0
5951  20221211   155500    155959  ...    0.545127   0.124180       0
5952  20221211   160000    160459  ...    0.545189   0.124200       0
5953  20221211   160500    160959  ...    0.545271   0.124216       0
5954  20221211   161000    161459  ...    0.545353   0.124232       0

[5 rows x 18 columns]
2022-12-11 16:15:00,624:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1670746499, self.tradeDate='20221211', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17163.8, self.close=17161.2, self.high=17166.3, self.low=17161.1, self.vol=419.626, self.amt=7201838.4402, ukdf['pct'].iloc[-1]=-0.000151 , ukdf['amount'].iloc[-1]=7201838.4402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.6488709369827739, value_mean=0.5453532873418868, signal=0, value_std=0.1242317975792826 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221211   040000    075959  1670716799  ...    721  0.540221  0.120987     NaN
722  20221211   080000    115959  1670731199  ...    722  0.528735  0.081942     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-8931.1815556101', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17149.14795545', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [11/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=96
self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17147.6, self.close=17173.4, self.high=17189.0, self.low=17144.7, self.vol=18948.471, self.amt=325247046.4014 
2022-12-11 16:00:01,006:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670745599, self.tradeDate='20221211', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17147.6, self.close=17173.4, self.high=17189.0, self.low=17144.7, self.vol=18948.471, self.amt=325247046.4014 
2022-12-11 16:00:01,066:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221210   200000    235959  ...  36351.612  6.241564e+08  0.002354
720  20221211   000000    035959  ...  20946.808  3.598371e+08 -0.001977
721  20221211   040000    075959  ...  26181.427  4.484955e+08 -0.002697
722  20221211   080000    115959  ...  16510.061  2.829950e+08  0.001618
723  20221211   120000    155959  ...  18948.471  3.252470e+08  0.001499

[5 rows x 11 columns]
2022-12-11 16:00:02,519:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221210   200000    235959  1670687999  ...    719  0.552818  0.166990     NaN
720  20221211   000000    035959  1670702399  ...    720  0.545006  0.137279     NaN
721  20221211   040000    075959  1670716799  ...    721  0.540221  0.120987     NaN
722  20221211   080000    115959  1670731199  ...    722  0.528735  0.081942     NaN
723  20221211   120000    155959  1670745599  ...    723  0.516006  0.036525     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-7509.4782', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17173.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


