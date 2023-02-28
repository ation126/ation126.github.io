# 20230228 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26716
self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23475.4, self.close=23496.1, self.high=23503.0, self.low=23462.0, self.vol=955.512, self.amt=22436199.7056 
127.0.0.1 - - [28/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-28 08:20:01,672:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230228   075500    075959  ...         0.0        0.0       0
5856  20230228   080000    080459  ...         0.0        0.0       0
5857  20230228   080500    080959  ...         0.0        0.0       0
5858  20230228   081000    081459  ...         0.0        0.0       0
5859  20230228   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 08:20:01,673:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23475.4, self.close=23496.1, self.high=23503.0, self.low=23462.0, self.vol=955.512, self.amt=22436199.7056, ukdf['pct'].iloc[-1]=0.000882 , ukdf['amount'].iloc[-1]=22436199.7056, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-419235.27595565504', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23496.11859804', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=26717
self.closeSec=1677543899, self.tradeDate='20230228', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23496.0, self.close=23515.2, self.high=23539.0, self.low=23496.0, self.vol=1912.763, self.amt=44984560.546 
127.0.0.1 - - [28/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-28 08:25:01,569:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230228   080000    080459  ...         0.0        0.0       0
5857  20230228   080500    080959  ...         0.0        0.0       0
5858  20230228   081000    081459  ...         0.0        0.0       0
5859  20230228   081500    081959  ...         0.0        0.0       0
5860  20230228   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 08:25:01,569:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677543899, self.tradeDate='20230228', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23496.0, self.close=23515.2, self.high=23539.0, self.low=23496.0, self.vol=1912.763, self.amt=44984560.546, ukdf['pct'].iloc[-1]=0.000813 , ukdf['amount'].iloc[-1]=44984560.546, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-420478.3437137208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23516.77579955', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.48810412795253627, self.count=27282 

self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23475.4, self.close=23496.1, self.high=23503.0, self.low=23462.0 
2023-02-28 08:20:01,500:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23475.4, self.close=23496.1, self.high=23503.0, self.low=23462.0   
2023-02-28 08:20:01,530:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230228   075500    075959  1677542399  ...  23474.0 -0.000285   1535    5
1536  20230228   080000    080459  1677542699  ...  23460.0  0.000703   1536    0
1537  20230228   080500    080959  1677542999  ...  23462.0 -0.000332   1537    1
1538  20230228   081000    081459  1677543299  ...  23465.3 -0.000566   1538    2
1539  20230228   081500    081959  1677543599  ...  23462.0  0.000882   1539    3

[5 rows x 11 columns]
2023-02-28 08:20:01,530:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=36, self.factor=0.48810412795253627, self.count=27283 

self.closeSec=1677543899, self.tradeDate='20230228', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23496.0, self.close=23515.2, self.high=23539.0, self.low=23496.0 
2023-02-28 08:25:01,488:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677543899, self.tradeDate='20230228', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23496.0, self.close=23515.2, self.high=23539.0, self.low=23496.0   
2023-02-28 08:25:01,516:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230228   080000    080459  1677542699  ...  23460.0  0.000703   1536    0
1537  20230228   080500    080959  1677542999  ...  23462.0 -0.000332   1537    1
1538  20230228   081000    081459  1677543299  ...  23465.3 -0.000566   1538    2
1539  20230228   081500    081959  1677543599  ...  23462.0  0.000882   1539    3
1540  20230228   082000    082459  1677543899  ...  23496.0  0.000813   1540    4

[5 rows x 11 columns]
2023-02-28 08:25:01,516:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-02-28 08:00:34,796:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230228    052959  23310.6  ...  49.166667  0.493933  0.583836
5771  20230228    055959  23339.8  ...  49.583333  0.500080  0.587955
5772  20230228    062959  23371.5  ...  49.166667  0.499551  0.592025
5773  20230228    065959  23368.8  ...  49.166667  0.519049  0.587373
5774  20230228    072959  23470.2  ...  49.166667  0.521320  0.582023

[5 rows x 33 columns]
0.5286506469500925
acc is : 0.5286506469500925
2023-02-28 08:00:34,967:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.513688  0.486312       1  ...  0.954135  -1.0    0.0  0.940473
537     0  0.514439  0.485561       0  ...  0.954245  -1.0    0.0  0.940364
538     0  0.510930  0.489070       1  ...  0.950104  -1.0    0.0  0.944444
539     0  0.538893  0.461107       1  ...  0.949614  -1.0    0.0  0.944931
540     0  0.518891  0.481109       0  ...  0.949707  -1.0    0.0  0.944839

[5 rows x 10 columns]
2023-02-28 08:00:35,001:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512986  0.487014       1  ...  0.934942  -1.0    0.0  0.931269
46     0  0.514280  0.485720       0  ...  0.945754  -1.0    0.0  0.940300
47     0  0.510249  0.489751       1  ...  0.942922  -1.0    0.0  0.942374
48     0  0.538842  0.461158       1  ...  0.949614  -1.0    0.0  0.944931
49     0  0.518891  0.481109       0  ...  0.949707  -1.0    0.0  0.944839

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.752', 'enterprice': '23379.5', 'countrevence': '0', 'unrealprofit': '-2859.23477611728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23466.79954739', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230228   075000    075959  1677542399  23497.4    23480 -0.000741
2023-02-28 08:00:02,192:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13640 

self.closeSec=1677542999, self.tradeDate='20230228', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23480', self.close='23488.7'
2023-02-28 08:10:01,609:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677542999, self.tradeDate='20230228', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23480', self.close='23488.7'
2023-02-28 08:10:01,629:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230228   072000    072959  1677540599  23494.8  23482.3 -0.000536
621  20230228   073000    073959  1677541199  23481.7  23488.2  0.000251
622  20230228   074000    074959  1677541799  23488.2  23497.4  0.000392
623  20230228   075000    075959  1677542399  23497.4    23480 -0.000741
624  20230228   080000    080959  1677542999    23480  23488.7  0.000371
2023-02-28 08:10:01,633:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13641 

self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23488.8', self.close='23496'
2023-02-28 08:20:01,585:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23488.8', self.close='23496'
127.0.0.1 - - [28/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-28 08:20:01,657:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230228   073000    073959  1677541199  23481.7  23488.2  0.000251
622  20230228   074000    074959  1677541799  23488.2  23497.4  0.000392
623  20230228   075000    075959  1677542399  23497.4    23480 -0.000741
624  20230228   080000    080959  1677542999    23480  23488.7  0.000371
625  20230228   081000    081959  1677543599  23488.8    23496  0.000311
2023-02-28 08:20:01,657:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230228   075000    075959  1677542399  23497.4    23480
2023-02-28 08:00:02,246:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13641 

self.closeSec=1677542999, self.tradeDate='20230228', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23480', self.close='23488.7'
2023-02-28 08:10:01,618:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677542999, self.tradeDate='20230228', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23480', self.close='23488.7'
2023-02-28 08:10:01,640:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230228   072000    072959  1677540599  23494.8  23482.3
17469  20230228   073000    073959  1677541199  23481.7  23488.2
17470  20230228   074000    074959  1677541799  23488.2  23497.4
17471  20230228   075000    075959  1677542399  23497.4    23480
17472  20230228   080000    080959  1677542999    23480  23488.7
2023-02-28 08:10:01,640:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13642 

self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23488.8', self.close='23496'
127.0.0.1 - - [28/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-02-28 08:20:01,608:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23488.8', self.close='23496'
2023-02-28 08:20:01,627:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230228   073000    073959  1677541199  23481.7  23488.2
17470  20230228   074000    074959  1677541799  23488.2  23497.4
17471  20230228   075000    075959  1677542399  23497.4    23480
17472  20230228   080000    080959  1677542999    23480  23488.7
17473  20230228   081000    081959  1677543599  23488.8    23496
2023-02-28 08:20:01,627:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230228   075000    075959  1677542399  23497.4    23480
2023-02-28 08:00:02,233:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/Feb/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13641 

self.closeSec=1677542999, self.tradeDate='20230228', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23480', self.close='23488.7'
2023-02-28 08:10:01,639:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677542999, self.tradeDate='20230228', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23480', self.close='23488.7'
2023-02-28 08:10:01,663:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230228   072000    072959  1677540599  23494.8  23482.3
12141  20230228   073000    073959  1677541199  23481.7  23488.2
12142  20230228   074000    074959  1677541799  23488.2  23497.4
12143  20230228   075000    075959  1677542399  23497.4    23480
12144  20230228   080000    080959  1677542999    23480  23488.7
2023-02-28 08:10:01,663:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--: 127.0.0.1 - - [28/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13642 

self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23488.8', self.close='23496'
2023-02-28 08:20:01,629:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23488.8', self.close='23496'
2023-02-28 08:20:01,658:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230228   073000    073959  1677541199  23481.7  23488.2
12142  20230228   074000    074959  1677541799  23488.2  23497.4
12143  20230228   075000    075959  1677542399  23497.4    23480
12144  20230228   080000    080959  1677542999    23480  23488.7
12145  20230228   081000    081959  1677543599  23488.8    23496
2023-02-28 08:20:01,658:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [28/Feb/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22714
self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23475.4, self.close=23496.1, self.high=23503.0, self.low=23462.0, self.vol=955.512, self.amt=22436199.7056 
2023-02-28 08:20:01,547:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230228   075500    075959  ...         0.0        0.0       0
5856  20230228   080000    080459  ...         0.0        0.0       0
5857  20230228   080500    080959  ...         0.0        0.0       0
5858  20230228   081000    081459  ...         0.0        0.0       0
5859  20230228   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 08:20:01,552:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677543599, self.tradeDate='20230228', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23475.4, self.close=23496.1, self.high=23503.0, self.low=23462.0, self.vol=955.512, self.amt=22436199.7056, ukdf['pct'].iloc[-1]=0.000882 , ukdf['amount'].iloc[-1]=22436199.7056, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=22715
self.closeSec=1677543899, self.tradeDate='20230228', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23496.0, self.close=23515.2, self.high=23539.0, self.low=23496.0, self.vol=1912.763, self.amt=44984560.546 
127.0.0.1 - - [28/Feb/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-02-28 08:25:01,566:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230228   080000    080459  ...         0.0        0.0       0
5857  20230228   080500    080959  ...         0.0        0.0       0
5858  20230228   081000    081459  ...         0.0        0.0       0
5859  20230228   081500    081959  ...         0.0        0.0       0
5860  20230228   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-02-28 08:25:01,566:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677543899, self.tradeDate='20230228', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23496.0, self.close=23515.2, self.high=23539.0, self.low=23496.0, self.vol=1912.763, self.amt=44984560.546, ukdf['pct'].iloc[-1]=0.000813 , ukdf['amount'].iloc[-1]=44984560.546, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230227   200000    235959  1677513599  ...    719  0.854884  0.495060     NaN
720  20230228   000000    035959  1677527999  ...    720  0.774757  0.304801     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '6469.72391495397', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23262.18732343', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
127.0.0.1 - - [28/Feb/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=973731.3691248, self.flagDict['side']='buy', self.tradeCount=22, self.count=568
self.closeSec=1677542399, self.tradeDate='20230228', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23262.5, self.close=23480.0, self.high=23580.0, self.low=23088.0, self.vol=76820.163, self.amt=1793671499.61513 
2023-02-28 08:00:02,076:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677542399, self.tradeDate='20230228', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23262.5, self.close=23480.0, self.high=23580.0, self.low=23088.0, self.vol=76820.163, self.amt=1793671499.61513 
2023-02-28 08:00:02,122:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230227   120000    155959  ...   53778.498  1.260110e+09 -0.005518
718  20230227   160000    195959  ...   46822.503  1.094781e+09  0.000380
719  20230227   200000    235959  ...  184984.884  4.377125e+09  0.005397
720  20230228   000000    035959  ...  166667.763  3.885504e+09 -0.012057
721  20230228   040000    075959  ...   76820.163  1.793671e+09  0.009350

[5 rows x 11 columns]
2023-02-28 08:00:04,710:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230227   120000    155959  1677484799  ...    717  0.893048  0.580876     NaN
718  20230227   160000    195959  1677499199  ...    718  0.934377  0.683758     1.0
719  20230227   200000    235959  1677513599  ...    719  0.854884  0.495060     NaN
720  20230228   000000    035959  1677527999  ...    720  0.774757  0.304801     NaN
721  20230228   040000    075959  1677542399  ...    721  0.716158  0.166024     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.179', 'enterprice': '23108.8', 'countrevence': '0', 'unrealprofit': '15698.13196131894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23480.97885586', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


