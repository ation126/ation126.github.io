# 20230705 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14944
self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30773.0, self.close=30812.9, self.high=30816.0, self.low=30773.0, self.vol=590.417, self.amt=18185379.8202 
127.0.0.1 - - [05/Jul/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-07-05 08:20:07,908:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230705   075500    075959  ...         0.0        0.0       0
5856  20230705   080000    080459  ...         0.0        0.0       0
5857  20230705   080500    080959  ...         0.0        0.0       0
5858  20230705   081000    081459  ...         0.0        0.0       0
5859  20230705   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 08:20:07,957:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30773.0, self.close=30812.9, self.high=30816.0, self.low=30773.0, self.vol=590.417, self.amt=18185379.8202, ukdf['pct'].iloc[-1]=0.0013 , ukdf['amount'].iloc[-1]=18185379.8202, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-55004.84108912496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30814.69470696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14945
self.closeSec=1688516699, self.tradeDate='20230705', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30812.9, self.close=30816.3, self.high=30823.3, self.low=30804.1, self.vol=407.488, self.amt=12556698.3872 
2023-07-05 08:25:00,780:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230705   080000    080459  ...         0.0        0.0       0
5857  20230705   080500    080959  ...         0.0        0.0       0
5858  20230705   081000    081459  ...         0.0        0.0       0
5859  20230705   081500    081959  ...         0.0        0.0       0
5860  20230705   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 08:25:00,782:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688516699, self.tradeDate='20230705', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30812.9, self.close=30816.3, self.high=30823.3, self.low=30804.1, self.vol=407.488, self.amt=12556698.3872, ukdf['pct'].iloc[-1]=0.00011 , ukdf['amount'].iloc[-1]=12556698.3872, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-55059.96392093736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30818.65297436', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30773.0, self.close=30812.9, self.high=30816.0, self.low=30773.0 
127.0.0.1 - - [05/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-05 08:20:05,307:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30773.0, self.close=30812.9, self.high=30816.0, self.low=30773.0   
2023-07-05 08:20:06,867:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230705   075500    075959  1688515199  ...  30752.0 -0.000319   1535    5
1536  20230705   080000    080459  1688515499  ...  30750.8  0.000829   1536    0
1537  20230705   080500    080959  1688515799  ...  30781.6  0.000633   1537    1
1538  20230705   081000    081459  1688516099  ...  30772.9 -0.000919   1538    2
1539  20230705   081500    081959  1688516399  ...  30773.0  0.001300   1539    3

[5 rows x 11 columns]
2023-07-05 08:20:06,888:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=222, self.factor=0.5749792027897531, self.count=14947 

self.closeSec=1688516699, self.tradeDate='20230705', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30812.9, self.close=30816.3, self.high=30823.3, self.low=30804.1 
127.0.0.1 - - [05/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-05 08:25:00,694:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688516699, self.tradeDate='20230705', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30812.9, self.close=30816.3, self.high=30823.3, self.low=30804.1   
2023-07-05 08:25:00,712:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230705   080000    080459  1688515499  ...  30750.8  0.000829   1536    0
1537  20230705   080500    080959  1688515799  ...  30781.6  0.000633   1537    1
1538  20230705   081000    081459  1688516099  ...  30772.9 -0.000919   1538    2
1539  20230705   081500    081959  1688516399  ...  30773.0  0.001300   1539    3
1540  20230705   082000    082459  1688516699  ...  30804.1  0.000110   1540    4

[5 rows x 11 columns]
2023-07-05 08:25:00,712:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-05 08:00:19,751:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230705    052959  30787.0  ...  50.833333  0.479382  0.678120
5771  20230705    055959  30786.2  ...  51.250000  0.480392  0.681858
5772  20230705    062959  30790.4  ...  50.833333  0.478049  0.685389
5773  20230705    065959  30779.9  ...  51.250000  0.485144  0.685856
5774  20230705    072959  30808.8  ...  50.833333  0.482773  0.687294

[5 rows x 33 columns]
0.5785582255083179
acc is : 0.5785582255083179
2023-07-05 08:00:19,865:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.493712  0.506288       1  ...  0.925896   1.0    0.0  0.989670
537     0  0.508778  0.491222       0  ...  0.925583   1.0    0.0  0.989335
538     0  0.508709  0.491291       1  ...  0.926449   1.0    0.0  0.990261
539     0  0.509184  0.490816       0  ...  0.926142   1.0    0.0  0.989933
540     0  0.500396  0.499604       0  ...  0.924867   1.0    0.0  0.988570

[5 rows x 10 columns]
2023-07-05 08:00:19,897:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493825  0.506175       1  ...  0.922129   1.0    0.0  0.985668
46     0  0.510545  0.489455       0  ...  0.930486   1.0    0.0  0.996533
47     0  0.508687  0.491313       1  ...  0.927082   1.0    0.0  0.990943
48     0  0.509184  0.490816       0  ...  0.926142   1.0    0.0  0.989933
49     0  0.500396  0.499604       0  ...  0.924867   1.0    0.0  0.988570

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '4943.2401245871', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30753.62476007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230705   075000    075959  1688515199    30785  30756.1 -0.000936
2023-07-05 08:00:02,254:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7472 

self.closeSec=1688515799, self.tradeDate='20230705', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30756.1', self.close='30801.2'
2023-07-05 08:10:01,163:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688515799, self.tradeDate='20230705', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30756.1', self.close='30801.2'
127.0.0.1 - - [05/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-05 08:10:01,171:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230705   072000    072959  1688513399  30773.9  30798.6  0.000806
621  20230705   073000    073959  1688513999  30798.7    30804  0.000175
622  20230705   074000    074959  1688514599    30804  30784.9 -0.000620
623  20230705   075000    075959  1688515199    30785  30756.1 -0.000936
624  20230705   080000    080959  1688515799  30756.1  30801.2  0.001466
2023-07-05 08:10:01,172:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7473 

self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30801.2', self.close='30812.9'
127.0.0.1 - - [05/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 08:20:07,747:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30801.2', self.close='30812.9'
2023-07-05 08:20:08,577:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230705   073000    073959  1688513999  30798.7    30804  0.000175
622  20230705   074000    074959  1688514599    30804  30784.9 -0.000620
623  20230705   075000    075959  1688515199    30785  30756.1 -0.000936
624  20230705   080000    080959  1688515799  30756.1  30801.2  0.001466
625  20230705   081000    081959  1688516399  30801.2  30812.9  0.000380
2023-07-05 08:20:08,577:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230705   075000    075959  1688515199    30785  30756.1
2023-07-05 08:00:02,269:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7475 

self.closeSec=1688515799, self.tradeDate='20230705', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30756.1', self.close='30801.2'
2023-07-05 08:10:01,176:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688515799, self.tradeDate='20230705', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30756.1', self.close='30801.2'
2023-07-05 08:10:01,185:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230705   072000    072959  1688513399  30773.9  30798.6
17469  20230705   073000    073959  1688513999  30798.7    30804
17470  20230705   074000    074959  1688514599    30804  30784.9
17471  20230705   075000    075959  1688515199    30785  30756.1
17472  20230705   080000    080959  1688515799  30756.1  30801.2
2023-07-05 08:10:01,185:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7476 

self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30801.2', self.close='30812.9'
127.0.0.1 - - [05/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 08:20:09,961:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30801.2', self.close='30812.9'
2023-07-05 08:20:10,113:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230705   073000    073959  1688513999  30798.7    30804
17470  20230705   074000    074959  1688514599    30804  30784.9
17471  20230705   075000    075959  1688515199    30785  30756.1
17472  20230705   080000    080959  1688515799  30756.1  30801.2
17473  20230705   081000    081959  1688516399  30801.2  30812.9
2023-07-05 08:20:10,113:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230705   075000    075959  1688515199    30785  30756.1
2023-07-05 08:00:02,251:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7475 

self.closeSec=1688515799, self.tradeDate='20230705', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30756.1', self.close='30801.2'
2023-07-05 08:10:01,182:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688515799, self.tradeDate='20230705', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30756.1', self.close='30801.2'
2023-07-05 08:10:01,187:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230705   072000    072959  1688513399  30773.9  30798.6
12141  20230705   073000    073959  1688513999  30798.7    30804
12142  20230705   074000    074959  1688514599    30804  30784.9
12143  20230705   075000    075959  1688515199    30785  30756.1
12144  20230705   080000    080959  1688515799  30756.1  30801.2
2023-07-05 08:10:01,187:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7476 

self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30801.2', self.close='30812.9'
127.0.0.1 - - [05/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-05 08:20:09,519:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30801.2', self.close='30812.9'
2023-07-05 08:20:09,878:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230705   073000    073959  1688513999  30798.7    30804
12142  20230705   074000    074959  1688514599    30804  30784.9
12143  20230705   075000    075959  1688515199    30785  30756.1
12144  20230705   080000    080959  1688515799  30756.1  30801.2
12145  20230705   081000    081959  1688516399  30801.2  30812.9
2023-07-05 08:20:09,880:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14944
self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30773.0, self.close=30812.9, self.high=30816.0, self.low=30773.0, self.vol=590.417, self.amt=18185379.8202 
127.0.0.1 - - [05/Jul/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-07-05 08:20:07,888:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230705   075500    075959  ...         0.0        0.0       0
5856  20230705   080000    080459  ...         0.0        0.0       0
5857  20230705   080500    080959  ...         0.0        0.0       0
5858  20230705   081000    081459  ...         0.0        0.0       0
5859  20230705   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 08:20:07,927:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688516399, self.tradeDate='20230705', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30773.0, self.close=30812.9, self.high=30816.0, self.low=30773.0, self.vol=590.417, self.amt=18185379.8202, ukdf['pct'].iloc[-1]=0.0013 , ukdf['amount'].iloc[-1]=18185379.8202, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '147475.57211120136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30814.69470696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14945
self.closeSec=1688516699, self.tradeDate='20230705', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30812.9, self.close=30816.3, self.high=30823.3, self.low=30804.1, self.vol=407.488, self.amt=12556698.3872 
127.0.0.1 - - [05/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-05 08:25:00,781:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230705   080000    080459  ...         0.0        0.0       0
5857  20230705   080500    080959  ...         0.0        0.0       0
5858  20230705   081000    081459  ...         0.0        0.0       0
5859  20230705   081500    081959  ...         0.0        0.0       0
5860  20230705   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-05 08:25:00,783:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688516699, self.tradeDate='20230705', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30812.9, self.close=30816.3, self.high=30823.3, self.low=30804.1, self.vol=407.488, self.amt=12556698.3872, ukdf['pct'].iloc[-1]=0.00011 , ukdf['amount'].iloc[-1]=12556698.3872, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '147622.58612070476', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30818.65297436', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

718  20230704   160000    195959  ...  45148.630  1.398908e+09  0.004990
719  20230704   200000    235959  ...  38716.412  1.199547e+09 -0.003127
720  20230705   000000    035959  ...  94152.133  2.904600e+09 -0.008854
721  20230705   040000    075959  ...  26150.576  8.044804e+08  0.002311

[5 rows x 11 columns]
2023-07-05 08:00:03,254:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230704   120000    155959  1688457599  ...    717  0.022771 -0.989740    -1.0
718  20230704   160000    195959  1688471999  ...    718  0.024925 -0.965120    -1.0
719  20230704   200000    235959  1688486399  ...    719  0.029170 -0.937501    -1.0
720  20230705   000000    035959  1688500799  ...    720  0.414172 -0.063960     NaN
721  20230705   040000    075959  1688515199  ...    721  0.847470  0.903770     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-2666.8260299658', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30757.06431685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-2666.8260299658', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30757.06431685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-07-05 08:00:10,169:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1636546.9195416', 'total': '1636546.9195416', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-07-05 08:00:10,669:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-07-05 08:00:10,669:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.050, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42530F1688515210667I0L65'}
2023-07-05 08:00:10,692:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:7050800, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230705, closeTime:075959, close:30756.2, sign:1, total:1636546.9195416, side:buy  
127.0.0.1 - - [05/Jul/2023 08:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/Jul/2023 08:00:10] "POST / HTTP/1.1" 200 -
2023-07-05 08:00:10,697:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42529F1688515205037I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688515205471826, 'quantity': '53.268', 'price': '30755.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688515204098, 'updatetime': 1688515205471, 'tradetype': 'usdt', 'selfid': 42529, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688515205471, 'clientorderid': '42529F1688515205037I0L65', 'price': '30755.8', 'quantity': '53.268', 'commission': '1638.2999544', 'commissionasset': 'USDT', 'tradetime': 1688515205471, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688515205471}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-05 08:00:10,698:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42529F1688515205037I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688515205471826, 'quantity': '53.268', 'price': '30755.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688515204098, 'updatetime': 1688515205471, 'tradetype': 'usdt', 'selfid': 42529, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688515205471, 'clientorderid': '42529F1688515205037I0L65', 'price': '30755.8', 'quantity': '53.268', 'commission': '1638.2999544', 'commissionasset': 'USDT', 'tradetime': 1688515205471, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688515205471}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Jul/2023 08:00:11] "POST / HTTP/1.1" 200 -
2023-07-05 08:00:11,091:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42530F1688515210667I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688515211058705, 'quantity': '53.05', 'price': '30750.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688515210201, 'updatetime': 1688515211058, 'tradetype': 'usdt', 'selfid': 42530, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688515211058, 'clientorderid': '42530F1688515210667I0L65', 'price': '30750.9', 'quantity': '53.05', 'commission': '1631.335245', 'commissionasset': 'USDT', 'tradetime': 1688515211058, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688515211058}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-05 08:00:11,665:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42530F1688515210667I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688515211058705, 'quantity': '53.05', 'price': '30750.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688515210201, 'updatetime': 1688515211058, 'tradetype': 'usdt', 'selfid': 42530, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688515211058, 'clientorderid': '42530F1688515210667I0L65', 'price': '30750.9', 'quantity': '53.05', 'commission': '1631.335245', 'commissionasset': 'USDT', 'tradetime': 1688515211058, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688515211058}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [05/Jul/2023 08:00:11] "POST / HTTP/1.1" 200 -


