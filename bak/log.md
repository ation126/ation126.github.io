# 20230727 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21184
self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29301.2, self.close=29314.1, self.high=29355.0, self.low=29301.2, self.vol=2794.538, self.amt=81984020.8471 
127.0.0.1 - - [27/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 00:20:05,902:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230726   235500    235959  ...         0.0        0.0       0
5760  20230727   000000    000459  ...         0.0        0.0       0
5761  20230727   000500    000959  ...         0.0        0.0       0
5762  20230727   001000    001459  ...         0.0        0.0       0
5763  20230727   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 00:20:05,922:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29301.2, self.close=29314.1, self.high=29355.0, self.low=29301.2, self.vol=2794.538, self.amt=81984020.8471, ukdf['pct'].iloc[-1]=0.000437 , ukdf['amount'].iloc[-1]=81984020.8471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34170.46120765596', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29318.61687546', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21185
self.closeSec=1690388699, self.tradeDate='20230727', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29314.1, self.close=29272.1, self.high=29322.0, self.low=29263.5, self.vol=1541.944, self.amt=45173906.3106 
2023-07-27 00:25:00,772:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230727   000000    000459  ...         0.0        0.0       0
5761  20230727   000500    000959  ...         0.0        0.0       0
5762  20230727   001000    001459  ...         0.0        0.0       0
5763  20230727   001500    001959  ...         0.0        0.0       0
5764  20230727   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 00:25:00,773:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690388699, self.tradeDate='20230727', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29314.1, self.close=29272.1, self.high=29322.0, self.low=29263.5, self.vol=1541.944, self.amt=45173906.3106, ukdf['pct'].iloc[-1]=-0.001433 , ukdf['amount'].iloc[-1]=45173906.3106, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33522.6672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29272.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29301.2, self.close=29314.1, self.high=29355.0, self.low=29301.2 
127.0.0.1 - - [27/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 00:20:04,101:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29301.2, self.close=29314.1, self.high=29355.0, self.low=29301.2   
2023-07-27 00:20:05,192:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230726   235500    235959  1690387199  ...  29299.7  0.000133   1727    5
1440  20230727   000000    000459  1690387499  ...  29303.0  0.000068   1440    0
1441  20230727   000500    000959  1690387799  ...  29308.4  0.000085   1441    1
1442  20230727   001000    001459  1690388099  ...  29300.0 -0.000355   1442    2
1443  20230727   001500    001959  1690388399  ...  29301.2  0.000437   1443    3

[5 rows x 11 columns]
2023-07-27 00:20:05,211:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=3, self.factor=0.44016268391311825, self.count=21187 

self.closeSec=1690388699, self.tradeDate='20230727', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29314.1, self.close=29272.1, self.high=29322.0, self.low=29263.5 
127.0.0.1 - - [27/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-27 00:25:00,748:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690388699, self.tradeDate='20230727', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29314.1, self.close=29272.1, self.high=29322.0, self.low=29263.5   
2023-07-27 00:25:00,769:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230727   000000    000459  1690387499  ...  29303.0  0.000068   1440    0
1441  20230727   000500    000959  1690387799  ...  29308.4  0.000085   1441    1
1442  20230727   001000    001459  1690388099  ...  29300.0 -0.000355   1442    2
1443  20230727   001500    001959  1690388399  ...  29301.2  0.000437   1443    3
1444  20230727   002000    002459  1690388699  ...  29263.5 -0.001433   1444    4

[5 rows x 11 columns]
2023-07-27 00:25:00,773:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-27 00:00:18,770:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230726    212959  29217.3  ...  50.000000  0.491258  0.591844
5803  20230726    215959  29248.0  ...  50.416667  0.508544  0.576373
5804  20230726    222959  29295.3  ...  50.416667  0.502879  0.565029
5805  20230726    225959  29279.8  ...  50.000000  0.493876  0.559407
5806  20230726    232959  29255.1  ...  50.416667  0.501472  0.550018

[5 rows x 33 columns]
0.5533088235294118
acc is : 0.5533088235294118
2023-07-27 00:00:18,828:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.517606  0.482394       1  ...  0.941381  -1.0    0.0  0.966277
540     0  0.525992  0.474008       0  ...  0.941876  -1.0    0.0  0.965769
541     0  0.512455  0.487545       0  ...  0.942671  -1.0    0.0  0.964954
542     0  0.500719  0.499281       1  ...  0.942007  -1.0    0.0  0.965634
543     0  0.512135  0.487865       1  ...  0.940997  -1.0    0.0  0.966670

[5 rows x 10 columns]
2023-07-27 00:00:18,839:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518147  0.481853       1  ...  0.941381  -1.0    0.0  0.967381
46     0  0.526305  0.473695       0  ...  0.941876  -1.0    0.0  0.966343
47     0  0.512804  0.487196       0  ...  0.942671  -1.0    0.0  0.965528
48     0  0.500932  0.499068       1  ...  0.942007  -1.0    0.0  0.965886
49     0  0.512135  0.487865       1  ...  0.940997  -1.0    0.0  0.966670

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.403', 'enterprice': '29752', 'countrevence': '0', 'unrealprofit': '10311.3618', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29311.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-07-27 00:00:04,174:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42739F1690387203483I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690387203869194, 'quantity': '25.702', 'price': '29307.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690387202624, 'updatetime': 1690387203869, 'tradetype': 'usdt', 'selfid': 42739, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690387203869, 'clientorderid': '42739F1690387203483I0L59', 'price': '29307.3', 'quantity': '25.702', 'commission': '753.2562246', 'commissionasset': 'USDT', 'tradetime': 1690387203869, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690387203869}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10592 

self.closeSec=1690387799, self.tradeDate='20230727', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29307.3', self.close='29312.8'
127.0.0.1 - - [27/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-27 00:10:01,088:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690387799, self.tradeDate='20230727', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29307.3', self.close='29312.8'
2023-07-27 00:10:01,099:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230726   232000    232959  1690385399  29286.6  29275.8 -0.000369
573  20230726   233000    233959  1690385999  29275.8  29307.6  0.001086
574  20230726   234000    234959  1690386599  29307.7    29320  0.000423
575  20230726   235000    235959  1690387199    29318  29307.2 -0.000437
576  20230727   000000    000959  1690387799  29307.3  29312.8  0.000191
2023-07-27 00:10:01,099:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10593 

self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29312.7', self.close='29314.1'
127.0.0.1 - - [27/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 00:20:06,462:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29312.7', self.close='29314.1'
2023-07-27 00:20:06,963:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230726   233000    233959  1690385999  29275.8  29307.6  0.001086
574  20230726   234000    234959  1690386599  29307.7    29320  0.000423
575  20230726   235000    235959  1690387199    29318  29307.2 -0.000437
576  20230727   000000    000959  1690387799  29307.3  29312.8  0.000191
577  20230727   001000    001959  1690388399  29312.7  29314.1  0.000044
2023-07-27 00:20:06,963:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-27 00:00:02,112:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-27 00:00:02,198:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7270000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230726, closeTime:235959, close:29307.2, total:1006174.6753163, pct_pre:-0.001211731201051558, thd:0.3559256439656955, side:sell 
127.0.0.1 - - [27/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10595 

self.closeSec=1690387799, self.tradeDate='20230727', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29307.3', self.close='29312.8'
2023-07-27 00:10:01,080:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690387799, self.tradeDate='20230727', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29307.3', self.close='29312.8'
2023-07-27 00:10:01,090:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230726   232000    232959  1690385399  29286.6  29275.8
17421  20230726   233000    233959  1690385999  29275.8  29307.6
17422  20230726   234000    234959  1690386599  29307.7    29320
17423  20230726   235000    235959  1690387199    29318  29307.2
17424  20230727   000000    000959  1690387799  29307.3  29312.8
2023-07-27 00:10:01,091:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10596 

self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29312.7', self.close='29314.1'
127.0.0.1 - - [27/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 00:20:07,654:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29312.7', self.close='29314.1'
2023-07-27 00:20:07,752:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230726   233000    233959  1690385999  29275.8  29307.6
17422  20230726   234000    234959  1690386599  29307.7    29320
17423  20230726   235000    235959  1690387199    29318  29307.2
17424  20230727   000000    000959  1690387799  29307.3  29312.8
17425  20230727   001000    001959  1690388399  29312.7  29314.1
2023-07-27 00:20:07,753:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-27 00:00:04,004:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42738F1690387203424I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690387203833477, 'quantity': '37.539', 'price': '29307.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690387202582, 'updatetime': 1690387203833, 'tradetype': 'usdt', 'selfid': 42738, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690387203833, 'clientorderid': '42738F1690387203424I0L2', 'price': '29307.3', 'quantity': '37.539', 'commission': '1100.1667347', 'commissionasset': 'USDT', 'tradetime': 1690387203833, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690387203833}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10595 

self.closeSec=1690387799, self.tradeDate='20230727', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29307.3', self.close='29312.8'
127.0.0.1 - - [27/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-27 00:10:01,083:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690387799, self.tradeDate='20230727', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29307.3', self.close='29312.8'
2023-07-27 00:10:01,101:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230726   232000    232959  1690385399  29286.6  29275.8
12237  20230726   233000    233959  1690385999  29275.8  29307.6
12238  20230726   234000    234959  1690386599  29307.7    29320
12239  20230726   235000    235959  1690387199    29318  29307.2
12240  20230727   000000    000959  1690387799  29307.3  29312.8
2023-07-27 00:10:01,101:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10596 

self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29312.7', self.close='29314.1'
127.0.0.1 - - [27/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-27 00:20:07,553:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29312.7', self.close='29314.1'
2023-07-27 00:20:07,663:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230726   233000    233959  1690385999  29275.8  29307.6
12238  20230726   234000    234959  1690386599  29307.7    29320
12239  20230726   235000    235959  1690387199    29318  29307.2
12240  20230727   000000    000959  1690387799  29307.3  29312.8
12241  20230727   001000    001959  1690388399  29312.7  29314.1
2023-07-27 00:20:07,664:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21184
self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29301.2, self.close=29314.1, self.high=29355.0, self.low=29301.2, self.vol=2794.538, self.amt=81984020.8471 
127.0.0.1 - - [27/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-27 00:20:06,001:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230726   235500    235959  ...         0.0        0.0       0
5760  20230727   000000    000459  ...         0.0        0.0       0
5761  20230727   000500    000959  ...         0.0        0.0       0
5762  20230727   001000    001459  ...         0.0        0.0       0
5763  20230727   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 00:20:06,031:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690388399, self.tradeDate='20230727', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29301.2, self.close=29314.1, self.high=29355.0, self.low=29301.2, self.vol=2794.538, self.amt=81984020.8471, ukdf['pct'].iloc[-1]=0.000437 , ukdf['amount'].iloc[-1]=81984020.8471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '91909.74537145986', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29318.61687546', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21185
self.closeSec=1690388699, self.tradeDate='20230727', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29314.1, self.close=29272.1, self.high=29322.0, self.low=29263.5, self.vol=1541.944, self.amt=45173906.3106 
2023-07-27 00:25:00,778:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230727   000000    000459  ...         0.0        0.0       0
5761  20230727   000500    000959  ...         0.0        0.0       0
5762  20230727   001000    001459  ...         0.0        0.0       0
5763  20230727   001500    001959  ...         0.0        0.0       0
5764  20230727   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-27 00:25:00,778:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690388699, self.tradeDate='20230727', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29314.1, self.close=29272.1, self.high=29322.0, self.low=29263.5, self.vol=1541.944, self.amt=45173906.3106, ukdf['pct'].iloc[-1]=-0.001433 , ukdf['amount'].iloc[-1]=45173906.3106, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '90182.0621', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29272.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230726   120000    155959  1690358399  ...    723  0.582017  0.862747     1.0
724  20230726   160000    195959  1690372799  ...    724  0.597699  0.904712     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '2502.26829899943', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29163.24433883', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [27/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1594659.6936504, self.flagDict['side']='buy', self.tradeCount=13, self.count=441
self.closeSec=1690387199, self.tradeDate='20230726', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29163.9, self.close=29307.2, self.high=29349.3, self.low=29152.4, self.vol=42475.796, self.amt=1242892085.18558 
2023-07-27 00:00:01,678:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690387199, self.tradeDate='20230726', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29163.9, self.close=29307.2, self.high=29349.3, self.low=29152.4, self.vol=42475.796, self.amt=1242892085.18558 
2023-07-27 00:00:01,697:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230726   040000    075959  ...  13574.242  3.965229e+08  0.000935
722  20230726   080000    115959  ...  47519.046  1.388819e+09  0.000400
723  20230726   120000    155959  ...  27037.859  7.900565e+08 -0.000777
724  20230726   160000    195959  ...  16394.134  4.784539e+08 -0.001418
725  20230726   200000    235959  ...  42475.796  1.242892e+09  0.004914

[5 rows x 11 columns]
2023-07-27 00:00:02,704:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230726   040000    075959  1690329599  ...    721  0.565665  0.836485     1.0
722  20230726   080000    115959  1690343999  ...    722  0.564654  0.813558     1.0
723  20230726   120000    155959  1690358399  ...    723  0.582017  0.862747     1.0
724  20230726   160000    195959  1690372799  ...    724  0.597699  0.904712     1.0
725  20230726   200000    235959  1690387199  ...    725  0.609597  0.931236     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.821', 'enterprice': '29117.6', 'countrevence': '0', 'unrealprofit': '10473.82163665318', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29308.65491758', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


