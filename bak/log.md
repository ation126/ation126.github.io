# 20230113 11:26:25

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13504
self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111500', self.closeTime='111959', self.symbol='BTCUSDT', self.open=18837.1, self.close=18824.4, self.high=18837.2, self.low=18824.3, self.vol=351.636, self.amt=6620913.476 
127.0.0.1 - - [13/Jan/2023 11:20:00] "POST / HTTP/1.1" 200 -
2023-01-13 11:20:00,453:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5891  20230113   105500    105959  ...         0.0        0.0       0
5892  20230113   110000    110459  ...         0.0        0.0       0
5893  20230113   110500    110959  ...         0.0        0.0       0
5894  20230113   111000    111459  ...         0.0        0.0       0
5895  20230113   111500    111959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 11:20:00,454:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111500', self.closeTime='111959',self.symbol='BTCUSDT',self.open=18837.1, self.close=18824.4, self.high=18837.2, self.low=18824.3, self.vol=351.636, self.amt=6620913.476, ukdf['pct'].iloc[-1]=-0.000674 , ukdf['amount'].iloc[-1]=6620913.476, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5895, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-138171.26299710384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18825.41910059', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Jan/2023 11:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=13505
self.closeSec=1673580299, self.tradeDate='20230113', self.openTime='112000', self.closeTime='112459', self.symbol='BTCUSDT', self.open=18824.4, self.close=18819.9, self.high=18834.6, self.low=18819.4, self.vol=429.76, self.amt=8090957.9267 
2023-01-13 11:25:01,502:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5892  20230113   110000    110459  ...         0.0        0.0       0
5893  20230113   110500    110959  ...         0.0        0.0       0
5894  20230113   111000    111459  ...         0.0        0.0       0
5895  20230113   111500    111959  ...         0.0        0.0       0
5896  20230113   112000    112459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 11:25:01,506:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673580299, self.tradeDate='20230113', self.openTime='112000', self.closeTime='112459',self.symbol='BTCUSDT',self.open=18824.4, self.close=18819.9, self.high=18834.6, self.low=18819.4, self.vol=429.76, self.amt=8090957.9267, ukdf['pct'].iloc[-1]=-0.000239 , ukdf['amount'].iloc[-1]=8090957.9267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5896, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-137966.69023809744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '18822.01952669', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=261, self.factor=0.20755920180830995, self.count=14070 

self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111500', self.closeTime='111959', self.symbol='BTCUSDT', self.open=18837.1, self.close=18824.4, self.high=18837.2, self.low=18824.3 
2023-01-13 11:20:00,409:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111500', self.closeTime='111959',self.symbol='BTCUSDT',self.open=18837.1, self.close=18824.4, self.high=18837.2, self.low=18824.3   
2023-01-13 11:20:00,439:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1571  20230113   105500    105959  1673578799  ...  18815.5  0.000616   1571    5
1572  20230113   110000    110459  1673579099  ...  18825.7 -0.000335   1572    0
1573  20230113   110500    110959  1673579399  ...  18821.0  0.000653   1573    1
1574  20230113   111000    111459  1673579699  ...  18829.8 -0.000154   1574    2
1575  20230113   111500    111959  1673579999  ...  18824.3 -0.000674   1575    3

[5 rows x 11 columns]
2023-01-13 11:20:00,446:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 11:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=261, self.factor=0.20755920180830995, self.count=14071 

self.closeSec=1673580299, self.tradeDate='20230113', self.openTime='112000', self.closeTime='112459', self.symbol='BTCUSDT', self.open=18824.4, self.close=18819.9, self.high=18834.6, self.low=18819.4 
2023-01-13 11:25:01,421:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673580299, self.tradeDate='20230113', self.openTime='112000', self.closeTime='112459',self.symbol='BTCUSDT',self.open=18824.4, self.close=18819.9, self.high=18834.6, self.low=18819.4   
2023-01-13 11:25:01,468:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1572  20230113   110000    110459  1673579099  ...  18825.7 -0.000335   1572    0
1573  20230113   110500    110959  1673579399  ...  18821.0  0.000653   1573    1
1574  20230113   111000    111459  1673579699  ...  18829.8 -0.000154   1574    2
1575  20230113   111500    111959  1673579999  ...  18824.3 -0.000674   1575    3
1576  20230113   112000    112459  1673580299  ...  18819.4 -0.000239   1576    4

[5 rows x 11 columns]
2023-01-13 11:25:01,468:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-13 11:00:31,845:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5776  20230113    082959  18838.1  ...  57.083333  0.655098  0.209563
5777  20230113    085959  18838.2  ...  57.083333  0.638043  0.214866
5778  20230113    092959  18769.5  ...  57.083333  0.640472  0.218853
5779  20230113    095959  18786.9  ...  57.500000  0.643403  0.221420
5780  20230113    102959  18807.9  ...  57.500000  0.638045  0.224982

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2023-01-13 11:00:32,017:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.515867  0.484133       0  ...  1.012262   1.0    0.0  1.130074
537     1  0.494577  0.505423       1  ...  1.013206   1.0    0.0  1.131128
538     0  0.503657  0.496343       1  ...  1.014339   1.0    0.0  1.132392
539     0  0.512761  0.487239       0  ...  1.013195   1.0    0.0  1.131116
540     0  0.502127  0.497873       1  ...  1.015746   1.0    0.0  1.133964

[5 rows x 10 columns]
2023-01-13 11:00:32,047:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.516038  0.483962       0  ...  1.012262   1.0    0.0  1.131505
46     1  0.494787  0.505213       1  ...  1.013206   1.0    0.0  1.132812
47     0  0.503615  0.496385       1  ...  1.014339   1.0    0.0  1.132099
48     0  0.512886  0.487114       0  ...  1.013195   1.0    0.0  1.131995
49     0  0.502127  0.497873       1  ...  1.015746   1.0    0.0  1.133964

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

641  20230113   105000    105959  1673578799  18816.4    18834  0.000930
2023-01-13 11:00:01,105:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 11:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7034 

self.closeSec=1673579399, self.tradeDate='20230113', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='18833.9', self.close='18840'
2023-01-13 11:10:01,531:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673579399, self.tradeDate='20230113', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='18833.9', self.close='18840'
2023-01-13 11:10:01,537:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
638  20230113   102000    102959  1673576999  18815.5  18786.7 -0.001557
639  20230113   103000    103959  1673577599  18786.6  18794.9  0.000436
640  20230113   104000    104959  1673578199  18794.9  18816.5  0.001149
641  20230113   105000    105959  1673578799  18816.4    18834  0.000930
642  20230113   110000    110959  1673579399  18833.9    18840  0.000319
2023-01-13 11:10:01,537:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 11:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7035 

self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111000', self.closeTime='111959', self.symbol='BTCUSDT', self.open='18839.8', self.close='18824.4'
2023-01-13 11:20:00,539:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111000', self.closeTime='111959',self.symbol='BTCUSDT',self.open='18839.8', self.close='18824.4'
2023-01-13 11:20:00,568:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
639  20230113   103000    103959  1673577599  18786.6  18794.9  0.000436
640  20230113   104000    104959  1673578199  18794.9  18816.5  0.001149
641  20230113   105000    105959  1673578799  18816.4    18834  0.000930
642  20230113   110000    110959  1673579399  18833.9    18840  0.000319
643  20230113   111000    111959  1673579999  18839.8  18824.4 -0.000828
2023-01-13 11:20:00,568:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17489  20230113   105000    105959  1673578799  18816.4    18834
2023-01-13 11:00:01,120:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7035 

self.closeSec=1673579399, self.tradeDate='20230113', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='18833.9', self.close='18840'
2023-01-13 11:10:01,552:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673579399, self.tradeDate='20230113', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='18833.9', self.close='18840'
127.0.0.1 - - [13/Jan/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 11:10:01,557:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17486  20230113   102000    102959  1673576999  18815.5  18786.7
17487  20230113   103000    103959  1673577599  18786.6  18794.9
17488  20230113   104000    104959  1673578199  18794.9  18816.5
17489  20230113   105000    105959  1673578799  18816.4    18834
17490  20230113   110000    110959  1673579399  18833.9    18840
2023-01-13 11:10:01,558:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Jan/2023 11:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7036 

self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111000', self.closeTime='111959', self.symbol='BTCUSDT', self.open='18839.8', self.close='18824.4'
2023-01-13 11:20:00,560:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111000', self.closeTime='111959',self.symbol='BTCUSDT',self.open='18839.8', self.close='18824.4'
2023-01-13 11:20:00,566:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17487  20230113   103000    103959  1673577599  18786.6  18794.9
17488  20230113   104000    104959  1673578199  18794.9  18816.5
17489  20230113   105000    105959  1673578799  18816.4    18834
17490  20230113   110000    110959  1673579399  18833.9    18840
17491  20230113   111000    111959  1673579999  18839.8  18824.4
2023-01-13 11:20:00,566:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12161  20230113   105000    105959  1673578799  18816.4    18834
2023-01-13 11:00:01,118:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7035 

self.closeSec=1673579399, self.tradeDate='20230113', self.openTime='110000', self.closeTime='110959', self.symbol='BTCUSDT', self.open='18833.9', self.close='18840'
2023-01-13 11:10:01,535:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673579399, self.tradeDate='20230113', self.openTime='110000', self.closeTime='110959',self.symbol='BTCUSDT',self.open='18833.9', self.close='18840'
127.0.0.1 - - [13/Jan/2023 11:10:01] "POST / HTTP/1.1" 200 -
2023-01-13 11:10:01,543:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12158  20230113   102000    102959  1673576999  18815.5  18786.7
12159  20230113   103000    103959  1673577599  18786.6  18794.9
12160  20230113   104000    104959  1673578199  18794.9  18816.5
12161  20230113   105000    105959  1673578799  18816.4    18834
12162  20230113   110000    110959  1673579399  18833.9    18840
2023-01-13 11:10:01,543:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7036 

self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111000', self.closeTime='111959', self.symbol='BTCUSDT', self.open='18839.8', self.close='18824.4'
2023-01-13 11:20:00,546:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111000', self.closeTime='111959',self.symbol='BTCUSDT',self.open='18839.8', self.close='18824.4'
127.0.0.1 - - [13/Jan/2023 11:20:00] "POST / HTTP/1.1" 200 -
2023-01-13 11:20:00,575:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12159  20230113   103000    103959  1673577599  18786.6  18794.9
12160  20230113   104000    104959  1673578199  18794.9  18816.5
12161  20230113   105000    105959  1673578799  18816.4    18834
12162  20230113   110000    110959  1673579399  18833.9    18840
12163  20230113   111000    111959  1673579999  18839.8  18824.4
2023-01-13 11:20:00,575:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [13/Jan/2023 11:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9502
self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111500', self.closeTime='111959', self.symbol='BTCUSDT', self.open=18837.1, self.close=18824.4, self.high=18837.2, self.low=18824.3, self.vol=351.636, self.amt=6620913.476 
2023-01-13 11:20:00,488:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5891  20230113   105500    105959  ...         0.0        0.0       0
5892  20230113   110000    110459  ...         0.0        0.0       0
5893  20230113   110500    110959  ...         0.0        0.0       0
5894  20230113   111000    111459  ...         0.0        0.0       0
5895  20230113   111500    111959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 11:20:00,489:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673579999, self.tradeDate='20230113', self.openTime='111500', self.closeTime='111959',self.symbol='BTCUSDT',self.open=18837.1, self.close=18824.4, self.high=18837.2, self.low=18824.3, self.vol=351.636, self.amt=6620913.476, ukdf['pct'].iloc[-1]=-0.000674 , ukdf['amount'].iloc[-1]=6620913.476, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5895, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=9503
self.closeSec=1673580299, self.tradeDate='20230113', self.openTime='112000', self.closeTime='112459', self.symbol='BTCUSDT', self.open=18824.4, self.close=18819.9, self.high=18834.6, self.low=18819.4, self.vol=429.76, self.amt=8090957.9267 
127.0.0.1 - - [13/Jan/2023 11:25:01] "POST / HTTP/1.1" 200 -
2023-01-13 11:25:01,506:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5892  20230113   110000    110459  ...         0.0        0.0       0
5893  20230113   110500    110959  ...         0.0        0.0       0
5894  20230113   111000    111459  ...         0.0        0.0       0
5895  20230113   111500    111959  ...         0.0        0.0       0
5896  20230113   112000    112459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-13 11:25:01,508:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673580299, self.tradeDate='20230113', self.openTime='112000', self.closeTime='112459',self.symbol='BTCUSDT',self.open=18824.4, self.close=18819.9, self.high=18834.6, self.low=18819.4, self.vol=429.76, self.amt=8090957.9267, ukdf['pct'].iloc[-1]=-0.000239 , ukdf['amount'].iloc[-1]=8090957.9267, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5896, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230112   200000    235959  1673539199  ...    719  1.297220  1.946828     1.0
720  20230113   000000    035959  1673553599  ...    720  1.612741  2.660284     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '86399.3856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18877.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=292
self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=18877.3, self.close=18838.0, self.high=19120.0, self.low=18758.5, self.vol=124572.563, self.amt=2353820342.8442 
127.0.0.1 - - [13/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-13 08:00:01,244:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673567999, self.tradeDate='20230113', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=18877.3, self.close=18838.0, self.high=19120.0, self.low=18758.5, self.vol=124572.563, self.amt=2353820342.8442 
2023-01-13 08:00:01,318:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230112   120000    155959  ...   51547.124  9.355653e+08 -0.004825
718  20230112   160000    195959  ...   45869.521  8.326695e+08  0.003596
719  20230112   200000    235959  ...  322077.456  5.844744e+09 -0.006425
720  20230113   000000    035959  ...  328471.599  6.135608e+09  0.044232
721  20230113   040000    075959  ...  124572.563  2.353820e+09 -0.002077

[5 rows x 11 columns]
2023-01-13 08:00:03,706:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230112   120000    155959  1673510399  ...    717  1.335643  2.179508     1.0
718  20230112   160000    195959  1673524799  ...    718  1.209428  1.770281     1.0
719  20230112   200000    235959  1673539199  ...    719  1.297220  1.946828     1.0
720  20230113   000000    035959  1673553599  ...    720  1.612741  2.660284     1.0
721  20230113   040000    075959  1673567999  ...    721  1.431327  2.104170     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '84410.98879594752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '18838.91551932', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


