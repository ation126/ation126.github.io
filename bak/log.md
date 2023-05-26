# 20230527 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3616
self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26743.0, self.close=26758.5, self.high=26765.7, self.low=26743.0, self.vol=670.895, self.amt=17952548.4352 
127.0.0.1 - - [27/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 00:20:04,520:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230526   235500    235959  ...    0.033904   0.196293       0
5760  20230527   000000    000459  ...    0.033745   0.196087       0
5761  20230527   000500    000959  ...    0.033585   0.195881       0
5762  20230527   001000    001459  ...    0.033426   0.195674       0
5763  20230527   001500    001959  ...    0.033266   0.195467       0

[5 rows x 18 columns]
2023-05-27 00:20:04,550:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26743.0, self.close=26758.5, self.high=26765.7, self.low=26743.0, self.vol=670.895, self.amt=17952548.4352, ukdf['pct'].iloc[-1]=0.00058 , ukdf['amount'].iloc[-1]=17952548.4352, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.03326617291328604, signal=0, value_std=0.19546720165155063 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '1466.77716681804', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26759.57347646', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [27/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=3617
self.closeSec=1685118299, self.tradeDate='20230527', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26757.6, self.close=26792.1, self.high=26820.0, self.low=26757.5, self.vol=2010.763, self.amt=53876122.738 
2023-05-27 00:25:00,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230527   000000    000459  ...    0.033745   0.196087       0
5761  20230527   000500    000959  ...    0.033585   0.195881       0
5762  20230527   001000    001459  ...    0.033426   0.195674       0
5763  20230527   001500    001959  ...    0.033266   0.195467       0
5764  20230527   002000    002459  ...    0.033105   0.195255       0

[5 rows x 18 columns]
2023-05-27 00:25:00,812:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685118299, self.tradeDate='20230527', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26757.6, self.close=26792.1, self.high=26820.0, self.low=26757.5, self.vol=2010.763, self.amt=53876122.738, ukdf['pct'].iloc[-1]=0.001256 , ukdf['amount'].iloc[-1]=53876122.738, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.03310502577119551, signal=0, value_std=0.19525531031298196 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '999.92697915594', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26793.09711481', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26743.0, self.close=26758.5, self.high=26765.7, self.low=26743.0 
127.0.0.1 - - [27/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 00:20:02,240:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26743.0, self.close=26758.5, self.high=26765.7, self.low=26743.0   
2023-05-27 00:20:03,500:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230526   235500    235959  1685116799  ...  26728.4  0.000281   1727    5
1440  20230527   000000    000459  1685117099  ...  26731.0  0.000752   1440    0
1441  20230527   000500    000959  1685117399  ...  26753.9  0.000303   1441    1
1442  20230527   001000    001459  1685117699  ...  26743.0 -0.000844   1442    2
1443  20230527   001500    001959  1685117999  ...  26743.0  0.000580   1443    3

[5 rows x 11 columns]
2023-05-27 00:20:03,500:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [27/May/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=3, self.factor=0.33624342619068437, self.count=3619 

self.closeSec=1685118299, self.tradeDate='20230527', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26757.6, self.close=26792.1, self.high=26820.0, self.low=26757.5 
2023-05-27 00:25:00,762:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685118299, self.tradeDate='20230527', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26757.6, self.close=26792.1, self.high=26820.0, self.low=26757.5   
2023-05-27 00:25:00,797:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230527   000000    000459  1685117099  ...  26731.0  0.000752   1440    0
1441  20230527   000500    000959  1685117399  ...  26753.9  0.000303   1441    1
1442  20230527   001000    001459  1685117699  ...  26743.0 -0.000844   1442    2
1443  20230527   001500    001959  1685117999  ...  26743.0  0.000580   1443    3
1444  20230527   002000    002459  1685118299  ...  26757.5  0.001256   1444    4

[5 rows x 11 columns]
2023-05-27 00:25:00,797:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-27 00:00:34,272:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230526    212959  26430.7  ...  47.500000  0.499146  0.428122
5803  20230526    215959  26456.7  ...  47.916667  0.520845  0.422624
5804  20230526    222959  26529.9  ...  47.916667  0.580419  0.403953
5805  20230526    225959  26764.9  ...  47.916667  0.574713  0.396485
5806  20230526    232959  26746.6  ...  47.916667  0.586701  0.383711

[5 rows x 33 columns]
0.5367647058823529
acc is : 0.5367647058823529
2023-05-27 00:00:34,438:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
539     0  0.502957  0.497043       1  ...  0.918662  -1.0  0.0000  0.968294
540     0  0.516777  0.483223       1  ...  0.910521  -1.0  0.0000  0.976875
541     0  0.563550  0.436450       0  ...  0.908438   1.0 -0.0016  0.976203
542     0  0.518430  0.481570       1  ...  0.910245   1.0  0.0000  0.978145
543     0  0.536696  0.463304       0  ...  0.908126   1.0  0.0000  0.975867

[5 rows x 10 columns]
2023-05-27 00:00:34,474:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.502817  0.497183       1  ...  0.918662  -1.0  0.0000  0.964787
46     0  0.516779  0.483221       1  ...  0.910521  -1.0  0.0000  0.974559
47     0  0.563662  0.436338       0  ...  0.908438   1.0 -0.0016  0.973889
48     0  0.518161  0.481839       1  ...  0.910245   1.0  0.0000  0.976797
49     0  0.536696  0.463304       0  ...  0.908126   1.0  0.0000  0.975867

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '-1332.72894097904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26740.97902072', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [27/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-27 00:00:04,455:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42270F1685116803821I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685116804205272, 'quantity': '25.866', 'price': '26742', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685116802820, 'updatetime': 1685116804205, 'tradetype': 'usdt', 'selfid': 42270, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685116804205, 'clientorderid': '42270F1685116803821I0L59', 'price': '26742', 'quantity': '25.866', 'commission': '691.708572', 'commissionasset': 'USDT', 'tradetime': 1685116804205, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685116804205}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1808 

self.closeSec=1685117399, self.tradeDate='20230527', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26737.5', self.close='26765.6'
2023-05-27 00:10:01,193:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685117399, self.tradeDate='20230527', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26737.5', self.close='26765.6'
2023-05-27 00:10:01,278:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230526   232000    232959  1685114999  26766.2  26799.8  0.001259
573  20230526   233000    233959  1685115599  26799.9    26761 -0.001448
574  20230526   234000    234959  1685116199    26761    26760 -0.000037
575  20230526   235000    235959  1685116799  26759.9  26737.4 -0.000845
576  20230527   000000    000959  1685117399  26737.5  26765.6  0.001055
2023-05-27 00:10:01,278:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1809 

self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26765.7', self.close='26758.5'
127.0.0.1 - - [27/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-27 00:20:05,321:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26765.7', self.close='26758.5'
2023-05-27 00:20:05,889:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230526   233000    233959  1685115599  26799.9    26761 -0.001448
574  20230526   234000    234959  1685116199    26761    26760 -0.000037
575  20230526   235000    235959  1685116799  26759.9  26737.4 -0.000845
576  20230527   000000    000959  1685117399  26737.5  26765.6  0.001055
577  20230527   001000    001959  1685117999  26765.7  26758.5 -0.000265
2023-05-27 00:20:05,889:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [27/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-27 00:00:04,705:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42271F1685116803845I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685116804227345, 'quantity': '36.788', 'price': '26742', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1685116802828, 'updatetime': 1685116804227, 'tradetype': 'usdt', 'selfid': 42271, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685116804227, 'clientorderid': '42271F1685116803845I0L57', 'price': '26742', 'quantity': '36.788', 'commission': '983.784696', 'commissionasset': 'USDT', 'tradetime': 1685116804227, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685116804227}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [27/May/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1811 

self.closeSec=1685117399, self.tradeDate='20230527', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26737.5', self.close='26765.6'
2023-05-27 00:10:01,220:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685117399, self.tradeDate='20230527', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26737.5', self.close='26765.6'
2023-05-27 00:10:01,291:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230526   232000    232959  1685114999  26766.2  26799.8
17421  20230526   233000    233959  1685115599  26799.9    26761
17422  20230526   234000    234959  1685116199    26761    26760
17423  20230526   235000    235959  1685116799  26759.9  26737.4
17424  20230527   000000    000959  1685117399  26737.5  26765.6
2023-05-27 00:10:01,294:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1812 

self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26765.7', self.close='26758.5'
127.0.0.1 - - [27/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-27 00:20:06,754:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26765.7', self.close='26758.5'
2023-05-27 00:20:06,888:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230526   233000    233959  1685115599  26799.9    26761
17422  20230526   234000    234959  1685116199    26761    26760
17423  20230526   235000    235959  1685116799  26759.9  26737.4
17424  20230527   000000    000959  1685117399  26737.5  26765.6
17425  20230527   001000    001959  1685117999  26765.7  26758.5
2023-05-27 00:20:06,888:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [27/May/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-05-27 00:00:04,958:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42269F1685116803803I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1685116804267094, 'quantity': '47.501', 'price': '26742.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1685116802810, 'updatetime': 1685116804267, 'tradetype': 'usdt', 'selfid': 42269, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1685116804267, 'clientorderid': '42269F1685116803803I0L2', 'price': '26742.1', 'quantity': '47.501', 'commission': '1270.2764921', 'commissionasset': 'USDT', 'tradetime': 1685116804267, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1685116804267}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1811 

self.closeSec=1685117399, self.tradeDate='20230527', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26737.5', self.close='26765.6'
127.0.0.1 - - [27/May/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-05-27 00:10:01,212:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685117399, self.tradeDate='20230527', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26737.5', self.close='26765.6'
2023-05-27 00:10:01,261:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230526   232000    232959  1685114999  26766.2  26799.8
12237  20230526   233000    233959  1685115599  26799.9    26761
12238  20230526   234000    234959  1685116199    26761    26760
12239  20230526   235000    235959  1685116799  26759.9  26737.4
12240  20230527   000000    000959  1685117399  26737.5  26765.6
2023-05-27 00:10:01,261:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1812 

self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26765.7', self.close='26758.5'
127.0.0.1 - - [27/May/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-05-27 00:20:06,523:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26765.7', self.close='26758.5'
2023-05-27 00:20:06,743:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230526   233000    233959  1685115599  26799.9    26761
12238  20230526   234000    234959  1685116199    26761    26760
12239  20230526   235000    235959  1685116799  26759.9  26737.4
12240  20230527   000000    000959  1685117399  26737.5  26765.6
12241  20230527   001000    001959  1685117999  26765.7  26758.5
2023-05-27 00:20:06,744:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3616
self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26743.0, self.close=26758.5, self.high=26765.7, self.low=26743.0, self.vol=670.895, self.amt=17952548.4352 
127.0.0.1 - - [27/May/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-05-27 00:20:04,610:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230526   235500    235959  ...         0.0        0.0       0
5760  20230527   000000    000459  ...         0.0        0.0       0
5761  20230527   000500    000959  ...         0.0        0.0       0
5762  20230527   001000    001459  ...         0.0        0.0       0
5763  20230527   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 00:20:04,650:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685117999, self.tradeDate='20230527', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26743.0, self.close=26758.5, self.high=26765.7, self.low=26743.0, self.vol=670.895, self.amt=17952548.4352, ukdf['pct'].iloc[-1]=0.00058 , ukdf['amount'].iloc[-1]=17952548.4352, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-3135.68551079914', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26759.57347646', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=3617
self.closeSec=1685118299, self.tradeDate='20230527', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26757.6, self.close=26792.1, self.high=26820.0, self.low=26757.5, self.vol=2010.763, self.amt=53876122.738 
127.0.0.1 - - [27/May/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-05-27 00:25:00,814:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230527   000000    000459  ...         0.0        0.0       0
5761  20230527   000500    000959  ...         0.0        0.0       0
5762  20230527   001000    001459  ...         0.0        0.0       0
5763  20230527   001500    001959  ...         0.0        0.0       0
5764  20230527   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-27 00:25:00,815:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685118299, self.tradeDate='20230527', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26757.6, self.close=26792.1, self.high=26820.0, self.low=26757.5, self.vol=2010.763, self.amt=53876122.738, ukdf['pct'].iloc[-1]=0.001256 , ukdf['amount'].iloc[-1]=53876122.738, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-1890.58405884179', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26793.09711481', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230526   120000    155959  1685087999  ...    723  0.620975  1.427004     1.0
724  20230526   160000    195959  1685102399  ...    724  0.627112  1.432435     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '17884.1013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26451.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [27/May/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=75
self.closeSec=1685116799, self.tradeDate='20230526', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26451.8, self.close=26737.4, self.high=26925.0, self.low=26342.9, self.vol=137774.544, self.amt=3674535872.15686 
2023-05-27 00:00:01,814:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685116799, self.tradeDate='20230526', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26451.8, self.close=26737.4, self.high=26925.0, self.low=26342.9, self.vol=137774.544, self.amt=3674535872.15686 
2023-05-27 00:00:01,860:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230526   040000    075959  ...   28461.259  7.533183e+08  0.000147
722  20230526   080000    115959  ...   38579.969  1.019498e+09 -0.001364
723  20230526   120000    155959  ...   34980.918  9.238922e+08  0.002482
724  20230526   160000    195959  ...   32939.619  8.717101e+08 -0.001487
725  20230526   200000    235959  ...  137774.544  3.674536e+09  0.010793

[5 rows x 11 columns]
2023-05-27 00:00:04,049:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230526   040000    075959  1685059199  ...    721  0.598183  1.345687     1.0
722  20230526   080000    115959  1685073599  ...    722  0.610372  1.394063     1.0
723  20230526   120000    155959  1685087999  ...    723  0.620975  1.427004     1.0
724  20230526   160000    195959  1685102399  ...    724  0.627112  1.432435     1.0
725  20230526   200000    235959  1685116799  ...    725  0.605951  1.281364     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '33801.3382', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26740', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


