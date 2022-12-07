# 20221207 16:44:57

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [07/Dec/2022 16:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2911
self.closeSec=1670402099, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=16780.9, self.close=16789.5, self.high=16790.1, self.low=16772.7, self.vol=2291.386, self.amt=38455399.0401 
2022-12-07 16:35:00,673:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5954  20221207   161000    161459  ...    0.154061   0.288663       0
5955  20221207   161500    161959  ...    0.153856   0.288510       0
5956  20221207   162000    162459  ...    0.153663   0.288380       0
5957  20221207   162500    162959  ...    0.153467   0.288245       0
5958  20221207   163000    163459  ...    0.153270   0.288107       0

[5 rows x 18 columns]
2022-12-07 16:35:00,674:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670402099, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=16780.9, self.close=16789.5, self.high=16790.1, self.low=16772.7, self.vol=2291.386, self.amt=38455399.0401, ukdf['pct'].iloc[-1]=0.000512 , ukdf['amount'].iloc[-1]=38455399.0401, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5958, value=0.0, value_mean=0.15327007645341686, signal=0, value_std=0.2881070982452443 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-15687.8832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16790', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Dec/2022 16:40:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=2912
self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163500', self.closeTime='163959', self.symbol='BTCUSDT', self.open=16789.5, self.close=16796.6, self.high=16803.8, self.low=16775.7, self.vol=2354.642, self.amt=39539396.9176 
2022-12-07 16:40:01,501:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5955  20221207   161500    161959  ...    0.153856   0.288510       0
5956  20221207   162000    162459  ...    0.153663   0.288380       0
5957  20221207   162500    162959  ...    0.153467   0.288245       0
5958  20221207   163000    163459  ...    0.153270   0.288107       0
5959  20221207   163500    163959  ...    0.153073   0.287969       0

[5 rows x 18 columns]
2022-12-07 16:40:01,507:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163500', self.closeTime='163959',self.symbol='BTCUSDT',self.open=16789.5, self.close=16796.6, self.high=16803.8, self.low=16775.7, self.vol=2354.642, self.amt=39539396.9176, ukdf['pct'].iloc[-1]=0.000423 , ukdf['amount'].iloc[-1]=39539396.9176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5959, value=0.0, value_mean=0.1530728958775874, signal=0, value_std=0.28796898495642964 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-16085.0448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16796.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=17, self.factor=0.5864739975523741, self.count=3477 

self.closeSec=1670402099, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163459', self.symbol='BTCUSDT', self.open=16780.9, self.close=16789.5, self.high=16790.1, self.low=16772.7 
2022-12-07 16:35:00,649:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670402099, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163459',self.symbol='BTCUSDT',self.open=16780.9, self.close=16789.5, self.high=16790.1, self.low=16772.7   
2022-12-07 16:35:00,668:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1634  20221207   161000    161459  1670400899  ...  16742.7  0.000609   1634    2
1635  20221207   161500    161959  1670401199  ...  16749.8 -0.000501   1635    3
1636  20221207   162000    162459  1670401499  ...  16740.2 -0.000465   1636    4
1637  20221207   162500    162959  1670401799  ...  16748.1  0.001851   1637    5
1638  20221207   163000    163459  1670402099  ...  16772.7  0.000512   1638    0

[5 rows x 11 columns]
2022-12-07 16:35:00,668:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=17, self.factor=0.5864739975523741, self.count=3478 

self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163500', self.closeTime='163959', self.symbol='BTCUSDT', self.open=16789.5, self.close=16796.6, self.high=16803.8, self.low=16775.7 
127.0.0.1 - - [07/Dec/2022 16:40:01] "POST / HTTP/1.1" 200 -
2022-12-07 16:40:01,405:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163500', self.closeTime='163959',self.symbol='BTCUSDT',self.open=16789.5, self.close=16796.6, self.high=16803.8, self.low=16775.7   
2022-12-07 16:40:01,444:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1635  20221207   161500    161959  1670401199  ...  16749.8 -0.000501   1635    3
1636  20221207   162000    162459  1670401499  ...  16740.2 -0.000465   1636    4
1637  20221207   162500    162959  1670401799  ...  16748.1  0.001851   1637    5
1638  20221207   163000    163459  1670402099  ...  16772.7  0.000512   1638    0
1639  20221207   163500    163959  1670402399  ...  16775.7  0.000423   1639    1

[5 rows x 11 columns]
2022-12-07 16:40:01,444:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-07 16:30:32,251:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5787  20221207    135959  16988.9  ...  51.666667  0.487198  0.497217
5788  20221207    142959  16997.3  ...  51.250000  0.480495  0.506399
5789  20221207    145959  16983.9  ...  51.250000  0.462090  0.526065
5790  20221207    152959  16945.7  ...  50.833333  0.404902  0.543367
5791  20221207    155959  16807.3  ...  50.416667  0.386729  0.567871

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2022-12-07 16:30:32,408:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485311  0.514689       0  ...  0.939028  -1.0    0.0  1.019368
538     1  0.479713  0.520287       0  ...  0.941146  -1.0    0.0  1.017070
539     1  0.470241  0.529759       0  ...  0.948833  -1.0    0.0  1.008763
540     1  0.434314  0.565686       0  ...  0.951740  -1.0    0.0  1.005672
541     1  0.450379  0.549621       1  ...  0.950371  -1.0    0.0  1.007118

[5 rows x 10 columns]
2022-12-07 16:30:32,439:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485296  0.514704       0  ...  0.939028  -1.0    0.0  1.025041
46     1  0.480138  0.519862       0  ...  0.941146  -1.0    0.0  1.026005
47     1  0.471053  0.528947       0  ...  0.970343  -1.0    0.0  1.017835
48     1  0.434262  0.565738       0  ...  0.951740  -1.0    0.0  1.011170
49     1  0.450379  0.549621       1  ...  0.950371  -1.0    0.0  1.007118

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.92', 'enterprice': '16964.2', 'countrevence': '0', 'unrealprofit': '7036.6009919688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16783.40346886', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

529  20221207   161000    161959  1670401199  16755.8  16757.8  0.000048
2022-12-07 16:20:00,618:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1738 

self.closeSec=1670401799, self.tradeDate='20221207', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='16756', self.close='16779.8'
2022-12-07 16:30:00,767:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670401799, self.tradeDate='20221207', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='16756', self.close='16779.8'
127.0.0.1 - - [07/Dec/2022 16:30:00] "POST / HTTP/1.1" 200 -
2022-12-07 16:30:00,813:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
526  20221207   154000    154959  1670399399    16754  16765.1  0.000657
527  20221207   155000    155959  1670399999  16765.1  16755.4 -0.000579
528  20221207   160000    160959  1670400599  16755.4    16757  0.000095
529  20221207   161000    161959  1670401199  16755.8  16757.8  0.000048
530  20221207   162000    162959  1670401799    16756  16779.8  0.001313
2022-12-07 16:30:00,813:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [07/Dec/2022 16:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1739 

self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163959', self.symbol='BTCUSDT', self.open='16780.9', self.close='16796.5'
2022-12-07 16:40:01,543:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163959',self.symbol='BTCUSDT',self.open='16780.9', self.close='16796.5'
2022-12-07 16:40:01,567:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
527  20221207   155000    155959  1670399999  16765.1  16755.4 -0.000579
528  20221207   160000    160959  1670400599  16755.4    16757  0.000095
529  20221207   161000    161959  1670401199  16755.8  16757.8  0.000048
530  20221207   162000    162959  1670401799    16756  16779.8  0.001313
531  20221207   163000    163959  1670402399  16780.9  16796.5  0.000995
2022-12-07 16:40:01,567:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17521  20221207   161000    161959  1670401199  16755.8  16757.8
2022-12-07 16:20:00,619:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1739 

self.closeSec=1670401799, self.tradeDate='20221207', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='16756', self.close='16779.8'
127.0.0.1 - - [07/Dec/2022 16:30:00] "POST / HTTP/1.1" 200 -
2022-12-07 16:30:00,758:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670401799, self.tradeDate='20221207', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='16756', self.close='16779.8'
2022-12-07 16:30:00,809:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17518  20221207   154000    154959  1670399399    16754  16765.1
17519  20221207   155000    155959  1670399999  16765.1  16755.4
17520  20221207   160000    160959  1670400599  16755.4    16757
17521  20221207   161000    161959  1670401199  16755.8  16757.8
17522  20221207   162000    162959  1670401799    16756  16779.8
2022-12-07 16:30:00,811:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1740 

self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163959', self.symbol='BTCUSDT', self.open='16780.9', self.close='16796.5'
127.0.0.1 - - [07/Dec/2022 16:40:01] "POST / HTTP/1.1" 200 -
2022-12-07 16:40:01,538:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163959',self.symbol='BTCUSDT',self.open='16780.9', self.close='16796.5'
2022-12-07 16:40:01,564:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17519  20221207   155000    155959  1670399999  16765.1  16755.4
17520  20221207   160000    160959  1670400599  16755.4    16757
17521  20221207   161000    161959  1670401199  16755.8  16757.8
17522  20221207   162000    162959  1670401799    16756  16779.8
17523  20221207   163000    163959  1670402399  16780.9  16796.5
2022-12-07 16:40:01,564:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12193  20221207   161000    161959  1670401199  16755.8  16757.8
2022-12-07 16:20:00,621:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Dec/2022 16:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1739 

self.closeSec=1670401799, self.tradeDate='20221207', self.openTime='162000', self.closeTime='162959', self.symbol='BTCUSDT', self.open='16756', self.close='16779.8'
2022-12-07 16:30:00,752:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670401799, self.tradeDate='20221207', self.openTime='162000', self.closeTime='162959',self.symbol='BTCUSDT',self.open='16756', self.close='16779.8'
2022-12-07 16:30:00,804:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12190  20221207   154000    154959  1670399399    16754  16765.1
12191  20221207   155000    155959  1670399999  16765.1  16755.4
12192  20221207   160000    160959  1670400599  16755.4    16757
12193  20221207   161000    161959  1670401199  16755.8  16757.8
12194  20221207   162000    162959  1670401799    16756  16779.8
2022-12-07 16:30:00,804:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1740 

self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163959', self.symbol='BTCUSDT', self.open='16780.9', self.close='16796.5'
127.0.0.1 - - [07/Dec/2022 16:40:01] "POST / HTTP/1.1" 200 -
2022-12-07 16:40:01,536:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1670402399, self.tradeDate='20221207', self.openTime='163000', self.closeTime='163959',self.symbol='BTCUSDT',self.open='16780.9', self.close='16796.5'
2022-12-07 16:40:01,562:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12191  20221207   155000    155959  1670399999  16765.1  16755.4
12192  20221207   160000    160959  1670400599  16755.4    16757
12193  20221207   161000    161959  1670401199  16755.8  16757.8
12194  20221207   162000    162959  1670401799    16756  16779.8
12195  20221207   163000    163959  1670402399  16780.9  16796.5
2022-12-07 16:40:01,563:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-16610.74134876276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17018.14662842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [07/Dec/2022 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1013234.284467, self.flagDict['side']='buy', self.tradeCount=4, self.count=72
self.closeSec=1670399999, self.tradeDate='20221207', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=17017.4, self.close=16755.7, self.high=17036.6, self.low=16719.1, self.vol=97327.468, self.amt=1641000514.5662 
2022-12-07 16:00:00,889:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1670399999, self.tradeDate='20221207', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=17017.4, self.close=16755.7, self.high=17036.6, self.low=16719.1, self.vol=97327.468, self.amt=1641000514.5662 
2022-12-07 16:00:00,923:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20221206   200000    235959  ...  69024.422  1.172189e+09  0.000018
720  20221207   000000    035959  ...  56413.953  9.566549e+08 -0.000636
721  20221207   040000    075959  ...  51125.606  8.698549e+08  0.006714
722  20221207   080000    115959  ...  42347.692  7.222808e+08 -0.003548
723  20221207   120000    155959  ...  97327.468  1.641001e+09 -0.015378

[5 rows x 11 columns]
2022-12-07 16:00:02,301:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20221206   200000    235959  1670342399  ...    719  0.716348  1.398787     1.0
720  20221207   000000    035959  1670356799  ...    720  1.120770  3.120988     1.0
721  20221207   040000    075959  1670371199  ...    721  1.096432  2.837693     1.0
722  20221207   080000    115959  1670385599  ...    722  1.084938  2.647182     1.0
723  20221207   120000    155959  1670399999  ...    723  0.702535  1.042009     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '58.622', 'enterprice': '17301.5', 'countrevence': '0', 'unrealprofit': '-32007.63118873926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16755.49967267', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


