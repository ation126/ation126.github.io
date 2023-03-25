# 20230325 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33916
self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27458.9, self.close=27452.8, self.high=27487.2, self.low=27451.0, self.vol=1444.639, self.amt=39682959.2355 
127.0.0.1 - - [25/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-25 08:20:06,777:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230325   075500    075959  ...         0.0        0.0       0
5856  20230325   080000    080459  ...         0.0        0.0       0
5857  20230325   080500    080959  ...         0.0        0.0       0
5858  20230325   081000    081459  ...         0.0        0.0       0
5859  20230325   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 08:20:06,798:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27458.9, self.close=27452.8, self.high=27487.2, self.low=27451.0, self.vol=1444.639, self.amt=39682959.2355, ukdf['pct'].iloc[-1]=-0.0002 , ukdf['amount'].iloc[-1]=39682959.2355, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-657392.712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27453.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33917
self.closeSec=1679703899, self.tradeDate='20230325', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27452.8, self.close=27447.9, self.high=27460.9, self.low=27440.0, self.vol=496.716, self.amt=13634385.7344 
127.0.0.1 - - [25/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-25 08:25:01,585:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230325   080000    080459  ...         0.0        0.0       0
5857  20230325   080500    080959  ...         0.0        0.0       0
5858  20230325   081000    081459  ...         0.0        0.0       0
5859  20230325   081500    081959  ...         0.0        0.0       0
5860  20230325   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 08:25:01,585:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679703899, self.tradeDate='20230325', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27452.8, self.close=27447.9, self.high=27460.9, self.low=27440.0, self.vol=496.716, self.amt=13634385.7344, ukdf['pct'].iloc[-1]=-0.000178 , ukdf['amount'].iloc[-1]=13634385.7344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-657053.09026756096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27448.15619296', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27458.9, self.close=27452.8, self.high=27487.2, self.low=27451.0 
127.0.0.1 - - [25/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-25 08:20:03,658:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27458.9, self.close=27452.8, self.high=27487.2, self.low=27451.0   
2023-03-25 08:20:04,467:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230325   075500    075959  1679702399  ...  27405.5  0.000978   1535    5
1536  20230325   080000    080459  1679702699  ...  27410.2 -0.000394   1536    0
1537  20230325   080500    080959  1679702999  ...  27414.3  0.000255   1537    1
1538  20230325   081000    081459  1679703299  ...  27409.9  0.000846   1538    2
1539  20230325   081500    081959  1679703599  ...  27451.0 -0.000200   1539    3

[5 rows x 11 columns]
2023-03-25 08:20:04,468:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=364, self.factor=0.5475229178400647, self.count=34483 

self.closeSec=1679703899, self.tradeDate='20230325', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27452.8, self.close=27447.9, self.high=27460.9, self.low=27440.0 
127.0.0.1 - - [25/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-25 08:25:01,515:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679703899, self.tradeDate='20230325', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27452.8, self.close=27447.9, self.high=27460.9, self.low=27440.0   
2023-03-25 08:25:01,599:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230325   080000    080459  1679702699  ...  27410.2 -0.000394   1536    0
1537  20230325   080500    080959  1679702999  ...  27414.3  0.000255   1537    1
1538  20230325   081000    081459  1679703299  ...  27409.9  0.000846   1538    2
1539  20230325   081500    081959  1679703599  ...  27451.0 -0.000200   1539    3
1540  20230325   082000    082459  1679703899  ...  27440.0 -0.000178   1540    4

[5 rows x 11 columns]
2023-03-25 08:25:01,600:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

5771  20230325    055959  27174.8  ...  50.416667  0.444784  0.568533
5772  20230325    062959  27315.0  ...  50.416667  0.453330  0.575988
5773  20230325    065959  27399.2  ...  50.000000  0.443328  0.588758
5774  20230325    072959  27279.4  ...  50.000000  0.459961  0.592724

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-03-25 08:00:35,664:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.388322  0.611678       1  ...  0.986059  -1.0 -0.0016  1.138405
537     0  0.539170  0.460830       1  ...  0.983049  -1.0  0.0000  1.141881
538     0  0.530277  0.469723       0  ...  0.987347  -1.0  0.0000  1.136888
539     1  0.476202  0.523798       1  ...  0.981415  -1.0  0.0000  1.143719
540     0  0.572117  0.427883       0  ...  0.979687   1.0 -0.0016  1.143535

[5 rows x 10 columns]
2023-03-25 08:00:35,735:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.384549  0.615451       1  ...  0.978288  -1.0 -0.0016  1.138078
46     0  0.540026  0.459974       1  ...  0.987024  -1.0  0.0000  1.141633
47     0  0.529350  0.470650       0  ...  0.999904  -1.0  0.0000  1.137452
48     1  0.476202  0.523798       1  ...  0.981415  -1.0  0.0000  1.143719
49     0  0.572117  0.427883       0  ...  0.979687   1.0 -0.0016  1.143535

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-03-25 08:00:35,999:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '27.875', 'buy' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:764882.321986235', 'result': 'success', 'clientorderid': ''}
2023-03-25 08:00:36,015:INFO:logic:main.py:494:insertFactor:885513: curDateTime:3250800, name:logic, symbol:BTCUSDT, tradeDate:20230325, closeTime:075959, close:27438.9, sign:1, total:767183.2585902, side:buy  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230325   075000    075959  1679702399  27398.1  27438.9  0.001493
2023-03-25 08:00:01,891:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17240 

self.closeSec=1679702999, self.tradeDate='20230325', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27439', self.close='27435.1'
2023-03-25 08:10:01,612:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679702999, self.tradeDate='20230325', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27439', self.close='27435.1'
2023-03-25 08:10:01,644:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230325   072000    072959  1679700599  27361.4  27443.3  0.002990
621  20230325   073000    073959  1679701199  27443.2  27401.8 -0.001512
622  20230325   074000    074959  1679701799  27401.9    27398 -0.000139
623  20230325   075000    075959  1679702399  27398.1  27438.9  0.001493
624  20230325   080000    080959  1679702999    27439  27435.1 -0.000138
2023-03-25 08:10:01,644:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17241 

self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27435.1', self.close='27452.8'
127.0.0.1 - - [25/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-25 08:20:06,017:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27435.1', self.close='27452.8'
2023-03-25 08:20:06,678:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230325   073000    073959  1679701199  27443.2  27401.8 -0.001512
622  20230325   074000    074959  1679701799  27401.9    27398 -0.000139
623  20230325   075000    075959  1679702399  27398.1  27438.9  0.001493
624  20230325   080000    080959  1679702999    27439  27435.1 -0.000138
625  20230325   081000    081959  1679703599  27435.1  27452.8  0.000645
2023-03-25 08:20:06,686:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230325   075000    075959  1679702399  27398.1  27438.9
2023-03-25 08:00:01,935:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [25/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17241 

self.closeSec=1679702999, self.tradeDate='20230325', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27439', self.close='27435.1'
2023-03-25 08:10:01,618:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679702999, self.tradeDate='20230325', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27439', self.close='27435.1'
2023-03-25 08:10:01,652:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230325   072000    072959  1679700599  27361.4  27443.3
17469  20230325   073000    073959  1679701199  27443.2  27401.8
17470  20230325   074000    074959  1679701799  27401.9    27398
17471  20230325   075000    075959  1679702399  27398.1  27438.9
17472  20230325   080000    080959  1679702999    27439  27435.1
2023-03-25 08:10:01,652:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17242 

self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27435.1', self.close='27452.8'
127.0.0.1 - - [25/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-25 08:20:08,709:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27435.1', self.close='27452.8'
2023-03-25 08:20:08,842:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230325   073000    073959  1679701199  27443.2  27401.8
17470  20230325   074000    074959  1679701799  27401.9    27398
17471  20230325   075000    075959  1679702399  27398.1  27438.9
17472  20230325   080000    080959  1679702999    27439  27435.1
17473  20230325   081000    081959  1679703599  27435.1  27452.8
2023-03-25 08:20:08,843:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230325   075000    075959  1679702399  27398.1  27438.9
2023-03-25 08:00:01,967:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [25/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17241 

self.closeSec=1679702999, self.tradeDate='20230325', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27439', self.close='27435.1'
2023-03-25 08:10:01,580:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679702999, self.tradeDate='20230325', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27439', self.close='27435.1'
2023-03-25 08:10:01,624:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230325   072000    072959  1679700599  27361.4  27443.3
12141  20230325   073000    073959  1679701199  27443.2  27401.8
12142  20230325   074000    074959  1679701799  27401.9    27398
12143  20230325   075000    075959  1679702399  27398.1  27438.9
12144  20230325   080000    080959  1679702999    27439  27435.1
2023-03-25 08:10:01,624:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17242 

self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27435.1', self.close='27452.8'
127.0.0.1 - - [25/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-25 08:20:08,169:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27435.1', self.close='27452.8'
2023-03-25 08:20:08,505:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230325   073000    073959  1679701199  27443.2  27401.8
12142  20230325   074000    074959  1679701799  27401.9    27398
12143  20230325   075000    075959  1679702399  27398.1  27438.9
12144  20230325   080000    080959  1679702999    27439  27435.1
12145  20230325   081000    081959  1679703599  27435.1  27452.8
2023-03-25 08:20:08,506:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--: 127.0.0.1 - - [25/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29914
self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27458.9, self.close=27452.8, self.high=27487.2, self.low=27451.0, self.vol=1444.639, self.amt=39682959.2355 
2023-03-25 08:20:02,397:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230325   075500    075959  ...         0.0        0.0       0
5856  20230325   080000    080459  ...         0.0        0.0       0
5857  20230325   080500    080959  ...         0.0        0.0       0
5858  20230325   081000    081459  ...         0.0        0.0       0
5859  20230325   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 08:20:02,417:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679703599, self.tradeDate='20230325', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27458.9, self.close=27452.8, self.high=27487.2, self.low=27451.0, self.vol=1444.639, self.amt=39682959.2355, ukdf['pct'].iloc[-1]=-0.0002 , ukdf['amount'].iloc[-1]=39682959.2355, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29915
self.closeSec=1679703899, self.tradeDate='20230325', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27452.8, self.close=27447.9, self.high=27460.9, self.low=27440.0, self.vol=496.716, self.amt=13634385.7344 
127.0.0.1 - - [25/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-25 08:25:01,591:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230325   080000    080459  ...         0.0        0.0       0
5857  20230325   080500    080959  ...         0.0        0.0       0
5858  20230325   081000    081459  ...         0.0        0.0       0
5859  20230325   081500    081959  ...         0.0        0.0       0
5860  20230325   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-25 08:25:01,592:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679703899, self.tradeDate='20230325', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27452.8, self.close=27447.9, self.high=27460.9, self.low=27440.0, self.vol=496.716, self.amt=13634385.7344, ukdf['pct'].iloc[-1]=-0.000178 , ukdf['amount'].iloc[-1]=13634385.7344, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230324   200000    235959  1679673599  ...    719  0.014419 -2.039357    -1.0
720  20230325   000000    035959  1679687999  ...    720  0.014771 -1.994090    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '14993.16369327366', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27811.92888889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [25/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=718
self.closeSec=1679702399, self.tradeDate='20230325', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27811.4, self.close=27438.9, self.high=27854.4, self.low=26960.0, self.vol=124877.686, self.amt=3416321164.03079 
2023-03-25 08:00:01,778:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679702399, self.tradeDate='20230325', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27811.4, self.close=27438.9, self.high=27854.4, self.low=26960.0, self.vol=124877.686, self.amt=3416321164.03079 
2023-03-25 08:00:01,839:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230324   120000    155959  ...   45073.281  1.272364e+09  0.002077
718  20230324   160000    195959  ...  143929.417  4.016502e+09 -0.024567
719  20230324   200000    235959  ...  208669.320  5.828417e+09  0.015296
720  20230325   000000    035959  ...  128438.580  3.563114e+09 -0.006640
721  20230325   040000    075959  ...  124877.686  3.416321e+09 -0.013390

[5 rows x 11 columns]
2023-03-25 08:00:04,552:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230324   120000    155959  1679644799  ...    717  0.015430 -2.159293    -1.0
718  20230324   160000    195959  1679659199  ...    718  0.016784 -2.093610    -1.0
719  20230324   200000    235959  1679673599  ...    719  0.014419 -2.039357    -1.0
720  20230325   000000    035959  1679687999  ...    720  0.014771 -1.994090    -1.0
721  20230325   040000    075959  1679702399  ...    721  0.018761 -1.935128    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '34765.70557405824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27443.76626496', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


