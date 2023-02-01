# 20230201 08:16:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [01/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18938
self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23126.8, self.close=23063.2, self.high=23129.0, self.low=23051.3, self.vol=3383.69, self.amt=78104232.6326 
2023-02-01 08:10:01,715:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230201   074500    074959  ...         0.0        0.0       0
5854  20230201   075000    075459  ...         0.0        0.0       0
5855  20230201   075500    075959  ...         0.0        0.0       0
5856  20230201   080000    080459  ...         0.0        0.0       0
5857  20230201   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 08:10:01,715:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23126.8, self.close=23063.2, self.high=23129.0, self.low=23051.3, self.vol=3383.69, self.amt=78104232.6326, ukdf['pct'].iloc[-1]=-0.00275 , ukdf['amount'].iloc[-1]=78104232.6326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-393183.9664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23063.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Feb/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=18939
self.closeSec=1675210499, self.tradeDate='20230201', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23063.2, self.close=23084.6, self.high=23089.2, self.low=23027.8, self.vol=2654.984, self.amt=61219417.0642 
2023-02-01 08:15:00,836:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230201   075000    075459  ...         0.0        0.0       0
5855  20230201   075500    075959  ...         0.0        0.0       0
5856  20230201   080000    080459  ...         0.0        0.0       0
5857  20230201   080500    080959  ...         0.0        0.0       0
5858  20230201   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 08:15:00,846:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1675210499, self.tradeDate='20230201', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23063.2, self.close=23084.6, self.high=23089.2, self.low=23027.8, self.vol=2654.984, self.amt=61219417.0642, ukdf['pct'].iloc[-1]=0.000928 , ukdf['amount'].iloc[-1]=61219417.0642, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-394557.08991476752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23086.01845777', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=18, self.factor=0.45615024228504414, self.count=19504 

self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23126.8, self.close=23063.2, self.high=23129.0, self.low=23051.3 
2023-02-01 08:10:01,654:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23126.8, self.close=23063.2, self.high=23129.0, self.low=23051.3   
2023-02-01 08:10:01,691:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230201   074500    074959  1675208999  ...  23115.6  0.000497   1533    3
1534  20230201   075000    075459  1675209299  ...  23117.7  0.000679   1534    4
1535  20230201   075500    075959  1675209599  ...  23116.0 -0.001063   1535    5
1536  20230201   080000    080459  1675209899  ...  23117.4  0.000320   1536    0
1537  20230201   080500    080959  1675210199  ...  23051.3 -0.002750   1537    1

[5 rows x 11 columns]
2023-02-01 08:10:01,691:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Feb/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=18, self.factor=0.45615024228504414, self.count=19505 

self.closeSec=1675210499, self.tradeDate='20230201', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23063.2, self.close=23084.6, self.high=23089.2, self.low=23027.8 
2023-02-01 08:15:00,777:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1675210499, self.tradeDate='20230201', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23063.2, self.close=23084.6, self.high=23089.2, self.low=23027.8   
2023-02-01 08:15:00,820:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230201   075000    075459  1675209299  ...  23117.7  0.000679   1534    4
1535  20230201   075500    075959  1675209599  ...  23116.0 -0.001063   1535    5
1536  20230201   080000    080459  1675209899  ...  23117.4  0.000320   1536    0
1537  20230201   080500    080959  1675210199  ...  23051.3 -0.002750   1537    1
1538  20230201   081000    081459  1675210499  ...  23027.8  0.000928   1538    2

[5 rows x 11 columns]
2023-02-01 08:15:00,820:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-01 08:00:34,079:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230201    052959  23090.4  ...  50.000000  0.476514  0.318688
5771  20230201    055959  22982.8  ...  49.583333  0.467863  0.335514
5772  20230201    062959  22944.0  ...  49.583333  0.456450  0.358418
5773  20230201    065959  22891.5  ...  50.000000  0.521574  0.351501
5774  20230201    072959  23178.5  ...  50.000000  0.504807  0.353792

[5 rows x 33 columns]
0.5415896487985212
acc is : 0.5415896487985212
2023-02-01 08:00:34,241:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.476049  0.523951       0  ...  0.978711   1.0    0.0  1.076117
537     1  0.485530  0.514470       0  ...  0.976471   1.0    0.0  1.073655
538     1  0.475893  0.524107       1  ...  0.988718   1.0    0.0  1.087120
539     0  0.563313  0.436687       0  ...  0.985391   1.0    0.0  1.083462
540     1  0.496413  0.503587       1  ...  0.986193   1.0    0.0  1.084344

[5 rows x 10 columns]
2023-02-01 08:00:34,270:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.478398  0.521602       0  ...  0.953812   1.0    0.0  1.085351
46     1  0.487087  0.512913       0  ...  0.951629   1.0    0.0  1.079090
47     1  0.476728  0.523272       1  ...  0.963564   1.0    0.0  1.087584
48     0  0.563313  0.436687       0  ...  0.985391   1.0    0.0  1.083462
49     1  0.496413  0.503587       1  ...  0.986193   1.0    0.0  1.084344

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '30.955', 'enterprice': '23100.3', 'countrevence': '0', 'unrealprofit': '752.2065', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23124.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230201   074000    074959  1675208999  23118.8  23128.3  0.000407
2023-02-01 07:50:00,528:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9751 

self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23129.3', self.close='23119.4'
2023-02-01 08:00:01,957:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23129.3', self.close='23119.4'
2023-02-01 08:00:01,984:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230201   071000    071959  1675207199  23112.2    23112 -0.000009
620  20230201   072000    072959  1675207799    23112  23100.6 -0.000493
621  20230201   073000    073959  1675208399  23100.5  23118.9  0.000792
622  20230201   074000    074959  1675208999  23118.8  23128.3  0.000407
623  20230201   075000    075959  1675209599  23129.3  23119.4 -0.000385
2023-02-01 08:00:01,984:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9752 

self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23119.5', self.close='23063.2'
2023-02-01 08:10:01,767:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23119.5', self.close='23063.2'
2023-02-01 08:10:01,816:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230201   072000    072959  1675207799    23112  23100.6 -0.000493
621  20230201   073000    073959  1675208399  23100.5  23118.9  0.000792
622  20230201   074000    074959  1675208999  23118.8  23128.3  0.000407
623  20230201   075000    075959  1675209599  23129.3  23119.4 -0.000385
624  20230201   080000    080959  1675210199  23119.5  23063.2 -0.002431
2023-02-01 08:10:01,816:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230201   074000    074959  1675208999  23118.8  23128.3
2023-02-01 07:50:00,586:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9752 

self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23129.3', self.close='23119.4'
2023-02-01 08:00:02,011:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23129.3', self.close='23119.4'
2023-02-01 08:00:02,037:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230201   071000    071959  1675207199  23112.2    23112
17468  20230201   072000    072959  1675207799    23112  23100.6
17469  20230201   073000    073959  1675208399  23100.5  23118.9
17470  20230201   074000    074959  1675208999  23118.8  23128.3
17471  20230201   075000    075959  1675209599  23129.3  23119.4
2023-02-01 08:00:02,038:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9753 

self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23119.5', self.close='23063.2'
2023-02-01 08:10:01,794:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23119.5', self.close='23063.2'
2023-02-01 08:10:01,825:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230201   072000    072959  1675207799    23112  23100.6
17469  20230201   073000    073959  1675208399  23100.5  23118.9
17470  20230201   074000    074959  1675208999  23118.8  23128.3
17471  20230201   075000    075959  1675209599  23129.3  23119.4
17472  20230201   080000    080959  1675210199  23119.5  23063.2
2023-02-01 08:10:01,825:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230201   074000    074959  1675208999  23118.8  23128.3
2023-02-01 07:50:00,573:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9752 

self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='23129.3', self.close='23119.4'
2023-02-01 08:00:01,968:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='23129.3', self.close='23119.4'
2023-02-01 08:00:01,997:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230201   071000    071959  1675207199  23112.2    23112
12140  20230201   072000    072959  1675207799    23112  23100.6
12141  20230201   073000    073959  1675208399  23100.5  23118.9
12142  20230201   074000    074959  1675208999  23118.8  23128.3
12143  20230201   075000    075959  1675209599  23129.3  23119.4
2023-02-01 08:00:01,997:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [01/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9753 

self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23119.5', self.close='23063.2'
2023-02-01 08:10:01,761:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23119.5', self.close='23063.2'
2023-02-01 08:10:01,804:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230201   072000    072959  1675207799    23112  23100.6
12141  20230201   073000    073959  1675208399  23100.5  23118.9
12142  20230201   074000    074959  1675208999  23118.8  23128.3
12143  20230201   075000    075959  1675209599  23129.3  23119.4
12144  20230201   080000    080959  1675210199  23119.5  23063.2
2023-02-01 08:10:01,804:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14936
self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=23126.8, self.close=23063.2, self.high=23129.0, self.low=23051.3, self.vol=3383.69, self.amt=78104232.6326 
127.0.0.1 - - [01/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-02-01 08:10:01,710:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230201   074500    074959  ...         0.0        0.0       0
5854  20230201   075000    075459  ...         0.0        0.0       0
5855  20230201   075500    075959  ...         0.0        0.0       0
5856  20230201   080000    080459  ...         0.0        0.0       0
5857  20230201   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 08:10:01,711:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675210199, self.tradeDate='20230201', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=23126.8, self.close=23063.2, self.high=23129.0, self.low=23051.3, self.vol=3383.69, self.amt=78104232.6326, ukdf['pct'].iloc[-1]=-0.00275 , ukdf['amount'].iloc[-1]=78104232.6326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Feb/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=14937
self.closeSec=1675210499, self.tradeDate='20230201', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=23063.2, self.close=23084.6, self.high=23089.2, self.low=23027.8, self.vol=2654.984, self.amt=61219417.0642 
2023-02-01 08:15:00,863:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230201   075000    075459  ...         0.0        0.0       0
5855  20230201   075500    075959  ...         0.0        0.0       0
5856  20230201   080000    080459  ...         0.0        0.0       0
5857  20230201   080500    080959  ...         0.0        0.0       0
5858  20230201   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-01 08:15:00,871:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1675210499, self.tradeDate='20230201', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=23063.2, self.close=23084.6, self.high=23089.2, self.low=23027.8, self.vol=2654.984, self.amt=61219417.0642, ukdf['pct'].iloc[-1]=0.000928 , ukdf['amount'].iloc[-1]=61219417.0642, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230131   200000    235959  1675180799  ...    719  0.665860  0.579371     NaN
720  20230201   000000    035959  1675195199  ...    720  0.649389  0.538291     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-21212.03567051124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23155.69912559', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [01/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=922527.2457035999, self.flagDict['side']='buy', self.tradeCount=16, self.count=406
self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23154.6, self.close=23119.4, self.high=23330.0, self.low=22804.0, self.vol=105553.545, self.amt=2432204759.64328 
2023-02-01 08:00:01,885:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1675209599, self.tradeDate='20230201', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23154.6, self.close=23119.4, self.high=23330.0, self.low=22804.0, self.vol=105553.545, self.amt=2432204759.64328 
2023-02-01 08:00:01,929:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230131   120000    155959  ...   43431.989  9.923849e+08  0.006177
718  20230131   160000    195959  ...   46060.100  1.054003e+09 -0.004824
719  20230131   200000    235959  ...  113354.585  2.613078e+09  0.011244
720  20230201   000000    035959  ...   49408.861  1.142916e+09  0.001761
721  20230201   040000    075959  ...  105553.545  2.432205e+09 -0.001520

[5 rows x 11 columns]
2023-02-01 08:00:03,958:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230131   120000    155959  1675151999  ...    717  0.655813  0.534550     NaN
718  20230131   160000    195959  1675166399  ...    718  0.678704  0.609307     1.0
719  20230131   200000    235959  1675180799  ...    719  0.665860  0.579371     NaN
720  20230201   000000    035959  1675195199  ...    720  0.649389  0.538291     NaN
721  20230201   040000    075959  1675209599  ...    721  0.611552  0.441319     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '38.964', 'enterprice': '23700.1', 'countrevence': '0', 'unrealprofit': '-22505.78453444628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23122.49542823', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


