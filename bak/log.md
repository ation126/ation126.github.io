# 20230302 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27196
self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23598.2, self.close=23594.8, self.high=23626.2, self.low=23547.3, self.vol=3806.587, self.amt=89774098.705 
127.0.0.1 - - [02/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:20:01,613:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230301   235500    235959  ...         0.0        0.0       0
5760  20230302   000000    000459  ...         0.0        0.0       0
5761  20230302   000500    000959  ...         0.0        0.0       0
5762  20230302   001000    001459  ...         0.0        0.0       0
5763  20230302   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 00:20:01,615:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23598.2, self.close=23594.8, self.high=23626.2, self.low=23547.3, self.vol=3806.587, self.amt=89774098.705, ukdf['pct'].iloc[-1]=-0.000148 , ukdf['amount'].iloc[-1]=89774098.705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-425173.528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23594.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27197
self.closeSec=1677687899, self.tradeDate='20230302', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23594.9, self.close=23630.1, self.high=23638.4, self.low=23567.0, self.vol=2672.735, self.amt=63103320.7671 
127.0.0.1 - - [02/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:25:01,611:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230302   000000    000459  ...         0.0        0.0       0
5761  20230302   000500    000959  ...         0.0        0.0       0
5762  20230302   001000    001459  ...         0.0        0.0       0
5763  20230302   001500    001959  ...         0.0        0.0       0
5764  20230302   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 00:25:01,612:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677687899, self.tradeDate='20230302', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23594.9, self.close=23630.1, self.high=23638.4, self.low=23567.0, self.vol=2672.735, self.amt=63103320.7671, ukdf['pct'].iloc[-1]=0.001496 , ukdf['amount'].iloc[-1]=63103320.7671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-427291.7232', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23630', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=116, self.factor=0.41782418058615184, self.count=27762 

self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23598.2, self.close=23594.8, self.high=23626.2, self.low=23547.3 
2023-03-02 00:20:01,547:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23598.2, self.close=23594.8, self.high=23626.2, self.low=23547.3   
2023-03-02 00:20:01,583:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230301   235500    235959  1677686399  ...  23682.0  0.000317   1727    5
1440  20230302   000000    000459  1677686699  ...  23664.8 -0.001489   1440    0
1441  20230302   000500    000959  1677686999  ...  23601.6 -0.002493   1441    1
1442  20230302   001000    001459  1677687299  ...  23543.8 -0.000432   1442    2
1443  20230302   001500    001959  1677687599  ...  23547.3 -0.000148   1443    3

[5 rows x 11 columns]
2023-03-02 00:20:01,595:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=116, self.factor=0.41782418058615184, self.count=27763 

self.closeSec=1677687899, self.tradeDate='20230302', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23594.9, self.close=23630.1, self.high=23638.4, self.low=23567.0 
2023-03-02 00:25:01,520:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677687899, self.tradeDate='20230302', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23594.9, self.close=23630.1, self.high=23638.4, self.low=23567.0   
127.0.0.1 - - [02/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:25:01,578:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230302   000000    000459  1677686699  ...  23664.8 -0.001489   1440    0
1441  20230302   000500    000959  1677686999  ...  23601.6 -0.002493   1441    1
1442  20230302   001000    001459  1677687299  ...  23543.8 -0.000432   1442    2
1443  20230302   001500    001959  1677687599  ...  23547.3 -0.000148   1443    3
1444  20230302   002000    002459  1677687899  ...  23567.0  0.001496   1444    4

[5 rows x 11 columns]
2023-03-02 00:25:01,579:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-02 00:00:38,412:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230301    212959  23719.0  ...  48.750000  0.535386  0.332278
5803  20230301    215959  23641.0  ...  49.166667  0.544547  0.332224
5804  20230301    222959  23686.4  ...  49.166667  0.542826  0.332685
5805  20230301    225959  23678.7  ...  48.750000  0.541304  0.333563
5806  20230301    232959  23671.9  ...  49.166667  0.541805  0.334212

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-03-02 00:00:38,589:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.476292  0.523708       1  ...  0.859362   1.0    0.0  0.965897
540     0  0.506736  0.493264       0  ...  0.859079   1.0    0.0  0.965579
541     1  0.496390  0.503610       0  ...  0.858832   1.0    0.0  0.965302
542     1  0.491218  0.508782       1  ...  0.858926   1.0    0.0  0.965408
543     1  0.499376  0.500624       1  ...  0.859953   1.0    0.0  0.966562

[5 rows x 10 columns]
2023-03-02 00:00:38,629:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.474440  0.525560       1  ...  0.827008   1.0    0.0  0.960550
46     0  0.505564  0.494436       0  ...  0.826736   1.0    0.0  0.961376
47     1  0.495160  0.504840       0  ...  0.826498   1.0    0.0  0.961100
48     1  0.490585  0.509415       1  ...  0.858926   1.0    0.0  0.963879
49     1  0.499376  0.500624       1  ...  0.859953   1.0    0.0  0.966562

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.563', 'enterprice': '23438.8', 'countrevence': '0', 'unrealprofit': '8223.35922872299', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23691.33690473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [02/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-02 00:00:03,394:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41862F1677686402738I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677686403026389, 'quantity': '43.394', 'price': '23702.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677686402380, 'updatetime': 1677686403026, 'tradetype': 'usdt', 'selfid': 41862, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677686403026, 'clientorderid': '41862F1677686402738I0L59', 'price': '23702.8', 'quantity': '43.394', 'commission': '1028.5593032', 'commissionasset': 'USDT', 'tradetime': 1677686403026, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677686403026}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13880 

self.closeSec=1677686999, self.tradeDate='20230302', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23702.9', self.close='23608.5'
127.0.0.1 - - [02/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:10:01,632:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677686999, self.tradeDate='20230302', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23702.9', self.close='23608.5'
2023-03-02 00:10:01,697:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230301   232000    232959  1677684599    23661  23674.5  0.000571
573  20230301   233000    233959  1677685199  23674.4  23725.6  0.002158
574  20230301   234000    234959  1677685799  23725.6  23732.3  0.000282
575  20230301   235000    235959  1677686399  23732.4  23702.8 -0.001243
576  20230302   000000    000959  1677686999  23702.9  23608.5 -0.003978
2023-03-02 00:10:01,699:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13881 

self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23608.5', self.close='23594.9'
127.0.0.1 - - [02/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:20:01,637:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23608.5', self.close='23594.9'
2023-03-02 00:20:01,652:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230301   233000    233959  1677685199  23674.4  23725.6  0.002158
574  20230301   234000    234959  1677685799  23725.6  23732.3  0.000282
575  20230301   235000    235959  1677686399  23732.4  23702.8 -0.001243
576  20230302   000000    000959  1677686999  23702.9  23608.5 -0.003978
577  20230302   001000    001959  1677687599  23608.5  23594.9 -0.000576
2023-03-02 00:20:01,653:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-02 00:00:03,124:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41861F1677686402712I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677686402819589, 'quantity': '41.437', 'price': '23702.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677686402306, 'updatetime': 1677686402819, 'tradetype': 'usdt', 'selfid': 41861, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677686402819, 'clientorderid': '41861F1677686402712I0L57', 'price': '23702.8', 'quantity': '41.437', 'commission': '982.1729236', 'commissionasset': 'USDT', 'tradetime': 1677686402819, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677686402819}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [02/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [02/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13881 

self.closeSec=1677686999, self.tradeDate='20230302', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23702.9', self.close='23608.5'
2023-03-02 00:10:01,646:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677686999, self.tradeDate='20230302', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23702.9', self.close='23608.5'
2023-03-02 00:10:01,727:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230301   232000    232959  1677684599    23661  23674.5
17421  20230301   233000    233959  1677685199  23674.4  23725.6
17422  20230301   234000    234959  1677685799  23725.6  23732.3
17423  20230301   235000    235959  1677686399  23732.4  23702.8
17424  20230302   000000    000959  1677686999  23702.9  23608.5
2023-03-02 00:10:01,727:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13882 

self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23608.5', self.close='23594.9'
127.0.0.1 - - [02/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:20:01,657:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23608.5', self.close='23594.9'
2023-03-02 00:20:01,702:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230301   233000    233959  1677685199  23674.4  23725.6
17422  20230301   234000    234959  1677685799  23725.6  23732.3
17423  20230301   235000    235959  1677686399  23732.4  23702.8
17424  20230302   000000    000959  1677686999  23702.9  23608.5
17425  20230302   001000    001959  1677687599  23608.5  23594.9
2023-03-02 00:20:01,710:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [02/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-02 00:00:03,643:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41863F1677686402892I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677686403350692, 'quantity': '50.211', 'price': '23702.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677686402454, 'updatetime': 1677686403350, 'tradetype': 'usdt', 'selfid': 41863, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677686403350, 'clientorderid': '41863F1677686402892I0L2', 'price': '23702.9', 'quantity': '50.211', 'commission': '1190.1463119', 'commissionasset': 'USDT', 'tradetime': 1677686403350, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677686403350}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13881 

self.closeSec=1677686999, self.tradeDate='20230302', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23702.9', self.close='23608.5'
127.0.0.1 - - [02/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:10:01,639:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677686999, self.tradeDate='20230302', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23702.9', self.close='23608.5'
2023-03-02 00:10:01,718:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230301   232000    232959  1677684599    23661  23674.5
12237  20230301   233000    233959  1677685199  23674.4  23725.6
12238  20230301   234000    234959  1677685799  23725.6  23732.3
12239  20230301   235000    235959  1677686399  23732.4  23702.8
12240  20230302   000000    000959  1677686999  23702.9  23608.5
2023-03-02 00:10:01,718:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [02/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13882 

self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23608.5', self.close='23594.9'
2023-03-02 00:20:01,655:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23608.5', self.close='23594.9'
2023-03-02 00:20:01,686:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230301   233000    233959  1677685199  23674.4  23725.6
12238  20230301   234000    234959  1677685799  23725.6  23732.3
12239  20230301   235000    235959  1677686399  23732.4  23702.8
12240  20230302   000000    000959  1677686999  23702.9  23608.5
12241  20230302   001000    001959  1677687599  23608.5  23594.9
2023-03-02 00:20:01,688:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23194
self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23598.2, self.close=23594.8, self.high=23626.2, self.low=23547.3, self.vol=3806.587, self.amt=89774098.705 
127.0.0.1 - - [02/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:20:01,608:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230301   235500    235959  ...         0.0        0.0       0
5760  20230302   000000    000459  ...         0.0        0.0       0
5761  20230302   000500    000959  ...         0.0        0.0       0
5762  20230302   001000    001459  ...         0.0        0.0       0
5763  20230302   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 00:20:01,611:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677687599, self.tradeDate='20230302', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23598.2, self.close=23594.8, self.high=23626.2, self.low=23547.3, self.vol=3806.587, self.amt=89774098.705, ukdf['pct'].iloc[-1]=-0.000148 , ukdf['amount'].iloc[-1]=89774098.705, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [02/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23195
self.closeSec=1677687899, self.tradeDate='20230302', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23594.9, self.close=23630.1, self.high=23638.4, self.low=23567.0, self.vol=2672.735, self.amt=63103320.7671 
2023-03-02 00:25:01,607:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230302   000000    000459  ...         0.0        0.0       0
5761  20230302   000500    000959  ...         0.0        0.0       0
5762  20230302   001000    001459  ...         0.0        0.0       0
5763  20230302   001500    001959  ...         0.0        0.0       0
5764  20230302   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-02 00:25:01,607:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677687899, self.tradeDate='20230302', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23594.9, self.close=23630.1, self.high=23638.4, self.low=23567.0, self.vol=2672.735, self.amt=63103320.7671, ukdf['pct'].iloc[-1]=0.001496 , ukdf['amount'].iloc[-1]=63103320.7671, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230301   120000    155959  1677657599  ...    723  0.676162  0.028418     NaN
724  20230301   160000    195959  1677671999  ...    724  0.747762  0.198074     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '26475.7583', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23736.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=578
self.closeSec=1677686399, self.tradeDate='20230301', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23736.9, self.close=23702.8, self.high=23880.0, self.low=23558.0, self.vol=137452.515, self.amt=3257163738.82774 
127.0.0.1 - - [02/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-02 00:00:01,788:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677686399, self.tradeDate='20230301', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23736.9, self.close=23702.8, self.high=23880.0, self.low=23558.0, self.vol=137452.515, self.amt=3257163738.82774 
2023-03-02 00:00:01,824:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230301   040000    075959  ...  100091.272  2.318269e+09 -0.005221
722  20230301   080000    115959  ...   94869.432  2.207722e+09  0.013057
723  20230301   120000    155959  ...  119744.837  2.837105e+09  0.011864
724  20230301   160000    195959  ...   87997.318  2.094237e+09  0.001147
725  20230301   200000    235959  ...  137452.515  3.257164e+09 -0.001432

[5 rows x 11 columns]
2023-03-02 00:00:05,030:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230301   040000    075959  1677628799  ...    721  0.635610 -0.042715     NaN
722  20230301   080000    115959  1677643199  ...    722  0.593669 -0.166411     NaN
723  20230301   120000    155959  1677657599  ...    723  0.676162  0.028418     NaN
724  20230301   160000    195959  1677671999  ...    724  0.747762  0.198074     NaN
725  20230301   200000    235959  1677686399  ...    725  0.744879  0.171695     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '25054.326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23702.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


