# 20230516 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [16/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=448
self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27421.4, self.close=27454.3, self.high=27500.0, self.low=27420.6, self.vol=4479.02, self.amt=123004336.6919 
2023-05-16 00:20:00,520:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230515   235500    235959  ...    0.506677   0.223962       0
5760  20230516   000000    000459  ...    0.506523   0.224120       0
5761  20230516   000500    000959  ...    0.506368   0.224277       0
5762  20230516   001000    001459  ...    0.506210   0.224433       0
5763  20230516   001500    001959  ...    0.506049   0.224589       0

[5 rows x 18 columns]
2023-05-16 00:20:00,523:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27421.4, self.close=27454.3, self.high=27500.0, self.low=27420.6, self.vol=4479.02, self.amt=123004336.6919, ukdf['pct'].iloc[-1]=0.0012 , ukdf['amount'].iloc[-1]=123004336.6919, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.506049244378299, signal=0, value_std=0.22458866479205156 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-8209.377', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27454.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=449
self.closeSec=1684167899, self.tradeDate='20230516', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27454.4, self.close=27426.7, self.high=27454.4, self.low=27422.0, self.vol=1088.023, self.amt=29847452.4228 
2023-05-16 00:25:00,385:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230516   000000    000459  ...    0.506523   0.224120       0
5761  20230516   000500    000959  ...    0.506368   0.224277       0
5762  20230516   001000    001459  ...    0.506210   0.224433       0
5763  20230516   001500    001959  ...    0.506049   0.224589       0
5764  20230516   002000    002459  ...    0.505887   0.224743       0

[5 rows x 18 columns]
2023-05-16 00:25:00,386:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684167899, self.tradeDate='20230516', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27454.4, self.close=27426.7, self.high=27454.4, self.low=27422.0, self.vol=1088.023, self.amt=29847452.4228, ukdf['pct'].iloc[-1]=-0.001005 , ukdf['amount'].iloc[-1]=29847452.4228, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.5058874458689202, signal=0, value_std=0.22474330840683615 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7852.1878527345', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27428.75091575', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27421.4, self.close=27454.3, self.high=27500.0, self.low=27420.6 
127.0.0.1 - - [16/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 00:20:00,414:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27421.4, self.close=27454.3, self.high=27500.0, self.low=27420.6   
2023-05-16 00:20:00,491:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1438  20230515   235500    235959  1684166399  ...  27358.0  0.000629   1726    4
1439  20230516   000000    000459  1684166699  ...  27357.2  0.000493   1439    5
1440  20230516   000500    000959  1684166999  ...  27390.5  0.000281   1440    0
1441  20230516   001000    001459  1684167299  ...  27400.5  0.000628   1441    1
1442  20230516   001500    001959  1684167599  ...  27420.6  0.001200   1442    2

[5 rows x 11 columns]
2023-05-16 00:20:00,492:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=74, self.factor=0.31765182008711884, self.count=451 

self.closeSec=1684167899, self.tradeDate='20230516', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27454.4, self.close=27426.7, self.high=27454.4, self.low=27422.0 
2023-05-16 00:25:00,333:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684167899, self.tradeDate='20230516', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27454.4, self.close=27426.7, self.high=27454.4, self.low=27422.0   
127.0.0.1 - - [16/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-16 00:25:00,359:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230516   000000    000459  1684166699  ...  27357.2  0.000493   1439    5
1440  20230516   000500    000959  1684166999  ...  27390.5  0.000281   1440    0
1441  20230516   001000    001459  1684167299  ...  27400.5  0.000628   1441    1
1442  20230516   001500    001959  1684167599  ...  27420.6  0.001200   1442    2
1443  20230516   002000    002459  1684167899  ...  27422.0 -0.001005   1443    3

[5 rows x 11 columns]
2023-05-16 00:25:00,359:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-16 00:00:18,974:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230515    212959  27380.7  ...  50.000000  0.577845  0.249535
5803  20230515    215959  27361.7  ...  49.583333  0.577818  0.247580
5804  20230515    222959  27361.6  ...  49.166667  0.557711  0.251512
5805  20230515    225959  27287.8  ...  49.583333  0.578587  0.247149
5806  20230515    232959  27390.7  ...  49.583333  0.585099  0.240459

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-05-16 00:00:19,089:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.482865  0.517135       1  ...  1.042526   1.0    0.0  0.941925
540     1  0.486072  0.513928       0  ...  1.039710   1.0    0.0  0.939381
541     1  0.473919  0.526081       1  ...  1.043639   1.0    0.0  0.942930
542     0  0.510810  0.489190       1  ...  1.044919   1.0    0.0  0.944087
543     1  0.497489  0.502511       0  ...  1.043341   1.0    0.0  0.942662

[5 rows x 10 columns]
2023-05-16 00:00:19,115:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.482530  0.517470       1  ...  1.042526   1.0    0.0  0.939935
46     1  0.485501  0.514499       0  ...  1.039710   1.0    0.0  0.936136
47     1  0.473369  0.526631       1  ...  1.043639   1.0    0.0  0.939673
48     0  0.510584  0.489416       1  ...  1.044919   1.0    0.0  0.942892
49     1  0.497489  0.502511       0  ...  1.043341   1.0    0.0  0.942662

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.199', 'enterprice': '26801.5', 'countrevence': '0', 'unrealprofit': '16620.4906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27390.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/May/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-05-16 00:00:02,727:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42168F1684166402133I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684166402542592, 'quantity': '26.124', 'price': '27385.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684166400980, 'updatetime': 1684166402542, 'tradetype': 'usdt', 'selfid': 42168, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684166402542, 'clientorderid': '42168F1684166402133I0L59', 'price': '27385.6', 'quantity': '26.124', 'commission': '715.4214144', 'commissionasset': 'USDT', 'tradetime': 1684166402542, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684166402542}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=224 

self.closeSec=1684166999, self.tradeDate='20230516', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27383', self.close='27404.2'
2023-05-16 00:10:00,348:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684166999, self.tradeDate='20230516', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27383', self.close='27404.2'
127.0.0.1 - - [16/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-16 00:10:00,388:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230515   232000    232959  1684164599    27407  27424.4  0.000631
573  20230515   233000    233959  1684165199  27424.3  27384.4 -0.001459
574  20230515   234000    234959  1684165799  27384.4  27408.5  0.000880
575  20230515   235000    235959  1684166399  27408.5    27383 -0.000930
576  20230516   000000    000959  1684166999    27383  27404.2  0.000774
2023-05-16 00:10:00,388:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=225 

self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27404.2', self.close='27454.3'
127.0.0.1 - - [16/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 00:20:00,927:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27404.2', self.close='27454.3'
2023-05-16 00:20:00,979:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230515   233000    233959  1684165199  27424.3  27384.4 -0.001459
574  20230515   234000    234959  1684165799  27384.4  27408.5  0.000880
575  20230515   235000    235959  1684166399  27408.5    27383 -0.000930
576  20230516   000000    000959  1684166999    27383  27404.2  0.000774
577  20230516   001000    001959  1684167599  27404.2  27454.3  0.001828
2023-05-16 00:20:00,979:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-16 00:00:00,497:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-16 00:00:00,647:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5160000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230515, closeTime:235959, close:27383, total:986122.7200962, pct_pre:0.00987078711781142, thd:-0.39157223138828584, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=227 

self.closeSec=1684166999, self.tradeDate='20230516', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27383', self.close='27404.2'
2023-05-16 00:10:00,365:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684166999, self.tradeDate='20230516', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27383', self.close='27404.2'
127.0.0.1 - - [16/May/2023 00:10:00] "POST / HTTP/1.1" 200 -
2023-05-16 00:10:00,413:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230515   232000    232959  1684164599    27407  27424.4
17421  20230515   233000    233959  1684165199  27424.3  27384.4
17422  20230515   234000    234959  1684165799  27384.4  27408.5
17423  20230515   235000    235959  1684166399  27408.5    27383
17424  20230516   000000    000959  1684166999    27383  27404.2
2023-05-16 00:10:00,418:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=228 

self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27404.2', self.close='27454.3'
127.0.0.1 - - [16/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 00:20:00,907:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27404.2', self.close='27454.3'
2023-05-16 00:20:00,954:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230515   233000    233959  1684165199  27424.3  27384.4
17422  20230515   234000    234959  1684165799  27384.4  27408.5
17423  20230515   235000    235959  1684166399  27408.5    27383
17424  20230516   000000    000959  1684166999    27383  27404.2
17425  20230516   001000    001959  1684167599  27404.2  27454.3
2023-05-16 00:20:00,955:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/May/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-05-16 00:00:03,378:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42169F1684166402546I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684166403115719, 'quantity': '45.891', 'price': '27385.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684166401298, 'updatetime': 1684166403115, 'tradetype': 'usdt', 'selfid': 42169, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684166403115, 'clientorderid': '42169F1684166402546I0L2', 'price': '27385.5', 'quantity': '45.891', 'commission': '1256.7479805', 'commissionasset': 'USDT', 'tradetime': 1684166403115, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684166403115}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/May/2023 00:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=227 

self.closeSec=1684166999, self.tradeDate='20230516', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27383', self.close='27404.2'
2023-05-16 00:10:00,332:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684166999, self.tradeDate='20230516', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27383', self.close='27404.2'
2023-05-16 00:10:00,345:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230515   232000    232959  1684164599    27407  27424.4
12237  20230515   233000    233959  1684165199  27424.3  27384.4
12238  20230515   234000    234959  1684165799  27384.4  27408.5
12239  20230515   235000    235959  1684166399  27408.5    27383
12240  20230516   000000    000959  1684166999    27383  27404.2
2023-05-16 00:10:00,345:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=228 

self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27404.2', self.close='27454.3'
127.0.0.1 - - [16/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-05-16 00:20:00,808:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27404.2', self.close='27454.3'
2023-05-16 00:20:00,876:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230515   233000    233959  1684165199  27424.3  27384.4
12238  20230515   234000    234959  1684165799  27384.4  27408.5
12239  20230515   235000    235959  1684166399  27408.5    27383
12240  20230516   000000    000959  1684166999    27383  27404.2
12241  20230516   001000    001959  1684167599  27404.2  27454.3
2023-05-16 00:20:00,876:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [16/May/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=448
self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27421.4, self.close=27454.3, self.high=27500.0, self.low=27420.6, self.vol=4479.02, self.amt=123004336.6919 
2023-05-16 00:20:00,520:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230515   235500    235959  ...    0.444566   0.223985       0
5760  20230516   000000    000459  ...    0.444319   0.224213       0
5761  20230516   000500    000959  ...    0.444070   0.224441       0
5762  20230516   001000    001459  ...    0.443818   0.224668       0
5763  20230516   001500    001959  ...    0.443565   0.224894       0

[5 rows x 18 columns]
2023-05-16 00:20:00,522:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684167599, self.tradeDate='20230516', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27421.4, self.close=27454.3, self.high=27500.0, self.low=27420.6, self.vol=4479.02, self.amt=123004336.6919, ukdf['pct'].iloc[-1]=0.0012 , ukdf['amount'].iloc[-1]=123004336.6919, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.44356516459675416, signal=0, value_std=0.22489381923172777 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '22670.8664', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27454.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=449
self.closeSec=1684167899, self.tradeDate='20230516', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27454.4, self.close=27426.7, self.high=27454.4, self.low=27422.0, self.vol=1088.023, self.amt=29847452.4228 
2023-05-16 00:25:00,369:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230516   000000    000459  ...    0.444319   0.224213       0
5761  20230516   000500    000959  ...    0.444070   0.224441       0
5762  20230516   001000    001459  ...    0.443818   0.224668       0
5763  20230516   001500    001959  ...    0.443565   0.224894       0
5764  20230516   002000    002459  ...    0.443312   0.225119       0

[5 rows x 18 columns]
2023-05-16 00:25:00,369:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684167899, self.tradeDate='20230516', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27454.4, self.close=27426.7, self.high=27454.4, self.low=27422.0, self.vol=1088.023, self.amt=29847452.4228, ukdf['pct'].iloc[-1]=-0.001005 , ukdf['amount'].iloc[-1]=29847452.4228, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.4433121718617789, signal=0, value_std=0.22511933108817367 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '21718.23376187075', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27428.75091575', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230515   120000    155959  1684137599  ...    723  0.395800 -0.299161     NaN
724  20230515   160000    195959  1684151999  ...    724  0.390643 -0.353810     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-26532.616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27324.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [16/May/2023 00:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=6897.9369698, self.flagDict['side']='', self.tradeCount=0, self.count=9
self.closeSec=1684166399, self.tradeDate='20230515', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=27323.2, self.close=27383.0, self.high=27525.0, self.low=27200.0, self.vol=79836.823, self.amt=2184423699.4391 
2023-05-16 00:00:00,400:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684166399, self.tradeDate='20230515', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=27323.2, self.close=27383.0, self.high=27525.0, self.low=27200.0, self.vol=79836.823, self.amt=2184423699.4391 
2023-05-16 00:00:00,529:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230515   040000    075959  ...   21451.127  5.768678e+08  0.001374
722  20230515   080000    115959  ...  100134.610  2.707659e+09  0.011687
723  20230515   120000    155959  ...   93928.690  2.569898e+09  0.006698
724  20230515   160000    195959  ...   39961.711  1.094175e+09 -0.002752
725  20230515   200000    235959  ...   79836.823  2.184424e+09  0.002189

[5 rows x 11 columns]
2023-05-16 00:00:02,007:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230515   040000    075959  1684108799  ...    721  0.488492  0.175305     NaN
722  20230515   080000    115959  1684123199  ...    722  0.397467 -0.263858     NaN
723  20230515   120000    155959  1684137599  ...    723  0.395800 -0.299161     NaN
724  20230515   160000    195959  1684151999  ...    724  0.390643 -0.353810     NaN
725  20230515   200000    235959  1684166399  ...    725  0.403817 -0.320462     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-29720.7248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27385.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


