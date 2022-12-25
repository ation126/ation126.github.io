# 20221225 16:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [25/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8090
self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16820.8, self.close=16818.0, self.high=16823.7, self.low=16817.9, self.vol=166.512, self.amt=2800990.6775 
2022-12-25 16:10:01,707:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221225   154500    154959  ...         0.0        0.0       0
5950  20221225   155000    155459  ...         0.0        0.0       0
5951  20221225   155500    155959  ...         0.0        0.0       0
5952  20221225   160000    160459  ...         0.0        0.0       0
5953  20221225   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 16:10:01,708:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16820.8, self.close=16818.0, self.high=16823.7, self.low=16817.9, self.vol=166.512, self.amt=2800990.6775, ukdf['pct'].iloc[-1]=-0.000166 , ukdf['amount'].iloc[-1]=2800990.6775, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17444.20539225328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16819.18642303', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8091
self.closeSec=1671956099, self.tradeDate='20221225', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16817.9, self.close=16817.5, self.high=16818.0, self.low=16816.6, self.vol=142.424, self.amt=2395168.3388 
127.0.0.1 - - [25/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
2022-12-25 16:15:00,567:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221225   155000    155459  ...         0.0        0.0       0
5951  20221225   155500    155959  ...         0.0        0.0       0
5952  20221225   160000    160459  ...         0.0        0.0       0
5953  20221225   160500    160959  ...         0.0        0.0       0
5954  20221225   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 16:15:00,568:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671956099, self.tradeDate='20221225', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16817.9, self.close=16817.5, self.high=16818.0, self.low=16816.6, self.vol=142.424, self.amt=2395168.3388, ukdf['pct'].iloc[-1]=-3e-05 , ukdf['amount'].iloc[-1]=2395168.3388, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17417.59628174944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16818.74423494', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16820.8, self.close=16818.0, self.high=16823.7, self.low=16817.9 
127.0.0.1 - - [25/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 16:10:01,660:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16820.8, self.close=16818.0, self.high=16823.7, self.low=16817.9   
2022-12-25 16:10:01,689:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1629  20221225   154500    154959  1671954599  ...  16816.3 -0.000006   1629    3
1630  20221225   155000    155459  1671954899  ...  16815.4 -0.000054   1630    4
1631  20221225   155500    155959  1671955199  ...  16815.0  0.000083   1631    5
1632  20221225   160000    160459  1671955499  ...  16816.7  0.000238   1632    0
1633  20221225   160500    160959  1671955799  ...  16817.9 -0.000166   1633    1

[5 rows x 11 columns]
2022-12-25 16:10:01,706:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=198, self.factor=0.4742841332913733, self.count=8657 

self.closeSec=1671956099, self.tradeDate='20221225', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16817.9, self.close=16817.5, self.high=16818.0, self.low=16816.6 
2022-12-25 16:15:00,560:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671956099, self.tradeDate='20221225', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16817.9, self.close=16817.5, self.high=16818.0, self.low=16816.6   
2022-12-25 16:15:00,591:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1630  20221225   155000    155459  1671954899  ...  16815.4 -0.000054   1630    4
1631  20221225   155500    155959  1671955199  ...  16815.0  0.000083   1631    5
1632  20221225   160000    160459  1671955499  ...  16816.7  0.000238   1632    0
1633  20221225   160500    160959  1671955799  ...  16817.9 -0.000166   1633    1
1634  20221225   161000    161459  1671956099  ...  16816.6 -0.000030   1634    2

[5 rows x 11 columns]
2022-12-25 16:15:00,591:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-25 16:00:17,827:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5786  20221225    132959  16816.1  ...    48.75  0.495708  0.518402
5787  20221225    135959  16814.0  ...    48.75  0.508232  0.516017
5788  20221225    142959  16825.3  ...    48.75  0.494913  0.524916
5789  20221225    145959  16813.1  ...    48.75  0.505600  0.524229
5790  20221225    152959  16822.9  ...    48.75  0.499815  0.528409

[5 rows x 33 columns]
0.5202952029520295
acc is : 0.5202952029520295
2022-12-25 16:00:17,919:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493720  0.506280       1  ...  1.072828   1.0    0.0  0.944286
538     1  0.496552  0.503448       0  ...  1.072063   1.0    0.0  0.943613
539     1  0.491132  0.508868       1  ...  1.072681   1.0    0.0  0.944157
540     1  0.497053  0.502947       0  ...  1.072350   1.0    0.0  0.943865
541     1  0.493894  0.506106       0  ...  1.072292   1.0    0.0  0.943815

[5 rows x 10 columns]
2022-12-25 16:00:17,946:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493745  0.506255       1  ...  1.072828   1.0    0.0  0.946571
46     1  0.496978  0.503022       0  ...  1.072063   1.0    0.0  0.945098
47     1  0.491755  0.508245       1  ...  1.072681   1.0    0.0  0.946324
48     1  0.497942  0.502058       0  ...  1.072350   1.0    0.0  0.946388
49     1  0.493894  0.506106       0  ...  1.072292   1.0    0.0  0.943815

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '4903.4784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16816.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

526  20221225   154000    154959  1671954599  16816.6  16816.3 -0.000024
2022-12-25 15:50:00,585:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4327 

self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16816.4', self.close='16816.8'
127.0.0.1 - - [25/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-25 16:00:01,240:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16816.4', self.close='16816.8'
2022-12-25 16:00:01,300:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
523  20221225   151000    151959  1671952799  16821.5    16816 -0.000321
524  20221225   152000    152959  1671953399  16815.9  16817.7  0.000101
525  20221225   153000    153959  1671953999  16817.7  16816.7 -0.000059
526  20221225   154000    154959  1671954599  16816.6  16816.3 -0.000024
527  20221225   155000    155959  1671955199  16816.4  16816.8  0.000030
2022-12-25 16:00:01,300:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4328 

self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.7', self.close='16818'
2022-12-25 16:10:01,752:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.7', self.close='16818'
2022-12-25 16:10:01,767:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20221225   152000    152959  1671953399  16815.9  16817.7  0.000101
525  20221225   153000    153959  1671953999  16817.7  16816.7 -0.000059
526  20221225   154000    154959  1671954599  16816.6  16816.3 -0.000024
527  20221225   155000    155959  1671955199  16816.4  16816.8  0.000030
528  20221225   160000    160959  1671955799  16816.7    16818  0.000071
2022-12-25 16:10:01,767:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17518  20221225   154000    154959  1671954599  16816.6  16816.3
2022-12-25 15:50:00,593:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4328 

self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16816.4', self.close='16816.8'
2022-12-25 16:00:01,241:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16816.4', self.close='16816.8'
2022-12-25 16:00:01,267:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17515  20221225   151000    151959  1671952799  16821.5    16816
17516  20221225   152000    152959  1671953399  16815.9  16817.7
17517  20221225   153000    153959  1671953999  16817.7  16816.7
17518  20221225   154000    154959  1671954599  16816.6  16816.3
17519  20221225   155000    155959  1671955199  16816.4  16816.8
2022-12-25 16:00:01,267:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4329 

self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.7', self.close='16818'
2022-12-25 16:10:01,767:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.7', self.close='16818'
2022-12-25 16:10:01,773:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20221225   152000    152959  1671953399  16815.9  16817.7
17517  20221225   153000    153959  1671953999  16817.7  16816.7
17518  20221225   154000    154959  1671954599  16816.6  16816.3
17519  20221225   155000    155959  1671955199  16816.4  16816.8
17520  20221225   160000    160959  1671955799  16816.7    16818
2022-12-25 16:10:01,773:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12190  20221225   154000    154959  1671954599  16816.6  16816.3
2022-12-25 15:50:00,589:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4328 

self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='16816.4', self.close='16816.8'
127.0.0.1 - - [25/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-25 16:00:01,281:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='155000', self.closeTime='155959',self.symbol='BTCUSDT',self.open='16816.4', self.close='16816.8'
2022-12-25 16:00:01,322:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12187  20221225   151000    151959  1671952799  16821.5    16816
12188  20221225   152000    152959  1671953399  16815.9  16817.7
12189  20221225   153000    153959  1671953999  16817.7  16816.7
12190  20221225   154000    154959  1671954599  16816.6  16816.3
12191  20221225   155000    155959  1671955199  16816.4  16816.8
2022-12-25 16:00:01,322:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4329 

self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='16816.7', self.close='16818'
2022-12-25 16:10:01,744:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='16816.7', self.close='16818'
127.0.0.1 - - [25/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
2022-12-25 16:10:01,756:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20221225   152000    152959  1671953399  16815.9  16817.7
12189  20221225   153000    153959  1671953999  16817.7  16816.7
12190  20221225   154000    154959  1671954599  16816.6  16816.3
12191  20221225   155000    155959  1671955199  16816.4  16816.8
12192  20221225   160000    160959  1671955799  16816.7    16818
2022-12-25 16:10:01,756:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [25/Dec/2022 16:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4088
self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=16820.8, self.close=16818.0, self.high=16823.7, self.low=16817.9, self.vol=166.512, self.amt=2800990.6775 
2022-12-25 16:10:01,710:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5949  20221225   154500    154959  ...         0.0        0.0       0
5950  20221225   155000    155459  ...         0.0        0.0       0
5951  20221225   155500    155959  ...         0.0        0.0       0
5952  20221225   160000    160459  ...         0.0        0.0       0
5953  20221225   160500    160959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 16:10:01,710:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671955799, self.tradeDate='20221225', self.openTime='160500', self.closeTime='160959',self.symbol='BTCUSDT',self.open=16820.8, self.close=16818.0, self.high=16823.7, self.low=16817.9, self.vol=166.512, self.amt=2800990.6775, ukdf['pct'].iloc[-1]=-0.000166 , ukdf['amount'].iloc[-1]=2800990.6775, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5953, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [25/Dec/2022 16:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4089
self.closeSec=1671956099, self.tradeDate='20221225', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=16817.9, self.close=16817.5, self.high=16818.0, self.low=16816.6, self.vol=142.424, self.amt=2395168.3388 
2022-12-25 16:15:00,611:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5950  20221225   155000    155459  ...         0.0        0.0       0
5951  20221225   155500    155959  ...         0.0        0.0       0
5952  20221225   160000    160459  ...         0.0        0.0       0
5953  20221225   160500    160959  ...         0.0        0.0       0
5954  20221225   161000    161459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-25 16:15:00,612:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671956099, self.tradeDate='20221225', self.openTime='161000', self.closeTime='161459',self.symbol='BTCUSDT',self.open=16817.9, self.close=16817.5, self.high=16818.0, self.low=16816.6, self.vol=142.424, self.amt=2395168.3388, ukdf['pct'].iloc[-1]=-3e-05 , ukdf['amount'].iloc[-1]=2395168.3388, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5954, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221225   040000    075959  1671926399  ...    721  0.016321 -1.231471    -1.0
722  20221225   080000    115959  1671940799  ...    722  0.009877 -1.221246    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5385.2348', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=180
self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=16824.1, self.close=16816.8, self.high=16826.2, self.low=16788.0, self.vol=13041.653, self.amt=219267471.6052 
127.0.0.1 - - [25/Dec/2022 16:00:01] "POST / HTTP/1.1" 200 -
2022-12-25 16:00:01,144:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671955199, self.tradeDate='20221225', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=16824.1, self.close=16816.8, self.high=16826.2, self.low=16788.0, self.vol=13041.653, self.amt=219267471.6052 
2022-12-25 16:00:01,186:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221224   200000    235959  ...  12508.365  2.103864e+08  0.000654
720  20221225   000000    035959  ...  12443.214  2.094663e+08  0.000261
721  20221225   040000    075959  ...  13189.410  2.219239e+08 -0.000339
722  20221225   080000    115959  ...   8339.966  1.403594e+08 -0.000291
723  20221225   120000    155959  ...  13041.653  2.192675e+08 -0.000428

[5 rows x 11 columns]
2022-12-25 16:00:02,440:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221224   200000    235959  1671897599  ...    719  0.002641 -1.316021    -1.0
720  20221225   000000    035959  1671911999  ...    720  0.018419 -1.252596    -1.0
721  20221225   040000    075959  1671926399  ...    721  0.016321 -1.231471    -1.0
722  20221225   080000    115959  1671940799  ...    722  0.009877 -1.221246    -1.0
723  20221225   120000    155959  1671955199  ...    723  0.007733 -1.202113    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5000.9564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16816.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


