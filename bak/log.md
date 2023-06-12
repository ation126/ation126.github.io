# 20230612 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8320
self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25935.6, self.close=25886.5, self.high=25947.9, self.low=25877.0, self.vol=910.73, self.amt=23594277.1638 
127.0.0.1 - - [12/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-12 08:20:06,859:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230612   075500    075959  ...         0.0        0.0       0
5856  20230612   080000    080459  ...         0.0        0.0       0
5857  20230612   080500    080959  ...         0.0        0.0       0
5858  20230612   081000    081459  ...         0.0        0.0       0
5859  20230612   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 08:20:06,909:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25935.6, self.close=25886.5, self.high=25947.9, self.low=25877.0, self.vol=910.73, self.amt=23594277.1638, ukdf['pct'].iloc[-1]=-0.001893 , ukdf['amount'].iloc[-1]=23594277.1638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13658.6208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25884.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8321
self.closeSec=1686529499, self.tradeDate='20230612', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25886.6, self.close=25879.8, self.high=25923.8, self.low=25875.6, self.vol=726.936, self.amt=18822224.2937 
127.0.0.1 - - [12/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 08:25:04,316:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230612   080000    080459  ...         0.0        0.0       0
5857  20230612   080500    080959  ...         0.0        0.0       0
5858  20230612   081000    081459  ...         0.0        0.0       0
5859  20230612   081500    081959  ...         0.0        0.0       0
5860  20230612   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 08:25:04,320:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686529499, self.tradeDate='20230612', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25886.6, self.close=25879.8, self.high=25923.8, self.low=25875.6, self.vol=726.936, self.amt=18822224.2937, ukdf['pct'].iloc[-1]=-0.000259 , ukdf['amount'].iloc[-1]=18822224.2937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13611.2724', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25887.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25935.6, self.close=25886.5, self.high=25947.9, self.low=25877.0 
127.0.0.1 - - [12/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-12 08:20:04,397:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25935.6, self.close=25886.5, self.high=25947.9, self.low=25877.0   
2023-06-12 08:20:05,448:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230612   075500    075959  1686527999  ...  25903.2  0.000197   1535    5
1536  20230612   080000    080459  1686528299  ...  25900.3 -0.000035   1536    0
1537  20230612   080500    080959  1686528599  ...  25890.5 -0.000104   1537    1
1538  20230612   081000    081459  1686528899  ...  25906.3  0.001127   1538    2
1539  20230612   081500    081959  1686529199  ...  25877.0 -0.001893   1539    3

[5 rows x 11 columns]
2023-06-12 08:20:05,458:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=27, self.factor=0.453987443917782, self.count=8323 

self.closeSec=1686529499, self.tradeDate='20230612', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25886.6, self.close=25879.8, self.high=25923.8, self.low=25875.6 
127.0.0.1 - - [12/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 08:25:03,348:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686529499, self.tradeDate='20230612', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25886.6, self.close=25879.8, self.high=25923.8, self.low=25875.6   
2023-06-12 08:25:04,048:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230612   080000    080459  1686528299  ...  25900.3 -0.000035   1536    0
1537  20230612   080500    080959  1686528599  ...  25890.5 -0.000104   1537    1
1538  20230612   081000    081459  1686528899  ...  25906.3  0.001127   1538    2
1539  20230612   081500    081959  1686529199  ...  25877.0 -0.001893   1539    3
1540  20230612   082000    082459  1686529499  ...  25875.6 -0.000259   1540    4

[5 rows x 11 columns]
2023-06-12 08:25:04,049:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-12 08:00:43,125:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230612    052959  26110.9  ...  49.583333  0.535827  0.345661
5771  20230612    055959  26078.4  ...  49.166667  0.525212  0.341658
5772  20230612    062959  26034.0  ...  49.166667  0.512239  0.344327
5773  20230612    065959  25978.4  ...  48.750000  0.491119  0.357746
5774  20230612    072959  25883.8  ...  48.333333  0.481954  0.375209

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-06-12 08:00:43,283:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.506886  0.493114       0  ...  0.962127  -1.0    0.0  0.965416
537     1  0.492736  0.507264       0  ...  0.964178  -1.0    0.0  0.963358
538     1  0.488047  0.511953       0  ...  0.967693  -1.0    0.0  0.959847
539     1  0.466134  0.533866       0  ...  0.969293  -1.0    0.0  0.958259
540     1  0.469105  0.530895       1  ...  0.966709  -1.0    0.0  0.960814

[5 rows x 10 columns]
2023-06-12 08:00:43,307:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.506952  0.493048       0  ...  0.962127  -1.0    0.0  0.967803
46     1  0.492755  0.507245       0  ...  0.964178  -1.0    0.0  0.963834
47     1  0.488120  0.511880       0  ...  0.967693  -1.0    0.0  0.961198
48     1  0.466134  0.533866       0  ...  0.969293  -1.0    0.0  0.958259
49     1  0.469105  0.530895       1  ...  0.966709  -1.0    0.0  0.960814

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-10007.0126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25914.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230612   075000    075959  1686527999    25877  25909.9  0.001271
2023-06-12 08:00:02,255:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4160 

self.closeSec=1686528599, self.tradeDate='20230612', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25910', self.close='25906.4'
2023-06-12 08:10:01,212:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686528599, self.tradeDate='20230612', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25910', self.close='25906.4'
2023-06-12 08:10:01,268:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230612   072000    072959  1686526199  25889.1  25839.5 -0.001916
621  20230612   073000    073959  1686526799  25839.5  25870.9  0.001215
622  20230612   074000    074959  1686527399  25870.9    25877  0.000236
623  20230612   075000    075959  1686527999    25877  25909.9  0.001271
624  20230612   080000    080959  1686528599    25910  25906.4 -0.000135
2023-06-12 08:10:01,268:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4161 

self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25906.3', self.close='25886.5'
127.0.0.1 - - [12/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-12 08:20:07,010:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25906.3', self.close='25886.5'
2023-06-12 08:20:07,990:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230612   073000    073959  1686526799  25839.5  25870.9  0.001215
622  20230612   074000    074959  1686527399  25870.9    25877  0.000236
623  20230612   075000    075959  1686527999    25877  25909.9  0.001271
624  20230612   080000    080959  1686528599    25910  25906.4 -0.000135
625  20230612   081000    081959  1686529199  25906.3  25886.5 -0.000768
2023-06-12 08:20:08,003:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230612   075000    075959  1686527999    25877  25909.9
2023-06-12 08:00:02,197:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [12/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4163 

self.closeSec=1686528599, self.tradeDate='20230612', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25910', self.close='25906.4'
2023-06-12 08:10:01,256:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686528599, self.tradeDate='20230612', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25910', self.close='25906.4'
2023-06-12 08:10:01,317:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230612   072000    072959  1686526199  25889.1  25839.5
17469  20230612   073000    073959  1686526799  25839.5  25870.9
17470  20230612   074000    074959  1686527399  25870.9    25877
17471  20230612   075000    075959  1686527999    25877  25909.9
17472  20230612   080000    080959  1686528599    25910  25906.4
2023-06-12 08:10:01,317:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4164 

self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25906.3', self.close='25886.5'
127.0.0.1 - - [12/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-12 08:20:09,035:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25906.3', self.close='25886.5'
2023-06-12 08:20:09,189:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230612   073000    073959  1686526799  25839.5  25870.9
17470  20230612   074000    074959  1686527399  25870.9    25877
17471  20230612   075000    075959  1686527999    25877  25909.9
17472  20230612   080000    080959  1686528599    25910  25906.4
17473  20230612   081000    081959  1686529199  25906.3  25886.5
2023-06-12 08:20:09,189:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230612   075000    075959  1686527999    25877  25909.9
2023-06-12 08:00:02,256:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4163 

self.closeSec=1686528599, self.tradeDate='20230612', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25910', self.close='25906.4'
2023-06-12 08:10:01,237:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686528599, self.tradeDate='20230612', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25910', self.close='25906.4'
2023-06-12 08:10:01,288:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230612   072000    072959  1686526199  25889.1  25839.5
12141  20230612   073000    073959  1686526799  25839.5  25870.9
12142  20230612   074000    074959  1686527399  25870.9    25877
12143  20230612   075000    075959  1686527999    25877  25909.9
12144  20230612   080000    080959  1686528599    25910  25906.4
2023-06-12 08:10:01,288:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4164 

self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25906.3', self.close='25886.5'
127.0.0.1 - - [12/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-12 08:20:08,760:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25906.3', self.close='25886.5'
2023-06-12 08:20:09,021:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230612   073000    073959  1686526799  25839.5  25870.9
12142  20230612   074000    074959  1686527399  25870.9    25877
12143  20230612   075000    075959  1686527999    25877  25909.9
12144  20230612   080000    080959  1686528599    25910  25906.4
12145  20230612   081000    081959  1686529199  25906.3  25886.5
2023-06-12 08:20:09,029:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8320
self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25935.6, self.close=25886.5, self.high=25947.9, self.low=25877.0, self.vol=910.73, self.amt=23594277.1638 
127.0.0.1 - - [12/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-12 08:20:06,839:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230612   075500    075959  ...         0.0        0.0       0
5856  20230612   080000    080459  ...         0.0        0.0       0
5857  20230612   080500    080959  ...         0.0        0.0       0
5858  20230612   081000    081459  ...         0.0        0.0       0
5859  20230612   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 08:20:06,890:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686529199, self.tradeDate='20230612', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25935.6, self.close=25886.5, self.high=25947.9, self.low=25877.0, self.vol=910.73, self.amt=23594277.1638, ukdf['pct'].iloc[-1]=-0.001893 , ukdf['amount'].iloc[-1]=23594277.1638, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35651.6459', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25884.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8321
self.closeSec=1686529499, self.tradeDate='20230612', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25886.6, self.close=25879.8, self.high=25923.8, self.low=25875.6, self.vol=726.936, self.amt=18822224.2937 
127.0.0.1 - - [12/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 08:25:04,460:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230612   080000    080459  ...         0.0        0.0       0
5857  20230612   080500    080959  ...         0.0        0.0       0
5858  20230612   081000    081459  ...         0.0        0.0       0
5859  20230612   081500    081959  ...         0.0        0.0       0
5860  20230612   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 08:25:04,477:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686529499, self.tradeDate='20230612', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25886.6, self.close=25879.8, self.high=25923.8, self.low=25875.6, self.vol=726.936, self.amt=18822224.2937, ukdf['pct'].iloc[-1]=-0.000259 , ukdf['amount'].iloc[-1]=18822224.2937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35525.3665', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25887.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230611   200000    235959  1686499199  ...    719  0.493000 -0.328305     NaN
720  20230612   000000    035959  1686513599  ...    720  0.484214 -0.360866     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '58034.632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26026.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [12/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=173
self.closeSec=1686527999, self.tradeDate='20230612', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26021.1, self.close=25909.9, self.high=26199.0, self.low=25726.2, self.vol=74781.74, self.amt=1942771269.02003 
2023-06-12 08:00:01,727:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686527999, self.tradeDate='20230612', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26021.1, self.close=25909.9, self.high=26199.0, self.low=25726.2, self.vol=74781.74, self.amt=1942771269.02003 
2023-06-12 08:00:01,775:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230611   120000    155959  ...  31162.773  8.018352e+08  0.000517
718  20230611   160000    195959  ...  25758.698  6.632785e+08  0.002212
719  20230611   200000    235959  ...  28819.212  7.417487e+08 -0.001695
720  20230612   000000    035959  ...  85800.036  2.226062e+09  0.010870
721  20230612   040000    075959  ...  74781.740  1.942771e+09 -0.004270

[5 rows x 11 columns]
2023-06-12 08:00:04,203:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230611   120000    155959  1686470399  ...    717  0.458586 -0.439942     NaN
718  20230611   160000    195959  1686484799  ...    718  0.477919 -0.376401     NaN
719  20230611   200000    235959  1686499199  ...    719  0.493000 -0.328305     NaN
720  20230612   000000    035959  1686513599  ...    720  0.484214 -0.360866     NaN
721  20230612   040000    075959  1686527999  ...    721  0.464084 -0.433618     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '64344.83936717608', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25912.21419412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


