# 20230619 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10240
self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26547.5, self.close=26585.9, self.high=26594.6, self.low=26534.6, self.vol=1141.318, self.amt=30328061.7958 
127.0.0.1 - - [19/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 00:20:07,145:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230618   235500    235959  ...         0.0        0.0       0
5760  20230619   000000    000459  ...         0.0        0.0       0
5761  20230619   000500    000959  ...         0.0        0.0       0
5762  20230619   001000    001459  ...         0.0        0.0       0
5763  20230619   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 00:20:07,176:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26547.5, self.close=26585.9, self.high=26594.6, self.low=26534.6, self.vol=1141.318, self.amt=30328061.7958, ukdf['pct'].iloc[-1]=0.001443 , ukdf['amount'].iloc[-1]=30328061.7958, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3828.2574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26590', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=10241
self.closeSec=1687105499, self.tradeDate='20230619', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26585.8, self.close=26617.4, self.high=26641.6, self.low=26585.8, self.vol=3473.529, self.amt=92435489.6648 
127.0.0.1 - - [19/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-19 00:25:00,800:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230619   000000    000459  ...         0.0        0.0       0
5761  20230619   000500    000959  ...         0.0        0.0       0
5762  20230619   001000    001459  ...         0.0        0.0       0
5763  20230619   001500    001959  ...         0.0        0.0       0
5764  20230619   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 00:25:00,800:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687105499, self.tradeDate='20230619', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26585.8, self.close=26617.4, self.high=26641.6, self.low=26585.8, self.vol=3473.529, self.amt=92435489.6648, ukdf['pct'].iloc[-1]=0.001185 , ukdf['amount'].iloc[-1]=92435489.6648, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '3422.36617409412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26619.14628938', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26547.5, self.close=26585.9, self.high=26594.6, self.low=26534.6 
127.0.0.1 - - [19/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 00:20:04,816:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26547.5, self.close=26585.9, self.high=26594.6, self.low=26534.6   
2023-06-19 00:20:06,225:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230618   235500    235959  1687103999  ...  26545.0  0.000090   1727    5
1440  20230619   000000    000459  1687104299  ...  26511.2 -0.000870   1440    0
1441  20230619   000500    000959  1687104599  ...  26524.4  0.001229   1441    1
1442  20230619   001000    001459  1687104899  ...  26530.3 -0.000354   1442    2
1443  20230619   001500    001959  1687105199  ...  26534.6  0.001443   1443    3

[5 rows x 11 columns]
2023-06-19 00:20:06,227:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=85, self.factor=0.408750298277398, self.count=10243 

self.closeSec=1687105499, self.tradeDate='20230619', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26585.8, self.close=26617.4, self.high=26641.6, self.low=26585.8 
2023-06-19 00:25:00,751:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687105499, self.tradeDate='20230619', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26585.8, self.close=26617.4, self.high=26641.6, self.low=26585.8   
2023-06-19 00:25:00,786:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230619   000000    000459  1687104299  ...  26511.2 -0.000870   1440    0
1441  20230619   000500    000959  1687104599  ...  26524.4  0.001229   1441    1
1442  20230619   001000    001459  1687104899  ...  26530.3 -0.000354   1442    2
1443  20230619   001500    001959  1687105199  ...  26534.6  0.001443   1443    3
1444  20230619   002000    002459  1687105499  ...  26585.8  0.001185   1444    4

[5 rows x 11 columns]
2023-06-19 00:25:00,786:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-19 00:00:21,040:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230618    212959  26521.8  ...  50.833333  0.557506  0.471093
5803  20230618    215959  26531.6  ...  50.833333  0.540539  0.482663
5804  20230618    222959  26477.1  ...  51.250000  0.551969  0.483179
5805  20230618    225959  26524.5  ...  51.666667  0.556011  0.479972
5806  20230618    232959  26541.4  ...  51.666667  0.551857  0.479995

[5 rows x 33 columns]
0.5735294117647058
acc is : 0.5735294117647058
2023-06-19 00:00:21,123:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.503724  0.496276       0  ...  1.060852   1.0    0.0  0.988438
540     1  0.489904  0.510096       1  ...  1.062752   1.0    0.0  0.990208
541     0  0.508946  0.491054       1  ...  1.063433   1.0    0.0  0.990842
542     0  0.507943  0.492057       0  ...  1.062876   1.0    0.0  0.990324
543     1  0.496554  0.503446       1  ...  1.063677   1.0    0.0  0.991070

[5 rows x 10 columns]
2023-06-19 00:00:21,135:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503869  0.496131       0  ...  1.060852   1.0    0.0  0.984359
46     1  0.489906  0.510094       1  ...  1.062752   1.0    0.0  0.988997
47     0  0.508886  0.491114       1  ...  1.063433   1.0    0.0  0.989631
48     0  0.507914  0.492086       0  ...  1.062876   1.0    0.0  0.988478
49     1  0.496554  0.503446       1  ...  1.063677   1.0    0.0  0.991070

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.127', 'enterprice': '25424', 'countrevence': '0', 'unrealprofit': '31640.55699514457', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26548.91758791', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [19/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-19 00:00:04,806:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42415F1687104003894I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687104004286776, 'quantity': '27.45', 'price': '26547.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687104002923, 'updatetime': 1687104004286, 'tradetype': 'usdt', 'selfid': 42415, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687104004286, 'clientorderid': '42415F1687104003894I0L59', 'price': '26547.5', 'quantity': '27.45', 'commission': '728.728875', 'commissionasset': 'USDT', 'tradetime': 1687104004286, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687104004286}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5120 

self.closeSec=1687104599, self.tradeDate='20230619', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26547.5', self.close='26557'
127.0.0.1 - - [19/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-19 00:10:01,130:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687104599, self.tradeDate='20230619', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26547.5', self.close='26557'
2023-06-19 00:10:01,140:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230618   232000    232959  1687102199  26540.3  26527.5 -0.000482
573  20230618   233000    233959  1687102799  26527.6    26525 -0.000094
574  20230618   234000    234959  1687103399  26524.9    26539  0.000528
575  20230618   235000    235959  1687103999  26538.9  26547.5  0.000320
576  20230619   000000    000959  1687104599  26547.5    26557  0.000358
2023-06-19 00:10:01,141:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5121 

self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26557', self.close='26585.9'
127.0.0.1 - - [19/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-19 00:20:07,005:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26557', self.close='26585.9'
2023-06-19 00:20:07,805:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230618   233000    233959  1687102799  26527.6    26525 -0.000094
574  20230618   234000    234959  1687103399  26524.9    26539  0.000528
575  20230618   235000    235959  1687103999  26538.9  26547.5  0.000320
576  20230619   000000    000959  1687104599  26547.5    26557  0.000358
577  20230619   001000    001959  1687105199    26557  26585.9  0.001088
2023-06-19 00:20:07,805:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

127.0.0.1 - - [19/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-19 00:00:04,400:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42413F1687104003679I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687104004094614, 'quantity': '36.654', 'price': '26547.5', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1687104002819, 'updatetime': 1687104004094, 'tradetype': 'usdt', 'selfid': 42413, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687104004094, 'clientorderid': '42413F1687104003679I0L57', 'price': '26547.5', 'quantity': '36.654', 'commission': '973.072065', 'commissionasset': 'USDT', 'tradetime': 1687104004094, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687104004094}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5123 

self.closeSec=1687104599, self.tradeDate='20230619', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26547.5', self.close='26557'
2023-06-19 00:10:01,109:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687104599, self.tradeDate='20230619', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26547.5', self.close='26557'
2023-06-19 00:10:01,147:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230618   232000    232959  1687102199  26540.3  26527.5
17421  20230618   233000    233959  1687102799  26527.6    26525
17422  20230618   234000    234959  1687103399  26524.9    26539
17423  20230618   235000    235959  1687103999  26538.9  26547.5
17424  20230619   000000    000959  1687104599  26547.5    26557
2023-06-19 00:10:01,147:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5124 

self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26557', self.close='26585.9'
127.0.0.1 - - [19/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-19 00:20:08,940:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26557', self.close='26585.9'
2023-06-19 00:20:09,083:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230618   233000    233959  1687102799  26527.6    26525
17422  20230618   234000    234959  1687103399  26524.9    26539
17423  20230618   235000    235959  1687103999  26538.9  26547.5
17424  20230619   000000    000959  1687104599  26547.5    26557
17425  20230619   001000    001959  1687105199    26557  26585.9
2023-06-19 00:20:09,084:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [19/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-19 00:00:04,608:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42414F1687104003821I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1687104004236858, 'quantity': '49.14', 'price': '26547.6', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1687104002892, 'updatetime': 1687104004236, 'tradetype': 'usdt', 'selfid': 42414, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1687104004236, 'clientorderid': '42414F1687104003821I0L2', 'price': '26547.6', 'quantity': '49.14', 'commission': '1304.549064', 'commissionasset': 'USDT', 'tradetime': 1687104004236, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1687104004236}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [19/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5123 

self.closeSec=1687104599, self.tradeDate='20230619', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26547.5', self.close='26557'
2023-06-19 00:10:01,113:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687104599, self.tradeDate='20230619', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26547.5', self.close='26557'
2023-06-19 00:10:01,123:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230618   232000    232959  1687102199  26540.3  26527.5
12237  20230618   233000    233959  1687102799  26527.6    26525
12238  20230618   234000    234959  1687103399  26524.9    26539
12239  20230618   235000    235959  1687103999  26538.9  26547.5
12240  20230619   000000    000959  1687104599  26547.5    26557
2023-06-19 00:10:01,124:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=5124 

self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26557', self.close='26585.9'
127.0.0.1 - - [19/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-19 00:20:08,556:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26557', self.close='26585.9'
2023-06-19 00:20:08,857:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230618   233000    233959  1687102799  26527.6    26525
12238  20230618   234000    234959  1687103399  26524.9    26539
12239  20230618   235000    235959  1687103999  26538.9  26547.5
12240  20230619   000000    000959  1687104599  26547.5    26557
12241  20230619   001000    001959  1687105199    26557  26585.9
2023-06-19 00:20:08,858:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10240
self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26547.5, self.close=26585.9, self.high=26594.6, self.low=26534.6, self.vol=1141.318, self.amt=30328061.7958 
127.0.0.1 - - [19/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-19 00:20:07,156:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230618   235500    235959  ...         0.0        0.0       0
5760  20230619   000000    000459  ...         0.0        0.0       0
5761  20230619   000500    000959  ...         0.0        0.0       0
5762  20230619   001000    001459  ...         0.0        0.0       0
5763  20230619   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 00:20:07,195:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687105199, self.tradeDate='20230619', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26547.5, self.close=26585.9, self.high=26594.6, self.low=26534.6, self.vol=1141.318, self.amt=30328061.7958, ukdf['pct'].iloc[-1]=0.001443 , ukdf['amount'].iloc[-1]=30328061.7958, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-9433.814', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26590', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=10241
self.closeSec=1687105499, self.tradeDate='20230619', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26585.8, self.close=26617.4, self.high=26641.6, self.low=26585.8, self.vol=3473.529, self.amt=92435489.6648 
2023-06-19 00:25:00,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230619   000000    000459  ...         0.0        0.0       0
5761  20230619   000500    000959  ...         0.0        0.0       0
5762  20230619   001000    001459  ...         0.0        0.0       0
5763  20230619   001500    001959  ...         0.0        0.0       0
5764  20230619   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-19 00:25:00,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687105499, self.tradeDate='20230619', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26585.8, self.close=26617.4, self.high=26641.6, self.low=26585.8, self.vol=3473.529, self.amt=92435489.6648, ukdf['pct'].iloc[-1]=0.001185 , ukdf['amount'].iloc[-1]=92435489.6648, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-8351.29166613742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26619.14628938', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230618   120000    155959  1687075199  ...    723  0.589647  1.084178     1.0
724  20230618   160000    195959  1687089599  ...    724  0.590845  1.086669     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-5711.7825', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26490.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1518762.96675, self.flagDict['side']='buy', self.tradeCount=5, self.count=213
self.closeSec=1687103999, self.tradeDate='20230618', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26488.5, self.close=26547.5, self.high=26566.0, self.low=26425.8, self.vol=33224.65, self.amt=880758089.1475 
127.0.0.1 - - [19/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-19 00:00:01,679:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687103999, self.tradeDate='20230618', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26488.5, self.close=26547.5, self.high=26566.0, self.low=26425.8, self.vol=33224.65, self.amt=880758089.1475 
2023-06-19 00:00:01,728:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230618   040000    075959  ...  21650.496  5.741625e+08  0.001613
722  20230618   080000    115959  ...  27032.825  7.153643e+08  0.001113
723  20230618   120000    155959  ...  40704.717  1.081643e+09  0.001266
724  20230618   160000    195959  ...  27593.456  7.312376e+08 -0.003142
725  20230618   200000    235959  ...  33224.650  8.807581e+08  0.002227

[5 rows x 11 columns]
2023-06-19 00:00:03,678:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230618   040000    075959  1687046399  ...    721  0.565101  0.945628     1.0
722  20230618   080000    115959  1687060799  ...    722  0.572393  0.992208     1.0
723  20230618   120000    155959  1687075199  ...    723  0.589647  1.084178     1.0
724  20230618   160000    195959  1687089599  ...    724  0.590845  1.086669     1.0
725  20230618   200000    235959  1687103999  ...    725  0.592151  1.080556     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '57.175', 'enterprice': '26590', 'countrevence': '0', 'unrealprofit': '-2353.88302169225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26548.83020513', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


