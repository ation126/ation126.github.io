# 20230813 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26176
self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29419.5, self.close=29420.3, self.high=29420.3, self.low=29419.5, self.vol=44.464, self.amt=1308124.2503 
127.0.0.1 - - [13/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 08:20:07,297:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230813   075500    075959  ...         0.0        0.0       0
5856  20230813   080000    080459  ...         0.0        0.0       0
5857  20230813   080500    080959  ...         0.0        0.0       0
5858  20230813   081000    081459  ...         0.0        0.0       0
5859  20230813   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 08:20:07,327:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29419.5, self.close=29420.3, self.high=29420.3, self.low=29419.5, self.vol=44.464, self.amt=1308124.2503, ukdf['pct'].iloc[-1]=2.4e-05 , ukdf['amount'].iloc[-1]=1308124.2503, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35585.1078', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29420.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26177
self.closeSec=1691886299, self.tradeDate='20230813', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29420.3, self.close=29419.6, self.high=29420.3, self.low=29419.5, self.vol=85.051, self.amt=2502209.5406 
127.0.0.1 - - [13/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-13 08:25:00,784:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230813   080000    080459  ...         0.0        0.0       0
5857  20230813   080500    080959  ...         0.0        0.0       0
5858  20230813   081000    081459  ...         0.0        0.0       0
5859  20230813   081500    081959  ...         0.0        0.0       0
5860  20230813   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 08:25:00,784:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691886299, self.tradeDate='20230813', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29420.3, self.close=29419.6, self.high=29420.3, self.low=29419.5, self.vol=85.051, self.amt=2502209.5406, ukdf['pct'].iloc[-1]=-2.4e-05 , ukdf['amount'].iloc[-1]=2502209.5406, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35581.27034684442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29419.92443967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29419.5, self.close=29420.3, self.high=29420.3, self.low=29419.5 
127.0.0.1 - - [13/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 08:20:05,057:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29419.5, self.close=29420.3, self.high=29420.3, self.low=29419.5   
2023-08-13 08:20:06,287:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230813   075500    075959  1691884799  ...  29418.2  0.000088   1535    5
1536  20230813   080000    080459  1691885099  ...  29420.7 -0.000003   1536    0
1537  20230813   080500    080959  1691885399  ...  29412.7 -0.000272   1537    1
1538  20230813   081000    081459  1691885699  ...  29412.7  0.000235   1538    2
1539  20230813   081500    081959  1691885999  ...  29419.5  0.000024   1539    3

[5 rows x 11 columns]
2023-08-13 08:20:06,298:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.5270369654298972, self.count=26179 

self.closeSec=1691886299, self.tradeDate='20230813', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29420.3, self.close=29419.6, self.high=29420.3, self.low=29419.5 
2023-08-13 08:25:00,751:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691886299, self.tradeDate='20230813', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29420.3, self.close=29419.6, self.high=29420.3, self.low=29419.5   
2023-08-13 08:25:00,774:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230813   080000    080459  1691885099  ...  29420.7 -0.000003   1536    0
1537  20230813   080500    080959  1691885399  ...  29412.7 -0.000272   1537    1
1538  20230813   081000    081459  1691885699  ...  29412.7  0.000235   1538    2
1539  20230813   081500    081959  1691885999  ...  29419.5  0.000024   1539    3
1540  20230813   082000    082459  1691886299  ...  29419.5 -0.000024   1540    4

[5 rows x 11 columns]
2023-08-13 08:25:00,774:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-13 08:00:18,899:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230813    052959  29409.5  ...  49.166667  0.487254  0.398708
5771  20230813    055959  29406.4  ...  49.583333  0.490273  0.407522
5772  20230813    062959  29411.5  ...  50.000000  0.492961  0.413020
5773  20230813    065959  29416.1  ...  50.000000  0.494712  0.416395
5774  20230813    072959  29419.0  ...  50.000000  0.496975  0.417302

[5 rows x 33 columns]
0.5231053604436229
acc is : 0.5231053604436229
2023-08-13 08:00:18,972:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.502547  0.497453       1  ...  0.993519  -1.0    0.0  1.015839
537     0  0.506221  0.493779       1  ...  0.993366  -1.0    0.0  1.015995
538     0  0.506223  0.493777       1  ...  0.993269  -1.0    0.0  1.016095
539     0  0.506733  0.493267       1  ...  0.993144  -1.0    0.0  1.016223
540     0  0.506456  0.493544       0  ...  0.993208  -1.0    0.0  1.016157

[5 rows x 10 columns]
2023-08-13 08:00:18,986:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502468  0.497532       1  ...  0.993519  -1.0    0.0  1.016176
46     0  0.506272  0.493728       1  ...  0.993366  -1.0    0.0  1.016841
47     0  0.506375  0.493625       1  ...  0.993269  -1.0    0.0  1.017177
48     0  0.506733  0.493267       1  ...  0.993144  -1.0    0.0  1.016223
49     0  0.506456  0.493544       0  ...  0.993208  -1.0    0.0  1.016157

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '1416.4861', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29420.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230813   075000    075959  1691884799  29418.3  29420.7  0.000082
2023-08-13 08:00:02,035:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13088 

self.closeSec=1691885399, self.tradeDate='20230813', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29420.8', self.close='29412.7'
2023-08-13 08:10:01,123:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691885399, self.tradeDate='20230813', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29420.8', self.close='29412.7'
2023-08-13 08:10:01,129:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230813   072000    072959  1691882999  29421.4  29422.6  0.000037
621  20230813   073000    073959  1691883599  29422.6  29418.3 -0.000146
622  20230813   074000    074959  1691884199  29418.4  29418.3  0.000000
623  20230813   075000    075959  1691884799  29418.3  29420.7  0.000082
624  20230813   080000    080959  1691885399  29420.8  29412.7 -0.000272
2023-08-13 08:10:01,129:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13089 

self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29412.8', self.close='29420.3'
127.0.0.1 - - [13/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 08:20:07,318:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29412.8', self.close='29420.3'
2023-08-13 08:20:07,897:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230813   073000    073959  1691883599  29422.6  29418.3 -0.000146
622  20230813   074000    074959  1691884199  29418.4  29418.3  0.000000
623  20230813   075000    075959  1691884799  29418.3  29420.7  0.000082
624  20230813   080000    080959  1691885399  29420.8  29412.7 -0.000272
625  20230813   081000    081959  1691885999  29412.8  29420.3  0.000258
2023-08-13 08:20:07,898:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230813   075000    075959  1691884799  29418.3  29420.7
2023-08-13 08:00:02,055:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [13/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13091 

self.closeSec=1691885399, self.tradeDate='20230813', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29420.8', self.close='29412.7'
2023-08-13 08:10:01,109:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691885399, self.tradeDate='20230813', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29420.8', self.close='29412.7'
2023-08-13 08:10:01,114:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230813   072000    072959  1691882999  29421.4  29422.6
17469  20230813   073000    073959  1691883599  29422.6  29418.3
17470  20230813   074000    074959  1691884199  29418.4  29418.3
17471  20230813   075000    075959  1691884799  29418.3  29420.7
17472  20230813   080000    080959  1691885399  29420.8  29412.7
2023-08-13 08:10:01,114:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13092 

self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29412.8', self.close='29420.3'
127.0.0.1 - - [13/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 08:20:09,100:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29412.8', self.close='29420.3'
2023-08-13 08:20:09,191:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230813   073000    073959  1691883599  29422.6  29418.3
17470  20230813   074000    074959  1691884199  29418.4  29418.3
17471  20230813   075000    075959  1691884799  29418.3  29420.7
17472  20230813   080000    080959  1691885399  29420.8  29412.7
17473  20230813   081000    081959  1691885999  29412.8  29420.3
2023-08-13 08:20:09,191:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230813   075000    075959  1691884799  29418.3  29420.7
2023-08-13 08:00:02,045:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13091 

self.closeSec=1691885399, self.tradeDate='20230813', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29420.8', self.close='29412.7'
2023-08-13 08:10:01,121:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691885399, self.tradeDate='20230813', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29420.8', self.close='29412.7'
127.0.0.1 - - [13/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-13 08:10:01,127:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230813   072000    072959  1691882999  29421.4  29422.6
12141  20230813   073000    073959  1691883599  29422.6  29418.3
12142  20230813   074000    074959  1691884199  29418.4  29418.3
12143  20230813   075000    075959  1691884799  29418.3  29420.7
12144  20230813   080000    080959  1691885399  29420.8  29412.7
2023-08-13 08:10:01,128:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13092 

self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29412.8', self.close='29420.3'
127.0.0.1 - - [13/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-13 08:20:08,860:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29412.8', self.close='29420.3'
2023-08-13 08:20:09,081:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230813   073000    073959  1691883599  29422.6  29418.3
12142  20230813   074000    074959  1691884199  29418.4  29418.3
12143  20230813   075000    075959  1691884799  29418.3  29420.7
12144  20230813   080000    080959  1691885399  29420.8  29412.7
12145  20230813   081000    081959  1691885999  29412.8  29420.3
2023-08-13 08:20:09,086:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26176
self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29419.5, self.close=29420.3, self.high=29420.3, self.low=29419.5, self.vol=44.464, self.amt=1308124.2503 
127.0.0.1 - - [13/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-13 08:20:07,207:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230813   075500    075959  ...         0.0        0.0       0
5856  20230813   080000    080459  ...         0.0        0.0       0
5857  20230813   080500    080959  ...         0.0        0.0       0
5858  20230813   081000    081459  ...         0.0        0.0       0
5859  20230813   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 08:20:07,238:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691885999, self.tradeDate='20230813', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29419.5, self.close=29420.3, self.high=29420.3, self.low=29419.5, self.vol=44.464, self.amt=1308124.2503, ukdf['pct'].iloc[-1]=2.4e-05 , ukdf['amount'].iloc[-1]=1308124.2503, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95682.6442', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29420.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [13/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26177
self.closeSec=1691886299, self.tradeDate='20230813', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29420.3, self.close=29419.6, self.high=29420.3, self.low=29419.5, self.vol=85.051, self.amt=2502209.5406 
2023-08-13 08:25:00,772:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230813   080000    080459  ...         0.0        0.0       0
5857  20230813   080500    080959  ...         0.0        0.0       0
5858  20230813   081000    081459  ...         0.0        0.0       0
5859  20230813   081500    081959  ...         0.0        0.0       0
5860  20230813   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-13 08:25:00,772:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691886299, self.tradeDate='20230813', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29420.3, self.close=29419.6, self.high=29420.3, self.low=29419.5, self.vol=85.051, self.amt=2502209.5406, ukdf['pct'].iloc[-1]=-2.4e-05 , ukdf['amount'].iloc[-1]=2502209.5406, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95672.40961378347', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29419.92443967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230812   200000    235959  1691855999  ...    719  1.313265  2.176949     1.0
720  20230813   000000    035959  1691870399  ...    720  1.461579  2.449267     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24596.15984299187', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29406.40556109', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [13/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=545
self.closeSec=1691884799, self.tradeDate='20230813', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29407.6, self.close=29420.7, self.high=29422.7, self.low=29385.1, self.vol=5810.372, self.amt=170885274.4016 
2023-08-13 08:00:01,620:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691884799, self.tradeDate='20230813', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29407.6, self.close=29420.7, self.high=29422.7, self.low=29385.1, self.vol=5810.372, self.amt=170885274.4016 
2023-08-13 08:00:01,638:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230812   120000    155959  ...   7457.781  2.192525e+08  0.000755
718  20230812   160000    195959  ...   9821.475  2.888007e+08  0.000221
719  20230812   200000    235959  ...  10838.163  3.188723e+08  0.000316
720  20230813   000000    035959  ...  10798.789  3.178413e+08 -0.000629
721  20230813   040000    075959  ...   5810.372  1.708853e+08  0.000449

[5 rows x 11 columns]
2023-08-13 08:00:02,393:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230812   120000    155959  1691827199  ...    717  1.113365  1.792293     1.0
718  20230812   160000    195959  1691841599  ...    718  1.103626  1.717364     1.0
719  20230812   200000    235959  1691855999  ...    719  1.313265  2.176949     1.0
720  20230813   000000    035959  1691870399  ...    720  1.461579  2.449267     1.0
721  20230813   040000    075959  1691884799  ...    721  1.431491  2.280324     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-23860.6109', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29420.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


