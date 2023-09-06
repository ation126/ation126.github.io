# 20230906 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33076
self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25790.1, self.close=25798.8, self.high=25800.1, self.low=25780.1, self.vol=395.933, self.amt=10212429.6479 
127.0.0.1 - - [06/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-06 08:20:06,047:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230906   075500    075959  ...         0.0        0.0       0
5856  20230906   080000    080459  ...         0.0        0.0       0
5857  20230906   080500    080959  ...         0.0        0.0       0
5858  20230906   081000    081459  ...         0.0        0.0       0
5859  20230906   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 08:20:06,049:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25790.1, self.close=25798.8, self.high=25800.1, self.low=25780.1, self.vol=395.933, self.amt=10212429.6479, ukdf['pct'].iloc[-1]=0.000337 , ukdf['amount'].iloc[-1]=10212429.6479, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14829.7974', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25800', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33077
self.closeSec=1693959899, self.tradeDate='20230906', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25798.8, self.close=25805.8, self.high=25808.5, self.low=25797.8, self.vol=252.737, self.amt=6521511.0352 
2023-09-06 08:25:00,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230906   080000    080459  ...         0.0        0.0       0
5857  20230906   080500    080959  ...         0.0        0.0       0
5858  20230906   081000    081459  ...         0.0        0.0       0
5859  20230906   081500    081959  ...         0.0        0.0       0
5860  20230906   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 08:25:00,784:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693959899, self.tradeDate='20230906', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25798.8, self.close=25805.8, self.high=25808.5, self.low=25797.8, self.vol=252.737, self.amt=6521511.0352, ukdf['pct'].iloc[-1]=0.000271 , ukdf['amount'].iloc[-1]=6521511.0352, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14734.06813722228', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25806.87413922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33074 

self.closeSec=1693958399, self.tradeDate='20230906', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25772.8, self.close=25779.7, self.high=25780.0, self.low=25765.6 
127.0.0.1 - - [06/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33075 

self.closeSec=1693958699, self.tradeDate='20230906', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=25779.7, self.close=25771.1, self.high=25785.0, self.low=25763.2 
127.0.0.1 - - [06/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33076 

self.closeSec=1693958999, self.tradeDate='20230906', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=25771.1, self.close=25805.0, self.high=25809.0, self.low=25771.1 
127.0.0.1 - - [06/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33077 

self.closeSec=1693959299, self.tradeDate='20230906', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=25805.0, self.close=25790.1, self.high=25812.3, self.low=25785.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33078 

self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25790.1, self.close=25798.8, self.high=25800.1, self.low=25780.1 
127.0.0.1 - - [06/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33079 

self.closeSec=1693959899, self.tradeDate='20230906', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25798.8, self.close=25805.8, self.high=25808.5, self.low=25797.8 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-06 08:00:19,379:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230906    052959  25701.4  ...  48.333333  0.481332  0.517099
5770  20230906    055959  25741.9  ...  47.916667  0.474192  0.515001
5771  20230906    062959  25720.8  ...  48.333333  0.483317  0.508614
5772  20230906    065959  25745.5  ...  48.333333  0.487539  0.500592
5773  20230906    072959  25756.7  ...  48.750000  0.493615  0.496369

[5 rows x 33 columns]
0.5222222222222223
acc is : 0.5222222222222223
2023-09-06 08:00:19,448:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.504575  0.495425       0  ...  1.007233  -1.0    0.0  0.993883
536     1  0.487955  0.512045       1  ...  1.006273  -1.0    0.0  0.994830
537     0  0.505933  0.494067       1  ...  1.005828  -1.0    0.0  0.995270
538     0  0.500218  0.499782       1  ...  1.005187  -1.0    0.0  0.995904
539     0  0.502477  0.497523       1  ...  1.004934  -1.0    0.0  0.996155

[5 rows x 10 columns]
2023-09-06 08:00:19,461:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503631  0.496369       0  ...  0.996341  -1.0    0.0  0.992380
46     1  0.486834  0.513166       1  ...  1.006273  -1.0    0.0  0.989675
47     0  0.505047  0.494953       1  ...  1.005828  -1.0    0.0  0.993439
48     1  0.499855  0.500145       1  ...  1.005187  -1.0    0.0  0.994862
49     0  0.502477  0.497523       1  ...  1.004934  -1.0    0.0  0.996155

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '23576.2951', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25785', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16535 

self.closeSec=1693956599, self.tradeDate='20230906', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25772.9', self.close='25773.2'
127.0.0.1 - - [06/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16536 

self.closeSec=1693957199, self.tradeDate='20230906', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25773.3', self.close='25785.2'
127.0.0.1 - - [06/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16537 

self.closeSec=1693957799, self.tradeDate='20230906', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25785.2', self.close='25787.9'
127.0.0.1 - - [06/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16538 

self.closeSec=1693958399, self.tradeDate='20230906', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25788', self.close='25779.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16539 

self.closeSec=1693958999, self.tradeDate='20230906', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25779.7', self.close='25805.1'
127.0.0.1 - - [06/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16540 

self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25805', self.close='25798.9'
127.0.0.1 - - [06/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [06/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16538 

self.closeSec=1693956599, self.tradeDate='20230906', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25772.9', self.close='25773.2'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16539 

self.closeSec=1693957199, self.tradeDate='20230906', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25773.3', self.close='25785.2'
127.0.0.1 - - [06/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16540 

self.closeSec=1693957799, self.tradeDate='20230906', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25785.2', self.close='25787.9'

--handleKline--: 127.0.0.1 - - [06/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16541 

self.closeSec=1693958399, self.tradeDate='20230906', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25788', self.close='25779.7'
127.0.0.1 - - [06/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16542 

self.closeSec=1693958999, self.tradeDate='20230906', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25779.7', self.close='25805.1'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16543 

self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25805', self.close='25798.9'
127.0.0.1 - - [06/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [06/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16538 

self.closeSec=1693956599, self.tradeDate='20230906', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='25772.9', self.close='25773.2'
127.0.0.1 - - [06/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16539 

self.closeSec=1693957199, self.tradeDate='20230906', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='25773.3', self.close='25785.2'
127.0.0.1 - - [06/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16540 

self.closeSec=1693957799, self.tradeDate='20230906', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='25785.2', self.close='25787.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16541 

self.closeSec=1693958399, self.tradeDate='20230906', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='25788', self.close='25779.7'
127.0.0.1 - - [06/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16542 

self.closeSec=1693958999, self.tradeDate='20230906', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='25779.7', self.close='25805.1'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16543 

self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='25805', self.close='25798.9'
127.0.0.1 - - [06/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33076
self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=25790.1, self.close=25798.8, self.high=25800.1, self.low=25780.1, self.vol=395.933, self.amt=10212429.6479 
127.0.0.1 - - [06/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-06 08:20:06,043:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230906   075500    075959  ...         0.0        0.0       0
5856  20230906   080000    080459  ...         0.0        0.0       0
5857  20230906   080500    080959  ...         0.0        0.0       0
5858  20230906   081000    081459  ...         0.0        0.0       0
5859  20230906   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 08:20:06,046:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693959599, self.tradeDate='20230906', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=25790.1, self.close=25798.8, self.high=25800.1, self.low=25780.1, self.vol=395.933, self.amt=10212429.6479, ukdf['pct'].iloc[-1]=0.000337 , ukdf['amount'].iloc[-1]=10212429.6479, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38775.204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25800', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33077
self.closeSec=1693959899, self.tradeDate='20230906', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=25798.8, self.close=25805.8, self.high=25808.5, self.low=25797.8, self.vol=252.737, self.amt=6521511.0352 
2023-09-06 08:25:00,790:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230906   080000    080459  ...         0.0        0.0       0
5857  20230906   080500    080959  ...         0.0        0.0       0
5858  20230906   081000    081459  ...         0.0        0.0       0
5859  20230906   081500    081959  ...         0.0        0.0       0
5860  20230906   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 08:25:00,791:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693959899, self.tradeDate='20230906', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=25798.8, self.close=25805.8, self.high=25808.5, self.low=25797.8, self.vol=252.737, self.amt=6521511.0352, ukdf['pct'].iloc[-1]=0.000271 , ukdf['amount'].iloc[-1]=6521511.0352, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38519.89159522998', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25806.87413922', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230905   200000    235959  1693929599  ...    719  0.002931 -1.066895    -1.0
720  20230906   000000    035959  1693943999  ...    720  0.018338 -1.025426    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '12580.40956096692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25672.27429804', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=689
self.closeSec=1693958399, self.tradeDate='20230906', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=25670.4, self.close=25779.7, self.high=25792.4, self.low=25660.0, self.vol=13973.252, self.amt=359457627.3203 
127.0.0.1 - - [06/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-06 08:00:01,561:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693958399, self.tradeDate='20230906', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=25670.4, self.close=25779.7, self.high=25792.4, self.low=25660.0, self.vol=13973.252, self.amt=359457627.3203 
2023-09-06 08:00:01,576:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230905   120000    155959  ...  20015.690  5.144326e+08  0.001674
718  20230905   160000    195959  ...  29224.242  7.520790e+08  0.001811
719  20230905   200000    235959  ...  67199.020  1.730131e+09 -0.000912
720  20230906   000000    035959  ...  25402.722  6.540294e+08 -0.003006
721  20230906   040000    075959  ...  13973.252  3.594576e+08  0.004258

[5 rows x 11 columns]
2023-09-06 08:00:02,385:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230905   120000    155959  1693900799  ...    717  0.005918 -1.076044    -1.0
718  20230905   160000    195959  1693915199  ...    718  0.004898 -1.066787    -1.0
719  20230905   200000    235959  1693929599  ...    719  0.002931 -1.066895    -1.0
720  20230906   000000    035959  1693943999  ...    720  0.018338 -1.025426    -1.0
721  20230906   040000    075959  1693958399  ...    721  0.144573 -0.675100    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '6432.4125', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25779.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


