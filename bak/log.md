# 20230725 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20704
self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29155.9, self.close=29140.6, self.high=29159.7, self.low=29140.6, self.vol=304.219, self.amt=8867545.2624 
127.0.0.1 - - [25/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 08:20:05,172:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230725   075500    075959  ...         0.0        0.0       0
5856  20230725   080000    080459  ...         0.0        0.0       0
5857  20230725   080500    080959  ...         0.0        0.0       0
5858  20230725   081000    081459  ...         0.0        0.0       0
5859  20230725   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 08:20:05,183:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29155.9, self.close=29140.6, self.high=29159.7, self.low=29140.6, self.vol=304.219, self.amt=8867545.2624, ukdf['pct'].iloc[-1]=-0.000525 , ukdf['amount'].iloc[-1]=8867545.2624, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31793.058', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29147.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20705
self.closeSec=1690244699, self.tradeDate='20230725', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29140.7, self.close=29161.2, self.high=29164.9, self.low=29140.6, self.vol=430.71, self.amt=12558207.8014 
127.0.0.1 - - [25/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-25 08:25:00,768:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230725   080000    080459  ...         0.0        0.0       0
5857  20230725   080500    080959  ...         0.0        0.0       0
5858  20230725   081000    081459  ...         0.0        0.0       0
5859  20230725   081500    081959  ...         0.0        0.0       0
5860  20230725   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 08:25:00,768:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690244699, self.tradeDate='20230725', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29140.7, self.close=29161.2, self.high=29164.9, self.low=29140.6, self.vol=430.71, self.amt=12558207.8014, ukdf['pct'].iloc[-1]=0.000707 , ukdf['amount'].iloc[-1]=12558207.8014, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31997.7702', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29162.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29155.9, self.close=29140.6, self.high=29159.7, self.low=29140.6 
127.0.0.1 - - [25/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 08:20:03,442:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29155.9, self.close=29140.6, self.high=29159.7, self.low=29140.6   
2023-07-25 08:20:04,433:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230725   075500    075959  1690243199  ...  29162.2 -0.000374   1535    5
1536  20230725   080000    080459  1690243499  ...  29155.5  0.000120   1536    0
1537  20230725   080500    080959  1690243799  ...  29137.3 -0.001029   1537    1
1538  20230725   081000    081459  1690244099  ...  29137.3  0.000638   1538    2
1539  20230725   081500    081959  1690244399  ...  29140.6 -0.000525   1539    3

[5 rows x 11 columns]
2023-07-25 08:20:04,443:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7306099605222547, self.count=20707 

self.closeSec=1690244699, self.tradeDate='20230725', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29140.7, self.close=29161.2, self.high=29164.9, self.low=29140.6 
2023-07-25 08:25:00,723:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690244699, self.tradeDate='20230725', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29140.7, self.close=29161.2, self.high=29164.9, self.low=29140.6   
2023-07-25 08:25:00,746:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230725   080000    080459  1690243499  ...  29155.5  0.000120   1536    0
1537  20230725   080500    080959  1690243799  ...  29137.3 -0.001029   1537    1
1538  20230725   081000    081459  1690244099  ...  29137.3  0.000638   1538    2
1539  20230725   081500    081959  1690244399  ...  29140.6 -0.000525   1539    3
1540  20230725   082000    082459  1690244699  ...  29140.6  0.000707   1540    4

[5 rows x 11 columns]
2023-07-25 08:25:00,746:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-25 08:00:16,860:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230725    052959  29134.6  ...  50.416667  0.390322  0.771133
5771  20230725    055959  29147.8  ...  50.416667  0.393474  0.766017
5772  20230725    062959  29158.5  ...  50.416667  0.391275  0.761149
5773  20230725    065959  29147.1  ...  50.833333  0.392824  0.756277
5774  20230725    072959  29152.3  ...  50.833333  0.399974  0.750219

[5 rows x 33 columns]
0.5360443622920518
acc is : 0.5360443622920518
2023-07-25 08:00:16,920:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.511603  0.488397       1  ...  0.939304  -1.0    0.0  0.944374
537     0  0.510549  0.489451       0  ...  0.939671  -1.0    0.0  0.944005
538     0  0.506367  0.493633       1  ...  0.939507  -1.0    0.0  0.944170
539     0  0.508465  0.491535       1  ...  0.938753  -1.0    0.0  0.944928
540     0  0.513318  0.486682       0  ...  0.939133  -1.0    0.0  0.944546

[5 rows x 10 columns]
2023-07-25 08:00:16,931:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511489  0.488511       1  ...  0.967911  -1.0    0.0  0.943311
46     0  0.510628  0.489372       0  ...  0.939671  -1.0    0.0  0.944192
47     0  0.506641  0.493359       1  ...  0.939507  -1.0    0.0  0.946042
48     0  0.508465  0.491535       1  ...  0.938753  -1.0    0.0  0.944928
49     0  0.513318  0.486682       0  ...  0.939133  -1.0    0.0  0.944546

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '13765.6446', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29163.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230725   075000    075959  1690243199  29162.1  29163.8  0.000055
2023-07-25 08:00:02,179:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10352 

self.closeSec=1690243799, self.tradeDate='20230725', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29163.8', self.close='29137.3'
2023-07-25 08:10:01,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690243799, self.tradeDate='20230725', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29163.8', self.close='29137.3'
2023-07-25 08:10:01,127:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230725   072000    072959  1690241399    29174  29175.6  0.000055
621  20230725   073000    073959  1690241999  29175.6  29176.1  0.000017
622  20230725   074000    074959  1690242599  29176.1  29162.2 -0.000476
623  20230725   075000    075959  1690243199  29162.1  29163.8  0.000055
624  20230725   080000    080959  1690243799  29163.8  29137.3 -0.000909
2023-07-25 08:10:01,127:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10353 

self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29137.3', self.close='29140.6'
127.0.0.1 - - [25/Jul/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-07-25 08:20:05,683:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29137.3', self.close='29140.6'
2023-07-25 08:20:06,132:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230725   073000    073959  1690241999  29175.6  29176.1  0.000017
622  20230725   074000    074959  1690242599  29176.1  29162.2 -0.000476
623  20230725   075000    075959  1690243199  29162.1  29163.8  0.000055
624  20230725   080000    080959  1690243799  29163.8  29137.3 -0.000909
625  20230725   081000    081959  1690244399  29137.3  29140.6  0.000113
2023-07-25 08:20:06,133:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230725   075000    075959  1690243199  29162.1  29163.8
2023-07-25 08:00:02,179:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10355 

self.closeSec=1690243799, self.tradeDate='20230725', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29163.8', self.close='29137.3'
127.0.0.1 - - [25/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-25 08:10:01,112:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690243799, self.tradeDate='20230725', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29163.8', self.close='29137.3'
2023-07-25 08:10:01,122:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230725   072000    072959  1690241399    29174  29175.6
17469  20230725   073000    073959  1690241999  29175.6  29176.1
17470  20230725   074000    074959  1690242599  29176.1  29162.2
17471  20230725   075000    075959  1690243199  29162.1  29163.8
17472  20230725   080000    080959  1690243799  29163.8  29137.3
2023-07-25 08:10:01,122:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10356 

self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29137.3', self.close='29140.6'
127.0.0.1 - - [25/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 08:20:06,814:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29137.3', self.close='29140.6'
2023-07-25 08:20:06,917:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230725   073000    073959  1690241999  29175.6  29176.1
17470  20230725   074000    074959  1690242599  29176.1  29162.2
17471  20230725   075000    075959  1690243199  29162.1  29163.8
17472  20230725   080000    080959  1690243799  29163.8  29137.3
17473  20230725   081000    081959  1690244399  29137.3  29140.6
2023-07-25 08:20:06,918:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230725   075000    075959  1690243199  29162.1  29163.8
2023-07-25 08:00:02,184:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10355 

self.closeSec=1690243799, self.tradeDate='20230725', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29163.8', self.close='29137.3'
2023-07-25 08:10:01,112:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690243799, self.tradeDate='20230725', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29163.8', self.close='29137.3'
2023-07-25 08:10:01,131:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230725   072000    072959  1690241399    29174  29175.6
12141  20230725   073000    073959  1690241999  29175.6  29176.1
12142  20230725   074000    074959  1690242599  29176.1  29162.2
12143  20230725   075000    075959  1690243199  29162.1  29163.8
12144  20230725   080000    080959  1690243799  29163.8  29137.3
2023-07-25 08:10:01,132:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10356 

self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29137.3', self.close='29140.6'
127.0.0.1 - - [25/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-25 08:20:06,665:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29137.3', self.close='29140.6'
2023-07-25 08:20:06,843:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230725   073000    073959  1690241999  29175.6  29176.1
12142  20230725   074000    074959  1690242599  29176.1  29162.2
12143  20230725   075000    075959  1690243199  29162.1  29163.8
12144  20230725   080000    080959  1690243799  29163.8  29137.3
12145  20230725   081000    081959  1690244399  29137.3  29140.6
2023-07-25 08:20:06,844:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20704
self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29155.9, self.close=29140.6, self.high=29159.7, self.low=29140.6, self.vol=304.219, self.amt=8867545.2624 
127.0.0.1 - - [25/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-25 08:20:05,202:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230725   075500    075959  ...         0.0        0.0       0
5856  20230725   080000    080459  ...         0.0        0.0       0
5857  20230725   080500    080959  ...         0.0        0.0       0
5858  20230725   081000    081459  ...         0.0        0.0       0
5859  20230725   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 08:20:05,213:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690244399, self.tradeDate='20230725', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29155.9, self.close=29140.6, self.high=29159.7, self.low=29140.6, self.vol=304.219, self.amt=8867545.2624, ukdf['pct'].iloc[-1]=-0.000525 , ukdf['amount'].iloc[-1]=8867545.2624, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '85569.1499', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29147.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20705
self.closeSec=1690244699, self.tradeDate='20230725', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29140.7, self.close=29161.2, self.high=29164.9, self.low=29140.6, self.vol=430.71, self.amt=12558207.8014 
2023-07-25 08:25:00,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230725   080000    080459  ...         0.0        0.0       0
5857  20230725   080500    080959  ...         0.0        0.0       0
5858  20230725   081000    081459  ...         0.0        0.0       0
5859  20230725   081500    081959  ...         0.0        0.0       0
5860  20230725   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-25 08:25:00,762:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690244699, self.tradeDate='20230725', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29140.7, self.close=29161.2, self.high=29164.9, self.low=29140.6, self.vol=430.71, self.amt=12558207.8014, ukdf['pct'].iloc[-1]=0.000707 , ukdf['amount'].iloc[-1]=12558207.8014, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '86115.1226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29162.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230724   200000    235959  1690214399  ...    719  0.093340 -0.933171    -1.0
720  20230725   000000    035959  1690228799  ...    720  0.246148 -0.333214     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '39847.64219358624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29106.88407326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [25/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=431
self.closeSec=1690243199, self.tradeDate='20230725', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29106.8, self.close=29163.8, self.high=29200.0, self.low=29075.5, self.vol=18811.829, self.amt=548289503.9866 
2023-07-25 08:00:01,761:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690243199, self.tradeDate='20230725', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29106.8, self.close=29163.8, self.high=29200.0, self.low=29075.5, self.vol=18811.829, self.amt=548289503.9866 
2023-07-25 08:00:01,777:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230724   120000    155959  ...   41872.139  1.246236e+09  0.003727
718  20230724   160000    195959  ...  137130.388  4.018484e+09 -0.018674
719  20230724   200000    235959  ...  124594.368  3.623508e+09 -0.005967
720  20230725   000000    035959  ...   41486.808  1.206293e+09  0.000753
721  20230725   040000    075959  ...   18811.829  5.482895e+08  0.001955

[5 rows x 11 columns]
2023-07-25 08:00:02,506:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230724   120000    155959  1690185599  ...    717  0.125401 -0.842012    -1.0
718  20230724   160000    195959  1690199999  ...    718  0.027101 -1.207360    -1.0
719  20230724   200000    235959  1690214399  ...    719  0.093340 -0.933171    -1.0
720  20230725   000000    035959  1690228799  ...    720  0.246148 -0.333214     NaN
721  20230725   040000    075959  1690243199  ...    721  0.339939  0.031975     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '36883.2144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29163.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


