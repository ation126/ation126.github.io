# 20230221 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24604
self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24850.1, self.close=24784.8, self.high=24889.7, self.low=24761.7, self.vol=4696.27, self.amt=116556590.699 
2023-02-21 00:20:01,730:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230220   235500    235959  ...         0.0        0.0       0
5760  20230221   000000    000459  ...         0.0        0.0       0
5761  20230221   000500    000959  ...         0.0        0.0       0
5762  20230221   001000    001459  ...         0.0        0.0       0
5763  20230221   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 00:20:01,732:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24850.1, self.close=24784.8, self.high=24889.7, self.low=24761.7, self.vol=4696.27, self.amt=116556590.699, ukdf['pct'].iloc[-1]=-0.002624 , ukdf['amount'].iloc[-1]=116556590.699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-497516.18044346704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24796.98446629', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=24605
self.closeSec=1676910299, self.tradeDate='20230221', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24799.7, self.close=24771.3, self.high=24810.6, self.low=24716.2, self.vol=7774.122, self.amt=192519819.5824 
2023-02-21 00:25:01,665:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230221   000000    000459  ...         0.0        0.0       0
5761  20230221   000500    000959  ...         0.0        0.0       0
5762  20230221   001000    001459  ...         0.0        0.0       0
5763  20230221   001500    001959  ...         0.0        0.0       0
5764  20230221   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 00:25:01,668:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1676910299, self.tradeDate='20230221', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24799.7, self.close=24771.3, self.high=24810.6, self.low=24716.2, self.vol=7774.122, self.amt=192519819.5824, ukdf['pct'].iloc[-1]=-0.000545 , ukdf['amount'].iloc[-1]=192519819.5824, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-496118.5388511528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24773.75856905', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=279, self.factor=0.45996469144277685, self.count=25170 

self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24850.1, self.close=24784.8, self.high=24889.7, self.low=24761.7 
2023-02-21 00:20:01,572:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24850.1, self.close=24784.8, self.high=24889.7, self.low=24761.7   
2023-02-21 00:20:01,627:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230220   235500    235959  1676908799  ...  24920.0 -0.000216   1727    5
1440  20230221   000000    000459  1676909099  ...  24850.0 -0.002778   1440    0
1441  20230221   000500    000959  1676909399  ...  24806.0 -0.000655   1441    1
1442  20230221   001000    001459  1676909699  ...  24839.1 -0.000362   1442    2
1443  20230221   001500    001959  1676909999  ...  24761.7 -0.002624   1443    3

[5 rows x 11 columns]
2023-02-21 00:20:01,631:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=279, self.factor=0.45996469144277685, self.count=25171 

self.closeSec=1676910299, self.tradeDate='20230221', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24799.7, self.close=24771.3, self.high=24810.6, self.low=24716.2 
2023-02-21 00:25:01,529:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1676910299, self.tradeDate='20230221', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24799.7, self.close=24771.3, self.high=24810.6, self.low=24716.2   
2023-02-21 00:25:01,620:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230221   000000    000459  1676909099  ...  24850.0 -0.002778   1440    0
1441  20230221   000500    000959  1676909399  ...  24806.0 -0.000655   1441    1
1442  20230221   001000    001459  1676909699  ...  24839.1 -0.000362   1442    2
1443  20230221   001500    001959  1676909999  ...  24761.7 -0.002624   1443    3
1444  20230221   002000    002459  1676910299  ...  24716.2 -0.000545   1444    4

[5 rows x 11 columns]
2023-02-21 00:25:01,626:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-21 00:00:34,385:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230220    212959  24819.2  ...  52.500000  0.558005  0.425370
5803  20230220    215959  24921.0  ...  52.500000  0.547135  0.404654
5804  20230220    222959  24856.8  ...  52.083333  0.544246  0.387905
5805  20230220    225959  24837.7  ...  52.500000  0.562713  0.370458
5806  20230220    232959  24974.2  ...  52.083333  0.552361  0.357277

[5 rows x 33 columns]
0.49816176470588236
acc is : 0.49816176470588236
2023-02-21 00:00:34,527:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.533510  0.466490       0  ...  1.077238   1.0    0.0  1.096521
540     0  0.503915  0.496085       0  ...  1.076493   1.0    0.0  1.095762
541     0  0.508762  0.491238       1  ...  1.082335   1.0    0.0  1.101709
542     0  0.553040  0.446960       0  ...  1.079687   1.0    0.0  1.099013
543     0  0.516160  0.483840       1  ...  1.081048   1.0    0.0  1.100398

[5 rows x 10 columns]
2023-02-21 00:00:34,555:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.533801  0.466199       0  ...  1.049951   1.0    0.0  1.100555
46     0  0.504007  0.495993       0  ...  1.049224   1.0    0.0  1.093755
47     0  0.508774  0.491226       1  ...  1.054918   1.0    0.0  1.099690
48     0  0.553473  0.446527       0  ...  1.079687   1.0    0.0  1.100222
49     0  0.516160  0.483840       1  ...  1.081048   1.0    0.0  1.100398

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '34.222', 'enterprice': '24804.7', 'countrevence': '0', 'unrealprofit': '4885.06672107932', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24947.44638306', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-21 00:00:04,070:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41779F1676908803440I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676908803803314, 'quantity': '39.337', 'price': '24944.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1676908802851, 'updatetime': 1676908803803, 'tradetype': 'usdt', 'selfid': 41779, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676908803803, 'clientorderid': '41779F1676908803440I0L59', 'price': '24944.7', 'quantity': '39.337', 'commission': '981.2496639', 'commissionasset': 'USDT', 'tradetime': 1676908803803, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676908803803}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Feb/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12584 

self.closeSec=1676909399, self.tradeDate='20230221', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24944.7', self.close='24859'
2023-02-21 00:10:01,673:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676909399, self.tradeDate='20230221', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24944.7', self.close='24859'
2023-02-21 00:10:01,737:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230220   232000    232959  1676906999  24977.6  24914.1 -0.002538
573  20230220   233000    233959  1676907599  24914.2  25029.6  0.004636
574  20230220   234000    234959  1676908199  25029.6  24950.3 -0.003168
575  20230220   235000    235959  1676908799  24950.3  24944.6 -0.000228
576  20230221   000000    000959  1676909399  24944.7    24859 -0.003432
2023-02-21 00:10:01,737:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12585 

self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24858.9', self.close='24784.8'
2023-02-21 00:20:01,679:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24858.9', self.close='24784.8'
2023-02-21 00:20:01,725:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230220   233000    233959  1676907599  24914.2  25029.6  0.004636
574  20230220   234000    234959  1676908199  25029.6  24950.3 -0.003168
575  20230220   235000    235959  1676908799  24950.3  24944.6 -0.000228
576  20230221   000000    000959  1676909399  24944.7    24859 -0.003432
577  20230221   001000    001959  1676909999  24858.9  24784.8 -0.002985
2023-02-21 00:20:01,729:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/percentile_regression_step2/log.txt ----- -----

127.0.0.1 - - [20/Feb/2023 23:00:02] "POST / HTTP/1.1" 200 -
2023-02-20 23:00:03,588:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 20:30:00  203000  24819.2  ...     NaN     NaN       0
145  2023/02/20 21:00:00  210000  24921.1  ...     NaN     NaN       0
146  2023/02/20 21:30:00  213000  24856.7  ...     NaN     NaN       0
147  2023/02/20 22:00:00  220000  24839.5  ...     NaN     NaN       0
148  2023/02/20 22:30:00  223000  24974.3  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [20/Feb/2023 23:30:02] "POST / HTTP/1.1" 200 -
2023-02-20 23:30:03,029:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 21:00:00  210000  24921.1  ...     NaN     NaN       0
145  2023/02/20 21:30:00  213000  24856.7  ...     NaN     NaN       0
146  2023/02/20 22:00:00  220000  24839.5  ...     NaN     NaN       0
147  2023/02/20 22:30:00  223000  24974.3  ...     NaN     NaN       0
148  2023/02/20 23:00:00  230000  24913.2  ...     NaN     NaN       0

[5 rows x 10 columns]
127.0.0.1 - - [21/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 00:00:03,500:DEBUG:percentile_regression_step2:main.py:154:get_signal:1265985: df_id.iloc[-5:,:] :
                 daytime     hms    close  ...  pct_10  pct_20  factor
144  2023/02/20 21:30:00  213000  24856.7  ...     NaN     NaN       0
145  2023/02/20 22:00:00  220000  24839.5  ...     NaN     NaN       0
146  2023/02/20 22:30:00  223000  24974.3  ...     NaN     NaN       0
147  2023/02/20 23:00:00  230000  24913.2  ...     NaN     NaN       0
148  2023/02/20 23:30:00  233000  24944.6  ...     NaN     NaN       0

[5 rows x 10 columns]


## /root/FIL/strategy/pyemd/log.txt ----- -----

2023-02-21 00:00:02,484:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-21 00:00:02,609:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2210000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230220, closeTime:235959, close:24944.6, total:979069.1011917, pct_pre:-0.002761113582354535, thd:0.08983219911439122, side:sell 
127.0.0.1 - - [21/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12585 

self.closeSec=1676909399, self.tradeDate='20230221', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24944.7', self.close='24859'
2023-02-21 00:10:01,704:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676909399, self.tradeDate='20230221', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24944.7', self.close='24859'
2023-02-21 00:10:01,747:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230220   232000    232959  1676906999  24977.6  24914.1
17421  20230220   233000    233959  1676907599  24914.2  25029.6
17422  20230220   234000    234959  1676908199  25029.6  24950.3
17423  20230220   235000    235959  1676908799  24950.3  24944.6
17424  20230221   000000    000959  1676909399  24944.7    24859
2023-02-21 00:10:01,747:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12586 

self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24858.9', self.close='24784.8'
2023-02-21 00:20:01,710:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24858.9', self.close='24784.8'
2023-02-21 00:20:01,747:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230220   233000    233959  1676907599  24914.2  25029.6
17422  20230220   234000    234959  1676908199  25029.6  24950.3
17423  20230220   235000    235959  1676908799  24950.3  24944.6
17424  20230221   000000    000959  1676909399  24944.7    24859
17425  20230221   001000    001959  1676909999  24858.9  24784.8
2023-02-21 00:20:01,747:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-02-21 00:00:03,560:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41778F1676908803172I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1676908803283591, 'quantity': '48.064', 'price': '24944.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1676908802710, 'updatetime': 1676908803283, 'tradetype': 'usdt', 'selfid': 41778, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1676908803283, 'clientorderid': '41778F1676908803172I0L2', 'price': '24944.6', 'quantity': '48.064', 'commission': '1198.9372544', 'commissionasset': 'USDT', 'tradetime': 1676908803283, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1676908803283}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12585 

self.closeSec=1676909399, self.tradeDate='20230221', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24944.7', self.close='24859'
2023-02-21 00:10:01,681:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676909399, self.tradeDate='20230221', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24944.7', self.close='24859'
2023-02-21 00:10:01,750:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230220   232000    232959  1676906999  24977.6  24914.1
12237  20230220   233000    233959  1676907599  24914.2  25029.6
12238  20230220   234000    234959  1676908199  25029.6  24950.3
12239  20230220   235000    235959  1676908799  24950.3  24944.6
12240  20230221   000000    000959  1676909399  24944.7    24859
2023-02-21 00:10:01,750:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [21/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12586 

self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24858.9', self.close='24784.8'
2023-02-21 00:20:01,704:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24858.9', self.close='24784.8'
2023-02-21 00:20:01,740:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230220   233000    233959  1676907599  24914.2  25029.6
12238  20230220   234000    234959  1676908199  25029.6  24950.3
12239  20230220   235000    235959  1676908799  24950.3  24944.6
12240  20230221   000000    000959  1676909399  24944.7    24859
12241  20230221   001000    001959  1676909999  24858.9  24784.8
2023-02-21 00:20:01,740:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20602
self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24850.1, self.close=24784.8, self.high=24889.7, self.low=24761.7, self.vol=4696.27, self.amt=116556590.699 
2023-02-21 00:20:01,643:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230220   235500    235959  ...         0.0        0.0       0
5760  20230221   000000    000459  ...         0.0        0.0       0
5761  20230221   000500    000959  ...         0.0        0.0       0
5762  20230221   001000    001459  ...         0.0        0.0       0
5763  20230221   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 00:20:01,645:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676909999, self.tradeDate='20230221', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24850.1, self.close=24784.8, self.high=24889.7, self.low=24761.7, self.vol=4696.27, self.amt=116556590.699, ukdf['pct'].iloc[-1]=-0.002624 , ukdf['amount'].iloc[-1]=116556590.699, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [21/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=20603
self.closeSec=1676910299, self.tradeDate='20230221', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24799.7, self.close=24771.3, self.high=24810.6, self.low=24716.2, self.vol=7774.122, self.amt=192519819.5824 
2023-02-21 00:25:01,640:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230221   000000    000459  ...         0.0        0.0       0
5761  20230221   000500    000959  ...         0.0        0.0       0
5762  20230221   001000    001459  ...         0.0        0.0       0
5763  20230221   001500    001959  ...         0.0        0.0       0
5764  20230221   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-21 00:25:01,640:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1676910299, self.tradeDate='20230221', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24799.7, self.close=24771.3, self.high=24810.6, self.low=24716.2, self.vol=7774.122, self.amt=192519819.5824, ukdf['pct'].iloc[-1]=-0.000545 , ukdf['amount'].iloc[-1]=192519819.5824, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230220   120000    155959  1676879999  ...    723  0.179914 -1.278394    -1.0
724  20230220   160000    195959  1676894399  ...    724  0.185992 -1.242748    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '1403.22054797925', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24896.31870155', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=524
self.closeSec=1676908799, self.tradeDate='20230220', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24896.0, self.close=24944.6, self.high=25140.0, self.low=24720.2, self.vol=167345.352, self.amt=4170410216.04735 
127.0.0.1 - - [21/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-21 00:00:02,294:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1676908799, self.tradeDate='20230220', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24896.0, self.close=24944.6, self.high=25140.0, self.low=24720.2, self.vol=167345.352, self.amt=4170410216.04735 
2023-02-21 00:00:02,345:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230220   040000    075959  ...   81659.528  1.993888e+09 -0.010060
722  20230220   080000    115959  ...  127984.816  3.095051e+09  0.006140
723  20230220   120000    155959  ...   50497.845  1.236248e+09  0.003490
724  20230220   160000    195959  ...  159438.885  3.951076e+09  0.016155
725  20230220   200000    235959  ...  167345.352  4.170410e+09  0.001956

[5 rows x 11 columns]
2023-02-21 00:00:05,146:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230220   040000    075959  1676851199  ...    721  0.152017 -1.404157    -1.0
722  20230220   080000    115959  1676865599  ...    722  0.193163 -1.266190    -1.0
723  20230220   120000    155959  1676879999  ...    723  0.179914 -1.278394    -1.0
724  20230220   160000    195959  1676894399  ...    724  0.185992 -1.242748    -1.0
725  20230220   200000    235959  1676908799  ...    725  0.220485 -1.139201    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '-334.6751931237', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24943.97798418', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


