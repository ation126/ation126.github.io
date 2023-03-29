# 20230330 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35260
self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28355.2, self.close=28346.3, self.high=28369.9, self.low=28302.0, self.vol=1759.411, self.amt=49849503.2212 
127.0.0.1 - - [30/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-30 00:20:08,783:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230329   235500    235959  ...         0.0        0.0       0
5760  20230330   000000    000459  ...         0.0        0.0       0
5761  20230330   000500    000959  ...         0.0        0.0       0
5762  20230330   001000    001459  ...         0.0        0.0       0
5763  20230330   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 00:20:08,803:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28355.2, self.close=28346.3, self.high=28369.9, self.low=28302.0, self.vol=1759.411, self.amt=49849503.2212, ukdf['pct'].iloc[-1]=-0.000222 , ukdf['amount'].iloc[-1]=49849503.2212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-711743.6752', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28357', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [30/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35261
self.closeSec=1680107099, self.tradeDate='20230330', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28346.3, self.close=28329.9, self.high=28360.2, self.low=28312.0, self.vol=1225.387, self.amt=34716004.1225 
2023-03-30 00:25:01,744:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230330   000000    000459  ...         0.0        0.0       0
5761  20230330   000500    000959  ...         0.0        0.0       0
5762  20230330   001000    001459  ...         0.0        0.0       0
5763  20230330   001500    001959  ...         0.0        0.0       0
5764  20230330   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 00:25:01,744:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680107099, self.tradeDate='20230330', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28346.3, self.close=28329.9, self.high=28360.2, self.low=28312.0, self.vol=1225.387, self.amt=34716004.1225, ukdf['pct'].iloc[-1]=-0.000579 , ukdf['amount'].iloc[-1]=34716004.1225, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-710357.97785226352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28333.97259127', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28355.2, self.close=28346.3, self.high=28369.9, self.low=28302.0 
127.0.0.1 - - [30/Mar/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-03-30 00:20:05,888:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28355.2, self.close=28346.3, self.high=28369.9, self.low=28302.0   
2023-03-30 00:20:07,023:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230329   235500    235959  1680105599  ...  28390.0  0.000655   1727    5
1440  20230330   000000    000459  1680105899  ...  28350.0 -0.002040   1440    0
1441  20230330   000500    000959  1680106199  ...  28323.8 -0.001251   1441    1
1442  20230330   001000    001459  1680106499  ...  28307.6  0.000699   1442    2
1443  20230330   001500    001959  1680106799  ...  28302.0 -0.000222   1443    3

[5 rows x 11 columns]
2023-03-30 00:20:07,023:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=41, self.factor=0.2957065336238675, self.count=35827 

self.closeSec=1680107099, self.tradeDate='20230330', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28346.3, self.close=28329.9, self.high=28360.2, self.low=28312.0 
2023-03-30 00:25:01,661:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680107099, self.tradeDate='20230330', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28346.3, self.close=28329.9, self.high=28360.2, self.low=28312.0   
2023-03-30 00:25:01,724:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230330   000000    000459  1680105899  ...  28350.0 -0.002040   1440    0
1441  20230330   000500    000959  1680106199  ...  28323.8 -0.001251   1441    1
1442  20230330   001000    001459  1680106499  ...  28307.6  0.000699   1442    2
1443  20230330   001500    001959  1680106799  ...  28302.0 -0.000222   1443    3
1444  20230330   002000    002459  1680107099  ...  28312.0 -0.000579   1444    4

[5 rows x 11 columns]
2023-03-30 00:25:01,724:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-30 00:00:35,897:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230329    212959  28430.1  ...  49.583333  0.614893  0.175131
5803  20230329    215959  28351.7  ...  49.583333  0.620452  0.172452
5804  20230329    222959  28415.5  ...  49.166667  0.611411  0.171962
5805  20230329    225959  28350.1  ...  49.166667  0.599543  0.176121
5806  20230329    232959  28282.1  ...  49.583333  0.613510  0.174618

[5 rows x 33 columns]
0.5036764705882353
acc is : 0.5036764705882353
2023-03-30 00:00:36,049:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.490768  0.509232       1  ...  0.977631   1.0    0.0  1.038454
540     0  0.523221  0.476779       0  ...  0.975835   1.0    0.0  1.036546
541     1  0.496490  0.503510       0  ...  0.973443   1.0    0.0  1.034005
542     1  0.489262  0.510738       1  ...  0.977807   1.0    0.0  1.038641
543     0  0.531069  0.468931       1  ...  0.978409   1.0    0.0  1.039281

[5 rows x 10 columns]
2023-03-30 00:00:36,087:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.489910  0.510090       1  ...  0.977631   1.0    0.0  1.034381
46     0  0.521512  0.478488       0  ...  1.013984   1.0    0.0  1.031166
47     1  0.494665  0.505335       0  ...  1.011498   1.0    0.0  1.028638
48     1  0.488255  0.511745       1  ...  1.016033   1.0    0.0  1.036640
49     0  0.531069  0.468931       1  ...  0.978409   1.0    0.0  1.039281

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-30 00:00:03,081:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42075F1680105602552I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680105602686780, 'quantity': '26.038', 'price': '28422.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680105602180, 'updatetime': 1680105602686, 'tradetype': 'usdt', 'selfid': 42075, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680105602686, 'clientorderid': '42075F1680105602552I0L59', 'price': '28422.6', 'quantity': '26.038', 'commission': '740.0676588', 'commissionasset': 'USDT', 'tradetime': 1680105602686, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680105602686}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [30/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17912 

self.closeSec=1680106199, self.tradeDate='20230330', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28426.4', self.close='28332.8'
2023-03-30 00:10:01,579:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680106199, self.tradeDate='20230330', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28426.4', self.close='28332.8'
2023-03-30 00:10:01,659:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230329   232000    232959  1680103799  28320.9  28408.8  0.003104
573  20230329   233000    233959  1680104399  28408.8  28411.9  0.000109
574  20230329   234000    234959  1680104999    28412  28405.6 -0.000222
575  20230329   235000    235959  1680105599  28405.2  28426.3  0.000729
576  20230330   000000    000959  1680106199  28426.4  28332.8 -0.003289
2023-03-30 00:10:01,659:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17913 

self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28332.8', self.close='28346.3'
127.0.0.1 - - [30/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 00:20:07,132:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28332.8', self.close='28346.3'
2023-03-30 00:20:07,964:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230329   233000    233959  1680104399  28408.8  28411.9  0.000109
574  20230329   234000    234959  1680104999    28412  28405.6 -0.000222
575  20230329   235000    235959  1680105599  28405.2  28426.3  0.000729
576  20230330   000000    000959  1680106199  28426.4  28332.8 -0.003289
577  20230330   001000    001959  1680106799  28332.8  28346.3  0.000476
2023-03-30 00:20:07,964:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-30 00:00:01,951:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-30 00:00:02,095:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3300000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230329, closeTime:235959, close:28426.3, total:1018676.5234079, pct_pre:0.052615924570952766, thd:-0.21295931429889509, side:sell 
127.0.0.1 - - [30/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17913 

self.closeSec=1680106199, self.tradeDate='20230330', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28426.4', self.close='28332.8'
2023-03-30 00:10:01,635:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680106199, self.tradeDate='20230330', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28426.4', self.close='28332.8'
2023-03-30 00:10:01,648:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230329   232000    232959  1680103799  28320.9  28408.8
17421  20230329   233000    233959  1680104399  28408.8  28411.9
17422  20230329   234000    234959  1680104999    28412  28405.6
17423  20230329   235000    235959  1680105599  28405.2  28426.3
17424  20230330   000000    000959  1680106199  28426.4  28332.8
2023-03-30 00:10:01,648:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17914 

self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28332.8', self.close='28346.3'
127.0.0.1 - - [30/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 00:20:10,347:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28332.8', self.close='28346.3'
2023-03-30 00:20:10,490:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230329   233000    233959  1680104399  28408.8  28411.9
17422  20230329   234000    234959  1680104999    28412  28405.6
17423  20230329   235000    235959  1680105599  28405.2  28426.3
17424  20230330   000000    000959  1680106199  28426.4  28332.8
17425  20230330   001000    001959  1680106799  28332.8  28346.3
2023-03-30 00:20:10,491:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [30/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-30 00:00:03,464:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42076F1680105602908I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1680105603168233, 'quantity': '45.403', 'price': '28422.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1680105602543, 'updatetime': 1680105603168, 'tradetype': 'usdt', 'selfid': 42076, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1680105603168, 'clientorderid': '42076F1680105602908I0L2', 'price': '28422.6', 'quantity': '45.403', 'commission': '1290.4713078', 'commissionasset': 'USDT', 'tradetime': 1680105603168, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1680105603168}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17913 

self.closeSec=1680106199, self.tradeDate='20230330', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='28426.4', self.close='28332.8'
127.0.0.1 - - [30/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-30 00:10:01,581:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680106199, self.tradeDate='20230330', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='28426.4', self.close='28332.8'
2023-03-30 00:10:01,622:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230329   232000    232959  1680103799  28320.9  28408.8
12237  20230329   233000    233959  1680104399  28408.8  28411.9
12238  20230329   234000    234959  1680104999    28412  28405.6
12239  20230329   235000    235959  1680105599  28405.2  28426.3
12240  20230330   000000    000959  1680106199  28426.4  28332.8
2023-03-30 00:10:01,622:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17914 

self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='28332.8', self.close='28346.3'
127.0.0.1 - - [30/Mar/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-03-30 00:20:09,835:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='28332.8', self.close='28346.3'
2023-03-30 00:20:10,160:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230329   233000    233959  1680104399  28408.8  28411.9
12238  20230329   234000    234959  1680104999    28412  28405.6
12239  20230329   235000    235959  1680105599  28405.2  28426.3
12240  20230330   000000    000959  1680106199  28426.4  28332.8
12241  20230330   001000    001959  1680106799  28332.8  28346.3
2023-03-30 00:20:10,160:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31258
self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=28355.2, self.close=28346.3, self.high=28369.9, self.low=28302.0, self.vol=1759.411, self.amt=49849503.2212 
127.0.0.1 - - [30/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-30 00:20:07,544:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230329   235500    235959  ...         0.0        0.0       0
5760  20230330   000000    000459  ...         0.0        0.0       0
5761  20230330   000500    000959  ...         0.0        0.0       0
5762  20230330   001000    001459  ...         0.0        0.0       0
5763  20230330   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 00:20:07,574:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680106799, self.tradeDate='20230330', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=28355.2, self.close=28346.3, self.high=28369.9, self.low=28302.0, self.vol=1759.411, self.amt=49849503.2212, ukdf['pct'].iloc[-1]=-0.000222 , ukdf['amount'].iloc[-1]=49849503.2212, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31259
self.closeSec=1680107099, self.tradeDate='20230330', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=28346.3, self.close=28329.9, self.high=28360.2, self.low=28312.0, self.vol=1225.387, self.amt=34716004.1225 
127.0.0.1 - - [30/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-30 00:25:01,771:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230330   000000    000459  ...         0.0        0.0       0
5761  20230330   000500    000959  ...         0.0        0.0       0
5762  20230330   001000    001459  ...         0.0        0.0       0
5763  20230330   001500    001959  ...         0.0        0.0       0
5764  20230330   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-30 00:25:01,772:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680107099, self.tradeDate='20230330', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=28346.3, self.close=28329.9, self.high=28360.2, self.low=28312.0, self.vol=1225.387, self.amt=34716004.1225, ukdf['pct'].iloc[-1]=-0.000579 , ukdf['amount'].iloc[-1]=34716004.1225, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230329   120000    155959  1680076799  ...    723  0.220758 -0.671756    -1.0
724  20230329   160000    195959  1680091199  ...    724  0.336155 -0.381777     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-13936.3008456897', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28350.59243745', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [30/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=746
self.closeSec=1680105599, self.tradeDate='20230329', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=28347.5, self.close=28426.3, self.high=28589.5, self.low=28211.5, self.vol=132706.077, self.amt=3766131837.90362 
2023-03-30 00:00:01,767:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680105599, self.tradeDate='20230329', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=28347.5, self.close=28426.3, self.high=28589.5, self.low=28211.5, self.vol=132706.077, self.amt=3766131837.90362 
2023-03-30 00:00:01,864:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230329   040000    075959  ...   58236.084  1.587364e+09 -0.005924
722  20230329   080000    115959  ...   46690.555  1.276502e+09  0.003831
723  20230329   120000    155959  ...  154440.639  4.298772e+09  0.026453
724  20230329   160000    195959  ...  170742.766  4.848562e+09  0.009609
725  20230329   200000    235959  ...  132706.077  3.766132e+09  0.002780

[5 rows x 11 columns]
2023-03-30 00:00:04,601:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230329   040000    075959  1680047999  ...    721  0.185511 -0.789420    -1.0
722  20230329   080000    115959  1680062399  ...    722  0.216890 -0.698211    -1.0
723  20230329   120000    155959  1680076799  ...    723  0.220758 -0.671756    -1.0
724  20230329   160000    195959  1680091199  ...    724  0.336155 -0.381777     NaN
725  20230329   200000    235959  1680105599  ...    725  0.409578 -0.188305     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-18039.99010759464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28427.00269444', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


