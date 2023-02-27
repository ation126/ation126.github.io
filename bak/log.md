# 20230228 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [28/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26620
self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23301.4, self.close=23281.0, self.high=23328.0, self.low=23223.6, self.vol=8890.937, self.amt=207057215.3277 
2023-02-28 00:20:01,737:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230227   235500    235959  ...         0.0        0.0       0
5760  20230228   000000    000459  ...         0.0        0.0       0
5761  20230228   000500    000959  ...         0.0        0.0       0
5762  20230228   001000    001459  ...         0.0        0.0       0
5763  20230228   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 00:20:01,738:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23301.4, self.close=23281.0, self.high=23328.0, self.low=23223.6, self.vol=8890.937, self.amt=207057215.3277, ukdf['pct'].iloc[-1]=-0.000528 , ukdf['amount'].iloc[-1]=207057215.3277, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-406284.2816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23280.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26621
self.closeSec=1677515099, self.tradeDate='20230228', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23281.0, self.close=23305.3, self.high=23339.9, self.low=23271.0, self.vol=5495.541, self.amt=128098562.2914 
2023-02-28 00:25:01,645:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230228   000000    000459  ...         0.0        0.0       0
5761  20230228   000500    000959  ...         0.0        0.0       0
5762  20230228   001000    001459  ...         0.0        0.0       0
5763  20230228   001500    001959  ...         0.0        0.0       0
5764  20230228   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 00:25:01,646:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677515099, self.tradeDate='20230228', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23281.0, self.close=23305.3, self.high=23339.9, self.low=23271.0, self.vol=5495.541, self.amt=128098562.2914, ukdf['pct'].iloc[-1]=0.001044 , ukdf['amount'].iloc[-1]=128098562.2914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-407514.47886223088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23301.34332063', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.34982804286773345, self.count=27186 

self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23301.4, self.close=23281.0, self.high=23328.0, self.low=23223.6 
2023-02-28 00:20:01,526:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23301.4, self.close=23281.0, self.high=23328.0, self.low=23223.6   
2023-02-28 00:20:01,584:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230227   235500    235959  1677513599  ...  23501.4  0.000136   1727    5
1440  20230228   000000    000459  1677513899  ...  23537.7  0.001125   1440    0
1441  20230228   000500    000959  1677514199  ...  23536.8 -0.000577   1441    1
1442  20230228   001000    001459  1677514499  ...  23181.4 -0.011291   1442    2
1443  20230228   001500    001959  1677514799  ...  23223.6 -0.000528   1443    3

[5 rows x 11 columns]
2023-02-28 00:20:01,584:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=20, self.factor=0.34982804286773345, self.count=27187 

self.closeSec=1677515099, self.tradeDate='20230228', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23281.0, self.close=23305.3, self.high=23339.9, self.low=23271.0 
2023-02-28 00:25:01,522:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677515099, self.tradeDate='20230228', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23281.0, self.close=23305.3, self.high=23339.9, self.low=23271.0   
2023-02-28 00:25:01,617:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230228   000000    000459  1677513899  ...  23537.7  0.001125   1440    0
1441  20230228   000500    000959  1677514199  ...  23536.8 -0.000577   1441    1
1442  20230228   001000    001459  1677514499  ...  23181.4 -0.011291   1442    2
1443  20230228   001500    001959  1677514799  ...  23223.6 -0.000528   1443    3
1444  20230228   002000    002459  1677515099  ...  23271.0  0.001044   1444    4

[5 rows x 11 columns]
2023-02-28 00:25:01,617:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-28 00:00:41,154:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230227    212959  23394.5  ...  48.333333  0.545496  0.415570
5803  20230227    215959  23549.6  ...  48.333333  0.575425  0.399458
5804  20230227    222959  23696.2  ...  48.750000  0.590554  0.381180
5805  20230227    225959  23778.2  ...  49.166667  0.592700  0.364167
5806  20230227    232959  23790.1  ...  49.583333  0.595012  0.349716

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-02-28 00:00:41,352:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.542554  0.457446       1  ...  0.933300   1.0    0.0  0.962052
540     0  0.549937  0.450063       1  ...  0.936533   1.0    0.0  0.965385
541     0  0.542445  0.457555       1  ...  0.937002   1.0    0.0  0.965868
542     0  0.534186  0.465814       1  ...  0.937502   1.0    0.0  0.966384
543     0  0.535124  0.464876       0  ...  0.927403   1.0    0.0  0.955974

[5 rows x 10 columns]
2023-02-28 00:00:41,390:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.542666  0.457334       1  ...  0.933491   1.0    0.0  0.958084
46     0  0.550479  0.449521       1  ...  0.936725   1.0    0.0  0.966676
47     0  0.543090  0.456910       1  ...  0.937194   1.0    0.0  0.967160
48     0  0.534504  0.465496       1  ...  0.937502   1.0    0.0  0.967597
49     0  0.535124  0.464876       0  ...  0.927403   1.0    0.0  0.955974

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.793', 'enterprice': '23035.2', 'countrevence': '0', 'unrealprofit': '16671.9612', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23543.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [28/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-28 00:00:03,741:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41847F1677513603038I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677513603201170, 'quantity': '43.138', 'price': '23546.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677513602543, 'updatetime': 1677513603201, 'tradetype': 'usdt', 'selfid': 41847, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677513603201, 'clientorderid': '41847F1677513603038I0L59', 'price': '23546.4', 'quantity': '43.138', 'commission': '1015.7446032', 'commissionasset': 'USDT', 'tradetime': 1677513603201, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677513603201}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13592 

self.closeSec=1677514199, self.tradeDate='20230228', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23546.5', self.close='23552.8'
127.0.0.1 - - [28/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-02-28 00:10:01,579:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677514199, self.tradeDate='20230228', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23546.5', self.close='23552.8'
2023-02-28 00:10:01,592:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230227   232000    232959  1677511799  23823.1  23802.8 -0.000785
573  20230227   233000    233959  1677512399  23802.7    23643 -0.006713
574  20230227   234000    234959  1677512999  23642.9  23579.9 -0.002669
575  20230227   235000    235959  1677513599    23580  23546.4 -0.001421
576  20230228   000000    000959  1677514199  23546.5  23552.8  0.000272
2023-02-28 00:10:01,592:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13593 

self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23552.7', self.close='23281'
127.0.0.1 - - [28/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-28 00:20:01,599:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23552.7', self.close='23281'
2023-02-28 00:20:01,618:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230227   233000    233959  1677512399  23802.7    23643 -0.006713
574  20230227   234000    234959  1677512999  23642.9  23579.9 -0.002669
575  20230227   235000    235959  1677513599    23580  23546.4 -0.001421
576  20230228   000000    000959  1677514199  23546.5  23552.8  0.000272
577  20230228   001000    001959  1677514799  23552.7    23281 -0.011540
2023-02-28 00:20:01,619:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [28/Feb/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-02-28 00:00:03,519:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41848F1677513603090I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677513603190949, 'quantity': '41.836', 'price': '23546.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677513602583, 'updatetime': 1677513603190, 'tradetype': 'usdt', 'selfid': 41848, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677513603190, 'clientorderid': '41848F1677513603090I0L57', 'price': '23546.4', 'quantity': '41.836', 'commission': '985.0871904', 'commissionasset': 'USDT', 'tradetime': 1677513603190, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677513603190}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13593 

self.closeSec=1677514199, self.tradeDate='20230228', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23546.5', self.close='23552.8'
2023-02-28 00:10:01,619:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677514199, self.tradeDate='20230228', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23546.5', self.close='23552.8'
2023-02-28 00:10:01,652:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230227   232000    232959  1677511799  23823.1  23802.8
17421  20230227   233000    233959  1677512399  23802.7    23643
17422  20230227   234000    234959  1677512999  23642.9  23579.9
17423  20230227   235000    235959  1677513599    23580  23546.4
17424  20230228   000000    000959  1677514199  23546.5  23552.8
2023-02-28 00:10:01,653:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13594 

self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23552.7', self.close='23281'
2023-02-28 00:20:01,634:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23552.7', self.close='23281'
2023-02-28 00:20:01,645:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230227   233000    233959  1677512399  23802.7    23643
17422  20230227   234000    234959  1677512999  23642.9  23579.9
17423  20230227   235000    235959  1677513599    23580  23546.4
17424  20230228   000000    000959  1677514199  23546.5  23552.8
17425  20230228   001000    001959  1677514799  23552.7    23281
2023-02-28 00:20:01,645:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [28/Feb/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-02-28 00:00:04,148:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41849F1677513603400I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677513603838893, 'quantity': '49.721', 'price': '23546.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1677513602688, 'updatetime': 1677513603838, 'tradetype': 'usdt', 'selfid': 41849, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677513603838, 'clientorderid': '41849F1677513603400I0L2', 'price': '23546.5', 'quantity': '49.721', 'commission': '1170.7555265', 'commissionasset': 'USDT', 'tradetime': 1677513603838, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677513603838}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [28/Feb/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13593 

self.closeSec=1677514199, self.tradeDate='20230228', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23546.5', self.close='23552.8'
2023-02-28 00:10:01,610:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677514199, self.tradeDate='20230228', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23546.5', self.close='23552.8'
2023-02-28 00:10:01,659:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230227   232000    232959  1677511799  23823.1  23802.8
12237  20230227   233000    233959  1677512399  23802.7    23643
12238  20230227   234000    234959  1677512999  23642.9  23579.9
12239  20230227   235000    235959  1677513599    23580  23546.4
12240  20230228   000000    000959  1677514199  23546.5  23552.8
2023-02-28 00:10:01,660:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [28/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13594 

self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23552.7', self.close='23281'
2023-02-28 00:20:01,647:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23552.7', self.close='23281'
2023-02-28 00:20:01,711:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230227   233000    233959  1677512399  23802.7    23643
12238  20230227   234000    234959  1677512999  23642.9  23579.9
12239  20230227   235000    235959  1677513599    23580  23546.4
12240  20230228   000000    000959  1677514199  23546.5  23552.8
12241  20230228   001000    001959  1677514799  23552.7    23281
2023-02-28 00:20:01,712:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22618
self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23301.4, self.close=23281.0, self.high=23328.0, self.low=23223.6, self.vol=8890.937, self.amt=207057215.3277 
127.0.0.1 - - [28/Feb/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-02-28 00:20:01,649:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230227   235500    235959  ...         0.0        0.0       0
5760  20230228   000000    000459  ...         0.0        0.0       0
5761  20230228   000500    000959  ...         0.0        0.0       0
5762  20230228   001000    001459  ...         0.0        0.0       0
5763  20230228   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 00:20:01,656:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677514799, self.tradeDate='20230228', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23301.4, self.close=23281.0, self.high=23328.0, self.low=23223.6, self.vol=8890.937, self.amt=207057215.3277, ukdf['pct'].iloc[-1]=-0.000528 , ukdf['amount'].iloc[-1]=207057215.3277, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [28/Feb/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22619
self.closeSec=1677515099, self.tradeDate='20230228', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23281.0, self.close=23305.3, self.high=23339.9, self.low=23271.0, self.vol=5495.541, self.amt=128098562.2914 
2023-02-28 00:25:01,671:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230228   000000    000459  ...         0.0        0.0       0
5761  20230228   000500    000959  ...         0.0        0.0       0
5762  20230228   001000    001459  ...         0.0        0.0       0
5763  20230228   001500    001959  ...         0.0        0.0       0
5764  20230228   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 00:25:01,672:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677515099, self.tradeDate='20230228', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23281.0, self.close=23305.3, self.high=23339.9, self.low=23271.0, self.vol=5495.541, self.amt=128098562.2914, ukdf['pct'].iloc[-1]=0.001044 , ukdf['amount'].iloc[-1]=128098562.2914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230227   120000    155959  1677484799  ...    723  0.893048  0.580876     NaN
724  20230227   160000    195959  1677499199  ...    724  0.934377  0.683758     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '13126.1048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23420', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=566
self.closeSec=1677513599, self.tradeDate='20230227', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23419.9, self.close=23546.4, self.high=23888.0, self.low=23369.1, self.vol=184984.884, self.amt=4377125257.90307 
127.0.0.1 - - [28/Feb/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-02-28 00:00:01,948:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677513599, self.tradeDate='20230227', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23419.9, self.close=23546.4, self.high=23888.0, self.low=23369.1, self.vol=184984.884, self.amt=4377125257.90307 
2023-02-28 00:00:01,991:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230227   040000    075959  ...  102114.230  2.402483e+09  0.002307
722  20230227   080000    115959  ...   47678.291  1.121959e+09 -0.000183
723  20230227   120000    155959  ...   53778.498  1.260110e+09 -0.005518
724  20230227   160000    195959  ...   46822.503  1.094781e+09  0.000380
725  20230227   200000    235959  ...  184984.884  4.377125e+09  0.005397

[5 rows x 11 columns]
2023-02-28 00:00:04,827:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230227   040000    075959  1677455999  ...    721  0.989702  0.819695     1.0
722  20230227   080000    115959  1677470399  ...    722  0.958338  0.740519     1.0
723  20230227   120000    155959  1677484799  ...    723  0.893048  0.580876     NaN
724  20230227   160000    195959  1677499199  ...    724  0.934377  0.683758     1.0
725  20230227   200000    235959  1677513599  ...    725  0.854884  0.495060     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '18461.7483', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23546.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


