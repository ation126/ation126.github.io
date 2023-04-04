# 20230404 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36796
self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27745.5, self.close=27816.1, self.high=27817.0, self.low=27741.6, self.vol=969.827, self.amt=26942042.6747 
127.0.0.1 - - [04/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 08:20:09,252:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230404   075500    075959  ...         0.0        0.0       0
5856  20230404   080000    080459  ...         0.0        0.0       0
5857  20230404   080500    080959  ...         0.0        0.0       0
5858  20230404   081000    081459  ...         0.0        0.0       0
5859  20230404   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 08:20:09,272:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27745.5, self.close=27816.1, self.high=27817.0, self.low=27741.6, self.vol=969.827, self.amt=26942042.6747, ukdf['pct'].iloc[-1]=0.002375 , ukdf['amount'].iloc[-1]=26942042.6747, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-679803.84730926784', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27826.22647084', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36797
self.closeSec=1680567899, self.tradeDate='20230404', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27816.1, self.close=27816.9, self.high=27857.9, self.low=27816.0, self.vol=1509.048, self.amt=42009326.8752 
127.0.0.1 - - [04/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-04 08:25:01,555:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230404   080000    080459  ...         0.0        0.0       0
5857  20230404   080500    080959  ...         0.0        0.0       0
5858  20230404   081000    081459  ...         0.0        0.0       0
5859  20230404   081500    081959  ...         0.0        0.0       0
5860  20230404   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 08:25:01,556:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680567899, self.tradeDate='20230404', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27816.1, self.close=27816.9, self.high=27857.9, self.low=27816.0, self.vol=1509.048, self.amt=42009326.8752, ukdf['pct'].iloc[-1]=2.9e-05 , ukdf['amount'].iloc[-1]=42009326.8752, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-679449.72810910128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27820.34174603', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27745.5, self.close=27816.1, self.high=27817.0, self.low=27741.6 
127.0.0.1 - - [04/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-04 08:20:06,501:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27745.5, self.close=27816.1, self.high=27817.0, self.low=27741.6   
2023-04-04 08:20:07,701:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230404   075500    075959  1680566399  ...  27755.6  0.000846   1535    5
1536  20230404   080000    080459  1680566699  ...  27736.7 -0.001454   1536    0
1537  20230404   080500    080959  1680566999  ...  27740.0  0.002072   1537    1
1538  20230404   081000    081459  1680567299  ...  27750.0 -0.001906   1538    2
1539  20230404   081500    081959  1680567599  ...  27741.6  0.002375   1539    3

[5 rows x 11 columns]
2023-04-04 08:20:07,701:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [04/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=26, self.factor=0.5758965496165115, self.count=37363 

self.closeSec=1680567899, self.tradeDate='20230404', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27816.1, self.close=27816.9, self.high=27857.9, self.low=27816.0 
2023-04-04 08:25:01,513:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680567899, self.tradeDate='20230404', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27816.1, self.close=27816.9, self.high=27857.9, self.low=27816.0   
2023-04-04 08:25:01,593:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230404   080000    080459  1680566699  ...  27736.7 -0.001454   1536    0
1537  20230404   080500    080959  1680566999  ...  27740.0  0.002072   1537    1
1538  20230404   081000    081459  1680567299  ...  27750.0 -0.001906   1538    2
1539  20230404   081500    081959  1680567599  ...  27741.6  0.002375   1539    3
1540  20230404   082000    082459  1680567899  ...  27816.0  0.000029   1540    4

[5 rows x 11 columns]
2023-04-04 08:25:01,593:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-04 08:00:34,166:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230404    052959  27569.3  ...  50.833333  0.408323  0.539670
5771  20230404    055959  27509.4  ...  51.250000  0.440695  0.544498
5772  20230404    062959  27699.1  ...  51.250000  0.469885  0.539930
5773  20230404    065959  27886.0  ...  50.833333  0.457355  0.540335
5774  20230404    072959  27789.7  ...  50.833333  0.467728  0.537369

[5 rows x 33 columns]
0.5508317929759704
acc is : 0.5508317929759704
2023-04-04 08:00:34,331:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.465292  0.534708       1  ...  0.850112   1.0    0.0  0.982025
537     0  0.522759  0.477241       1  ...  0.855851   1.0    0.0  0.988655
538     0  0.534329  0.465671       0  ...  0.852899   1.0    0.0  0.985244
539     0  0.506021  0.493979       1  ...  0.855013   1.0    0.0  0.987687
540     0  0.548527  0.451473       0  ...  0.852785   1.0    0.0  0.985113

[5 rows x 10 columns]
2023-04-04 08:00:34,366:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.466107  0.533893       1  ...  0.829617  -1.0    0.0  0.969361
46     0  0.524125  0.475875       1  ...  0.826751  -1.0    0.0  0.979140
47     0  0.534611  0.465389       0  ...  0.830175  -1.0    0.0  0.976448
48     0  0.506108  0.493892       1  ...  0.855013   1.0    0.0  0.987687
49     0  0.548527  0.451473       0  ...  0.852785   1.0    0.0  0.985113

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230404   075000    075959  1680566399  27822.4  27786.1 -0.001308
2023-04-04 08:00:02,098:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18680 

self.closeSec=1680566999, self.tradeDate='20230404', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27786.1', self.close='27803.2'
2023-04-04 08:10:01,609:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680566999, self.tradeDate='20230404', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27786.1', self.close='27803.2'
2023-04-04 08:10:01,669:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230404   072000    072959  1680564599  27888.3  27858.7 -0.001061
621  20230404   073000    073959  1680565199  27858.7    27822 -0.001317
622  20230404   074000    074959  1680565799    27822  27822.5  0.000018
623  20230404   075000    075959  1680566399  27822.4  27786.1 -0.001308
624  20230404   080000    080959  1680566999  27786.1  27803.2  0.000615
2023-04-04 08:10:01,669:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18681 

self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27803.3', self.close='27816.1'
127.0.0.1 - - [04/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 08:20:07,730:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27803.3', self.close='27816.1'
2023-04-04 08:20:08,630:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230404   073000    073959  1680565199  27858.7    27822 -0.001317
622  20230404   074000    074959  1680565799    27822  27822.5  0.000018
623  20230404   075000    075959  1680566399  27822.4  27786.1 -0.001308
624  20230404   080000    080959  1680566999  27786.1  27803.2  0.000615
625  20230404   081000    081959  1680567599  27803.3  27816.1  0.000464
2023-04-04 08:20:08,630:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230404   075000    075959  1680566399  27822.4  27786.1
2023-04-04 08:00:02,053:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [04/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18681 

self.closeSec=1680566999, self.tradeDate='20230404', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27786.1', self.close='27803.2'
2023-04-04 08:10:01,635:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680566999, self.tradeDate='20230404', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27786.1', self.close='27803.2'
2023-04-04 08:10:01,681:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230404   072000    072959  1680564599  27888.3  27858.7
17469  20230404   073000    073959  1680565199  27858.7    27822
17470  20230404   074000    074959  1680565799    27822  27822.5
17471  20230404   075000    075959  1680566399  27822.4  27786.1
17472  20230404   080000    080959  1680566999  27786.1  27803.2
2023-04-04 08:10:01,681:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18682 

self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27803.3', self.close='27816.1'
127.0.0.1 - - [04/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 08:20:10,893:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27803.3', self.close='27816.1'
2023-04-04 08:20:11,034:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230404   073000    073959  1680565199  27858.7    27822
17470  20230404   074000    074959  1680565799    27822  27822.5
17471  20230404   075000    075959  1680566399  27822.4  27786.1
17472  20230404   080000    080959  1680566999  27786.1  27803.2
17473  20230404   081000    081959  1680567599  27803.3  27816.1
2023-04-04 08:20:11,034:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230404   075000    075959  1680566399  27822.4  27786.1
2023-04-04 08:00:02,117:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [04/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18681 

self.closeSec=1680566999, self.tradeDate='20230404', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27786.1', self.close='27803.2'
2023-04-04 08:10:01,619:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680566999, self.tradeDate='20230404', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27786.1', self.close='27803.2'
2023-04-04 08:10:01,649:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230404   072000    072959  1680564599  27888.3  27858.7
12141  20230404   073000    073959  1680565199  27858.7    27822
12142  20230404   074000    074959  1680565799    27822  27822.5
12143  20230404   075000    075959  1680566399  27822.4  27786.1
12144  20230404   080000    080959  1680566999  27786.1  27803.2
2023-04-04 08:10:01,650:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18682 

self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27803.3', self.close='27816.1'
127.0.0.1 - - [04/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-04 08:20:10,370:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27803.3', self.close='27816.1'
2023-04-04 08:20:10,692:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230404   073000    073959  1680565199  27858.7    27822
12142  20230404   074000    074959  1680565799    27822  27822.5
12143  20230404   075000    075959  1680566399  27822.4  27786.1
12144  20230404   080000    080959  1680566999  27786.1  27803.2
12145  20230404   081000    081959  1680567599  27803.3  27816.1
2023-04-04 08:20:10,692:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32794
self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27745.5, self.close=27816.1, self.high=27817.0, self.low=27741.6, self.vol=969.827, self.amt=26942042.6747 
127.0.0.1 - - [04/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-04 08:20:08,310:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230404   075500    075959  ...         0.0        0.0       0
5856  20230404   080000    080459  ...         0.0        0.0       0
5857  20230404   080500    080959  ...         0.0        0.0       0
5858  20230404   081000    081459  ...         0.0        0.0       0
5859  20230404   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 08:20:08,340:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680567599, self.tradeDate='20230404', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27745.5, self.close=27816.1, self.high=27817.0, self.low=27741.6, self.vol=969.827, self.amt=26942042.6747, ukdf['pct'].iloc[-1]=0.002375 , ukdf['amount'].iloc[-1]=26942042.6747, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32795
self.closeSec=1680567899, self.tradeDate='20230404', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27816.1, self.close=27816.9, self.high=27857.9, self.low=27816.0, self.vol=1509.048, self.amt=42009326.8752 
127.0.0.1 - - [04/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-04 08:25:01,647:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230404   080000    080459  ...         0.0        0.0       0
5857  20230404   080500    080959  ...         0.0        0.0       0
5858  20230404   081000    081459  ...         0.0        0.0       0
5859  20230404   081500    081959  ...         0.0        0.0       0
5860  20230404   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-04 08:25:01,648:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680567899, self.tradeDate='20230404', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27816.1, self.close=27816.9, self.high=27857.9, self.low=27816.0, self.vol=1509.048, self.amt=42009326.8752, ukdf['pct'].iloc[-1]=2.9e-05 , ukdf['amount'].iloc[-1]=42009326.8752, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230403   200000    235959  1680537599  ...    719  0.195187 -0.487681     NaN
720  20230404   000000    035959  1680551999  ...    720  0.195604 -0.468981     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '17090.0728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28070.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=778
self.closeSec=1680566399, self.tradeDate='20230404', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28071.8, self.close=27786.1, self.high=28084.0, self.low=27166.0, self.vol=178714.809, self.amt=4945556731.09789 
127.0.0.1 - - [04/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-04 08:00:01,909:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680566399, self.tradeDate='20230404', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28071.8, self.close=27786.1, self.high=28084.0, self.low=27166.0, self.vol=178714.809, self.amt=4945556731.09789 
2023-04-04 08:00:01,942:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230403   120000    155959  ...   59552.703  1.652843e+09  0.007510
718  20230403   160000    195959  ...  169914.981  4.806848e+09  0.010627
719  20230403   200000    235959  ...  141711.342  3.985696e+09 -0.007467
720  20230404   000000    035959  ...   99518.618  2.791907e+09  0.001398
721  20230404   040000    075959  ...  178714.809  4.945557e+09 -0.010174

[5 rows x 11 columns]
2023-04-04 08:00:04,353:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230403   120000    155959  1680508799  ...    717  0.249354 -0.352679     NaN
718  20230403   160000    195959  1680523199  ...    718  0.214565 -0.443444     NaN
719  20230403   200000    235959  1680537599  ...    719  0.195187 -0.487681     NaN
720  20230404   000000    035959  1680551999  ...    720  0.195604 -0.468981     NaN
721  20230404   040000    075959  1680566399  ...    721  0.172701 -0.528990     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '31657.1240054352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27791.0376746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


