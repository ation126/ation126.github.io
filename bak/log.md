# 20230906 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33172
self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25721.3, self.close=25726.1, self.high=25726.1, self.low=25713.2, self.vol=274.269, self.amt=7053655.1991 
127.0.0.1 - - [06/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-06 16:20:06,342:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230906   155500    155959  ...         0.0        0.0       0
5952  20230906   160000    160459  ...         0.0        0.0       0
5953  20230906   160500    160959  ...         0.0        0.0       0
5954  20230906   161000    161459  ...         0.0        0.0       0
5955  20230906   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 16:20:06,345:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25721.3, self.close=25726.1, self.high=25726.1, self.low=25713.2, self.vol=274.269, self.amt=7053655.1991, ukdf['pct'].iloc[-1]=0.000191 , ukdf['amount'].iloc[-1]=7053655.1991, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15839.4324', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25727.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=33173
self.closeSec=1693988699, self.tradeDate='20230906', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25726.1, self.close=25730.4, self.high=25736.8, self.low=25723.7, self.vol=275.023, self.amt=7076524.1789 
2023-09-06 16:25:00,777:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230906   160000    160459  ...         0.0        0.0       0
5953  20230906   160500    160959  ...         0.0        0.0       0
5954  20230906   161000    161459  ...         0.0        0.0       0
5955  20230906   161500    161959  ...         0.0        0.0       0
5956  20230906   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 16:25:00,778:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1693988699, self.tradeDate='20230906', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25726.1, self.close=25730.4, self.high=25736.8, self.low=25723.7, self.vol=275.023, self.amt=7076524.1789, ukdf['pct'].iloc[-1]=0.000167 , ukdf['amount'].iloc[-1]=7076524.1789, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '15799.047', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25730.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [06/Sep/2023 16:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33170 

self.closeSec=1693987199, self.tradeDate='20230906', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25730.0, self.close=25715.0, self.high=25730.0, self.low=25711.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33171 

self.closeSec=1693987499, self.tradeDate='20230906', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=25715.1, self.close=25724.5, self.high=25726.2, self.low=25713.0 
127.0.0.1 - - [06/Sep/2023 16:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33172 

self.closeSec=1693987799, self.tradeDate='20230906', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=25724.5, self.close=25728.0, self.high=25728.0, self.low=25717.1 
127.0.0.1 - - [06/Sep/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33173 

self.closeSec=1693988099, self.tradeDate='20230906', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=25728.0, self.close=25721.2, self.high=25728.0, self.low=25711.0 
127.0.0.1 - - [06/Sep/2023 16:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33174 

self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25721.3, self.close=25726.1, self.high=25726.1, self.low=25713.2 
127.0.0.1 - - [06/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=33175 

self.closeSec=1693988699, self.tradeDate='20230906', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25726.1, self.close=25730.4, self.high=25736.8, self.low=25723.7 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-09-06 16:00:19,034:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230906    132959  25741.9  ...  49.166667  0.483222  0.455399
5786  20230906    135959  25745.8  ...  49.166667  0.479335  0.462809
5787  20230906    142959  25735.6  ...  49.583333  0.485340  0.466392
5788  20230906    145959  25750.3  ...  50.000000  0.491733  0.466173
5789  20230906    152959  25765.7  ...  50.416667  0.492480  0.465554

[5 rows x 33 columns]
0.5239852398523985
acc is : 0.5239852398523985
2023-09-06 16:00:19,130:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485202  0.514798       0  ...  1.006643  -1.0    0.0  0.988694
538     1  0.483428  0.516572       1  ...  1.006075  -1.0    0.0  0.989251
539     1  0.494387  0.505613       1  ...  1.005470  -1.0    0.0  0.989846
540     1  0.497986  0.502014       1  ...  1.005400  -1.0    0.0  0.989915
541     1  0.496612  0.503388       0  ...  1.007448  -1.0    0.0  0.987899

[5 rows x 10 columns]
2023-09-06 16:00:19,150:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485382  0.514618       0  ...  1.006643  -1.0    0.0  0.988174
46     1  0.483926  0.516074       1  ...  1.006075  -1.0    0.0  0.989414
47     1  0.494541  0.505459       1  ...  1.005470  -1.0    0.0  0.989018
48     1  0.497787  0.502213       1  ...  1.005400  -1.0    0.0  0.988196
49     1  0.496612  0.503388       0  ...  1.007448  -1.0    0.0  0.987899

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.263', 'enterprice': '26682.7', 'countrevence': '0', 'unrealprofit': '25419.9577', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25714.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16583 

self.closeSec=1693985399, self.tradeDate='20230906', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25751.7', self.close='25767.5'
127.0.0.1 - - [06/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16584 

self.closeSec=1693985999, self.tradeDate='20230906', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25767.6', self.close='25766.2'
127.0.0.1 - - [06/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16585 

self.closeSec=1693986599, self.tradeDate='20230906', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25766.1', self.close='25751.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16586 

self.closeSec=1693987199, self.tradeDate='20230906', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25751.5', self.close='25715'
127.0.0.1 - - [06/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16587 

self.closeSec=1693987799, self.tradeDate='20230906', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25715.1', self.close='25728'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16588 

self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25728', self.close='25726.1'
127.0.0.1 - - [06/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16586 

self.closeSec=1693985399, self.tradeDate='20230906', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25751.7', self.close='25767.5'
127.0.0.1 - - [06/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16587 

self.closeSec=1693985999, self.tradeDate='20230906', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25767.6', self.close='25766.2'
127.0.0.1 - - [06/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16588 

self.closeSec=1693986599, self.tradeDate='20230906', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25766.1', self.close='25751.6'
127.0.0.1 - - [06/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16589 

self.closeSec=1693987199, self.tradeDate='20230906', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25751.5', self.close='25715'
127.0.0.1 - - [06/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16590 

self.closeSec=1693987799, self.tradeDate='20230906', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25715.1', self.close='25728'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16591 

self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25728', self.close='25726.1'
127.0.0.1 - - [06/Sep/2023 16:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16586 

self.closeSec=1693985399, self.tradeDate='20230906', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='25751.7', self.close='25767.5'
127.0.0.1 - - [06/Sep/2023 15:30:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [06/Sep/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16587 

self.closeSec=1693985999, self.tradeDate='20230906', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='25767.6', self.close='25766.2'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16588 

127.0.0.1 - - [06/Sep/2023 15:50:01] "POST / HTTP/1.1" 200 -
self.closeSec=1693986599, self.tradeDate='20230906', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='25766.1', self.close='25751.6'
127.0.0.1 - - [06/Sep/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16589 

self.closeSec=1693987199, self.tradeDate='20230906', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='25751.5', self.close='25715'
127.0.0.1 - - [06/Sep/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16590 

self.closeSec=1693987799, self.tradeDate='20230906', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25715.1', self.close='25728'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16591 

self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25728', self.close='25726.1'
127.0.0.1 - - [06/Sep/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33172
self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25721.3, self.close=25726.1, self.high=25726.1, self.low=25713.2, self.vol=274.269, self.amt=7053655.1991 
127.0.0.1 - - [06/Sep/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-09-06 16:20:06,339:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230906   155500    155959  ...         0.0        0.0       0
5952  20230906   160000    160459  ...         0.0        0.0       0
5953  20230906   160500    160959  ...         0.0        0.0       0
5954  20230906   161000    161459  ...         0.0        0.0       0
5955  20230906   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 16:20:06,342:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693988399, self.tradeDate='20230906', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25721.3, self.close=25726.1, self.high=25726.1, self.low=25713.2, self.vol=274.269, self.amt=7053655.1991, ukdf['pct'].iloc[-1]=0.000191 , ukdf['amount'].iloc[-1]=7053655.1991, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41467.9265', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25727.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [06/Sep/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=33173
self.closeSec=1693988699, self.tradeDate='20230906', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25726.1, self.close=25730.4, self.high=25736.8, self.low=25723.7, self.vol=275.023, self.amt=7076524.1789 
2023-09-06 16:25:00,784:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230906   160000    160459  ...         0.0        0.0       0
5953  20230906   160500    160959  ...         0.0        0.0       0
5954  20230906   161000    161459  ...         0.0        0.0       0
5955  20230906   161500    161959  ...         0.0        0.0       0
5956  20230906   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-09-06 16:25:00,784:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1693988699, self.tradeDate='20230906', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25726.1, self.close=25730.4, self.high=25736.8, self.low=25723.7, self.vol=275.023, self.amt=7076524.1789, ukdf['pct'].iloc[-1]=0.000167 , ukdf['amount'].iloc[-1]=7076524.1789, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-41360.2176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25730.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230906   040000    075959  1693958399  ...    721  0.144573 -0.675100    -1.0
722  20230906   080000    115959  1693972799  ...    722  0.223616 -0.456905     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '6971.41043724249', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25770.37316863', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [06/Sep/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1478963.5930628998, self.flagDict['side']='sell', self.tradeCount=22, self.count=691
self.closeSec=1693987199, self.tradeDate='20230906', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=25770.1, self.close=25715.0, self.high=25780.9, self.low=25711.0, self.vol=14492.862, self.amt=373191657.2905 
2023-09-06 16:00:01,849:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1693987199, self.tradeDate='20230906', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=25770.1, self.close=25715.0, self.high=25780.9, self.low=25711.0, self.vol=14492.862, self.amt=373191657.2905 
2023-09-06 16:00:01,867:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230905   200000    235959  ...  67199.020  1.730131e+09 -0.000912
720  20230906   000000    035959  ...  25402.722  6.540294e+08 -0.003006
721  20230906   040000    075959  ...  13973.252  3.594576e+08  0.004258
722  20230906   080000    115959  ...  16399.582  4.230987e+08 -0.000372
723  20230906   120000    155959  ...  14492.862  3.731917e+08 -0.002138

[5 rows x 11 columns]
2023-09-06 16:00:02,873:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230905   200000    235959  1693929599  ...    719  0.002931 -1.066895    -1.0
720  20230906   000000    035959  1693943999  ...    720  0.018338 -1.025426    -1.0
721  20230906   040000    075959  1693958399  ...    721  0.144573 -0.675100    -1.0
722  20230906   080000    115959  1693972799  ...    722  0.223616 -0.456905     NaN
723  20230906   120000    155959  1693987199  ...    723  0.235360 -0.430896     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.177', 'enterprice': '25892.3', 'countrevence': '0', 'unrealprofit': '10137.4821', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25715', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


