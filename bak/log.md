# 20230510 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47157
self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27640.9, self.close=27691.0, self.high=27697.8, self.low=27632.2, self.vol=1729.649, self.amt=47859910.0284 
127.0.0.1 - - [10/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-10 08:20:05,785:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230510   075500    075959  ...         0.0        0.0       0
5856  20230510   080000    080459  ...         0.0        0.0       0
5857  20230510   080500    080959  ...         0.0        0.0       0
5858  20230510   081000    081459  ...         0.0        0.0       0
5859  20230510   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 08:20:05,786:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27640.9, self.close=27691.0, self.high=27697.8, self.low=27632.2, self.vol=1729.649, self.amt=47859910.0284, ukdf['pct'].iloc[-1]=0.001809 , ukdf['amount'].iloc[-1]=47859910.0284, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-671828.9344', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27693.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=47158
self.closeSec=1683678299, self.tradeDate='20230510', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27690.9, self.close=27719.3, self.high=27740.0, self.low=27686.1, self.vol=2285.827, self.amt=63354764.66042 
2023-05-10 08:25:02,102:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230510   080000    080459  ...         0.0        0.0       0
5857  20230510   080500    080959  ...         0.0        0.0       0
5858  20230510   081000    081459  ...         0.0        0.0       0
5859  20230510   081500    081959  ...         0.0        0.0       0
5860  20230510   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 08:25:02,103:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1683678299, self.tradeDate='20230510', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27690.9, self.close=27719.3, self.high=27740.0, self.low=27686.1, self.vol=2285.827, self.amt=63354764.66042, ukdf['pct'].iloc[-1]=0.001022 , ukdf['amount'].iloc[-1]=63354764.66042, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-673387.4928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27719.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47719 

self.closeSec=1683676799, self.tradeDate='20230510', self.openTime='075500', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27633.5, self.close=27610.2, self.high=27633.6, self.low=27610.2 
127.0.0.1 - - [10/May/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47720 

self.closeSec=1683677099, self.tradeDate='20230510', self.openTime='080000', self.closeTime='080459', self.symbol='BTCUSDT', self.open=27610.2, self.close=27623.0, self.high=27623.7, self.low=27605.0 
127.0.0.1 - - [10/May/2023 08:05:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47721 

self.closeSec=1683677399, self.tradeDate='20230510', self.openTime='080500', self.closeTime='080959', self.symbol='BTCUSDT', self.open=27623.0, self.close=27618.8, self.high=27636.6, self.low=27613.9 
127.0.0.1 - - [10/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47722 

self.closeSec=1683677699, self.tradeDate='20230510', self.openTime='081000', self.closeTime='081459', self.symbol='BTCUSDT', self.open=27618.9, self.close=27641.0, self.high=27641.3, self.low=27618.8 
127.0.0.1 - - [10/May/2023 08:15:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47723 

self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27640.9, self.close=27691.0, self.high=27697.8, self.low=27632.2 
127.0.0.1 - - [10/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 08:25:02] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=23, self.factor=0.43541661550691446, self.count=47724 

self.closeSec=1683678299, self.tradeDate='20230510', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27690.9, self.close=27719.3, self.high=27740.0, self.low=27686.1 


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-10 08:00:22,512:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5769  20230510    052959  27636.0  ...  48.750000  0.458525  0.480981
5770  20230510    055959  27614.9  ...  48.333333  0.454730  0.479108
5771  20230510    062959  27589.6  ...  48.333333  0.447294  0.483989
5772  20230510    065959  27540.2  ...  48.333333  0.451702  0.485351
5773  20230510    072959  27564.0  ...  48.333333  0.453989  0.484977

[5 rows x 33 columns]
0.5462962962962963
acc is : 0.5462962962962963
2023-05-10 08:00:22,621:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
535     0  0.502740  0.497260       0  ...  1.026296   1.0    0.0  0.944044
536     1  0.495811  0.504189       0  ...  1.024451   1.0    0.0  0.942347
537     1  0.479343  0.520657       1  ...  1.025340   1.0    0.0  0.943165
538     1  0.499578  0.500422       1  ...  1.025797   1.0    0.0  0.943586
539     1  0.498223  0.501777       1  ...  1.027058   1.0    0.0  0.944746

[5 rows x 10 columns]
2023-05-10 08:00:22,648:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502866  0.497134       0  ...  1.012382   1.0    0.0  0.946996
46     1  0.496058  0.503942       0  ...  1.010562   1.0    0.0  0.945313
47     1  0.479392  0.520608       1  ...  1.011439   1.0    0.0  0.942050
48     1  0.499787  0.500213       1  ...  1.011890   1.0    0.0  0.944142
49     1  0.498223  0.501777       1  ...  1.027058   1.0    0.0  0.944746

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----


--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23857 

self.closeSec=1683674999, self.tradeDate='20230510', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27568.6', self.close='27576.3'
127.0.0.1 - - [10/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23858 

self.closeSec=1683675599, self.tradeDate='20230510', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27576.3', self.close='27583.4'
127.0.0.1 - - [10/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23859 

self.closeSec=1683676199, self.tradeDate='20230510', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27583.3', self.close='27626.3'
127.0.0.1 - - [10/May/2023 07:50:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23860 

self.closeSec=1683676799, self.tradeDate='20230510', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27626.4', self.close='27610.2'

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23861 

self.closeSec=1683677399, self.tradeDate='20230510', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27610.2', self.close='27618.8'
127.0.0.1 - - [10/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23862 

self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27618.9', self.close='27691'
127.0.0.1 - - [10/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


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

127.0.0.1 - - [10/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23858 

self.closeSec=1683674999, self.tradeDate='20230510', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27568.6', self.close='27576.3'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23859 

self.closeSec=1683675599, self.tradeDate='20230510', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27576.3', self.close='27583.4'
127.0.0.1 - - [10/May/2023 07:40:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23860 

self.closeSec=1683676199, self.tradeDate='20230510', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27583.3', self.close='27626.3'
127.0.0.1 - - [10/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23861 

self.closeSec=1683676799, self.tradeDate='20230510', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27626.4', self.close='27610.2'
127.0.0.1 - - [10/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23862 

self.closeSec=1683677399, self.tradeDate='20230510', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27610.2', self.close='27618.8'

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23863 

self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27618.9', self.close='27691'
127.0.0.1 - - [10/May/2023 08:20:04] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/similarity/log.txt ----- -----


--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23858 

self.closeSec=1683674999, self.tradeDate='20230510', self.openTime='072000', self.closeTime='072959', self.symbol='BTCUSDT', self.open='27568.6', self.close='27576.3'
127.0.0.1 - - [10/May/2023 07:30:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23859 

self.closeSec=1683675599, self.tradeDate='20230510', self.openTime='073000', self.closeTime='073959', self.symbol='BTCUSDT', self.open='27576.3', self.close='27583.4'
127.0.0.1 - - [10/May/2023 07:40:02] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [10/May/2023 07:50:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23860 

self.closeSec=1683676199, self.tradeDate='20230510', self.openTime='074000', self.closeTime='074959', self.symbol='BTCUSDT', self.open='27583.3', self.close='27626.3'

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23861 

self.closeSec=1683676799, self.tradeDate='20230510', self.openTime='075000', self.closeTime='075959', self.symbol='BTCUSDT', self.open='27626.4', self.close='27610.2'
127.0.0.1 - - [10/May/2023 08:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23862 

self.closeSec=1683677399, self.tradeDate='20230510', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27610.2', self.close='27618.8'
127.0.0.1 - - [10/May/2023 08:10:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=23863 

self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27618.9', self.close='27691'
127.0.0.1 - - [10/May/2023 08:20:05] "POST / HTTP/1.1" 200 -


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43155
self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27640.9, self.close=27691.0, self.high=27697.8, self.low=27632.2, self.vol=1729.649, self.amt=47859910.0284 
127.0.0.1 - - [10/May/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-05-10 08:20:05,695:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230510   075500    075959  ...         0.0        0.0       0
5856  20230510   080000    080459  ...         0.0        0.0       0
5857  20230510   080500    080959  ...         0.0        0.0       0
5858  20230510   081000    081459  ...         0.0        0.0       0
5859  20230510   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 08:20:05,708:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683677999, self.tradeDate='20230510', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27640.9, self.close=27691.0, self.high=27697.8, self.low=27632.2, self.vol=1729.649, self.amt=47859910.0284, ukdf['pct'].iloc[-1]=0.001809 , ukdf['amount'].iloc[-1]=47859910.0284, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [10/May/2023 08:25:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=43156
self.closeSec=1683678299, self.tradeDate='20230510', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27690.9, self.close=27719.3, self.high=27740.0, self.low=27686.1, self.vol=2285.827, self.amt=63354764.66042 
2023-05-10 08:25:02,102:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230510   080000    080459  ...         0.0        0.0       0
5857  20230510   080500    080959  ...         0.0        0.0       0
5858  20230510   081000    081459  ...         0.0        0.0       0
5859  20230510   081500    081959  ...         0.0        0.0       0
5860  20230510   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-10 08:25:02,103:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1683678299, self.tradeDate='20230510', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27690.9, self.close=27719.3, self.high=27740.0, self.low=27686.1, self.vol=2285.827, self.amt=63354764.66042, ukdf['pct'].iloc[-1]=0.001022 , ukdf['amount'].iloc[-1]=63354764.66042, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230509   200000    235959  1683647999  ...    719  0.826353  1.084247     1.0
720  20230510   000000    035959  1683662399  ...    720  0.828544  1.085154     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '5302.601', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27711.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1448108.3022399, self.flagDict['side']='buy', self.tradeCount=34, self.count=994
self.closeSec=1683676799, self.tradeDate='20230510', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27704.7, self.close=27610.2, self.high=27769.4, self.low=27501.3, self.vol=33703.303, self.amt=930979688.797 
127.0.0.1 - - [10/May/2023 08:00:03] "POST / HTTP/1.1" 200 -
2023-05-10 08:00:03,175:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1683676799, self.tradeDate='20230510', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27704.7, self.close=27610.2, self.high=27769.4, self.low=27501.3, self.vol=33703.303, self.amt=930979688.797 
2023-05-10 08:00:03,198:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230509   120000    155959  ...   47560.102  1.310025e+09  0.001333
718  20230509   160000    195959  ...   42312.157  1.167581e+09  0.000528
719  20230509   200000    235959  ...  119288.926  3.290036e+09 -0.010053
720  20230510   000000    035959  ...   78744.119  2.170562e+09  0.011645
721  20230510   040000    075959  ...   33703.303  9.309797e+08 -0.003411

[5 rows x 11 columns]
2023-05-10 08:00:04,711:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230509   120000    155959  1683619199  ...    717  0.764124  0.834596     1.0
718  20230509   160000    195959  1683633599  ...    718  0.808445  1.003837     1.0
719  20230509   200000    235959  1683647999  ...    719  0.826353  1.084247     1.0
720  20230510   000000    035959  1683662399  ...    720  0.828544  1.085154     1.0
721  20230510   040000    075959  1683676799  ...    721  0.831298  1.080613     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.501', 'enterprice': '27610.1', 'countrevence': '0', 'unrealprofit': '143.81485475339', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27612.83927839', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


