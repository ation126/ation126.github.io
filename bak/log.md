# 20230502 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44949
self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28094.3, self.close=28089.1, self.high=28107.0, self.low=28080.4, self.vol=927.166, self.amt=26046340.2184 
127.0.0.1 - - [02/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-02 16:20:06,486:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230502   155500    155959  ...         0.0        0.0       0
5952  20230502   160000    160459  ...         0.0        0.0       0
5953  20230502   160500    160959  ...         0.0        0.0       0
5954  20230502   161000    161459  ...         0.0        0.0       0
5955  20230502   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 16:20:06,494:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28094.3, self.close=28089.1, self.high=28107.0, self.low=28080.4, self.vol=927.166, self.amt=26046340.2184, ukdf['pct'].iloc[-1]=-0.000189 , ukdf['amount'].iloc[-1]=26046340.2184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695510.258919912', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28087.2343745', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=44950
self.closeSec=1683015899, self.tradeDate='20230502', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28089.1, self.close=28073.8, self.high=28103.0, self.low=28073.7, self.vol=665.415, self.amt=18689836.9024 
127.0.0.1 - - [02/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
2023-05-02 16:25:02,061:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230502   160000    160459  ...         0.0        0.0       0
5953  20230502   160500    160959  ...         0.0        0.0       0
5954  20230502   161000    161459  ...         0.0        0.0       0
5955  20230502   161500    161959  ...         0.0        0.0       0
5956  20230502   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 16:25:02,061:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683015899, self.tradeDate='20230502', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28089.1, self.close=28073.8, self.high=28103.0, self.low=28073.7, self.vol=665.415, self.amt=18689836.9024, ukdf['pct'].iloc[-1]=-0.000545 , ukdf['amount'].iloc[-1]=18689836.9024, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-694645.3346160472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28072.86113095', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45511 

self.closeSec=1683014399, self.tradeDate='20230502', self.openTime='155500', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28019.2, self.close=28045.0, self.high=28047.2, self.low=28019.2 
127.0.0.1 - - [02/May/2023 16:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45512 

self.closeSec=1683014699, self.tradeDate='20230502', self.openTime='160000', self.closeTime='160459', self.symbol='BTCUSDT', self.open=28045.1, self.close=28063.9, self.high=28071.2, self.low=28044.3 
127.0.0.1 - - [02/May/2023 16:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45513 

self.closeSec=1683014999, self.tradeDate='20230502', self.openTime='160500', self.closeTime='160959', self.symbol='BTCUSDT', self.open=28063.9, self.close=28113.5, self.high=28116.5, self.low=28063.9 
127.0.0.1 - - [02/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45514 

self.closeSec=1683015299, self.tradeDate='20230502', self.openTime='161000', self.closeTime='161459', self.symbol='BTCUSDT', self.open=28113.5, self.close=28094.4, self.high=28121.8, self.low=28081.0 
127.0.0.1 - - [02/May/2023 16:15:04] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45515 

self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28094.3, self.close=28089.1, self.high=28107.0, self.low=28080.4 
127.0.0.1 - - [02/May/2023 16:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=45516 

self.closeSec=1683015899, self.tradeDate='20230502', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28089.1, self.close=28073.8, self.high=28103.0, self.low=28073.7 
127.0.0.1 - - [02/May/2023 16:25:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-02 16:00:19,701:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5785  20230502    132959  27916.9  ...  48.750000  0.407148  0.733186
5786  20230502    135959  27937.3  ...  49.166667  0.415994  0.727750
5787  20230502    142959  27987.2  ...  49.166667  0.413772  0.723889
5788  20230502    145959  27969.5  ...  49.583333  0.416266  0.719335
5789  20230502    152959  27983.3  ...  49.583333  0.429444  0.710030

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-05-02 16:00:19,806:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.524567  0.475433       1  ...  0.862599   1.0    0.0  0.989667
538     0  0.537611  0.462389       0  ...  0.862056   1.0    0.0  0.989045
539     0  0.515773  0.484227       1  ...  0.862482   1.0    0.0  0.989533
540     0  0.528468  0.471532       1  ...  0.864744   1.0    0.0  0.992129
541     0  0.547992  0.452008       0  ...  0.864380   1.0    0.0  0.991711

[5 rows x 10 columns]
2023-05-02 16:00:19,831:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524614  0.475386       1  ...  0.862599   1.0    0.0  0.991087
46     0  0.538090  0.461910       0  ...  0.862056   1.0    0.0  0.991285
47     0  0.515824  0.484176       1  ...  0.862482   1.0    0.0  0.991268
48     0  0.528901  0.471099       1  ...  0.864744   1.0    0.0  0.997221
49     0  0.547992  0.452008       0  ...  0.864380   1.0    0.0  0.991711

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22753 

self.closeSec=1683012599, self.tradeDate='20230502', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28053.5', self.close='28056.8'
127.0.0.1 - - [02/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22754 

self.closeSec=1683013199, self.tradeDate='20230502', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28056.7', self.close='28026.3'
127.0.0.1 - - [02/May/2023 15:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22755 

self.closeSec=1683013799, self.tradeDate='20230502', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28026.2', self.close='28001.6'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22756 

self.closeSec=1683014399, self.tradeDate='20230502', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28001.7', self.close='28045'
127.0.0.1 - - [02/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22757 

self.closeSec=1683014999, self.tradeDate='20230502', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28045.1', self.close='28113.5'
127.0.0.1 - - [02/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22758 

self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28113.5', self.close='28089.1'
127.0.0.1 - - [02/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


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


--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22754 

self.closeSec=1683012599, self.tradeDate='20230502', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28053.5', self.close='28056.8'
127.0.0.1 - - [02/May/2023 15:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22755 

self.closeSec=1683013199, self.tradeDate='20230502', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28056.7', self.close='28026.3'
127.0.0.1 - - [02/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22756 

self.closeSec=1683013799, self.tradeDate='20230502', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28026.2', self.close='28001.6'
127.0.0.1 - - [02/May/2023 15:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22757 

self.closeSec=1683014399, self.tradeDate='20230502', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28001.7', self.close='28045'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22758 

self.closeSec=1683014999, self.tradeDate='20230502', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28045.1', self.close='28113.5'
127.0.0.1 - - [02/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22759 

self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28113.5', self.close='28089.1'
127.0.0.1 - - [02/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22754 

self.closeSec=1683012599, self.tradeDate='20230502', self.openTime='152000', self.closeTime='152959', self.symbol='BTCUSDT', self.open='28053.5', self.close='28056.8'
127.0.0.1 - - [02/May/2023 15:30:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/May/2023 15:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22755 

self.closeSec=1683013199, self.tradeDate='20230502', self.openTime='153000', self.closeTime='153959', self.symbol='BTCUSDT', self.open='28056.7', self.close='28026.3'
127.0.0.1 - - [02/May/2023 15:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22756 

self.closeSec=1683013799, self.tradeDate='20230502', self.openTime='154000', self.closeTime='154959', self.symbol='BTCUSDT', self.open='28026.2', self.close='28001.6'
127.0.0.1 - - [02/May/2023 16:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22757 

self.closeSec=1683014399, self.tradeDate='20230502', self.openTime='155000', self.closeTime='155959', self.symbol='BTCUSDT', self.open='28001.7', self.close='28045'
127.0.0.1 - - [02/May/2023 16:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22758 

self.closeSec=1683014999, self.tradeDate='20230502', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28045.1', self.close='28113.5'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=22759 

self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28113.5', self.close='28089.1'
127.0.0.1 - - [02/May/2023 16:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40947
self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28094.3, self.close=28089.1, self.high=28107.0, self.low=28080.4, self.vol=927.166, self.amt=26046340.2184 
127.0.0.1 - - [02/May/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-05-02 16:20:06,485:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230502   155500    155959  ...         0.0        0.0       0
5952  20230502   160000    160459  ...         0.0        0.0       0
5953  20230502   160500    160959  ...         0.0        0.0       0
5954  20230502   161000    161459  ...         0.0        0.0       0
5955  20230502   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 16:20:06,493:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683015599, self.tradeDate='20230502', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28094.3, self.close=28089.1, self.high=28107.0, self.low=28080.4, self.vol=927.166, self.amt=26046340.2184, ukdf['pct'].iloc[-1]=-0.000189 , ukdf['amount'].iloc[-1]=26046340.2184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/May/2023 16:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=40948
self.closeSec=1683015899, self.tradeDate='20230502', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28089.1, self.close=28073.8, self.high=28103.0, self.low=28073.7, self.vol=665.415, self.amt=18689836.9024 
2023-05-02 16:25:02,060:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230502   160000    160459  ...         0.0        0.0       0
5953  20230502   160500    160959  ...         0.0        0.0       0
5954  20230502   161000    161459  ...         0.0        0.0       0
5955  20230502   161500    161959  ...         0.0        0.0       0
5956  20230502   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-02 16:25:02,060:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683015899, self.tradeDate='20230502', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28089.1, self.close=28073.8, self.high=28103.0, self.low=28073.7, self.vol=665.415, self.amt=18689836.9024, ukdf['pct'].iloc[-1]=-0.000545 , ukdf['amount'].iloc[-1]=18689836.9024, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230502   040000    075959  1682985599  ...    721  0.467685 -0.435252     NaN
722  20230502   080000    115959  1682999999  ...    722  0.530782 -0.259239     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '61209.9236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28031.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1369396.0865466, self.flagDict['side']='sell', self.tradeCount=33, self.count=948
self.closeSec=1683014399, self.tradeDate='20230502', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28031.9, self.close=28045.0, self.high=28158.0, self.low=27854.0, self.vol=39868.257, self.amt=1116406659.24734 
127.0.0.1 - - [02/May/2023 16:00:02] "POST / HTTP/1.1" 200 -
2023-05-02 16:00:02,039:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683014399, self.tradeDate='20230502', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28031.9, self.close=28045.0, self.high=28158.0, self.low=27854.0, self.vol=39868.257, self.amt=1116406659.24734 
2023-05-02 16:00:02,084:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230501   200000    235959  ...  130179.626  3.688902e+09 -0.012357
720  20230502   000000    035959  ...  148882.200  4.182104e+09 -0.011521
721  20230502   040000    075959  ...   85032.810  2.372994e+09  0.007922
722  20230502   080000    115959  ...   44341.090  1.241580e+09 -0.000802
723  20230502   120000    155959  ...   39868.257  1.116407e+09  0.000467

[5 rows x 11 columns]
2023-05-02 16:00:04,071:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230501   200000    235959  1682956799  ...    719  0.199479 -1.238036    -1.0
720  20230502   000000    035959  1682971199  ...    720  0.349701 -0.784732    -1.0
721  20230502   040000    075959  1682985599  ...    721  0.467685 -0.435252     NaN
722  20230502   080000    115959  1682999999  ...    722  0.530782 -0.259239     NaN
723  20230502   120000    155959  1683014399  ...    723  0.582597 -0.113055     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '46.718', 'enterprice': '29341.3', 'countrevence': '0', 'unrealprofit': '60492.05407058534', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28046.46601587', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


