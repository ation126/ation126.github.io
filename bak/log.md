# 20221222 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [22/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7130
self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16821.0, self.close=16816.1, self.high=16826.7, self.low=16813.9, self.vol=648.477, self.amt=10907404.6746 
2022-12-22 08:10:01,505:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221222   074500    074959  ...         0.0        0.0       0
5854  20221222   075000    075459  ...         0.0        0.0       0
5855  20221222   075500    075959  ...         0.0        0.0       0
5856  20221222   080000    080459  ...         0.0        0.0       0
5857  20221222   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 08:10:01,507:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16821.0, self.close=16816.1, self.high=16826.7, self.low=16813.9, self.vol=648.477, self.amt=10907404.6746, ukdf['pct'].iloc[-1]=-0.000285 , ukdf['amount'].iloc[-1]=10907404.6746, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17392.7574769544', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16818.33146565', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=7131
self.closeSec=1671668099, self.tradeDate='20221222', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16816.1, self.close=16815.0, self.high=16822.3, self.low=16813.0, self.vol=294.873, self.amt=4958965.2819 
127.0.0.1 - - [22/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-22 08:15:00,599:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221222   075000    075459  ...         0.0        0.0       0
5855  20221222   075500    075959  ...         0.0        0.0       0
5856  20221222   080000    080459  ...         0.0        0.0       0
5857  20221222   080500    080959  ...         0.0        0.0       0
5858  20221222   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 08:15:00,600:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1671668099, self.tradeDate='20221222', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16816.1, self.close=16815.0, self.high=16822.3, self.low=16813.0, self.vol=294.873, self.amt=4958965.2819, ukdf['pct'].iloc[-1]=-6.5e-05 , ukdf['amount'].iloc[-1]=4958965.2819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-17198.3008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16815.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16821.0, self.close=16816.1, self.high=16826.7, self.low=16813.9 
2022-12-22 08:10:01,444:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16821.0, self.close=16816.1, self.high=16826.7, self.low=16813.9   
127.0.0.1 - - [22/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 08:10:01,482:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20221222   074500    074959  1671666599  ...  16784.9  0.000202   1533    3
1534  20221222   075000    075459  1671666899  ...  16796.0 -0.000101   1534    4
1535  20221222   075500    075959  1671667199  ...  16797.0  0.001345   1535    5
1536  20221222   080000    080459  1671667499  ...  16810.4  0.000077   1536    0
1537  20221222   080500    080959  1671667799  ...  16813.9 -0.000285   1537    1

[5 rows x 11 columns]
2022-12-22 08:10:01,483:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=38, self.factor=0.5090459662323797, self.count=7697 

self.closeSec=1671668099, self.tradeDate='20221222', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16816.1, self.close=16815.0, self.high=16822.3, self.low=16813.0 
2022-12-22 08:15:00,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1671668099, self.tradeDate='20221222', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16816.1, self.close=16815.0, self.high=16822.3, self.low=16813.0   
127.0.0.1 - - [22/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-22 08:15:00,578:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20221222   075000    075459  1671666899  ...  16796.0 -0.000101   1534    4
1535  20221222   075500    075959  1671667199  ...  16797.0  0.001345   1535    5
1536  20221222   080000    080459  1671667499  ...  16810.4  0.000077   1536    0
1537  20221222   080500    080959  1671667799  ...  16813.9 -0.000285   1537    1
1538  20221222   081000    081459  1671668099  ...  16813.0 -0.000065   1538    2

[5 rows x 11 columns]
2022-12-22 08:15:00,584:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2022-12-22 08:00:20,316:DEBUG:logic:main.py:454:getModel:174970: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20221222    052959  16773.5  ...  50.000000  0.495272  0.572538
5771  20221222    055959  16785.4  ...  50.416667  0.495633  0.574310
5772  20221222    062959  16786.5  ...  50.000000  0.484140  0.583501
5773  20221222    065959  16760.3  ...  50.000000  0.483216  0.592688
5774  20221222    072959  16758.3  ...  50.416667  0.490209  0.596973

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2022-12-22 08:00:20,427:INFO:logic:main.py:459:getModel:174970: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498777  0.501223       1  ...  1.097033   1.0    0.0  0.977147
537     1  0.497169  0.502831       0  ...  1.095334   1.0    0.0  0.975633
538     1  0.489660  0.510340       0  ...  1.095196   1.0    0.0  0.975511
539     1  0.495397  0.504603       1  ...  1.096163   1.0    0.0  0.976372
540     1  0.498141  0.501859       1  ...  1.099313   1.0    0.0  0.979178

[5 rows x 10 columns]
2022-12-22 08:00:20,450:INFO:logic:main.py:469:getModel:174970: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.498671  0.501329       1  ...  1.097033   1.0    0.0  0.975936
46     1  0.497280  0.502720       0  ...  1.095334   1.0    0.0  0.975758
47     1  0.489565  0.510435       0  ...  1.095196   1.0    0.0  0.975454
48     1  0.495544  0.504456       1  ...  1.096163   1.0    0.0  0.976372
49     1  0.498141  0.501859       1  ...  1.099313   1.0    0.0  0.979178

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.528', 'enterprice': '16701.5', 'countrevence': '0', 'unrealprofit': '4881.94381262304', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '16816.29363743', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20221222   074000    074959  1671666599  16795.3  16798.6  0.000202
2022-12-22 07:50:00,575:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3847 

self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16798.7', self.close='16821.3'
2022-12-22 08:00:01,314:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16798.7', self.close='16821.3'
2022-12-22 08:00:01,350:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20221222   071000    071959  1671664799  16765.9  16784.4  0.001103
620  20221222   072000    072959  1671665399  16784.7  16773.1 -0.000673
621  20221222   073000    073959  1671665999    16773  16795.2  0.001318
622  20221222   074000    074959  1671666599  16795.3  16798.6  0.000202
623  20221222   075000    075959  1671667199  16798.7  16821.3  0.001351
2022-12-22 08:00:01,350:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3848 

self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16819.7', self.close='16813.9'
2022-12-22 08:10:01,583:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16819.7', self.close='16813.9'
2022-12-22 08:10:01,607:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20221222   072000    072959  1671665399  16784.7  16773.1 -0.000673
621  20221222   073000    073959  1671665999    16773  16795.2  0.001318
622  20221222   074000    074959  1671666599  16795.3  16798.6  0.000202
623  20221222   075000    075959  1671667199  16798.7  16821.3  0.001351
624  20221222   080000    080959  1671667799  16819.7  16813.9 -0.000440
2022-12-22 08:10:01,607:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20221222   074000    074959  1671666599  16795.3  16798.6
2022-12-22 07:50:00,581:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3848 

self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16798.7', self.close='16821.3'
2022-12-22 08:00:01,303:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16798.7', self.close='16821.3'
2022-12-22 08:00:01,340:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20221222   071000    071959  1671664799  16765.9  16784.4
17468  20221222   072000    072959  1671665399  16784.7  16773.1
17469  20221222   073000    073959  1671665999    16773  16795.2
17470  20221222   074000    074959  1671666599  16795.3  16798.6
17471  20221222   075000    075959  1671667199  16798.7  16821.3
2022-12-22 08:00:01,340:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3849 

self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16819.7', self.close='16813.9'
2022-12-22 08:10:01,565:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16819.7', self.close='16813.9'
2022-12-22 08:10:01,610:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20221222   072000    072959  1671665399  16784.7  16773.1
17469  20221222   073000    073959  1671665999    16773  16795.2
17470  20221222   074000    074959  1671666599  16795.3  16798.6
17471  20221222   075000    075959  1671667199  16798.7  16821.3
17472  20221222   080000    080959  1671667799  16819.7  16813.9
2022-12-22 08:10:01,610:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20221222   074000    074959  1671666599  16795.3  16798.6
2022-12-22 07:50:00,580:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3848 

self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='16798.7', self.close='16821.3'
2022-12-22 08:00:01,317:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='16798.7', self.close='16821.3'
2022-12-22 08:00:01,347:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20221222   071000    071959  1671664799  16765.9  16784.4
12140  20221222   072000    072959  1671665399  16784.7  16773.1
12141  20221222   073000    073959  1671665999    16773  16795.2
12142  20221222   074000    074959  1671666599  16795.3  16798.6
12143  20221222   075000    075959  1671667199  16798.7  16821.3
2022-12-22 08:00:01,347:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [22/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3849 

self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='16819.7', self.close='16813.9'
2022-12-22 08:10:01,566:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='16819.7', self.close='16813.9'
2022-12-22 08:10:01,605:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20221222   072000    072959  1671665399  16784.7  16773.1
12141  20221222   073000    073959  1671665999    16773  16795.2
12142  20221222   074000    074959  1671666599  16795.3  16798.6
12143  20221222   075000    075959  1671667199  16798.7  16821.3
12144  20221222   080000    080959  1671667799  16819.7  16813.9
2022-12-22 08:10:01,605:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3128
self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=16821.0, self.close=16816.1, self.high=16826.7, self.low=16813.9, self.vol=648.477, self.amt=10907404.6746 
127.0.0.1 - - [22/Dec/2022 08:10:01] "POST / HTTP/1.1" 200 -
2022-12-22 08:10:01,499:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20221222   074500    074959  ...         0.0        0.0       0
5854  20221222   075000    075459  ...         0.0        0.0       0
5855  20221222   075500    075959  ...         0.0        0.0       0
5856  20221222   080000    080459  ...         0.0        0.0       0
5857  20221222   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 08:10:01,499:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671667799, self.tradeDate='20221222', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=16821.0, self.close=16816.1, self.high=16826.7, self.low=16813.9, self.vol=648.477, self.amt=10907404.6746, ukdf['pct'].iloc[-1]=-0.000285 , ukdf['amount'].iloc[-1]=10907404.6746, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=3129
self.closeSec=1671668099, self.tradeDate='20221222', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=16816.1, self.close=16815.0, self.high=16822.3, self.low=16813.0, self.vol=294.873, self.amt=4958965.2819 
127.0.0.1 - - [22/Dec/2022 08:15:00] "POST / HTTP/1.1" 200 -
2022-12-22 08:15:00,632:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20221222   075000    075459  ...         0.0        0.0       0
5855  20221222   075500    075959  ...         0.0        0.0       0
5856  20221222   080000    080459  ...         0.0        0.0       0
5857  20221222   080500    080959  ...         0.0        0.0       0
5858  20221222   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2022-12-22 08:15:00,633:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1671668099, self.tradeDate='20221222', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=16816.1, self.close=16815.0, self.high=16822.3, self.low=16813.0, self.vol=294.873, self.amt=4958965.2819, ukdf['pct'].iloc[-1]=-6.5e-05 , ukdf['amount'].iloc[-1]=4958965.2819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20221221   200000    235959  1671638399  ...    719  0.037568 -2.003620    -1.0
720  20221222   000000    035959  1671652799  ...    720  0.037600 -1.940573    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-1130.02247168756', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16744.27257123', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=891652.7479068, self.flagDict['side']='sell', self.tradeCount=7, self.count=160
self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=16746.9, self.close=16824.6, self.high=16830.7, self.low=16721.0, self.vol=26341.897, self.amt=441750790.639 
127.0.0.1 - - [22/Dec/2022 08:00:01] "POST / HTTP/1.1" 200 -
2022-12-22 08:00:01,208:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1671667199, self.tradeDate='20221222', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=16746.9, self.close=16824.6, self.high=16830.7, self.low=16721.0, self.vol=26341.897, self.amt=441750790.639 
2022-12-22 08:00:01,245:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20221221   120000    155959  ...  27534.062  4.629347e+08 -0.001224
718  20221221   160000    195959  ...  31332.466  5.279092e+08  0.003754
719  20221221   200000    235959  ...  72649.874  1.222429e+09 -0.001049
720  20221222   000000    035959  ...  36319.230  6.097925e+08 -0.006396
721  20221222   040000    075959  ...  26341.897  4.417508e+08  0.004646

[5 rows x 11 columns]
2022-12-22 08:00:02,734:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20221221   120000    155959  1671609599  ...    717  0.031652 -2.167219    -1.0
718  20221221   160000    195959  1671623999  ...    718  0.036194 -2.077497    -1.0
719  20221221   200000    235959  1671638399  ...    719  0.037568 -2.003620    -1.0
720  20221222   000000    035959  1671652799  ...    720  0.037600 -1.940573    -1.0
721  20221222   040000    075959  1671667199  ...    721  0.036546 -1.883876    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.372', 'enterprice': '16723.1', 'countrevence': '0', 'unrealprofit': '-5150.398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '16819.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


