# 20230922 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37780
self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26715.0, self.close=26686.1, self.high=26724.1, self.low=26681.1, self.vol=1139.055, self.amt=30409880.5743 
127.0.0.1 - - [22/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-22 16:20:05,966:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230922   155500    155959  ...         0.0        0.0       0
5952  20230922   160000    160459  ...         0.0        0.0       0
5953  20230922   160500    160959  ...         0.0        0.0       0
5954  20230922   161000    161459  ...         0.0        0.0       0
5955  20230922   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 16:20:05,970:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26715.0, self.close=26686.1, self.high=26724.1, self.low=26681.1, self.vol=1139.055, self.amt=30409880.5743, ukdf['pct'].iloc[-1]=-0.001078 , ukdf['amount'].iloc[-1]=30409880.5743, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2467.29132921876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26687.72842674', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=37781
self.closeSec=1695371099, self.tradeDate='20230922', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26686.1, self.close=26675.6, self.high=26692.3, self.low=26664.2, self.vol=1045.376, self.amt=27888546.4946 
2023-09-22 16:25:00,796:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230922   160000    160459  ...         0.0        0.0       0
5953  20230922   160500    160959  ...         0.0        0.0       0
5954  20230922   161000    161459  ...         0.0        0.0       0
5955  20230922   161500    161959  ...         0.0        0.0       0
5956  20230922   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 16:25:00,796:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1695371099, self.tradeDate='20230922', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26686.1, self.close=26675.6, self.high=26692.3, self.low=26664.2, self.vol=1045.376, self.amt=27888546.4946, ukdf['pct'].iloc[-1]=-0.000393 , ukdf['amount'].iloc[-1]=27888546.4946, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2635.41675292632', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26675.65565468', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37778 

self.closeSec=1695369599, self.tradeDate='20230922', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26674.9, self.close=26660.9, self.high=26697.5, self.low=26652.5 
127.0.0.1 - - [22/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37779 

self.closeSec=1695369899, self.tradeDate='20230922', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=26660.9, self.close=26697.6, self.high=26730.0, self.low=26656.0 
127.0.0.1 - - [22/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37780 

self.closeSec=1695370199, self.tradeDate='20230922', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=26695.7, self.close=26721.7, self.high=26737.7, self.low=26673.4 
127.0.0.1 - - [22/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37781 

self.closeSec=1695370499, self.tradeDate='20230922', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=26721.3, self.close=26714.9, self.high=26735.2, self.low=26707.3 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37782 

self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26715.0, self.close=26686.1, self.high=26724.1, self.low=26681.1 
127.0.0.1 - - [22/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=37783 

self.closeSec=1695371099, self.tradeDate='20230922', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26686.1, self.close=26675.6, self.high=26692.3, self.low=26664.2 
127.0.0.1 - - [22/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-22 16:00:16,653:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230922    132959  26631.2  ...  49.166667  0.454091  0.663358
5786  20230922    135959  26602.2  ...  49.166667  0.466695  0.641135
5787  20230922    142959  26653.7  ...  49.166667  0.464383  0.621951
5788  20230922    145959  26639.9  ...  48.750000  0.456906  0.607141
5789  20230922    152959  26607.2  ...  48.750000  0.448921  0.598884

[5 rows x 33 columns]
0.5461254612546126
acc is : 0.5461254612546126
2023-09-22 16:00:16,712:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.486543  0.513457       1  ...  0.898042  -1.0    0.0  1.036336
538     0  0.508412  0.491588       0  ...  0.898383  -1.0    0.0  1.035943
539     1  0.492070  0.507930       0  ...  0.899485  -1.0    0.0  1.034672
540     1  0.484723  0.515277       0  ...  0.900682  -1.0    0.0  1.033295
541     1  0.482519  0.517481       1  ...  0.897662  -1.0    0.0  1.036760

[5 rows x 10 columns]
2023-09-22 16:00:16,723:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.486076  0.513924       1  ...  0.898042  -1.0    0.0  1.031415
46     0  0.508200  0.491800       0  ...  0.898383  -1.0    0.0  1.032162
47     1  0.491647  0.508353       0  ...  0.899485  -1.0    0.0  1.030153
48     1  0.484471  0.515529       0  ...  0.900682  -1.0    0.0  1.030614
49     1  0.482519  0.517481       1  ...  0.897662  -1.0    0.0  1.036760

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.67', 'enterprice': '27131.4', 'countrevence': '0', 'unrealprofit': '11936.55', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26666.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18887 

self.closeSec=1695367799, self.tradeDate='20230922', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26609.5', self.close='26571.8'
127.0.0.1 - - [22/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18888 

self.closeSec=1695368399, self.tradeDate='20230922', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26571.7', self.close='26593'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18889 

self.closeSec=1695368999, self.tradeDate='20230922', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26593', self.close='26619.5'
127.0.0.1 - - [22/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18890 

self.closeSec=1695369599, self.tradeDate='20230922', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26619.5', self.close='26660.9'
127.0.0.1 - - [22/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18891 

self.closeSec=1695370199, self.tradeDate='20230922', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26660.9', self.close='26721.7'
127.0.0.1 - - [22/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18892 

self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26721.3', self.close='26686.1'
127.0.0.1 - - [22/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18890 

self.closeSec=1695367799, self.tradeDate='20230922', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26609.5', self.close='26571.8'
127.0.0.1 - - [22/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18891 

self.closeSec=1695368399, self.tradeDate='20230922', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26571.7', self.close='26593'
127.0.0.1 - - [22/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18892 

self.closeSec=1695368999, self.tradeDate='20230922', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26593', self.close='26619.5'
127.0.0.1 - - [22/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18893 

self.closeSec=1695369599, self.tradeDate='20230922', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26619.5', self.close='26660.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18894 

self.closeSec=1695370199, self.tradeDate='20230922', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26660.9', self.close='26721.7'
127.0.0.1 - - [22/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18895 

self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26721.3', self.close='26686.1'
127.0.0.1 - - [22/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  127.0.0.1 - - [22/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18890 

self.closeSec=1695367799, self.tradeDate='20230922', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='26609.5', self.close='26571.8'
127.0.0.1 - - [22/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18891 

self.closeSec=1695368399, self.tradeDate='20230922', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='26571.7', self.close='26593'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18892 

self.closeSec=1695368999, self.tradeDate='20230922', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='26593', self.close='26619.5'
127.0.0.1 - - [22/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18893 

self.closeSec=1695369599, self.tradeDate='20230922', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='26619.5', self.close='26660.9'
127.0.0.1 - - [22/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18894 

self.closeSec=1695370199, self.tradeDate='20230922', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26660.9', self.close='26721.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18895 

self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26721.3', self.close='26686.1'
127.0.0.1 - - [22/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37780
self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26715.0, self.close=26686.1, self.high=26724.1, self.low=26681.1, self.vol=1139.055, self.amt=30409880.5743 
127.0.0.1 - - [22/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-22 16:20:05,964:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230922   155500    155959  ...         0.0        0.0       0
5952  20230922   160000    160459  ...         0.0        0.0       0
5953  20230922   160500    160959  ...         0.0        0.0       0
5954  20230922   161000    161459  ...         0.0        0.0       0
5955  20230922   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 16:20:05,968:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695370799, self.tradeDate='20230922', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26715.0, self.close=26686.1, self.high=26724.1, self.low=26681.1, self.vol=1139.055, self.amt=30409880.5743, ukdf['pct'].iloc[-1]=-0.001078 , ukdf['amount'].iloc[-1]=30409880.5743, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-5804.08250244966', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26687.72842674', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=37781
self.closeSec=1695371099, self.tradeDate='20230922', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26686.1, self.close=26675.6, self.high=26692.3, self.low=26664.2, self.vol=1045.376, self.amt=27888546.4946 
127.0.0.1 - - [22/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-09-22 16:25:00,800:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230922   160000    160459  ...         0.0        0.0       0
5953  20230922   160500    160959  ...         0.0        0.0       0
5954  20230922   161000    161459  ...         0.0        0.0       0
5955  20230922   161500    161959  ...         0.0        0.0       0
5956  20230922   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-22 16:25:00,800:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1695371099, self.tradeDate='20230922', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26686.1, self.close=26675.6, self.high=26692.3, self.low=26664.2, self.vol=1045.376, self.amt=27888546.4946, ukdf['pct'].iloc[-1]=-0.000393 , ukdf['amount'].iloc[-1]=27888546.4946, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-6252.47732953012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26675.65565468', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230922   040000    075959  1695340799  ...    721  0.639944  0.565536     NaN
722  20230922   080000    115959  1695355199  ...    722  0.593971  0.427436     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-31970.4165', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26621.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [22/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1382632.8349482, self.flagDict['side']='buy', self.tradeCount=25, self.count=787
self.closeSec=1695369599, self.tradeDate='20230922', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26616.9, self.close=26660.9, self.high=26697.5, self.low=26559.4, self.vol=22748.224, self.amt=605806598.4204 
2023-09-22 16:00:01,515:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1695369599, self.tradeDate='20230922', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26616.9, self.close=26660.9, self.high=26697.5, self.low=26559.4, self.vol=22748.224, self.amt=605806598.4204 
2023-09-22 16:00:01,527:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230921   200000    235959  ...  114856.578  3.047360e+09 -0.005804
720  20230922   000000    035959  ...   36722.499  9.768476e+08  0.000719
721  20230922   040000    075959  ...   18947.754  5.032164e+08 -0.001275
722  20230922   080000    115959  ...   37097.683  9.863139e+08  0.002399
723  20230922   120000    155959  ...   22748.224  6.058066e+08  0.001664

[5 rows x 11 columns]
2023-09-22 16:00:02,165:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230921   200000    235959  1695311999  ...    719  0.683797  0.714745     1.0
720  20230922   000000    035959  1695326399  ...    720  0.662706  0.642095     1.0
721  20230922   040000    075959  1695340799  ...    721  0.639944  0.565536     NaN
722  20230922   080000    115959  1695355199  ...    722  0.593971  0.427436     NaN
723  20230922   120000    155959  1695369599  ...    723  0.653103  0.571336     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '50.787', 'enterprice': '27251.4', 'countrevence': '0', 'unrealprofit': '-29989.7235', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26660.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


