# 20230708 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15712
self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30395.6, self.close=30346.0, self.high=30395.7, self.low=30345.8, self.vol=936.625, self.amt=28442722.7482 
127.0.0.1 - - [08/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 00:20:06,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230707   235500    235959  ...         0.0        0.0       0
5760  20230708   000000    000459  ...         0.0        0.0       0
5761  20230708   000500    000959  ...         0.0        0.0       0
5762  20230708   001000    001459  ...         0.0        0.0       0
5763  20230708   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 00:20:06,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30395.6, self.close=30346.0, self.high=30395.7, self.low=30345.8, self.vol=936.625, self.amt=28442722.7482, ukdf['pct'].iloc[-1]=-0.001635 , ukdf['amount'].iloc[-1]=28442722.7482, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48544.6434', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30350.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15713
self.closeSec=1688747099, self.tradeDate='20230708', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30346.0, self.close=30316.6, self.high=30369.1, self.low=30298.8, self.vol=2101.116, self.amt=63716417.7385 
2023-07-08 00:25:00,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230708   000000    000459  ...         0.0        0.0       0
5761  20230708   000500    000959  ...         0.0        0.0       0
5762  20230708   001000    001459  ...         0.0        0.0       0
5763  20230708   001500    001959  ...         0.0        0.0       0
5764  20230708   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 00:25:00,784:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688747099, self.tradeDate='20230708', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30346.0, self.close=30316.6, self.high=30369.1, self.low=30298.8, self.vol=2101.116, self.amt=63716417.7385, ukdf['pct'].iloc[-1]=-0.000969 , ukdf['amount'].iloc[-1]=63716417.7385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48066.9816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30316.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30395.6, self.close=30346.0, self.high=30395.7, self.low=30345.8 
127.0.0.1 - - [08/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 00:20:04,513:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30395.6, self.close=30346.0, self.high=30395.7, self.low=30345.8   
2023-07-08 00:20:05,863:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230707   235500    235959  1688745599  ...  30350.2  0.000768   1727    5
1440  20230708   000000    000459  1688745899  ...  30356.9 -0.000435   1440    0
1441  20230708   000500    000959  1688746199  ...  30347.0 -0.000079   1441    1
1442  20230708   001000    001459  1688746499  ...  30359.9  0.001179   1442    2
1443  20230708   001500    001959  1688746799  ...  30345.8 -0.001635   1443    3

[5 rows x 11 columns]
2023-07-08 00:20:05,873:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6029772801768181, self.count=15715 

self.closeSec=1688747099, self.tradeDate='20230708', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30346.0, self.close=30316.6, self.high=30369.1, self.low=30298.8 
127.0.0.1 - - [08/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-08 00:25:00,737:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688747099, self.tradeDate='20230708', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30346.0, self.close=30316.6, self.high=30369.1, self.low=30298.8   
2023-07-08 00:25:00,762:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230708   000000    000459  1688745899  ...  30356.9 -0.000435   1440    0
1441  20230708   000500    000959  1688746199  ...  30347.0 -0.000079   1441    1
1442  20230708   001000    001459  1688746499  ...  30359.9  0.001179   1442    2
1443  20230708   001500    001959  1688746799  ...  30345.8 -0.001635   1443    3
1444  20230708   002000    002459  1688747099  ...  30298.8 -0.000969   1444    4

[5 rows x 11 columns]
2023-07-08 00:25:00,762:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-08 00:00:21,826:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230707    212959  30190.4  ...  48.750000  0.485224  0.567733
5803  20230707    215959  30269.0  ...  48.750000  0.502132  0.531925
5804  20230707    222959  30367.2  ...  48.333333  0.494370  0.506134
5805  20230707    225959  30314.5  ...  48.333333  0.506923  0.475450
5806  20230707    232959  30395.6  ...  48.333333  0.496343  0.452375

[5 rows x 33 columns]
0.5422794117647058
acc is : 0.5422794117647058
2023-07-08 00:00:21,958:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.538896  0.461104       1  ...  0.974895   1.0    0.0  0.999069
540     0  0.550027  0.449973       0  ...  0.973415   1.0    0.0  0.997552
541     0  0.519838  0.480162       1  ...  0.975803   1.0    0.0  1.000000
542     0  0.537361  0.462639       0  ...  0.973794   1.0    0.0  0.997940
543     1  0.495843  0.504157       1  ...  0.975155   1.0    0.0  0.999335

[5 rows x 10 columns]
2023-07-08 00:00:21,981:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.538327  0.461673       1  ...  0.979946   1.0    0.0  1.002764
46     0  0.548769  0.451231       0  ...  0.978459   1.0    0.0  0.994960
47     0  0.518239  0.481761       1  ...  0.963900   1.0    0.0  0.997401
48     0  0.536700  0.463300       0  ...  0.973794   1.0    0.0  0.997396
49     1  0.495843  0.504157       1  ...  0.975155   1.0    0.0  0.999335

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '7212.58906516176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30378.45299084', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [08/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-08 00:00:04,556:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42553F1688745603665I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688745604049419, 'quantity': '25.557', 'price': '30375.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688745602651, 'updatetime': 1688745604049, 'tradetype': 'usdt', 'selfid': 42553, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688745604049, 'clientorderid': '42553F1688745603665I0L59', 'price': '30375.5', 'quantity': '25.557', 'commission': '776.3066535', 'commissionasset': 'USDT', 'tradetime': 1688745604049, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688745604049}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7856 

self.closeSec=1688746199, self.tradeDate='20230708', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30375.5', self.close='30359.9'
2023-07-08 00:10:01,155:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688746199, self.tradeDate='20230708', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30375.5', self.close='30359.9'
2023-07-08 00:10:01,168:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230707   232000    232959  1688743799    30315    30333  0.000594
573  20230707   233000    233959  1688744399  30333.1  30306.1 -0.000887
574  20230707   234000    234959  1688744999  30306.1    30351  0.001482
575  20230707   235000    235959  1688745599    30351  30375.4  0.000804
576  20230708   000000    000959  1688746199  30375.5  30359.9 -0.000510
2023-07-08 00:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7857 

self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30360', self.close='30346'
127.0.0.1 - - [08/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 00:20:06,802:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30360', self.close='30346'
2023-07-08 00:20:07,403:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230707   233000    233959  1688744399  30333.1  30306.1 -0.000887
574  20230707   234000    234959  1688744999  30306.1    30351  0.001482
575  20230707   235000    235959  1688745599    30351  30375.4  0.000804
576  20230708   000000    000959  1688746199  30375.5  30359.9 -0.000510
577  20230708   001000    001959  1688746799    30360    30346 -0.000458
2023-07-08 00:20:07,413:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-08 00:00:02,132:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-08 00:00:02,269:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7080000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230707, closeTime:235959, close:30375.4, total:993267.8008712, pct_pre:-0.009757797525701273, thd:0.017707312940933417, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7859 

self.closeSec=1688746199, self.tradeDate='20230708', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30375.5', self.close='30359.9'
2023-07-08 00:10:01,142:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688746199, self.tradeDate='20230708', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30375.5', self.close='30359.9'
127.0.0.1 - - [08/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-08 00:10:01,149:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230707   232000    232959  1688743799    30315    30333
17421  20230707   233000    233959  1688744399  30333.1  30306.1
17422  20230707   234000    234959  1688744999  30306.1    30351
17423  20230707   235000    235959  1688745599    30351  30375.4
17424  20230708   000000    000959  1688746199  30375.5  30359.9
2023-07-08 00:10:01,149:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7860 

self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30360', self.close='30346'
127.0.0.1 - - [08/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 00:20:08,185:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30360', self.close='30346'
2023-07-08 00:20:08,369:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230707   233000    233959  1688744399  30333.1  30306.1
17422  20230707   234000    234959  1688744999  30306.1    30351
17423  20230707   235000    235959  1688745599    30351  30375.4
17424  20230708   000000    000959  1688746199  30375.5  30359.9
17425  20230708   001000    001959  1688746799    30360    30346
2023-07-08 00:20:08,370:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [08/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-08 00:00:04,913:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42554F1688745603913I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688745604348405, 'quantity': '38.03', 'price': '30375.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688745602880, 'updatetime': 1688745604348, 'tradetype': 'usdt', 'selfid': 42554, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688745604348, 'clientorderid': '42554F1688745603913I0L2', 'price': '30375.5', 'quantity': '38.03', 'commission': '1155.180265', 'commissionasset': 'USDT', 'tradetime': 1688745604348, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688745604348}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [08/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7859 

self.closeSec=1688746199, self.tradeDate='20230708', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30375.5', self.close='30359.9'
2023-07-08 00:10:01,145:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688746199, self.tradeDate='20230708', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30375.5', self.close='30359.9'
2023-07-08 00:10:01,162:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230707   232000    232959  1688743799    30315    30333
12237  20230707   233000    233959  1688744399  30333.1  30306.1
12238  20230707   234000    234959  1688744999  30306.1    30351
12239  20230707   235000    235959  1688745599    30351  30375.4
12240  20230708   000000    000959  1688746199  30375.5  30359.9
2023-07-08 00:10:01,162:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7860 

self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30360', self.close='30346'
127.0.0.1 - - [08/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-08 00:20:07,825:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30360', self.close='30346'
2023-07-08 00:20:08,174:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230707   233000    233959  1688744399  30333.1  30306.1
12238  20230707   234000    234959  1688744999  30306.1    30351
12239  20230707   235000    235959  1688745599    30351  30375.4
12240  20230708   000000    000959  1688746199  30375.5  30359.9
12241  20230708   001000    001959  1688746799    30360    30346
2023-07-08 00:20:08,176:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15712
self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30395.6, self.close=30346.0, self.high=30395.7, self.low=30345.8, self.vol=936.625, self.amt=28442722.7482 
127.0.0.1 - - [08/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-08 00:20:06,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230707   235500    235959  ...         0.0        0.0       0
5760  20230708   000000    000459  ...         0.0        0.0       0
5761  20230708   000500    000959  ...         0.0        0.0       0
5762  20230708   001000    001459  ...         0.0        0.0       0
5763  20230708   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 00:20:06,803:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688746799, self.tradeDate='20230708', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30395.6, self.close=30346.0, self.high=30395.7, self.low=30345.8, self.vol=936.625, self.amt=28442722.7482, ukdf['pct'].iloc[-1]=-0.001635 , ukdf['amount'].iloc[-1]=28442722.7482, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '130246.0588', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30350.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [08/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15713
self.closeSec=1688747099, self.tradeDate='20230708', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30346.0, self.close=30316.6, self.high=30369.1, self.low=30298.8, self.vol=2101.116, self.amt=63716417.7385 
2023-07-08 00:25:00,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230708   000000    000459  ...         0.0        0.0       0
5761  20230708   000500    000959  ...         0.0        0.0       0
5762  20230708   001000    001459  ...         0.0        0.0       0
5763  20230708   001500    001959  ...         0.0        0.0       0
5764  20230708   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-08 00:25:00,785:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688747099, self.tradeDate='20230708', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30346.0, self.close=30316.6, self.high=30369.1, self.low=30298.8, self.vol=2101.116, self.amt=63716417.7385, ukdf['pct'].iloc[-1]=-0.000969 , ukdf['amount'].iloc[-1]=63716417.7385, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '128972.1225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30316.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230707   120000    155959  1688716799  ...    723  0.431824  0.158499     NaN
724  20230707   160000    195959  1688731199  ...    724  0.496998  0.374479     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-34365.0220381205', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30103.11447619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=327
self.closeSec=1688745599, self.tradeDate='20230707', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30103.9, self.close=30375.4, self.high=30430.0, self.low=30012.1, self.vol=105396.246, self.amt=3188922325.91142 
127.0.0.1 - - [08/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-08 00:00:01,660:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688745599, self.tradeDate='20230707', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30103.9, self.close=30375.4, self.high=30430.0, self.low=30012.1, self.vol=105396.246, self.amt=3188922325.91142 
2023-07-08 00:00:01,695:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230707   040000    075959  ...   69574.823  2.092299e+09 -0.013643
722  20230707   080000    115959  ...   73967.626  2.215445e+09  0.008055
723  20230707   120000    155959  ...   54675.684  1.646778e+09 -0.004286
724  20230707   160000    195959  ...   37803.361  1.137748e+09  0.003701
725  20230707   200000    235959  ...  105396.246  3.188922e+09  0.009015

[5 rows x 11 columns]
2023-07-08 00:00:03,767:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230707   040000    075959  1688687999  ...    721  0.320735 -0.195696     NaN
722  20230707   080000    115959  1688702399  ...    722  0.387131  0.007713     NaN
723  20230707   120000    155959  1688716799  ...    723  0.431824  0.158499     NaN
724  20230707   160000    195959  1688731199  ...    724  0.496998  0.374479     NaN
725  20230707   200000    235959  1688745599  ...    725  0.530504  0.507898     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-19793.2086877525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30377.79521795', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


