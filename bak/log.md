# 20230702 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13984
self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30542.4, self.close=30540.4, self.high=30567.7, self.low=30534.1, self.vol=616.989, self.amt=18846455.6299 
127.0.0.1 - - [02/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 00:20:07,502:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230701   235500    235959  ...         0.0        0.0       0
5760  20230702   000000    000459  ...         0.0        0.0       0
5761  20230702   000500    000959  ...         0.0        0.0       0
5762  20230702   001000    001459  ...         0.0        0.0       0
5763  20230702   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 00:20:07,533:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30542.4, self.close=30540.4, self.high=30567.7, self.low=30534.1, self.vol=616.989, self.amt=18846455.6299, ukdf['pct'].iloc[-1]=-7.5e-05 , ukdf['amount'].iloc[-1]=18846455.6299, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51185.013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30540.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [02/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13985
self.closeSec=1688228699, self.tradeDate='20230702', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30540.3, self.close=30537.7, self.high=30555.7, self.low=30533.8, self.vol=534.094, self.amt=16313077.7847 
2023-07-02 00:25:00,785:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230702   000000    000459  ...         0.0        0.0       0
5761  20230702   000500    000959  ...         0.0        0.0       0
5762  20230702   001000    001459  ...         0.0        0.0       0
5763  20230702   001500    001959  ...         0.0        0.0       0
5764  20230702   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 00:25:00,785:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688228699, self.tradeDate='20230702', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30540.3, self.close=30537.7, self.high=30555.7, self.low=30533.8, self.vol=534.094, self.amt=16313077.7847, ukdf['pct'].iloc[-1]=-8.8e-05 , ukdf['amount'].iloc[-1]=16313077.7847, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51196.50454399602', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30541.22518627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30542.4, self.close=30540.4, self.high=30567.7, self.low=30534.1 
127.0.0.1 - - [02/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 00:20:04,884:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30542.4, self.close=30540.4, self.high=30567.7, self.low=30534.1   
2023-07-02 00:20:06,472:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230701   235500    235959  1688227199  ...  30558.8  0.000088   1727    5
1440  20230702   000000    000459  1688227499  ...  30559.4  0.000252   1440    0
1441  20230702   000500    000959  1688227799  ...  30568.7  0.000415   1441    1
1442  20230702   001000    001459  1688228099  ...  30542.7 -0.001282   1442    2
1443  20230702   001500    001959  1688228399  ...  30534.1 -0.000075   1443    3

[5 rows x 11 columns]
2023-07-02 00:20:06,482:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [02/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=62, self.factor=0.4272708596044005, self.count=13987 

self.closeSec=1688228699, self.tradeDate='20230702', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30540.3, self.close=30537.7, self.high=30555.7, self.low=30533.8 
2023-07-02 00:25:00,710:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688228699, self.tradeDate='20230702', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30540.3, self.close=30537.7, self.high=30555.7, self.low=30533.8   
2023-07-02 00:25:00,766:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230702   000000    000459  1688227499  ...  30559.4  0.000252   1440    0
1441  20230702   000500    000959  1688227799  ...  30568.7  0.000415   1441    1
1442  20230702   001000    001459  1688228099  ...  30542.7 -0.001282   1442    2
1443  20230702   001500    001959  1688228399  ...  30534.1 -0.000075   1443    3
1444  20230702   002000    002459  1688228699  ...  30533.8 -0.000088   1444    4

[5 rows x 11 columns]
2023-07-02 00:25:00,767:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-02 00:00:19,461:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230701    212959  30552.0  ...  52.916667  0.511210  0.392662
5803  20230701    215959  30530.1  ...  52.916667  0.514790  0.382353
5804  20230701    222959  30549.9  ...  53.333333  0.516038  0.371455
5805  20230701    225959  30557.0  ...  53.750000  0.523629  0.354311
5806  20230701    232959  30598.8  ...  53.750000  0.517149  0.349781

[5 rows x 33 columns]
0.5091911764705882
acc is : 0.5091911764705882
2023-07-02 00:00:19,573:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.524198  0.475802       1  ...  1.081487   1.0    0.0  1.139058
540     0  0.528167  0.471833       1  ...  1.081731   1.0    0.0  1.139316
541     0  0.524320  0.475680       1  ...  1.083214   1.0    0.0  1.140878
542     0  0.526475  0.473525       0  ...  1.082053   1.0    0.0  1.139655
543     0  0.516631  0.483369       0  ...  1.081894   1.0    0.0  1.139487

[5 rows x 10 columns]
2023-07-02 00:00:19,598:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524328  0.475672       1  ...  1.081487   1.0    0.0  1.139900
46     0  0.528229  0.471771       1  ...  1.081731   1.0    0.0  1.141384
47     0  0.524390  0.475610       1  ...  1.083214   1.0    0.0  1.142949
48     0  0.526591  0.473409       0  ...  1.082053   1.0    0.0  1.140229
49     0  0.516631  0.483369       0  ...  1.081894   1.0    0.0  1.139487

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.53', 'enterprice': '30560', 'countrevence': '0', 'unrealprofit': '114.885', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30564.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [02/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-02 00:00:04,635:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42513F1688227203688I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688227204109915, 'quantity': '25.675', 'price': '30561.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688227202642, 'updatetime': 1688227204109, 'tradetype': 'usdt', 'selfid': 42513, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688227204109, 'clientorderid': '42513F1688227203688I0L59', 'price': '30561.5', 'quantity': '25.675', 'commission': '784.6665125', 'commissionasset': 'USDT', 'tradetime': 1688227204109, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688227204109}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6992 

self.closeSec=1688227799, self.tradeDate='20230702', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30561.5', self.close='30581.9'
2023-07-02 00:10:01,161:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688227799, self.tradeDate='20230702', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30561.5', self.close='30581.9'
2023-07-02 00:10:01,171:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230701   232000    232959  1688225399    30550    30566  0.000524
573  20230701   233000    233959  1688225999  30566.1    30589  0.000752
574  20230701   234000    234959  1688226599    30589  30577.5 -0.000376
575  20230701   235000    235959  1688227199  30577.5  30561.5 -0.000523
576  20230702   000000    000959  1688227799  30561.5  30581.9  0.000668
2023-07-02 00:10:01,171:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6993 

self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30582', self.close='30540.4'
127.0.0.1 - - [02/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 00:20:07,281:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30582', self.close='30540.4'
2023-07-02 00:20:08,002:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230701   233000    233959  1688225999  30566.1    30589  0.000752
574  20230701   234000    234959  1688226599    30589  30577.5 -0.000376
575  20230701   235000    235959  1688227199  30577.5  30561.5 -0.000523
576  20230702   000000    000959  1688227799  30561.5  30581.9  0.000668
577  20230702   001000    001959  1688228399    30582  30540.4 -0.001357
2023-07-02 00:20:08,011:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [02/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-02 00:00:04,249:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42511F1688227203634I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688227204014553, 'quantity': '32.579', 'price': '30561.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688227202590, 'updatetime': 1688227204014, 'tradetype': 'usdt', 'selfid': 42511, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688227204014, 'clientorderid': '42511F1688227203634I0L57', 'price': '30561.4', 'quantity': '32.579', 'commission': '995.6598506', 'commissionasset': 'USDT', 'tradetime': 1688227204014, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688227204014}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6995 

self.closeSec=1688227799, self.tradeDate='20230702', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30561.5', self.close='30581.9'
2023-07-02 00:10:01,133:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688227799, self.tradeDate='20230702', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30561.5', self.close='30581.9'
2023-07-02 00:10:01,140:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230701   232000    232959  1688225399    30550    30566
17421  20230701   233000    233959  1688225999  30566.1    30589
17422  20230701   234000    234959  1688226599    30589  30577.5
17423  20230701   235000    235959  1688227199  30577.5  30561.5
17424  20230702   000000    000959  1688227799  30561.5  30581.9
2023-07-02 00:10:01,141:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6996 

self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30582', self.close='30540.4'
127.0.0.1 - - [02/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 00:20:09,190:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30582', self.close='30540.4'
2023-07-02 00:20:09,309:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230701   233000    233959  1688225999  30566.1    30589
17422  20230701   234000    234959  1688226599    30589  30577.5
17423  20230701   235000    235959  1688227199  30577.5  30561.5
17424  20230702   000000    000959  1688227799  30561.5  30581.9
17425  20230702   001000    001959  1688228399    30582  30540.4
2023-07-02 00:20:09,310:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [02/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-02 00:00:04,423:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42512F1688227203655I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688227204089642, 'quantity': '37.468', 'price': '30561.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688227202658, 'updatetime': 1688227204089, 'tradetype': 'usdt', 'selfid': 42512, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688227204089, 'clientorderid': '42512F1688227203655I0L2', 'price': '30561.4', 'quantity': '37.468', 'commission': '1145.0745352', 'commissionasset': 'USDT', 'tradetime': 1688227204089, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688227204089}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6995 

self.closeSec=1688227799, self.tradeDate='20230702', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30561.5', self.close='30581.9'
2023-07-02 00:10:01,138:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688227799, self.tradeDate='20230702', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30561.5', self.close='30581.9'
2023-07-02 00:10:01,155:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230701   232000    232959  1688225399    30550    30566
12237  20230701   233000    233959  1688225999  30566.1    30589
12238  20230701   234000    234959  1688226599    30589  30577.5
12239  20230701   235000    235959  1688227199  30577.5  30561.5
12240  20230702   000000    000959  1688227799  30561.5  30581.9
2023-07-02 00:10:01,155:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6996 

self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30582', self.close='30540.4'
127.0.0.1 - - [02/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-02 00:20:08,764:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30582', self.close='30540.4'
2023-07-02 00:20:09,074:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230701   233000    233959  1688225999  30566.1    30589
12238  20230701   234000    234959  1688226599    30589  30577.5
12239  20230701   235000    235959  1688227199  30577.5  30561.5
12240  20230702   000000    000959  1688227799  30561.5  30581.9
12241  20230702   001000    001959  1688228399    30582  30540.4
2023-07-02 00:20:09,074:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13984
self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30542.4, self.close=30540.4, self.high=30567.7, self.low=30534.1, self.vol=616.989, self.amt=18846455.6299 
127.0.0.1 - - [02/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-02 00:20:07,551:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230701   235500    235959  ...         0.0        0.0       0
5760  20230702   000000    000459  ...         0.0        0.0       0
5761  20230702   000500    000959  ...         0.0        0.0       0
5762  20230702   001000    001459  ...         0.0        0.0       0
5763  20230702   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 00:20:07,582:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688228399, self.tradeDate='20230702', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30542.4, self.close=30540.4, self.high=30567.7, self.low=30534.1, self.vol=616.989, self.amt=18846455.6299, ukdf['pct'].iloc[-1]=-7.5e-05 , ukdf['amount'].iloc[-1]=18846455.6299, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137287.9924', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30540.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13985
self.closeSec=1688228699, self.tradeDate='20230702', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30540.3, self.close=30537.7, self.high=30555.7, self.low=30533.8, self.vol=534.094, self.amt=16313077.7847 
127.0.0.1 - - [02/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-02 00:25:00,787:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230702   000000    000459  ...         0.0        0.0       0
5761  20230702   000500    000959  ...         0.0        0.0       0
5762  20230702   001000    001459  ...         0.0        0.0       0
5763  20230702   001500    001959  ...         0.0        0.0       0
5764  20230702   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-02 00:25:00,788:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688228699, self.tradeDate='20230702', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30540.3, self.close=30537.7, self.high=30555.7, self.low=30533.8, self.vol=534.094, self.amt=16313077.7847, ukdf['pct'].iloc[-1]=-8.8e-05 , ukdf['amount'].iloc[-1]=16313077.7847, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137318.64064325407', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30541.22518627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230701   120000    155959  1688198399  ...    723  0.011212 -1.469111    -1.0
724  20230701   160000    195959  1688212799  ...    724  0.009735 -1.443327    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '10360.626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30512.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=291
self.closeSec=1688227199, self.tradeDate='20230701', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30508.5, self.close=30561.5, self.high=30668.2, self.low=30490.8, self.vol=32888.967, self.amt=1005597894.8934 
127.0.0.1 - - [02/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-02 00:00:01,670:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688227199, self.tradeDate='20230701', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30508.5, self.close=30561.5, self.high=30668.2, self.low=30490.8, self.vol=32888.967, self.amt=1005597894.8934 
2023-07-02 00:00:01,694:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230701   040000    075959  ...  35577.773  1.083165e+09  0.003290
722  20230701   080000    115959  ...  29778.267  9.064876e+08 -0.002265
723  20230701   120000    155959  ...  23531.509  7.153048e+08  0.001872
724  20230701   160000    195959  ...  23695.114  7.221367e+08  0.001984
725  20230701   200000    235959  ...  32888.967  1.005598e+09  0.001737

[5 rows x 11 columns]
2023-07-02 00:00:03,128:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230701   040000    075959  1688169599  ...    721  0.019349 -1.508678    -1.0
722  20230701   080000    115959  1688183999  ...    722  0.013109 -1.494357    -1.0
723  20230701   120000    155959  1688198399  ...    723  0.011212 -1.469111    -1.0
724  20230701   160000    195959  1688212799  ...    724  0.009735 -1.443327    -1.0
725  20230701   200000    235959  1688227199  ...    725  0.008270 -1.421216    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '7564.345631433', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30564.99456275', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


