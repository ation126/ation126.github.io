# 20230825 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29524
self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26070.1, self.close=26076.1, self.high=26102.0, self.low=26060.1, self.vol=1535.012, self.amt=40034040.2964 
127.0.0.1 - - [25/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-25 00:20:05,207:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230824   235500    235959  ...         0.0        0.0       0
5748  20230825   000000    000459  ...         0.0        0.0       0
5749  20230825   000500    000959  ...         0.0        0.0       0
5750  20230825   001000    001459  ...         0.0        0.0       0
5751  20230825   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 00:20:05,211:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26070.1, self.close=26076.1, self.high=26102.0, self.low=26060.1, self.vol=1535.012, self.amt=40034040.2964, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=40034040.2964, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11010.01914854754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26074.29112821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [25/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=29525
self.closeSec=1692894299, self.tradeDate='20230825', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26076.1, self.close=26054.6, self.high=26084.8, self.low=26054.4, self.vol=1052.144, self.amt=27424558.121 
2023-08-25 00:25:00,790:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230825   000000    000459  ...         0.0        0.0       0
5749  20230825   000500    000959  ...         0.0        0.0       0
5750  20230825   001000    001459  ...         0.0        0.0       0
5751  20230825   001500    001959  ...         0.0        0.0       0
5752  20230825   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 00:25:00,790:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692894299, self.tradeDate='20230825', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26076.1, self.close=26054.6, self.high=26084.8, self.low=26054.4, self.vol=1052.144, self.amt=27424558.121, ukdf['pct'].iloc[-1]=-0.000825 , ukdf['amount'].iloc[-1]=27424558.121, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '11246.40419926518', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26057.31676007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

self.closeSec=1692893099, self.tradeDate='20230825', self.openTime='000000', self.closeTime='000459', self.symbol='BTCUSDT', self.open=25987.3, self.close=26037.5, self.high=26043.0, self.low=25981.6 

--ukdf-hist--: overDate='20230820' 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 
 Empty DataFrame
Columns: [tradeDate, openTime, closeTime, closeSec, open, close, high, low, pct, index, idx]
Index: [] 

127.0.0.1 - - [25/Aug/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29524 

self.closeSec=1692893399, self.tradeDate='20230825', self.openTime='000500', self.closeTime='000959', self.symbol='BTCUSDT', self.open=26032.3, self.close=26059.2, self.high=26059.6, self.low=26030.4 
127.0.0.1 - - [25/Aug/2023 00:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29525 

self.closeSec=1692893699, self.tradeDate='20230825', self.openTime='001000', self.closeTime='001459', self.symbol='BTCUSDT', self.open=26059.1, self.close=26070.0, self.high=26102.5, self.low=26046.7 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29526 

self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26070.1, self.close=26076.1, self.high=26102.0, self.low=26060.1 
127.0.0.1 - - [25/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=29527 

self.closeSec=1692894299, self.tradeDate='20230825', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26076.1, self.close=26054.6, self.high=26084.8, self.low=26054.4 
127.0.0.1 - - [25/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-25 00:00:16,925:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5801  20230824    212959  26377.5  ...  53.333333  0.523849  0.430872
5802  20230824    215959  26360.1  ...  53.333333  0.518930  0.453464
5803  20230824    222959  26346.5  ...  52.916667  0.483618  0.489076
5804  20230824    225959  26190.2  ...  52.916667  0.464268  0.519218
5805  20230824    232959  26100.1  ...  52.500000  0.454848  0.549509

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-08-25 00:00:17,000:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.483312  0.516688       0  ...  1.026798  -1.0    0.0  0.896240
540     1  0.480796  0.519204       0  ...  1.032650  -1.0    0.0  0.891132
541     1  0.431922  0.568078       0  ...  1.036202  -1.0    0.0  0.888067
542     1  0.442015  0.557985       0  ...  1.038016  -1.0    0.0  0.886512
543     1  0.455875  0.544125       0  ...  1.040742  -1.0    0.0  0.884184

[5 rows x 10 columns]
2023-08-25 00:00:17,012:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483793  0.516207       0  ...  1.041025  -1.0    0.0  0.896715
46     1  0.481181  0.518819       0  ...  1.032650  -1.0    0.0  0.891357
47     1  0.432375  0.567625       0  ...  1.036202  -1.0    0.0  0.888055
48     1  0.442007  0.557993       0  ...  1.038016  -1.0    0.0  0.886500
49     1  0.455875  0.544125       0  ...  1.040742  -1.0    0.0  0.884184

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.231', 'enterprice': '26402', 'countrevence': '0', 'unrealprofit': '11509.7787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25994.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14759 

self.closeSec=1692890999, self.tradeDate='20230824', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26107', self.close='26054.4'
127.0.0.1 - - [24/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14760 

self.closeSec=1692891599, self.tradeDate='20230824', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26057.3', self.close='26064.5'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14761 

self.closeSec=1692892199, self.tradeDate='20230824', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26064.6', self.close='26059.3'
127.0.0.1 - - [24/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14762 

self.closeSec=1692892799, self.tradeDate='20230824', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26059.3', self.close='25986'
127.0.0.1 - - [25/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14763 

self.closeSec=1692893399, self.tradeDate='20230825', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25987.3', self.close='26059.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14764 

self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26059.1', self.close='26076.1'
127.0.0.1 - - [25/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [24/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14762 

self.closeSec=1692890999, self.tradeDate='20230824', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26107', self.close='26054.4'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14763 

self.closeSec=1692891599, self.tradeDate='20230824', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26057.3', self.close='26064.5'
127.0.0.1 - - [24/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14764 

self.closeSec=1692892199, self.tradeDate='20230824', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26064.6', self.close='26059.3'
127.0.0.1 - - [24/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14765 

self.closeSec=1692892799, self.tradeDate='20230824', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26059.3', self.close='25986'
127.0.0.1 - - [25/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [25/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14766 

self.closeSec=1692893399, self.tradeDate='20230825', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25987.3', self.close='26059.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14767 

self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26059.1', self.close='26076.1'
127.0.0.1 - - [25/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Aug/2023 23:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14762 

self.closeSec=1692890999, self.tradeDate='20230824', self.openTime='232000', self.closeTime='232959', self.symbol='BTCUSDT', self.open='26107', self.close='26054.4'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14763 

self.closeSec=1692891599, self.tradeDate='20230824', self.openTime='233000', self.closeTime='233959', self.symbol='BTCUSDT', self.open='26057.3', self.close='26064.5'
127.0.0.1 - - [24/Aug/2023 23:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [24/Aug/2023 23:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14764 

self.closeSec=1692892199, self.tradeDate='20230824', self.openTime='234000', self.closeTime='234959', self.symbol='BTCUSDT', self.open='26064.6', self.close='26059.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14765 

self.closeSec=1692892799, self.tradeDate='20230824', self.openTime='235000', self.closeTime='235959', self.symbol='BTCUSDT', self.open='26059.3', self.close='25986'
127.0.0.1 - - [25/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14766 

self.closeSec=1692893399, self.tradeDate='20230825', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25987.3', self.close='26059.2'
127.0.0.1 - - [25/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14767 

self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26059.1', self.close='26076.1'
127.0.0.1 - - [25/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29524
self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26070.1, self.close=26076.1, self.high=26102.0, self.low=26060.1, self.vol=1535.012, self.amt=40034040.2964 
127.0.0.1 - - [25/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-25 00:20:05,204:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5747  20230824   235500    235959  ...         0.0        0.0       0
5748  20230825   000000    000459  ...         0.0        0.0       0
5749  20230825   000500    000959  ...         0.0        0.0       0
5750  20230825   001000    001459  ...         0.0        0.0       0
5751  20230825   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 00:20:05,206:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692893999, self.tradeDate='20230825', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26070.1, self.close=26076.1, self.high=26102.0, self.low=26060.1, self.vol=1535.012, self.amt=40034040.2964, ukdf['pct'].iloc[-1]=0.000234 , ukdf['amount'].iloc[-1]=40034040.2964, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5751, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-28587.75720715239', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26074.29112821', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [25/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=29525
self.closeSec=1692894299, self.tradeDate='20230825', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26076.1, self.close=26054.6, self.high=26084.8, self.low=26054.4, self.vol=1052.144, self.amt=27424558.121 
2023-08-25 00:25:00,788:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5748  20230825   000000    000459  ...         0.0        0.0       0
5749  20230825   000500    000959  ...         0.0        0.0       0
5750  20230825   001000    001459  ...         0.0        0.0       0
5751  20230825   001500    001959  ...         0.0        0.0       0
5752  20230825   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-25 00:25:00,788:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692894299, self.tradeDate='20230825', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26076.1, self.close=26054.6, self.high=26084.8, self.low=26054.4, self.vol=1052.144, self.amt=27424558.121, ukdf['pct'].iloc[-1]=-0.000825 , ukdf['amount'].iloc[-1]=27424558.121, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5752, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-29218.20221424013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26057.31676007', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230824   120000    155959  1692863999  ...    723  0.141513 -0.704028    -1.0
724  20230824   160000    195959  1692878399  ...    724  0.183111 -0.590625     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '154102.3344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26433.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=615
self.closeSec=1692892799, self.tradeDate='20230824', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26433.8, self.close=25986.0, self.high=26433.9, self.low=25972.5, self.vol=100354.824, self.amt=2628388221.1174 
127.0.0.1 - - [25/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-25 00:00:01,557:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692892799, self.tradeDate='20230824', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26433.8, self.close=25986.0, self.high=26433.9, self.low=25972.5, self.vol=100354.824, self.amt=2628388221.1174 
2023-08-25 00:00:01,571:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230824   040000    075959  ...   70672.879  1.870824e+09 -0.007364
722  20230824   080000    115959  ...   29657.298  7.837921e+08  0.000413
723  20230824   120000    155959  ...   23503.450  6.214354e+08  0.001158
724  20230824   160000    195959  ...   33863.295  8.963928e+08 -0.001013
725  20230824   200000    235959  ...  100354.824  2.628388e+09 -0.016944

[5 rows x 11 columns]
2023-08-25 00:00:02,262:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230824   040000    075959  1692835199  ...    721  0.066786 -0.908375    -1.0
722  20230824   080000    115959  1692849599  ...    722  0.111271 -0.790753    -1.0
723  20230824   120000    155959  1692863999  ...    723  0.141513 -0.704028    -1.0
724  20230824   160000    195959  1692878399  ...    724  0.183111 -0.590625     NaN
725  20230824   200000    235959  1692892799  ...    725  0.180320 -0.580225     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '177041.9376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25987.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


