# 20230526 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3328
self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26244.7, self.close=26270.3, self.high=26275.6, self.low=26235.0, self.vol=862.399, self.amt=22645847.0001 
127.0.0.1 - - [26/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 00:20:05,821:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230525   235500    235959  ...    0.081786   0.250861       0
5760  20230526   000000    000459  ...    0.081665   0.250795       0
5761  20230526   000500    000959  ...    0.081543   0.250727       0
5762  20230526   001000    001459  ...    0.081425   0.250667       0
5763  20230526   001500    001959  ...    0.081307   0.250604       0

[5 rows x 18 columns]
2023-05-26 00:20:05,832:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26244.7, self.close=26270.3, self.high=26275.6, self.low=26235.0, self.vol=862.399, self.amt=22645847.0001, ukdf['pct'].iloc[-1]=0.000972 , ukdf['amount'].iloc[-1]=22645847.0001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.08130668281905157, signal=0, value_std=0.2506042767058846 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8195.451', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26276.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3329
self.closeSec=1685031899, self.tradeDate='20230526', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26270.2, self.close=26259.2, self.high=26315.3, self.low=26250.8, self.vol=2391.693, self.amt=62869387.8882 
2023-05-26 00:25:00,886:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230526   000000    000459  ...    0.081665   0.250795       0
5761  20230526   000500    000959  ...    0.081543   0.250727       0
5762  20230526   001000    001459  ...    0.081425   0.250667       0
5763  20230526   001500    001959  ...    0.081307   0.250604       0
5764  20230526   002000    002459  ...    0.081187   0.250540       0

[5 rows x 18 columns]
2023-05-26 00:25:00,887:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685031899, self.tradeDate='20230526', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26270.2, self.close=26259.2, self.high=26315.3, self.low=26250.8, self.vol=2391.693, self.amt=62869387.8882, ukdf['pct'].iloc[-1]=-0.000423 , ukdf['amount'].iloc[-1]=62869387.8882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.08118690666548133, signal=0, value_std=0.2505400558460406 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8397.09948', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26261.92', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26244.7, self.close=26270.3, self.high=26275.6, self.low=26235.0 
127.0.0.1 - - [26/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 00:20:03,871:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26244.7, self.close=26270.3, self.high=26275.6, self.low=26235.0   
2023-05-26 00:20:04,992:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230525   235500    235959  1685030399  ...  26196.7  0.000664   1727    5
1440  20230526   000000    000459  1685030699  ...  26193.5  0.000744   1440    0
1441  20230526   000500    000959  1685030999  ...  26215.5 -0.000217   1441    1
1442  20230526   001000    001459  1685031299  ...  26230.6  0.000538   1442    2
1443  20230526   001500    001959  1685031599  ...  26235.0  0.000972   1443    3

[5 rows x 11 columns]
2023-05-26 00:20:04,993:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [26/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=4, self.factor=0.5755255804023657, self.count=3331 

self.closeSec=1685031899, self.tradeDate='20230526', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26270.2, self.close=26259.2, self.high=26315.3, self.low=26250.8 
2023-05-26 00:25:00,782:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685031899, self.tradeDate='20230526', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26270.2, self.close=26259.2, self.high=26315.3, self.low=26250.8   
2023-05-26 00:25:00,854:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230526   000000    000459  1685030699  ...  26193.5  0.000744   1440    0
1441  20230526   000500    000959  1685030999  ...  26215.5 -0.000217   1441    1
1442  20230526   001000    001459  1685031299  ...  26230.6  0.000538   1442    2
1443  20230526   001500    001959  1685031599  ...  26235.0  0.000972   1443    3
1444  20230526   002000    002459  1685031899  ...  26250.8 -0.000423   1444    4

[5 rows x 11 columns]
2023-05-26 00:25:00,854:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-26 00:00:36,878:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230525    212959  26392.0  ...  46.250000  0.468557  0.498423
5803  20230525    215959  26387.8  ...  45.833333  0.455766  0.482135
5804  20230525    222959  26327.0  ...  45.833333  0.467058  0.462065
5805  20230525    225959  26373.7  ...  45.416667  0.463736  0.444979
5806  20230525    232959  26357.8  ...  45.000000  0.442575  0.439885

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-05-26 00:00:37,075:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.514701  0.485299       0  ...  0.913910  -1.0    0.0  0.980890
540     0  0.502589  0.497411       1  ...  0.912289  -1.0    0.0  0.982630
541     0  0.518091  0.481909       0  ...  0.912835  -1.0    0.0  0.982042
542     1  0.494929  0.505071       0  ...  0.916441  -1.0    0.0  0.978163
543     1  0.472183  0.527817       0  ...  0.917729  -1.0    0.0  0.976788

[5 rows x 10 columns]
2023-05-26 00:00:37,116:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.514833  0.485167       0  ...  0.913910  -1.0    0.0  0.979427
46     0  0.502773  0.497227       1  ...  0.912289  -1.0    0.0  0.983030
47     0  0.518361  0.481639       0  ...  0.912835  -1.0    0.0  0.982441
48     1  0.495028  0.504972       0  ...  0.916441  -1.0    0.0  0.978571
49     1  0.472183  0.527817       0  ...  0.917729  -1.0    0.0  0.976788

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.287', 'enterprice': '26103', 'countrevence': '0', 'unrealprofit': '-3051.02869821048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26214.81253704', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [26/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-26 00:00:04,732:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42261F1685030404094I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685030404497958, 'quantity': '26.108', 'price': '26214.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685030403092, 'updatetime': 1685030404497, 'tradetype': 'usdt', 'selfid': 42261, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685030404497, 'clientorderid': '42261F1685030404094I0L59', 'price': '26214.2', 'quantity': '26.108', 'commission': '684.4003336', 'commissionasset': 'USDT', 'tradetime': 1685030404497, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685030404497}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1664 

self.closeSec=1685030999, self.tradeDate='20230526', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26216.9', self.close='26230.7'
2023-05-26 00:10:01,150:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685030999, self.tradeDate='20230526', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26216.9', self.close='26230.7'
2023-05-26 00:10:01,161:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230525   232000    232959  1685028599  26280.1  26253.8 -0.001001
573  20230525   233000    233959  1685029199  26253.8  26218.6 -0.001341
574  20230525   234000    234959  1685029799  26218.6  26198.8 -0.000755
575  20230525   235000    235959  1685030399    26200  26216.9  0.000691
576  20230526   000000    000959  1685030999  26216.9  26230.7  0.000526
2023-05-26 00:10:01,161:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1665 

self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26230.6', self.close='26270.3'
127.0.0.1 - - [26/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-26 00:20:05,841:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26230.6', self.close='26270.3'
2023-05-26 00:20:06,360:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230525   233000    233959  1685029199  26253.8  26218.6 -0.001341
574  20230525   234000    234959  1685029799  26218.6  26198.8 -0.000755
575  20230525   235000    235959  1685030399    26200  26216.9  0.000691
576  20230526   000000    000959  1685030999  26216.9  26230.7  0.000526
577  20230526   001000    001959  1685031599  26230.6  26270.3  0.001510
2023-05-26 00:20:06,360:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-26 00:00:02,474:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-26 00:00:02,618:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5260000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230525, closeTime:235959, close:26216.9, total:973579.8686232, pct_pre:-0.0005212078325742553, thd:0.32729343445234, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1667 

self.closeSec=1685030999, self.tradeDate='20230526', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26216.9', self.close='26230.7'
2023-05-26 00:10:01,175:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685030999, self.tradeDate='20230526', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26216.9', self.close='26230.7'
127.0.0.1 - - [26/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-26 00:10:01,202:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230525   232000    232959  1685028599  26280.1  26253.8
17421  20230525   233000    233959  1685029199  26253.8  26218.6
17422  20230525   234000    234959  1685029799  26218.6  26198.8
17423  20230525   235000    235959  1685030399    26200  26216.9
17424  20230526   000000    000959  1685030999  26216.9  26230.7
2023-05-26 00:10:01,203:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1668 

self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26230.6', self.close='26270.3'
127.0.0.1 - - [26/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-26 00:20:07,071:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26230.6', self.close='26270.3'
2023-05-26 00:20:07,163:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230525   233000    233959  1685029199  26253.8  26218.6
17422  20230525   234000    234959  1685029799  26218.6  26198.8
17423  20230525   235000    235959  1685030399    26200  26216.9
17424  20230526   000000    000959  1685030999  26216.9  26230.7
17425  20230526   001000    001959  1685031599  26230.6  26270.3
2023-05-26 00:20:07,163:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/May/2023 00:00:05] "POST / HTTP/1.1" 200 -
2023-05-26 00:00:05,095:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42262F1685030404116I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685030404526659, 'quantity': '47.518', 'price': '26214.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685030403092, 'updatetime': 1685030404526, 'tradetype': 'usdt', 'selfid': 42262, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685030404526, 'clientorderid': '42262F1685030404116I0L2', 'price': '26214.3', 'quantity': '47.518', 'commission': '1245.6511074', 'commissionasset': 'USDT', 'tradetime': 1685030404526, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685030404526}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1667 

self.closeSec=1685030999, self.tradeDate='20230526', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26216.9', self.close='26230.7'
127.0.0.1 - - [26/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-26 00:10:01,184:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685030999, self.tradeDate='20230526', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26216.9', self.close='26230.7'
2023-05-26 00:10:01,204:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230525   232000    232959  1685028599  26280.1  26253.8
12237  20230525   233000    233959  1685029199  26253.8  26218.6
12238  20230525   234000    234959  1685029799  26218.6  26198.8
12239  20230525   235000    235959  1685030399    26200  26216.9
12240  20230526   000000    000959  1685030999  26216.9  26230.7
2023-05-26 00:10:01,206:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1668 

self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26230.6', self.close='26270.3'
127.0.0.1 - - [26/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-26 00:20:06,873:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26230.6', self.close='26270.3'
2023-05-26 00:20:07,013:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230525   233000    233959  1685029199  26253.8  26218.6
12238  20230525   234000    234959  1685029799  26218.6  26198.8
12239  20230525   235000    235959  1685030399    26200  26216.9
12240  20230526   000000    000959  1685030999  26216.9  26230.7
12241  20230526   001000    001959  1685031599  26230.6  26270.3
2023-05-26 00:20:07,014:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3328
self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26244.7, self.close=26270.3, self.high=26275.6, self.low=26235.0, self.vol=862.399, self.amt=22645847.0001 
127.0.0.1 - - [26/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-26 00:20:05,821:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230525   235500    235959  ...         0.0        0.0       0
5760  20230526   000000    000459  ...         0.0        0.0       0
5761  20230526   000500    000959  ...         0.0        0.0       0
5762  20230526   001000    001459  ...         0.0        0.0       0
5763  20230526   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-26 00:20:05,833:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685031599, self.tradeDate='20230526', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26244.7, self.close=26270.3, self.high=26275.6, self.low=26235.0, self.vol=862.399, self.amt=22645847.0001, ukdf['pct'].iloc[-1]=0.000972 , ukdf['amount'].iloc[-1]=22645847.0001, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-21081.2316', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26276.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3329
self.closeSec=1685031899, self.tradeDate='20230526', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26270.2, self.close=26259.2, self.high=26315.3, self.low=26250.8, self.vol=2391.693, self.amt=62869387.8882 
127.0.0.1 - - [26/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-26 00:25:00,892:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230526   000000    000459  ...         0.0        0.0       0
5761  20230526   000500    000959  ...         0.0        0.0       0
5762  20230526   001000    001459  ...         0.0        0.0       0
5763  20230526   001500    001959  ...         0.0        0.0       0
5764  20230526   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-26 00:25:00,892:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685031899, self.tradeDate='20230526', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26270.2, self.close=26259.2, self.high=26315.3, self.low=26250.8, self.vol=2391.693, self.amt=62869387.8882, ukdf['pct'].iloc[-1]=-0.000423 , ukdf['amount'].iloc[-1]=62869387.8882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-21619.03328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26261.92', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230525   120000    155959  1685001599  ...    723  0.521366  0.807871     1.0
724  20230525   160000    195959  1685015999  ...    724  0.573660  1.166532     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '8679.18859482787', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26285.29222963', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=69
self.closeSec=1685030399, self.tradeDate='20230525', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26282.5, self.close=26216.9, self.high=26489.5, self.low=26151.4, self.vol=110196.106, self.amt=2902615215.15644 
127.0.0.1 - - [26/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-05-26 00:00:01,997:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685030399, self.tradeDate='20230525', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26282.5, self.close=26216.9, self.high=26489.5, self.low=26151.4, self.vol=110196.106, self.amt=2902615215.15644 
2023-05-26 00:00:02,068:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230525   040000    075959  ...   50565.341  1.333426e+09  0.002751
722  20230525   080000    115959  ...   94944.153  2.478461e+09 -0.005427
723  20230525   120000    155959  ...   40575.044  1.063439e+09 -0.001991
724  20230525   160000    195959  ...   40284.053  1.056670e+09  0.006264
725  20230525   200000    235959  ...  110196.106  2.902615e+09 -0.002496

[5 rows x 11 columns]
2023-05-26 00:00:04,528:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230525   040000    075959  1684972799  ...    721  0.463025  0.405514     NaN
722  20230525   080000    115959  1684987199  ...    722  0.467197  0.467010     NaN
723  20230525   120000    155959  1685001599  ...    723  0.521366  0.807871     1.0
724  20230525   160000    195959  1685015999  ...    724  0.573660  1.166532     1.0
725  20230525   200000    235959  1685030399  ...    725  0.581766  1.282105     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '4764.32446366722', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26214.43367778', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


