# 20230908 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33652
self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26209.4, self.close=26230.2, self.high=26236.7, self.low=26207.7, self.vol=575.923, self.amt=15103644.2471 
127.0.0.1 - - [08/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-08 08:20:05,738:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230908   075500    075959  ...         0.0        0.0       0
5856  20230908   080000    080459  ...         0.0        0.0       0
5857  20230908   080500    080959  ...         0.0        0.0       0
5858  20230908   081000    081459  ...         0.0        0.0       0
5859  20230908   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 08:20:05,743:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26209.4, self.close=26230.2, self.high=26236.7, self.low=26207.7, self.vol=575.923, self.amt=15103644.2471, ukdf['pct'].iloc[-1]=0.000794 , ukdf['amount'].iloc[-1]=15103644.2471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8813.95539046836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26231.98635714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33653
self.closeSec=1694132699, self.tradeDate='20230908', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26230.1, self.close=26275.1, self.high=26280.4, self.low=26230.1, self.vol=1373.388, self.amt=36068687.0243 
2023-09-08 08:25:00,777:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230908   080000    080459  ...         0.0        0.0       0
5857  20230908   080500    080959  ...         0.0        0.0       0
5858  20230908   081000    081459  ...         0.0        0.0       0
5859  20230908   081500    081959  ...         0.0        0.0       0
5860  20230908   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 08:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1694132699, self.tradeDate='20230908', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26230.1, self.close=26275.1, self.high=26280.4, self.low=26230.1, self.vol=1373.388, self.amt=36068687.0243, ukdf['pct'].iloc[-1]=0.001712 , ukdf['amount'].iloc[-1]=36068687.0243, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8173.21107592242', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26277.99700733', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [08/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33650 

self.closeSec=1694131199, self.tradeDate='20230908', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26193.0, self.close=26239.7, self.high=26242.1, self.low=26184.8 
127.0.0.1 - - [08/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33651 

self.closeSec=1694131499, self.tradeDate='20230908', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26240.7, self.close=26223.1, self.high=26255.7, self.low=26218.9 
127.0.0.1 - - [08/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33652 

self.closeSec=1694131799, self.tradeDate='20230908', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26223.0, self.close=26216.9, self.high=26224.0, self.low=26211.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33653 

self.closeSec=1694132099, self.tradeDate='20230908', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26216.9, self.close=26209.4, self.high=26230.1, self.low=26207.7 
127.0.0.1 - - [08/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33654 

self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26209.4, self.close=26230.2, self.high=26236.7, self.low=26207.7 
127.0.0.1 - - [08/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33655 

self.closeSec=1694132699, self.tradeDate='20230908', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26230.1, self.close=26275.1, self.high=26280.4, self.low=26230.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-08 08:00:16,156:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230908    052959  25991.5  ...  50.000000  0.623933  0.350869
5770  20230908    055959  26196.5  ...  50.000000  0.607259  0.351161
5771  20230908    062959  26149.6  ...  50.416667  0.631523  0.342518
5772  20230908    065959  26262.9  ...  50.416667  0.641150  0.330657
5773  20230908    072959  26311.3  ...  50.000000  0.598440  0.329744

[5 rows x 33 columns]
0.5388888888888889
acc is : 0.5388888888888889
2023-09-08 08:00:16,224:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.578745  0.421255       0  ...  1.012302   1.0    0.0  1.003654
536     0  0.514321  0.485679       1  ...  1.016696   1.0    0.0  1.008010
537     0  0.564303  0.435697       1  ...  1.018566   1.0    0.0  1.009864
538     0  0.547123  0.452877       0  ...  1.013561   1.0    0.0  1.004901
539     1  0.483002  0.516998       1  ...  1.015798   1.0    0.0  1.007120

[5 rows x 10 columns]
2023-09-08 08:00:16,237:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.578854  0.421146       0  ...  1.012302   1.0    0.0  1.001482
46     0  0.513652  0.486348       1  ...  1.016696   1.0    0.0  1.004559
47     0  0.563670  0.436330       1  ...  1.018566   1.0    0.0  1.006099
48     0  0.546772  0.453228       0  ...  1.013561   1.0    0.0  1.002266
49     1  0.483002  0.516998       1  ...  1.015798   1.0    0.0  1.007120

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.331', 'enterprice': '25653.5', 'countrevence': '0', 'unrealprofit': '16800.283', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26246.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [08/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16823 

self.closeSec=1694129399, self.tradeDate='20230908', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26210.2', self.close='26182'
127.0.0.1 - - [08/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16824 

self.closeSec=1694129999, self.tradeDate='20230908', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26181.9', self.close='26162'
127.0.0.1 - - [08/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16825 

self.closeSec=1694130599, self.tradeDate='20230908', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26161.9', self.close='26170.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16826 

self.closeSec=1694131199, self.tradeDate='20230908', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26170', self.close='26240.7'
127.0.0.1 - - [08/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16827 

self.closeSec=1694131799, self.tradeDate='20230908', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26240.7', self.close='26217'
127.0.0.1 - - [08/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16828 

self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26216.9', self.close='26230.2'
127.0.0.1 - - [08/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16826 

self.closeSec=1694129399, self.tradeDate='20230908', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26210.2', self.close='26182'
127.0.0.1 - - [08/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16827 

self.closeSec=1694129999, self.tradeDate='20230908', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26181.9', self.close='26162'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16828 

self.closeSec=1694130599, self.tradeDate='20230908', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26161.9', self.close='26170.1'
127.0.0.1 - - [08/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16829 

self.closeSec=1694131199, self.tradeDate='20230908', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26170', self.close='26240.7'
127.0.0.1 - - [08/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16830 

self.closeSec=1694131799, self.tradeDate='20230908', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26240.7', self.close='26217'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16831 

self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26216.9', self.close='26230.2'
127.0.0.1 - - [08/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16826 

self.closeSec=1694129399, self.tradeDate='20230908', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26210.2', self.close='26182'
127.0.0.1 - - [08/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16827 

self.closeSec=1694129999, self.tradeDate='20230908', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26181.9', self.close='26162'
127.0.0.1 - - [08/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [08/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16828 

self.closeSec=1694130599, self.tradeDate='20230908', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26161.9', self.close='26170.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16829 

self.closeSec=1694131199, self.tradeDate='20230908', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26170', self.close='26240.7'
127.0.0.1 - - [08/Sep/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16830 

self.closeSec=1694131799, self.tradeDate='20230908', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26240.7', self.close='26217'
127.0.0.1 - - [08/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16831 

self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26216.9', self.close='26230.2'
127.0.0.1 - - [08/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33652
self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26209.4, self.close=26230.2, self.high=26236.7, self.low=26207.7, self.vol=575.923, self.amt=15103644.2471 
127.0.0.1 - - [08/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-08 08:20:05,737:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230908   075500    075959  ...         0.0        0.0       0
5856  20230908   080000    080459  ...         0.0        0.0       0
5857  20230908   080500    080959  ...         0.0        0.0       0
5858  20230908   081000    081459  ...         0.0        0.0       0
5859  20230908   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 08:20:05,740:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694132399, self.tradeDate='20230908', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26209.4, self.close=26230.2, self.high=26236.7, self.low=26207.7, self.vol=575.923, self.amt=15103644.2471, ukdf['pct'].iloc[-1]=0.000794 , ukdf['amount'].iloc[-1]=15103644.2471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-22730.79870946326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26231.98635714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [08/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33653
self.closeSec=1694132699, self.tradeDate='20230908', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26230.1, self.close=26275.1, self.high=26280.4, self.low=26230.1, self.vol=1373.388, self.amt=36068687.0243 
2023-09-08 08:25:00,764:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230908   080000    080459  ...         0.0        0.0       0
5857  20230908   080500    080959  ...         0.0        0.0       0
5858  20230908   081000    081459  ...         0.0        0.0       0
5859  20230908   081500    081959  ...         0.0        0.0       0
5860  20230908   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-08 08:25:00,764:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1694132699, self.tradeDate='20230908', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26230.1, self.close=26275.1, self.high=26280.4, self.low=26230.1, self.vol=1373.388, self.amt=36068687.0243, ukdf['pct'].iloc[-1]=0.001712 , ukdf['amount'].iloc[-1]=36068687.0243, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-21021.91715075647', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26277.99700733', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230907   200000    235959  1694102399  ...    719  0.028042 -1.034925    -1.0
720  20230908   000000    035959  1694116799  ...    720  0.020270 -1.056341    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '1718.93539859643', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25862.23659341', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [08/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=701
self.closeSec=1694131199, self.tradeDate='20230908', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25867.1, self.close=26239.8, self.high=26451.0, self.low=25843.3, self.vol=115647.917, self.amt=3031112405.25198 
2023-09-08 08:00:01,587:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1694131199, self.tradeDate='20230908', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25867.1, self.close=26239.8, self.high=26451.0, self.low=25843.3, self.vol=115647.917, self.amt=3031112405.25198 
2023-09-08 08:00:01,602:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230907   120000    155959  ...   15151.927  3.906374e+08 -0.002858
718  20230907   160000    195959  ...   14981.411  3.853597e+08 -0.002151
719  20230907   200000    235959  ...   47604.669  1.223882e+09  0.002771
720  20230908   000000    035959  ...   48160.796  1.245784e+09  0.003897
721  20230908   040000    075959  ...  115647.917  3.031112e+09  0.014408

[5 rows x 11 columns]
2023-09-08 08:00:02,335:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230907   120000    155959  1694073599  ...    717  0.024359 -1.043592    -1.0
718  20230907   160000    195959  1694087999  ...    718  0.025352 -1.041454    -1.0
719  20230907   200000    235959  1694102399  ...    719  0.028042 -1.034925    -1.0
720  20230908   000000    035959  1694116799  ...    720  0.020270 -1.056341    -1.0
721  20230908   040000    075959  1694131199  ...    721  0.049128 -0.974409    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '-19941.32802742596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26241.06485348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


