# 20230530 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4576
self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27720.0, self.close=27726.4, self.high=27739.7, self.low=27719.9, self.vol=471.569, self.amt=13077947.9395 
127.0.0.1 - - [30/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 08:20:07,448:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230530   075500    075959  ...         0.0        0.0       0
5856  20230530   080000    080459  ...         0.0        0.0       0
5857  20230530   080500    080959  ...         0.0        0.0       0
5858  20230530   081000    081459  ...         0.0        0.0       0
5859  20230530   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 08:20:07,478:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27720.0, self.close=27726.4, self.high=27739.7, self.low=27719.9, self.vol=471.569, self.amt=13077947.9395, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=13077947.9395, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11995.9580598', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27726.3073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4577
self.closeSec=1685406299, self.tradeDate='20230530', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27726.4, self.close=27712.5, self.high=27726.4, self.low=27703.1, self.vol=497.629, self.amt=13791121.489 
127.0.0.1 - - [30/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-30 08:25:00,827:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230530   080000    080459  ...         0.0        0.0       0
5857  20230530   080500    080959  ...         0.0        0.0       0
5858  20230530   081000    081459  ...         0.0        0.0       0
5859  20230530   081500    081959  ...         0.0        0.0       0
5860  20230530   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 08:25:00,827:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685406299, self.tradeDate='20230530', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27726.4, self.close=27712.5, self.high=27726.4, self.low=27703.1, self.vol=497.629, self.amt=13791121.489, ukdf['pct'].iloc[-1]=-0.000501 , ukdf['amount'].iloc[-1]=13791121.489, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-11802.285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27712.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27720.0, self.close=27726.4, self.high=27739.7, self.low=27719.9 
127.0.0.1 - - [30/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 08:20:04,688:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27720.0, self.close=27726.4, self.high=27739.7, self.low=27719.9   
2023-05-30 08:20:06,308:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230530   075500    075959  1685404799  ...  27717.0 -0.000325   1535    5
1536  20230530   080000    080459  1685405099  ...  27717.0  0.000509   1536    0
1537  20230530   080500    080959  1685405399  ...  27725.1  0.000808   1537    1
1538  20230530   081000    081459  1685405699  ...  27700.0 -0.001391   1538    2
1539  20230530   081500    081959  1685405999  ...  27719.9  0.000234   1539    3

[5 rows x 11 columns]
2023-05-30 08:20:06,318:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=163, self.factor=0.4754931029024177, self.count=4579 

self.closeSec=1685406299, self.tradeDate='20230530', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27726.4, self.close=27712.5, self.high=27726.4, self.low=27703.1 
127.0.0.1 - - [30/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-30 08:25:00,761:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685406299, self.tradeDate='20230530', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27726.4, self.close=27712.5, self.high=27726.4, self.low=27703.1   
2023-05-30 08:25:00,808:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230530   080000    080459  1685405099  ...  27717.0  0.000509   1536    0
1537  20230530   080500    080959  1685405399  ...  27725.1  0.000808   1537    1
1538  20230530   081000    081459  1685405699  ...  27700.0 -0.001391   1538    2
1539  20230530   081500    081959  1685405999  ...  27719.9  0.000234   1539    3
1540  20230530   082000    082459  1685406299  ...  27703.1 -0.000501   1540    4

[5 rows x 11 columns]
2023-05-30 08:25:00,808:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-30 08:00:31,741:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230530    052959  27670.1  ...  50.000000  0.529456  0.665112
5771  20230530    055959  27650.0  ...  50.416667  0.530191  0.673229
5772  20230530    062959  27653.5  ...  50.416667  0.510150  0.688947
5773  20230530    065959  27572.1  ...  50.416667  0.533731  0.691776
5774  20230530    072959  27678.7  ...  50.833333  0.549288  0.685291

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2023-05-30 08:00:31,892:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.496934  0.503066       1  ...  0.980559  -1.0    0.0  1.023283
537     1  0.497992  0.502008       0  ...  0.983441  -1.0    0.0  1.020274
538     1  0.479585  0.520415       1  ...  0.979639  -1.0    0.0  1.024219
539     0  0.518240  0.481760       1  ...  0.976988  -1.0    0.0  1.026991
540     0  0.515490  0.484510       0  ...  0.978101  -1.0    0.0  1.025821

[5 rows x 10 columns]
2023-05-30 08:00:31,928:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496857  0.503143       1  ...  0.980559  -1.0    0.0  1.021355
46     1  0.498139  0.501861       0  ...  0.983441  -1.0    0.0  1.020403
47     1  0.479388  0.520612       1  ...  0.979639  -1.0    0.0  1.022860
48     0  0.518348  0.481652       1  ...  0.976988  -1.0    0.0  1.026991
49     0  0.515490  0.484510       0  ...  0.978101  -1.0    0.0  1.025821

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.849', 'enterprice': '27935.3', 'countrevence': '0', 'unrealprofit': '5389.5165', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27726.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230530   075000    075959  1685404799  27747.3    27722 -0.000912
2023-05-30 08:00:02,053:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2288 

self.closeSec=1685405399, self.tradeDate='20230530', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27722.1', self.close='27758.5'
2023-05-30 08:10:01,121:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685405399, self.tradeDate='20230530', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27722.1', self.close='27758.5'
2023-05-30 08:10:01,133:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230530   072000    072959  1685402999  27740.6  27753.6  0.000508
621  20230530   073000    073959  1685403599  27753.5  27752.4 -0.000043
622  20230530   074000    074959  1685404199  27752.4  27747.3 -0.000184
623  20230530   075000    075959  1685404799  27747.3    27722 -0.000912
624  20230530   080000    080959  1685405399  27722.1  27758.5  0.001317
2023-05-30 08:10:01,133:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2289 

self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27758.5', self.close='27726.3'
127.0.0.1 - - [30/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 08:20:07,469:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27758.5', self.close='27726.3'
2023-05-30 08:20:08,208:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230530   073000    073959  1685403599  27753.5  27752.4 -0.000043
622  20230530   074000    074959  1685404199  27752.4  27747.3 -0.000184
623  20230530   075000    075959  1685404799  27747.3    27722 -0.000912
624  20230530   080000    080959  1685405399  27722.1  27758.5  0.001317
625  20230530   081000    081959  1685405999  27758.5  27726.3 -0.001160
2023-05-30 08:20:08,217:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230530   075000    075959  1685404799  27747.3    27722
2023-05-30 08:00:02,043:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [30/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2291 

self.closeSec=1685405399, self.tradeDate='20230530', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27722.1', self.close='27758.5'
2023-05-30 08:10:01,150:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685405399, self.tradeDate='20230530', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27722.1', self.close='27758.5'
2023-05-30 08:10:01,190:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230530   072000    072959  1685402999  27740.6  27753.6
17469  20230530   073000    073959  1685403599  27753.5  27752.4
17470  20230530   074000    074959  1685404199  27752.4  27747.3
17471  20230530   075000    075959  1685404799  27747.3    27722
17472  20230530   080000    080959  1685405399  27722.1  27758.5
2023-05-30 08:10:01,190:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2292 

self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27758.5', self.close='27726.3'
127.0.0.1 - - [30/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 08:20:09,160:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27758.5', self.close='27726.3'
2023-05-30 08:20:09,280:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230530   073000    073959  1685403599  27753.5  27752.4
17470  20230530   074000    074959  1685404199  27752.4  27747.3
17471  20230530   075000    075959  1685404799  27747.3    27722
17472  20230530   080000    080959  1685405399  27722.1  27758.5
17473  20230530   081000    081959  1685405999  27758.5  27726.3
2023-05-30 08:20:09,281:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230530   075000    075959  1685404799  27747.3    27722
2023-05-30 08:00:02,033:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2291 

self.closeSec=1685405399, self.tradeDate='20230530', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27722.1', self.close='27758.5'
2023-05-30 08:10:01,129:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685405399, self.tradeDate='20230530', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27722.1', self.close='27758.5'
2023-05-30 08:10:01,180:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230530   072000    072959  1685402999  27740.6  27753.6
12141  20230530   073000    073959  1685403599  27753.5  27752.4
12142  20230530   074000    074959  1685404199  27752.4  27747.3
12143  20230530   075000    075959  1685404799  27747.3    27722
12144  20230530   080000    080959  1685405399  27722.1  27758.5
2023-05-30 08:10:01,180:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2292 

self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27758.5', self.close='27726.3'
127.0.0.1 - - [30/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-30 08:20:08,848:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27758.5', self.close='27726.3'
2023-05-30 08:20:09,069:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230530   073000    073959  1685403599  27753.5  27752.4
12142  20230530   074000    074959  1685404199  27752.4  27747.3
12143  20230530   075000    075959  1685404799  27747.3    27722
12144  20230530   080000    080959  1685405399  27722.1  27758.5
12145  20230530   081000    081959  1685405999  27758.5  27726.3
2023-05-30 08:20:09,077:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4576
self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27720.0, self.close=27726.4, self.high=27739.7, self.low=27719.9, self.vol=471.569, self.amt=13077947.9395 
127.0.0.1 - - [30/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-30 08:20:07,638:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230530   075500    075959  ...         0.0        0.0       0
5856  20230530   080000    080459  ...         0.0        0.0       0
5857  20230530   080500    080959  ...         0.0        0.0       0
5858  20230530   081000    081459  ...         0.0        0.0       0
5859  20230530   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 08:20:07,657:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685405999, self.tradeDate='20230530', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27720.0, self.close=27726.4, self.high=27739.7, self.low=27719.9, self.vol=471.569, self.amt=13077947.9395, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=13077947.9395, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '32769.7754293', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27726.3073', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4577
self.closeSec=1685406299, self.tradeDate='20230530', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27726.4, self.close=27712.5, self.high=27726.4, self.low=27703.1, self.vol=497.629, self.amt=13791121.489 
2023-05-30 08:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230530   080000    080459  ...         0.0        0.0       0
5857  20230530   080500    080959  ...         0.0        0.0       0
5858  20230530   081000    081459  ...         0.0        0.0       0
5859  20230530   081500    081959  ...         0.0        0.0       0
5860  20230530   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-30 08:25:00,824:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685406299, self.tradeDate='20230530', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27726.4, self.close=27712.5, self.high=27726.4, self.low=27703.1, self.vol=497.629, self.amt=13791121.489, ukdf['pct'].iloc[-1]=-0.000501 , ukdf['amount'].iloc[-1]=13791121.489, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '32253.2444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27712.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230529   200000    235959  1685375999  ...    719  1.106273  2.811384     1.0
720  20230530   000000    035959  1685390399  ...    720  1.107363  2.667881     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '82479.09171285574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27621.06125926', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [30/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=95
self.closeSec=1685404799, self.tradeDate='20230530', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27624.1, self.close=27722.0, self.high=27803.5, self.low=27533.8, self.vol=41577.115, self.amt=1150710268.63622 
2023-05-30 08:00:01,694:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685404799, self.tradeDate='20230530', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27624.1, self.close=27722.0, self.high=27803.5, self.low=27533.8, self.vol=41577.115, self.amt=1150710268.63622 
2023-05-30 08:00:01,727:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230529   120000    155959  ...  60707.279  1.695958e+09 -0.001893
718  20230529   160000    195959  ...  48976.302  1.365145e+09  0.000470
719  20230529   200000    235959  ...  81223.202  2.254190e+09 -0.010252
720  20230530   000000    035959  ...  75215.644  2.077855e+09  0.000072
721  20230530   040000    075959  ...  41577.115  1.150710e+09  0.003548

[5 rows x 11 columns]
2023-05-30 08:00:03,674:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230529   120000    155959  1685347199  ...    717  1.148239  3.355206     1.0
718  20230529   160000    195959  1685361599  ...    718  1.095699  2.928957     1.0
719  20230529   200000    235959  1685375999  ...    719  1.106273  2.811384     1.0
720  20230530   000000    035959  1685390399  ...    720  1.107363  2.667881     1.0
721  20230530   040000    075959  1685404799  ...    721  1.159886  2.726214     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '88078.51442871639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27722.41011111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


