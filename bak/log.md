# 20230618 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10048
self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26520.1, self.close=26514.1, self.high=26520.1, self.low=26460.2, self.vol=1138.172, self.amt=30150625.2178 
127.0.0.1 - - [18/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-18 08:20:07,803:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230618   075500    075959  ...         0.0        0.0       0
5856  20230618   080000    080459  ...         0.0        0.0       0
5857  20230618   080500    080959  ...         0.0        0.0       0
5858  20230618   081000    081459  ...         0.0        0.0       0
5859  20230618   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 08:20:07,842:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26520.1, self.close=26514.1, self.high=26520.1, self.low=26460.2, self.vol=1138.172, self.amt=30150625.2178, ukdf['pct'].iloc[-1]=-0.000189 , ukdf['amount'].iloc[-1]=30150625.2178, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4906.7741198124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26512.5537326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10049
self.closeSec=1687047899, self.tradeDate='20230618', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26514.1, self.close=26435.3, self.high=26514.1, self.low=26415.2, self.vol=2624.898, self.amt=69414653.9782 
127.0.0.1 - - [18/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-18 08:25:00,789:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230618   080000    080459  ...         0.0        0.0       0
5857  20230618   080500    080959  ...         0.0        0.0       0
5858  20230618   081000    081459  ...         0.0        0.0       0
5859  20230618   081500    081959  ...         0.0        0.0       0
5860  20230618   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 08:25:00,789:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687047899, self.tradeDate='20230618', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26514.1, self.close=26435.3, self.high=26514.1, self.low=26415.2, self.vol=2624.898, self.amt=69414653.9782, ukdf['pct'].iloc[-1]=-0.002972 , ukdf['amount'].iloc[-1]=69414653.9782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5946.72357334308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26437.87690842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26520.1, self.close=26514.1, self.high=26520.1, self.low=26460.2 
127.0.0.1 - - [18/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-18 08:20:05,053:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26520.1, self.close=26514.1, self.high=26520.1, self.low=26460.2   
2023-06-18 08:20:06,703:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230618   075500    075959  1687046399  ...  26504.0 -0.000128   1535    5
1536  20230618   080000    080459  1687046699  ...  26502.7  0.000102   1536    0
1537  20230618   080500    080959  1687046999  ...  26508.8  0.000004   1537    1
1538  20230618   081000    081459  1687047299  ...  26509.0  0.000283   1538    2
1539  20230618   081500    081959  1687047599  ...  26460.2 -0.000189   1539    3

[5 rows x 11 columns]
2023-06-18 08:20:06,713:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=53, self.factor=0.32154299529368713, self.count=10051 

self.closeSec=1687047899, self.tradeDate='20230618', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26514.1, self.close=26435.3, self.high=26514.1, self.low=26415.2 
127.0.0.1 - - [18/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-18 08:25:00,734:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687047899, self.tradeDate='20230618', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26514.1, self.close=26435.3, self.high=26514.1, self.low=26415.2   
2023-06-18 08:25:00,775:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230618   080000    080459  1687046699  ...  26502.7  0.000102   1536    0
1537  20230618   080500    080959  1687046999  ...  26508.8  0.000004   1537    1
1538  20230618   081000    081459  1687047299  ...  26509.0  0.000283   1538    2
1539  20230618   081500    081959  1687047599  ...  26460.2 -0.000189   1539    3
1540  20230618   082000    082459  1687047899  ...  26415.2 -0.002972   1540    4

[5 rows x 11 columns]
2023-06-18 08:25:00,775:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-18 08:00:18,436:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230618    052959  26531.4  ...  51.250000  0.576540  0.460781
5771  20230618    055959  26493.3  ...  51.250000  0.579707  0.465718
5772  20230618    062959  26510.1  ...  51.666667  0.584548  0.470939
5773  20230618    065959  26535.4  ...  51.666667  0.588342  0.473821
5774  20230618    072959  26555.5  ...  51.666667  0.574214  0.481766

[5 rows x 33 columns]
0.5637707948243993
acc is : 0.5637707948243993
2023-06-18 08:00:18,514:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.498565  0.501435       1  ...  1.078273   1.0    0.0  0.993111
537     0  0.508102  0.491898       1  ...  1.079310   1.0    0.0  0.994066
538     0  0.514055  0.485945       1  ...  1.080124   1.0    0.0  0.994815
539     0  0.509868  0.490132       0  ...  1.077976   1.0    0.0  0.992837
540     1  0.491321  0.508679       1  ...  1.078224   1.0    0.0  0.993066

[5 rows x 10 columns]
2023-06-18 08:00:18,525:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496671  0.503329       1  ...  1.104887   1.0    0.0  1.017611
46     0  0.507152  0.492848       1  ...  1.099716   1.0    0.0  1.012848
47     0  0.513380  0.486620       1  ...  1.093792   1.0    0.0  1.007382
48     0  0.509868  0.490132       0  ...  1.077976   1.0    0.0  0.992837
49     1  0.491321  0.508679       1  ...  1.078224   1.0    0.0  0.993066

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '30621.8649', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26512.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230618   075000    075959  1687046399  26521.9  26508.9 -0.000490
2023-06-18 08:00:02,272:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5024 

self.closeSec=1687046999, self.tradeDate='20230618', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26508.8', self.close='26511.6'
2023-06-18 08:10:01,103:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687046999, self.tradeDate='20230618', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26508.8', self.close='26511.6'
2023-06-18 08:10:01,121:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230618   072000    072959  1687044599  26531.2  26502.7 -0.001082
621  20230618   073000    073959  1687045199  26502.6  26507.8  0.000192
622  20230618   074000    074959  1687045799  26507.8  26521.9  0.000532
623  20230618   075000    075959  1687046399  26521.9  26508.9 -0.000490
624  20230618   080000    080959  1687046999  26508.8  26511.6  0.000102
2023-06-18 08:10:01,123:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5025 

self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26511.6', self.close='26514.1'
127.0.0.1 - - [18/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 08:20:07,563:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26511.6', self.close='26514.1'
2023-06-18 08:20:08,413:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230618   073000    073959  1687045199  26502.6  26507.8  0.000192
622  20230618   074000    074959  1687045799  26507.8  26521.9  0.000532
623  20230618   075000    075959  1687046399  26521.9  26508.9 -0.000490
624  20230618   080000    080959  1687046999  26508.8  26511.6  0.000102
625  20230618   081000    081959  1687047599  26511.6  26514.1  0.000094
2023-06-18 08:20:08,422:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230618   075000    075959  1687046399  26521.9  26508.9
2023-06-18 08:00:02,300:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5027 

self.closeSec=1687046999, self.tradeDate='20230618', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26508.8', self.close='26511.6'
2023-06-18 08:10:01,116:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687046999, self.tradeDate='20230618', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26508.8', self.close='26511.6'
127.0.0.1 - - [18/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-18 08:10:01,128:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230618   072000    072959  1687044599  26531.2  26502.7
17469  20230618   073000    073959  1687045199  26502.6  26507.8
17470  20230618   074000    074959  1687045799  26507.8  26521.9
17471  20230618   075000    075959  1687046399  26521.9  26508.9
17472  20230618   080000    080959  1687046999  26508.8  26511.6
2023-06-18 08:10:01,128:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5028 

self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26511.6', self.close='26514.1'
127.0.0.1 - - [18/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 08:20:09,753:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26511.6', self.close='26514.1'
2023-06-18 08:20:09,895:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230618   073000    073959  1687045199  26502.6  26507.8
17470  20230618   074000    074959  1687045799  26507.8  26521.9
17471  20230618   075000    075959  1687046399  26521.9  26508.9
17472  20230618   080000    080959  1687046999  26508.8  26511.6
17473  20230618   081000    081959  1687047599  26511.6  26514.1
2023-06-18 08:20:09,895:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230618   075000    075959  1687046399  26521.9  26508.9
2023-06-18 08:00:02,277:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5027 

self.closeSec=1687046999, self.tradeDate='20230618', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26508.8', self.close='26511.6'
2023-06-18 08:10:01,112:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687046999, self.tradeDate='20230618', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26508.8', self.close='26511.6'
127.0.0.1 - - [18/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-18 08:10:01,137:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230618   072000    072959  1687044599  26531.2  26502.7
12141  20230618   073000    073959  1687045199  26502.6  26507.8
12142  20230618   074000    074959  1687045799  26507.8  26521.9
12143  20230618   075000    075959  1687046399  26521.9  26508.9
12144  20230618   080000    080959  1687046999  26508.8  26511.6
2023-06-18 08:10:01,137:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5028 

self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26511.6', self.close='26514.1'
127.0.0.1 - - [18/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-18 08:20:09,307:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26511.6', self.close='26514.1'
2023-06-18 08:20:09,664:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230618   073000    073959  1687045199  26502.6  26507.8
12142  20230618   074000    074959  1687045799  26507.8  26521.9
12143  20230618   075000    075959  1687046399  26521.9  26508.9
12144  20230618   080000    080959  1687046999  26508.8  26511.6
12145  20230618   081000    081959  1687047599  26511.6  26514.1
2023-06-18 08:20:09,666:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10048
self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26520.1, self.close=26514.1, self.high=26520.1, self.low=26460.2, self.vol=1138.172, self.amt=30150625.2178 
127.0.0.1 - - [18/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-18 08:20:07,774:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230618   075500    075959  ...         0.0        0.0       0
5856  20230618   080000    080459  ...         0.0        0.0       0
5857  20230618   080500    080959  ...         0.0        0.0       0
5858  20230618   081000    081459  ...         0.0        0.0       0
5859  20230618   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 08:20:07,813:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687047599, self.tradeDate='20230618', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26520.1, self.close=26514.1, self.high=26520.1, self.low=26460.2, self.vol=1138.172, self.amt=30150625.2178, ukdf['pct'].iloc[-1]=-0.000189 , ukdf['amount'].iloc[-1]=30150625.2178, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12310.2458175034', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26512.5537326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10049
self.closeSec=1687047899, self.tradeDate='20230618', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26514.1, self.close=26435.3, self.high=26514.1, self.low=26415.2, self.vol=2624.898, self.amt=69414653.9782 
2023-06-18 08:25:00,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230618   080000    080459  ...         0.0        0.0       0
5857  20230618   080500    080959  ...         0.0        0.0       0
5858  20230618   081000    081459  ...         0.0        0.0       0
5859  20230618   081500    081959  ...         0.0        0.0       0
5860  20230618   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-18 08:25:00,786:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687047899, self.tradeDate='20230618', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26514.1, self.close=26435.3, self.high=26514.1, self.low=26415.2, self.vol=2624.898, self.amt=69414653.9782, ukdf['pct'].iloc[-1]=-0.002972 , ukdf['amount'].iloc[-1]=69414653.9782, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-15083.81774437278', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26437.87690842', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230617   200000    235959  1687017599  ...    719  0.560629  0.902073     1.0
720  20230618   000000    035959  1687031999  ...    720  0.563406  0.926846     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-6106.29', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26483.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [18/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=209
self.closeSec=1687046399, self.tradeDate='20230618', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26466.1, self.close=26508.9, self.high=26590.0, self.low=26452.2, self.vol=21650.496, self.amt=574162499.9434 
2023-06-18 08:00:01,814:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687046399, self.tradeDate='20230618', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26466.1, self.close=26508.9, self.high=26590.0, self.low=26452.2, self.vol=21650.496, self.amt=574162499.9434 
2023-06-18 08:00:01,834:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230617   120000    155959  ...  107938.264  2.873805e+09  0.012730
718  20230617   160000    195959  ...   43152.994  1.146774e+09 -0.003389
719  20230617   200000    235959  ...   64566.845  1.708797e+09 -0.003683
720  20230618   000000    035959  ...   31768.742  8.405475e+08  0.002511
721  20230618   040000    075959  ...   21650.496  5.741625e+08  0.001613

[5 rows x 11 columns]
2023-06-18 08:00:03,127:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230617   120000    155959  1686988799  ...    717  0.515413  0.637007     1.0
718  20230617   160000    195959  1687003199  ...    718  0.541351  0.787352     1.0
719  20230617   200000    235959  1687017599  ...    719  0.560629  0.902073     1.0
720  20230618   000000    035959  1687031999  ...    720  0.563406  0.926846     1.0
721  20230618   040000    075959  1687046399  ...    721  0.565101  0.945628     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-4636.8925', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26508.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


