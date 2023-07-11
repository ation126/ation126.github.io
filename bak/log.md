# 20230711 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16768
self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30553.9, self.close=30528.9, self.high=30554.0, self.low=30528.8, self.vol=397.207, self.amt=12130588.6184 
127.0.0.1 - - [11/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 16:20:07,210:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230711   155500    155959  ...         0.0        0.0       0
5952  20230711   160000    160459  ...         0.0        0.0       0
5953  20230711   160500    160959  ...         0.0        0.0       0
5954  20230711   161000    161459  ...         0.0        0.0       0
5955  20230711   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 16:20:07,240:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30553.9, self.close=30528.9, self.high=30554.0, self.low=30528.8, self.vol=397.207, self.amt=12130588.6184, ukdf['pct'].iloc[-1]=-0.000818 , ukdf['amount'].iloc[-1]=12130588.6184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51038.79', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30529.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16769
self.closeSec=1689063899, self.tradeDate='20230711', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30528.9, self.close=30524.7, self.high=30530.0, self.low=30503.2, self.vol=956.543, self.amt=29190663.0269 
2023-07-11 16:25:00,809:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230711   160000    160459  ...         0.0        0.0       0
5953  20230711   160500    160959  ...         0.0        0.0       0
5954  20230711   161000    161459  ...         0.0        0.0       0
5955  20230711   161500    161959  ...         0.0        0.0       0
5956  20230711   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 16:25:00,809:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689063899, self.tradeDate='20230711', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30528.9, self.close=30524.7, self.high=30530.0, self.low=30503.2, self.vol=956.543, self.amt=29190663.0269, ukdf['pct'].iloc[-1]=-0.000138 , ukdf['amount'].iloc[-1]=29190663.0269, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50964.9822', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30524.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30553.9, self.close=30528.9, self.high=30554.0, self.low=30528.8 
127.0.0.1 - - [11/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 16:20:04,860:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30553.9, self.close=30528.9, self.high=30554.0, self.low=30528.8   
2023-07-11 16:20:06,380:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230711   155500    155959  1689062399  ...  30518.0 -0.000377   1631    5
1632  20230711   160000    160459  1689062699  ...  30523.4  0.000314   1632    0
1633  20230711   160500    160959  1689062999  ...  30538.0  0.000390   1633    1
1634  20230711   161000    161459  1689063299  ...  30547.2  0.000128   1634    2
1635  20230711   161500    161959  1689063599  ...  30528.8 -0.000818   1635    3

[5 rows x 11 columns]
2023-07-11 16:20:06,391:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=127, self.factor=0.4555568274896642, self.count=16771 

self.closeSec=1689063899, self.tradeDate='20230711', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30528.9, self.close=30524.7, self.high=30530.0, self.low=30503.2 
2023-07-11 16:25:00,750:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689063899, self.tradeDate='20230711', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30528.9, self.close=30524.7, self.high=30530.0, self.low=30503.2   
2023-07-11 16:25:00,776:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230711   160000    160459  1689062699  ...  30523.4  0.000314   1632    0
1633  20230711   160500    160959  1689062999  ...  30538.0  0.000390   1633    1
1634  20230711   161000    161459  1689063299  ...  30547.2  0.000128   1634    2
1635  20230711   161500    161959  1689063599  ...  30528.8 -0.000818   1635    3
1636  20230711   162000    162459  1689063899  ...  30503.2 -0.000138   1636    4

[5 rows x 11 columns]
2023-07-11 16:25:00,776:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-11 16:00:20,353:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230711    132959  30429.9  ...  49.583333  0.529624  0.480283
5787  20230711    135959  30449.7  ...  49.166667  0.528263  0.490540
5788  20230711    142959  30443.9  ...  49.166667  0.545625  0.494015
5789  20230711    145959  30529.9  ...  49.166667  0.563156  0.490740
5790  20230711    152959  30621.9  ...  48.750000  0.550008  0.491641

[5 rows x 33 columns]
0.5811808118081181
acc is : 0.5811808118081181
2023-07-11 16:00:20,469:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.509973  0.490027       0  ...  1.003735   1.0    0.0  1.000414
538     0  0.510591  0.489409       1  ...  1.006571   1.0    0.0  1.003240
539     0  0.537840  0.462160       1  ...  1.009601   1.0    0.0  1.006260
540     0  0.549927  0.450073       0  ...  1.007761   1.0    0.0  1.004426
541     0  0.512811  0.487189       0  ...  1.006525   1.0    0.0  1.003194

[5 rows x 10 columns]
2023-07-11 16:00:20,497:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509993  0.490007       0  ...  1.003735   1.0    0.0  1.001362
46     0  0.510142  0.489858       1  ...  1.006571   1.0    0.0  1.001900
47     0  0.537823  0.462177       1  ...  1.009601   1.0    0.0  1.005976
48     0  0.549425  0.450575       0  ...  1.007761   1.0    0.0  1.003032
49     0  0.512811  0.487189       0  ...  1.006525   1.0    0.0  1.003194

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.383', 'enterprice': '30486.7', 'countrevence': '0', 'unrealprofit': '938.89026796675', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30525.20593725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230711   155000    155959  1689062399    30540  30528.5 -0.000373
2023-07-11 16:00:02,073:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8384 

self.closeSec=1689062999, self.tradeDate='20230711', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30528.6', self.close='30550'
2023-07-11 16:10:01,098:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689062999, self.tradeDate='20230711', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30528.6', self.close='30550'
127.0.0.1 - - [11/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-11 16:10:01,124:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230711   152000    152959  1689060599  30560.4  30566.1  0.000190
525  20230711   153000    153959  1689061199  30566.1    30544 -0.000723
526  20230711   154000    154959  1689061799    30544  30539.9 -0.000134
527  20230711   155000    155959  1689062399    30540  30528.5 -0.000373
528  20230711   160000    160959  1689062999  30528.6    30550  0.000704
2023-07-11 16:10:01,124:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8385 

self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30550.1', self.close='30528.9'
127.0.0.1 - - [11/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 16:20:07,140:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30550.1', self.close='30528.9'
2023-07-11 16:20:07,871:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230711   153000    153959  1689061199  30566.1    30544 -0.000723
526  20230711   154000    154959  1689061799    30544  30539.9 -0.000134
527  20230711   155000    155959  1689062399    30540  30528.5 -0.000373
528  20230711   160000    160959  1689062999  30528.6    30550  0.000704
529  20230711   161000    161959  1689063599  30550.1  30528.9 -0.000691
2023-07-11 16:20:07,871:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230711   155000    155959  1689062399    30540  30528.5
2023-07-11 16:00:02,088:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8387 

self.closeSec=1689062999, self.tradeDate='20230711', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30528.6', self.close='30550'
127.0.0.1 - - [11/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-11 16:10:01,105:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689062999, self.tradeDate='20230711', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30528.6', self.close='30550'
2023-07-11 16:10:01,133:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230711   152000    152959  1689060599  30560.4  30566.1
17517  20230711   153000    153959  1689061199  30566.1    30544
17518  20230711   154000    154959  1689061799    30544  30539.9
17519  20230711   155000    155959  1689062399    30540  30528.5
17520  20230711   160000    160959  1689062999  30528.6    30550
2023-07-11 16:10:01,133:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8388 

self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30550.1', self.close='30528.9'
127.0.0.1 - - [11/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 16:20:08,834:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30550.1', self.close='30528.9'
2023-07-11 16:20:09,042:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230711   153000    153959  1689061199  30566.1    30544
17518  20230711   154000    154959  1689061799    30544  30539.9
17519  20230711   155000    155959  1689062399    30540  30528.5
17520  20230711   160000    160959  1689062999  30528.6    30550
17521  20230711   161000    161959  1689063599  30550.1  30528.9
2023-07-11 16:20:09,042:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230711   155000    155959  1689062399    30540  30528.5
2023-07-11 16:00:02,085:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8387 

self.closeSec=1689062999, self.tradeDate='20230711', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='30528.6', self.close='30550'
2023-07-11 16:10:01,110:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689062999, self.tradeDate='20230711', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='30528.6', self.close='30550'
127.0.0.1 - - [11/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-11 16:10:01,129:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230711   152000    152959  1689060599  30560.4  30566.1
12189  20230711   153000    153959  1689061199  30566.1    30544
12190  20230711   154000    154959  1689061799    30544  30539.9
12191  20230711   155000    155959  1689062399    30540  30528.5
12192  20230711   160000    160959  1689062999  30528.6    30550
2023-07-11 16:10:01,130:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8388 

self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='30550.1', self.close='30528.9'
127.0.0.1 - - [11/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 16:20:08,613:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='30550.1', self.close='30528.9'
2023-07-11 16:20:08,901:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230711   153000    153959  1689061199  30566.1    30544
12190  20230711   154000    154959  1689061799    30544  30539.9
12191  20230711   155000    155959  1689062399    30540  30528.5
12192  20230711   160000    160959  1689062999  30528.6    30550
12193  20230711   161000    161959  1689063599  30550.1  30528.9
2023-07-11 16:20:08,902:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16768
self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=30553.9, self.close=30528.9, self.high=30554.0, self.low=30528.8, self.vol=397.207, self.amt=12130588.6184 
127.0.0.1 - - [11/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 16:20:07,200:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230711   155500    155959  ...         0.0        0.0       0
5952  20230711   160000    160459  ...         0.0        0.0       0
5953  20230711   160500    160959  ...         0.0        0.0       0
5954  20230711   161000    161459  ...         0.0        0.0       0
5955  20230711   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 16:20:07,231:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689063599, self.tradeDate='20230711', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=30553.9, self.close=30528.9, self.high=30554.0, self.low=30528.8, self.vol=397.207, self.amt=12130588.6184, ukdf['pct'].iloc[-1]=-0.000818 , ukdf['amount'].iloc[-1]=12130588.6184, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136898.0119', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30529.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16769
self.closeSec=1689063899, self.tradeDate='20230711', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=30528.9, self.close=30524.7, self.high=30530.0, self.low=30503.2, self.vol=956.543, self.amt=29190663.0269 
2023-07-11 16:25:00,796:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230711   160000    160459  ...         0.0        0.0       0
5953  20230711   160500    160959  ...         0.0        0.0       0
5954  20230711   161000    161459  ...         0.0        0.0       0
5955  20230711   161500    161959  ...         0.0        0.0       0
5956  20230711   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 16:25:00,796:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689063899, self.tradeDate='20230711', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=30528.9, self.close=30524.7, self.high=30530.0, self.low=30503.2, self.vol=956.543, self.amt=29190663.0269, ukdf['pct'].iloc[-1]=-0.000138 , ukdf['amount'].iloc[-1]=29190663.0269, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136701.1646', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30524.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230711   040000    075959  1689033599  ...    721  0.028964 -1.074251    -1.0
722  20230711   080000    115959  1689047999  ...    722  0.067099 -0.893681    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-8614.9375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30466', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [11/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1604933.5124475, self.flagDict['side']='sell', self.tradeCount=10, self.count=349
self.closeSec=1689062399, self.tradeDate='20230711', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=30460.9, self.close=30528.5, self.high=30660.0, self.low=30416.4, self.vol=37038.603, self.amt=1130975499.4982 
2023-07-11 16:00:01,637:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689062399, self.tradeDate='20230711', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=30460.9, self.close=30528.5, self.high=30660.0, self.low=30416.4, self.vol=37038.603, self.amt=1130975499.4982 
2023-07-11 16:00:01,685:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230710   200000    235959  ...   62189.014  1.880878e+09  0.002518
720  20230711   000000    035959  ...   91867.895  2.802292e+09  0.017391
721  20230711   040000    075959  ...  157092.883  4.807923e+09 -0.013875
722  20230711   080000    115959  ...   45182.060  1.376224e+09  0.002112
723  20230711   120000    155959  ...   37038.603  1.130975e+09  0.002216

[5 rows x 11 columns]
2023-07-11 16:00:03,260:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230710   200000    235959  1689004799  ...    719  0.000017 -1.233220    -1.0
720  20230711   000000    035959  1689019199  ...    720  0.047909 -1.006761    -1.0
721  20230711   040000    075959  1689033599  ...    721  0.028964 -1.074251    -1.0
722  20230711   080000    115959  1689047999  ...    722  0.067099 -0.893681    -1.0
723  20230711   120000    155959  1689062399  ...    723  0.112018 -0.687766    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-11928.375', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30528.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


