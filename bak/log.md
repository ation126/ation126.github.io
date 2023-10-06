# 20231006 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41716
self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27402.9, self.close=27391.6, self.high=27405.0, self.low=27382.6, self.vol=436.715, self.amt=11962368.7423 
127.0.0.1 - - [06/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-06 08:20:05,804:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231006   075500    075959  ...         0.0        0.0       0
5856  20231006   080000    080459  ...         0.0        0.0       0
5857  20231006   080500    080959  ...         0.0        0.0       0
5858  20231006   081000    081459  ...         0.0        0.0       0
5859  20231006   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 08:20:05,815:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27402.9, self.close=27391.6, self.high=27405.0, self.low=27382.6, self.vol=436.715, self.amt=11962368.7423, ukdf['pct'].iloc[-1]=-0.000412 , ukdf['amount'].iloc[-1]=11962368.7423, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7336.2168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27391.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41717
self.closeSec=1696551899, self.tradeDate='20231006', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27391.7, self.close=27420.0, self.high=27420.0, self.low=27386.0, self.vol=465.165, self.amt=12750250.6261 
2023-10-06 08:25:00,838:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231006   080000    080459  ...         0.0        0.0       0
5857  20231006   080500    080959  ...         0.0        0.0       0
5858  20231006   081000    081459  ...         0.0        0.0       0
5859  20231006   081500    081959  ...         0.0        0.0       0
5860  20231006   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 08:25:00,839:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696551899, self.tradeDate='20231006', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27391.7, self.close=27420.0, self.high=27420.0, self.low=27386.0, self.vol=465.165, self.amt=12750250.6261, ukdf['pct'].iloc[-1]=0.001037 , ukdf['amount'].iloc[-1]=12750250.6261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7741.4634', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27420.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41714127.0.0.1 - - [06/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -
 

self.closeSec=1696550399, self.tradeDate='20231006', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27401.6, self.close=27398.4, self.high=27406.2, self.low=27392.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41715 

self.closeSec=1696550699, self.tradeDate='20231006', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27398.3, self.close=27405.1, self.high=27412.4, self.low=27393.6 
127.0.0.1 - - [06/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41716 

self.closeSec=1696550999, self.tradeDate='20231006', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27405.0, self.close=27409.8, self.high=27410.4, self.low=27394.0 
127.0.0.1 - - [06/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41717 

self.closeSec=1696551299, self.tradeDate='20231006', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27409.7, self.close=27402.9, self.high=27409.9, self.low=27395.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41718 

self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27402.9, self.close=27391.6, self.high=27405.0, self.low=27382.6 
127.0.0.1 - - [06/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41719 

self.closeSec=1696551899, self.tradeDate='20231006', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27391.7, self.close=27420.0, self.high=27420.0, self.low=27386.0 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-06 08:00:17,487:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231006    052959  27463.0  ...  55.416667  0.477178  0.629148
5770  20231006    055959  27473.4  ...  55.416667  0.469563  0.645321
5771  20231006    062959  27433.1  ...  55.000000  0.468314  0.660981
5772  20231006    065959  27427.8  ...  55.000000  0.467507  0.675959
5773  20231006    072959  27422.2  ...  55.000000  0.461456  0.692625

[5 rows x 33 columns]
0.5666666666666667
acc is : 0.5666666666666667
2023-10-06 08:00:17,548:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.495192  0.504808       0  ...  0.933552  -1.0    0.0  1.028995
536     1  0.477810  0.522190       0  ...  0.933776  -1.0    0.0  1.028747
537     1  0.488971  0.511029       0  ...  0.933919  -1.0    0.0  1.028590
538     1  0.490843  0.509157       0  ...  0.934985  -1.0    0.0  1.027416
539     1  0.480376  0.519624       1  ...  0.934733  -1.0    0.0  1.027693

[5 rows x 10 columns]
2023-10-06 08:00:17,559:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495387  0.504613       0  ...  0.933552  -1.0    0.0  1.032636
46     1  0.478182  0.521818       0  ...  0.933776  -1.0    0.0  1.033083
47     1  0.489183  0.510817       0  ...  0.933919  -1.0    0.0  1.032365
48     1  0.490924  0.509076       0  ...  0.934985  -1.0    0.0  1.030965
49     1  0.480376  0.519624       1  ...  0.934733  -1.0    0.0  1.027693

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.386', 'enterprice': '27541.7', 'countrevence': '0', 'unrealprofit': '3531.53700757248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27396.88178432', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20855 

self.closeSec=1696548599, self.tradeDate='20231006', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27420.4', self.close='27391'
127.0.0.1 - - [06/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20856 

self.closeSec=1696549199, self.tradeDate='20231006', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27389.5', self.close='27407.4'
127.0.0.1 - - [06/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20857 

self.closeSec=1696549799, self.tradeDate='20231006', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27405.9', self.close='27395.5'
127.0.0.1 - - [06/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20858 

self.closeSec=1696550399, self.tradeDate='20231006', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27395.5', self.close='27398.4'
127.0.0.1 - - [06/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20859 

self.closeSec=1696550999, self.tradeDate='20231006', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27398.3', self.close='27409.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20860 

self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27409.7', self.close='27391.6'
127.0.0.1 - - [06/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [06/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20858 

self.closeSec=1696548599, self.tradeDate='20231006', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27420.4', self.close='27391'
127.0.0.1 - - [06/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20859 

self.closeSec=1696549199, self.tradeDate='20231006', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27389.5', self.close='27407.4'

--handleKline--: 127.0.0.1 - - [06/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20860 

self.closeSec=1696549799, self.tradeDate='20231006', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27405.9', self.close='27395.5'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20861 

self.closeSec=1696550399, self.tradeDate='20231006', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27395.5', self.close='27398.4'
127.0.0.1 - - [06/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20862 

self.closeSec=1696550999, self.tradeDate='20231006', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27398.3', self.close='27409.8'
127.0.0.1 - - [06/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20863 

self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27409.7', self.close='27391.6'
127.0.0.1 - - [06/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20858 

self.closeSec=1696548599, self.tradeDate='20231006', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27420.4', self.close='27391'
127.0.0.1 - - [06/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20859 

self.closeSec=1696549199, self.tradeDate='20231006', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27389.5', self.close='27407.4'
127.0.0.1 - - [06/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20860 

self.closeSec=1696549799, self.tradeDate='20231006', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27405.9', self.close='27395.5'
127.0.0.1 - - [06/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20861 

self.closeSec=1696550399, self.tradeDate='20231006', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27395.5', self.close='27398.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20862 

self.closeSec=1696550999, self.tradeDate='20231006', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27398.3', self.close='27409.8'
127.0.0.1 - - [06/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20863 

self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27409.7', self.close='27391.6'
127.0.0.1 - - [06/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41716
self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27402.9, self.close=27391.6, self.high=27405.0, self.low=27382.6, self.vol=436.715, self.amt=11962368.7423 
127.0.0.1 - - [06/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-06 08:20:05,814:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231006   075500    075959  ...         0.0        0.0       0
5856  20231006   080000    080459  ...         0.0        0.0       0
5857  20231006   080500    080959  ...         0.0        0.0       0
5858  20231006   081000    081459  ...         0.0        0.0       0
5859  20231006   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 08:20:05,825:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696551599, self.tradeDate='20231006', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27402.9, self.close=27391.6, self.high=27405.0, self.low=27382.6, self.vol=436.715, self.amt=11962368.7423, ukdf['pct'].iloc[-1]=-0.000412 , ukdf['amount'].iloc[-1]=11962368.7423, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '20342.1257', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27391.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41717
self.closeSec=1696551899, self.tradeDate='20231006', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27391.7, self.close=27420.0, self.high=27420.0, self.low=27386.0, self.vol=465.165, self.amt=12750250.6261 
2023-10-06 08:25:00,847:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231006   080000    080459  ...         0.0        0.0       0
5857  20231006   080500    080959  ...         0.0        0.0       0
5858  20231006   081000    081459  ...         0.0        0.0       0
5859  20231006   081500    081959  ...         0.0        0.0       0
5860  20231006   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-06 08:25:00,848:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696551899, self.tradeDate='20231006', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27391.7, self.close=27420.0, self.high=27420.0, self.low=27386.0, self.vol=465.165, self.amt=12750250.6261, ukdf['pct'].iloc[-1]=0.001037 , ukdf['amount'].iloc[-1]=12750250.6261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21422.9288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27420.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231005   200000    235959  1696521599  ...    719  0.468945 -0.620412    -1.0
720  20231006   000000    035959  1696535999  ...    720  0.405187 -0.770041    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.706', 'enterprice': '27536.4', 'countrevence': '0', 'unrealprofit': '3419.80390643814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27458.15436081', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [06/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1202302.3925016, self.flagDict['side']='sell', self.tradeCount=30, self.count=869
self.closeSec=1696550399, self.tradeDate='20231006', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27457.1, self.close=27398.4, self.high=27497.2, self.low=27368.5, self.vol=22243.134, self.amt=610118456.8127 
2023-10-06 08:00:01,577:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696550399, self.tradeDate='20231006', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27457.1, self.close=27398.4, self.high=27497.2, self.low=27368.5, self.vol=22243.134, self.amt=610118456.8127 
2023-10-06 08:00:01,591:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231005   120000    155959  ...   23302.294  6.435468e+08 -0.001552
718  20231005   160000    195959  ...   26856.381  7.432812e+08  0.004178
719  20231005   200000    235959  ...  182212.597  5.068501e+09 -0.006160
720  20231006   000000    035959  ...   80767.492  2.217417e+09 -0.003101
721  20231006   040000    075959  ...   22243.134  6.101185e+08 -0.002047

[5 rows x 11 columns]
2023-10-06 08:00:02,291:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231005   120000    155959  1696492799  ...    717  0.646229 -0.194907     NaN
718  20231005   160000    195959  1696507199  ...    718  0.553523 -0.416799     NaN
719  20231005   200000    235959  1696521599  ...    719  0.468945 -0.620412    -1.0
720  20231006   000000    035959  1696535999  ...    720  0.405187 -0.770041    -1.0
721  20231006   040000    075959  1696550399  ...    721  0.315995 -0.984895    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.706', 'enterprice': '27536.4', 'countrevence': '0', 'unrealprofit': '6035.7986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27398.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


