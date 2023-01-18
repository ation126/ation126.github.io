# 20230118 08:16:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14906
self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=21166.8, self.close=21164.9, self.high=21185.0, self.low=21158.1, self.vol=1109.513, self.amt=23489735.2558 
2023-01-18 08:10:01,507:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230118   074500    074959  ...         0.0        0.0       0
5854  20230118   075000    075459  ...         0.0        0.0       0
5855  20230118   075500    075959  ...         0.0        0.0       0
5856  20230118   080000    080459  ...         0.0        0.0       0
5857  20230118   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 08:10:01,508:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=21166.8, self.close=21164.9, self.high=21185.0, self.low=21158.1, self.vol=1109.513, self.amt=23489735.2558, ukdf['pct'].iloc[-1]=-9e-05 , ukdf['amount'].iloc[-1]=23489735.2558, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-279030.188515264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21166.201564', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=14907
self.closeSec=1674000899, self.tradeDate='20230118', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=21164.9, self.close=21114.7, self.high=21165.5, self.low=21104.0, self.vol=1918.098, self.amt=40524751.8333 
127.0.0.1 - - [18/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 08:15:00,732:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230118   075000    075459  ...         0.0        0.0       0
5855  20230118   075500    075959  ...         0.0        0.0       0
5856  20230118   080000    080459  ...         0.0        0.0       0
5857  20230118   080500    080959  ...         0.0        0.0       0
5858  20230118   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 08:15:00,733:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1674000899, self.tradeDate='20230118', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=21164.9, self.close=21114.7, self.high=21165.5, self.low=21104.0, self.vol=1918.098, self.amt=40524751.8333, ukdf['pct'].iloc[-1]=-0.002372 , ukdf['amount'].iloc[-1]=40524751.8333, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-276050.92171781792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21116.69234442', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=21166.8, self.close=21164.9, self.high=21185.0, self.low=21158.1 
2023-01-18 08:10:01,442:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=21166.8, self.close=21164.9, self.high=21185.0, self.low=21158.1   
127.0.0.1 - - [18/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 08:10:01,474:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1533  20230118   074500    074959  1673999399  ...  21124.3  0.000033   1533    3
1534  20230118   075000    075459  1673999699  ...  21145.1 -0.000846   1534    4
1535  20230118   075500    075959  1673999999  ...  21123.1 -0.000766   1535    5
1536  20230118   080000    080459  1674000299  ...  21118.7  0.001699   1536    0
1537  20230118   080500    080959  1674000599  ...  21158.1 -0.000090   1537    1

[5 rows x 11 columns]
2023-01-18 08:10:01,474:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=495, self.factor=0.46463082183010157, self.count=15473 

self.closeSec=1674000899, self.tradeDate='20230118', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=21164.9, self.close=21114.7, self.high=21165.5, self.low=21104.0 
2023-01-18 08:15:00,646:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1674000899, self.tradeDate='20230118', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=21164.9, self.close=21114.7, self.high=21165.5, self.low=21104.0   
127.0.0.1 - - [18/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
2023-01-18 08:15:00,697:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230118   075000    075459  1673999699  ...  21145.1 -0.000846   1534    4
1535  20230118   075500    075959  1673999999  ...  21123.1 -0.000766   1535    5
1536  20230118   080000    080459  1674000299  ...  21118.7  0.001699   1536    0
1537  20230118   080500    080959  1674000599  ...  21158.1 -0.000090   1537    1
1538  20230118   081000    081459  1674000899  ...  21104.0 -0.002372   1538    2

[5 rows x 11 columns]
2023-01-18 08:15:00,697:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-01-18 08:00:34,336:DEBUG:logic:main.py:456:getModel:726423: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230118    052959  21393.6  ...  52.083333  0.560182  0.428607
5771  20230118    055959  21328.1  ...  51.666667  0.554878  0.434079
5772  20230118    062959  21307.7  ...  51.666667  0.553763  0.441587
5773  20230118    065959  21303.5  ...  51.250000  0.535412  0.456552
5774  20230118    072959  21229.9  ...  51.250000  0.531840  0.472101

[5 rows x 33 columns]
0.5194085027726433
acc is : 0.5194085027726433
2023-01-18 08:00:34,533:INFO:logic:main.py:461:getModel:726423: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.493959  0.506041       0  ...  1.058347   1.0    0.0  1.266919
537     1  0.499974  0.500026       0  ...  1.058129   1.0    0.0  1.266657
538     0  0.502435  0.497565       0  ...  1.054478   1.0    0.0  1.262287
539     1  0.477671  0.522329       0  ...  1.053753   1.0    0.0  1.261419
540     1  0.484916  0.515084       0  ...  1.049427   1.0    0.0  1.256240

[5 rows x 10 columns]
2023-01-18 08:00:34,572:INFO:logic:main.py:471:getModel:726423: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494114  0.505886       0  ...  1.058347   1.0    0.0  1.265752
46     1  0.499899  0.500101       0  ...  1.058129   1.0    0.0  1.267645
47     0  0.502505  0.497495       0  ...  1.054478   1.0    0.0  1.262144
48     1  0.477613  0.522387       0  ...  1.053753   1.0    0.0  1.261419
49     1  0.484916  0.515084       0  ...  1.049427   1.0    0.0  1.256240

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

622  20230118   074000    074959  1673999399    21182    21165 -0.000803
2023-01-18 07:50:00,610:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7735 

self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21168.5', self.close='21130.9'
2023-01-18 08:00:01,606:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21168.5', self.close='21130.9'
2023-01-18 08:00:01,652:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
619  20230118   071000    071959  1673997599  21263.3  21239.2 -0.001331
620  20230118   072000    072959  1673998199  21239.9  21215.3 -0.001125
621  20230118   073000    073959  1673998799  21215.2    21182 -0.001570
622  20230118   074000    074959  1673999399    21182    21165 -0.000803
623  20230118   075000    075959  1673999999  21168.5  21130.9 -0.001611
2023-01-18 08:00:01,652:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7736 

self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21130.8', self.close='21164.9'
2023-01-18 08:10:01,534:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21130.8', self.close='21164.9'
2023-01-18 08:10:01,562:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230118   072000    072959  1673998199  21239.9  21215.3 -0.001125
621  20230118   073000    073959  1673998799  21215.2    21182 -0.001570
622  20230118   074000    074959  1673999399    21182    21165 -0.000803
623  20230118   075000    075959  1673999999  21168.5  21130.9 -0.001611
624  20230118   080000    080959  1674000599  21130.8  21164.9  0.001609
2023-01-18 08:10:01,562:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/pyemd/log.txt ----- -----

17470  20230118   074000    074959  1673999399    21182    21165
2023-01-18 07:50:00,666:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7736 

self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21168.5', self.close='21130.9'
127.0.0.1 - - [18/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-18 08:00:01,628:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21168.5', self.close='21130.9'
2023-01-18 08:00:01,692:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17467  20230118   071000    071959  1673997599  21263.3  21239.2
17468  20230118   072000    072959  1673998199  21239.9  21215.3
17469  20230118   073000    073959  1673998799  21215.2    21182
17470  20230118   074000    074959  1673999399    21182    21165
17471  20230118   075000    075959  1673999999  21168.5  21130.9
2023-01-18 08:00:01,692:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7737 

self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21130.8', self.close='21164.9'
2023-01-18 08:10:01,544:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21130.8', self.close='21164.9'
127.0.0.1 - - [18/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 08:10:01,561:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230118   072000    072959  1673998199  21239.9  21215.3
17469  20230118   073000    073959  1673998799  21215.2    21182
17470  20230118   074000    074959  1673999399    21182    21165
17471  20230118   075000    075959  1673999999  21168.5  21130.9
17472  20230118   080000    080959  1674000599  21130.8  21164.9
2023-01-18 08:10:01,561:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12142  20230118   074000    074959  1673999399    21182    21165
2023-01-18 07:50:00,640:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7736 

self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='21168.5', self.close='21130.9'
2023-01-18 08:00:01,610:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='075000', self.closeTime='075959',self.symbol='BTCUSDT',self.open='21168.5', self.close='21130.9'
2023-01-18 08:00:01,684:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12139  20230118   071000    071959  1673997599  21263.3  21239.2
12140  20230118   072000    072959  1673998199  21239.9  21215.3
12141  20230118   073000    073959  1673998799  21215.2    21182
12142  20230118   074000    074959  1673999399    21182    21165
12143  20230118   075000    075959  1673999999  21168.5  21130.9
2023-01-18 08:00:01,689:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7737 

self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21130.8', self.close='21164.9'
2023-01-18 08:10:01,518:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21130.8', self.close='21164.9'
2023-01-18 08:10:01,554:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230118   072000    072959  1673998199  21239.9  21215.3
12141  20230118   073000    073959  1673998799  21215.2    21182
12142  20230118   074000    074959  1673999399    21182    21165
12143  20230118   075000    075959  1673999999  21168.5  21130.9
12144  20230118   080000    080959  1674000599  21130.8  21164.9
2023-01-18 08:10:01,555:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10904
self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=21166.8, self.close=21164.9, self.high=21185.0, self.low=21158.1, self.vol=1109.513, self.amt=23489735.2558 
127.0.0.1 - - [18/Jan/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-01-18 08:10:01,494:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5853  20230118   074500    074959  ...         0.0        0.0       0
5854  20230118   075000    075459  ...         0.0        0.0       0
5855  20230118   075500    075959  ...         0.0        0.0       0
5856  20230118   080000    080459  ...         0.0        0.0       0
5857  20230118   080500    080959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 08:10:01,494:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674000599, self.tradeDate='20230118', self.openTime='080500', self.closeTime='080959',self.symbol='BTCUSDT',self.open=21166.8, self.close=21164.9, self.high=21185.0, self.low=21158.1, self.vol=1109.513, self.amt=23489735.2558, ukdf['pct'].iloc[-1]=-9e-05 , ukdf['amount'].iloc[-1]=23489735.2558, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5857, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [18/Jan/2023 08:15:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=10905
self.closeSec=1674000899, self.tradeDate='20230118', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=21164.9, self.close=21114.7, self.high=21165.5, self.low=21104.0, self.vol=1918.098, self.amt=40524751.8333 
2023-01-18 08:15:00,728:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5854  20230118   075000    075459  ...         0.0        0.0       0
5855  20230118   075500    075959  ...         0.0        0.0       0
5856  20230118   080000    080459  ...         0.0        0.0       0
5857  20230118   080500    080959  ...         0.0        0.0       0
5858  20230118   081000    081459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-01-18 08:15:00,728:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1674000899, self.tradeDate='20230118', self.openTime='081000', self.closeTime='081459',self.symbol='BTCUSDT',self.open=21164.9, self.close=21114.7, self.high=21165.5, self.low=21104.0, self.vol=1918.098, self.amt=40524751.8333, ukdf['pct'].iloc[-1]=-0.002372 , ukdf['amount'].iloc[-1]=40524751.8333, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5858, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230117   200000    235959  1673971199  ...    719  0.515810 -0.841899    -1.0
720  20230118   000000    035959  1673985599  ...    720  0.363703 -1.263897    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '-8699.4312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21337.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1079553.1119543002, self.flagDict['side']='sell', self.tradeCount=13, self.count=322
self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21337.3, self.close=21128.2, self.high=21410.8, self.low=21123.1, self.vol=56117.691, self.amt=1193677679.6111 
127.0.0.1 - - [18/Jan/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-01-18 08:00:01,236:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1673999999, self.tradeDate='20230118', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21337.3, self.close=21128.2, self.high=21410.8, self.low=21123.1, self.vol=56117.691, self.amt=1193677679.6111 
2023-01-18 08:00:01,269:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230117   120000    155959  ...   40393.627  8.539123e+08  0.000241
718  20230117   160000    195959  ...   49711.091  1.052226e+09  0.003970
719  20230117   200000    235959  ...  233118.482  4.958880e+09 -0.002022
720  20230118   000000    035959  ...   86362.443  1.834486e+09  0.007627
721  20230118   040000    075959  ...   56117.691  1.193678e+09 -0.009795

[5 rows x 11 columns]
2023-01-18 08:00:03,344:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230117   120000    155959  1673942399  ...    717  0.774235 -0.117167     NaN
718  20230117   160000    195959  1673956799  ...    718  0.635010 -0.505098     NaN
719  20230117   200000    235959  1673971199  ...    719  0.515810 -0.841899    -1.0
720  20230118   000000    035959  1673985599  ...    720  0.363703 -1.263897    -1.0
721  20230118   040000    075959  1673999999  ...    721  0.123877 -1.893662    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.053', 'enterprice': '21166.9', 'countrevence': '0', 'unrealprofit': '1837.908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21130.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


