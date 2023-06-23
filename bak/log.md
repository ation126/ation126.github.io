# 20230624 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11680
self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=31372.0, self.close=31208.6, self.high=31385.7, self.low=31100.0, self.vol=10322.831, self.amt=322379647.77716 
127.0.0.1 - - [24/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 00:20:07,601:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230623   235500    235959  ...         0.0        0.0       0
5760  20230624   000000    000459  ...         0.0        0.0       0
5761  20230624   000500    000959  ...         0.0        0.0       0
5762  20230624   001000    001459  ...         0.0        0.0       0
5763  20230624   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 00:20:07,632:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=31372.0, self.close=31208.6, self.high=31385.7, self.low=31100.0, self.vol=10322.831, self.amt=322379647.77716, ukdf['pct'].iloc[-1]=-0.004913 , ukdf['amount'].iloc[-1]=322379647.77716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-59937.504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31168.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=11681
self.closeSec=1687537499, self.tradeDate='20230624', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31208.5, self.close=30886.6, self.high=31212.8, self.low=30655.1, self.vol=22939.9, self.amt=708814925.2472 
127.0.0.1 - - [24/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-24 00:25:00,798:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230624   000000    000459  ...         0.0        0.0       0
5761  20230624   000500    000959  ...         0.0        0.0       0
5762  20230624   001000    001459  ...         0.0        0.0       0
5763  20230624   001500    001959  ...         0.0        0.0       0
5764  20230624   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 00:25:00,799:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687537499, self.tradeDate='20230624', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31208.5, self.close=30886.6, self.high=31212.8, self.low=30655.1, self.vol=22939.9, self.amt=708814925.2472, ukdf['pct'].iloc[-1]=-0.010318 , ukdf['amount'].iloc[-1]=708814925.2472, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-56024.57567831256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30887.91993956', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=31372.0, self.close=31208.6, self.high=31385.7, self.low=31100.0 
127.0.0.1 - - [24/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 00:20:05,021:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=31372.0, self.close=31208.6, self.high=31385.7, self.low=31100.0   
2023-06-24 00:20:06,541:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230623   235500    235959  1687535999  ...  31151.5  0.000641   1727    5
1440  20230624   000000    000459  1687536299  ...  31042.7 -0.001690   1440    0
1441  20230624   000500    000959  1687536599  ...  31160.0  0.003970   1441    1
1442  20230624   001000    001459  1687536899  ...  31222.0  0.001712   1442    2
1443  20230624   001500    001959  1687537199  ...  31100.0 -0.004913   1443    3

[5 rows x 11 columns]
2023-06-24 00:20:06,551:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=325, self.factor=0.39492220110878656, self.count=11683 

self.closeSec=1687537499, self.tradeDate='20230624', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31208.5, self.close=30886.6, self.high=31212.8, self.low=30655.1 
127.0.0.1 - - [24/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-24 00:25:00,748:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687537499, self.tradeDate='20230624', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31208.5, self.close=30886.6, self.high=31212.8, self.low=30655.1   
2023-06-24 00:25:00,771:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230624   000000    000459  1687536299  ...  31042.7 -0.001690   1440    0
1441  20230624   000500    000959  1687536599  ...  31160.0  0.003970   1441    1
1442  20230624   001000    001459  1687536899  ...  31222.0  0.001712   1442    2
1443  20230624   001500    001959  1687537199  ...  31100.0 -0.004913   1443    3
1444  20230624   002000    002459  1687537499  ...  30655.1 -0.010318   1444    4

[5 rows x 11 columns]
2023-06-24 00:25:00,773:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-24 00:00:20,646:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230623    212959  30090.2  ...  55.416667  0.551157  0.388350
5803  20230623    215959  30095.9  ...  55.416667  0.546343  0.390480
5804  20230623    222959  30063.3  ...  55.416667  0.555375  0.381883
5805  20230623    225959  30137.6  ...  55.416667  0.571259  0.365602
5806  20230623    232959  30275.0  ...  55.833333  0.609958  0.360600

[5 rows x 33 columns]
0.5680147058823529
acc is : 0.5680147058823529
2023-06-24 00:00:20,751:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.494616  0.505384       0  ...  1.136140   1.0    0.0  1.165551
540     1  0.487246  0.512754       1  ...  1.138948   1.0    0.0  1.168432
541     0  0.502113  0.497887       1  ...  1.144069   1.0    0.0  1.173685
542     0  0.522086  0.477914       1  ...  1.158006   1.0    0.0  1.187984
543     0  0.581204  0.418796       1  ...  1.180538   1.0    0.0  1.211098

[5 rows x 10 columns]
2023-06-24 00:00:20,767:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.494700  0.505300       0  ...  1.136140   1.0    0.0  1.162765
46     1  0.487368  0.512632       1  ...  1.138948   1.0    0.0  1.166672
47     0  0.502246  0.497754       1  ...  1.144069   1.0    0.0  1.171918
48     0  0.522106  0.477894       1  ...  1.158006   1.0    0.0  1.187174
49     0  0.581204  0.418796       1  ...  1.180538   1.0    0.0  1.211098

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.727', 'enterprice': '30025.4', 'countrevence': '0', 'unrealprofit': '31088.41710370971', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31188.58393773', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [24/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-24 00:00:04,496:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42451F1687536003751I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687536004191867, 'quantity': '25.658', 'price': '31232.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687536002814, 'updatetime': 1687536004191, 'tradetype': 'usdt', 'selfid': 42451, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687536004191, 'clientorderid': '42451F1687536003751I0L59', 'price': '31232.4', 'quantity': '25.658', 'commission': '801.3609192', 'commissionasset': 'USDT', 'tradetime': 1687536004191, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687536004191}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [24/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5840 

self.closeSec=1687536599, self.tradeDate='20230624', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31232.9', self.close='31309.1'
2023-06-24 00:10:01,107:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687536599, self.tradeDate='20230624', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31232.9', self.close='31309.1'
2023-06-24 00:10:01,144:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230623   232000    232959  1687534199  30694.9  30641.9 -0.001723
573  20230623   233000    233959  1687534799  30645.2  30759.9  0.003851
574  20230623   234000    234959  1687535399  30760.7  30908.2  0.004821
575  20230623   235000    235959  1687535999  30908.3  31238.1  0.010674
576  20230624   000000    000959  1687536599  31232.9  31309.1  0.002273
2023-06-24 00:10:01,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5841 

self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='31318.2', self.close='31208.6'
127.0.0.1 - - [24/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 00:20:07,440:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='31318.2', self.close='31208.6'
2023-06-24 00:20:08,310:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230623   233000    233959  1687534799  30645.2  30759.9  0.003851
574  20230623   234000    234959  1687535399  30760.7  30908.2  0.004821
575  20230623   235000    235959  1687535999  30908.3  31238.1  0.010674
576  20230624   000000    000959  1687536599  31232.9  31309.1  0.002273
577  20230624   001000    001959  1687537199  31318.2  31208.6 -0.003210
2023-06-24 00:20:08,311:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [24/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-24 00:00:04,098:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42449F1687536003502I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687536003883356, 'quantity': '31.911', 'price': '31232.4', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687536002584, 'updatetime': 1687536003883, 'tradetype': 'usdt', 'selfid': 42449, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687536003883, 'clientorderid': '42449F1687536003502I0L57', 'price': '31232.4', 'quantity': '31.911', 'commission': '996.6571164', 'commissionasset': 'USDT', 'tradetime': 1687536003883, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687536003883}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5843 

self.closeSec=1687536599, self.tradeDate='20230624', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31232.9', self.close='31309.1'
2023-06-24 00:10:01,120:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687536599, self.tradeDate='20230624', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31232.9', self.close='31309.1'
127.0.0.1 - - [24/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-24 00:10:01,136:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230623   232000    232959  1687534199  30694.9  30641.9
17421  20230623   233000    233959  1687534799  30645.2  30759.9
17422  20230623   234000    234959  1687535399  30760.7  30908.2
17423  20230623   235000    235959  1687535999  30908.3  31238.1
17424  20230624   000000    000959  1687536599  31232.9  31309.1
2023-06-24 00:10:01,136:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5844 

self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='31318.2', self.close='31208.6'
127.0.0.1 - - [24/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 00:20:09,583:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='31318.2', self.close='31208.6'
2023-06-24 00:20:09,721:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230623   233000    233959  1687534799  30645.2  30759.9
17422  20230623   234000    234959  1687535399  30760.7  30908.2
17423  20230623   235000    235959  1687535999  30908.3  31238.1
17424  20230624   000000    000959  1687536599  31232.9  31309.1
17425  20230624   001000    001959  1687537199  31318.2  31208.6
2023-06-24 00:20:09,722:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [24/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-24 00:00:04,313:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42450F1687536003688I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687536004101259, 'quantity': '40.903', 'price': '31232.5', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687536002768, 'updatetime': 1687536004101, 'tradetype': 'usdt', 'selfid': 42450, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687536004101, 'clientorderid': '42450F1687536003688I0L2', 'price': '31232.5', 'quantity': '40.903', 'commission': '1277.5029475', 'commissionasset': 'USDT', 'tradetime': 1687536004101, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687536004101}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5843 

self.closeSec=1687536599, self.tradeDate='20230624', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='31232.9', self.close='31309.1'
127.0.0.1 - - [24/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-24 00:10:01,109:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687536599, self.tradeDate='20230624', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='31232.9', self.close='31309.1'
2023-06-24 00:10:01,131:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230623   232000    232959  1687534199  30694.9  30641.9
12237  20230623   233000    233959  1687534799  30645.2  30759.9
12238  20230623   234000    234959  1687535399  30760.7  30908.2
12239  20230623   235000    235959  1687535999  30908.3  31238.1
12240  20230624   000000    000959  1687536599  31232.9  31309.1
2023-06-24 00:10:01,133:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5844 

self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='31318.2', self.close='31208.6'
127.0.0.1 - - [24/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-24 00:20:09,084:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='31318.2', self.close='31208.6'
2023-06-24 00:20:09,422:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230623   233000    233959  1687534799  30645.2  30759.9
12238  20230623   234000    234959  1687535399  30760.7  30908.2
12239  20230623   235000    235959  1687535999  30908.3  31238.1
12240  20230624   000000    000959  1687536599  31232.9  31309.1
12241  20230624   001000    001959  1687537199  31318.2  31208.6
2023-06-24 00:20:09,424:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11680
self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=31372.0, self.close=31208.6, self.high=31385.7, self.low=31100.0, self.vol=10322.831, self.amt=322379647.77716 
127.0.0.1 - - [24/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-24 00:20:07,591:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230623   235500    235959  ...         0.0        0.0       0
5760  20230624   000000    000459  ...         0.0        0.0       0
5761  20230624   000500    000959  ...         0.0        0.0       0
5762  20230624   001000    001459  ...         0.0        0.0       0
5763  20230624   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 00:20:07,622:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687537199, self.tradeDate='20230624', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=31372.0, self.close=31208.6, self.high=31385.7, self.low=31100.0, self.vol=10322.831, self.amt=322379647.77716, ukdf['pct'].iloc[-1]=-0.004913 , ukdf['amount'].iloc[-1]=322379647.77716, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '160827.07531906054', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31174.17622894', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=11681
self.closeSec=1687537499, self.tradeDate='20230624', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=31208.5, self.close=30886.6, self.high=31212.8, self.low=30655.1, self.vol=22939.9, self.amt=708814925.2472 
127.0.0.1 - - [24/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-24 00:25:00,805:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230624   000000    000459  ...         0.0        0.0       0
5761  20230624   000500    000959  ...         0.0        0.0       0
5762  20230624   001000    001459  ...         0.0        0.0       0
5763  20230624   001500    001959  ...         0.0        0.0       0
5764  20230624   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-24 00:25:00,806:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687537499, self.tradeDate='20230624', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=31208.5, self.close=30886.6, self.high=31212.8, self.low=30655.1, self.vol=22939.9, self.amt=708814925.2472, ukdf['pct'].iloc[-1]=-0.010318 , ukdf['amount'].iloc[-1]=708814925.2472, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '150195.23047519796', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30887.91993956', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230623   120000    155959  1687507199  ...    723  1.037418  1.420951     1.0
724  20230623   160000    195959  1687521599  ...    724  0.997270  1.273535     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '115064.84051416288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30134.73435277', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [24/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1490949.9863712, self.flagDict['side']='buy', self.tradeCount=7, self.count=243
self.closeSec=1687535999, self.tradeDate='20230623', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30125.2, self.close=31238.1, self.high=31500.0, self.low=29901.1, self.vol=269745.999, self.amt=8259524515.47093 
2023-06-24 00:00:01,705:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687535999, self.tradeDate='20230623', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30125.2, self.close=31238.1, self.high=31500.0, self.low=29901.1, self.vol=269745.999, self.amt=8259524515.47093 
2023-06-24 00:00:01,734:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230623   040000    075959  ...   45457.791  1.365426e+09 -0.011050
722  20230623   080000    115959  ...   46051.180  1.379366e+09  0.004264
723  20230623   120000    155959  ...   29527.682  8.858129e+08 -0.002513
724  20230623   160000    195959  ...   57808.102  1.737403e+09  0.006626
725  20230623   200000    235959  ...  269745.999  8.259525e+09  0.036939

[5 rows x 11 columns]
2023-06-24 00:00:03,554:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230623   040000    075959  1687478399  ...    721  1.101090  1.690718     1.0
722  20230623   080000    115959  1687492799  ...    722  1.081274  1.587372     1.0
723  20230623   120000    155959  1687507199  ...    723  1.037418  1.420951     1.0
724  20230623   160000    195959  1687521599  ...    724  0.997270  1.273535     1.0
725  20230623   200000    235959  1687535999  ...    725  1.006118  1.272443     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.344', 'enterprice': '27977.7', 'countrevence': '0', 'unrealprofit': '173768.4856491136', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31235.2076044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


