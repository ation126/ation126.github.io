# 20230605 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6304
self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27087.2, self.close=27061.2, self.high=27094.3, self.low=27044.4, self.vol=1488.008, self.amt=40269092.6997 
127.0.0.1 - - [05/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 08:20:06,963:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230605   075500    075959  ...         0.0        0.0       0
5856  20230605   080000    080459  ...         0.0        0.0       0
5857  20230605   080500    080959  ...         0.0        0.0       0
5858  20230605   081000    081459  ...         0.0        0.0       0
5859  20230605   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 08:20:06,973:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27087.2, self.close=27061.2, self.high=27094.3, self.low=27044.4, self.vol=1488.008, self.amt=40269092.6997, ukdf['pct'].iloc[-1]=-0.000956 , ukdf['amount'].iloc[-1]=40269092.6997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2665.4364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27056.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=6305
self.closeSec=1685924699, self.tradeDate='20230605', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27061.2, self.close=27091.4, self.high=27105.4, self.low=27027.8, self.vol=1863.496, self.amt=50428562.1769 
2023-06-05 08:25:00,865:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230605   080000    080459  ...         0.0        0.0       0
5857  20230605   080500    080959  ...         0.0        0.0       0
5858  20230605   081000    081459  ...         0.0        0.0       0
5859  20230605   081500    081959  ...         0.0        0.0       0
5860  20230605   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 08:25:00,865:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685924699, self.tradeDate='20230605', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27061.2, self.close=27091.4, self.high=27105.4, self.low=27027.8, self.vol=1863.496, self.amt=50428562.1769, ukdf['pct'].iloc[-1]=0.001116 , ukdf['amount'].iloc[-1]=50428562.1769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3192.36235344642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27094.13756667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27087.2, self.close=27061.2, self.high=27094.3, self.low=27044.4 
127.0.0.1 - - [05/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 08:20:04,673:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27087.2, self.close=27061.2, self.high=27094.3, self.low=27044.4   
2023-06-05 08:20:05,984:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230605   075500    075959  1685923199  ...  27074.6  0.000218   1535    5
1536  20230605   080000    080459  1685923499  ...  27054.8 -0.001015   1536    0
1537  20230605   080500    080959  1685923799  ...  27056.1  0.001662   1537    1
1538  20230605   081000    081459  1685924099  ...  27073.7 -0.001213   1538    2
1539  20230605   081500    081959  1685924399  ...  27044.4 -0.000956   1539    3

[5 rows x 11 columns]
2023-06-05 08:20:05,993:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [05/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=83, self.factor=0.4619805532803441, self.count=6307 

self.closeSec=1685924699, self.tradeDate='20230605', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27061.2, self.close=27091.4, self.high=27105.4, self.low=27027.8 
2023-06-05 08:25:00,746:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685924699, self.tradeDate='20230605', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27061.2, self.close=27091.4, self.high=27105.4, self.low=27027.8   
2023-06-05 08:25:00,814:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230605   080000    080459  1685923499  ...  27054.8 -0.001015   1536    0
1537  20230605   080500    080959  1685923799  ...  27056.1  0.001662   1537    1
1538  20230605   081000    081459  1685924099  ...  27073.7 -0.001213   1538    2
1539  20230605   081500    081959  1685924399  ...  27044.4 -0.000956   1539    3
1540  20230605   082000    082459  1685924699  ...  27027.8  0.001116   1540    4

[5 rows x 11 columns]
2023-06-05 08:25:00,814:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-05 08:00:32,881:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230605    052959  27233.2  ...  46.250000  0.533483  0.307859
5771  20230605    055959  27223.5  ...  46.250000  0.517919  0.312717
5772  20230605    062959  27185.3  ...  46.666667  0.536867  0.325158
5773  20230605    065959  27237.7  ...  46.250000  0.530104  0.339271
5774  20230605    072959  27221.1  ...  46.250000  0.496261  0.365716

[5 rows x 33 columns]
0.5304990757855823
acc is : 0.5304990757855823
2023-06-05 08:00:33,041:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498056  0.501944       0  ...  1.040869   1.0    0.0  1.035244
537     1  0.489347  0.510653       1  ...  1.042879   1.0    0.0  1.037243
538     0  0.509544  0.490456       0  ...  1.042240   1.0    0.0  1.036607
539     1  0.493463  0.506537       0  ...  1.038848   1.0    0.0  1.033233
540     1  0.474305  0.525695       0  ...  1.037699   1.0    0.0  1.032091

[5 rows x 10 columns]
2023-06-05 08:00:33,069:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497832  0.502168       0  ...  1.040869   1.0    0.0  1.033394
46     1  0.489572  0.510428       1  ...  1.042879   1.0    0.0  1.039535
47     0  0.509407  0.490593       0  ...  1.042240   1.0    0.0  1.037785
48     1  0.493463  0.506537       0  ...  1.038848   1.0    0.0  1.033233
49     1  0.474305  0.525695       0  ...  1.037699   1.0    0.0  1.032091

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.623', 'enterprice': '26988.6', 'countrevence': '0', 'unrealprofit': '2856.03568351357', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27091.99339259', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230605   075000    075959  1685923199    27095  27102.4  0.000273
2023-06-05 08:00:02,185:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3152 

self.closeSec=1685923799, self.tradeDate='20230605', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27102.4', self.close='27120'
2023-06-05 08:10:01,155:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685923799, self.tradeDate='20230605', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27102.4', self.close='27120'
127.0.0.1 - - [05/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-05 08:10:01,223:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230605   072000    072959  1685921399  27251.1  27132.5 -0.004348
621  20230605   073000    073959  1685921999  27132.6  27147.6  0.000557
622  20230605   074000    074959  1685922599  27147.5    27095 -0.001938
623  20230605   075000    075959  1685923199    27095  27102.4  0.000273
624  20230605   080000    080959  1685923799  27102.4    27120  0.000649
2023-06-05 08:10:01,223:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3153 

self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27120', self.close='27061.2'
127.0.0.1 - - [05/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 08:20:06,960:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27120', self.close='27061.2'
2023-06-05 08:20:07,722:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230605   073000    073959  1685921999  27132.6  27147.6  0.000557
622  20230605   074000    074959  1685922599  27147.5    27095 -0.001938
623  20230605   075000    075959  1685923199    27095  27102.4  0.000273
624  20230605   080000    080959  1685923799  27102.4    27120  0.000649
625  20230605   081000    081959  1685924399    27120  27061.2 -0.002168
2023-06-05 08:20:07,723:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230605   075000    075959  1685923199    27095  27102.4
2023-06-05 08:00:02,210:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3155 

self.closeSec=1685923799, self.tradeDate='20230605', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27102.4', self.close='27120'
2023-06-05 08:10:01,144:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685923799, self.tradeDate='20230605', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27102.4', self.close='27120'
2023-06-05 08:10:01,236:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230605   072000    072959  1685921399  27251.1  27132.5
17469  20230605   073000    073959  1685921999  27132.6  27147.6
17470  20230605   074000    074959  1685922599  27147.5    27095
17471  20230605   075000    075959  1685923199    27095  27102.4
17472  20230605   080000    080959  1685923799  27102.4    27120
2023-06-05 08:10:01,236:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3156 

self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27120', self.close='27061.2'
127.0.0.1 - - [05/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 08:20:08,536:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27120', self.close='27061.2'
2023-06-05 08:20:08,674:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230605   073000    073959  1685921999  27132.6  27147.6
17470  20230605   074000    074959  1685922599  27147.5    27095
17471  20230605   075000    075959  1685923199    27095  27102.4
17472  20230605   080000    080959  1685923799  27102.4    27120
17473  20230605   081000    081959  1685924399    27120  27061.2
2023-06-05 08:20:08,674:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230605   075000    075959  1685923199    27095  27102.4
2023-06-05 08:00:02,208:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [05/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3155 

self.closeSec=1685923799, self.tradeDate='20230605', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27102.4', self.close='27120'
2023-06-05 08:10:01,111:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685923799, self.tradeDate='20230605', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27102.4', self.close='27120'
2023-06-05 08:10:01,201:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230605   072000    072959  1685921399  27251.1  27132.5
12141  20230605   073000    073959  1685921999  27132.6  27147.6
12142  20230605   074000    074959  1685922599  27147.5    27095
12143  20230605   075000    075959  1685923199    27095  27102.4
12144  20230605   080000    080959  1685923799  27102.4    27120
2023-06-05 08:10:01,201:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3156 

self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27120', self.close='27061.2'
127.0.0.1 - - [05/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-05 08:20:08,306:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27120', self.close='27061.2'
2023-06-05 08:20:08,524:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230605   073000    073959  1685921999  27132.6  27147.6
12142  20230605   074000    074959  1685922599  27147.5    27095
12143  20230605   075000    075959  1685923199    27095  27102.4
12144  20230605   080000    080959  1685923799  27102.4    27120
12145  20230605   081000    081959  1685924399    27120  27061.2
2023-06-05 08:20:08,525:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6304
self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27087.2, self.close=27061.2, self.high=27094.3, self.low=27044.4, self.vol=1488.008, self.amt=40269092.6997 
127.0.0.1 - - [05/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-05 08:20:06,916:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230605   075500    075959  ...         0.0        0.0       0
5856  20230605   080000    080459  ...         0.0        0.0       0
5857  20230605   080500    080959  ...         0.0        0.0       0
5858  20230605   081000    081459  ...         0.0        0.0       0
5859  20230605   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 08:20:06,959:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685924399, self.tradeDate='20230605', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27087.2, self.close=27061.2, self.high=27094.3, self.low=27044.4, self.vol=1488.008, self.amt=40269092.6997, ukdf['pct'].iloc[-1]=-0.000956 , ukdf['amount'].iloc[-1]=40269092.6997, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '7881.3202', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27056.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [05/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=6305
self.closeSec=1685924699, self.tradeDate='20230605', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27061.2, self.close=27091.4, self.high=27105.4, self.low=27027.8, self.vol=1863.496, self.amt=50428562.1769 
2023-06-05 08:25:00,753:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230605   080000    080459  ...         0.0        0.0       0
5857  20230605   080500    080959  ...         0.0        0.0       0
5858  20230605   081000    081459  ...         0.0        0.0       0
5859  20230605   081500    081959  ...         0.0        0.0       0
5860  20230605   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-05 08:25:00,762:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685924699, self.tradeDate='20230605', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27061.2, self.close=27091.4, self.high=27105.4, self.low=27027.8, self.vol=1863.496, self.amt=50428562.1769, ukdf['pct'].iloc[-1]=0.001116 , ukdf['amount'].iloc[-1]=50428562.1769, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '9290.35936369047', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27094.13756667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230604   200000    235959  1685894399  ...    719  0.040939 -1.528777    -1.0
720  20230605   000000    035959  1685908799  ...    720  0.041719 -1.513107    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '-7023.39952701722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27205.91391667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [05/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=131
self.closeSec=1685923199, self.tradeDate='20230605', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27205.0, self.close=27102.4, self.high=27460.0, self.low=27026.0, self.vol=83709.147, self.amt=2280936192.86417 
2023-06-05 08:00:01,741:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685923199, self.tradeDate='20230605', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27205.0, self.close=27102.4, self.high=27460.0, self.low=27026.0, self.vol=83709.147, self.amt=2280936192.86417 
2023-06-05 08:00:01,771:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230604   120000    155959  ...  23617.719  6.399566e+08  0.003423
718  20230604   160000    195959  ...  29667.465  8.064795e+08  0.001839
719  20230604   200000    235959  ...  38245.649  1.040603e+09 -0.000883
720  20230605   000000    035959  ...  17756.474  4.826483e+08  0.001402
721  20230605   040000    075959  ...  83709.147  2.280936e+09 -0.003771

[5 rows x 11 columns]
2023-06-05 08:00:03,707:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230604   120000    155959  1685865599  ...    717  0.029091 -1.593836    -1.0
718  20230604   160000    195959  1685879999  ...    718  0.035998 -1.557238    -1.0
719  20230604   200000    235959  1685894399  ...    719  0.040939 -1.528777    -1.0
720  20230605   000000    035959  1685908799  ...    720  0.041719 -1.513107    -1.0
721  20230605   040000    075959  1685923199  ...    721  0.045863 -1.488578    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '-1412.8455969142', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27104.2108037', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


