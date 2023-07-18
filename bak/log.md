# 20230719 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18880
self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29944.8, self.close=29921.5, self.high=29954.3, self.low=29915.0, self.vol=1081.878, self.amt=32386991.2751 
127.0.0.1 - - [19/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 00:20:04,657:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230718   235500    235959  ...         0.0        0.0       0
5760  20230719   000000    000459  ...         0.0        0.0       0
5761  20230719   000500    000959  ...         0.0        0.0       0
5762  20230719   001000    001459  ...         0.0        0.0       0
5763  20230719   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 00:20:04,678:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29944.8, self.close=29921.5, self.high=29954.3, self.low=29915.0, self.vol=1081.878, self.amt=32386991.2751, ukdf['pct'].iloc[-1]=-0.000781 , ukdf['amount'].iloc[-1]=32386991.2751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42598.2414', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29923.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=18881
self.closeSec=1689697499, self.tradeDate='20230719', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29921.9, self.close=29896.0, self.high=29926.3, self.low=29894.0, self.vol=802.432, self.amt=23999661.048 
127.0.0.1 - - [19/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-19 00:25:00,777:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230719   000000    000459  ...         0.0        0.0       0
5761  20230719   000500    000959  ...         0.0        0.0       0
5762  20230719   001000    001459  ...         0.0        0.0       0
5763  20230719   001500    001959  ...         0.0        0.0       0
5764  20230719   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 00:25:00,786:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689697499, self.tradeDate='20230719', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29921.9, self.close=29896.0, self.high=29926.3, self.low=29894.0, self.vol=802.432, self.amt=23999661.048, ukdf['pct'].iloc[-1]=-0.000852 , ukdf['amount'].iloc[-1]=23999661.048, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-42173.396224938', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29893.292663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29944.8, self.close=29921.5, self.high=29954.3, self.low=29915.0 
127.0.0.1 - - [19/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-07-19 00:20:02,909:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29944.8, self.close=29921.5, self.high=29954.3, self.low=29915.0   
2023-07-19 00:20:03,927:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230718   235500    235959  1689695999  ...  29868.1  0.000596   1727    5
1440  20230719   000000    000459  1689696299  ...  29879.9  0.000649   1440    0
1441  20230719   000500    000959  1689696599  ...  29906.0  0.000388   1441    1
1442  20230719   001000    001459  1689696899  ...  29917.1  0.000628   1442    2
1443  20230719   001500    001959  1689697199  ...  29915.0 -0.000781   1443    3

[5 rows x 11 columns]
2023-07-19 00:20:03,927:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=68, self.factor=0.5651900672274617, self.count=18883 

self.closeSec=1689697499, self.tradeDate='20230719', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29921.9, self.close=29896.0, self.high=29926.3, self.low=29894.0 
127.0.0.1 - - [19/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-19 00:25:00,722:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689697499, self.tradeDate='20230719', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29921.9, self.close=29896.0, self.high=29926.3, self.low=29894.0   
2023-07-19 00:25:00,773:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230719   000000    000459  1689696299  ...  29879.9  0.000649   1440    0
1441  20230719   000500    000959  1689696599  ...  29906.0  0.000388   1441    1
1442  20230719   001000    001459  1689696899  ...  29917.1  0.000628   1442    2
1443  20230719   001500    001959  1689697199  ...  29915.0 -0.000781   1443    3
1444  20230719   002000    002459  1689697499  ...  29894.0 -0.000852   1444    4

[5 rows x 11 columns]
2023-07-19 00:25:00,773:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-19 00:00:17,535:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230718    212959  29776.0  ...  48.333333  0.412037  0.488427
5803  20230718    215959  29767.4  ...  48.333333  0.425591  0.503447
5804  20230718    222959  29817.5  ...  48.750000  0.453113  0.506807
5805  20230718    225959  29921.3  ...  48.333333  0.450748  0.512734
5806  20230718    232959  29910.0  ...  47.916667  0.437480  0.525063

[5 rows x 33 columns]
0.5165441176470589
acc is : 0.5165441176470589
2023-07-19 00:00:17,595:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.483817  0.516183       1  ...  0.954820   1.0    0.0  0.994129
540     1  0.498763  0.501237       1  ...  0.958163   1.0    0.0  0.997609
541     0  0.536681  0.463319       0  ...  0.957805   1.0    0.0  0.997236
542     0  0.512216  0.487784       0  ...  0.955762   1.0    0.0  0.995109
543     1  0.499453  0.500547       1  ...  0.957324   1.0    0.0  0.996736

[5 rows x 10 columns]
2023-07-19 00:00:17,606:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.483196  0.516804       1  ...  0.942305   1.0    0.0  0.989717
46     1  0.498118  0.501882       1  ...  0.945604   1.0    0.0  0.993862
47     0  0.536411  0.463589       0  ...  0.945250   1.0    0.0  0.993490
48     0  0.511885  0.488115       0  ...  0.955762   1.0    0.0  0.992455
49     1  0.499453  0.500547       1  ...  0.957324   1.0    0.0  0.996736

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.036', 'enterprice': '30219.4', 'countrevence': '0', 'unrealprofit': '-7669.8876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29900.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-19 00:00:04,344:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42682F1689696003606I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689696004044810, 'quantity': '24.645', 'price': '29895.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689696002657, 'updatetime': 1689696004044, 'tradetype': 'usdt', 'selfid': 42682, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689696004044, 'clientorderid': '42682F1689696003606I0L59', 'price': '29895.1', 'quantity': '24.645', 'commission': '736.7647395', 'commissionasset': 'USDT', 'tradetime': 1689696004044, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689696004044}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9440 

self.closeSec=1689696599, self.tradeDate='20230719', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29895.1', self.close='29926.2'
127.0.0.1 - - [19/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-07-19 00:10:01,080:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689696599, self.tradeDate='20230719', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29895.1', self.close='29926.2'
2023-07-19 00:10:01,091:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230718   232000    232959  1689694199    29885  29846.2 -0.001295
573  20230718   233000    233959  1689694799  29846.3  29867.8  0.000724
574  20230718   234000    234959  1689695399  29867.9  29873.2  0.000181
575  20230718   235000    235959  1689695999  29873.1  29895.1  0.000733
576  20230719   000000    000959  1689696599  29895.1  29926.2  0.001040
2023-07-19 00:10:01,094:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9441 

self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29926.2', self.close='29921.9'
127.0.0.1 - - [19/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 00:20:05,700:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29926.2', self.close='29921.9'
2023-07-19 00:20:06,064:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230718   233000    233959  1689694799  29846.3  29867.8  0.000724
574  20230718   234000    234959  1689695399  29867.9  29873.2  0.000181
575  20230718   235000    235959  1689695999  29873.1  29895.1  0.000733
576  20230719   000000    000959  1689696599  29895.1  29926.2  0.001040
577  20230719   001000    001959  1689697199  29926.2  29921.9 -0.000144
2023-07-19 00:20:06,065:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-07-19 00:00:02,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-07-19 00:00:02,212:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:7190000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230718, closeTime:235959, close:29895.1, total:1011809.3588385, pct_pre:-0.008512709465298585, thd:0.3649372569403312, side:sell 
127.0.0.1 - - [19/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9443 

self.closeSec=1689696599, self.tradeDate='20230719', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29895.1', self.close='29926.2'
2023-07-19 00:10:01,082:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689696599, self.tradeDate='20230719', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29895.1', self.close='29926.2'
2023-07-19 00:10:01,095:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230718   232000    232959  1689694199    29885  29846.2
17421  20230718   233000    233959  1689694799  29846.3  29867.8
17422  20230718   234000    234959  1689695399  29867.9  29873.2
17423  20230718   235000    235959  1689695999  29873.1  29895.1
17424  20230719   000000    000959  1689696599  29895.1  29926.2
2023-07-19 00:10:01,095:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9444 

self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29926.2', self.close='29921.9'
127.0.0.1 - - [19/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 00:20:06,605:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29926.2', self.close='29921.9'
2023-07-19 00:20:06,777:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230718   233000    233959  1689694799  29846.3  29867.8
17422  20230718   234000    234959  1689695399  29867.9  29873.2
17423  20230718   235000    235959  1689695999  29873.1  29895.1
17424  20230719   000000    000959  1689696599  29895.1  29926.2
17425  20230719   001000    001959  1689697199  29926.2  29921.9
2023-07-19 00:20:06,777:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/Jul/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-07-19 00:00:04,211:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42683F1689696003634I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689696004035983, 'quantity': '37.402', 'price': '29895.1', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1689696002690, 'updatetime': 1689696004035, 'tradetype': 'usdt', 'selfid': 42683, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689696004035, 'clientorderid': '42683F1689696003634I0L2', 'price': '29895.1', 'quantity': '37.402', 'commission': '1118.1365302', 'commissionasset': 'USDT', 'tradetime': 1689696004035, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689696004035}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jul/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9443 

self.closeSec=1689696599, self.tradeDate='20230719', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='29895.1', self.close='29926.2'
2023-07-19 00:10:01,082:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689696599, self.tradeDate='20230719', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='29895.1', self.close='29926.2'
2023-07-19 00:10:01,097:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230718   232000    232959  1689694199    29885  29846.2
12237  20230718   233000    233959  1689694799  29846.3  29867.8
12238  20230718   234000    234959  1689695399  29867.9  29873.2
12239  20230718   235000    235959  1689695999  29873.1  29895.1
12240  20230719   000000    000959  1689696599  29895.1  29926.2
2023-07-19 00:10:01,098:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9444 

self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='29926.2', self.close='29921.9'
127.0.0.1 - - [19/Jul/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-07-19 00:20:06,484:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='29926.2', self.close='29921.9'
2023-07-19 00:20:06,682:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230718   233000    233959  1689694799  29846.3  29867.8
12238  20230718   234000    234959  1689695399  29867.9  29873.2
12239  20230718   235000    235959  1689695999  29873.1  29895.1
12240  20230719   000000    000959  1689696599  29895.1  29926.2
12241  20230719   001000    001959  1689697199  29926.2  29921.9
2023-07-19 00:20:06,683:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18880
127.0.0.1 - - [19/Jul/2023 00:20:01] "POST / HTTP/1.1" 200 -
self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=29944.8, self.close=29921.5, self.high=29954.3, self.low=29915.0, self.vol=1081.878, self.amt=32386991.2751 
2023-07-19 00:20:04,658:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230718   235500    235959  ...         0.0        0.0       0
5760  20230719   000000    000459  ...         0.0        0.0       0
5761  20230719   000500    000959  ...         0.0        0.0       0
5762  20230719   001000    001459  ...         0.0        0.0       0
5763  20230719   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 00:20:04,678:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689697199, self.tradeDate='20230719', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=29944.8, self.close=29921.5, self.high=29954.3, self.low=29915.0, self.vol=1081.878, self.amt=32386991.2751, ukdf['pct'].iloc[-1]=-0.000781 , ukdf['amount'].iloc[-1]=32386991.2751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '114386.8518', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29923.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=18881
self.closeSec=1689697499, self.tradeDate='20230719', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=29921.9, self.close=29896.0, self.high=29926.3, self.low=29894.0, self.vol=802.432, self.amt=23999661.048 
127.0.0.1 - - [19/Jul/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-07-19 00:25:00,787:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230719   000000    000459  ...         0.0        0.0       0
5761  20230719   000500    000959  ...         0.0        0.0       0
5762  20230719   001000    001459  ...         0.0        0.0       0
5763  20230719   001500    001959  ...         0.0        0.0       0
5764  20230719   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-19 00:25:00,788:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689697499, self.tradeDate='20230719', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=29921.9, self.close=29896.0, self.high=29926.3, self.low=29894.0, self.vol=802.432, self.amt=23999661.048, ukdf['pct'].iloc[-1]=-0.000852 , ukdf['amount'].iloc[-1]=23999661.048, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '113253.778796483', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29893.292663', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-07-18 20:00:10,601:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42680F1689681605044I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689681605441703, 'quantity': '52.241', 'price': '29864', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689681604209, 'updatetime': 1689681605441, 'tradetype': 'usdt', 'selfid': 42680, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689681605441, 'clientorderid': '42680F1689681605044I0L65', 'price': '29864', 'quantity': '52.241', 'commission': '1560.125224', 'commissionasset': 'USDT', 'tradetime': 1689681605441, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689681605441}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-18 20:00:10,601:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42680F1689681605044I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689681605441703, 'quantity': '52.241', 'price': '29864', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689681604209, 'updatetime': 1689681605441, 'tradetype': 'usdt', 'selfid': 42680, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689681605441, 'clientorderid': '42680F1689681605044I0L65', 'price': '29864', 'quantity': '52.241', 'commission': '1560.125224', 'commissionasset': 'USDT', 'tradetime': 1689681605441, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689681605441}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jul/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-07-18 20:00:11,027:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42681F1689681610576I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689681610968283, 'quantity': '52.176', 'price': '29870.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689681610125, 'updatetime': 1689681610968, 'tradetype': 'usdt', 'selfid': 42681, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689681610968, 'clientorderid': '42681F1689681610576I0L65', 'price': '29870.6', 'quantity': '52.176', 'commission': '1558.5284256', 'commissionasset': 'USDT', 'tradetime': 1689681610968, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689681610968}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [18/Jul/2023 20:00:11] "POST / HTTP/1.1" 200 -
2023-07-18 20:00:11,367:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42681F1689681610576I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1689681610968283, 'quantity': '52.176', 'price': '29870.6', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1689681610125, 'updatetime': 1689681610968, 'tradetype': 'usdt', 'selfid': 42681, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1689681610968, 'clientorderid': '42681F1689681610576I0L65', 'price': '29870.6', 'quantity': '52.176', 'commission': '1558.5284256', 'commissionasset': 'USDT', 'tradetime': 1689681610968, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1689681610968}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jul/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=393
self.closeSec=1689695999, self.tradeDate='20230718', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=29872.0, self.close=29895.1, self.high=30028.6, self.low=29657.1, self.vol=98912.984, self.amt=2951514562.70584 
2023-07-19 00:00:01,748:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689695999, self.tradeDate='20230718', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=29872.0, self.close=29895.1, self.high=30028.6, self.low=29657.1, self.vol=98912.984, self.amt=2951514562.70584 
2023-07-19 00:00:01,764:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230718   040000    075959  ...  51790.057  1.558369e+09  0.008574
722  20230718   080000    115959  ...  23756.585  7.160705e+08 -0.002068
723  20230718   120000    155959  ...  38504.713  1.155475e+09 -0.003722
724  20230718   160000    195959  ...  60543.472  1.813636e+09 -0.002668
725  20230718   200000    235959  ...  98912.984  2.951515e+09  0.000773

[5 rows x 11 columns]
2023-07-19 00:00:02,557:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230718   040000    075959  1689638399  ...    721  0.608408  0.713520     1.0
722  20230718   080000    115959  1689652799  ...    722  0.497627  0.265788     NaN
723  20230718   120000    155959  1689667199  ...    723  0.375309 -0.236925     NaN
724  20230718   160000    195959  1689681599  ...    724  0.239216 -0.804205    -1.0
725  20230718   200000    235959  1689695999  ...    725  0.126414 -1.279727    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '-1576.41766479312', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29900.81346337', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


