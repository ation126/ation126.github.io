# 20230927 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39124
self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26227.1, self.close=26220.7, self.high=26239.7, self.low=26218.8, self.vol=497.932, self.amt=13060517.4694 
127.0.0.1 - - [27/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-27 08:20:06,652:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230927   075500    075959  ...         0.0        0.0       0
5856  20230927   080000    080459  ...         0.0        0.0       0
5857  20230927   080500    080959  ...         0.0        0.0       0
5858  20230927   081000    081459  ...         0.0        0.0       0
5859  20230927   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 08:20:06,654:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26227.1, self.close=26220.7, self.high=26239.7, self.low=26218.8, self.vol=497.932, self.amt=13060517.4694, ukdf['pct'].iloc[-1]=-0.000244 , ukdf['amount'].iloc[-1]=13060517.4694, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8946.64469048394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26222.45818681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=39125
self.closeSec=1695774299, self.tradeDate='20230927', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26220.7, self.close=26220.5, self.high=26221.6, self.low=26213.6, self.vol=389.192, self.amt=10203385.0396 
127.0.0.1 - - [27/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-27 08:25:00,796:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230927   080000    080459  ...         0.0        0.0       0
5857  20230927   080500    080959  ...         0.0        0.0       0
5858  20230927   081000    081459  ...         0.0        0.0       0
5859  20230927   081500    081959  ...         0.0        0.0       0
5860  20230927   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 08:25:00,796:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695774299, self.tradeDate='20230927', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26220.7, self.close=26220.5, self.high=26221.6, self.low=26213.6, self.vol=389.192, self.amt=10203385.0396, ukdf['pct'].iloc[-1]=-8e-06 , ukdf['amount'].iloc[-1]=10203385.0396, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8973.9144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26220.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39122 

self.closeSec=1695772799, self.tradeDate='20230927', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26205.3, self.close=26208.8, self.high=26215.0, self.low=26195.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39123 

self.closeSec=1695773099, self.tradeDate='20230927', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26208.7, self.close=26226.6, self.high=26226.7, self.low=26201.8 
127.0.0.1 - - [27/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39124 

self.closeSec=1695773399, self.tradeDate='20230927', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26226.8, self.close=26248.6, self.high=26249.6, self.low=26223.4 
127.0.0.1 - - [27/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39125 

self.closeSec=1695773699, self.tradeDate='20230927', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26248.5, self.close=26227.1, self.high=26250.0, self.low=26210.8 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39126 

self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26227.1, self.close=26220.7, self.high=26239.7, self.low=26218.8 
127.0.0.1 - - [27/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=39127 

self.closeSec=1695774299, self.tradeDate='20230927', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26220.7, self.close=26220.5, self.high=26221.6, self.low=26213.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-27 08:00:19,257:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230927    052959  26153.5  ...  46.250000  0.452967  0.646044
5770  20230927    055959  26138.6  ...  46.250000  0.459913  0.652030
5771  20230927    062959  26156.8  ...  46.666667  0.470432  0.651698
5772  20230927    065959  26184.8  ...  46.250000  0.457526  0.659789
5773  20230927    072959  26145.1  ...  46.666667  0.466205  0.662462

[5 rows x 33 columns]
0.5333333333333333
acc is : 0.5333333333333333
2023-09-27 08:00:19,336:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.487146  0.512854       1  ...  0.978115  -1.0    0.0  0.993705
536     1  0.494317  0.505683       1  ...  0.977072  -1.0    0.0  0.994765
537     1  0.495814  0.504186       0  ...  0.978550  -1.0    0.0  0.993261
538     1  0.474601  0.525399       1  ...  0.977689  -1.0    0.0  0.994134
539     1  0.498717  0.501283       1  ...  0.976168  -1.0    0.0  0.995681

[5 rows x 10 columns]
2023-09-27 08:00:19,348:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487229  0.512771       1  ...  0.978115  -1.0    0.0  0.994136
46     1  0.494178  0.505822       1  ...  0.977072  -1.0    0.0  0.993919
47     1  0.495414  0.504586       0  ...  0.978550  -1.0    0.0  0.991554
48     1  0.474406  0.525594       1  ...  0.977689  -1.0    0.0  0.993983
49     1  0.498717  0.501283       1  ...  0.976168  -1.0    0.0  0.995681

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '23677.5794144501', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26209.01669597', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19559 

self.closeSec=1695770999, self.tradeDate='20230927', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26170.1', self.close='26168.1'
127.0.0.1 - - [27/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19560 

self.closeSec=1695771599, self.tradeDate='20230927', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26168.1', self.close='26206.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19561 

self.closeSec=1695772199, self.tradeDate='20230927', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26200.6', self.close='26207.3'
127.0.0.1 - - [27/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19562 

self.closeSec=1695772799, self.tradeDate='20230927', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26207.4', self.close='26208.8'
127.0.0.1 - - [27/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19563 

self.closeSec=1695773399, self.tradeDate='20230927', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26208.7', self.close='26248.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19564 

self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26248.5', self.close='26220.7'
127.0.0.1 - - [27/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19562 

self.closeSec=1695770999, self.tradeDate='20230927', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26170.1', self.close='26168.1'
127.0.0.1 - - [27/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19563 

self.closeSec=1695771599, self.tradeDate='20230927', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26168.1', self.close='26206.2'
127.0.0.1 - - [27/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19564 

self.closeSec=1695772199, self.tradeDate='20230927', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26200.6', self.close='26207.3'
127.0.0.1 - - [27/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19565 

self.closeSec=1695772799, self.tradeDate='20230927', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26207.4', self.close='26208.8'
127.0.0.1 - - [27/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19566 

self.closeSec=1695773399, self.tradeDate='20230927', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26208.7', self.close='26248.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19567 

self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26248.5', self.close='26220.7'
127.0.0.1 - - [27/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19562 

self.closeSec=1695770999, self.tradeDate='20230927', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26170.1', self.close='26168.1'
127.0.0.1 - - [27/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19563 

self.closeSec=1695771599, self.tradeDate='20230927', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26168.1', self.close='26206.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19564 

self.closeSec=1695772199, self.tradeDate='20230927', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26200.6', self.close='26207.3'
127.0.0.1 - - [27/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19565 

self.closeSec=1695772799, self.tradeDate='20230927', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26207.4', self.close='26208.8'
127.0.0.1 - - [27/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19566 

self.closeSec=1695773399, self.tradeDate='20230927', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26208.7', self.close='26248.6'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19567 

self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26248.5', self.close='26220.7'
127.0.0.1 - - [27/Sep/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39124
self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26227.1, self.close=26220.7, self.high=26239.7, self.low=26218.8, self.vol=497.932, self.amt=13060517.4694 
127.0.0.1 - - [27/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-27 08:20:06,652:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230927   075500    075959  ...         0.0        0.0       0
5856  20230927   080000    080459  ...         0.0        0.0       0
5857  20230927   080500    080959  ...         0.0        0.0       0
5858  20230927   081000    081459  ...         0.0        0.0       0
5859  20230927   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 08:20:06,654:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695773999, self.tradeDate='20230927', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26227.1, self.close=26220.7, self.high=26239.7, self.low=26218.8, self.vol=497.932, self.amt=13060517.4694, ukdf['pct'].iloc[-1]=-0.000244 , ukdf['amount'].iloc[-1]=13060517.4694, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-23084.68448368979', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26222.45818681', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=39125
self.closeSec=1695774299, self.tradeDate='20230927', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26220.7, self.close=26220.5, self.high=26221.6, self.low=26213.6, self.vol=389.192, self.amt=10203385.0396 
127.0.0.1 - - [27/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-27 08:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230927   080000    080459  ...         0.0        0.0       0
5857  20230927   080500    080959  ...         0.0        0.0       0
5858  20230927   081000    081459  ...         0.0        0.0       0
5859  20230927   081500    081959  ...         0.0        0.0       0
5860  20230927   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-27 08:25:00,802:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695774299, self.tradeDate='20230927', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26220.7, self.close=26220.5, self.high=26221.6, self.low=26213.6, self.vol=389.192, self.amt=10203385.0396, ukdf['pct'].iloc[-1]=-8e-06 , ukdf['amount'].iloc[-1]=10203385.0396, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-23157.4135', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26220.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230926   200000    235959  1695743999  ...    719  0.266004 -0.852583    -1.0
720  20230927   000000    035959  1695758399  ...    720  0.264997 -0.857729    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-4613.21525700072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26239.79004762', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1325886.3548316, self.flagDict['side']='sell', self.tradeCount=26, self.count=815
self.closeSec=1695772799, self.tradeDate='20230927', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26235.8, self.close=26208.8, self.high=26280.9, self.low=26080.0, self.vol=23705.843, self.amt=620686853.4948 
127.0.0.1 - - [27/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-27 08:00:01,590:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695772799, self.tradeDate='20230927', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26235.8, self.close=26208.8, self.high=26280.9, self.low=26080.0, self.vol=23705.843, self.amt=620686853.4948 
2023-09-27 08:00:01,607:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230926   120000    155959  ...  15913.957  4.184392e+08 -0.003132
718  20230926   160000    195959  ...  29876.724  7.839168e+08  0.000232
719  20230926   200000    235959  ...  54593.775  1.429196e+09 -0.005620
720  20230927   000000    035959  ...  36140.137  9.469580e+08  0.004633
721  20230927   040000    075959  ...  23705.843  6.206869e+08 -0.001029

[5 rows x 11 columns]
2023-09-27 08:00:02,357:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230926   120000    155959  1695715199  ...    717  0.269543 -0.835454    -1.0
718  20230926   160000    195959  1695729599  ...    718  0.271739 -0.829211    -1.0
719  20230926   200000    235959  1695743999  ...    719  0.266004 -0.852583    -1.0
720  20230927   000000    035959  1695758399  ...    720  0.264997 -0.857729    -1.0
721  20230927   040000    075959  1695772799  ...    721  0.268882 -0.846173    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.756', 'enterprice': '26148.9', 'countrevence': '0', 'unrealprofit': '-3116.64615130808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26210.30448718', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


