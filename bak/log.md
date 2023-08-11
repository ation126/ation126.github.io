# 20230812 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25792
self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29405.3, self.close=29392.6, self.high=29420.0, self.low=29384.8, self.vol=1416.547, self.amt=41655990.8073 
127.0.0.1 - - [12/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 00:20:06,326:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230811   235500    235959  ...         0.0        0.0       0
5760  20230812   000000    000459  ...         0.0        0.0       0
5761  20230812   000500    000959  ...         0.0        0.0       0
5762  20230812   001000    001459  ...         0.0        0.0       0
5763  20230812   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 00:20:06,356:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29405.3, self.close=29392.6, self.high=29420.0, self.low=29384.8, self.vol=1416.547, self.amt=41655990.8073, ukdf['pct'].iloc[-1]=-0.000435 , ukdf['amount'].iloc[-1]=41655990.8073, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35206.3206', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29393', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25793
self.closeSec=1691771099, self.tradeDate='20230812', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29392.6, self.close=29384.2, self.high=29404.5, self.low=29384.2, self.vol=393.503, self.amt=11567370.2074 
2023-08-12 00:25:00,786:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230812   000000    000459  ...         0.0        0.0       0
5761  20230812   000500    000959  ...         0.0        0.0       0
5762  20230812   001000    001459  ...         0.0        0.0       0
5763  20230812   001500    001959  ...         0.0        0.0       0
5764  20230812   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 00:25:00,787:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691771099, self.tradeDate='20230812', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29392.6, self.close=29384.2, self.high=29404.5, self.low=29384.2, self.vol=393.503, self.amt=11567370.2074, ukdf['pct'].iloc[-1]=-0.000286 , ukdf['amount'].iloc[-1]=11567370.2074, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35113.63194967122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29386.34420147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29405.3, self.close=29392.6, self.high=29420.0, self.low=29384.8 
127.0.0.1 - - [12/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 00:20:04,384:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29405.3, self.close=29392.6, self.high=29420.0, self.low=29384.8   
2023-08-12 00:20:05,605:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230811   235500    235959  1691769599  ...  29347.0  0.001128   1727    5
1440  20230812   000000    000459  1691769899  ...  29373.4  0.000330   1440    0
1441  20230812   000500    000959  1691770199  ...  29383.5 -0.000031   1441    1
1442  20230812   001000    001459  1691770499  ...  29389.0  0.000463   1442    2
1443  20230812   001500    001959  1691770799  ...  29384.8 -0.000435   1443    3

[5 rows x 11 columns]
2023-08-12 00:20:05,615:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6465440992295391, self.count=25795 

self.closeSec=1691771099, self.tradeDate='20230812', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29392.6, self.close=29384.2, self.high=29404.5, self.low=29384.2 
2023-08-12 00:25:00,768:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691771099, self.tradeDate='20230812', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29392.6, self.close=29384.2, self.high=29404.5, self.low=29384.2   
2023-08-12 00:25:00,799:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230812   000000    000459  1691769899  ...  29373.4  0.000330   1440    0
1441  20230812   000500    000959  1691770199  ...  29383.5 -0.000031   1441    1
1442  20230812   001000    001459  1691770499  ...  29389.0  0.000463   1442    2
1443  20230812   001500    001959  1691770799  ...  29384.8 -0.000435   1443    3
1444  20230812   002000    002459  1691771099  ...  29384.2 -0.000286   1444    4

[5 rows x 11 columns]
2023-08-12 00:25:00,799:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-12 00:00:17,097:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230811    212959  29417.0  ...  46.666667  0.481548  0.617377
5803  20230811    215959  29425.6  ...  47.083333  0.494410  0.588943
5804  20230811    222959  29459.8  ...  47.083333  0.508879  0.568567
5805  20230811    225959  29499.6  ...  46.666667  0.502028  0.554913
5806  20230811    232959  29481.0  ...  46.666667  0.469338  0.569361

[5 rows x 33 columns]
0.5183823529411765
acc is : 0.5183823529411765
2023-08-12 00:00:17,154:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.508171  0.491829       1  ...  0.979934  -1.0    0.0  1.003269
540     0  0.518061  0.481939       1  ...  0.978610  -1.0    0.0  1.004625
541     0  0.520361  0.479639       0  ...  0.979227  -1.0    0.0  1.003991
542     0  0.504396  0.495604       0  ...  0.982360  -1.0    0.0  1.000780
543     1  0.479236  0.520764       0  ...  0.982483  -1.0    0.0  1.000654

[5 rows x 10 columns]
2023-08-12 00:00:17,165:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508042  0.491958       1  ...  0.979934  -1.0    0.0  1.001540
46     0  0.518099  0.481901       1  ...  0.978610  -1.0    0.0  1.003384
47     0  0.520396  0.479604       0  ...  0.979227  -1.0    0.0  1.002752
48     0  0.504253  0.495747       0  ...  0.982360  -1.0    0.0  0.999650
49     1  0.479236  0.520764       0  ...  0.982483  -1.0    0.0  1.000654

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '2382.30570020149', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29380.63951099', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-12 00:00:04,210:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42846F1691769603596I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691769603996839, 'quantity': '24.584', 'price': '29383', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691769602699, 'updatetime': 1691769603996, 'tradetype': 'usdt', 'selfid': 42846, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691769603996, 'clientorderid': '42846F1691769603596I0L59', 'price': '29383', 'quantity': '24.584', 'commission': '722.351672', 'commissionasset': 'USDT', 'tradetime': 1691769603996, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691769603996}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--: 127.0.0.1 - - [12/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12896 

self.closeSec=1691770199, self.tradeDate='20230812', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29382.9', self.close='29391.8'
2023-08-12 00:10:01,187:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691770199, self.tradeDate='20230812', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29382.9', self.close='29391.8'
2023-08-12 00:10:01,195:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230811   232000    232959  1691767799  29361.6  29386.6  0.000855
573  20230811   233000    233959  1691768399  29386.7  29375.1 -0.000391
574  20230811   234000    234959  1691768999    29375  29357.3 -0.000606
575  20230811   235000    235959  1691769599  29357.3    29383  0.000875
576  20230812   000000    000959  1691770199  29382.9  29391.8  0.000299
2023-08-12 00:10:01,196:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12897 

self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29391.8', self.close='29392.6'
127.0.0.1 - - [12/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 00:20:06,946:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29391.8', self.close='29392.6'
2023-08-12 00:20:07,484:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230811   233000    233959  1691768399  29386.7  29375.1 -0.000391
574  20230811   234000    234959  1691768999    29375  29357.3 -0.000606
575  20230811   235000    235959  1691769599  29357.3    29383  0.000875
576  20230812   000000    000959  1691770199  29382.9  29391.8  0.000299
577  20230812   001000    001959  1691770799  29391.8  29392.6  0.000027
2023-08-12 00:20:07,485:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-12 00:00:02,124:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-12 00:00:02,179:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8120000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230811, closeTime:235959, close:29383, total:977345.2184116, pct_pre:-0.001855142584356373, thd:0.32541673260852444, side:sell 
127.0.0.1 - - [12/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12899 

self.closeSec=1691770199, self.tradeDate='20230812', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29382.9', self.close='29391.8'
2023-08-12 00:10:01,178:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691770199, self.tradeDate='20230812', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29382.9', self.close='29391.8'
2023-08-12 00:10:01,185:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230811   232000    232959  1691767799  29361.6  29386.6
17421  20230811   233000    233959  1691768399  29386.7  29375.1
17422  20230811   234000    234959  1691768999    29375  29357.3
17423  20230811   235000    235959  1691769599  29357.3    29383
17424  20230812   000000    000959  1691770199  29382.9  29391.8
2023-08-12 00:10:01,185:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12900 

self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29391.8', self.close='29392.6'
127.0.0.1 - - [12/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 00:20:08,720:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29391.8', self.close='29392.6'
2023-08-12 00:20:08,843:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230811   233000    233959  1691768399  29386.7  29375.1
17422  20230811   234000    234959  1691768999    29375  29357.3
17423  20230811   235000    235959  1691769599  29357.3    29383
17424  20230812   000000    000959  1691770199  29382.9  29391.8
17425  20230812   001000    001959  1691770799  29391.8  29392.6
2023-08-12 00:20:08,844:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [12/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-12 00:00:04,071:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42845F1691769603485I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691769603896107, 'quantity': '36.561', 'price': '29383', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691769602635, 'updatetime': 1691769603896, 'tradetype': 'usdt', 'selfid': 42845, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691769603896, 'clientorderid': '42845F1691769603485I0L2', 'price': '29383', 'quantity': '36.561', 'commission': '1074.271863', 'commissionasset': 'USDT', 'tradetime': 1691769603896, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691769603896}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12899 

self.closeSec=1691770199, self.tradeDate='20230812', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29382.9', self.close='29391.8'
2023-08-12 00:10:01,170:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691770199, self.tradeDate='20230812', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29382.9', self.close='29391.8'
2023-08-12 00:10:01,177:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230811   232000    232959  1691767799  29361.6  29386.6
12237  20230811   233000    233959  1691768399  29386.7  29375.1
12238  20230811   234000    234959  1691768999    29375  29357.3
12239  20230811   235000    235959  1691769599  29357.3    29383
12240  20230812   000000    000959  1691770199  29382.9  29391.8
2023-08-12 00:10:01,177:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12900 

self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29391.8', self.close='29392.6'
127.0.0.1 - - [12/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 00:20:08,538:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29391.8', self.close='29392.6'
2023-08-12 00:20:08,707:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230811   233000    233959  1691768399  29386.7  29375.1
12238  20230811   234000    234959  1691768999    29375  29357.3
12239  20230811   235000    235959  1691769599  29357.3    29383
12240  20230812   000000    000959  1691770199  29382.9  29391.8
12241  20230812   001000    001959  1691770799  29391.8  29392.6
2023-08-12 00:20:08,708:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25792
self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29405.3, self.close=29392.6, self.high=29420.0, self.low=29384.8, self.vol=1416.547, self.amt=41655990.8073 
127.0.0.1 - - [12/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 00:20:06,454:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230811   235500    235959  ...         0.0        0.0       0
5760  20230812   000000    000459  ...         0.0        0.0       0
5761  20230812   000500    000959  ...         0.0        0.0       0
5762  20230812   001000    001459  ...         0.0        0.0       0
5763  20230812   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 00:20:06,485:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691770799, self.tradeDate='20230812', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29405.3, self.close=29392.6, self.high=29420.0, self.low=29384.8, self.vol=1416.547, self.amt=41655990.8073, ukdf['pct'].iloc[-1]=-0.000435 , ukdf['amount'].iloc[-1]=41655990.8073, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94672.409', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29393', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25793
self.closeSec=1691771099, self.tradeDate='20230812', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29392.6, self.close=29384.2, self.high=29404.5, self.low=29384.2, self.vol=393.503, self.amt=11567370.2074 
127.0.0.1 - - [12/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-12 00:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230812   000000    000459  ...         0.0        0.0       0
5761  20230812   000500    000959  ...         0.0        0.0       0
5762  20230812   001000    001459  ...         0.0        0.0       0
5763  20230812   001500    001959  ...         0.0        0.0       0
5764  20230812   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 00:25:00,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691771099, self.tradeDate='20230812', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29392.6, self.close=29384.2, self.high=29404.5, self.low=29384.2, self.vol=393.503, self.amt=11567370.2074, ukdf['pct'].iloc[-1]=-0.000286 , ukdf['amount'].iloc[-1]=11567370.2074, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '94425.20598679727', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29386.34420147', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230811   120000    155959  1691740799  ...    723  0.760064  1.001768     1.0
724  20230811   160000    195959  1691755199  ...    724  0.716036  0.872106     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-23124.7758', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29435', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [12/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=537
self.closeSec=1691769599, self.tradeDate='20230811', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29435.0, self.close=29383.0, self.high=29565.1, self.low=29339.9, self.vol=67828.797, self.amt=1997329748.00054 
2023-08-12 00:00:01,666:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691769599, self.tradeDate='20230811', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29435.0, self.close=29383.0, self.high=29565.1, self.low=29339.9, self.vol=67828.797, self.amt=1997329748.00054 
2023-08-12 00:00:01,678:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230811   040000    075959  ...  13216.051  3.892165e+08  0.000279
722  20230811   080000    115959  ...  19307.071  5.679160e+08 -0.001460
723  20230811   120000    155959  ...  18382.821  5.409012e+08  0.000204
724  20230811   160000    195959  ...  21936.641  6.448357e+08  0.000962
725  20230811   200000    235959  ...  67828.797  1.997330e+09 -0.001767

[5 rows x 11 columns]
2023-08-12 00:00:02,496:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230811   040000    075959  1691711999  ...    721  0.823996  1.202551     1.0
722  20230811   080000    115959  1691726399  ...    722  0.791911  1.100409     1.0
723  20230811   120000    155959  1691740799  ...    723  0.760064  1.001768     1.0
724  20230811   160000    195959  1691755199  ...    724  0.716036  0.872106     1.0
725  20230811   200000    235959  1691769599  ...    725  0.661498  0.717812     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-25652.99693652829', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29385.86730403', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


