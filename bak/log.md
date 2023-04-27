# 20230427 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43413
self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28557.9, self.close=28855.1, self.high=28860.0, self.low=28549.4, self.vol=12984.717, self.amt=372830628.2428 
127.0.0.1 - - [27/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-27 08:20:06,170:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230427   075500    075959  ...         0.0        0.0       0
5849  20230427   080000    080459  ...         0.0        0.0       0
5850  20230427   080500    080959  ...         0.0        0.0       0
5851  20230427   081000    081459  ...         0.0        0.0       0
5852  20230427   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 08:20:06,176:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28557.9, self.close=28855.1, self.high=28860.0, self.low=28549.4, self.vol=12984.717, self.amt=372830628.2428, ukdf['pct'].iloc[-1]=0.010407 , ukdf['amount'].iloc[-1]=372830628.2428, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-739123.7552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28812', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43414
self.closeSec=1682555099, self.tradeDate='20230427', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28850.1, self.close=29261.1, self.high=29409.5, self.low=28771.5, self.vol=25649.342, self.amt=745871595.46555 
2023-04-27 08:25:02,069:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230427   080000    080459  ...         0.0        0.0       0
5850  20230427   080500    080959  ...         0.0        0.0       0
5851  20230427   081000    081459  ...         0.0        0.0       0
5852  20230427   081500    081959  ...         0.0        0.0       0
5853  20230427   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 08:25:02,069:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682555099, self.tradeDate='20230427', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28850.1, self.close=29261.1, self.high=29409.5, self.low=28771.5, self.vol=25649.342, self.amt=745871595.46555, ukdf['pct'].iloc[-1]=0.01407 , ukdf['amount'].iloc[-1]=745871595.46555, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-767401.22864953024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29281.91281324', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [27/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43975 

self.closeSec=1682553599, self.tradeDate='20230427', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28366.0, self.close=28395.9, self.high=28417.2, self.low=28360.0 
127.0.0.1 - - [27/Apr/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43976 

self.closeSec=1682553899, self.tradeDate='20230427', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28396.0, self.close=28368.0, self.high=28409.9, self.low=28365.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43977 

self.closeSec=1682554199, self.tradeDate='20230427', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28368.1, self.close=28415.8, self.high=28443.8, self.low=28367.4 
127.0.0.1 - - [27/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43978 

self.closeSec=1682554499, self.tradeDate='20230427', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28415.8, self.close=28557.9, self.high=28598.0, self.low=28413.8 
127.0.0.1 - - [27/Apr/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43979 

self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28557.9, self.close=28855.1, self.high=28860.0, self.low=28549.4 
127.0.0.1 - - [27/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=43980 

self.closeSec=1682555099, self.tradeDate='20230427', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28850.1, self.close=29261.1, self.high=29409.5, self.low=28771.5 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-27 08:00:19,370:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230427    052959  28405.4  ...  55.000000  0.493018  0.296160
5770  20230427    055959  28284.1  ...  55.416667  0.521990  0.308778
5771  20230427    062959  28669.9  ...  55.416667  0.498979  0.327617
5772  20230427    065959  28363.9  ...  55.000000  0.492975  0.347112
5773  20230427    072959  28282.3  ...  55.000000  0.498843  0.363484

[5 rows x 33 columns]
0.5407407407407407
acc is : 0.5407407407407407
2023-04-27 08:00:19,465:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
535     1  0.364307  0.635693       1  ...  0.878400  -1.0 -0.0016  0.948109
536     0  0.529354  0.470646       0  ...  0.887645  -1.0  0.0000  0.938130
537     1  0.468975  0.531025       0  ...  0.890201  -1.0  0.0000  0.935428
538     0  0.532336  0.467664       1  ...  0.887750  -1.0  0.0000  0.938005
539     1  0.499349  0.500651       1  ...  0.886629  -1.0  0.0000  0.939189

[5 rows x 10 columns]
2023-04-27 08:00:19,481:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.363982  0.636018       1  ...  0.892168  -1.0 -0.0016  0.945438
46     0  0.529033  0.470967       0  ...  0.887645  -1.0  0.0000  0.936096
47     1  0.468353  0.531647       0  ...  0.904155  -1.0  0.0000  0.933212
48     0  0.531898  0.468102       1  ...  0.887750  -1.0  0.0000  0.937000
49     1  0.499349  0.500651       1  ...  0.886629  -1.0  0.0000  0.939189

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21985 

self.closeSec=1682551799, self.tradeDate='20230427', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28342.6', self.close='28360.1'
127.0.0.1 - - [27/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21986 

self.closeSec=1682552399, self.tradeDate='20230427', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28360', self.close='28299'
127.0.0.1 - - [27/Apr/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21987 

self.closeSec=1682552999, self.tradeDate='20230427', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28299', self.close='28355'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21988 

self.closeSec=1682553599, self.tradeDate='20230427', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28355', self.close='28395.9'
127.0.0.1 - - [27/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [27/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21989 

self.closeSec=1682554199, self.tradeDate='20230427', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28396', self.close='28415.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21990 

self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28415.8', self.close='28855.1'
127.0.0.1 - - [27/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [27/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21986 

self.closeSec=1682551799, self.tradeDate='20230427', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28342.6', self.close='28360.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21987 

self.closeSec=1682552399, self.tradeDate='20230427', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28360', self.close='28299'
127.0.0.1 - - [27/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21988 

self.closeSec=1682552999, self.tradeDate='20230427', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28299', self.close='28355'
127.0.0.1 - - [27/Apr/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21989 

self.closeSec=1682553599, self.tradeDate='20230427', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28355', self.close='28395.9'
127.0.0.1 - - [27/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21990 

self.closeSec=1682554199, self.tradeDate='20230427', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28396', self.close='28415.8'
127.0.0.1 - - [27/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21991 

self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28415.8', self.close='28855.1'
127.0.0.1 - - [27/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21986 

self.closeSec=1682551799, self.tradeDate='20230427', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28342.6', self.close='28360.1'
127.0.0.1 - - [27/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21987 

self.closeSec=1682552399, self.tradeDate='20230427', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28360', self.close='28299'
127.0.0.1 - - [27/Apr/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21988 

self.closeSec=1682552999, self.tradeDate='20230427', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28299', self.close='28355'
127.0.0.1 - - [27/Apr/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21989 

self.closeSec=1682553599, self.tradeDate='20230427', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28355', self.close='28395.9'
127.0.0.1 - - [27/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21990 

self.closeSec=1682554199, self.tradeDate='20230427', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28396', self.close='28415.8'
127.0.0.1 - - [27/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21991 

self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28415.8', self.close='28855.1'
127.0.0.1 - - [27/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39411
self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28557.9, self.close=28855.1, self.high=28860.0, self.low=28549.4, self.vol=12984.717, self.amt=372830628.2428 
127.0.0.1 - - [27/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-27 08:20:04,994:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230427   075500    075959  ...         0.0        0.0       0
5849  20230427   080000    080459  ...         0.0        0.0       0
5850  20230427   080500    080959  ...         0.0        0.0       0
5851  20230427   081000    081459  ...         0.0        0.0       0
5852  20230427   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 08:20:05,009:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682554799, self.tradeDate='20230427', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28557.9, self.close=28855.1, self.high=28860.0, self.low=28549.4, self.vol=12984.717, self.amt=372830628.2428, ukdf['pct'].iloc[-1]=0.010407 , ukdf['amount'].iloc[-1]=372830628.2428, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39412
self.closeSec=1682555099, self.tradeDate='20230427', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28850.1, self.close=29261.1, self.high=29409.5, self.low=28771.5, self.vol=25649.342, self.amt=745871595.46555 
127.0.0.1 - - [27/Apr/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-04-27 08:25:02,070:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230427   080000    080459  ...         0.0        0.0       0
5850  20230427   080500    080959  ...         0.0        0.0       0
5851  20230427   081000    081459  ...         0.0        0.0       0
5852  20230427   081500    081959  ...         0.0        0.0       0
5853  20230427   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-27 08:25:02,070:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682555099, self.tradeDate='20230427', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28850.1, self.close=29261.1, self.high=29409.5, self.low=28771.5, self.vol=25649.342, self.amt=745871595.46555, ukdf['pct'].iloc[-1]=0.01407 , ukdf['amount'].iloc[-1]=745871595.46555, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230426   200000    235959  1682524799  ...    719  1.365592  2.168048     1.0
720  20230427   000000    035959  1682539199  ...    720  1.098689  1.319755     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '-51408.05065782474', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27849.54425794', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [27/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=916
self.closeSec=1682553599, self.tradeDate='20230427', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27871.9, self.close=28395.9, self.high=28729.1, self.low=27200.0, self.vol=333531.894, self.amt=9343429581.63539 
2023-04-27 08:00:02,025:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682553599, self.tradeDate='20230427', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27871.9, self.close=28395.9, self.high=28729.1, self.low=27200.0, self.vol=333531.894, self.amt=9343429581.63539 
2023-04-27 08:00:02,064:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230426   120000    155959  ...   62803.722  1.782336e+09  0.002431
718  20230426   160000    195959  ...  213528.425  6.150918e+09  0.020296
719  20230426   200000    235959  ...  306318.812  9.088141e+09  0.029795
720  20230427   000000    035959  ...  297294.343  8.583094e+09 -0.064551
721  20230427   040000    075959  ...  333531.894  9.343430e+09  0.018534

[5 rows x 11 columns]
2023-04-27 08:00:03,767:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230426   120000    155959  1682495999  ...    717  0.687079 -0.037325     NaN
718  20230426   160000    195959  1682510399  ...    718  0.966401  0.887644     1.0
719  20230426   200000    235959  1682524799  ...    719  1.365592  2.168048     1.0
720  20230427   000000    035959  1682539199  ...    720  1.098689  1.319755     1.0
721  20230427   040000    075959  1682553599  ...    721  0.870679  0.595804     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '-25312.1092890567', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28407.4001627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


