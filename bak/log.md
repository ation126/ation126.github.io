# 20230111 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12890
self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17430.4, self.close=17425.7, self.high=17433.6, self.low=17425.6, self.vol=319.669, self.amt=5571864.558 
127.0.0.1 - - [11/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 08:10:01,582:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230111   074500    074959  ...         0.0        0.0       0
5854  20230111   075000    075459  ...         0.0        0.0       0
5855  20230111   075500    075959  ...         0.0        0.0       0
5856  20230111   080000    080459  ...         0.0        0.0       0
5857  20230111   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 08:10:01,584:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17430.4, self.close=17425.7, self.high=17433.6, self.low=17425.6, self.vol=319.669, self.amt=5571864.558, ukdf['pct'].iloc[-1]=-0.00027 , ukdf['amount'].iloc[-1]=5571864.558, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-53954.30824461088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17425.90841938', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=12891
self.closeSec=1673396099, self.tradeDate='20230111', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17425.7, self.close=17427.4, self.high=17429.4, self.low=17420.6, self.vol=686.787, self.amt=11966405.4987 
2023-01-11 08:15:00,615:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230111   075000    075459  ...         0.0        0.0       0
5855  20230111   075500    075959  ...         0.0        0.0       0
5856  20230111   080000    080459  ...         0.0        0.0       0
5857  20230111   080500    080959  ...         0.0        0.0       0
5858  20230111   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 08:15:00,616:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1673396099, self.tradeDate='20230111', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17425.7, self.close=17427.4, self.high=17429.4, self.low=17420.6, self.vol=686.787, self.amt=11966405.4987, ukdf['pct'].iloc[-1]=9.8e-05 , ukdf['amount'].iloc[-1]=11966405.4987, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-54060.1989179872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '17427.6681022', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17430.4, self.close=17425.7, self.high=17433.6, self.low=17425.6 
2023-01-11 08:10:01,449:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17430.4, self.close=17425.7, self.high=17433.6, self.low=17425.6   
127.0.0.1 - - [11/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 08:10:01,491:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230111   074500    074959  1673394599  ...  17416.9 -0.000241   1533    3
1534  20230111   075000    075459  1673394899  ...  17418.6  0.000425   1534    4
1535  20230111   075500    075959  1673395199  ...  17425.9  0.000161   1535    5
1536  20230111   080000    080459  1673395499  ...  17428.5  0.000092   1536    0
1537  20230111   080500    080959  1673395799  ...  17425.6 -0.000270   1537    1

[5 rows x 11 columns]
2023-01-11 08:10:01,491:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=159, self.factor=0.3897271016655221, self.count=13457 

self.closeSec=1673396099, self.tradeDate='20230111', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17425.7, self.close=17427.4, self.high=17429.4, self.low=17420.6 
2023-01-11 08:15:00,545:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1673396099, self.tradeDate='20230111', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17425.7, self.close=17427.4, self.high=17429.4, self.low=17420.6   
2023-01-11 08:15:00,575:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230111   075000    075459  1673394899  ...  17418.6  0.000425   1534    4
1535  20230111   075500    075959  1673395199  ...  17425.9  0.000161   1535    5
1536  20230111   080000    080459  1673395499  ...  17428.5  0.000092   1536    0
1537  20230111   080500    080959  1673395799  ...  17425.6 -0.000270   1537    1
1538  20230111   081000    081459  1673396099  ...  17420.6  0.000098   1538    2

[5 rows x 11 columns]
2023-01-11 08:15:00,575:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-11 08:00:24,698:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230111    052959  17466.6  ...  54.166667  0.630498  0.303655
5771  20230111    055959  17443.2  ...  54.166667  0.634840  0.289556
5772  20230111    062959  17453.5  ...  53.750000  0.618024  0.280958
5773  20230111    065959  17429.9  ...  53.750000  0.611996  0.275670
5774  20230111    072959  17419.8  ...  53.750000  0.611783  0.271383

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-01-11 08:00:24,818:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
536     0  0.502187  0.497813       1  ...  NaN   NaN -0.0016  1.056098
537     0  0.512034  0.487966       0  ...  NaN   NaN -0.0016  1.054670
538     0  0.500496  0.499504       0  ...  NaN   NaN -0.0016  1.054149
539     1  0.499983  0.500017       0  ...  NaN   NaN -0.0016  1.054131
540     1  0.499373  0.500627       1  ...  NaN   NaN -0.0016  1.054597

[5 rows x 10 columns]
2023-01-11 08:00:24,835:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...  nav  sign   cost_        bm
45     0  0.502023  0.497977       1  ...  NaN   NaN -0.0016  1.054745
46     0  0.511999  0.488001       0  ...  NaN   NaN -0.0016  1.055500
47     0  0.500354  0.499646       0  ...  NaN   NaN -0.0016  1.053276
48     1  0.499912  0.500088       0  ...  NaN   NaN -0.0016  1.054131
49     1  0.499373  0.500627       1  ...  NaN   NaN -0.0016  1.054597

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '31070.9568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17432.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230111   074000    074959  1673394599  17421.7  17418.6 -0.000178
2023-01-11 07:50:01,038:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6727 

self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17418.6', self.close='17428.8'
2023-01-11 08:00:01,133:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17418.6', self.close='17428.8'
2023-01-11 08:00:01,225:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230111   071000    071959  1673392799    17424  17412.9 -0.000643
620  20230111   072000    072959  1673393399  17412.9  17422.6  0.000557
621  20230111   073000    073959  1673393999  17422.7  17421.7 -0.000052
622  20230111   074000    074959  1673394599  17421.7  17418.6 -0.000178
623  20230111   075000    075959  1673395199  17418.6  17428.8  0.000586
2023-01-11 08:00:01,229:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6728 

self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17428.8', self.close='17425.7'
2023-01-11 08:10:01,523:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17428.8', self.close='17425.7'
2023-01-11 08:10:01,581:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230111   072000    072959  1673393399  17412.9  17422.6  0.000557
621  20230111   073000    073959  1673393999  17422.7  17421.7 -0.000052
622  20230111   074000    074959  1673394599  17421.7  17418.6 -0.000178
623  20230111   075000    075959  1673395199  17418.6  17428.8  0.000586
624  20230111   080000    080959  1673395799  17428.8  17425.7 -0.000178
2023-01-11 08:10:01,582:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230111   074000    074959  1673394599  17421.7  17418.6
2023-01-11 07:50:01,041:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6728 

self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17418.6', self.close='17428.8'
2023-01-11 08:00:01,157:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17418.6', self.close='17428.8'
2023-01-11 08:00:01,240:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230111   071000    071959  1673392799    17424  17412.9
17468  20230111   072000    072959  1673393399  17412.9  17422.6
17469  20230111   073000    073959  1673393999  17422.7  17421.7
17470  20230111   074000    074959  1673394599  17421.7  17418.6
17471  20230111   075000    075959  1673395199  17418.6  17428.8
2023-01-11 08:00:01,240:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6729 

self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17428.8', self.close='17425.7'
127.0.0.1 - - [11/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 08:10:01,542:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17428.8', self.close='17425.7'
2023-01-11 08:10:01,609:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230111   072000    072959  1673393399  17412.9  17422.6
17469  20230111   073000    073959  1673393999  17422.7  17421.7
17470  20230111   074000    074959  1673394599  17421.7  17418.6
17471  20230111   075000    075959  1673395199  17418.6  17428.8
17472  20230111   080000    080959  1673395799  17428.8  17425.7
2023-01-11 08:10:01,609:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230111   074000    074959  1673394599  17421.7  17418.6
2023-01-11 07:50:01,047:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6728 

self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='17418.6', self.close='17428.8'
127.0.0.1 - - [11/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-11 08:00:01,128:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='17418.6', self.close='17428.8'
2023-01-11 08:00:01,158:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230111   071000    071959  1673392799    17424  17412.9
12140  20230111   072000    072959  1673393399  17412.9  17422.6
12141  20230111   073000    073959  1673393999  17422.7  17421.7
12142  20230111   074000    074959  1673394599  17421.7  17418.6
12143  20230111   075000    075959  1673395199  17418.6  17428.8
2023-01-11 08:00:01,158:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6729 

self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='17428.8', self.close='17425.7'
2023-01-11 08:10:01,567:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='17428.8', self.close='17425.7'
127.0.0.1 - - [11/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-11 08:10:01,605:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230111   072000    072959  1673393399  17412.9  17422.6
12141  20230111   073000    073959  1673393999  17422.7  17421.7
12142  20230111   074000    074959  1673394599  17421.7  17418.6
12143  20230111   075000    075959  1673395199  17418.6  17428.8
12144  20230111   080000    080959  1673395799  17428.8  17425.7
2023-01-11 08:10:01,608:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [11/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8888
self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=17430.4, self.close=17425.7, self.high=17433.6, self.low=17425.6, self.vol=319.669, self.amt=5571864.558 
2023-01-11 08:10:01,574:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230111   074500    074959  ...         0.0        0.0       0
5854  20230111   075000    075459  ...         0.0        0.0       0
5855  20230111   075500    075959  ...         0.0        0.0       0
5856  20230111   080000    080459  ...         0.0        0.0       0
5857  20230111   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 08:10:01,575:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673395799, self.tradeDate='20230111', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=17430.4, self.close=17425.7, self.high=17433.6, self.low=17425.6, self.vol=319.669, self.amt=5571864.558, ukdf['pct'].iloc[-1]=-0.00027 , ukdf['amount'].iloc[-1]=5571864.558, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [11/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=8889
self.closeSec=1673396099, self.tradeDate='20230111', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=17425.7, self.close=17427.4, self.high=17429.4, self.low=17420.6, self.vol=686.787, self.amt=11966405.4987 
2023-01-11 08:15:00,584:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230111   075000    075459  ...         0.0        0.0       0
5855  20230111   075500    075959  ...         0.0        0.0       0
5856  20230111   080000    080459  ...         0.0        0.0       0
5857  20230111   080500    080959  ...         0.0        0.0       0
5858  20230111   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-11 08:15:00,585:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1673396099, self.tradeDate='20230111', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=17425.7, self.close=17427.4, self.high=17429.4, self.low=17420.6, self.vol=686.787, self.amt=11966405.4987, ukdf['pct'].iloc[-1]=9.8e-05 , ukdf['amount'].iloc[-1]=11966405.4987, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230110   200000    235959  1673366399  ...    719  0.916099  1.636005     1.0
720  20230111   000000    035959  1673380799  ...    720  1.118817  2.235224     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '12155.32492555328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17425.90582223', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=878056.8594048, self.flagDict['side']='buy', self.tradeCount=12, self.count=280
self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=17424.1, self.close=17428.8, self.high=17485.4, self.low=17393.3, self.vol=48167.989, self.amt=840177220.8528 
2023-01-11 08:00:01,043:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673395199, self.tradeDate='20230111', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=17424.1, self.close=17428.8, self.high=17485.4, self.low=17393.3, self.vol=48167.989, self.amt=840177220.8528 
2023-01-11 08:00:01,118:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230110   120000    155959  ...  18254.506  3.140340e+08 -0.000302
718  20230110   160000    195959  ...  37043.962  6.388362e+08  0.002896
719  20230110   200000    235959  ...  92789.110  1.603150e+09  0.004204
720  20230111   000000    035959  ...  73563.359  1.278025e+09  0.006190
721  20230111   040000    075959  ...  48167.989  8.401772e+08  0.000264

[5 rows x 11 columns]
2023-01-11 08:00:02,844:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230110   120000    155959  1673337599  ...    717  0.878976  1.587603     1.0
718  20230110   160000    195959  1673351999  ...    718  0.856784  1.476983     1.0
719  20230110   200000    235959  1673366399  ...    719  0.916099  1.636005     1.0
720  20230111   000000    035959  1673380799  ...    720  1.118817  2.235224     1.0
721  20230111   040000    075959  1673395199  ...    721  1.158436  2.281776     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.136', 'enterprice': '17188.2', 'countrevence': '0', 'unrealprofit': '12380.17243753536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '17430.30287151', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


