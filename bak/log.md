# 20230801 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22624
self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29194.3, self.close=29225.9, self.high=29230.7, self.low=29162.7, self.vol=2589.818, self.amt=75618306.1347 
127.0.0.1 - - [01/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 00:20:05,807:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230731   235500    235959  ...         0.0        0.0       0
5760  20230801   000000    000459  ...         0.0        0.0       0
5761  20230801   000500    000959  ...         0.0        0.0       0
5762  20230801   001000    001459  ...         0.0        0.0       0
5763  20230801   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 00:20:05,819:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29194.3, self.close=29225.9, self.high=29230.7, self.low=29162.7, self.vol=2589.818, self.amt=75618306.1347, ukdf['pct'].iloc[-1]=0.001082 , ukdf['amount'].iloc[-1]=75618306.1347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32858.67860614086', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29224.42022161', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=22625
self.closeSec=1690820699, self.tradeDate='20230801', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29225.9, self.close=29246.7, self.high=29249.7, self.low=29205.6, self.vol=1161.251, self.amt=33941201.1022 
127.0.0.1 - - [01/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-08-01 00:25:00,831:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230801   000000    000459  ...         0.0        0.0       0
5761  20230801   000500    000959  ...         0.0        0.0       0
5762  20230801   001000    001459  ...         0.0        0.0       0
5763  20230801   001500    001959  ...         0.0        0.0       0
5764  20230801   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 00:25:00,831:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690820699, self.tradeDate='20230801', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29225.9, self.close=29246.7, self.high=29249.7, self.low=29205.6, self.vol=1161.251, self.amt=33941201.1022, ukdf['pct'].iloc[-1]=0.000712 , ukdf['amount'].iloc[-1]=33941201.1022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33167.5542', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29246.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29194.3, self.close=29225.9, self.high=29230.7, self.low=29162.7 
127.0.0.1 - - [01/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 00:20:03,909:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29194.3, self.close=29225.9, self.high=29230.7, self.low=29162.7   
2023-08-01 00:20:05,207:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230731   235500    235959  1690819199  ...  29230.6 -0.000356   1727    5
1440  20230801   000000    000459  1690819499  ...  29190.2  0.000811   1440    0
1441  20230801   000500    000959  1690819799  ...  29155.0 -0.001456   1441    1
1442  20230801   001000    001459  1690820099  ...  29177.2 -0.000620   1442    2
1443  20230801   001500    001959  1690820399  ...  29162.7  0.001082   1443    3

[5 rows x 11 columns]
2023-08-01 00:20:05,208:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=6, self.factor=0.39701746556148704, self.count=22627 

self.closeSec=1690820699, self.tradeDate='20230801', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29225.9, self.close=29246.7, self.high=29249.7, self.low=29205.6 
2023-08-01 00:25:00,799:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690820699, self.tradeDate='20230801', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29225.9, self.close=29246.7, self.high=29249.7, self.low=29205.6   
2023-08-01 00:25:00,812:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230801   000000    000459  1690819499  ...  29190.2  0.000811   1440    0
1441  20230801   000500    000959  1690819799  ...  29155.0 -0.001456   1441    1
1442  20230801   001000    001459  1690820099  ...  29177.2 -0.000620   1442    2
1443  20230801   001500    001959  1690820399  ...  29162.7  0.001082   1443    3
1444  20230801   002000    002459  1690820699  ...  29205.6  0.000712   1444    4

[5 rows x 11 columns]
2023-08-01 00:25:00,812:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-01 00:00:15,843:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230731    212959  29456.9  ...  46.250000  0.534798  0.284766
5803  20230731    215959  29422.3  ...  45.833333  0.507307  0.287572
5804  20230731    222959  29352.7  ...  45.833333  0.496329  0.293782
5805  20230731    225959  29328.0  ...  45.833333  0.481925  0.304439
5806  20230731    232959  29290.0  ...  45.416667  0.480161  0.314989

[5 rows x 33 columns]
0.5661764705882353
acc is : 0.5661764705882353
2023-08-01 00:00:15,902:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.497151  0.502849       0  ...  0.970852   1.0    0.0  0.972191
540     1  0.483483  0.516517       0  ...  0.969926   1.0    0.0  0.971264
541     1  0.488344  0.511656       0  ...  0.968673   1.0    0.0  0.970009
542     1  0.482687  0.517313       0  ...  0.968517   1.0    0.0  0.969853
543     1  0.484841  0.515159       0  ...  0.966731   1.0    0.0  0.968065

[5 rows x 10 columns]
2023-08-01 00:00:15,914:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.497025  0.502975       0  ...  0.970852   1.0    0.0  0.972604
46     1  0.483582  0.516418       0  ...  0.930726   1.0    0.0  0.974025
47     1  0.488388  0.511612       0  ...  0.929523   1.0    0.0  0.972767
48     1  0.482602  0.517398       0  ...  0.968517   1.0    0.0  0.969879
49     1  0.484841  0.515159       0  ...  0.966731   1.0    0.0  0.968065

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-5844.9372', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29232.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-01 00:00:04,109:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42773F1690819203485I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690819203890066, 'quantity': '24.994', 'price': '29231.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690819202576, 'updatetime': 1690819203890, 'tradetype': 'usdt', 'selfid': 42773, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690819203890, 'clientorderid': '42773F1690819203485I0L59', 'price': '29231.4', 'quantity': '24.994', 'commission': '730.6096116', 'commissionasset': 'USDT', 'tradetime': 1690819203890, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690819203890}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11312 

self.closeSec=1690819799, self.tradeDate='20230801', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29231.3', self.close='29212.4'
2023-08-01 00:10:01,160:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690819799, self.tradeDate='20230801', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29231.3', self.close='29212.4'
2023-08-01 00:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230731   232000    232959  1690817399  29306.8  29285.3 -0.000734
573  20230731   233000    233959  1690817999  29285.2  29273.9 -0.000389
574  20230731   234000    234959  1690818599  29273.9  29247.7 -0.000895
575  20230731   235000    235959  1690819199  29247.8  29231.3 -0.000561
576  20230801   000000    000959  1690819799  29231.3  29212.4 -0.000647
2023-08-01 00:10:01,170:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11313 

self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29212.3', self.close='29225.9'
127.0.0.1 - - [01/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 00:20:06,359:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29212.3', self.close='29225.9'
2023-08-01 00:20:06,728:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230731   233000    233959  1690817999  29285.2  29273.9 -0.000389
574  20230731   234000    234959  1690818599  29273.9  29247.7 -0.000895
575  20230731   235000    235959  1690819199  29247.8  29231.3 -0.000561
576  20230801   000000    000959  1690819799  29231.3  29212.4 -0.000647
577  20230801   001000    001959  1690820399  29212.3  29225.9  0.000462
2023-08-01 00:20:06,729:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-08-01 00:00:02,053:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-08-01 00:00:02,111:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:8010000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230731, closeTime:235959, close:29231.3, total:996515.1559743, pct_pre:-0.0002416289192381793, thd:0.2397701982839141, side:sell 
127.0.0.1 - - [01/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11315 

self.closeSec=1690819799, self.tradeDate='20230801', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29231.3', self.close='29212.4'
2023-08-01 00:10:01,166:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690819799, self.tradeDate='20230801', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29231.3', self.close='29212.4'
2023-08-01 00:10:01,177:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230731   232000    232959  1690817399  29306.8  29285.3
17421  20230731   233000    233959  1690817999  29285.2  29273.9
17422  20230731   234000    234959  1690818599  29273.9  29247.7
17423  20230731   235000    235959  1690819199  29247.8  29231.3
17424  20230801   000000    000959  1690819799  29231.3  29212.4
2023-08-01 00:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11316 

self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29212.3', self.close='29225.9'
127.0.0.1 - - [01/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 00:20:07,468:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29212.3', self.close='29225.9'
2023-08-01 00:20:07,545:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230731   233000    233959  1690817999  29285.2  29273.9
17422  20230731   234000    234959  1690818599  29273.9  29247.7
17423  20230731   235000    235959  1690819199  29247.8  29231.3
17424  20230801   000000    000959  1690819799  29231.3  29212.4
17425  20230801   001000    001959  1690820399  29212.3  29225.9
2023-08-01 00:20:07,546:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [01/Aug/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-08-01 00:00:04,021:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42772F1690819203468I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690819203865866, 'quantity': '37.237', 'price': '29231.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690819202560, 'updatetime': 1690819203865, 'tradetype': 'usdt', 'selfid': 42772, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690819203865, 'clientorderid': '42772F1690819203468I0L2', 'price': '29231.4', 'quantity': '37.237', 'commission': '1088.4896418', 'commissionasset': 'USDT', 'tradetime': 1690819203865, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690819203865}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11315 

self.closeSec=1690819799, self.tradeDate='20230801', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29231.3', self.close='29212.4'
2023-08-01 00:10:01,164:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690819799, self.tradeDate='20230801', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29231.3', self.close='29212.4'
127.0.0.1 - - [01/Aug/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-08-01 00:10:01,178:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230731   232000    232959  1690817399  29306.8  29285.3
12237  20230731   233000    233959  1690817999  29285.2  29273.9
12238  20230731   234000    234959  1690818599  29273.9  29247.7
12239  20230731   235000    235959  1690819199  29247.8  29231.3
12240  20230801   000000    000959  1690819799  29231.3  29212.4
2023-08-01 00:10:01,182:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11316 

self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29212.3', self.close='29225.9'
127.0.0.1 - - [01/Aug/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-08-01 00:20:07,362:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29212.3', self.close='29225.9'
2023-08-01 00:20:07,469:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230731   233000    233959  1690817999  29285.2  29273.9
12238  20230731   234000    234959  1690818599  29273.9  29247.7
12239  20230731   235000    235959  1690819199  29247.8  29231.3
12240  20230801   000000    000959  1690819799  29231.3  29212.4
12241  20230801   001000    001959  1690820399  29212.3  29225.9
2023-08-01 00:20:07,469:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22624
self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29194.3, self.close=29225.9, self.high=29230.7, self.low=29162.7, self.vol=2589.818, self.amt=75618306.1347 
127.0.0.1 - - [01/Aug/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-08-01 00:20:05,769:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230731   235500    235959  ...         0.0        0.0       0
5760  20230801   000000    000459  ...         0.0        0.0       0
5761  20230801   000500    000959  ...         0.0        0.0       0
5762  20230801   001000    001459  ...         0.0        0.0       0
5763  20230801   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 00:20:05,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690820399, self.tradeDate='20230801', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29194.3, self.close=29225.9, self.high=29230.7, self.low=29162.7, self.vol=2589.818, self.amt=75618306.1347, ukdf['pct'].iloc[-1]=0.001082 , ukdf['amount'].iloc[-1]=75618306.1347, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '88411.93707319116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29224.44040476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [01/Aug/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=22625
self.closeSec=1690820699, self.tradeDate='20230801', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29225.9, self.close=29246.7, self.high=29249.7, self.low=29205.6, self.vol=1161.251, self.amt=33941201.1022 
2023-08-01 00:25:00,828:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230801   000000    000459  ...         0.0        0.0       0
5761  20230801   000500    000959  ...         0.0        0.0       0
5762  20230801   001000    001459  ...         0.0        0.0       0
5763  20230801   001500    001959  ...         0.0        0.0       0
5764  20230801   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-01 00:25:00,828:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690820699, self.tradeDate='20230801', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29225.9, self.close=29246.7, self.high=29249.7, self.low=29205.6, self.vol=1161.251, self.amt=33941201.1022, ukdf['pct'].iloc[-1]=0.000712 , ukdf['amount'].iloc[-1]=33941201.1022, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '89234.9666', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29246.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230731   120000    155959  1690790399  ...    723  0.097876 -0.926380    -1.0
724  20230731   160000    195959  1690804799  ...    724  0.078130 -0.989512    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-7995.552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=471
self.closeSec=1690819199, self.tradeDate='20230731', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29395.8, self.close=29231.3, self.high=29461.4, self.low=29208.9, self.vol=58214.878, self.amt=1707881695.8164 
127.0.0.1 - - [01/Aug/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-08-01 00:00:01,629:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690819199, self.tradeDate='20230731', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29395.8, self.close=29231.3, self.high=29461.4, self.low=29208.9, self.vol=58214.878, self.amt=1707881695.8164 
2023-08-01 00:00:01,642:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230731   040000    075959  ...  50696.613  1.478429e+09  0.002875
722  20230731   080000    115959  ...  49619.636  1.459752e+09  0.004807
723  20230731   120000    155959  ...  19913.294  5.852377e+08 -0.001632
724  20230731   160000    195959  ...  19231.234  5.647518e+08  0.001093
725  20230731   200000    235959  ...  58214.878  1.707882e+09 -0.005599

[5 rows x 11 columns]
2023-08-01 00:00:02,423:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230731   040000    075959  1690761599  ...    721  0.098298 -0.965533    -1.0
722  20230731   080000    115959  1690775999  ...    722  0.101916 -0.929582    -1.0
723  20230731   120000    155959  1690790399  ...    723  0.097876 -0.926380    -1.0
724  20230731   160000    195959  1690804799  ...    724  0.078130 -0.989512    -1.0
725  20230731   200000    235959  1690819199  ...    725  0.033872 -1.156911    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '753.5396151144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29234.0517619', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


