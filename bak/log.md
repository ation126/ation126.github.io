# 20230611 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7936
self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25586.6, self.close=25600.0, self.high=25604.0, self.low=25575.6, self.vol=938.929, self.amt=24030052.5056 
127.0.0.1 - - [11/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:20:04,366:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230610   235500    235959  ...         0.0        0.0       0
5760  20230611   000000    000459  ...         0.0        0.0       0
5761  20230611   000500    000959  ...         0.0        0.0       0
5762  20230611   001000    001459  ...         0.0        0.0       0
5763  20230611   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 00:20:04,388:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25586.6, self.close=25600.0, self.high=25604.0, self.low=25575.6, self.vol=938.929, self.amt=24030052.5056, ukdf['pct'].iloc[-1]=0.000528 , ukdf['amount'].iloc[-1]=24030052.5056, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '17587.1454', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25602', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7937
self.closeSec=1686414299, self.tradeDate='20230611', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25599.9, self.close=25602.0, self.high=25605.0, self.low=25589.0, self.vol=543.288, self.amt=13907746.2676 
127.0.0.1 - - [11/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:25:04,474:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230611   000000    000459  ...         0.0        0.0       0
5761  20230611   000500    000959  ...         0.0        0.0       0
5762  20230611   001000    001459  ...         0.0        0.0       0
5763  20230611   001500    001959  ...         0.0        0.0       0
5764  20230611   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 00:25:04,491:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686414299, self.tradeDate='20230611', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25599.9, self.close=25602.0, self.high=25605.0, self.low=25589.0, self.vol=543.288, self.amt=13907746.2676, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=13907746.2676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '17567.649', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25603.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25586.6, self.close=25600.0, self.high=25604.0, self.low=25575.6 
127.0.0.1 - - [11/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:20:02,417:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25586.6, self.close=25600.0, self.high=25604.0, self.low=25575.6   
2023-06-11 00:20:03,667:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230610   235500    235959  1686412799  ...  25609.1  0.000156   1727    5
1440  20230611   000000    000459  1686413099  ...  25596.3  0.000207   1440    0
1441  20230611   000500    000959  1686413399  ...  25601.3 -0.000363   1441    1
1442  20230611   001000    001459  1686413699  ...  25575.9 -0.001152   1442    2
1443  20230611   001500    001959  1686413999  ...  25575.6  0.000528   1443    3

[5 rows x 11 columns]
2023-06-11 00:20:03,677:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7077336387595538, self.count=7939 

self.closeSec=1686414299, self.tradeDate='20230611', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25599.9, self.close=25602.0, self.high=25605.0, self.low=25589.0 
127.0.0.1 - - [11/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:25:03,302:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686414299, self.tradeDate='20230611', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25599.9, self.close=25602.0, self.high=25605.0, self.low=25589.0   
2023-06-11 00:25:04,071:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230611   000000    000459  1686413099  ...  25596.3  0.000207   1440    0
1441  20230611   000500    000959  1686413399  ...  25601.3 -0.000363   1441    1
1442  20230611   001000    001459  1686413699  ...  25575.9 -0.001152   1442    2
1443  20230611   001500    001959  1686413999  ...  25575.6  0.000528   1443    3
1444  20230611   002000    002459  1686414299  ...  25589.0  0.000078   1444    4

[5 rows x 11 columns]
2023-06-11 00:25:04,073:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-11 00:00:37,294:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230610    212959  25602.0  ...  50.416667  0.390416  0.797253
5803  20230610    215959  25647.4  ...  50.000000  0.390056  0.798430
5804  20230610    222959  25645.0  ...  49.583333  0.388944  0.799979
5805  20230610    225959  25637.6  ...  49.583333  0.393655  0.800221
5806  20230610    232959  25657.1  ...  50.000000  0.394217  0.800305

[5 rows x 33 columns]
0.5183823529411765
acc is : 0.5183823529411765
2023-06-11 00:00:37,478:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.507703  0.492297       0  ...  1.023222  -1.0    0.0  0.925107
540     0  0.500690  0.499310       0  ...  1.023513  -1.0    0.0  0.924844
541     1  0.495222  0.504778       1  ...  1.022735  -1.0    0.0  0.925547
542     0  0.510659  0.489341       1  ...  1.022643  -1.0    0.0  0.925630
543     0  0.510193  0.489807       0  ...  1.024213  -1.0    0.0  0.924209

[5 rows x 10 columns]
2023-06-11 00:00:37,516:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.507722  0.492278       0  ...  1.023222  -1.0    0.0  0.923525
46     0  0.500694  0.499306       0  ...  1.023513  -1.0    0.0  0.922717
47     1  0.495252  0.504748       1  ...  1.022735  -1.0    0.0  0.923419
48     0  0.510621  0.489379       1  ...  1.022643  -1.0    0.0  0.923741
49     0  0.510193  0.489807       0  ...  1.024213  -1.0    0.0  0.924209

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.53', 'enterprice': '25699.9', 'countrevence': '0', 'unrealprofit': '2344.578276294', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25617.7206002', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [11/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-11 00:00:04,288:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42361F1686412803598I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686412803963285, 'quantity': '26.761', 'price': '25620', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686412802713, 'updatetime': 1686412803963, 'tradetype': 'usdt', 'selfid': 42361, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686412803963, 'clientorderid': '42361F1686412803598I0L59', 'price': '25620', 'quantity': '26.761', 'commission': '685.61682', 'commissionasset': 'USDT', 'tradetime': 1686412803963, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686412803963}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3968 

self.closeSec=1686413399, self.tradeDate='20230611', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25619.9', self.close='25616'
127.0.0.1 - - [11/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:10:01,154:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686413399, self.tradeDate='20230611', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25619.9', self.close='25616'
2023-06-11 00:10:01,178:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230610   232000    232959  1686410999  25662.4  25659.4 -0.000117
573  20230610   233000    233959  1686411599  25659.4  25628.1 -0.001220
574  20230610   234000    234959  1686412199    25628  25634.5  0.000250
575  20230610   235000    235959  1686412799  25634.5    25620 -0.000566
576  20230611   000000    000959  1686413399  25619.9    25616 -0.000156
2023-06-11 00:10:01,178:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3969 

self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25616', self.close='25600'
127.0.0.1 - - [11/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-11 00:20:04,528:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25616', self.close='25600'
2023-06-11 00:20:04,852:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230610   233000    233959  1686411599  25659.4  25628.1 -0.001220
574  20230610   234000    234959  1686412199    25628  25634.5  0.000250
575  20230610   235000    235959  1686412799  25634.5    25620 -0.000566
576  20230611   000000    000959  1686413399  25619.9    25616 -0.000156
577  20230611   001000    001959  1686413999    25616    25600 -0.000625
2023-06-11 00:20:04,852:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-11 00:00:02,190:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-11 00:00:02,324:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6110000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230610, closeTime:235959, close:25620, total:986921.7718383, pct_pre:-0.03231101903112232, thd:-0.3531831443705867, side:sell 
127.0.0.1 - - [11/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3971 

self.closeSec=1686413399, self.tradeDate='20230611', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25619.9', self.close='25616'
2023-06-11 00:10:01,142:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686413399, self.tradeDate='20230611', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25619.9', self.close='25616'
2023-06-11 00:10:01,162:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230610   232000    232959  1686410999  25662.4  25659.4
17421  20230610   233000    233959  1686411599  25659.4  25628.1
17422  20230610   234000    234959  1686412199    25628  25634.5
17423  20230610   235000    235959  1686412799  25634.5    25620
17424  20230611   000000    000959  1686413399  25619.9    25616
2023-06-11 00:10:01,163:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3972 

self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25616', self.close='25600'
127.0.0.1 - - [11/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-11 00:20:05,329:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25616', self.close='25600'
2023-06-11 00:20:05,337:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230610   233000    233959  1686411599  25659.4  25628.1
17422  20230610   234000    234959  1686412199    25628  25634.5
17423  20230610   235000    235959  1686412799  25634.5    25620
17424  20230611   000000    000959  1686413399  25619.9    25616
17425  20230611   001000    001959  1686413999    25616    25600
2023-06-11 00:20:05,337:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [11/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-11 00:00:04,619:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42362F1686412803667I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686412804063754, 'quantity': '46.953', 'price': '25620', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686412802805, 'updatetime': 1686412804063, 'tradetype': 'usdt', 'selfid': 42362, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686412804063, 'clientorderid': '42362F1686412803667I0L2', 'price': '25620', 'quantity': '46.953', 'commission': '1202.93586', 'commissionasset': 'USDT', 'tradetime': 1686412804063, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686412804063}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3971 

self.closeSec=1686413399, self.tradeDate='20230611', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25619.9', self.close='25616'
2023-06-11 00:10:01,170:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686413399, self.tradeDate='20230611', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25619.9', self.close='25616'
127.0.0.1 - - [11/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:10:01,185:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230610   232000    232959  1686410999  25662.4  25659.4
12237  20230610   233000    233959  1686411599  25659.4  25628.1
12238  20230610   234000    234959  1686412199    25628  25634.5
12239  20230610   235000    235959  1686412799  25634.5    25620
12240  20230611   000000    000959  1686413399  25619.9    25616
2023-06-11 00:10:01,185:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3972 

self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25616', self.close='25600'
127.0.0.1 - - [11/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-11 00:20:04,992:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25616', self.close='25600'
2023-06-11 00:20:05,070:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230610   233000    233959  1686411599  25659.4  25628.1
12238  20230610   234000    234959  1686412199    25628  25634.5
12239  20230610   235000    235959  1686412799  25634.5    25620
12240  20230611   000000    000959  1686413399  25619.9    25616
12241  20230611   001000    001959  1686413999    25616    25600
2023-06-11 00:20:05,070:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7936
self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25586.6, self.close=25600.0, self.high=25604.0, self.low=25575.6, self.vol=938.929, self.amt=24030052.5056 
127.0.0.1 - - [11/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:20:04,473:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230610   235500    235959  ...         0.0        0.0       0
5760  20230611   000000    000459  ...         0.0        0.0       0
5761  20230611   000500    000959  ...         0.0        0.0       0
5762  20230611   001000    001459  ...         0.0        0.0       0
5763  20230611   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 00:20:04,487:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686413999, self.tradeDate='20230611', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25586.6, self.close=25600.0, self.high=25604.0, self.low=25575.6, self.vol=938.929, self.amt=24030052.5056, ukdf['pct'].iloc[-1]=0.000528 , ukdf['amount'].iloc[-1]=24030052.5056, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-46129.122', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25602', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7937
self.closeSec=1686414299, self.tradeDate='20230611', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25599.9, self.close=25602.0, self.high=25605.0, self.low=25589.0, self.vol=543.288, self.amt=13907746.2676 
127.0.0.1 - - [11/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-11 00:25:04,452:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230611   000000    000459  ...         0.0        0.0       0
5761  20230611   000500    000959  ...         0.0        0.0       0
5762  20230611   001000    001459  ...         0.0        0.0       0
5763  20230611   001500    001959  ...         0.0        0.0       0
5764  20230611   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-11 00:25:04,465:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686414299, self.tradeDate='20230611', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25599.9, self.close=25602.0, self.high=25605.0, self.low=25589.0, self.vol=543.288, self.amt=13907746.2676, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=13907746.2676, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-46077.1246', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25603.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230610   120000    155959  1686383999  ...    723  0.324140 -0.931206    -1.0
724  20230610   160000    195959  1686398399  ...    724  0.343188 -0.854035    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '75248.89619422918', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25714.55518627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [11/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=165
self.closeSec=1686412799, self.tradeDate='20230610', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25718.7, self.close=25620.0, self.high=25718.7, self.low=25559.5, self.vol=36077.085, self.amt=924855922.7235 
2023-06-11 00:00:01,748:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686412799, self.tradeDate='20230610', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25718.7, self.close=25620.0, self.high=25718.7, self.low=25559.5, self.vol=36077.085, self.amt=924855922.7235 
2023-06-11 00:00:01,818:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230610   040000    075959  ...   17679.394  4.676059e+08  0.002580
722  20230610   080000    115959  ...   53810.499  1.419281e+09 -0.005871
723  20230610   120000    155959  ...  239102.737  6.149956e+09 -0.025668
724  20230610   160000    195959  ...   45062.365  1.155978e+09  0.003175
725  20230610   200000    235959  ...   36077.085  9.248559e+08 -0.003838

[5 rows x 11 columns]
2023-06-11 00:00:04,421:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230610   040000    075959  1686355199  ...    721  0.589680 -0.064565     NaN
722  20230610   080000    115959  1686369599  ...    722  0.535291 -0.243040     NaN
723  20230610   120000    155959  1686383999  ...    723  0.324140 -0.931206    -1.0
724  20230610   160000    195959  1686398399  ...    724  0.343188 -0.854035    -1.0
725  20230610   200000    235959  1686412799  ...    725  0.358009 -0.793134    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '80465.1276', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25620', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


