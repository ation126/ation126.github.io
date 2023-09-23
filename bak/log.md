# 20230923 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37972
self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26594.3, self.close=26584.4, self.high=26596.5, self.low=26579.0, self.vol=194.891, self.amt=5181326.5216 
127.0.0.1 - - [23/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-23 08:20:06,314:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230923   075500    075959  ...         0.0        0.0       0
5856  20230923   080000    080459  ...         0.0        0.0       0
5857  20230923   080500    080959  ...         0.0        0.0       0
5858  20230923   081000    081459  ...         0.0        0.0       0
5859  20230923   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 08:20:06,318:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26594.3, self.close=26584.4, self.high=26596.5, self.low=26579.0, self.vol=194.891, self.amt=5181326.5216, ukdf['pct'].iloc[-1]=-0.000372 , ukdf['amount'].iloc[-1]=5181326.5216, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3801.798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26591.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37973
self.closeSec=1695428699, self.tradeDate='20230923', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26589.4, self.close=26579.7, self.high=26592.6, self.low=26576.9, self.vol=210.688, self.amt=5601302.3455 
127.0.0.1 - - [23/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-09-23 08:25:00,854:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230923   080000    080459  ...         0.0        0.0       0
5857  20230923   080500    080959  ...         0.0        0.0       0
5858  20230923   081000    081459  ...         0.0        0.0       0
5859  20230923   081500    081959  ...         0.0        0.0       0
5860  20230923   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 08:25:00,854:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695428699, self.tradeDate='20230923', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26589.4, self.close=26579.7, self.high=26592.6, self.low=26576.9, self.vol=210.688, self.amt=5601302.3455, ukdf['pct'].iloc[-1]=-0.000177 , ukdf['amount'].iloc[-1]=5601302.3455, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3971.6952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26579.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [23/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37970 

self.closeSec=1695427199, self.tradeDate='20230923', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26565.0, self.close=26566.7, self.high=26570.0, self.low=26558.3 
127.0.0.1 - - [23/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37971 

self.closeSec=1695427499, self.tradeDate='20230923', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26566.7, self.close=26581.1, self.high=26581.1, self.low=26563.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37972 

self.closeSec=1695427799, self.tradeDate='20230923', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26581.2, self.close=26584.0, self.high=26587.8, self.low=26575.0 
127.0.0.1 - - [23/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37973 

self.closeSec=1695428099, self.tradeDate='20230923', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26583.9, self.close=26594.3, self.high=26606.2, self.low=26581.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37974 

self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26594.3, self.close=26584.4, self.high=26596.5, self.low=26579.0 
127.0.0.1 - - [23/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37975 

self.closeSec=1695428699, self.tradeDate='20230923', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26589.4, self.close=26579.7, self.high=26592.6, self.low=26576.9 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-23 08:00:16,977:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230923    052959  26529.8  ...  48.333333  0.446383  0.571476
5770  20230923    055959  26525.1  ...  48.333333  0.458633  0.577038
5771  20230923    062959  26561.4  ...  48.333333  0.455544  0.584929
5772  20230923    065959  26550.6  ...  48.333333  0.462826  0.586969
5773  20230923    072959  26572.0  ...  48.333333  0.461566  0.589937

[5 rows x 33 columns]
0.5351851851851852
acc is : 0.5351851851851852
2023-09-23 08:00:17,044:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.494922  0.505078       1  ...  0.951011  -1.0    0.0  1.053606
536     0  0.506149  0.493851       0  ...  0.951402  -1.0    0.0  1.053173
537     1  0.495525  0.504475       1  ...  0.950631  -1.0    0.0  1.054026
538     0  0.505721  0.494279       0  ...  0.950785  -1.0    0.0  1.053856
539     1  0.498501  0.501499       0  ...  0.950821  -1.0    0.0  1.053816

[5 rows x 10 columns]
2023-09-23 08:00:17,055:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495067  0.504933       1  ...  0.951011  -1.0    0.0  1.058076
46     0  0.505714  0.494286       0  ...  0.951402  -1.0    0.0  1.053834
47     1  0.495704  0.504296       1  ...  0.950631  -1.0    0.0  1.055475
48     0  0.505971  0.494029       0  ...  0.950785  -1.0    0.0  1.057779
49     1  0.498501  0.501499       0  ...  0.950821  -1.0    0.0  1.053816

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14518.3712149665', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26565.82262505', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [23/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18983 

self.closeSec=1695425399, self.tradeDate='20230923', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26556.3', self.close='26567.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18984 

self.closeSec=1695425999, self.tradeDate='20230923', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26567.8', self.close='26577.9'
127.0.0.1 - - [23/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18985 

self.closeSec=1695426599, self.tradeDate='20230923', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26578', self.close='26566.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18986 

self.closeSec=1695427199, self.tradeDate='20230923', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26566.3', self.close='26566.7'
127.0.0.1 - - [23/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18987 

self.closeSec=1695427799, self.tradeDate='20230923', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26566.7', self.close='26584'
127.0.0.1 - - [23/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18988 

self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26583.9', self.close='26589.5'
127.0.0.1 - - [23/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18986 

self.closeSec=1695425399, self.tradeDate='20230923', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26556.3', self.close='26567.7'
127.0.0.1 - - [23/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18987 

self.closeSec=1695425999, self.tradeDate='20230923', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26567.8', self.close='26577.9'
127.0.0.1 - - [23/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18988 

self.closeSec=1695426599, self.tradeDate='20230923', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26578', self.close='26566.3'
127.0.0.1 - - [23/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18989 

self.closeSec=1695427199, self.tradeDate='20230923', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26566.3', self.close='26566.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18990 

self.closeSec=1695427799, self.tradeDate='20230923', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26566.7', self.close='26584'
127.0.0.1 - - [23/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18991 

self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26583.9', self.close='26589.5'
127.0.0.1 - - [23/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18986 

self.closeSec=1695425399, self.tradeDate='20230923', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26556.3', self.close='26567.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18987 

self.closeSec=1695425999, self.tradeDate='20230923', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26567.8', self.close='26577.9'
127.0.0.1 - - [23/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18988 

self.closeSec=1695426599, self.tradeDate='20230923', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26578', self.close='26566.3'
127.0.0.1 - - [23/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [23/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18989 

self.closeSec=1695427199, self.tradeDate='20230923', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26566.3', self.close='26566.7'
127.0.0.1 - - [23/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18990 

self.closeSec=1695427799, self.tradeDate='20230923', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26566.7', self.close='26584'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18991 

self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26583.9', self.close='26589.5'
127.0.0.1 - - [23/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37972
self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26594.3, self.close=26584.4, self.high=26596.5, self.low=26579.0, self.vol=194.891, self.amt=5181326.5216 
127.0.0.1 - - [23/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-23 08:20:06,318:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230923   075500    075959  ...         0.0        0.0       0
5856  20230923   080000    080459  ...         0.0        0.0       0
5857  20230923   080500    080959  ...         0.0        0.0       0
5858  20230923   081000    081459  ...         0.0        0.0       0
5859  20230923   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 08:20:06,329:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695428399, self.tradeDate='20230923', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26594.3, self.close=26584.4, self.high=26596.5, self.low=26579.0, self.vol=194.891, self.amt=5181326.5216, ukdf['pct'].iloc[-1]=-0.000372 , ukdf['amount'].iloc[-1]=5181326.5216, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-9363.2461', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26591.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [23/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37973
self.closeSec=1695428699, self.tradeDate='20230923', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26589.4, self.close=26579.7, self.high=26592.6, self.low=26576.9, self.vol=210.688, self.amt=5601302.3455 
2023-09-23 08:25:00,826:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230923   080000    080459  ...         0.0        0.0       0
5857  20230923   080500    080959  ...         0.0        0.0       0
5858  20230923   081000    081459  ...         0.0        0.0       0
5859  20230923   081500    081959  ...         0.0        0.0       0
5860  20230923   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-23 08:25:00,826:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695428699, self.tradeDate='20230923', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26589.4, self.close=26579.7, self.high=26592.6, self.low=26576.9, self.vol=210.688, self.amt=5601302.3455, ukdf['pct'].iloc[-1]=-0.000177 , ukdf['amount'].iloc[-1]=5601302.3455, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-9816.3663', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26579.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230922   200000    235959  1695398399  ...    719  0.798307  0.930515     1.0
720  20230923   000000    035959  1695412799  ...    720  0.869762  1.101778     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-36602.1909', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26530.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [23/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=791
self.closeSec=1695427199, self.tradeDate='20230923', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26525.0, self.close=26566.7, self.high=26588.0, self.low=26468.5, self.vol=20007.182, self.amt=530953498.405 
2023-09-23 08:00:01,548:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695427199, self.tradeDate='20230923', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26525.0, self.close=26566.7, self.high=26588.0, self.low=26468.5, self.vol=20007.182, self.amt=530953498.405 
2023-09-23 08:00:01,562:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230922   120000    155959  ...  22748.224  6.058066e+08  0.001664
718  20230922   160000    195959  ...  29532.864  7.868368e+08 -0.001155
719  20230922   200000    235959  ...  37446.547  9.966943e+08 -0.000383
720  20230923   000000    035959  ...  26686.848  7.092073e+08 -0.003486
721  20230923   040000    075959  ...  20007.182  5.309535e+08  0.001493

[5 rows x 11 columns]
2023-09-23 08:00:02,254:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230922   120000    155959  1695369599  ...    717  0.653103  0.571336     NaN
718  20230922   160000    195959  1695383999  ...    718  0.669128  0.598612     NaN
719  20230922   200000    235959  1695398399  ...    719  0.798307  0.930515     1.0
720  20230923   000000    035959  1695412799  ...    720  0.869762  1.101778     1.0
721  20230923   040000    075959  1695427199  ...    721  1.134255  1.774907     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-34712.64784539585', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26567.90525045', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


