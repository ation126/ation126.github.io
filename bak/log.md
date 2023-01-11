# 20230111 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12986
self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17436.4, self.close=17431.7, self.high=17437.1, self.low=17431.7, self.vol=410.593, self.amt=7158529.8613 
127.0.0.1 - - [11/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 16:10:01,526:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230111   154500    154959  ...         0.0        0.0       0
5950  20230111   155000    155459  ...         0.0        0.0       0
5951  20230111   155500    155959  ...         0.0        0.0       0
5952  20230111   160000    160459  ...         0.0        0.0       0
5953  20230111   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 16:10:01,528:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17436.4, self.close=17431.7, self.high=17437.1, self.low=17431.7, self.vol=410.593, self.amt=7158529.8613, ukdf['pct'].iloc[-1]=-0.000264 , ukdf['amount'].iloc[-1]=7158529.8613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-54347.27160459136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17432.43865336', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12987
self.closeSec=1673424899, self.tradeDate='20230111', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17431.7, self.close=17432.7, self.high=17435.0, self.low=17431.4, self.vol=383.309, self.amt=6682330.8758 
127.0.0.1 - - [11/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
2023-01-11 16:15:00,617:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230111   155000    155459  ...         0.0        0.0       0
5951  20230111   155500    155959  ...         0.0        0.0       0
5952  20230111   160000    160459  ...         0.0        0.0       0
5953  20230111   160500    160959  ...         0.0        0.0       0
5954  20230111   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 16:15:00,618:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673424899, self.tradeDate='20230111', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17431.7, self.close=17432.7, self.high=17435.0, self.low=17431.4, self.vol=383.309, self.amt=6682330.8758, ukdf['pct'].iloc[-1]=5.7e-05 , ukdf['amount'].iloc[-1]=6682330.8758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-54402.9696039408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17433.3642383', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17436.4, self.close=17431.7, self.high=17437.1, self.low=17431.7 
2023-01-11 16:10:01,455:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17436.4, self.close=17431.7, self.high=17437.1, self.low=17431.7   
127.0.0.1 - - [11/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 16:10:01,499:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20230111   154500    154959  1673423399  ...  17431.4 -0.000350   1629    3
1630  20230111   155000    155459  1673423699  ...  17431.7  0.000316   1630    4
1631  20230111   155500    155959  1673423999  ...  17433.7 -0.000011   1631    5
1632  20230111   160000    160459  1673424299  ...  17435.2 -0.000040   1632    0
1633  20230111   160500    160959  1673424599  ...  17431.7 -0.000264   1633    1

[5 rows x 11 columns]
2023-01-11 16:10:01,499:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=175, self.factor=0.3347836913154511, self.count=13553 

self.closeSec=1673424899, self.tradeDate='20230111', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17431.7, self.close=17432.7, self.high=17435.0, self.low=17431.4 
2023-01-11 16:15:00,556:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673424899, self.tradeDate='20230111', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17431.7, self.close=17432.7, self.high=17435.0, self.low=17431.4   
2023-01-11 16:15:00,600:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20230111   155000    155459  1673423699  ...  17431.7  0.000316   1630    4
1631  20230111   155500    155959  1673423999  ...  17433.7 -0.000011   1631    5
1632  20230111   160000    160459  1673424299  ...  17435.2 -0.000040   1632    0
1633  20230111   160500    160959  1673424599  ...  17431.7 -0.000264   1633    1
1634  20230111   161000    161459  1673424899  ...  17431.4  0.000057   1634    2

[5 rows x 11 columns]
2023-01-11 16:15:00,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-11 16:00:19,913:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230111    132959  17401.3  ...  53.750000  0.582381  0.271092
5787  20230111    135959  17410.9  ...  53.750000  0.574101  0.275888
5788  20230111    142959  17398.7  ...  54.166667  0.583123  0.276260
5789  20230111    145959  17416.8  ...  54.583333  0.588162  0.274284
5790  20230111    152959  17427.1  ...  54.583333  0.595381  0.269079

[5 rows x 33 columns]
0.5498154981549815
acc is : 0.5498154981549815
2023-01-11 16:00:20,021:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
537     0  0.508580  0.491420       0  ...  NaN   NaN -0.0016  1.049753
538     1  0.499739  0.500261       1  ...  NaN   NaN -0.0016  1.050851
539     0  0.507868  0.492132       1  ...  NaN   NaN -0.0016  1.051472
540     0  0.508268  0.491732       1  ...  NaN   NaN -0.0016  1.052371
541     0  0.510994  0.489006       0  ...  NaN   NaN -0.0016  1.052076

[5 rows x 10 columns]
2023-01-11 16:00:20,043:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.506822  0.493178       0  ...  NaN   NaN -0.0016  1.049373
46     1  0.499567  0.500433       1  ...  NaN   NaN -0.0016  1.049749
47     0  0.507568  0.492432       1  ...  NaN   NaN -0.0016  1.049749
48     0  0.508115  0.491885       1  ...  NaN   NaN -0.0016  1.051401
49     0  0.510994  0.489006       0  ...  NaN   NaN -0.0016  1.052076

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '31300.608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17437.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20230111   154000    154959  1673423399  17433.5  17431.7 -0.000109
2023-01-11 15:50:00,590:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6775 

self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17431.7', self.close='17437'
127.0.0.1 - - [11/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-11 16:00:00,955:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17431.7', self.close='17437'
2023-01-11 16:00:01,025:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20230111   151000    151959  1673421599  17425.3  17429.2  0.000224
524  20230111   152000    152959  1673422199  17429.1    17442  0.000734
525  20230111   153000    153959  1673422799    17442  17433.6 -0.000482
526  20230111   154000    154959  1673423399  17433.5  17431.7 -0.000109
527  20230111   155000    155959  1673423999  17431.7    17437  0.000304
2023-01-11 16:00:01,025:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6776 

self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17437.1', self.close='17431.7'
2023-01-11 16:10:01,555:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17437.1', self.close='17431.7'
2023-01-11 16:10:01,604:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230111   152000    152959  1673422199  17429.1    17442  0.000734
525  20230111   153000    153959  1673422799    17442  17433.6 -0.000482
526  20230111   154000    154959  1673423399  17433.5  17431.7 -0.000109
527  20230111   155000    155959  1673423999  17431.7    17437  0.000304
528  20230111   160000    160959  1673424599  17437.1  17431.7 -0.000304
2023-01-11 16:10:01,605:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20230111   154000    154959  1673423399  17433.5  17431.7
2023-01-11 15:50:00,602:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6776 

self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17431.7', self.close='17437'
127.0.0.1 - - [11/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-11 16:00:00,937:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17431.7', self.close='17437'
2023-01-11 16:00:00,994:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20230111   151000    151959  1673421599  17425.3  17429.2
17516  20230111   152000    152959  1673422199  17429.1    17442
17517  20230111   153000    153959  1673422799    17442  17433.6
17518  20230111   154000    154959  1673423399  17433.5  17431.7
17519  20230111   155000    155959  1673423999  17431.7    17437
2023-01-11 16:00:01,006:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6777 

self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17437.1', self.close='17431.7'
127.0.0.1 - - [11/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 16:10:01,588:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17437.1', self.close='17431.7'
2023-01-11 16:10:01,608:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230111   152000    152959  1673422199  17429.1    17442
17517  20230111   153000    153959  1673422799    17442  17433.6
17518  20230111   154000    154959  1673423399  17433.5  17431.7
17519  20230111   155000    155959  1673423999  17431.7    17437
17520  20230111   160000    160959  1673424599  17437.1  17431.7
2023-01-11 16:10:01,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20230111   154000    154959  1673423399  17433.5  17431.7
2023-01-11 15:50:00,587:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6776 

self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='17431.7', self.close='17437'
2023-01-11 16:00:00,988:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='17431.7', self.close='17437'
2023-01-11 16:00:01,033:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20230111   151000    151959  1673421599  17425.3  17429.2
12188  20230111   152000    152959  1673422199  17429.1    17442
12189  20230111   153000    153959  1673422799    17442  17433.6
12190  20230111   154000    154959  1673423399  17433.5  17431.7
12191  20230111   155000    155959  1673423999  17431.7    17437
2023-01-11 16:00:01,035:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6777 

self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='17437.1', self.close='17431.7'
127.0.0.1 - - [11/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 16:10:01,598:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='17437.1', self.close='17431.7'
2023-01-11 16:10:01,620:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230111   152000    152959  1673422199  17429.1    17442
12189  20230111   153000    153959  1673422799    17442  17433.6
12190  20230111   154000    154959  1673423399  17433.5  17431.7
12191  20230111   155000    155959  1673423999  17431.7    17437
12192  20230111   160000    160959  1673424599  17437.1  17431.7
2023-01-11 16:10:01,620:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [11/Jan/2023 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8984
self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=17436.4, self.close=17431.7, self.high=17437.1, self.low=17431.7, self.vol=410.593, self.amt=7158529.8613 
2023-01-11 16:10:01,523:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20230111   154500    154959  ...         0.0        0.0       0
5950  20230111   155000    155459  ...         0.0        0.0       0
5951  20230111   155500    155959  ...         0.0        0.0       0
5952  20230111   160000    160459  ...         0.0        0.0       0
5953  20230111   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 16:10:01,525:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673424599, self.tradeDate='20230111', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=17436.4, self.close=17431.7, self.high=17437.1, self.low=17431.7, self.vol=410.593, self.amt=7158529.8613, ukdf['pct'].iloc[-1]=-0.000264 , ukdf['amount'].iloc[-1]=7158529.8613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/Jan/2023 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8985
self.closeSec=1673424899, self.tradeDate='20230111', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=17431.7, self.close=17432.7, self.high=17435.0, self.low=17431.4, self.vol=383.309, self.amt=6682330.8758 
2023-01-11 16:15:00,613:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20230111   155000    155459  ...         0.0        0.0       0
5951  20230111   155500    155959  ...         0.0        0.0       0
5952  20230111   160000    160459  ...         0.0        0.0       0
5953  20230111   160500    160959  ...         0.0        0.0       0
5954  20230111   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 16:15:00,613:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673424899, self.tradeDate='20230111', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=17431.7, self.close=17432.7, self.high=17435.0, self.low=17431.4, self.vol=383.309, self.amt=6682330.8758, ukdf['pct'].iloc[-1]=5.7e-05 , ukdf['amount'].iloc[-1]=6682330.8758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230111   040000    075959  1673395199  ...    721  1.158436  2.281776     1.0
722  20230111   080000    115959  1673409599  ...    722  1.230810  2.418932     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '11229.4656', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17407.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=282
self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17407.7, self.close=17437.0, self.high=17456.0, self.low=17380.0, self.vol=25910.727, self.amt=451201938.7167 
2023-01-11 16:00:00,838:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673423999, self.tradeDate='20230111', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17407.7, self.close=17437.0, self.high=17456.0, self.low=17380.0, self.vol=25910.727, self.amt=451201938.7167 
127.0.0.1 - - [11/Jan/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-01-11 16:00:00,876:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230110   200000    235959  ...  92789.110  1.603150e+09  0.004204
720  20230111   000000    035959  ...  73563.359  1.278025e+09  0.006190
721  20230111   040000    075959  ...  48167.989  8.401772e+08  0.000264
722  20230111   080000    115959  ...  42391.318  7.389567e+08 -0.001211
723  20230111   120000    155959  ...  25910.727  4.512019e+08  0.001683

[5 rows x 11 columns]
2023-01-11 16:00:02,538:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230110   200000    235959  1673366399  ...    719  0.916099  1.636005     1.0
720  20230111   000000    035959  1673380799  ...    720  1.118817  2.235224     1.0
721  20230111   040000    075959  1673395199  ...    721  1.158436  2.281776     1.0
722  20230111   080000    115959  1673409599  ...    722  1.230810  2.418932     1.0
723  20230111   120000    155959  1673423999  ...    723  1.161141  2.127499     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '12771.91955619008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17437.96375853', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


