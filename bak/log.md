# 20230710 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16288
self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30294.0, self.close=30290.3, self.high=30301.2, self.low=30281.6, self.vol=666.649, self.amt=20192923.1451 
127.0.0.1 - - [10/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 00:20:07,235:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230709   235500    235959  ...         0.0        0.0       0
5760  20230710   000000    000459  ...         0.0        0.0       0
5761  20230710   000500    000959  ...         0.0        0.0       0
5762  20230710   001000    001459  ...         0.0        0.0       0
5763  20230710   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 00:20:07,276:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30294.0, self.close=30290.3, self.high=30301.2, self.low=30281.6, self.vol=666.649, self.amt=20192923.1451, ukdf['pct'].iloc[-1]=-0.000122 , ukdf['amount'].iloc[-1]=20192923.1451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47702.1204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30290.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16289
self.closeSec=1688919899, self.tradeDate='20230710', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30290.2, self.close=30288.6, self.high=30290.3, self.low=30279.2, self.vol=441.378, self.amt=13367149.6856 
2023-07-10 00:25:00,797:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230710   000000    000459  ...         0.0        0.0       0
5761  20230710   000500    000959  ...         0.0        0.0       0
5762  20230710   001000    001459  ...         0.0        0.0       0
5763  20230710   001500    001959  ...         0.0        0.0       0
5764  20230710   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 00:25:00,797:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688919899, self.tradeDate='20230710', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30290.2, self.close=30288.6, self.high=30290.3, self.low=30279.2, self.vol=441.378, self.amt=13367149.6856, ukdf['pct'].iloc[-1]=-5.6e-05 , ukdf['amount'].iloc[-1]=13367149.6856, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47679.8388', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30288.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30294.0, self.close=30290.3, self.high=30301.2, self.low=30281.6 
127.0.0.1 - - [10/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 00:20:04,900:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30294.0, self.close=30290.3, self.high=30301.2, self.low=30281.6   
2023-07-10 00:20:06,341:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230709   235500    235959  1688918399  ...  30311.0  0.000696   1727    5
1440  20230710   000000    000459  1688918699  ...  30311.9 -0.000620   1440    0
1441  20230710   000500    000959  1688918999  ...  30306.5 -0.000313   1441    1
1442  20230710   001000    001459  1688919299  ...  30291.3 -0.000478   1442    2
1443  20230710   001500    001959  1688919599  ...  30281.6 -0.000122   1443    3

[5 rows x 11 columns]
2023-07-10 00:20:06,360:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=47, self.factor=0.3912836004216668, self.count=16291 

self.closeSec=1688919899, self.tradeDate='20230710', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30290.2, self.close=30288.6, self.high=30290.3, self.low=30279.2 
127.0.0.1 - - [10/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-10 00:25:00,755:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688919899, self.tradeDate='20230710', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30290.2, self.close=30288.6, self.high=30290.3, self.low=30279.2   
2023-07-10 00:25:00,787:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230710   000000    000459  1688918699  ...  30311.9 -0.000620   1440    0
1441  20230710   000500    000959  1688918999  ...  30306.5 -0.000313   1441    1
1442  20230710   001000    001459  1688919299  ...  30291.3 -0.000478   1442    2
1443  20230710   001500    001959  1688919599  ...  30281.6 -0.000122   1443    3
1444  20230710   002000    002459  1688919899  ...  30279.2 -0.000056   1444    4

[5 rows x 11 columns]
2023-07-10 00:25:00,787:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-10 00:00:20,074:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230709    212959  30320.0  ...  46.666667  0.513821  0.367472
5803  20230709    215959  30298.1  ...  46.666667  0.495019  0.369807
5804  20230709    222959  30247.9  ...  46.250000  0.487820  0.375551
5805  20230709    225959  30228.3  ...  46.666667  0.523463  0.368981
5806  20230709    232959  30328.0  ...  47.083333  0.524782  0.362696

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-07-10 00:00:20,245:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.509584  0.490416       0  ...  0.952319   1.0    0.0  1.002353
540     1  0.498880  0.501120       0  ...  0.951696   1.0    0.0  1.001697
541     0  0.501691  0.498309       1  ...  0.954838   1.0    0.0  1.005004
542     0  0.536121  0.463879       1  ...  0.954960   1.0    0.0  1.005133
543     0  0.512865  0.487135       1  ...  0.955115   1.0    0.0  1.005295

[5 rows x 10 columns]
2023-07-10 00:00:20,280:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509543  0.490457       0  ...  0.942480   1.0    0.0  0.995583
46     1  0.498813  0.501187       0  ...  0.951696   1.0    0.0  0.995724
47     0  0.501588  0.498412       1  ...  0.954838   1.0    0.0  0.999012
48     0  0.535655  0.464345       1  ...  0.945094   1.0    0.0  1.000066
49     0  0.512865  0.487135       1  ...  0.955115   1.0    0.0  1.005295

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.764', 'enterprice': '30087.2', 'countrevence': '0', 'unrealprofit': '6183.02884927032', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30336.87811538', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [10/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-10 00:00:04,340:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42564F1688918403621I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688918403995521, 'quantity': '25.199', 'price': '30336.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688918402724, 'updatetime': 1688918403995, 'tradetype': 'usdt', 'selfid': 42564, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688918403995, 'clientorderid': '42564F1688918403621I0L59', 'price': '30336.9', 'quantity': '25.199', 'commission': '764.4595431', 'commissionasset': 'USDT', 'tradetime': 1688918403995, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688918403995}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8144 

self.closeSec=1688918999, self.tradeDate='20230710', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30336.9', self.close='30308.5'
127.0.0.1 - - [10/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-10 00:10:01,167:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688918999, self.tradeDate='20230710', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30336.9', self.close='30308.5'
2023-07-10 00:10:01,194:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230709   232000    232959  1688916599  30301.8  30331.9  0.001106
573  20230709   233000    233959  1688917199    30332  30325.4 -0.000214
574  20230709   234000    234959  1688917799  30325.5  30332.3  0.000228
575  20230709   235000    235959  1688918399  30332.3  30336.8  0.000148
576  20230710   000000    000959  1688918999  30336.9  30308.5 -0.000933
2023-07-10 00:10:01,194:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8145 

self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30308.4', self.close='30290.3'
127.0.0.1 - - [10/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 00:20:07,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30308.4', self.close='30290.3'
2023-07-10 00:20:07,845:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230709   233000    233959  1688917199    30332  30325.4 -0.000214
574  20230709   234000    234959  1688917799  30325.5  30332.3  0.000228
575  20230709   235000    235959  1688918399  30332.3  30336.8  0.000148
576  20230710   000000    000959  1688918999  30336.9  30308.5 -0.000933
577  20230710   001000    001959  1688919599  30308.4  30290.3 -0.000600
2023-07-10 00:20:07,854:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [10/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-10 00:00:04,101:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42563F1688918403501I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688918403863117, 'quantity': '32.791', 'price': '30336.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688918402621, 'updatetime': 1688918403863, 'tradetype': 'usdt', 'selfid': 42563, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688918403863, 'clientorderid': '42563F1688918403501I0L57', 'price': '30336.8', 'quantity': '32.791', 'commission': '994.7740088', 'commissionasset': 'USDT', 'tradetime': 1688918403863, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688918403863}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--: 127.0.0.1 - - [10/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8147 

self.closeSec=1688918999, self.tradeDate='20230710', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30336.9', self.close='30308.5'
2023-07-10 00:10:01,188:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688918999, self.tradeDate='20230710', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30336.9', self.close='30308.5'
2023-07-10 00:10:01,205:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230709   232000    232959  1688916599  30301.8  30331.9
17421  20230709   233000    233959  1688917199    30332  30325.4
17422  20230709   234000    234959  1688917799  30325.5  30332.3
17423  20230709   235000    235959  1688918399  30332.3  30336.8
17424  20230710   000000    000959  1688918999  30336.9  30308.5
2023-07-10 00:10:01,205:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8148 

self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30308.4', self.close='30290.3'
127.0.0.1 - - [10/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 00:20:08,988:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30308.4', self.close='30290.3'
2023-07-10 00:20:09,164:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230709   233000    233959  1688917199    30332  30325.4
17422  20230709   234000    234959  1688917799  30325.5  30332.3
17423  20230709   235000    235959  1688918399  30332.3  30336.8
17424  20230710   000000    000959  1688918999  30336.9  30308.5
17425  20230710   001000    001959  1688919599  30308.4  30290.3
2023-07-10 00:20:09,165:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [10/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-10 00:00:04,508:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42565F1688918403642I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688918404013481, 'quantity': '37.705', 'price': '30336.9', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688918402747, 'updatetime': 1688918404013, 'tradetype': 'usdt', 'selfid': 42565, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688918404013, 'clientorderid': '42565F1688918403642I0L2', 'price': '30336.9', 'quantity': '37.705', 'commission': '1143.8528145', 'commissionasset': 'USDT', 'tradetime': 1688918404013, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688918404013}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8147 

self.closeSec=1688918999, self.tradeDate='20230710', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30336.9', self.close='30308.5'
127.0.0.1 - - [10/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-10 00:10:01,173:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688918999, self.tradeDate='20230710', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30336.9', self.close='30308.5'
2023-07-10 00:10:01,199:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230709   232000    232959  1688916599  30301.8  30331.9
12237  20230709   233000    233959  1688917199    30332  30325.4
12238  20230709   234000    234959  1688917799  30325.5  30332.3
12239  20230709   235000    235959  1688918399  30332.3  30336.8
12240  20230710   000000    000959  1688918999  30336.9  30308.5
2023-07-10 00:10:01,199:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8148 

self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30308.4', self.close='30290.3'
127.0.0.1 - - [10/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-10 00:20:08,730:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30308.4', self.close='30290.3'
2023-07-10 00:20:08,999:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230709   233000    233959  1688917199    30332  30325.4
12238  20230709   234000    234959  1688917799  30325.5  30332.3
12239  20230709   235000    235959  1688918399  30332.3  30336.8
12240  20230710   000000    000959  1688918999  30336.9  30308.5
12241  20230710   001000    001959  1688919599  30308.4  30290.3
2023-07-10 00:20:09,006:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16288
self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30294.0, self.close=30290.3, self.high=30301.2, self.low=30281.6, self.vol=666.649, self.amt=20192923.1451 
127.0.0.1 - - [10/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-10 00:20:07,216:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230709   235500    235959  ...         0.0        0.0       0
5760  20230710   000000    000459  ...         0.0        0.0       0
5761  20230710   000500    000959  ...         0.0        0.0       0
5762  20230710   001000    001459  ...         0.0        0.0       0
5763  20230710   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 00:20:07,246:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688919599, self.tradeDate='20230710', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30294.0, self.close=30290.3, self.high=30301.2, self.low=30281.6, self.vol=666.649, self.amt=20192923.1451, ukdf['pct'].iloc[-1]=-0.000122 , ukdf['amount'].iloc[-1]=20192923.1451, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127999.0283', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30290.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [10/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16289
self.closeSec=1688919899, self.tradeDate='20230710', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30290.2, self.close=30288.6, self.high=30290.3, self.low=30279.2, self.vol=441.378, self.amt=13367149.6856 
2023-07-10 00:25:00,818:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230710   000000    000459  ...         0.0        0.0       0
5761  20230710   000500    000959  ...         0.0        0.0       0
5762  20230710   001000    001459  ...         0.0        0.0       0
5763  20230710   001500    001959  ...         0.0        0.0       0
5764  20230710   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-10 00:25:00,818:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688919899, self.tradeDate='20230710', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30290.2, self.close=30288.6, self.high=30290.3, self.low=30279.2, self.vol=441.378, self.amt=13367149.6856, ukdf['pct'].iloc[-1]=-5.6e-05 , ukdf['amount'].iloc[-1]=13367149.6856, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127939.6027', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30288.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230709   120000    155959  1688889599  ...    723  0.342819  0.197953     NaN
724  20230709   160000    195959  1688903999  ...    724  0.344940  0.236151     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-26185.48', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30257.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [10/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=339
self.closeSec=1688918399, self.tradeDate='20230709', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30257.2, self.close=30336.8, self.high=30443.4, self.low=30163.6, self.vol=52366.13, self.amt=1586752298.94564 
2023-07-10 00:00:01,682:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688918399, self.tradeDate='20230709', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30257.2, self.close=30336.8, self.high=30443.4, self.low=30163.6, self.vol=52366.13, self.amt=1586752298.94564 
2023-07-10 00:00:01,724:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230709   040000    075959  ...  19275.386  5.815407e+08  0.005625
722  20230709   080000    115959  ...  29538.533  8.953542e+08  0.000274
723  20230709   120000    155959  ...  12970.718  3.924279e+08 -0.000912
724  20230709   160000    195959  ...  13831.500  4.185744e+08  0.000241
725  20230709   200000    235959  ...  52366.130  1.586752e+09  0.002627

[5 rows x 11 columns]
2023-07-10 00:00:03,298:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230709   040000    075959  1688860799  ...    721  0.358795  0.194950     NaN
722  20230709   080000    115959  1688875199  ...    722  0.351068  0.198917     NaN
723  20230709   120000    155959  1688889599  ...    723  0.342819  0.197953     NaN
724  20230709   160000    195959  1688903999  ...    724  0.344940  0.236151     NaN
725  20230709   200000    235959  1688918399  ...    725  0.307437  0.097427     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-21968.005', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30336.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


