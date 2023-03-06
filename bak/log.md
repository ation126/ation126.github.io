# 20230307 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [07/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28636
self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22535.3, self.close=22521.8, self.high=22551.1, self.low=22521.5, self.vol=2166.318, self.amt=48817360.62 
2023-03-07 00:20:01,631:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230306   235500    235959  ...         0.0        0.0       0
5760  20230307   000000    000459  ...         0.0        0.0       0
5761  20230307   000500    000959  ...         0.0        0.0       0
5762  20230307   001000    001459  ...         0.0        0.0       0
5763  20230307   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 00:20:01,632:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22535.3, self.close=22521.8, self.high=22551.1, self.low=22521.5, self.vol=2166.318, self.amt=48817360.62, ukdf['pct'].iloc[-1]=-0.000599 , ukdf['amount'].iloc[-1]=48817360.62, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-360636.40745359856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22522.32724431', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [07/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=28637
self.closeSec=1678119899, self.tradeDate='20230307', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22521.7, self.close=22510.6, self.high=22532.7, self.low=22500.9, self.vol=1733.38, self.amt=39028107.0844 
2023-03-07 00:25:01,937:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230307   000000    000459  ...         0.0        0.0       0
5761  20230307   000500    000959  ...         0.0        0.0       0
5762  20230307   001000    001459  ...         0.0        0.0       0
5763  20230307   001500    001959  ...         0.0        0.0       0
5764  20230307   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 00:25:01,939:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678119899, self.tradeDate='20230307', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22521.7, self.close=22510.6, self.high=22532.7, self.low=22500.9, self.vol=1733.38, self.amt=39028107.0844, ukdf['pct'].iloc[-1]=-0.000497 , ukdf['amount'].iloc[-1]=39028107.0844, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-359996.9024', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22511.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22535.3, self.close=22521.8, self.high=22551.1, self.low=22521.5 
2023-03-07 00:20:01,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22535.3, self.close=22521.8, self.high=22551.1, self.low=22521.5   
127.0.0.1 - - [07/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-07 00:20:01,532:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230306   235500    235959  1678118399  ...  22532.7 -0.000811   1727    5
1440  20230307   000000    000459  1678118699  ...  22543.5  0.000461   1440    0
1441  20230307   000500    000959  1678118999  ...  22496.6 -0.001281   1441    1
1442  20230307   001000    001459  1678119299  ...  22525.0  0.000453   1442    2
1443  20230307   001500    001959  1678119599  ...  22521.5 -0.000599   1443    3

[5 rows x 11 columns]
2023-03-07 00:20:01,532:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=68, self.factor=0.5593340063514834, self.count=29203 

self.closeSec=1678119899, self.tradeDate='20230307', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22521.7, self.close=22510.6, self.high=22532.7, self.low=22500.9 
2023-03-07 00:25:01,794:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678119899, self.tradeDate='20230307', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22521.7, self.close=22510.6, self.high=22532.7, self.low=22500.9   
2023-03-07 00:25:01,878:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230307   000000    000459  1678118699  ...  22543.5  0.000461   1440    0
1441  20230307   000500    000959  1678118999  ...  22496.6 -0.001281   1441    1
1442  20230307   001000    001459  1678119299  ...  22525.0  0.000453   1442    2
1443  20230307   001500    001959  1678119599  ...  22521.5 -0.000599   1443    3
1444  20230307   002000    002459  1678119899  ...  22500.9 -0.000497   1444    4

[5 rows x 11 columns]
2023-03-07 00:25:01,878:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-07 00:00:37,022:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230306    212959  22390.1  ...  47.500000  0.491798  0.536099
5803  20230306    215959  22398.9  ...  47.500000  0.505555  0.526653
5804  20230306    222959  22430.8  ...  47.500000  0.504722  0.518240
5805  20230306    225959  22428.8  ...  47.916667  0.509195  0.508206
5806  20230306    232959  22439.2  ...  47.500000  0.504545  0.501022

[5 rows x 33 columns]
0.5588235294117647
acc is : 0.5588235294117647
2023-03-07 00:00:37,189:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.508996  0.491004       1  ...  0.900792  -1.0    0.0  0.920604
540     0  0.523838  0.476162       0  ...  0.900869  -1.0    0.0  0.920526
541     0  0.512673  0.487327       1  ...  0.900455  -1.0    0.0  0.920949
542     0  0.515684  0.484316       0  ...  0.900868  -1.0    0.0  0.920526
543     0  0.506716  0.493284       1  ...  0.896261  -1.0    0.0  0.925234

[5 rows x 10 columns]
2023-03-07 00:00:37,205:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509285  0.490715       1  ...  0.900792  -1.0    0.0  0.920884
46     0  0.523791  0.476209       0  ...  0.900869  -1.0    0.0  0.920066
47     0  0.512701  0.487299       1  ...  0.900455  -1.0    0.0  0.920488
48     0  0.515432  0.484568       0  ...  0.923532  -1.0    0.0  0.918980
49     0  0.506716  0.493284       1  ...  0.896261  -1.0    0.0  0.925234

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.887', 'enterprice': '22396.9', 'countrevence': '0', 'unrealprofit': '-5423.9787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22567', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [07/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-07 00:00:03,146:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41897F1678118402751I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678118402864723, 'quantity': '45.997', 'price': '22547.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678118402236, 'updatetime': 1678118402864, 'tradetype': 'usdt', 'selfid': 41897, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678118402864, 'clientorderid': '41897F1678118402751I0L59', 'price': '22547.8', 'quantity': '45.997', 'commission': '1037.1311566', 'commissionasset': 'USDT', 'tradetime': 1678118402864, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678118402864}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14600 

self.closeSec=1678118999, self.tradeDate='20230307', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22543.6', self.close='22525.1'
2023-03-07 00:10:01,730:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678118999, self.tradeDate='20230307', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22543.6', self.close='22525.1'
127.0.0.1 - - [07/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-07 00:10:01,770:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230306   232000    232959  1678116599  22460.1  22428.9 -0.001394
573  20230306   233000    233959  1678117199  22428.9  22436.5  0.000339
574  20230306   234000    234959  1678117799  22436.5    22495  0.002607
575  20230306   235000    235959  1678118399  22494.9  22543.6  0.002160
576  20230307   000000    000959  1678118999  22543.6  22525.1 -0.000821
2023-03-07 00:10:01,774:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14601 

self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22525.1', self.close='22521.8'
2023-03-07 00:20:01,592:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22525.1', self.close='22521.8'
2023-03-07 00:20:01,663:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230306   233000    233959  1678117199  22428.9  22436.5  0.000339
574  20230306   234000    234959  1678117799  22436.5    22495  0.002607
575  20230306   235000    235959  1678118399  22494.9  22543.6  0.002160
576  20230307   000000    000959  1678118999  22543.6  22525.1 -0.000821
577  20230307   001000    001959  1678119599  22525.1  22521.8 -0.000147
2023-03-07 00:20:01,663:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-07 00:00:02,140:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-07 00:00:02,320:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3070000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230306, closeTime:235959, close:22543.6, total:984062.1980325, pct_pre:-0.0013735283624687344, thd:0.2568954600128267, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14601 

self.closeSec=1678118999, self.tradeDate='20230307', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22543.6', self.close='22525.1'
2023-03-07 00:10:01,768:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678118999, self.tradeDate='20230307', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22543.6', self.close='22525.1'
127.0.0.1 - - [07/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-07 00:10:01,790:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230306   232000    232959  1678116599  22460.1  22428.9
17421  20230306   233000    233959  1678117199  22428.9  22436.5
17422  20230306   234000    234959  1678117799  22436.5    22495
17423  20230306   235000    235959  1678118399  22494.9  22543.6
17424  20230307   000000    000959  1678118999  22543.6  22525.1
2023-03-07 00:10:01,791:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [07/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14602 

self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22525.1', self.close='22521.8'
2023-03-07 00:20:01,609:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22525.1', self.close='22521.8'
2023-03-07 00:20:01,633:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230306   233000    233959  1678117199  22428.9  22436.5
17422  20230306   234000    234959  1678117799  22436.5    22495
17423  20230306   235000    235959  1678118399  22494.9  22543.6
17424  20230307   000000    000959  1678118999  22543.6  22525.1
17425  20230307   001000    001959  1678119599  22525.1  22521.8
2023-03-07 00:20:01,636:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [07/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-07 00:00:03,403:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41898F1678118402770I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678118403056261, 'quantity': '52.661', 'price': '22547.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678118402389, 'updatetime': 1678118403056, 'tradetype': 'usdt', 'selfid': 41898, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678118403056, 'clientorderid': '41898F1678118402770I0L2', 'price': '22547.8', 'quantity': '52.661', 'commission': '1187.3896958', 'commissionasset': 'USDT', 'tradetime': 1678118403056, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678118403056}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14601 

self.closeSec=1678118999, self.tradeDate='20230307', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='22543.6', self.close='22525.1'
127.0.0.1 - - [07/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-07 00:10:01,744:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678118999, self.tradeDate='20230307', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='22543.6', self.close='22525.1'
2023-03-07 00:10:01,781:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230306   232000    232959  1678116599  22460.1  22428.9
12237  20230306   233000    233959  1678117199  22428.9  22436.5
12238  20230306   234000    234959  1678117799  22436.5    22495
12239  20230306   235000    235959  1678118399  22494.9  22543.6
12240  20230307   000000    000959  1678118999  22543.6  22525.1
2023-03-07 00:10:01,781:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [07/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14602 

self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='22525.1', self.close='22521.8'
2023-03-07 00:20:01,624:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='22525.1', self.close='22521.8'
2023-03-07 00:20:01,669:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230306   233000    233959  1678117199  22428.9  22436.5
12238  20230306   234000    234959  1678117799  22436.5    22495
12239  20230306   235000    235959  1678118399  22494.9  22543.6
12240  20230307   000000    000959  1678118999  22543.6  22525.1
12241  20230307   001000    001959  1678119599  22525.1  22521.8
2023-03-07 00:20:01,670:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [07/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24634
self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=22535.3, self.close=22521.8, self.high=22551.1, self.low=22521.5, self.vol=2166.318, self.amt=48817360.62 
2023-03-07 00:20:01,629:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230306   235500    235959  ...         0.0        0.0       0
5760  20230307   000000    000459  ...         0.0        0.0       0
5761  20230307   000500    000959  ...         0.0        0.0       0
5762  20230307   001000    001459  ...         0.0        0.0       0
5763  20230307   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 00:20:01,630:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678119599, self.tradeDate='20230307', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=22535.3, self.close=22521.8, self.high=22551.1, self.low=22521.5, self.vol=2166.318, self.amt=48817360.62, ukdf['pct'].iloc[-1]=-0.000599 , ukdf['amount'].iloc[-1]=48817360.62, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [07/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=24635
self.closeSec=1678119899, self.tradeDate='20230307', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=22521.7, self.close=22510.6, self.high=22532.7, self.low=22500.9, self.vol=1733.38, self.amt=39028107.0844 
2023-03-07 00:25:01,939:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230307   000000    000459  ...         0.0        0.0       0
5761  20230307   000500    000959  ...         0.0        0.0       0
5762  20230307   001000    001459  ...         0.0        0.0       0
5763  20230307   001500    001959  ...         0.0        0.0       0
5764  20230307   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-07 00:25:01,940:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678119899, self.tradeDate='20230307', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=22521.7, self.close=22510.6, self.high=22532.7, self.low=22500.9, self.vol=1733.38, self.amt=39028107.0844, ukdf['pct'].iloc[-1]=-0.000497 , ukdf['amount'].iloc[-1]=39028107.0844, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230306   120000    155959  1678089599  ...    723  0.425069 -0.518944     NaN
724  20230306   160000    195959  1678103999  ...    724  0.359881 -0.753584    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '41265.62809963305', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22370.93301057', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=608
self.closeSec=1678118399, self.tradeDate='20230306', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=22369.9, self.close=22543.6, self.high=22594.5, self.low=22348.0, self.vol=69925.596, self.amt=1570429741.3818 
127.0.0.1 - - [07/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-07 00:00:01,940:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678118399, self.tradeDate='20230306', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=22369.9, self.close=22543.6, self.high=22594.5, self.low=22348.0, self.vol=69925.596, self.amt=1570429741.3818 
2023-03-07 00:00:01,984:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230306   040000    075959  ...  53766.640  1.205734e+09  0.001134
722  20230306   080000    115959  ...  65552.847  1.466936e+09 -0.001847
723  20230306   120000    155959  ...  27604.231  6.175179e+08  0.000130
724  20230306   160000    195959  ...  29028.106  6.498239e+08 -0.000491
725  20230306   200000    235959  ...  69925.596  1.570430e+09  0.007765

[5 rows x 11 columns]
2023-03-07 00:00:05,178:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230306   040000    075959  1678060799  ...    721  0.571982  0.009081     NaN
722  20230306   080000    115959  1678075199  ...    722  0.516390 -0.187218     NaN
723  20230306   120000    155959  1678089599  ...    723  0.425069 -0.518944     NaN
724  20230306   160000    195959  1678103999  ...    724  0.359881 -0.753584    -1.0
725  20230306   200000    235959  1678118399  ...    725  0.290726 -1.003096    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '33813.3375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22547.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


