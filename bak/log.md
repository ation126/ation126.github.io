# 20230525 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3040
self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26249.9, self.close=26190.0, self.high=26250.0, self.low=26168.2, self.vol=3848.939, self.amt=100830218.7413 
127.0.0.1 - - [25/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 00:20:05,540:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230524   235500    235959  ...    0.128120   0.283231       0
5760  20230525   000000    000459  ...    0.127960   0.283141       0
5761  20230525   000500    000959  ...    0.127803   0.283055       0
5762  20230525   001000    001459  ...    0.127646   0.282968       0
5763  20230525   001500    001959  ...    0.127488   0.282881       0

[5 rows x 18 columns]
2023-05-25 00:20:05,572:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26249.9, self.close=26190.0, self.high=26250.0, self.low=26168.2, self.vol=3848.939, self.amt=100830218.7413, ukdf['pct'].iloc[-1]=-0.002286 , ukdf['amount'].iloc[-1]=100830218.7413, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.12748758318143036, signal=0, value_std=0.2828806913681722 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '9294.2124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26197.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3041
self.closeSec=1684945499, self.tradeDate='20230525', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26190.0, self.close=26228.3, self.high=26240.0, self.low=26190.0, self.vol=1865.197, self.amt=48900056.8748 
127.0.0.1 - - [25/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-25 00:25:00,897:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230525   000000    000459  ...    0.127960   0.283141       0
5761  20230525   000500    000959  ...    0.127803   0.283055       0
5762  20230525   001000    001459  ...    0.127646   0.282968       0
5763  20230525   001500    001959  ...    0.127488   0.282881       0
5764  20230525   002000    002459  ...    0.127329   0.282792       0

[5 rows x 18 columns]
2023-05-25 00:25:00,901:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684945499, self.tradeDate='20230525', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26190.0, self.close=26228.3, self.high=26240.0, self.low=26190.0, self.vol=1865.197, self.amt=48900056.8748, ukdf['pct'].iloc[-1]=0.001462 , ukdf['amount'].iloc[-1]=48900056.8748, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.1273288839664197, signal=0, value_std=0.2827918972233845 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '8842.5899542398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26229.9301627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26249.9, self.close=26190.0, self.high=26250.0, self.low=26168.2 
127.0.0.1 - - [25/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 00:20:03,137:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26249.9, self.close=26190.0, self.high=26250.0, self.low=26168.2   
2023-05-25 00:20:04,331:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230524   235500    235959  1684943999  ...  26281.2 -0.000365   1727    5
1440  20230525   000000    000459  1684944299  ...  26291.1 -0.000593   1440    0
1441  20230525   000500    000959  1684944599  ...  26273.6 -0.000232   1441    1
1442  20230525   001000    001459  1684944899  ...  26214.1 -0.001335   1442    2
1443  20230525   001500    001959  1684945199  ...  26168.2 -0.002286   1443    3

[5 rows x 11 columns]
2023-05-25 00:20:04,341:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6704659596391607, self.count=3043 

self.closeSec=1684945499, self.tradeDate='20230525', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26190.0, self.close=26228.3, self.high=26240.0, self.low=26190.0 
127.0.0.1 - - [25/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-25 00:25:00,769:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684945499, self.tradeDate='20230525', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26190.0, self.close=26228.3, self.high=26240.0, self.low=26190.0   
2023-05-25 00:25:00,821:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230525   000000    000459  1684944299  ...  26291.1 -0.000593   1440    0
1441  20230525   000500    000959  1684944599  ...  26273.6 -0.000232   1441    1
1442  20230525   001000    001459  1684944899  ...  26214.1 -0.001335   1442    2
1443  20230525   001500    001959  1684945199  ...  26168.2 -0.002286   1443    3
1444  20230525   002000    002459  1684945499  ...  26190.0  0.001462   1444    4

[5 rows x 11 columns]
2023-05-25 00:25:00,821:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-25 00:00:35,021:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230524    212959  26681.1  ...  46.250000  0.414509  0.765248
5803  20230524    215959  26669.7  ...  46.250000  0.365677  0.767304
5804  20230524    222959  26432.0  ...  46.250000  0.340986  0.773230
5805  20230524    225959  26289.6  ...  45.833333  0.334194  0.781273
5806  20230524    232959  26247.6  ...  45.833333  0.352309  0.782037

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-05-25 00:00:35,220:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.499277  0.500723       0  ...  0.945751  -1.0    0.0  0.987769
540     1  0.444634  0.555366       0  ...  0.950846  -1.0    0.0  0.982447
541     1  0.446396  0.553604       0  ...  0.952365  -1.0    0.0  0.980878
542     1  0.463322  0.536678       1  ...  0.950268  -1.0    0.0  0.983038
543     1  0.488523  0.511477       1  ...  0.950217  -1.0    0.0  0.983090

[5 rows x 10 columns]
2023-05-25 00:00:35,251:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499519  0.500481       0  ...  0.945751  -1.0    0.0  0.988567
46     1  0.444998  0.555002       0  ...  0.950846  -1.0    0.0  0.983819
47     1  0.446712  0.553288       0  ...  0.952365  -1.0    0.0  0.982247
48     1  0.463392  0.536608       1  ...  0.950268  -1.0    0.0  0.984546
49     1  0.488523  0.511477       1  ...  0.950217  -1.0    0.0  0.983090

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.649', 'enterprice': '26743.4', 'countrevence': '0', 'unrealprofit': '11970.7308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26294.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [25/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-25 00:00:04,986:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42252F1684944004280I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684944004699570, 'quantity': '26.004', 'price': '26306.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684944003085, 'updatetime': 1684944004699, 'tradetype': 'usdt', 'selfid': 42252, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684944004699, 'clientorderid': '42252F1684944004280I0L59', 'price': '26306.7', 'quantity': '26.004', 'commission': '684.0794268', 'commissionasset': 'USDT', 'tradetime': 1684944004699, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684944004699}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1520 

self.closeSec=1684944599, self.tradeDate='20230525', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26306.9', self.close='26285.1'
2023-05-25 00:10:01,224:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684944599, self.tradeDate='20230525', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26306.9', self.close='26285.1'
2023-05-25 00:10:01,248:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230524   232000    232959  1684942199  26274.9  26305.4  0.001161
573  20230524   233000    233959  1684942799  26305.4  26331.9  0.001007
574  20230524   234000    234959  1684943399    26332  26300.3 -0.001200
575  20230524   235000    235959  1684943999  26300.3  26306.9  0.000251
576  20230525   000000    000959  1684944599  26306.9  26285.1 -0.000829
2023-05-25 00:10:01,248:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1521 

self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26285.2', self.close='26190'
127.0.0.1 - - [25/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-25 00:20:06,180:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26285.2', self.close='26190'
2023-05-25 00:20:06,820:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230524   233000    233959  1684942799  26305.4  26331.9  0.001007
574  20230524   234000    234959  1684943399    26332  26300.3 -0.001200
575  20230524   235000    235959  1684943999  26300.3  26306.9  0.000251
576  20230525   000000    000959  1684944599  26306.9  26285.1 -0.000829
577  20230525   001000    001959  1684945199  26285.2    26190 -0.003618
2023-05-25 00:20:06,821:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-05-25 00:00:02,426:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-05-25 00:00:02,528:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:5250000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230524, closeTime:235959, close:26306.9, total:973579.8686232, pct_pre:-0.019635595613066936, thd:-0.4317702165455982, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1523 

self.closeSec=1684944599, self.tradeDate='20230525', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26306.9', self.close='26285.1'
127.0.0.1 - - [25/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-25 00:10:01,232:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684944599, self.tradeDate='20230525', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26306.9', self.close='26285.1'
2023-05-25 00:10:01,275:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230524   232000    232959  1684942199  26274.9  26305.4
17421  20230524   233000    233959  1684942799  26305.4  26331.9
17422  20230524   234000    234959  1684943399    26332  26300.3
17423  20230524   235000    235959  1684943999  26300.3  26306.9
17424  20230525   000000    000959  1684944599  26306.9  26285.1
2023-05-25 00:10:01,277:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1524 

self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26285.2', self.close='26190'
127.0.0.1 - - [25/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-25 00:20:08,106:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26285.2', self.close='26190'
2023-05-25 00:20:08,222:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230524   233000    233959  1684942799  26305.4  26331.9
17422  20230524   234000    234959  1684943399    26332  26300.3
17423  20230524   235000    235959  1684943999  26300.3  26306.9
17424  20230525   000000    000959  1684944599  26306.9  26285.1
17425  20230525   001000    001959  1684945199  26285.2    26190
2023-05-25 00:20:08,222:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [25/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-25 00:00:04,669:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42251F1684944003993I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684944004417146, 'quantity': '47.618', 'price': '26306.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1684944003008, 'updatetime': 1684944004417, 'tradetype': 'usdt', 'selfid': 42251, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684944004417, 'clientorderid': '42251F1684944003993I0L2', 'price': '26306.7', 'quantity': '47.618', 'commission': '1252.6724406', 'commissionasset': 'USDT', 'tradetime': 1684944004417, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684944004417}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1523 

self.closeSec=1684944599, self.tradeDate='20230525', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26306.9', self.close='26285.1'
127.0.0.1 - - [25/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-25 00:10:01,213:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684944599, self.tradeDate='20230525', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26306.9', self.close='26285.1'
2023-05-25 00:10:01,231:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230524   232000    232959  1684942199  26274.9  26305.4
12237  20230524   233000    233959  1684942799  26305.4  26331.9
12238  20230524   234000    234959  1684943399    26332  26300.3
12239  20230524   235000    235959  1684943999  26300.3  26306.9
12240  20230525   000000    000959  1684944599  26306.9  26285.1
2023-05-25 00:10:01,231:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1524 

self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26285.2', self.close='26190'
127.0.0.1 - - [25/May/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-05-25 00:20:07,723:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26285.2', self.close='26190'
2023-05-25 00:20:07,992:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230524   233000    233959  1684942799  26305.4  26331.9
12238  20230524   234000    234959  1684943399    26332  26300.3
12239  20230524   235000    235959  1684943999  26300.3  26306.9
12240  20230525   000000    000959  1684944599  26306.9  26285.1
12241  20230525   001000    001959  1684945199  26285.2    26190
2023-05-25 00:20:07,999:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3040
self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26249.9, self.close=26190.0, self.high=26250.0, self.low=26168.2, self.vol=3848.939, self.amt=100830218.7413 
127.0.0.1 - - [25/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-25 00:20:05,440:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230524   235500    235959  ...         0.0        0.0       0
5760  20230525   000000    000459  ...         0.0        0.0       0
5761  20230525   000500    000959  ...         0.0        0.0       0
5762  20230525   001000    001459  ...         0.0        0.0       0
5763  20230525   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-25 00:20:05,461:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684945199, self.tradeDate='20230525', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26249.9, self.close=26190.0, self.high=26250.0, self.low=26168.2, self.vol=3848.939, self.amt=100830218.7413, ukdf['pct'].iloc[-1]=-0.002286 , ukdf['amount'].iloc[-1]=100830218.7413, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-24011.6565', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26197.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3041
self.closeSec=1684945499, self.tradeDate='20230525', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26190.0, self.close=26228.3, self.high=26240.0, self.low=26190.0, self.vol=1865.197, self.amt=48900056.8748 
127.0.0.1 - - [25/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-25 00:25:00,908:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230525   000000    000459  ...         0.0        0.0       0
5761  20230525   000500    000959  ...         0.0        0.0       0
5762  20230525   001000    001459  ...         0.0        0.0       0
5763  20230525   001500    001959  ...         0.0        0.0       0
5764  20230525   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-25 00:25:00,912:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684945499, self.tradeDate='20230525', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26190.0, self.close=26228.3, self.high=26240.0, self.low=26190.0, self.vol=1865.197, self.amt=48900056.8748, ukdf['pct'].iloc[-1]=0.001462 , ukdf['amount'].iloc[-1]=48900056.8748, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-22807.1678271593', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26229.9301627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230524   120000    155959  1684915199  ...    723  0.351419 -0.259060     NaN
724  20230524   160000    195959  1684929599  ...    724  0.385182 -0.077219     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '17461.26784338615', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26731.76854365', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [25/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=63
self.closeSec=1684943999, self.tradeDate='20230524', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26731.7, self.close=26306.9, self.high=26731.7, self.low=26060.0, self.vol=189840.762, self.amt=5000673894.26554 
2023-05-25 00:00:01,931:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684943999, self.tradeDate='20230524', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26731.7, self.close=26306.9, self.high=26731.7, self.low=26060.0, self.vol=189840.762, self.amt=5000673894.26554 
2023-05-25 00:00:01,955:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230524   040000    075959  ...   21367.419  5.811356e+08  0.001410
722  20230524   080000    115959  ...  105289.512  2.832790e+09 -0.016167
723  20230524   120000    155959  ...   72171.252  1.928814e+09 -0.003952
724  20230524   160000    195959  ...   47356.312  1.265978e+09  0.002531
725  20230524   200000    235959  ...  189840.762  5.000674e+09 -0.015891

[5 rows x 11 columns]
2023-05-25 00:00:04,431:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230524   040000    075959  1684886399  ...    721  0.467182  0.243154     NaN
722  20230524   080000    115959  1684900799  ...    722  0.322284 -0.413415     NaN
723  20230524   120000    155959  1684915199  ...    723  0.351419 -0.259060     NaN
724  20230524   160000    195959  1684929599  ...    724  0.385182 -0.077219     NaN
725  20230524   200000    235959  1684943999  ...    725  0.282606 -0.560483     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '39367.9713', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26306.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


