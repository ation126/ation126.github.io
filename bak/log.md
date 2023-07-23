# 20230724 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20320
self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29926.1, self.close=29900.6, self.high=29928.8, self.low=29900.6, self.vol=601.098, self.amt=17979788.5837 
127.0.0.1 - - [24/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 00:20:05,338:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230723   235500    235959  ...         0.0        0.0       0
5760  20230724   000000    000459  ...         0.0        0.0       0
5761  20230724   000500    000959  ...         0.0        0.0       0
5762  20230724   001000    001459  ...         0.0        0.0       0
5763  20230724   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 00:20:05,358:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29926.1, self.close=29900.6, self.high=29928.8, self.low=29900.6, self.vol=601.098, self.amt=17979788.5837, ukdf['pct'].iloc[-1]=-0.000885 , ukdf['amount'].iloc[-1]=17979788.5837, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42286.4421878283', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29901.41028205', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--: 127.0.0.1 - - [24/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=20321
self.closeSec=1690129499, self.tradeDate='20230724', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29900.7, self.close=29909.4, self.high=29909.4, self.low=29899.6, self.vol=203.971, self.amt=6099734.9166 
2023-07-24 00:25:00,760:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230724   000000    000459  ...         0.0        0.0       0
5761  20230724   000500    000959  ...         0.0        0.0       0
5762  20230724   001000    001459  ...         0.0        0.0       0
5763  20230724   001500    001959  ...         0.0        0.0       0
5764  20230724   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 00:25:00,760:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690129499, self.tradeDate='20230724', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29900.7, self.close=29909.4, self.high=29909.4, self.low=29899.6, self.vol=203.971, self.amt=6099734.9166, ukdf['pct'].iloc[-1]=0.000294 , ukdf['amount'].iloc[-1]=6099734.9166, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42396.3144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29909.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29926.1, self.close=29900.6, self.high=29928.8, self.low=29900.6 
127.0.0.1 - - [24/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 00:20:03,579:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29926.1, self.close=29900.6, self.high=29928.8, self.low=29900.6   
2023-07-24 00:20:04,569:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230723   235500    235959  1690127999  ...  29875.6  0.000348   1727    5
1440  20230724   000000    000459  1690128299  ...  29885.9  0.000325   1440    0
1441  20230724   000500    000959  1690128599  ...  29895.6  0.001030   1441    1
1442  20230724   001000    001459  1690128899  ...  29905.0  0.000020   1442    2
1443  20230724   001500    001959  1690129199  ...  29900.6 -0.000885   1443    3

[5 rows x 11 columns]
2023-07-24 00:20:04,577:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [24/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=29, self.factor=0.4207702300706728, self.count=20323 

self.closeSec=1690129499, self.tradeDate='20230724', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29900.7, self.close=29909.4, self.high=29909.4, self.low=29899.6 
2023-07-24 00:25:00,725:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690129499, self.tradeDate='20230724', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29900.7, self.close=29909.4, self.high=29909.4, self.low=29899.6   
2023-07-24 00:25:00,738:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230724   000000    000459  1690128299  ...  29885.9  0.000325   1440    0
1441  20230724   000500    000959  1690128599  ...  29895.6  0.001030   1441    1
1442  20230724   001000    001459  1690128899  ...  29905.0  0.000020   1442    2
1443  20230724   001500    001959  1690129199  ...  29900.6 -0.000885   1443    3
1444  20230724   002000    002459  1690129499  ...  29899.6  0.000294   1444    4

[5 rows x 11 columns]
2023-07-24 00:25:00,738:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-24 00:00:18,227:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230723    212959  29911.1  ...  51.666667  0.492986  0.310762
5803  20230723    215959  29854.6  ...  51.666667  0.500975  0.307785
5804  20230723    222959  29875.5  ...  51.250000  0.499209  0.305830
5805  20230723    225959  29870.9  ...  51.666667  0.504173  0.301714
5806  20230723    232959  29883.6  ...  51.666667  0.502703  0.298535

[5 rows x 33 columns]
0.5404411764705882
acc is : 0.5404411764705882
2023-07-24 00:00:18,318:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.487464  0.512536       1  ...  0.949869   1.0    0.0  0.972168
540     0  0.505382  0.494618       0  ...  0.949723   1.0    0.0  0.972018
541     1  0.497678  0.502322       1  ...  0.950130   1.0    0.0  0.972435
542     0  0.503845  0.496155       0  ...  0.950012   1.0    0.0  0.972314
543     1  0.498150  0.501850       1  ...  0.950203   1.0    0.0  0.972510

[5 rows x 10 columns]
2023-07-24 00:00:18,337:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.487346  0.512654       1  ...  0.949869   1.0    0.0  0.972215
46     0  0.505409  0.494591       0  ...  0.949723   1.0    0.0  0.972784
47     1  0.497705  0.502295       1  ...  0.950130   1.0    0.0  0.973201
48     0  0.503614  0.496386       0  ...  0.950012   1.0    0.0  0.970782
49     1  0.498150  0.501850       1  ...  0.950203   1.0    0.0  0.972510

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '1188.6108', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29890', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-24 00:00:04,143:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42717F1690128003549I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690128003951051, 'quantity': '24.853', 'price': '29886', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690128002714, 'updatetime': 1690128003951, 'tradetype': 'usdt', 'selfid': 42717, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690128003951, 'clientorderid': '42717F1690128003549I0L59', 'price': '29886', 'quantity': '24.853', 'commission': '742.756758', 'commissionasset': 'USDT', 'tradetime': 1690128003951, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690128003951}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10160 

self.closeSec=1690128599, self.tradeDate='20230724', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29885.9', self.close='29926.5'
2023-07-24 00:10:01,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690128599, self.tradeDate='20230724', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29885.9', self.close='29926.5'
2023-07-24 00:10:01,129:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230723   232000    232959  1690126199  29888.5    29880 -0.000281
573  20230723   233000    233959  1690126799    29880  29882.5  0.000084
574  20230723   234000    234959  1690127399  29882.6  29888.9  0.000214
575  20230723   235000    235959  1690127999  29888.9    29886 -0.000097
576  20230724   000000    000959  1690128599  29885.9  29926.5  0.001355
2023-07-24 00:10:01,129:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10161 

self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29926.6', self.close='29900.6'
127.0.0.1 - - [24/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 00:20:05,689:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29926.6', self.close='29900.6'
2023-07-24 00:20:06,140:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230723   233000    233959  1690126799    29880  29882.5  0.000084
574  20230723   234000    234959  1690127399  29882.6  29888.9  0.000214
575  20230723   235000    235959  1690127999  29888.9    29886 -0.000097
576  20230724   000000    000959  1690128599  29885.9  29926.5  0.001355
577  20230724   001000    001959  1690129199  29926.6  29900.6 -0.000865
2023-07-24 00:20:06,147:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-24 00:00:02,211:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-24 00:00:02,298:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7240000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230723, closeTime:235959, close:29886, total:1006791.0689493, pct_pre:2.0072730192444155e-05, thd:-0.17386285215508646, side:sell 
127.0.0.1 - - [24/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10163 

self.closeSec=1690128599, self.tradeDate='20230724', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29885.9', self.close='29926.5'
2023-07-24 00:10:01,094:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690128599, self.tradeDate='20230724', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29885.9', self.close='29926.5'
2023-07-24 00:10:01,111:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230723   232000    232959  1690126199  29888.5    29880
17421  20230723   233000    233959  1690126799    29880  29882.5
17422  20230723   234000    234959  1690127399  29882.6  29888.9
17423  20230723   235000    235959  1690127999  29888.9    29886
17424  20230724   000000    000959  1690128599  29885.9  29926.5
2023-07-24 00:10:01,111:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10164 

self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29926.6', self.close='29900.6'
127.0.0.1 - - [24/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 00:20:06,802:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29926.6', self.close='29900.6'
2023-07-24 00:20:06,995:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230723   233000    233959  1690126799    29880  29882.5
17422  20230723   234000    234959  1690127399  29882.6  29888.9
17423  20230723   235000    235959  1690127999  29888.9    29886
17424  20230724   000000    000959  1690128599  29885.9  29926.5
17425  20230724   001000    001959  1690129199  29926.6  29900.6
2023-07-24 00:20:06,996:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-24 00:00:04,255:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42718F1690128003583I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690128003962561, 'quantity': '37.962', 'price': '29885.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1690128002745, 'updatetime': 1690128003962, 'tradetype': 'usdt', 'selfid': 42718, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690128003962, 'clientorderid': '42718F1690128003583I0L2', 'price': '29885.9', 'quantity': '37.962', 'commission': '1134.5285358', 'commissionasset': 'USDT', 'tradetime': 1690128003962, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690128003962}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10163 

self.closeSec=1690128599, self.tradeDate='20230724', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29885.9', self.close='29926.5'
2023-07-24 00:10:01,122:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690128599, self.tradeDate='20230724', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29885.9', self.close='29926.5'
127.0.0.1 - - [24/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-24 00:10:01,135:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230723   232000    232959  1690126199  29888.5    29880
12237  20230723   233000    233959  1690126799    29880  29882.5
12238  20230723   234000    234959  1690127399  29882.6  29888.9
12239  20230723   235000    235959  1690127999  29888.9    29886
12240  20230724   000000    000959  1690128599  29885.9  29926.5
2023-07-24 00:10:01,135:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10164 

self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29926.6', self.close='29900.6'
127.0.0.1 - - [24/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-24 00:20:06,681:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29926.6', self.close='29900.6'
2023-07-24 00:20:06,899:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230723   233000    233959  1690126799    29880  29882.5
12238  20230723   234000    234959  1690127399  29882.6  29888.9
12239  20230723   235000    235959  1690127999  29888.9    29886
12240  20230724   000000    000959  1690128599  29885.9  29926.5
12241  20230724   001000    001959  1690129199  29926.6  29900.6
2023-07-24 00:20:06,899:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20320
self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29926.1, self.close=29900.6, self.high=29928.8, self.low=29900.6, self.vol=601.098, self.amt=17979788.5837 
127.0.0.1 - - [24/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-24 00:20:05,287:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230723   235500    235959  ...         0.0        0.0       0
5760  20230724   000000    000459  ...         0.0        0.0       0
5761  20230724   000500    000959  ...         0.0        0.0       0
5762  20230724   001000    001459  ...         0.0        0.0       0
5763  20230724   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 00:20:05,308:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690129199, self.tradeDate='20230724', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29926.1, self.close=29900.6, self.high=29928.8, self.low=29900.6, self.vol=601.098, self.amt=17979788.5837, ukdf['pct'].iloc[-1]=-0.000885 , ukdf['amount'].iloc[-1]=17979788.5837, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113555.27528561905', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29901.41028205', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=20321
self.closeSec=1690129499, self.tradeDate='20230724', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29900.7, self.close=29909.4, self.high=29909.4, self.low=29899.6, self.vol=203.971, self.amt=6099734.9166 
127.0.0.1 - - [24/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-24 00:25:00,753:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230724   000000    000459  ...         0.0        0.0       0
5761  20230724   000500    000959  ...         0.0        0.0       0
5762  20230724   001000    001459  ...         0.0        0.0       0
5763  20230724   001500    001959  ...         0.0        0.0       0
5764  20230724   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-24 00:25:00,754:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690129499, self.tradeDate='20230724', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29900.7, self.close=29909.4, self.high=29909.4, self.low=29899.6, self.vol=203.971, self.amt=6099734.9166, ukdf['pct'].iloc[-1]=0.000294 , ukdf['amount'].iloc[-1]=6099734.9166, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113848.3073', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29909.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230723   120000    155959  1690099199  ...    723  0.148149 -0.843344    -1.0
724  20230723   160000    195959  1690113599  ...    724  0.107702 -0.988349    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-568.7184', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29881.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=423
self.closeSec=1690127999, self.tradeDate='20230723', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29881.5, self.close=29886.0, self.high=29922.7, self.low=29836.2, self.vol=14726.508, self.amt=440026232.6405 
127.0.0.1 - - [24/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-07-24 00:00:01,786:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690127999, self.tradeDate='20230723', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29881.5, self.close=29886.0, self.high=29922.7, self.low=29836.2, self.vol=14726.508, self.amt=440026232.6405 
2023-07-24 00:00:01,799:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230723   040000    075959  ...  33991.832  1.010297e+09 -0.001244
722  20230723   080000    115959  ...  29826.520  8.891474e+08  0.001645
723  20230723   120000    155959  ...  34347.504  1.027396e+09  0.002293
724  20230723   160000    195959  ...  15675.657  4.687871e+08 -0.000649
725  20230723   200000    235959  ...  14726.508  4.400262e+08  0.000151

[5 rows x 11 columns]
2023-07-24 00:00:02,575:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230723   040000    075959  1690070399  ...    721  0.164716 -0.808995    -1.0
722  20230723   080000    115959  1690084799  ...    722  0.156991 -0.823997    -1.0
723  20230723   120000    155959  1690099199  ...    723  0.148149 -0.843344    -1.0
724  20230723   160000    195959  1690113599  ...    724  0.107702 -0.988349    -1.0
725  20230723   200000    235959  1690127999  ...    725  0.096704 -1.012718    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-798.2928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29885.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


