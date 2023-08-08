# 20230808 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24736
self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29193.5, self.close=29187.9, self.high=29193.6, self.low=29184.5, self.vol=404.397, self.amt=11803843.5611 
127.0.0.1 - - [08/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 08:20:06,602:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230808   075500    075959  ...         0.0        0.0       0
5856  20230808   080000    080459  ...         0.0        0.0       0
5857  20230808   080500    080959  ...         0.0        0.0       0
5858  20230808   081000    081459  ...         0.0        0.0       0
5859  20230808   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 08:20:06,632:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29193.5, self.close=29187.9, self.high=29193.6, self.low=29184.5, self.vol=404.397, self.amt=11803843.5611, ukdf['pct'].iloc[-1]=-0.000195 , ukdf['amount'].iloc[-1]=11803843.5611, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32460.1134', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29195.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=24737
self.closeSec=1691454299, self.tradeDate='20230808', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29188.0, self.close=29188.1, self.high=29195.9, self.low=29183.4, self.vol=375.185, self.amt=10951239.9769 
127.0.0.1 - - [08/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-08 08:25:00,814:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230808   080000    080459  ...         0.0        0.0       0
5857  20230808   080500    080959  ...         0.0        0.0       0
5858  20230808   081000    081459  ...         0.0        0.0       0
5859  20230808   081500    081959  ...         0.0        0.0       0
5860  20230808   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 08:25:00,815:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691454299, self.tradeDate='20230808', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29188.0, self.close=29188.1, self.high=29195.9, self.low=29183.4, self.vol=375.185, self.amt=10951239.9769, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=10951239.9769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32351.4906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29188', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29193.5, self.close=29187.9, self.high=29193.6, self.low=29184.5 
127.0.0.1 - - [08/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 08:20:04,632:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29193.5, self.close=29187.9, self.high=29193.6, self.low=29184.5   
2023-08-08 08:20:05,862:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230808   075500    075959  1691452799  ...  29197.2  0.000182   1535    5
1536  20230808   080000    080459  1691453099  ...  29186.3  0.000024   1536    0
1537  20230808   080500    080959  1691453399  ...  29203.3  0.000264   1537    1
1538  20230808   081000    081459  1691453699  ...  29193.5 -0.000596   1538    2
1539  20230808   081500    081959  1691453999  ...  29184.5 -0.000195   1539    3

[5 rows x 11 columns]
2023-08-08 08:20:05,871:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=171, self.factor=0.45759474053944915, self.count=24739 

self.closeSec=1691454299, self.tradeDate='20230808', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29188.0, self.close=29188.1, self.high=29195.9, self.low=29183.4 
127.0.0.1 - - [08/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-08 08:25:00,786:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691454299, self.tradeDate='20230808', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29188.0, self.close=29188.1, self.high=29195.9, self.low=29183.4   
2023-08-08 08:25:00,805:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230808   080000    080459  1691453099  ...  29186.3  0.000024   1536    0
1537  20230808   080500    080959  1691453399  ...  29203.3  0.000264   1537    1
1538  20230808   081000    081459  1691453699  ...  29193.5 -0.000596   1538    2
1539  20230808   081500    081959  1691453999  ...  29184.5 -0.000195   1539    3
1540  20230808   082000    082459  1691454299  ...  29183.4  0.000007   1540    4

[5 rows x 11 columns]
2023-08-08 08:25:00,805:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-08 08:00:18,262:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230808    052959  29186.5  ...  48.333333  0.558797  0.439530
5771  20230808    055959  29269.5  ...  47.916667  0.531604  0.420382
5772  20230808    062959  29184.2  ...  47.500000  0.525169  0.404875
5773  20230808    065959  29163.3  ...  47.916667  0.527199  0.389580
5774  20230808    072959  29170.7  ...  48.333333  0.527341  0.375248

[5 rows x 33 columns]
0.5434380776340111
acc is : 0.5434380776340111
2023-08-08 08:00:18,324:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.541108  0.458892       0  ...  0.952482   1.0    0.0  0.997174
537     1  0.493873  0.506127       0  ...  0.951797   1.0    0.0  0.996457
538     0  0.501435  0.498565       1  ...  0.952035   1.0    0.0  0.996706
539     0  0.507940  0.492060       1  ...  0.952052   1.0    0.0  0.996723
540     0  0.502882  0.497118       1  ...  0.953080   1.0    0.0  0.997800

[5 rows x 10 columns]
2023-08-08 08:00:18,336:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.541247  0.458753       0  ...  0.992687   1.0    0.0  0.996800
46     1  0.494037  0.505963       0  ...  0.951797   1.0    0.0  0.996310
47     0  0.501554  0.498446       1  ...  0.952035   1.0    0.0  0.996819
48     0  0.507940  0.492060       1  ...  0.952052   1.0    0.0  0.996723
49     0  0.502882  0.497118       1  ...  0.953080   1.0    0.0  0.997800

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '1763.598', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29204.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230808   075000    075959  1691452799    29203  29202.7 -0.000014
2023-08-08 08:00:02,193:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12368 

self.closeSec=1691453399, self.tradeDate='20230808', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29202.7', self.close='29211'
2023-08-08 08:10:01,146:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691453399, self.tradeDate='20230808', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29202.7', self.close='29211'
127.0.0.1 - - [08/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-08 08:10:01,164:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230808   072000    072959  1691450999  29170.4    29171  0.000024
621  20230808   073000    073959  1691451599  29171.1  29192.5  0.000737
622  20230808   074000    074959  1691452199  29192.5  29203.1  0.000363
623  20230808   075000    075959  1691452799    29203  29202.7 -0.000014
624  20230808   080000    080959  1691453399  29202.7    29211  0.000284
2023-08-08 08:10:01,164:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12369 

self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29211', self.close='29187.9'
127.0.0.1 - - [08/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 08:20:07,021:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29211', self.close='29187.9'
2023-08-08 08:20:07,662:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230808   073000    073959  1691451599  29171.1  29192.5  0.000737
622  20230808   074000    074959  1691452199  29192.5  29203.1  0.000363
623  20230808   075000    075959  1691452799    29203  29202.7 -0.000014
624  20230808   080000    080959  1691453399  29202.7    29211  0.000284
625  20230808   081000    081959  1691453999    29211  29187.9 -0.000791
2023-08-08 08:20:07,663:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230808   075000    075959  1691452799    29203  29202.7
2023-08-08 08:00:02,195:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12371 

self.closeSec=1691453399, self.tradeDate='20230808', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29202.7', self.close='29211'
2023-08-08 08:10:01,151:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691453399, self.tradeDate='20230808', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29202.7', self.close='29211'
2023-08-08 08:10:01,159:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230808   072000    072959  1691450999  29170.4    29171
17469  20230808   073000    073959  1691451599  29171.1  29192.5
17470  20230808   074000    074959  1691452199  29192.5  29203.1
17471  20230808   075000    075959  1691452799    29203  29202.7
17472  20230808   080000    080959  1691453399  29202.7    29211
2023-08-08 08:10:01,159:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12372 

self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29211', self.close='29187.9'
127.0.0.1 - - [08/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 08:20:08,816:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29211', self.close='29187.9'
2023-08-08 08:20:08,974:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230808   073000    073959  1691451599  29171.1  29192.5
17470  20230808   074000    074959  1691452199  29192.5  29203.1
17471  20230808   075000    075959  1691452799    29203  29202.7
17472  20230808   080000    080959  1691453399  29202.7    29211
17473  20230808   081000    081959  1691453999    29211  29187.9
2023-08-08 08:20:08,974:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230808   075000    075959  1691452799    29203  29202.7
2023-08-08 08:00:02,203:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12371 

self.closeSec=1691453399, self.tradeDate='20230808', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29202.7', self.close='29211'
127.0.0.1 - - [08/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-08 08:10:01,156:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691453399, self.tradeDate='20230808', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29202.7', self.close='29211'
2023-08-08 08:10:01,167:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230808   072000    072959  1691450999  29170.4    29171
12141  20230808   073000    073959  1691451599  29171.1  29192.5
12142  20230808   074000    074959  1691452199  29192.5  29203.1
12143  20230808   075000    075959  1691452799    29203  29202.7
12144  20230808   080000    080959  1691453399  29202.7    29211
2023-08-08 08:10:01,167:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12372 

self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29211', self.close='29187.9'
127.0.0.1 - - [08/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-08 08:20:08,622:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29211', self.close='29187.9'
2023-08-08 08:20:08,771:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230808   073000    073959  1691451599  29171.1  29192.5
12142  20230808   074000    074959  1691452199  29192.5  29203.1
12143  20230808   075000    075959  1691452799    29203  29202.7
12144  20230808   080000    080959  1691453399  29202.7    29211
12145  20230808   081000    081959  1691453999    29211  29187.9
2023-08-08 08:20:08,771:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24736
self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29193.5, self.close=29187.9, self.high=29193.6, self.low=29184.5, self.vol=404.397, self.amt=11803843.5611 
127.0.0.1 - - [08/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-08 08:20:06,583:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230808   075500    075959  ...         0.0        0.0       0
5856  20230808   080000    080459  ...         0.0        0.0       0
5857  20230808   080500    080959  ...         0.0        0.0       0
5858  20230808   081000    081459  ...         0.0        0.0       0
5859  20230808   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 08:20:06,602:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691453999, self.tradeDate='20230808', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29193.5, self.close=29187.9, self.high=29193.6, self.low=29184.5, self.vol=404.397, self.amt=11803843.5611, ukdf['pct'].iloc[-1]=-0.000195 , ukdf['amount'].iloc[-1]=11803843.5611, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87348.2038', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29195.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [08/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=24737
self.closeSec=1691454299, self.tradeDate='20230808', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29188.0, self.close=29188.1, self.high=29195.9, self.low=29183.4, self.vol=375.185, self.amt=10951239.9769 
2023-08-08 08:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230808   080000    080459  ...         0.0        0.0       0
5857  20230808   080500    080959  ...         0.0        0.0       0
5858  20230808   081000    081459  ...         0.0        0.0       0
5859  20230808   081500    081959  ...         0.0        0.0       0
5860  20230808   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-08 08:25:00,822:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691454299, self.tradeDate='20230808', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29188.0, self.close=29188.1, self.high=29195.9, self.low=29183.4, self.vol=375.185, self.amt=10951239.9769, ukdf['pct'].iloc[-1]=7e-06 , ukdf['amount'].iloc[-1]=10951239.9769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '87058.504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29188', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230807   200000    235959  1691423999  ...    719  0.060565 -1.198875    -1.0
720  20230808   000000    035959  1691438399  ...    720  0.012625 -1.399162    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-8377.4789', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29149.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1585089.2233008002, self.flagDict['side']='sell', self.tradeCount=18, self.count=515
self.closeSec=1691452799, self.tradeDate='20230808', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29144.9, self.close=29202.6, self.high=29274.5, self.low=29107.7, self.vol=34487.02, self.amt=1006610163.38059 
2023-08-08 08:00:01,750:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691452799, self.tradeDate='20230808', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29144.9, self.close=29202.6, self.high=29274.5, self.low=29107.7, self.vol=34487.02, self.amt=1006610163.38059 
2023-08-08 08:00:01,765:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230807   120000    155959  ...   22738.520  6.617512e+08 -0.002199
718  20230807   160000    195959  ...   23220.442  6.754080e+08  0.000038
719  20230807   200000    235959  ...   85465.104  2.475642e+09 -0.007997
720  20230808   000000    035959  ...  101877.164  2.950085e+09  0.010110
721  20230808   040000    075959  ...   34487.020  1.006610e+09  0.001980

[5 rows x 11 columns]
2023-08-08 08:00:02,602:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230807   120000    155959  1691395199  ...    717  0.120496 -0.929934    -1.0
718  20230807   160000    195959  1691409599  ...    718  0.120296 -0.932049    -1.0
719  20230807   200000    235959  1691423999  ...    719  0.060565 -1.198875    -1.0
720  20230808   000000    035959  1691438399  ...    720  0.012625 -1.399162    -1.0
721  20230808   040000    075959  1691452799  ...    721  0.008901 -1.397944    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.719', 'enterprice': '28996.8', 'countrevence': '0', 'unrealprofit': '-11301.66666980421', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29203.34008059', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


