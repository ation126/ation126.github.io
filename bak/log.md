# 20230630 00:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13408
self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30518.4, self.close=30517.7, self.high=30521.2, self.low=30489.0, self.vol=748.963, self.amt=22844047.4971 
127.0.0.1 - - [30/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 00:20:07,308:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230629   235500    235959  ...         0.0        0.0       0
5760  20230630   000000    000459  ...         0.0        0.0       0
5761  20230630   000500    000959  ...         0.0        0.0       0
5762  20230630   001000    001459  ...         0.0        0.0       0
5763  20230630   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 00:20:07,328:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30518.4, self.close=30517.7, self.high=30521.2, self.low=30489.0, self.vol=748.963, self.amt=22844047.4971, ukdf['pct'].iloc[-1]=-1e-05 , ukdf['amount'].iloc[-1]=22844047.4971, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50850.789', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30516.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13409
self.closeSec=1688055899, self.tradeDate='20230630', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30517.8, self.close=30483.1, self.high=30536.5, self.low=30480.6, self.vol=831.611, self.amt=25369004.2401 
127.0.0.1 - - [30/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-30 00:25:00,839:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230630   000000    000459  ...         0.0        0.0       0
5761  20230630   000500    000959  ...         0.0        0.0       0
5762  20230630   001000    001459  ...         0.0        0.0       0
5763  20230630   001500    001959  ...         0.0        0.0       0
5764  20230630   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 00:25:00,839:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688055899, self.tradeDate='20230630', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30517.8, self.close=30483.1, self.high=30536.5, self.low=30480.6, self.vol=831.611, self.amt=25369004.2401, ukdf['pct'].iloc[-1]=-0.001134 , ukdf['amount'].iloc[-1]=25369004.2401, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50422.53895122114', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30485.64816539', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30518.4, self.close=30517.7, self.high=30521.2, self.low=30489.0 
127.0.0.1 - - [30/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 00:20:04,848:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30518.4, self.close=30517.7, self.high=30521.2, self.low=30489.0   
2023-06-30 00:20:06,377:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1439  20230629   235500    235959  1688054399  ...  30460.0 -0.001203   1727    5
1440  20230630   000000    000459  1688054699  ...  30468.2  0.000929   1440    0
1441  20230630   000500    000959  1688054999  ...  30496.6  0.001469   1441    1
1442  20230630   001000    001459  1688055299  ...  30492.6 -0.000766   1442    2
1443  20230630   001500    001959  1688055599  ...  30489.0 -0.000010   1443    3

[5 rows x 11 columns]
2023-06-30 00:20:06,387:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [30/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=15, self.factor=0.47095031451175906, self.count=13411 

self.closeSec=1688055899, self.tradeDate='20230630', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30517.8, self.close=30483.1, self.high=30536.5, self.low=30480.6 
2023-06-30 00:25:00,770:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688055899, self.tradeDate='20230630', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30517.8, self.close=30483.1, self.high=30536.5, self.low=30480.6   
2023-06-30 00:25:00,808:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1440  20230630   000000    000459  1688054699  ...  30468.2  0.000929   1440    0
1441  20230630   000500    000959  1688054999  ...  30496.6  0.001469   1441    1
1442  20230630   001000    001459  1688055299  ...  30492.6 -0.000766   1442    2
1443  20230630   001500    001959  1688055599  ...  30489.0 -0.000010   1443    3
1444  20230630   002000    002459  1688055899  ...  30480.6 -0.001134   1444    4

[5 rows x 11 columns]
2023-06-30 00:25:00,808:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-30 00:00:18,759:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5802  20230629    212959  30613.8  ...  50.416667  0.564659  0.281000
5803  20230629    215959  30727.8  ...  50.000000  0.532895  0.280606
5804  20230629    222959  30553.0  ...  50.416667  0.536064  0.278927
5805  20230629    225959  30573.3  ...  50.000000  0.512355  0.286123
5806  20230629    232959  30434.0  ...  50.416667  0.524176  0.288015

[5 rows x 33 columns]
0.5386029411764706
acc is : 0.5386029411764706
2023-06-30 00:00:18,864:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
539     0  0.517462  0.482538       0  ...  1.035000   1.0    0.0  1.149819
540     1  0.469987  0.530013       1  ...  1.035687   1.0    0.0  1.150583
541     1  0.495187  0.504813       0  ...  1.031090   1.0    0.0  1.145476
542     1  0.460022  0.539978       1  ...  1.033621   1.0    0.0  1.148288
543     0  0.501571  0.498429       0  ...  1.032130   1.0    0.0  1.146632

[5 rows x 10 columns]
2023-06-30 00:00:18,888:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.517411  0.482589       0  ...  1.035000   1.0    0.0  1.151188
46     1  0.470067  0.529933       1  ...  1.035687   1.0    0.0  1.152327
47     1  0.495201  0.504799       0  ...  1.031090   1.0    0.0  1.147212
48     1  0.460075  0.539925       1  ...  1.033621   1.0    0.0  1.147584
49     0  0.501571  0.498429       0  ...  1.032130   1.0    0.0  1.146632

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.241', 'enterprice': '30643.5', 'countrevence': '0', 'unrealprofit': '-4251.042', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30481.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

127.0.0.1 - - [30/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-30 00:00:04,404:INFO:modifiedmom:main.py:319:handleOrderFilled:2218259: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42498F1688054403691I0L59', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688054404073433, 'quantity': '26.775', 'price': '30468.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1688054402714, 'updatetime': 1688054404073, 'tradetype': 'usdt', 'selfid': 42498, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688054404073, 'clientorderid': '42498F1688054403691I0L59', 'price': '30468.3', 'quantity': '26.775', 'commission': '815.7887325', 'commissionasset': 'USDT', 'tradetime': 1688054404073, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688054404073}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6704 

self.closeSec=1688054999, self.tradeDate='20230630', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30468.2', self.close='30541.4'
2023-06-30 00:10:01,143:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688054999, self.tradeDate='20230630', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30468.2', self.close='30541.4'
127.0.0.1 - - [30/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-30 00:10:01,166:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
572  20230629   232000    232959  1688052599  30503.3  30512.3  0.000295
573  20230629   233000    233959  1688053199  30512.4    30526  0.000449
574  20230629   234000    234959  1688053799    30527  30503.3 -0.000744
575  20230629   235000    235959  1688054399  30503.3  30468.3 -0.001147
576  20230630   000000    000959  1688054999  30468.2  30541.4  0.002399
2023-06-30 00:10:01,166:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6705 

self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30541.5', self.close='30517.7'
127.0.0.1 - - [30/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 00:20:07,098:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30541.5', self.close='30517.7'
2023-06-30 00:20:07,868:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
573  20230629   233000    233959  1688053199  30512.4    30526  0.000449
574  20230629   234000    234959  1688053799    30527  30503.3 -0.000744
575  20230629   235000    235959  1688054399  30503.3  30468.3 -0.001147
576  20230630   000000    000959  1688054999  30468.2  30541.4  0.002399
577  20230630   001000    001959  1688055599  30541.5  30517.7 -0.000776
2023-06-30 00:20:07,878:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

2023-06-30 00:00:02,176:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
2023-06-30 00:00:02,288:INFO:pyemd2:main.py:190:insertFactor:2217508: curDateTime:6300000, name:pyemd2, symbol:BTCUSDT, tradeDate:20230629, closeTime:235959, close:30468.3, total:992420.1027844, pct_pre:-0.00012490344634896733, thd:-0.3019075564652959, side:sell 

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6707 

self.closeSec=1688054999, self.tradeDate='20230630', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30468.2', self.close='30541.4'
2023-06-30 00:10:01,138:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688054999, self.tradeDate='20230630', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30468.2', self.close='30541.4'
127.0.0.1 - - [30/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-30 00:10:01,172:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17420  20230629   232000    232959  1688052599  30503.3  30512.3
17421  20230629   233000    233959  1688053199  30512.4    30526
17422  20230629   234000    234959  1688053799    30527  30503.3
17423  20230629   235000    235959  1688054399  30503.3  30468.3
17424  20230630   000000    000959  1688054999  30468.2  30541.4
2023-06-30 00:10:01,172:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6708 

self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30541.5', self.close='30517.7'
127.0.0.1 - - [30/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 00:20:09,197:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30541.5', self.close='30517.7'
2023-06-30 00:20:09,336:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17421  20230629   233000    233959  1688053199  30512.4    30526
17422  20230629   234000    234959  1688053799    30527  30503.3
17423  20230629   235000    235959  1688054399  30503.3  30468.3
17424  20230630   000000    000959  1688054999  30468.2  30541.4
17425  20230630   001000    001959  1688055599  30541.5  30517.7
2023-06-30 00:20:09,337:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

127.0.0.1 - - [30/Jun/2023 00:00:04] "POST / HTTP/1.1" 200 -
2023-06-30 00:00:04,232:INFO:testStrategy:main.py:308:handleOrderFilled:2217133: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42497F1688054403676I0L2', 'symbol': 'BTCUSDT', 'gatewayorderid': 1688054404062669, 'quantity': '37.981', 'price': '30468.2', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1688054402743, 'updatetime': 1688054404062, 'tradetype': 'usdt', 'selfid': 42497, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1688054404062, 'clientorderid': '42497F1688054403676I0L2', 'price': '30468.2', 'quantity': '37.981', 'commission': '1157.2127042', 'commissionasset': 'USDT', 'tradetime': 1688054404062, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1688054404062}], 'gatetype': 'simulator', 'handletime': 0}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6707 

self.closeSec=1688054999, self.tradeDate='20230630', self.openTime='000000', self.closeTime='000959', self.symbol='BTCUSDT', self.open='30468.2', self.close='30541.4'
127.0.0.1 - - [30/Jun/2023 00:10:01] "POST / HTTP/1.1" 200 -
2023-06-30 00:10:01,137:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688054999, self.tradeDate='20230630', self.openTime='000000', self.closeTime='000959',self.symbol='BTCUSDT',self.open='30468.2', self.close='30541.4'
2023-06-30 00:10:01,171:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12236  20230629   232000    232959  1688052599  30503.3  30512.3
12237  20230629   233000    233959  1688053199  30512.4    30526
12238  20230629   234000    234959  1688053799    30527  30503.3
12239  20230629   235000    235959  1688054399  30503.3  30468.3
12240  20230630   000000    000959  1688054999  30468.2  30541.4
2023-06-30 00:10:01,171:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6708 

self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001000', self.closeTime='001959', self.symbol='BTCUSDT', self.open='30541.5', self.close='30517.7'
127.0.0.1 - - [30/Jun/2023 00:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 00:20:08,712:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001000', self.closeTime='001959',self.symbol='BTCUSDT',self.open='30541.5', self.close='30517.7'
2023-06-30 00:20:09,067:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12237  20230629   233000    233959  1688053199  30512.4    30526
12238  20230629   234000    234959  1688053799    30527  30503.3
12239  20230629   235000    235959  1688054399  30503.3  30468.3
12240  20230630   000000    000959  1688054999  30468.2  30541.4
12241  20230630   001000    001959  1688055599  30541.5  30517.7
2023-06-30 00:20:09,067:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13408
self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001500', self.closeTime='001959', self.symbol='BTCUSDT', self.open=30518.4, self.close=30517.7, self.high=30521.2, self.low=30489.0, self.vol=748.963, self.amt=22844047.4971 
127.0.0.1 - - [30/Jun/2023 00:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 00:20:07,307:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5759  20230629   235500    235959  ...         0.0        0.0       0
5760  20230630   000000    000459  ...         0.0        0.0       0
5761  20230630   000500    000959  ...         0.0        0.0       0
5762  20230630   001000    001459  ...         0.0        0.0       0
5763  20230630   001500    001959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 00:20:07,328:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688055599, self.tradeDate='20230630', self.openTime='001500', self.closeTime='001959',self.symbol='BTCUSDT',self.open=30518.4, self.close=30517.7, self.high=30521.2, self.low=30489.0, self.vol=748.963, self.amt=22844047.4971, ukdf['pct'].iloc[-1]=-1e-05 , ukdf['amount'].iloc[-1]=22844047.4971, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5763, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136396.6084', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30516.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13409
self.closeSec=1688055899, self.tradeDate='20230630', self.openTime='002000', self.closeTime='002459', self.symbol='BTCUSDT', self.open=30517.8, self.close=30483.1, self.high=30536.5, self.low=30480.6, self.vol=831.611, self.amt=25369004.2401 
127.0.0.1 - - [30/Jun/2023 00:25:00] "POST / HTTP/1.1" 200 -
2023-06-30 00:25:00,822:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5760  20230630   000000    000459  ...         0.0        0.0       0
5761  20230630   000500    000959  ...         0.0        0.0       0
5762  20230630   001000    001459  ...         0.0        0.0       0
5763  20230630   001500    001959  ...         0.0        0.0       0
5764  20230630   002000    002459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 00:25:00,822:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688055899, self.tradeDate='20230630', self.openTime='002000', self.closeTime='002459',self.symbol='BTCUSDT',self.open=30517.8, self.close=30483.1, self.high=30536.5, self.low=30480.6, self.vol=831.611, self.amt=25369004.2401, ukdf['pct'].iloc[-1]=-0.001134 , ukdf['amount'].iloc[-1]=25369004.2401, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5764, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '135254.45451074999', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30485.64816539', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

723  20230629   120000    155959  1688025599  ...    723  0.380362 -0.491571     NaN
724  20230629   160000    195959  1688039999  ...    724  0.292563 -0.741058    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '2471.6352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30660.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=279
self.closeSec=1688054399, self.tradeDate='20230629', self.openTime='200000', self.closeTime='235959', self.symbol='BTCUSDT', self.open=30660.7, self.close=30468.3, self.high=30837.0, self.low=30380.0, self.vol=113767.896, self.amt=3482064627.14469 
2023-06-30 00:00:01,683:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688054399, self.tradeDate='20230629', self.openTime='200000', self.closeTime='235959',self.symbol='BTCUSDT',self.open=30660.7, self.close=30468.3, self.high=30837.0, self.low=30380.0, self.vol=113767.896, self.amt=3482064627.14469 
127.0.0.1 - - [30/Jun/2023 00:00:01] "POST / HTTP/1.1" 200 -
2023-06-30 00:00:01,727:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
721  20230629   040000    075959  ...   40288.685  1.211925e+09 -0.000469
722  20230629   080000    115959  ...   34206.224  1.030926e+09  0.003193
723  20230629   120000    155959  ...   37925.711  1.148028e+09  0.005689
724  20230629   160000    195959  ...   98223.108  3.002113e+09  0.010773
725  20230629   200000    235959  ...  113767.896  3.482065e+09 -0.006275

[5 rows x 11 columns]
2023-06-30 00:00:03,203:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
721  20230629   040000    075959  1687996799  ...    721  0.331663 -0.588163     NaN
722  20230629   080000    115959  1688011199  ...    722  0.383382 -0.466988     NaN
723  20230629   120000    155959  1688025599  ...    723  0.380362 -0.491571     NaN
724  20230629   160000    195959  1688039999  ...    724  0.292563 -0.741058    -1.0
725  20230629   200000    235959  1688054399  ...    725  0.355426 -0.588082     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '12720.3984', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30468.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


