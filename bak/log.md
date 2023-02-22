# 20230223 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25180
self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23687.2, self.close=23719.4, self.high=23719.4, self.low=23655.0, self.vol=2928.35, self.amt=69366739.695 
127.0.0.1 - - [23/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:20:01,728:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230222   235500    235959  ...         0.0        0.0       0
5760  20230223   000000    000459  ...         0.0        0.0       0
5761  20230223   000500    000959  ...         0.0        0.0       0
5762  20230223   001000    001459  ...         0.0        0.0       0
5763  20230223   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 00:20:01,728:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23687.2, self.close=23719.4, self.high=23719.4, self.low=23655.0, self.vol=2928.35, self.amt=69366739.695, ukdf['pct'].iloc[-1]=0.001355 , ukdf['amount'].iloc[-1]=69366739.695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-432827.9152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23722', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=25181
self.closeSec=1677083099, self.tradeDate='20230223', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23719.3, self.close=23736.0, self.high=23738.6, self.low=23700.6, self.vol=1886.898, self.amt=44766637.3773 
2023-02-23 00:25:01,671:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230223   000000    000459  ...         0.0        0.0       0
5761  20230223   000500    000959  ...         0.0        0.0       0
5762  20230223   001000    001459  ...         0.0        0.0       0
5763  20230223   001500    001959  ...         0.0        0.0       0
5764  20230223   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 00:25:01,671:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677083099, self.tradeDate='20230223', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23719.3, self.close=23736.0, self.high=23738.6, self.low=23700.6, self.vol=1886.898, self.amt=44766637.3773, ukdf['pct'].iloc[-1]=0.0007 , ukdf['amount'].iloc[-1]=44766637.3773, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-433778.696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23737.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23687.2, self.close=23719.4, self.high=23719.4, self.low=23655.0 
2023-02-23 00:20:01,571:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23687.2, self.close=23719.4, self.high=23719.4, self.low=23655.0   
127.0.0.1 - - [23/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:20:01,636:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230222   235500    235959  1677081599  ...  23696.8  0.000350   1727    5
1440  20230223   000000    000459  1677081899  ...  23683.9  0.000261   1440    0
1441  20230223   000500    000959  1677082199  ...  23704.9  0.000784   1441    1
1442  20230223   001000    001459  1677082499  ...  23680.4 -0.002005   1442    2
1443  20230223   001500    001959  1677082799  ...  23655.0  0.001355   1443    3

[5 rows x 11 columns]
2023-02-23 00:20:01,637:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7449615856103571, self.count=25747 

self.closeSec=1677083099, self.tradeDate='20230223', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23719.3, self.close=23736.0, self.high=23738.6, self.low=23700.6 
2023-02-23 00:25:01,577:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677083099, self.tradeDate='20230223', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23719.3, self.close=23736.0, self.high=23738.6, self.low=23700.6   
2023-02-23 00:25:01,611:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230223   000000    000459  1677081899  ...  23683.9  0.000261   1440    0
1441  20230223   000500    000959  1677082199  ...  23704.9  0.000784   1441    1
1442  20230223   001000    001459  1677082499  ...  23680.4 -0.002005   1442    2
1443  20230223   001500    001959  1677082799  ...  23655.0  0.001355   1443    3
1444  20230223   002000    002459  1677083099  ...  23700.6  0.000700   1444    4

[5 rows x 11 columns]
2023-02-23 00:25:01,611:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-23 00:00:35,271:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230222    212959  24128.4  ...  49.583333  0.446863  0.751536
5803  20230222    215959  24066.4  ...  50.000000  0.453117  0.749239
5804  20230222    222959  24104.2  ...  49.583333  0.435179  0.757077
5805  20230222    225959  23968.8  ...  49.583333  0.429502  0.767513
5806  20230222    232959  23927.8  ...  49.166667  0.407742  0.775210

[5 rows x 33 columns]
0.5220588235294118
acc is : 0.5220588235294118
2023-02-23 00:00:35,429:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.507552  0.492448       1  ...  1.055556   1.0    0.0  1.111725
540     0  0.533155  0.466845       0  ...  1.049626   1.0    0.0  1.105480
541     1  0.488049  0.511951       0  ...  1.047686   1.0    0.0  1.103437
542     1  0.487232  0.512768       0  ...  1.039909   1.0    0.0  1.095245
543     1  0.456010  0.543990       0  ...  1.038293   1.0    0.0  1.093543

[5 rows x 10 columns]
2023-02-23 00:00:35,451:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507646  0.492354       1  ...  1.055556   1.0    0.0  1.112854
46     0  0.534070  0.465930       0  ...  1.049626   1.0    0.0  1.106700
47     1  0.488957  0.511043       0  ...  1.047686   1.0    0.0  1.104654
48     1  0.487698  0.512302       0  ...  1.039909   1.0    0.0  1.096393
49     1  0.456010  0.543990       0  ...  1.038293   1.0    0.0  1.093543

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.835', 'enterprice': '24119', 'countrevence': '0', 'unrealprofit': '-14386.642', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23693.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-02-23 00:00:03,995:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41804F1677081603367I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677081603760215, 'quantity': '39.301', 'price': '23703.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677081602949, 'updatetime': 1677081603760, 'tradetype': 'usdt', 'selfid': 41804, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677081603760, 'clientorderid': '41804F1677081603367I0L59', 'price': '23703.7', 'quantity': '39.301', 'commission': '931.5791137', 'commissionasset': 'USDT', 'tradetime': 1677081603760, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677081603760}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12872 

self.closeSec=1677082199, self.tradeDate='20230223', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23707.5', self.close='23734.9'
2023-02-23 00:10:01,694:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677082199, self.tradeDate='20230223', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23707.5', self.close='23734.9'
127.0.0.1 - - [23/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:10:01,717:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230222   232000    232959  1677079799  23696.6    23747  0.002021
573  20230222   233000    233959  1677080399  23747.1  23684.9 -0.002615
574  20230222   234000    234959  1677080999    23685    23767  0.003466
575  20230222   235000    235959  1677081599  23766.9  23710.1 -0.002394
576  20230223   000000    000959  1677082199  23707.5  23734.9  0.001046
2023-02-23 00:10:01,717:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12873 

self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23729.6', self.close='23719.4'
2023-02-23 00:20:01,666:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23729.6', self.close='23719.4'
127.0.0.1 - - [23/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:20:01,691:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230222   233000    233959  1677080399  23747.1  23684.9 -0.002615
574  20230222   234000    234959  1677080999    23685    23767  0.003466
575  20230222   235000    235959  1677081599  23766.9  23710.1 -0.002394
576  20230223   000000    000959  1677082199  23707.5  23734.9  0.001046
577  20230223   001000    001959  1677082799  23729.6  23719.4 -0.000653
2023-02-23 00:20:01,692:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-02-23 00:00:02,707:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-02-23 00:00:02,821:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:2230000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230222, closeTime:235959, close:23710.1, total:979069.1011917, pct_pre:-0.015776580107790372, thd:-0.3601147001068337, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12873 

self.closeSec=1677082199, self.tradeDate='20230223', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23707.5', self.close='23734.9'
2023-02-23 00:10:01,684:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677082199, self.tradeDate='20230223', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23707.5', self.close='23734.9'
127.0.0.1 - - [23/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:10:01,723:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230222   232000    232959  1677079799  23696.6    23747
17421  20230222   233000    233959  1677080399  23747.1  23684.9
17422  20230222   234000    234959  1677080999    23685    23767
17423  20230222   235000    235959  1677081599  23766.9  23710.1
17424  20230223   000000    000959  1677082199  23707.5  23734.9
2023-02-23 00:10:01,725:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12874 

self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23729.6', self.close='23719.4'
2023-02-23 00:20:01,655:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23729.6', self.close='23719.4'
2023-02-23 00:20:01,702:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230222   233000    233959  1677080399  23747.1  23684.9
17422  20230222   234000    234959  1677080999    23685    23767
17423  20230222   235000    235959  1677081599  23766.9  23710.1
17424  20230223   000000    000959  1677082199  23707.5  23734.9
17425  20230223   001000    001959  1677082799  23729.6  23719.4
2023-02-23 00:20:01,707:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [23/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-23 00:00:03,698:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41803F1677081603352I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677081603499737, 'quantity': '48.794', 'price': '23703.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677081602988, 'updatetime': 1677081603499, 'tradetype': 'usdt', 'selfid': 41803, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677081603499, 'clientorderid': '41803F1677081603352I0L2', 'price': '23703.6', 'quantity': '48.794', 'commission': '1156.5934584', 'commissionasset': 'USDT', 'tradetime': 1677081603499, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677081603499}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [23/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12873 

self.closeSec=1677082199, self.tradeDate='20230223', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23707.5', self.close='23734.9'
2023-02-23 00:10:01,673:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677082199, self.tradeDate='20230223', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23707.5', self.close='23734.9'
2023-02-23 00:10:01,718:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230222   232000    232959  1677079799  23696.6    23747
12237  20230222   233000    233959  1677080399  23747.1  23684.9
12238  20230222   234000    234959  1677080999    23685    23767
12239  20230222   235000    235959  1677081599  23766.9  23710.1
12240  20230223   000000    000959  1677082199  23707.5  23734.9
2023-02-23 00:10:01,718:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12874 

self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23729.6', self.close='23719.4'
127.0.0.1 - - [23/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:20:01,654:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23729.6', self.close='23719.4'
2023-02-23 00:20:01,696:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230222   233000    233959  1677080399  23747.1  23684.9
12238  20230222   234000    234959  1677080999    23685    23767
12239  20230222   235000    235959  1677081599  23766.9  23710.1
12240  20230223   000000    000959  1677082199  23707.5  23734.9
12241  20230223   001000    001959  1677082799  23729.6  23719.4
2023-02-23 00:20:01,697:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21178
self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23687.2, self.close=23719.4, self.high=23719.4, self.low=23655.0, self.vol=2928.35, self.amt=69366739.695 
127.0.0.1 - - [23/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:20:01,611:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230222   235500    235959  ...         0.0        0.0       0
5760  20230223   000000    000459  ...         0.0        0.0       0
5761  20230223   000500    000959  ...         0.0        0.0       0
5762  20230223   001000    001459  ...         0.0        0.0       0
5763  20230223   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 00:20:01,611:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677082799, self.tradeDate='20230223', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23687.2, self.close=23719.4, self.high=23719.4, self.low=23655.0, self.vol=2928.35, self.amt=69366739.695, ukdf['pct'].iloc[-1]=0.001355 , ukdf['amount'].iloc[-1]=69366739.695, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=21179
self.closeSec=1677083099, self.tradeDate='20230223', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23719.3, self.close=23736.0, self.high=23738.6, self.low=23700.6, self.vol=1886.898, self.amt=44766637.3773 
127.0.0.1 - - [23/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-02-23 00:25:01,655:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230223   000000    000459  ...         0.0        0.0       0
5761  20230223   000500    000959  ...         0.0        0.0       0
5762  20230223   001000    001459  ...         0.0        0.0       0
5763  20230223   001500    001959  ...         0.0        0.0       0
5764  20230223   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-23 00:25:01,655:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677083099, self.tradeDate='20230223', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23719.3, self.close=23736.0, self.high=23738.6, self.low=23700.6, self.vol=1886.898, self.amt=44766637.3773, ukdf['pct'].iloc[-1]=0.0007 , ukdf['amount'].iloc[-1]=44766637.3773, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230222   120000    155959  1677052799  ...    723  0.211909 -0.964276    -1.0
724  20230222   160000    195959  1677067199  ...    724  0.289427 -0.762059    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '28383.26072960235', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24156.43003621', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=908338.234518, self.flagDict['side']='sell', self.tradeCount=21, self.count=536
self.closeSec=1677081599, self.tradeDate='20230222', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24156.4, self.close=23710.1, self.high=24231.7, self.low=23621.0, self.vol=185020.734, self.amt=4423616270.82032 
2023-02-23 00:00:02,289:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677081599, self.tradeDate='20230222', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24156.4, self.close=23710.1, self.high=24231.7, self.low=23621.0, self.vol=185020.734, self.amt=4423616270.82032 
127.0.0.1 - - [23/Feb/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-02-23 00:00:02,326:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230222   040000    075959  ...  105687.690  2.571925e+09 -0.006677
722  20230222   080000    115959  ...  128324.856  3.100163e+09 -0.010007
723  20230222   120000    155959  ...   84541.648  2.033516e+09 -0.005752
724  20230222   160000    195959  ...   93248.828  2.242632e+09  0.004023
725  20230222   200000    235959  ...  185020.734  4.423616e+09 -0.018475

[5 rows x 11 columns]
2023-02-23 00:00:04,795:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230222   040000    075959  1677023999  ...    721  0.037081 -1.436210    -1.0
722  20230222   080000    115959  1677038399  ...    722  0.130064 -1.182392    -1.0
723  20230222   120000    155959  1677052799  ...    723  0.211909 -0.964276    -1.0
724  20230222   160000    195959  1677067199  ...    724  0.289427 -0.762059    -1.0
725  20230222   200000    235959  1677081599  ...    725  0.330927 -0.651380    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '36.465', 'enterprice': '24934.8', 'countrevence': '0', 'unrealprofit': '44892.0615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23703.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


