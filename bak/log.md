# 20230116 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [16/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14330
self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20879.0, self.close=20910.9, self.high=20913.0, self.low=20878.4, self.vol=1509.554, self.amt=31547115.4759 
2023-01-16 08:10:01,649:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230116   074500    074959  ...         0.0        0.0       0
5854  20230116   075000    075459  ...         0.0        0.0       0
5855  20230116   075500    075959  ...         0.0        0.0       0
5856  20230116   080000    080459  ...         0.0        0.0       0
5857  20230116   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 08:10:01,649:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20879.0, self.close=20910.9, self.high=20913.0, self.low=20878.4, self.vol=1509.554, self.amt=31547115.4759, ukdf['pct'].iloc[-1]=0.001494 , ukdf['amount'].iloc[-1]=31547115.4759, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-263658.36736683088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20910.75385813', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14331
self.closeSec=1673828099, self.tradeDate='20230116', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20910.9, self.close=20926.4, self.high=20934.4, self.low=20905.7, self.vol=1350.051, self.amt=28246760.385 
127.0.0.1 - - [16/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-16 08:15:00,741:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230116   075000    075459  ...         0.0        0.0       0
5855  20230116   075500    075959  ...         0.0        0.0       0
5856  20230116   080000    080459  ...         0.0        0.0       0
5857  20230116   080500    080959  ...         0.0        0.0       0
5858  20230116   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 08:15:00,742:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673828099, self.tradeDate='20230116', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20910.9, self.close=20926.4, self.high=20934.4, self.low=20905.7, self.vol=1350.051, self.amt=28246760.385, ukdf['pct'].iloc[-1]=0.000741 , ukdf['amount'].iloc[-1]=28246760.385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-264750.3296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20928.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20879.0, self.close=20910.9, self.high=20913.0, self.low=20878.4 
2023-01-16 08:10:01,422:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20879.0, self.close=20910.9, self.high=20913.0, self.low=20878.4   
127.0.0.1 - - [16/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-16 08:10:01,486:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230116   074500    074959  1673826599  ...  20856.6 -0.000967   1533    3
1534  20230116   075000    075459  1673826899  ...  20860.1  0.000096   1534    4
1535  20230116   075500    075959  1673827199  ...  20865.9  0.000752   1535    5
1536  20230116   080000    080459  1673827499  ...  20835.7 -0.000144   1536    0
1537  20230116   080500    080959  1673827799  ...  20878.4  0.001494   1537    1

[5 rows x 11 columns]
2023-01-16 08:10:01,489:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=399, self.factor=0.40572117863125784, self.count=14897 

self.closeSec=1673828099, self.tradeDate='20230116', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20910.9, self.close=20926.4, self.high=20934.4, self.low=20905.7 
2023-01-16 08:15:00,594:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673828099, self.tradeDate='20230116', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20910.9, self.close=20926.4, self.high=20934.4, self.low=20905.7   
2023-01-16 08:15:00,704:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230116   075000    075459  1673826899  ...  20860.1  0.000096   1534    4
1535  20230116   075500    075959  1673827199  ...  20865.9  0.000752   1535    5
1536  20230116   080000    080459  1673827499  ...  20835.7 -0.000144   1536    0
1537  20230116   080500    080959  1673827799  ...  20878.4  0.001494   1537    1
1538  20230116   081000    081459  1673828099  ...  20905.7  0.000741   1538    2

[5 rows x 11 columns]
2023-01-16 08:15:00,704:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-16 08:00:34,507:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230116    052959  20914.7  ...  54.583333  0.574213  0.469323
5771  20230116    055959  20882.0  ...  54.583333  0.578880  0.458866
5772  20230116    062959  20912.1  ...  54.583333  0.567269  0.456175
5773  20230116    065959  20857.1  ...  55.000000  0.578274  0.444651
5774  20230116    072959  20927.0  ...  55.000000  0.570179  0.440055

[5 rows x 33 columns]
0.5194085027726433
acc is : 0.5194085027726433
2023-01-16 08:00:34,677:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.505176  0.494824       1  ...  1.089495   1.0    0.0  1.239854
537     0  0.517169  0.482831       0  ...  1.086634   1.0    0.0  1.236599
538     1  0.493674  0.506326       1  ...  1.090281   1.0    0.0  1.240749
539     0  0.523809  0.476191       0  ...  1.088286   1.0    0.0  1.238479
540     1  0.497228  0.502772       0  ...  1.087968   1.0    0.0  1.238117

[5 rows x 10 columns]
2023-01-16 08:00:34,707:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504933  0.495067       1  ...  1.089495   1.0    0.0  1.241319
46     0  0.517155  0.482845       0  ...  1.086634   1.0    0.0  1.237142
47     1  0.493679  0.506321       1  ...  1.090281   1.0    0.0  1.241913
48     0  0.523809  0.476191       0  ...  1.088286   1.0    0.0  1.238479
49     1  0.497228  0.502772       0  ...  1.087968   1.0    0.0  1.238117

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230116   074000    074959  1673826599  20876.2    20865 -0.000541
2023-01-16 07:50:00,611:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7447 

self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='20865', self.close='20882.7'
2023-01-16 08:00:01,013:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='20865', self.close='20882.7'
2023-01-16 08:00:01,040:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230116   071000    071959  1673824799  20882.5  20901.7  0.000886
620  20230116   072000    072959  1673825399  20901.7  20888.8 -0.000617
621  20230116   073000    073959  1673825999  20888.9  20876.3 -0.000598
622  20230116   074000    074959  1673826599  20876.2    20865 -0.000541
623  20230116   075000    075959  1673827199    20865  20882.7  0.000848
2023-01-16 08:00:01,040:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7448 

self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20882.7', self.close='20910.9'
2023-01-16 08:10:01,547:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20882.7', self.close='20910.9'
2023-01-16 08:10:01,623:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230116   072000    072959  1673825399  20901.7  20888.8 -0.000617
621  20230116   073000    073959  1673825999  20888.9  20876.3 -0.000598
622  20230116   074000    074959  1673826599  20876.2    20865 -0.000541
623  20230116   075000    075959  1673827199    20865  20882.7  0.000848
624  20230116   080000    080959  1673827799  20882.7  20910.9  0.001350
2023-01-16 08:10:01,624:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230116   074000    074959  1673826599  20876.2    20865
2023-01-16 07:50:00,629:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7448 

self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='20865', self.close='20882.7'
2023-01-16 08:00:00,966:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='20865', self.close='20882.7'
2023-01-16 08:00:01,030:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230116   071000    071959  1673824799  20882.5  20901.7
17468  20230116   072000    072959  1673825399  20901.7  20888.8
17469  20230116   073000    073959  1673825999  20888.9  20876.3
17470  20230116   074000    074959  1673826599  20876.2    20865
17471  20230116   075000    075959  1673827199    20865  20882.7
2023-01-16 08:00:01,031:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7449 

self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20882.7', self.close='20910.9'
2023-01-16 08:10:01,586:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20882.7', self.close='20910.9'
2023-01-16 08:10:01,646:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230116   072000    072959  1673825399  20901.7  20888.8
17469  20230116   073000    073959  1673825999  20888.9  20876.3
17470  20230116   074000    074959  1673826599  20876.2    20865
17471  20230116   075000    075959  1673827199    20865  20882.7
17472  20230116   080000    080959  1673827799  20882.7  20910.9
2023-01-16 08:10:01,646:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230116   074000    074959  1673826599  20876.2    20865
2023-01-16 07:50:00,620:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7448 

self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='20865', self.close='20882.7'
2023-01-16 08:00:00,997:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='20865', self.close='20882.7'
127.0.0.1 - - [16/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-16 08:00:01,033:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230116   071000    071959  1673824799  20882.5  20901.7
12140  20230116   072000    072959  1673825399  20901.7  20888.8
12141  20230116   073000    073959  1673825999  20888.9  20876.3
12142  20230116   074000    074959  1673826599  20876.2    20865
12143  20230116   075000    075959  1673827199    20865  20882.7
2023-01-16 08:00:01,038:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [16/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7449 

self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20882.7', self.close='20910.9'
2023-01-16 08:10:01,563:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20882.7', self.close='20910.9'
2023-01-16 08:10:01,630:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230116   072000    072959  1673825399  20901.7  20888.8
12141  20230116   073000    073959  1673825999  20888.9  20876.3
12142  20230116   074000    074959  1673826599  20876.2    20865
12143  20230116   075000    075959  1673827199    20865  20882.7
12144  20230116   080000    080959  1673827799  20882.7  20910.9
2023-01-16 08:10:01,631:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10328
self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=20879.0, self.close=20910.9, self.high=20913.0, self.low=20878.4, self.vol=1509.554, self.amt=31547115.4759 
127.0.0.1 - - [16/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-16 08:10:01,639:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230116   074500    074959  ...         0.0        0.0       0
5854  20230116   075000    075459  ...         0.0        0.0       0
5855  20230116   075500    075959  ...         0.0        0.0       0
5856  20230116   080000    080459  ...         0.0        0.0       0
5857  20230116   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 08:10:01,642:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673827799, self.tradeDate='20230116', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=20879.0, self.close=20910.9, self.high=20913.0, self.low=20878.4, self.vol=1509.554, self.amt=31547115.4759, ukdf['pct'].iloc[-1]=0.001494 , ukdf['amount'].iloc[-1]=31547115.4759, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10329
self.closeSec=1673828099, self.tradeDate='20230116', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=20910.9, self.close=20926.4, self.high=20934.4, self.low=20905.7, self.vol=1350.051, self.amt=28246760.385 
127.0.0.1 - - [16/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-16 08:15:00,731:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230116   075000    075459  ...         0.0        0.0       0
5855  20230116   075500    075959  ...         0.0        0.0       0
5856  20230116   080000    080459  ...         0.0        0.0       0
5857  20230116   080500    080959  ...         0.0        0.0       0
5858  20230116   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-16 08:15:00,731:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673828099, self.tradeDate='20230116', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=20910.9, self.close=20926.4, self.high=20934.4, self.low=20905.7, self.vol=1350.051, self.amt=28246760.385, ukdf['pct'].iloc[-1]=0.000741 , ukdf['amount'].iloc[-1]=28246760.385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230115   200000    235959  1673798399  ...    719  0.985609  0.573577     NaN
720  20230116   000000    035959  1673812799  ...    720  0.949314  0.476058     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '188706.49543493056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20878.48659721', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=310
self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20877.3, self.close=20882.7, self.high=20970.0, self.low=20750.0, self.vol=44695.035, self.amt=933290308.1066 
127.0.0.1 - - [16/Jan/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-01-16 08:00:00,874:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673827199, self.tradeDate='20230116', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20877.3, self.close=20882.7, self.high=20970.0, self.low=20750.0, self.vol=44695.035, self.amt=933290308.1066 
2023-01-16 08:00:01,022:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230115   120000    155959  ...   34775.593  7.212492e+08  0.000651
718  20230115   160000    195959  ...   63521.557  1.314180e+09 -0.000607
719  20230115   200000    235959  ...   82799.747  1.724175e+09  0.009181
720  20230116   000000    035959  ...  106046.834  2.214465e+09 -0.002418
721  20230116   040000    075959  ...   44695.035  9.332903e+08  0.000263

[5 rows x 11 columns]
2023-01-16 08:00:03,282:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230115   120000    155959  1673769599  ...    717  1.073325  0.800655     1.0
718  20230115   160000    195959  1673783999  ...    718  1.022775  0.672264     1.0
719  20230115   200000    235959  1673798399  ...    719  0.985609  0.573577     NaN
720  20230116   000000    035959  1673812799  ...    720  0.949314  0.476058     NaN
721  20230116   040000    075959  1673827199  ...    721  0.901201  0.351053     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '188921.952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20882.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


