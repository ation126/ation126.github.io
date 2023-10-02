# 20231002 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40564
self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27938.3, self.close=27949.5, self.high=27954.2, self.low=27922.0, self.vol=867.197, self.amt=24228360.1207 
127.0.0.1 - - [02/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-02 08:20:05,383:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231002   075500    075959  ...         0.0        0.0       0
5856  20231002   080000    080459  ...         0.0        0.0       0
5857  20231002   080500    080959  ...         0.0        0.0       0
5858  20231002   081000    081459  ...         0.0        0.0       0
5859  20231002   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 08:20:05,393:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27938.3, self.close=27949.5, self.high=27954.2, self.low=27922.0, self.vol=867.197, self.amt=24228360.1207, ukdf['pct'].iloc[-1]=0.00068 , ukdf['amount'].iloc[-1]=24228360.1207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-15102.17521779714', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27949.35894139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=40565
self.closeSec=1696206299, self.tradeDate='20231002', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27949.5, self.close=27889.7, self.high=27975.6, self.low=27889.5, self.vol=1741.42, self.amt=48632678.7087 
127.0.0.1 - - [02/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-02 08:25:00,794:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231002   080000    080459  ...         0.0        0.0       0
5857  20231002   080500    080959  ...         0.0        0.0       0
5858  20231002   081000    081459  ...         0.0        0.0       0
5859  20231002   081500    081959  ...         0.0        0.0       0
5860  20231002   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 08:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696206299, self.tradeDate='20231002', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27949.5, self.close=27889.7, self.high=27975.6, self.low=27889.5, self.vol=1741.42, self.amt=48632678.7087, ukdf['pct'].iloc[-1]=-0.00214 , ukdf['amount'].iloc[-1]=48632678.7087, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14368.8468', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27896.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [02/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40562 

self.closeSec=1696204799, self.tradeDate='20231002', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27965.2, self.close=27981.4, self.high=27981.4, self.low=27941.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40563 

self.closeSec=1696205099, self.tradeDate='20231002', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27981.4, self.close=27965.6, self.high=28050.7, self.low=27955.6 
127.0.0.1 - - [02/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40564 

self.closeSec=1696205399, self.tradeDate='20231002', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27967.2, self.close=27938.3, self.high=27984.0, self.low=27925.7 
127.0.0.1 - - [02/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40565 

self.closeSec=1696205699, self.tradeDate='20231002', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27940.0, self.close=27930.5, self.high=27969.9, self.low=27925.5 
127.0.0.1 - - [02/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40566 

self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27938.3, self.close=27949.5, self.high=27954.2, self.low=27922.0 
127.0.0.1 - - [02/Oct/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=40567 

self.closeSec=1696206299, self.tradeDate='20231002', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27949.5, self.close=27889.7, self.high=27975.6, self.low=27889.5 
127.0.0.1 - - [02/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-02 08:00:17,112:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231002    052959  27093.6  ...  55.000000  0.546304  0.436894
5770  20231002    055959  27119.7  ...  55.000000  0.562104  0.436052
5771  20231002    062959  27164.1  ...  55.000000  0.732269  0.431659
5772  20231002    065959  27862.2  ...  55.416667  0.751385  0.420968
5773  20231002    072959  27989.6  ...  55.000000  0.704451  0.417204

[5 rows x 33 columns]
0.5425925925925926
acc is : 0.5425925925925926
2023-10-02 08:00:17,166:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
535     0  0.501406  0.498594       1  ...  0.981600  -1.0  0.0000  0.998871
536     0  0.507539  0.492461       1  ...  0.956324  -1.0  0.0000  1.024591
537     0  0.717321  0.282679       1  ...  0.959449   1.0 -0.0016  1.029578
538     0  0.584132  0.415868       0  ...  0.955199   1.0  0.0000  1.025018
539     0  0.506878  0.493122       1  ...  0.959048   1.0  0.0000  1.029148

[5 rows x 10 columns]
2023-10-02 08:00:17,177:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.501209  0.498791       1  ...  0.981600  -1.0  0.0000  0.999694
46     0  0.507497  0.492503       1  ...  0.956324  -1.0  0.0000  1.026180
47     0  0.716849  0.283151       1  ...  0.959449   1.0 -0.0016  1.031084
48     0  0.583673  0.416327       0  ...  0.955199   1.0  0.0000  1.023027
49     0  0.506878  0.493122       1  ...  0.959048   1.0  0.0000  1.029148

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.95', 'enterprice': '28012.5', 'countrevence': '0', 'unrealprofit': '-627.49', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27986.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  127.0.0.1 - - [02/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20279 

self.closeSec=1696202999, self.tradeDate='20231002', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27917', self.close='27869.1'
127.0.0.1 - - [02/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20280 

self.closeSec=1696203599, self.tradeDate='20231002', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27882.5', self.close='27929.5'
127.0.0.1 - - [02/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20281 

self.closeSec=1696204199, self.tradeDate='20231002', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27927.6', self.close='27955.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20282 

self.closeSec=1696204799, self.tradeDate='20231002', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27955.6', self.close='27981.4'
127.0.0.1 - - [02/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20283 

self.closeSec=1696205399, self.tradeDate='20231002', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27981.4', self.close='27939.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20284 

self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27940', self.close='27949.4'
127.0.0.1 - - [02/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20282 

self.closeSec=1696202999, self.tradeDate='20231002', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27917', self.close='27869.1'
127.0.0.1 - - [02/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20283 

self.closeSec=1696203599, self.tradeDate='20231002', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27882.5', self.close='27929.5'
127.0.0.1 - - [02/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20284 

self.closeSec=1696204199, self.tradeDate='20231002', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27927.6', self.close='27955.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20285 

self.closeSec=1696204799, self.tradeDate='20231002', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27955.6', self.close='27981.4'
127.0.0.1 - - [02/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20286 

self.closeSec=1696205399, self.tradeDate='20231002', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27981.4', self.close='27939.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20287 

self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27940', self.close='27949.4'
127.0.0.1 - - [02/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20282 

self.closeSec=1696202999, self.tradeDate='20231002', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27917', self.close='27869.1'
127.0.0.1 - - [02/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20283 

self.closeSec=1696203599, self.tradeDate='20231002', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27882.5', self.close='27929.5'
127.0.0.1 - - [02/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20284 

self.closeSec=1696204199, self.tradeDate='20231002', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27927.6', self.close='27955.7'
127.0.0.1 - - [02/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20285 

self.closeSec=1696204799, self.tradeDate='20231002', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27955.6', self.close='27981.4'
127.0.0.1 - - [02/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20286 

self.closeSec=1696205399, self.tradeDate='20231002', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27981.4', self.close='27939.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20287 

self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27940', self.close='27949.4'
127.0.0.1 - - [02/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40564
self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27938.3, self.close=27949.5, self.high=27954.2, self.low=27922.0, self.vol=867.197, self.amt=24228360.1207 
127.0.0.1 - - [02/Oct/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-10-02 08:20:05,376:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231002   075500    075959  ...         0.0        0.0       0
5856  20231002   080000    080459  ...         0.0        0.0       0
5857  20231002   080500    080959  ...         0.0        0.0       0
5858  20231002   081000    081459  ...         0.0        0.0       0
5859  20231002   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 08:20:05,385:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696205999, self.tradeDate='20231002', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27938.3, self.close=27949.5, self.high=27954.2, self.low=27922.0, self.vol=867.197, self.amt=24228360.1207, ukdf['pct'].iloc[-1]=0.00068 , ukdf['amount'].iloc[-1]=24228360.1207, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '41054.13644216599', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27949.35894139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=40565
self.closeSec=1696206299, self.tradeDate='20231002', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27949.5, self.close=27889.7, self.high=27975.6, self.low=27889.5, self.vol=1741.42, self.amt=48632678.7087 
2023-10-02 08:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231002   080000    080459  ...         0.0        0.0       0
5857  20231002   080500    080959  ...         0.0        0.0       0
5858  20231002   081000    081459  ...         0.0        0.0       0
5859  20231002   081500    081959  ...         0.0        0.0       0
5860  20231002   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-02 08:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696206299, self.tradeDate='20231002', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27949.5, self.close=27889.7, self.high=27975.6, self.low=27889.5, self.vol=1741.42, self.amt=48632678.7087, ukdf['pct'].iloc[-1]=-0.00214 , ukdf['amount'].iloc[-1]=48632678.7087, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '39098.3307', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27896.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231001   200000    235959  1696175999  ...    719  0.361394 -0.670357    -1.0
720  20231002   000000    035959  1696190399  ...    720  0.578343 -0.157510     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '290.6188', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27088.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [02/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1268776.2962574002, self.flagDict['side']='sell', self.tradeCount=28, self.count=845
self.closeSec=1696204799, self.tradeDate='20231002', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27091.0, self.close=27981.4, self.high=28365.2, self.low=27015.0, self.vol=122070.984, self.amt=3388269106.49385 
2023-10-02 08:00:01,527:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696204799, self.tradeDate='20231002', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27091.0, self.close=27981.4, self.high=28365.2, self.low=27015.0, self.vol=122070.984, self.amt=3388269106.49385 
2023-10-02 08:00:01,546:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231001   120000    155959  ...   19731.246  5.344221e+08  0.002186
718  20231001   160000    195959  ...   39467.035  1.072977e+09  0.003030
719  20231001   200000    235959  ...   29635.945  8.042991e+08 -0.001413
720  20231002   000000    035959  ...   18484.542  5.006412e+08 -0.001651
721  20231002   040000    075959  ...  122070.984  3.388269e+09  0.032867

[5 rows x 11 columns]
2023-10-02 08:00:02,478:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231001   120000    155959  1696147199  ...    717  0.339582 -0.726072    -1.0
718  20231001   160000    195959  1696161599  ...    718  0.295177 -0.829722    -1.0
719  20231001   200000    235959  1696175999  ...    719  0.361394 -0.670357    -1.0
720  20231002   000000    035959  1696190399  ...    720  0.578343 -0.157510     NaN
721  20231002   040000    075959  1696204799  ...    721  0.458085 -0.444898     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.874', 'enterprice': '27094.9', 'countrevence': '0', 'unrealprofit': '-41553.801', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27981.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


