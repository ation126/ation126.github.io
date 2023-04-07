# 20230407 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37660
self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28002.7, self.close=27981.5, self.high=28006.6, self.low=27981.4, self.vol=781.577, self.amt=21878647.7221 
127.0.0.1 - - [07/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-07 08:20:10,229:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230407   075500    075959  ...         0.0        0.0       0
5856  20230407   080000    080459  ...         0.0        0.0       0
5857  20230407   080500    080959  ...         0.0        0.0       0
5858  20230407   081000    081459  ...         0.0        0.0       0
5859  20230407   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 08:20:10,249:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28002.7, self.close=27981.5, self.high=28006.6, self.low=27981.4, self.vol=781.577, self.amt=21878647.7221, ukdf['pct'].iloc[-1]=-0.000754 , ukdf['amount'].iloc[-1]=21878647.7221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-689322.0976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27984.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37661
self.closeSec=1680827099, self.tradeDate='20230407', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27981.4, self.close=28038.6, self.high=28038.6, self.low=27981.4, self.vol=883.64, self.amt=24752907.7578 
127.0.0.1 - - [07/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-07 08:25:01,712:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230407   080000    080459  ...         0.0        0.0       0
5857  20230407   080500    080959  ...         0.0        0.0       0
5858  20230407   081000    081459  ...         0.0        0.0       0
5859  20230407   081500    081959  ...         0.0        0.0       0
5860  20230407   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 08:25:01,714:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680827099, self.tradeDate='20230407', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27981.4, self.close=28038.6, self.high=28038.6, self.low=27981.4, self.vol=883.64, self.amt=24752907.7578, ukdf['pct'].iloc[-1]=0.002041 , ukdf['amount'].iloc[-1]=24752907.7578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-692577.6192', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28038.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28002.7, self.close=27981.5, self.high=28006.6, self.low=27981.4 
127.0.0.1 - - [07/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-07 08:20:07,579:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28002.7, self.close=27981.5, self.high=28006.6, self.low=27981.4   
2023-04-07 08:20:08,858:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230407   075500    075959  1680825599  ...  28006.8  0.000568   1535    5
1536  20230407   080000    080459  1680825899  ...  28016.3 -0.000079   1536    0
1537  20230407   080500    080959  1680826199  ...  28010.1 -0.000375   1537    1
1538  20230407   081000    081459  1680826499  ...  28002.6 -0.000268   1538    2
1539  20230407   081500    081959  1680826799  ...  27981.4 -0.000754   1539    3

[5 rows x 11 columns]
2023-04-07 08:20:08,859:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.5797373538283357, self.count=38227 

self.closeSec=1680827099, self.tradeDate='20230407', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27981.4, self.close=28038.6, self.high=28038.6, self.low=27981.4 
127.0.0.1 - - [07/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-07 08:25:01,807:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680827099, self.tradeDate='20230407', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27981.4, self.close=28038.6, self.high=28038.6, self.low=27981.4   
2023-04-07 08:25:01,834:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230407   080000    080459  1680825899  ...  28016.3 -0.000079   1536    0
1537  20230407   080500    080959  1680826199  ...  28010.1 -0.000375   1537    1
1538  20230407   081000    081459  1680826499  ...  28002.6 -0.000268   1538    2
1539  20230407   081500    081959  1680826799  ...  27981.4 -0.000754   1539    3
1540  20230407   082000    082459  1680827099  ...  27981.4  0.002041   1540    4

[5 rows x 11 columns]
2023-04-07 08:25:01,834:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-07 08:00:35,433:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230407    052959  27965.0  ...  47.916667  0.484801  0.480458
5771  20230407    055959  28008.7  ...  47.500000  0.478226  0.475812
5772  20230407    062959  27973.4  ...  47.083333  0.466254  0.480372
5773  20230407    065959  27907.8  ...  47.500000  0.483692  0.472865
5774  20230407    072959  27994.4  ...  47.916667  0.490537  0.461118

[5 rows x 33 columns]
0.5360443622920518
acc is : 0.5360443622920518
2023-04-07 08:00:35,590:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.529873  0.470127       0  ...  0.935830   1.0    0.0  1.006502
537     0  0.509344  0.490656       0  ...  0.933639   1.0    0.0  1.004145
538     1  0.496941  0.503059       1  ...  0.936536   1.0    0.0  1.007261
539     0  0.528494  0.471506       1  ...  0.937704   1.0    0.0  1.008517
540     0  0.529316  0.470684       0  ...  0.937483   1.0    0.0  1.008279

[5 rows x 10 columns]
2023-04-07 08:00:35,630:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.528955  0.471045       0  ...  0.935830   1.0    0.0  1.006549
46     0  0.509017  0.490983       0  ...  0.933639   1.0    0.0  1.004492
47     1  0.497484  0.502516       1  ...  0.936536   1.0    0.0  1.011088
48     0  0.528494  0.471506       1  ...  0.937704   1.0    0.0  1.008517
49     0  0.529316  0.470684       0  ...  0.937483   1.0    0.0  1.008279

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230407   075000    075959  1680825599    28010  28022.8  0.000457
2023-04-07 08:00:01,933:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19112 

self.closeSec=1680826199, self.tradeDate='20230407', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28022.9', self.close='28010.1'
2023-04-07 08:10:01,611:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680826199, self.tradeDate='20230407', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28022.9', self.close='28010.1'
2023-04-07 08:10:01,655:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230407   072000    072959  1680823799  28024.2  28029.4  0.000186
621  20230407   073000    073959  1680824399  28029.3  28004.8 -0.000878
622  20230407   074000    074959  1680824999  28004.9    28010  0.000186
623  20230407   075000    075959  1680825599    28010  28022.8  0.000457
624  20230407   080000    080959  1680826199  28022.9  28010.1 -0.000453
2023-04-07 08:10:01,655:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19113 

self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28010.1', self.close='27981.5'
127.0.0.1 - - [07/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 08:20:08,559:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28010.1', self.close='27981.5'
2023-04-07 08:20:09,428:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230407   073000    073959  1680824399  28029.3  28004.8 -0.000878
622  20230407   074000    074959  1680824999  28004.9    28010  0.000186
623  20230407   075000    075959  1680825599    28010  28022.8  0.000457
624  20230407   080000    080959  1680826199  28022.9  28010.1 -0.000453
625  20230407   081000    081959  1680826799  28010.1  27981.5 -0.001021
2023-04-07 08:20:09,429:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230407   075000    075959  1680825599    28010  28022.8
2023-04-07 08:00:01,936:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19113 

self.closeSec=1680826199, self.tradeDate='20230407', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28022.9', self.close='28010.1'
2023-04-07 08:10:01,633:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680826199, self.tradeDate='20230407', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28022.9', self.close='28010.1'
2023-04-07 08:10:01,663:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230407   072000    072959  1680823799  28024.2  28029.4
17469  20230407   073000    073959  1680824399  28029.3  28004.8
17470  20230407   074000    074959  1680824999  28004.9    28010
17471  20230407   075000    075959  1680825599    28010  28022.8
17472  20230407   080000    080959  1680826199  28022.9  28010.1
2023-04-07 08:10:01,663:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19114 

self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28010.1', self.close='27981.5'
127.0.0.1 - - [07/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 08:20:12,201:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28010.1', self.close='27981.5'
2023-04-07 08:20:12,338:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230407   073000    073959  1680824399  28029.3  28004.8
17470  20230407   074000    074959  1680824999  28004.9    28010
17471  20230407   075000    075959  1680825599    28010  28022.8
17472  20230407   080000    080959  1680826199  28022.9  28010.1
17473  20230407   081000    081959  1680826799  28010.1  27981.5
2023-04-07 08:20:12,338:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230407   075000    075959  1680825599    28010  28022.8
2023-04-07 08:00:01,947:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [07/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19113 

self.closeSec=1680826199, self.tradeDate='20230407', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28022.9', self.close='28010.1'
2023-04-07 08:10:01,643:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680826199, self.tradeDate='20230407', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28022.9', self.close='28010.1'
2023-04-07 08:10:01,689:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230407   072000    072959  1680823799  28024.2  28029.4
12141  20230407   073000    073959  1680824399  28029.3  28004.8
12142  20230407   074000    074959  1680824999  28004.9    28010
12143  20230407   075000    075959  1680825599    28010  28022.8
12144  20230407   080000    080959  1680826199  28022.9  28010.1
2023-04-07 08:10:01,700:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19114 

self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28010.1', self.close='27981.5'
127.0.0.1 - - [07/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-07 08:20:11,500:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28010.1', self.close='27981.5'
2023-04-07 08:20:11,929:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230407   073000    073959  1680824399  28029.3  28004.8
12142  20230407   074000    074959  1680824999  28004.9    28010
12143  20230407   075000    075959  1680825599    28010  28022.8
12144  20230407   080000    080959  1680826199  28022.9  28010.1
12145  20230407   081000    081959  1680826799  28010.1  27981.5
2023-04-07 08:20:11,930:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33658
self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28002.7, self.close=27981.5, self.high=28006.6, self.low=27981.4, self.vol=781.577, self.amt=21878647.7221 
127.0.0.1 - - [07/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-07 08:20:09,249:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230407   075500    075959  ...         0.0        0.0       0
5856  20230407   080000    080459  ...         0.0        0.0       0
5857  20230407   080500    080959  ...         0.0        0.0       0
5858  20230407   081000    081459  ...         0.0        0.0       0
5859  20230407   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 08:20:09,279:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680826799, self.tradeDate='20230407', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28002.7, self.close=27981.5, self.high=28006.6, self.low=27981.4, self.vol=781.577, self.amt=21878647.7221, ukdf['pct'].iloc[-1]=-0.000754 , ukdf['amount'].iloc[-1]=21878647.7221, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [07/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33659
self.closeSec=1680827099, self.tradeDate='20230407', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27981.4, self.close=28038.6, self.high=28038.6, self.low=27981.4, self.vol=883.64, self.amt=24752907.7578 
2023-04-07 08:25:01,646:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230407   080000    080459  ...         0.0        0.0       0
5857  20230407   080500    080959  ...         0.0        0.0       0
5858  20230407   081000    081459  ...         0.0        0.0       0
5859  20230407   081500    081959  ...         0.0        0.0       0
5860  20230407   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-07 08:25:01,648:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680827099, self.tradeDate='20230407', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27981.4, self.close=28038.6, self.high=28038.6, self.low=27981.4, self.vol=883.64, self.amt=24752907.7578, ukdf['pct'].iloc[-1]=0.002041 , ukdf['amount'].iloc[-1]=24752907.7578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230406   200000    235959  1680796799  ...    719  0.143949 -0.399815     NaN
720  20230407   000000    035959  1680811199  ...    720  0.136631 -0.433788     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '20670.00313041576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28001.97149573', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [07/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=796
self.closeSec=1680825599, self.tradeDate='20230407', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28005.0, self.close=28022.8, self.high=28112.0, self.low=27873.5, self.vol=34378.119, self.amt=962449698.5514 
2023-04-07 08:00:01,813:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680825599, self.tradeDate='20230407', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28005.0, self.close=28022.8, self.high=28112.0, self.low=27873.5, self.vol=34378.119, self.amt=962449698.5514 
2023-04-07 08:00:01,865:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230406   120000    155959  ...   36721.731  1.028841e+09 -0.007846
718  20230406   160000    195959  ...   78981.475  2.200855e+09  0.001366
719  20230406   200000    235959  ...  102413.306  2.862261e+09  0.005169
720  20230407   000000    035959  ...   45472.386  1.275123e+09 -0.002646
721  20230407   040000    075959  ...   34378.119  9.624497e+08  0.000636

[5 rows x 11 columns]
2023-04-07 08:00:04,402:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230406   120000    155959  1680767999  ...    717  0.109884 -0.581008     NaN
718  20230406   160000    195959  1680782399  ...    718  0.129378 -0.479627     NaN
719  20230406   200000    235959  1680796799  ...    719  0.143949 -0.399815     NaN
720  20230407   000000    035959  1680811199  ...    720  0.136631 -0.433788     NaN
721  20230407   040000    075959  1680825599  ...    721  0.131946 -0.455118     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '19579.8792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28022.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


