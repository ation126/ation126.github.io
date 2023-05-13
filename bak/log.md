# 20230514 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

[5 rows x 10 columns]
2023-05-13 23:04:04,904:INFO:amihud:main.py:487:getuklines:2202413: ukdf.iloc[:5,:] :
  tradeDate openTime closeTime  ...        vol           amt       pct
0  20230423   000000    000459  ...   2143.430  5.892513e+07  0.000000
1  20230423   000500    000959  ...  10031.220  2.767596e+08  0.002963
2  20230423   001000    001459  ...   6018.813  1.662074e+08  0.001965
3  20230423   001500    001959  ...   3872.109  1.069941e+08 -0.000999
4  20230423   002000    002459  ...   2501.026  6.902111e+07 -0.001358

[5 rows x 11 columns]
2023-05-13 23:04:04,915:INFO:amihud:main.py:488:getuklines:2202413: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...      vol           amt       pct
6032  20230513   224000    224459  ...  658.253  1.762930e+07 -0.000780
6033  20230513   224500    224959  ...  961.831  2.578102e+07  0.000904
6034  20230513   225000    225459  ...  565.991  1.516236e+07 -0.000881
6035  20230513   225500    225959  ...  904.939  2.422452e+07  0.000108
6036  20230513   230000    230459  ...  771.101  2.063724e+07  0.000000

[5 rows x 11 columns]
2023-05-13 23:04:10,407:INFO:amihud:main.py:568:run:2202413: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
6032  20230513   224000    224459  ...    0.524652   0.120992       0
6033  20230513   224500    224959  ...    0.524772   0.121045       0
6034  20230513   225000    225459  ...    0.524891   0.121102       0
6035  20230513   225500    225959  ...    0.525009   0.121157       0
6036  20230513   230000    230459  ...    0.525123   0.121215       0

[5 rows x 18 columns]
2023-05-13 23:04:10,888:INFO:amihud:main.py:206:queryContractAssets:2202413: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '-1231005.1917114', 'total': '997787.4786886', 'margin': '1611729.9136', 'unreal': '-617062.7568', 'type': 'AssetType_ucontract'}]}
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-617116.9152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26784.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [13/May/2023 22:05:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48752 

self.closeSec=1683986699, self.tradeDate='20230513', self.openTime='220000', self.closeTime='220459', self.symbol='BTCUSDT', self.open=26810.7, self.close=26814.3, self.high=26831.7, self.low=26810.6 
127.0.0.1 - - [13/May/2023 22:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48753 

self.closeSec=1683986999, self.tradeDate='20230513', self.openTime='220500', self.closeTime='220959', self.symbol='BTCUSDT', self.open=26814.3, self.close=26798.2, self.high=26838.5, self.low=26798.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48754 

self.closeSec=1683987299, self.tradeDate='20230513', self.openTime='221000', self.closeTime='221459', self.symbol='BTCUSDT', self.open=26798.2, self.close=26807.5, self.high=26807.5, self.low=26784.9 
127.0.0.1 - - [13/May/2023 22:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48755 

self.closeSec=1683987599, self.tradeDate='20230513', self.openTime='221500', self.closeTime='221959', self.symbol='BTCUSDT', self.open=26807.5, self.close=26784.0, self.high=26807.5, self.low=26780.3 
127.0.0.1 - - [13/May/2023 22:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 22:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48756 

self.closeSec=1683987899, self.tradeDate='20230513', self.openTime='222000', self.closeTime='222459', self.symbol='BTCUSDT', self.open=26784.1, self.close=26789.0, self.high=26791.3, self.low=26780.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=48757 

self.closeSec=1683988199, self.tradeDate='20230513', self.openTime='222500', self.closeTime='222959', self.symbol='BTCUSDT', self.open=26789.0, self.close=26756.7, self.high=26789.0, self.low=26722.8 
127.0.0.1 - - [13/May/2023 22:30:02] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

5798  20230513    195959  26821.8  ...  50.416667  0.501018  0.222591
5799  20230513    202959  26814.4  ...  50.416667  0.499220  0.217029
5800  20230513    205959  26803.9  ...  50.833333  0.500188  0.211537
5801  20230513    212959  26809.5  ...  50.416667  0.500045  0.206456
5802  20230513    215959  26808.5  ...  50.833333  0.500428  0.201598

[5 rows x 33 columns]
0.5156537753222836
acc is : 0.5156537753222836
2023-05-13 22:30:19,620:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
538     1  0.493084  0.506916       0  ...  0.966263   1.0    0.0  0.957850
539     1  0.488922  0.511078       1  ...  0.966461   1.0    0.0  0.958047
540     1  0.497245  0.502755       0  ...  0.966432   1.0    0.0  0.958018
541     1  0.492935  0.507065       1  ...  0.966508   1.0    0.0  0.958093
542     1  0.493007  0.506993       0  ...  0.964561   1.0    0.0  0.956163

[5 rows x 10 columns]
2023-05-13 22:30:19,631:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493411  0.506589       0  ...  0.966263   1.0    0.0  0.960132
46     1  0.488693  0.511307       1  ...  0.966461   1.0    0.0  0.959627
47     1  0.497205  0.502795       0  ...  0.966432   1.0    0.0  0.957888
48     1  0.493042  0.506958       1  ...  0.966508   1.0    0.0  0.958566
49     1  0.493007  0.506993       0  ...  0.964561   1.0    0.0  0.956163

[5 rows x 10 columns]
2023-05-13 22:30:19,654:ERROR:client:client.py:127:__post:885513: connect error
2023-05-13 22:30:19,654:ERROR:client:client.py:127:__post:885513: connect error
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24374 

self.closeSec=1683985199, self.tradeDate='20230513', self.openTime='213000', self.closeTime='213959', self.symbol='BTCUSDT', self.open='26808.5', self.close='26781.9'
127.0.0.1 - - [13/May/2023 21:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24375 

self.closeSec=1683985799, self.tradeDate='20230513', self.openTime='214000', self.closeTime='214959', self.symbol='BTCUSDT', self.open='26781.9', self.close='26781'
127.0.0.1 - - [13/May/2023 21:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24376 

self.closeSec=1683986399, self.tradeDate='20230513', self.openTime='215000', self.closeTime='215959', self.symbol='BTCUSDT', self.open='26781', self.close='26810.7'
127.0.0.1 - - [13/May/2023 22:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24377 

self.closeSec=1683986999, self.tradeDate='20230513', self.openTime='220000', self.closeTime='220959', self.symbol='BTCUSDT', self.open='26810.7', self.close='26798.2'
127.0.0.1 - - [13/May/2023 22:10:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 22:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24378 

self.closeSec=1683987599, self.tradeDate='20230513', self.openTime='221000', self.closeTime='221959', self.symbol='BTCUSDT', self.open='26798.2', self.close='26784'
127.0.0.1 - - [13/May/2023 22:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24379 

self.closeSec=1683988199, self.tradeDate='20230513', self.openTime='222000', self.closeTime='222959', self.symbol='BTCUSDT', self.open='26784.1', self.close='26756.7'


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

127.0.0.1 - - [13/May/2023 21:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24375 

self.closeSec=1683985199, self.tradeDate='20230513', self.openTime='213000', self.closeTime='213959', self.symbol='BTCUSDT', self.open='26808.5', self.close='26781.9'
127.0.0.1 - - [13/May/2023 21:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24376 

self.closeSec=1683985799, self.tradeDate='20230513', self.openTime='214000', self.closeTime='214959', self.symbol='BTCUSDT', self.open='26781.9', self.close='26781'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24377 

self.closeSec=1683986399, self.tradeDate='20230513', self.openTime='215000', self.closeTime='215959', self.symbol='BTCUSDT', self.open='26781', self.close='26810.7'
127.0.0.1 - - [13/May/2023 22:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 22:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24378 

self.closeSec=1683986999, self.tradeDate='20230513', self.openTime='220000', self.closeTime='220959', self.symbol='BTCUSDT', self.open='26810.7', self.close='26798.2'
127.0.0.1 - - [13/May/2023 22:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24379 

self.closeSec=1683987599, self.tradeDate='20230513', self.openTime='221000', self.closeTime='221959', self.symbol='BTCUSDT', self.open='26798.2', self.close='26784'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24380 

self.closeSec=1683988199, self.tradeDate='20230513', self.openTime='222000', self.closeTime='222959', self.symbol='BTCUSDT', self.open='26784.1', self.close='26756.7'
127.0.0.1 - - [13/May/2023 22:30:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24375 

self.closeSec=1683985199, self.tradeDate='20230513', self.openTime='213000', self.closeTime='213959', self.symbol='BTCUSDT', self.open='26808.5', self.close='26781.9'
127.0.0.1 - - [13/May/2023 21:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 21:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24376 

self.closeSec=1683985799, self.tradeDate='20230513', self.openTime='214000', self.closeTime='214959', self.symbol='BTCUSDT', self.open='26781.9', self.close='26781'
127.0.0.1 - - [13/May/2023 22:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24377 

self.closeSec=1683986399, self.tradeDate='20230513', self.openTime='215000', self.closeTime='215959', self.symbol='BTCUSDT', self.open='26781', self.close='26810.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24378 

self.closeSec=1683986999, self.tradeDate='20230513', self.openTime='220000', self.closeTime='220959', self.symbol='BTCUSDT', self.open='26810.7', self.close='26798.2'
127.0.0.1 - - [13/May/2023 22:10:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [13/May/2023 22:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24379 

self.closeSec=1683987599, self.tradeDate='20230513', self.openTime='221000', self.closeTime='221959', self.symbol='BTCUSDT', self.open='26798.2', self.close='26784'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=24380 

self.closeSec=1683988199, self.tradeDate='20230513', self.openTime='222000', self.closeTime='222959', self.symbol='BTCUSDT', self.open='26784.1', self.close='26756.7'
127.0.0.1 - - [13/May/2023 22:30:03] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=44188
self.closeSec=1683987899, self.tradeDate='20230513', self.openTime='222000', self.closeTime='222459', self.symbol='BTCUSDT', self.open=26784.1, self.close=26789.0, self.high=26791.3, self.low=26780.0, self.vol=507.226, self.amt=13586440.4678 
127.0.0.1 - - [13/May/2023 22:25:02] "POST / HTTP/1.1" 200 -
2023-05-13 22:25:02,180:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
6024  20230513   220000    220459  ...         0.0        0.0       0
6025  20230513   220500    220959  ...         0.0        0.0       0
6026  20230513   221000    221459  ...         0.0        0.0       0
6027  20230513   221500    221959  ...         0.0        0.0       0
6028  20230513   222000    222459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 22:25:02,181:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683987899, self.tradeDate='20230513', self.openTime='222000', self.closeTime='222459',self.symbol='BTCUSDT',self.open=26784.1, self.close=26789.0, self.high=26791.3, self.low=26780.0, self.vol=507.226, self.amt=13586440.4678, ukdf['pct'].iloc[-1]=0.000187 , ukdf['amount'].iloc[-1]=13586440.4678, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=6028, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=44189
self.closeSec=1683988199, self.tradeDate='20230513', self.openTime='222500', self.closeTime='222959', self.symbol='BTCUSDT', self.open=26789.0, self.close=26756.7, self.high=26789.0, self.low=26722.8, self.vol=2417.078, self.amt=64660666.6558 
127.0.0.1 - - [13/May/2023 22:30:02] "POST / HTTP/1.1" 200 -
2023-05-13 22:30:02,641:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
6025  20230513   220500    220959  ...         0.0        0.0       0
6026  20230513   221000    221459  ...         0.0        0.0       0
6027  20230513   221500    221959  ...         0.0        0.0       0
6028  20230513   222000    222459  ...         0.0        0.0       0
6029  20230513   222500    222959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-13 22:30:02,641:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683988199, self.tradeDate='20230513', self.openTime='222500', self.closeTime='222959',self.symbol='BTCUSDT',self.open=26789.0, self.close=26756.7, self.high=26789.0, self.low=26722.8, self.vol=2417.078, self.amt=64660666.6558, ukdf['pct'].iloc[-1]=-0.001206 , ukdf['amount'].iloc[-1]=64660666.6558, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=6029, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

722  20230513   080000    115959  1683950399  ...    722  0.440599 -0.034408     NaN
723  20230513   120000    155959  1683964799  ...    723  0.463283  0.076900     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '3115.3042953582', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26759.28844505', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1404859.0878468, self.flagDict['side']='sell', self.tradeCount=35, self.count=1015
self.closeSec=1683979199, self.tradeDate='20230513', self.openTime='160000', self.closeTime='195959', self.symbol='BTCUSDT', self.open=26759.2, self.close=26814.3, self.high=26864.8, self.low=26727.3, self.vol=27857.048, self.amt=746497577.5357 
127.0.0.1 - - [13/May/2023 20:00:04] "POST / HTTP/1.1" 200 -
2023-05-13 20:00:04,922:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683979199, self.tradeDate='20230513', self.openTime='160000', self.closeTime='195959',self.symbol='BTCUSDT',self.open=26759.2, self.close=26814.3, self.high=26864.8, self.low=26727.3, self.vol=27857.048, self.amt=746497577.5357 
2023-05-13 20:00:05,089:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
720  20230513   000000    035959  ...  132224.157  3.458559e+09  0.005227
721  20230513   040000    075959  ...  107072.897  2.850922e+09  0.012853
722  20230513   080000    115959  ...   56653.067  1.519934e+09  0.000355
723  20230513   120000    155959  ...   32070.296  8.581604e+08 -0.001317
724  20230513   160000    195959  ...   27857.048  7.464976e+08  0.002055

[5 rows x 11 columns]
2023-05-13 20:00:06,497:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
720  20230513   000000    035959  1683921599  ...    720  0.421779 -0.152010     NaN
721  20230513   040000    075959  1683935999  ...    721  0.430637 -0.094261     NaN
722  20230513   080000    115959  1683950399  ...    722  0.440599 -0.034408     NaN
723  20230513   120000    155959  1683964799  ...    723  0.463283  0.076900     NaN
724  20230513   160000    195959  1683979199  ...    724  0.480886  0.165427     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-141.5772', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26821.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


