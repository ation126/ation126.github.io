# 20230309 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [09/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29308
self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=21705.5, self.close=21684.1, self.high=21713.7, self.low=21681.7, self.vol=1263.732, self.amt=27419385.4079 
2023-03-09 08:20:01,807:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230309   075500    075959  ...         0.0        0.0       0
5856  20230309   080000    080459  ...         0.0        0.0       0
5857  20230309   080500    080959  ...         0.0        0.0       0
5858  20230309   081000    081459  ...         0.0        0.0       0
5859  20230309   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 08:20:01,810:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=21705.5, self.close=21684.1, self.high=21713.7, self.low=21681.7, self.vol=1263.732, self.amt=27419385.4079, ukdf['pct'].iloc[-1]=-0.000991 , ukdf['amount'].iloc[-1]=27419385.4079, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-310253.50834594224', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21685.06821899', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29309
self.closeSec=1678321499, self.tradeDate='20230309', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=21684.0, self.close=21717.0, self.high=21717.0, self.low=21684.0, self.vol=1195.427, self.amt=25941315.2003 
127.0.0.1 - - [09/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:25:01,573:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230309   080000    080459  ...         0.0        0.0       0
5857  20230309   080500    080959  ...         0.0        0.0       0
5858  20230309   081000    081459  ...         0.0        0.0       0
5859  20230309   081500    081959  ...         0.0        0.0       0
5860  20230309   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 08:25:01,573:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678321499, self.tradeDate='20230309', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=21684.0, self.close=21717.0, self.high=21717.0, self.low=21684.0, self.vol=1195.427, self.amt=25941315.2003, ukdf['pct'].iloc[-1]=0.001517 , ukdf['amount'].iloc[-1]=25941315.2003, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-312175.0352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21717', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=21705.5, self.close=21684.1, self.high=21713.7, self.low=21681.7 
127.0.0.1 - - [09/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:20:01,643:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=21705.5, self.close=21684.1, self.high=21713.7, self.low=21681.7   
2023-03-09 08:20:01,722:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230309   075500    075959  1678319999  ...  21681.4  0.000355   1535    5
1536  20230309   080000    080459  1678320299  ...  21668.6  0.000028   1536    0
1537  20230309   080500    080959  1678320599  ...  21681.5  0.001226   1537    1
1538  20230309   081000    081459  1678320899  ...  21696.0 -0.000783   1538    2
1539  20230309   081500    081959  1678321199  ...  21681.7 -0.000991   1539    3

[5 rows x 11 columns]
2023-03-09 08:20:01,722:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6883198601758979, self.count=29875 

self.closeSec=1678321499, self.tradeDate='20230309', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=21684.0, self.close=21717.0, self.high=21717.0, self.low=21684.0 
2023-03-09 08:25:01,500:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678321499, self.tradeDate='20230309', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=21684.0, self.close=21717.0, self.high=21717.0, self.low=21684.0   
127.0.0.1 - - [09/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:25:01,553:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230309   080000    080459  1678320299  ...  21668.6  0.000028   1536    0
1537  20230309   080500    080959  1678320599  ...  21681.5  0.001226   1537    1
1538  20230309   081000    081459  1678320899  ...  21696.0 -0.000783   1538    2
1539  20230309   081500    081959  1678321199  ...  21681.7 -0.000991   1539    3
1540  20230309   082000    082459  1678321499  ...  21684.0  0.001517   1540    4

[5 rows x 11 columns]
2023-03-09 08:25:01,553:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-09 08:00:34,318:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230309    052959  22095.2  ...  43.750000  0.470812  0.539979
5771  20230309    055959  22068.8  ...  43.750000  0.454020  0.538262
5772  20230309    062959  22004.9  ...  43.333333  0.450493  0.538823
5773  20230309    065959  21991.3  ...  42.916667  0.404659  0.547336
5774  20230309    072959  21792.7  ...  42.500000  0.383510  0.562742

[5 rows x 33 columns]
0.5508317929759704
acc is : 0.5508317929759704
2023-03-09 08:00:34,492:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.505655  0.494345       0  ...  0.931061   1.0  0.0000  0.956357
537     1  0.482085  0.517915       0  ...  0.930481   1.0  0.0000  0.955761
538     0  0.503952  0.496048       0  ...  0.922197   1.0  0.0000  0.947252
539     1  0.396330  0.603670       0  ...  0.925122  -1.0 -0.0016  0.942732
540     1  0.408687  0.591313       1  ...  0.924955  -1.0  0.0000  0.942901

[5 rows x 10 columns]
2023-03-09 08:00:34,517:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.506091  0.493909       0  ...  0.931061   1.0  0.0000  0.956889
46     1  0.482198  0.517802       0  ...  0.930481   1.0  0.0000  0.954778
47     0  0.504337  0.495663       0  ...  0.922197   1.0  0.0000  0.947540
48     1  0.396330  0.603670       0  ...  0.925122  -1.0 -0.0016  0.942732
49     1  0.408687  0.591313       1  ...  0.924955  -1.0  0.0000  0.942901

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.495', 'enterprice': '21711.9', 'countrevence': '0', 'unrealprofit': '304.68421829285', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21702.22594957', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230309   075000    075959  1678319999  21713.3  21695.4 -0.000829
2023-03-09 08:00:02,198:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [09/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14936 

self.closeSec=1678320599, self.tradeDate='20230309', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21695.3', self.close='21722.5'
2023-03-09 08:10:01,726:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678320599, self.tradeDate='20230309', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21695.3', self.close='21722.5'
2023-03-09 08:10:01,769:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230309   072000    072959  1678318199  21715.9  21691.5 -0.001082
621  20230309   073000    073959  1678318799  21691.5  21693.8  0.000106
622  20230309   074000    074959  1678319399  21693.7  21713.4  0.000903
623  20230309   075000    075959  1678319999  21713.3  21695.4 -0.000829
624  20230309   080000    080959  1678320599  21695.3  21722.5  0.001249
2023-03-09 08:10:01,769:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14937 

self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21722.5', self.close='21684.1'
127.0.0.1 - - [09/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:20:01,781:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21722.5', self.close='21684.1'
2023-03-09 08:20:01,807:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230309   073000    073959  1678318799  21691.5  21693.8  0.000106
622  20230309   074000    074959  1678319399  21693.7  21713.4  0.000903
623  20230309   075000    075959  1678319999  21713.3  21695.4 -0.000829
624  20230309   080000    080959  1678320599  21695.3  21722.5  0.001249
625  20230309   081000    081959  1678321199  21722.5  21684.1 -0.001768
2023-03-09 08:20:01,808:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230309   075000    075959  1678319999  21713.3  21695.4
2023-03-09 08:00:02,176:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14937 

self.closeSec=1678320599, self.tradeDate='20230309', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21695.3', self.close='21722.5'
2023-03-09 08:10:01,745:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678320599, self.tradeDate='20230309', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21695.3', self.close='21722.5'
127.0.0.1 - - [09/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:10:01,783:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230309   072000    072959  1678318199  21715.9  21691.5
17469  20230309   073000    073959  1678318799  21691.5  21693.8
17470  20230309   074000    074959  1678319399  21693.7  21713.4
17471  20230309   075000    075959  1678319999  21713.3  21695.4
17472  20230309   080000    080959  1678320599  21695.3  21722.5
2023-03-09 08:10:01,783:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14938 

self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21722.5', self.close='21684.1'
127.0.0.1 - - [09/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:20:01,721:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21722.5', self.close='21684.1'
2023-03-09 08:20:01,775:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230309   073000    073959  1678318799  21691.5  21693.8
17470  20230309   074000    074959  1678319399  21693.7  21713.4
17471  20230309   075000    075959  1678319999  21713.3  21695.4
17472  20230309   080000    080959  1678320599  21695.3  21722.5
17473  20230309   081000    081959  1678321199  21722.5  21684.1
2023-03-09 08:20:01,776:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230309   075000    075959  1678319999  21713.3  21695.4
2023-03-09 08:00:02,171:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14937 

self.closeSec=1678320599, self.tradeDate='20230309', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='21695.3', self.close='21722.5'
2023-03-09 08:10:01,704:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678320599, self.tradeDate='20230309', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='21695.3', self.close='21722.5'
127.0.0.1 - - [09/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:10:01,716:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230309   072000    072959  1678318199  21715.9  21691.5
12141  20230309   073000    073959  1678318799  21691.5  21693.8
12142  20230309   074000    074959  1678319399  21693.7  21713.4
12143  20230309   075000    075959  1678319999  21713.3  21695.4
12144  20230309   080000    080959  1678320599  21695.3  21722.5
2023-03-09 08:10:01,716:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14938 

self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='21722.5', self.close='21684.1'
127.0.0.1 - - [09/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:20:01,735:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='21722.5', self.close='21684.1'
2023-03-09 08:20:01,800:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230309   073000    073959  1678318799  21691.5  21693.8
12142  20230309   074000    074959  1678319399  21693.7  21713.4
12143  20230309   075000    075959  1678319999  21713.3  21695.4
12144  20230309   080000    080959  1678320599  21695.3  21722.5
12145  20230309   081000    081959  1678321199  21722.5  21684.1
2023-03-09 08:20:01,800:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25306
self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=21705.5, self.close=21684.1, self.high=21713.7, self.low=21681.7, self.vol=1263.732, self.amt=27419385.4079 
127.0.0.1 - - [09/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:20:01,723:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230309   075500    075959  ...         0.0        0.0       0
5856  20230309   080000    080459  ...         0.0        0.0       0
5857  20230309   080500    080959  ...         0.0        0.0       0
5858  20230309   081000    081459  ...         0.0        0.0       0
5859  20230309   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 08:20:01,729:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678321199, self.tradeDate='20230309', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=21705.5, self.close=21684.1, self.high=21713.7, self.low=21681.7, self.vol=1263.732, self.amt=27419385.4079, ukdf['pct'].iloc[-1]=-0.000991 , ukdf['amount'].iloc[-1]=27419385.4079, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [09/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25307
self.closeSec=1678321499, self.tradeDate='20230309', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=21684.0, self.close=21717.0, self.high=21717.0, self.low=21684.0, self.vol=1195.427, self.amt=25941315.2003 
2023-03-09 08:25:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230309   080000    080459  ...         0.0        0.0       0
5857  20230309   080500    080959  ...         0.0        0.0       0
5858  20230309   081000    081459  ...         0.0        0.0       0
5859  20230309   081500    081959  ...         0.0        0.0       0
5860  20230309   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-09 08:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678321499, self.tradeDate='20230309', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=21684.0, self.close=21717.0, self.high=21717.0, self.low=21684.0, self.vol=1195.427, self.amt=25941315.2003, ukdf['pct'].iloc[-1]=0.001517 , ukdf['amount'].iloc[-1]=25941315.2003, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230308   200000    235959  1678291199  ...    719  0.142494 -1.353199    -1.0
720  20230309   000000    035959  1678305599  ...    720  0.172296 -1.266241    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '57160.341', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21993.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=622
self.closeSec=1678319999, self.tradeDate='20230309', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=21993.8, self.close=21695.3, self.high=22127.4, self.low=21540.5, self.vol=124293.667, self.amt=2713468779.9131 
127.0.0.1 - - [09/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-09 08:00:01,929:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678319999, self.tradeDate='20230309', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=21993.8, self.close=21695.3, self.high=22127.4, self.low=21540.5, self.vol=124293.667, self.amt=2713468779.9131 
2023-03-09 08:00:02,023:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230308   120000    155959  ...   89535.701  1.968240e+09 -0.008111
718  20230308   160000    195959  ...   56848.317  1.252963e+09  0.004508
719  20230308   200000    235959  ...  148584.459  3.274852e+09  0.003096
720  20230309   000000    035959  ...   77456.277  1.708864e+09 -0.006137
721  20230309   040000    075959  ...  124293.667  2.713469e+09 -0.013568

[5 rows x 11 columns]
2023-03-09 08:00:04,493:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230308   120000    155959  1678262399  ...    717  0.067822 -1.613690    -1.0
718  20230308   160000    195959  1678276799  ...    718  0.111385 -1.452801    -1.0
719  20230308   200000    235959  1678291199  ...    719  0.142494 -1.353199    -1.0
720  20230309   000000    035959  1678305599  ...    720  0.172296 -1.266241    -1.0
721  20230309   040000    075959  1678319999  ...    721  0.169537 -1.290595    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '69733.425', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '21695.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


