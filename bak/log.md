# 20231007 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42004
self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27901.0, self.close=27892.3, self.high=27901.1, self.low=27870.0, self.vol=1634.978, self.amt=45587924.8956 
127.0.0.1 - - [07/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-07 08:20:06,643:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231007   075500    075959  ...         0.0        0.0       0
5856  20231007   080000    080459  ...         0.0        0.0       0
5857  20231007   080500    080959  ...         0.0        0.0       0
5858  20231007   081000    081459  ...         0.0        0.0       0
5859  20231007   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 08:20:06,654:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27901.0, self.close=27892.3, self.high=27901.1, self.low=27870.0, self.vol=1634.978, self.amt=45587924.8956, ukdf['pct'].iloc[-1]=-0.000315 , ukdf['amount'].iloc[-1]=45587924.8956, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-14221.05720145374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27886.08750549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=42005
self.closeSec=1696638299, self.tradeDate='20231007', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27888.7, self.close=27843.7, self.high=27888.8, self.low=27836.0, self.vol=2561.723, self.amt=71371818.8445 
127.0.0.1 - - [07/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-07 08:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231007   080000    080459  ...         0.0        0.0       0
5857  20231007   080500    080959  ...         0.0        0.0       0
5858  20231007   081000    081459  ...         0.0        0.0       0
5859  20231007   081500    081959  ...         0.0        0.0       0
5860  20231007   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 08:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1696638299, self.tradeDate='20231007', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27888.7, self.close=27843.7, self.high=27888.8, self.low=27836.0, self.vol=2561.723, self.amt=71371818.8445, ukdf['pct'].iloc[-1]=-0.001742 , ukdf['amount'].iloc[-1]=71371818.8445, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-13625.1984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27843.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

127.0.0.1 - - [07/Oct/2023 08:00:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42002 

self.closeSec=1696636799, self.tradeDate='20231007', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27916.5, self.close=27916.3, self.high=27936.5, self.low=27916.2 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42003 

self.closeSec=1696637099, self.tradeDate='20231007', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27916.3, self.close=27925.3, self.high=27928.9, self.low=27892.1 
127.0.0.1 - - [07/Oct/2023 08:05:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42004 

self.closeSec=1696637399, self.tradeDate='20231007', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27923.4, self.close=27914.8, self.high=27944.6, self.low=27913.1 
127.0.0.1 - - [07/Oct/2023 08:10:00] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 08:15:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42005 

self.closeSec=1696637699, self.tradeDate='20231007', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27910.7, self.close=27901.1, self.high=27935.8, self.low=27901.0 

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42006 

self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27901.0, self.close=27892.3, self.high=27901.1, self.low=27870.0 
127.0.0.1 - - [07/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.714181719035411, self.count=42007 

self.closeSec=1696638299, self.tradeDate='20231007', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27888.7, self.close=27843.7, self.high=27888.8, self.low=27836.0 
127.0.0.1 - - [07/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/logic/log.txt ----- -----

2023-10-07 08:00:19,359:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20231007    052959  27963.5  ...  55.833333  0.560341  0.285721
5770  20231007    055959  27986.5  ...  55.833333  0.567468  0.288295
5771  20231007    062959  28030.2  ...  55.416667  0.567386  0.290719
5772  20231007    065959  28030.0  ...  55.000000  0.553497  0.296490
5773  20231007    072959  27956.1  ...  55.000000  0.539681  0.305472

[5 rows x 33 columns]
0.5462962962962963
acc is : 0.5462962962962963
2023-10-07 08:00:19,419:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.512399  0.487601       1  ...  0.982809   1.0    0.0  1.063970
536     0  0.515597  0.484403       1  ...  0.982795   1.0    0.0  1.063955
537     0  0.505274  0.494726       0  ...  0.980408   1.0    0.0  1.061370
538     1  0.479818  0.520182       0  ...  0.977960   1.0    0.0  1.058721
539     1  0.474381  0.525619       1  ...  0.978840   1.0    0.0  1.059674

[5 rows x 10 columns]
2023-10-07 08:00:19,430:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512575  0.487425       1  ...  0.982809   1.0    0.0  1.068647
46     0  0.515374  0.484626       1  ...  0.982795   1.0    0.0  1.063273
47     0  0.505504  0.494496       0  ...  0.980408   1.0    0.0  1.062815
48     1  0.479964  0.520036       0  ...  0.977960   1.0    0.0  1.062998
49     1  0.474381  0.525619       1  ...  0.978840   1.0    0.0  1.059674

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.669', 'enterprice': '27936.3', 'countrevence': '0', 'unrealprofit': '-421.1045424564', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27918.5086044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=20999 

self.closeSec=1696634999, self.tradeDate='20231007', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27888.2', self.close='27892'
127.0.0.1 - - [07/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21000 

self.closeSec=1696635599, self.tradeDate='20231007', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27891.9', self.close='27926.9'
127.0.0.1 - - [07/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21001 

self.closeSec=1696636199, self.tradeDate='20231007', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27926.9', self.close='27923.3'
127.0.0.1 - - [07/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21002 

self.closeSec=1696636799, self.tradeDate='20231007', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27923.3', self.close='27916.3'
127.0.0.1 - - [07/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21003 

self.closeSec=1696637399, self.tradeDate='20231007', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27916.3', self.close='27910.7'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21004 

self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27910.7', self.close='27892.3'
127.0.0.1 - - [07/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [07/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21002 

self.closeSec=1696634999, self.tradeDate='20231007', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27888.2', self.close='27892'
127.0.0.1 - - [07/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21003 

self.closeSec=1696635599, self.tradeDate='20231007', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27891.9', self.close='27926.9'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21004 

self.closeSec=1696636199, self.tradeDate='20231007', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27926.9', self.close='27923.3'
127.0.0.1 - - [07/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21005 

self.closeSec=1696636799, self.tradeDate='20231007', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27923.3', self.close='27916.3'
127.0.0.1 - - [07/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21006 

self.closeSec=1696637399, self.tradeDate='20231007', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27916.3', self.close='27910.7'
127.0.0.1 - - [07/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21007 

self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27910.7', self.close='27892.3'
127.0.0.1 - - [07/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21002 

self.closeSec=1696634999, self.tradeDate='20231007', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27888.2', self.close='27892'
127.0.0.1 - - [07/Oct/2023 07:30:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21003 

self.closeSec=1696635599, self.tradeDate='20231007', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27891.9', self.close='27926.9'
127.0.0.1 - - [07/Oct/2023 07:40:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21004 

self.closeSec=1696636199, self.tradeDate='20231007', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27926.9', self.close='27923.3'
127.0.0.1 - - [07/Oct/2023 07:50:01] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [07/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21005 

self.closeSec=1696636799, self.tradeDate='20231007', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27923.3', self.close='27916.3'
127.0.0.1 - - [07/Oct/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21006 

self.closeSec=1696637399, self.tradeDate='20231007', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27916.3', self.close='27910.7'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=21007 

self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27910.7', self.close='27892.3'
127.0.0.1 - - [07/Oct/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42004
self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27901.0, self.close=27892.3, self.high=27901.1, self.low=27870.0, self.vol=1634.978, self.amt=45587924.8956 
127.0.0.1 - - [07/Oct/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-10-07 08:20:06,633:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20231007   075500    075959  ...         0.0        0.0       0
5856  20231007   080000    080459  ...         0.0        0.0       0
5857  20231007   080500    080959  ...         0.0        0.0       0
5858  20231007   081000    081459  ...         0.0        0.0       0
5859  20231007   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 08:20:06,636:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696637999, self.tradeDate='20231007', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27901.0, self.close=27892.3, self.high=27901.1, self.low=27870.0, self.vol=1634.978, self.amt=45587924.8956, ukdf['pct'].iloc[-1]=-0.000315 , ukdf['amount'].iloc[-1]=45587924.8956, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '38704.17204140409', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27886.08750549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=42005
self.closeSec=1696638299, self.tradeDate='20231007', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27888.7, self.close=27843.7, self.high=27888.8, self.low=27836.0, self.vol=2561.723, self.amt=71371818.8445 
127.0.0.1 - - [07/Oct/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-10-07 08:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20231007   080000    080459  ...         0.0        0.0       0
5857  20231007   080500    080959  ...         0.0        0.0       0
5858  20231007   081000    081459  ...         0.0        0.0       0
5859  20231007   081500    081959  ...         0.0        0.0       0
5860  20231007   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-10-07 08:25:00,805:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1696638299, self.tradeDate='20231007', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27888.7, self.close=27843.7, self.high=27888.8, self.low=27836.0, self.vol=2561.723, self.amt=71371818.8445, ukdf['pct'].iloc[-1]=-0.001742 , ukdf['amount'].iloc[-1]=71371818.8445, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '37115.0013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27843.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20231006   200000    235959  1696607999  ...    719  0.332489 -0.923390    -1.0
720  20231007   000000    035959  1696622399  ...    720  0.067516 -1.587487    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '178.7477', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27940.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1217073.7147932001, self.flagDict['side']='sell', self.tradeCount=32, self.count=875
self.closeSec=1696636799, self.tradeDate='20231007', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27939.1, self.close=27916.3, self.high=28450.0, self.low=27861.0, self.vol=61484.735, self.amt=1724950747.50893 
127.0.0.1 - - [07/Oct/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-10-07 08:00:01,559:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1696636799, self.tradeDate='20231007', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27939.1, self.close=27916.3, self.high=28450.0, self.low=27861.0, self.vol=61484.735, self.amt=1724950747.50893 
2023-10-07 08:00:01,576:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20231006   120000    155959  ...   29146.062  8.023779e+08  0.002992
718  20231006   160000    195959  ...   52608.948  1.455988e+09  0.004231
719  20231006   200000    235959  ...  192444.274  5.308505e+09  0.006578
720  20231007   000000    035959  ...   74169.479  2.070069e+09  0.000351
721  20231007   040000    075959  ...   61484.735  1.724951e+09 -0.000716

[5 rows x 11 columns]
2023-10-07 08:00:02,384:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20231006   120000    155959  1696579199  ...    717  0.892012  0.555175     NaN
718  20231006   160000    195959  1696593599  ...    718  0.737146  0.143416     NaN
719  20231006   200000    235959  1696607999  ...    719  0.332489 -0.923390    -1.0
720  20231007   000000    035959  1696622399  ...    720  0.067516 -1.587487    -1.0
721  20231007   040000    075959  1696636799  ...    721  0.195185 -1.229155    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '43.597', 'enterprice': '27944.4', 'countrevence': '0', 'unrealprofit': '1187.85128787701', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27917.15382967', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


