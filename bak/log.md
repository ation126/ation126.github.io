# 20230307 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [07/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28732
self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22392.0, self.close=22394.7, self.high=22397.3, self.low=22382.1, self.vol=419.145, self.amt=9384067.134 
2023-03-07 08:20:01,920:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230307   075500    075959  ...         0.0        0.0       0
5856  20230307   080000    080459  ...         0.0        0.0       0
5857  20230307   080500    080959  ...         0.0        0.0       0
5858  20230307   081000    081459  ...         0.0        0.0       0
5859  20230307   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 08:20:01,923:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22392.0, self.close=22394.7, self.high=22397.3, self.low=22382.1, self.vol=419.145, self.amt=9384067.134, ukdf['pct'].iloc[-1]=0.000116 , ukdf['amount'].iloc[-1]=9384067.134, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-352950.2928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22394.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28733
self.closeSec=1678148699, self.tradeDate='20230307', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22394.6, self.close=22392.7, self.high=22397.2, self.low=22391.3, self.vol=319.41, self.amt=7152903.6551 
2023-03-07 08:25:01,575:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230307   080000    080459  ...         0.0        0.0       0
5857  20230307   080500    080959  ...         0.0        0.0       0
5858  20230307   081000    081459  ...         0.0        0.0       0
5859  20230307   081500    081959  ...         0.0        0.0       0
5860  20230307   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 08:25:01,575:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678148699, self.tradeDate='20230307', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22394.6, self.close=22392.7, self.high=22397.2, self.low=22391.3, self.vol=319.41, self.amt=7152903.6551, ukdf['pct'].iloc[-1]=-8.9e-05 , ukdf['amount'].iloc[-1]=7152903.6551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-352855.03441104064', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22393.01700364', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=84, self.factor=0.5660135726547264, self.count=29298 

self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22392.0, self.close=22394.7, self.high=22397.3, self.low=22382.1 
2023-03-07 08:20:01,557:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22392.0, self.close=22394.7, self.high=22397.3, self.low=22382.1   
2023-03-07 08:20:01,601:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230307   075500    075959  1678147199  ...  22390.2  0.000058   1535    5
1536  20230307   080000    080459  1678147499  ...  22397.0  0.000491   1536    0
1537  20230307   080500    080959  1678147799  ...  22397.8 -0.000460   1537    1
1538  20230307   081000    081459  1678148099  ...  22378.8 -0.000254   1538    2
1539  20230307   081500    081959  1678148399  ...  22382.1  0.000116   1539    3

[5 rows x 11 columns]
2023-03-07 08:20:01,603:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=84, self.factor=0.5660135726547264, self.count=29299 

self.closeSec=1678148699, self.tradeDate='20230307', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22394.6, self.close=22392.7, self.high=22397.2, self.low=22391.3 
2023-03-07 08:25:01,526:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678148699, self.tradeDate='20230307', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22394.6, self.close=22392.7, self.high=22397.2, self.low=22391.3   
2023-03-07 08:25:01,570:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230307   080000    080459  1678147499  ...  22397.0  0.000491   1536    0
1537  20230307   080500    080959  1678147799  ...  22397.8 -0.000460   1537    1
1538  20230307   081000    081459  1678148099  ...  22378.8 -0.000254   1538    2
1539  20230307   081500    081959  1678148399  ...  22382.1  0.000116   1539    3
1540  20230307   082000    082459  1678148699  ...  22391.3 -0.000089   1540    4

[5 rows x 11 columns]
2023-03-07 08:25:01,570:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-07 08:00:35,130:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230307    052959  22340.9  ...  46.250000  0.479928  0.475767
5771  20230307    055959  22371.9  ...  46.250000  0.490583  0.480806
5772  20230307    062959  22399.1  ...  46.666667  0.498219  0.489330
5773  20230307    065959  22418.8  ...  46.666667  0.500918  0.495668
5774  20230307    072959  22425.9  ...  46.250000  0.495864  0.504588

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-03-07 08:00:35,290:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.501293  0.498707       1  ...  0.933033  -1.0    0.0  0.940593
537     0  0.518425  0.481575       1  ...  0.932208  -1.0    0.0  0.941425
538     0  0.520231  0.479769       1  ...  0.931917  -1.0    0.0  0.941719
539     0  0.519547  0.480453       0  ...  0.932457  -1.0    0.0  0.941173
540     0  0.512391  0.487609       0  ...  0.933114  -1.0    0.0  0.940509

[5 rows x 10 columns]
2023-03-07 08:00:35,322:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500895  0.499105       1  ...  0.922292  -1.0    0.0  0.935635
46     0  0.518365  0.481635       1  ...  0.921477  -1.0    0.0  0.937547
47     0  0.520428  0.479572       1  ...  0.898583  -1.0    0.0  0.944280
48     0  0.519547  0.480453       0  ...  0.932457  -1.0    0.0  0.941173
49     0  0.512391  0.487609       0  ...  0.933114  -1.0    0.0  0.940509

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.561', 'enterprice': '22386.6', 'countrevence': '0', 'unrealprofit': '-577.5663', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22404.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230307   075000    075959  1678147199  22388.6  22397.1  0.000375
2023-03-07 08:00:02,325:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14648 

self.closeSec=1678147799, self.tradeDate='20230307', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22397.1', self.close='22397.8'
2023-03-07 08:10:01,721:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678147799, self.tradeDate='20230307', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22397.1', self.close='22397.8'
2023-03-07 08:10:01,775:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230307   072000    072959  1678145399  22420.5  22412.9 -0.000335
621  20230307   073000    073959  1678145999  22412.8  22394.7 -0.000812
622  20230307   074000    074959  1678146599  22394.6  22388.7 -0.000268
623  20230307   075000    075959  1678147199  22388.6  22397.1  0.000375
624  20230307   080000    080959  1678147799  22397.1  22397.8  0.000031
2023-03-07 08:10:01,775:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14649 

self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22397.8', self.close='22394.7'
127.0.0.1 - - [07/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-07 08:20:01,684:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22397.8', self.close='22394.7'
2023-03-07 08:20:01,790:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230307   073000    073959  1678145999  22412.8  22394.7 -0.000812
622  20230307   074000    074959  1678146599  22394.6  22388.7 -0.000268
623  20230307   075000    075959  1678147199  22388.6  22397.1  0.000375
624  20230307   080000    080959  1678147799  22397.1  22397.8  0.000031
625  20230307   081000    081959  1678148399  22397.8  22394.7 -0.000138
2023-03-07 08:20:01,790:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 09:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 09:30:03,026:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:00:00  070000  24795.1  ...     NaN     NaN       0
145  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
146  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
147  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
148  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 10:00:03,553:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 07:30:00  073000  24849.9  ...     NaN     NaN       0
145  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
146  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
147  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
148  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 10:30:01] "POST / HTTP/1.1" 200 -
2023-02-21 10:30:03,245:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/21 08:00:00  080000  24819.0  ...     NaN     NaN       0
145  2023/02/21 08:30:00  083000  24860.9  ...     NaN     NaN       0
146  2023/02/21 09:00:00  090000  24831.0  ...     NaN     NaN       0
147  2023/02/21 09:30:00  093000  24870.0  ...     NaN     NaN       0
148  2023/02/21 10:00:00  100000  24936.1  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

17471  20230307   075000    075959  1678147199  22388.6  22397.1
2023-03-07 08:00:02,356:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14649 

self.closeSec=1678147799, self.tradeDate='20230307', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22397.1', self.close='22397.8'
127.0.0.1 - - [07/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-07 08:10:01,740:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678147799, self.tradeDate='20230307', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22397.1', self.close='22397.8'
2023-03-07 08:10:01,772:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230307   072000    072959  1678145399  22420.5  22412.9
17469  20230307   073000    073959  1678145999  22412.8  22394.7
17470  20230307   074000    074959  1678146599  22394.6  22388.7
17471  20230307   075000    075959  1678147199  22388.6  22397.1
17472  20230307   080000    080959  1678147799  22397.1  22397.8
2023-03-07 08:10:01,772:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14650 

self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22397.8', self.close='22394.7'
127.0.0.1 - - [07/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-07 08:20:01,759:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22397.8', self.close='22394.7'
2023-03-07 08:20:01,818:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230307   073000    073959  1678145999  22412.8  22394.7
17470  20230307   074000    074959  1678146599  22394.6  22388.7
17471  20230307   075000    075959  1678147199  22388.6  22397.1
17472  20230307   080000    080959  1678147799  22397.1  22397.8
17473  20230307   081000    081959  1678148399  22397.8  22394.7
2023-03-07 08:20:01,818:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230307   075000    075959  1678147199  22388.6  22397.1
2023-03-07 08:00:02,342:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14649 

self.closeSec=1678147799, self.tradeDate='20230307', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22397.1', self.close='22397.8'
2023-03-07 08:10:01,751:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678147799, self.tradeDate='20230307', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22397.1', self.close='22397.8'
127.0.0.1 - - [07/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-07 08:10:01,777:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230307   072000    072959  1678145399  22420.5  22412.9
12141  20230307   073000    073959  1678145999  22412.8  22394.7
12142  20230307   074000    074959  1678146599  22394.6  22388.7
12143  20230307   075000    075959  1678147199  22388.6  22397.1
12144  20230307   080000    080959  1678147799  22397.1  22397.8
2023-03-07 08:10:01,777:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14650 

self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22397.8', self.close='22394.7'
127.0.0.1 - - [07/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-07 08:20:01,738:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22397.8', self.close='22394.7'
2023-03-07 08:20:01,761:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230307   073000    073959  1678145999  22412.8  22394.7
12142  20230307   074000    074959  1678146599  22394.6  22388.7
12143  20230307   075000    075959  1678147199  22388.6  22397.1
12144  20230307   080000    080959  1678147799  22397.1  22397.8
12145  20230307   081000    081959  1678148399  22397.8  22394.7
2023-03-07 08:20:01,761:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24730
self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22392.0, self.close=22394.7, self.high=22397.3, self.low=22382.1, self.vol=419.145, self.amt=9384067.134 
127.0.0.1 - - [07/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-07 08:20:01,621:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230307   075500    075959  ...         0.0        0.0       0
5856  20230307   080000    080459  ...         0.0        0.0       0
5857  20230307   080500    080959  ...         0.0        0.0       0
5858  20230307   081000    081459  ...         0.0        0.0       0
5859  20230307   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 08:20:01,638:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678148399, self.tradeDate='20230307', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22392.0, self.close=22394.7, self.high=22397.3, self.low=22382.1, self.vol=419.145, self.amt=9384067.134, ukdf['pct'].iloc[-1]=0.000116 , ukdf['amount'].iloc[-1]=9384067.134, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24731
self.closeSec=1678148699, self.tradeDate='20230307', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22394.6, self.close=22392.7, self.high=22397.2, self.low=22391.3, self.vol=319.41, self.amt=7152903.6551 
127.0.0.1 - - [07/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-07 08:25:01,574:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230307   080000    080459  ...         0.0        0.0       0
5857  20230307   080500    080959  ...         0.0        0.0       0
5858  20230307   081000    081459  ...         0.0        0.0       0
5859  20230307   081500    081959  ...         0.0        0.0       0
5860  20230307   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 08:25:01,577:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678148699, self.tradeDate='20230307', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22394.6, self.close=22392.7, self.high=22397.2, self.low=22391.3, self.vol=319.41, self.amt=7152903.6551, ukdf['pct'].iloc[-1]=-8.9e-05 , ukdf['amount'].iloc[-1]=7152903.6551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230306   200000    235959  1678118399  ...    719  0.290726 -1.003096    -1.0
720  20230307   000000    035959  1678132799  ...    720  0.192246 -1.361699    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '40854.096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22380.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=610
self.closeSec=1678147199, self.tradeDate='20230307', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22382.9, self.close=22397.1, self.high=22437.5, self.low=22307.9, self.vol=34143.09, self.amt=764152598.3988 
127.0.0.1 - - [07/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-07 08:00:02,053:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678147199, self.tradeDate='20230307', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22382.9, self.close=22397.1, self.high=22437.5, self.low=22307.9, self.vol=34143.09, self.amt=764152598.3988 
2023-03-07 08:00:02,126:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230306   120000    155959  ...  27604.231  6.175179e+08  0.000130
718  20230306   160000    195959  ...  29028.106  6.498239e+08 -0.000491
719  20230306   200000    235959  ...  69925.596  1.570430e+09  0.007765
720  20230307   000000    035959  ...  72720.927  1.633468e+09 -0.007133
721  20230307   040000    075959  ...  34143.090  7.641526e+08  0.000639

[5 rows x 11 columns]
2023-03-07 08:00:04,832:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230306   120000    155959  1678089599  ...    717  0.425069 -0.518944     NaN
718  20230306   160000    195959  1678103999  ...    718  0.359881 -0.753584    -1.0
719  20230306   200000    235959  1678118399  ...    719  0.290726 -1.003096    -1.0
720  20230307   000000    035959  1678132799  ...    720  0.192246 -1.361699    -1.0
721  20230307   040000    075959  1678147199  ...    721  0.054042 -1.859668    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '40163.082', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22397.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


