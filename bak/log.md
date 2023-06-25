# 20230625 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12064
self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30579.5, self.close=30544.2, self.high=30579.6, self.low=30544.1, self.vol=516.951, self.amt=15798609.2445 
127.0.0.1 - - [25/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 08:20:07,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230625   075500    075959  ...         0.0        0.0       0
5856  20230625   080000    080459  ...         0.0        0.0       0
5857  20230625   080500    080959  ...         0.0        0.0       0
5858  20230625   081000    081459  ...         0.0        0.0       0
5859  20230625   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 08:20:07,840:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30579.5, self.close=30544.2, self.high=30579.6, self.low=30544.1, self.vol=516.951, self.amt=15798609.2445, ukdf['pct'].iloc[-1]=-0.001158 , ukdf['amount'].iloc[-1]=15798609.2445, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51217.0428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30542.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12065
self.closeSec=1687652699, self.tradeDate='20230625', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30544.1, self.close=30495.7, self.high=30554.0, self.low=30466.6, self.vol=1330.667, self.amt=40578404.4761 
127.0.0.1 - - [25/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-25 08:25:00,881:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230625   080000    080459  ...         0.0        0.0       0
5857  20230625   080500    080959  ...         0.0        0.0       0
5858  20230625   081000    081459  ...         0.0        0.0       0
5859  20230625   081500    081959  ...         0.0        0.0       0
5860  20230625   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 08:25:00,882:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687652699, self.tradeDate='20230625', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30544.1, self.close=30495.7, self.high=30554.0, self.low=30466.6, self.vol=1330.667, self.amt=40578404.4761, ukdf['pct'].iloc[-1]=-0.001588 , ukdf['amount'].iloc[-1]=40578404.4761, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50580.6246', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30497', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30579.5, self.close=30544.2, self.high=30579.6, self.low=30544.1 
127.0.0.1 - - [25/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 08:20:05,210:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30579.5, self.close=30544.2, self.high=30579.6, self.low=30544.1   
2023-06-25 08:20:06,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230625   075500    075959  1687651199  ...  30522.0 -0.000550   1535    5
1536  20230625   080000    080459  1687651499  ...  30524.1  0.000219   1536    0
1537  20230625   080500    080959  1687651799  ...  30497.5  0.000016   1537    1
1538  20230625   081000    081459  1687652099  ...  30524.1  0.001582   1538    2
1539  20230625   081500    081959  1687652399  ...  30544.1 -0.001158   1539    3

[5 rows x 11 columns]
2023-06-25 08:20:06,790:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=389, self.factor=0.5140120230005834, self.count=12067 

self.closeSec=1687652699, self.tradeDate='20230625', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30544.1, self.close=30495.7, self.high=30554.0, self.low=30466.6 
2023-06-25 08:25:00,801:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687652699, self.tradeDate='20230625', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30544.1, self.close=30495.7, self.high=30554.0, self.low=30466.6   
2023-06-25 08:25:00,861:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230625   080000    080459  1687651499  ...  30524.1  0.000219   1536    0
1537  20230625   080500    080959  1687651799  ...  30497.5  0.000016   1537    1
1538  20230625   081000    081459  1687652099  ...  30524.1  0.001582   1538    2
1539  20230625   081500    081959  1687652399  ...  30544.1 -0.001158   1539    3
1540  20230625   082000    082459  1687652699  ...  30466.6 -0.001588   1540    4

[5 rows x 11 columns]
2023-06-25 08:25:00,862:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-25 08:00:18,948:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5770  20230625    052959  30503.9  ...    53.75  0.515044  0.500155
5771  20230625    055959  30489.2  ...    53.75  0.516190  0.501288
5772  20230625    062959  30499.3  ...    53.75  0.518628  0.500418
5773  20230625    065959  30515.9  ...    53.75  0.517282  0.500582
5774  20230625    072959  30507.6  ...    53.75  0.523264  0.496116

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-06-25 08:00:19,080:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.480679  0.519321       1  ...  1.177549  -1.0    0.0  1.180829
537     1  0.479450  0.520550       1  ...  1.176908  -1.0    0.0  1.181472
538     1  0.486359  0.513641       0  ...  1.177232  -1.0    0.0  1.181147
539     1  0.481596  0.518404       1  ...  1.175696  -1.0    0.0  1.182688
540     1  0.497764  0.502236       0  ...  1.176593  -1.0    0.0  1.181785

[5 rows x 10 columns]
2023-06-25 08:00:19,105:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.480793  0.519207       1  ...  1.177549  -1.0    0.0  1.184397
46     1  0.479448  0.520552       1  ...  1.176908  -1.0    0.0  1.182419
47     1  0.486293  0.513707       0  ...  1.177232  -1.0    0.0  1.180137
48     1  0.481836  0.518164       1  ...  1.175696  -1.0    0.0  1.182688
49     1  0.497764  0.502236       0  ...  1.176593  -1.0    0.0  1.181785

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '11012.5125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30525.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230625   075000    075959  1687651199  30488.7  30524.2  0.001164
2023-06-25 08:00:02,090:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6032 

self.closeSec=1687651799, self.tradeDate='20230625', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30524.2', self.close='30531.3'
2023-06-25 08:10:01,196:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687651799, self.tradeDate='20230625', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30524.2', self.close='30531.3'
2023-06-25 08:10:01,217:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230625   072000    072959  1687649399  30529.9  30547.4  0.000573
621  20230625   073000    073959  1687649999  30547.4  30520.5 -0.000881
622  20230625   074000    074959  1687650599  30520.6  30488.7 -0.001042
623  20230625   075000    075959  1687651199  30488.7  30524.2  0.001164
624  20230625   080000    080959  1687651799  30524.2  30531.3  0.000233
2023-06-25 08:10:01,217:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6033 

self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30531.4', self.close='30544.2'
127.0.0.1 - - [25/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 08:20:07,650:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30531.4', self.close='30544.2'
2023-06-25 08:20:08,450:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230625   073000    073959  1687649999  30547.4  30520.5 -0.000881
622  20230625   074000    074959  1687650599  30520.6  30488.7 -0.001042
623  20230625   075000    075959  1687651199  30488.7  30524.2  0.001164
624  20230625   080000    080959  1687651799  30524.2  30531.3  0.000233
625  20230625   081000    081959  1687652399  30531.4  30544.2  0.000423
2023-06-25 08:20:08,450:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230625   075000    075959  1687651199  30488.7  30524.2
2023-06-25 08:00:02,109:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6035 

self.closeSec=1687651799, self.tradeDate='20230625', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30524.2', self.close='30531.3'
2023-06-25 08:10:01,202:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687651799, self.tradeDate='20230625', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30524.2', self.close='30531.3'
127.0.0.1 - - [25/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-25 08:10:01,215:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230625   072000    072959  1687649399  30529.9  30547.4
17469  20230625   073000    073959  1687649999  30547.4  30520.5
17470  20230625   074000    074959  1687650599  30520.6  30488.7
17471  20230625   075000    075959  1687651199  30488.7  30524.2
17472  20230625   080000    080959  1687651799  30524.2  30531.3
2023-06-25 08:10:01,215:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6036 

self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30531.4', self.close='30544.2'
127.0.0.1 - - [25/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-25 08:20:09,716:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30531.4', self.close='30544.2'
2023-06-25 08:20:09,857:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230625   073000    073959  1687649999  30547.4  30520.5
17470  20230625   074000    074959  1687650599  30520.6  30488.7
17471  20230625   075000    075959  1687651199  30488.7  30524.2
17472  20230625   080000    080959  1687651799  30524.2  30531.3
17473  20230625   081000    081959  1687652399  30531.4  30544.2
2023-06-25 08:20:09,857:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230625   075000    075959  1687651199  30488.7  30524.2
2023-06-25 08:00:02,053:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6035 

self.closeSec=1687651799, self.tradeDate='20230625', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30524.2', self.close='30531.3'
2023-06-25 08:10:01,184:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687651799, self.tradeDate='20230625', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30524.2', self.close='30531.3'
127.0.0.1 - - [25/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-25 08:10:01,207:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230625   072000    072959  1687649399  30529.9  30547.4
12141  20230625   073000    073959  1687649999  30547.4  30520.5
12142  20230625   074000    074959  1687650599  30520.6  30488.7
12143  20230625   075000    075959  1687651199  30488.7  30524.2
12144  20230625   080000    080959  1687651799  30524.2  30531.3
2023-06-25 08:10:01,208:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6036 

self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30531.4', self.close='30544.2'
127.0.0.1 - - [25/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-25 08:20:09,253:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30531.4', self.close='30544.2'
2023-06-25 08:20:09,571:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230625   073000    073959  1687649999  30547.4  30520.5
12142  20230625   074000    074959  1687650599  30520.6  30488.7
12143  20230625   075000    075959  1687651199  30488.7  30524.2
12144  20230625   080000    080959  1687651799  30524.2  30531.3
12145  20230625   081000    081959  1687652399  30531.4  30544.2
2023-06-25 08:20:09,579:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12064
self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30579.5, self.close=30544.2, self.high=30579.6, self.low=30544.1, self.vol=516.951, self.amt=15798609.2445 
127.0.0.1 - - [25/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-25 08:20:07,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230625   075500    075959  ...         0.0        0.0       0
5856  20230625   080000    080459  ...         0.0        0.0       0
5857  20230625   080500    080959  ...         0.0        0.0       0
5858  20230625   081000    081459  ...         0.0        0.0       0
5859  20230625   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 08:20:07,801:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687652399, self.tradeDate='20230625', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30579.5, self.close=30544.2, self.high=30579.6, self.low=30544.1, self.vol=516.951, self.amt=15798609.2445, ukdf['pct'].iloc[-1]=-0.001158 , ukdf['amount'].iloc[-1]=15798609.2445, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137373.4167', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30542.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12065
self.closeSec=1687652699, self.tradeDate='20230625', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30544.1, self.close=30495.7, self.high=30554.0, self.low=30466.6, self.vol=1330.667, self.amt=40578404.4761 
127.0.0.1 - - [25/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-25 08:25:00,879:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230625   080000    080459  ...         0.0        0.0       0
5857  20230625   080500    080959  ...         0.0        0.0       0
5858  20230625   081000    081459  ...         0.0        0.0       0
5859  20230625   081500    081959  ...         0.0        0.0       0
5860  20230625   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-25 08:25:00,880:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687652699, self.tradeDate='20230625', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30544.1, self.close=30495.7, self.high=30554.0, self.low=30466.6, self.vol=1330.667, self.amt=40578404.4761, ukdf['pct'].iloc[-1]=-0.001588 , ukdf['amount'].iloc[-1]=40578404.4761, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135676.073', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30497', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230624   200000    235959  1687622399  ...    719  0.734894  0.390758     NaN
720  20230625   000000    035959  1687636799  ...    720  0.615898  0.050613     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '140949.74020611232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30619.97917303', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=251
self.closeSec=1687651199, self.tradeDate='20230625', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30622.2, self.close=30524.2, self.high=30622.3, self.low=30395.0, self.vol=31333.988, self.amt=956135392.5132 
127.0.0.1 - - [25/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-25 08:00:01,637:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687651199, self.tradeDate='20230625', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30622.2, self.close=30524.2, self.high=30622.3, self.low=30395.0, self.vol=31333.988, self.amt=956135392.5132 
2023-06-25 08:00:01,662:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230624   120000    155959  ...  29137.580  8.935192e+08 -0.005081
718  20230624   160000    195959  ...  30744.164  9.420450e+08  0.003648
719  20230624   200000    235959  ...  72296.954  2.209368e+09 -0.009474
720  20230625   000000    035959  ...  58688.914  1.790778e+09  0.007833
721  20230625   040000    075959  ...  31333.988  9.561354e+08 -0.003204

[5 rows x 11 columns]
2023-06-25 08:00:03,043:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230624   120000    155959  1687593599  ...    717  0.910667  0.909653     1.0
718  20230624   160000    195959  1687607999  ...    718  0.831920  0.673413     1.0
719  20230624   200000    235959  1687622399  ...    719  0.734894  0.390758     NaN
720  20230625   000000    035959  1687636799  ...    720  0.615898  0.050613     NaN
721  20230625   040000    075959  1687651199  ...    721  0.620402  0.062441     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '135894.01488243616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30525.20327839', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


