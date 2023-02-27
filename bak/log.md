# 20230227 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [27/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26428
self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23490.8, self.close=23512.1, self.high=23519.0, self.low=23486.0, self.vol=648.872, self.amt=15250457.0619 
2023-02-27 08:20:01,633:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230227   075500    075959  ...         0.0        0.0       0
5856  20230227   080000    080459  ...         0.0        0.0       0
5857  20230227   080500    080959  ...         0.0        0.0       0
5858  20230227   081000    081459  ...         0.0        0.0       0
5859  20230227   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 08:20:01,634:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23490.8, self.close=23512.1, self.high=23519.0, self.low=23486.0, self.vol=648.872, self.amt=15250457.0619, ukdf['pct'].iloc[-1]=0.000907 , ukdf['amount'].iloc[-1]=15250457.0619, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-420190.9552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23512', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26429
self.closeSec=1677457499, self.tradeDate='20230227', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23512.0, self.close=23472.0, self.high=23517.2, self.low=23467.0, self.vol=973.146, self.amt=22858516.5451 
127.0.0.1 - - [27/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-27 08:25:01,594:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230227   080000    080459  ...         0.0        0.0       0
5857  20230227   080500    080959  ...         0.0        0.0       0
5858  20230227   081000    081459  ...         0.0        0.0       0
5859  20230227   081500    081959  ...         0.0        0.0       0
5860  20230227   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 08:25:01,594:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677457499, self.tradeDate='20230227', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23512.0, self.close=23472.0, self.high=23517.2, self.low=23467.0, self.vol=973.146, self.amt=22858516.5451, ukdf['pct'].iloc[-1]=-0.001706 , ukdf['amount'].iloc[-1]=22858516.5451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-417845.88627595568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23473.02983043', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.3493689093295243, self.count=26994 

self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23490.8, self.close=23512.1, self.high=23519.0, self.low=23486.0 
2023-02-27 08:20:01,507:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23490.8, self.close=23512.1, self.high=23519.0, self.low=23486.0   
2023-02-27 08:20:01,669:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230227   075500    075959  1677455999  ...  23521.6  0.001003   1535    5
1536  20230227   080000    080459  1677456299  ...  23524.5 -0.000849   1536    0
1537  20230227   080500    080959  1677456599  ...  23462.2 -0.001603   1537    1
1538  20230227   081000    081459  1677456899  ...  23480.0  0.000136   1538    2
1539  20230227   081500    081959  1677457199  ...  23486.0  0.000907   1539    3

[5 rows x 11 columns]
2023-02-27 08:20:01,672:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.3493689093295243, self.count=26995 

self.closeSec=1677457499, self.tradeDate='20230227', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23512.0, self.close=23472.0, self.high=23517.2, self.low=23467.0 
2023-02-27 08:25:01,505:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677457499, self.tradeDate='20230227', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23512.0, self.close=23472.0, self.high=23517.2, self.low=23467.0   
127.0.0.1 - - [27/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-27 08:25:01,583:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230227   080000    080459  1677456299  ...  23524.5 -0.000849   1536    0
1537  20230227   080500    080959  1677456599  ...  23462.2 -0.001603   1537    1
1538  20230227   081000    081459  1677456899  ...  23480.0  0.000136   1538    2
1539  20230227   081500    081959  1677457199  ...  23486.0  0.000907   1539    3
1540  20230227   082000    082459  1677457499  ...  23467.0 -0.001706   1540    4

[5 rows x 11 columns]
2023-02-27 08:25:01,584:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-27 08:00:35,866:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230227    052959  23627.0  ...  47.500000  0.576428  0.184814
5771  20230227    055959  23591.0  ...  47.500000  0.564834  0.186008
5772  20230227    062959  23548.3  ...  47.083333  0.518679  0.207938
5773  20230227    065959  23363.6  ...  47.083333  0.540581  0.217026
5774  20230227    072959  23469.2  ...  47.500000  0.549223  0.220647

[5 rows x 33 columns]
0.5378927911275416
acc is : 0.5378927911275416
2023-02-27 08:00:36,032:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.515332  0.484668       0  ...  0.989908   1.0    0.0  1.033600
537     0  0.510826  0.489174       0  ...  0.982144   1.0    0.0  1.025493
538     1  0.464971  0.535029       1  ...  0.986583   1.0    0.0  1.030128
539     0  0.517067  0.482933       1  ...  0.988416   1.0    0.0  1.032042
540     0  0.506713  0.493287       1  ...  0.989782   1.0    0.0  1.033468

[5 rows x 10 columns]
2023-02-27 08:00:36,065:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515434  0.484566       0  ...  0.945111   1.0    0.0  1.032906
46     0  0.510851  0.489149       0  ...  0.982144   1.0    0.0  1.023673
47     1  0.465511  0.534489       1  ...  0.986583   1.0    0.0  1.031563
48     0  0.517067  0.482933       1  ...  0.988416   1.0    0.0  1.032042
49     0  0.506713  0.493287       1  ...  0.989782   1.0    0.0  1.033468

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.793', 'enterprice': '23035.2', 'countrevence': '0', 'unrealprofit': '17010.6883837911', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23553.9292527', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230227   075000    075959  1677455999  23537.7  23545.3  0.000319
2023-02-27 08:00:01,882:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13496 

self.closeSec=1677456599, self.tradeDate='20230227', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23545.2', self.close='23487.6'
2023-02-27 08:10:01,614:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677456599, self.tradeDate='20230227', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23545.2', self.close='23487.6'
2023-02-27 08:10:01,676:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230227   072000    072959  1677454199  23562.1  23512.8 -0.002097
621  20230227   073000    073959  1677454799  23512.8  23537.2  0.001038
622  20230227   074000    074959  1677455399    23537  23537.8  0.000025
623  20230227   075000    075959  1677455999  23537.7  23545.3  0.000319
624  20230227   080000    080959  1677456599  23545.2  23487.6 -0.002451
2023-02-27 08:10:01,679:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13497 

self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23487.6', self.close='23512.1'
127.0.0.1 - - [27/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-27 08:20:01,589:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23487.6', self.close='23512.1'
2023-02-27 08:20:01,611:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230227   073000    073959  1677454799  23512.8  23537.2  0.001038
622  20230227   074000    074959  1677455399    23537  23537.8  0.000025
623  20230227   075000    075959  1677455999  23537.7  23545.3  0.000319
624  20230227   080000    080959  1677456599  23545.2  23487.6 -0.002451
625  20230227   081000    081959  1677457199  23487.6  23512.1  0.001043
2023-02-27 08:20:01,612:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230227   075000    075959  1677455999  23537.7  23545.3
2023-02-27 08:00:01,914:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13497 

self.closeSec=1677456599, self.tradeDate='20230227', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23545.2', self.close='23487.6'
2023-02-27 08:10:01,618:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677456599, self.tradeDate='20230227', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23545.2', self.close='23487.6'
2023-02-27 08:10:01,652:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230227   072000    072959  1677454199  23562.1  23512.8
17469  20230227   073000    073959  1677454799  23512.8  23537.2
17470  20230227   074000    074959  1677455399    23537  23537.8
17471  20230227   075000    075959  1677455999  23537.7  23545.3
17472  20230227   080000    080959  1677456599  23545.2  23487.6
2023-02-27 08:10:01,652:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13498 

self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23487.6', self.close='23512.1'
2023-02-27 08:20:01,642:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23487.6', self.close='23512.1'
2023-02-27 08:20:01,693:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230227   073000    073959  1677454799  23512.8  23537.2
17470  20230227   074000    074959  1677455399    23537  23537.8
17471  20230227   075000    075959  1677455999  23537.7  23545.3
17472  20230227   080000    080959  1677456599  23545.2  23487.6
17473  20230227   081000    081959  1677457199  23487.6  23512.1
2023-02-27 08:20:01,694:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230227   075000    075959  1677455999  23537.7  23545.3
2023-02-27 08:00:01,919:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13497 

self.closeSec=1677456599, self.tradeDate='20230227', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23545.2', self.close='23487.6'
2023-02-27 08:10:01,630:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677456599, self.tradeDate='20230227', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23545.2', self.close='23487.6'
2023-02-27 08:10:01,680:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230227   072000    072959  1677454199  23562.1  23512.8
12141  20230227   073000    073959  1677454799  23512.8  23537.2
12142  20230227   074000    074959  1677455399    23537  23537.8
12143  20230227   075000    075959  1677455999  23537.7  23545.3
12144  20230227   080000    080959  1677456599  23545.2  23487.6
2023-02-27 08:10:01,680:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13498 

self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23487.6', self.close='23512.1'
2023-02-27 08:20:01,634:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23487.6', self.close='23512.1'
2023-02-27 08:20:01,687:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230227   073000    073959  1677454799  23512.8  23537.2
12142  20230227   074000    074959  1677455399    23537  23537.8
12143  20230227   075000    075959  1677455999  23537.7  23545.3
12144  20230227   080000    080959  1677456599  23545.2  23487.6
12145  20230227   081000    081959  1677457199  23487.6  23512.1
2023-02-27 08:20:01,689:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [27/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22426
self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23490.8, self.close=23512.1, self.high=23519.0, self.low=23486.0, self.vol=648.872, self.amt=15250457.0619 
2023-02-27 08:20:01,700:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230227   075500    075959  ...         0.0        0.0       0
5856  20230227   080000    080459  ...         0.0        0.0       0
5857  20230227   080500    080959  ...         0.0        0.0       0
5858  20230227   081000    081459  ...         0.0        0.0       0
5859  20230227   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 08:20:01,704:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677457199, self.tradeDate='20230227', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23490.8, self.close=23512.1, self.high=23519.0, self.low=23486.0, self.vol=648.872, self.amt=15250457.0619, ukdf['pct'].iloc[-1]=0.000907 , ukdf['amount'].iloc[-1]=15250457.0619, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22427
self.closeSec=1677457499, self.tradeDate='20230227', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23512.0, self.close=23472.0, self.high=23517.2, self.low=23467.0, self.vol=973.146, self.amt=22858516.5451 
127.0.0.1 - - [27/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-27 08:25:01,600:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230227   080000    080459  ...         0.0        0.0       0
5857  20230227   080500    080959  ...         0.0        0.0       0
5858  20230227   081000    081459  ...         0.0        0.0       0
5859  20230227   081500    081959  ...         0.0        0.0       0
5860  20230227   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-27 08:25:01,601:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677457499, self.tradeDate='20230227', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23512.0, self.close=23472.0, self.high=23517.2, self.low=23467.0, self.vol=973.146, self.amt=22858516.5451, ukdf['pct'].iloc[-1]=-0.001706 , ukdf['amount'].iloc[-1]=22858516.5451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230226   200000    235959  1677427199  ...    719  1.023122  0.908203     1.0
720  20230227   000000    035959  1677441599  ...    720  0.995328  0.837074     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '16281.10226370968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23494.80019592', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=562
self.closeSec=1677455999, self.tradeDate='20230227', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23491.0, self.close=23545.3, self.high=23675.0, self.low=23310.0, self.vol=102114.23, self.amt=2402483031.9119 
127.0.0.1 - - [27/Feb/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-02-27 08:00:01,761:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677455999, self.tradeDate='20230227', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23491.0, self.close=23545.3, self.high=23675.0, self.low=23310.0, self.vol=102114.23, self.amt=2402483031.9119 
2023-02-27 08:00:01,807:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230226   120000    155959  ...   31491.179  7.292206e+08 -0.002547
718  20230226   160000    195959  ...   42192.201  9.793469e+08  0.004386
719  20230226   200000    235959  ...   63502.842  1.473863e+09 -0.000194
720  20230227   000000    035959  ...   93742.249  2.190288e+09  0.010818
721  20230227   040000    075959  ...  102114.230  2.402483e+09  0.002307

[5 rows x 11 columns]
2023-02-27 08:00:04,045:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230226   120000    155959  1677398399  ...    717  0.973914  0.797723     1.0
718  20230226   160000    195959  1677412799  ...    718  1.008950  0.878677     1.0
719  20230226   200000    235959  1677427199  ...    719  1.023122  0.908203     1.0
720  20230227   000000    035959  1677441599  ...    720  0.995328  0.837074     1.0
721  20230227   040000    075959  1677455999  ...    721  0.989702  0.819695     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '18499.17818206777', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23547.38740563', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


