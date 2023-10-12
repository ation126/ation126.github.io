# 20231012 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43444
self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26830.1, self.close=26818.2, self.high=26854.7, self.low=26818.2, self.vol=668.178, self.amt=17930822.1158 
127.0.0.1 - - [12/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-12 08:20:06,315:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231012   075500    075959  ...         0.0        0.0       0
5856  20231012   080000    080459  ...         0.0        0.0       0
5857  20231012   080500    080959  ...         0.0        0.0       0
5858  20231012   081000    081459  ...         0.0        0.0       0
5859  20231012   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 08:20:06,326:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26830.1, self.close=26818.2, self.high=26854.7, self.low=26818.2, self.vol=668.178, self.amt=17930822.1158, ukdf['pct'].iloc[-1]=-0.000444 , ukdf['amount'].iloc[-1]=17930822.1158, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '607.82959648488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26821.25289412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=43445
self.closeSec=1697070299, self.tradeDate='20231012', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26818.2, self.close=26814.6, self.high=26840.4, self.low=26809.0, self.vol=635.763, self.amt=17052580.9178 
2023-10-12 08:25:00,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231012   080000    080459  ...         0.0        0.0       0
5857  20231012   080500    080959  ...         0.0        0.0       0
5858  20231012   081000    081459  ...         0.0        0.0       0
5859  20231012   081500    081959  ...         0.0        0.0       0
5860  20231012   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 08:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1697070299, self.tradeDate='20231012', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26818.2, self.close=26814.6, self.high=26840.4, self.low=26809.0, self.vol=635.763, self.amt=17052580.9178, ukdf['pct'].iloc[-1]=-0.000134 , ukdf['amount'].iloc[-1]=17052580.9178, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '699.0852', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26814.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [12/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43442 

self.closeSec=1697068799, self.tradeDate='20231012', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26838.0, self.close=26867.0, self.high=26879.7, self.low=26836.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43443 

self.closeSec=1697069099, self.tradeDate='20231012', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26864.5, self.close=26843.2, self.high=26869.8, self.low=26839.6 
127.0.0.1 - - [12/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43444 

self.closeSec=1697069399, self.tradeDate='20231012', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26843.2, self.close=26852.6, self.high=26880.0, self.low=26840.9 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43445 

self.closeSec=1697069699, self.tradeDate='20231012', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26852.7, self.close=26830.1, self.high=26856.0, self.low=26826.7 
127.0.0.1 - - [12/Oct/2023 08:15:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43446 

self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26830.1, self.close=26818.2, self.high=26854.7, self.low=26818.2 
127.0.0.1 - - [12/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=43447 

self.closeSec=1697070299, self.tradeDate='20231012', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26818.2, self.close=26814.6, self.high=26840.4, self.low=26809.0 
127.0.0.1 - - [12/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-12 08:00:18,841:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231012    052959  26714.4  ...  45.833333  0.371440  0.782805
5770  20231012    055959  26701.5  ...  45.833333  0.377556  0.782803
5771  20231012    062959  26721.4  ...  46.250000  0.386975  0.778864
5772  20231012    065959  26752.6  ...  46.666667  0.394312  0.772474
5773  20231012    072959  26777.0  ...  47.083333  0.407886  0.762670

[5 rows x 33 columns]
0.5518518518518518
acc is : 0.5518518518518518
2023-10-12 08:00:18,905:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.485438  0.514562       1  ...  0.979158  -1.0    0.0  0.989473
536     1  0.495815  0.504185       1  ...  0.978019  -1.0    0.0  0.990624
537     1  0.499993  0.500007       1  ...  0.977127  -1.0    0.0  0.991528
538     0  0.503503  0.496497       1  ...  0.975455  -1.0    0.0  0.993224
539     0  0.513278  0.486722       1  ...  0.973873  -1.0    0.0  0.994834

[5 rows x 10 columns]
2023-10-12 08:00:18,917:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485887  0.514113       1  ...  0.979158  -1.0    0.0  0.990191
46     1  0.495839  0.504161       1  ...  0.978019  -1.0    0.0  0.991623
47     1  0.499951  0.500049       1  ...  0.977127  -1.0    0.0  0.991517
48     0  0.503609  0.496391       1  ...  0.975455  -1.0    0.0  0.993316
49     0  0.513278  0.486722       1  ...  0.973873  -1.0    0.0  0.994834

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.051', 'enterprice': '26768.8', 'countrevence': '0', 'unrealprofit': '-2426.7459', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26869.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21719 

self.closeSec=1697066999, self.tradeDate='20231012', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26769.8', self.close='26822.8'
127.0.0.1 - - [12/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21720 

self.closeSec=1697067599, self.tradeDate='20231012', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26823.4', self.close='26832.9'
127.0.0.1 - - [12/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21721 

self.closeSec=1697068199, self.tradeDate='20231012', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26834.6', self.close='26840.9'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21722 

self.closeSec=1697068799, self.tradeDate='20231012', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26841', self.close='26866.3'
127.0.0.1 - - [12/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21723 

self.closeSec=1697069399, self.tradeDate='20231012', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26864.5', self.close='26852.6'
127.0.0.1 - - [12/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21724 

self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26852.7', self.close='26818.3'
127.0.0.1 - - [12/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21722 

self.closeSec=1697066999, self.tradeDate='20231012', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26769.8', self.close='26822.8'
127.0.0.1 - - [12/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21723 

self.closeSec=1697067599, self.tradeDate='20231012', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26823.4', self.close='26832.9'
127.0.0.1 - - [12/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21724 

self.closeSec=1697068199, self.tradeDate='20231012', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26834.6', self.close='26840.9'
127.0.0.1 - - [12/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21725 

self.closeSec=1697068799, self.tradeDate='20231012', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26841', self.close='26866.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21726 

self.closeSec=1697069399, self.tradeDate='20231012', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26864.5', self.close='26852.6'
127.0.0.1 - - [12/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21727 

self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26852.7', self.close='26818.3'
127.0.0.1 - - [12/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21722 

self.closeSec=1697066999, self.tradeDate='20231012', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26769.8', self.close='26822.8'
127.0.0.1 - - [12/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21723 

self.closeSec=1697067599, self.tradeDate='20231012', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26823.4', self.close='26832.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21724 

self.closeSec=1697068199, self.tradeDate='20231012', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26834.6', self.close='26840.9'
127.0.0.1 - - [12/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [12/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21725 

self.closeSec=1697068799, self.tradeDate='20231012', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26841', self.close='26866.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21726 

self.closeSec=1697069399, self.tradeDate='20231012', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26864.5', self.close='26852.6'
127.0.0.1 - - [12/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21727 

self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26852.7', self.close='26818.3'
127.0.0.1 - - [12/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43444
self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26830.1, self.close=26818.2, self.high=26854.7, self.low=26818.2, self.vol=668.178, self.amt=17930822.1158 
127.0.0.1 - - [12/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-12 08:20:06,302:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231012   075500    075959  ...         0.0        0.0       0
5856  20231012   080000    080459  ...         0.0        0.0       0
5857  20231012   080500    080959  ...         0.0        0.0       0
5858  20231012   081000    081459  ...         0.0        0.0       0
5859  20231012   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 08:20:06,313:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697069999, self.tradeDate='20231012', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26830.1, self.close=26818.2, self.high=26854.7, self.low=26818.2, self.vol=668.178, self.amt=17930822.1158, ukdf['pct'].iloc[-1]=-0.000444 , ukdf['amount'].iloc[-1]=17930822.1158, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-844.85025948908', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26821.25289412', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [12/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=43445
self.closeSec=1697070299, self.tradeDate='20231012', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26818.2, self.close=26814.6, self.high=26840.4, self.low=26809.0, self.vol=635.763, self.amt=17052580.9178 
2023-10-12 08:25:00,796:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231012   080000    080459  ...         0.0        0.0       0
5857  20231012   080500    080959  ...         0.0        0.0       0
5858  20231012   081000    081459  ...         0.0        0.0       0
5859  20231012   081500    081959  ...         0.0        0.0       0
5860  20231012   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-12 08:25:00,797:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1697070299, self.tradeDate='20231012', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26818.2, self.close=26814.6, self.high=26840.4, self.low=26809.0, self.vol=635.763, self.amt=17052580.9178, ukdf['pct'].iloc[-1]=-0.000134 , ukdf['amount'].iloc[-1]=17052580.9178, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1088.2313', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26814.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231011   200000    235959  1697039999  ...    719  0.473472 -0.077798     NaN
720  20231012   000000    035959  1697054399  ...    720  0.577880  0.198424     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '51915.3076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26753.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [12/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=905
self.closeSec=1697068799, self.tradeDate='20231012', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26753.8, self.close=26866.3, self.high=26879.7, self.low=26666.0, self.vol=28736.228, self.amt=769096272.36562 
2023-10-12 08:00:01,506:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1697068799, self.tradeDate='20231012', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26753.8, self.close=26866.3, self.high=26879.7, self.low=26666.0, self.vol=28736.228, self.amt=769096272.36562 
2023-10-12 08:00:01,525:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231011   120000    155959  ...  38484.453  1.041483e+09  0.000470
718  20231011   160000    195959  ...  57422.558  1.561342e+09  0.006371
719  20231011   200000    235959  ...  99764.109  2.690309e+09 -0.015262
720  20231012   000000    035959  ...  92108.235  2.456312e+09 -0.000609
721  20231012   040000    075959  ...  28736.228  7.690963e+08  0.004209

[5 rows x 11 columns]
2023-10-12 08:00:02,313:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231011   120000    155959  1697011199  ...    717  0.492972 -0.010388     NaN
718  20231011   160000    195959  1697025599  ...    718  0.527985  0.077283     NaN
719  20231011   200000    235959  1697039999  ...    719  0.473472 -0.077798     NaN
720  20231012   000000    035959  1697054399  ...    720  0.577880  0.198424     NaN
721  20231012   040000    075959  1697068799  ...    721  0.642365  0.364240     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '46819.64809608801', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26870.48096667', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


