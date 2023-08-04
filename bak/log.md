# 20230804 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23584
self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29192.4, self.close=29214.5, self.high=29219.3, self.low=29190.4, self.vol=411.481, self.amt=12018747.6714 
127.0.0.1 - - [04/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 08:20:07,065:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230804   075500    075959  ...         0.0        0.0       0
5856  20230804   080000    080459  ...         0.0        0.0       0
5857  20230804   080500    080959  ...         0.0        0.0       0
5858  20230804   081000    081459  ...         0.0        0.0       0
5859  20230804   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 08:20:07,085:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29192.4, self.close=29214.5, self.high=29219.3, self.low=29190.4, self.vol=411.481, self.amt=12018747.6714, ukdf['pct'].iloc[-1]=0.000754 , ukdf['amount'].iloc[-1]=12018747.6714, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32749.7742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29216.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [04/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23585
self.closeSec=1691108699, self.tradeDate='20230804', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29214.5, self.close=29223.0, self.high=29244.4, self.low=29214.5, self.vol=661.392, self.amt=19334409.3864 
2023-08-04 08:25:00,754:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230804   080000    080459  ...         0.0        0.0       0
5857  20230804   080500    080959  ...         0.0        0.0       0
5858  20230804   081000    081459  ...         0.0        0.0       0
5859  20230804   081500    081959  ...         0.0        0.0       0
5860  20230804   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 08:25:00,754:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691108699, self.tradeDate='20230804', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29214.5, self.close=29223.0, self.high=29244.4, self.low=29214.5, self.vol=661.392, self.amt=19334409.3864, ukdf['pct'].iloc[-1]=0.000291 , ukdf['amount'].iloc[-1]=19334409.3864, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32893.39640474976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29226.91324176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29192.4, self.close=29214.5, self.high=29219.3, self.low=29190.4 
127.0.0.1 - - [04/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 08:20:04,785:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29192.4, self.close=29214.5, self.high=29219.3, self.low=29190.4   
2023-08-04 08:20:06,065:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230804   075500    075959  1691107199  ...  29178.6 -0.000031   1535    5
1536  20230804   080000    080459  1691107499  ...  29159.6  0.000884   1536    0
1537  20230804   080500    080959  1691107799  ...  29153.0 -0.001798   1537    1
1538  20230804   081000    081459  1691108099  ...  29153.4  0.001341   1538    2
1539  20230804   081500    081959  1691108399  ...  29190.4  0.000754   1539    3

[5 rows x 11 columns]
2023-08-04 08:20:06,075:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=28, self.factor=0.49042646995752637, self.count=23587 

self.closeSec=1691108699, self.tradeDate='20230804', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29214.5, self.close=29223.0, self.high=29244.4, self.low=29214.5 
2023-08-04 08:25:00,738:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691108699, self.tradeDate='20230804', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29214.5, self.close=29223.0, self.high=29244.4, self.low=29214.5   
2023-08-04 08:25:00,760:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230804   080000    080459  1691107499  ...  29159.6  0.000884   1536    0
1537  20230804   080500    080959  1691107799  ...  29153.0 -0.001798   1537    1
1538  20230804   081000    081459  1691108099  ...  29153.4  0.001341   1538    2
1539  20230804   081500    081959  1691108399  ...  29190.4  0.000754   1539    3
1540  20230804   082000    082459  1691108699  ...  29214.5  0.000291   1540    4

[5 rows x 11 columns]
2023-08-04 08:25:00,761:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-04 08:00:17,559:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230804    052959  29293.8  ...  46.250000  0.516426  0.425919
5771  20230804    055959  29297.2  ...  46.250000  0.503541  0.424420
5772  20230804    062959  29244.6  ...  45.833333  0.486826  0.432815
5773  20230804    065959  29173.3  ...  45.833333  0.498166  0.434116
5774  20230804    072959  29220.8  ...  45.833333  0.490758  0.439705

[5 rows x 33 columns]
0.5452865064695009
acc is : 0.5452865064695009
2023-08-04 08:00:17,622:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.503992  0.496008       0  ...  0.942989   1.0    0.0  0.975900
537     1  0.485635  0.514365       0  ...  0.940693   1.0    0.0  0.973524
538     1  0.472631  0.527369       1  ...  0.942225   1.0    0.0  0.975109
539     0  0.507240  0.492760       0  ...  0.941199   1.0    0.0  0.974048
540     1  0.484447  0.515553       0  ...  0.940913   1.0    0.0  0.973751

[5 rows x 10 columns]
2023-08-04 08:00:17,634:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503848  0.496152       0  ...  0.942989   1.0    0.0  0.978535
46     1  0.485530  0.514470       0  ...  0.940693   1.0    0.0  0.975435
47     1  0.472379  0.527621       1  ...  0.942225   1.0    0.0  0.975943
48     0  0.507240  0.492760       0  ...  0.941199   1.0    0.0  0.974048
49     1  0.484447  0.515553       0  ...  0.940913   1.0    0.0  0.973751

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '1030.8071629488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29174.34319048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230804   075000    075959  1691107199  29204.7  29180.1 -0.000842
2023-08-04 08:00:02,058:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11792 

self.closeSec=1691107799, self.tradeDate='20230804', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29180.1', self.close='29153.5'
2023-08-04 08:10:01,131:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691107799, self.tradeDate='20230804', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29180.1', self.close='29153.5'
127.0.0.1 - - [04/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-04 08:10:01,138:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230804   072000    072959  1691105399  29187.9    29189  0.000041
621  20230804   073000    073959  1691105999    29189  29217.1  0.000963
622  20230804   074000    074959  1691106599  29217.1  29204.7 -0.000424
623  20230804   075000    075959  1691107199  29204.7  29180.1 -0.000842
624  20230804   080000    080959  1691107799  29180.1  29153.5 -0.000912
2023-08-04 08:10:01,141:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11793 

self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29153.5', self.close='29214.6'
127.0.0.1 - - [04/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 08:20:07,244:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29153.5', self.close='29214.6'
2023-08-04 08:20:07,914:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230804   073000    073959  1691105999    29189  29217.1  0.000963
622  20230804   074000    074959  1691106599  29217.1  29204.7 -0.000424
623  20230804   075000    075959  1691107199  29204.7  29180.1 -0.000842
624  20230804   080000    080959  1691107799  29180.1  29153.5 -0.000912
625  20230804   081000    081959  1691108399  29153.5  29214.6  0.002096
2023-08-04 08:20:07,915:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230804   075000    075959  1691107199  29204.7  29180.1
2023-08-04 08:00:02,062:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11795 

self.closeSec=1691107799, self.tradeDate='20230804', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29180.1', self.close='29153.5'
2023-08-04 08:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691107799, self.tradeDate='20230804', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29180.1', self.close='29153.5'
2023-08-04 08:10:01,143:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230804   072000    072959  1691105399  29187.9    29189
17469  20230804   073000    073959  1691105999    29189  29217.1
17470  20230804   074000    074959  1691106599  29217.1  29204.7
17471  20230804   075000    075959  1691107199  29204.7  29180.1
17472  20230804   080000    080959  1691107799  29180.1  29153.5
2023-08-04 08:10:01,143:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11796 

self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29153.5', self.close='29214.6'
127.0.0.1 - - [04/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 08:20:08,966:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29153.5', self.close='29214.6'
2023-08-04 08:20:09,082:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230804   073000    073959  1691105999    29189  29217.1
17470  20230804   074000    074959  1691106599  29217.1  29204.7
17471  20230804   075000    075959  1691107199  29204.7  29180.1
17472  20230804   080000    080959  1691107799  29180.1  29153.5
17473  20230804   081000    081959  1691108399  29153.5  29214.6
2023-08-04 08:20:09,082:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230804   075000    075959  1691107199  29204.7  29180.1
2023-08-04 08:00:02,075:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11795 

self.closeSec=1691107799, self.tradeDate='20230804', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29180.1', self.close='29153.5'
2023-08-04 08:10:01,127:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691107799, self.tradeDate='20230804', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29180.1', self.close='29153.5'
127.0.0.1 - - [04/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-04 08:10:01,133:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230804   072000    072959  1691105399  29187.9    29189
12141  20230804   073000    073959  1691105999    29189  29217.1
12142  20230804   074000    074959  1691106599  29217.1  29204.7
12143  20230804   075000    075959  1691107199  29204.7  29180.1
12144  20230804   080000    080959  1691107799  29180.1  29153.5
2023-08-04 08:10:01,133:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11796 

self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29153.5', self.close='29214.6'
127.0.0.1 - - [04/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-04 08:20:08,765:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29153.5', self.close='29214.6'
2023-08-04 08:20:08,957:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230804   073000    073959  1691105999    29189  29217.1
12142  20230804   074000    074959  1691106599  29217.1  29204.7
12143  20230804   075000    075959  1691107199  29204.7  29180.1
12144  20230804   080000    080959  1691107799  29180.1  29153.5
12145  20230804   081000    081959  1691108399  29153.5  29214.6
2023-08-04 08:20:08,965:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23584
self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29192.4, self.close=29214.5, self.high=29219.3, self.low=29190.4, self.vol=411.481, self.amt=12018747.6714 
127.0.0.1 - - [04/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-04 08:20:07,045:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230804   075500    075959  ...         0.0        0.0       0
5856  20230804   080000    080459  ...         0.0        0.0       0
5857  20230804   080500    080959  ...         0.0        0.0       0
5858  20230804   081000    081459  ...         0.0        0.0       0
5859  20230804   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 08:20:07,085:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691108399, self.tradeDate='20230804', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29192.4, self.close=29214.5, self.high=29219.3, self.low=29190.4, self.vol=411.481, self.amt=12018747.6714, ukdf['pct'].iloc[-1]=0.000754 , ukdf['amount'].iloc[-1]=12018747.6714, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88120.7366', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29216.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23585
self.closeSec=1691108699, self.tradeDate='20230804', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29214.5, self.close=29223.0, self.high=29244.4, self.low=29214.5, self.vol=661.392, self.amt=19334409.3864 
127.0.0.1 - - [04/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-04 08:25:00,772:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230804   080000    080459  ...         0.0        0.0       0
5857  20230804   080500    080959  ...         0.0        0.0       0
5858  20230804   081000    081459  ...         0.0        0.0       0
5859  20230804   081500    081959  ...         0.0        0.0       0
5860  20230804   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-04 08:25:00,772:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691108699, self.tradeDate='20230804', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29214.5, self.close=29223.0, self.high=29244.4, self.low=29214.5, self.vol=661.392, self.amt=19334409.3864, ukdf['pct'].iloc[-1]=0.000291 , ukdf['amount'].iloc[-1]=19334409.3864, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88503.78071220816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29226.91324176', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230803   200000    235959  1691078399  ...    719  0.426334  0.858964     1.0
720  20230804   000000    035959  1691092799  ...    720  0.435090  0.886587     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '12803.437415111', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29268.54600484', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=491
self.closeSec=1691107199, self.tradeDate='20230804', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29265.6, self.close=29180.1, self.high=29352.4, self.low=29150.0, self.vol=32069.536, self.amt=938127360.6519 
127.0.0.1 - - [04/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-04 08:00:01,637:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691107199, self.tradeDate='20230804', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29265.6, self.close=29180.1, self.high=29352.4, self.low=29150.0, self.vol=32069.536, self.amt=938127360.6519 
2023-08-04 08:00:01,657:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230803   120000    155959  ...  28883.917  8.400553e+08 -0.004666
718  20230803   160000    195959  ...  39270.953  1.142696e+09  0.003451
719  20230803   200000    235959  ...  78353.291  2.291478e+09  0.003782
720  20230804   000000    035959  ...  49254.329  1.440697e+09  0.000745
721  20230804   040000    075959  ...  32069.536  9.381274e+08 -0.002942

[5 rows x 11 columns]
2023-08-04 08:00:02,513:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230803   120000    155959  1691049599  ...    717  0.370799  0.605461     1.0
718  20230803   160000    195959  1691063999  ...    718  0.409624  0.789930     1.0
719  20230803   200000    235959  1691078399  ...    719  0.426334  0.858964     1.0
720  20230804   000000    035959  1691092799  ...    720  0.435090  0.886587     1.0
721  20230804   040000    075959  1691107199  ...    721  0.429670  0.843415     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '7958.8075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29180.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


