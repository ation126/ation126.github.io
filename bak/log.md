# 20230316 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31228
self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24240.0, self.close=24267.0, self.high=24360.6, self.low=24205.5, self.vol=10355.382, self.amt=251514286.2151 
127.0.0.1 - - [16/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:20:04,222:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230315   235500    235959  ...         0.0        0.0       0
5760  20230316   000000    000459  ...         0.0        0.0       0
5761  20230316   000500    000959  ...         0.0        0.0       0
5762  20230316   001000    001459  ...         0.0        0.0       0
5763  20230316   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 00:20:04,231:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24240.0, self.close=24267.0, self.high=24360.6, self.low=24205.5, self.vol=10355.382, self.amt=251514286.2151, ukdf['pct'].iloc[-1]=0.001866 , ukdf['amount'].iloc[-1]=251514286.2151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-465412.2685576048', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24263.4842023', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31229
self.closeSec=1678897499, self.tradeDate='20230316', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24267.7, self.close=24311.5, self.high=24388.6, self.low=24245.4, self.vol=6151.31, self.amt=149569059.4356 
127.0.0.1 - - [16/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:25:01,647:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230316   000000    000459  ...         0.0        0.0       0
5761  20230316   000500    000959  ...         0.0        0.0       0
5762  20230316   001000    001459  ...         0.0        0.0       0
5763  20230316   001500    001959  ...         0.0        0.0       0
5764  20230316   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 00:25:01,648:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678897499, self.tradeDate='20230316', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24267.7, self.close=24311.5, self.high=24388.6, self.low=24245.4, self.vol=6151.31, self.amt=149569059.4356, ukdf['pct'].iloc[-1]=0.001834 , ukdf['amount'].iloc[-1]=149569059.4356, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-468158.28434882464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24309.11727514', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24240.0, self.close=24267.0, self.high=24360.6, self.low=24205.5 
127.0.0.1 - - [16/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:20:02,371:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24240.0, self.close=24267.0, self.high=24360.6, self.low=24205.5   
2023-03-16 00:20:02,830:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230315   235500    235959  1678895999  ...  24364.7  0.000364   1727    5
1440  20230316   000000    000459  1678896299  ...  24373.3 -0.004175   1440    0
1441  20230316   000500    000959  1678896599  ...  24337.0  0.000213   1441    1
1442  20230316   001000    001459  1678896899  ...  24138.0 -0.006615   1442    2
1443  20230316   001500    001959  1678897199  ...  24205.5  0.001866   1443    3

[5 rows x 11 columns]
2023-03-16 00:20:02,831:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=135, self.factor=0.5136892660959795, self.count=31795 

self.closeSec=1678897499, self.tradeDate='20230316', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24267.7, self.close=24311.5, self.high=24388.6, self.low=24245.4 
127.0.0.1 - - [16/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:25:01,582:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678897499, self.tradeDate='20230316', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24267.7, self.close=24311.5, self.high=24388.6, self.low=24245.4   
2023-03-16 00:25:01,620:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230316   000000    000459  1678896299  ...  24373.3 -0.004175   1440    0
1441  20230316   000500    000959  1678896599  ...  24337.0  0.000213   1441    1
1442  20230316   001000    001459  1678896899  ...  24138.0 -0.006615   1442    2
1443  20230316   001500    001959  1678897199  ...  24205.5  0.001866   1443    3
1444  20230316   002000    002459  1678897499  ...  24245.4  0.001834   1444    4

[5 rows x 11 columns]
2023-03-16 00:25:01,620:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

5803  20230315    215959  24992.7  ...  54.583333  0.543218  0.620039
5804  20230315    222959  24799.9  ...  54.583333  0.540134  0.612201
5805  20230315    225959  24749.7  ...  54.583333  0.536358  0.596800
5806  20230315    232959  24723.9  ...  54.166667  0.528466  0.587464

[5 rows x 33 columns]
0.5588235294117647
acc is : 0.5588235294117647
2023-03-16 00:00:34,468:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.598728  0.401272       0  ...  1.106565   1.0  0.0000  1.110057
540     1  0.496397  0.503603       0  ...  1.104910   1.0  0.0000  1.108396
541     1  0.486791  0.513209       0  ...  1.102898   1.0  0.0000  1.106378
542     1  0.491676  0.508324       0  ...  1.098687   1.0  0.0000  1.102154
543     1  0.449098  0.550902       0  ...  1.103594  -1.0 -0.0016  1.095468

[5 rows x 10 columns]
2023-03-16 00:00:34,509:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.598459  0.401541       0  ...  1.102741   1.0  0.0000  1.108430
46     1  0.496411  0.503589       0  ...  1.104910   1.0  0.0000  1.107985
47     1  0.486759  0.513241       0  ...  1.102898   1.0  0.0000  1.105967
48     1  0.491606  0.508394       0  ...  1.098687   1.0  0.0000  1.101370
49     1  0.449098  0.550902       0  ...  1.103594  -1.0 -0.0016  1.095468

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
2023-03-16 00:00:34,909:INFO:logic:main.py:555:handlebackTrade:885513: ret = self.client.insertMarketUOrder('simulator',  'BTCUSDT', '31.245', 'sell' ), ret=InsertOrderReturn{'error': 32607, 'message': 'orderfreecheck. account`s free isn`t enough. contractasset`s free:757991.8275646. order`s cost:765341.2072190997', 'result': 'success', 'clientorderid': ''}
2023-03-16 00:00:34,935:INFO:logic:main.py:494:insertFactor:885513: curDateTime:3160000, name:logic, symbol:BTCUSDT, tradeDate:20230315, closeTime:235959, close:24480.1, sign:-1, total:767183.2585902, side:sell  


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-03-16 00:00:04,970:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41998F1678896004209I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678896004462844, 'quantity': '34.689', 'price': '24481.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1678896003542, 'updatetime': 1678896004462, 'tradetype': 'usdt', 'selfid': 41998, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678896004462, 'clientorderid': '41998F1678896004209I0L59', 'price': '24481.3', 'quantity': '34.689', 'commission': '849.2318157', 'commissionasset': 'USDT', 'tradetime': 1678896004462, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678896004462}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Mar/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [16/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15896 

self.closeSec=1678896599, self.tradeDate='20230316', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24480', self.close='24379.3'
2023-03-16 00:10:01,647:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678896599, self.tradeDate='20230316', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24480', self.close='24379.3'
2023-03-16 00:10:01,682:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230315   232000    232959  1678894199    24817  24629.5 -0.007763
573  20230315   233000    233959  1678894799  24629.4  24470.2 -0.006468
574  20230315   234000    234959  1678895399  24470.2  24640.8  0.006972
575  20230315   235000    235959  1678895999  24639.7  24480.1 -0.006522
576  20230316   000000    000959  1678896599    24480  24379.3 -0.004118
2023-03-16 00:10:01,682:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15897 

self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24378.4', self.close='24267'
127.0.0.1 - - [16/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-16 00:20:03,391:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24378.4', self.close='24267'
2023-03-16 00:20:03,830:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230315   233000    233959  1678894799  24629.4  24470.2 -0.006468
574  20230315   234000    234959  1678895399  24470.2  24640.8  0.006972
575  20230315   235000    235959  1678895999  24639.7  24480.1 -0.006522
576  20230316   000000    000959  1678896599    24480  24379.3 -0.004118
577  20230316   001000    001959  1678897199  24378.4    24267 -0.004606
2023-03-16 00:20:03,830:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-16 00:00:03,131:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-16 00:00:03,285:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3160000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230315, closeTime:235959, close:24480.1, total:1046472.2759802, pct_pre:-0.05553074002479852, thd:0.04211861418099594, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15897 

self.closeSec=1678896599, self.tradeDate='20230316', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24480', self.close='24379.3'
127.0.0.1 - - [16/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:10:01,678:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678896599, self.tradeDate='20230316', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24480', self.close='24379.3'
2023-03-16 00:10:01,703:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230315   232000    232959  1678894199    24817  24629.5
17421  20230315   233000    233959  1678894799  24629.4  24470.2
17422  20230315   234000    234959  1678895399  24470.2  24640.8
17423  20230315   235000    235959  1678895999  24639.7  24480.1
17424  20230316   000000    000959  1678896599    24480  24379.3
2023-03-16 00:10:01,703:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15898 

self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24378.4', self.close='24267'
127.0.0.1 - - [16/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-16 00:20:05,046:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24378.4', self.close='24267'
2023-03-16 00:20:05,145:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230315   233000    233959  1678894799  24629.4  24470.2
17422  20230315   234000    234959  1678895399  24470.2  24640.8
17423  20230315   235000    235959  1678895999  24639.7  24480.1
17424  20230316   000000    000959  1678896599    24480  24379.3
17425  20230316   001000    001959  1678897199  24378.4    24267
2023-03-16 00:20:05,145:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-03-16 00:00:04,717:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41999F1678896004218I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1678896004456811, 'quantity': '47.127', 'price': '24481.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1678896003560, 'updatetime': 1678896004456, 'tradetype': 'usdt', 'selfid': 41999, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1678896004456, 'clientorderid': '41999F1678896004218I0L2', 'price': '24481.4', 'quantity': '47.127', 'commission': '1153.7349378', 'commissionasset': 'USDT', 'tradetime': 1678896004456, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1678896004456}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Mar/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15897 

self.closeSec=1678896599, self.tradeDate='20230316', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='24480', self.close='24379.3'
127.0.0.1 - - [16/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:10:01,674:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678896599, self.tradeDate='20230316', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='24480', self.close='24379.3'
2023-03-16 00:10:01,696:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230315   232000    232959  1678894199    24817  24629.5
12237  20230315   233000    233959  1678894799  24629.4  24470.2
12238  20230315   234000    234959  1678895399  24470.2  24640.8
12239  20230315   235000    235959  1678895999  24639.7  24480.1
12240  20230316   000000    000959  1678896599    24480  24379.3
2023-03-16 00:10:01,696:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15898 

self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='24378.4', self.close='24267'
127.0.0.1 - - [16/Mar/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-03-16 00:20:04,723:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='24378.4', self.close='24267'
2023-03-16 00:20:04,940:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230315   233000    233959  1678894799  24629.4  24470.2
12238  20230315   234000    234959  1678895399  24470.2  24640.8
12239  20230315   235000    235959  1678895999  24639.7  24480.1
12240  20230316   000000    000959  1678896599    24480  24379.3
12241  20230316   001000    001959  1678897199  24378.4    24267
2023-03-16 00:20:04,941:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27226
self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=24240.0, self.close=24267.0, self.high=24360.6, self.low=24205.5, self.vol=10355.382, self.amt=251514286.2151 
127.0.0.1 - - [16/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:20:01,664:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230315   235500    235959  ...         0.0        0.0       0
5760  20230316   000000    000459  ...         0.0        0.0       0
5761  20230316   000500    000959  ...         0.0        0.0       0
5762  20230316   001000    001459  ...         0.0        0.0       0
5763  20230316   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 00:20:01,670:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678897199, self.tradeDate='20230316', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=24240.0, self.close=24267.0, self.high=24360.6, self.low=24205.5, self.vol=10355.382, self.amt=251514286.2151, ukdf['pct'].iloc[-1]=0.001866 , ukdf['amount'].iloc[-1]=251514286.2151, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27227
self.closeSec=1678897499, self.tradeDate='20230316', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=24267.7, self.close=24311.5, self.high=24388.6, self.low=24245.4, self.vol=6151.31, self.amt=149569059.4356 
127.0.0.1 - - [16/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-16 00:25:01,640:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230316   000000    000459  ...         0.0        0.0       0
5761  20230316   000500    000959  ...         0.0        0.0       0
5762  20230316   001000    001459  ...         0.0        0.0       0
5763  20230316   001500    001959  ...         0.0        0.0       0
5764  20230316   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-16 00:25:01,640:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678897499, self.tradeDate='20230316', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=24267.7, self.close=24311.5, self.high=24388.6, self.low=24245.4, self.vol=6151.31, self.amt=149569059.4356, ukdf['pct'].iloc[-1]=0.001834 , ukdf['amount'].iloc[-1]=149569059.4356, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230315   120000    155959  1678867199  ...    723  1.161865  1.800504     1.0
724  20230315   160000    195959  1678881599  ...    724  1.150130  1.715110     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '262857.595', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24778.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [16/Mar/2023 00:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=662
self.closeSec=1678895999, self.tradeDate='20230315', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=24782.6, self.close=24480.1, self.high=25200.0, self.low=24364.7, self.vol=376951.657, self.amt=9340376245.94927 
2023-03-16 00:00:02,756:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678895999, self.tradeDate='20230315', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=24782.6, self.close=24480.1, self.high=25200.0, self.low=24364.7, self.vol=376951.657, self.amt=9340376245.94927 
2023-03-16 00:00:02,797:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230315   040000    075959  ...  240076.010  5.904620e+09 -0.015064
722  20230315   080000    115959  ...  126773.008  3.138394e+09  0.002394
723  20230315   120000    155959  ...   66779.179  1.654865e+09  0.006079
724  20230315   160000    195959  ...  173691.809  4.270609e+09 -0.004395
725  20230315   200000    235959  ...  376951.657  9.340376e+09 -0.012206

[5 rows x 11 columns]
2023-03-16 00:00:04,918:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230315   040000    075959  1678838399  ...    721  1.246479  2.193121     1.0
722  20230315   080000    115959  1678852799  ...    722  1.218211  2.032856     1.0
723  20230315   120000    155959  1678867199  ...    723  1.161865  1.800504     1.0
724  20230315   160000    195959  1678881599  ...    724  1.150130  1.715110     1.0
725  20230315   200000    235959  1678895999  ...    725  1.137514  1.631562     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '246354.435239297', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24482.97689636', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


