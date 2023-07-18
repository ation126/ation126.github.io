# 20230718 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18688
self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30125.6, self.close=30122.1, self.high=30125.6, self.low=30093.1, self.vol=870.335, self.amt=26204613.6243 
127.0.0.1 - - [18/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 08:20:06,718:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230718   075500    075959  ...         0.0        0.0       0
5856  20230718   080000    080459  ...         0.0        0.0       0
5857  20230718   080500    080959  ...         0.0        0.0       0
5858  20230718   081000    081459  ...         0.0        0.0       0
5859  20230718   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 08:20:06,747:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30125.6, self.close=30122.1, self.high=30125.6, self.low=30093.1, self.vol=870.335, self.amt=26204613.6243, ukdf['pct'].iloc[-1]=-0.000116 , ukdf['amount'].iloc[-1]=26204613.6243, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-45358.3746', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30122', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18689
self.closeSec=1689639899, self.tradeDate='20230718', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30122.1, self.close=30134.7, self.high=30155.6, self.low=30109.4, self.vol=497.48, self.amt=14991090.5433 
2023-07-18 08:25:00,734:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230718   080000    080459  ...         0.0        0.0       0
5857  20230718   080500    080959  ...         0.0        0.0       0
5858  20230718   081000    081459  ...         0.0        0.0       0
5859  20230718   081500    081959  ...         0.0        0.0       0
5860  20230718   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 08:25:00,734:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689639899, self.tradeDate='20230718', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30122.1, self.close=30134.7, self.high=30155.6, self.low=30109.4, self.vol=497.48, self.amt=14991090.5433, ukdf['pct'].iloc[-1]=0.000418 , ukdf['amount'].iloc[-1]=14991090.5433, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-45593.4312142056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30138.8789756', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30125.6, self.close=30122.1, self.high=30125.6, self.low=30093.1 
127.0.0.1 - - [18/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 08:20:04,667:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30125.6, self.close=30122.1, self.high=30125.6, self.low=30093.1   
2023-07-18 08:20:05,918:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230718   075500    075959  1689638399  ...  30122.1 -0.000620   1535    5
1536  20230718   080000    080459  1689638699  ...  30112.6 -0.000342   1536    0
1537  20230718   080500    080959  1689638999  ...  30115.8  0.001139   1537    1
1538  20230718   081000    081459  1689639299  ...  30124.2 -0.000813   1538    2
1539  20230718   081500    081959  1689639599  ...  30093.1 -0.000116   1539    3

[5 rows x 11 columns]
2023-07-18 08:20:05,928:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.5170786224997616, self.count=18691 

self.closeSec=1689639899, self.tradeDate='20230718', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30122.1, self.close=30134.7, self.high=30155.6, self.low=30109.4 
127.0.0.1 - - [18/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-18 08:25:00,720:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689639899, self.tradeDate='20230718', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30122.1, self.close=30134.7, self.high=30155.6, self.low=30109.4   
2023-07-18 08:25:00,746:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230718   080000    080459  1689638699  ...  30112.6 -0.000342   1536    0
1537  20230718   080500    080959  1689638999  ...  30115.8  0.001139   1537    1
1538  20230718   081000    081459  1689639299  ...  30124.2 -0.000813   1538    2
1539  20230718   081500    081959  1689639599  ...  30093.1 -0.000116   1539    3
1540  20230718   082000    082459  1689639899  ...  30109.4  0.000418   1540    4

[5 rows x 11 columns]
2023-07-18 08:25:00,746:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-18 08:00:17,297:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230718    052959  29907.1  ...  52.083333  0.453947  0.525766
5771  20230718    055959  30048.1  ...  52.083333  0.499538  0.498806
5772  20230718    062959  30229.9  ...  51.666667  0.488124  0.478536
5773  20230718    065959  30180.7  ...  51.250000  0.469732  0.467836
5774  20230718    072959  30096.3  ...  51.250000  0.473907  0.456153

[5 rows x 33 columns]
0.5175600739371534
acc is : 0.5175600739371534
2023-07-18 08:00:17,361:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.567193  0.432807       1  ...  0.969623   1.0 -0.0016  1.000238
537     0  0.586186  0.413814       0  ...  0.968013   1.0  0.0000  0.998577
538     0  0.526080  0.473920       0  ...  0.965309   1.0  0.0000  0.995788
539     0  0.504055  0.495945       1  ...  0.965867   1.0  0.0000  0.996364
540     0  0.531759  0.468241       1  ...  0.966262   1.0  0.0000  0.996771

[5 rows x 10 columns]
2023-07-18 08:00:17,373:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.566109  0.433891       1  ...  0.999812   1.0 -0.0016  0.994863
46     0  0.585477  0.414523       0  ...  0.998152   1.0  0.0000  0.994969
47     0  0.525929  0.474071       0  ...  0.965309   1.0  0.0000  0.993169
48     0  0.504631  0.495369       1  ...  0.965867   1.0  0.0000  0.996364
49     0  0.531759  0.468241       1  ...  0.966262   1.0  0.0000  0.996771

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.036', 'enterprice': '30219.4', 'countrevence': '0', 'unrealprofit': '-2153.6256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30129.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230718   075000    075959  1689638399  30130.4  30126.1 -0.000143
2023-07-18 08:00:02,135:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9344 

self.closeSec=1689638999, self.tradeDate='20230718', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30126', self.close='30150.1'
2023-07-18 08:10:01,136:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689638999, self.tradeDate='20230718', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30126', self.close='30150.1'
127.0.0.1 - - [18/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-18 08:10:01,172:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230718   072000    072959  1689636599  30126.3  30113.8 -0.000415
621  20230718   073000    073959  1689637199  30113.8  30138.3  0.000814
622  20230718   074000    074959  1689637799  30138.3  30130.4 -0.000262
623  20230718   075000    075959  1689638399  30130.4  30126.1 -0.000143
624  20230718   080000    080959  1689638999    30126  30150.1  0.000797
2023-07-18 08:10:01,172:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9345 

self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30150', self.close='30122.1'
127.0.0.1 - - [18/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 08:20:07,237:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30150', self.close='30122.1'
2023-07-18 08:20:07,957:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230718   073000    073959  1689637199  30113.8  30138.3  0.000814
622  20230718   074000    074959  1689637799  30138.3  30130.4 -0.000262
623  20230718   075000    075959  1689638399  30130.4  30126.1 -0.000143
624  20230718   080000    080959  1689638999    30126  30150.1  0.000797
625  20230718   081000    081959  1689639599    30150  30122.1 -0.000929
2023-07-18 08:20:07,958:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230718   075000    075959  1689638399  30130.4  30126.1
2023-07-18 08:00:02,127:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9347 

self.closeSec=1689638999, self.tradeDate='20230718', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30126', self.close='30150.1'
2023-07-18 08:10:01,137:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689638999, self.tradeDate='20230718', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30126', self.close='30150.1'
127.0.0.1 - - [18/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-18 08:10:01,151:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230718   072000    072959  1689636599  30126.3  30113.8
17469  20230718   073000    073959  1689637199  30113.8  30138.3
17470  20230718   074000    074959  1689637799  30138.3  30130.4
17471  20230718   075000    075959  1689638399  30130.4  30126.1
17472  20230718   080000    080959  1689638999    30126  30150.1
2023-07-18 08:10:01,151:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9348 

self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30150', self.close='30122.1'
127.0.0.1 - - [18/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 08:20:08,832:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30150', self.close='30122.1'
2023-07-18 08:20:09,067:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230718   073000    073959  1689637199  30113.8  30138.3
17470  20230718   074000    074959  1689637799  30138.3  30130.4
17471  20230718   075000    075959  1689638399  30130.4  30126.1
17472  20230718   080000    080959  1689638999    30126  30150.1
17473  20230718   081000    081959  1689639599    30150  30122.1
2023-07-18 08:20:09,068:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230718   075000    075959  1689638399  30130.4  30126.1
2023-07-18 08:00:02,138:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9347 

self.closeSec=1689638999, self.tradeDate='20230718', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30126', self.close='30150.1'
2023-07-18 08:10:01,148:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689638999, self.tradeDate='20230718', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30126', self.close='30150.1'
2023-07-18 08:10:01,175:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230718   072000    072959  1689636599  30126.3  30113.8
12141  20230718   073000    073959  1689637199  30113.8  30138.3
12142  20230718   074000    074959  1689637799  30138.3  30130.4
12143  20230718   075000    075959  1689638399  30130.4  30126.1
12144  20230718   080000    080959  1689638999    30126  30150.1
2023-07-18 08:10:01,175:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9348 

self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30150', self.close='30122.1'
127.0.0.1 - - [18/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-18 08:20:08,637:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30150', self.close='30122.1'
2023-07-18 08:20:08,926:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230718   073000    073959  1689637199  30113.8  30138.3
12142  20230718   074000    074959  1689637799  30138.3  30130.4
12143  20230718   075000    075959  1689638399  30130.4  30126.1
12144  20230718   080000    080959  1689638999    30126  30150.1
12145  20230718   081000    081959  1689639599    30150  30122.1
2023-07-18 08:20:08,927:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18688
self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30125.6, self.close=30122.1, self.high=30125.6, self.low=30093.1, self.vol=870.335, self.amt=26204613.6243 
127.0.0.1 - - [18/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-18 08:20:06,578:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230718   075500    075959  ...         0.0        0.0       0
5856  20230718   080000    080459  ...         0.0        0.0       0
5857  20230718   080500    080959  ...         0.0        0.0       0
5858  20230718   081000    081459  ...         0.0        0.0       0
5859  20230718   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 08:20:06,608:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689639599, self.tradeDate='20230718', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30125.6, self.close=30122.1, self.high=30125.6, self.low=30093.1, self.vol=870.335, self.amt=26204613.6243, ukdf['pct'].iloc[-1]=-0.000116 , ukdf['amount'].iloc[-1]=26204613.6243, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '121748.198', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30122', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18689
self.closeSec=1689639899, self.tradeDate='20230718', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30122.1, self.close=30134.7, self.high=30155.6, self.low=30109.4, self.vol=497.48, self.amt=14991090.5433 
127.0.0.1 - - [18/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-18 08:25:00,754:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230718   080000    080459  ...         0.0        0.0       0
5857  20230718   080500    080959  ...         0.0        0.0       0
5858  20230718   081000    081459  ...         0.0        0.0       0
5859  20230718   081500    081959  ...         0.0        0.0       0
5860  20230718   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-18 08:25:00,754:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689639899, self.tradeDate='20230718', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30122.1, self.close=30134.7, self.high=30155.6, self.low=30109.4, self.vol=497.48, self.amt=14991090.5433, ukdf['pct'].iloc[-1]=0.000418 , ukdf['amount'].iloc[-1]=14991090.5433, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '122375.1000327596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30138.8789756', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230717   200000    235959  1689609599  ...    719  0.746221  1.277956     1.0
720  20230718   000000    035959  1689623999  ...    720  0.675919  0.990122     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-33153.50833864601', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29876.47378039', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=389
self.closeSec=1689638399, self.tradeDate='20230718', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29869.9, self.close=30126.1, self.high=30282.9, self.low=29864.6, self.vol=51790.057, self.amt=1558369426.7134 
127.0.0.1 - - [18/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-18 08:00:01,713:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689638399, self.tradeDate='20230718', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29869.9, self.close=30126.1, self.high=30282.9, self.low=29864.6, self.vol=51790.057, self.amt=1558369426.7134 
2023-07-18 08:00:01,726:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230717   120000    155959  ...   13248.606  4.010111e+08 -0.001013
718  20230717   160000    195959  ...   67733.832  2.041188e+09 -0.003972
719  20230717   200000    235959  ...   66486.808  2.006394e+09  0.000610
720  20230718   000000    035959  ...  122153.882  3.654921e+09 -0.009727
721  20230718   040000    075959  ...   51790.057  1.558369e+09  0.008574

[5 rows x 11 columns]
2023-07-18 08:00:02,448:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230717   120000    155959  1689580799  ...    717  0.755479  1.365454     1.0
718  20230717   160000    195959  1689595199  ...    718  0.734620  1.260333     1.0
719  20230717   200000    235959  1689609599  ...    719  0.746221  1.277956     1.0
720  20230718   000000    035959  1689623999  ...    720  0.675919  0.990122     1.0
721  20230718   040000    075959  1689638399  ...    721  0.608408  0.713520     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-20112.785', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30126.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


