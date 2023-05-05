# 20230505 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45717
self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28837.8, self.close=28846.8, self.high=28846.9, self.low=28802.8, self.vol=764.172, self.amt=22027400.6015 
127.0.0.1 - - [05/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-05 08:20:06,476:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230505   075500    075959  ...         0.0        0.0       0
5856  20230505   080000    080459  ...         0.0        0.0       0
5857  20230505   080500    080959  ...         0.0        0.0       0
5858  20230505   081000    081459  ...         0.0        0.0       0
5859  20230505   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 08:20:06,487:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28837.8, self.close=28846.8, self.high=28846.9, self.low=28802.8, self.vol=764.172, self.amt=22027400.6015, ukdf['pct'].iloc[-1]=0.000312 , ukdf['amount'].iloc[-1]=22027400.6015, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-740997.18738558112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28843.13254762', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=45718
self.closeSec=1683246299, self.tradeDate='20230505', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28846.8, self.close=28824.8, self.high=28846.9, self.low=28824.6, self.vol=364.39, self.amt=10507156.1318 
127.0.0.1 - - [05/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-05 08:25:02,097:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230505   080000    080459  ...         0.0        0.0       0
5857  20230505   080500    080959  ...         0.0        0.0       0
5858  20230505   081000    081459  ...         0.0        0.0       0
5859  20230505   081500    081959  ...         0.0        0.0       0
5860  20230505   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 08:25:02,098:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683246299, self.tradeDate='20230505', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28846.8, self.close=28824.8, self.high=28846.9, self.low=28824.6, self.vol=364.39, self.amt=10507156.1318, ukdf['pct'].iloc[-1]=-0.000763 , ukdf['amount'].iloc[-1]=10507156.1318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-740029.93651006096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28827.05884921', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46279 

self.closeSec=1683244799, self.tradeDate='20230505', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28809.9, self.close=28826.0, self.high=28829.0, self.low=28809.5 
127.0.0.1 - - [05/May/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46280 

self.closeSec=1683245099, self.tradeDate='20230505', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=28826.0, self.close=28824.7, self.high=28833.6, self.low=28818.1 
127.0.0.1 - - [05/May/2023 08:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46281 

self.closeSec=1683245399, self.tradeDate='20230505', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=28824.7, self.close=28837.1, self.high=28842.1, self.low=28818.0 
127.0.0.1 - - [05/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46282 

self.closeSec=1683245699, self.tradeDate='20230505', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=28837.1, self.close=28837.8, self.high=28842.2, self.low=28824.4 
127.0.0.1 - - [05/May/2023 08:15:03] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46283 

self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28837.8, self.close=28846.8, self.high=28846.9, self.low=28802.8 
127.0.0.1 - - [05/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 08:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=46284 

self.closeSec=1683246299, self.tradeDate='20230505', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28846.8, self.close=28824.8, self.high=28846.9, self.low=28824.6 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-05 08:00:18,595:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230505    052959  28856.8  ...  51.250000  0.503518  0.529316
5770  20230505    055959  28803.9  ...  51.250000  0.507822  0.544954
5771  20230505    062959  28830.1  ...  51.250000  0.494465  0.566957
5772  20230505    065959  28750.0  ...  51.666667  0.496627  0.586308
5773  20230505    072959  28762.9  ...  52.083333  0.506979  0.598666

[5 rows x 33 columns]
0.5574074074074075
acc is : 0.5574074074074075
2023-05-05 08:00:18,683:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.485430  0.514570       1  ...  0.898799  -1.0    0.0  1.048337
536     0  0.500857  0.499143       0  ...  0.901293  -1.0    0.0  1.045428
537     1  0.470850  0.529150       1  ...  0.900891  -1.0    0.0  1.045893
538     1  0.492290  0.507710       1  ...  0.898962  -1.0    0.0  1.048133
539     0  0.506818  0.493182       1  ...  0.898912  -1.0    0.0  1.048192

[5 rows x 10 columns]
2023-05-05 08:00:18,708:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485882  0.514118       1  ...  0.889593  -1.0    0.0  1.049883
46     0  0.500959  0.499041       0  ...  0.901293  -1.0    0.0  1.044509
47     1  0.470341  0.529659       1  ...  0.900891  -1.0    0.0  1.043261
48     1  0.492004  0.507996       1  ...  0.898962  -1.0    0.0  1.047022
49     0  0.506818  0.493182       1  ...  0.898912  -1.0    0.0  1.048192

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23137 

self.closeSec=1683242999, self.tradeDate='20230505', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28818.1', self.close='28824.4'
127.0.0.1 - - [05/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23138 

self.closeSec=1683243599, self.tradeDate='20230505', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28824.5', self.close='28842'
127.0.0.1 - - [05/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23139 

self.closeSec=1683244199, self.tradeDate='20230505', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28842', self.close='28821.9'
127.0.0.1 - - [05/May/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23140 

self.closeSec=1683244799, self.tradeDate='20230505', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28821.9', self.close='28826'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23141 

self.closeSec=1683245399, self.tradeDate='20230505', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28826', self.close='28837.1'
127.0.0.1 - - [05/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23142 

self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28837.1', self.close='28846.8'
127.0.0.1 - - [05/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [05/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23138 

self.closeSec=1683242999, self.tradeDate='20230505', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28818.1', self.close='28824.4'
127.0.0.1 - - [05/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23139 

self.closeSec=1683243599, self.tradeDate='20230505', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28824.5', self.close='28842'
127.0.0.1 - - [05/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23140 

self.closeSec=1683244199, self.tradeDate='20230505', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28842', self.close='28821.9'
127.0.0.1 - - [05/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23141 

self.closeSec=1683244799, self.tradeDate='20230505', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28821.9', self.close='28826'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23142 

self.closeSec=1683245399, self.tradeDate='20230505', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28826', self.close='28837.1'
127.0.0.1 - - [05/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23143 

self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28837.1', self.close='28846.8'
127.0.0.1 - - [05/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23138 

self.closeSec=1683242999, self.tradeDate='20230505', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='28818.1', self.close='28824.4'
127.0.0.1 - - [05/May/2023 07:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [05/May/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23139 

self.closeSec=1683243599, self.tradeDate='20230505', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='28824.5', self.close='28842'
127.0.0.1 - - [05/May/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23140 

self.closeSec=1683244199, self.tradeDate='20230505', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='28842', self.close='28821.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23141 

self.closeSec=1683244799, self.tradeDate='20230505', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='28821.9', self.close='28826'
127.0.0.1 - - [05/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23142 

self.closeSec=1683245399, self.tradeDate='20230505', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28826', self.close='28837.1'
127.0.0.1 - - [05/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23143 

self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28837.1', self.close='28846.8'
127.0.0.1 - - [05/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41715
self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28837.8, self.close=28846.8, self.high=28846.9, self.low=28802.8, self.vol=764.172, self.amt=22027400.6015 
127.0.0.1 - - [05/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-05 08:20:06,478:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230505   075500    075959  ...         0.0        0.0       0
5856  20230505   080000    080459  ...         0.0        0.0       0
5857  20230505   080500    080959  ...         0.0        0.0       0
5858  20230505   081000    081459  ...         0.0        0.0       0
5859  20230505   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 08:20:06,487:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683245999, self.tradeDate='20230505', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28837.8, self.close=28846.8, self.high=28846.9, self.low=28802.8, self.vol=764.172, self.amt=22027400.6015, ukdf['pct'].iloc[-1]=0.000312 , ukdf['amount'].iloc[-1]=22027400.6015, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=41716
self.closeSec=1683246299, self.tradeDate='20230505', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28846.8, self.close=28824.8, self.high=28846.9, self.low=28824.6, self.vol=364.39, self.amt=10507156.1318 
127.0.0.1 - - [05/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
2023-05-05 08:25:02,099:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230505   080000    080459  ...         0.0        0.0       0
5857  20230505   080500    080959  ...         0.0        0.0       0
5858  20230505   081000    081459  ...         0.0        0.0       0
5859  20230505   081500    081959  ...         0.0        0.0       0
5860  20230505   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-05 08:25:02,100:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683246299, self.tradeDate='20230505', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28846.8, self.close=28824.8, self.high=28846.9, self.low=28824.6, self.vol=364.39, self.amt=10507156.1318, ukdf['pct'].iloc[-1]=-0.000763 , ukdf['amount'].iloc[-1]=10507156.1318, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230504   200000    235959  1683215999  ...    719  0.693773  0.177212     NaN
720  20230505   000000    035959  1683230399  ...    720  0.574766 -0.198913     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '21647.84184532284', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28877.92738462', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [05/May/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=964
self.closeSec=1683244799, self.tradeDate='20230505', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28883.2, self.close=28826.0, self.high=28913.3, self.low=28731.2, self.vol=29440.989, self.amt=848390093.6805 
2023-05-05 08:00:02,018:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683244799, self.tradeDate='20230505', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28883.2, self.close=28826.0, self.high=28913.3, self.low=28731.2, self.vol=29440.989, self.amt=848390093.6805 
2023-05-05 08:00:02,046:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230504   120000    155959  ...   50341.471  1.465750e+09 -0.001241
718  20230504   160000    195959  ...   78089.723  2.277858e+09  0.003319
719  20230504   200000    235959  ...  145934.750  4.214657e+09 -0.010122
720  20230505   000000    035959  ...   73790.969  2.126806e+09  0.001151
721  20230505   040000    075959  ...   29440.989  8.483901e+08 -0.001980

[5 rows x 11 columns]
2023-05-05 08:00:03,644:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230504   120000    155959  1683187199  ...    717  0.587248 -0.124703     NaN
718  20230504   160000    195959  1683201599  ...    718  0.643034  0.033319     NaN
719  20230504   200000    235959  1683215999  ...    719  0.693773  0.177212     NaN
720  20230505   000000    035959  1683230399  ...    720  0.574766 -0.198913     NaN
721  20230505   040000    075959  1683244799  ...    721  0.437957 -0.626680    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '24026.07556938512', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28827.02123016', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


