# 20230723 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20128
self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29760.1, self.close=29777.3, self.high=29780.1, self.low=29748.2, self.vol=608.899, self.amt=18123966.1399 
127.0.0.1 - - [23/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 08:20:05,590:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230723   075500    075959  ...         0.0        0.0       0
5856  20230723   080000    080459  ...         0.0        0.0       0
5857  20230723   080500    080959  ...         0.0        0.0       0
5858  20230723   081000    081459  ...         0.0        0.0       0
5859  20230723   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 08:20:05,609:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29760.1, self.close=29777.3, self.high=29780.1, self.low=29748.2, self.vol=608.899, self.amt=18123966.1399, ukdf['pct'].iloc[-1]=0.000581 , ukdf['amount'].iloc[-1]=18123966.1399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40558.0824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29777.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20129
self.closeSec=1690071899, self.tradeDate='20230723', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29777.3, self.close=29768.2, self.high=29777.4, self.low=29758.7, self.vol=397.528, self.amt=11834084.2224 
127.0.0.1 - - [23/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-23 08:25:00,762:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230723   080000    080459  ...         0.0        0.0       0
5857  20230723   080500    080959  ...         0.0        0.0       0
5858  20230723   081000    081459  ...         0.0        0.0       0
5859  20230723   081500    081959  ...         0.0        0.0       0
5860  20230723   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 08:25:00,762:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690071899, self.tradeDate='20230723', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29777.3, self.close=29768.2, self.high=29777.4, self.low=29758.7, self.vol=397.528, self.amt=11834084.2224, ukdf['pct'].iloc[-1]=-0.000306 , ukdf['amount'].iloc[-1]=11834084.2224, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40429.9632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29768.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29760.1, self.close=29777.3, self.high=29780.1, self.low=29748.2 
127.0.0.1 - - [23/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 08:20:04,049:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29760.1, self.close=29777.3, self.high=29780.1, self.low=29748.2   
2023-07-23 08:20:04,980:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230723   075500    075959  1690070399  ...  29740.4  0.001439   1535    5
1536  20230723   080000    080459  1690070699  ...  29769.3 -0.000527   1536    0
1537  20230723   080500    080959  1690070999  ...  29766.7  0.000927   1537    1
1538  20230723   081000    081459  1690071299  ...  29760.0 -0.001238   1538    2
1539  20230723   081500    081959  1690071599  ...  29748.2  0.000581   1539    3

[5 rows x 11 columns]
2023-07-23 08:20:04,989:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6051361738333548, self.count=20131 

self.closeSec=1690071899, self.tradeDate='20230723', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29777.3, self.close=29768.2, self.high=29777.4, self.low=29758.7 
2023-07-23 08:25:00,728:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690071899, self.tradeDate='20230723', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29777.3, self.close=29768.2, self.high=29777.4, self.low=29758.7   
2023-07-23 08:25:00,752:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230723   080000    080459  1690070699  ...  29769.3 -0.000527   1536    0
1537  20230723   080500    080959  1690070999  ...  29766.7  0.000927   1537    1
1538  20230723   081000    081459  1690071299  ...  29760.0 -0.001238   1538    2
1539  20230723   081500    081959  1690071599  ...  29748.2  0.000581   1539    3
1540  20230723   082000    082459  1690071899  ...  29758.7 -0.000306   1540    4

[5 rows x 11 columns]
2023-07-23 08:25:00,752:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-23 08:00:18,484:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230723    052959  29810.3  ...  50.416667  0.478247  0.687626
5771  20230723    055959  29823.1  ...  50.000000  0.473607  0.699458
5772  20230723    062959  29810.9  ...  50.000000  0.470690  0.712015
5773  20230723    065959  29803.1  ...  50.000000  0.466766  0.722983
5774  20230723    072959  29792.9  ...  49.583333  0.427892  0.727433

[5 rows x 33 columns]
0.5138632162661737
acc is : 0.5138632162661737
2023-07-23 08:00:18,536:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.510752  0.489248       0  ...  0.963098   1.0    0.0  0.972963
537     0  0.501355  0.498645       0  ...  0.962849   1.0    0.0  0.972712
538     0  0.503247  0.496753       0  ...  0.962517   1.0    0.0  0.972375
539     0  0.502156  0.497844       0  ...  0.958963   1.0    0.0  0.968785
540     1  0.466647  0.533353       1  ...  0.962261   1.0    0.0  0.972118

[5 rows x 10 columns]
2023-07-23 08:00:18,547:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.511081  0.488919       0  ...  0.968627   1.0    0.0  0.974674
46     0  0.501871  0.498129       0  ...  0.968377   1.0    0.0  0.976472
47     0  0.503485  0.496515       0  ...  0.968042   1.0    0.0  0.972639
48     0  0.502156  0.497844       0  ...  0.958963   1.0    0.0  0.968785
49     1  0.466647  0.533353       1  ...  0.962261   1.0    0.0  0.972118

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '-1263.6316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29785.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230723   075000    075959  1690070399    29714  29783.5  0.002336
2023-07-23 08:00:02,434:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10064 

self.closeSec=1690070999, self.tradeDate='20230723', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29783.5', self.close='29796.9'
2023-07-23 08:10:01,064:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690070999, self.tradeDate='20230723', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29783.5', self.close='29796.9'
127.0.0.1 - - [23/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-23 08:10:01,095:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230723   072000    072959  1690068599  29689.4  29682.9 -0.000222
621  20230723   073000    073959  1690069199  29682.8  29690.5  0.000256
622  20230723   074000    074959  1690069799  29690.1  29714.1  0.000795
623  20230723   075000    075959  1690070399    29714  29783.5  0.002336
624  20230723   080000    080959  1690070999  29783.5  29796.9  0.000450
2023-07-23 08:10:01,095:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10065 

self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29797', self.close='29777.3'
127.0.0.1 - - [23/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 08:20:05,929:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29797', self.close='29777.3'
2023-07-23 08:20:06,410:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230723   073000    073959  1690069199  29682.8  29690.5  0.000256
622  20230723   074000    074959  1690069799  29690.1  29714.1  0.000795
623  20230723   075000    075959  1690070399    29714  29783.5  0.002336
624  20230723   080000    080959  1690070999  29783.5  29796.9  0.000450
625  20230723   081000    081959  1690071599    29797  29777.3 -0.000658
2023-07-23 08:20:06,419:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230723   075000    075959  1690070399    29714  29783.5
2023-07-23 08:00:02,441:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10067 

self.closeSec=1690070999, self.tradeDate='20230723', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29783.5', self.close='29796.9'
2023-07-23 08:10:01,082:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690070999, self.tradeDate='20230723', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29783.5', self.close='29796.9'
2023-07-23 08:10:01,099:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230723   072000    072959  1690068599  29689.4  29682.9
17469  20230723   073000    073959  1690069199  29682.8  29690.5
17470  20230723   074000    074959  1690069799  29690.1  29714.1
17471  20230723   075000    075959  1690070399    29714  29783.5
17472  20230723   080000    080959  1690070999  29783.5  29796.9
2023-07-23 08:10:01,099:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10068 

self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29797', self.close='29777.3'
127.0.0.1 - - [23/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 08:20:07,054:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29797', self.close='29777.3'
2023-07-23 08:20:07,250:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230723   073000    073959  1690069199  29682.8  29690.5
17470  20230723   074000    074959  1690069799  29690.1  29714.1
17471  20230723   075000    075959  1690070399    29714  29783.5
17472  20230723   080000    080959  1690070999  29783.5  29796.9
17473  20230723   081000    081959  1690071599    29797  29777.3
2023-07-23 08:20:07,250:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230723   075000    075959  1690070399    29714  29783.5
2023-07-23 08:00:02,426:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10067 

self.closeSec=1690070999, self.tradeDate='20230723', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29783.5', self.close='29796.9'
2023-07-23 08:10:01,072:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690070999, self.tradeDate='20230723', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29783.5', self.close='29796.9'
127.0.0.1 - - [23/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-23 08:10:01,090:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230723   072000    072959  1690068599  29689.4  29682.9
12141  20230723   073000    073959  1690069199  29682.8  29690.5
12142  20230723   074000    074959  1690069799  29690.1  29714.1
12143  20230723   075000    075959  1690070399    29714  29783.5
12144  20230723   080000    080959  1690070999  29783.5  29796.9
2023-07-23 08:10:01,090:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10068 

self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29797', self.close='29777.3'
127.0.0.1 - - [23/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-23 08:20:06,920:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29797', self.close='29777.3'
2023-07-23 08:20:07,152:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230723   073000    073959  1690069199  29682.8  29690.5
12142  20230723   074000    074959  1690069799  29690.1  29714.1
12143  20230723   075000    075959  1690070399    29714  29783.5
12144  20230723   080000    080959  1690070999  29783.5  29796.9
12145  20230723   081000    081959  1690071599    29797  29777.3
2023-07-23 08:20:07,153:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20128
self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29760.1, self.close=29777.3, self.high=29780.1, self.low=29748.2, self.vol=608.899, self.amt=18123966.1399 
127.0.0.1 - - [23/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-23 08:20:05,610:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230723   075500    075959  ...         0.0        0.0       0
5856  20230723   080000    080459  ...         0.0        0.0       0
5857  20230723   080500    080959  ...         0.0        0.0       0
5858  20230723   081000    081459  ...         0.0        0.0       0
5859  20230723   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 08:20:05,631:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690071599, self.tradeDate='20230723', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29760.1, self.close=29777.3, self.high=29780.1, self.low=29748.2, self.vol=608.899, self.amt=18123966.1399, ukdf['pct'].iloc[-1]=0.000581 , ukdf['amount'].iloc[-1]=18123966.1399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '108945.6953', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29777.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20129
self.closeSec=1690071899, self.tradeDate='20230723', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29777.3, self.close=29768.2, self.high=29777.4, self.low=29758.7, self.vol=397.528, self.amt=11834084.2224 
127.0.0.1 - - [23/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-23 08:25:00,765:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230723   080000    080459  ...         0.0        0.0       0
5857  20230723   080500    080959  ...         0.0        0.0       0
5858  20230723   081000    081459  ...         0.0        0.0       0
5859  20230723   081500    081959  ...         0.0        0.0       0
5860  20230723   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-23 08:25:00,766:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690071899, self.tradeDate='20230723', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29777.3, self.close=29768.2, self.high=29777.4, self.low=29758.7, self.vol=397.528, self.amt=11834084.2224, ukdf['pct'].iloc[-1]=-0.000306 , ukdf['amount'].iloc[-1]=11834084.2224, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '108603.9981', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29768.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230722   200000    235959  1690041599  ...    719  0.072097 -1.233408    -1.0
720  20230723   000000    035959  1690055999  ...    720  0.074972 -1.193808    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '2614.0176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29820.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=419
self.closeSec=1690070399, self.tradeDate='20230723', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29820.5, self.close=29783.5, self.high=29831.3, self.low=29602.2, self.vol=33991.832, self.amt=1010297192.22228 
127.0.0.1 - - [23/Jul/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-07-23 08:00:02,013:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690070399, self.tradeDate='20230723', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29820.5, self.close=29783.5, self.high=29831.3, self.low=29602.2, self.vol=33991.832, self.amt=1010297192.22228 
2023-07-23 08:00:02,026:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230722   120000    155959  ...  26673.540  7.974821e+08  0.001553
718  20230722   160000    195959  ...  22981.220  6.872208e+08 -0.001968
719  20230722   200000    235959  ...  24285.778  7.249418e+08  0.000328
720  20230723   000000    035959  ...  17262.524  5.149351e+08 -0.002118
721  20230723   040000    075959  ...  33991.832  1.010297e+09 -0.001244

[5 rows x 11 columns]
2023-07-23 08:00:02,721:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230722   120000    155959  1690012799  ...    717  0.092641 -1.205199    -1.0
718  20230722   160000    195959  1690027199  ...    718  0.080624 -1.227083    -1.0
719  20230722   200000    235959  1690041599  ...    719  0.072097 -1.233408    -1.0
720  20230723   000000    035959  1690055999  ...    720  0.074972 -1.193808    -1.0
721  20230723   040000    075959  1690070399  ...    721  0.164716 -0.808995    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '4544.38578155184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29783.50275641', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


