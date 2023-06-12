# 20230613 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8512
self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25831.1, self.close=25852.1, self.high=25861.2, self.low=25820.0, self.vol=915.062, self.amt=23645464.8119 
127.0.0.1 - - [13/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 00:20:01,643:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230612   235500    235959  ...         0.0        0.0       0
5760  20230613   000000    000459  ...         0.0        0.0       0
5761  20230613   000500    000959  ...         0.0        0.0       0
5762  20230613   001000    001459  ...         0.0        0.0       0
5763  20230613   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 00:20:01,659:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25831.1, self.close=25852.1, self.high=25861.2, self.low=25820.0, self.vol=915.062, self.amt=23645464.8119, ukdf['pct'].iloc[-1]=0.000817 , ukdf['amount'].iloc[-1]=23645464.8119, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14090.3268', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25853.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8513
self.closeSec=1686587099, self.tradeDate='20230613', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25852.1, self.close=25842.0, self.high=25854.1, self.low=25834.0, self.vol=730.416, self.amt=18877945.5903 
127.0.0.1 - - [13/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-13 00:25:03,872:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230613   000000    000459  ...         0.0        0.0       0
5761  20230613   000500    000959  ...         0.0        0.0       0
5762  20230613   001000    001459  ...         0.0        0.0       0
5763  20230613   001500    001959  ...         0.0        0.0       0
5764  20230613   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 00:25:03,882:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686587099, self.tradeDate='20230613', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25852.1, self.close=25842.0, self.high=25854.1, self.low=25834.0, self.vol=730.416, self.amt=18877945.5903, ukdf['pct'].iloc[-1]=-0.000391 , ukdf['amount'].iloc[-1]=18877945.5903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '14211.483', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25844.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25831.1, self.close=25852.1, self.high=25861.2, self.low=25820.0 
127.0.0.1 - - [13/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 00:20:01,260:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25831.1, self.close=25852.1, self.high=25861.2, self.low=25820.0   
2023-06-13 00:20:01,539:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230612   235500    235959  1686585599  ...  25807.0 -0.000128   1727    5
1440  20230613   000000    000459  1686585899  ...  25774.4 -0.000666   1440    0
1441  20230613   000500    000959  1686586199  ...  25790.2  0.001590   1441    1
1442  20230613   001000    001459  1686586499  ...  25818.9 -0.000081   1442    2
1443  20230613   001500    001959  1686586799  ...  25820.0  0.000817   1443    3

[5 rows x 11 columns]
2023-06-13 00:20:01,539:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=10, self.factor=0.47937033095065407, self.count=8515 

self.closeSec=1686587099, self.tradeDate='20230613', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25852.1, self.close=25842.0, self.high=25854.1, self.low=25834.0 
127.0.0.1 - - [13/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-13 00:25:02,803:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686587099, self.tradeDate='20230613', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25852.1, self.close=25842.0, self.high=25854.1, self.low=25834.0   
2023-06-13 00:25:03,526:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230613   000000    000459  1686585899  ...  25774.4 -0.000666   1440    0
1441  20230613   000500    000959  1686586199  ...  25790.2  0.001590   1441    1
1442  20230613   001000    001459  1686586499  ...  25818.9 -0.000081   1442    2
1443  20230613   001500    001959  1686586799  ...  25820.0  0.000817   1443    3
1444  20230613   002000    002459  1686587099  ...  25834.0 -0.000391   1444    4

[5 rows x 11 columns]
2023-06-13 00:25:03,531:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-13 00:00:43,942:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230612    212959  25920.1  ...  49.166667  0.492140  0.492317
5803  20230612    215959  25868.1  ...  48.750000  0.476080  0.504960
5804  20230612    222959  25790.5  ...  49.166667  0.482747  0.513422
5805  20230612    225959  25820.5  ...  49.583333  0.485199  0.520095
5806  20230612    232959  25837.4  ...  49.166667  0.477247  0.530542

[5 rows x 33 columns]
0.5330882352941176
acc is : 0.5330882352941176
2023-06-13 00:00:44,155:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.485680  0.514320       0  ...  0.986369  -1.0    0.0  0.962688
540     1  0.474291  0.525709       1  ...  0.985221  -1.0    0.0  0.963808
541     1  0.492554  0.507446       1  ...  0.984801  -1.0    0.0  0.964218
542     1  0.497388  0.502612       0  ...  0.986246  -1.0    0.0  0.962803
543     1  0.483488  0.516512       1  ...  0.985646  -1.0    0.0  0.963389

[5 rows x 10 columns]
2023-06-13 00:00:44,195:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485753  0.514247       0  ...  0.986369  -1.0    0.0  0.962282
46     1  0.474351  0.525649       1  ...  0.985221  -1.0    0.0  0.964257
47     1  0.492541  0.507459       1  ...  0.984801  -1.0    0.0  0.964668
48     1  0.497332  0.502668       0  ...  0.986246  -1.0    0.0  0.960895
49     1  0.483488  0.516512       1  ...  0.985646  -1.0    0.0  0.963389

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-7284.1678', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25816.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [13/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-13 00:00:04,862:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42379F1686585604042I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686585604453780, 'quantity': '28.073', 'price': '25809.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686585603055, 'updatetime': 1686585604453, 'tradetype': 'usdt', 'selfid': 42379, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686585604453, 'clientorderid': '42379F1686585604042I0L59', 'price': '25809.4', 'quantity': '28.073', 'commission': '724.5472862', 'commissionasset': 'USDT', 'tradetime': 1686585604453, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686585604453}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4256 

self.closeSec=1686586199, self.tradeDate='20230613', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25809.3', self.close='25833.1'
2023-06-13 00:10:01,120:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686586199, self.tradeDate='20230613', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25809.3', self.close='25833.1'
2023-06-13 00:10:01,194:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230612   232000    232959  1686583799  25785.5  25793.6  0.000314
573  20230612   233000    233959  1686584399  25793.7  25817.7  0.000934
574  20230612   234000    234959  1686584999  25817.7  25831.1  0.000519
575  20230612   235000    235959  1686585599  25831.2  25809.3 -0.000844
576  20230613   000000    000959  1686586199  25809.3  25833.1  0.000922
2023-06-13 00:10:01,194:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4257 

self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25833.1', self.close='25852.1'
127.0.0.1 - - [13/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-13 00:20:03,710:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25833.1', self.close='25852.1'
2023-06-13 00:20:04,108:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230612   233000    233959  1686584399  25793.7  25817.7  0.000934
574  20230612   234000    234959  1686584999  25817.7  25831.1  0.000519
575  20230612   235000    235959  1686585599  25831.2  25809.3 -0.000844
576  20230613   000000    000959  1686586199  25809.3  25833.1  0.000922
577  20230613   001000    001959  1686586799  25833.1  25852.1  0.000735
2023-06-13 00:20:04,108:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [13/Jun/2023 00:00:05] "POST / HTTP/1.1" 200 -
2023-06-13 00:00:05,092:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42378F1686585604008I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686585604439947, 'quantity': '38.022', 'price': '25809.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686585603035, 'updatetime': 1686585604439, 'tradetype': 'usdt', 'selfid': 42378, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686585604439, 'clientorderid': '42378F1686585604008I0L57', 'price': '25809.3', 'quantity': '38.022', 'commission': '981.3212046', 'commissionasset': 'USDT', 'tradetime': 1686585604439, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686585604439}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4259 

self.closeSec=1686586199, self.tradeDate='20230613', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25809.3', self.close='25833.1'
2023-06-13 00:10:01,143:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686586199, self.tradeDate='20230613', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25809.3', self.close='25833.1'
2023-06-13 00:10:01,175:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230612   232000    232959  1686583799  25785.5  25793.6
17421  20230612   233000    233959  1686584399  25793.7  25817.7
17422  20230612   234000    234959  1686584999  25817.7  25831.1
17423  20230612   235000    235959  1686585599  25831.2  25809.3
17424  20230613   000000    000959  1686586199  25809.3  25833.1
2023-06-13 00:10:01,187:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4260 

self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25833.1', self.close='25852.1'
127.0.0.1 - - [13/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-13 00:20:04,511:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25833.1', self.close='25852.1'
2023-06-13 00:20:04,635:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230612   233000    233959  1686584399  25793.7  25817.7
17422  20230612   234000    234959  1686584999  25817.7  25831.1
17423  20230612   235000    235959  1686585599  25831.2  25809.3
17424  20230613   000000    000959  1686586199  25809.3  25833.1
17425  20230613   001000    001959  1686586799  25833.1  25852.1
2023-06-13 00:20:04,635:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [13/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-13 00:00:04,652:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42377F1686585603981I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686585604384242, 'quantity': '49.741', 'price': '25809.4', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686585603091, 'updatetime': 1686585604384, 'tradetype': 'usdt', 'selfid': 42377, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686585604384, 'clientorderid': '42377F1686585603981I0L2', 'price': '25809.4', 'quantity': '49.741', 'commission': '1283.7853654', 'commissionasset': 'USDT', 'tradetime': 1686585604384, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686585604384}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [13/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4259 

self.closeSec=1686586199, self.tradeDate='20230613', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25809.3', self.close='25833.1'
2023-06-13 00:10:01,149:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686586199, self.tradeDate='20230613', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25809.3', self.close='25833.1'
2023-06-13 00:10:01,200:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230612   232000    232959  1686583799  25785.5  25793.6
12237  20230612   233000    233959  1686584399  25793.7  25817.7
12238  20230612   234000    234959  1686584999  25817.7  25831.1
12239  20230612   235000    235959  1686585599  25831.2  25809.3
12240  20230613   000000    000959  1686586199  25809.3  25833.1
2023-06-13 00:10:01,200:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4260 

self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25833.1', self.close='25852.1'
127.0.0.1 - - [13/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-13 00:20:04,290:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25833.1', self.close='25852.1'
2023-06-13 00:20:04,520:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230612   233000    233959  1686584399  25793.7  25817.7
12238  20230612   234000    234959  1686584999  25817.7  25831.1
12239  20230612   235000    235959  1686585599  25831.2  25809.3
12240  20230613   000000    000959  1686586199  25809.3  25833.1
12241  20230613   001000    001959  1686586799  25833.1  25852.1
2023-06-13 00:20:04,520:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8512
self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25831.1, self.close=25852.1, self.high=25861.2, self.low=25820.0, self.vol=915.062, self.amt=23645464.8119 
127.0.0.1 - - [13/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 00:20:01,643:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230612   235500    235959  ...         0.0        0.0       0
5760  20230613   000000    000459  ...         0.0        0.0       0
5761  20230613   000500    000959  ...         0.0        0.0       0
5762  20230613   001000    001459  ...         0.0        0.0       0
5763  20230613   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 00:20:01,660:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686586799, self.tradeDate='20230613', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25831.1, self.close=25852.1, self.high=25861.2, self.low=25820.0, self.vol=915.062, self.amt=23645464.8119, ukdf['pct'].iloc[-1]=0.000817 , ukdf['amount'].iloc[-1]=23645464.8119, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-36803.0169', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25853.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8513
self.closeSec=1686587099, self.tradeDate='20230613', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25852.1, self.close=25842.0, self.high=25854.1, self.low=25834.0, self.vol=730.416, self.amt=18877945.5903 
127.0.0.1 - - [13/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-13 00:25:03,804:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230613   000000    000459  ...         0.0        0.0       0
5761  20230613   000500    000959  ...         0.0        0.0       0
5762  20230613   001000    001459  ...         0.0        0.0       0
5763  20230613   001500    001959  ...         0.0        0.0       0
5764  20230613   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 00:25:03,824:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686587099, self.tradeDate='20230613', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25852.1, self.close=25842.0, self.high=25854.1, self.low=25834.0, self.vol=730.416, self.amt=18877945.5903, ukdf['pct'].iloc[-1]=-0.000391 , ukdf['amount'].iloc[-1]=18877945.5903, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-37126.1436', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25844.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230612   120000    155959  1686556799  ...    723  0.472319 -0.417763     NaN
724  20230612   160000    195959  1686571199  ...    724  0.470036 -0.426078     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '60428.8364', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25983.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--: 127.0.0.1 - - [13/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=177
self.closeSec=1686585599, self.tradeDate='20230612', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25975.7, self.close=25809.3, self.high=25983.2, self.low=25722.0, self.vol=55282.739, self.amt=1428065670.03068 
2023-06-13 00:00:02,011:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686585599, self.tradeDate='20230612', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25975.7, self.close=25809.3, self.high=25983.2, self.low=25722.0, self.vol=55282.739, self.amt=1428065670.03068 
2023-06-13 00:00:02,071:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230612   040000    075959  ...  74781.740  1.942771e+09 -0.004270
722  20230612   080000    115959  ...  67095.778  1.732531e+09 -0.005029
723  20230612   120000    155959  ...  30360.911  7.834327e+08  0.000528
724  20230612   160000    195959  ...  60565.670  1.572473e+09  0.007076
725  20230612   200000    235959  ...  55282.739  1.428066e+09 -0.006406

[5 rows x 11 columns]
2023-06-13 00:00:05,224:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230612   040000    075959  1686527999  ...    721  0.464084 -0.433618     NaN
722  20230612   080000    115959  1686542399  ...    722  0.459192 -0.456180     NaN
723  20230612   120000    155959  1686556799  ...    723  0.472319 -0.417763     NaN
724  20230612   160000    195959  1686571199  ...    724  0.470036 -0.426078     NaN
725  20230612   200000    235959  1686585599  ...    725  0.487058 -0.369591     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '69844.0091327109', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25812.53015385', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


