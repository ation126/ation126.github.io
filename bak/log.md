# 20230609 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7360
self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26668.3, self.close=26641.2, self.high=26695.9, self.low=26641.2, self.vol=1455.808, self.amt=38828815.4556 
127.0.0.1 - - [09/Jun/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-06-09 00:20:01,235:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230608   235500    235959  ...         0.0        0.0       0
5760  20230609   000000    000459  ...         0.0        0.0       0
5761  20230609   000500    000959  ...         0.0        0.0       0
5762  20230609   001000    001459  ...         0.0        0.0       0
5763  20230609   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 00:20:01,242:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26668.3, self.close=26641.2, self.high=26695.9, self.low=26641.2, self.vol=1455.808, self.amt=38828815.4556, ukdf['pct'].iloc[-1]=-0.001016 , ukdf['amount'].iloc[-1]=38828815.4556, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3053.1727128903', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26645.65738095', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7361
self.closeSec=1686241499, self.tradeDate='20230609', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26641.2, self.close=26642.1, self.high=26673.0, self.low=26612.0, self.vol=2480.671, self.amt=66081991.9515 
127.0.0.1 - - [09/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:25:04,261:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230609   000000    000459  ...         0.0        0.0       0
5761  20230609   000500    000959  ...         0.0        0.0       0
5762  20230609   001000    001459  ...         0.0        0.0       0
5763  20230609   001500    001959  ...         0.0        0.0       0
5764  20230609   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 00:25:04,265:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686241499, self.tradeDate='20230609', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26641.2, self.close=26642.1, self.high=26673.0, self.low=26612.0, self.vol=2480.671, self.amt=66081991.9515, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=66081991.9515, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3143.0982', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26639.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26668.3, self.close=26641.2, self.high=26695.9, self.low=26641.2 
127.0.0.1 - - [09/Jun/2023 00:20:00] "POST / HTTP/1.1" 200 -
2023-06-09 00:20:00,974:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26668.3, self.close=26641.2, self.high=26695.9, self.low=26641.2   
2023-06-09 00:20:01,185:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230608   235500    235959  1686239999  ...  26692.1 -0.001133   1727    5
1440  20230609   000000    000459  1686240299  ...  26670.1 -0.001303   1440    0
1441  20230609   000500    000959  1686240599  ...  26642.2 -0.001072   1441    1
1442  20230609   001000    001459  1686240899  ...  26642.0  0.000961   1442    2
1443  20230609   001500    001959  1686241199  ...  26641.2 -0.001016   1443    3

[5 rows x 11 columns]
2023-06-09 00:20:01,190:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=13, self.factor=0.4993739979684123, self.count=7363 

self.closeSec=1686241499, self.tradeDate='20230609', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26641.2, self.close=26642.1, self.high=26673.0, self.low=26612.0 
127.0.0.1 - - [09/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:25:03,115:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686241499, self.tradeDate='20230609', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26641.2, self.close=26642.1, self.high=26673.0, self.low=26612.0   
2023-06-09 00:25:03,837:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230609   000000    000459  1686240299  ...  26670.1 -0.001303   1440    0
1441  20230609   000500    000959  1686240599  ...  26642.2 -0.001072   1441    1
1442  20230609   001000    001459  1686240899  ...  26642.0  0.000961   1442    2
1443  20230609   001500    001959  1686241199  ...  26641.2 -0.001016   1443    3
1444  20230609   002000    002459  1686241499  ...  26612.0  0.000034   1444    4

[5 rows x 11 columns]
2023-06-09 00:25:03,846:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-09 00:00:44,882:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230608    212959  26447.7  ...  49.583333  0.484835  0.562868
5803  20230608    215959  26374.0  ...  49.583333  0.487569  0.553587
5804  20230608    222959  26389.8  ...  49.583333  0.501537  0.533516
5805  20230608    225959  26472.7  ...  50.000000  0.527051  0.503420
5806  20230608    232959  26635.9  ...  49.583333  0.524425  0.477135

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-06-09 00:00:45,043:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     1  0.475607  0.524393       1  ...  1.104778  -1.0  0.0000  0.969543
540     1  0.498711  0.501289       1  ...  1.101311  -1.0  0.0000  0.972585
541     0  0.517524  0.482476       1  ...  1.094630  -1.0  0.0000  0.978486
542     0  0.550642  0.449358       0  ...  1.092246   1.0 -0.0016  0.977920
543     0  0.509981  0.490019       1  ...  1.095865   1.0  0.0000  0.981160

[5 rows x 10 columns]
2023-06-09 00:00:45,064:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.475860  0.524140       1  ...  1.104778  -1.0  0.0000  0.970856
46     1  0.498990  0.501010       1  ...  1.101311  -1.0  0.0000  0.974135
47     0  0.517791  0.482209       1  ...  1.094630  -1.0  0.0000  0.980045
48     0  0.550790  0.449210       0  ...  1.092246   1.0 -0.0016  0.979024
49     0  0.509981  0.490019       1  ...  1.095865   1.0  0.0000  0.981160

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.647', 'enterprice': '26630.1', 'countrevence': '0', 'unrealprofit': '2104.27839675387', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26703.55545421', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [09/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-09 00:00:04,654:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42350F1686240003908I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686240004289788, 'quantity': '26.427', 'price': '26705.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686240002806, 'updatetime': 1686240004289, 'tradetype': 'usdt', 'selfid': 42350, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686240004289, 'clientorderid': '42350F1686240003908I0L59', 'price': '26705.8', 'quantity': '26.427', 'commission': '705.7541766', 'commissionasset': 'USDT', 'tradetime': 1686240004289, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686240004289}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3680 

self.closeSec=1686240599, self.tradeDate='20230609', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26705.8', self.close='26642.7'
127.0.0.1 - - [09/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:10:01,174:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686240599, self.tradeDate='20230609', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26705.8', self.close='26642.7'
2023-06-09 00:10:01,246:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230608   232000    232959  1686238199    26610  26617.9  0.000368
573  20230608   233000    233959  1686238799    26618  26620.4  0.000094
574  20230608   234000    234959  1686239399  26620.4  26694.2  0.002772
575  20230608   235000    235959  1686239999  26694.2  26705.9  0.000438
576  20230609   000000    000959  1686240599  26705.8  26642.7 -0.002367
2023-06-09 00:10:01,246:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3681 

self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26642.7', self.close='26641.2'
127.0.0.1 - - [09/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:20:03,166:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26642.7', self.close='26641.2'
2023-06-09 00:20:03,549:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230608   233000    233959  1686238799    26618  26620.4  0.000094
574  20230608   234000    234959  1686239399  26620.4  26694.2  0.002772
575  20230608   235000    235959  1686239999  26694.2  26705.9  0.000438
576  20230609   000000    000959  1686240599  26705.8  26642.7 -0.002367
577  20230609   001000    001959  1686241199  26642.7  26641.2 -0.000056
2023-06-09 00:20:03,555:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-09 00:00:05,027:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42349F1686240003890I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686240004279495, 'quantity': '36.955', 'price': '26705.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686240002795, 'updatetime': 1686240004279, 'tradetype': 'usdt', 'selfid': 42349, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686240004279, 'clientorderid': '42349F1686240003890I0L57', 'price': '26705.8', 'quantity': '36.955', 'commission': '986.912839', 'commissionasset': 'USDT', 'tradetime': 1686240004279, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686240004279}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jun/2023 00:00:05] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3683 

self.closeSec=1686240599, self.tradeDate='20230609', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26705.8', self.close='26642.7'
127.0.0.1 - - [09/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:10:01,167:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686240599, self.tradeDate='20230609', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26705.8', self.close='26642.7'
2023-06-09 00:10:01,205:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230608   232000    232959  1686238199    26610  26617.9
17421  20230608   233000    233959  1686238799    26618  26620.4
17422  20230608   234000    234959  1686239399  26620.4  26694.2
17423  20230608   235000    235959  1686239999  26694.2  26705.9
17424  20230609   000000    000959  1686240599  26705.8  26642.7
2023-06-09 00:10:01,206:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3684 

self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26642.7', self.close='26641.2'
127.0.0.1 - - [09/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:20:04,408:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26642.7', self.close='26641.2'
2023-06-09 00:20:04,547:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230608   233000    233959  1686238799    26618  26620.4
17422  20230608   234000    234959  1686239399  26620.4  26694.2
17423  20230608   235000    235959  1686239999  26694.2  26705.9
17424  20230609   000000    000959  1686240599  26705.8  26642.7
17425  20230609   001000    001959  1686241199  26642.7  26641.2
2023-06-09 00:20:04,548:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [09/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-09 00:00:04,407:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42348F1686240003801I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686240004173710, 'quantity': '48.118', 'price': '26705.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686240002852, 'updatetime': 1686240004173, 'tradetype': 'usdt', 'selfid': 42348, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686240004173, 'clientorderid': '42348F1686240003801I0L2', 'price': '26705.9', 'quantity': '48.118', 'commission': '1285.0344962', 'commissionasset': 'USDT', 'tradetime': 1686240004173, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686240004173}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [09/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3683 

self.closeSec=1686240599, self.tradeDate='20230609', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26705.8', self.close='26642.7'
2023-06-09 00:10:01,149:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686240599, self.tradeDate='20230609', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26705.8', self.close='26642.7'
2023-06-09 00:10:01,197:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230608   232000    232959  1686238199    26610  26617.9
12237  20230608   233000    233959  1686238799    26618  26620.4
12238  20230608   234000    234959  1686239399  26620.4  26694.2
12239  20230608   235000    235959  1686239999  26694.2  26705.9
12240  20230609   000000    000959  1686240599  26705.8  26642.7
2023-06-09 00:10:01,197:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3684 

self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26642.7', self.close='26641.2'
127.0.0.1 - - [09/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:20:04,108:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26642.7', self.close='26641.2'
2023-06-09 00:20:04,414:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230608   233000    233959  1686238799    26618  26620.4
12238  20230608   234000    234959  1686239399  26620.4  26694.2
12239  20230608   235000    235959  1686239999  26694.2  26705.9
12240  20230609   000000    000959  1686240599  26705.8  26642.7
12241  20230609   001000    001959  1686241199  26642.7  26641.2
2023-06-09 00:20:04,414:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [09/Jun/2023 00:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7360
self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26668.3, self.close=26641.2, self.high=26695.9, self.low=26641.2, self.vol=1455.808, self.amt=38828815.4556 
2023-06-09 00:20:01,250:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230608   235500    235959  ...         0.0        0.0       0
5760  20230609   000000    000459  ...         0.0        0.0       0
5761  20230609   000500    000959  ...         0.0        0.0       0
5762  20230609   001000    001459  ...         0.0        0.0       0
5763  20230609   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 00:20:01,256:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686241199, self.tradeDate='20230609', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26668.3, self.close=26641.2, self.high=26695.9, self.low=26641.2, self.vol=1455.808, self.amt=38828815.4556, ukdf['pct'].iloc[-1]=-0.001016 , ukdf['amount'].iloc[-1]=38828815.4556, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-7366.64321413605', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26645.65738095', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7361
self.closeSec=1686241499, self.tradeDate='20230609', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26641.2, self.close=26642.1, self.high=26673.0, self.low=26612.0, self.vol=2480.671, self.amt=66081991.9515 
127.0.0.1 - - [09/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:25:04,233:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230609   000000    000459  ...         0.0        0.0       0
5761  20230609   000500    000959  ...         0.0        0.0       0
5762  20230609   001000    001459  ...         0.0        0.0       0
5763  20230609   001500    001959  ...         0.0        0.0       0
5764  20230609   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-09 00:25:04,240:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686241499, self.tradeDate='20230609', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26641.2, self.close=26642.1, self.high=26673.0, self.low=26612.0, self.vol=2480.671, self.amt=66081991.9515, ukdf['pct'].iloc[-1]=3.4e-05 , ukdf['amount'].iloc[-1]=66081991.9515, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-7606.4768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26639.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230608   120000    155959  1686211199  ...    723  0.517285 -0.282857     NaN
724  20230608   160000    195959  1686225599  ...    724  0.523612 -0.267755     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '35819.2838', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26429.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=153
self.closeSec=1686239999, self.tradeDate='20230608', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26421.5, self.close=26705.9, self.high=26800.0, self.low=26283.4, self.vol=127003.344, self.amt=3367354779.87239 
127.0.0.1 - - [09/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-09 00:00:01,774:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686239999, self.tradeDate='20230608', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26421.5, self.close=26705.9, self.high=26800.0, self.low=26283.4, self.vol=127003.344, self.amt=3367354779.87239 
2023-06-09 00:00:01,820:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230608   040000    075959  ...   64175.757  1.687819e+09 -0.005414
722  20230608   080000    115959  ...   45884.902  1.209048e+09  0.000232
723  20230608   120000    155959  ...   44715.213  1.180481e+09  0.003779
724  20230608   160000    195959  ...   31664.967  8.364446e+08 -0.000382
725  20230608   200000    235959  ...  127003.344  3.367355e+09  0.010768

[5 rows x 11 columns]
2023-06-09 00:00:04,556:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230608   040000    075959  1686182399  ...    721  0.500401 -0.323202     NaN
722  20230608   080000    115959  1686196799  ...    722  0.507395 -0.308328     NaN
723  20230608   120000    155959  1686211199  ...    723  0.517285 -0.282857     NaN
724  20230608   160000    195959  1686225599  ...    724  0.523612 -0.267755     NaN
725  20230608   200000    235959  1686239999  ...    725  0.535715 -0.238526     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '20560.3682', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26705.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


