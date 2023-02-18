# 20230219 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24028
self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24685.8, self.close=24670.1, self.high=24699.7, self.low=24656.0, self.vol=1294.628, self.amt=31949915.9345 
2023-02-19 00:20:01,647:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230218   235500    235959  ...         0.0        0.0       0
5760  20230219   000000    000459  ...         0.0        0.0       0
5761  20230219   000500    000959  ...         0.0        0.0       0
5762  20230219   001000    001459  ...         0.0        0.0       0
5763  20230219   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 00:20:01,647:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24685.8, self.close=24670.1, self.high=24699.7, self.low=24656.0, self.vol=1294.628, self.amt=31949915.9345, ukdf['pct'].iloc[-1]=-0.000636 , ukdf['amount'].iloc[-1]=31949915.9345, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-489862.728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24669.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24029
self.closeSec=1676737499, self.tradeDate='20230219', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24670.0, self.close=24663.5, self.high=24670.1, self.low=24653.0, self.vol=478.114, self.amt=11790625.4238 
2023-02-19 00:25:01,667:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230219   000000    000459  ...         0.0        0.0       0
5761  20230219   000500    000959  ...         0.0        0.0       0
5762  20230219   001000    001459  ...         0.0        0.0       0
5763  20230219   001500    001959  ...         0.0        0.0       0
5764  20230219   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 00:25:01,671:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676737499, self.tradeDate='20230219', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24670.0, self.close=24663.5, self.high=24670.1, self.low=24653.0, self.vol=478.114, self.amt=11790625.4238, ukdf['pct'].iloc[-1]=-0.000268 , ukdf['amount'].iloc[-1]=11790625.4238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-489446.5965598832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24662.8847607', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24685.8, self.close=24670.1, self.high=24699.7, self.low=24656.0 
2023-02-19 00:20:01,539:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24685.8, self.close=24670.1, self.high=24699.7, self.low=24656.0   
127.0.0.1 - - [19/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 00:20:01,571:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230218   235500    235959  1676735999  ...  24669.7 -0.001643   1727    5
1440  20230219   000000    000459  1676736299  ...  24667.4  0.000336   1440    0
1441  20230219   000500    000959  1676736599  ...  24663.2 -0.000608   1441    1
1442  20230219   001000    001459  1676736899  ...  24646.0  0.000912   1442    2
1443  20230219   001500    001959  1676737199  ...  24656.0 -0.000636   1443    3

[5 rows x 11 columns]
2023-02-19 00:20:01,580:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=183, self.factor=0.4260811330189351, self.count=24595 

self.closeSec=1676737499, self.tradeDate='20230219', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24670.0, self.close=24663.5, self.high=24670.1, self.low=24653.0 
2023-02-19 00:25:01,525:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676737499, self.tradeDate='20230219', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24670.0, self.close=24663.5, self.high=24670.1, self.low=24653.0   
2023-02-19 00:25:01,595:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230219   000000    000459  1676736299  ...  24667.4  0.000336   1440    0
1441  20230219   000500    000959  1676736599  ...  24663.2 -0.000608   1441    1
1442  20230219   001000    001459  1676736899  ...  24646.0  0.000912   1442    2
1443  20230219   001500    001959  1676737199  ...  24656.0 -0.000636   1443    3
1444  20230219   002000    002459  1676737499  ...  24653.0 -0.000268   1444    4

[5 rows x 11 columns]
2023-02-19 00:25:01,596:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-19 00:00:34,901:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230218    212959  24624.6  ...  52.083333  0.554175  0.373217
5803  20230218    215959  24610.1  ...  52.083333  0.550563  0.378333
5804  20230218    222959  24587.9  ...  52.500000  0.552066  0.382370
5805  20230218    225959  24598.8  ...  52.500000  0.565308  0.379551
5806  20230218    232959  24699.1  ...  52.500000  0.563371  0.377671

[5 rows x 33 columns]
0.5073529411764706
acc is : 0.5073529411764706
2023-02-19 00:00:35,049:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.510791  0.489209       0  ...  1.046060   1.0    0.0  1.073441
540     1  0.496982  0.503018       1  ...  1.046537   1.0    0.0  1.073930
541     0  0.502710  0.497290       1  ...  1.050791   1.0    0.0  1.078295
542     0  0.522271  0.477729       0  ...  1.050306   1.0    0.0  1.077798
543     1  0.499164  0.500836       0  ...  1.049557   1.0    0.0  1.077029

[5 rows x 10 columns]
2023-02-19 00:00:35,085:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.510305  0.489695       0  ...  1.046060   1.0    0.0  1.070664
46     1  0.496973  0.503027       1  ...  1.046537   1.0    0.0  1.073470
47     0  0.502689  0.497311       1  ...  1.050791   1.0    0.0  1.077834
48     0  0.521714  0.478286       0  ...  1.050306   1.0    0.0  1.076853
49     1  0.499164  0.500836       0  ...  1.049557   1.0    0.0  1.077029

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '35.459', 'enterprice': '24163.6', 'countrevence': '0', 'unrealprofit': '18067.56124953536', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24673.13386304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-19 00:00:03,981:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41764F1676736003290I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676736003480907, 'quantity': '38.761', 'price': '24674.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676736002695, 'updatetime': 1676736003480, 'tradetype': 'usdt', 'selfid': 41764, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676736003480, 'clientorderid': '41764F1676736003290I0L59', 'price': '24674.5', 'quantity': '38.761', 'commission': '956.4082945', 'commissionasset': 'USDT', 'tradetime': 1676736003480, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676736003480}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12296 

self.closeSec=1676736599, self.tradeDate='20230219', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24670', self.close='24663.3'
2023-02-19 00:10:01,647:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676736599, self.tradeDate='20230219', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24670', self.close='24663.3'
127.0.0.1 - - [19/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-19 00:10:01,658:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230218   232000    232959  1676734199  24660.6  24687.6  0.001099
573  20230218   233000    233959  1676734799  24687.7  24725.1  0.001519
574  20230218   234000    234959  1676735399  24725.1    24720 -0.000206
575  20230218   235000    235959  1676735999    24720    24670 -0.002023
576  20230219   000000    000959  1676736599    24670  24663.3 -0.000272
2023-02-19 00:10:01,659:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12297 

self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24663.3', self.close='24670.1'
2023-02-19 00:20:01,675:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24663.3', self.close='24670.1'
127.0.0.1 - - [19/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 00:20:01,689:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230218   233000    233959  1676734799  24687.7  24725.1  0.001519
574  20230218   234000    234959  1676735399  24725.1    24720 -0.000206
575  20230218   235000    235959  1676735999    24720    24670 -0.002023
576  20230219   000000    000959  1676736599    24670  24663.3 -0.000272
577  20230219   001000    001959  1676737199  24663.3  24670.1  0.000276
2023-02-19 00:20:01,694:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [18/Feb/2023 23:00:02] "POST / HTTP/1.1" 200 -
2023-02-18 23:00:03,362:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 20:30:00  203000  24624.6  ...     NaN     NaN       0
145  2023/02/18 21:00:00  210000  24610.0  ...     NaN     NaN       0
146  2023/02/18 21:30:00  213000  24587.8  ...     NaN     NaN       0
147  2023/02/18 22:00:00  220000  24599.0  ...     NaN     NaN       0
148  2023/02/18 22:30:00  223000  24699.0  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [18/Feb/2023 23:30:01] "POST / HTTP/1.1" 200 -
2023-02-18 23:30:02,823:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 21:00:00  210000  24610.0  ...     NaN     NaN       0
145  2023/02/18 21:30:00  213000  24587.8  ...     NaN     NaN       0
146  2023/02/18 22:00:00  220000  24599.0  ...     NaN     NaN       0
147  2023/02/18 22:30:00  223000  24699.0  ...     NaN     NaN       0
148  2023/02/18 23:00:00  230000  24687.6  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [19/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-19 00:00:03,572:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/18 21:30:00  213000  24587.8  ...     NaN     NaN       0
145  2023/02/18 22:00:00  220000  24599.0  ...     NaN     NaN       0
146  2023/02/18 22:30:00  223000  24699.0  ...     NaN     NaN       0
147  2023/02/18 23:00:00  230000  24687.6  ...     NaN     NaN       0
148  2023/02/18 23:30:00  233000  24670.0  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-19 00:00:03,694:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41763F1676736003261I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676736003381107, 'quantity': '39.679', 'price': '24674.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676736002777, 'updatetime': 1676736003381, 'tradetype': 'usdt', 'selfid': 41763, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676736003381, 'clientorderid': '41763F1676736003261I0L57', 'price': '24674.4', 'quantity': '39.679', 'commission': '979.0555176', 'commissionasset': 'USDT', 'tradetime': 1676736003381, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676736003381}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12297 

self.closeSec=1676736599, self.tradeDate='20230219', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24670', self.close='24663.3'
2023-02-19 00:10:01,620:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676736599, self.tradeDate='20230219', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24670', self.close='24663.3'
2023-02-19 00:10:01,660:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230218   232000    232959  1676734199  24660.6  24687.6
17421  20230218   233000    233959  1676734799  24687.7  24725.1
17422  20230218   234000    234959  1676735399  24725.1    24720
17423  20230218   235000    235959  1676735999    24720    24670
17424  20230219   000000    000959  1676736599    24670  24663.3
2023-02-19 00:10:01,661:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12298 

self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24663.3', self.close='24670.1'
127.0.0.1 - - [19/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-19 00:20:01,659:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24663.3', self.close='24670.1'
2023-02-19 00:20:01,671:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230218   233000    233959  1676734799  24687.7  24725.1
17422  20230218   234000    234959  1676735399  24725.1    24720
17423  20230218   235000    235959  1676735999    24720    24670
17424  20230219   000000    000959  1676736599    24670  24663.3
17425  20230219   001000    001959  1676737199  24663.3  24670.1
2023-02-19 00:20:01,671:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-02-19 00:00:04,443:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41765F1676736003503I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676736004215001, 'quantity': '48.376', 'price': '24674.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676736003000, 'updatetime': 1676736004215, 'tradetype': 'usdt', 'selfid': 41765, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676736004215, 'clientorderid': '41765F1676736003503I0L2', 'price': '24674.4', 'quantity': '48.376', 'commission': '1193.6487744', 'commissionasset': 'USDT', 'tradetime': 1676736004215, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676736004215}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12297 

self.closeSec=1676736599, self.tradeDate='20230219', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24670', self.close='24663.3'
127.0.0.1 - - [19/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-19 00:10:01,629:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676736599, self.tradeDate='20230219', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24670', self.close='24663.3'
2023-02-19 00:10:01,667:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230218   232000    232959  1676734199  24660.6  24687.6
12237  20230218   233000    233959  1676734799  24687.7  24725.1
12238  20230218   234000    234959  1676735399  24725.1    24720
12239  20230218   235000    235959  1676735999    24720    24670
12240  20230219   000000    000959  1676736599    24670  24663.3
2023-02-19 00:10:01,668:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [19/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12298 

self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24663.3', self.close='24670.1'
2023-02-19 00:20:01,695:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24663.3', self.close='24670.1'
2023-02-19 00:20:01,723:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230218   233000    233959  1676734799  24687.7  24725.1
12238  20230218   234000    234959  1676735399  24725.1    24720
12239  20230218   235000    235959  1676735999    24720    24670
12240  20230219   000000    000959  1676736599    24670  24663.3
12241  20230219   001000    001959  1676737199  24663.3  24670.1
2023-02-19 00:20:01,723:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20026
self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24685.8, self.close=24670.1, self.high=24699.7, self.low=24656.0, self.vol=1294.628, self.amt=31949915.9345 
2023-02-19 00:20:01,608:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230218   235500    235959  ...         0.0        0.0       0
5760  20230219   000000    000459  ...         0.0        0.0       0
5761  20230219   000500    000959  ...         0.0        0.0       0
5762  20230219   001000    001459  ...         0.0        0.0       0
5763  20230219   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 00:20:01,609:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676737199, self.tradeDate='20230219', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24685.8, self.close=24670.1, self.high=24699.7, self.low=24656.0, self.vol=1294.628, self.amt=31949915.9345, ukdf['pct'].iloc[-1]=-0.000636 , ukdf['amount'].iloc[-1]=31949915.9345, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [19/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20027
self.closeSec=1676737499, self.tradeDate='20230219', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24670.0, self.close=24663.5, self.high=24670.1, self.low=24653.0, self.vol=478.114, self.amt=11790625.4238 
2023-02-19 00:25:01,616:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230219   000000    000459  ...         0.0        0.0       0
5761  20230219   000500    000959  ...         0.0        0.0       0
5762  20230219   001000    001459  ...         0.0        0.0       0
5763  20230219   001500    001959  ...         0.0        0.0       0
5764  20230219   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-19 00:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676737499, self.tradeDate='20230219', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24670.0, self.close=24663.5, self.high=24670.1, self.low=24653.0, self.vol=478.114, self.amt=11790625.4238, ukdf['pct'].iloc[-1]=-0.000268 , ukdf['amount'].iloc[-1]=11790625.4238, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230218   120000    155959  1676707199  ...    723  1.082603  1.179174     1.0
724  20230218   160000    195959  1676721599  ...    724  1.004289  0.942814     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '44026.1008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24523.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [19/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=850682.4935724001, self.flagDict['side']='buy', self.tradeCount=20, self.count=512
self.closeSec=1676735999, self.tradeDate='20230218', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24525.7, self.close=24670.0, self.high=24750.0, self.low=24494.4, self.vol=55533.683, self.amt=1368031083.1196 
2023-02-19 00:00:02,299:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676735999, self.tradeDate='20230218', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24525.7, self.close=24670.0, self.high=24750.0, self.low=24494.4, self.vol=55533.683, self.amt=1368031083.1196 
2023-02-19 00:00:02,336:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230218   040000    075959  ...  225818.499  5.563054e+09  0.002234
722  20230218   080000    115959  ...   50759.107  1.250384e+09  0.001562
723  20230218   120000    155959  ...   34345.925  8.447181e+08 -0.003944
724  20230218   160000    195959  ...   36886.129  9.047125e+08  0.000114
725  20230218   200000    235959  ...   55533.683  1.368031e+09  0.005888

[5 rows x 11 columns]
2023-02-19 00:00:04,898:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230218   040000    075959  1676678399  ...    721  1.199144  1.565452     1.0
722  20230218   080000    115959  1676692799  ...    722  1.148250  1.388875     1.0
723  20230218   120000    155959  1676707199  ...    723  1.082603  1.179174     1.0
724  20230218   160000    195959  1676721599  ...    724  1.004289  0.942814     1.0
725  20230218   200000    235959  1676735999  ...    725  0.941629  0.757507     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.518', 'enterprice': '23318.2', 'countrevence': '0', 'unrealprofit': '49457.86481254734', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24672.54210013', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


