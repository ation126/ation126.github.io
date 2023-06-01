# 20230601 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5152
self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27301.9, self.close=27277.3, self.high=27327.9, self.low=27274.8, self.vol=2424.596, self.amt=66191739.3089 
127.0.0.1 - - [01/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 08:20:06,646:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230601   075500    075959  ...         0.0        0.0       0
5856  20230601   080000    080459  ...         0.0        0.0       0
5857  20230601   080500    080959  ...         0.0        0.0       0
5858  20230601   081000    081459  ...         0.0        0.0       0
5859  20230601   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 08:20:06,666:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27301.9, self.close=27277.3, self.high=27327.9, self.low=27274.8, self.vol=2424.596, self.amt=66191739.3089, ukdf['pct'].iloc[-1]=-0.000905 , ukdf['amount'].iloc[-1]=66191739.3089, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5844.7422', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27284.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=5153
self.closeSec=1685579099, self.tradeDate='20230601', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27277.3, self.close=27291.9, self.high=27317.5, self.low=27277.3, self.vol=1262.129, self.amt=34449507.9527 
127.0.0.1 - - [01/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-01 08:25:00,781:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230601   080000    080459  ...         0.0        0.0       0
5857  20230601   080500    080959  ...         0.0        0.0       0
5858  20230601   081000    081459  ...         0.0        0.0       0
5859  20230601   081500    081959  ...         0.0        0.0       0
5860  20230601   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 08:25:00,781:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685579099, self.tradeDate='20230601', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27277.3, self.close=27291.9, self.high=27317.5, self.low=27277.3, self.vol=1262.129, self.amt=34449507.9527, ukdf['pct'].iloc[-1]=0.000535 , ukdf['amount'].iloc[-1]=34449507.9527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5947.7946', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27292', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27301.9, self.close=27277.3, self.high=27327.9, self.low=27274.8 
127.0.0.1 - - [01/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 08:20:04,486:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27301.9, self.close=27277.3, self.high=27327.9, self.low=27274.8   
2023-06-01 08:20:05,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230601   075500    075959  1685577599  ...  27176.8 -0.000349   1535    5
1536  20230601   080000    080459  1685577899  ...  27200.0  0.000882   1536    0
1537  20230601   080500    080959  1685578199  ...  27183.4  0.000331   1537    1
1538  20230601   081000    081459  1685578499  ...  27232.0  0.002493   1538    2
1539  20230601   081500    081959  1685578799  ...  27274.8 -0.000905   1539    3

[5 rows x 11 columns]
2023-06-01 08:20:05,805:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.736651357591548, self.count=5155 

self.closeSec=1685579099, self.tradeDate='20230601', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27277.3, self.close=27291.9, self.high=27317.5, self.low=27277.3 
127.0.0.1 - - [01/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-01 08:25:00,712:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685579099, self.tradeDate='20230601', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27277.3, self.close=27291.9, self.high=27317.5, self.low=27277.3   
2023-06-01 08:25:00,761:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230601   080000    080459  1685577899  ...  27200.0  0.000882   1536    0
1537  20230601   080500    080959  1685578199  ...  27183.4  0.000331   1537    1
1538  20230601   081000    081459  1685578499  ...  27232.0  0.002493   1538    2
1539  20230601   081500    081959  1685578799  ...  27274.8 -0.000905   1539    3
1540  20230601   082000    082459  1685579099  ...  27277.3  0.000535   1540    4

[5 rows x 11 columns]
2023-06-01 08:25:00,761:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-01 08:00:33,907:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230601    052959  27096.9  ...  49.166667  0.430400  0.802584
5771  20230601    055959  27049.7  ...  49.583333  0.438253  0.796805
5772  20230601    062959  27081.9  ...  49.583333  0.451083  0.786296
5773  20230601    065959  27135.5  ...  50.000000  0.459234  0.773799
5774  20230601    072959  27170.0  ...  50.000000  0.462623  0.761015

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-06-01 08:00:34,105:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.495919  0.504081       1  ...  1.072245  -1.0    0.0  1.006212
537     0  0.512932  0.487068       1  ...  1.070127  -1.0    0.0  1.008200
538     0  0.522534  0.477466       1  ...  1.068763  -1.0    0.0  1.009486
539     0  0.514576  0.485424       1  ...  1.068196  -1.0    0.0  1.010021
540     0  0.510618  0.489382       1  ...  1.067540  -1.0    0.0  1.010641

[5 rows x 10 columns]
2023-06-01 08:00:34,138:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495787  0.504213       1  ...  1.072245  -1.0    0.0  1.005417
46     0  0.513191  0.486809       1  ...  1.030363  -1.0    0.0  1.007927
47     0  0.522651  0.477349       1  ...  1.068763  -1.0    0.0  1.009797
48     0  0.514576  0.485424       1  ...  1.068196  -1.0    0.0  1.010021
49     0  0.510618  0.489382       1  ...  1.067540  -1.0    0.0  1.010641

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '18797.3928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27208.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230601   075000    075959  1685577599  27222.1  27201.1 -0.000771
2023-06-01 08:00:02,266:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2576 

self.closeSec=1685578199, self.tradeDate='20230601', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27201.1', self.close='27234.1'
2023-06-01 08:10:01,087:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685578199, self.tradeDate='20230601', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27201.1', self.close='27234.1'
2023-06-01 08:10:01,112:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230601   072000    072959  1685575799  27152.7  27184.5  0.001175
621  20230601   073000    073959  1685576399  27184.5    27185  0.000018
622  20230601   074000    074959  1685576999    27185  27222.1  0.001365
623  20230601   075000    075959  1685577599  27222.1  27201.1 -0.000771
624  20230601   080000    080959  1685578199  27201.1  27234.1  0.001213
2023-06-01 08:10:01,112:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2577 

self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27234', self.close='27277.3'
127.0.0.1 - - [01/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 08:20:06,635:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27234', self.close='27277.3'
2023-06-01 08:20:07,275:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230601   073000    073959  1685576399  27184.5    27185  0.000018
622  20230601   074000    074959  1685576999    27185  27222.1  0.001365
623  20230601   075000    075959  1685577599  27222.1  27201.1 -0.000771
624  20230601   080000    080959  1685578199  27201.1  27234.1  0.001213
625  20230601   081000    081959  1685578799    27234  27277.3  0.001586
2023-06-01 08:20:07,275:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230601   075000    075959  1685577599  27222.1  27201.1
2023-06-01 08:00:02,296:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2579 

self.closeSec=1685578199, self.tradeDate='20230601', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27201.1', self.close='27234.1'
2023-06-01 08:10:01,096:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685578199, self.tradeDate='20230601', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27201.1', self.close='27234.1'
127.0.0.1 - - [01/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-01 08:10:01,129:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230601   072000    072959  1685575799  27152.7  27184.5
17469  20230601   073000    073959  1685576399  27184.5    27185
17470  20230601   074000    074959  1685576999    27185  27222.1
17471  20230601   075000    075959  1685577599  27222.1  27201.1
17472  20230601   080000    080959  1685578199  27201.1  27234.1
2023-06-01 08:10:01,129:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2580 

self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27234', self.close='27277.3'
127.0.0.1 - - [01/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 08:20:08,243:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27234', self.close='27277.3'
2023-06-01 08:20:08,391:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230601   073000    073959  1685576399  27184.5    27185
17470  20230601   074000    074959  1685576999    27185  27222.1
17471  20230601   075000    075959  1685577599  27222.1  27201.1
17472  20230601   080000    080959  1685578199  27201.1  27234.1
17473  20230601   081000    081959  1685578799    27234  27277.3
2023-06-01 08:20:08,392:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230601   075000    075959  1685577599  27222.1  27201.1
2023-06-01 08:00:02,297:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2579 

self.closeSec=1685578199, self.tradeDate='20230601', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27201.1', self.close='27234.1'
2023-06-01 08:10:01,085:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685578199, self.tradeDate='20230601', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27201.1', self.close='27234.1'
127.0.0.1 - - [01/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-01 08:10:01,100:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230601   072000    072959  1685575799  27152.7  27184.5
12141  20230601   073000    073959  1685576399  27184.5    27185
12142  20230601   074000    074959  1685576999    27185  27222.1
12143  20230601   075000    075959  1685577599  27222.1  27201.1
12144  20230601   080000    080959  1685578199  27201.1  27234.1
2023-06-01 08:10:01,100:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2580 

self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27234', self.close='27277.3'
127.0.0.1 - - [01/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-01 08:20:07,986:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27234', self.close='27277.3'
2023-06-01 08:20:08,243:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230601   073000    073959  1685576399  27184.5    27185
12142  20230601   074000    074959  1685576999    27185  27222.1
12143  20230601   075000    075959  1685577599  27222.1  27201.1
12144  20230601   080000    080959  1685578199  27201.1  27234.1
12145  20230601   081000    081959  1685578799    27234  27277.3
2023-06-01 08:20:08,245:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5152
self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27301.9, self.close=27277.3, self.high=27327.9, self.low=27274.8, self.vol=2424.596, self.amt=66191739.3089 
127.0.0.1 - - [01/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-01 08:20:06,636:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230601   075500    075959  ...         0.0        0.0       0
5856  20230601   080000    080459  ...         0.0        0.0       0
5857  20230601   080500    080959  ...         0.0        0.0       0
5858  20230601   081000    081459  ...         0.0        0.0       0
5859  20230601   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 08:20:06,656:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685578799, self.tradeDate='20230601', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27301.9, self.close=27277.3, self.high=27327.9, self.low=27274.8, self.vol=2424.596, self.amt=66191739.3089, ukdf['pct'].iloc[-1]=-0.000905 , ukdf['amount'].iloc[-1]=66191739.3089, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '16364.3246', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27284.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=5153
self.closeSec=1685579099, self.tradeDate='20230601', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27277.3, self.close=27291.9, self.high=27317.5, self.low=27277.3, self.vol=1262.129, self.amt=34449507.9527 
2023-06-01 08:25:00,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230601   080000    080459  ...         0.0        0.0       0
5857  20230601   080500    080959  ...         0.0        0.0       0
5858  20230601   081000    081459  ...         0.0        0.0       0
5859  20230601   081500    081959  ...         0.0        0.0       0
5860  20230601   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-01 08:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685579099, self.tradeDate='20230601', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27277.3, self.close=27291.9, self.high=27317.5, self.low=27277.3, self.vol=1262.129, self.amt=34449507.9527, ukdf['pct'].iloc[-1]=0.000535 , ukdf['amount'].iloc[-1]=34449507.9527, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '16639.168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27292', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230531   200000    235959  1685548799  ...    719  0.890645  1.114161     1.0
720  20230601   000000    035959  1685563199  ...    720  0.855047  0.988011     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '48585.9706', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27007.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [01/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=107
self.closeSec=1685577599, self.tradeDate='20230601', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26999.5, self.close=27201.1, self.high=27290.0, self.low=26992.0, self.vol=40645.961, self.amt=1103126498.00048 
2023-06-01 08:00:01,724:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685577599, self.tradeDate='20230601', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26999.5, self.close=27201.1, self.high=27290.0, self.low=26992.0, self.vol=40645.961, self.amt=1103126498.00048 
2023-06-01 08:00:01,769:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230531   120000    155959  ...  156776.296  4.265625e+09 -0.017944
718  20230531   160000    195959  ...   56728.662  1.536835e+09 -0.002302
719  20230531   200000    235959  ...  119487.274  3.226958e+09 -0.006933
720  20230601   000000    035959  ...   58700.858  1.584253e+09  0.003639
721  20230601   040000    075959  ...   40645.961  1.103126e+09  0.007523

[5 rows x 11 columns]
2023-06-01 08:00:03,796:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230531   120000    155959  1685519999  ...    717  1.026520  1.580231     1.0
718  20230531   160000    195959  1685534399  ...    718  0.979737  1.406118     1.0
719  20230531   200000    235959  1685548799  ...    719  0.890645  1.114161     1.0
720  20230601   000000    035959  1685563199  ...    720  0.855047  0.988011     1.0
721  20230601   040000    075959  1685577599  ...    721  0.807567  0.836682     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '59282.177', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27201.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


