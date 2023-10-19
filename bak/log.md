# 20231019 08:26:08

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45460
self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28316.2, self.close=28297.4, self.high=28316.2, self.low=28291.2, self.vol=390.254, self.amt=11045065.4434 
127.0.0.1 - - [19/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
2023-10-19 08:20:17,476:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231019   075500    075959  ...         0.0        0.0       0
5856  20231019   080000    080459  ...         0.0        0.0       0
5857  20231019   080500    080959  ...         0.0        0.0       0
5858  20231019   081000    081459  ...         0.0        0.0       0
5859  20231019   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 08:20:17,784:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28316.2, self.close=28297.4, self.high=28316.2, self.low=28291.2, self.vol=390.254, self.amt=11045065.4434, ukdf['pct'].iloc[-1]=-0.000738 , ukdf['amount'].iloc[-1]=11045065.4434, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-19950.3876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28297.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45461
self.closeSec=1697675099, self.tradeDate='20231019', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28297.4, self.close=28329.7, self.high=28333.4, self.low=28297.4, self.vol=274.286, self.amt=7767228.0064 
127.0.0.1 - - [19/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-19 08:25:03,317:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231019   080000    080459  ...         0.0        0.0       0
5857  20231019   080500    080959  ...         0.0        0.0       0
5858  20231019   081000    081459  ...         0.0        0.0       0
5859  20231019   081500    081959  ...         0.0        0.0       0
5860  20231019   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 08:25:03,318:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697675099, self.tradeDate='20231019', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28297.4, self.close=28329.7, self.high=28333.4, self.low=28297.4, self.vol=274.286, self.amt=7767228.0064, ukdf['pct'].iloc[-1]=0.001141 , ukdf['amount'].iloc[-1]=7767228.0064, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-20440.29160371924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28332.67908974', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [19/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45458 

self.closeSec=1697673599, self.tradeDate='20231019', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28309.6, self.close=28307.1, self.high=28309.7, self.low=28304.5 
127.0.0.1 - - [19/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45459 

self.closeSec=1697673899, self.tradeDate='20231019', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28307.2, self.close=28289.9, self.high=28307.2, self.low=28273.9 
127.0.0.1 - - [19/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45460 

self.closeSec=1697674199, self.tradeDate='20231019', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28290.0, self.close=28308.2, self.high=28313.9, self.low=28289.9 

--handleKline--: 127.0.0.1 - - [19/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45461 

self.closeSec=1697674499, self.tradeDate='20231019', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28308.2, self.close=28318.3, self.high=28320.5, self.low=28305.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45462 

self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28316.2, self.close=28297.4, self.high=28316.2, self.low=28291.2 
127.0.0.1 - - [19/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45463 

self.closeSec=1697675099, self.tradeDate='20231019', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28297.4, self.close=28329.7, self.high=28333.4, self.low=28297.4 
127.0.0.1 - - [19/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-19 08:00:18,954:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231019    052959  28236.9  ...  51.666667  0.501214  0.774317
5770  20231019    055959  28261.5  ...  51.250000  0.499684  0.780706
5771  20231019    062959  28252.9  ...  51.666667  0.507353  0.783723
5772  20231019    065959  28296.1  ...  52.083333  0.513354  0.784218
5773  20231019    072959  28329.9  ...  52.083333  0.511311  0.785426

[5 rows x 33 columns]
0.5703703703703704
acc is : 0.5703703703703704
2023-10-19 08:00:19,037:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.504591  0.495409       0  ...  0.944128  -1.0    0.0  1.011963
536     1  0.496295  0.503705       1  ...  0.942691  -1.0    0.0  1.013503
537     0  0.515329  0.484671       1  ...  0.941562  -1.0    0.0  1.014718
538     0  0.512939  0.487061       0  ...  0.941924  -1.0    0.0  1.014327
539     0  0.503092  0.496908       0  ...  0.942320  -1.0    0.0  1.013901

[5 rows x 10 columns]
2023-10-19 08:00:19,050:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504930  0.495070       0  ...  0.944128  -1.0    0.0  1.011695
46     1  0.496187  0.503813       1  ...  0.942691  -1.0    0.0  1.012771
47     0  0.515558  0.484442       1  ...  0.941562  -1.0    0.0  1.014431
48     0  0.513017  0.486983       0  ...  0.941924  -1.0    0.0  1.014389
49     0  0.503092  0.496908       0  ...  0.942320  -1.0    0.0  1.013901

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.922', 'enterprice': '28335.6', 'countrevence': '0', 'unrealprofit': '710.2728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28303.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22727 

self.closeSec=1697671799, self.tradeDate='20231019', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28293.8', self.close='28319'

--handleKline--: 127.0.0.1 - - [19/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22728 

self.closeSec=1697672399, self.tradeDate='20231019', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28321.5', self.close='28293.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22729 

self.closeSec=1697672999, self.tradeDate='20231019', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28293.2', self.close='28303.6'
127.0.0.1 - - [19/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22730 

self.closeSec=1697673599, self.tradeDate='20231019', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28303.5', self.close='28307.2'
127.0.0.1 - - [19/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22731 

self.closeSec=1697674199, self.tradeDate='20231019', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28307.2', self.close='28308.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22732 

self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28308.2', self.close='28297.4'
127.0.0.1 - - [19/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22730 

self.closeSec=1697671799, self.tradeDate='20231019', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28293.8', self.close='28319'
127.0.0.1 - - [19/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [19/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22731 

self.closeSec=1697672399, self.tradeDate='20231019', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28321.5', self.close='28293.1'
127.0.0.1 - - [19/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22732 

self.closeSec=1697672999, self.tradeDate='20231019', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28293.2', self.close='28303.6'
127.0.0.1 - - [19/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22733 

self.closeSec=1697673599, self.tradeDate='20231019', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28303.5', self.close='28307.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22734 

self.closeSec=1697674199, self.tradeDate='20231019', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28307.2', self.close='28308.2'
127.0.0.1 - - [19/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22735 

self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28308.2', self.close='28297.4'
127.0.0.1 - - [19/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22730 

self.closeSec=1697671799, self.tradeDate='20231019', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28293.8', self.close='28319'
127.0.0.1 - - [19/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22731 

self.closeSec=1697672399, self.tradeDate='20231019', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28321.5', self.close='28293.1'
127.0.0.1 - - [19/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22732 

self.closeSec=1697672999, self.tradeDate='20231019', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28293.2', self.close='28303.6'
127.0.0.1 - - [19/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22733 

self.closeSec=1697673599, self.tradeDate='20231019', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28303.5', self.close='28307.2'
127.0.0.1 - - [19/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22734 

self.closeSec=1697674199, self.tradeDate='20231019', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28307.2', self.close='28308.2'
127.0.0.1 - - [19/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22735 

self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28308.2', self.close='28297.4'
127.0.0.1 - - [19/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45460
self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28316.2, self.close=28297.4, self.high=28316.2, self.low=28291.2, self.vol=390.254, self.amt=11045065.4434 
127.0.0.1 - - [19/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
2023-10-19 08:20:17,474:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231019   075500    075959  ...         0.0        0.0       0
5856  20231019   080000    080459  ...         0.0        0.0       0
5857  20231019   080500    080959  ...         0.0        0.0       0
5858  20231019   081000    081459  ...         0.0        0.0       0
5859  20231019   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 08:20:17,704:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697674799, self.tradeDate='20231019', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28316.2, self.close=28297.4, self.high=28316.2, self.low=28291.2, self.vol=390.254, self.amt=11045065.4434, ukdf['pct'].iloc[-1]=-0.000738 , ukdf['amount'].iloc[-1]=11045065.4434, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '53984.4435', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28297.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45461
self.closeSec=1697675099, self.tradeDate='20231019', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28297.4, self.close=28329.7, self.high=28333.4, self.low=28297.4, self.vol=274.286, self.amt=7767228.0064 
127.0.0.1 - - [19/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-19 08:25:03,316:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231019   080000    080459  ...         0.0        0.0       0
5857  20231019   080500    080959  ...         0.0        0.0       0
5858  20231019   081000    081459  ...         0.0        0.0       0
5859  20231019   081500    081959  ...         0.0        0.0       0
5860  20231019   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 08:25:03,318:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697675099, self.tradeDate='20231019', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28297.4, self.close=28329.7, self.high=28333.4, self.low=28297.4, self.vol=274.286, self.amt=7767228.0064, ukdf['pct'].iloc[-1]=0.001141 , ukdf['amount'].iloc[-1]=7767228.0064, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '55291.03007203334', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28332.67908974', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231018   200000    235959  1697644799  ...    719  0.859830  0.301681     NaN
720  20231019   000000    035959  1697659199  ...    720  0.785640  0.190189     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '17802.7584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28247.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=947
self.closeSec=1697673599, self.tradeDate='20231019', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28233.2, self.close=28307.2, self.high=28363.1, self.low=28169.4, self.vol=20335.057, self.amt=574801057.899 
127.0.0.1 - - [19/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-19 08:00:01,529:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697673599, self.tradeDate='20231019', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28233.2, self.close=28307.2, self.high=28363.1, self.low=28169.4, self.vol=20335.057, self.amt=574801057.899 
2023-10-19 08:00:01,545:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231018   120000    155959  ...  98876.718  2.836423e+09 -0.000481
718  20231018   160000    195959  ...  56062.116  1.592322e+09 -0.005543
719  20231018   200000    235959  ...  58144.088  1.643344e+09 -0.003248
720  20231019   000000    035959  ...  37844.621  1.071876e+09 -0.000071
721  20231019   040000    075959  ...  20335.057  5.748011e+08  0.002617

[5 rows x 11 columns]
2023-10-19 08:00:02,374:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231018   120000    155959  1697615999  ...    717  0.968668  0.467607     NaN
718  20231018   160000    195959  1697630399  ...    718  0.924896  0.401351     NaN
719  20231018   200000    235959  1697644799  ...    719  0.859830  0.301681     NaN
720  20231019   000000    035959  1697659199  ...    720  0.785640  0.190189     NaN
721  20231019   040000    075959  1697673599  ...    721  0.709252  0.075467     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '20422.3572', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28307.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


