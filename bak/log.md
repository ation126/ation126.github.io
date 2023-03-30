# 20230331 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35548
self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28169.9, self.close=28111.8, self.high=28196.3, self.low=28022.0, self.vol=11530.007, self.amt=324064301.78114 
127.0.0.1 - - [31/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-31 00:20:08,388:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230330   235500    235959  ...         0.0        0.0       0
5760  20230331   000000    000459  ...         0.0        0.0       0
5761  20230331   000500    000959  ...         0.0        0.0       0
5762  20230331   001000    001459  ...         0.0        0.0       0
5763  20230331   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 00:20:08,408:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28169.9, self.close=28111.8, self.high=28196.3, self.low=28022.0, self.vol=11530.007, self.amt=324064301.78114, ukdf['pct'].iloc[-1]=-0.001928 , ukdf['amount'].iloc[-1]=324064301.78114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695171.86267652704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28081.61093254', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35549
self.closeSec=1680193499, self.tradeDate='20230331', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28107.6, self.close=28114.4, self.high=28150.7, self.low=28033.4, self.vol=6770.596, self.amt=190278817.2658 
127.0.0.1 - - [31/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-31 00:25:01,628:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230331   000000    000459  ...         0.0        0.0       0
5761  20230331   000500    000959  ...         0.0        0.0       0
5762  20230331   001000    001459  ...         0.0        0.0       0
5763  20230331   001500    001959  ...         0.0        0.0       0
5764  20230331   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 00:25:01,628:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680193499, self.tradeDate='20230331', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28107.6, self.close=28114.4, self.high=28150.7, self.low=28033.4, self.vol=6770.596, self.amt=190278817.2658, ukdf['pct'].iloc[-1]=9.2e-05 , ukdf['amount'].iloc[-1]=190278817.2658, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-697144.9776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28114.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28169.9, self.close=28111.8, self.high=28196.3, self.low=28022.0 
127.0.0.1 - - [31/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-31 00:20:05,509:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28169.9, self.close=28111.8, self.high=28196.3, self.low=28022.0   
2023-03-31 00:20:06,619:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230330   235500    235959  1680191999  ...  28223.1  0.001406   1727    5
1440  20230331   000000    000459  1680192299  ...  28235.6 -0.001580   1440    0
1441  20230331   000500    000959  1680192599  ...  28150.0 -0.000205   1441    1
1442  20230331   001000    001459  1680192899  ...  28130.0 -0.002408   1442    2
1443  20230331   001500    001959  1680193199  ...  28022.0 -0.001928   1443    3

[5 rows x 11 columns]
2023-03-31 00:20:06,628:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=40, self.factor=0.403173879736589, self.count=36115 

self.closeSec=1680193499, self.tradeDate='20230331', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28107.6, self.close=28114.4, self.high=28150.7, self.low=28033.4 
2023-03-31 00:25:01,533:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680193499, self.tradeDate='20230331', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28107.6, self.close=28114.4, self.high=28150.7, self.low=28033.4   
2023-03-31 00:25:01,626:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230331   000000    000459  1680192299  ...  28235.6 -0.001580   1440    0
1441  20230331   000500    000959  1680192599  ...  28150.0 -0.000205   1441    1
1442  20230331   001000    001459  1680192899  ...  28130.0 -0.002408   1442    2
1443  20230331   001500    001959  1680193199  ...  28022.0 -0.001928   1443    3
1444  20230331   002000    002459  1680193499  ...  28033.4  0.000092   1444    4

[5 rows x 11 columns]
2023-03-31 00:25:01,626:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-31 00:00:34,907:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230330    212959  28630.3  ...  52.083333  0.555927  0.455479
5803  20230330    215959  28555.9  ...  51.666667  0.548208  0.465747
5804  20230330    222959  28504.9  ...  51.250000  0.531636  0.482278
5805  20230330    225959  28386.2  ...  51.666667  0.535482  0.495842
5806  20230330    232959  28417.6  ...  51.250000  0.524804  0.513030

[5 rows x 33 columns]
0.5165441176470589
acc is : 0.5165441176470589
2023-03-31 00:00:35,058:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.499703  0.500297       0  ...  0.989589   1.0    0.0  1.057096
540     0  0.500386  0.499614       0  ...  0.985541   1.0    0.0  1.052772
541     1  0.481644  0.518356       1  ...  0.986628   1.0    0.0  1.053932
542     0  0.517233  0.482767       0  ...  0.983989   1.0    0.0  1.051114
543     1  0.486586  0.513414       0  ...  0.982010   1.0    0.0  1.049000

[5 rows x 10 columns]
2023-03-31 00:00:35,089:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500018  0.499982       0  ...  0.989589   1.0    0.0  1.056790
46     0  0.501966  0.498034       0  ...  0.985541   1.0    0.0  1.054226
47     1  0.483503  0.516497       1  ...  0.986628   1.0    0.0  1.055388
48     0  0.518158  0.481842       0  ...  0.983989   1.0    0.0  1.051886
49     1  0.486586  0.513414       0  ...  0.982010   1.0    0.0  1.049000

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [31/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-31 00:00:03,189:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42081F1680192002558I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680192002697198, 'quantity': '25.917', 'price': '28278.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680192002205, 'updatetime': 1680192002697, 'tradetype': 'usdt', 'selfid': 42081, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680192002697, 'clientorderid': '42081F1680192002558I0L59', 'price': '28278.5', 'quantity': '25.917', 'commission': '732.8938845', 'commissionasset': 'USDT', 'tradetime': 1680192002697, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680192002697}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18056 

self.closeSec=1680192599, self.tradeDate='20230331', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28282.8', self.close='28234'
127.0.0.1 - - [31/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-31 00:10:01,605:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680192599, self.tradeDate='20230331', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28282.8', self.close='28234'
2023-03-31 00:10:01,633:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230330   232000    232959  1680190199  28448.9  28341.6 -0.003772
573  20230330   233000    233959  1680190799  28341.7  28317.1 -0.000864
574  20230330   234000    234959  1680191399  28317.2  28224.1 -0.003284
575  20230330   235000    235959  1680191999  28224.1  28282.8  0.002080
576  20230331   000000    000959  1680192599  28282.8    28234 -0.001725
2023-03-31 00:10:01,637:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18057 

self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28234.1', self.close='28111.8'
127.0.0.1 - - [31/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 00:20:07,479:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28234.1', self.close='28111.8'
2023-03-31 00:20:08,189:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230330   233000    233959  1680190799  28341.7  28317.1 -0.000864
574  20230330   234000    234959  1680191399  28317.2  28224.1 -0.003284
575  20230330   235000    235959  1680191999  28224.1  28282.8  0.002080
576  20230331   000000    000959  1680192599  28282.8    28234 -0.001725
577  20230331   001000    001959  1680193199  28234.1  28111.8 -0.004328
2023-03-31 00:20:08,189:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [31/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
2023-03-31 00:00:02,994:INFO:pyemd2:main.py:303:handleOrderFilled:185189: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42082F1680192002578I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680192002687712, 'quantity': '35.624', 'price': '28278.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680192002221, 'updatetime': 1680192002687, 'tradetype': 'usdt', 'selfid': 42082, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680192002687, 'clientorderid': '42082F1680192002578I0L57', 'price': '28278.5', 'quantity': '35.624', 'commission': '1007.393284', 'commissionasset': 'USDT', 'tradetime': 1680192002687, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680192002687}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18057 

self.closeSec=1680192599, self.tradeDate='20230331', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28282.8', self.close='28234'
127.0.0.1 - - [31/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-31 00:10:01,604:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680192599, self.tradeDate='20230331', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28282.8', self.close='28234'
2023-03-31 00:10:01,656:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230330   232000    232959  1680190199  28448.9  28341.6
17421  20230330   233000    233959  1680190799  28341.7  28317.1
17422  20230330   234000    234959  1680191399  28317.2  28224.1
17423  20230330   235000    235959  1680191999  28224.1  28282.8
17424  20230331   000000    000959  1680192599  28282.8    28234
2023-03-31 00:10:01,656:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18058 

self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28234.1', self.close='28111.8'
127.0.0.1 - - [31/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 00:20:10,455:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28234.1', self.close='28111.8'
2023-03-31 00:20:10,604:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230330   233000    233959  1680190799  28341.7  28317.1
17422  20230330   234000    234959  1680191399  28317.2  28224.1
17423  20230330   235000    235959  1680191999  28224.1  28282.8
17424  20230331   000000    000959  1680192599  28282.8    28234
17425  20230331   001000    001959  1680193199  28234.1  28111.8
2023-03-31 00:20:10,605:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [31/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-31 00:00:03,530:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42083F1680192002685I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680192002833551, 'quantity': '45.429', 'price': '28278.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680192002277, 'updatetime': 1680192002833, 'tradetype': 'usdt', 'selfid': 42083, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680192002833, 'clientorderid': '42083F1680192002685I0L2', 'price': '28278.5', 'quantity': '45.429', 'commission': '1284.6639765', 'commissionasset': 'USDT', 'tradetime': 1680192002833, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680192002833}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [31/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18057 

self.closeSec=1680192599, self.tradeDate='20230331', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28282.8', self.close='28234'
2023-03-31 00:10:01,612:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680192599, self.tradeDate='20230331', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28282.8', self.close='28234'
2023-03-31 00:10:01,655:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230330   232000    232959  1680190199  28448.9  28341.6
12237  20230330   233000    233959  1680190799  28341.7  28317.1
12238  20230330   234000    234959  1680191399  28317.2  28224.1
12239  20230330   235000    235959  1680191999  28224.1  28282.8
12240  20230331   000000    000959  1680192599  28282.8    28234
2023-03-31 00:10:01,656:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18058 

self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28234.1', self.close='28111.8'
127.0.0.1 - - [31/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 00:20:09,872:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28234.1', self.close='28111.8'
2023-03-31 00:20:10,189:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230330   233000    233959  1680190799  28341.7  28317.1
12238  20230330   234000    234959  1680191399  28317.2  28224.1
12239  20230330   235000    235959  1680191999  28224.1  28282.8
12240  20230331   000000    000959  1680192599  28282.8    28234
12241  20230331   001000    001959  1680193199  28234.1  28111.8
2023-03-31 00:20:10,189:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31546
self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28169.9, self.close=28111.8, self.high=28196.3, self.low=28022.0, self.vol=11530.007, self.amt=324064301.78114 
127.0.0.1 - - [31/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-31 00:20:06,399:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230330   235500    235959  ...         0.0        0.0       0
5760  20230331   000000    000459  ...         0.0        0.0       0
5761  20230331   000500    000959  ...         0.0        0.0       0
5762  20230331   001000    001459  ...         0.0        0.0       0
5763  20230331   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 00:20:06,419:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680193199, self.tradeDate='20230331', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28169.9, self.close=28111.8, self.high=28196.3, self.low=28022.0, self.vol=11530.007, self.amt=324064301.78114, ukdf['pct'].iloc[-1]=-0.001928 , ukdf['amount'].iloc[-1]=324064301.78114, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [31/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31547
self.closeSec=1680193499, self.tradeDate='20230331', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28107.6, self.close=28114.4, self.high=28150.7, self.low=28033.4, self.vol=6770.596, self.amt=190278817.2658 
2023-03-31 00:25:01,599:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230331   000000    000459  ...         0.0        0.0       0
5761  20230331   000500    000959  ...         0.0        0.0       0
5762  20230331   001000    001459  ...         0.0        0.0       0
5763  20230331   001500    001959  ...         0.0        0.0       0
5764  20230331   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 00:25:01,600:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680193499, self.tradeDate='20230331', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28107.6, self.close=28114.4, self.high=28150.7, self.low=28033.4, self.vol=6770.596, self.amt=190278817.2658, ukdf['pct'].iloc[-1]=9.2e-05 , ukdf['amount'].iloc[-1]=190278817.2658, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230330   120000    155959  1680163199  ...    723  0.568499  0.298260     NaN
724  20230330   160000    195959  1680177599  ...    724  0.578144  0.346862     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-29144.73991802214', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28633.77195319', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [31/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=752
self.closeSec=1680191999, self.tradeDate='20230330', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28630.0, self.close=28284.6, self.high=28683.5, self.low=28146.4, self.vol=132432.531, self.amt=3763736167.76574 
2023-03-31 00:00:01,797:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680191999, self.tradeDate='20230330', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28630.0, self.close=28284.6, self.high=28683.5, self.low=28146.4, self.vol=132432.531, self.amt=3763736167.76574 
2023-03-31 00:00:01,834:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230330   040000    075959  ...   59350.476  1.683516e+09 -0.002380
722  20230330   080000    115959  ...  244943.146  7.017047e+09  0.004658
723  20230330   120000    155959  ...   79859.667  2.284422e+09  0.008293
724  20230330   160000    195959  ...   63603.014  1.818524e+09 -0.002665
725  20230330   200000    235959  ...  132432.531  3.763736e+09 -0.012068

[5 rows x 11 columns]
2023-03-31 00:00:04,506:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230330   040000    075959  1680134399  ...    721  0.463239 -0.015555     NaN
722  20230330   080000    115959  1680148799  ...    722  0.546246  0.218175     NaN
723  20230330   120000    155959  1680163199  ...    723  0.568499  0.298260     NaN
724  20230330   160000    195959  1680177599  ...    724  0.578144  0.346862     NaN
725  20230330   200000    235959  1680191999  ...    725  0.600231  0.430188     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-10514.157885', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28286.8725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


