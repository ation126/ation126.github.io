# 20230525 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3136
self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26345.1, self.close=26286.1, self.high=26351.8, self.low=26277.4, self.vol=1516.172, self.amt=39881731.9105 
127.0.0.1 - - [25/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 08:20:04,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230525   075500    075959  ...    0.112839   0.274079       0
5856  20230525   080000    080459  ...    0.112671   0.273962       0
5857  20230525   080500    080959  ...    0.112503   0.273845       0
5858  20230525   081000    081459  ...    0.112338   0.273734       0
5859  20230525   081500    081959  ...    0.112173   0.273622       0

[5 rows x 18 columns]
2023-05-25 08:20:04,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26345.1, self.close=26286.1, self.high=26351.8, self.low=26277.4, self.vol=1516.172, self.amt=39881731.9105, ukdf['pct'].iloc[-1]=-0.00224 , ukdf['amount'].iloc[-1]=39881731.9105, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.11217267194215043, signal=0, value_std=0.2736222186261967 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8075.55250566174', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26285.00968651', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3137
self.closeSec=1684974299, self.tradeDate='20230525', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26285.2, self.close=26280.3, self.high=26296.1, self.low=26253.1, self.vol=1876.702, self.amt=49311156.0587 
2023-05-25 08:25:00,846:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230525   080000    080459  ...    0.112671   0.273962       0
5857  20230525   080500    080959  ...    0.112503   0.273845       0
5858  20230525   081000    081459  ...    0.112338   0.273734       0
5859  20230525   081500    081959  ...    0.112173   0.273622       0
5860  20230525   082000    082459  ...    0.112003   0.273502       0

[5 rows x 18 columns]
2023-05-25 08:25:00,848:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684974299, self.tradeDate='20230525', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26285.2, self.close=26280.3, self.high=26296.1, self.low=26253.1, self.vol=1876.702, self.amt=49311156.0587, ukdf['pct'].iloc[-1]=-0.000221 , ukdf['amount'].iloc[-1]=49311156.0587, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.11200289498951707, signal=0, value_std=0.2735021228462533 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8141.1396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26280.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26345.1, self.close=26286.1, self.high=26351.8, self.low=26277.4 
127.0.0.1 - - [25/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 08:20:02,506:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26345.1, self.close=26286.1, self.high=26351.8, self.low=26277.4   
2023-05-25 08:20:03,716:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230525   075500    075959  1684972799  ...  26313.8 -0.000475   1535    5
1536  20230525   080000    080459  1684973099  ...  26291.9  0.001015   1536    0
1537  20230525   080500    080959  1684973399  ...  26313.1  0.001055   1537    1
1538  20230525   081000    081459  1684973699  ...  26339.4 -0.000880   1538    2
1539  20230525   081500    081959  1684973999  ...  26277.4 -0.002240   1539    3

[5 rows x 11 columns]
2023-05-25 08:20:03,736:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [25/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7355861780843191, self.count=3139 

self.closeSec=1684974299, self.tradeDate='20230525', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26285.2, self.close=26280.3, self.high=26296.1, self.low=26253.1 
2023-05-25 08:25:00,764:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684974299, self.tradeDate='20230525', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26285.2, self.close=26280.3, self.high=26296.1, self.low=26253.1   
2023-05-25 08:25:00,814:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230525   080000    080459  1684973099  ...  26291.9  0.001015   1536    0
1537  20230525   080500    080959  1684973399  ...  26313.1  0.001055   1537    1
1538  20230525   081000    081459  1684973699  ...  26339.4 -0.000880   1538    2
1539  20230525   081500    081959  1684973999  ...  26277.4 -0.002240   1539    3
1540  20230525   082000    082459  1684974299  ...  26253.1 -0.000221   1540    4

[5 rows x 11 columns]
2023-05-25 08:25:00,814:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-25 08:00:36,979:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230525    052959  26390.9  ...  45.833333  0.409897  0.787903
5771  20230525    055959  26396.0  ...  45.416667  0.402493  0.784174
5772  20230525    062959  26356.2  ...  45.416667  0.396184  0.782763
5773  20230525    065959  26321.9  ...  45.833333  0.400461  0.780398
5774  20230525    072959  26337.3  ...  45.416667  0.396286  0.775234

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-05-25 08:00:37,173:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.526387  0.473613       0  ...  0.943000   1.0    0.0  0.982667
537     0  0.506326  0.493674       0  ...  0.941773   1.0    0.0  0.981388
538     0  0.509955  0.490045       1  ...  0.942320   1.0    0.0  0.981958
539     0  0.503874  0.496126       0  ...  0.941522   1.0    0.0  0.981127
540     1  0.497776  0.502224       0  ...  0.941483   1.0    0.0  0.981086

[5 rows x 10 columns]
2023-05-25 08:00:37,204:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526252  0.473748       0  ...  0.943000   1.0    0.0  0.983367
46     0  0.506412  0.493588       0  ...  0.941773   1.0    0.0  0.982256
47     0  0.509792  0.490208       1  ...  0.942320   1.0    0.0  0.982365
48     0  0.503874  0.496126       0  ...  0.941522   1.0    0.0  0.981127
49     1  0.497776  0.502224       0  ...  0.941483   1.0    0.0  0.981086

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.343', 'enterprice': '26406.6', 'countrevence': '0', 'unrealprofit': '-2523.13317567882', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26314.32288426', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230525   075000    075959  1684972799  26349.8  26313.8 -0.001370
2023-05-25 08:00:02,277:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1568 

self.closeSec=1684973399, self.tradeDate='20230525', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26313.9', self.close='26368.3'
2023-05-25 08:10:01,192:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684973399, self.tradeDate='20230525', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26313.9', self.close='26368.3'
127.0.0.1 - - [25/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-25 08:10:01,210:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230525   072000    072959  1684970999  26346.4  26314.9 -0.001196
621  20230525   073000    073959  1684971599  26314.9  26330.4  0.000589
622  20230525   074000    074959  1684972199  26330.4  26349.9  0.000741
623  20230525   075000    075959  1684972799  26349.8  26313.8 -0.001370
624  20230525   080000    080959  1684973399  26313.9  26368.3  0.002071
2023-05-25 08:10:01,210:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1569 

self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26368.2', self.close='26285.2'
127.0.0.1 - - [25/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-25 08:20:05,206:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26368.2', self.close='26285.2'
2023-05-25 08:20:05,746:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230525   073000    073959  1684971599  26314.9  26330.4  0.000589
622  20230525   074000    074959  1684972199  26330.4  26349.9  0.000741
623  20230525   075000    075959  1684972799  26349.8  26313.8 -0.001370
624  20230525   080000    080959  1684973399  26313.9  26368.3  0.002071
625  20230525   081000    081959  1684973999  26368.2  26285.2 -0.003152
2023-05-25 08:20:05,746:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230525   075000    075959  1684972799  26349.8  26313.8
2023-05-25 08:00:02,303:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1571 

self.closeSec=1684973399, self.tradeDate='20230525', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26313.9', self.close='26368.3'
2023-05-25 08:10:01,183:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684973399, self.tradeDate='20230525', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26313.9', self.close='26368.3'
2023-05-25 08:10:01,224:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230525   072000    072959  1684970999  26346.4  26314.9
17469  20230525   073000    073959  1684971599  26314.9  26330.4
17470  20230525   074000    074959  1684972199  26330.4  26349.9
17471  20230525   075000    075959  1684972799  26349.8  26313.8
17472  20230525   080000    080959  1684973399  26313.9  26368.3
2023-05-25 08:10:01,225:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1572 

self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26368.2', self.close='26285.2'
127.0.0.1 - - [25/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-25 08:20:06,378:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26368.2', self.close='26285.2'
2023-05-25 08:20:06,509:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230525   073000    073959  1684971599  26314.9  26330.4
17470  20230525   074000    074959  1684972199  26330.4  26349.9
17471  20230525   075000    075959  1684972799  26349.8  26313.8
17472  20230525   080000    080959  1684973399  26313.9  26368.3
17473  20230525   081000    081959  1684973999  26368.2  26285.2
2023-05-25 08:20:06,510:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230525   075000    075959  1684972799  26349.8  26313.8
2023-05-25 08:00:02,292:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1571 

self.closeSec=1684973399, self.tradeDate='20230525', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26313.9', self.close='26368.3'
2023-05-25 08:10:01,179:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684973399, self.tradeDate='20230525', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26313.9', self.close='26368.3'
2023-05-25 08:10:01,214:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230525   072000    072959  1684970999  26346.4  26314.9
12141  20230525   073000    073959  1684971599  26314.9  26330.4
12142  20230525   074000    074959  1684972199  26330.4  26349.9
12143  20230525   075000    075959  1684972799  26349.8  26313.8
12144  20230525   080000    080959  1684973399  26313.9  26368.3
2023-05-25 08:10:01,214:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1572 

self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26368.2', self.close='26285.2'
127.0.0.1 - - [25/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-25 08:20:06,150:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26368.2', self.close='26285.2'
2023-05-25 08:20:06,319:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230525   073000    073959  1684971599  26314.9  26330.4
12142  20230525   074000    074959  1684972199  26330.4  26349.9
12143  20230525   075000    075959  1684972799  26349.8  26313.8
12144  20230525   080000    080959  1684973399  26313.9  26368.3
12145  20230525   081000    081959  1684973999  26368.2  26285.2
2023-05-25 08:20:06,319:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3136
self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26345.1, self.close=26286.1, self.high=26351.8, self.low=26277.4, self.vol=1516.172, self.amt=39881731.9105 
127.0.0.1 - - [25/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 08:20:05,066:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230525   075500    075959  ...         0.0        0.0       0
5856  20230525   080000    080459  ...         0.0        0.0       0
5857  20230525   080500    080959  ...         0.0        0.0       0
5858  20230525   081000    081459  ...         0.0        0.0       0
5859  20230525   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-25 08:20:05,096:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684973999, self.tradeDate='20230525', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26345.1, self.close=26286.1, self.high=26351.8, self.low=26277.4, self.vol=1516.172, self.amt=39881731.9105, ukdf['pct'].iloc[-1]=-0.00224 , ukdf['amount'].iloc[-1]=39881731.9105, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-20761.45923333209', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26285.00968651', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3137
self.closeSec=1684974299, self.tradeDate='20230525', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26285.2, self.close=26280.3, self.high=26296.1, self.low=26253.1, self.vol=1876.702, self.amt=49311156.0587 
127.0.0.1 - - [25/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-25 08:25:00,850:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230525   080000    080459  ...         0.0        0.0       0
5857  20230525   080500    080959  ...         0.0        0.0       0
5858  20230525   081000    081459  ...         0.0        0.0       0
5859  20230525   081500    081959  ...         0.0        0.0       0
5860  20230525   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-25 08:25:00,851:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684974299, self.tradeDate='20230525', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26285.2, self.close=26280.3, self.high=26296.1, self.low=26253.1, self.vol=1876.702, self.amt=49311156.0587, ukdf['pct'].iloc[-1]=-0.000221 , ukdf['amount'].iloc[-1]=49311156.0587, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-20936.3817', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26280.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230524   200000    235959  1684943999  ...    719  0.282606 -0.560483     NaN
720  20230525   000000    035959  1684958399  ...    720  0.402509  0.062808     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '42723.5411811831', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26241.7052381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [25/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=65
self.closeSec=1684972799, self.tradeDate='20230525', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26241.6, self.close=26313.8, self.high=26476.0, self.low=26228.2, self.vol=50565.341, self.amt=1333426055.9433 
2023-05-25 08:00:01,844:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684972799, self.tradeDate='20230525', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26241.6, self.close=26313.8, self.high=26476.0, self.low=26228.2, self.vol=50565.341, self.amt=1333426055.9433 
2023-05-25 08:00:01,906:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230524   120000    155959  ...   72171.252  1.928814e+09 -0.003952
718  20230524   160000    195959  ...   47356.312  1.265978e+09  0.002531
719  20230524   200000    235959  ...  189840.762  5.000674e+09 -0.015891
720  20230525   000000    035959  ...   69968.498  1.837039e+09 -0.002482
721  20230525   040000    075959  ...   50565.341  1.333426e+09  0.002751

[5 rows x 11 columns]
2023-05-25 08:00:03,612:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230524   120000    155959  1684915199  ...    717  0.351419 -0.259060     NaN
718  20230524   160000    195959  1684929599  ...    718  0.385182 -0.077219     NaN
719  20230524   200000    235959  1684943999  ...    719  0.282606 -0.560483     NaN
720  20230525   000000    035959  1684958399  ...    720  0.402509  0.062808     NaN
721  20230525   040000    075959  1684972799  ...    721  0.463025  0.405514     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '38957.68500138846', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26314.75915146', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


