# 20230508 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46581
self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28542.2, self.close=28598.5, self.high=28624.6, self.low=28481.8, self.vol=6159.343, self.amt=175873581.0925 
127.0.0.1 - - [08/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-08 08:20:06,672:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230508   075500    075959  ...         0.0        0.0       0
5856  20230508   080000    080459  ...         0.0        0.0       0
5857  20230508   080500    080959  ...         0.0        0.0       0
5858  20230508   081000    081459  ...         0.0        0.0       0
5859  20230508   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 08:20:06,677:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28542.2, self.close=28598.5, self.high=28624.6, self.low=28481.8, self.vol=6159.343, self.amt=175873581.0925, ukdf['pct'].iloc[-1]=0.001973 , ukdf['amount'].iloc[-1]=175873581.0925, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-726468.7424', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28601.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=46582
self.closeSec=1683505499, self.tradeDate='20230508', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28598.6, self.close=28580.2, self.high=28601.8, self.low=28524.2, self.vol=2269.288, self.amt=64805742.8912 
127.0.0.1 - - [08/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-05-08 08:25:01,730:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230508   080000    080459  ...         0.0        0.0       0
5857  20230508   080500    080959  ...         0.0        0.0       0
5858  20230508   081000    081459  ...         0.0        0.0       0
5859  20230508   081500    081959  ...         0.0        0.0       0
5860  20230508   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 08:25:01,730:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683505499, self.tradeDate='20230508', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28598.6, self.close=28580.2, self.high=28601.8, self.low=28524.2, self.vol=2269.288, self.amt=64805742.8912, ukdf['pct'].iloc[-1]=-0.00064 , ukdf['amount'].iloc[-1]=64805742.8912, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-725168.9408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28580.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47143 

self.closeSec=1683503999, self.tradeDate='20230508', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28444.7, self.close=28419.4, self.high=28459.8, self.low=28370.0 
127.0.0.1 - - [08/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47144 

self.closeSec=1683504299, self.tradeDate='20230508', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28419.5, self.close=28448.7, self.high=28449.9, self.low=28345.0 
127.0.0.1 - - [08/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47145 

self.closeSec=1683504599, self.tradeDate='20230508', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28448.8, self.close=28468.5, self.high=28501.6, self.low=28405.0 
127.0.0.1 - - [08/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47146 

self.closeSec=1683504899, self.tradeDate='20230508', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28468.6, self.close=28542.2, self.high=28579.0, self.low=28451.2 
127.0.0.1 - - [08/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47147 

self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28542.2, self.close=28598.5, self.high=28624.6, self.low=28481.8 
127.0.0.1 - - [08/May/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47148 

self.closeSec=1683505499, self.tradeDate='20230508', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28598.6, self.close=28580.2, self.high=28601.8, self.low=28524.2 
127.0.0.1 - - [08/May/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-08 08:00:20,103:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230508    052959  28901.6  ...  50.000000  0.491237  0.491267
5770  20230508    055959  28913.6  ...  49.583333  0.457870  0.513985
5771  20230508    062959  28757.9  ...  49.583333  0.465273  0.529967
5772  20230508    065959  28789.0  ...  49.583333  0.452816  0.555192
5773  20230508    072959  28727.5  ...  50.000000  0.453108  0.569357

[5 rows x 33 columns]
0.5555555555555556
acc is : 0.5555555555555556
2023-05-08 08:00:20,208:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.501403  0.498597       0  ...  0.954757  -1.0    0.0  0.967846
536     1  0.459819  0.540181       1  ...  0.953724  -1.0    0.0  0.968893
537     1  0.491581  0.508419       0  ...  0.955758  -1.0    0.0  0.966826
538     1  0.469143  0.530857       1  ...  0.955718  -1.0    0.0  0.966867
539     1  0.482535  0.517465       0  ...  0.966011  -1.0    0.0  0.956454

[5 rows x 10 columns]
2023-05-08 08:00:20,227:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500812  0.499188       0  ...  0.954757  -1.0    0.0  0.964933
46     1  0.459464  0.540536       1  ...  0.953724  -1.0    0.0  0.966116
47     1  0.491104  0.508896       0  ...  0.955758  -1.0    0.0  0.963894
48     1  0.468903  0.531097       1  ...  0.955718  -1.0    0.0  0.964513
49     1  0.482535  0.517465       0  ...  0.966011  -1.0    0.0  0.956454

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23569 

self.closeSec=1683502199, self.tradeDate='20230508', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28730', self.close='28728.8'
127.0.0.1 - - [08/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23570 

self.closeSec=1683502799, self.tradeDate='20230508', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28728.8', self.close='28775.1'

--handleKline--:  127.0.0.1 - - [08/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23571 

self.closeSec=1683503399, self.tradeDate='20230508', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28775', self.close='28559.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23572 

self.closeSec=1683503999, self.tradeDate='20230508', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28559.6', self.close='28419.4'
127.0.0.1 - - [08/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23573 

self.closeSec=1683504599, self.tradeDate='20230508', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28419.5', self.close='28468.5'
127.0.0.1 - - [08/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23574 

self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28468.6', self.close='28598.5'
127.0.0.1 - - [08/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23570 

self.closeSec=1683502199, self.tradeDate='20230508', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28730', self.close='28728.8'
127.0.0.1 - - [08/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23571 

self.closeSec=1683502799, self.tradeDate='20230508', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28728.8', self.close='28775.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23572 

self.closeSec=1683503399, self.tradeDate='20230508', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28775', self.close='28559.6'
127.0.0.1 - - [08/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23573 

self.closeSec=1683503999, self.tradeDate='20230508', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28559.6', self.close='28419.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23574 

self.closeSec=1683504599, self.tradeDate='20230508', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28419.5', self.close='28468.5'
127.0.0.1 - - [08/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23575 

self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28468.6', self.close='28598.5'
127.0.0.1 - - [08/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23570 

self.closeSec=1683502199, self.tradeDate='20230508', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28730', self.close='28728.8'
127.0.0.1 - - [08/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23571 

self.closeSec=1683502799, self.tradeDate='20230508', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28728.8', self.close='28775.1'
127.0.0.1 - - [08/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23572 

self.closeSec=1683503399, self.tradeDate='20230508', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28775', self.close='28559.6'
127.0.0.1 - - [08/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23573 

self.closeSec=1683503999, self.tradeDate='20230508', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28559.6', self.close='28419.4'
127.0.0.1 - - [08/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23574 

self.closeSec=1683504599, self.tradeDate='20230508', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28419.5', self.close='28468.5'
127.0.0.1 - - [08/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23575 

self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28468.6', self.close='28598.5'
127.0.0.1 - - [08/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42579
self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28542.2, self.close=28598.5, self.high=28624.6, self.low=28481.8, self.vol=6159.343, self.amt=175873581.0925 
127.0.0.1 - - [08/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-08 08:20:06,673:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230508   075500    075959  ...         0.0        0.0       0
5856  20230508   080000    080459  ...         0.0        0.0       0
5857  20230508   080500    080959  ...         0.0        0.0       0
5858  20230508   081000    081459  ...         0.0        0.0       0
5859  20230508   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 08:20:06,686:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683505199, self.tradeDate='20230508', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28542.2, self.close=28598.5, self.high=28624.6, self.low=28481.8, self.vol=6159.343, self.amt=175873581.0925, ukdf['pct'].iloc[-1]=0.001973 , ukdf['amount'].iloc[-1]=175873581.0925, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [08/May/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=42580
self.closeSec=1683505499, self.tradeDate='20230508', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28598.6, self.close=28580.2, self.high=28601.8, self.low=28524.2, self.vol=2269.288, self.amt=64805742.8912 
2023-05-08 08:25:01,729:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230508   080000    080459  ...         0.0        0.0       0
5857  20230508   080500    080959  ...         0.0        0.0       0
5858  20230508   081000    081459  ...         0.0        0.0       0
5859  20230508   081500    081959  ...         0.0        0.0       0
5860  20230508   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-08 08:25:01,731:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683505499, self.tradeDate='20230508', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28598.6, self.close=28580.2, self.high=28601.8, self.low=28524.2, self.vol=2269.288, self.amt=64805742.8912, ukdf['pct'].iloc[-1]=-0.00064 , ukdf['amount'].iloc[-1]=64805742.8912, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230507   200000    235959  1683475199  ...    719  0.210014 -1.138046    -1.0
720  20230508   000000    035959  1683489599  ...    720  0.147027 -1.300751    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '20898.76432283598', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28893.96140839', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=982
self.closeSec=1683503999, self.tradeDate='20230508', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28894.0, self.close=28419.4, self.high=28947.7, self.low=28370.0, self.vol=66956.679, self.amt=1920791279.74526 
2023-05-08 08:00:03,159:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683503999, self.tradeDate='20230508', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28894.0, self.close=28419.4, self.high=28947.7, self.low=28370.0, self.vol=66956.679, self.amt=1920791279.74526 
2023-05-08 08:00:03,207:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230507   120000    155959  ...  27761.690  8.013814e+08  0.003512
718  20230507   160000    195959  ...  44539.548  1.283918e+09 -0.002264
719  20230507   200000    235959  ...  58996.190  1.707798e+09  0.003698
720  20230508   000000    035959  ...  46812.975  1.352144e+09 -0.001351
721  20230508   040000    075959  ...  66956.679  1.920791e+09 -0.016426

[5 rows x 11 columns]
2023-05-08 08:00:04,508:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230507   120000    155959  1683446399  ...    717  0.262112 -1.028641    -1.0
718  20230507   160000    195959  1683460799  ...    718  0.233096 -1.092998    -1.0
719  20230507   200000    235959  1683475199  ...    719  0.210014 -1.138046    -1.0
720  20230508   000000    035959  1683489599  ...    720  0.147027 -1.300751    -1.0
721  20230508   040000    075959  1683503999  ...    721  0.129701 -1.323498    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '43344.9604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28413.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


