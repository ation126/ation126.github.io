# 20230818 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27604
self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26766.6, self.close=26745.0, self.high=26791.5, self.low=26703.6, self.vol=2522.752, self.amt=67490038.3283 
127.0.0.1 - - [18/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-18 08:20:04,474:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230818   075500    075959  ...         0.0        0.0       0
5844  20230818   080000    080459  ...         0.0        0.0       0
5845  20230818   080500    080959  ...         0.0        0.0       0
5846  20230818   081000    081459  ...         0.0        0.0       0
5847  20230818   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 08:20:04,476:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26766.6, self.close=26745.0, self.high=26791.5, self.low=26703.6, self.vol=2522.752, self.amt=67490038.3283, ukdf['pct'].iloc[-1]=-0.000837 , ukdf['amount'].iloc[-1]=67490038.3283, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1703.1498', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26742.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27605
self.closeSec=1692318299, self.tradeDate='20230818', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26745.0, self.close=26717.6, self.high=26780.0, self.low=26717.6, self.vol=2084.147, self.amt=55750862.0793 
2023-08-18 08:25:00,755:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230818   080000    080459  ...         0.0        0.0       0
5845  20230818   080500    080959  ...         0.0        0.0       0
5846  20230818   081000    081459  ...         0.0        0.0       0
5847  20230818   081500    081959  ...         0.0        0.0       0
5848  20230818   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 08:25:00,755:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692318299, self.tradeDate='20230818', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26745.0, self.close=26717.6, self.high=26780.0, self.low=26717.6, self.vol=2084.147, self.amt=55750862.0793, ukdf['pct'].iloc[-1]=-0.001024 , ukdf['amount'].iloc[-1]=55750862.0793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1997.14431507822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26721.48880403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27602 

self.closeSec=1692316799, self.tradeDate='20230818', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26593.9, self.close=26607.8, self.high=26658.0, self.low=26590.0 
127.0.0.1 - - [18/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27603 

self.closeSec=1692317099, self.tradeDate='20230818', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26609.7, self.close=26652.1, self.high=26652.1, self.low=26579.2 
127.0.0.1 - - [18/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27604 

self.closeSec=1692317399, self.tradeDate='20230818', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26652.6, self.close=26753.9, self.high=26806.5, self.low=26650.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27605 

self.closeSec=1692317699, self.tradeDate='20230818', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26752.0, self.close=26767.4, self.high=26818.0, self.low=26688.0 
127.0.0.1 - - [18/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27606 

self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26766.6, self.close=26745.0, self.high=26791.5, self.low=26703.6 
127.0.0.1 - - [18/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=27607 

self.closeSec=1692318299, self.tradeDate='20230818', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26745.0, self.close=26717.6, self.high=26780.0, self.low=26717.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-18 08:00:16,350:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230818    052959  27663.5  ...  45.000000  0.275061  0.797761
5770  20230818    055959  27660.0  ...  45.000000  0.168915  0.784310
5771  20230818    062959  26250.0  ...  45.000000  0.218472  0.768059
5772  20230818    065959  26457.2  ...  45.000000  0.280267  0.747672
5773  20230818    072959  26790.0  ...  44.583333  0.268920  0.731374

[5 rows x 33 columns]
0.5407407407407407
acc is : 0.5407407407407407
2023-08-18 08:00:16,409:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.458552  0.541448       0  ...  1.104533  -1.0    0.0  0.903283
536     1  0.062783  0.937217       1  ...  1.094928  -1.0    0.0  0.911138
537     1  0.440937  0.559063       1  ...  1.081609  -1.0    0.0  0.922221
538     0  0.508849  0.491151       0  ...  1.088407  -1.0    0.0  0.916425
539     1  0.328587  0.671413       0  ...  1.089024  -1.0    0.0  0.915905

[5 rows x 10 columns]
2023-08-18 08:00:16,420:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.458594  0.541406       0  ...  1.104533  -1.0    0.0  0.904077
46     1  0.062842  0.937158       1  ...  1.094928  -1.0    0.0  0.912769
47     1  0.440981  0.559019       1  ...  1.081609  -1.0    0.0  0.923251
48     0  0.508605  0.491395       0  ...  1.088407  -1.0    0.0  0.915618
49     1  0.328587  0.671413       0  ...  1.089024  -1.0    0.0  0.915905

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.207', 'enterprice': '29084.9', 'countrevence': '0', 'unrealprofit': '59990.90677428432', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26606.65375824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13799 

self.closeSec=1692314999, self.tradeDate='20230818', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26795.9', self.close='26624.8'
127.0.0.1 - - [18/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13800 

self.closeSec=1692315599, self.tradeDate='20230818', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26627.6', self.close='26584.7'
127.0.0.1 - - [18/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13801 

self.closeSec=1692316199, self.tradeDate='20230818', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26584.7', self.close='26635.8'
127.0.0.1 - - [18/Aug/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13802 

self.closeSec=1692316799, self.tradeDate='20230818', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26631.7', self.close='26609.7'
127.0.0.1 - - [18/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13803 

self.closeSec=1692317399, self.tradeDate='20230818', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26609.7', self.close='26753.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13804 

self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26752', self.close='26745'
127.0.0.1 - - [18/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13802 

self.closeSec=1692314999, self.tradeDate='20230818', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26795.9', self.close='26624.8'
127.0.0.1 - - [18/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13803 

self.closeSec=1692315599, self.tradeDate='20230818', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26627.6', self.close='26584.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13804 

self.closeSec=1692316199, self.tradeDate='20230818', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26584.7', self.close='26635.8'
127.0.0.1 - - [18/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13805 

self.closeSec=1692316799, self.tradeDate='20230818', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26631.7', self.close='26609.7'
127.0.0.1 - - [18/Aug/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13806 

self.closeSec=1692317399, self.tradeDate='20230818', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26609.7', self.close='26753.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13807 

self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26752', self.close='26745'
127.0.0.1 - - [18/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13802 

self.closeSec=1692314999, self.tradeDate='20230818', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26795.9', self.close='26624.8'
127.0.0.1 - - [18/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13803 

self.closeSec=1692315599, self.tradeDate='20230818', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26627.6', self.close='26584.7'
127.0.0.1 - - [18/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13804 

self.closeSec=1692316199, self.tradeDate='20230818', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26584.7', self.close='26635.8'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13805 

self.closeSec=1692316799, self.tradeDate='20230818', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26631.7', self.close='26609.7'
127.0.0.1 - - [18/Aug/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [18/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13806 

self.closeSec=1692317399, self.tradeDate='20230818', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26609.7', self.close='26753.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13807 

self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26752', self.close='26745'
127.0.0.1 - - [18/Aug/2023 08:20:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27604
self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26766.6, self.close=26745.0, self.high=26791.5, self.low=26703.6, self.vol=2522.752, self.amt=67490038.3283 
127.0.0.1 - - [18/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-18 08:20:04,464:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230818   075500    075959  ...         0.0        0.0       0
5844  20230818   080000    080459  ...         0.0        0.0       0
5845  20230818   080500    080959  ...         0.0        0.0       0
5846  20230818   081000    081459  ...         0.0        0.0       0
5847  20230818   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 08:20:04,466:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692317999, self.tradeDate='20230818', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26766.6, self.close=26745.0, self.high=26791.5, self.low=26703.6, self.vol=2522.752, self.amt=67490038.3283, ukdf['pct'].iloc[-1]=-0.000837 , ukdf['amount'].iloc[-1]=67490038.3283, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-3758.6692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26742.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [18/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27605
self.closeSec=1692318299, self.tradeDate='20230818', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26745.0, self.close=26717.6, self.high=26780.0, self.low=26717.6, self.vol=2084.147, self.amt=55750862.0793 
2023-08-18 08:25:00,762:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230818   080000    080459  ...         0.0        0.0       0
5845  20230818   080500    080959  ...         0.0        0.0       0
5846  20230818   081000    081459  ...         0.0        0.0       0
5847  20230818   081500    081959  ...         0.0        0.0       0
5848  20230818   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-18 08:25:00,763:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692318299, self.tradeDate='20230818', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26745.0, self.close=26717.6, self.high=26780.0, self.low=26717.6, self.vol=2084.147, self.amt=55750862.0793, ukdf['pct'].iloc[-1]=-0.001024 , ukdf['amount'].iloc[-1]=55750862.0793, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-4550.18832952177', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26721.48880403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230817   200000    235959  1692287999  ...    719  0.423048 -0.179032     NaN
720  20230818   000000    035959  1692302399  ...    720  0.534098  0.066503     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '79276.2676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27889.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [18/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=575
self.closeSec=1692316799, self.tradeDate='20230818', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27889.4, self.close=26609.7, self.high=27915.8, self.low=24581.0, self.vol=384716.301, self.amt=10216747200.27413 
2023-08-18 08:00:01,614:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692316799, self.tradeDate='20230818', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27889.4, self.close=26609.7, self.high=27915.8, self.low=24581.0, self.vol=384716.301, self.amt=10216747200.27413 
2023-08-18 08:00:01,632:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230817   120000    155959  ...   27424.778  7.854386e+08 -0.001061
718  20230817   160000    195959  ...   39605.705  1.130810e+09 -0.002555
719  20230817   200000    235959  ...  182531.640  5.157597e+09 -0.021538
720  20230818   000000    035959  ...  133611.979  3.727531e+09 -0.001286
721  20230818   040000    075959  ...  384716.301  1.021675e+10 -0.045885

[5 rows x 11 columns]
2023-08-18 08:00:02,445:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230817   120000    155959  1692259199  ...    717  0.389168 -0.246678     NaN
718  20230817   160000    195959  1692273599  ...    718  0.502190  0.003736     NaN
719  20230817   200000    235959  1692287999  ...    719  0.423048 -0.179032     NaN
720  20230818   000000    035959  1692302399  ...    720  0.534098  0.066503     NaN
721  20230818   040000    075959  1692316799  ...    721  0.117928 -0.871146    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '145063.1852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26609.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


