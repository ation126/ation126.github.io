# 20230922 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37684
self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26541.0, self.close=26530.5, self.high=26559.7, self.low=26528.4, self.vol=695.81, self.amt=18467468.9652 
127.0.0.1 - - [22/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-22 08:20:05,929:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230922   075500    075959  ...         0.0        0.0       0
5856  20230922   080000    080459  ...         0.0        0.0       0
5857  20230922   080500    080959  ...         0.0        0.0       0
5858  20230922   081000    081459  ...         0.0        0.0       0
5859  20230922   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 08:20:05,939:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26541.0, self.close=26530.5, self.high=26559.7, self.low=26528.4, self.vol=695.81, self.amt=18467468.9652, ukdf['pct'].iloc[-1]=-0.000399 , ukdf['amount'].iloc[-1]=18467468.9652, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4669.83496232814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26529.56789011', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37685
self.closeSec=1695342299, self.tradeDate='20230922', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26530.6, self.close=26517.2, self.high=26555.5, self.low=26517.2, self.vol=587.511, self.amt=15588199.4677 
2023-09-22 08:25:00,778:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230922   080000    080459  ...         0.0        0.0       0
5857  20230922   080500    080959  ...         0.0        0.0       0
5858  20230922   081000    081459  ...         0.0        0.0       0
5859  20230922   081500    081959  ...         0.0        0.0       0
5860  20230922   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 08:25:00,779:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695342299, self.tradeDate='20230922', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26530.6, self.close=26517.2, self.high=26555.5, self.low=26517.2, self.vol=587.511, self.amt=15588199.4677, ukdf['pct'].iloc[-1]=-0.000501 , ukdf['amount'].iloc[-1]=15588199.4677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '4821.49086215676', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26518.67776374', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [22/Sep/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37682 

self.closeSec=1695340799, self.tradeDate='20230922', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26544.0, self.close=26552.9, self.high=26558.1, self.low=26544.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37683 

self.closeSec=1695341099, self.tradeDate='20230922', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=26552.6, self.close=26565.3, self.high=26583.4, self.low=26547.7 
127.0.0.1 - - [22/Sep/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37684 

self.closeSec=1695341399, self.tradeDate='20230922', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=26565.2, self.close=26573.3, self.high=26573.4, self.low=26540.0 
127.0.0.1 - - [22/Sep/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37685 

self.closeSec=1695341699, self.tradeDate='20230922', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=26573.3, self.close=26541.1, self.high=26588.8, self.low=26537.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37686 

self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26541.0, self.close=26530.5, self.high=26559.7, self.low=26528.4 
127.0.0.1 - - [22/Sep/2023 08:20:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37687 

self.closeSec=1695342299, self.tradeDate='20230922', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26530.6, self.close=26517.2, self.high=26555.5, self.low=26517.2 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-22 08:00:16,727:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230922    052959  26580.2  ...  49.583333  0.434680  0.720253
5770  20230922    055959  26565.7  ...  49.583333  0.443114  0.717054
5771  20230922    062959  26600.1  ...  49.166667  0.434066  0.718356
5772  20230922    065959  26553.1  ...  49.583333  0.439889  0.717431
5773  20230922    072959  26576.5  ...  49.583333  0.438400  0.717261

[5 rows x 33 columns]
0.5481481481481482
acc is : 0.5481481481481482
2023-09-22 08:00:16,796:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     1  0.492484  0.507516       1  ...  0.899757  -1.0    0.0  1.035612
536     0  0.507818  0.492182       0  ...  0.901350  -1.0    0.0  1.033778
537     1  0.483911  0.516089       1  ...  0.900552  -1.0    0.0  1.034693
538     0  0.505170  0.494830       0  ...  0.900810  -1.0    0.0  1.034397
539     1  0.493830  0.506170       0  ...  0.901352  -1.0    0.0  1.033774

[5 rows x 10 columns]
2023-09-22 08:00:16,807:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.491995  0.508005       1  ...  0.899757  -1.0    0.0  1.032448
46     0  0.507571  0.492429       0  ...  0.901350  -1.0    0.0  1.031245
47     1  0.483396  0.516604       1  ...  0.900552  -1.0    0.0  1.030872
48     0  0.504948  0.495052       0  ...  0.900810  -1.0    0.0  1.033600
49     1  0.493830  0.506170       0  ...  0.901352  -1.0    0.0  1.033774

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '14878.332', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26551.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18839 

self.closeSec=1695338999, self.tradeDate='20230922', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26573', self.close='26568.9'
127.0.0.1 - - [22/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18840 

self.closeSec=1695339599, self.tradeDate='20230922', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26568.9', self.close='26556.9'
127.0.0.1 - - [22/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18841 

self.closeSec=1695340199, self.tradeDate='20230922', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26556.8', self.close='26563.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18842 

self.closeSec=1695340799, self.tradeDate='20230922', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26563.4', self.close='26552.6'
127.0.0.1 - - [22/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18843 

self.closeSec=1695341399, self.tradeDate='20230922', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26552.6', self.close='26573.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18844 

self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26573.3', self.close='26530.5'
127.0.0.1 - - [22/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18842 

self.closeSec=1695338999, self.tradeDate='20230922', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26573', self.close='26568.9'
127.0.0.1 - - [22/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18843 

self.closeSec=1695339599, self.tradeDate='20230922', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26568.9', self.close='26556.9'

--handleKline--: 127.0.0.1 - - [22/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18844 

self.closeSec=1695340199, self.tradeDate='20230922', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26556.8', self.close='26563.3'
127.0.0.1 - - [22/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18845 

self.closeSec=1695340799, self.tradeDate='20230922', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26563.4', self.close='26552.6'
127.0.0.1 - - [22/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18846 

self.closeSec=1695341399, self.tradeDate='20230922', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26552.6', self.close='26573.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18847 

self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26573.3', self.close='26530.5'
127.0.0.1 - - [22/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [22/Sep/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18842 

self.closeSec=1695338999, self.tradeDate='20230922', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='26573', self.close='26568.9'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18843 

self.closeSec=1695339599, self.tradeDate='20230922', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='26568.9', self.close='26556.9'
127.0.0.1 - - [22/Sep/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [22/Sep/2023 07:50:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18844 

self.closeSec=1695340199, self.tradeDate='20230922', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='26556.8', self.close='26563.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18845 

self.closeSec=1695340799, self.tradeDate='20230922', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='26563.4', self.close='26552.6'
127.0.0.1 - - [22/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18846 

self.closeSec=1695341399, self.tradeDate='20230922', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26552.6', self.close='26573.3'
127.0.0.1 - - [22/Sep/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18847 

self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26573.3', self.close='26530.5'
127.0.0.1 - - [22/Sep/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37684
self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26541.0, self.close=26530.5, self.high=26559.7, self.low=26528.4, self.vol=695.81, self.amt=18467468.9652 
127.0.0.1 - - [22/Sep/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-09-22 08:20:05,926:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230922   075500    075959  ...         0.0        0.0       0
5856  20230922   080000    080459  ...         0.0        0.0       0
5857  20230922   080500    080959  ...         0.0        0.0       0
5858  20230922   081000    081459  ...         0.0        0.0       0
5859  20230922   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 08:20:05,931:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695341999, self.tradeDate='20230922', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26541.0, self.close=26530.5, self.high=26559.7, self.low=26528.4, self.vol=695.81, self.amt=18467468.9652, ukdf['pct'].iloc[-1]=-0.000399 , ukdf['amount'].iloc[-1]=18467468.9652, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-11678.32299342449', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26529.56789011', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/Sep/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37685
self.closeSec=1695342299, self.tradeDate='20230922', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26530.6, self.close=26517.2, self.high=26555.5, self.low=26517.2, self.vol=587.511, self.amt=15588199.4677 
2023-09-22 08:25:00,776:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230922   080000    080459  ...         0.0        0.0       0
5857  20230922   080500    080959  ...         0.0        0.0       0
5858  20230922   081000    081459  ...         0.0        0.0       0
5859  20230922   081500    081959  ...         0.0        0.0       0
5860  20230922   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 08:25:00,777:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695342299, self.tradeDate='20230922', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26530.6, self.close=26517.2, self.high=26555.5, self.low=26517.2, self.vol=587.511, self.amt=15588199.4677, ukdf['pct'].iloc[-1]=-0.000501 , ukdf['amount'].iloc[-1]=15588199.4677, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12082.79317693266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26518.67776374', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230921   200000    235959  1695311999  ...    719  0.683797  0.714745     1.0
720  20230922   000000    035959  1695326399  ...    720  0.662706  0.642095     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-33433.0821', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26593.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=785
self.closeSec=1695340799, self.tradeDate='20230922', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26589.1, self.close=26552.9, self.high=26611.2, self.low=26484.0, self.vol=18947.754, self.amt=503216396.7037 
127.0.0.1 - - [22/Sep/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-09-22 08:00:01,541:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695340799, self.tradeDate='20230922', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26589.1, self.close=26552.9, self.high=26611.2, self.low=26484.0, self.vol=18947.754, self.amt=503216396.7037 
2023-09-22 08:00:01,553:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230921   120000    155959  ...   23776.748  6.426496e+08 -0.001798
718  20230921   160000    195959  ...   93622.480  2.506864e+09 -0.009474
719  20230921   200000    235959  ...  114856.578  3.047360e+09 -0.005804
720  20230922   000000    035959  ...   36722.499  9.768476e+08  0.000719
721  20230922   040000    075959  ...   18947.754  5.032164e+08 -0.001275

[5 rows x 11 columns]
2023-09-22 08:00:02,241:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230921   120000    155959  1695283199  ...    717  0.918522  1.378474     1.0
718  20230921   160000    195959  1695297599  ...    718  0.803757  1.048500     1.0
719  20230921   200000    235959  1695311999  ...    719  0.683797  0.714745     1.0
720  20230922   000000    035959  1695326399  ...    720  0.662706  0.642095     1.0
721  20230922   040000    075959  1695340799  ...    721  0.639944  0.565536     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-35366.68652818158', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26555.02717766', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


