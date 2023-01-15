# 20230115 11:43:31

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Jan/2023 11:35:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14083
self.closeSec=1673753699, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113459', self.symbol='BTCUSDT', self.open=20668.2, self.close=20682.4, self.high=20682.4, self.low=20643.4, self.vol=1337.22, self.amt=27637601.2211 
2023-01-15 11:35:00,496:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5894  20230115   111000    111459  ...         0.0        0.0       0
5895  20230115   111500    111959  ...         0.0        0.0       0
5896  20230115   112000    112459  ...         0.0        0.0       0
5897  20230115   112500    112959  ...         0.0        0.0       0
5898  20230115   113000    113459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 11:35:00,497:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673753699, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113459',self.symbol='BTCUSDT',self.open=20668.2, self.close=20682.4, self.high=20682.4, self.low=20643.4, self.vol=1337.22, self.amt=27637601.2211, ukdf['pct'].iloc[-1]=0.000687 , ukdf['amount'].iloc[-1]=27637601.2211, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5898, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-249916.9456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20682.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Jan/2023 11:40:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14084
self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113500', self.closeTime='113959', self.symbol='BTCUSDT', self.open=20682.3, self.close=20687.7, self.high=20694.8, self.low=20668.3, self.vol=762.921, self.amt=15780861.8525 
2023-01-15 11:40:01,892:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5895  20230115   111500    111959  ...         0.0        0.0       0
5896  20230115   112000    112459  ...         0.0        0.0       0
5897  20230115   112500    112959  ...         0.0        0.0       0
5898  20230115   113000    113459  ...         0.0        0.0       0
5899  20230115   113500    113959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 11:40:01,894:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113500', self.closeTime='113959',self.symbol='BTCUSDT',self.open=20682.3, self.close=20687.7, self.high=20694.8, self.low=20668.3, self.vol=762.921, self.amt=15780861.8525, ukdf['pct'].iloc[-1]=0.000256 , ukdf['amount'].iloc[-1]=15780861.8525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5899, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-250241.896', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20687.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=358, self.factor=0.19595562143007872, self.count=14649 

self.closeSec=1673753699, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113459', self.symbol='BTCUSDT', self.open=20668.2, self.close=20682.4, self.high=20682.4, self.low=20643.4 
2023-01-15 11:35:00,452:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673753699, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113459',self.symbol='BTCUSDT',self.open=20668.2, self.close=20682.4, self.high=20682.4, self.low=20643.4   
2023-01-15 11:35:00,488:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1574  20230115   111000    111459  1673752499  ...  20650.0  0.001704   1574    2
1575  20230115   111500    111959  1673752799  ...  20665.0 -0.001068   1575    3
1576  20230115   112000    112459  1673753099  ...  20556.0 -0.002293   1576    4
1577  20230115   112500    112959  1673753399  ...  20609.1  0.002172   1577    5
1578  20230115   113000    113459  1673753699  ...  20643.4  0.000687   1578    0

[5 rows x 11 columns]
2023-01-15 11:35:00,488:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=358, self.factor=0.19595562143007872, self.count=14650 

self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113500', self.closeTime='113959', self.symbol='BTCUSDT', self.open=20682.3, self.close=20687.7, self.high=20694.8, self.low=20668.3 
2023-01-15 11:40:01,649:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113500', self.closeTime='113959',self.symbol='BTCUSDT',self.open=20682.3, self.close=20687.7, self.high=20694.8, self.low=20668.3   
127.0.0.1 - - [15/Jan/2023 11:40:01] "POST / HTTP/1.1" 200 -
2023-01-15 11:40:01,716:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1575  20230115   111500    111959  1673752799  ...  20665.0 -0.001068   1575    3
1576  20230115   112000    112459  1673753099  ...  20556.0 -0.002293   1576    4
1577  20230115   112500    112959  1673753399  ...  20609.1  0.002172   1577    5
1578  20230115   113000    113459  1673753699  ...  20643.4  0.000687   1578    0
1579  20230115   113500    113959  1673753999  ...  20668.3  0.000256   1579    1

[5 rows x 11 columns]
2023-01-15 11:40:01,717:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-15 11:30:16,999:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5777  20230115    085959  20927.3  ...  55.833333  0.595989  0.333383
5778  20230115    092959  20774.7  ...  55.833333  0.584478  0.347649
5779  20230115    095959  20702.2  ...  56.250000  0.594160  0.355075
5780  20230115    102959  20785.3  ...  56.250000  0.591213  0.363241
5781  20230115    105959  20770.7  ...  56.250000  0.577464  0.376669

[5 rows x 33 columns]
0.5157116451016636
acc is : 0.5157116451016636
2023-01-15 11:30:17,090:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.462058  0.537942       0  ...  1.078559   1.0    0.0  1.242921
537     1  0.458573  0.541427       1  ...  1.083081   1.0    0.0  1.248133
538     1  0.488995  0.511005       0  ...  1.082133   1.0    0.0  1.247040
539     1  0.477366  0.522634       0  ...  1.077673   1.0    0.0  1.241901
540     1  0.459310  0.540690       0  ...  1.076793   1.0    0.0  1.240886

[5 rows x 10 columns]
2023-01-15 11:30:17,105:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.462265  0.537735       0  ...  1.078559   1.0    0.0  1.244289
46     1  0.458491  0.541509       1  ...  1.083081   1.0    0.0  1.250174
47     1  0.488968  0.511032       0  ...  1.082133   1.0    0.0  1.248412
48     1  0.477281  0.522719       0  ...  1.077673   1.0    0.0  1.242222
49     1  0.459310  0.540690       0  ...  1.076793   1.0    0.0  1.240886

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

643  20230115   111000    111959  1673752799  20657.8  20670.8  0.000634
2023-01-15 11:20:00,608:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 11:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7324 

self.closeSec=1673753399, self.tradeDate='20230115', self.openTime='112000', self.closeTime='112959', self.symbol='BTCUSDT', self.open='20670.9', self.close='20668.2'
2023-01-15 11:30:00,729:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673753399, self.tradeDate='20230115', self.openTime='112000', self.closeTime='112959',self.symbol='BTCUSDT',self.open='20670.9', self.close='20668.2'
2023-01-15 11:30:00,751:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
640  20230115   104000    104959  1673750999  20719.1  20730.7  0.000560
641  20230115   105000    105959  1673751599  20730.8  20685.1 -0.002200
642  20230115   110000    110959  1673752199  20684.9  20657.7 -0.001325
643  20230115   111000    111959  1673752799  20657.8  20670.8  0.000634
644  20230115   112000    112959  1673753399  20670.9  20668.2 -0.000126
2023-01-15 11:30:00,751:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7325 

self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113959', self.symbol='BTCUSDT', self.open='20668.2', self.close='20687.7'
2023-01-15 11:40:01,783:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113959',self.symbol='BTCUSDT',self.open='20668.2', self.close='20687.7'
127.0.0.1 - - [15/Jan/2023 11:40:01] "POST / HTTP/1.1" 200 -
2023-01-15 11:40:01,837:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
641  20230115   105000    105959  1673751599  20730.8  20685.1 -0.002200
642  20230115   110000    110959  1673752199  20684.9  20657.7 -0.001325
643  20230115   111000    111959  1673752799  20657.8  20670.8  0.000634
644  20230115   112000    112959  1673753399  20670.9  20668.2 -0.000126
645  20230115   113000    113959  1673753999  20668.2  20687.7  0.000943
2023-01-15 11:40:01,837:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17491  20230115   111000    111959  1673752799  20657.8  20670.8
2023-01-15 11:20:00,586:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7325 

self.closeSec=1673753399, self.tradeDate='20230115', self.openTime='112000', self.closeTime='112959', self.symbol='BTCUSDT', self.open='20670.9', self.close='20668.2'
2023-01-15 11:30:00,741:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673753399, self.tradeDate='20230115', self.openTime='112000', self.closeTime='112959',self.symbol='BTCUSDT',self.open='20670.9', self.close='20668.2'
127.0.0.1 - - [15/Jan/2023 11:30:00] "POST / HTTP/1.1" 200 -
2023-01-15 11:30:00,757:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17488  20230115   104000    104959  1673750999  20719.1  20730.7
17489  20230115   105000    105959  1673751599  20730.8  20685.1
17490  20230115   110000    110959  1673752199  20684.9  20657.7
17491  20230115   111000    111959  1673752799  20657.8  20670.8
17492  20230115   112000    112959  1673753399  20670.9  20668.2
2023-01-15 11:30:00,758:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7326 

self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113959', self.symbol='BTCUSDT', self.open='20668.2', self.close='20687.7'
127.0.0.1 - - [15/Jan/2023 11:40:01] "POST / HTTP/1.1" 200 -
2023-01-15 11:40:01,808:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113959',self.symbol='BTCUSDT',self.open='20668.2', self.close='20687.7'
2023-01-15 11:40:01,845:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17489  20230115   105000    105959  1673751599  20730.8  20685.1
17490  20230115   110000    110959  1673752199  20684.9  20657.7
17491  20230115   111000    111959  1673752799  20657.8  20670.8
17492  20230115   112000    112959  1673753399  20670.9  20668.2
17493  20230115   113000    113959  1673753999  20668.2  20687.7
2023-01-15 11:40:01,849:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12163  20230115   111000    111959  1673752799  20657.8  20670.8
2023-01-15 11:20:00,593:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jan/2023 11:30:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7325 

self.closeSec=1673753399, self.tradeDate='20230115', self.openTime='112000', self.closeTime='112959', self.symbol='BTCUSDT', self.open='20670.9', self.close='20668.2'
2023-01-15 11:30:00,737:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673753399, self.tradeDate='20230115', self.openTime='112000', self.closeTime='112959',self.symbol='BTCUSDT',self.open='20670.9', self.close='20668.2'
2023-01-15 11:30:00,750:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12160  20230115   104000    104959  1673750999  20719.1  20730.7
12161  20230115   105000    105959  1673751599  20730.8  20685.1
12162  20230115   110000    110959  1673752199  20684.9  20657.7
12163  20230115   111000    111959  1673752799  20657.8  20670.8
12164  20230115   112000    112959  1673753399  20670.9  20668.2
2023-01-15 11:30:00,751:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jan/2023 11:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7326 

self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113959', self.symbol='BTCUSDT', self.open='20668.2', self.close='20687.7'
2023-01-15 11:40:01,850:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113959',self.symbol='BTCUSDT',self.open='20668.2', self.close='20687.7'
2023-01-15 11:40:01,895:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12161  20230115   105000    105959  1673751599  20730.8  20685.1
12162  20230115   110000    110959  1673752199  20684.9  20657.7
12163  20230115   111000    111959  1673752799  20657.8  20670.8
12164  20230115   112000    112959  1673753399  20670.9  20668.2
12165  20230115   113000    113959  1673753999  20668.2  20687.7
2023-01-15 11:40:01,899:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10081
self.closeSec=1673753699, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113459', self.symbol='BTCUSDT', self.open=20668.2, self.close=20682.4, self.high=20682.4, self.low=20643.4, self.vol=1337.22, self.amt=27637601.2211 
127.0.0.1 - - [15/Jan/2023 11:35:00] "POST / HTTP/1.1" 200 -
2023-01-15 11:35:00,469:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5894  20230115   111000    111459  ...         0.0        0.0       0
5895  20230115   111500    111959  ...         0.0        0.0       0
5896  20230115   112000    112459  ...         0.0        0.0       0
5897  20230115   112500    112959  ...         0.0        0.0       0
5898  20230115   113000    113459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 11:35:00,470:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673753699, self.tradeDate='20230115', self.openTime='113000', self.closeTime='113459',self.symbol='BTCUSDT',self.open=20668.2, self.close=20682.4, self.high=20682.4, self.low=20643.4, self.vol=1337.22, self.amt=27637601.2211, ukdf['pct'].iloc[-1]=0.000687 , ukdf['amount'].iloc[-1]=27637601.2211, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5898, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [15/Jan/2023 11:40:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10082
self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113500', self.closeTime='113959', self.symbol='BTCUSDT', self.open=20682.3, self.close=20687.7, self.high=20694.8, self.low=20668.3, self.vol=762.921, self.amt=15780861.8525 
2023-01-15 11:40:01,750:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5895  20230115   111500    111959  ...         0.0        0.0       0
5896  20230115   112000    112459  ...         0.0        0.0       0
5897  20230115   112500    112959  ...         0.0        0.0       0
5898  20230115   113000    113459  ...         0.0        0.0       0
5899  20230115   113500    113959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 11:40:01,753:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673753999, self.tradeDate='20230115', self.openTime='113500', self.closeTime='113959',self.symbol='BTCUSDT',self.open=20682.3, self.close=20687.7, self.high=20694.8, self.low=20668.3, self.vol=762.921, self.amt=15780861.8525, ukdf['pct'].iloc[-1]=0.000256 , ukdf['amount'].iloc[-1]=15780861.8525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5899, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230114   200000    235959  1673711999  ...    719  1.292952  1.376640     1.0
720  20230115   000000    035959  1673726399  ...    720  1.213180  1.171201     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '184335.0528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20793', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [15/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=304
self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20796.8, self.close=20962.8, self.high=21092.0, self.low=20773.9, self.vol=59647.002, self.amt=1249464723.83337 
2023-01-15 08:00:00,932:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20796.8, self.close=20962.8, self.high=21092.0, self.low=20773.9, self.vol=59647.002, self.amt=1249464723.83337 
2023-01-15 08:00:00,976:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230114   120000    155959  ...   75863.507  1.587466e+09 -0.003967
718  20230114   160000    195959  ...  208916.807  4.304202e+09 -0.008759
719  20230114   200000    235959  ...  186884.918  3.898285e+09  0.003072
720  20230115   000000    035959  ...   78646.183  1.636048e+09  0.000082
721  20230115   040000    075959  ...   59647.002  1.249465e+09  0.007890

[5 rows x 11 columns]
2023-01-15 08:00:02,930:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230114   120000    155959  1673683199  ...    717  1.289315  1.435970     1.0
718  20230114   160000    195959  1673697599  ...    718  1.303569  1.434301     1.0
719  20230114   200000    235959  1673711999  ...    719  1.292952  1.376640     1.0
720  20230115   000000    035959  1673726399  ...    720  1.213180  1.171201     1.0
721  20230115   040000    075959  1673740799  ...    721  1.161411  1.034070     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '192879.8784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20960.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


