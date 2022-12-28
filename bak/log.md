# 20221228 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [28/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8858
self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16703.1, self.close=16691.1, self.high=16704.8, self.low=16689.4, self.vol=411.342, self.amt=6867561.7812 
2022-12-28 08:10:01,519:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221228   074500    074959  ...         0.0        0.0       0
5854  20221228   075000    075459  ...         0.0        0.0       0
5855  20221228   075500    075959  ...         0.0        0.0       0
5856  20221228   080000    080459  ...         0.0        0.0       0
5857  20221228   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 08:10:01,519:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16703.1, self.close=16691.1, self.high=16704.8, self.low=16689.4, self.vol=411.342, self.amt=6867561.7812, ukdf['pct'].iloc[-1]=-0.000712 , ukdf['amount'].iloc[-1]=6867561.7812, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9754.08411526672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16691.39259697', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=8859
self.closeSec=1672186499, self.tradeDate='20221228', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16691.1, self.close=16691.5, self.high=16691.8, self.low=16686.0, self.vol=300.049, self.amt=5007547.3449 
2022-12-28 08:15:00,683:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221228   075000    075459  ...         0.0        0.0       0
5855  20221228   075500    075959  ...         0.0        0.0       0
5856  20221228   080000    080459  ...         0.0        0.0       0
5857  20221228   080500    080959  ...         0.0        0.0       0
5858  20221228   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 08:15:00,683:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1672186499, self.tradeDate='20221228', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16691.1, self.close=16691.5, self.high=16691.8, self.low=16686.0, self.vol=300.049, self.amt=5007547.3449, ukdf['pct'].iloc[-1]=2.4e-05 , ukdf['amount'].iloc[-1]=5007547.3449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-9760.5472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16691.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16703.1, self.close=16691.1, self.high=16704.8, self.low=16689.4 
2022-12-28 08:10:01,451:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16703.1, self.close=16691.1, self.high=16704.8, self.low=16689.4   
127.0.0.1 - - [28/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-28 08:10:01,497:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221228   074500    074959  1672184999  ...  16686.5  0.000330   1533    3
1534  20221228   075000    075459  1672185299  ...  16692.7  0.000437   1534    4
1535  20221228   075500    075959  1672185599  ...  16697.6 -0.000120   1535    5
1536  20221228   080000    080459  1672185899  ...  16684.5  0.000293   1536    0
1537  20221228   080500    080959  1672186199  ...  16689.4 -0.000712   1537    1

[5 rows x 11 columns]
2022-12-28 08:10:01,499:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6484106912092734, self.count=9425 

self.closeSec=1672186499, self.tradeDate='20221228', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16691.1, self.close=16691.5, self.high=16691.8, self.low=16686.0 
2022-12-28 08:15:00,570:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1672186499, self.tradeDate='20221228', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16691.1, self.close=16691.5, self.high=16691.8, self.low=16686.0   
127.0.0.1 - - [28/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-28 08:15:00,648:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221228   075000    075459  1672185299  ...  16692.7  0.000437   1534    4
1535  20221228   075500    075959  1672185599  ...  16697.6 -0.000120   1535    5
1536  20221228   080000    080459  1672185899  ...  16684.5  0.000293   1536    0
1537  20221228   080500    080959  1672186199  ...  16689.4 -0.000712   1537    1
1538  20221228   081000    081459  1672186499  ...  16686.0  0.000024   1538    2

[5 rows x 11 columns]
2022-12-28 08:15:00,648:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-28 08:00:17,940:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221228    052959  16658.4  ...  44.166667  0.395106  0.744178
5771  20221228    055959  16655.5  ...  44.583333  0.427671  0.736059
5772  20221228    062959  16696.4  ...  44.166667  0.424811  0.729565
5773  20221228    065959  16691.3  ...  44.166667  0.419487  0.725516
5774  20221228    072959  16682.1  ...  44.166667  0.440937  0.715698

[5 rows x 33 columns]
0.5101663585951941
acc is : 0.5101663585951941
2022-12-28 08:00:18,035:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498969  0.501031       1  ...  0.988042   1.0    0.0  0.994336
537     0  0.509867  0.490133       0  ...  0.987746   1.0    0.0  0.994039
538     1  0.497469  0.502531       0  ...  0.987196   1.0    0.0  0.993485
539     1  0.495717  0.504283       1  ...  0.988847   1.0    0.0  0.995146
540     0  0.508214  0.491786       0  ...  0.988154   1.0    0.0  0.994450

[5 rows x 10 columns]
2022-12-28 08:00:18,054:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498257  0.501743       1  ...  0.988042   1.0    0.0  0.984347
46     0  0.509993  0.490007       0  ...  0.987746   1.0    0.0  0.989982
47     1  0.497318  0.502682       0  ...  0.987196   1.0    0.0  0.992876
48     1  0.495773  0.504227       1  ...  0.988847   1.0    0.0  0.995146
49     0  0.508214  0.491786       0  ...  0.988154   1.0    0.0  0.994450

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '-99.69673138272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16699.15573901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221228   074000    074959  1672184999  16699.4  16692.8 -0.000395
2022-12-28 07:50:00,575:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4711 

self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16692.9', self.close='16698.2'
2022-12-28 08:00:01,211:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16692.9', self.close='16698.2'
127.0.0.1 - - [28/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-28 08:00:01,243:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221228   071000    071959  1672183199  16696.4  16695.9 -0.000030
620  20221228   072000    072959  1672183799    16696  16710.3  0.000862
621  20221228   073000    073959  1672184399    16710  16699.4 -0.000652
622  20221228   074000    074959  1672184999  16699.4  16692.8 -0.000395
623  20221228   075000    075959  1672185599  16692.9  16698.2  0.000323
2022-12-28 08:00:01,243:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4712 

self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16698.2', self.close='16691.1'
2022-12-28 08:10:01,548:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16698.2', self.close='16691.1'
127.0.0.1 - - [28/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-28 08:10:01,561:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221228   072000    072959  1672183799    16696  16710.3  0.000862
621  20221228   073000    073959  1672184399    16710  16699.4 -0.000652
622  20221228   074000    074959  1672184999  16699.4  16692.8 -0.000395
623  20221228   075000    075959  1672185599  16692.9  16698.2  0.000323
624  20221228   080000    080959  1672186199  16698.2  16691.1 -0.000425
2022-12-28 08:10:01,561:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221228   074000    074959  1672184999  16699.4  16692.8
2022-12-28 07:50:00,582:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4712 

self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16692.9', self.close='16698.2'
127.0.0.1 - - [28/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-28 08:00:01,213:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16692.9', self.close='16698.2'
2022-12-28 08:00:01,249:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221228   071000    071959  1672183199  16696.4  16695.9
17468  20221228   072000    072959  1672183799    16696  16710.3
17469  20221228   073000    073959  1672184399    16710  16699.4
17470  20221228   074000    074959  1672184999  16699.4  16692.8
17471  20221228   075000    075959  1672185599  16692.9  16698.2
2022-12-28 08:00:01,249:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4713 

self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16698.2', self.close='16691.1'
2022-12-28 08:10:01,543:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16698.2', self.close='16691.1'
127.0.0.1 - - [28/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-28 08:10:01,563:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221228   072000    072959  1672183799    16696  16710.3
17469  20221228   073000    073959  1672184399    16710  16699.4
17470  20221228   074000    074959  1672184999  16699.4  16692.8
17471  20221228   075000    075959  1672185599  16692.9  16698.2
17472  20221228   080000    080959  1672186199  16698.2  16691.1
2022-12-28 08:10:01,563:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221228   074000    074959  1672184999  16699.4  16692.8
2022-12-28 07:50:00,579:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4712 

self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16692.9', self.close='16698.2'
127.0.0.1 - - [28/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-28 08:00:01,211:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16692.9', self.close='16698.2'
2022-12-28 08:00:01,240:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221228   071000    071959  1672183199  16696.4  16695.9
12140  20221228   072000    072959  1672183799    16696  16710.3
12141  20221228   073000    073959  1672184399    16710  16699.4
12142  20221228   074000    074959  1672184999  16699.4  16692.8
12143  20221228   075000    075959  1672185599  16692.9  16698.2
2022-12-28 08:00:01,241:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4713 

self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16698.2', self.close='16691.1'
2022-12-28 08:10:01,553:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16698.2', self.close='16691.1'
2022-12-28 08:10:01,586:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221228   072000    072959  1672183799    16696  16710.3
12141  20221228   073000    073959  1672184399    16710  16699.4
12142  20221228   074000    074959  1672184999  16699.4  16692.8
12143  20221228   075000    075959  1672185599  16692.9  16698.2
12144  20221228   080000    080959  1672186199  16698.2  16691.1
2022-12-28 08:10:01,588:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4856
self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16703.1, self.close=16691.1, self.high=16704.8, self.low=16689.4, self.vol=411.342, self.amt=6867561.7812 
127.0.0.1 - - [28/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-28 08:10:01,511:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221228   074500    074959  ...         0.0        0.0       0
5854  20221228   075000    075459  ...         0.0        0.0       0
5855  20221228   075500    075959  ...         0.0        0.0       0
5856  20221228   080000    080459  ...         0.0        0.0       0
5857  20221228   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 08:10:01,512:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672186199, self.tradeDate='20221228', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16703.1, self.close=16691.1, self.high=16704.8, self.low=16689.4, self.vol=411.342, self.amt=6867561.7812, ukdf['pct'].iloc[-1]=-0.000712 , ukdf['amount'].iloc[-1]=6867561.7812, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [28/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=4857
self.closeSec=1672186499, self.tradeDate='20221228', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16691.1, self.close=16691.5, self.high=16691.8, self.low=16686.0, self.vol=300.049, self.amt=5007547.3449 
2022-12-28 08:15:00,683:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221228   075000    075459  ...         0.0        0.0       0
5855  20221228   075500    075959  ...         0.0        0.0       0
5856  20221228   080000    080459  ...         0.0        0.0       0
5857  20221228   080500    080959  ...         0.0        0.0       0
5858  20221228   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-28 08:15:00,683:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1672186499, self.tradeDate='20221228', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16691.1, self.close=16691.5, self.high=16691.8, self.low=16686.0, self.vol=300.049, self.amt=5007547.3449, ukdf['pct'].iloc[-1]=2.4e-05 , ukdf['amount'].iloc[-1]=5007547.3449, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221227   200000    235959  1672156799  ...    719  0.000625 -0.966176    -1.0
720  20221228   000000    035959  1672171199  ...    720  0.052460 -0.853560    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '2236.2868', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16681.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [28/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=196
self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16681.3, self.close=16698.2, self.high=16714.1, self.low=16646.3, self.vol=29295.519, self.amt=488666131.1375 
2022-12-28 08:00:01,076:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1672185599, self.tradeDate='20221228', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16681.3, self.close=16698.2, self.high=16714.1, self.low=16646.3, self.vol=29295.519, self.amt=488666131.1375 
2022-12-28 08:00:01,110:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221227   120000    155959  ...  15232.900  2.569441e+08 -0.000504
718  20221227   160000    195959  ...  30792.583  5.184878e+08 -0.002135
719  20221227   200000    235959  ...  66673.069  1.119302e+09 -0.001956
720  20221228   000000    035959  ...  78151.443  1.303535e+09 -0.006516
721  20221228   040000    075959  ...  29295.519  4.886661e+08  0.001013

[5 rows x 11 columns]
2022-12-28 08:00:02,454:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221227   120000    155959  1672127999  ...    717  0.000190 -0.986887    -1.0
718  20221227   160000    195959  1672142399  ...    718  0.000242 -0.975139    -1.0
719  20221227   200000    235959  1672156799  ...    719  0.000625 -0.966176    -1.0
720  20221228   000000    035959  1672171199  ...    720  0.052460 -0.853560    -1.0
721  20221228   040000    075959  1672185599  ...    721  0.131348 -0.681255    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '1250.64293069848', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16699.66743366', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


