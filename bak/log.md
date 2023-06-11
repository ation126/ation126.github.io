# 20230612 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8224
self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25770.0, self.close=25815.8, self.high=25829.9, self.low=25769.9, self.vol=1769.614, self.amt=45660162.4302 
127.0.0.1 - - [12/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:20:03,769:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230611   235500    235959  ...         0.0        0.0       0
5760  20230612   000000    000459  ...         0.0        0.0       0
5761  20230612   000500    000959  ...         0.0        0.0       0
5762  20230612   001000    001459  ...         0.0        0.0       0
5763  20230612   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 00:20:03,790:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25770.0, self.close=25815.8, self.high=25829.9, self.low=25769.9, self.vol=1769.614, self.amt=45660162.4302, ukdf['pct'].iloc[-1]=0.001781 , ukdf['amount'].iloc[-1]=45660162.4302, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14635.17477820398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25813.97548627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8225
self.closeSec=1686500699, self.tradeDate='20230612', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25813.3, self.close=25849.4, self.high=25887.4, self.low=25799.2, self.vol=4569.608, self.amt=118083049.22868 
127.0.0.1 - - [12/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:25:04,195:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230612   000000    000459  ...         0.0        0.0       0
5761  20230612   000500    000959  ...         0.0        0.0       0
5762  20230612   001000    001459  ...         0.0        0.0       0
5763  20230612   001500    001959  ...         0.0        0.0       0
5764  20230612   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 00:25:04,199:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686500699, self.tradeDate='20230612', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25813.3, self.close=25849.4, self.high=25887.4, self.low=25799.2, self.vol=4569.608, self.amt=118083049.22868, ukdf['pct'].iloc[-1]=0.001302 , ukdf['amount'].iloc[-1]=118083049.22868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '13782.31846770504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25875.21750196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25770.0, self.close=25815.8, self.high=25829.9, self.low=25769.9 
127.0.0.1 - - [12/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:20:01,850:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25770.0, self.close=25815.8, self.high=25829.9, self.low=25769.9   
2023-06-12 00:20:02,809:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230611   235500    235959  1686499199  ...  25732.6  0.000330   1727    5
1440  20230612   000000    000459  1686499499  ...  25726.7  0.000388   1440    0
1441  20230612   000500    000959  1686499799  ...  25751.1  0.000497   1441    1
1442  20230612   001000    001459  1686500099  ...  25753.8  0.000233   1442    2
1443  20230612   001500    001959  1686500399  ...  25769.9  0.001781   1443    3

[5 rows x 11 columns]
2023-06-12 00:20:02,819:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=11, self.factor=0.5661292716968389, self.count=8227 

self.closeSec=1686500699, self.tradeDate='20230612', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25813.3, self.close=25849.4, self.high=25887.4, self.low=25799.2 
127.0.0.1 - - [12/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:25:03,107:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686500699, self.tradeDate='20230612', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25813.3, self.close=25849.4, self.high=25887.4, self.low=25799.2   
2023-06-12 00:25:03,825:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230612   000000    000459  1686499499  ...  25726.7  0.000388   1440    0
1441  20230612   000500    000959  1686499799  ...  25751.1  0.000497   1441    1
1442  20230612   001000    001459  1686500099  ...  25753.8  0.000233   1442    2
1443  20230612   001500    001959  1686500399  ...  25769.9  0.001781   1443    3
1444  20230612   002000    002459  1686500699  ...  25799.2  0.001302   1444    4

[5 rows x 11 columns]
2023-06-12 00:25:03,826:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-12 00:00:36,550:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230611    212959  25740.3  ...  49.583333  0.459349  0.498574
5803  20230611    215959  25741.6  ...  49.166667  0.449564  0.496246
5804  20230611    222959  25693.3  ...  49.166667  0.456607  0.495997
5805  20230611    225959  25721.9  ...  49.166667  0.463009  0.492226
5806  20230611    232959  25748.3  ...  49.583333  0.465647  0.492497

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-06-12 00:00:36,709:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.500967  0.499033       0  ...  0.976320  -1.0    0.0  0.946329
540     1  0.485634  0.514366       1  ...  0.975226  -1.0    0.0  0.947389
541     0  0.502133  0.497867       1  ...  0.974229  -1.0    0.0  0.948358
542     0  0.504969  0.495031       1  ...  0.973820  -1.0    0.0  0.948756
543     0  0.506542  0.493458       0  ...  0.974497  -1.0    0.0  0.948097

[5 rows x 10 columns]
2023-06-12 00:00:36,739:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500900  0.499100       0  ...  0.976320  -1.0    0.0  0.946935
46     1  0.485450  0.514550       1  ...  0.975226  -1.0    0.0  0.947403
47     0  0.502177  0.497823       1  ...  0.974229  -1.0    0.0  0.948372
48     0  0.504829  0.495171       1  ...  0.973820  -1.0    0.0  0.948145
49     0  0.506542  0.493458       0  ...  0.974497  -1.0    0.0  0.948097

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-5277.13628408018', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25744.55822941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [12/Jun/2023 00:00:05] "POST / HTTP/1.1" 200 -
2023-06-12 00:00:05,103:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42371F1686499204153I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686499204619417, 'quantity': '28.147', 'price': '25741', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686499203085, 'updatetime': 1686499204619, 'tradetype': 'usdt', 'selfid': 42371, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686499204619, 'clientorderid': '42371F1686499204153I0L59', 'price': '25741', 'quantity': '28.147', 'commission': '724.531927', 'commissionasset': 'USDT', 'tradetime': 1686499204619, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686499204619}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4112 

self.closeSec=1686499799, self.tradeDate='20230612', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25741.1', self.close='25763.9'
2023-06-12 00:10:01,097:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686499799, self.tradeDate='20230612', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25741.1', self.close='25763.9'
127.0.0.1 - - [12/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:10:01,196:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230611   232000    232959  1686497399  25739.9  25759.1  0.000746
573  20230611   233000    233959  1686497999  25759.1  25746.9 -0.000474
574  20230611   234000    234959  1686498599  25746.9  25753.6  0.000260
575  20230611   235000    235959  1686499199  25753.7  25741.2 -0.000481
576  20230612   000000    000959  1686499799  25741.1  25763.9  0.000882
2023-06-12 00:10:01,196:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4113 

self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25764', self.close='25815.8'
127.0.0.1 - - [12/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-12 00:20:05,010:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25764', self.close='25815.8'
2023-06-12 00:20:05,669:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230611   233000    233959  1686497999  25759.1  25746.9 -0.000474
574  20230611   234000    234959  1686498599  25746.9  25753.6  0.000260
575  20230611   235000    235959  1686499199  25753.7  25741.2 -0.000481
576  20230612   000000    000959  1686499799  25741.1  25763.9  0.000882
577  20230612   001000    001959  1686500399    25764  25815.8  0.002014
2023-06-12 00:20:05,670:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [12/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-12 00:00:04,561:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42370F1686499203985I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686499204355949, 'quantity': '38.366', 'price': '25741.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686499203103, 'updatetime': 1686499204355, 'tradetype': 'usdt', 'selfid': 42370, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686499204355, 'clientorderid': '42370F1686499203985I0L57', 'price': '25741.1', 'quantity': '38.366', 'commission': '987.5830426', 'commissionasset': 'USDT', 'tradetime': 1686499204355, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686499204355}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4115 

self.closeSec=1686499799, self.tradeDate='20230612', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25741.1', self.close='25763.9'
2023-06-12 00:10:01,126:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686499799, self.tradeDate='20230612', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25741.1', self.close='25763.9'
2023-06-12 00:10:01,201:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230611   232000    232959  1686497399  25739.9  25759.1
17421  20230611   233000    233959  1686497999  25759.1  25746.9
17422  20230611   234000    234959  1686498599  25746.9  25753.6
17423  20230611   235000    235959  1686499199  25753.7  25741.2
17424  20230612   000000    000959  1686499799  25741.1  25763.9
2023-06-12 00:10:01,201:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4116 

self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25764', self.close='25815.8'
127.0.0.1 - - [12/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-12 00:20:06,789:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25764', self.close='25815.8'
2023-06-12 00:20:06,929:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230611   233000    233959  1686497999  25759.1  25746.9
17422  20230611   234000    234959  1686498599  25746.9  25753.6
17423  20230611   235000    235959  1686499199  25753.7  25741.2
17424  20230612   000000    000959  1686499799  25741.1  25763.9
17425  20230612   001000    001959  1686500399    25764  25815.8
2023-06-12 00:20:06,929:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-06-12 00:00:04,835:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42372F1686499204192I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686499204571789, 'quantity': '49.589', 'price': '25741.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686499203195, 'updatetime': 1686499204571, 'tradetype': 'usdt', 'selfid': 42372, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686499204571, 'clientorderid': '42372F1686499204192I0L2', 'price': '25741.1', 'quantity': '49.589', 'commission': '1276.4754079', 'commissionasset': 'USDT', 'tradetime': 1686499204571, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686499204571}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [12/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4115 

self.closeSec=1686499799, self.tradeDate='20230612', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25741.1', self.close='25763.9'
127.0.0.1 - - [12/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:10:01,151:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686499799, self.tradeDate='20230612', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25741.1', self.close='25763.9'
2023-06-12 00:10:01,203:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230611   232000    232959  1686497399  25739.9  25759.1
12237  20230611   233000    233959  1686497999  25759.1  25746.9
12238  20230611   234000    234959  1686498599  25746.9  25753.6
12239  20230611   235000    235959  1686499199  25753.7  25741.2
12240  20230612   000000    000959  1686499799  25741.1  25763.9
2023-06-12 00:10:01,203:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4116 

self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25764', self.close='25815.8'
127.0.0.1 - - [12/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-12 00:20:06,536:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25764', self.close='25815.8'
2023-06-12 00:20:06,797:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230611   233000    233959  1686497999  25759.1  25746.9
12238  20230611   234000    234959  1686498599  25746.9  25753.6
12239  20230611   235000    235959  1686499199  25753.7  25741.2
12240  20230612   000000    000959  1686499799  25741.1  25763.9
12241  20230612   001000    001959  1686500399    25764  25815.8
2023-06-12 00:20:06,798:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [12/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8224
self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25770.0, self.close=25815.8, self.high=25829.9, self.low=25769.9, self.vol=1769.614, self.amt=45660162.4302 
2023-06-12 00:20:03,670:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230611   235500    235959  ...         0.0        0.0       0
5760  20230612   000000    000459  ...         0.0        0.0       0
5761  20230612   000500    000959  ...         0.0        0.0       0
5762  20230612   001000    001459  ...         0.0        0.0       0
5763  20230612   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 00:20:03,710:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686500399, self.tradeDate='20230612', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25770.0, self.close=25815.8, self.high=25829.9, self.low=25769.9, self.vol=1769.614, self.amt=45660162.4302, ukdf['pct'].iloc[-1]=0.001781 , ukdf['amount'].iloc[-1]=45660162.4302, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-38256.14046444593', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25813.97548627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8225
self.closeSec=1686500699, self.tradeDate='20230612', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25813.3, self.close=25849.4, self.high=25887.4, self.low=25799.2, self.vol=4569.608, self.amt=118083049.22868 
127.0.0.1 - - [12/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:25:04,187:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230612   000000    000459  ...         0.0        0.0       0
5761  20230612   000500    000959  ...         0.0        0.0       0
5762  20230612   001000    001459  ...         0.0        0.0       0
5763  20230612   001500    001959  ...         0.0        0.0       0
5764  20230612   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-12 00:25:04,196:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686500699, self.tradeDate='20230612', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25813.3, self.close=25849.4, self.high=25887.4, self.low=25799.2, self.vol=4569.608, self.amt=118083049.22868, ukdf['pct'].iloc[-1]=0.001302 , ukdf['amount'].iloc[-1]=118083049.22868, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-35981.55075970364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25875.21750196', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230611   120000    155959  1686470399  ...    723  0.458586 -0.439942     NaN
724  20230611   160000    195959  1686484799  ...    724  0.477919 -0.376401     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '71324.1214', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25785.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=171
self.closeSec=1686499199, self.tradeDate='20230611', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25784.9, self.close=25741.2, self.high=25795.4, self.low=25661.0, self.vol=28819.212, self.amt=741748742.8602 
127.0.0.1 - - [12/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-12 00:00:01,889:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686499199, self.tradeDate='20230611', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25784.9, self.close=25741.2, self.high=25795.4, self.low=25661.0, self.vol=28819.212, self.amt=741748742.8602 
2023-06-12 00:00:01,943:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230611   040000    075959  ...  46686.517  1.203926e+09  0.003435
722  20230611   080000    115959  ...  33043.104  8.513945e+08 -0.004333
723  20230611   120000    155959  ...  31162.773  8.018352e+08  0.000517
724  20230611   160000    195959  ...  25758.698  6.632785e+08  0.002212
725  20230611   200000    235959  ...  28819.212  7.417487e+08 -0.001695

[5 rows x 11 columns]
2023-06-12 00:00:04,705:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230611   040000    075959  1686441599  ...    721  0.517683 -0.254692     NaN
722  20230611   080000    115959  1686455999  ...    722  0.496457 -0.320242     NaN
723  20230611   120000    155959  1686470399  ...    723  0.458586 -0.439942     NaN
724  20230611   160000    195959  1686484799  ...    724  0.477919 -0.376401     NaN
725  20230611   200000    235959  1686499199  ...    725  0.493000 -0.328305     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '73771.96337742392', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25741.32770588', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


