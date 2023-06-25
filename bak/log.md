# 20230626 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12256
self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30533.9, self.close=30548.1, self.high=30560.0, self.low=30481.6, self.vol=1707.906, self.amt=52130090.9092 
127.0.0.1 - - [26/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-26 00:20:07,365:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230625   235500    235959  ...         0.0        0.0       0
5760  20230626   000000    000459  ...         0.0        0.0       0
5761  20230626   000500    000959  ...         0.0        0.0       0
5762  20230626   001000    001459  ...         0.0        0.0       0
5763  20230626   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 00:20:07,395:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30533.9, self.close=30548.1, self.high=30560.0, self.low=30481.6, self.vol=1707.906, self.amt=52130090.9092, ukdf['pct'].iloc[-1]=0.000468 , ukdf['amount'].iloc[-1]=52130090.9092, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-51270.4325334531', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30546.53381685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12257
self.closeSec=1687710299, self.tradeDate='20230626', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30548.1, self.close=30510.8, self.high=30548.2, self.low=30510.0, self.vol=658.111, self.amt=20091430.9493 
2023-06-26 00:25:00,770:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230626   000000    000459  ...         0.0        0.0       0
5761  20230626   000500    000959  ...         0.0        0.0       0
5762  20230626   001000    001459  ...         0.0        0.0       0
5763  20230626   001500    001959  ...         0.0        0.0       0
5764  20230626   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 00:25:00,770:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687710299, self.tradeDate='20230626', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30548.1, self.close=30510.8, self.high=30548.2, self.low=30510.0, self.vol=658.111, self.amt=20091430.9493, ukdf['pct'].iloc[-1]=-0.001221 , ukdf['amount'].iloc[-1]=20091430.9493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50785.83244834308', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30511.73559158', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30533.9, self.close=30548.1, self.high=30560.0, self.low=30481.6 
127.0.0.1 - - [26/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-26 00:20:05,155:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30533.9, self.close=30548.1, self.high=30560.0, self.low=30481.6   
2023-06-26 00:20:06,535:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230625   235500    235959  1687708799  ...  30542.1  0.000370   1727    5
1440  20230626   000000    000459  1687709099  ...  30547.8  0.000890   1440    0
1441  20230626   000500    000959  1687709399  ...  30599.1  0.000807   1441    1
1442  20230626   001000    001459  1687709699  ...  30512.3 -0.003011   1442    2
1443  20230626   001500    001959  1687709999  ...  30481.6  0.000468   1443    3

[5 rows x 11 columns]
2023-06-26 00:20:06,547:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=421, self.factor=0.4948681527888591, self.count=12259 

self.closeSec=1687710299, self.tradeDate='20230626', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30548.1, self.close=30510.8, self.high=30548.2, self.low=30510.0 
2023-06-26 00:25:00,711:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687710299, self.tradeDate='20230626', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30548.1, self.close=30510.8, self.high=30548.2, self.low=30510.0   
127.0.0.1 - - [26/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-26 00:25:00,753:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230626   000000    000459  1687709099  ...  30547.8  0.000890   1440    0
1441  20230626   000500    000959  1687709399  ...  30599.1  0.000807   1441    1
1442  20230626   001000    001459  1687709699  ...  30512.3 -0.003011   1442    2
1443  20230626   001500    001959  1687709999  ...  30481.6  0.000468   1443    3
1444  20230626   002000    002459  1687710299  ...  30510.0 -0.001221   1444    4

[5 rows x 11 columns]
2023-06-26 00:25:00,754:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-26 00:00:18,968:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230625    212959  30664.1  ...  51.666667  0.509976  0.444535
5803  20230625    215959  30583.1  ...  52.083333  0.524321  0.453793
5804  20230625    222959  30669.2  ...  52.500000  0.527081  0.460733
5805  20230625    225959  30686.0  ...  52.083333  0.501476  0.481886
5806  20230625    232959  30540.2  ...  52.083333  0.505771  0.499056

[5 rows x 33 columns]
0.5459558823529411
acc is : 0.5459558823529411
2023-06-26 00:00:19,053:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.476229  0.523771       1  ...  1.170869  -1.0    0.0  1.184866
540     0  0.507233  0.492767       1  ...  1.170228  -1.0    0.0  1.185515
541     1  0.491001  0.508999       0  ...  1.175754  -1.0    0.0  1.179917
542     1  0.459780  0.540220       1  ...  1.174776  -1.0    0.0  1.180899
543     1  0.485332  0.514668       1  ...  1.174484  -1.0    0.0  1.181192

[5 rows x 10 columns]
2023-06-26 00:00:19,079:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.476307  0.523693       1  ...  1.170869  -1.0    0.0  1.185343
46     0  0.507222  0.492778       1  ...  1.170228  -1.0    0.0  1.185744
47     1  0.491076  0.508924       0  ...  1.175754  -1.0    0.0  1.180145
48     1  0.459940  0.540060       1  ...  1.174776  -1.0    0.0  1.181739
49     1  0.485332  0.514668       1  ...  1.174484  -1.0    0.0  1.181192

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '9602.9109', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30578.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [26/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-26 00:00:04,579:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42465F1687708803677I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687708804078419, 'quantity': '26.311', 'price': '30574', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687708802794, 'updatetime': 1687708804078, 'tradetype': 'usdt', 'selfid': 42465, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687708804078, 'clientorderid': '42465F1687708803677I0L59', 'price': '30574', 'quantity': '26.311', 'commission': '804.432514', 'commissionasset': 'USDT', 'tradetime': 1687708804078, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687708804078}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6128 

self.closeSec=1687709399, self.tradeDate='20230626', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30574.1', self.close='30626'
127.0.0.1 - - [26/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-26 00:10:01,083:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687709399, self.tradeDate='20230626', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30574.1', self.close='30626'
2023-06-26 00:10:01,108:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230625   232000    232959  1687706999  30606.5  30566.5 -0.001304
573  20230625   233000    233959  1687707599  30566.5  30574.1  0.000249
574  20230625   234000    234959  1687708199  30574.1    30606  0.001043
575  20230625   235000    235959  1687708799    30606  30574.1 -0.001042
576  20230626   000000    000959  1687709399  30574.1    30626  0.001698
2023-06-26 00:10:01,108:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6129 

self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30626', self.close='30548.1'
127.0.0.1 - - [26/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 00:20:06,997:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30626', self.close='30548.1'
2023-06-26 00:20:07,745:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230625   233000    233959  1687707599  30566.5  30574.1  0.000249
574  20230625   234000    234959  1687708199  30574.1    30606  0.001043
575  20230625   235000    235959  1687708799    30606  30574.1 -0.001042
576  20230626   000000    000959  1687709399  30574.1    30626  0.001698
577  20230626   001000    001959  1687709999    30626  30548.1 -0.002544
2023-06-26 00:20:07,745:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-26 00:00:04,379:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42464F1687708803573I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687708804014483, 'quantity': '32.459', 'price': '30574', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687708802606, 'updatetime': 1687708804014, 'tradetype': 'usdt', 'selfid': 42464, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687708804014, 'clientorderid': '42464F1687708803573I0L57', 'price': '30574', 'quantity': '32.459', 'commission': '992.401466', 'commissionasset': 'USDT', 'tradetime': 1687708804014, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687708804014}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [26/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6131 

self.closeSec=1687709399, self.tradeDate='20230626', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30574.1', self.close='30626'
127.0.0.1 - - [26/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-26 00:10:01,079:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687709399, self.tradeDate='20230626', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30574.1', self.close='30626'
2023-06-26 00:10:01,116:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230625   232000    232959  1687706999  30606.5  30566.5
17421  20230625   233000    233959  1687707599  30566.5  30574.1
17422  20230625   234000    234959  1687708199  30574.1    30606
17423  20230625   235000    235959  1687708799    30606  30574.1
17424  20230626   000000    000959  1687709399  30574.1    30626
2023-06-26 00:10:01,116:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6132 

self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30626', self.close='30548.1'
127.0.0.1 - - [26/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 00:20:08,926:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30626', self.close='30548.1'
2023-06-26 00:20:09,063:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230625   233000    233959  1687707599  30566.5  30574.1
17422  20230625   234000    234959  1687708199  30574.1    30606
17423  20230625   235000    235959  1687708799    30606  30574.1
17424  20230626   000000    000959  1687709399  30574.1    30626
17425  20230626   001000    001959  1687709999    30626  30548.1
2023-06-26 00:20:09,063:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [26/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-26 00:00:04,157:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42463F1687708803536I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687708803937497, 'quantity': '37.955', 'price': '30574', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687708802709, 'updatetime': 1687708803937, 'tradetype': 'usdt', 'selfid': 42463, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687708803937, 'clientorderid': '42463F1687708803536I0L2', 'price': '30574', 'quantity': '37.955', 'commission': '1160.43617', 'commissionasset': 'USDT', 'tradetime': 1687708803937, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687708803937}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6131 

self.closeSec=1687709399, self.tradeDate='20230626', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30574.1', self.close='30626'
127.0.0.1 - - [26/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-26 00:10:01,090:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687709399, self.tradeDate='20230626', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30574.1', self.close='30626'
2023-06-26 00:10:01,113:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230625   232000    232959  1687706999  30606.5  30566.5
12237  20230625   233000    233959  1687707599  30566.5  30574.1
12238  20230625   234000    234959  1687708199  30574.1    30606
12239  20230625   235000    235959  1687708799    30606  30574.1
12240  20230626   000000    000959  1687709399  30574.1    30626
2023-06-26 00:10:01,114:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6132 

self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30626', self.close='30548.1'
127.0.0.1 - - [26/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 00:20:08,539:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30626', self.close='30548.1'
2023-06-26 00:20:08,827:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230625   233000    233959  1687707599  30566.5  30574.1
12238  20230625   234000    234959  1687708199  30574.1    30606
12239  20230625   235000    235959  1687708799    30606  30574.1
12240  20230626   000000    000959  1687709399  30574.1    30626
12241  20230626   001000    001959  1687709999    30626  30548.1
2023-06-26 00:20:08,828:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12256
self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30533.9, self.close=30548.1, self.high=30560.0, self.low=30481.6, self.vol=1707.906, self.amt=52130090.9092 
127.0.0.1 - - [26/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-26 00:20:07,375:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230625   235500    235959  ...         0.0        0.0       0
5760  20230626   000000    000459  ...         0.0        0.0       0
5761  20230626   000500    000959  ...         0.0        0.0       0
5762  20230626   001000    001459  ...         0.0        0.0       0
5763  20230626   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 00:20:07,395:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687709999, self.tradeDate='20230626', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30533.9, self.close=30548.1, self.high=30560.0, self.low=30481.6, self.vol=1707.906, self.amt=52130090.9092, ukdf['pct'].iloc[-1]=0.000468 , ukdf['amount'].iloc[-1]=52130090.9092, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '137515.80849162585', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30546.53381685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12257
self.closeSec=1687710299, self.tradeDate='20230626', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30548.1, self.close=30510.8, self.high=30548.2, self.low=30510.0, self.vol=658.111, self.amt=20091430.9493 
2023-06-26 00:25:00,731:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230626   000000    000459  ...         0.0        0.0       0
5761  20230626   000500    000959  ...         0.0        0.0       0
5762  20230626   001000    001459  ...         0.0        0.0       0
5763  20230626   001500    001959  ...         0.0        0.0       0
5764  20230626   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 00:25:00,732:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687710299, self.tradeDate='20230626', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30548.1, self.close=30510.8, self.high=30548.2, self.low=30510.0, self.vol=658.111, self.amt=20091430.9493, ukdf['pct'].iloc[-1]=-0.001221 , ukdf['amount'].iloc[-1]=20091430.9493, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136230.9100867585', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30511.9386685', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-06-25 20:00:11,336:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42461F1687694405675I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687694406049066, 'quantity': '53.344', 'price': '30709.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687694404826, 'updatetime': 1687694406049, 'tradetype': 'usdt', 'selfid': 42461, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687694406049, 'clientorderid': '42461F1687694405675I0L65', 'price': '30709.5', 'quantity': '53.344', 'commission': '1638.167568', 'commissionasset': 'USDT', 'tradetime': 1687694406049, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687694406049}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-25 20:00:11,336:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42461F1687694405675I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687694406049066, 'quantity': '53.344', 'price': '30709.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687694404826, 'updatetime': 1687694406049, 'tradetype': 'usdt', 'selfid': 42461, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687694406049, 'clientorderid': '42461F1687694405675I0L65', 'price': '30709.5', 'quantity': '53.344', 'commission': '1638.167568', 'commissionasset': 'USDT', 'tradetime': 1687694406049, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687694406049}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jun/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-06-25 20:00:11,731:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42462F1687694411313I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687694411707504, 'quantity': '53.268', 'price': '30707', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687694410816, 'updatetime': 1687694411707, 'tradetype': 'usdt', 'selfid': 42462, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687694411707, 'clientorderid': '42462F1687694411313I0L65', 'price': '30707', 'quantity': '53.268', 'commission': '1635.700476', 'commissionasset': 'USDT', 'tradetime': 1687694411707, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687694411707}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-25 20:00:12,154:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42462F1687694411313I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687694411707504, 'quantity': '53.268', 'price': '30707', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687694410816, 'updatetime': 1687694411707, 'tradetype': 'usdt', 'selfid': 42462, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687694411707, 'clientorderid': '42462F1687694411313I0L65', 'price': '30707', 'quantity': '53.268', 'commission': '1635.700476', 'commissionasset': 'USDT', 'tradetime': 1687694411707, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687694411707}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [25/Jun/2023 20:00:12] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=255
self.closeSec=1687708799, self.tradeDate='20230625', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30710.0, self.close=30574.1, self.high=30732.9, self.low=30425.0, self.vol=60922.334, self.amt=1864297432.75004 
127.0.0.1 - - [26/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-26 00:00:01,738:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687708799, self.tradeDate='20230625', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30710.0, self.close=30574.1, self.high=30732.9, self.low=30425.0, self.vol=60922.334, self.amt=1864297432.75004 
2023-06-26 00:00:01,759:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230625   040000    075959  ...  31333.988  9.561354e+08 -0.003204
722  20230625   080000    115959  ...  36315.838  1.111841e+09  0.007135
723  20230625   120000    155959  ...  79266.773  2.445980e+09 -0.000911
724  20230625   160000    195959  ...  36842.297  1.129452e+09 -0.000130
725  20230625   200000    235959  ...  60922.334  1.864297e+09 -0.004425

[5 rows x 11 columns]
2023-06-26 00:00:03,048:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230625   040000    075959  1687651199  ...    721  0.620402  0.062441     NaN
722  20230625   080000    115959  1687665599  ...    722  0.493758 -0.296012     NaN
723  20230625   120000    155959  1687679999  ...    723  0.469958 -0.369203     NaN
724  20230625   160000    195959  1687694399  ...    724  0.299954 -0.851107    -1.0
725  20230625   200000    235959  1687708799  ...    725  0.151870 -1.257836    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '6983.32358121012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30575.90208791', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


