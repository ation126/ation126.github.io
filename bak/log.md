# 20230815 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26752
self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29429.1, self.close=29426.5, self.high=29431.2, self.low=29426.5, self.vol=198.269, self.amt=5834937.0483 
127.0.0.1 - - [15/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 08:20:06,399:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230815   075500    075959  ...         0.0        0.0       0
5856  20230815   080000    080459  ...         0.0        0.0       0
5857  20230815   080500    080959  ...         0.0        0.0       0
5858  20230815   081000    081459  ...         0.0        0.0       0
5859  20230815   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 08:20:06,419:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29429.1, self.close=29426.5, self.high=29431.2, self.low=29426.5, self.vol=198.269, self.amt=5834937.0483, ukdf['pct'].iloc[-1]=-9.2e-05 , ukdf['amount'].iloc[-1]=5834937.0483, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35705.74243272498', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29428.86254723', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [15/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=26753
self.closeSec=1692059099, self.tradeDate='20230815', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29426.5, self.close=29446.5, self.high=29446.5, self.low=29426.1, self.vol=411.227, self.amt=12104104.8976 
2023-08-15 08:25:00,783:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230815   080000    080459  ...         0.0        0.0       0
5857  20230815   080500    080959  ...         0.0        0.0       0
5858  20230815   081000    081459  ...         0.0        0.0       0
5859  20230815   081500    081959  ...         0.0        0.0       0
5860  20230815   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 08:25:00,783:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692059099, self.tradeDate='20230815', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29426.5, self.close=29446.5, self.high=29446.5, self.low=29426.1, self.vol=411.227, self.amt=12104104.8976, ukdf['pct'].iloc[-1]=0.00068 , ukdf['amount'].iloc[-1]=12104104.8976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35951.3616', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29446.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29429.1, self.close=29426.5, self.high=29431.2, self.low=29426.5 
127.0.0.1 - - [15/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 08:20:04,283:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29429.1, self.close=29426.5, self.high=29431.2, self.low=29426.5   
2023-08-15 08:20:05,448:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230815   075500    075959  1692057599  ...  29419.5  0.000000   1535    5
1536  20230815   080000    080459  1692057899  ...  29406.6 -0.000354   1536    0
1537  20230815   080500    080959  1692058199  ...  29406.5  0.000680   1537    1
1538  20230815   081000    081459  1692058499  ...  29429.1  0.000000   1538    2
1539  20230815   081500    081959  1692058799  ...  29426.5 -0.000092   1539    3

[5 rows x 11 columns]
2023-08-15 08:20:05,458:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [15/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=37, self.factor=0.44744076965617113, self.count=26755 

self.closeSec=1692059099, self.tradeDate='20230815', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29426.5, self.close=29446.5, self.high=29446.5, self.low=29426.1 
2023-08-15 08:25:00,763:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692059099, self.tradeDate='20230815', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29426.5, self.close=29446.5, self.high=29446.5, self.low=29426.1   
2023-08-15 08:25:00,796:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230815   080000    080459  1692057899  ...  29406.6 -0.000354   1536    0
1537  20230815   080500    080959  1692058199  ...  29406.5  0.000680   1537    1
1538  20230815   081000    081459  1692058499  ...  29429.1  0.000000   1538    2
1539  20230815   081500    081959  1692058799  ...  29426.5 -0.000092   1539    3
1540  20230815   082000    082459  1692059099  ...  29426.1  0.000680   1540    4

[5 rows x 11 columns]
2023-08-15 08:25:00,796:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-15 08:00:17,324:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230815    052959  29388.4  ...  46.250000  0.488299  0.344581
5771  20230815    055959  29375.9  ...  46.666667  0.493681  0.353650
5772  20230815    062959  29390.3  ...  46.666667  0.515669  0.361489
5773  20230815    065959  29450.9  ...  46.250000  0.506651  0.375624
5774  20230815    072959  29426.5  ...  45.833333  0.503839  0.389933

[5 rows x 33 columns]
0.5360443622920518
acc is : 0.5360443622920518
2023-08-15 08:00:17,389:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.505044  0.494956       1  ...  0.994783   1.0    0.0  1.003342
537     0  0.509937  0.490063       1  ...  0.996831   1.0    0.0  1.005408
538     0  0.526886  0.473114       0  ...  0.996008   1.0    0.0  1.004578
539     0  0.502096  0.497904       0  ...  0.995751   1.0    0.0  1.004319
540     0  0.504639  0.495361       1  ...  0.995771   1.0    0.0  1.004339

[5 rows x 10 columns]
2023-08-15 08:00:17,401:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.503762  0.496238       1  ...  1.012947  -1.0    0.0  1.004992
46     0  0.509949  0.490051       1  ...  0.996831   1.0    0.0  1.005432
47     0  0.527081  0.472919       0  ...  0.996008   1.0    0.0  1.004773
48     0  0.502096  0.497904       0  ...  0.995751   1.0    0.0  1.004319
49     0  0.504639  0.495361       1  ...  0.995771   1.0    0.0  1.004339

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.817', 'enterprice': '29450.9', 'countrevence': '0', 'unrealprofit': '-747.8538', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29419.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230815   075000    075959  1692057599  29428.5  29419.5 -0.000306
2023-08-15 08:00:01,988:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [15/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13376 

self.closeSec=1692058199, self.tradeDate='20230815', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29419.5', self.close='29429.3'
2023-08-15 08:10:01,163:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692058199, self.tradeDate='20230815', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29419.5', self.close='29429.3'
2023-08-15 08:10:01,173:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230815   072000    072959  1692055799  29413.9  29418.9  0.000170
621  20230815   073000    073959  1692056399  29418.8  29418.4 -0.000017
622  20230815   074000    074959  1692056999  29418.4  29428.5  0.000343
623  20230815   075000    075959  1692057599  29428.5  29419.5 -0.000306
624  20230815   080000    080959  1692058199  29419.5  29429.3  0.000333
2023-08-15 08:10:01,173:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13377 

self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29429.3', self.close='29426.5'
127.0.0.1 - - [15/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 08:20:06,668:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29429.3', self.close='29426.5'
2023-08-15 08:20:07,219:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230815   073000    073959  1692056399  29418.8  29418.4 -0.000017
622  20230815   074000    074959  1692056999  29418.4  29428.5  0.000343
623  20230815   075000    075959  1692057599  29428.5  29419.5 -0.000306
624  20230815   080000    080959  1692058199  29419.5  29429.3  0.000333
625  20230815   081000    081959  1692058799  29429.3  29426.5 -0.000095
2023-08-15 08:20:07,220:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230815   075000    075959  1692057599  29428.5  29419.5
2023-08-15 08:00:02,009:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13379 

self.closeSec=1692058199, self.tradeDate='20230815', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29419.5', self.close='29429.3'
2023-08-15 08:10:01,153:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692058199, self.tradeDate='20230815', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29419.5', self.close='29429.3'
127.0.0.1 - - [15/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-15 08:10:01,163:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230815   072000    072959  1692055799  29413.9  29418.9
17469  20230815   073000    073959  1692056399  29418.8  29418.4
17470  20230815   074000    074959  1692056999  29418.4  29428.5
17471  20230815   075000    075959  1692057599  29428.5  29419.5
17472  20230815   080000    080959  1692058199  29419.5  29429.3
2023-08-15 08:10:01,163:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13380 

self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29429.3', self.close='29426.5'
127.0.0.1 - - [15/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 08:20:08,222:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29429.3', self.close='29426.5'
2023-08-15 08:20:08,289:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230815   073000    073959  1692056399  29418.8  29418.4
17470  20230815   074000    074959  1692056999  29418.4  29428.5
17471  20230815   075000    075959  1692057599  29428.5  29419.5
17472  20230815   080000    080959  1692058199  29419.5  29429.3
17473  20230815   081000    081959  1692058799  29429.3  29426.5
2023-08-15 08:20:08,289:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230815   075000    075959  1692057599  29428.5  29419.5
2023-08-15 08:00:01,993:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13379 

self.closeSec=1692058199, self.tradeDate='20230815', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29419.5', self.close='29429.3'
2023-08-15 08:10:01,152:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692058199, self.tradeDate='20230815', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29419.5', self.close='29429.3'
127.0.0.1 - - [15/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-15 08:10:01,158:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230815   072000    072959  1692055799  29413.9  29418.9
12141  20230815   073000    073959  1692056399  29418.8  29418.4
12142  20230815   074000    074959  1692056999  29418.4  29428.5
12143  20230815   075000    075959  1692057599  29428.5  29419.5
12144  20230815   080000    080959  1692058199  29419.5  29429.3
2023-08-15 08:10:01,159:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13380 

self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29429.3', self.close='29426.5'
127.0.0.1 - - [15/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-15 08:20:08,033:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29429.3', self.close='29426.5'
2023-08-15 08:20:08,199:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230815   073000    073959  1692056399  29418.8  29418.4
12142  20230815   074000    074959  1692056999  29418.4  29428.5
12143  20230815   075000    075959  1692057599  29428.5  29419.5
12144  20230815   080000    080959  1692058199  29419.5  29429.3
12145  20230815   081000    081959  1692058799  29429.3  29426.5
2023-08-15 08:20:08,200:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26752
self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29429.1, self.close=29426.5, self.high=29431.2, self.low=29426.5, self.vol=198.269, self.amt=5834937.0483 
127.0.0.1 - - [15/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-15 08:20:06,239:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230815   075500    075959  ...         0.0        0.0       0
5856  20230815   080000    080459  ...         0.0        0.0       0
5857  20230815   080500    080959  ...         0.0        0.0       0
5858  20230815   081000    081459  ...         0.0        0.0       0
5859  20230815   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 08:20:06,259:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692058799, self.tradeDate='20230815', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29429.1, self.close=29426.5, self.high=29431.2, self.low=29426.5, self.vol=198.269, self.amt=5834937.0483, ukdf['pct'].iloc[-1]=-9.2e-05 , ukdf['amount'].iloc[-1]=5834937.0483, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96004.37986666943', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29428.86254723', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [15/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=26753
self.closeSec=1692059099, self.tradeDate='20230815', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29426.5, self.close=29446.5, self.high=29446.5, self.low=29426.1, self.vol=411.227, self.amt=12104104.8976 
2023-08-15 08:25:00,802:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230815   080000    080459  ...         0.0        0.0       0
5857  20230815   080500    080959  ...         0.0        0.0       0
5858  20230815   081000    081459  ...         0.0        0.0       0
5859  20230815   081500    081959  ...         0.0        0.0       0
5860  20230815   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-15 08:25:00,802:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692059099, self.tradeDate='20230815', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29426.5, self.close=29446.5, self.high=29446.5, self.low=29426.1, self.vol=411.227, self.amt=12104104.8976, ukdf['pct'].iloc[-1]=0.00068 , ukdf['amount'].iloc[-1]=12104104.8976, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96659.4525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29446.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230814   200000    235959  1692028799  ...    719  0.000513 -1.156555    -1.0
720  20230815   000000    035959  1692043199  ...    720  0.000152 -1.153554    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '4210.05941695208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29350.67310234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=557
self.closeSec=1692057599, self.tradeDate='20230815', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29353.7, self.close=29419.5, self.high=29465.8, self.low=29323.2, self.vol=17851.488, self.amt=524854534.1484 
127.0.0.1 - - [15/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-15 08:00:01,541:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692057599, self.tradeDate='20230815', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29353.7, self.close=29419.5, self.high=29465.8, self.low=29323.2, self.vol=17851.488, self.amt=524854534.1484 
2023-08-15 08:00:01,557:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230814   120000    155959  ...  22168.394  6.520981e+08  0.000698
718  20230814   160000    195959  ...  24534.443  7.217591e+08 -0.000364
719  20230814   200000    235959  ...  80846.779  2.385466e+09  0.006568
720  20230815   000000    035959  ...  81315.670  2.394447e+09 -0.008080
721  20230815   040000    075959  ...  17851.488  5.248545e+08  0.002238

[5 rows x 11 columns]
2023-08-15 08:00:02,355:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230814   120000    155959  1691999999  ...    717  0.015864 -1.133319    -1.0
718  20230814   160000    195959  1692014399  ...    718  0.004699 -1.152454    -1.0
719  20230814   200000    235959  1692028799  ...    719  0.000513 -1.156555    -1.0
720  20230815   000000    035959  1692043199  ...    720  0.000152 -1.153554    -1.0
721  20230815   040000    075959  1692057599  ...    721  0.000146 -1.148049    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '667.85624058112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29419.60365376', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


