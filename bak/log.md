# 20230610 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7648
self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26511.5, self.close=26493.9, self.high=26521.1, self.low=26493.4, self.vol=1199.132, self.amt=31784805.017 
127.0.0.1 - - [10/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:20:04,197:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230609   235500    235959  ...         0.0        0.0       0
5760  20230610   000000    000459  ...         0.0        0.0       0
5761  20230610   000500    000959  ...         0.0        0.0       0
5762  20230610   001000    001459  ...         0.0        0.0       0
5763  20230610   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 00:20:04,201:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26511.5, self.close=26493.9, self.high=26521.1, self.low=26493.4, self.vol=1199.132, self.amt=31784805.017, ukdf['pct'].iloc[-1]=-0.000547 , ukdf['amount'].iloc[-1]=31784805.017, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5114.51989225056', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26497.63589744', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7649
self.closeSec=1686327899, self.tradeDate='20230610', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26494.0, self.close=26492.0, self.high=26507.0, self.low=26485.0, self.vol=759.594, self.amt=20124830.0882 
127.0.0.1 - - [10/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:25:04,320:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230610   000000    000459  ...         0.0        0.0       0
5761  20230610   000500    000959  ...         0.0        0.0       0
5762  20230610   001000    001459  ...         0.0        0.0       0
5763  20230610   001500    001959  ...         0.0        0.0       0
5764  20230610   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 00:25:04,333:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686327899, self.tradeDate='20230610', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26494.0, self.close=26492.0, self.high=26507.0, self.low=26485.0, self.vol=759.594, self.amt=20124830.0882, ukdf['pct'].iloc[-1]=-7.2e-05 , ukdf['amount'].iloc[-1]=20124830.0882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '5206.9314', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26511.5, self.close=26493.9, self.high=26521.1, self.low=26493.4 
127.0.0.1 - - [10/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:20:02,831:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26511.5, self.close=26493.9, self.high=26521.1, self.low=26493.4   
2023-06-10 00:20:03,832:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230609   235500    235959  1686326399  ...  26440.0 -0.000008   1727    5
1440  20230610   000000    000459  1686326699  ...  26430.0  0.000023   1440    0
1441  20230610   000500    000959  1686326999  ...  26466.9  0.001247   1441    1
1442  20230610   001000    001459  1686327299  ...  26490.1  0.000366   1442    2
1443  20230610   001500    001959  1686327599  ...  26493.4 -0.000547   1443    3

[5 rows x 11 columns]
2023-06-10 00:20:03,841:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=17, self.factor=0.447013511170895, self.count=7651 

self.closeSec=1686327899, self.tradeDate='20230610', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26494.0, self.close=26492.0, self.high=26507.0, self.low=26485.0 
127.0.0.1 - - [10/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:25:03,190:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686327899, self.tradeDate='20230610', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26494.0, self.close=26492.0, self.high=26507.0, self.low=26485.0   
2023-06-10 00:25:03,935:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230610   000000    000459  1686326699  ...  26430.0  0.000023   1440    0
1441  20230610   000500    000959  1686326999  ...  26466.9  0.001247   1441    1
1442  20230610   001000    001459  1686327299  ...  26490.1  0.000366   1442    2
1443  20230610   001500    001959  1686327599  ...  26493.4 -0.000547   1443    3
1444  20230610   002000    002459  1686327899  ...  26485.0 -0.000072   1444    4

[5 rows x 11 columns]
2023-06-10 00:25:03,938:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-10 00:00:38,383:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230609    212959  26662.2  ...  50.416667  0.534209  0.392702
5803  20230609    215959  26673.3  ...  50.000000  0.522961  0.385817
5804  20230609    222959  26619.0  ...  50.416667  0.533533  0.372972
5805  20230609    225959  26670.9  ...  50.000000  0.513272  0.372188
5806  20230609    232959  26580.2  ...  50.000000  0.510586  0.372979

[5 rows x 33 columns]
0.5055147058823529
acc is : 0.5055147058823529
2023-06-10 00:00:38,593:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.505925  0.494075       0  ...  1.053726   1.0    0.0  0.954257
540     1  0.495031  0.504969       1  ...  1.055781   1.0    0.0  0.956118
541     0  0.516160  0.483840       0  ...  1.052194   1.0    0.0  0.952870
542     1  0.479788  0.520212       0  ...  1.051707   1.0    0.0  0.952429
543     1  0.488931  0.511069       0  ...  1.047634   1.0    0.0  0.948740

[5 rows x 10 columns]
2023-06-10 00:00:38,630:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505991  0.494009       0  ...  1.053726   1.0    0.0  0.949986
46     1  0.495266  0.504734       1  ...  1.055781   1.0    0.0  0.952532
47     0  0.516293  0.483707       0  ...  1.052194   1.0    0.0  0.949296
48     1  0.479966  0.520034       0  ...  1.051707   1.0    0.0  0.952668
49     1  0.488931  0.511069       0  ...  1.047634   1.0    0.0  0.948740

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.647', 'enterprice': '26630.1', 'countrevence': '0', 'unrealprofit': '-5162.1894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26449.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-06-10 00:00:04,530:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42354F1686326403949I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686326404320185, 'quantity': '26.615', 'price': '26465.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686326403023, 'updatetime': 1686326404320, 'tradetype': 'usdt', 'selfid': 42354, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686326404320, 'clientorderid': '42354F1686326403949I0L59', 'price': '26465.2', 'quantity': '26.615', 'commission': '704.371298', 'commissionasset': 'USDT', 'tradetime': 1686326404320, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686326404320}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [10/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3824 

self.closeSec=1686326999, self.tradeDate='20230610', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26465.2', self.close='26498.7'
127.0.0.1 - - [10/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:10:01,104:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686326999, self.tradeDate='20230610', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26465.2', self.close='26498.7'
2023-06-10 00:10:01,144:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230609   232000    232959  1686324599  26621.9    26568 -0.002028
573  20230609   233000    233959  1686325199    26568  26576.1  0.000305
574  20230609   234000    234959  1686325799    26576  26491.1 -0.003198
575  20230609   235000    235959  1686326399  26491.2  26465.1 -0.000981
576  20230610   000000    000959  1686326999  26465.2  26498.7  0.001270
2023-06-10 00:10:01,145:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3825 

self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26498.7', self.close='26493.9'
127.0.0.1 - - [10/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-10 00:20:04,076:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26498.7', self.close='26493.9'
2023-06-10 00:20:04,153:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230609   233000    233959  1686325199    26568  26576.1  0.000305
574  20230609   234000    234959  1686325799    26576  26491.1 -0.003198
575  20230609   235000    235959  1686326399  26491.2  26465.1 -0.000981
576  20230610   000000    000959  1686326999  26465.2  26498.7  0.001270
577  20230610   001000    001959  1686327599  26498.7  26493.9 -0.000181
2023-06-10 00:20:04,154:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-10 00:00:02,309:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-10 00:00:02,515:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6100000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230609, closeTime:235959, close:26465.1, total:986921.7718383, pct_pre:-0.0006080464817754816, thd:0.38153893596908695, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3827 

self.closeSec=1686326999, self.tradeDate='20230610', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26465.2', self.close='26498.7'
127.0.0.1 - - [10/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:10:01,109:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686326999, self.tradeDate='20230610', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26465.2', self.close='26498.7'
2023-06-10 00:10:01,164:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230609   232000    232959  1686324599  26621.9    26568
17421  20230609   233000    233959  1686325199    26568  26576.1
17422  20230609   234000    234959  1686325799    26576  26491.1
17423  20230609   235000    235959  1686326399  26491.2  26465.1
17424  20230610   000000    000959  1686326999  26465.2  26498.7
2023-06-10 00:10:01,165:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3828 

self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26498.7', self.close='26493.9'
127.0.0.1 - - [10/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-10 00:20:03,899:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26498.7', self.close='26493.9'
2023-06-10 00:20:03,936:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230609   233000    233959  1686325199    26568  26576.1
17422  20230609   234000    234959  1686325799    26576  26491.1
17423  20230609   235000    235959  1686326399  26491.2  26465.1
17424  20230610   000000    000959  1686326999  26465.2  26498.7
17425  20230610   001000    001959  1686327599  26498.7  26493.9
2023-06-10 00:20:03,938:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [10/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-10 00:00:04,715:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42355F1686326403969I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686326404357385, 'quantity': '46.783', 'price': '26465.2', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1686326402990, 'updatetime': 1686326404357, 'tradetype': 'usdt', 'selfid': 42355, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686326404357, 'clientorderid': '42355F1686326403969I0L2', 'price': '26465.2', 'quantity': '46.783', 'commission': '1238.1214516', 'commissionasset': 'USDT', 'tradetime': 1686326404357, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686326404357}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3827 

self.closeSec=1686326999, self.tradeDate='20230610', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='26465.2', self.close='26498.7'
127.0.0.1 - - [10/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:10:01,128:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686326999, self.tradeDate='20230610', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='26465.2', self.close='26498.7'
2023-06-10 00:10:01,158:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230609   232000    232959  1686324599  26621.9    26568
12237  20230609   233000    233959  1686325199    26568  26576.1
12238  20230609   234000    234959  1686325799    26576  26491.1
12239  20230609   235000    235959  1686326399  26491.2  26465.1
12240  20230610   000000    000959  1686326999  26465.2  26498.7
2023-06-10 00:10:01,170:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3828 

self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='26498.7', self.close='26493.9'
127.0.0.1 - - [10/Jun/2023 00:20:03] "POST / HTTP/1.1" 200 -
2023-06-10 00:20:04,172:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='26498.7', self.close='26493.9'
2023-06-10 00:20:04,205:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230609   233000    233959  1686325199    26568  26576.1
12238  20230609   234000    234959  1686325799    26576  26491.1
12239  20230609   235000    235959  1686326399  26491.2  26465.1
12240  20230610   000000    000959  1686326999  26465.2  26498.7
12241  20230610   001000    001959  1686327599  26498.7  26493.9
2023-06-10 00:20:04,205:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7648
self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=26511.5, self.close=26493.9, self.high=26521.1, self.low=26493.4, self.vol=1199.132, self.amt=31784805.017 
127.0.0.1 - - [10/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:20:04,214:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230609   235500    235959  ...         0.0        0.0       0
5760  20230610   000000    000459  ...         0.0        0.0       0
5761  20230610   000500    000959  ...         0.0        0.0       0
5762  20230610   001000    001459  ...         0.0        0.0       0
5763  20230610   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 00:20:04,215:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686327599, self.tradeDate='20230610', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=26511.5, self.close=26493.9, self.high=26521.1, self.low=26493.4, self.vol=1199.132, self.amt=31784805.017, ukdf['pct'].iloc[-1]=-0.000547 , ukdf['amount'].iloc[-1]=31784805.017, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-12864.30913318096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26497.63589744', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7649
self.closeSec=1686327899, self.tradeDate='20230610', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=26494.0, self.close=26492.0, self.high=26507.0, self.low=26485.0, self.vol=759.594, self.amt=20124830.0882 
127.0.0.1 - - [10/Jun/2023 00:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:25:04,277:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230610   000000    000459  ...         0.0        0.0       0
5761  20230610   000500    000959  ...         0.0        0.0       0
5762  20230610   001000    001459  ...         0.0        0.0       0
5763  20230610   001500    001959  ...         0.0        0.0       0
5764  20230610   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 00:25:04,292:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686327899, self.tradeDate='20230610', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=26494.0, self.close=26492.0, self.high=26507.0, self.low=26485.0, self.vol=759.594, self.amt=20124830.0882, ukdf['pct'].iloc[-1]=-7.2e-05 , ukdf['amount'].iloc[-1]=20124830.0882, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-13110.773', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230609   120000    155959  1686297599  ...    723  0.493077 -0.392767     NaN
724  20230609   160000    195959  1686311999  ...    724  0.505577 -0.348308     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '26379.28825782792', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26600.41981188', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=159
self.closeSec=1686326399, self.tradeDate='20230609', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=26599.9, self.close=26465.1, self.high=26775.0, self.low=26436.8, self.vol=78006.116, self.amt=2075991908.3396 
127.0.0.1 - - [10/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-10 00:00:01,813:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686326399, self.tradeDate='20230609', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=26599.9, self.close=26465.1, self.high=26775.0, self.low=26436.8, self.vol=78006.116, self.amt=2075991908.3396 
2023-06-10 00:00:01,867:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230609   040000    075959  ...  27001.036  7.172898e+08 -0.001546
722  20230609   080000    115959  ...  59149.513  1.563425e+09 -0.000619
723  20230609   120000    155959  ...  33723.828  8.930172e+08  0.000499
724  20230609   160000    195959  ...  49448.532  1.315238e+09  0.004422
725  20230609   200000    235959  ...  78006.116  2.075992e+09 -0.005064

[5 rows x 11 columns]
2023-06-10 00:00:04,693:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230609   040000    075959  1686268799  ...    721  0.576510 -0.112975     NaN
722  20230609   080000    115959  1686283199  ...    722  0.529046 -0.273858     NaN
723  20230609   120000    155959  1686297599  ...    723  0.493077 -0.392767     NaN
724  20230609   160000    195959  1686311999  ...    724  0.505577 -0.348308     NaN
725  20230609   200000    235959  1686326399  ...    725  0.527936 -0.271627     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '33844.341', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26465.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


