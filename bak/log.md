# 20230716 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18112
self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30293.8, self.close=30282.8, self.high=30293.8, self.low=30277.1, self.vol=240.932, self.amt=7296068.8233 
127.0.0.1 - - [16/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 08:20:06,113:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230716   075500    075959  ...         0.0        0.0       0
5856  20230716   080000    080459  ...         0.0        0.0       0
5857  20230716   080500    080959  ...         0.0        0.0       0
5858  20230716   081000    081459  ...         0.0        0.0       0
5859  20230716   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 08:20:06,124:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30293.8, self.close=30282.8, self.high=30293.8, self.low=30277.1, self.vol=240.932, self.amt=7296068.8233, ukdf['pct'].iloc[-1]=-0.000363 , ukdf['amount'].iloc[-1]=7296068.8233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47597.6754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30282.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18113
self.closeSec=1689467099, self.tradeDate='20230716', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30282.8, self.close=30271.2, self.high=30282.9, self.low=30271.2, self.vol=180.577, self.amt=5467374.6876 
127.0.0.1 - - [16/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-16 08:25:00,715:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230716   080000    080459  ...         0.0        0.0       0
5857  20230716   080500    080959  ...         0.0        0.0       0
5858  20230716   081000    081459  ...         0.0        0.0       0
5859  20230716   081500    081959  ...         0.0        0.0       0
5860  20230716   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 08:25:00,715:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689467099, self.tradeDate='20230716', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30282.8, self.close=30271.2, self.high=30282.9, self.low=30271.2, self.vol=180.577, self.amt=5467374.6876, ukdf['pct'].iloc[-1]=-0.000383 , ukdf['amount'].iloc[-1]=5467374.6876, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47463.50346560922', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30273.16536447', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30293.8, self.close=30282.8, self.high=30293.8, self.low=30277.1 
127.0.0.1 - - [16/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 08:20:04,374:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30293.8, self.close=30282.8, self.high=30293.8, self.low=30277.1   
2023-07-16 08:20:05,323:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230716   075500    075959  1689465599  ...  30264.5  0.000393   1535    5
1536  20230716   080000    080459  1689465899  ...  30273.3  0.000198   1536    0
1537  20230716   080500    080959  1689466199  ...  30276.3  0.000149   1537    1
1538  20230716   081000    081459  1689466499  ...  30283.0  0.000225   1538    2
1539  20230716   081500    081959  1689466799  ...  30277.1 -0.000363   1539    3

[5 rows x 11 columns]
2023-07-16 08:20:05,333:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=13, self.factor=0.58099603610295, self.count=18115 

self.closeSec=1689467099, self.tradeDate='20230716', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30282.8, self.close=30271.2, self.high=30282.9, self.low=30271.2 
127.0.0.1 - - [16/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-16 08:25:00,696:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689467099, self.tradeDate='20230716', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30282.8, self.close=30271.2, self.high=30282.9, self.low=30271.2   
2023-07-16 08:25:00,707:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230716   080000    080459  1689465899  ...  30273.3  0.000198   1536    0
1537  20230716   080500    080959  1689466199  ...  30276.3  0.000149   1537    1
1538  20230716   081000    081459  1689466499  ...  30283.0  0.000225   1538    2
1539  20230716   081500    081959  1689466799  ...  30277.1 -0.000363   1539    3
1540  20230716   082000    082459  1689467099  ...  30271.2 -0.000383   1540    4

[5 rows x 11 columns]
2023-07-16 08:25:00,707:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-16 08:00:17,339:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230716    052959  30284.7  ...  54.166667  0.438915  0.532839
5771  20230716    055959  30278.4  ...  54.583333  0.441905  0.535961
5772  20230716    062959  30288.8  ...  54.583333  0.443891  0.535244
5773  20230716    065959  30295.3  ...  54.583333  0.438425  0.547041
5774  20230716    072959  30272.4  ...  54.583333  0.438793  0.557401

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-07-16 08:00:17,413:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.483477  0.516523       1  ...  1.021041  -1.0    0.0  0.979412
537     1  0.488495  0.511505       1  ...  1.020815  -1.0    0.0  0.979628
538     1  0.492195  0.507805       0  ...  1.021590  -1.0    0.0  0.978885
539     1  0.483857  0.516143       1  ...  1.021550  -1.0    0.0  0.978923
540     1  0.497285  0.502715       1  ...  1.021455  -1.0    0.0  0.979014

[5 rows x 10 columns]
2023-07-16 08:00:17,426:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483272  0.516728       1  ...  1.021041  -1.0    0.0  0.978336
46     1  0.487882  0.512118       1  ...  1.007493  -1.0    0.0  0.976238
47     1  0.491869  0.508131       0  ...  1.021590  -1.0    0.0  0.978208
48     1  0.483780  0.516220       1  ...  1.021550  -1.0    0.0  0.978923
49     1  0.497285  0.502715       1  ...  1.021455  -1.0    0.0  0.979014

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.355', 'enterprice': '30274.7', 'countrevence': '0', 'unrealprofit': '-38.9499344352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30276.29925824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230716   075000    075959  1689465599    30267  30276.4  0.000314
2023-07-16 08:00:02,219:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [16/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9056 

self.closeSec=1689466199, self.tradeDate='20230716', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30276.5', self.close='30287'
2023-07-16 08:10:01,149:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689466199, self.tradeDate='20230716', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30276.5', self.close='30287'
2023-07-16 08:10:01,167:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230716   072000    072959  1689463799  30273.1  30273.6  0.000017
621  20230716   073000    073959  1689464399  30273.6  30267.3 -0.000208
622  20230716   074000    074959  1689464999  30267.3  30266.9 -0.000013
623  20230716   075000    075959  1689465599    30267  30276.4  0.000314
624  20230716   080000    080959  1689466199  30276.5    30287  0.000350
2023-07-16 08:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9057 

self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30287', self.close='30282.8'
127.0.0.1 - - [16/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 08:20:06,454:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30287', self.close='30282.8'
2023-07-16 08:20:07,143:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230716   073000    073959  1689464399  30273.6  30267.3 -0.000208
622  20230716   074000    074959  1689464999  30267.3  30266.9 -0.000013
623  20230716   075000    075959  1689465599    30267  30276.4  0.000314
624  20230716   080000    080959  1689466199  30276.5    30287  0.000350
625  20230716   081000    081959  1689466799    30287  30282.8 -0.000139
2023-07-16 08:20:07,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230716   075000    075959  1689465599    30267  30276.4
2023-07-16 08:00:02,204:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9059 

self.closeSec=1689466199, self.tradeDate='20230716', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30276.5', self.close='30287'
127.0.0.1 - - [16/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-16 08:10:01,153:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689466199, self.tradeDate='20230716', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30276.5', self.close='30287'
2023-07-16 08:10:01,161:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230716   072000    072959  1689463799  30273.1  30273.6
17469  20230716   073000    073959  1689464399  30273.6  30267.3
17470  20230716   074000    074959  1689464999  30267.3  30266.9
17471  20230716   075000    075959  1689465599    30267  30276.4
17472  20230716   080000    080959  1689466199  30276.5    30287
2023-07-16 08:10:01,161:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9060 

self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30287', self.close='30282.8'
127.0.0.1 - - [16/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 08:20:07,777:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30287', self.close='30282.8'
2023-07-16 08:20:08,010:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230716   073000    073959  1689464399  30273.6  30267.3
17470  20230716   074000    074959  1689464999  30267.3  30266.9
17471  20230716   075000    075959  1689465599    30267  30276.4
17472  20230716   080000    080959  1689466199  30276.5    30287
17473  20230716   081000    081959  1689466799    30287  30282.8
2023-07-16 08:20:08,011:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230716   075000    075959  1689465599    30267  30276.4
2023-07-16 08:00:02,223:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9059 

self.closeSec=1689466199, self.tradeDate='20230716', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30276.5', self.close='30287'
2023-07-16 08:10:01,158:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689466199, self.tradeDate='20230716', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30276.5', self.close='30287'
127.0.0.1 - - [16/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-16 08:10:01,169:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230716   072000    072959  1689463799  30273.1  30273.6
12141  20230716   073000    073959  1689464399  30273.6  30267.3
12142  20230716   074000    074959  1689464999  30267.3  30266.9
12143  20230716   075000    075959  1689465599    30267  30276.4
12144  20230716   080000    080959  1689466199  30276.5    30287
2023-07-16 08:10:01,169:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9060 

self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30287', self.close='30282.8'
127.0.0.1 - - [16/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 08:20:07,647:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30287', self.close='30282.8'
2023-07-16 08:20:07,867:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230716   073000    073959  1689464399  30273.6  30267.3
12142  20230716   074000    074959  1689464999  30267.3  30266.9
12143  20230716   075000    075959  1689465599    30267  30276.4
12144  20230716   080000    080959  1689466199  30276.5    30287
12145  20230716   081000    081959  1689466799    30287  30282.8
2023-07-16 08:20:07,872:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18112
self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30293.8, self.close=30282.8, self.high=30293.8, self.low=30277.1, self.vol=240.932, self.amt=7296068.8233 
127.0.0.1 - - [16/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 08:20:06,024:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230716   075500    075959  ...         0.0        0.0       0
5856  20230716   080000    080459  ...         0.0        0.0       0
5857  20230716   080500    080959  ...         0.0        0.0       0
5858  20230716   081000    081459  ...         0.0        0.0       0
5859  20230716   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 08:20:06,064:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689466799, self.tradeDate='20230716', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30293.8, self.close=30282.8, self.high=30293.8, self.low=30277.1, self.vol=240.932, self.amt=7296068.8233, ukdf['pct'].iloc[-1]=-0.000363 , ukdf['amount'].iloc[-1]=7296068.8233, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127720.4708', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30282.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18113
self.closeSec=1689467099, self.tradeDate='20230716', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30282.8, self.close=30271.2, self.high=30282.9, self.low=30271.2, self.vol=180.577, self.amt=5467374.6876 
2023-07-16 08:25:00,747:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230716   080000    080459  ...         0.0        0.0       0
5857  20230716   080500    080959  ...         0.0        0.0       0
5858  20230716   081000    081459  ...         0.0        0.0       0
5859  20230716   081500    081959  ...         0.0        0.0       0
5860  20230716   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 08:25:00,747:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689467099, self.tradeDate='20230716', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30282.8, self.close=30271.2, self.high=30282.9, self.low=30271.2, self.vol=180.577, self.amt=5467374.6876, ukdf['pct'].iloc[-1]=-0.000383 , ukdf['amount'].iloc[-1]=5467374.6876, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127362.63080178027', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30273.16536447', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230715   200000    235959  1689436799  ...    719  0.515319  0.731175     1.0
720  20230716   000000    035959  1689451199  ...    720  0.560820  0.881317     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-10534.10448813548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30309.45561172', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [16/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=377
self.closeSec=1689465599, self.tradeDate='20230716', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30309.7, self.close=30276.4, self.high=30309.8, self.low=30251.0, self.vol=10464.59, self.amt=316849924.7255 
2023-07-16 08:00:01,769:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689465599, self.tradeDate='20230716', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30309.7, self.close=30276.4, self.high=30309.8, self.low=30251.0, self.vol=10464.59, self.amt=316849924.7255 
2023-07-16 08:00:01,786:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230715   120000    155959  ...  18539.329  5.617057e+08  0.001374
718  20230715   160000    195959  ...  17263.000  5.232511e+08 -0.000630
719  20230715   200000    235959  ...  19740.322  5.980437e+08 -0.000264
720  20230716   000000    035959  ...  16143.855  4.889786e+08  0.000634
721  20230716   040000    075959  ...  10464.590  3.168499e+08 -0.001099

[5 rows x 11 columns]
2023-07-16 08:00:02,499:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230715   120000    155959  1689407999  ...    717  0.473833  0.585196     NaN
718  20230715   160000    195959  1689422399  ...    718  0.497323  0.681657     1.0
719  20230715   200000    235959  1689436799  ...    719  0.515319  0.731175     1.0
720  20230716   000000    035959  1689451199  ...    720  0.560820  0.881317     1.0
721  20230716   040000    075959  1689465599  ...    721  0.585894  0.953976     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-12260.9627', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30276.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


