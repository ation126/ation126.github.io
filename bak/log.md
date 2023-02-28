# 20230301 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [01/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26908
self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23494.7, self.close=23480.1, self.high=23521.0, self.low=23471.3, self.vol=2496.994, self.amt=58658156.8287 
2023-03-01 00:20:01,720:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230228   235500    235959  ...         0.0        0.0       0
5760  20230301   000000    000459  ...         0.0        0.0       0
5761  20230301   000500    000959  ...         0.0        0.0       0
5762  20230301   001000    001459  ...         0.0        0.0       0
5763  20230301   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 00:20:01,720:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23494.7, self.close=23480.1, self.high=23521.0, self.low=23471.3, self.vol=2496.994, self.amt=58658156.8287, ukdf['pct'].iloc[-1]=-0.000626 , ukdf['amount'].iloc[-1]=58658156.8287, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-418283.37437464624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23480.29997299', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [01/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26909
self.closeSec=1677601499, self.tradeDate='20230301', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23480.1, self.close=23468.2, self.high=23502.0, self.low=23450.0, self.vol=2355.833, self.amt=55295563.1847 
2023-03-01 00:25:01,590:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230301   000000    000459  ...         0.0        0.0       0
5761  20230301   000500    000959  ...         0.0        0.0       0
5762  20230301   001000    001459  ...         0.0        0.0       0
5763  20230301   001500    001959  ...         0.0        0.0       0
5764  20230301   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 00:25:01,590:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677601499, self.tradeDate='20230301', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23480.1, self.close=23468.2, self.high=23502.0, self.low=23450.0, self.vol=2355.833, self.amt=55295563.1847, ukdf['pct'].iloc[-1]=-0.000507 , ukdf['amount'].iloc[-1]=55295563.1847, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-417747.8096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23471.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23494.7, self.close=23480.1, self.high=23521.0, self.low=23471.3 
127.0.0.1 - - [01/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-01 00:20:01,530:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23494.7, self.close=23480.1, self.high=23521.0, self.low=23471.3   
2023-03-01 00:20:01,581:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230228   235500    235959  1677599999  ...  23481.0  0.000800   1727    5
1440  20230301   000000    000459  1677600299  ...  23507.9  0.000834   1440    0
1441  20230301   000500    000959  1677600599  ...  23531.1  0.000990   1441    1
1442  20230301   001000    001459  1677600899  ...  23489.0 -0.002518   1442    2
1443  20230301   001500    001959  1677601199  ...  23471.3 -0.000626   1443    3

[5 rows x 11 columns]
2023-03-01 00:20:01,581:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=68, self.factor=0.5202676652184015, self.count=27475 

self.closeSec=1677601499, self.tradeDate='20230301', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23480.1, self.close=23468.2, self.high=23502.0, self.low=23450.0 
2023-03-01 00:25:01,491:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677601499, self.tradeDate='20230301', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23480.1, self.close=23468.2, self.high=23502.0, self.low=23450.0   
127.0.0.1 - - [01/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-03-01 00:25:01,560:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230301   000000    000459  1677600299  ...  23507.9  0.000834   1440    0
1441  20230301   000500    000959  1677600599  ...  23531.1  0.000990   1441    1
1442  20230301   001000    001459  1677600899  ...  23489.0 -0.002518   1442    2
1443  20230301   001500    001959  1677601199  ...  23471.3 -0.000626   1443    3
1444  20230301   002000    002459  1677601499  ...  23450.0 -0.000507   1444    4

[5 rows x 11 columns]
2023-03-01 00:25:01,562:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-01 00:00:34,632:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230228    212959  23445.6  ...  48.333333  0.504887  0.575466
5803  20230228    215959  23396.9  ...  48.333333  0.504357  0.562223
5804  20230228    222959  23394.6  ...  47.916667  0.501186  0.551707
5805  20230228    225959  23381.0  ...  48.333333  0.508124  0.537839
5806  20230228    232959  23411.0  ...  48.750000  0.518522  0.518731

[5 rows x 33 columns]
0.5275735294117647
acc is : 0.5275735294117647
2023-03-01 00:00:34,776:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505322  0.494678       0  ...  0.897365  -1.0    0.0  0.989787
540     0  0.513966  0.486034       0  ...  0.897887  -1.0    0.0  0.989211
541     0  0.506104  0.493896       1  ...  0.896739  -1.0    0.0  0.990476
542     0  0.507759  0.492241       1  ...  0.894996  -1.0    0.0  0.992401
543     0  0.518239  0.481761       1  ...  0.892905  -1.0    0.0  0.994720

[5 rows x 10 columns]
2023-03-01 00:00:34,809:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504988  0.495012       0  ...  0.888968  -1.0    0.0  0.985966
46     0  0.513994  0.486006       0  ...  0.897887  -1.0    0.0  0.987661
47     0  0.506147  0.493853       1  ...  0.896739  -1.0    0.0  0.988924
48     0  0.507183  0.492817       1  ...  0.886621  -1.0    0.0  0.986915
49     0  0.518239  0.481761       1  ...  0.892905  -1.0    0.0  0.994720

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.752', 'enterprice': '23379.5', 'countrevence': '0', 'unrealprofit': '-4624.5824', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23520.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [01/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-01 00:00:03,309:INFO:modifiedmom:main.py:319:handleOrderFilled:185213: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41854F1677600002664I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677600002806394, 'quantity': '43.281', 'price': '23510.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677600002295, 'updatetime': 1677600002806, 'tradetype': 'usdt', 'selfid': 41854, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677600002806, 'clientorderid': '41854F1677600002664I0L59', 'price': '23510.7', 'quantity': '43.281', 'commission': '1017.5666067', 'commissionasset': 'USDT', 'tradetime': 1677600002806, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677600002806}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13736 

self.closeSec=1677600599, self.tradeDate='20230301', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23511.1', self.close='23554.1'
2023-03-01 00:10:01,755:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677600599, self.tradeDate='20230301', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23511.1', self.close='23554.1'
2023-03-01 00:10:01,770:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230228   232000    232959  1677598199  23422.4  23456.4  0.001447
573  20230228   233000    233959  1677598799  23456.5  23492.1  0.001522
574  20230228   234000    234959  1677599399    23492  23478.1 -0.000596
575  20230228   235000    235959  1677599999  23475.1  23511.2  0.001410
576  20230301   000000    000959  1677600599  23511.1  23554.1  0.001825
2023-03-01 00:10:01,770:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13737 

self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23554', self.close='23480.1'
127.0.0.1 - - [01/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-03-01 00:20:01,607:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23554', self.close='23480.1'
2023-03-01 00:20:01,635:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230228   233000    233959  1677598799  23456.5  23492.1  0.001522
574  20230228   234000    234959  1677599399    23492  23478.1 -0.000596
575  20230228   235000    235959  1677599999  23475.1  23511.2  0.001410
576  20230301   000000    000959  1677600599  23511.1  23554.1  0.001825
577  20230301   001000    001959  1677601199    23554  23480.1 -0.003142
2023-03-01 00:20:01,635:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-03-01 00:00:01,955:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-03-01 00:00:02,063:INFO:pyemd2:main.py:190:insertFactor:185189: curDateTime:3010000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230228, closeTime:235959, close:23511.2, total:985099.9112013, pct_pre:-0.012525050100200441, thd:0.47233088318056715, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13737 

self.closeSec=1677600599, self.tradeDate='20230301', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23511.1', self.close='23554.1'
2023-03-01 00:10:01,739:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677600599, self.tradeDate='20230301', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23511.1', self.close='23554.1'
127.0.0.1 - - [01/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-03-01 00:10:01,771:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230228   232000    232959  1677598199  23422.4  23456.4
17421  20230228   233000    233959  1677598799  23456.5  23492.1
17422  20230228   234000    234959  1677599399    23492  23478.1
17423  20230228   235000    235959  1677599999  23475.1  23511.2
17424  20230301   000000    000959  1677600599  23511.1  23554.1
2023-03-01 00:10:01,771:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [01/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13738 

self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23554', self.close='23480.1'
2023-03-01 00:20:01,635:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23554', self.close='23480.1'
2023-03-01 00:20:01,705:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230228   233000    233959  1677598799  23456.5  23492.1
17422  20230228   234000    234959  1677599399    23492  23478.1
17423  20230228   235000    235959  1677599999  23475.1  23511.2
17424  20230301   000000    000959  1677600599  23511.1  23554.1
17425  20230301   001000    001959  1677601199    23554  23480.1
2023-03-01 00:20:01,705:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [01/Mar/2023 00:00:03] "POST / HTTP/1.1" 200 -
2023-03-01 00:00:03,093:INFO:testStrategy:main.py:308:handleOrderFilled:185174: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '41855F1677600002697I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1677600002804899, 'quantity': '49.496', 'price': '23510.7', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1677600002364, 'updatetime': 1677600002804, 'tradetype': 'usdt', 'selfid': 41855, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1677600002804, 'clientorderid': '41855F1677600002697I0L2', 'price': '23510.7', 'quantity': '49.496', 'commission': '1163.6856072', 'commissionasset': 'USDT', 'tradetime': 1677600002804, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1677600002804}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [01/Mar/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13737 

self.closeSec=1677600599, self.tradeDate='20230301', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='23511.1', self.close='23554.1'
2023-03-01 00:10:01,738:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677600599, self.tradeDate='20230301', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='23511.1', self.close='23554.1'
2023-03-01 00:10:01,767:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230228   232000    232959  1677598199  23422.4  23456.4
12237  20230228   233000    233959  1677598799  23456.5  23492.1
12238  20230228   234000    234959  1677599399    23492  23478.1
12239  20230228   235000    235959  1677599999  23475.1  23511.2
12240  20230301   000000    000959  1677600599  23511.1  23554.1
2023-03-01 00:10:01,767:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}
127.0.0.1 - - [01/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13738 

self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='23554', self.close='23480.1'
2023-03-01 00:20:01,641:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='23554', self.close='23480.1'
2023-03-01 00:20:01,710:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230228   233000    233959  1677598799  23456.5  23492.1
12238  20230228   234000    234959  1677599399    23492  23478.1
12239  20230228   235000    235959  1677599999  23475.1  23511.2
12240  20230301   000000    000959  1677600599  23511.1  23554.1
12241  20230301   001000    001959  1677601199    23554  23480.1
2023-03-01 00:20:01,710:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [01/Mar/2023 00:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22906
self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=23494.7, self.close=23480.1, self.high=23521.0, self.low=23471.3, self.vol=2496.994, self.amt=58658156.8287 
2023-03-01 00:20:01,663:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230228   235500    235959  ...         0.0        0.0       0
5760  20230301   000000    000459  ...         0.0        0.0       0
5761  20230301   000500    000959  ...         0.0        0.0       0
5762  20230301   001000    001459  ...         0.0        0.0       0
5763  20230301   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 00:20:01,671:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677601199, self.tradeDate='20230301', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=23494.7, self.close=23480.1, self.high=23521.0, self.low=23471.3, self.vol=2496.994, self.amt=58658156.8287, ukdf['pct'].iloc[-1]=-0.000626 , ukdf['amount'].iloc[-1]=58658156.8287, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [01/Mar/2023 00:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22907
self.closeSec=1677601499, self.tradeDate='20230301', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=23480.1, self.close=23468.2, self.high=23502.0, self.low=23450.0, self.vol=2355.833, self.amt=55295563.1847 
2023-03-01 00:25:01,623:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230301   000000    000459  ...         0.0        0.0       0
5761  20230301   000500    000959  ...         0.0        0.0       0
5762  20230301   001000    001459  ...         0.0        0.0       0
5763  20230301   001500    001959  ...         0.0        0.0       0
5764  20230301   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-01 00:25:01,623:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677601499, self.tradeDate='20230301', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=23480.1, self.close=23468.2, self.high=23502.0, self.low=23450.0, self.vol=2355.833, self.amt=55295563.1847, ukdf['pct'].iloc[-1]=-0.000507 , ukdf['amount'].iloc[-1]=55295563.1847, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230228   120000    155959  1677571199  ...    723  0.613378 -0.076614     NaN
724  20230228   160000    195959  1677585599  ...    724  0.590085 -0.133811     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '11666.25663951928', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23385.38921832', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=572
self.closeSec=1677599999, self.tradeDate='20230228', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=23381.5, self.close=23511.2, self.high=23571.1, self.low=23300.5, self.vol=126298.911, self.amt=2961352323.422 
127.0.0.1 - - [01/Mar/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-03-01 00:00:01,831:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677599999, self.tradeDate='20230228', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=23381.5, self.close=23511.2, self.high=23571.1, self.low=23300.5, self.vol=126298.911, self.amt=2961352323.422 
2023-03-01 00:00:01,895:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230228   040000    075959  ...   76820.163  1.793671e+09  0.009350
722  20230228   080000    115959  ...   44084.232  1.033383e+09 -0.001095
723  20230228   120000    155959  ...   44074.367  1.028988e+09 -0.009849
724  20230228   160000    195959  ...   51908.370  1.209622e+09  0.006816
725  20230228   200000    235959  ...  126298.911  2.961352e+09  0.005543

[5 rows x 11 columns]
2023-03-01 00:00:04,383:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230228   040000    075959  1677542399  ...    721  0.716158  0.166024     NaN
722  20230228   080000    115959  1677556799  ...    722  0.666186  0.050230     NaN
723  20230228   120000    155959  1677571199  ...    723  0.613378 -0.076614     NaN
724  20230228   160000    195959  1677585599  ...    724  0.590085 -0.133811     NaN
725  20230228   200000    235959  1677599999  ...    725  0.558675 -0.210626     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '16955.958', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23510.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


