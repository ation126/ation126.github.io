# 20230820 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28180
self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26094.1, self.close=26109.0, self.high=26109.0, self.low=26084.0, self.vol=350.369, self.amt=9143965.255 
127.0.0.1 - - [20/Aug/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-08-20 08:20:05,728:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230820   075500    075959  ...         0.0        0.0       0
5844  20230820   080000    080459  ...         0.0        0.0       0
5845  20230820   080500    080959  ...         0.0        0.0       0
5846  20230820   081000    081459  ...         0.0        0.0       0
5847  20230820   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 08:20:05,738:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26094.1, self.close=26109.0, self.high=26109.0, self.low=26084.0, self.vol=350.369, self.amt=9143965.255, ukdf['pct'].iloc[-1]=0.000575 , ukdf['amount'].iloc[-1]=9143965.255, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10512.5894508723', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26110.01062395', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=28181
self.closeSec=1692491099, self.tradeDate='20230820', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26109.0, self.close=26110.3, self.high=26115.6, self.low=26108.9, self.vol=391.462, self.amt=10221500.3818 
2023-08-20 08:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230820   080000    080459  ...         0.0        0.0       0
5845  20230820   080500    080959  ...         0.0        0.0       0
5846  20230820   081000    081459  ...         0.0        0.0       0
5847  20230820   081500    081959  ...         0.0        0.0       0
5848  20230820   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 08:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692491099, self.tradeDate='20230820', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26109.0, self.close=26110.3, self.high=26115.6, self.low=26108.9, self.vol=391.462, self.amt=10221500.3818, ukdf['pct'].iloc[-1]=5e-05 , ukdf['amount'].iloc[-1]=10221500.3818, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10481.03422332846', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26112.27654579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [20/Aug/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28178 

self.closeSec=1692489599, self.tradeDate='20230820', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26076.2, self.close=26088.3, self.high=26088.4, self.low=26073.5 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28179 

self.closeSec=1692489899, self.tradeDate='20230820', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26088.4, self.close=26069.9, self.high=26089.0, self.low=26069.8 
127.0.0.1 - - [20/Aug/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28180 

self.closeSec=1692490199, self.tradeDate='20230820', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26069.9, self.close=26069.0, self.high=26069.9, self.low=26069.0 
127.0.0.1 - - [20/Aug/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [20/Aug/2023 08:15:00] "POST / HTTP/1.1" 200 -
 version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28181 

self.closeSec=1692490499, self.tradeDate='20230820', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26069.1, self.close=26094.0, self.high=26094.1, self.low=26069.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28182 

self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26094.1, self.close=26109.0, self.high=26109.0, self.low=26084.0 
127.0.0.1 - - [20/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=28183 

self.closeSec=1692491099, self.tradeDate='20230820', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26109.0, self.close=26110.3, self.high=26115.6, self.low=26108.9 
127.0.0.1 - - [20/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-20 08:00:17,429:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230820    052959  26045.0  ...  43.333333  0.428353  0.453813
5770  20230820    055959  26061.4  ...  43.750000  0.430351  0.450774
5771  20230820    062959  26071.1  ...  43.333333  0.430176  0.448088
5772  20230820    065959  26069.9  ...  42.916667  0.424940  0.450040
5773  20230820    072959  26037.5  ...  43.333333  0.438710  0.443055

[5 rows x 33 columns]
0.5259259259259259
acc is : 0.5259259259259259
2023-08-20 08:00:17,488:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.496420  0.503580       1  ...  1.073166  -1.0    0.0  0.877106
536     1  0.497530  0.502470       0  ...  1.073211  -1.0    0.0  0.877069
537     1  0.492294  0.507706       0  ...  1.074549  -1.0    0.0  0.875975
538     1  0.486568  0.513432       1  ...  1.071899  -1.0    0.0  0.878135
539     0  0.530624  0.469376       0  ...  1.072441  -1.0    0.0  0.877691

[5 rows x 10 columns]
2023-08-20 08:00:17,499:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496015  0.503985       1  ...  1.080108  -1.0    0.0  0.884056
46     1  0.497047  0.502953       0  ...  1.080153  -1.0    0.0  0.883201
47     1  0.491477  0.508523       0  ...  1.081500  -1.0    0.0  0.879556
48     1  0.485929  0.514071       1  ...  1.074130  -1.0    0.0  0.877887
49     0  0.530624  0.469376       0  ...  1.072441  -1.0    0.0  0.877691

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '29.581', 'enterprice': '26067.4', 'countrevence': '0', 'unrealprofit': '-556.60617158441', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26086.21634061', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14087 

self.closeSec=1692487799, self.tradeDate='20230820', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26071.7', self.close='26101.6'
127.0.0.1 - - [20/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  127.0.0.1 - - [20/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14088 

self.closeSec=1692488399, self.tradeDate='20230820', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26101.7', self.close='26101.9'
127.0.0.1 - - [20/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14089 

self.closeSec=1692488999, self.tradeDate='20230820', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26101.9', self.close='26084.4'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14090 

self.closeSec=1692489599, self.tradeDate='20230820', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26084.5', self.close='26088.3'
127.0.0.1 - - [20/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14091 

self.closeSec=1692490199, self.tradeDate='20230820', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26088.4', self.close='26069'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14092 

self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26069.1', self.close='26109'
127.0.0.1 - - [20/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [20/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14090 

self.closeSec=1692487799, self.tradeDate='20230820', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26071.7', self.close='26101.6'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14091 

self.closeSec=1692488399, self.tradeDate='20230820', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26101.7', self.close='26101.9'
127.0.0.1 - - [20/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14092 

self.closeSec=1692488999, self.tradeDate='20230820', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26101.9', self.close='26084.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14093 

self.closeSec=1692489599, self.tradeDate='20230820', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26084.5', self.close='26088.3'
127.0.0.1 - - [20/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14094 

self.closeSec=1692490199, self.tradeDate='20230820', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26088.4', self.close='26069'
127.0.0.1 - - [20/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14095 

self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26069.1', self.close='26109'
127.0.0.1 - - [20/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Aug/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14090 

self.closeSec=1692487799, self.tradeDate='20230820', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26071.7', self.close='26101.6'

--handleKline--: 127.0.0.1 - - [20/Aug/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14091 

self.closeSec=1692488399, self.tradeDate='20230820', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26101.7', self.close='26101.9'
127.0.0.1 - - [20/Aug/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14092 

self.closeSec=1692488999, self.tradeDate='20230820', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26101.9', self.close='26084.4'
127.0.0.1 - - [20/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14093 

self.closeSec=1692489599, self.tradeDate='20230820', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26084.5', self.close='26088.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14094 

self.closeSec=1692490199, self.tradeDate='20230820', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26088.4', self.close='26069'
127.0.0.1 - - [20/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14095 

self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26069.1', self.close='26109'
127.0.0.1 - - [20/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28180
self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26094.1, self.close=26109.0, self.high=26109.0, self.low=26084.0, self.vol=350.369, self.amt=9143965.255 
127.0.0.1 - - [20/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-20 08:20:05,732:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5843  20230820   075500    075959  ...         0.0        0.0       0
5844  20230820   080000    080459  ...         0.0        0.0       0
5845  20230820   080500    080959  ...         0.0        0.0       0
5846  20230820   081000    081459  ...         0.0        0.0       0
5847  20230820   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 08:20:05,740:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692490799, self.tradeDate='20230820', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26094.1, self.close=26109.0, self.high=26109.0, self.low=26084.0, self.vol=350.369, self.amt=9143965.255, ukdf['pct'].iloc[-1]=0.000575 , ukdf['amount'].iloc[-1]=9143965.255, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5847, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27261.09941587305', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26110.01062395', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [20/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=28181
self.closeSec=1692491099, self.tradeDate='20230820', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26109.0, self.close=26110.3, self.high=26115.6, self.low=26108.9, self.vol=391.462, self.amt=10221500.3818 
2023-08-20 08:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5844  20230820   080000    080459  ...         0.0        0.0       0
5845  20230820   080500    080959  ...         0.0        0.0       0
5846  20230820   081000    081459  ...         0.0        0.0       0
5847  20230820   081500    081959  ...         0.0        0.0       0
5848  20230820   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-20 08:25:00,822:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692491099, self.tradeDate='20230820', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26109.0, self.close=26110.3, self.high=26115.6, self.low=26108.9, self.vol=391.462, self.amt=10221500.3818, ukdf['pct'].iloc[-1]=5e-05 , ukdf['amount'].iloc[-1]=10221500.3818, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5848, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27176.94081281361', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26112.27654579', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230819   200000    235959  1692460799  ...    719  0.534194  0.074744     NaN
720  20230820   000000    035959  1692475199  ...    720  0.538999  0.083438     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '170603.0212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26112.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=587
self.closeSec=1692489599, self.tradeDate='20230820', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26112.6, self.close=26088.3, self.high=26143.7, self.low=26016.6, self.vol=15244.606, self.amt=397427940.091 
127.0.0.1 - - [20/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-20 08:00:01,505:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692489599, self.tradeDate='20230820', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26112.6, self.close=26088.3, self.high=26143.7, self.low=26016.6, self.vol=15244.606, self.amt=397427940.091 
2023-08-20 08:00:01,524:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230819   120000    155959  ...  38367.552  9.932486e+08 -0.001995
718  20230819   160000    195959  ...  26956.868  6.987260e+08 -0.000834
719  20230819   200000    235959  ...  50260.815  1.307815e+09  0.012200
720  20230820   000000    035959  ...  42478.706  1.109830e+09 -0.003370
721  20230820   040000    075959  ...  15244.606  3.974279e+08 -0.000934

[5 rows x 11 columns]
2023-08-20 08:00:02,210:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230819   120000    155959  1692431999  ...    717  0.494699 -0.010184     NaN
718  20230819   160000    195959  1692446399  ...    718  0.521104  0.047041     NaN
719  20230819   200000    235959  1692460799  ...    719  0.534194  0.074744     NaN
720  20230820   000000    035959  1692475199  ...    720  0.538999  0.083438     NaN
721  20230820   040000    075959  1692489599  ...    721  0.541444  0.087172     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '171856.8884', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26088.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


