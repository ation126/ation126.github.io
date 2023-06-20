# 20230621 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10816
self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27091.0, self.close=27131.9, self.high=27199.0, self.low=27056.0, self.vol=11158.032, self.amt=302744509.32525 
127.0.0.1 - - [21/Jun/2023 00:20:02] "POST / HTTP/1.1" 200 -
2023-06-21 00:20:08,161:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230620   235500    235959  ...         0.0        0.0       0
5760  20230621   000000    000459  ...         0.0        0.0       0
5761  20230621   000500    000959  ...         0.0        0.0       0
5762  20230621   001000    001459  ...         0.0        0.0       0
5763  20230621   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 00:20:08,191:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27091.0, self.close=27131.9, self.high=27199.0, self.low=27056.0, self.vol=11158.032, self.amt=302744509.32525, ukdf['pct'].iloc[-1]=0.00151 , ukdf['amount'].iloc[-1]=302744509.32525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-3813.43245887472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27138.73544872', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10817
self.closeSec=1687278299, self.tradeDate='20230621', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27131.9, self.close=27248.5, self.high=27275.0, self.low=27110.0, self.vol=14195.442, self.amt=386082245.8504 
2023-06-21 00:25:00,765:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230621   000000    000459  ...         0.0        0.0       0
5761  20230621   000500    000959  ...         0.0        0.0       0
5762  20230621   001000    001459  ...         0.0        0.0       0
5763  20230621   001500    001959  ...         0.0        0.0       0
5764  20230621   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 00:25:00,767:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687278299, self.tradeDate='20230621', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27131.9, self.close=27248.5, self.high=27275.0, self.low=27110.0, self.vol=14195.442, self.amt=386082245.8504, ukdf['pct'].iloc[-1]=0.004298 , ukdf['amount'].iloc[-1]=386082245.8504, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-5286.3096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27244.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27091.0, self.close=27131.9, self.high=27199.0, self.low=27056.0 
127.0.0.1 - - [21/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-21 00:20:05,232:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27091.0, self.close=27131.9, self.high=27199.0, self.low=27056.0   
2023-06-21 00:20:06,902:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230620   235500    235959  1687276799  ...  27018.8  0.001218   1727    5
1440  20230621   000000    000459  1687277099  ...  26985.4 -0.001508   1440    0
1441  20230621   000500    000959  1687277399  ...  26983.3  0.000637   1441    1
1442  20230621   001000    001459  1687277699  ...  27030.5  0.002235   1442    2
1443  20230621   001500    001959  1687277999  ...  27056.0  0.001510   1443    3

[5 rows x 11 columns]
2023-06-21 00:20:06,921:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=181, self.factor=0.386082197768861, self.count=10819 

self.closeSec=1687278299, self.tradeDate='20230621', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27131.9, self.close=27248.5, self.high=27275.0, self.low=27110.0 
127.0.0.1 - - [21/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-21 00:25:00,702:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687278299, self.tradeDate='20230621', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27131.9, self.close=27248.5, self.high=27275.0, self.low=27110.0   
2023-06-21 00:25:00,729:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230621   000000    000459  1687277099  ...  26985.4 -0.001508   1440    0
1441  20230621   000500    000959  1687277399  ...  26983.3  0.000637   1441    1
1442  20230621   001000    001459  1687277699  ...  27030.5  0.002235   1442    2
1443  20230621   001500    001959  1687277999  ...  27056.0  0.001510   1443    3
1444  20230621   002000    002459  1687278299  ...  27110.0  0.004298   1444    4

[5 rows x 11 columns]
2023-06-21 00:25:00,729:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-21 00:00:25,773:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230620    212959  26839.7  ...  55.000000  0.558567  0.399499
5803  20230620    215959  26884.7  ...  55.000000  0.537292  0.403365
5804  20230620    222959  26795.4  ...  55.000000  0.504561  0.418392
5805  20230620    225959  26658.9  ...  55.416667  0.526411  0.423942
5806  20230620    232959  26763.8  ...  55.833333  0.529642  0.438860

[5 rows x 33 columns]
0.5514705882352942
acc is : 0.5514705882352942
2023-06-21 00:00:25,913:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.517726  0.482274       0  ...  1.021825  -1.0    0.0  1.011989
540     1  0.488215  0.511785       0  ...  1.027209  -1.0    0.0  1.006657
541     1  0.459212  0.540788       1  ...  1.023171  -1.0    0.0  1.010614
542     0  0.510568  0.489432       1  ...  1.022559  -1.0    0.0  1.011219
543     0  0.500347  0.499653       1  ...  1.012081  -1.0    0.0  1.021580

[5 rows x 10 columns]
2023-06-21 00:00:25,946:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517721  0.482279       0  ...  1.021825  -1.0    0.0  1.010055
46     1  0.488313  0.511687       0  ...  1.027209  -1.0    0.0  1.006680
47     1  0.459288  0.540712       1  ...  1.023171  -1.0    0.0  1.010637
48     0  0.510681  0.489319       1  ...  1.022559  -1.0    0.0  1.012121
49     0  0.500347  0.499653       1  ...  1.012081  -1.0    0.0  1.021580

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.089', 'enterprice': '26626.6', 'countrevence': '0', 'unrealprofit': '-12394.4979169944', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27067.8580696', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [21/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-21 00:00:04,382:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42424F1687276803638I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687276804020428, 'quantity': '27.067', 'price': '27054.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687276802660, 'updatetime': 1687276804020, 'tradetype': 'usdt', 'selfid': 42424, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687276804020, 'clientorderid': '42424F1687276803638I0L59', 'price': '27054.2', 'quantity': '27.067', 'commission': '732.2760314', 'commissionasset': 'USDT', 'tradetime': 1687276804020, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687276804020}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5408 

self.closeSec=1687277399, self.tradeDate='20230621', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27054.3', self.close='27030.6'
2023-06-21 00:10:01,088:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687277399, self.tradeDate='20230621', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27054.3', self.close='27030.6'
2023-06-21 00:10:01,096:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230620   232000    232959  1687274999  26744.9  26779.8  0.001305
573  20230620   233000    233959  1687275599  26779.8  26864.2  0.003152
574  20230620   234000    234959  1687276199  26864.2    26984  0.004459
575  20230620   235000    235959  1687276799    26982  27054.2  0.002602
576  20230621   000000    000959  1687277399  27054.3  27030.6 -0.000872
2023-06-21 00:10:01,096:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5409 

self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27030.6', self.close='27130.1'
127.0.0.1 - - [21/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 00:20:07,801:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27030.6', self.close='27130.1'
2023-06-21 00:20:08,711:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230620   233000    233959  1687275599  26779.8  26864.2  0.003152
574  20230620   234000    234959  1687276199  26864.2    26984  0.004459
575  20230620   235000    235959  1687276799    26982  27054.2  0.002602
576  20230621   000000    000959  1687277399  27054.3  27030.6 -0.000872
577  20230621   001000    001959  1687277999  27030.6  27130.1  0.003681
2023-06-21 00:20:08,712:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-21 00:00:02,115:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-21 00:00:02,274:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6210000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230620, closeTime:235959, close:27054.2, total:972975.8716388, pct_pre:0.01303090629707282, thd:-0.17974889377056863, side:sell 
127.0.0.1 - - [21/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5411 

self.closeSec=1687277399, self.tradeDate='20230621', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27054.3', self.close='27030.6'
2023-06-21 00:10:01,095:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687277399, self.tradeDate='20230621', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27054.3', self.close='27030.6'
2023-06-21 00:10:01,106:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230620   232000    232959  1687274999  26744.9  26779.8
17421  20230620   233000    233959  1687275599  26779.8  26864.2
17422  20230620   234000    234959  1687276199  26864.2    26984
17423  20230620   235000    235959  1687276799    26982  27054.2
17424  20230621   000000    000959  1687277399  27054.3  27030.6
2023-06-21 00:10:01,106:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5412 

self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27030.6', self.close='27130.1'
127.0.0.1 - - [21/Jun/2023 00:20:05] "POST / HTTP/1.1" 200 -
2023-06-21 00:20:10,110:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27030.6', self.close='27130.1'
2023-06-21 00:20:10,260:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230620   233000    233959  1687275599  26779.8  26864.2
17422  20230620   234000    234959  1687276199  26864.2    26984
17423  20230620   235000    235959  1687276799    26982  27054.2
17424  20230621   000000    000959  1687277399  27054.3  27030.6
17425  20230621   001000    001959  1687277999  27030.6  27130.1
2023-06-21 00:20:10,261:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [21/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-21 00:00:04,744:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42425F1687276803670I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687276804085247, 'quantity': '48.593', 'price': '27054.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687276802700, 'updatetime': 1687276804085, 'tradetype': 'usdt', 'selfid': 42425, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687276804085, 'clientorderid': '42425F1687276803670I0L2', 'price': '27054.2', 'quantity': '48.593', 'commission': '1314.6447406', 'commissionasset': 'USDT', 'tradetime': 1687276804085, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687276804085}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5411 

self.closeSec=1687277399, self.tradeDate='20230621', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='27054.3', self.close='27030.6'
127.0.0.1 - - [21/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-21 00:10:01,066:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687277399, self.tradeDate='20230621', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='27054.3', self.close='27030.6'
2023-06-21 00:10:01,072:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230620   232000    232959  1687274999  26744.9  26779.8
12237  20230620   233000    233959  1687275599  26779.8  26864.2
12238  20230620   234000    234959  1687276199  26864.2    26984
12239  20230620   235000    235959  1687276799    26982  27054.2
12240  20230621   000000    000959  1687277399  27054.3  27030.6
2023-06-21 00:10:01,073:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5412 

self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='27030.6', self.close='27130.1'
127.0.0.1 - - [21/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-21 00:20:09,617:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='27030.6', self.close='27130.1'
2023-06-21 00:20:09,991:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230620   233000    233959  1687275599  26779.8  26864.2
12238  20230620   234000    234959  1687276199  26864.2    26984
12239  20230620   235000    235959  1687276799    26982  27054.2
12240  20230621   000000    000959  1687277399  27054.3  27030.6
12241  20230621   001000    001959  1687277999  27030.6  27130.1
2023-06-21 00:20:09,993:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10816
self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=27091.0, self.close=27131.9, self.high=27199.0, self.low=27056.0, self.vol=11158.032, self.amt=302744509.32525 
127.0.0.1 - - [21/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-21 00:20:08,171:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230620   235500    235959  ...         0.0        0.0       0
5760  20230621   000000    000459  ...         0.0        0.0       0
5761  20230621   000500    000959  ...         0.0        0.0       0
5762  20230621   001000    001459  ...         0.0        0.0       0
5763  20230621   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 00:20:08,202:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687277999, self.tradeDate='20230621', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=27091.0, self.close=27131.9, self.high=27199.0, self.low=27056.0, self.vol=11158.032, self.amt=302744509.32525, ukdf['pct'].iloc[-1]=0.00151 , ukdf['amount'].iloc[-1]=302744509.32525, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '10946.76930090952', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27138.73544872', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10817
self.closeSec=1687278299, self.tradeDate='20230621', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=27131.9, self.close=27248.5, self.high=27275.0, self.low=27110.0, self.vol=14195.442, self.amt=386082245.8504 
127.0.0.1 - - [21/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-21 00:25:00,766:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230621   000000    000459  ...         0.0        0.0       0
5761  20230621   000500    000959  ...         0.0        0.0       0
5762  20230621   001000    001459  ...         0.0        0.0       0
5763  20230621   001500    001959  ...         0.0        0.0       0
5764  20230621   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-21 00:25:00,766:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687278299, self.tradeDate='20230621', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=27131.9, self.close=27248.5, self.high=27275.0, self.low=27110.0, self.vol=14195.442, self.amt=386082245.8504, ukdf['pct'].iloc[-1]=0.004298 , ukdf['amount'].iloc[-1]=386082245.8504, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '14874.9705', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27244.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230620   040000    075959  ...   57994.516  1.551427e+09  0.005841
722  20230620   080000    115959  ...   79486.167  2.142766e+09  0.001942
723  20230620   120000    155959  ...   58296.884  1.565392e+09 -0.002243
724  20230620   160000    195959  ...   41628.652  1.114877e+09  0.002789
725  20230620   200000    235959  ...  114387.910  3.072620e+09  0.005912

[5 rows x 11 columns]
2023-06-21 00:00:03,867:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230620   040000    075959  1687219199  ...    721  0.469583  0.213430     NaN
722  20230620   080000    115959  1687233599  ...    722  0.522307  0.501207     NaN
723  20230620   120000    155959  1687247999  ...    723  0.454998  0.083055     NaN
724  20230620   160000    195959  1687262399  ...    724  0.349276 -0.573679     NaN
725  20230620   200000    235959  1687276799  ...    725  0.227191 -1.342353    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '27078.92610595275', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27063.61479853', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '27078.92610595275', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27063.61479853', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-06-21 00:00:10,792:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1550154.980292', 'total': '1550154.980292', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-06-21 00:00:11,404:INFO:s_rsrs:main.py:269:openSell:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 57.126, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42427F1687276811395I0L65'}
2023-06-21 00:00:11,463:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:6210000, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230620, closeTime:235959, close:27054.2, sign:-1, total:1550154.980292, side:sell  
127.0.0.1 - - [21/Jun/2023 00:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [21/Jun/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-06-21 00:00:11,468:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42426F1687276805582I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687276805982341, 'quantity': '57.175', 'price': '27061.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687276804683, 'updatetime': 1687276805982, 'tradetype': 'usdt', 'selfid': 42426, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687276805982, 'clientorderid': '42426F1687276805582I0L65', 'price': '27061.9', 'quantity': '57.175', 'commission': '1547.2641325', 'commissionasset': 'USDT', 'tradetime': 1687276805982, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687276805982}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-21 00:00:11,471:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42426F1687276805582I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687276805982341, 'quantity': '57.175', 'price': '27061.9', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687276804683, 'updatetime': 1687276805982, 'tradetype': 'usdt', 'selfid': 42426, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687276805982, 'clientorderid': '42426F1687276805582I0L65', 'price': '27061.9', 'quantity': '57.175', 'commission': '1547.2641325', 'commissionasset': 'USDT', 'tradetime': 1687276805982, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687276805982}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jun/2023 00:00:11] "POST / HTTP/1.1" 200 -
2023-06-21 00:00:11,836:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42427F1687276811395I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687276811797028, 'quantity': '57.126', 'price': '27070.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687276810816, 'updatetime': 1687276811797, 'tradetype': 'usdt', 'selfid': 42427, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687276811797, 'clientorderid': '42427F1687276811395I0L65', 'price': '27070.2', 'quantity': '57.126', 'commission': '1546.4122452', 'commissionasset': 'USDT', 'tradetime': 1687276811797, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687276811797}], 'gatetype': 'simulator', 'handletime': 0}
2023-06-21 00:00:12,840:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42427F1687276811395I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687276811797028, 'quantity': '57.126', 'price': '27070.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687276810816, 'updatetime': 1687276811797, 'tradetype': 'usdt', 'selfid': 42427, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687276811797, 'clientorderid': '42427F1687276811395I0L65', 'price': '27070.2', 'quantity': '57.126', 'commission': '1546.4122452', 'commissionasset': 'USDT', 'tradetime': 1687276811797, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687276811797}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [21/Jun/2023 00:00:12] "POST / HTTP/1.1" 200 -


