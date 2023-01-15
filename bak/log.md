# 20230115 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [15/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14042
self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20920.7, self.close=20976.8, self.high=21012.0, self.low=20920.7, self.vol=2866.584, self.amt=60108506.3258 
2023-01-15 08:10:01,509:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230115   074500    074959  ...         0.0        0.0       0
5854  20230115   075000    075459  ...         0.0        0.0       0
5855  20230115   075500    075959  ...         0.0        0.0       0
5856  20230115   080000    080459  ...         0.0        0.0       0
5857  20230115   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 08:10:01,510:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20920.7, self.close=20976.8, self.high=21012.0, self.low=20920.7, self.vol=2866.584, self.amt=60108506.3258, ukdf['pct'].iloc[-1]=0.002792 , ukdf['amount'].iloc[-1]=60108506.3258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-267861.4288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20980.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14043
self.closeSec=1673741699, self.tradeDate='20230115', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20979.4, self.close=20954.6, self.high=20991.2, self.low=20940.0, self.vol=1621.794, self.amt=33998113.5228 
2023-01-15 08:15:00,805:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230115   075000    075459  ...         0.0        0.0       0
5855  20230115   075500    075959  ...         0.0        0.0       0
5856  20230115   080000    080459  ...         0.0        0.0       0
5857  20230115   080500    080959  ...         0.0        0.0       0
5858  20230115   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 08:15:00,806:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673741699, self.tradeDate='20230115', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20979.4, self.close=20954.6, self.high=20991.2, self.low=20940.0, self.vol=1621.794, self.amt=33998113.5228, ukdf['pct'].iloc[-1]=-0.001058 , ukdf['amount'].iloc[-1]=33998113.5228, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-266140.3952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20952', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=351, self.factor=0.1508219562958285, self.count=14608 

self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20920.7, self.close=20976.8, self.high=21012.0, self.low=20920.7 
2023-01-15 08:10:01,461:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20920.7, self.close=20976.8, self.high=21012.0, self.low=20920.7   
2023-01-15 08:10:01,492:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230115   074500    074959  1673740199  ...  21027.7 -0.000789   1533    3
1534  20230115   075000    075459  1673740499  ...  20975.1 -0.002216   1534    4
1535  20230115   075500    075959  1673740799  ...  20940.4 -0.000886   1535    5
1536  20230115   080000    080459  1673741099  ...  20904.4 -0.002118   1536    0
1537  20230115   080500    080959  1673741399  ...  20920.7  0.002792   1537    1

[5 rows x 11 columns]
2023-01-15 08:10:01,492:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=351, self.factor=0.1508219562958285, self.count=14609 

self.closeSec=1673741699, self.tradeDate='20230115', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20979.4, self.close=20954.6, self.high=20991.2, self.low=20940.0 
2023-01-15 08:15:00,606:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673741699, self.tradeDate='20230115', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20979.4, self.close=20954.6, self.high=20991.2, self.low=20940.0   
2023-01-15 08:15:00,671:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230115   075000    075459  1673740499  ...  20975.1 -0.002216   1534    4
1535  20230115   075500    075959  1673740799  ...  20940.4 -0.000886   1535    5
1536  20230115   080000    080459  1673741099  ...  20904.4 -0.002118   1536    0
1537  20230115   080500    080959  1673741399  ...  20920.7  0.002792   1537    1
1538  20230115   081000    081459  1673741699  ...  20940.0 -0.001058   1538    2

[5 rows x 11 columns]
2023-01-15 08:15:00,672:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-15 08:00:33,641:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230115    052959  20895.0  ...  56.250000  0.629374  0.345631
5771  20230115    055959  20879.5  ...  56.666667  0.632898  0.344691
5772  20230115    062959  20914.2  ...  56.250000  0.629763  0.345022
5773  20230115    065959  20896.4  ...  56.666667  0.640778  0.338003
5774  20230115    072959  21004.4  ...  57.083333  0.647971  0.326521

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-01-15 08:00:33,814:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.510113  0.489887       1  ...  1.089609   1.0    0.0  1.258557
537     0  0.517504  0.482496       0  ...  1.088682   1.0    0.0  1.257486
538     0  0.507571  0.492429       1  ...  1.094309   1.0    0.0  1.263985
539     0  0.540364  0.459636       1  ...  1.098096   1.0    0.0  1.268360
540     0  0.536500  0.463500       0  ...  1.092141   1.0    0.0  1.261482

[5 rows x 10 columns]
2023-01-15 08:00:33,840:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510054  0.489946       1  ...  1.089609   1.0    0.0  1.254526
46     0  0.517428  0.482572       0  ...  1.088682   1.0    0.0  1.255491
47     0  0.507474  0.492526       1  ...  1.094309   1.0    0.0  1.264008
48     0  0.540364  0.459636       1  ...  1.098096   1.0    0.0  1.268360
49     0  0.536500  0.463500       0  ...  1.092141   1.0    0.0  1.261482

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230115   074000    074959  1673740199  21028.6    21028 -0.000033
2023-01-15 07:50:00,596:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7303 

self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21027.4', self.close='20962.8'
127.0.0.1 - - [15/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-15 08:00:01,036:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21027.4', self.close='20962.8'
2023-01-15 08:00:01,071:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230115   071000    071959  1673738399  20992.5  21042.9  0.002253
620  20230115   072000    072959  1673738999  21040.1  21077.1  0.001625
621  20230115   073000    073959  1673739599  21077.1  21028.7 -0.002296
622  20230115   074000    074959  1673740199  21028.6    21028 -0.000033
623  20230115   075000    075959  1673740799  21027.4  20962.8 -0.003101
2023-01-15 08:00:01,076:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7304 

self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20962.8', self.close='20976.8'
2023-01-15 08:10:01,531:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20962.8', self.close='20976.8'
2023-01-15 08:10:01,551:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230115   072000    072959  1673738999  21040.1  21077.1  0.001625
621  20230115   073000    073959  1673739599  21077.1  21028.7 -0.002296
622  20230115   074000    074959  1673740199  21028.6    21028 -0.000033
623  20230115   075000    075959  1673740799  21027.4  20962.8 -0.003101
624  20230115   080000    080959  1673741399  20962.8  20976.8  0.000668
2023-01-15 08:10:01,551:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230115   074000    074959  1673740199  21028.6    21028
2023-01-15 07:50:00,610:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7304 

self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21027.4', self.close='20962.8'
2023-01-15 08:00:01,052:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21027.4', self.close='20962.8'
127.0.0.1 - - [15/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-15 08:00:01,126:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230115   071000    071959  1673738399  20992.5  21042.9
17468  20230115   072000    072959  1673738999  21040.1  21077.1
17469  20230115   073000    073959  1673739599  21077.1  21028.7
17470  20230115   074000    074959  1673740199  21028.6    21028
17471  20230115   075000    075959  1673740799  21027.4  20962.8
2023-01-15 08:00:01,126:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7305 

self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20962.8', self.close='20976.8'
2023-01-15 08:10:01,548:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20962.8', self.close='20976.8'
127.0.0.1 - - [15/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-15 08:10:01,568:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230115   072000    072959  1673738999  21040.1  21077.1
17469  20230115   073000    073959  1673739599  21077.1  21028.7
17470  20230115   074000    074959  1673740199  21028.6    21028
17471  20230115   075000    075959  1673740799  21027.4  20962.8
17472  20230115   080000    080959  1673741399  20962.8  20976.8
2023-01-15 08:10:01,569:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230115   074000    074959  1673740199  21028.6    21028
2023-01-15 07:50:00,601:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7304 

self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21027.4', self.close='20962.8'
2023-01-15 08:00:01,051:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673740799, self.tradeDate='20230115', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21027.4', self.close='20962.8'
2023-01-15 08:00:01,095:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230115   071000    071959  1673738399  20992.5  21042.9
12140  20230115   072000    072959  1673738999  21040.1  21077.1
12141  20230115   073000    073959  1673739599  21077.1  21028.7
12142  20230115   074000    074959  1673740199  21028.6    21028
12143  20230115   075000    075959  1673740799  21027.4  20962.8
2023-01-15 08:00:01,096:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [15/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7305 

self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20962.8', self.close='20976.8'
2023-01-15 08:10:01,563:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20962.8', self.close='20976.8'
2023-01-15 08:10:01,591:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230115   072000    072959  1673738999  21040.1  21077.1
12141  20230115   073000    073959  1673739599  21077.1  21028.7
12142  20230115   074000    074959  1673740199  21028.6    21028
12143  20230115   075000    075959  1673740799  21027.4  20962.8
12144  20230115   080000    080959  1673741399  20962.8  20976.8
2023-01-15 08:10:01,594:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10040
self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20920.7, self.close=20976.8, self.high=21012.0, self.low=20920.7, self.vol=2866.584, self.amt=60108506.3258 
127.0.0.1 - - [15/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-15 08:10:01,511:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230115   074500    074959  ...         0.0        0.0       0
5854  20230115   075000    075459  ...         0.0        0.0       0
5855  20230115   075500    075959  ...         0.0        0.0       0
5856  20230115   080000    080459  ...         0.0        0.0       0
5857  20230115   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 08:10:01,511:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673741399, self.tradeDate='20230115', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20920.7, self.close=20976.8, self.high=21012.0, self.low=20920.7, self.vol=2866.584, self.amt=60108506.3258, ukdf['pct'].iloc[-1]=0.002792 , ukdf['amount'].iloc[-1]=60108506.3258, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10041
self.closeSec=1673741699, self.tradeDate='20230115', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20979.4, self.close=20954.6, self.high=20991.2, self.low=20940.0, self.vol=1621.794, self.amt=33998113.5228 
127.0.0.1 - - [15/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-15 08:15:00,804:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230115   075000    075459  ...         0.0        0.0       0
5855  20230115   075500    075959  ...         0.0        0.0       0
5856  20230115   080000    080459  ...         0.0        0.0       0
5857  20230115   080500    080959  ...         0.0        0.0       0
5858  20230115   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-15 08:15:00,805:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673741699, self.tradeDate='20230115', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20979.4, self.close=20954.6, self.high=20991.2, self.low=20940.0, self.vol=1621.794, self.amt=33998113.5228, ukdf['pct'].iloc[-1]=-0.001058 , ukdf['amount'].iloc[-1]=33998113.5228, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
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


