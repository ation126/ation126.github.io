# 20230615 00:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9088
self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25990.7, self.close=25965.3, self.high=25995.9, self.low=25965.3, self.vol=519.208, self.amt=13486550.9145 
127.0.0.1 - - [15/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 00:20:06,992:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230614   235500    235959  ...         0.0        0.0       0
5760  20230615   000000    000459  ...         0.0        0.0       0
5761  20230615   000500    000959  ...         0.0        0.0       0
5762  20230615   001000    001459  ...         0.0        0.0       0
5763  20230615   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 00:20:07,022:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25990.7, self.close=25965.3, self.high=25995.9, self.low=25965.3, self.vol=519.208, self.amt=13486550.9145, ukdf['pct'].iloc[-1]=-0.000973 , ukdf['amount'].iloc[-1]=13486550.9145, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12542.47332459396', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25964.24846154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=9089
self.closeSec=1686759899, self.tradeDate='20230615', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25965.4, self.close=25965.2, self.high=25972.6, self.low=25959.5, self.vol=293.874, self.amt=7630470.8653 
127.0.0.1 - - [15/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-15 00:25:00,789:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230615   000000    000459  ...         0.0        0.0       0
5761  20230615   000500    000959  ...         0.0        0.0       0
5762  20230615   001000    001459  ...         0.0        0.0       0
5763  20230615   001500    001959  ...         0.0        0.0       0
5764  20230615   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 00:25:00,789:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686759899, self.tradeDate='20230615', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25965.4, self.close=25965.2, self.high=25972.6, self.low=25959.5, self.vol=293.874, self.amt=7630470.8653, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=7630470.8653, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '12498.04887448458', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25967.43849817', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25990.7, self.close=25965.3, self.high=25995.9, self.low=25965.3 
127.0.0.1 - - [15/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 00:20:04,496:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25990.7, self.close=25965.3, self.high=25995.9, self.low=25965.3   
2023-06-15 00:20:05,987:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230614   235500    235959  1686758399  ...  25947.0  0.000936   1727    5
1440  20230615   000000    000459  1686758699  ...  25960.7 -0.000604   1440    0
1441  20230615   000500    000959  1686758999  ...  25952.9 -0.000270   1441    1
1442  20230615   001000    001459  1686759299  ...  25953.5  0.001422   1442    2
1443  20230615   001500    001959  1686759599  ...  25965.3 -0.000973   1443    3

[5 rows x 11 columns]
2023-06-15 00:20:05,997:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=106, self.factor=0.4504614472489969, self.count=9091 

self.closeSec=1686759899, self.tradeDate='20230615', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25965.4, self.close=25965.2, self.high=25972.6, self.low=25959.5 
2023-06-15 00:25:00,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686759899, self.tradeDate='20230615', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25965.4, self.close=25965.2, self.high=25972.6, self.low=25959.5   
2023-06-15 00:25:00,772:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230615   000000    000459  1686758699  ...  25960.7 -0.000604   1440    0
1441  20230615   000500    000959  1686758999  ...  25952.9 -0.000270   1441    1
1442  20230615   001000    001459  1686759299  ...  25953.5  0.001422   1442    2
1443  20230615   001500    001959  1686759599  ...  25965.3 -0.000973   1443    3
1444  20230615   002000    002459  1686759899  ...  25959.5 -0.000004   1444    4

[5 rows x 11 columns]
2023-06-15 00:25:00,775:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-15 00:00:21,133:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230614    212959  26006.9  ...  47.500000  0.512032  0.486913
5803  20230614    215959  25979.8  ...  47.916667  0.512520  0.476536
5804  20230614    222959  25981.5  ...  47.500000  0.509519  0.469278
5805  20230614    225959  25971.8  ...  47.916667  0.514990  0.458198
5806  20230614    232959  25990.2  ...  47.916667  0.507251  0.453629

[5 rows x 33 columns]
0.5238970588235294
acc is : 0.5238970588235294
2023-06-15 00:00:21,231:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     1  0.499086  0.500914       1  ...  1.002711  -1.0    0.0  0.956563
540     0  0.502091  0.497909       0  ...  1.003089  -1.0    0.0  0.956202
541     1  0.499621  0.500379       1  ...  1.002375  -1.0    0.0  0.956884
542     0  0.503699  0.496301       0  ...  1.003331  -1.0    0.0  0.955970
543     1  0.493418  0.506582       1  ...  1.002906  -1.0    0.0  0.956375

[5 rows x 10 columns]
2023-06-15 00:00:21,255:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499071  0.500929       1  ...  1.002711  -1.0    0.0  0.955722
46     0  0.502144  0.497856       0  ...  1.003089  -1.0    0.0  0.955917
47     1  0.499675  0.500325       1  ...  1.002375  -1.0    0.0  0.956598
48     0  0.503609  0.496391       0  ...  1.003331  -1.0    0.0  0.955823
49     1  0.493418  0.506582       1  ...  1.002906  -1.0    0.0  0.956375

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-11643.40259302636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25972.75617582', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [15/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-15 00:00:04,441:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42388F1686758403726I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686758404120839, 'quantity': '28.142', 'price': '25976.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686758402802, 'updatetime': 1686758404120, 'tradetype': 'usdt', 'selfid': 42388, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686758404120, 'clientorderid': '42388F1686758403726I0L59', 'price': '25976.3', 'quantity': '28.142', 'commission': '731.0250346', 'commissionasset': 'USDT', 'tradetime': 1686758404120, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686758404120}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4544 

self.closeSec=1686758999, self.tradeDate='20230615', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25976.4', self.close='25953.7'
2023-06-15 00:10:01,106:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686758999, self.tradeDate='20230615', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25976.4', self.close='25953.7'
2023-06-15 00:10:01,120:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230614   232000    232959  1686756599  25981.2  25968.5 -0.000493
573  20230614   233000    233959  1686757199  25968.4  25968.2 -0.000012
574  20230614   234000    234959  1686757799  25968.2  25950.3 -0.000689
575  20230614   235000    235959  1686758399  25950.2  25976.4  0.001006
576  20230615   000000    000959  1686758999  25976.4  25953.7 -0.000874
2023-06-15 00:10:01,121:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4545 

self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25953.7', self.close='25965.4'
127.0.0.1 - - [15/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 00:20:06,942:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25953.7', self.close='25965.4'
2023-06-15 00:20:07,772:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230614   233000    233959  1686757199  25968.4  25968.2 -0.000012
574  20230614   234000    234959  1686757799  25968.2  25950.3 -0.000689
575  20230614   235000    235959  1686758399  25950.2  25976.4  0.001006
576  20230615   000000    000959  1686758999  25976.4  25953.7 -0.000874
577  20230615   001000    001959  1686759599  25953.7  25965.4  0.000451
2023-06-15 00:20:07,781:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-15 00:00:04,263:INFO:pyemd2:main.py:303:handleOrderFilled:2217508: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42387F1686758403635I0L57', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686758404007526, 'quantity': '37.748', 'price': '25976.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686758402785, 'updatetime': 1686758404007, 'tradetype': 'usdt', 'selfid': 42387, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686758404007, 'clientorderid': '42387F1686758403635I0L57', 'price': '25976.3', 'quantity': '37.748', 'commission': '980.5533724', 'commissionasset': 'USDT', 'tradetime': 1686758404007, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686758404007}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [15/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4547 

self.closeSec=1686758999, self.tradeDate='20230615', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25976.4', self.close='25953.7'
2023-06-15 00:10:01,134:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686758999, self.tradeDate='20230615', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25976.4', self.close='25953.7'
2023-06-15 00:10:01,145:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230614   232000    232959  1686756599  25981.2  25968.5
17421  20230614   233000    233959  1686757199  25968.4  25968.2
17422  20230614   234000    234959  1686757799  25968.2  25950.3
17423  20230614   235000    235959  1686758399  25950.2  25976.4
17424  20230615   000000    000959  1686758999  25976.4  25953.7
2023-06-15 00:10:01,146:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4548 

self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25953.7', self.close='25965.4'
127.0.0.1 - - [15/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 00:20:08,874:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25953.7', self.close='25965.4'
2023-06-15 00:20:09,032:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230614   233000    233959  1686757199  25968.4  25968.2
17422  20230614   234000    234959  1686757799  25968.2  25950.3
17423  20230614   235000    235959  1686758399  25950.2  25976.4
17424  20230615   000000    000959  1686758999  25976.4  25953.7
17425  20230615   001000    001959  1686759599  25953.7  25965.4
2023-06-15 00:20:09,033:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

2023-06-15 00:00:04,601:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42389F1686758403742I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1686758404124351, 'quantity': '50.237', 'price': '25976.3', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1686758402837, 'updatetime': 1686758404124, 'tradetype': 'usdt', 'selfid': 42389, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1686758404124, 'clientorderid': '42389F1686758403742I0L2', 'price': '25976.3', 'quantity': '50.237', 'commission': '1304.9713831', 'commissionasset': 'USDT', 'tradetime': 1686758404124, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1686758404124}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [15/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4547 

self.closeSec=1686758999, self.tradeDate='20230615', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='25976.4', self.close='25953.7'
127.0.0.1 - - [15/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-15 00:10:01,108:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686758999, self.tradeDate='20230615', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='25976.4', self.close='25953.7'
2023-06-15 00:10:01,125:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230614   232000    232959  1686756599  25981.2  25968.5
12237  20230614   233000    233959  1686757199  25968.4  25968.2
12238  20230614   234000    234959  1686757799  25968.2  25950.3
12239  20230614   235000    235959  1686758399  25950.2  25976.4
12240  20230615   000000    000959  1686758999  25976.4  25953.7
2023-06-15 00:10:01,125:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4548 

self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='25953.7', self.close='25965.4'
127.0.0.1 - - [15/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-15 00:20:08,578:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='25953.7', self.close='25965.4'
2023-06-15 00:20:08,841:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230614   233000    233959  1686757199  25968.4  25968.2
12238  20230614   234000    234959  1686757799  25968.2  25950.3
12239  20230614   235000    235959  1686758399  25950.2  25976.4
12240  20230615   000000    000959  1686758999  25976.4  25953.7
12241  20230615   001000    001959  1686759599  25953.7  25965.4
2023-06-15 00:20:08,842:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9088
self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=25990.7, self.close=25965.3, self.high=25995.9, self.low=25965.3, self.vol=519.208, self.amt=13486550.9145 
127.0.0.1 - - [15/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-15 00:20:06,972:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230614   235500    235959  ...         0.0        0.0       0
5760  20230615   000000    000459  ...         0.0        0.0       0
5761  20230615   000500    000959  ...         0.0        0.0       0
5762  20230615   001000    001459  ...         0.0        0.0       0
5763  20230615   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 00:20:06,993:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686759599, self.tradeDate='20230615', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=25990.7, self.close=25965.3, self.high=25995.9, self.low=25965.3, self.vol=519.208, self.amt=13486550.9145, ukdf['pct'].iloc[-1]=-0.000973 , ukdf['amount'].iloc[-1]=13486550.9145, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32674.85188994286', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25964.24846154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=9089
self.closeSec=1686759899, self.tradeDate='20230615', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=25965.4, self.close=25965.2, self.high=25972.6, self.low=25959.5, self.vol=293.874, self.amt=7630470.8653 
127.0.0.1 - - [15/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-15 00:25:00,788:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230615   000000    000459  ...         0.0        0.0       0
5761  20230615   000500    000959  ...         0.0        0.0       0
5762  20230615   001000    001459  ...         0.0        0.0       0
5763  20230615   001500    001959  ...         0.0        0.0       0
5764  20230615   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-15 00:25:00,790:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686759899, self.tradeDate='20230615', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=25965.4, self.close=25965.2, self.high=25972.6, self.low=25959.5, self.vol=293.874, self.amt=7630470.8653, ukdf['pct'].iloc[-1]=-4e-06 , ukdf['amount'].iloc[-1]=7630470.8653, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-32556.37073946803', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25967.43849817', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230614   120000    155959  1686729599  ...    723  0.001596 -1.874697    -1.0
724  20230614   160000    195959  1686743999  ...    724  0.022247 -1.771563    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '61221.447282755', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25968.8322575', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [15/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=189
self.closeSec=1686758399, self.tradeDate='20230614', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=25967.3, self.close=25976.4, self.high=26077.0, self.low=25915.6, self.vol=41580.783, self.amt=1080340094.83536 
2023-06-15 00:00:01,784:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686758399, self.tradeDate='20230614', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=25967.3, self.close=25976.4, self.high=26077.0, self.low=25915.6, self.vol=41580.783, self.amt=1080340094.83536 
2023-06-15 00:00:01,833:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
721  20230614   040000    075959  ...  28618.868  7.399962e+08  0.001035
722  20230614   080000    115959  ...  33269.028  8.642652e+08  0.002033
723  20230614   120000    155959  ...  30116.376  7.800111e+08 -0.003335
724  20230614   160000    195959  ...  28960.713  7.513646e+08  0.003210
725  20230614   200000    235959  ...  41580.783  1.080340e+09  0.000354

[5 rows x 11 columns]
2023-06-15 00:00:03,415:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230614   040000    075959  1686700799  ...    721  0.092837 -1.599018    -1.0
722  20230614   080000    115959  1686715199  ...    722  0.038794 -1.770530    -1.0
723  20230614   120000    155959  1686729599  ...    723  0.001596 -1.874697    -1.0
724  20230614   160000    195959  1686743999  ...    724  0.022247 -1.771563    -1.0
725  20230614   200000    235959  1686758399  ...    725  0.012297 -1.782169    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '60803.9652', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25976.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


