# 20230706 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15232
self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30443.2, self.close=30450.2, self.high=30463.0, self.low=30438.4, self.vol=702.388, self.amt=21389744.462 
127.0.0.1 - - [06/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 08:20:07,409:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230706   075500    075959  ...         0.0        0.0       0
5856  20230706   080000    080459  ...         0.0        0.0       0
5857  20230706   080500    080959  ...         0.0        0.0       0
5858  20230706   081000    081459  ...         0.0        0.0       0
5859  20230706   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 08:20:07,449:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30443.2, self.close=30450.2, self.high=30463.0, self.low=30438.4, self.vol=702.388, self.amt=21389744.462, ukdf['pct'].iloc[-1]=0.000233 , ukdf['amount'].iloc[-1]=21389744.462, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49998.02985440604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30455.16496154', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [06/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=15233
self.closeSec=1688603099, self.tradeDate='20230706', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30450.1, self.close=30512.9, self.high=30521.0, self.low=30448.8, self.vol=1248.468, self.amt=38064497.6667 
2023-07-06 08:25:00,835:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230706   080000    080459  ...         0.0        0.0       0
5857  20230706   080500    080959  ...         0.0        0.0       0
5858  20230706   081000    081459  ...         0.0        0.0       0
5859  20230706   081500    081959  ...         0.0        0.0       0
5860  20230706   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 08:25:00,835:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1688603099, self.tradeDate='20230706', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30450.1, self.close=30512.9, self.high=30521.0, self.low=30448.8, self.vol=1248.468, self.amt=38064497.6667, ukdf['pct'].iloc[-1]=0.002059 , ukdf['amount'].iloc[-1]=38064497.6667, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50834.36312995326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30515.22048901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30443.2, self.close=30450.2, self.high=30463.0, self.low=30438.4 
127.0.0.1 - - [06/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 08:20:04,959:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30443.2, self.close=30450.2, self.high=30463.0, self.low=30438.4   
2023-07-06 08:20:06,520:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230706   075500    075959  1688601599  ...  30488.4 -0.000308   1535    5
1536  20230706   080000    080459  1688601899  ...  30471.2 -0.000564   1536    0
1537  20230706   080500    080959  1688602199  ...  30455.0 -0.000128   1537    1
1538  20230706   081000    081459  1688602499  ...  30440.4 -0.000798   1538    2
1539  20230706   081500    081959  1688602799  ...  30438.4  0.000233   1539    3

[5 rows x 11 columns]
2023-07-06 08:20:06,529:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [06/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6660607732193702, self.count=15235 

self.closeSec=1688603099, self.tradeDate='20230706', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30450.1, self.close=30512.9, self.high=30521.0, self.low=30448.8 
2023-07-06 08:25:00,772:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1688603099, self.tradeDate='20230706', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30450.1, self.close=30512.9, self.high=30521.0, self.low=30448.8   
2023-07-06 08:25:00,811:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230706   080000    080459  1688601899  ...  30471.2 -0.000564   1536    0
1537  20230706   080500    080959  1688602199  ...  30455.0 -0.000128   1537    1
1538  20230706   081000    081459  1688602499  ...  30440.4 -0.000798   1538    2
1539  20230706   081500    081959  1688602799  ...  30438.4  0.000233   1539    3
1540  20230706   082000    082459  1688603099  ...  30448.8  0.002059   1540    4

[5 rows x 11 columns]
2023-07-06 08:25:00,811:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-06 08:00:18,033:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230706    052959  30450.2  ...  48.333333  0.449467  0.661493
5771  20230706    055959  30475.0  ...  47.916667  0.446087  0.657075
5772  20230706    062959  30458.9  ...  47.500000  0.441639  0.654954
5773  20230706    065959  30438.0  ...  47.500000  0.440040  0.653688
5774  20230706    072959  30430.3  ...  47.500000  0.455986  0.646836

[5 rows x 33 columns]
0.5822550831792976
acc is : 0.5822550831792976
2023-07-06 08:00:18,118:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.514199  0.485801       0  ...  0.913275  -1.0    0.0  0.996640
537     0  0.505945  0.494055       0  ...  0.913904  -1.0    0.0  0.995952
538     0  0.508103  0.491897       0  ...  0.914130  -1.0    0.0  0.995707
539     0  0.507636  0.492364       1  ...  0.912342  -1.0    0.0  0.997654
540     0  0.526332  0.473668       0  ...  0.912384  -1.0    0.0  0.997608

[5 rows x 10 columns]
2023-07-06 08:00:18,141:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.515792  0.484208       0  ...  0.913275  -1.0    0.0  1.002238
46     0  0.506987  0.493013       0  ...  0.913904  -1.0    0.0  0.999580
47     0  0.508548  0.491452       0  ...  0.914130  -1.0    0.0  0.997587
48     0  0.507636  0.492364       1  ...  0.912342  -1.0    0.0  0.997654
49     0  0.526332  0.473668       0  ...  0.912384  -1.0    0.0  0.997608

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.486', 'enterprice': '30415.6', 'countrevence': '0', 'unrealprofit': '-1898.707', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30490.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230706   075000    075959  1688601599  30485.5  30488.4  0.000095
2023-07-06 08:00:02,080:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7616 

self.closeSec=1688602199, self.tradeDate='20230706', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30488.4', self.close='30467.4'
2023-07-06 08:10:01,110:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688602199, self.tradeDate='20230706', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30488.4', self.close='30467.4'
2023-07-06 08:10:01,144:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230706   072000    072959  1688599799  30464.1    30490  0.000847
621  20230706   073000    073959  1688600399    30490  30510.2  0.000663
622  20230706   074000    074959  1688600999  30510.2  30485.5 -0.000810
623  20230706   075000    075959  1688601599  30485.5  30488.4  0.000095
624  20230706   080000    080959  1688602199  30488.4  30467.4 -0.000689
2023-07-06 08:10:01,145:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7617 

self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30467.4', self.close='30450.2'
127.0.0.1 - - [06/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-06 08:20:07,600:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30467.4', self.close='30450.2'
2023-07-06 08:20:08,470:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230706   073000    073959  1688600399    30490  30510.2  0.000663
622  20230706   074000    074959  1688600999  30510.2  30485.5 -0.000810
623  20230706   075000    075959  1688601599  30485.5  30488.4  0.000095
624  20230706   080000    080959  1688602199  30488.4  30467.4 -0.000689
625  20230706   081000    081959  1688602799  30467.4  30450.2 -0.000565
2023-07-06 08:20:08,478:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230706   075000    075959  1688601599  30485.5  30488.4
2023-07-06 08:00:02,137:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7619 

self.closeSec=1688602199, self.tradeDate='20230706', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30488.4', self.close='30467.4'
127.0.0.1 - - [06/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-06 08:10:01,130:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688602199, self.tradeDate='20230706', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30488.4', self.close='30467.4'
2023-07-06 08:10:01,150:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230706   072000    072959  1688599799  30464.1    30490
17469  20230706   073000    073959  1688600399    30490  30510.2
17470  20230706   074000    074959  1688600999  30510.2  30485.5
17471  20230706   075000    075959  1688601599  30485.5  30488.4
17472  20230706   080000    080959  1688602199  30488.4  30467.4
2023-07-06 08:10:01,150:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7620 

self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30467.4', self.close='30450.2'
127.0.0.1 - - [06/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-06 08:20:09,442:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30467.4', self.close='30450.2'
2023-07-06 08:20:09,630:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230706   073000    073959  1688600399    30490  30510.2
17470  20230706   074000    074959  1688600999  30510.2  30485.5
17471  20230706   075000    075959  1688601599  30485.5  30488.4
17472  20230706   080000    080959  1688602199  30488.4  30467.4
17473  20230706   081000    081959  1688602799  30467.4  30450.2
2023-07-06 08:20:09,631:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230706   075000    075959  1688601599  30485.5  30488.4
2023-07-06 08:00:02,134:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7619 

self.closeSec=1688602199, self.tradeDate='20230706', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30488.4', self.close='30467.4'
2023-07-06 08:10:01,122:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688602199, self.tradeDate='20230706', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30488.4', self.close='30467.4'
127.0.0.1 - - [06/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-06 08:10:01,142:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230706   072000    072959  1688599799  30464.1    30490
12141  20230706   073000    073959  1688600399    30490  30510.2
12142  20230706   074000    074959  1688600999  30510.2  30485.5
12143  20230706   075000    075959  1688601599  30485.5  30488.4
12144  20230706   080000    080959  1688602199  30488.4  30467.4
2023-07-06 08:10:01,142:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=7620 

self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30467.4', self.close='30450.2'
127.0.0.1 - - [06/Jul/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-07-06 08:20:09,190:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30467.4', self.close='30450.2'
2023-07-06 08:20:09,449:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230706   073000    073959  1688600399    30490  30510.2
12142  20230706   074000    074959  1688600999  30510.2  30485.5
12143  20230706   075000    075959  1688601599  30485.5  30488.4
12144  20230706   080000    080959  1688602199  30488.4  30467.4
12145  20230706   081000    081959  1688602799  30467.4  30450.2
2023-07-06 08:20:09,450:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15232
self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30443.2, self.close=30450.2, self.high=30463.0, self.low=30438.4, self.vol=702.388, self.amt=21389744.462 
127.0.0.1 - - [06/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-06 08:20:07,409:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230706   075500    075959  ...         0.0        0.0       0
5856  20230706   080000    080459  ...         0.0        0.0       0
5857  20230706   080500    080959  ...         0.0        0.0       0
5858  20230706   081000    081459  ...         0.0        0.0       0
5859  20230706   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 08:20:07,440:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688602799, self.tradeDate='20230706', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30443.2, self.close=30450.2, self.high=30463.0, self.low=30438.4, self.vol=702.388, self.amt=21389744.462, ukdf['pct'].iloc[-1]=0.000233 , ukdf['amount'].iloc[-1]=21389744.462, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '134122.44109353674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30455.16935714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=15233
self.closeSec=1688603099, self.tradeDate='20230706', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30450.1, self.close=30512.9, self.high=30521.0, self.low=30448.8, self.vol=1248.468, self.amt=38064497.6667 
127.0.0.1 - - [06/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-06 08:25:00,834:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230706   080000    080459  ...         0.0        0.0       0
5857  20230706   080500    080959  ...         0.0        0.0       0
5858  20230706   081000    081459  ...         0.0        0.0       0
5859  20230706   081500    081959  ...         0.0        0.0       0
5860  20230706   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-06 08:25:00,834:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1688603099, self.tradeDate='20230706', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30450.1, self.close=30512.9, self.high=30521.0, self.low=30448.8, self.vol=1248.468, self.amt=38064497.6667, ukdf['pct'].iloc[-1]=0.002059 , ukdf['amount'].iloc[-1]=38064497.6667, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136352.80018232041', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30515.22048901', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230705   200000    235959  1688572799  ...    719  0.568203  0.246937     NaN
720  20230706   000000    035959  1688587199  ...    720  0.578402  0.269805     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-17411.01', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30422.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1629703.909755, self.flagDict['side']='buy', self.tradeCount=9, self.count=317
self.closeSec=1688601599, self.tradeDate='20230706', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30420.0, self.close=30488.5, self.high=30525.1, self.low=30369.6, self.vol=26258.551, self.amt=799587958.3123 
127.0.0.1 - - [06/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-06 08:00:01,699:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1688601599, self.tradeDate='20230706', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30420.0, self.close=30488.5, self.high=30525.1, self.low=30369.6, self.vol=26258.551, self.amt=799587958.3123 
2023-07-06 08:00:01,727:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230705   120000    155959  ...  19242.008  5.926999e+08 -0.002959
718  20230705   160000    195959  ...  90362.983  2.760664e+09 -0.012056
719  20230705   200000    235959  ...  93102.558  2.823460e+09 -0.001645
720  20230706   000000    035959  ...  47167.111  1.437322e+09  0.002472
721  20230706   040000    075959  ...  26258.551  7.995880e+08  0.002252

[5 rows x 11 columns]
2023-07-06 08:00:03,155:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230705   120000    155959  1688543999  ...    717  0.702982  0.562522     NaN
718  20230705   160000    195959  1688558399  ...    718  0.548848  0.211732     NaN
719  20230705   200000    235959  1688572799  ...    719  0.568203  0.246937     NaN
720  20230706   000000    035959  1688587199  ...    720  0.578402  0.269805     NaN
721  20230706   040000    075959  1688601599  ...    721  0.614850  0.372855     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.05', 'enterprice': '30750.9', 'countrevence': '0', 'unrealprofit': '-13840.933201241', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30489.99645238', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


