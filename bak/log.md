# 20230322 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33052
self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28089.7, self.close=28083.0, self.high=28098.6, self.low=28068.3, self.vol=612.253, self.amt=17197477.3415 
127.0.0.1 - - [22/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 08:20:04,490:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230322   075500    075959  ...         0.0        0.0       0
5856  20230322   080000    080459  ...         0.0        0.0       0
5857  20230322   080500    080959  ...         0.0        0.0       0
5858  20230322   081000    081459  ...         0.0        0.0       0
5859  20230322   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 08:20:04,500:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28089.7, self.close=28083.0, self.high=28098.6, self.low=28068.3, self.vol=612.253, self.amt=17197477.3415, ukdf['pct'].iloc[-1]=-0.000235 , ukdf['amount'].iloc[-1]=17197477.3415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695339.6976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28084.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33053
self.closeSec=1679444699, self.tradeDate='20230322', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28083.1, self.close=28063.6, self.high=28091.3, self.low=28058.3, self.vol=567.35, self.amt=15925429.1875 
2023-03-22 08:25:01,621:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230322   080000    080459  ...         0.0        0.0       0
5857  20230322   080500    080959  ...         0.0        0.0       0
5858  20230322   081000    081459  ...         0.0        0.0       0
5859  20230322   081500    081959  ...         0.0        0.0       0
5860  20230322   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 08:25:01,621:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679444699, self.tradeDate='20230322', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28083.1, self.close=28063.6, self.high=28091.3, self.low=28058.3, self.vol=567.35, self.amt=15925429.1875, ukdf['pct'].iloc[-1]=-0.000691 , ukdf['amount'].iloc[-1]=15925429.1875, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-694088.0368', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28063.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28089.7, self.close=28083.0, self.high=28098.6, self.low=28068.3 
127.0.0.1 - - [22/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-22 08:20:02,590:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28089.7, self.close=28083.0, self.high=28098.6, self.low=28068.3   
2023-03-22 08:20:02,879:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230322   075500    075959  1679443199  ...  28086.7 -0.000167   1535    5
1536  20230322   080000    080459  1679443499  ...  28074.1 -0.000007   1536    0
1537  20230322   080500    080959  1679443799  ...  28062.3 -0.000840   1537    1
1538  20230322   081000    081459  1679444099  ...  28059.2  0.000791   1538    2
1539  20230322   081500    081959  1679444399  ...  28068.3 -0.000235   1539    3

[5 rows x 11 columns]
2023-03-22 08:20:02,880:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=220, self.factor=0.38404958452416676, self.count=33619 

self.closeSec=1679444699, self.tradeDate='20230322', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28083.1, self.close=28063.6, self.high=28091.3, self.low=28058.3 
2023-03-22 08:25:01,512:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679444699, self.tradeDate='20230322', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28083.1, self.close=28063.6, self.high=28091.3, self.low=28058.3   
2023-03-22 08:25:01,602:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230322   080000    080459  1679443499  ...  28074.1 -0.000007   1536    0
1537  20230322   080500    080959  1679443799  ...  28062.3 -0.000840   1537    1
1538  20230322   081000    081459  1679444099  ...  28059.2  0.000791   1538    2
1539  20230322   081500    081959  1679444399  ...  28068.3 -0.000235   1539    3
1540  20230322   082000    082459  1679444699  ...  28058.3 -0.000691   1540    4

[5 rows x 11 columns]
2023-03-22 08:25:01,602:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-22 08:00:33,918:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230322    052959  28058.0  ...  52.083333  0.521692  0.345103
5771  20230322    055959  27994.7  ...  51.666667  0.521260  0.348774
5772  20230322    062959  27990.0  ...  52.083333  0.523163  0.351205
5773  20230322    065959  28008.5  ...  52.083333  0.524332  0.352871
5774  20230322    072959  28019.2  ...  52.500000  0.533426  0.349728

[5 rows x 33 columns]
0.5415896487985212
acc is : 0.5415896487985212
2023-03-22 08:00:34,098:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.500496  0.499504       0  ...  1.216365   1.0    0.0  1.406208
537     0  0.512977  0.487023       1  ...  1.217125   1.0    0.0  1.407088
538     0  0.525030  0.474970       1  ...  1.217586   1.0    0.0  1.407620
539     0  0.522227  0.477773       1  ...  1.221175   1.0    0.0  1.411770
540     0  0.558149  0.441851       0  ...  1.220719   1.0    0.0  1.411242

[5 rows x 10 columns]
2023-03-22 08:00:34,133:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.499969  0.500031       0  ...  1.217311   1.0    0.0  1.399900
46     0  0.512090  0.487910       1  ...  1.209704   1.0    0.0  1.391181
47     0  0.524408  0.475592       1  ...  1.223007   1.0    0.0  1.400549
48     0  0.521769  0.478231       1  ...  1.221175   1.0    0.0  1.411770
49     0  0.558149  0.441851       0  ...  1.220719   1.0    0.0  1.411242

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230322   075000    075959  1679443199  28088.9  28091.1  0.000078
2023-03-22 08:00:02,378:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16808 

self.closeSec=1679443799, self.tradeDate='20230322', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28091.1', self.close='28067.4'
2023-03-22 08:10:01,733:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679443799, self.tradeDate='20230322', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28091.1', self.close='28067.4'
2023-03-22 08:10:01,791:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230322   072000    072959  1679441399  28061.9  28101.7  0.001418
621  20230322   073000    073959  1679441999  28101.7  28076.3 -0.000904
622  20230322   074000    074959  1679442599  28076.2  28088.9  0.000449
623  20230322   075000    075959  1679443199  28088.9  28091.1  0.000078
624  20230322   080000    080959  1679443799  28091.1  28067.4 -0.000844
2023-03-22 08:10:01,792:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16809 

self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28067.3', self.close='28083'
127.0.0.1 - - [22/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 08:20:03,639:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28067.3', self.close='28083'
2023-03-22 08:20:04,019:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230322   073000    073959  1679441999  28101.7  28076.3 -0.000904
622  20230322   074000    074959  1679442599  28076.2  28088.9  0.000449
623  20230322   075000    075959  1679443199  28088.9  28091.1  0.000078
624  20230322   080000    080959  1679443799  28091.1  28067.4 -0.000844
625  20230322   081000    081959  1679444399  28067.3    28083  0.000556
2023-03-22 08:20:04,020:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230322   075000    075959  1679443199  28088.9  28091.1
2023-03-22 08:00:02,396:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [22/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16809 

self.closeSec=1679443799, self.tradeDate='20230322', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28091.1', self.close='28067.4'
2023-03-22 08:10:01,737:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679443799, self.tradeDate='20230322', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28091.1', self.close='28067.4'
2023-03-22 08:10:01,771:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230322   072000    072959  1679441399  28061.9  28101.7
17469  20230322   073000    073959  1679441999  28101.7  28076.3
17470  20230322   074000    074959  1679442599  28076.2  28088.9
17471  20230322   075000    075959  1679443199  28088.9  28091.1
17472  20230322   080000    080959  1679443799  28091.1  28067.4
2023-03-22 08:10:01,772:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16810 

self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28067.3', self.close='28083'
127.0.0.1 - - [22/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 08:20:05,994:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28067.3', self.close='28083'
2023-03-22 08:20:06,141:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230322   073000    073959  1679441999  28101.7  28076.3
17470  20230322   074000    074959  1679442599  28076.2  28088.9
17471  20230322   075000    075959  1679443199  28088.9  28091.1
17472  20230322   080000    080959  1679443799  28091.1  28067.4
17473  20230322   081000    081959  1679444399  28067.3    28083
2023-03-22 08:20:06,141:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230322   075000    075959  1679443199  28088.9  28091.1
2023-03-22 08:00:02,300:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16809 

self.closeSec=1679443799, self.tradeDate='20230322', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28091.1', self.close='28067.4'
2023-03-22 08:10:01,761:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679443799, self.tradeDate='20230322', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28091.1', self.close='28067.4'
127.0.0.1 - - [22/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-22 08:10:01,775:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230322   072000    072959  1679441399  28061.9  28101.7
12141  20230322   073000    073959  1679441999  28101.7  28076.3
12142  20230322   074000    074959  1679442599  28076.2  28088.9
12143  20230322   075000    075959  1679443199  28088.9  28091.1
12144  20230322   080000    080959  1679443799  28091.1  28067.4
2023-03-22 08:10:01,775:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16810 

self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28067.3', self.close='28083'
127.0.0.1 - - [22/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-22 08:20:05,340:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28067.3', self.close='28083'
2023-03-22 08:20:05,671:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230322   073000    073959  1679441999  28101.7  28076.3
12142  20230322   074000    074959  1679442599  28076.2  28088.9
12143  20230322   075000    075959  1679443199  28088.9  28091.1
12144  20230322   080000    080959  1679443799  28091.1  28067.4
12145  20230322   081000    081959  1679444399  28067.3    28083
2023-03-22 08:20:05,672:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [22/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29050
self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28089.7, self.close=28083.0, self.high=28098.6, self.low=28068.3, self.vol=612.253, self.amt=17197477.3415 
2023-03-22 08:20:01,709:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230322   075500    075959  ...         0.0        0.0       0
5856  20230322   080000    080459  ...         0.0        0.0       0
5857  20230322   080500    080959  ...         0.0        0.0       0
5858  20230322   081000    081459  ...         0.0        0.0       0
5859  20230322   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 08:20:01,717:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679444399, self.tradeDate='20230322', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28089.7, self.close=28083.0, self.high=28098.6, self.low=28068.3, self.vol=612.253, self.amt=17197477.3415, ukdf['pct'].iloc[-1]=-0.000235 , ukdf['amount'].iloc[-1]=17197477.3415, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [22/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29051
self.closeSec=1679444699, self.tradeDate='20230322', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28083.1, self.close=28063.6, self.high=28091.3, self.low=28058.3, self.vol=567.35, self.amt=15925429.1875 
2023-03-22 08:25:01,639:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230322   080000    080459  ...         0.0        0.0       0
5857  20230322   080500    080959  ...         0.0        0.0       0
5858  20230322   081000    081459  ...         0.0        0.0       0
5859  20230322   081500    081959  ...         0.0        0.0       0
5860  20230322   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-22 08:25:01,642:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679444699, self.tradeDate='20230322', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28083.1, self.close=28063.6, self.high=28091.3, self.low=28058.3, self.vol=567.35, self.amt=15925429.1875, ukdf['pct'].iloc[-1]=-0.000691 , ukdf['amount'].iloc[-1]=15925429.1875, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

717  20230321   120000    155959  ...  105693.226  2.919067e+09 -0.010157
718  20230321   160000    195959  ...  143510.008  3.996684e+09  0.019468
719  20230321   200000    235959  ...  166351.235  4.656915e+09  0.000068
720  20230322   000000    035959  ...  165390.923  4.661815e+09  0.002840
721  20230322   040000    075959  ...   50579.928  1.418130e+09 -0.000587

[5 rows x 11 columns]
2023-03-22 08:00:04,452:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230321   120000    155959  1679385599  ...    717  0.664354 -0.102804     NaN
718  20230321   160000    195959  1679399999  ...    718  0.552215 -0.430259     NaN
719  20230321   200000    235959  1679414399  ...    719  0.607069 -0.285479     NaN
720  20230322   000000    035959  1679428799  ...    720  0.593629 -0.341142     NaN
721  20230322   040000    075959  1679443199  ...    721  0.438918 -0.819217    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '37258.23572967825', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28092.59663035', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.795', 'enterprice': '27400', 'countrevence': '0', 'unrealprofit': '37258.23572967825', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28092.59663035', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-03-22 08:00:10,307:INFO:s_rsrs:main.py:182:queryContractAssets:185271: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1513217.4104129', 'total': '1513217.4104129', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-03-22 08:00:10,482:INFO:s_rsrs:main.py:269:openSell:185271: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 53.706, "sell"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42038F1679443210481I0L65'}
2023-03-22 08:00:10,505:INFO:s_rsrs:main.py:176:insertFactor:185271: curDateTime:3220800, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230322, closeTime:075959, close:28091.1, sign:-1, total:1513217.4104129, side:sell  
127.0.0.1 - - [22/Mar/2023 08:00:10] "POST / HTTP/1.1" 200 -
2023-03-22 08:00:10,508:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42037F1679443205210I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679443205321000, 'quantity': '53.795', 'price': '28090.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679443204839, 'updatetime': 1679443205320, 'tradetype': 'usdt', 'selfid': 42037, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679443205320, 'clientorderid': '42037F1679443205210I0L65', 'price': '28090.8', 'quantity': '53.795', 'commission': '1511.144586', 'commissionasset': 'USDT', 'tradetime': 1679443205320, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679443205320}], 'gatetype': 'simulator', 'handletime': 0}
2023-03-22 08:00:10,508:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42037F1679443205210I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679443205321000, 'quantity': '53.795', 'price': '28090.8', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679443204839, 'updatetime': 1679443205320, 'tradetype': 'usdt', 'selfid': 42037, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679443205320, 'clientorderid': '42037F1679443205210I0L65', 'price': '28090.8', 'quantity': '53.795', 'commission': '1511.144586', 'commissionasset': 'USDT', 'tradetime': 1679443205320, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679443205320}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Mar/2023 08:00:10] "POST / HTTP/1.1" 200 -
2023-03-22 08:00:10,770:INFO:s_rsrs:main.py:343:handleOrderNew:185271: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42038F1679443210481I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679443210728063, 'quantity': '53.706', 'price': '28091.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679443210319, 'updatetime': 1679443210728, 'tradetype': 'usdt', 'selfid': 42038, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679443210728, 'clientorderid': '42038F1679443210481I0L65', 'price': '28091.1', 'quantity': '53.706', 'commission': '1508.6606166', 'commissionasset': 'USDT', 'tradetime': 1679443210728, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679443210728}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [22/Mar/2023 08:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [22/Mar/2023 08:00:10] "POST / HTTP/1.1" 200 -
2023-03-22 08:00:10,956:INFO:s_rsrs:main.py:346:handleOrderFilled:185271: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42038F1679443210481I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1679443210728063, 'quantity': '53.706', 'price': '28091.1', 'stopprice': '0', 'ordertype': '', 'side': 'SELL', 'status': 'FILLED', 'positionside': 'SHORT', 'createtime': 1679443210319, 'updatetime': 1679443210728, 'tradetype': 'usdt', 'selfid': 42038, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1679443210728, 'clientorderid': '42038F1679443210481I0L65', 'price': '28091.1', 'quantity': '53.706', 'commission': '1508.6606166', 'commissionasset': 'USDT', 'tradetime': 1679443210728, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1679443210728}], 'gatetype': 'simulator', 'handletime': 0}


