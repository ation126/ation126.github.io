# 20230920 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37204
self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27100.1, self.close=27130.0, self.high=27133.4, self.low=27093.4, self.vol=1079.195, self.amt=29269025.9589 
127.0.0.1 - - [20/Sep/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-09-20 16:20:06,779:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230920   155500    155959  ...         0.0        0.0       0
5952  20230920   160000    160459  ...         0.0        0.0       0
5953  20230920   160500    160959  ...         0.0        0.0       0
5954  20230920   161000    161459  ...         0.0        0.0       0
5955  20230920   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 16:20:06,789:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27100.1, self.close=27130.0, self.high=27133.4, self.low=27093.4, self.vol=1079.195, self.amt=29269025.9589, ukdf['pct'].iloc[-1]=0.001107 , ukdf['amount'].iloc[-1]=29269025.9589, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3748.8792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27134.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [20/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37205
self.closeSec=1695198299, self.tradeDate='20230920', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27130.1, self.close=27127.3, self.high=27135.9, self.low=27101.7, self.vol=695.69, self.amt=18867139.8817 
2023-09-20 16:25:00,764:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230920   160000    160459  ...         0.0        0.0       0
5953  20230920   160500    160959  ...         0.0        0.0       0
5954  20230920   161000    161459  ...         0.0        0.0       0
5955  20230920   161500    161959  ...         0.0        0.0       0
5956  20230920   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 16:25:00,764:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695198299, self.tradeDate='20230920', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27130.1, self.close=27127.3, self.high=27135.9, self.low=27101.7, self.vol=695.69, self.amt=18867139.8817, ukdf['pct'].iloc[-1]=-0.0001 , ukdf['amount'].iloc[-1]=18867139.8817, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3607.6298479221', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27123.95714835', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [20/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37202 

self.closeSec=1695196799, self.tradeDate='20230920', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27091.0, self.close=27089.4, self.high=27091.5, self.low=27075.8 
127.0.0.1 - - [20/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37203 

self.closeSec=1695197099, self.tradeDate='20230920', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=27089.5, self.close=27084.4, self.high=27090.3, self.low=27076.1 
127.0.0.1 - - [20/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37204 

self.closeSec=1695197399, self.tradeDate='20230920', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=27084.3, self.close=27092.7, self.high=27093.5, self.low=27080.9 
127.0.0.1 - - [20/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37205 

self.closeSec=1695197699, self.tradeDate='20230920', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=27092.6, self.close=27100.0, self.high=27115.0, self.low=27092.6 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37206 

self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27100.1, self.close=27130.0, self.high=27133.4, self.low=27093.4 
127.0.0.1 - - [20/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37207 

self.closeSec=1695198299, self.tradeDate='20230920', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27130.1, self.close=27127.3, self.high=27135.9, self.low=27101.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-20 16:00:17,336:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230920    132959  27054.1  ...  52.916667  0.519638  0.464176
5786  20230920    135959  27088.6  ...  52.916667  0.505231  0.484015
5787  20230920    142959  27012.1  ...  52.916667  0.511559  0.498796
5788  20230920    145959  27048.2  ...  53.333333  0.511782  0.512460
5789  20230920    152959  27049.2  ...  53.333333  0.514720  0.523514

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-09-20 16:00:17,394:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503564  0.496436       0  ...  0.925905  -1.0    0.0  1.045167
538     1  0.475158  0.524842       1  ...  0.924729  -1.0    0.0  1.046494
539     0  0.508677  0.491323       1  ...  0.924688  -1.0    0.0  1.046540
540     0  0.502631  0.497369       1  ...  0.924155  -1.0    0.0  1.047144
541     0  0.507687  0.492313       1  ...  0.923315  -1.0    0.0  1.048096

[5 rows x 10 columns]
2023-09-20 16:00:17,405:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503605  0.496395       0  ...  0.925905  -1.0    0.0  1.043403
46     1  0.474796  0.525204       1  ...  0.924729  -1.0    0.0  1.044574
47     0  0.508082  0.491918       1  ...  0.924688  -1.0    0.0  1.044379
48     0  0.502338  0.497662       1  ...  0.924155  -1.0    0.0  1.045853
49     0  0.507687  0.492313       1  ...  0.923315  -1.0    0.0  1.048096

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '1065.305', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27089.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [20/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18599 

self.closeSec=1695194999, self.tradeDate='20230920', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27054.3', self.close='27065'
127.0.0.1 - - [20/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18600 

self.closeSec=1695195599, self.tradeDate='20230920', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27064.9', self.close='27112.7'
127.0.0.1 - - [20/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18601 

self.closeSec=1695196199, self.tradeDate='20230920', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27116', self.close='27116.8'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18602 

self.closeSec=1695196799, self.tradeDate='20230920', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27116.9', self.close='27089.5'
127.0.0.1 - - [20/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18603 

self.closeSec=1695197399, self.tradeDate='20230920', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27089.5', self.close='27092.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18604 

self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27092.6', self.close='27130.1'
127.0.0.1 - - [20/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [20/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18602 

self.closeSec=1695194999, self.tradeDate='20230920', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27054.3', self.close='27065'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18603 

self.closeSec=1695195599, self.tradeDate='20230920', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27064.9', self.close='27112.7'
127.0.0.1 - - [20/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18604 

self.closeSec=1695196199, self.tradeDate='20230920', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27116', self.close='27116.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18605 

self.closeSec=1695196799, self.tradeDate='20230920', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27116.9', self.close='27089.5'
127.0.0.1 - - [20/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18606 

self.closeSec=1695197399, self.tradeDate='20230920', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27089.5', self.close='27092.7'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18607 

self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27092.6', self.close='27130.1'
127.0.0.1 - - [20/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [20/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18602 

self.closeSec=1695194999, self.tradeDate='20230920', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='27054.3', self.close='27065'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18603 

self.closeSec=1695195599, self.tradeDate='20230920', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='27064.9', self.close='27112.7'
127.0.0.1 - - [20/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [20/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18604 

self.closeSec=1695196199, self.tradeDate='20230920', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='27116', self.close='27116.8'
127.0.0.1 - - [20/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18605 

self.closeSec=1695196799, self.tradeDate='20230920', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='27116.9', self.close='27089.5'
127.0.0.1 - - [20/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18606 

self.closeSec=1695197399, self.tradeDate='20230920', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27089.5', self.close='27092.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18607 

self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27092.6', self.close='27130.1'
127.0.0.1 - - [20/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37204
self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27100.1, self.close=27130.0, self.high=27133.4, self.low=27093.4, self.vol=1079.195, self.amt=29269025.9589 
127.0.0.1 - - [20/Sep/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-09-20 16:20:06,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230920   155500    155959  ...         0.0        0.0       0
5952  20230920   160000    160459  ...         0.0        0.0       0
5953  20230920   160500    160959  ...         0.0        0.0       0
5954  20230920   161000    161459  ...         0.0        0.0       0
5955  20230920   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 16:20:06,781:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695197999, self.tradeDate='20230920', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27100.1, self.close=27130.0, self.high=27133.4, self.low=27093.4, self.vol=1079.195, self.amt=29269025.9589, ukdf['pct'].iloc[-1]=0.001107 , ukdf['amount'].iloc[-1]=29269025.9589, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10774.6041', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27134.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37205
self.closeSec=1695198299, self.tradeDate='20230920', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27130.1, self.close=27127.3, self.high=27135.9, self.low=27101.7, self.vol=695.69, self.amt=18867139.8817 
127.0.0.1 - - [20/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-20 16:25:00,771:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230920   160000    160459  ...         0.0        0.0       0
5953  20230920   160500    160959  ...         0.0        0.0       0
5954  20230920   161000    161459  ...         0.0        0.0       0
5955  20230920   161500    161959  ...         0.0        0.0       0
5956  20230920   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-20 16:25:00,771:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695198299, self.tradeDate='20230920', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27130.1, self.close=27127.3, self.high=27135.9, self.low=27101.7, self.vol=695.69, self.amt=18867139.8817, ukdf['pct'].iloc[-1]=-0.0001 , ukdf['amount'].iloc[-1]=18867139.8817, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10397.88844686735', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27123.95714835', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230920   040000    075959  1695167999  ...    721  1.258084  3.471109     1.0
722  20230920   080000    115959  1695182399  ...    722  1.453450  3.795504     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-7592.597434719', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27101.901163', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [20/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=775
self.closeSec=1695196799, self.tradeDate='20230920', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27106.4, self.close=27089.5, self.high=27149.8, self.low=26923.3, self.vol=42439.459, self.amt=1147898789.9428 
2023-09-20 16:00:01,531:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695196799, self.tradeDate='20230920', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27106.4, self.close=27089.5, self.high=27149.8, self.low=26923.3, self.vol=42439.459, self.amt=1147898789.9428 
2023-09-20 16:00:01,555:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230919   200000    235959  ...  148476.423  4.037187e+09  0.007005
720  20230920   000000    035959  ...   78548.985  2.138192e+09 -0.008912
721  20230920   040000    075959  ...   32685.998  8.865219e+08  0.000994
722  20230920   080000    115959  ...   46102.861  1.254524e+09 -0.003291
723  20230920   120000    155959  ...   42439.459  1.147899e+09 -0.000623

[5 rows x 11 columns]
2023-09-20 16:00:02,193:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230919   200000    235959  1695139199  ...    719  1.189022  3.968225     1.0
720  20230920   000000    035959  1695153599  ...    720  1.395255  4.296544     1.0
721  20230920   040000    075959  1695167999  ...    721  1.258084  3.471109     1.0
722  20230920   080000    115959  1695182399  ...    722  1.453450  3.795504     1.0
723  20230920   120000    155959  1695196799  ...    723  1.389618  3.322454     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-8227.494', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27089.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


