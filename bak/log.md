# 20230611 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8032
self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25788.1, self.close=25772.0, self.high=25790.0, self.low=25755.1, self.vol=794.157, self.amt=20462890.5926 
127.0.0.1 - - [11/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:20:04,653:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230611   075500    075959  ...         0.0        0.0       0
5856  20230611   080000    080459  ...         0.0        0.0       0
5857  20230611   080500    080959  ...         0.0        0.0       0
5858  20230611   081000    081459  ...         0.0        0.0       0
5859  20230611   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 08:20:04,665:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25788.1, self.close=25772.0, self.high=25790.0, self.low=25755.1, self.vol=794.157, self.amt=20462890.5926, ukdf['pct'].iloc[-1]=-0.000702 , ukdf['amount'].iloc[-1]=20462890.5926, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15145.9176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25777.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8033
self.closeSec=1686443099, self.tradeDate='20230611', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25771.9, self.close=25789.7, self.high=25793.3, self.low=25771.9, self.vol=380.291, self.amt=9805737.6368 
127.0.0.1 - - [11/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:25:04,409:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230611   080000    080459  ...         0.0        0.0       0
5857  20230611   080500    080959  ...         0.0        0.0       0
5858  20230611   081000    081459  ...         0.0        0.0       0
5859  20230611   081500    081959  ...         0.0        0.0       0
5860  20230611   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 08:25:04,419:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686443099, self.tradeDate='20230611', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25771.9, self.close=25789.7, self.high=25793.3, self.low=25771.9, self.vol=380.291, self.amt=9805737.6368, ukdf['pct'].iloc[-1]=0.000687 , ukdf['amount'].iloc[-1]=9805737.6368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14901.37086883236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25794.86044314', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25788.1, self.close=25772.0, self.high=25790.0, self.low=25755.1 
127.0.0.1 - - [11/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:20:03,894:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25788.1, self.close=25772.0, self.high=25790.0, self.low=25755.1   
2023-06-11 08:20:04,475:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230611   075500    075959  1686441599  ...  25821.0 -0.000159   1535    5
1536  20230611   080000    080459  1686441899  ...  25803.1 -0.000848   1536    0
1537  20230611   080500    080959  1686442199  ...  25781.5 -0.000333   1537    1
1538  20230611   081000    081459  1686442499  ...  25761.2 -0.000236   1538    2
1539  20230611   081500    081959  1686442799  ...  25755.1 -0.000702   1539    3

[5 rows x 11 columns]
2023-06-11 08:20:04,484:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6961622840513849, self.count=8035 

self.closeSec=1686443099, self.tradeDate='20230611', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25771.9, self.close=25789.7, self.high=25793.3, self.low=25771.9 
127.0.0.1 - - [11/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:25:03,318:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686443099, self.tradeDate='20230611', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25771.9, self.close=25789.7, self.high=25793.3, self.low=25771.9   
2023-06-11 08:25:04,020:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230611   080000    080459  1686441899  ...  25803.1 -0.000848   1536    0
1537  20230611   080500    080959  1686442199  ...  25781.5 -0.000333   1537    1
1538  20230611   081000    081459  1686442499  ...  25761.2 -0.000236   1538    2
1539  20230611   081500    081959  1686442799  ...  25755.1 -0.000702   1539    3
1540  20230611   082000    082459  1686443099  ...  25771.9  0.000687   1540    4

[5 rows x 11 columns]
2023-06-11 08:25:04,028:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-11 08:00:36,061:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230611    052959  25740.8  ...  50.833333  0.439723  0.743041
5771  20230611    055959  25708.8  ...  50.833333  0.447525  0.733485
5772  20230611    062959  25751.1  ...  50.833333  0.458084  0.720788
5773  20230611    065959  25810.2  ...  50.833333  0.467765  0.703951
5774  20230611    072959  25863.2  ...  50.416667  0.465070  0.689319

[5 rows x 33 columns]
0.5138632162661737
acc is : 0.5138632162661737
2023-06-11 08:00:36,200:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.515183  0.484817       1  ...  0.986867  -1.0    0.0  0.931270
537     0  0.525737  0.474263       1  ...  0.984644  -1.0    0.0  0.933367
538     0  0.522566  0.477434       1  ...  0.982580  -1.0    0.0  0.935324
539     0  0.528212  0.471788       0  ...  0.983234  -1.0    0.0  0.934702
540     0  0.512001  0.487999       0  ...  0.983972  -1.0    0.0  0.934000

[5 rows x 10 columns]
2023-06-11 08:00:36,227:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515206  0.484794       1  ...  0.986867  -1.0    0.0  0.930822
46     0  0.525643  0.474357       1  ...  0.984644  -1.0    0.0  0.932625
47     0  0.522347  0.477653       1  ...  0.982580  -1.0    0.0  0.933797
48     0  0.528260  0.471740       0  ...  0.988360  -1.0    0.0  0.934702
49     0  0.512001  0.487999       0  ...  0.983972  -1.0    0.0  0.934000

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-7573.17767333712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25826.85951944', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230611   075000    075959  1686441599  25835.4  25826.6 -0.000341
2023-06-11 08:00:02,288:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4016 

self.closeSec=1686442199, self.tradeDate='20230611', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25826.6', self.close='25796.3'
2023-06-11 08:10:01,110:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686442199, self.tradeDate='20230611', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25826.6', self.close='25796.3'
127.0.0.1 - - [11/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:10:01,165:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230611   072000    072959  1686439799  25858.8    25846 -0.000491
621  20230611   073000    073959  1686440399  25845.9  25824.5 -0.000832
622  20230611   074000    074959  1686440999  25824.4  25835.4  0.000422
623  20230611   075000    075959  1686441599  25835.4  25826.6 -0.000341
624  20230611   080000    080959  1686442199  25826.6  25796.3 -0.001173
2023-06-11 08:10:01,175:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4017 

self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25796.3', self.close='25772'
127.0.0.1 - - [11/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-11 08:20:05,355:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25796.3', self.close='25772'
2023-06-11 08:20:05,904:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230611   073000    073959  1686440399  25845.9  25824.5 -0.000832
622  20230611   074000    074959  1686440999  25824.4  25835.4  0.000422
623  20230611   075000    075959  1686441599  25835.4  25826.6 -0.000341
624  20230611   080000    080959  1686442199  25826.6  25796.3 -0.001173
625  20230611   081000    081959  1686442799  25796.3    25772 -0.000942
2023-06-11 08:20:05,905:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230611   075000    075959  1686441599  25835.4  25826.6
2023-06-11 08:00:02,319:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4019 

self.closeSec=1686442199, self.tradeDate='20230611', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25826.6', self.close='25796.3'
2023-06-11 08:10:01,141:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686442199, self.tradeDate='20230611', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25826.6', self.close='25796.3'
2023-06-11 08:10:01,177:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230611   072000    072959  1686439799  25858.8    25846
17469  20230611   073000    073959  1686440399  25845.9  25824.5
17470  20230611   074000    074959  1686440999  25824.4  25835.4
17471  20230611   075000    075959  1686441599  25835.4  25826.6
17472  20230611   080000    080959  1686442199  25826.6  25796.3
2023-06-11 08:10:01,180:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4020 

self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25796.3', self.close='25772'
127.0.0.1 - - [11/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-11 08:20:06,827:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25796.3', self.close='25772'
2023-06-11 08:20:06,962:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230611   073000    073959  1686440399  25845.9  25824.5
17470  20230611   074000    074959  1686440999  25824.4  25835.4
17471  20230611   075000    075959  1686441599  25835.4  25826.6
17472  20230611   080000    080959  1686442199  25826.6  25796.3
17473  20230611   081000    081959  1686442799  25796.3    25772
2023-06-11 08:20:06,963:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230611   075000    075959  1686441599  25835.4  25826.6
2023-06-11 08:00:02,320:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4019 

self.closeSec=1686442199, self.tradeDate='20230611', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25826.6', self.close='25796.3'
2023-06-11 08:10:01,131:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686442199, self.tradeDate='20230611', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25826.6', self.close='25796.3'
2023-06-11 08:10:01,172:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230611   072000    072959  1686439799  25858.8    25846
12141  20230611   073000    073959  1686440399  25845.9  25824.5
12142  20230611   074000    074959  1686440999  25824.4  25835.4
12143  20230611   075000    075959  1686441599  25835.4  25826.6
12144  20230611   080000    080959  1686442199  25826.6  25796.3
2023-06-11 08:10:01,172:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4020 

self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25796.3', self.close='25772'
127.0.0.1 - - [11/Jun/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-06-11 08:20:06,536:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25796.3', self.close='25772'
2023-06-11 08:20:06,806:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230611   073000    073959  1686440399  25845.9  25824.5
12142  20230611   074000    074959  1686440999  25824.4  25835.4
12143  20230611   075000    075959  1686441599  25835.4  25826.6
12144  20230611   080000    080959  1686442199  25826.6  25796.3
12145  20230611   081000    081959  1686442799  25796.3    25772
2023-06-11 08:20:06,806:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8032
self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25788.1, self.close=25772.0, self.high=25790.0, self.low=25755.1, self.vol=794.157, self.amt=20462890.5926 
127.0.0.1 - - [11/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:20:04,965:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230611   075500    075959  ...         0.0        0.0       0
5856  20230611   080000    080459  ...         0.0        0.0       0
5857  20230611   080500    080959  ...         0.0        0.0       0
5858  20230611   081000    081459  ...         0.0        0.0       0
5859  20230611   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 08:20:04,974:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686442799, self.tradeDate='20230611', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25788.1, self.close=25772.0, self.high=25790.0, self.low=25755.1, self.vol=794.157, self.amt=20462890.5926, ukdf['pct'].iloc[-1]=-0.000702 , ukdf['amount'].iloc[-1]=20462890.5926, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-39618.3047', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25777.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8033
self.closeSec=1686443099, self.tradeDate='20230611', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25771.9, self.close=25789.7, self.high=25793.3, self.low=25771.9, self.vol=380.291, self.amt=9805737.6368 
127.0.0.1 - - [11/Jun/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:25:04,433:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230611   080000    080459  ...         0.0        0.0       0
5857  20230611   080500    080959  ...         0.0        0.0       0
5858  20230611   081000    081459  ...         0.0        0.0       0
5859  20230611   081500    081959  ...         0.0        0.0       0
5860  20230611   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 08:25:04,436:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686443099, self.tradeDate='20230611', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25771.9, self.close=25789.7, self.high=25793.3, self.low=25771.9, self.vol=380.291, self.amt=9805737.6368, ukdf['pct'].iloc[-1]=0.000687 , ukdf['amount'].iloc[-1]=9805737.6368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38966.09228133726', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25794.86044314', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230610   200000    235959  1686412799  ...    719  0.358009 -0.793134    -1.0
720  20230611   000000    035959  1686427199  ...    720  0.349759 -0.808214    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '73883.8238', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25739.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=167
self.closeSec=1686441599, self.tradeDate='20230611', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25738.2, self.close=25826.6, self.high=25919.5, self.low=25666.7, self.vol=46686.517, self.amt=1203925590.53273 
127.0.0.1 - - [11/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-11 08:00:01,860:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686441599, self.tradeDate='20230611', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25738.2, self.close=25826.6, self.high=25919.5, self.low=25666.7, self.vol=46686.517, self.amt=1203925590.53273 
2023-06-11 08:00:01,892:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230610   120000    155959  ...  239102.737  6.149956e+09 -0.025668
718  20230610   160000    195959  ...   45062.365  1.155978e+09  0.003175
719  20230610   200000    235959  ...   36077.085  9.248559e+08 -0.003838
720  20230611   000000    035959  ...  188175.676  4.844864e+09  0.004614
721  20230611   040000    075959  ...   46686.517  1.203926e+09  0.003435

[5 rows x 11 columns]
2023-06-11 08:00:04,626:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230610   120000    155959  1686383999  ...    717  0.324140 -0.931206    -1.0
718  20230610   160000    195959  1686398399  ...    718  0.343188 -0.854035    -1.0
719  20230610   200000    235959  1686412799  ...    719  0.358009 -0.793134    -1.0
720  20230611   000000    035959  1686427199  ...    720  0.349759 -0.808214    -1.0
721  20230611   040000    075959  1686441599  ...    721  0.517683 -0.254692     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '68977.11529904258', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25828.24443137', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


