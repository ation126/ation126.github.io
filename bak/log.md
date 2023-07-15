# 20230716 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18016
self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30269.3, self.close=30286.3, self.high=30295.7, self.low=30269.3, self.vol=479.274, self.amt=14513624.9965 
127.0.0.1 - - [16/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 00:20:05,867:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230715   235500    235959  ...         0.0        0.0       0
5760  20230716   000000    000459  ...         0.0        0.0       0
5761  20230716   000500    000959  ...         0.0        0.0       0
5762  20230716   001000    001459  ...         0.0        0.0       0
5763  20230716   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 00:20:05,887:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30269.3, self.close=30286.3, self.high=30295.7, self.low=30269.3, self.vol=479.274, self.amt=14513624.9965, ukdf['pct'].iloc[-1]=0.000558 , ukdf['amount'].iloc[-1]=14513624.9965, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47696.96142918696', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30289.92954396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18017
self.closeSec=1689438299, self.tradeDate='20230716', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30286.4, self.close=30250.2, self.high=30286.4, self.low=30238.1, self.vol=811.53, self.amt=24554923.5493 
2023-07-16 00:25:00,897:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230716   000000    000459  ...         0.0        0.0       0
5761  20230716   000500    000959  ...         0.0        0.0       0
5762  20230716   001000    001459  ...         0.0        0.0       0
5763  20230716   001500    001959  ...         0.0        0.0       0
5764  20230716   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 00:25:00,898:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689438299, self.tradeDate='20230716', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30286.4, self.close=30250.2, self.high=30286.4, self.low=30238.1, self.vol=811.53, self.amt=24554923.5493, ukdf['pct'].iloc[-1]=-0.001192 , ukdf['amount'].iloc[-1]=24554923.5493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47192.4288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30253.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30269.3, self.close=30286.3, self.high=30295.7, self.low=30269.3 
127.0.0.1 - - [16/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 00:20:03,911:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30269.3, self.close=30286.3, self.high=30295.7, self.low=30269.3   
2023-07-16 00:20:05,106:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230715   235500    235959  1689436799  ...  30284.2 -0.000406   1727    5
1440  20230716   000000    000459  1689437099  ...  30270.3 -0.000399   1440    0
1441  20230716   000500    000959  1689437399  ...  30246.7 -0.000667   1441    1
1442  20230716   001000    001459  1689437699  ...  30255.9  0.000370   1442    2
1443  20230716   001500    001959  1689437999  ...  30269.3  0.000558   1443    3

[5 rows x 11 columns]
2023-07-16 00:20:05,107:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6169913962517329, self.count=18019 

self.closeSec=1689438299, self.tradeDate='20230716', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30286.4, self.close=30250.2, self.high=30286.4, self.low=30238.1 
127.0.0.1 - - [16/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-16 00:25:00,834:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689438299, self.tradeDate='20230716', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30286.4, self.close=30250.2, self.high=30286.4, self.low=30238.1   
2023-07-16 00:25:00,874:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230716   000000    000459  1689437099  ...  30270.3 -0.000399   1440    0
1441  20230716   000500    000959  1689437399  ...  30246.7 -0.000667   1441    1
1442  20230716   001000    001459  1689437699  ...  30255.9  0.000370   1442    2
1443  20230716   001500    001959  1689437999  ...  30269.3  0.000558   1443    3
1444  20230716   002000    002459  1689438299  ...  30238.1 -0.001192   1444    4

[5 rows x 11 columns]
2023-07-16 00:25:00,875:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-16 00:00:18,381:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230715    212959  30334.3  ...  55.000000  0.433441  0.701273
5803  20230715    215959  30287.3  ...  55.000000  0.439058  0.688443
5804  20230715    222959  30310.6  ...  54.583333  0.433146  0.655896
5805  20230715    225959  30279.2  ...  54.166667  0.431782  0.626473
5806  20230715    232959  30272.0  ...  54.583333  0.433022  0.601270

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-07-16 00:00:18,472:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.471438  0.528562       1  ...  1.000370   1.0    0.0  0.980852
540     1  0.497642  0.502358       0  ...  0.999337   1.0    0.0  0.979840
541     1  0.478324  0.521676       0  ...  0.999099   1.0    0.0  0.979607
542     1  0.478366  0.521634       1  ...  0.999261   1.0    0.0  0.979765
543     1  0.484046  0.515954       1  ...  0.999709   1.0    0.0  0.980205

[5 rows x 10 columns]
2023-07-16 00:00:18,495:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.471064  0.528936       1  ...  1.000370   1.0    0.0  0.976646
46     1  0.497620  0.502380       0  ...  0.999337   1.0    0.0  0.977060
47     1  0.478364  0.521636       0  ...  0.999099   1.0    0.0  0.976828
48     1  0.477968  0.522032       1  ...  0.999261   1.0    0.0  0.976359
49     1  0.484046  0.515954       1  ...  0.999709   1.0    0.0  0.980205

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.379', 'enterprice': '30337.4', 'countrevence': '0', 'unrealprofit': '-1301.8386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30284', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [16/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-16 00:00:04,617:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42645F1689436803765I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689436804186807, 'quantity': '24.279', 'price': '30290.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689436802796, 'updatetime': 1689436804186, 'tradetype': 'usdt', 'selfid': 42645, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689436804186, 'clientorderid': '42645F1689436803765I0L59', 'price': '30290.5', 'quantity': '24.279', 'commission': '735.4230495', 'commissionasset': 'USDT', 'tradetime': 1689436804186, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689436804186}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9008 

self.closeSec=1689437399, self.tradeDate='20230716', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30258.2'
2023-07-16 00:10:01,116:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689437399, self.tradeDate='20230716', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30290.4', self.close='30258.2'
2023-07-16 00:10:01,146:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230715   232000    232959  1689434999  30297.7  30276.9 -0.000683
573  20230715   233000    233959  1689435599  30276.9  30291.9  0.000495
574  20230715   234000    234959  1689436199  30291.9  30307.2  0.000505
575  20230715   235000    235959  1689436799  30307.2  30290.5 -0.000551
576  20230716   000000    000959  1689437399  30290.4  30258.2 -0.001066
2023-07-16 00:10:01,146:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9009 

self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30258.2', self.close='30286.3'
127.0.0.1 - - [16/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 00:20:06,136:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30258.2', self.close='30286.3'
2023-07-16 00:20:06,796:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230715   233000    233959  1689435599  30276.9  30291.9  0.000495
574  20230715   234000    234959  1689436199  30291.9  30307.2  0.000505
575  20230715   235000    235959  1689436799  30307.2  30290.5 -0.000551
576  20230716   000000    000959  1689437399  30290.4  30258.2 -0.001066
577  20230716   001000    001959  1689437999  30258.2  30286.3  0.000929
2023-07-16 00:20:06,797:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-16 00:00:02,238:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-16 00:00:02,324:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7160000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230715, closeTime:235959, close:30290.5, total:1010358.7155583, pct_pre:-0.029268042919636028, thd:0.15608426744117748, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9011 

self.closeSec=1689437399, self.tradeDate='20230716', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30258.2'
2023-07-16 00:10:01,127:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689437399, self.tradeDate='20230716', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30290.4', self.close='30258.2'
127.0.0.1 - - [16/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-16 00:10:01,152:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230715   232000    232959  1689434999  30297.7  30276.9
17421  20230715   233000    233959  1689435599  30276.9  30291.9
17422  20230715   234000    234959  1689436199  30291.9  30307.2
17423  20230715   235000    235959  1689436799  30307.2  30290.5
17424  20230716   000000    000959  1689437399  30290.4  30258.2
2023-07-16 00:10:01,152:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9012 

self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30258.2', self.close='30286.3'
127.0.0.1 - - [16/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 00:20:07,537:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30258.2', self.close='30286.3'
2023-07-16 00:20:07,713:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230715   233000    233959  1689435599  30276.9  30291.9
17422  20230715   234000    234959  1689436199  30291.9  30307.2
17423  20230715   235000    235959  1689436799  30307.2  30290.5
17424  20230716   000000    000959  1689437399  30290.4  30258.2
17425  20230716   001000    001959  1689437999  30258.2  30286.3
2023-07-16 00:20:07,714:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [16/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-16 00:00:04,400:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42646F1689436803787I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689436804150640, 'quantity': '37.554', 'price': '30290.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689436802786, 'updatetime': 1689436804150, 'tradetype': 'usdt', 'selfid': 42646, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689436804150, 'clientorderid': '42646F1689436803787I0L2', 'price': '30290.5', 'quantity': '37.554', 'commission': '1137.529437', 'commissionasset': 'USDT', 'tradetime': 1689436804150, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689436804150}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [16/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9011 

self.closeSec=1689437399, self.tradeDate='20230716', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30290.4', self.close='30258.2'
2023-07-16 00:10:01,134:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689437399, self.tradeDate='20230716', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30290.4', self.close='30258.2'
2023-07-16 00:10:01,150:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230715   232000    232959  1689434999  30297.7  30276.9
12237  20230715   233000    233959  1689435599  30276.9  30291.9
12238  20230715   234000    234959  1689436199  30291.9  30307.2
12239  20230715   235000    235959  1689436799  30307.2  30290.5
12240  20230716   000000    000959  1689437399  30290.4  30258.2
2023-07-16 00:10:01,151:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9012 

self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30258.2', self.close='30286.3'
127.0.0.1 - - [16/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-16 00:20:07,389:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30258.2', self.close='30286.3'
2023-07-16 00:20:07,597:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230715   233000    233959  1689435599  30276.9  30291.9
12238  20230715   234000    234959  1689436199  30291.9  30307.2
12239  20230715   235000    235959  1689436799  30307.2  30290.5
12240  20230716   000000    000959  1689437399  30290.4  30258.2
12241  20230716   001000    001959  1689437999  30258.2  30286.3
2023-07-16 00:20:07,597:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18016
self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30269.3, self.close=30286.3, self.high=30295.7, self.low=30269.3, self.vol=479.274, self.amt=14513624.9965 
127.0.0.1 - - [16/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-16 00:20:05,849:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230715   235500    235959  ...         0.0        0.0       0
5760  20230716   000000    000459  ...         0.0        0.0       0
5761  20230716   000500    000959  ...         0.0        0.0       0
5762  20230716   001000    001459  ...         0.0        0.0       0
5763  20230716   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 00:20:05,877:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689437999, self.tradeDate='20230716', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30269.3, self.close=30286.3, self.high=30295.7, self.low=30269.3, self.vol=479.274, self.amt=14513624.9965, ukdf['pct'].iloc[-1]=0.000558 , ukdf['amount'].iloc[-1]=14513624.9965, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127985.26919221836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30289.92954396', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [16/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18017
self.closeSec=1689438299, self.tradeDate='20230716', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30286.4, self.close=30250.2, self.high=30286.4, self.low=30238.1, self.vol=811.53, self.amt=24554923.5493 
2023-07-16 00:25:00,898:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230716   000000    000459  ...         0.0        0.0       0
5761  20230716   000500    000959  ...         0.0        0.0       0
5762  20230716   001000    001459  ...         0.0        0.0       0
5763  20230716   001500    001959  ...         0.0        0.0       0
5764  20230716   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-16 00:25:00,899:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689438299, self.tradeDate='20230716', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30286.4, self.close=30250.2, self.high=30286.4, self.low=30238.1, self.vol=811.53, self.amt=24554923.5493, ukdf['pct'].iloc[-1]=-0.001192 , ukdf['amount'].iloc[-1]=24554923.5493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '126639.6677', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30253.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230715   120000    155959  1689407999  ...    723  0.473833  0.585196     NaN
724  20230715   160000    195959  1689422399  ...    724  0.497323  0.681657     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-11111.6607', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30298.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [16/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=375
self.closeSec=1689436799, self.tradeDate='20230715', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30298.5, self.close=30290.5, self.high=30348.4, self.low=30237.0, self.vol=19740.322, self.amt=598043672.2784 
2023-07-16 00:00:01,701:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689436799, self.tradeDate='20230715', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30298.5, self.close=30290.5, self.high=30348.4, self.low=30237.0, self.vol=19740.322, self.amt=598043672.2784 
2023-07-16 00:00:01,758:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230715   040000    075959  ...  59521.811  1.795398e+09  0.006425
722  20230715   080000    115959  ...  29471.378  8.929200e+08 -0.000571
723  20230715   120000    155959  ...  18539.329  5.617057e+08  0.001374
724  20230715   160000    195959  ...  17263.000  5.232511e+08 -0.000630
725  20230715   200000    235959  ...  19740.322  5.980437e+08 -0.000264

[5 rows x 11 columns]
2023-07-16 00:00:03,241:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230715   040000    075959  1689379199  ...    721  0.334821  0.061710     NaN
722  20230715   080000    115959  1689393599  ...    722  0.452623  0.490778     NaN
723  20230715   120000    155959  1689407999  ...    723  0.473833  0.585196     NaN
724  20230715   160000    195959  1689422399  ...    724  0.497323  0.681657     1.0
725  20230715   200000    235959  1689436799  ...    725  0.515319  0.731175     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '-11529.5887', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30290.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


