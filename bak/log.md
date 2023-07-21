# 20230721 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19552
self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29775.3, self.close=29757.5, self.high=29785.1, self.low=29753.2, self.vol=764.759, self.amt=22764728.8529 
127.0.0.1 - - [21/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 08:20:06,457:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230721   075500    075959  ...         0.0        0.0       0
5856  20230721   080000    080459  ...         0.0        0.0       0
5857  20230721   080500    080959  ...         0.0        0.0       0
5858  20230721   081000    081459  ...         0.0        0.0       0
5859  20230721   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 08:20:06,477:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29775.3, self.close=29757.5, self.high=29785.1, self.low=29753.2, self.vol=764.759, self.amt=22764728.8529, ukdf['pct'].iloc[-1]=-0.000594 , ukdf['amount'].iloc[-1]=22764728.8529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40280.955', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29757.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [21/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=19553
self.closeSec=1689899099, self.tradeDate='20230721', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29757.5, self.close=29806.6, self.high=29809.0, self.low=29753.1, self.vol=958.803, self.amt=28548752.8722 
2023-07-21 08:25:00,744:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230721   080000    080459  ...         0.0        0.0       0
5857  20230721   080500    080959  ...         0.0        0.0       0
5858  20230721   081000    081459  ...         0.0        0.0       0
5859  20230721   081500    081959  ...         0.0        0.0       0
5860  20230721   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 08:25:00,744:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689899099, self.tradeDate='20230721', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29757.5, self.close=29806.6, self.high=29809.0, self.low=29753.1, self.vol=958.803, self.amt=28548752.8722, ukdf['pct'].iloc[-1]=0.00165 , ukdf['amount'].iloc[-1]=28548752.8722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40966.1142', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29806.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29775.3, self.close=29757.5, self.high=29785.1, self.low=29753.2 
127.0.0.1 - - [21/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 08:20:04,458:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29775.3, self.close=29757.5, self.high=29785.1, self.low=29753.2   
2023-07-21 08:20:05,688:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230721   075500    075959  1689897599  ...  29772.0  0.000430   1535    5
1536  20230721   080000    080459  1689897899  ...  29779.4 -0.000272   1536    0
1537  20230721   080500    080959  1689898199  ...  29778.9  0.000776   1537    1
1538  20230721   081000    081459  1689898499  ...  29775.2 -0.001033   1538    2
1539  20230721   081500    081959  1689898799  ...  29753.2 -0.000594   1539    3

[5 rows x 11 columns]
2023-07-21 08:20:05,697:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=44, self.factor=0.5206762827609869, self.count=19555 

self.closeSec=1689899099, self.tradeDate='20230721', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29757.5, self.close=29806.6, self.high=29809.0, self.low=29753.1 
127.0.0.1 - - [21/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-21 08:25:00,744:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689899099, self.tradeDate='20230721', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29757.5, self.close=29806.6, self.high=29809.0, self.low=29753.1   
2023-07-21 08:25:00,758:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230721   080000    080459  1689897899  ...  29779.4 -0.000272   1536    0
1537  20230721   080500    080959  1689898199  ...  29778.9  0.000776   1537    1
1538  20230721   081000    081459  1689898499  ...  29775.2 -0.001033   1538    2
1539  20230721   081500    081959  1689898799  ...  29753.2 -0.000594   1539    3
1540  20230721   082000    082459  1689899099  ...  29753.1  0.001650   1540    4

[5 rows x 11 columns]
2023-07-21 08:25:00,758:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-21 08:00:18,242:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230721    052959  29729.8  ...  50.416667  0.469487  0.596037
5771  20230721    055959  29831.8  ...  50.416667  0.474870  0.597170
5772  20230721    062959  29856.0  ...  50.000000  0.464672  0.601946
5773  20230721    065959  29804.7  ...  50.000000  0.463188  0.606947
5774  20230721    072959  29797.2  ...  50.000000  0.463281  0.611585

[5 rows x 33 columns]
0.5101663585951941
acc is : 0.5101663585951941
2023-07-21 08:00:18,308:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.552337  0.447663       1  ...  0.952215   1.0 -0.0016  0.987236
537     0  0.528240  0.471760       0  ...  0.950578   1.0  0.0000  0.985540
538     0  0.506246  0.493754       0  ...  0.950339   1.0  0.0000  0.985292
539     0  0.517965  0.482035       1  ...  0.950352   1.0  0.0000  0.985305
540     0  0.517129  0.482871       0  ...  0.950141   1.0  0.0000  0.985087

[5 rows x 10 columns]
2023-07-21 08:00:18,320:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.551707  0.448293       1  ...  0.952215   1.0 -0.0016  0.984151
46     0  0.528356  0.471644       0  ...  0.950578   1.0  0.0000  0.984274
47     0  0.506061  0.493939       0  ...  0.950339   1.0  0.0000  0.984179
48     0  0.518066  0.481934       1  ...  0.950352   1.0  0.0000  0.985305
49     0  0.517129  0.482871       0  ...  0.950141   1.0  0.0000  0.985087

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.444', 'enterprice': '29839.3', 'countrevence': '0', 'unrealprofit': '-1104.2124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29792.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230721   075000    075959  1689897599    29794    29791 -0.000104
2023-07-21 08:00:02,249:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9776 

self.closeSec=1689898199, self.tradeDate='20230721', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29791', self.close='29806'
2023-07-21 08:10:01,086:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689898199, self.tradeDate='20230721', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29791', self.close='29806'
127.0.0.1 - - [21/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-21 08:10:01,092:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230721   072000    072959  1689895799  29801.5  29797.6 -0.000128
621  20230721   073000    073959  1689896399  29797.7  29791.3 -0.000211
622  20230721   074000    074959  1689896999  29791.2  29794.1  0.000094
623  20230721   075000    075959  1689897599    29794    29791 -0.000104
624  20230721   080000    080959  1689898199    29791    29806  0.000504
2023-07-21 08:10:01,093:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9777 

self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29806.1', self.close='29757.5'
127.0.0.1 - - [21/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 08:20:06,787:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29806.1', self.close='29757.5'
2023-07-21 08:20:07,376:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230721   073000    073959  1689896399  29797.7  29791.3 -0.000211
622  20230721   074000    074959  1689896999  29791.2  29794.1  0.000094
623  20230721   075000    075959  1689897599    29794    29791 -0.000104
624  20230721   080000    080959  1689898199    29791    29806  0.000504
625  20230721   081000    081959  1689898799  29806.1  29757.5 -0.001627
2023-07-21 08:20:07,384:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230721   075000    075959  1689897599    29794    29791
2023-07-21 08:00:02,289:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9779 

self.closeSec=1689898199, self.tradeDate='20230721', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29791', self.close='29806'
2023-07-21 08:10:01,088:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689898199, self.tradeDate='20230721', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29791', self.close='29806'
2023-07-21 08:10:01,098:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230721   072000    072959  1689895799  29801.5  29797.6
17469  20230721   073000    073959  1689896399  29797.7  29791.3
17470  20230721   074000    074959  1689896999  29791.2  29794.1
17471  20230721   075000    075959  1689897599    29794    29791
17472  20230721   080000    080959  1689898199    29791    29806
2023-07-21 08:10:01,098:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9780 

self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29806.1', self.close='29757.5'
127.0.0.1 - - [21/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 08:20:08,336:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29806.1', self.close='29757.5'
2023-07-21 08:20:08,546:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230721   073000    073959  1689896399  29797.7  29791.3
17470  20230721   074000    074959  1689896999  29791.2  29794.1
17471  20230721   075000    075959  1689897599    29794    29791
17472  20230721   080000    080959  1689898199    29791    29806
17473  20230721   081000    081959  1689898799  29806.1  29757.5
2023-07-21 08:20:08,546:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230721   075000    075959  1689897599    29794    29791
2023-07-21 08:00:02,258:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9779 

self.closeSec=1689898199, self.tradeDate='20230721', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29791', self.close='29806'
2023-07-21 08:10:01,095:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689898199, self.tradeDate='20230721', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29791', self.close='29806'
127.0.0.1 - - [21/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-21 08:10:01,101:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230721   072000    072959  1689895799  29801.5  29797.6
12141  20230721   073000    073959  1689896399  29797.7  29791.3
12142  20230721   074000    074959  1689896999  29791.2  29794.1
12143  20230721   075000    075959  1689897599    29794    29791
12144  20230721   080000    080959  1689898199    29791    29806
2023-07-21 08:10:01,102:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=9780 

self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29806.1', self.close='29757.5'
127.0.0.1 - - [21/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-21 08:20:08,148:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29806.1', self.close='29757.5'
2023-07-21 08:20:08,409:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230721   073000    073959  1689896399  29797.7  29791.3
12142  20230721   074000    074959  1689896999  29791.2  29794.1
12143  20230721   075000    075959  1689897599    29794    29791
12144  20230721   080000    080959  1689898199    29791    29806
12145  20230721   081000    081959  1689898799  29806.1  29757.5
2023-07-21 08:20:08,415:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19552
self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29775.3, self.close=29757.5, self.high=29785.1, self.low=29753.2, self.vol=764.759, self.amt=22764728.8529 
127.0.0.1 - - [21/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-21 08:20:06,456:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230721   075500    075959  ...         0.0        0.0       0
5856  20230721   080000    080459  ...         0.0        0.0       0
5857  20230721   080500    080959  ...         0.0        0.0       0
5858  20230721   081000    081459  ...         0.0        0.0       0
5859  20230721   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 08:20:06,468:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689898799, self.tradeDate='20230721', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29775.3, self.close=29757.5, self.high=29785.1, self.low=29753.2, self.vol=764.759, self.amt=22764728.8529, ukdf['pct'].iloc[-1]=-0.000594 , ukdf['amount'].iloc[-1]=22764728.8529, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '108206.5894', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29757.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [21/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=19553
self.closeSec=1689899099, self.tradeDate='20230721', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29757.5, self.close=29806.6, self.high=29809.0, self.low=29753.1, self.vol=958.803, self.amt=28548752.8722 
2023-07-21 08:25:00,782:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230721   080000    080459  ...         0.0        0.0       0
5857  20230721   080500    080959  ...         0.0        0.0       0
5858  20230721   081000    081459  ...         0.0        0.0       0
5859  20230721   081500    081959  ...         0.0        0.0       0
5860  20230721   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-21 08:25:00,783:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689899099, self.tradeDate='20230721', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29757.5, self.close=29806.6, self.high=29809.0, self.low=29753.1, self.vol=958.803, self.amt=28548752.8722, ukdf['pct'].iloc[-1]=0.00165 , ukdf['amount'].iloc[-1]=28548752.8722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '110033.9266', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29806.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230720   200000    235959  1689868799  ...    719  0.143075 -1.207132    -1.0
720  20230721   000000    035959  1689883199  ...    720  0.155606 -1.126586    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '6092.69826113904', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29753.82795421', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1556969.8971744, self.flagDict['side']='sell', self.tradeCount=12, self.count=407
self.closeSec=1689897599, self.tradeDate='20230721', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29744.5, self.close=29791.0, self.high=29880.2, self.low=29652.7, self.vol=28490.094, self.amt=848441429.306 
127.0.0.1 - - [21/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-21 08:00:01,874:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689897599, self.tradeDate='20230721', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29744.5, self.close=29791.0, self.high=29880.2, self.low=29652.7, self.vol=28490.094, self.amt=848441429.306 
2023-07-21 08:00:01,891:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230720   120000    155959  ...   54428.275  1.638943e+09  0.008638
718  20230720   160000    195959  ...   79217.962  2.400256e+09  0.002596
719  20230720   200000    235959  ...  146334.281  4.377740e+09 -0.015895
720  20230721   000000    035959  ...   78409.883  2.329877e+09 -0.001625
721  20230721   040000    075959  ...   28490.094  8.484414e+08  0.001567

[5 rows x 11 columns]
2023-07-21 08:00:02,860:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230720   120000    155959  1689839999  ...    717  0.212172 -0.948531    -1.0
718  20230720   160000    195959  1689854399  ...    718  0.230542 -0.849614    -1.0
719  20230720   200000    235959  1689868799  ...    719  0.143075 -1.207132    -1.0
720  20230721   000000    035959  1689883199  ...    720  0.155606 -1.126586    -1.0
721  20230721   040000    075959  1689897599  ...    721  0.156485 -1.097778    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.176', 'enterprice': '29870.6', 'countrevence': '0', 'unrealprofit': '4158.4272', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29790.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


