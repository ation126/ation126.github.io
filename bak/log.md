# 20230524 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2848
self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27194.7, self.close=27181.7, self.high=27194.7, self.low=27167.3, self.vol=771.129, self.amt=20957612.3505 
127.0.0.1 - - [24/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 08:20:06,246:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230524   075500    075959  ...    0.156066   0.295048       0
5856  20230524   080000    080459  ...    0.155890   0.294953       0
5857  20230524   080500    080959  ...    0.155720   0.294865       0
5858  20230524   081000    081459  ...    0.155551   0.294780       0
5859  20230524   081500    081959  ...    0.155382   0.294696       0

[5 rows x 18 columns]
2023-05-24 08:20:06,266:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27194.7, self.close=27181.7, self.high=27194.7, self.low=27167.3, self.vol=771.129, self.amt=20957612.3505, ukdf['pct'].iloc[-1]=-0.000478 , ukdf['amount'].iloc[-1]=20957612.3505, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.15538225338375228, signal=0, value_std=0.29469552376753483 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4411.7568', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27181.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [24/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2849
self.closeSec=1684887899, self.tradeDate='20230524', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27181.6, self.close=27197.2, self.high=27197.2, self.low=27181.6, self.vol=511.737, self.amt=13913947.2914 
2023-05-24 08:25:00,931:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230524   080000    080459  ...    0.155890   0.294953       0
5857  20230524   080500    080959  ...    0.155720   0.294865       0
5858  20230524   081000    081459  ...    0.155551   0.294780       0
5859  20230524   081500    081959  ...    0.155382   0.294696       0
5860  20230524   082000    082459  ...    0.155213   0.294609       0

[5 rows x 18 columns]
2023-05-24 08:25:00,932:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684887899, self.tradeDate='20230524', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27181.6, self.close=27197.2, self.high=27197.2, self.low=27181.6, self.vol=511.737, self.amt=13913947.2914, ukdf['pct'].iloc[-1]=0.00057 , ukdf['amount'].iloc[-1]=13913947.2914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.15521251798498473, signal=0, value_std=0.29460898539564917 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4627.6098', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27197.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27194.7, self.close=27181.7, self.high=27194.7, self.low=27167.3 
127.0.0.1 - - [24/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 08:20:04,247:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27194.7, self.close=27181.7, self.high=27194.7, self.low=27167.3   
2023-05-24 08:20:05,307:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230524   075500    075959  1684886399  ...  27208.2 -0.000081   1535    5
1536  20230524   080000    080459  1684886699  ...  27192.7 -0.000500   1536    0
1537  20230524   080500    080959  1684886999  ...  27187.1  0.000221   1537    1
1538  20230524   081000    081459  1684887299  ...  27190.0 -0.000279   1538    2
1539  20230524   081500    081959  1684887599  ...  27167.3 -0.000478   1539    3

[5 rows x 11 columns]
2023-05-24 08:20:05,318:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=27, self.factor=0.4309145612616123, self.count=2851 

self.closeSec=1684887899, self.tradeDate='20230524', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27181.6, self.close=27197.2, self.high=27197.2, self.low=27181.6 
2023-05-24 08:25:00,809:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684887899, self.tradeDate='20230524', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27181.6, self.close=27197.2, self.high=27197.2, self.low=27181.6   
2023-05-24 08:25:00,907:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230524   080000    080459  1684886699  ...  27192.7 -0.000500   1536    0
1537  20230524   080500    080959  1684886999  ...  27187.1  0.000221   1537    1
1538  20230524   081000    081459  1684887299  ...  27190.0 -0.000279   1538    2
1539  20230524   081500    081959  1684887599  ...  27167.3 -0.000478   1539    3
1540  20230524   082000    082459  1684887899  ...  27181.6  0.000570   1540    4

[5 rows x 11 columns]
2023-05-24 08:25:00,907:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-24 08:00:33,606:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230524    052959  27206.0  ...  49.166667  0.533549  0.398282
5771  20230524    055959  27194.5  ...  48.750000  0.531342  0.413322
5772  20230524    062959  27187.2  ...  49.166667  0.531946  0.428549
5773  20230524    065959  27189.6  ...  48.750000  0.531819  0.450392
5774  20230524    072959  27189.0  ...  49.166667  0.545450  0.463450

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-05-24 08:00:33,761:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.499319  0.500681       0  ...  0.945300   1.0    0.0  1.032121
537     1  0.495185  0.504815       1  ...  0.945377   1.0    0.0  1.032204
538     1  0.496217  0.503783       0  ...  0.945363   1.0    0.0  1.032189
539     1  0.497000  0.503000       1  ...  0.947074   1.0    0.0  1.034057
540     0  0.504868  0.495132       0  ...  0.946086   1.0    0.0  1.032979

[5 rows x 10 columns]
2023-05-24 08:00:33,793:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499282  0.500718       0  ...  0.945300   1.0    0.0  1.033435
46     1  0.495180  0.504820       1  ...  0.945377   1.0    0.0  1.032212
47     1  0.496279  0.503721       0  ...  0.945363   1.0    0.0  1.034534
48     1  0.497000  0.503000       1  ...  0.947074   1.0    0.0  1.034057
49     0  0.504868  0.495132       0  ...  0.946086   1.0    0.0  1.032979

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.741', 'enterprice': '27035', 'countrevence': '0', 'unrealprofit': '4633.38587199631', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27208.26898291', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230524   075000    075959  1684886399  27208.5  27209.9  0.000051
2023-05-24 08:00:02,454:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1424 

self.closeSec=1684886999, self.tradeDate='20230524', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27209.9', self.close='27202.3'
2023-05-24 08:10:01,175:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684886999, self.tradeDate='20230524', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27209.9', self.close='27202.3'
2023-05-24 08:10:01,227:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230524   072000    072959  1684884599  27213.8  27238.3  0.000900
621  20230524   073000    073959  1684885199  27238.3    27211 -0.001002
622  20230524   074000    074959  1684885799    27211  27208.5 -0.000092
623  20230524   075000    075959  1684886399  27208.5  27209.9  0.000051
624  20230524   080000    080959  1684886999  27209.9  27202.3 -0.000279
2023-05-24 08:10:01,229:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1425 

self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27202.2', self.close='27181.7'
127.0.0.1 - - [24/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 08:20:05,776:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27202.2', self.close='27181.7'
2023-05-24 08:20:06,426:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230524   073000    073959  1684885199  27238.3    27211 -0.001002
622  20230524   074000    074959  1684885799    27211  27208.5 -0.000092
623  20230524   075000    075959  1684886399  27208.5  27209.9  0.000051
624  20230524   080000    080959  1684886999  27209.9  27202.3 -0.000279
625  20230524   081000    081959  1684887599  27202.2  27181.7 -0.000757
2023-05-24 08:20:06,427:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230524   075000    075959  1684886399  27208.5  27209.9
2023-05-24 08:00:02,434:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1427 

self.closeSec=1684886999, self.tradeDate='20230524', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27209.9', self.close='27202.3'
2023-05-24 08:10:01,186:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684886999, self.tradeDate='20230524', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27209.9', self.close='27202.3'
127.0.0.1 - - [24/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-24 08:10:01,219:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230524   072000    072959  1684884599  27213.8  27238.3
17469  20230524   073000    073959  1684885199  27238.3    27211
17470  20230524   074000    074959  1684885799    27211  27208.5
17471  20230524   075000    075959  1684886399  27208.5  27209.9
17472  20230524   080000    080959  1684886999  27209.9  27202.3
2023-05-24 08:10:01,220:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1428 

self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27202.2', self.close='27181.7'
127.0.0.1 - - [24/May/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-05-24 08:20:07,431:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27202.2', self.close='27181.7'
2023-05-24 08:20:07,532:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230524   073000    073959  1684885199  27238.3    27211
17470  20230524   074000    074959  1684885799    27211  27208.5
17471  20230524   075000    075959  1684886399  27208.5  27209.9
17472  20230524   080000    080959  1684886999  27209.9  27202.3
17473  20230524   081000    081959  1684887599  27202.2  27181.7
2023-05-24 08:20:07,533:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230524   075000    075959  1684886399  27208.5  27209.9
2023-05-24 08:00:02,426:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [24/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1427 

self.closeSec=1684886999, self.tradeDate='20230524', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27209.9', self.close='27202.3'
2023-05-24 08:10:01,167:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684886999, self.tradeDate='20230524', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27209.9', self.close='27202.3'
2023-05-24 08:10:01,196:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230524   072000    072959  1684884599  27213.8  27238.3
12141  20230524   073000    073959  1684885199  27238.3    27211
12142  20230524   074000    074959  1684885799    27211  27208.5
12143  20230524   075000    075959  1684886399  27208.5  27209.9
12144  20230524   080000    080959  1684886999  27209.9  27202.3
2023-05-24 08:10:01,196:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1428 

self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27202.2', self.close='27181.7'
127.0.0.1 - - [24/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-24 08:20:07,149:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27202.2', self.close='27181.7'
2023-05-24 08:20:07,362:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230524   073000    073959  1684885199  27238.3    27211
12142  20230524   074000    074959  1684885799    27211  27208.5
12143  20230524   075000    075959  1684886399  27208.5  27209.9
12144  20230524   080000    080959  1684886999  27209.9  27202.3
12145  20230524   081000    081959  1684887599  27202.2  27181.7
2023-05-24 08:20:07,366:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2848
self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27194.7, self.close=27181.7, self.high=27194.7, self.low=27167.3, self.vol=771.129, self.amt=20957612.3505 
127.0.0.1 - - [24/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-24 08:20:06,208:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230524   075500    075959  ...         0.0        0.0       0
5856  20230524   080000    080459  ...         0.0        0.0       0
5857  20230524   080500    080959  ...         0.0        0.0       0
5858  20230524   081000    081459  ...         0.0        0.0       0
5859  20230524   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-24 08:20:06,229:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684887599, self.tradeDate='20230524', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27194.7, self.close=27181.7, self.high=27194.7, self.low=27167.3, self.vol=771.129, self.amt=20957612.3505, ukdf['pct'].iloc[-1]=-0.000478 , ukdf['amount'].iloc[-1]=20957612.3505, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '12546.2298', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27181.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [24/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2849
self.closeSec=1684887899, self.tradeDate='20230524', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27181.6, self.close=27197.2, self.high=27197.2, self.low=27181.6, self.vol=511.737, self.amt=13913947.2914 
2023-05-24 08:25:00,935:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230524   080000    080459  ...         0.0        0.0       0
5857  20230524   080500    080959  ...         0.0        0.0       0
5858  20230524   081000    081459  ...         0.0        0.0       0
5859  20230524   081500    081959  ...         0.0        0.0       0
5860  20230524   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-24 08:25:00,936:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684887899, self.tradeDate='20230524', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27181.6, self.close=27197.2, self.high=27197.2, self.low=27181.6, self.vol=511.737, self.amt=13913947.2914, ukdf['pct'].iloc[-1]=0.00057 , ukdf['amount'].iloc[-1]=13913947.2914, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '13118.2012', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27197.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230523   200000    235959  1684857599  ...    719  0.307050 -0.510986     NaN
720  20230524   000000    035959  1684871999  ...    720  0.492751  0.349268     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-5479.6587', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27176.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=59
self.closeSec=1684886399, self.tradeDate='20230524', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27171.7, self.close=27209.9, self.high=27244.0, self.low=27139.0, self.vol=21367.419, self.amt=581135649.236 
2023-05-24 08:00:01,970:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684886399, self.tradeDate='20230524', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27171.7, self.close=27209.9, self.high=27244.0, self.low=27139.0, self.vol=21367.419, self.amt=581135649.236 
127.0.0.1 - - [24/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-05-24 08:00:02,020:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230523   120000    155959  ...  83809.328  2.292565e+09 -0.002150
718  20230523   160000    195959  ...  32695.377  8.924195e+08  0.001139
719  20230523   200000    235959  ...  63502.505  1.732442e+09 -0.000593
720  20230524   000000    035959  ...  55692.994  1.514264e+09 -0.005093
721  20230524   040000    075959  ...  21367.419  5.811356e+08  0.001410

[5 rows x 11 columns]
2023-05-24 08:00:03,963:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230523   120000    155959  1684828799  ...    717  0.225133 -0.915867    -1.0
718  20230523   160000    195959  1684843199  ...    718  0.255594 -0.760390    -1.0
719  20230523   200000    235959  1684857599  ...    719  0.307050 -0.510986     NaN
720  20230524   000000    035959  1684871999  ...    720  0.492751  0.349268     NaN
721  20230524   040000    075959  1684886399  ...    721  0.467182  0.243154     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-7197.88611471225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27210.13192525', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


