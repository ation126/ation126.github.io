# 20230401 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35836
self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28447.6, self.close=28430.0, self.high=28474.4, self.low=28400.0, self.vol=1559.18, self.amt=44338424.5945 
127.0.0.1 - - [01/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-01 00:20:08,968:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230331   235500    235959  ...         0.0        0.0       0
5760  20230401   000000    000459  ...         0.0        0.0       0
5761  20230401   000500    000959  ...         0.0        0.0       0
5762  20230401   001000    001459  ...         0.0        0.0       0
5763  20230401   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 00:20:08,981:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28447.6, self.close=28430.0, self.high=28474.4, self.low=28400.0, self.vol=1559.18, self.amt=44338424.5945, ukdf['pct'].iloc[-1]=-0.000615 , ukdf['amount'].iloc[-1]=44338424.5945, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-716335.104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28433.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35837
self.closeSec=1680279899, self.tradeDate='20230401', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28430.0, self.close=28409.0, self.high=28455.1, self.low=28388.5, self.vol=1454.582, self.amt=41340085.9647 
127.0.0.1 - - [01/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-04-01 00:25:01,680:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230401   000000    000459  ...         0.0        0.0       0
5761  20230401   000500    000959  ...         0.0        0.0       0
5762  20230401   001000    001459  ...         0.0        0.0       0
5763  20230401   001500    001959  ...         0.0        0.0       0
5764  20230401   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 00:25:01,680:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680279899, self.tradeDate='20230401', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28430.0, self.close=28409.0, self.high=28455.1, self.low=28388.5, self.vol=1454.582, self.amt=41340085.9647, ukdf['pct'].iloc[-1]=-0.000739 , ukdf['amount'].iloc[-1]=41340085.9647, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-714872.8272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28409', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28447.6, self.close=28430.0, self.high=28474.4, self.low=28400.0 
127.0.0.1 - - [01/Apr/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-04-01 00:20:05,831:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28447.6, self.close=28430.0, self.high=28474.4, self.low=28400.0   
2023-04-01 00:20:07,142:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230331   235500    235959  1680278399  ...  28426.5  0.002054   1727    5
1440  20230401   000000    000459  1680278699  ...  28467.8  0.001309   1440    0
1441  20230401   000500    000959  1680278999  ...  28450.7 -0.002629   1441    1
1442  20230401   001000    001459  1680279299  ...  28425.8 -0.000116   1442    2
1443  20230401   001500    001959  1680279599  ...  28400.0 -0.000615   1443    3

[5 rows x 11 columns]
2023-04-01 00:20:07,142:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [01/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.5368868385901041, self.count=36403 

self.closeSec=1680279899, self.tradeDate='20230401', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28430.0, self.close=28409.0, self.high=28455.1, self.low=28388.5 
2023-04-01 00:25:01,645:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680279899, self.tradeDate='20230401', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28430.0, self.close=28409.0, self.high=28455.1, self.low=28388.5   
2023-04-01 00:25:01,717:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230401   000000    000459  1680278699  ...  28467.8  0.001309   1440    0
1441  20230401   000500    000959  1680278999  ...  28450.7 -0.002629   1441    1
1442  20230401   001000    001459  1680279299  ...  28425.8 -0.000116   1442    2
1443  20230401   001500    001959  1680279599  ...  28400.0 -0.000615   1443    3
1444  20230401   002000    002459  1680279899  ...  28388.5 -0.000739   1444    4

[5 rows x 11 columns]
2023-04-01 00:25:01,717:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-01 00:00:35,877:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230331    212959  28098.0  ...  51.666667  0.527520  0.576214
5803  20230331    215959  28265.1  ...  51.666667  0.539918  0.549869
5804  20230331    222959  28361.0  ...  52.083333  0.544638  0.522951
5805  20230331    225959  28396.5  ...  52.500000  0.559283  0.497288
5806  20230331    232959  28510.1  ...  52.083333  0.538778  0.480999

[5 rows x 33 columns]
0.5220588235294118
acc is : 0.5220588235294118
2023-04-01 00:00:35,981:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.592664  0.407336       1  ...  0.947813   1.0    0.0  1.006795
540     0  0.586866  0.413134       1  ...  0.949040   1.0    0.0  1.008098
541     0  0.573761  0.426239       1  ...  0.952933   1.0    0.0  1.012234
542     0  0.592947  0.407053       0  ...  0.948418   1.0    0.0  1.007437
543     0  0.523346  0.476654       1  ...  0.952111   1.0    0.0  1.011360

[5 rows x 10 columns]
2023-04-01 00:00:36,005:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.594945  0.405055       1  ...  0.959121   1.0    0.0  1.030243
46     0  0.588243  0.411757       1  ...  0.960362   1.0    0.0  1.028225
47     0  0.575430  0.424570       1  ...  0.964302   1.0    0.0  1.032444
48     0  0.593989  0.406011       0  ...  0.959733   1.0    0.0  1.019438
49     0  0.523346  0.476654       1  ...  0.952111   1.0    0.0  1.011360

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-01 00:00:03,256:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42087F1680278402768I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680278402885398, 'quantity': '26.007', 'price': '28488.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680278402438, 'updatetime': 1680278402885, 'tradetype': 'usdt', 'selfid': 42087, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680278402885, 'clientorderid': '42087F1680278402768I0L59', 'price': '28488.6', 'quantity': '26.007', 'commission': '740.9030202', 'commissionasset': 'USDT', 'tradetime': 1680278402885, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680278402885}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18200 

self.closeSec=1680278999, self.tradeDate='20230401', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28488.6', self.close='28450.8'
127.0.0.1 - - [01/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-01 00:10:01,594:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680278999, self.tradeDate='20230401', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28488.6', self.close='28450.8'
2023-04-01 00:10:01,611:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230331   232000    232959  1680276599    28359    28378  0.000970
573  20230331   233000    233959  1680277199  28378.1  28368.5 -0.000335
574  20230331   234000    234959  1680277799  28368.5  28434.1  0.002312
575  20230331   235000    235959  1680278399    28434  28488.5  0.001913
576  20230401   000000    000959  1680278999  28488.6  28450.8 -0.001323
2023-04-01 00:10:01,611:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18201 

self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28451.5', self.close='28430.1'
127.0.0.1 - - [01/Apr/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-04-01 00:20:07,798:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28451.5', self.close='28430.1'
2023-04-01 00:20:08,599:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230331   233000    233959  1680277199  28378.1  28368.5 -0.000335
574  20230331   234000    234959  1680277799  28368.5  28434.1  0.002312
575  20230331   235000    235959  1680278399    28434  28488.5  0.001913
576  20230401   000000    000959  1680278999  28488.6  28450.8 -0.001323
577  20230401   001000    001959  1680279599  28451.5  28430.1 -0.000728
2023-04-01 00:20:08,599:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-04-01 00:00:02,105:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-04-01 00:00:02,219:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:4010000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230331, closeTime:235959, close:28488.5, total:1007412.9805239, pct_pre:-0.015194446412127194, thd:0.33143610848910826, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18201 

self.closeSec=1680278999, self.tradeDate='20230401', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28488.6', self.close='28450.8'
2023-04-01 00:10:01,588:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680278999, self.tradeDate='20230401', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28488.6', self.close='28450.8'
127.0.0.1 - - [01/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-04-01 00:10:01,626:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230331   232000    232959  1680276599    28359    28378
17421  20230331   233000    233959  1680277199  28378.1  28368.5
17422  20230331   234000    234959  1680277799  28368.5  28434.1
17423  20230331   235000    235959  1680278399    28434  28488.5
17424  20230401   000000    000959  1680278999  28488.6  28450.8
2023-04-01 00:10:01,627:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18202 

self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28451.5', self.close='28430.1'
127.0.0.1 - - [01/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-01 00:20:10,804:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28451.5', self.close='28430.1'
2023-04-01 00:20:10,943:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230331   233000    233959  1680277199  28378.1  28368.5
17422  20230331   234000    234959  1680277799  28368.5  28434.1
17423  20230331   235000    235959  1680278399    28434  28488.5
17424  20230401   000000    000959  1680278999  28488.6  28450.8
17425  20230401   001000    001959  1680279599  28451.5  28430.1
2023-04-01 00:20:10,944:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [01/Apr/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-04-01 00:00:03,436:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42088F1680278402825I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680278402937740, 'quantity': '46.017', 'price': '28488.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680278402470, 'updatetime': 1680278402937, 'tradetype': 'usdt', 'selfid': 42088, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680278402937, 'clientorderid': '42088F1680278402825I0L2', 'price': '28488.5', 'quantity': '46.017', 'commission': '1310.9553045', 'commissionasset': 'USDT', 'tradetime': 1680278402937, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680278402937}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Apr/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18201 

self.closeSec=1680278999, self.tradeDate='20230401', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28488.6', self.close='28450.8'
2023-04-01 00:10:01,623:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680278999, self.tradeDate='20230401', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28488.6', self.close='28450.8'
2023-04-01 00:10:01,673:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230331   232000    232959  1680276599    28359    28378
12237  20230331   233000    233959  1680277199  28378.1  28368.5
12238  20230331   234000    234959  1680277799  28368.5  28434.1
12239  20230331   235000    235959  1680278399    28434  28488.5
12240  20230401   000000    000959  1680278999  28488.6  28450.8
2023-04-01 00:10:01,679:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18202 

self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28451.5', self.close='28430.1'
127.0.0.1 - - [01/Apr/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-04-01 00:20:10,272:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28451.5', self.close='28430.1'
2023-04-01 00:20:10,589:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230331   233000    233959  1680277199  28378.1  28368.5
12238  20230331   234000    234959  1680277799  28368.5  28434.1
12239  20230331   235000    235959  1680278399    28434  28488.5
12240  20230401   000000    000959  1680278999  28488.6  28450.8
12241  20230401   001000    001959  1680279599  28451.5  28430.1
2023-04-01 00:20:10,589:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31834
self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28447.6, self.close=28430.0, self.high=28474.4, self.low=28400.0, self.vol=1559.18, self.amt=44338424.5945 
127.0.0.1 - - [01/Apr/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-04-01 00:20:07,102:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230331   235500    235959  ...         0.0        0.0       0
5760  20230401   000000    000459  ...         0.0        0.0       0
5761  20230401   000500    000959  ...         0.0        0.0       0
5762  20230401   001000    001459  ...         0.0        0.0       0
5763  20230401   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 00:20:07,115:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680279599, self.tradeDate='20230401', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28447.6, self.close=28430.0, self.high=28474.4, self.low=28400.0, self.vol=1559.18, self.amt=44338424.5945, ukdf['pct'].iloc[-1]=-0.000615 , ukdf['amount'].iloc[-1]=44338424.5945, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Apr/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31835
self.closeSec=1680279899, self.tradeDate='20230401', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28430.0, self.close=28409.0, self.high=28455.1, self.low=28388.5, self.vol=1454.582, self.amt=41340085.9647 
2023-04-01 00:25:01,737:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230401   000000    000459  ...         0.0        0.0       0
5761  20230401   000500    000959  ...         0.0        0.0       0
5762  20230401   001000    001459  ...         0.0        0.0       0
5763  20230401   001500    001959  ...         0.0        0.0       0
5764  20230401   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-01 00:25:01,737:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680279899, self.tradeDate='20230401', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28430.0, self.close=28409.0, self.high=28455.1, self.low=28388.5, self.vol=1454.582, self.amt=41340085.9647, ukdf['pct'].iloc[-1]=-0.000739 , ukdf['amount'].iloc[-1]=41340085.9647, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

722  20230331   080000    115959  ...   82802.246  2.332319e+09  0.004901
723  20230331   120000    155959  ...  101966.835  2.840422e+09 -0.014883
724  20230331   160000    195959  ...   76287.669  2.123632e+09  0.006588
725  20230331   200000    235959  ...  217230.739  6.157321e+09  0.020508

[5 rows x 11 columns]
2023-04-01 00:00:04,966:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230331   040000    075959  1680220799  ...    721  0.604340  0.486068     NaN
722  20230331   080000    115959  1680235199  ...    722  0.607554  0.514258     NaN
723  20230331   120000    155959  1680249599  ...    723  0.615690  0.553546     NaN
724  20230331   160000    195959  1680263999  ...    724  0.616793  0.568794     NaN
725  20230331   200000    235959  1680278399  ...    725  0.648754  0.667380     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-21348.135', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28488.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-21348.135', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28488.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-04-01 00:00:10,708:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1490253.2511317', 'total': '1490253.2511317', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-04-01 00:00:10,894:DEBUG:s_rsrs:main.py:253:openBuy:185271: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-04-01 00:00:10,894:INFO:s_rsrs:main.py:254:openBuy:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 52.153, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42090F1680278410893I0L65'}
2023-04-01 00:00:10,910:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:4010000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230331, closeTime:235959, close:28488.5, sign:1, total:1490253.2511317, side:buy  
127.0.0.1 - - [01/Apr/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-04-01 00:00:10,915:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42089F1680278405618I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680278405773731, 'quantity': '53.706', 'price': '28490.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680278405240, 'updatetime': 1680278405773, 'tradetype': 'usdt', 'selfid': 42089, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680278405773, 'clientorderid': '42089F1680278405618I0L65', 'price': '28490.2', 'quantity': '53.706', 'commission': '1530.0946812', 'commissionasset': 'USDT', 'tradetime': 1680278405773, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680278405773}], 'gatetype': 'simulator', 'handletime': 0}
2023-04-01 00:00:10,915:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42089F1680278405618I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680278405773731, 'quantity': '53.706', 'price': '28490.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680278405240, 'updatetime': 1680278405773, 'tradetype': 'usdt', 'selfid': 42089, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680278405773, 'clientorderid': '42089F1680278405618I0L65', 'price': '28490.2', 'quantity': '53.706', 'commission': '1530.0946812', 'commissionasset': 'USDT', 'tradetime': 1680278405773, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680278405773}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Apr/2023 00:00:10] "POST / HTTP/1.1" 200 -
2023-04-01 00:00:11,016:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42090F1680278410893I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680278410987056, 'quantity': '52.153', 'price': '28496', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680278410718, 'updatetime': 1680278410987, 'tradetype': 'usdt', 'selfid': 42090, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680278410987, 'clientorderid': '42090F1680278410893I0L65', 'price': '28496', 'quantity': '52.153', 'commission': '1486.151888', 'commissionasset': 'USDT', 'tradetime': 1680278410987, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680278410987}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Apr/2023 00:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [01/Apr/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-04-01 00:00:11,266:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42090F1680278410893I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680278410987056, 'quantity': '52.153', 'price': '28496', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1680278410718, 'updatetime': 1680278410987, 'tradetype': 'usdt', 'selfid': 42090, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680278410987, 'clientorderid': '42090F1680278410893I0L65', 'price': '28496', 'quantity': '52.153', 'commission': '1486.151888', 'commissionasset': 'USDT', 'tradetime': 1680278410987, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680278410987}], 'gatetype': 'simulator', 'handletime': 0}


