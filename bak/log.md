# 20230608 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [08/Jun/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7168
self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26316.7, self.close=26338.9, self.high=26348.0, self.low=26294.4, self.vol=982.684, self.amt=25858983.2565 
2023-06-08 08:20:01,462:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230608   075500    075959  ...         0.0        0.0       0
5856  20230608   080000    080459  ...         0.0        0.0       0
5857  20230608   080500    080959  ...         0.0        0.0       0
5858  20230608   081000    081459  ...         0.0        0.0       0
5859  20230608   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 08:20:01,472:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26316.7, self.close=26338.9, self.high=26348.0, self.low=26294.4, self.vol=982.684, self.amt=25858983.2565, ukdf['pct'].iloc[-1]=0.000847 , ukdf['amount'].iloc[-1]=25858983.2565, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7311.04580789616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26339.90748184', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7169
self.closeSec=1686183899, self.tradeDate='20230608', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26339.8, self.close=26336.0, self.high=26348.4, self.low=26309.4, self.vol=703.802, self.amt=18530848.8613 
127.0.0.1 - - [08/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:25:04,337:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230608   080000    080459  ...         0.0        0.0       0
5857  20230608   080500    080959  ...         0.0        0.0       0
5858  20230608   081000    081459  ...         0.0        0.0       0
5859  20230608   081500    081959  ...         0.0        0.0       0
5860  20230608   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 08:25:04,344:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686183899, self.tradeDate='20230608', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26339.8, self.close=26336.0, self.high=26348.4, self.low=26309.4, self.vol=703.802, self.amt=18530848.8613, ukdf['pct'].iloc[-1]=-0.00011 , ukdf['amount'].iloc[-1]=18530848.8613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '7365.4614', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26336', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26316.7, self.close=26338.9, self.high=26348.0, self.low=26294.4 
127.0.0.1 - - [08/Jun/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-06-08 08:20:01,122:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26316.7, self.close=26338.9, self.high=26348.0, self.low=26294.4   
2023-06-08 08:20:01,240:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230608   075500    075959  1686182399  ...  26324.8 -0.001119   1535    5
1536  20230608   080000    080459  1686182699  ...  26313.4  0.000038   1536    0
1537  20230608   080500    080959  1686182999  ...  26301.1 -0.000839   1537    1
1538  20230608   081000    081459  1686183299  ...  26304.8  0.000449   1538    2
1539  20230608   081500    081959  1686183599  ...  26294.4  0.000847   1539    3

[5 rows x 11 columns]
2023-06-08 08:20:01,241:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=11, self.factor=0.579992508540442, self.count=7171 

self.closeSec=1686183899, self.tradeDate='20230608', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26339.8, self.close=26336.0, self.high=26348.4, self.low=26309.4 
127.0.0.1 - - [08/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:25:03,066:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686183899, self.tradeDate='20230608', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26339.8, self.close=26336.0, self.high=26348.4, self.low=26309.4   
2023-06-08 08:25:03,909:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230608   080000    080459  1686182699  ...  26313.4  0.000038   1536    0
1537  20230608   080500    080959  1686182999  ...  26301.1 -0.000839   1537    1
1538  20230608   081000    081459  1686183299  ...  26304.8  0.000449   1538    2
1539  20230608   081500    081959  1686183599  ...  26294.4  0.000847   1539    3
1540  20230608   082000    082459  1686183899  ...  26309.4 -0.000110   1540    4

[5 rows x 11 columns]
2023-06-08 08:25:03,918:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-08 08:00:36,090:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230608    052959  26351.1  ...  47.083333  0.485261  0.663580
5771  20230608    055959  26442.7  ...  46.666667  0.444215  0.684376
5772  20230608    062959  26141.9  ...  46.666667  0.463493  0.694203
5773  20230608    065959  26263.0  ...  46.666667  0.463671  0.702746
5774  20230608    072959  26264.4  ...  47.083333  0.468301  0.708332

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-06-08 08:00:36,232:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.520970  0.479030       0  ...  1.137463  -1.0    0.0  0.980234
537     1  0.420113  0.579887       1  ...  1.131887  -1.0    0.0  0.985039
538     0  0.512106  0.487894       1  ...  1.131836  -1.0    0.0  0.985084
539     1  0.499885  0.500115       1  ...  1.130504  -1.0    0.0  0.986243
540     0  0.507501  0.492499       1  ...  1.129184  -1.0    0.0  0.987394

[5 rows x 10 columns]
2023-06-08 08:00:36,257:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520838  0.479162       0  ...  1.137463  -1.0    0.0  0.979492
46     1  0.420154  0.579846       1  ...  1.131887  -1.0    0.0  0.985186
47     0  0.512270  0.487730       1  ...  1.131836  -1.0    0.0  0.985376
48     1  0.499885  0.500115       1  ...  1.130504  -1.0    0.0  0.986243
49     0  0.507501  0.492499       1  ...  1.129184  -1.0    0.0  0.987394

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.022', 'enterprice': '26938.4', 'countrevence': '0', 'unrealprofit': '17113.0354', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26327.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230608   075000    075959  1686182399  26338.7  26325.9 -0.000486
2023-06-08 08:00:02,318:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3584 

self.closeSec=1686182999, self.tradeDate='20230608', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26325.9', self.close='26304.8'
2023-06-08 08:10:01,171:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686182999, self.tradeDate='20230608', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26325.9', self.close='26304.8'
127.0.0.1 - - [08/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:10:01,204:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230608   072000    072959  1686180599  26294.5  26295.2  0.000027
621  20230608   073000    073959  1686181199  26295.1  26331.1  0.001365
622  20230608   074000    074959  1686181799  26331.2  26338.7  0.000289
623  20230608   075000    075959  1686182399  26338.7  26325.9 -0.000486
624  20230608   080000    080959  1686182999  26325.9  26304.8 -0.000801
2023-06-08 08:10:01,204:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3585 

self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26304.8', self.close='26339.8'
127.0.0.1 - - [08/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:20:01,443:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26304.8', self.close='26339.8'
2023-06-08 08:20:01,505:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230608   073000    073959  1686181199  26295.1  26331.1  0.001365
622  20230608   074000    074959  1686181799  26331.2  26338.7  0.000289
623  20230608   075000    075959  1686182399  26338.7  26325.9 -0.000486
624  20230608   080000    080959  1686182999  26325.9  26304.8 -0.000801
625  20230608   081000    081959  1686183599  26304.8  26339.8  0.001331
2023-06-08 08:20:01,507:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230608   075000    075959  1686182399  26338.7  26325.9
2023-06-08 08:00:02,338:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3587 

self.closeSec=1686182999, self.tradeDate='20230608', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26325.9', self.close='26304.8'
127.0.0.1 - - [08/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:10:01,160:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686182999, self.tradeDate='20230608', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26325.9', self.close='26304.8'
2023-06-08 08:10:01,197:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230608   072000    072959  1686180599  26294.5  26295.2
17469  20230608   073000    073959  1686181199  26295.1  26331.1
17470  20230608   074000    074959  1686181799  26331.2  26338.7
17471  20230608   075000    075959  1686182399  26338.7  26325.9
17472  20230608   080000    080959  1686182999  26325.9  26304.8
2023-06-08 08:10:01,197:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3588 

self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26304.8', self.close='26339.8'
2023-06-08 08:20:01,584:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26304.8', self.close='26339.8'
2023-06-08 08:20:01,609:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230608   073000    073959  1686181199  26295.1  26331.1
17470  20230608   074000    074959  1686181799  26331.2  26338.7
17471  20230608   075000    075959  1686182399  26338.7  26325.9
17472  20230608   080000    080959  1686182999  26325.9  26304.8
17473  20230608   081000    081959  1686183599  26304.8  26339.8
2023-06-08 08:20:01,610:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230608   075000    075959  1686182399  26338.7  26325.9
2023-06-08 08:00:02,337:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3587 

self.closeSec=1686182999, self.tradeDate='20230608', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26325.9', self.close='26304.8'
2023-06-08 08:10:01,152:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686182999, self.tradeDate='20230608', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26325.9', self.close='26304.8'
127.0.0.1 - - [08/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:10:01,203:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230608   072000    072959  1686180599  26294.5  26295.2
12141  20230608   073000    073959  1686181199  26295.1  26331.1
12142  20230608   074000    074959  1686181799  26331.2  26338.7
12143  20230608   075000    075959  1686182399  26338.7  26325.9
12144  20230608   080000    080959  1686182999  26325.9  26304.8
2023-06-08 08:10:01,205:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3588 

self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26304.8', self.close='26339.8'
127.0.0.1 - - [08/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:20:01,501:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26304.8', self.close='26339.8'
2023-06-08 08:20:01,525:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230608   073000    073959  1686181199  26295.1  26331.1
12142  20230608   074000    074959  1686181799  26331.2  26338.7
12143  20230608   075000    075959  1686182399  26338.7  26325.9
12144  20230608   080000    080959  1686182999  26325.9  26304.8
12145  20230608   081000    081959  1686183599  26304.8  26339.8
2023-06-08 08:20:01,525:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7168
self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26316.7, self.close=26338.9, self.high=26348.0, self.low=26294.4, self.vol=982.684, self.amt=25858983.2565 
127.0.0.1 - - [08/Jun/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-06-08 08:20:01,430:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230608   075500    075959  ...         0.0        0.0       0
5856  20230608   080000    080459  ...         0.0        0.0       0
5857  20230608   080500    080959  ...         0.0        0.0       0
5858  20230608   081000    081459  ...         0.0        0.0       0
5859  20230608   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 08:20:01,434:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686183599, self.tradeDate='20230608', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26316.7, self.close=26338.9, self.high=26348.0, self.low=26294.4, self.vol=982.684, self.amt=25858983.2565, ukdf['pct'].iloc[-1]=0.000847 , ukdf['amount'].iloc[-1]=25858983.2565, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18722.50021698056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26339.90748184', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7169
self.closeSec=1686183899, self.tradeDate='20230608', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26339.8, self.close=26336.0, self.high=26348.4, self.low=26309.4, self.vol=703.802, self.amt=18530848.8613 
127.0.0.1 - - [08/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:25:04,340:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230608   080000    080459  ...         0.0        0.0       0
5857  20230608   080500    080959  ...         0.0        0.0       0
5858  20230608   081000    081459  ...         0.0        0.0       0
5859  20230608   081500    081959  ...         0.0        0.0       0
5860  20230608   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-08 08:25:04,345:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686183899, self.tradeDate='20230608', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26339.8, self.close=26336.0, self.high=26348.4, self.low=26309.4, self.vol=703.802, self.amt=18530848.8613, ukdf['pct'].iloc[-1]=-0.00011 , ukdf['amount'].iloc[-1]=18530848.8613, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-18867.628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26336', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230607   200000    235959  1686153599  ...    719  0.502840 -0.313424     NaN
720  20230608   000000    035959  1686167999  ...    720  0.503967 -0.310189     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '33300.31798851066', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26474.96156349', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=149
self.closeSec=1686182399, self.tradeDate='20230608', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26469.2, self.close=26325.9, self.high=26483.5, self.low=26111.0, self.vol=64175.757, self.amt=1687819280.67292 
127.0.0.1 - - [08/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-08 08:00:01,806:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686182399, self.tradeDate='20230608', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26469.2, self.close=26325.9, self.high=26483.5, self.low=26111.0, self.vol=64175.757, self.amt=1687819280.67292 
2023-06-08 08:00:01,862:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230607   120000    155959  ...   47010.017  1.263080e+09 -0.004101
718  20230607   160000    195959  ...  151149.929  4.026422e+09  0.003793
719  20230607   200000    235959  ...  202615.316  5.380169e+09 -0.020619
720  20230608   000000    035959  ...   80719.705  2.130781e+09  0.005138
721  20230608   040000    075959  ...   64175.757  1.687819e+09 -0.005414

[5 rows x 11 columns]
2023-06-08 08:00:04,601:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230607   120000    155959  1686124799  ...    717  0.503559 -0.291878     NaN
718  20230607   160000    195959  1686139199  ...    718  0.501072 -0.310688     NaN
719  20230607   200000    235959  1686153599  ...    719  0.502840 -0.313424     NaN
720  20230608   000000    035959  1686167999  ...    720  0.503967 -0.310189     NaN
721  20230608   040000    075959  1686182399  ...    721  0.500401 -0.323202     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '41428.96241449098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26327.61275397', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


