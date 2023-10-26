# 20231026 08:26:03

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47476
self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=34509.1, self.close=34520.0, self.high=34540.0, self.low=34490.0, self.vol=584.102, self.amt=20163566.27322 
127.0.0.1 - - [26/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-26 08:20:17,534:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231026   075500    075959  ...         0.0        0.0       0
5856  20231026   080000    080459  ...         0.0        0.0       0
5857  20231026   080500    080959  ...         0.0        0.0       0
5858  20231026   081000    081459  ...         0.0        0.0       0
5859  20231026   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 08:20:17,545:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=34509.1, self.close=34520.0, self.high=34540.0, self.low=34490.0, self.vol=584.102, self.amt=20163566.27322, ukdf['pct'].iloc[-1]=0.000316 , ukdf['amount'].iloc[-1]=20163566.27322, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-106601.554854531', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34519.7581685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=47477
self.closeSec=1698279899, self.tradeDate='20231026', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=34520.1, self.close=34547.2, self.high=34549.6, self.low=34503.1, self.vol=515.236, self.amt=17792776.4949 
127.0.0.1 - - [26/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-26 08:25:03,270:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231026   080000    080459  ...         0.0        0.0       0
5857  20231026   080500    080959  ...         0.0        0.0       0
5858  20231026   081000    081459  ...         0.0        0.0       0
5859  20231026   081500    081959  ...         0.0        0.0       0
5860  20231026   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 08:25:03,271:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1698279899, self.tradeDate='20231026', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=34520.1, self.close=34547.2, self.high=34549.6, self.low=34503.1, self.vol=515.236, self.amt=17792776.4949, ukdf['pct'].iloc[-1]=0.000788 , ukdf['amount'].iloc[-1]=17792776.4949, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-106982.3172', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '34547.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47474 

self.closeSec=1698278399, self.tradeDate='20231026', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=34461.5, self.close=34487.8, self.high=34492.8, self.low=34461.4 
127.0.0.1 - - [26/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47475 

self.closeSec=1698278699, self.tradeDate='20231026', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=34487.8, self.close=34466.3, self.high=34499.9, self.low=34432.8 
127.0.0.1 - - [26/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47476 

self.closeSec=1698278999, self.tradeDate='20231026', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=34466.4, self.close=34478.4, self.high=34511.0, self.low=34442.5 
127.0.0.1 - - [26/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47477 

self.closeSec=1698279299, self.tradeDate='20231026', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=34483.4, self.close=34509.1, self.high=34525.3, self.low=34450.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47478 

self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=34509.1, self.close=34520.0, self.high=34540.0, self.low=34490.0 
127.0.0.1 - - [26/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=47479 

self.closeSec=1698279899, self.tradeDate='20231026', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=34520.1, self.close=34547.2, self.high=34549.6, self.low=34503.1 
127.0.0.1 - - [26/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-26 08:00:19,968:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231026    052959  34656.2  ...  57.083333  0.586610  0.315383
5770  20231026    055959  34727.9  ...  56.666667  0.569635  0.321342
5771  20231026    062959  34549.7  ...  56.666667  0.574240  0.323989
5772  20231026    065959  34614.9  ...  56.250000  0.573281  0.326906
5773  20231026    072959  34603.0  ...  55.833333  0.561294  0.335226

[5 rows x 33 columns]
0.5351851851851852
acc is : 0.5351851851851852
2023-10-26 08:00:20,116:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.552926  0.447074       0  ...  1.080725   1.0    0.0  1.285570
536     1  0.493523  0.506477       1  ...  1.082768   1.0    0.0  1.288000
537     0  0.540833  0.459167       0  ...  1.082455   1.0    0.0  1.287628
538     0  0.524960  0.475040       0  ...  1.078533   1.0    0.0  1.282962
539     1  0.495292  0.504708       1  ...  1.078789   1.0    0.0  1.283267

[5 rows x 10 columns]
2023-10-26 08:00:20,142:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.552939  0.447061       0  ...  1.080725   1.0    0.0  1.282983
46     1  0.493583  0.506417       1  ...  1.082768   1.0    0.0  1.286803
47     0  0.541017  0.458983       0  ...  1.082455   1.0    0.0  1.285729
48     0  0.525064  0.474936       0  ...  1.078533   1.0    0.0  1.282847
49     1  0.495292  0.504708       1  ...  1.078789   1.0    0.0  1.283267

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '20.978', 'enterprice': '33828.2', 'countrevence': '0', 'unrealprofit': '13593.12749266216', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34476.17061172', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23735 

self.closeSec=1698276599, self.tradeDate='20231026', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='34469', self.close='34479.6'
127.0.0.1 - - [26/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23736 
127.0.0.1 - - [26/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

self.closeSec=1698277199, self.tradeDate='20231026', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='34480.7', self.close='34442.1'
127.0.0.1 - - [26/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23737 

self.closeSec=1698277799, self.tradeDate='20231026', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='34437.1', self.close='34445.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23738 

self.closeSec=1698278399, self.tradeDate='20231026', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='34445.9', self.close='34487.8'
127.0.0.1 - - [26/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23739 

self.closeSec=1698278999, self.tradeDate='20231026', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='34487.8', self.close='34478.4'
127.0.0.1 - - [26/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23740 

self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='34483.4', self.close='34520.1'
127.0.0.1 - - [26/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23738 

self.closeSec=1698276599, self.tradeDate='20231026', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='34469', self.close='34479.6'
127.0.0.1 - - [26/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23739 

self.closeSec=1698277199, self.tradeDate='20231026', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='34480.7', self.close='34442.1'
127.0.0.1 - - [26/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23740 

self.closeSec=1698277799, self.tradeDate='20231026', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='34437.1', self.close='34445.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23741 

self.closeSec=1698278399, self.tradeDate='20231026', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='34445.9', self.close='34487.8'
127.0.0.1 - - [26/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23742 

self.closeSec=1698278999, self.tradeDate='20231026', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='34487.8', self.close='34478.4'
127.0.0.1 - - [26/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23743 

self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='34483.4', self.close='34520.1'
127.0.0.1 - - [26/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23738 

self.closeSec=1698276599, self.tradeDate='20231026', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='34469', self.close='34479.6'
127.0.0.1 - - [26/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23739 

self.closeSec=1698277199, self.tradeDate='20231026', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='34480.7', self.close='34442.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23740 

self.closeSec=1698277799, self.tradeDate='20231026', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='34437.1', self.close='34445.9'
127.0.0.1 - - [26/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23741 

self.closeSec=1698278399, self.tradeDate='20231026', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='34445.9', self.close='34487.8'
127.0.0.1 - - [26/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [26/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23742 

self.closeSec=1698278999, self.tradeDate='20231026', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='34487.8', self.close='34478.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23743 

self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='34483.4', self.close='34520.1'
127.0.0.1 - - [26/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47476
self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=34509.1, self.close=34520.0, self.high=34540.0, self.low=34490.0, self.vol=584.102, self.amt=20163566.27322 
127.0.0.1 - - [26/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-26 08:20:17,533:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231026   075500    075959  ...         0.0        0.0       0
5856  20231026   080000    080459  ...         0.0        0.0       0
5857  20231026   080500    080959  ...         0.0        0.0       0
5858  20231026   081000    081459  ...         0.0        0.0       0
5859  20231026   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 08:20:17,546:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698279599, self.tradeDate='20231026', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=34509.1, self.close=34520.0, self.high=34540.0, self.low=34490.0, self.vol=584.102, self.amt=20163566.27322, ukdf['pct'].iloc[-1]=0.000316 , ukdf['amount'].iloc[-1]=20163566.27322, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '285077.11413916462', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34519.53684982', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=47477
self.closeSec=1698279899, self.tradeDate='20231026', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=34520.1, self.close=34547.2, self.high=34549.6, self.low=34503.1, self.vol=515.236, self.amt=17792776.4949 
127.0.0.1 - - [26/Oct/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-10-26 08:25:03,270:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231026   080000    080459  ...         0.0        0.0       0
5857  20231026   080500    080959  ...         0.0        0.0       0
5858  20231026   081000    081459  ...         0.0        0.0       0
5859  20231026   081500    081959  ...         0.0        0.0       0
5860  20231026   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-26 08:25:03,272:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1698279899, self.tradeDate='20231026', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=34520.1, self.close=34547.2, self.high=34549.6, self.low=34503.1, self.vol=515.236, self.amt=17792776.4949, ukdf['pct'].iloc[-1]=0.000788 , ukdf['amount'].iloc[-1]=17792776.4949, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '286100.8371', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34547.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231025   200000    235959  1698249599  ...    719  1.072746  0.263102     NaN
720  20231026   000000    035959  1698263999  ...    720  1.033059  0.189144     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '214319.77879608378', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34720.88755098', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1220549.0803488, self.flagDict['side']='buy', self.tradeCount=37, self.count=989
self.closeSec=1698278399, self.tradeDate='20231026', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=34732.0, self.close=34487.8, self.high=34847.0, self.low=34203.5, self.vol=49659.588, self.amt=1716450026.68046 127.0.0.1 - - [26/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

2023-10-26 08:00:01,564:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1698278399, self.tradeDate='20231026', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=34732.0, self.close=34487.8, self.high=34847.0, self.low=34203.5, self.vol=49659.588, self.amt=1716450026.68046 
2023-10-26 08:00:01,581:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231025   120000    155959  ...   54108.207  1.839219e+09 -0.004394
718  20231025   160000    195959  ...   73788.503  2.519740e+09  0.010108
719  20231025   200000    235959  ...  133242.385  4.610593e+09  0.018795
720  20231026   000000    035959  ...   96954.612  3.363552e+09 -0.003212
721  20231026   040000    075959  ...   49659.588  1.716450e+09 -0.006871

[5 rows x 11 columns]
2023-10-26 08:00:02,324:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231025   120000    155959  1698220799  ...    717  1.167537  0.441805     NaN
718  20231025   160000    195959  1698235199  ...    718  1.112812  0.341099     NaN
719  20231025   200000    235959  1698249599  ...    719  1.072746  0.263102     NaN
720  20231026   000000    035959  1698263999  ...    720  1.033059  0.189144     NaN
721  20231026   040000    075959  1698278399  ...    721  0.998519  0.124421     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '41.361', 'enterprice': '29539.2', 'countrevence': '0', 'unrealprofit': '204742.66236316029', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '34489.33810989', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


