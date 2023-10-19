# 20231019 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45556
self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28335.4, self.close=28332.3, self.high=28338.0, self.low=28323.3, self.vol=336.14, self.amt=9523276.6402 
127.0.0.1 - - [19/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-10-19 16:20:06,358:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231019   155500    155959  ...         0.0        0.0       0
5952  20231019   160000    160459  ...         0.0        0.0       0
5953  20231019   160500    160959  ...         0.0        0.0       0
5954  20231019   161000    161459  ...         0.0        0.0       0
5955  20231019   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 16:20:06,361:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28335.4, self.close=28332.3, self.high=28338.0, self.low=28323.3, self.vol=336.14, self.amt=9523276.6402, ukdf['pct'].iloc[-1]=-0.000159 , ukdf['amount'].iloc[-1]=9523276.6402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-20386.6075019211', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28328.82413485', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=45557
self.closeSec=1697703899, self.tradeDate='20231019', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28332.4, self.close=28323.0, self.high=28361.0, self.low=28314.8, self.vol=680.094, self.amt=19272457.6968 
127.0.0.1 - - [19/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-19 16:25:03,164:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231019   160000    160459  ...         0.0        0.0       0
5953  20231019   160500    160959  ...         0.0        0.0       0
5954  20231019   161000    161459  ...         0.0        0.0       0
5955  20231019   161500    161959  ...         0.0        0.0       0
5956  20231019   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 16:25:03,167:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697703899, self.tradeDate='20231019', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28332.4, self.close=28323.0, self.high=28361.0, self.low=28314.8, self.vol=680.094, self.amt=19272457.6968, ukdf['pct'].iloc[-1]=-0.000328 , ukdf['amount'].iloc[-1]=19272457.6968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-20306.8932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28323.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [19/Oct/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45554 

self.closeSec=1697702399, self.tradeDate='20231019', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28324.9, self.close=28317.0, self.high=28325.0, self.low=28311.1 
127.0.0.1 - - [19/Oct/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45555 

self.closeSec=1697702699, self.tradeDate='20231019', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28314.9, self.close=28309.8, self.high=28327.2, self.low=28300.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45556 

self.closeSec=1697702999, self.tradeDate='20231019', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28311.6, self.close=28345.3, self.high=28355.9, self.low=28307.6 
127.0.0.1 - - [19/Oct/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45557 

self.closeSec=1697703299, self.tradeDate='20231019', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28344.1, self.close=28336.8, self.high=28366.2, self.low=28329.4 
127.0.0.1 - - [19/Oct/2023 16:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45558 

self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28335.4, self.close=28332.3, self.high=28338.0, self.low=28323.3 
127.0.0.1 - - [19/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=45559 

self.closeSec=1697703899, self.tradeDate='20231019', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28332.4, self.close=28323.0, self.high=28361.0, self.low=28314.8 
127.0.0.1 - - [19/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-19 16:00:17,584:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20231019    132959  28271.7  ...  52.083333  0.512768  0.733522
5786  20231019    135959  28325.0  ...  52.083333  0.507359  0.708608
5787  20231019    142959  28298.5  ...  52.500000  0.507439  0.685279
5788  20231019    145959  28298.8  ...  52.083333  0.502666  0.667918
5789  20231019    152959  28275.7  ...  51.666667  0.496370  0.657549

[5 rows x 33 columns]
0.5719557195571956
acc is : 0.5719557195571956
2023-10-19 16:00:17,668:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.524054  0.475946       0  ...  0.942570  -1.0    0.0  1.012436
538     1  0.498512  0.501488       1  ...  0.942557  -1.0    0.0  1.012450
539     0  0.504486  0.495514       0  ...  0.943323  -1.0    0.0  1.011628
540     1  0.496742  0.503258       0  ...  0.944337  -1.0    0.0  1.010540
541     1  0.490978  0.509022       1  ...  0.941943  -1.0    0.0  1.013102

[5 rows x 10 columns]
2023-10-19 16:00:17,685:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524017  0.475983       0  ...  0.942570  -1.0    0.0  1.012882
46     1  0.498607  0.501393       1  ...  0.942557  -1.0    0.0  1.012932
47     0  0.504476  0.495524       0  ...  0.943323  -1.0    0.0  1.011906
48     1  0.496636  0.503364       0  ...  0.944337  -1.0    0.0  1.010779
49     1  0.490978  0.509022       1  ...  0.941943  -1.0    0.0  1.013102

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '21.922', 'enterprice': '28335.6', 'countrevence': '0', 'unrealprofit': '444.76172671686', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28315.31162637', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22775 

self.closeSec=1697700599, self.tradeDate='20231019', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28235.5', self.close='28245.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22776 

self.closeSec=1697701199, self.tradeDate='20231019', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28245.4', self.close='28299.4'
127.0.0.1 - - [19/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22777 

self.closeSec=1697701799, self.tradeDate='20231019', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28299.4', self.close='28295.2'
127.0.0.1 - - [19/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [19/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22778 

self.closeSec=1697702399, self.tradeDate='20231019', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28297', self.close='28315'
127.0.0.1 - - [19/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22779 

self.closeSec=1697702999, self.tradeDate='20231019', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28314.9', self.close='28345.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22780 

self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28344.1', self.close='28332.3'
127.0.0.1 - - [19/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [19/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22778 

self.closeSec=1697700599, self.tradeDate='20231019', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28235.5', self.close='28245.4'
127.0.0.1 - - [19/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22779 

self.closeSec=1697701199, self.tradeDate='20231019', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28245.4', self.close='28299.4'
127.0.0.1 - - [19/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22780 

self.closeSec=1697701799, self.tradeDate='20231019', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28299.4', self.close='28295.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22781 

self.closeSec=1697702399, self.tradeDate='20231019', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28297', self.close='28315'
127.0.0.1 - - [19/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22782 

self.closeSec=1697702999, self.tradeDate='20231019', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28314.9', self.close='28345.3'
127.0.0.1 - - [19/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22783 

self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28344.1', self.close='28332.3'
127.0.0.1 - - [19/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/Oct/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22778 

self.closeSec=1697700599, self.tradeDate='20231019', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28235.5', self.close='28245.4'
127.0.0.1 - - [19/Oct/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22779 

self.closeSec=1697701199, self.tradeDate='20231019', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28245.4', self.close='28299.4'
127.0.0.1 - - [19/Oct/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22780 

self.closeSec=1697701799, self.tradeDate='20231019', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28299.4', self.close='28295.2'
127.0.0.1 - - [19/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22781 

self.closeSec=1697702399, self.tradeDate='20231019', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28297', self.close='28315'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22782 

self.closeSec=1697702999, self.tradeDate='20231019', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28314.9', self.close='28345.3'
127.0.0.1 - - [19/Oct/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22783 

self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28344.1', self.close='28332.3'
127.0.0.1 - - [19/Oct/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45556
self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28335.4, self.close=28332.3, self.high=28338.0, self.low=28323.3, self.vol=336.14, self.amt=9523276.6402 
127.0.0.1 - - [19/Oct/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-10-19 16:20:06,359:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20231019   155500    155959  ...         0.0        0.0       0
5952  20231019   160000    160459  ...         0.0        0.0       0
5953  20231019   160500    160959  ...         0.0        0.0       0
5954  20231019   161000    161459  ...         0.0        0.0       0
5955  20231019   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 16:20:06,367:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697703599, self.tradeDate='20231019', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28335.4, self.close=28332.3, self.high=28338.0, self.low=28323.3, self.vol=336.14, self.amt=9523276.6402, ukdf['pct'].iloc[-1]=-0.000159 , ukdf['amount'].iloc[-1]=9523276.6402, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '55147.85319246385', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28328.82413485', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=45557
self.closeSec=1697703899, self.tradeDate='20231019', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28332.4, self.close=28323.0, self.high=28361.0, self.low=28314.8, self.vol=680.094, self.amt=19272457.6968 
127.0.0.1 - - [19/Oct/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-10-19 16:25:03,165:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20231019   160000    160459  ...         0.0        0.0       0
5953  20231019   160500    160959  ...         0.0        0.0       0
5954  20231019   161000    161459  ...         0.0        0.0       0
5955  20231019   161500    161959  ...         0.0        0.0       0
5956  20231019   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-19 16:25:03,168:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697703899, self.tradeDate='20231019', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28332.4, self.close=28323.0, self.high=28361.0, self.low=28314.8, self.vol=680.094, self.amt=19272457.6968, ukdf['pct'].iloc[-1]=-0.000328 , ukdf['amount'].iloc[-1]=19272457.6968, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '54931.539', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28323', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20231019   040000    075959  1697673599  ...    721  0.709252  0.075467     NaN
722  20231019   080000    115959  1697687999  ...    722  0.632386 -0.040189     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '17737.0494', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28245.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [19/Oct/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1218378.8669346, self.flagDict['side']='buy', self.tradeCount=35, self.count=949
self.closeSec=1697702399, self.tradeDate='20231019', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28247.1, self.close=28315.0, self.high=28337.0, self.low=28214.6, self.vol=20030.161, self.amt=566472709.48506 
2023-10-19 16:00:01,499:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697702399, self.tradeDate='20231019', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28247.1, self.close=28315.0, self.high=28337.0, self.low=28214.6, self.vol=20030.161, self.amt=566472709.48506 
2023-10-19 16:00:01,526:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20231018   200000    235959  ...  58144.088  1.643344e+09 -0.003248
720  20231019   000000    035959  ...  37844.621  1.071876e+09 -0.000071
721  20231019   040000    075959  ...  20335.057  5.748011e+08  0.002617
722  20231019   080000    115959  ...  37580.898  1.061172e+09 -0.002098
723  20231019   120000    155959  ...  20030.161  5.664727e+08  0.002379

[5 rows x 11 columns]
2023-10-19 16:00:02,331:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20231018   200000    235959  1697644799  ...    719  0.859830  0.301681     NaN
720  20231019   000000    035959  1697659199  ...    720  0.785640  0.190189     NaN
721  20231019   040000    075959  1697673599  ...    721  0.709252  0.075467     NaN
722  20231019   080000    115959  1697687999  ...    722  0.632386 -0.040189     NaN
723  20231019   120000    155959  1697702399  ...    723  0.524652 -0.206264     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.806', 'enterprice': '27840.9', 'countrevence': '0', 'unrealprofit': '20833.0991848287', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28316.47638645', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


