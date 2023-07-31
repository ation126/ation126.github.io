# 20230731 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22432
self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29253.9, self.close=29270.0, self.high=29270.1, self.low=29250.0, self.vol=457.335, self.amt=13379679.9508 
127.0.0.1 - - [31/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 08:20:05,036:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230731   075500    075959  ...         0.0        0.0       0
5856  20230731   080000    080459  ...         0.0        0.0       0
5857  20230731   080500    080959  ...         0.0        0.0       0
5858  20230731   081000    081459  ...         0.0        0.0       0
5859  20230731   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 08:20:05,047:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29253.9, self.close=29270.0, self.high=29270.1, self.low=29250.0, self.vol=457.335, self.amt=13379679.9508, ukdf['pct'].iloc[-1]=0.00055 , ukdf['amount'].iloc[-1]=13379679.9508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33493.4226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29270', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22433
self.closeSec=1690763099, self.tradeDate='20230731', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29270.1, self.close=29277.4, self.high=29279.5, self.low=29265.9, self.vol=373.211, self.amt=10925146.8601 
127.0.0.1 - - [31/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-31 08:25:00,793:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230731   080000    080459  ...         0.0        0.0       0
5857  20230731   080500    080959  ...         0.0        0.0       0
5858  20230731   081000    081459  ...         0.0        0.0       0
5859  20230731   081500    081959  ...         0.0        0.0       0
5860  20230731   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 08:25:00,793:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690763099, self.tradeDate='20230731', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29270.1, self.close=29277.4, self.high=29279.5, self.low=29265.9, self.vol=373.211, self.amt=10925146.8601, ukdf['pct'].iloc[-1]=0.000253 , ukdf['amount'].iloc[-1]=10925146.8601, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33597.8676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29277.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29253.9, self.close=29270.0, self.high=29270.1, self.low=29250.0 
127.0.0.1 - - [31/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 08:20:03,636:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29253.9, self.close=29270.0, self.high=29270.1, self.low=29250.0   
2023-07-31 08:20:04,418:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230731   075500    075959  1690761599  ...  29260.8  0.000355   1535    5
1536  20230731   080000    080459  1690761899  ...  29267.0  0.000249   1536    0
1537  20230731   080500    080959  1690762199  ...  29250.4 -0.000639   1537    1
1538  20230731   081000    081459  1690762499  ...  29252.0 -0.000202   1538    2
1539  20230731   081500    081959  1690762799  ...  29250.0  0.000550   1539    3

[5 rows x 11 columns]
2023-07-31 08:20:04,426:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [31/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.5819453029494369, self.count=22435 

self.closeSec=1690763099, self.tradeDate='20230731', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29270.1, self.close=29277.4, self.high=29279.5, self.low=29265.9 
2023-07-31 08:25:00,773:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690763099, self.tradeDate='20230731', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29270.1, self.close=29277.4, self.high=29279.5, self.low=29265.9   
2023-07-31 08:25:00,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230731   080000    080459  1690761899  ...  29267.0  0.000249   1536    0
1537  20230731   080500    080959  1690762199  ...  29250.4 -0.000639   1537    1
1538  20230731   081000    081459  1690762499  ...  29252.0 -0.000202   1538    2
1539  20230731   081500    081959  1690762799  ...  29250.0  0.000550   1539    3
1540  20230731   082000    082459  1690763099  ...  29265.9  0.000253   1540    4

[5 rows x 11 columns]
2023-07-31 08:25:00,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-31 08:00:18,184:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230731    052959  29255.6  ...  45.833333  0.449284  0.494845
5771  20230731    055959  29180.6  ...  46.250000  0.455896  0.499640
5772  20230731    062959  29195.2  ...  46.250000  0.437381  0.511768
5773  20230731    065959  29145.1  ...  46.666667  0.437753  0.522965
5774  20230731    072959  29145.9  ...  46.666667  0.483378  0.517425

[5 rows x 33 columns]
0.5656192236598891
acc is : 0.5656192236598891
2023-07-31 08:00:18,266:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.470690  0.529310       1  ...  0.926511   1.0    0.0  0.974687
537     1  0.491841  0.508159       0  ...  0.924922   1.0    0.0  0.973015
538     1  0.486306  0.513694       0  ...  0.924947   1.0    0.0  0.973041
539     0  0.501019  0.498981       1  ...  0.928270   1.0    0.0  0.976537
540     0  0.525183  0.474817       1  ...  0.928923   1.0    0.0  0.977225

[5 rows x 10 columns]
2023-07-31 08:00:18,285:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.470782  0.529218       1  ...  0.926511   1.0    0.0  0.975107
46     1  0.492150  0.507850       0  ...  0.924922   1.0    0.0  0.975212
47     1  0.486393  0.513607       0  ...  0.924947   1.0    0.0  0.975037
48     0  0.501019  0.498981       1  ...  0.928270   1.0    0.0  0.976537
49     0  0.525183  0.474817       1  ...  0.928923   1.0    0.0  0.977225

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-4981.49133909282', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29268.85182051', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230731   075000    075959  1690761599    29255  29271.1  0.000550
2023-07-31 08:00:02,285:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11216 

self.closeSec=1690762199, self.tradeDate='20230731', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29271.2', self.close='29259.8'
2023-07-31 08:10:01,156:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690762199, self.tradeDate='20230731', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29271.2', self.close='29259.8'
2023-07-31 08:10:01,172:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230731   072000    072959  1690759799    29220  29250.5  0.001044
621  20230731   073000    073959  1690760399  29250.5  29257.7  0.000246
622  20230731   074000    074959  1690760999  29257.8    29255 -0.000092
623  20230731   075000    075959  1690761599    29255  29271.1  0.000550
624  20230731   080000    080959  1690762199  29271.2  29259.8 -0.000386
2023-07-31 08:10:01,173:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11217 

self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29259.9', self.close='29270.1'
127.0.0.1 - - [31/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 08:20:05,596:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29259.9', self.close='29270.1'
2023-07-31 08:20:05,986:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230731   073000    073959  1690760399  29250.5  29257.7  0.000246
622  20230731   074000    074959  1690760999  29257.8    29255 -0.000092
623  20230731   075000    075959  1690761599    29255  29271.1  0.000550
624  20230731   080000    080959  1690762199  29271.2  29259.8 -0.000386
625  20230731   081000    081959  1690762799  29259.9  29270.1  0.000352
2023-07-31 08:20:05,986:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230731   075000    075959  1690761599    29255  29271.1
2023-07-31 08:00:02,292:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11219 

self.closeSec=1690762199, self.tradeDate='20230731', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29271.2', self.close='29259.8'
2023-07-31 08:10:01,166:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690762199, self.tradeDate='20230731', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29271.2', self.close='29259.8'
127.0.0.1 - - [31/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-31 08:10:01,175:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230731   072000    072959  1690759799    29220  29250.5
17469  20230731   073000    073959  1690760399  29250.5  29257.7
17470  20230731   074000    074959  1690760999  29257.8    29255
17471  20230731   075000    075959  1690761599    29255  29271.1
17472  20230731   080000    080959  1690762199  29271.2  29259.8
2023-07-31 08:10:01,175:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11220 

self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29259.9', self.close='29270.1'
127.0.0.1 - - [31/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-31 08:20:06,670:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29259.9', self.close='29270.1'
2023-07-31 08:20:06,773:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230731   073000    073959  1690760399  29250.5  29257.7
17470  20230731   074000    074959  1690760999  29257.8    29255
17471  20230731   075000    075959  1690761599    29255  29271.1
17472  20230731   080000    080959  1690762199  29271.2  29259.8
17473  20230731   081000    081959  1690762799  29259.9  29270.1
2023-07-31 08:20:06,774:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230731   075000    075959  1690761599    29255  29271.1
2023-07-31 08:00:02,289:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11219 

self.closeSec=1690762199, self.tradeDate='20230731', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29271.2', self.close='29259.8'
2023-07-31 08:10:01,158:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690762199, self.tradeDate='20230731', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29271.2', self.close='29259.8'
127.0.0.1 - - [31/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-31 08:10:01,164:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230731   072000    072959  1690759799    29220  29250.5
12141  20230731   073000    073959  1690760399  29250.5  29257.7
12142  20230731   074000    074959  1690760999  29257.8    29255
12143  20230731   075000    075959  1690761599    29255  29271.1
12144  20230731   080000    080959  1690762199  29271.2  29259.8
2023-07-31 08:10:01,165:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11220 

self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29259.9', self.close='29270.1'
127.0.0.1 - - [31/Jul/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-07-31 08:20:06,545:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29259.9', self.close='29270.1'
2023-07-31 08:20:06,671:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230731   073000    073959  1690760399  29250.5  29257.7
12142  20230731   074000    074959  1690760999  29257.8    29255
12143  20230731   075000    075959  1690761599    29255  29271.1
12144  20230731   080000    080959  1690762199  29271.2  29259.8
12145  20230731   081000    081959  1690762799  29259.9  29270.1
2023-07-31 08:20:06,671:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22432
self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29253.9, self.close=29270.0, self.high=29270.1, self.low=29250.0, self.vol=457.335, self.amt=13379679.9508 
127.0.0.1 - - [31/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-31 08:20:05,007:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230731   075500    075959  ...         0.0        0.0       0
5856  20230731   080000    080459  ...         0.0        0.0       0
5857  20230731   080500    080959  ...         0.0        0.0       0
5858  20230731   081000    081459  ...         0.0        0.0       0
5859  20230731   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 08:20:05,028:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690762799, self.tradeDate='20230731', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29253.9, self.close=29270.0, self.high=29270.1, self.low=29250.0, self.vol=457.335, self.amt=13379679.9508, ukdf['pct'].iloc[-1]=0.00055 , ukdf['amount'].iloc[-1]=13379679.9508, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90104.066', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29270', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [31/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22433
self.closeSec=1690763099, self.tradeDate='20230731', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29270.1, self.close=29277.4, self.high=29279.5, self.low=29265.9, self.vol=373.211, self.amt=10925146.8601 
2023-07-31 08:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230731   080000    080459  ...         0.0        0.0       0
5857  20230731   080500    080959  ...         0.0        0.0       0
5858  20230731   081000    081459  ...         0.0        0.0       0
5859  20230731   081500    081959  ...         0.0        0.0       0
5860  20230731   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-31 08:25:00,822:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690763099, self.tradeDate='20230731', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29270.1, self.close=29277.4, self.high=29279.5, self.low=29265.9, self.vol=373.211, self.amt=10925146.8601, ukdf['pct'].iloc[-1]=0.000253 , ukdf['amount'].iloc[-1]=10925146.8601, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90382.6235', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29277.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230730   200000    235959  1690732799  ...    719  0.097821 -1.014500    -1.0
720  20230731   000000    035959  1690747199  ...    720  0.066577 -1.120057    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '4230.83276564928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29169.68605128', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=467
self.closeSec=1690761599, self.tradeDate='20230731', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29187.2, self.close=29271.1, self.high=29274.0, self.low=29006.0, self.vol=50696.613, self.amt=1478429324.01631 
127.0.0.1 - - [31/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-31 08:00:01,835:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690761599, self.tradeDate='20230731', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29187.2, self.close=29271.1, self.high=29274.0, self.low=29006.0, self.vol=50696.613, self.amt=1478429324.01631 
2023-07-31 08:00:01,851:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230730   120000    155959  ...  11221.774  3.286130e+08 -0.000689
718  20230730   160000    195959  ...  20506.002  6.003079e+08  0.000727
719  20230730   200000    235959  ...  40656.643  1.193675e+09  0.001222
720  20230731   000000    035959  ...  37631.169  1.101025e+09 -0.005110
721  20230731   040000    075959  ...  50696.613  1.478429e+09  0.002875

[5 rows x 11 columns]
2023-07-31 08:00:02,666:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230730   120000    155959  1690703999  ...    717  0.121428 -0.957668    -1.0
718  20230730   160000    195959  1690718399  ...    718  0.123511 -0.928860    -1.0
719  20230730   200000    235959  1690732799  ...    719  0.097821 -1.014500    -1.0
720  20230731   000000    035959  1690747199  ...    720  0.066577 -1.120057    -1.0
721  20230731   040000    075959  1690761599  ...    721  0.098298 -0.965533    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-1253.3568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29271.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


