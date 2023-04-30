# 20230430 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44277
self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29197.3, self.close=29198.0, self.high=29202.8, self.low=29190.0, self.vol=288.2, self.amt=8414314.0367 
127.0.0.1 - - [30/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-30 08:20:06,741:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230430   075500    075959  ...         0.0        0.0       0
5849  20230430   080000    080459  ...         0.0        0.0       0
5850  20230430   080500    080959  ...         0.0        0.0       0
5851  20230430   081000    081459  ...         0.0        0.0       0
5852  20230430   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 08:20:06,752:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29197.3, self.close=29198.0, self.high=29202.8, self.low=29190.0, self.vol=288.2, self.amt=8414314.0367, ukdf['pct'].iloc[-1]=2.4e-05 , ukdf['amount'].iloc[-1]=8414314.0367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-762173.73214232448', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29195.04269048', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44278
self.closeSec=1682814299, self.tradeDate='20230430', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29198.0, self.close=29193.4, self.high=29198.1, self.low=29175.6, self.vol=334.431, self.amt=9761328.6384 
2023-04-30 08:25:02,186:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230430   080000    080459  ...         0.0        0.0       0
5850  20230430   080500    080959  ...         0.0        0.0       0
5851  20230430   081000    081459  ...         0.0        0.0       0
5852  20230430   081500    081959  ...         0.0        0.0       0
5853  20230430   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 08:25:02,186:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682814299, self.tradeDate='20230430', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29198.0, self.close=29193.4, self.high=29198.1, self.low=29175.6, self.vol=334.431, self.amt=9761328.6384, ukdf['pct'].iloc[-1]=-0.000158 , ukdf['amount'].iloc[-1]=9761328.6384, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-762068.864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29193.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [30/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44839 

self.closeSec=1682812799, self.tradeDate='20230430', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29201.2, self.close=29212.7, self.high=29230.0, self.low=29201.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44840 

self.closeSec=1682813099, self.tradeDate='20230430', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29212.7, self.close=29209.6, self.high=29217.7, self.low=29207.9 
127.0.0.1 - - [30/Apr/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44841 

self.closeSec=1682813399, self.tradeDate='20230430', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29209.6, self.close=29204.2, self.high=29210.6, self.low=29198.2 
127.0.0.1 - - [30/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44842 

self.closeSec=1682813699, self.tradeDate='20230430', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29204.2, self.close=29197.3, self.high=29210.9, self.low=29197.3 
127.0.0.1 - - [30/Apr/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44843 

self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29197.3, self.close=29198.0, self.high=29202.8, self.low=29190.0 
127.0.0.1 - - [30/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44844 

self.closeSec=1682814299, self.tradeDate='20230430', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29198.0, self.close=29193.4, self.high=29198.1, self.low=29175.6 
127.0.0.1 - - [30/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-30 08:00:19,256:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230430    052959  29205.8  ...  50.833333  0.498240  0.486966
5770  20230430    055959  29211.1  ...  50.833333  0.499863  0.488309
5771  20230430    062959  29219.0  ...  50.416667  0.494517  0.493500
5772  20230430    065959  29192.7  ...  50.000000  0.493120  0.499367
5773  20230430    072959  29186.1  ...  49.583333  0.487153  0.509188

[5 rows x 33 columns]
0.5648148148148148
acc is : 0.5648148148148148
2023-04-30 08:00:19,357:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.513671  0.486329       1  ...  0.864310  -1.0    0.0  0.973532
536     0  0.510369  0.489631       0  ...  0.865085  -1.0    0.0  0.972659
537     0  0.503526  0.496474       0  ...  0.865286  -1.0    0.0  0.972432
538     0  0.506286  0.493714       0  ...  0.866143  -1.0    0.0  0.971469
539     0  0.502670  0.497330       1  ...  0.864492  -1.0    0.0  0.973322

[5 rows x 10 columns]
2023-04-30 08:00:19,382:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.513618  0.486382       1  ...  0.864310  -1.0    0.0  0.968472
46     0  0.509869  0.490131       0  ...  0.891410  -1.0    0.0  0.966966
47     0  0.502823  0.497177       0  ...  0.891617  -1.0    0.0  0.966114
48     0  0.505927  0.494073       0  ...  0.892500  -1.0    0.0  0.966510
49     0  0.502670  0.497330       1  ...  0.864492  -1.0    0.0  0.973322

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22417 

self.closeSec=1682810999, self.tradeDate='20230430', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29173.9', self.close='29157.1'
127.0.0.1 - - [30/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22418 

self.closeSec=1682811599, self.tradeDate='20230430', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29157.1', self.close='29168'
127.0.0.1 - - [30/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22419 

self.closeSec=1682812199, self.tradeDate='20230430', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29167.9', self.close='29186.3'
127.0.0.1 - - [30/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22420 

self.closeSec=1682812799, self.tradeDate='20230430', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29186.3', self.close='29212.7'
127.0.0.1 - - [30/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22421 

self.closeSec=1682813399, self.tradeDate='20230430', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29212.7', self.close='29204.2'
127.0.0.1 - - [30/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22422 

self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29204.2', self.close='29198'
127.0.0.1 - - [30/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22418 

self.closeSec=1682810999, self.tradeDate='20230430', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29173.9', self.close='29157.1'
127.0.0.1 - - [30/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22419 

self.closeSec=1682811599, self.tradeDate='20230430', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29157.1', self.close='29168'
127.0.0.1 - - [30/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22420 

self.closeSec=1682812199, self.tradeDate='20230430', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29167.9', self.close='29186.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22421 

self.closeSec=1682812799, self.tradeDate='20230430', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29186.3', self.close='29212.7'
127.0.0.1 - - [30/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22422 

self.closeSec=1682813399, self.tradeDate='20230430', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29212.7', self.close='29204.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22423 

self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29204.2', self.close='29198'
127.0.0.1 - - [30/Apr/2023 08:20:06] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22418 

self.closeSec=1682810999, self.tradeDate='20230430', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29173.9', self.close='29157.1'
127.0.0.1 - - [30/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [30/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22419 

self.closeSec=1682811599, self.tradeDate='20230430', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29157.1', self.close='29168'
127.0.0.1 - - [30/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22420 

self.closeSec=1682812199, self.tradeDate='20230430', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29167.9', self.close='29186.3'
127.0.0.1 - - [30/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22421 

self.closeSec=1682812799, self.tradeDate='20230430', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29186.3', self.close='29212.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22422 

self.closeSec=1682813399, self.tradeDate='20230430', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29212.7', self.close='29204.2'
127.0.0.1 - - [30/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22423 

self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29204.2', self.close='29198'
127.0.0.1 - - [30/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40275
self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29197.3, self.close=29198.0, self.high=29202.8, self.low=29190.0, self.vol=288.2, self.amt=8414314.0367 
127.0.0.1 - - [30/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-30 08:20:06,689:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230430   075500    075959  ...         0.0        0.0       0
5849  20230430   080000    080459  ...         0.0        0.0       0
5850  20230430   080500    080959  ...         0.0        0.0       0
5851  20230430   081000    081459  ...         0.0        0.0       0
5852  20230430   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 08:20:06,696:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682813999, self.tradeDate='20230430', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29197.3, self.close=29198.0, self.high=29202.8, self.low=29190.0, self.vol=288.2, self.amt=8414314.0367, ukdf['pct'].iloc[-1]=2.4e-05 , ukdf['amount'].iloc[-1]=8414314.0367, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [30/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40276
self.closeSec=1682814299, self.tradeDate='20230430', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29198.0, self.close=29193.4, self.high=29198.1, self.low=29175.6, self.vol=334.431, self.amt=9761328.6384 
2023-04-30 08:25:02,151:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230430   080000    080459  ...         0.0        0.0       0
5850  20230430   080500    080959  ...         0.0        0.0       0
5851  20230430   081000    081459  ...         0.0        0.0       0
5852  20230430   081500    081959  ...         0.0        0.0       0
5853  20230430   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-30 08:25:02,151:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682814299, self.tradeDate='20230430', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29198.0, self.close=29193.4, self.high=29198.1, self.low=29175.6, self.vol=334.431, self.amt=9761328.6384, ukdf['pct'].iloc[-1]=-0.000158 , ukdf['amount'].iloc[-1]=9761328.6384, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230429   200000    235959  1682783999  ...    719  0.222407 -1.497885    -1.0
720  20230430   000000    035959  1682798399  ...    720  0.117851 -1.833244    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '5488.02371127024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29223.82871032', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [30/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=934
self.closeSec=1682812799, self.tradeDate='20230430', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29222.1, self.close=29212.7, self.high=29258.6, self.low=29115.6, self.vol=19822.623, self.amt=578736366.0703 
2023-04-30 08:00:02,164:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682812799, self.tradeDate='20230430', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29222.1, self.close=29212.7, self.high=29258.6, self.low=29115.6, self.vol=19822.623, self.amt=578736366.0703 
2023-04-30 08:00:02,239:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230429   120000    155959  ...  36929.533  1.083732e+09  0.000174
718  20230429   160000    195959  ...  35064.791  1.026637e+09 -0.000358
719  20230429   200000    235959  ...  38754.353  1.136095e+09 -0.002227
720  20230430   000000    035959  ...  47665.322  1.390575e+09 -0.001234
721  20230430   040000    075959  ...  19822.623  5.787364e+08 -0.000318

[5 rows x 11 columns]
2023-04-30 08:00:03,948:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230429   120000    155959  1682755199  ...    717  0.428820 -0.812974    -1.0
718  20230429   160000    195959  1682769599  ...    718  0.328351 -1.150894    -1.0
719  20230429   200000    235959  1682783999  ...    719  0.222407 -1.497885    -1.0
720  20230430   000000    035959  1682798399  ...    720  0.117851 -1.833244    -1.0
721  20230430   040000    075959  1682812799  ...    721  0.041425 -2.057776    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '5879.80832854408', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29215.44255044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


