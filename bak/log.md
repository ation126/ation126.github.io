# 20231004 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41140
self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27346.5, self.close=27368.4, self.high=27376.4, self.low=27338.4, self.vol=1174.033, self.amt=32123115.7765 
127.0.0.1 - - [04/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-04 08:20:06,486:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231004   075500    075959  ...         0.0        0.0       0
5856  20231004   080000    080459  ...         0.0        0.0       0
5857  20231004   080500    080959  ...         0.0        0.0       0
5858  20231004   081000    081459  ...         0.0        0.0       0
5859  20231004   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 08:20:06,489:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27346.5, self.close=27368.4, self.high=27376.4, self.low=27338.4, self.vol=1174.033, self.amt=32123115.7765, ukdf['pct'].iloc[-1]=0.000676 , ukdf['amount'].iloc[-1]=32123115.7765, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7034.0226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27370', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=41141
self.closeSec=1696379099, self.tradeDate='20231004', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27368.3, self.close=27366.9, self.high=27384.9, self.low=27336.4, self.vol=1712.833, self.amt=46872440.5016 
127.0.0.1 - - [04/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-04 08:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231004   080000    080459  ...         0.0        0.0       0
5857  20231004   080500    080959  ...         0.0        0.0       0
5858  20231004   081000    081459  ...         0.0        0.0       0
5859  20231004   081500    081959  ...         0.0        0.0       0
5860  20231004   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 08:25:00,792:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696379099, self.tradeDate='20231004', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27368.3, self.close=27366.9, self.high=27384.9, self.low=27336.4, self.vol=1712.833, self.amt=46872440.5016, ukdf['pct'].iloc[-1]=-5.5e-05 , ukdf['amount'].iloc[-1]=46872440.5016, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7035.03177585978', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27370.07246703', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41138 

self.closeSec=1696377599, self.tradeDate='20231004', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27412.0, self.close=27412.0, self.high=27418.8, self.low=27407.2 
127.0.0.1 - - [04/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41139 

self.closeSec=1696377899, self.tradeDate='20231004', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27412.0, self.close=27391.4, self.high=27423.2, self.low=27388.0 
127.0.0.1 - - [04/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41140 

self.closeSec=1696378199, self.tradeDate='20231004', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27391.3, self.close=27390.1, self.high=27399.9, self.low=27359.4 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41141 

self.closeSec=1696378499, self.tradeDate='20231004', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27389.7, self.close=27349.9, self.high=27399.7, self.low=27343.9 
127.0.0.1 - - [04/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41142 

self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27346.5, self.close=27368.4, self.high=27376.4, self.low=27338.4 
127.0.0.1 - - [04/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=41143 

self.closeSec=1696379099, self.tradeDate='20231004', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27368.3, self.close=27366.9, self.high=27384.9, self.low=27336.4 
127.0.0.1 - - [04/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-04 08:00:17,839:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231004    052959  27384.5  ...  55.416667  0.475275  0.695739
5770  20231004    055959  27401.8  ...  55.000000  0.473002  0.683428
5771  20231004    062959  27388.0  ...  54.583333  0.459922  0.681900
5772  20231004    065959  27306.5  ...  55.000000  0.475685  0.669860
5773  20231004    072959  27393.3  ...  55.000000  0.482772  0.653739

[5 rows x 33 columns]
0.5703703703703704
acc is : 0.5703703703703704
2023-10-04 08:00:17,906:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.508766  0.491234       0  ...  0.962102  -1.0    0.0  1.030926
536     1  0.496599  0.503401       0  ...  0.964947  -1.0    0.0  1.027877
537     1  0.478697  0.521303       1  ...  0.961898  -1.0    0.0  1.031126
538     0  0.522310  0.477690       1  ...  0.960504  -1.0    0.0  1.032620
539     0  0.511898  0.488102       0  ...  0.961239  -1.0    0.0  1.031830

[5 rows x 10 columns]
2023-10-04 08:00:17,920:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509144  0.490856       0  ...  0.962102  -1.0    0.0  1.028854
46     1  0.496558  0.503442       0  ...  0.964947  -1.0    0.0  1.026128
47     1  0.478769  0.521231       1  ...  0.961898  -1.0    0.0  1.030397
48     0  0.522157  0.477843       1  ...  0.960504  -1.0    0.0  1.032399
49     0  0.511898  0.488102       0  ...  0.961239  -1.0    0.0  1.031830

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.906', 'enterprice': '28298.9', 'countrevence': '0', 'unrealprofit': '21444.14173078762', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27401.88076923', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20567 

self.closeSec=1696375799, self.tradeDate='20231004', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27378.1', self.close='27432.9'
127.0.0.1 - - [04/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--: 127.0.0.1 - - [04/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20568 

self.closeSec=1696376399, self.tradeDate='20231004', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27432.9', self.close='27448.3'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20569 

self.closeSec=1696376999, self.tradeDate='20231004', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27450', self.close='27437.5'
127.0.0.1 - - [04/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20570 

self.closeSec=1696377599, self.tradeDate='20231004', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27436.5', self.close='27412'
127.0.0.1 - - [04/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20571 

self.closeSec=1696378199, self.tradeDate='20231004', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27412', self.close='27390.1'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20572 

self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27389.7', self.close='27368.4'
127.0.0.1 - - [04/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20570 

self.closeSec=1696375799, self.tradeDate='20231004', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27378.1', self.close='27432.9'
127.0.0.1 - - [04/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20571 

self.closeSec=1696376399, self.tradeDate='20231004', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27432.9', self.close='27448.3'
127.0.0.1 - - [04/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20572 

self.closeSec=1696376999, self.tradeDate='20231004', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27450', self.close='27437.5'
127.0.0.1 - - [04/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20573 

self.closeSec=1696377599, self.tradeDate='20231004', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27436.5', self.close='27412'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20574 

self.closeSec=1696378199, self.tradeDate='20231004', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27412', self.close='27390.1'
127.0.0.1 - - [04/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20575 

self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27389.7', self.close='27368.4'
127.0.0.1 - - [04/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--: 127.0.0.1 - - [04/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20570 

self.closeSec=1696375799, self.tradeDate='20231004', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27378.1', self.close='27432.9'
127.0.0.1 - - [04/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20571 

self.closeSec=1696376399, self.tradeDate='20231004', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27432.9', self.close='27448.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20572 

self.closeSec=1696376999, self.tradeDate='20231004', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27450', self.close='27437.5'
127.0.0.1 - - [04/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [04/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20573 

self.closeSec=1696377599, self.tradeDate='20231004', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27436.5', self.close='27412'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20574 

self.closeSec=1696378199, self.tradeDate='20231004', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27412', self.close='27390.1'
127.0.0.1 - - [04/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20575 

self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27389.7', self.close='27368.4'
127.0.0.1 - - [04/Oct/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41140
self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27346.5, self.close=27368.4, self.high=27376.4, self.low=27338.4, self.vol=1174.033, self.amt=32123115.7765 
127.0.0.1 - - [04/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-04 08:20:06,485:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231004   075500    075959  ...         0.0        0.0       0
5856  20231004   080000    080459  ...         0.0        0.0       0
5857  20231004   080500    080959  ...         0.0        0.0       0
5858  20231004   081000    081459  ...         0.0        0.0       0
5859  20231004   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 08:20:06,490:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696378799, self.tradeDate='20231004', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27346.5, self.close=27368.4, self.high=27376.4, self.low=27338.4, self.vol=1174.033, self.amt=32123115.7765, ukdf['pct'].iloc[-1]=0.000676 , ukdf['amount'].iloc[-1]=32123115.7765, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '19536.166', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27370', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [04/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=41141
self.closeSec=1696379099, self.tradeDate='20231004', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27368.3, self.close=27366.9, self.high=27384.9, self.low=27336.4, self.vol=1712.833, self.amt=46872440.5016 
2023-10-04 08:25:00,795:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231004   080000    080459  ...         0.0        0.0       0
5857  20231004   080500    080959  ...         0.0        0.0       0
5858  20231004   081000    081459  ...         0.0        0.0       0
5859  20231004   081500    081959  ...         0.0        0.0       0
5860  20231004   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-04 08:25:00,796:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696379099, self.tradeDate='20231004', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27368.3, self.close=27366.9, self.high=27384.9, self.low=27336.4, self.vol=1712.833, self.amt=46872440.5016, ukdf['pct'].iloc[-1]=-5.5e-05 , ukdf['amount'].iloc[-1]=46872440.5016, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '19538.85749796123', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27370.07246703', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231003   200000    235959  1696348799  ...    719  1.102317  0.925811     1.0
720  20231004   000000    035959  1696363199  ...    720  1.197020  1.140802     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-32737.7752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27266.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1223948.6721539998, self.flagDict['side']='buy', self.tradeCount=29, self.count=857
self.closeSec=1696377599, self.tradeDate='20231004', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27263.8, self.close=27412.0, self.high=27459.7, self.low=27123.0, self.vol=48321.199, self.amt=1320650792.25061 
127.0.0.1 - - [04/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-04 08:00:01,560:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696377599, self.tradeDate='20231004', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27263.8, self.close=27412.0, self.high=27459.7, self.low=27123.0, self.vol=48321.199, self.amt=1320650792.25061 
2023-10-04 08:00:01,579:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20231003   120000    155959  ...  24064.809  6.638310e+08 -0.002095
718  20231003   160000    195959  ...  33099.077  9.119116e+08  0.000763
719  20231003   200000    235959  ...  90415.713  2.476740e+09 -0.007877
720  20231004   000000    035959  ...  47928.263  1.311400e+09 -0.002495
721  20231004   040000    075959  ...  48321.199  1.320651e+09  0.005436

[5 rows x 11 columns]
2023-10-04 08:00:02,489:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231003   120000    155959  1696319999  ...    717  1.122867  1.016519     1.0
718  20231003   160000    195959  1696334399  ...    718  1.109387  0.961711     1.0
719  20231003   200000    235959  1696348799  ...    719  1.102317  0.925811     1.0
720  20231004   000000    035959  1696363199  ...    720  1.197020  1.140802     1.0
721  20231004   040000    075959  1696377599  ...    721  1.186991  1.095715     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.732', 'enterprice': '28015.5', 'countrevence': '0', 'unrealprofit': '-26264.85086640688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27414.91345316', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


