# 20231014 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44020
self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26861.0, self.close=26848.0, self.high=26861.1, self.low=26840.0, self.vol=393.866, self.amt=10575252.0551 
127.0.0.1 - - [14/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-10-14 08:20:08,796:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231014   075500    075959  ...         0.0        0.0       0
5856  20231014   080000    080459  ...         0.0        0.0       0
5857  20231014   080500    080959  ...         0.0        0.0       0
5858  20231014   081000    081459  ...         0.0        0.0       0
5859  20231014   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 08:20:08,807:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26861.0, self.close=26848.0, self.high=26861.1, self.low=26840.0, self.vol=393.866, self.amt=10575252.0551, ukdf['pct'].iloc[-1]=-0.000477 , ukdf['amount'].iloc[-1]=10575252.0551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '218.6382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26849.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=44021
self.closeSec=1697243099, self.tradeDate='20231014', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26847.9, self.close=26858.1, self.high=26858.2, self.low=26837.5, self.vol=326.795, self.amt=8773940.0148 
127.0.0.1 - - [14/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-14 08:25:02,610:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231014   080000    080459  ...         0.0        0.0       0
5857  20231014   080500    080959  ...         0.0        0.0       0
5858  20231014   081000    081459  ...         0.0        0.0       0
5859  20231014   081500    081959  ...         0.0        0.0       0
5860  20231014   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 08:25:02,612:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697243099, self.tradeDate='20231014', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26847.9, self.close=26858.1, self.high=26858.2, self.low=26837.5, self.vol=326.795, self.amt=8773940.0148, ukdf['pct'].iloc[-1]=0.000376 , ukdf['amount'].iloc[-1]=8773940.0148, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '94.6968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26858.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44018 

self.closeSec=1697241599, self.tradeDate='20231014', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26831.0, self.close=26849.8, self.high=26849.8, self.low=26831.0 
127.0.0.1 - - [14/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44019 

self.closeSec=1697241899, self.tradeDate='20231014', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26849.7, self.close=26870.3, self.high=26875.9, self.low=26838.6 
127.0.0.1 - - [14/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44020 

self.closeSec=1697242199, self.tradeDate='20231014', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26868.9, self.close=26858.4, self.high=26873.6, self.low=26857.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44021 

self.closeSec=1697242499, self.tradeDate='20231014', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26858.4, self.close=26860.8, self.high=26866.5, self.low=26857.2 
127.0.0.1 - - [14/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44022 

self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26861.0, self.close=26848.0, self.high=26861.1, self.low=26840.0 
127.0.0.1 - - [14/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=44023 

self.closeSec=1697243099, self.tradeDate='20231014', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26847.9, self.close=26858.1, self.high=26858.2, self.low=26837.5 
127.0.0.1 - - [14/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-14 08:00:15,837:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231014    052959  26967.8  ...  48.750000  0.540962  0.523125
5770  20231014    055959  26989.2  ...  49.166667  0.545170  0.505320
5771  20231014    062959  27005.4  ...  49.166667  0.533465  0.494323
5772  20231014    065959  26966.0  ...  48.750000  0.490095  0.506764
5773  20231014    072959  26813.9  ...  48.750000  0.488642  0.519189

[5 rows x 33 columns]
0.5518518518518518
acc is : 0.5518518518518518
2023-10-14 08:00:15,907:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.520828  0.479172       1  ...  0.993130   1.0    0.0  0.962890
536     0  0.518835  0.481165       0  ...  0.991733   1.0    0.0  0.961535
537     1  0.498658  0.501342       0  ...  0.986088   1.0    0.0  0.956062
538     1  0.454671  0.545329       0  ...  0.985886   1.0    0.0  0.955866
539     1  0.484466  0.515534       1  ...  0.987408   1.0    0.0  0.957342

[5 rows x 10 columns]
2023-10-14 08:00:15,919:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520947  0.479053       1  ...  1.001664   1.0    0.0  0.963515
46     0  0.518721  0.481279       0  ...  0.991733   1.0    0.0  0.960891
47     1  0.498719  0.501281       0  ...  0.986088   1.0    0.0  0.958091
48     1  0.454473  0.545527       0  ...  0.985886   1.0    0.0  0.955791
49     1  0.484466  0.515534       1  ...  0.987408   1.0    0.0  0.957342

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.627', 'enterprice': '27009.6', 'countrevence': '0', 'unrealprofit': '-3639.81768980763', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26855.54668431', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22007 

self.closeSec=1697239799, self.tradeDate='20231014', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26795.4', self.close='26813'
127.0.0.1 - - [14/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [14/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22008 

self.closeSec=1697240399, self.tradeDate='20231014', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26813', self.close='26830'
127.0.0.1 - - [14/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22009 

self.closeSec=1697240999, self.tradeDate='20231014', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26830.1', self.close='26827'
127.0.0.1 - - [14/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22010 

self.closeSec=1697241599, self.tradeDate='20231014', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26827', self.close='26849.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22011 

self.closeSec=1697242199, self.tradeDate='20231014', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26849.7', self.close='26857.6'
127.0.0.1 - - [14/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22012 

self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26858.4', self.close='26847.9'
127.0.0.1 - - [14/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [14/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22010 

self.closeSec=1697239799, self.tradeDate='20231014', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26795.4', self.close='26813'
127.0.0.1 - - [14/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22011 

self.closeSec=1697240399, self.tradeDate='20231014', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26813', self.close='26830'
127.0.0.1 - - [14/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22012 

self.closeSec=1697240999, self.tradeDate='20231014', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26830.1', self.close='26827'
127.0.0.1 - - [14/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22013 

self.closeSec=1697241599, self.tradeDate='20231014', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26827', self.close='26849.8'
127.0.0.1 - - [14/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22014 

self.closeSec=1697242199, self.tradeDate='20231014', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26849.7', self.close='26857.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22015 

self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26858.4', self.close='26847.9'
127.0.0.1 - - [14/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22010 

self.closeSec=1697239799, self.tradeDate='20231014', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26795.4', self.close='26813'
127.0.0.1 - - [14/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [14/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22011 

self.closeSec=1697240399, self.tradeDate='20231014', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26813', self.close='26830'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22012 

self.closeSec=1697240999, self.tradeDate='20231014', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26830.1', self.close='26827'
127.0.0.1 - - [14/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22013 

self.closeSec=1697241599, self.tradeDate='20231014', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26827', self.close='26849.8'
127.0.0.1 - - [14/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22014 

self.closeSec=1697242199, self.tradeDate='20231014', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26849.7', self.close='26857.6'
127.0.0.1 - - [14/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22015 

self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26858.4', self.close='26847.9'
127.0.0.1 - - [14/Oct/2023 08:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44020
self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26861.0, self.close=26848.0, self.high=26861.1, self.low=26840.0, self.vol=393.866, self.amt=10575252.0551 
127.0.0.1 - - [14/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-10-14 08:20:08,778:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231014   075500    075959  ...         0.0        0.0       0
5856  20231014   080000    080459  ...         0.0        0.0       0
5857  20231014   080500    080959  ...         0.0        0.0       0
5858  20231014   081000    081459  ...         0.0        0.0       0
5859  20231014   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 08:20:08,782:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697242799, self.tradeDate='20231014', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26861.0, self.close=26848.0, self.high=26861.1, self.low=26840.0, self.vol=393.866, self.amt=10575252.0551, ukdf['pct'].iloc[-1]=-0.000477 , ukdf['amount'].iloc[-1]=10575252.0551, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '193.1332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26849.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=44021
self.closeSec=1697243099, self.tradeDate='20231014', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26847.9, self.close=26858.1, self.high=26858.2, self.low=26837.5, self.vol=326.795, self.amt=8773940.0148 
127.0.0.1 - - [14/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-14 08:25:02,608:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231014   080000    080459  ...         0.0        0.0       0
5857  20231014   080500    080959  ...         0.0        0.0       0
5858  20231014   081000    081459  ...         0.0        0.0       0
5859  20231014   081500    081959  ...         0.0        0.0       0
5860  20231014   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-14 08:25:02,609:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697243099, self.tradeDate='20231014', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26847.9, self.close=26858.1, self.high=26858.2, self.low=26837.5, self.vol=326.795, self.amt=8773940.0148, ukdf['pct'].iloc[-1]=0.000376 , ukdf['amount'].iloc[-1]=8773940.0148, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '523.6881', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26858.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231013   200000    235959  1697212799  ...    719  0.846559  0.756405     1.0
720  20231014   000000    035959  1697227199  ...    720  0.868009  0.813295     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '-2758.0995', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26768.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=917
self.closeSec=1697241599, self.tradeDate='20231014', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26769.0, self.close=26849.8, self.high=27120.8, self.low=26733.3, self.vol=93383.298, self.amt=2515111840.22272 
127.0.0.1 - - [14/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-14 08:00:01,515:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697241599, self.tradeDate='20231014', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26769.0, self.close=26849.8, self.high=27120.8, self.low=26733.3, self.vol=93383.298, self.amt=2515111840.22272 
2023-10-14 08:00:01,541:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231013   120000    155959  ...  22522.718  6.045876e+08  0.003422
718  20231013   160000    195959  ...  25997.959  6.966675e+08 -0.001902
719  20231013   200000    235959  ...  52873.068  1.417818e+09 -0.004368
720  20231014   000000    035959  ...  24418.280  6.530784e+08  0.002821
721  20231014   040000    075959  ...  93383.298  2.515112e+09  0.003048

[5 rows x 11 columns]
2023-10-14 08:00:02,404:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231013   120000    155959  1697183999  ...    717  0.855994  0.822502     1.0
718  20231013   160000    195959  1697198399  ...    718  0.903855  0.938535     1.0
719  20231013   200000    235959  1697212799  ...    719  0.846559  0.756405     1.0
720  20231014   000000    035959  1697227199  ...    720  0.868009  0.813295     1.0
721  20231014   040000    075959  1697241599  ...    721  0.804414  0.629649     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '1079.6663', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26849.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


