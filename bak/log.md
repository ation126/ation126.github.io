# 20230630 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13504
self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30408.0, self.close=30425.8, self.high=30449.0, self.low=30385.0, self.vol=1263.602, self.amt=38434688.9753 
127.0.0.1 - - [30/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-30 08:20:08,121:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230630   075500    075959  ...         0.0        0.0       0
5856  20230630   080000    080459  ...         0.0        0.0       0
5857  20230630   080500    080959  ...         0.0        0.0       0
5858  20230630   081000    081459  ...         0.0        0.0       0
5859  20230630   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 08:20:08,151:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30408.0, self.close=30425.8, self.high=30449.0, self.low=30385.0, self.vol=1263.602, self.amt=38434688.9753, ukdf['pct'].iloc[-1]=0.000585 , ukdf['amount'].iloc[-1]=38434688.9753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49606.1137265628', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30427.0221978', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13505
self.closeSec=1688084699, self.tradeDate='20230630', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30425.8, self.close=30465.8, self.high=30465.8, self.low=30416.2, self.vol=621.679, self.amt=18923304.0136 
127.0.0.1 - - [30/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-30 08:25:00,785:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230630   080000    080459  ...         0.0        0.0       0
5857  20230630   080500    080959  ...         0.0        0.0       0
5858  20230630   081000    081459  ...         0.0        0.0       0
5859  20230630   081500    081959  ...         0.0        0.0       0
5860  20230630   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 08:25:00,786:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688084699, self.tradeDate='20230630', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30425.8, self.close=30465.8, self.high=30465.8, self.low=30416.2, self.vol=621.679, self.amt=18923304.0136, ukdf['pct'].iloc[-1]=0.001315 , ukdf['amount'].iloc[-1]=18923304.0136, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50157.2742', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30466.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30408.0, self.close=30425.8, self.high=30449.0, self.low=30385.0 
127.0.0.1 - - [30/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 08:20:05,399:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30408.0, self.close=30425.8, self.high=30449.0, self.low=30385.0   
2023-06-30 08:20:07,119:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230630   075500    075959  1688083199  ...  30430.4 -0.000194   1535    5
1536  20230630   080000    080459  1688083499  ...  30417.2 -0.000039   1536    0
1537  20230630   080500    080959  1688083799  ...  30421.8  0.000765   1537    1
1538  20230630   081000    081459  1688084099  ...  30408.0 -0.001773   1538    2
1539  20230630   081500    081959  1688084399  ...  30385.0  0.000585   1539    3

[5 rows x 11 columns]
2023-06-30 08:20:07,130:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=31, self.factor=0.4509294852608375, self.count=13507 

self.closeSec=1688084699, self.tradeDate='20230630', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30425.8, self.close=30465.8, self.high=30465.8, self.low=30416.2 
127.0.0.1 - - [30/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-30 08:25:00,736:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688084699, self.tradeDate='20230630', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30425.8, self.close=30465.8, self.high=30465.8, self.low=30416.2   
2023-06-30 08:25:00,769:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230630   080000    080459  1688083499  ...  30417.2 -0.000039   1536    0
1537  20230630   080500    080959  1688083799  ...  30421.8  0.000765   1537    1
1538  20230630   081000    081459  1688084099  ...  30408.0 -0.001773   1538    2
1539  20230630   081500    081959  1688084399  ...  30385.0  0.000585   1539    3
1540  20230630   082000    082459  1688084699  ...  30416.2  0.001315   1540    4

[5 rows x 11 columns]
2023-06-30 08:25:00,771:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-30 08:00:18,438:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230630    052959  30386.4  ...  50.416667  0.504610  0.371705
5771  20230630    055959  30422.0  ...  50.000000  0.503026  0.384547
5772  20230630    062959  30412.4  ...  50.000000  0.507561  0.394087
5773  20230630    065959  30440.0  ...  50.000000  0.501219  0.406313
5774  20230630    072959  30402.5  ...  50.000000  0.512734  0.413421

[5 rows x 33 columns]
0.5693160813308688
acc is : 0.5693160813308688
2023-06-30 08:00:18,521:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.501322  0.498678       0  ...  1.000082   1.0    0.0  1.144709
537     1  0.497893  0.502107       1  ...  1.000989   1.0    0.0  1.145748
538     0  0.503678  0.496322       0  ...  0.999756   1.0    0.0  1.144336
539     0  0.509415  0.490585       1  ...  1.002042   1.0    0.0  1.146952
540     0  0.528722  0.471278       0  ...  1.000986   1.0    0.0  1.145744

[5 rows x 10 columns]
2023-06-30 08:00:18,532:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500617  0.499383       0  ...  1.000082   1.0    0.0  1.145584
46     1  0.497909  0.502091       1  ...  1.000989   1.0    0.0  1.144628
47     0  0.503683  0.496317       0  ...  0.999756   1.0    0.0  1.142526
48     0  0.509832  0.490168       1  ...  1.002042   1.0    0.0  1.146952
49     0  0.528722  0.471278       0  ...  1.000986   1.0    0.0  1.145744

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.241', 'enterprice': '30643.5', 'countrevence': '0', 'unrealprofit': '-5395.1496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30437.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230630   075000    075959  1688083199  30457.9  30439.9 -0.000594
2023-06-30 08:00:02,073:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6752 

self.closeSec=1688083799, self.tradeDate='20230630', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30439.9', self.close='30462'
2023-06-30 08:10:01,157:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688083799, self.tradeDate='20230630', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30439.9', self.close='30462'
127.0.0.1 - - [30/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-30 08:10:01,169:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230630   072000    072959  1688081399  30409.6    30472  0.002052
621  20230630   073000    073959  1688081999  30472.1    30480  0.000263
622  20230630   074000    074959  1688082599  30479.9    30458 -0.000722
623  20230630   075000    075959  1688083199  30457.9  30439.9 -0.000594
624  20230630   080000    080959  1688083799  30439.9    30462  0.000726
2023-06-30 08:10:01,169:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6753 

self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30462', self.close='30425.9'
127.0.0.1 - - [30/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 08:20:07,842:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30462', self.close='30425.9'
2023-06-30 08:20:08,681:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230630   073000    073959  1688081999  30472.1    30480  0.000263
622  20230630   074000    074959  1688082599  30479.9    30458 -0.000722
623  20230630   075000    075959  1688083199  30457.9  30439.9 -0.000594
624  20230630   080000    080959  1688083799  30439.9    30462  0.000726
625  20230630   081000    081959  1688084399    30462  30425.9 -0.001185
2023-06-30 08:20:08,690:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230630   075000    075959  1688083199  30457.9  30439.9
2023-06-30 08:00:02,083:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6755 

self.closeSec=1688083799, self.tradeDate='20230630', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30439.9', self.close='30462'
2023-06-30 08:10:01,145:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688083799, self.tradeDate='20230630', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30439.9', self.close='30462'
127.0.0.1 - - [30/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-30 08:10:01,165:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230630   072000    072959  1688081399  30409.6    30472
17469  20230630   073000    073959  1688081999  30472.1    30480
17470  20230630   074000    074959  1688082599  30479.9    30458
17471  20230630   075000    075959  1688083199  30457.9  30439.9
17472  20230630   080000    080959  1688083799  30439.9    30462
2023-06-30 08:10:01,166:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6756 

self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30462', self.close='30425.9'
127.0.0.1 - - [30/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 08:20:10,418:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30462', self.close='30425.9'
2023-06-30 08:20:10,568:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230630   073000    073959  1688081999  30472.1    30480
17470  20230630   074000    074959  1688082599  30479.9    30458
17471  20230630   075000    075959  1688083199  30457.9  30439.9
17472  20230630   080000    080959  1688083799  30439.9    30462
17473  20230630   081000    081959  1688084399    30462  30425.9
2023-06-30 08:20:10,569:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230630   075000    075959  1688083199  30457.9  30439.9
2023-06-30 08:00:02,118:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [30/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6755 

self.closeSec=1688083799, self.tradeDate='20230630', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30439.9', self.close='30462'
2023-06-30 08:10:01,178:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688083799, self.tradeDate='20230630', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30439.9', self.close='30462'
2023-06-30 08:10:01,184:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230630   072000    072959  1688081399  30409.6    30472
12141  20230630   073000    073959  1688081999  30472.1    30480
12142  20230630   074000    074959  1688082599  30479.9    30458
12143  20230630   075000    075959  1688083199  30457.9  30439.9
12144  20230630   080000    080959  1688083799  30439.9    30462
2023-06-30 08:10:01,184:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6756 

self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30462', self.close='30425.9'
127.0.0.1 - - [30/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-30 08:20:09,780:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30462', self.close='30425.9'
2023-06-30 08:20:10,201:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230630   073000    073959  1688081999  30472.1    30480
12142  20230630   074000    074959  1688082599  30479.9    30458
12143  20230630   075000    075959  1688083199  30457.9  30439.9
12144  20230630   080000    080959  1688083799  30439.9    30462
12145  20230630   081000    081959  1688084399    30462  30425.9
2023-06-30 08:20:10,210:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13504
self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30408.0, self.close=30425.8, self.high=30449.0, self.low=30385.0, self.vol=1263.602, self.amt=38434688.9753 
127.0.0.1 - - [30/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-30 08:20:08,120:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230630   075500    075959  ...         0.0        0.0       0
5856  20230630   080000    080459  ...         0.0        0.0       0
5857  20230630   080500    080959  ...         0.0        0.0       0
5858  20230630   081000    081459  ...         0.0        0.0       0
5859  20230630   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 08:20:08,151:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688084399, self.tradeDate='20230630', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30408.0, self.close=30425.8, self.high=30449.0, self.low=30385.0, self.vol=1263.602, self.amt=38434688.9753, ukdf['pct'].iloc[-1]=0.000585 , ukdf['amount'].iloc[-1]=38434688.9753, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '133077.0274484898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30427.0221978', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [30/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13505
self.closeSec=1688084699, self.tradeDate='20230630', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30425.8, self.close=30465.8, self.high=30465.8, self.low=30416.2, self.vol=621.679, self.amt=18923304.0136 
2023-06-30 08:25:00,789:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230630   080000    080459  ...         0.0        0.0       0
5857  20230630   080500    080959  ...         0.0        0.0       0
5858  20230630   081000    081459  ...         0.0        0.0       0
5859  20230630   081500    081959  ...         0.0        0.0       0
5860  20230630   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-30 08:25:00,789:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688084699, self.tradeDate='20230630', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30425.8, self.close=30465.8, self.high=30465.8, self.low=30416.2, self.vol=621.679, self.amt=18923304.0136, ukdf['pct'].iloc[-1]=0.001315 , ukdf['amount'].iloc[-1]=18923304.0136, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '134546.9866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30466.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230629   200000    235959  1688054399  ...    719  0.355426 -0.588082     NaN
720  20230630   000000    035959  1688068799  ...    720  0.333707 -0.664776    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '6626.2868108892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30582.6047381', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=281
self.closeSec=1688083199, self.tradeDate='20230630', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30571.5, self.close=30439.9, self.high=30630.0, self.low=30222.0, self.vol=43576.159, self.amt=1324846276.66475 
127.0.0.1 - - [30/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-30 08:00:01,652:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688083199, self.tradeDate='20230630', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30571.5, self.close=30439.9, self.high=30630.0, self.low=30222.0, self.vol=43576.159, self.amt=1324846276.66475 
2023-06-30 08:00:01,676:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230629   120000    155959  ...   37925.711  1.148028e+09  0.005689
718  20230629   160000    195959  ...   98223.108  3.002113e+09  0.010773
719  20230629   200000    235959  ...  113767.896  3.482065e+09 -0.006275
720  20230630   000000    035959  ...   54373.148  1.660331e+09  0.003387
721  20230630   040000    075959  ...   43576.159  1.324846e+09 -0.004305

[5 rows x 11 columns]
2023-06-30 08:00:03,027:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230629   120000    155959  1688025599  ...    717  0.380362 -0.491571     NaN
718  20230629   160000    195959  1688039999  ...    718  0.292563 -0.741058    -1.0
719  20230629   200000    235959  1688054399  ...    719  0.355426 -0.588082     NaN
720  20230630   000000    035959  1688068799  ...    720  0.333707 -0.664776    -1.0
721  20230630   040000    075959  1688083199  ...    721  0.334840 -0.679149    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '14227.8828', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30439.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


