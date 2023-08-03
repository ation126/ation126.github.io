# 20230803 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23296
self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29155.4, self.close=29191.6, self.high=29193.5, self.low=29152.3, self.vol=588.647, self.amt=17171688.2605 
127.0.0.1 - - [03/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 08:20:05,518:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230803   075500    075959  ...         0.0        0.0       0
5856  20230803   080000    080459  ...         0.0        0.0       0
5857  20230803   080500    080959  ...         0.0        0.0       0
5858  20230803   081000    081459  ...         0.0        0.0       0
5859  20230803   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 08:20:05,528:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29155.4, self.close=29191.6, self.high=29193.5, self.low=29152.3, self.vol=588.647, self.amt=17171688.2605, ukdf['pct'].iloc[-1]=0.001242 , ukdf['amount'].iloc[-1]=17171688.2605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32403.0168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29191.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23297
self.closeSec=1691022299, self.tradeDate='20230803', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29191.6, self.close=29186.0, self.high=29208.8, self.low=29186.0, self.vol=772.39, self.amt=22551339.758 
2023-08-03 08:25:00,789:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230803   080000    080459  ...         0.0        0.0       0
5857  20230803   080500    080959  ...         0.0        0.0       0
5858  20230803   081000    081459  ...         0.0        0.0       0
5859  20230803   081500    081959  ...         0.0        0.0       0
5860  20230803   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 08:25:00,790:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691022299, self.tradeDate='20230803', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29191.6, self.close=29186.0, self.high=29208.8, self.low=29186.0, self.vol=772.39, self.amt=22551339.758, ukdf['pct'].iloc[-1]=-0.000192 , ukdf['amount'].iloc[-1]=22551339.758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32385.50972659332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29190.44284982', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29155.4, self.close=29191.6, self.high=29193.5, self.low=29152.3 
127.0.0.1 - - [03/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 08:20:03,782:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29155.4, self.close=29191.6, self.high=29193.5, self.low=29152.3   
2023-08-03 08:20:04,901:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230803   075500    075959  1691020799  ...  29141.7  0.000920   1535    5
1536  20230803   080000    080459  1691021099  ...  29153.0 -0.000586   1536    0
1537  20230803   080500    080959  1691021399  ...  29150.0  0.000422   1537    1
1538  20230803   081000    081459  1691021699  ...  29155.4 -0.000339   1538    2
1539  20230803   081500    081959  1691021999  ...  29152.3  0.001242   1539    3

[5 rows x 11 columns]
2023-08-03 08:20:04,902:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=5, self.factor=0.5685984870249026, self.count=23299 

self.closeSec=1691022299, self.tradeDate='20230803', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29191.6, self.close=29186.0, self.high=29208.8, self.low=29186.0 
2023-08-03 08:25:00,760:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691022299, self.tradeDate='20230803', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29191.6, self.close=29186.0, self.high=29208.8, self.low=29186.0   
2023-08-03 08:25:00,771:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230803   080000    080459  1691021099  ...  29153.0 -0.000586   1536    0
1537  20230803   080500    080959  1691021399  ...  29150.0  0.000422   1537    1
1538  20230803   081000    081459  1691021699  ...  29155.4 -0.000339   1538    2
1539  20230803   081500    081959  1691021999  ...  29152.3  0.001242   1539    3
1540  20230803   082000    082459  1691022299  ...  29186.0 -0.000192   1540    4

[5 rows x 11 columns]
2023-08-03 08:25:00,771:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-03 08:00:17,708:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230803    052959  29129.9  ...  45.000000  0.470967  0.658232
5771  20230803    055959  29149.0  ...  45.416667  0.474735  0.663060
5772  20230803    062959  29166.9  ...  45.833333  0.484831  0.664258
5773  20230803    065959  29214.9  ...  45.833333  0.476862  0.666890
5774  20230803    072959  29174.0  ...  45.416667  0.471334  0.669874

[5 rows x 33 columns]
0.55637707948244
acc is : 0.55637707948244
2023-08-03 08:00:17,773:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.527624  0.472376       1  ...  0.980098   1.0    0.0  0.976376
537     0  0.519175  0.480825       1  ...  0.981711   1.0    0.0  0.977983
538     0  0.535401  0.464599       0  ...  0.980337   1.0    0.0  0.976614
539     0  0.510237  0.489763       0  ...  0.979376   1.0    0.0  0.975657
540     0  0.507557  0.492443       1  ...  0.980206   1.0    0.0  0.976483

[5 rows x 10 columns]
2023-08-03 08:00:17,785:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.527386  0.472614       1  ...  0.980098   1.0    0.0  0.976007
46     0  0.519317  0.480683       1  ...  0.981711   1.0    0.0  0.978314
47     0  0.535153  0.464847       0  ...  0.980337   1.0    0.0  0.976104
48     0  0.510481  0.489519       0  ...  0.979376   1.0    0.0  0.975657
49     0  0.507557  0.492443       1  ...  0.980206   1.0    0.0  0.976483

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '831.1777293774', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29166.04604029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230803   075000    075959  1691020799  29165.1  29170.1  0.000175
2023-08-03 08:00:02,076:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [03/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11648 

self.closeSec=1691021399, self.tradeDate='20230803', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29170.2', self.close='29165.3'
2023-08-03 08:10:01,127:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691021399, self.tradeDate='20230803', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29170.2', self.close='29165.3'
2023-08-03 08:10:01,160:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230803   072000    072959  1691018999  29157.7  29145.4 -0.000422
621  20230803   073000    073959  1691019599  29145.4  29132.5 -0.000443
622  20230803   074000    074959  1691020199  29132.5    29165  0.001116
623  20230803   075000    075959  1691020799  29165.1  29170.1  0.000175
624  20230803   080000    080959  1691021399  29170.2  29165.3 -0.000165
2023-08-03 08:10:01,161:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11649 

self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29163.6', self.close='29191.6'
127.0.0.1 - - [03/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 08:20:06,187:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29163.6', self.close='29191.6'
2023-08-03 08:20:06,577:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230803   073000    073959  1691019599  29145.4  29132.5 -0.000443
622  20230803   074000    074959  1691020199  29132.5    29165  0.001116
623  20230803   075000    075959  1691020799  29165.1  29170.1  0.000175
624  20230803   080000    080959  1691021399  29170.2  29165.3 -0.000165
625  20230803   081000    081959  1691021999  29163.6  29191.6  0.000902
2023-08-03 08:20:06,578:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230803   075000    075959  1691020799  29165.1  29170.1
2023-08-03 08:00:02,068:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11651 

self.closeSec=1691021399, self.tradeDate='20230803', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29170.2', self.close='29165.3'
2023-08-03 08:10:01,120:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691021399, self.tradeDate='20230803', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29170.2', self.close='29165.3'
2023-08-03 08:10:01,129:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230803   072000    072959  1691018999  29157.7  29145.4
17469  20230803   073000    073959  1691019599  29145.4  29132.5
17470  20230803   074000    074959  1691020199  29132.5    29165
17471  20230803   075000    075959  1691020799  29165.1  29170.1
17472  20230803   080000    080959  1691021399  29170.2  29165.3
2023-08-03 08:10:01,129:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11652 

self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29163.6', self.close='29191.6'
127.0.0.1 - - [03/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 08:20:07,411:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29163.6', self.close='29191.6'
2023-08-03 08:20:07,484:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230803   073000    073959  1691019599  29145.4  29132.5
17470  20230803   074000    074959  1691020199  29132.5    29165
17471  20230803   075000    075959  1691020799  29165.1  29170.1
17472  20230803   080000    080959  1691021399  29170.2  29165.3
17473  20230803   081000    081959  1691021999  29163.6  29191.6
2023-08-03 08:20:07,484:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230803   075000    075959  1691020799  29165.1  29170.1
2023-08-03 08:00:02,073:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11651 

self.closeSec=1691021399, self.tradeDate='20230803', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29170.2', self.close='29165.3'
127.0.0.1 - - [03/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-03 08:10:01,135:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691021399, self.tradeDate='20230803', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29170.2', self.close='29165.3'
2023-08-03 08:10:01,144:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230803   072000    072959  1691018999  29157.7  29145.4
12141  20230803   073000    073959  1691019599  29145.4  29132.5
12142  20230803   074000    074959  1691020199  29132.5    29165
12143  20230803   075000    075959  1691020799  29165.1  29170.1
12144  20230803   080000    080959  1691021399  29170.2  29165.3
2023-08-03 08:10:01,144:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11652 

self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29163.6', self.close='29191.6'
127.0.0.1 - - [03/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 08:20:07,239:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29163.6', self.close='29191.6'
2023-08-03 08:20:07,419:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230803   073000    073959  1691019599  29145.4  29132.5
12142  20230803   074000    074959  1691020199  29132.5    29165
12143  20230803   075000    075959  1691020799  29165.1  29170.1
12144  20230803   080000    080959  1691021399  29170.2  29165.3
12145  20230803   081000    081959  1691021999  29163.6  29191.6
2023-08-03 08:20:07,419:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23296
self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29155.4, self.close=29191.6, self.high=29193.5, self.low=29152.3, self.vol=588.647, self.amt=17171688.2605 
127.0.0.1 - - [03/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 08:20:05,418:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230803   075500    075959  ...         0.0        0.0       0
5856  20230803   080000    080459  ...         0.0        0.0       0
5857  20230803   080500    080959  ...         0.0        0.0       0
5858  20230803   081000    081459  ...         0.0        0.0       0
5859  20230803   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 08:20:05,438:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691021999, self.tradeDate='20230803', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29155.4, self.close=29191.6, self.high=29193.5, self.low=29152.3, self.vol=588.647, self.amt=17171688.2605, ukdf['pct'].iloc[-1]=0.001242 , ukdf['amount'].iloc[-1]=17171688.2605, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87195.9257', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29191.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [03/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23297
self.closeSec=1691022299, self.tradeDate='20230803', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29191.6, self.close=29186.0, self.high=29208.8, self.low=29186.0, self.vol=772.39, self.amt=22551339.758 
2023-08-03 08:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230803   080000    080459  ...         0.0        0.0       0
5857  20230803   080500    080959  ...         0.0        0.0       0
5858  20230803   081000    081459  ...         0.0        0.0       0
5859  20230803   081500    081959  ...         0.0        0.0       0
5860  20230803   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 08:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691022299, self.tradeDate='20230803', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29191.6, self.close=29186.0, self.high=29208.8, self.low=29186.0, self.vol=772.39, self.amt=22551339.758, ukdf['pct'].iloc[-1]=-0.000192 , ukdf['amount'].iloc[-1]=22551339.758, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87149.23388516462', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29190.44284982', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230802   200000    235959  1690991999  ...    719  0.292143  0.241824     NaN
720  20230803   000000    035959  1691006399  ...    720  0.280406  0.168011     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '5811.4952057184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29140.4275284', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=485
self.closeSec=1691020799, self.tradeDate='20230803', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29141.8, self.close=29170.1, self.high=29229.1, self.low=29050.3, self.vol=23823.33, self.amt=694515050.4595 
127.0.0.1 - - [03/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-03 08:00:01,654:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691020799, self.tradeDate='20230803', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29141.8, self.close=29170.1, self.high=29229.1, self.low=29050.3, self.vol=23823.33, self.amt=694515050.4595 
2023-08-03 08:00:01,670:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230802   120000    155959  ...   45298.470  1.341810e+09 -0.001769
718  20230802   160000    195959  ...   75164.964  2.215702e+09 -0.000582
719  20230802   200000    235959  ...   97917.578  2.873899e+09 -0.008135
720  20230803   000000    035959  ...  115887.845  3.373807e+09 -0.005823
721  20230803   040000    075959  ...   23823.330  6.945151e+08  0.000971

[5 rows x 11 columns]
2023-08-03 08:00:02,424:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230802   120000    155959  1690963199  ...    717  0.275701  0.170171     NaN
718  20230802   160000    195959  1690977599  ...    718  0.291438  0.247200     NaN
719  20230802   200000    235959  1690991999  ...    719  0.292143  0.241824     NaN
720  20230803   000000    035959  1691006399  ...    720  0.280406  0.168011     NaN
721  20230803   040000    075959  1691020799  ...    721  0.304316  0.283613     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '4177.0733444076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29170.68115385', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


