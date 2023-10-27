# 20231027 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47764
self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=34117.4, self.close=34084.9, self.high=34131.3, self.low=34035.0, self.vol=1260.848, self.amt=42961428.9327 
127.0.0.1 - - [27/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-27 08:20:17,449:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231027   075500    075959  ...         0.0        0.0       0
5856  20231027   080000    080459  ...         0.0        0.0       0
5857  20231027   080500    080959  ...         0.0        0.0       0
5858  20231027   081000    081459  ...         0.0        0.0       0
5859  20231027   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 08:20:17,468:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=34117.4, self.close=34084.9, self.high=34131.3, self.low=34035.0, self.vol=1260.848, self.amt=42961428.9327, ukdf['pct'].iloc[-1]=-0.000853 , ukdf['amount'].iloc[-1]=42961428.9327, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-100639.19901460986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34091.61255311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47765
self.closeSec=1698366299, self.tradeDate='20231027', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=34085.0, self.close=34120.9, self.high=34128.0, self.low=34081.1, self.vol=606.271, self.amt=20676951.0471 
127.0.0.1 - - [27/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-27 08:25:03,063:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231027   080000    080459  ...         0.0        0.0       0
5857  20231027   080500    080959  ...         0.0        0.0       0
5858  20231027   081000    081459  ...         0.0        0.0       0
5859  20231027   081500    081959  ...         0.0        0.0       0
5860  20231027   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 08:25:03,066:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698366299, self.tradeDate='20231027', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=34085.0, self.close=34120.9, self.high=34128.0, self.low=34081.1, self.vol=606.271, self.amt=20676951.0471, ukdf['pct'].iloc[-1]=0.001056 , ukdf['amount'].iloc[-1]=20676951.0471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-101047.056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34120.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47762 

self.closeSec=1698364799, self.tradeDate='20231027', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=34148.9, self.close=34154.0, self.high=34174.0, self.low=34148.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47763 

self.closeSec=1698365099, self.tradeDate='20231027', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=34154.0, self.close=34142.4, self.high=34179.6, self.low=34111.7 
127.0.0.1 - - [27/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47764 

self.closeSec=1698365399, self.tradeDate='20231027', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=34142.4, self.close=34107.0, self.high=34147.8, self.low=34098.1 
127.0.0.1 - - [27/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47765 

self.closeSec=1698365699, self.tradeDate='20231027', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=34107.0, self.close=34114.0, self.high=34124.3, self.low=34078.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47766 

self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=34117.4, self.close=34084.9, self.high=34131.3, self.low=34035.0 
127.0.0.1 - - [27/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47767 

self.closeSec=1698366299, self.tradeDate='20231027', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=34085.0, self.close=34120.9, self.high=34128.0, self.low=34081.1 
127.0.0.1 - - [27/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-27 08:00:18,438:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231027    052959  34189.0  ...  56.250000  0.507122  0.690629
5770  20231027    055959  34138.9  ...  56.250000  0.505611  0.688097
5771  20231027    062959  34124.6  ...  56.666667  0.513949  0.680745
5772  20231027    065959  34205.4  ...  56.666667  0.517172  0.671949
5773  20231027    072959  34236.7  ...  56.666667  0.513520  0.665773

[5 rows x 33 columns]
0.5351851851851852
acc is : 0.5351851851851852
2023-10-27 08:00:18,509:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.530733  0.469267       0  ...  1.033456   1.0    0.0  1.265307
536     0  0.537509  0.462491       1  ...  1.035900   1.0    0.0  1.268299
537     0  0.558908  0.441092       1  ...  1.036848   1.0    0.0  1.269460
538     0  0.545698  0.454302       0  ...  1.035851   1.0    0.0  1.268240
539     0  0.529916  0.470084       0  ...  1.034343   1.0    0.0  1.266394

[5 rows x 10 columns]
2023-10-27 08:00:18,522:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.530191  0.469809       0  ...  1.027637   1.0    0.0  1.269251
46     0  0.537189  0.462811       1  ...  1.030067   1.0    0.0  1.271775
47     0  0.559609  0.440391       1  ...  1.064514   1.0    0.0  1.271931
48     0  0.546612  0.453388       0  ...  1.063491   1.0    0.0  1.267746
49     0  0.529916  0.470084       0  ...  1.034343   1.0    0.0  1.266394

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.749', 'enterprice': '34210', 'countrevence': '0', 'unrealprofit': '-1464.51355632937', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34139.41763187', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23879 

self.closeSec=1698362999, self.tradeDate='20231027', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='34280.2', self.close='34203.8'
127.0.0.1 - - [27/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23880 

self.closeSec=1698363599, self.tradeDate='20231027', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='34203.7', self.close='34170.9'

--handleKline--:  127.0.0.1 - - [27/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23881 

self.closeSec=1698364199, self.tradeDate='20231027', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='34170.9', self.close='34156.1'
127.0.0.1 - - [27/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23882 

self.closeSec=1698364799, self.tradeDate='20231027', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='34156.1', self.close='34154'
127.0.0.1 - - [27/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23883 

self.closeSec=1698365399, self.tradeDate='20231027', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='34154', self.close='34107'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23884 

self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='34107', self.close='34084.9'
127.0.0.1 - - [27/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23882 

self.closeSec=1698362999, self.tradeDate='20231027', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='34280.2', self.close='34203.8'
127.0.0.1 - - [27/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23883 

self.closeSec=1698363599, self.tradeDate='20231027', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='34203.7', self.close='34170.9'
127.0.0.1 - - [27/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23884 

self.closeSec=1698364199, self.tradeDate='20231027', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='34170.9', self.close='34156.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23885 

self.closeSec=1698364799, self.tradeDate='20231027', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='34156.1', self.close='34154'
127.0.0.1 - - [27/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23886 

self.closeSec=1698365399, self.tradeDate='20231027', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='34154', self.close='34107'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23887 

self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='34107', self.close='34084.9'
127.0.0.1 - - [27/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23882 

self.closeSec=1698362999, self.tradeDate='20231027', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='34280.2', self.close='34203.8'
127.0.0.1 - - [27/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23883 

self.closeSec=1698363599, self.tradeDate='20231027', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='34203.7', self.close='34170.9'
127.0.0.1 - - [27/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23884 

self.closeSec=1698364199, self.tradeDate='20231027', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='34170.9', self.close='34156.1'
127.0.0.1 - - [27/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23885 

self.closeSec=1698364799, self.tradeDate='20231027', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='34156.1', self.close='34154'
127.0.0.1 - - [27/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23886 

self.closeSec=1698365399, self.tradeDate='20231027', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='34154', self.close='34107'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23887 

self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='34107', self.close='34084.9'
127.0.0.1 - - [27/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47764
self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=34117.4, self.close=34084.9, self.high=34131.3, self.low=34035.0, self.vol=1260.848, self.amt=42961428.9327 
127.0.0.1 - - [27/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-27 08:20:17,439:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231027   075500    075959  ...         0.0        0.0       0
5856  20231027   080000    080459  ...         0.0        0.0       0
5857  20231027   080500    080959  ...         0.0        0.0       0
5858  20231027   081000    081459  ...         0.0        0.0       0
5859  20231027   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 08:20:17,459:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698365999, self.tradeDate='20231027', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=34117.4, self.close=34084.9, self.high=34131.3, self.low=34035.0, self.vol=1260.848, self.amt=42961428.9327, ukdf['pct'].iloc[-1]=-0.000853 , ukdf['amount'].iloc[-1]=42961428.9327, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '269183.57783505851', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34091.61255311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47765
self.closeSec=1698366299, self.tradeDate='20231027', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=34085.0, self.close=34120.9, self.high=34128.0, self.low=34081.1, self.vol=606.271, self.amt=20676951.0471 
127.0.0.1 - - [27/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-27 08:25:03,062:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231027   080000    080459  ...         0.0        0.0       0
5857  20231027   080500    080959  ...         0.0        0.0       0
5858  20231027   081000    081459  ...         0.0        0.0       0
5859  20231027   081500    081959  ...         0.0        0.0       0
5860  20231027   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-27 08:25:03,065:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698366299, self.tradeDate='20231027', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=34085.0, self.close=34120.9, self.high=34128.0, self.low=34081.1, self.vol=606.271, self.amt=20676951.0471, ukdf['pct'].iloc[-1]=0.001056 , ukdf['amount'].iloc[-1]=20676951.0471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '270271.3429', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34120.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231026   200000    235959  1698335999  ...    719  0.790856 -0.239494     NaN
720  20231027   000000    035959  1698350399  ...    720  0.711377 -0.371256     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '186058.30925257893', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34037.59968213', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [27/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=995
self.closeSec=1698364799, self.tradeDate='20231027', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=34052.2, self.close=34154.0, self.high=34287.5, self.low=34026.6, self.vol=26897.615, self.amt=919136317.69483 
2023-10-27 08:00:01,557:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698364799, self.tradeDate='20231027', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=34052.2, self.close=34154.0, self.high=34287.5, self.low=34026.6, self.vol=26897.615, self.amt=919136317.69483 
2023-10-27 08:00:01,570:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231026   120000    155959  ...   42890.458  1.484707e+09 -0.003444
718  20231026   160000    195959  ...   78780.151  2.703214e+09 -0.016138
719  20231026   200000    235959  ...  100680.980  3.434658e+09 -0.001589
720  20231027   000000    035959  ...   54823.275  1.860932e+09  0.000120
721  20231027   040000    075959  ...   26897.615  9.191363e+08  0.002934

[5 rows x 11 columns]
2023-10-27 08:00:02,452:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231026   120000    155959  1698307199  ...    717  0.880106 -0.082705     NaN
718  20231026   160000    195959  1698321599  ...    718  0.853465 -0.131839     NaN
719  20231026   200000    235959  1698335999  ...    719  0.790856 -0.239494     NaN
720  20231027   000000    035959  1698350399  ...    720  0.711377 -0.371256     NaN
721  20231027   040000    075959  1698364799  ...    721  0.607470 -0.539195     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '190931.38526377386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34155.41782026', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


