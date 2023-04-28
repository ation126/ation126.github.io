# 20230428 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43701
self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29412.8, self.close=29418.4, self.high=29418.4, self.low=29366.7, self.vol=1895.107, self.amt=55696343.5569 
127.0.0.1 - - [28/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-28 08:20:06,312:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230428   075500    075959  ...         0.0        0.0       0
5849  20230428   080000    080459  ...         0.0        0.0       0
5850  20230428   080500    080959  ...         0.0        0.0       0
5851  20230428   081000    081459  ...         0.0        0.0       0
5852  20230428   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 08:20:06,322:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29412.8, self.close=29418.4, self.high=29418.4, self.low=29366.7, self.vol=1895.107, self.amt=55696343.5569, ukdf['pct'].iloc[-1]=0.00019 , ukdf['amount'].iloc[-1]=55696343.5569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-776276.4176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29429.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=43702
self.closeSec=1682641499, self.tradeDate='20230428', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29418.4, self.close=29382.8, self.high=29463.1, self.low=29382.8, self.vol=1242.05, self.amt=36548296.4099 
127.0.0.1 - - [28/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-28 08:25:01,565:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230428   080000    080459  ...         0.0        0.0       0
5850  20230428   080500    080959  ...         0.0        0.0       0
5851  20230428   081000    081459  ...         0.0        0.0       0
5852  20230428   081500    081959  ...         0.0        0.0       0
5853  20230428   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 08:25:01,566:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1682641499, self.tradeDate='20230428', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29418.4, self.close=29382.8, self.high=29463.1, self.low=29382.8, self.vol=1242.05, self.amt=36548296.4099, ukdf['pct'].iloc[-1]=-0.00121 , ukdf['amount'].iloc[-1]=36548296.4099, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-773653.18051489872', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29385.80725397', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44263 

self.closeSec=1682639999, self.tradeDate='20230428', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29456.6, self.close=29459.0, self.high=29471.0, self.low=29447.5 
127.0.0.1 - - [28/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44264 

self.closeSec=1682640299, self.tradeDate='20230428', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=29459.0, self.close=29467.3, self.high=29486.4, self.low=29442.0 
127.0.0.1 - - [28/Apr/2023 08:05:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44265 

self.closeSec=1682640599, self.tradeDate='20230428', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=29467.5, self.close=29481.9, self.high=29520.0, self.low=29438.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44266 

self.closeSec=1682640899, self.tradeDate='20230428', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=29482.0, self.close=29412.8, self.high=29482.0, self.low=29408.0 
127.0.0.1 - - [28/Apr/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44267 

self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29412.8, self.close=29418.4, self.high=29418.4, self.low=29366.7 
127.0.0.1 - - [28/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=44268 

self.closeSec=1682641499, self.tradeDate='20230428', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29418.4, self.close=29382.8, self.high=29463.1, self.low=29382.8 
127.0.0.1 - - [28/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-28 08:00:18,628:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230428    052959  29610.0  ...  55.833333  0.573970  0.255742
5770  20230428    055959  29690.0  ...  55.416667  0.568220  0.252542
5771  20230428    062959  29631.1  ...  55.000000  0.562346  0.252682
5772  20230428    065959  29570.7  ...  54.583333  0.543786  0.262933
5773  20230428    072959  29375.5  ...  55.000000  0.550283  0.268159

[5 rows x 33 columns]
0.5537037037037037
acc is : 0.5537037037037037
2023-04-28 08:00:18,731:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.521141  0.478859       0  ...  0.842851   1.0    0.0  0.978179
536     0  0.502850  0.497150       0  ...  0.841136   1.0    0.0  0.976188
537     1  0.496790  0.503210       0  ...  0.835586   1.0    0.0  0.969748
538     1  0.467301  0.532699       1  ...  0.837967   1.0    0.0  0.972511
539     0  0.518032  0.481968       0  ...  0.837959   1.0    0.0  0.972501

[5 rows x 10 columns]
2023-04-28 08:00:18,743:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.519795  0.480205       0  ...  0.868500   1.0    0.0  0.977127
46     0  0.502524  0.497476       0  ...  0.841136   1.0    0.0  0.976701
47     1  0.495983  0.504017       0  ...  0.835586   1.0    0.0  0.968376
48     1  0.466878  0.533122       1  ...  0.837967   1.0    0.0  0.971395
49     0  0.518032  0.481968       0  ...  0.837959   1.0    0.0  0.972501

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22129 

self.closeSec=1682638199, self.tradeDate='20230428', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29440.5', self.close='29459.3'
127.0.0.1 - - [28/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22130 

self.closeSec=1682638799, self.tradeDate='20230428', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29459.4', self.close='29450.7'
127.0.0.1 - - [28/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22131 

self.closeSec=1682639399, self.tradeDate='20230428', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29450.7', self.close='29420.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22132 

self.closeSec=1682639999, self.tradeDate='20230428', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29420.7', self.close='29459'
127.0.0.1 - - [28/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22133 

self.closeSec=1682640599, self.tradeDate='20230428', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29459', self.close='29481.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22134 

self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29482', self.close='29418.4'
127.0.0.1 - - [28/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [28/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22130 

self.closeSec=1682638199, self.tradeDate='20230428', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29440.5', self.close='29459.3'
127.0.0.1 - - [28/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22131 

self.closeSec=1682638799, self.tradeDate='20230428', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29459.4', self.close='29450.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22132 

self.closeSec=1682639399, self.tradeDate='20230428', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29450.7', self.close='29420.7'
127.0.0.1 - - [28/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22133 

self.closeSec=1682639999, self.tradeDate='20230428', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29420.7', self.close='29459'
127.0.0.1 - - [28/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22134 

self.closeSec=1682640599, self.tradeDate='20230428', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29459', self.close='29481.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22135 

self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29482', self.close='29418.4'
127.0.0.1 - - [28/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22130 

self.closeSec=1682638199, self.tradeDate='20230428', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='29440.5', self.close='29459.3'
127.0.0.1 - - [28/Apr/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [28/Apr/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22131 

self.closeSec=1682638799, self.tradeDate='20230428', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='29459.4', self.close='29450.7'
127.0.0.1 - - [28/Apr/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22132 

self.closeSec=1682639399, self.tradeDate='20230428', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='29450.7', self.close='29420.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22133 

self.closeSec=1682639999, self.tradeDate='20230428', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='29420.7', self.close='29459'
127.0.0.1 - - [28/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22134 

self.closeSec=1682640599, self.tradeDate='20230428', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29459', self.close='29481.9'
127.0.0.1 - - [28/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22135 

self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29482', self.close='29418.4'
127.0.0.1 - - [28/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39699
self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29412.8, self.close=29418.4, self.high=29418.4, self.low=29366.7, self.vol=1895.107, self.amt=55696343.5569 
127.0.0.1 - - [28/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-28 08:20:06,313:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5848  20230428   075500    075959  ...         0.0        0.0       0
5849  20230428   080000    080459  ...         0.0        0.0       0
5850  20230428   080500    080959  ...         0.0        0.0       0
5851  20230428   081000    081459  ...         0.0        0.0       0
5852  20230428   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 08:20:06,330:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682641199, self.tradeDate='20230428', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29412.8, self.close=29418.4, self.high=29418.4, self.low=29366.7, self.vol=1895.107, self.amt=55696343.5569, ukdf['pct'].iloc[-1]=0.00019 , ukdf['amount'].iloc[-1]=55696343.5569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5852, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=39700
self.closeSec=1682641499, self.tradeDate='20230428', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29418.4, self.close=29382.8, self.high=29463.1, self.low=29382.8, self.vol=1242.05, self.amt=36548296.4099 
127.0.0.1 - - [28/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-28 08:25:01,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5849  20230428   080000    080459  ...         0.0        0.0       0
5850  20230428   080500    080959  ...         0.0        0.0       0
5851  20230428   081000    081459  ...         0.0        0.0       0
5852  20230428   081500    081959  ...         0.0        0.0       0
5853  20230428   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-28 08:25:01,572:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1682641499, self.tradeDate='20230428', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29418.4, self.close=29382.8, self.high=29463.1, self.low=29382.8, self.vol=1242.05, self.amt=36548296.4099, ukdf['pct'].iloc[-1]=-0.00121 , ukdf['amount'].iloc[-1]=36548296.4099, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5853, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230427   200000    235959  1682611199  ...    719  0.972886  0.997366     1.0
720  20230428   000000    035959  1682625599  ...    720  1.016249  1.156824     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '33568.6104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29666.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1352827.6996185002, self.flagDict['side']='buy', self.tradeCount=32, self.count=922
self.closeSec=1682639999, self.tradeDate='20230428', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29659.9, self.close=29459.0, self.high=29781.7, self.low=29239.2, self.vol=98577.491, self.amt=2912385355.55719 
127.0.0.1 - - [28/Apr/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-04-28 08:00:02,172:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1682639999, self.tradeDate='20230428', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29659.9, self.close=29459.0, self.high=29781.7, self.low=29239.2, self.vol=98577.491, self.amt=2912385355.55719 
2023-04-28 08:00:02,208:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230427   120000    155959  ...  112459.212  3.256536e+09  0.000118
718  20230427   160000    195959  ...   98201.412  2.844151e+09  0.001427
719  20230427   200000    235959  ...  206699.481  6.004047e+09  0.007451
720  20230428   000000    035959  ...  204824.129  6.045769e+09  0.017957
721  20230428   040000    075959  ...   98577.491  2.912385e+09 -0.006773

[5 rows x 11 columns]
2023-04-28 08:00:04,087:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230427   120000    155959  1682582399  ...    717  1.012936  1.100041     1.0
718  20230427   160000    195959  1682596799  ...    718  0.910117  0.768211     1.0
719  20230427   200000    235959  1682611199  ...    719  0.972886  0.997366     1.0
720  20230428   000000    035959  1682625599  ...    720  1.016249  1.156824     1.0
721  20230428   040000    075959  1682639999  ...    721  0.951217  0.942706     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.779', 'enterprice': '28948.5', 'countrevence': '0', 'unrealprofit': '23981.59739584407', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29461.15733333', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


