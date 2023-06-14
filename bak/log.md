# 20230614 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8896
self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25943.2, self.close=25943.4, self.high=25945.5, self.low=25897.6, self.vol=1371.796, self.amt=35555952.646 
127.0.0.1 - - [14/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 08:20:07,196:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230614   075500    075959  ...         0.0        0.0       0
5856  20230614   080000    080459  ...         0.0        0.0       0
5857  20230614   080500    080959  ...         0.0        0.0       0
5858  20230614   081000    081459  ...         0.0        0.0       0
5859  20230614   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 08:20:07,225:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25943.2, self.close=25943.4, self.high=25945.5, self.low=25897.6, self.vol=1371.796, self.amt=35555952.646, ukdf['pct'].iloc[-1]=1.2e-05 , ukdf['amount'].iloc[-1]=35555952.646, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12866.2314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8897
self.closeSec=1686702299, self.tradeDate='20230614', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25943.4, self.close=25963.8, self.high=25969.6, self.low=25926.6, self.vol=910.084, self.amt=23619800.835 
127.0.0.1 - - [14/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-14 08:25:00,772:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230614   080000    080459  ...         0.0        0.0       0
5857  20230614   080500    080959  ...         0.0        0.0       0
5858  20230614   081000    081459  ...         0.0        0.0       0
5859  20230614   081500    081959  ...         0.0        0.0       0
5860  20230614   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 08:25:00,773:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686702299, self.tradeDate='20230614', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25943.4, self.close=25963.8, self.high=25969.6, self.low=25926.6, self.vol=910.084, self.amt=23619800.835, ukdf['pct'].iloc[-1]=0.000786 , ukdf['amount'].iloc[-1]=23619800.835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12495.38681500032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25967.62965568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25943.2, self.close=25943.4, self.high=25945.5, self.low=25897.6 
127.0.0.1 - - [14/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 08:20:04,877:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25943.2, self.close=25943.4, self.high=25945.5, self.low=25897.6   
2023-06-14 08:20:06,265:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230614   075500    075959  1686700799  ...  25890.7  0.000707   1535    5
1536  20230614   080000    080459  1686701099  ...  25911.7  0.000598   1536    0
1537  20230614   080500    080959  1686701399  ...  25930.4  0.000332   1537    1
1538  20230614   081000    081459  1686701699  ...  25926.5  0.000035   1538    2
1539  20230614   081500    081959  1686701999  ...  25897.6  0.000012   1539    3

[5 rows x 11 columns]
2023-06-14 08:20:06,266:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [14/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=74, self.factor=0.48540749395289895, self.count=8899 

self.closeSec=1686702299, self.tradeDate='20230614', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25943.4, self.close=25963.8, self.high=25969.6, self.low=25926.6 
2023-06-14 08:25:00,721:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686702299, self.tradeDate='20230614', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25943.4, self.close=25963.8, self.high=25969.6, self.low=25926.6   
2023-06-14 08:25:00,756:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230614   080000    080459  1686701099  ...  25911.7  0.000598   1536    0
1537  20230614   080500    080959  1686701399  ...  25930.4  0.000332   1537    1
1538  20230614   081000    081459  1686701699  ...  25926.5  0.000035   1538    2
1539  20230614   081500    081959  1686701999  ...  25897.6  0.000012   1539    3
1540  20230614   082000    082459  1686702299  ...  25926.6  0.000786   1540    4

[5 rows x 11 columns]
2023-06-14 08:25:00,757:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-14 08:00:18,753:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230614    052959  25835.8  ...  47.500000  0.476707  0.623852
5771  20230614    055959  25840.7  ...  47.500000  0.475003  0.637376
5772  20230614    062959  25833.3  ...  47.083333  0.467354  0.653145
5773  20230614    065959  25799.1  ...  47.500000  0.474944  0.665095
5774  20230614    072959  25829.1  ...  47.916667  0.482371  0.673516

[5 rows x 33 columns]
0.5341959334565619
acc is : 0.5341959334565619
2023-06-14 08:00:18,849:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.500638  0.499362       0  ...  1.008527  -1.0    0.0  0.954463
537     1  0.498910  0.501090       0  ...  1.009858  -1.0    0.0  0.953203
538     1  0.488497  0.511503       1  ...  1.008684  -1.0    0.0  0.954311
539     0  0.506800  0.493200       1  ...  1.007528  -1.0    0.0  0.955405
540     0  0.510954  0.489046       1  ...  1.005214  -1.0    0.0  0.957599

[5 rows x 10 columns]
2023-06-14 08:00:18,872:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500628  0.499372       0  ...  1.008527  -1.0    0.0  0.953913
46     1  0.499074  0.500926       0  ...  1.009858  -1.0    0.0  0.954105
47     1  0.488490  0.511510       1  ...  1.008684  -1.0    0.0  0.954950
48     0  0.506800  0.493200       1  ...  1.007528  -1.0    0.0  0.955405
49     0  0.510954  0.489046       1  ...  1.005214  -1.0    0.0  0.957599

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-10285.9926', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25924.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230614   075000    075959  1686700799  25876.6    25918  0.001604
2023-06-14 08:00:02,282:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4448 

self.closeSec=1686701399, self.tradeDate='20230614', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25918', self.close='25942.2'
2023-06-14 08:10:01,137:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686701399, self.tradeDate='20230614', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25918', self.close='25942.2'
127.0.0.1 - - [14/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-14 08:10:01,172:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230614   072000    072959  1686698999  25864.8  25858.7 -0.000236
621  20230614   073000    073959  1686699599  25858.7    25854 -0.000182
622  20230614   074000    074959  1686700199    25854  25876.5  0.000870
623  20230614   075000    075959  1686700799  25876.6    25918  0.001604
624  20230614   080000    080959  1686701399    25918  25942.2  0.000934
2023-06-14 08:10:01,172:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4449 

self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25942.1', self.close='25943.4'
127.0.0.1 - - [14/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 08:20:06,816:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25942.1', self.close='25943.4'
2023-06-14 08:20:07,615:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230614   073000    073959  1686699599  25858.7    25854 -0.000182
622  20230614   074000    074959  1686700199    25854  25876.5  0.000870
623  20230614   075000    075959  1686700799  25876.6    25918  0.001604
624  20230614   080000    080959  1686701399    25918  25942.2  0.000934
625  20230614   081000    081959  1686701999  25942.1  25943.4  0.000046
2023-06-14 08:20:07,617:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230614   075000    075959  1686700799  25876.6    25918
2023-06-14 08:00:02,291:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4451 

self.closeSec=1686701399, self.tradeDate='20230614', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25918', self.close='25942.2'
127.0.0.1 - - [14/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-14 08:10:01,156:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686701399, self.tradeDate='20230614', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25918', self.close='25942.2'
2023-06-14 08:10:01,177:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230614   072000    072959  1686698999  25864.8  25858.7
17469  20230614   073000    073959  1686699599  25858.7    25854
17470  20230614   074000    074959  1686700199    25854  25876.5
17471  20230614   075000    075959  1686700799  25876.6    25918
17472  20230614   080000    080959  1686701399    25918  25942.2
2023-06-14 08:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4452 

self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25942.1', self.close='25943.4'
127.0.0.1 - - [14/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 08:20:08,547:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25942.1', self.close='25943.4'
2023-06-14 08:20:08,693:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230614   073000    073959  1686699599  25858.7    25854
17470  20230614   074000    074959  1686700199    25854  25876.5
17471  20230614   075000    075959  1686700799  25876.6    25918
17472  20230614   080000    080959  1686701399    25918  25942.2
17473  20230614   081000    081959  1686701999  25942.1  25943.4
2023-06-14 08:20:08,694:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230614   075000    075959  1686700799  25876.6    25918
2023-06-14 08:00:02,295:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4451 

self.closeSec=1686701399, self.tradeDate='20230614', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25918', self.close='25942.2'
2023-06-14 08:10:01,137:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686701399, self.tradeDate='20230614', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='25918', self.close='25942.2'
127.0.0.1 - - [14/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-14 08:10:01,153:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230614   072000    072959  1686698999  25864.8  25858.7
12141  20230614   073000    073959  1686699599  25858.7    25854
12142  20230614   074000    074959  1686700199    25854  25876.5
12143  20230614   075000    075959  1686700799  25876.6    25918
12144  20230614   080000    080959  1686701399    25918  25942.2
2023-06-14 08:10:01,154:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4452 

self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25942.1', self.close='25943.4'
127.0.0.1 - - [14/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-14 08:20:08,246:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='25942.1', self.close='25943.4'
2023-06-14 08:20:08,505:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230614   073000    073959  1686699599  25858.7    25854
12142  20230614   074000    074959  1686700199    25854  25876.5
12143  20230614   075000    075959  1686700799  25876.6    25918
12144  20230614   080000    080959  1686701399    25918  25942.2
12145  20230614   081000    081959  1686701999  25942.1  25943.4
2023-06-14 08:20:08,507:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8896
self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25943.2, self.close=25943.4, self.high=25945.5, self.low=25897.6, self.vol=1371.796, self.amt=35555952.646 
127.0.0.1 - - [14/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-14 08:20:07,186:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230614   075500    075959  ...         0.0        0.0       0
5856  20230614   080000    080459  ...         0.0        0.0       0
5857  20230614   080500    080959  ...         0.0        0.0       0
5858  20230614   081000    081459  ...         0.0        0.0       0
5859  20230614   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 08:20:07,215:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686701999, self.tradeDate='20230614', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25943.2, self.close=25943.4, self.high=25945.5, self.low=25897.6, self.vol=1371.796, self.amt=35555952.646, ukdf['pct'].iloc[-1]=1.2e-05 , ukdf['amount'].iloc[-1]=35555952.646, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-33538.323', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8897
self.closeSec=1686702299, self.tradeDate='20230614', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25943.4, self.close=25963.8, self.high=25969.6, self.low=25926.6, self.vol=910.084, self.amt=23619800.835 
127.0.0.1 - - [14/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-14 08:25:00,776:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230614   080000    080459  ...         0.0        0.0       0
5857  20230614   080500    080959  ...         0.0        0.0       0
5858  20230614   081000    081459  ...         0.0        0.0       0
5859  20230614   081500    081959  ...         0.0        0.0       0
5860  20230614   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-14 08:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686702299, self.tradeDate='20230614', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25943.4, self.close=25963.8, self.high=25969.6, self.low=25926.6, self.vol=910.084, self.amt=23619800.835, ukdf['pct'].iloc[-1]=0.000786 , ukdf['amount'].iloc[-1]=23619800.835, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32549.27095838912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25967.62965568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230613   200000    235959  1686671999  ...    719  0.245567 -1.098139    -1.0
720  20230614   000000    035959  1686686399  ...    720  0.145470 -1.430737    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '65934.4032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25883.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=185
self.closeSec=1686700799, self.tradeDate='20230614', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25891.2, self.close=25918.0, self.high=25949.7, self.low=25790.6, self.vol=28618.868, self.amt=739996232.0259 
127.0.0.1 - - [14/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-14 08:00:01,855:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686700799, self.tradeDate='20230614', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25891.2, self.close=25918.0, self.high=25949.7, self.low=25790.6, self.vol=28618.868, self.amt=739996232.0259 
2023-06-14 08:00:01,882:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230613   120000    155959  ...   34095.200  8.883871e+08  0.000215
718  20230613   160000    195959  ...   67198.597  1.757390e+09  0.004524
719  20230613   200000    235959  ...  185012.495  4.820442e+09 -0.016315
720  20230614   000000    035959  ...   49220.461  1.272345e+09  0.005444
721  20230614   040000    075959  ...   28618.868  7.399962e+08  0.001035

[5 rows x 11 columns]
2023-06-14 08:00:03,343:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230613   120000    155959  1686643199  ...    717  0.362114 -0.726321    -1.0
718  20230613   160000    195959  1686657599  ...    718  0.341905 -0.779007    -1.0
719  20230613   200000    235959  1686671999  ...    719  0.245567 -1.098139    -1.0
720  20230614   000000    035959  1686686399  ...    720  0.145470 -1.430737    -1.0
721  20230614   040000    075959  1686700799  ...    721  0.092837 -1.599018    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '63974.2440798181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25918.93201465', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


