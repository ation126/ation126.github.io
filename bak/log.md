# 20230627 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12544
self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30377.3, self.close=30379.1, self.high=30417.0, self.low=30376.0, self.vol=606.24, self.amt=18424855.3594 
127.0.0.1 - - [27/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-27 00:20:07,688:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230626   235500    235959  ...         0.0        0.0       0
5760  20230627   000000    000459  ...         0.0        0.0       0
5761  20230627   000500    000959  ...         0.0        0.0       0
5762  20230627   001000    001459  ...         0.0        0.0       0
5763  20230627   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 00:20:07,718:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30377.3, self.close=30379.1, self.high=30417.0, self.low=30376.0, self.vol=606.24, self.amt=18424855.3594, ukdf['pct'].iloc[-1]=5.6e-05 , ukdf['amount'].iloc[-1]=18424855.3594, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48963.73948345374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30380.89450549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12545
self.closeSec=1687796699, self.tradeDate='20230627', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30379.1, self.close=30359.5, self.high=30382.8, self.low=30343.3, self.vol=842.476, self.amt=25582897.8337 
2023-06-27 00:25:00,894:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230627   000000    000459  ...         0.0        0.0       0
5761  20230627   000500    000959  ...         0.0        0.0       0
5762  20230627   001000    001459  ...         0.0        0.0       0
5763  20230627   001500    001959  ...         0.0        0.0       0
5764  20230627   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 00:25:00,895:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687796699, self.tradeDate='20230627', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30379.1, self.close=30359.5, self.high=30382.8, self.low=30343.3, self.vol=842.476, self.amt=25582897.8337, ukdf['pct'].iloc[-1]=-0.000645 , ukdf['amount'].iloc[-1]=25582897.8337, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-48665.7996', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30359.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30377.3, self.close=30379.1, self.high=30417.0, self.low=30376.0 
127.0.0.1 - - [27/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-27 00:20:05,037:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30377.3, self.close=30379.1, self.high=30417.0, self.low=30376.0   
2023-06-27 00:20:06,587:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230626   235500    235959  1687795199  ...  30393.0 -0.000155   1727    5
1440  20230627   000000    000459  1687795499  ...  30377.3 -0.000549   1440    0
1441  20230627   000500    000959  1687795799  ...  30383.5 -0.000158   1441    1
1442  20230627   001000    001459  1687796099  ...  30373.1 -0.000244   1442    2
1443  20230627   001500    001959  1687796399  ...  30376.0  0.000056   1443    3

[5 rows x 11 columns]
2023-06-27 00:20:06,597:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [27/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=1, self.factor=0.5971710846002286, self.count=12547 

self.closeSec=1687796699, self.tradeDate='20230627', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30379.1, self.close=30359.5, self.high=30382.8, self.low=30343.3 
2023-06-27 00:25:00,794:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687796699, self.tradeDate='20230627', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30379.1, self.close=30359.5, self.high=30382.8, self.low=30343.3   
2023-06-27 00:25:00,871:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230627   000000    000459  1687795499  ...  30377.3 -0.000549   1440    0
1441  20230627   000500    000959  1687795799  ...  30383.5 -0.000158   1441    1
1442  20230627   001000    001459  1687796099  ...  30373.1 -0.000244   1442    2
1443  20230627   001500    001959  1687796399  ...  30376.0  0.000056   1443    3
1444  20230627   002000    002459  1687796699  ...  30343.3 -0.000645   1444    4

[5 rows x 11 columns]
2023-06-27 00:25:00,874:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-27 00:00:18,888:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230626    212959  30347.7  ...  47.916667  0.496488  0.530553
5803  20230626    215959  30407.9  ...  47.916667  0.535677  0.498022
5804  20230626    222959  30631.2  ...  47.500000  0.512377  0.479389
5805  20230626    225959  30503.9  ...  47.083333  0.492001  0.472703
5806  20230626    232959  30383.9  ...  46.666667  0.487435  0.468933

[5 rows x 33 columns]
0.5349264705882353
acc is : 0.5349264705882353
2023-06-27 00:00:18,964:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.518799  0.481201       1  ...  1.168140  -1.0  0.0000  1.226550
540     0  0.553479  0.446521       0  ...  1.161367   1.0 -0.0016  1.221401
541     1  0.493484  0.506516       0  ...  1.156798   1.0  0.0000  1.216596
542     1  0.488223  0.511777       0  ...  1.155744   1.0  0.0000  1.215487
543     1  0.495305  0.504695       1  ...  1.157426   1.0  0.0000  1.217257

[5 rows x 10 columns]
2023-06-27 00:00:18,977:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.518895  0.481105       1  ...  1.168140  -1.0  0.0000  1.225618
46     0  0.553376  0.446624       0  ...  1.161367   1.0 -0.0016  1.224205
47     1  0.493405  0.506595       0  ...  1.156798   1.0  0.0000  1.219389
48     1  0.488160  0.511840       0  ...  1.155744   1.0  0.0000  1.217129
49     1  0.495305  0.504695       1  ...  1.157426   1.0  0.0000  1.217257

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.426', 'enterprice': '30507.9', 'countrevence': '0', 'unrealprofit': '-2889.17585365962', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30402.55558763', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [27/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-27 00:00:04,446:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42472F1687795203671I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687795204064729, 'quantity': '26.559', 'price': '30400.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687795202727, 'updatetime': 1687795204064, 'tradetype': 'usdt', 'selfid': 42472, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687795204064, 'clientorderid': '42472F1687795203671I0L59', 'price': '30400.5', 'quantity': '26.559', 'commission': '807.4068795', 'commissionasset': 'USDT', 'tradetime': 1687795204064, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687795204064}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6272 

self.closeSec=1687795799, self.tradeDate='20230627', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30400.7', self.close='30384.8'
2023-06-27 00:10:01,126:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687795799, self.tradeDate='20230627', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30400.7', self.close='30384.8'
2023-06-27 00:10:01,144:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230626   232000    232959  1687793399  30408.1  30356.3 -0.001703
573  20230626   233000    233959  1687793999  30356.3  30444.6  0.002909
574  20230626   234000    234959  1687794599  30444.6  30428.5 -0.000529
575  20230626   235000    235959  1687795199  30428.6  30400.5 -0.000920
576  20230627   000000    000959  1687795799  30400.7  30384.8 -0.000516
2023-06-27 00:10:01,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6273 

self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30384.8', self.close='30379.1'
127.0.0.1 - - [27/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-27 00:20:07,417:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30384.8', self.close='30379.1'
2023-06-27 00:20:08,248:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230626   233000    233959  1687793999  30356.3  30444.6  0.002909
574  20230626   234000    234959  1687794599  30444.6  30428.5 -0.000529
575  20230626   235000    235959  1687795199  30428.6  30400.5 -0.000920
576  20230627   000000    000959  1687795799  30400.7  30384.8 -0.000516
577  20230627   001000    001959  1687796399  30384.8  30379.1 -0.000188
2023-06-27 00:20:08,257:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-27 00:00:02,107:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-27 00:00:02,179:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6270000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230626, closeTime:235959, close:30400.5, total:992420.1027844, pct_pre:-0.012042055769607485, thd:0.09813975092739952, side:sell 
127.0.0.1 - - [27/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6275 

self.closeSec=1687795799, self.tradeDate='20230627', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30400.7', self.close='30384.8'
2023-06-27 00:10:01,121:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687795799, self.tradeDate='20230627', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30400.7', self.close='30384.8'
2023-06-27 00:10:01,143:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230626   232000    232959  1687793399  30408.1  30356.3
17421  20230626   233000    233959  1687793999  30356.3  30444.6
17422  20230626   234000    234959  1687794599  30444.6  30428.5
17423  20230626   235000    235959  1687795199  30428.6  30400.5
17424  20230627   000000    000959  1687795799  30400.7  30384.8
2023-06-27 00:10:01,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6276 

self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30384.8', self.close='30379.1'
127.0.0.1 - - [27/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-27 00:20:09,702:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30384.8', self.close='30379.1'
2023-06-27 00:20:09,826:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230626   233000    233959  1687793999  30356.3  30444.6
17422  20230626   234000    234959  1687794599  30444.6  30428.5
17423  20230626   235000    235959  1687795199  30428.6  30400.5
17424  20230627   000000    000959  1687795799  30400.7  30384.8
17425  20230627   001000    001959  1687796399  30384.8  30379.1
2023-06-27 00:20:09,827:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-27 00:00:04,268:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42471F1687795203644I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687795204039578, 'quantity': '38.021', 'price': '30400.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687795202746, 'updatetime': 1687795204039, 'tradetype': 'usdt', 'selfid': 42471, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687795204039, 'clientorderid': '42471F1687795203644I0L2', 'price': '30400.6', 'quantity': '38.021', 'commission': '1155.8612126', 'commissionasset': 'USDT', 'tradetime': 1687795204039, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687795204039}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6275 

self.closeSec=1687795799, self.tradeDate='20230627', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30400.7', self.close='30384.8'
2023-06-27 00:10:01,133:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687795799, self.tradeDate='20230627', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30400.7', self.close='30384.8'
2023-06-27 00:10:01,146:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230626   232000    232959  1687793399  30408.1  30356.3
12237  20230626   233000    233959  1687793999  30356.3  30444.6
12238  20230626   234000    234959  1687794599  30444.6  30428.5
12239  20230626   235000    235959  1687795199  30428.6  30400.5
12240  20230627   000000    000959  1687795799  30400.7  30384.8
2023-06-27 00:10:01,146:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6276 

self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30384.8', self.close='30379.1'
127.0.0.1 - - [27/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-27 00:20:09,208:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30384.8', self.close='30379.1'
2023-06-27 00:20:09,559:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230626   233000    233959  1687793999  30356.3  30444.6
12238  20230626   234000    234959  1687794599  30444.6  30428.5
12239  20230626   235000    235959  1687795199  30428.6  30400.5
12240  20230627   000000    000959  1687795799  30400.7  30384.8
12241  20230627   001000    001959  1687796399  30384.8  30379.1
2023-06-27 00:20:09,567:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12544
self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30377.3, self.close=30379.1, self.high=30417.0, self.low=30376.0, self.vol=606.24, self.amt=18424855.3594 
127.0.0.1 - - [27/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-27 00:20:07,698:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230626   235500    235959  ...         0.0        0.0       0
5760  20230627   000000    000459  ...         0.0        0.0       0
5761  20230627   000500    000959  ...         0.0        0.0       0
5762  20230627   001000    001459  ...         0.0        0.0       0
5763  20230627   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 00:20:07,718:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687796399, self.tradeDate='20230627', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30377.3, self.close=30379.1, self.high=30417.0, self.low=30376.0, self.vol=606.24, self.amt=18424855.3594, ukdf['pct'].iloc[-1]=5.6e-05 , ukdf['amount'].iloc[-1]=18424855.3594, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '131363.79882840409', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30380.89450549', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [27/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12545
self.closeSec=1687796699, self.tradeDate='20230627', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30379.1, self.close=30359.5, self.high=30382.8, self.low=30343.3, self.vol=842.476, self.amt=25582897.8337 
2023-06-27 00:25:00,892:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230627   000000    000459  ...         0.0        0.0       0
5761  20230627   000500    000959  ...         0.0        0.0       0
5762  20230627   001000    001459  ...         0.0        0.0       0
5763  20230627   001500    001959  ...         0.0        0.0       0
5764  20230627   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 00:25:00,892:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687796699, self.tradeDate='20230627', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30379.1, self.close=30359.5, self.high=30382.8, self.low=30343.3, self.vol=842.476, self.amt=25582897.8337, ukdf['pct'].iloc[-1]=-0.000645 , ukdf['amount'].iloc[-1]=25582897.8337, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '130569.1855', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30359.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230626   120000    155959  1687766399  ...    723  0.211291 -1.035406    -1.0
724  20230626   160000    195959  1687780799  ...    724  0.203232 -1.043268    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '20768.28803445444', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30317.11699267', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=261
self.closeSec=1687795199, self.tradeDate='20230626', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30315.1, self.close=30400.5, self.high=30667.3, self.low=30241.3, self.vol=86040.677, self.amt=2618050493.86816 
2023-06-27 00:00:01,687:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687795199, self.tradeDate='20230626', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30315.1, self.close=30400.5, self.high=30667.3, self.low=30241.3, self.vol=86040.677, self.amt=2618050493.86816 
2023-06-27 00:00:01,709:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230626   040000    075959  ...  38707.641  1.178424e+09  0.001249
722  20230626   080000    115959  ...  87301.166  2.637983e+09 -0.005680
723  20230626   120000    155959  ...  60412.330  1.834276e+09  0.003652
724  20230626   160000    195959  ...  45961.531  1.391983e+09 -0.002648
725  20230626   200000    235959  ...  86040.677  2.618050e+09  0.002817

[5 rows x 11 columns]
2023-06-27 00:00:02,995:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230626   040000    075959  1687737599  ...    721  0.240057 -0.983551    -1.0
722  20230626   080000    115959  1687751999  ...    722  0.206493 -1.061974    -1.0
723  20230626   120000    155959  1687766399  ...    723  0.211291 -1.035406    -1.0
724  20230626   160000    195959  1687780799  ...    724  0.203232 -1.043268    -1.0
725  20230626   200000    235959  1687795199  ...    725  0.179621 -1.091527    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '16105.32380144952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30404.65480586', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


