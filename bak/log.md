# 20230704 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14656
self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=31130.0, self.close=31131.9, self.high=31136.0, self.low=31129.2, self.vol=222.713, self.amt=6933518.343 
127.0.0.1 - - [04/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 08:20:07,723:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230704   075500    075959  ...         0.0        0.0       0
5856  20230704   080000    080459  ...         0.0        0.0       0
5857  20230704   080500    080959  ...         0.0        0.0       0
5858  20230704   081000    081459  ...         0.0        0.0       0
5859  20230704   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 08:20:07,754:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=31130.0, self.close=31131.9, self.high=31136.0, self.low=31129.2, self.vol=222.713, self.amt=6933518.343, ukdf['pct'].iloc[-1]=5.8e-05 , ukdf['amount'].iloc[-1]=6933518.343, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-59429.0717922396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31132.3904346', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=14657
self.closeSec=1688430299, self.tradeDate='20230704', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=31132.0, self.close=31118.0, self.high=31136.0, self.low=31107.9, self.vol=669.99, self.amt=20850947.6723 
127.0.0.1 - - [04/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-04 08:25:00,849:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230704   080000    080459  ...         0.0        0.0       0
5857  20230704   080500    080959  ...         0.0        0.0       0
5858  20230704   081000    081459  ...         0.0        0.0       0
5859  20230704   081500    081959  ...         0.0        0.0       0
5860  20230704   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 08:25:00,849:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688430299, self.tradeDate='20230704', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=31132.0, self.close=31118.0, self.high=31136.0, self.low=31107.9, self.vol=669.99, self.amt=20850947.6723, ukdf['pct'].iloc[-1]=-0.000446 , ukdf['amount'].iloc[-1]=20850947.6723, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-59227.278', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31117.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=31130.0, self.close=31131.9, self.high=31136.0, self.low=31129.2 
127.0.0.1 - - [04/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 08:20:05,263:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=31130.0, self.close=31131.9, self.high=31136.0, self.low=31129.2   
2023-07-04 08:20:06,892:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230704   075500    075959  1688428799  ...  31134.4  0.000189   1535    5
1536  20230704   080000    080459  1688429099  ...  31109.8 -0.000549   1536    0
1537  20230704   080500    080959  1688429399  ...  31131.8  0.000585   1537    1
1538  20230704   081000    081459  1688429699  ...  31130.0 -0.000639   1538    2
1539  20230704   081500    081959  1688429999  ...  31129.2  0.000058   1539    3

[5 rows x 11 columns]
2023-07-04 08:20:06,893:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=174, self.factor=0.3065857238187155, self.count=14659 

self.closeSec=1688430299, self.tradeDate='20230704', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=31132.0, self.close=31118.0, self.high=31136.0, self.low=31107.9 
127.0.0.1 - - [04/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-04 08:25:00,777:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688430299, self.tradeDate='20230704', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=31132.0, self.close=31118.0, self.high=31136.0, self.low=31107.9   
2023-07-04 08:25:00,827:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230704   080000    080459  1688429099  ...  31109.8 -0.000549   1536    0
1537  20230704   080500    080959  1688429399  ...  31131.8  0.000585   1537    1
1538  20230704   081000    081459  1688429699  ...  31130.0 -0.000639   1538    2
1539  20230704   081500    081959  1688429999  ...  31129.2  0.000058   1539    3
1540  20230704   082000    082459  1688430299  ...  31107.9 -0.000446   1540    4

[5 rows x 11 columns]
2023-07-04 08:25:00,828:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-04 08:00:18,406:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230704    052959  31113.0  ...  53.333333  0.567946  0.251960
5771  20230704    055959  31015.9  ...  53.333333  0.573074  0.263168
5772  20230704    062959  31044.0  ...  53.333333  0.587410  0.267335
5773  20230704    065959  31123.0  ...  53.333333  0.584794  0.272046
5774  20230704    072959  31112.7  ...  52.916667  0.583558  0.276826

[5 rows x 33 columns]
0.5249537892791127
acc is : 0.5249537892791127
2023-07-04 08:00:18,496:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.489699  0.510301       1  ...  1.007134   1.0    0.0  1.034900
537     1  0.496919  0.503081       1  ...  1.009694   1.0    0.0  1.037530
538     0  0.516730  0.483270       0  ...  1.009360   1.0    0.0  1.037187
539     0  0.506000  0.494000       0  ...  1.009204   1.0    0.0  1.037027
540     0  0.514198  0.485802       1  ...  1.010537   1.0    0.0  1.038397

[5 rows x 10 columns]
2023-07-04 08:00:18,511:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.490132  0.509868       1  ...  1.007134   1.0    0.0  1.040446
46     1  0.496920  0.503080       1  ...  1.009694   1.0    0.0  1.034458
47     0  0.517328  0.482672       0  ...  1.009360   1.0    0.0  1.038551
48     0  0.506000  0.494000       0  ...  1.009204   1.0    0.0  1.037027
49     0  0.514198  0.485802       1  ...  1.010537   1.0    0.0  1.038397

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '15121.419', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31152.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230704   075000    075959  1688428799    31124    31149  0.000803
2023-07-04 08:00:02,132:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7328 

self.closeSec=1688429399, self.tradeDate='20230704', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='31149', self.close='31150'
2023-07-04 08:10:01,085:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688429399, self.tradeDate='20230704', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='31149', self.close='31150'
2023-07-04 08:10:01,146:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230704   072000    072959  1688426999  31108.8  31107.9 -0.000029
621  20230704   073000    073959  1688427599  31107.8  31114.7  0.000219
622  20230704   074000    074959  1688428199  31114.6    31124  0.000299
623  20230704   075000    075959  1688428799    31124    31149  0.000803
624  20230704   080000    080959  1688429399    31149    31150  0.000032
2023-07-04 08:10:01,147:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7329 

self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='31150.1', self.close='31131.9'
127.0.0.1 - - [04/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 08:20:07,512:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='31150.1', self.close='31131.9'
2023-07-04 08:20:08,393:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230704   073000    073959  1688427599  31107.8  31114.7  0.000219
622  20230704   074000    074959  1688428199  31114.6    31124  0.000299
623  20230704   075000    075959  1688428799    31124    31149  0.000803
624  20230704   080000    080959  1688429399    31149    31150  0.000032
625  20230704   081000    081959  1688429999  31150.1  31131.9 -0.000581
2023-07-04 08:20:08,402:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230704   075000    075959  1688428799    31124    31149
2023-07-04 08:00:02,127:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7331 

self.closeSec=1688429399, self.tradeDate='20230704', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='31149', self.close='31150'
2023-07-04 08:10:01,134:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688429399, self.tradeDate='20230704', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='31149', self.close='31150'
2023-07-04 08:10:01,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230704   072000    072959  1688426999  31108.8  31107.9
17469  20230704   073000    073959  1688427599  31107.8  31114.7
17470  20230704   074000    074959  1688428199  31114.6    31124
17471  20230704   075000    075959  1688428799    31124    31149
17472  20230704   080000    080959  1688429399    31149    31150
2023-07-04 08:10:01,179:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7332 

self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='31150.1', self.close='31131.9'
127.0.0.1 - - [04/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 08:20:09,743:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='31150.1', self.close='31131.9'
2023-07-04 08:20:09,892:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230704   073000    073959  1688427599  31107.8  31114.7
17470  20230704   074000    074959  1688428199  31114.6    31124
17471  20230704   075000    075959  1688428799    31124    31149
17472  20230704   080000    080959  1688429399    31149    31150
17473  20230704   081000    081959  1688429999  31150.1  31131.9
2023-07-04 08:20:09,893:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230704   075000    075959  1688428799    31124    31149
2023-07-04 08:00:02,124:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7331 

self.closeSec=1688429399, self.tradeDate='20230704', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='31149', self.close='31150'
2023-07-04 08:10:01,130:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688429399, self.tradeDate='20230704', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='31149', self.close='31150'
2023-07-04 08:10:01,168:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230704   072000    072959  1688426999  31108.8  31107.9
12141  20230704   073000    073959  1688427599  31107.8  31114.7
12142  20230704   074000    074959  1688428199  31114.6    31124
12143  20230704   075000    075959  1688428799    31124    31149
12144  20230704   080000    080959  1688429399    31149    31150
2023-07-04 08:10:01,169:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7332 

self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='31150.1', self.close='31131.9'
127.0.0.1 - - [04/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-04 08:20:09,286:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='31150.1', self.close='31131.9'
2023-07-04 08:20:09,638:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230704   073000    073959  1688427599  31107.8  31114.7
12142  20230704   074000    074959  1688428199  31114.6    31124
12143  20230704   075000    075959  1688428799    31124    31149
12144  20230704   080000    080959  1688429399    31149    31150
12145  20230704   081000    081959  1688429999  31150.1  31131.9
2023-07-04 08:20:09,640:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14656
self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=31130.0, self.close=31131.9, self.high=31136.0, self.low=31129.2, self.vol=222.713, self.amt=6933518.343 
127.0.0.1 - - [04/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-04 08:20:07,714:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230704   075500    075959  ...         0.0        0.0       0
5856  20230704   080000    080459  ...         0.0        0.0       0
5857  20230704   080500    080959  ...         0.0        0.0       0
5858  20230704   081000    081459  ...         0.0        0.0       0
5859  20230704   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 08:20:07,755:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688429999, self.tradeDate='20230704', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=31130.0, self.close=31131.9, self.high=31136.0, self.low=31129.2, self.vol=222.713, self.amt=6933518.343, ukdf['pct'].iloc[-1]=5.8e-05 , ukdf['amount'].iloc[-1]=6933518.343, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '159275.1091314786', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31132.3904346', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=14657
self.closeSec=1688430299, self.tradeDate='20230704', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=31132.0, self.close=31118.0, self.high=31136.0, self.low=31107.9, self.vol=669.99, self.amt=20850947.6723 
127.0.0.1 - - [04/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-04 08:25:00,848:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230704   080000    080459  ...         0.0        0.0       0
5857  20230704   080500    080959  ...         0.0        0.0       0
5858  20230704   081000    081459  ...         0.0        0.0       0
5859  20230704   081500    081959  ...         0.0        0.0       0
5860  20230704   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-04 08:25:00,850:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688430299, self.tradeDate='20230704', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=31132.0, self.close=31118.0, self.high=31136.0, self.low=31107.9, self.vol=669.99, self.amt=20850947.6723, ukdf['pct'].iloc[-1]=-0.000446 , ukdf['amount'].iloc[-1]=20850947.6723, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '158736.9199', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31117.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230703   200000    235959  1688399999  ...    719  0.000007 -1.130948    -1.0
720  20230704   000000    035959  1688414399  ...    720  0.000231 -1.107635    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-29350.668', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31258', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [04/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=305
self.closeSec=1688428799, self.tradeDate='20230704', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=31254.0, self.close=31149.0, self.high=31300.5, self.low=30875.2, self.vol=56721.25, self.amt=1764470426.54252 
2023-07-04 08:00:01,692:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688428799, self.tradeDate='20230704', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=31254.0, self.close=31149.0, self.high=31300.5, self.low=30875.2, self.vol=56721.25, self.amt=1764470426.54252 
2023-07-04 08:00:01,713:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230703   120000    155959  ...   33689.441  1.033809e+09 -0.002768
718  20230703   160000    195959  ...   24118.202  7.388557e+08 -0.001409
719  20230703   200000    235959  ...  104314.045  3.220393e+09  0.014340
720  20230704   000000    035959  ...  115662.573  3.598670e+09  0.006291
721  20230704   040000    075959  ...   56721.250  1.764470e+09 -0.003363

[5 rows x 11 columns]
2023-07-04 08:00:03,036:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230703   120000    155959  1688371199  ...    717  0.000010 -1.178390    -1.0
718  20230703   160000    195959  1688385599  ...    718  0.000193 -1.153916    -1.0
719  20230703   200000    235959  1688399999  ...    719  0.000007 -1.130948    -1.0
720  20230704   000000    035959  1688414399  ...    720  0.000231 -1.107635    -1.0
721  20230704   040000    075959  1688428799  ...    721  0.003309 -1.078267    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '-23544.456', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31149', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


