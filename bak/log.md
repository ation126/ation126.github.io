# 20230528 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3904
self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26671.0, self.close=26654.9, self.high=26671.1, self.low=26648.4, self.vol=658.527, self.amt=17553740.083 
127.0.0.1 - - [28/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 00:20:07,027:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230527   235500    235959  ...         0.0        0.0       0
5760  20230528   000000    000459  ...         0.0        0.0       0
5761  20230528   000500    000959  ...         0.0        0.0       0
5762  20230528   001000    001459  ...         0.0        0.0       0
5763  20230528   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 00:20:07,077:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26671.0, self.close=26654.9, self.high=26671.1, self.low=26648.4, self.vol=658.527, self.amt=17553740.083, ukdf['pct'].iloc[-1]=-0.000604 , ukdf['amount'].iloc[-1]=17553740.083, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2918.99780279184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26655.29223016', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3905
self.closeSec=1685204699, self.tradeDate='20230528', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26654.8, self.close=26652.2, self.high=26658.4, self.low=26634.7, self.vol=416.133, self.amt=11088493.3176 
2023-05-28 00:25:00,825:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230528   000000    000459  ...         0.0        0.0       0
5761  20230528   000500    000959  ...         0.0        0.0       0
5762  20230528   001000    001459  ...         0.0        0.0       0
5763  20230528   001500    001959  ...         0.0        0.0       0
5764  20230528   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 00:25:00,834:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685204699, self.tradeDate='20230528', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26654.8, self.close=26652.2, self.high=26658.4, self.low=26634.7, self.vol=416.133, self.amt=11088493.3176, ukdf['pct'].iloc[-1]=-0.000101 , ukdf['amount'].iloc[-1]=11088493.3176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '2963.4528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26652.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26671.0, self.close=26654.9, self.high=26671.1, self.low=26648.4 
127.0.0.1 - - [28/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 00:20:04,407:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26671.0, self.close=26654.9, self.high=26671.1, self.low=26648.4   
2023-05-28 00:20:05,897:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230527   235500    235959  1685203199  ...  26663.0  0.000698   1727    5
1440  20230528   000000    000459  1685203499  ...  26674.3 -0.000296   1440    0
1441  20230528   000500    000959  1685203799  ...  26669.6  0.000229   1441    1
1442  20230528   001000    001459  1685204099  ...  26668.0 -0.000352   1442    2
1443  20230528   001500    001959  1685204399  ...  26648.4 -0.000604   1443    3

[5 rows x 11 columns]
2023-05-28 00:20:05,907:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=51, self.factor=0.36824088451626175, self.count=3907 

self.closeSec=1685204699, self.tradeDate='20230528', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26654.8, self.close=26652.2, self.high=26658.4, self.low=26634.7 
127.0.0.1 - - [28/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-28 00:25:00,764:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685204699, self.tradeDate='20230528', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26654.8, self.close=26652.2, self.high=26658.4, self.low=26634.7   
2023-05-28 00:25:00,811:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230528   000000    000459  1685203499  ...  26674.3 -0.000296   1440    0
1441  20230528   000500    000959  1685203799  ...  26669.6  0.000229   1441    1
1442  20230528   001000    001459  1685204099  ...  26668.0 -0.000352   1442    2
1443  20230528   001500    001959  1685204399  ...  26648.4 -0.000604   1443    3
1444  20230528   002000    002459  1685204699  ...  26634.7 -0.000101   1444    4

[5 rows x 11 columns]
2023-05-28 00:25:00,811:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-28 00:00:36,735:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230527    212959  26699.9  ...  47.083333  0.550626  0.457396
5803  20230527    215959  26757.1  ...  46.666667  0.500998  0.472914
5804  20230527    222959  26617.8  ...  47.083333  0.522710  0.471444
5805  20230527    225959  26686.6  ...  46.666667  0.513478  0.476531
5806  20230527    232959  26658.8  ...  46.666667  0.511694  0.482530

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-05-28 00:00:36,893:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.514149  0.485851       0  ...  0.903617   1.0    0.0  0.977137
540     1  0.467145  0.532855       1  ...  0.905956   1.0    0.0  0.979666
541     0  0.509021  0.490979       0  ...  0.905009   1.0    0.0  0.978642
542     1  0.487115  0.512885       0  ...  0.904825   1.0    0.0  0.978444
543     1  0.491031  0.508969       1  ...  0.905803   1.0    0.0  0.979501

[5 rows x 10 columns]
2023-05-28 00:00:36,926:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514228  0.485772       0  ...  0.903617   1.0    0.0  0.984022
46     1  0.467250  0.532750       1  ...  0.905956   1.0    0.0  0.986526
47     0  0.509394  0.490606       0  ...  0.905009   1.0    0.0  0.985494
48     1  0.487262  0.512738       0  ...  0.904825   1.0    0.0  0.980828
49     1  0.491031  0.508969       1  ...  0.905803   1.0    0.0  0.979501

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '-2803.15943867726', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26684.24507143', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-28 00:00:04,143:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42274F1685203203515I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685203203891849, 'quantity': '25.828', 'price': '26683.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685203202620, 'updatetime': 1685203203891, 'tradetype': 'usdt', 'selfid': 42274, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685203203891, 'clientorderid': '42274F1685203203515I0L59', 'price': '26683.5', 'quantity': '25.828', 'commission': '689.181438', 'commissionasset': 'USDT', 'tradetime': 1685203203891, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685203203891}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1952 

self.closeSec=1685203799, self.tradeDate='20230528', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26682.2', self.close='26680.4'
127.0.0.1 - - [28/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-28 00:10:01,140:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685203799, self.tradeDate='20230528', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26682.2', self.close='26680.4'
2023-05-28 00:10:01,229:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230527   232000    232959  1685201399  26653.4  26653.4 -0.000004
573  20230527   233000    233959  1685201999  26653.4  26658.1  0.000176
574  20230527   234000    234959  1685202599  26658.1  26660.5  0.000090
575  20230527   235000    235959  1685203199  26660.5  26682.1  0.000810
576  20230528   000000    000959  1685203799  26682.2  26680.4 -0.000064
2023-05-28 00:10:01,229:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1953 

self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26680.5', self.close='26654.9'
127.0.0.1 - - [28/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 00:20:06,957:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26680.5', self.close='26654.9'
2023-05-28 00:20:07,539:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230527   233000    233959  1685201999  26653.4  26658.1  0.000176
574  20230527   234000    234959  1685202599  26658.1  26660.5  0.000090
575  20230527   235000    235959  1685203199  26660.5  26682.1  0.000810
576  20230528   000000    000959  1685203799  26682.2  26680.4 -0.000064
577  20230528   001000    001959  1685204399  26680.5  26654.9 -0.000956
2023-05-28 00:20:07,546:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-28 00:00:02,098:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-28 00:00:02,214:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5280000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230527, closeTime:235959, close:26682.1, total:983849.5331272, pct_pre:-0.0029552858893504563, thd:0.25329518738873136, side:sell 
127.0.0.1 - - [28/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1955 

self.closeSec=1685203799, self.tradeDate='20230528', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26682.2', self.close='26680.4'
2023-05-28 00:10:01,197:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685203799, self.tradeDate='20230528', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26682.2', self.close='26680.4'
2023-05-28 00:10:01,241:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230527   232000    232959  1685201399  26653.4  26653.4
17421  20230527   233000    233959  1685201999  26653.4  26658.1
17422  20230527   234000    234959  1685202599  26658.1  26660.5
17423  20230527   235000    235959  1685203199  26660.5  26682.1
17424  20230528   000000    000959  1685203799  26682.2  26680.4
2023-05-28 00:10:01,241:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1956 

self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26680.5', self.close='26654.9'
127.0.0.1 - - [28/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 00:20:08,538:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26680.5', self.close='26654.9'
2023-05-28 00:20:08,655:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230527   233000    233959  1685201999  26653.4  26658.1
17422  20230527   234000    234959  1685202599  26658.1  26660.5
17423  20230527   235000    235959  1685203199  26660.5  26682.1
17424  20230528   000000    000959  1685203799  26682.2  26680.4
17425  20230528   001000    001959  1685204399  26680.5  26654.9
2023-05-28 00:20:08,656:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-28 00:00:04,441:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42275F1685203203541I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685203203905591, 'quantity': '46.526', 'price': '26683.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685203202596, 'updatetime': 1685203203905, 'tradetype': 'usdt', 'selfid': 42275, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685203203905, 'clientorderid': '42275F1685203203541I0L2', 'price': '26683.5', 'quantity': '46.526', 'commission': '1241.476521', 'commissionasset': 'USDT', 'tradetime': 1685203203905, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685203203905}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1955 

self.closeSec=1685203799, self.tradeDate='20230528', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26682.2', self.close='26680.4'
2023-05-28 00:10:01,163:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685203799, self.tradeDate='20230528', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26682.2', self.close='26680.4'
2023-05-28 00:10:01,245:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230527   232000    232959  1685201399  26653.4  26653.4
12237  20230527   233000    233959  1685201999  26653.4  26658.1
12238  20230527   234000    234959  1685202599  26658.1  26660.5
12239  20230527   235000    235959  1685203199  26660.5  26682.1
12240  20230528   000000    000959  1685203799  26682.2  26680.4
2023-05-28 00:10:01,246:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1956 

self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26680.5', self.close='26654.9'
127.0.0.1 - - [28/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 00:20:08,269:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26680.5', self.close='26654.9'
2023-05-28 00:20:08,499:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230527   233000    233959  1685201999  26653.4  26658.1
12238  20230527   234000    234959  1685202599  26658.1  26660.5
12239  20230527   235000    235959  1685203199  26660.5  26682.1
12240  20230528   000000    000959  1685203799  26682.2  26680.4
12241  20230528   001000    001959  1685204399  26680.5  26654.9
2023-05-28 00:20:08,506:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3904
self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26671.0, self.close=26654.9, self.high=26671.1, self.low=26648.4, self.vol=658.527, self.amt=17553740.083 
127.0.0.1 - - [28/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 00:20:07,016:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230527   235500    235959  ...         0.0        0.0       0
5760  20230528   000000    000459  ...         0.0        0.0       0
5761  20230528   000500    000959  ...         0.0        0.0       0
5762  20230528   001000    001459  ...         0.0        0.0       0
5763  20230528   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 00:20:07,057:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685204399, self.tradeDate='20230528', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26671.0, self.close=26654.9, self.high=26671.1, self.low=26648.4, self.vol=658.527, self.amt=17553740.083, ukdf['pct'].iloc[-1]=-0.000604 , ukdf['amount'].iloc[-1]=17553740.083, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-7008.79527962744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26655.29223016', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3905
self.closeSec=1685204699, self.tradeDate='20230528', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26654.8, self.close=26652.2, self.high=26658.4, self.low=26634.7, self.vol=416.133, self.amt=11088493.3176 
127.0.0.1 - - [28/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-28 00:25:00,833:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230528   000000    000459  ...         0.0        0.0       0
5761  20230528   000500    000959  ...         0.0        0.0       0
5762  20230528   001000    001459  ...         0.0        0.0       0
5763  20230528   001500    001959  ...         0.0        0.0       0
5764  20230528   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 00:25:00,834:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685204699, self.tradeDate='20230528', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26654.8, self.close=26652.2, self.high=26658.4, self.low=26634.7, self.vol=416.133, self.amt=11088493.3176, ukdf['pct'].iloc[-1]=-0.000101 , ukdf['amount'].iloc[-1]=11088493.3176, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-7127.3579', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26652.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230527   120000    155959  1685174399  ...    723  0.565573  0.949284     1.0
724  20230527   160000    195959  1685188799  ...    724  0.484661  0.477806     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '31027.82170098975', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26689.79969775', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [28/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=81
self.closeSec=1685203199, self.tradeDate='20230527', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26687.6, self.close=26682.1, self.high=26774.9, self.low=26528.6, self.vol=47080.958, self.amt=1255307046.5825 
2023-05-28 00:00:01,673:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685203199, self.tradeDate='20230527', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26687.6, self.close=26682.1, self.high=26774.9, self.low=26528.6, self.vol=47080.958, self.amt=1255307046.5825 
2023-05-28 00:00:01,727:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230527   040000    075959  ...  18689.388  4.995218e+08 -0.002441
722  20230527   080000    115959  ...  21434.056  5.720833e+08  0.001858
723  20230527   120000    155959  ...  15097.708  4.035509e+08 -0.000905
724  20230527   160000    195959  ...  19863.179  5.300554e+08 -0.001033
725  20230527   200000    235959  ...  47080.958  1.255307e+09 -0.000210

[5 rows x 11 columns]
2023-05-28 00:00:04,125:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230527   040000    075959  1685145599  ...    721  0.595322  1.166378     1.0
722  20230527   080000    115959  1685159999  ...    722  0.601728  1.176548     1.0
723  20230527   120000    155959  1685174399  ...    723  0.565573  0.949284     1.0
724  20230527   160000    195959  1685188799  ...    724  0.484661  0.477806     NaN
725  20230527   200000    235959  1685203199  ...    725  0.462421  0.346905     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '30679.7697', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26683.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


