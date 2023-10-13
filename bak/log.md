# 20231013 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43732
self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26790.4, self.close=26810.3, self.high=26833.7, self.low=26790.3, self.vol=3101.043, self.amt=83162127.4939 
127.0.0.1 - - [13/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-13 08:20:17,377:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231013   075500    075959  ...         0.0        0.0       0
5856  20231013   080000    080459  ...         0.0        0.0       0
5857  20231013   080500    080959  ...         0.0        0.0       0
5858  20231013   081000    081459  ...         0.0        0.0       0
5859  20231013   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 08:20:17,388:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26790.4, self.close=26810.3, self.high=26833.7, self.low=26790.3, self.vol=3101.043, self.amt=83162127.4939, ukdf['pct'].iloc[-1]=0.000743 , ukdf['amount'].iloc[-1]=83162127.4939, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '612.744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26820.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43733
self.closeSec=1697156699, self.tradeDate='20231013', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26810.4, self.close=26821.0, self.high=26832.6, self.low=26810.3, self.vol=669.969, self.amt=17970564.4592 
127.0.0.1 - - [13/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-13 08:25:00,841:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231013   080000    080459  ...         0.0        0.0       0
5857  20231013   080500    080959  ...         0.0        0.0       0
5858  20231013   081000    081459  ...         0.0        0.0       0
5859  20231013   081500    081959  ...         0.0        0.0       0
5860  20231013   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 08:25:00,842:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697156699, self.tradeDate='20231013', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26810.4, self.close=26821.0, self.high=26832.6, self.low=26810.3, self.vol=669.969, self.amt=17970564.4592, ukdf['pct'].iloc[-1]=0.000399 , ukdf['amount'].iloc[-1]=17970564.4592, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '591.13707139014', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26822.45155311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43730 

self.closeSec=1697155199, self.tradeDate='20231013', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26729.5, self.close=26744.1, self.high=26754.4, self.low=26729.5 
127.0.0.1 - - [13/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43731 

self.closeSec=1697155499, self.tradeDate='20231013', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26744.0, self.close=26748.1, self.high=26749.2, self.low=26733.9 
127.0.0.1 - - [13/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43732 

self.closeSec=1697155799, self.tradeDate='20231013', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26748.1, self.close=26777.9, self.high=26787.5, self.low=26745.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43733 

self.closeSec=1697156099, self.tradeDate='20231013', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26778.0, self.close=26790.4, self.high=26796.0, self.low=26763.8 
127.0.0.1 - - [13/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43734 

self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26790.4, self.close=26810.3, self.high=26833.7, self.low=26790.3 
127.0.0.1 - - [13/Oct/2023 08:20:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43735 

self.closeSec=1697156699, self.tradeDate='20231013', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26810.4, self.close=26821.0, self.high=26832.6, self.low=26810.3 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-13 08:00:16,528:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231013    052959  26734.4  ...  48.750000  0.441220  0.628954
5770  20231013    055959  26717.1  ...  49.166667  0.449946  0.618922
5771  20231013    062959  26745.6  ...  48.750000  0.449468  0.609872
5772  20231013    065959  26743.6  ...  48.333333  0.448522  0.599411
5773  20231013    072959  26738.9  ...  48.333333  0.443478  0.593130

[5 rows x 33 columns]
0.55
acc is : 0.55
2023-10-13 08:00:16,584:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.493287  0.506713       1  ...  1.014963  -1.0    0.0  0.988338
536     0  0.508095  0.491905       0  ...  1.015036  -1.0    0.0  0.988267
537     1  0.498437  0.501563       0  ...  1.015176  -1.0    0.0  0.988131
538     1  0.497013  0.502987       0  ...  1.015920  -1.0    0.0  0.987406
539     1  0.490190  0.509810       1  ...  1.015019  -1.0    0.0  0.988282

[5 rows x 10 columns]
2023-10-13 08:00:16,595:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492981  0.507019       1  ...  1.014963  -1.0    0.0  0.985620
46     0  0.507946  0.492054       0  ...  1.015036  -1.0    0.0  0.986510
47     1  0.498376  0.501624       0  ...  1.015176  -1.0    0.0  0.986720
48     1  0.496582  0.503418       0  ...  1.015920  -1.0    0.0  0.985629
49     1  0.490190  0.509810       1  ...  1.015019  -1.0    0.0  0.988282

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.051', 'enterprice': '26768.8', 'countrevence': '0', 'unrealprofit': '631.11559544211', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26742.55927839', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21863 

self.closeSec=1697153399, self.tradeDate='20231013', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26697.9', self.close='26720.4'

--handleKline--: 127.0.0.1 - - [13/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21864 

self.closeSec=1697153999, self.tradeDate='20231013', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26720.4', self.close='26744.1'
127.0.0.1 - - [13/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21865 

self.closeSec=1697154599, self.tradeDate='20231013', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26744.1', self.close='26735'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21866 

self.closeSec=1697155199, self.tradeDate='20231013', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26735', self.close='26744.1'
127.0.0.1 - - [13/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21867 

self.closeSec=1697155799, self.tradeDate='20231013', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26744', self.close='26777.9'
127.0.0.1 - - [13/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21868 

self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26778', self.close='26810.3'
127.0.0.1 - - [13/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [13/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21866 

self.closeSec=1697153399, self.tradeDate='20231013', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26697.9', self.close='26720.4'

--handleKline--: 127.0.0.1 - - [13/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21867 

self.closeSec=1697153999, self.tradeDate='20231013', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26720.4', self.close='26744.1'
127.0.0.1 - - [13/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21868 

self.closeSec=1697154599, self.tradeDate='20231013', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26744.1', self.close='26735'
127.0.0.1 - - [13/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21869 

self.closeSec=1697155199, self.tradeDate='20231013', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26735', self.close='26744.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21870 

self.closeSec=1697155799, self.tradeDate='20231013', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26744', self.close='26777.9'
127.0.0.1 - - [13/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21871 

self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26778', self.close='26810.3'
127.0.0.1 - - [13/Oct/2023 08:20:12] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21866 

self.closeSec=1697153399, self.tradeDate='20231013', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26697.9', self.close='26720.4'
127.0.0.1 - - [13/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21867 

self.closeSec=1697153999, self.tradeDate='20231013', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26720.4', self.close='26744.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21868 

self.closeSec=1697154599, self.tradeDate='20231013', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26744.1', self.close='26735'
127.0.0.1 - - [13/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21869 

self.closeSec=1697155199, self.tradeDate='20231013', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26735', self.close='26744.1'
127.0.0.1 - - [13/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21870 

self.closeSec=1697155799, self.tradeDate='20231013', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26744', self.close='26777.9'
127.0.0.1 - - [13/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21871 

self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26778', self.close='26810.3'
127.0.0.1 - - [13/Oct/2023 08:20:11] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43732
self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26790.4, self.close=26810.3, self.high=26833.7, self.low=26790.3, self.vol=3101.043, self.amt=83162127.4939 
127.0.0.1 - - [13/Oct/2023 08:20:10] "POST / HTTP/1.1" 200 -
2023-10-13 08:20:17,366:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231013   075500    075959  ...         0.0        0.0       0
5856  20231013   080000    080459  ...         0.0        0.0       0
5857  20231013   080500    080959  ...         0.0        0.0       0
5858  20231013   081000    081459  ...         0.0        0.0       0
5859  20231013   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 08:20:17,378:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697156399, self.tradeDate='20231013', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26790.4, self.close=26810.3, self.high=26833.7, self.low=26790.3, self.vol=3101.043, self.amt=83162127.4939, ukdf['pct'].iloc[-1]=0.000743 , ukdf['amount'].iloc[-1]=83162127.4939, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-895.0981', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26819.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43733
self.closeSec=1697156699, self.tradeDate='20231013', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26810.4, self.close=26821.0, self.high=26832.6, self.low=26810.3, self.vol=669.969, self.amt=17970564.4592 
127.0.0.1 - - [13/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-13 08:25:00,845:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231013   080000    080459  ...         0.0        0.0       0
5857  20231013   080500    080959  ...         0.0        0.0       0
5858  20231013   081000    081459  ...         0.0        0.0       0
5859  20231013   081500    081959  ...         0.0        0.0       0
5860  20231013   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-13 08:25:00,846:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697156699, self.tradeDate='20231013', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26810.4, self.close=26821.0, self.high=26832.6, self.low=26810.3, self.vol=669.969, self.amt=17970564.4592, ukdf['pct'].iloc[-1]=0.000399 , ukdf['amount'].iloc[-1]=17970564.4592, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-800.33086594149', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26822.45155311', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231012   200000    235959  1697126399  ...    719  0.783933  0.693354     1.0
720  20231013   000000    035959  1697140799  ...    720  0.777967  0.659623     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '-5921.63772694737', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26701.30054029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1263543.0464457, self.flagDict['side']='buy', self.tradeCount=33, self.count=911
self.closeSec=1697155199, self.tradeDate='20231013', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26700.2, self.close=26744.1, self.high=26767.2, self.low=26692.0, self.vol=15277.367, self.amt=408311312.1063 
127.0.0.1 - - [13/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-13 08:00:01,549:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697155199, self.tradeDate='20231013', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26700.2, self.close=26744.1, self.high=26767.2, self.low=26692.0, self.vol=15277.367, self.amt=408311312.1063 
2023-10-13 08:00:01,561:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231012   120000    155959  ...  22534.866  6.047471e+08 -0.001368
718  20231012   160000    195959  ...  41185.888  1.101793e+09  0.001049
719  20231012   200000    235959  ...  52334.340  1.398958e+09 -0.006128
720  20231013   000000    035959  ...  58269.011  1.553183e+09  0.001399
721  20231013   040000    075959  ...  15277.367  4.083113e+08  0.001640

[5 rows x 11 columns]
2023-10-13 08:00:02,241:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231012   120000    155959  1697097599  ...    717  0.732357  0.584987     NaN
718  20231012   160000    195959  1697111999  ...    718  0.758655  0.641186     1.0
719  20231012   200000    235959  1697126399  ...    719  0.783933  0.693354     1.0
720  20231013   000000    035959  1697140799  ...    720  0.777967  0.659623     1.0
721  20231013   040000    075959  1697155199  ...    721  0.822618  0.766006     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '47.147', 'enterprice': '26826.9', 'countrevence': '0', 'unrealprofit': '-3696.70188972099', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26748.49200183', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


