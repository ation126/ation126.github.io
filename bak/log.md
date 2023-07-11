# 20230711 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16672
self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30428.1, self.close=30468.1, self.high=30495.1, self.low=30418.1, self.vol=3495.795, self.amt=106497092.43915 
127.0.0.1 - - [11/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 08:20:07,426:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230711   075500    075959  ...         0.0        0.0       0
5856  20230711   080000    080459  ...         0.0        0.0       0
5857  20230711   080500    080959  ...         0.0        0.0       0
5858  20230711   081000    081459  ...         0.0        0.0       0
5859  20230711   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 08:20:07,466:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30428.1, self.close=30468.1, self.high=30495.1, self.low=30418.1, self.vol=3495.795, self.amt=106497092.43915, ukdf['pct'].iloc[-1]=0.001315 , ukdf['amount'].iloc[-1]=106497092.43915, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50076.86766043236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30460.82615686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=16673
self.closeSec=1689035099, self.tradeDate='20230711', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30468.2, self.close=30449.5, self.high=30468.2, self.low=30439.0, self.vol=986.119, self.amt=30027405.1017 
2023-07-11 08:25:00,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230711   080000    080459  ...         0.0        0.0       0
5857  20230711   080500    080959  ...         0.0        0.0       0
5858  20230711   081000    081459  ...         0.0        0.0       0
5859  20230711   081500    081959  ...         0.0        0.0       0
5860  20230711   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 08:25:00,813:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689035099, self.tradeDate='20230711', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30468.2, self.close=30449.5, self.high=30468.2, self.low=30439.0, self.vol=986.119, self.amt=30027405.1017, ukdf['pct'].iloc[-1]=-0.00061 , ukdf['amount'].iloc[-1]=30027405.1017, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49894.5572883252', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30447.7347902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30428.1, self.close=30468.1, self.high=30495.1, self.low=30418.1 
127.0.0.1 - - [11/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 08:20:05,037:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30428.1, self.close=30468.1, self.high=30495.1, self.low=30418.1   
2023-07-11 08:20:06,516:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230711   075500    075959  1689033599  ...  30383.5  0.000023   1535    5
1536  20230711   080000    080459  1689033899  ...  30381.0 -0.000520   1536    0
1537  20230711   080500    080959  1689034199  ...  30373.0  0.000836   1537    1
1538  20230711   081000    081459  1689034499  ...  30401.0  0.000714   1538    2
1539  20230711   081500    081959  1689034799  ...  30418.1  0.001315   1539    3

[5 rows x 11 columns]
2023-07-11 08:20:06,537:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=111, self.factor=0.4303816552743679, self.count=16675 

self.closeSec=1689035099, self.tradeDate='20230711', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30468.2, self.close=30449.5, self.high=30468.2, self.low=30439.0 
2023-07-11 08:25:00,724:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689035099, self.tradeDate='20230711', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30468.2, self.close=30449.5, self.high=30468.2, self.low=30439.0   
2023-07-11 08:25:00,783:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230711   080000    080459  1689033899  ...  30381.0 -0.000520   1536    0
1537  20230711   080500    080959  1689034199  ...  30373.0  0.000836   1537    1
1538  20230711   081000    081459  1689034499  ...  30401.0  0.000714   1538    2
1539  20230711   081500    081959  1689034799  ...  30418.1  0.001315   1539    3
1540  20230711   082000    082459  1689035099  ...  30439.0 -0.000610   1540    4

[5 rows x 11 columns]
2023-07-11 08:25:00,785:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-11 08:00:19,184:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230711    052959  30773.3  ...  48.750000  0.606594  0.286951
5771  20230711    055959  30701.6  ...  48.750000  0.502388  0.314856
5772  20230711    062959  30282.8  ...  49.166667  0.515976  0.336732
5773  20230711    065959  30349.8  ...  49.166667  0.512211  0.358250
5774  20230711    072959  30332.0  ...  49.166667  0.517869  0.376600

[5 rows x 33 columns]
0.5859519408502772
acc is : 0.5859519408502772
2023-07-11 08:00:19,269:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.506424  0.493576       0  ...  0.987907   1.0  0.0000  0.988723
537     1  0.374624  0.625376       1  ...  0.984137  -1.0 -0.0016  0.990914
538     1  0.462678  0.537322       0  ...  0.984711  -1.0  0.0000  0.990336
539     1  0.435822  0.564178       1  ...  0.983805  -1.0  0.0000  0.991247
540     1  0.462334  0.537666       1  ...  0.982613  -1.0  0.0000  0.992448

[5 rows x 10 columns]
2023-07-11 08:00:19,281:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.506940  0.493060       0  ...  1.000970   1.0  0.0000  0.993908
46     1  0.374845  0.625155       1  ...  0.984137  -1.0 -0.0016  0.994945
47     1  0.463355  0.536645       0  ...  0.997733  -1.0  0.0000  0.994766
48     1  0.435822  0.564178       1  ...  0.983805  -1.0  0.0000  0.991247
49     1  0.462334  0.537666       1  ...  0.982613  -1.0  0.0000  0.992448

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.635', 'enterprice': '30339.7', 'countrevence': '0', 'unrealprofit': '-1384.487', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30395.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230711   075000    075959  1689033599  30364.9  30396.8  0.001054
2023-07-11 08:00:02,188:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8336 

self.closeSec=1689034199, self.tradeDate='20230711', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30396.9', self.close='30406.4'
2023-07-11 08:10:01,143:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689034199, self.tradeDate='20230711', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30396.9', self.close='30406.4'
2023-07-11 08:10:01,156:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230711   072000    072959  1689031799  30338.1  30360.1  0.000847
621  20230711   073000    073959  1689032399    30360  30381.4  0.000702
622  20230711   074000    074959  1689032999  30381.4  30364.8 -0.000546
623  20230711   075000    075959  1689033599  30364.9  30396.8  0.001054
624  20230711   080000    080959  1689034199  30396.9  30406.4  0.000316
2023-07-11 08:10:01,157:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8337 

self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30406.5', self.close='30470'
127.0.0.1 - - [11/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 08:20:07,356:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30406.5', self.close='30470'
2023-07-11 08:20:08,124:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230711   073000    073959  1689032399    30360  30381.4  0.000702
622  20230711   074000    074959  1689032999  30381.4  30364.8 -0.000546
623  20230711   075000    075959  1689033599  30364.9  30396.8  0.001054
624  20230711   080000    080959  1689034199  30396.9  30406.4  0.000316
625  20230711   081000    081959  1689034799  30406.5    30470  0.002092
2023-07-11 08:20:08,125:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230711   075000    075959  1689033599  30364.9  30396.8
2023-07-11 08:00:02,171:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8339 

self.closeSec=1689034199, self.tradeDate='20230711', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30396.9', self.close='30406.4'
127.0.0.1 - - [11/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-11 08:10:01,178:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689034199, self.tradeDate='20230711', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30396.9', self.close='30406.4'
2023-07-11 08:10:01,195:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230711   072000    072959  1689031799  30338.1  30360.1
17469  20230711   073000    073959  1689032399    30360  30381.4
17470  20230711   074000    074959  1689032999  30381.4  30364.8
17471  20230711   075000    075959  1689033599  30364.9  30396.8
17472  20230711   080000    080959  1689034199  30396.9  30406.4
2023-07-11 08:10:01,195:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8340 

self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30406.5', self.close='30470'
127.0.0.1 - - [11/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 08:20:08,989:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30406.5', self.close='30470'
2023-07-11 08:20:09,201:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230711   073000    073959  1689032399    30360  30381.4
17470  20230711   074000    074959  1689032999  30381.4  30364.8
17471  20230711   075000    075959  1689033599  30364.9  30396.8
17472  20230711   080000    080959  1689034199  30396.9  30406.4
17473  20230711   081000    081959  1689034799  30406.5    30470
2023-07-11 08:20:09,202:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230711   075000    075959  1689033599  30364.9  30396.8
2023-07-11 08:00:02,207:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8339 

self.closeSec=1689034199, self.tradeDate='20230711', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30396.9', self.close='30406.4'
2023-07-11 08:10:01,175:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689034199, self.tradeDate='20230711', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30396.9', self.close='30406.4'
2023-07-11 08:10:01,196:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230711   072000    072959  1689031799  30338.1  30360.1
12141  20230711   073000    073959  1689032399    30360  30381.4
12142  20230711   074000    074959  1689032999  30381.4  30364.8
12143  20230711   075000    075959  1689033599  30364.9  30396.8
12144  20230711   080000    080959  1689034199  30396.9  30406.4
2023-07-11 08:10:01,196:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8340 

self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30406.5', self.close='30470'
127.0.0.1 - - [11/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-11 08:20:08,756:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30406.5', self.close='30470'
2023-07-11 08:20:09,054:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230711   073000    073959  1689032399    30360  30381.4
12142  20230711   074000    074959  1689032999  30381.4  30364.8
12143  20230711   075000    075959  1689033599  30364.9  30396.8
12144  20230711   080000    080959  1689034199  30396.9  30406.4
12145  20230711   081000    081959  1689034799  30406.5    30470
2023-07-11 08:20:09,056:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16672
self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30428.1, self.close=30468.1, self.high=30495.1, self.low=30418.1, self.vol=3495.795, self.amt=106497092.43915 
127.0.0.1 - - [11/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-11 08:20:07,426:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230711   075500    075959  ...         0.0        0.0       0
5856  20230711   080000    080459  ...         0.0        0.0       0
5857  20230711   080500    080959  ...         0.0        0.0       0
5858  20230711   081000    081459  ...         0.0        0.0       0
5859  20230711   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 08:20:07,457:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689034799, self.tradeDate='20230711', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30428.1, self.close=30468.1, self.high=30495.1, self.low=30418.1, self.vol=3495.795, self.amt=106497092.43915, ukdf['pct'].iloc[-1]=0.001315 , ukdf['amount'].iloc[-1]=106497092.43915, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '134332.54029193726', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30460.82615686', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [11/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=16673
self.closeSec=1689035099, self.tradeDate='20230711', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30468.2, self.close=30449.5, self.high=30468.2, self.low=30439.0, self.vol=986.119, self.amt=30027405.1017 
2023-07-11 08:25:00,817:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230711   080000    080459  ...         0.0        0.0       0
5857  20230711   080500    080959  ...         0.0        0.0       0
5858  20230711   081000    081459  ...         0.0        0.0       0
5859  20230711   081500    081959  ...         0.0        0.0       0
5860  20230711   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-11 08:25:00,818:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689035099, self.tradeDate='20230711', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30468.2, self.close=30449.5, self.high=30468.2, self.low=30439.0, self.vol=986.119, self.amt=30027405.1017, ukdf['pct'].iloc[-1]=-0.00061 , ukdf['amount'].iloc[-1]=30027405.1017, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '133846.3138428182', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30447.7347902', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230710   200000    235959  1689004799  ...    719  0.000017 -1.233220    -1.0
720  20230711   000000    035959  1689019199  ...    720  0.047909 -1.006761    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-27495.35167580875', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30822.13343725', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [11/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1604933.5124475, self.flagDict['side']='sell', self.tradeCount=10, self.count=347
self.closeSec=1689033599, self.tradeDate='20230711', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30824.5, self.close=30396.8, self.high=31040.0, self.low=30100.0, self.vol=157092.883, self.amt=4807922575.68155 
2023-07-11 08:00:01,772:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689033599, self.tradeDate='20230711', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30824.5, self.close=30396.8, self.high=31040.0, self.low=30100.0, self.vol=157092.883, self.amt=4807922575.68155 
2023-07-11 08:00:01,810:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230710   120000    155959  ...   22884.999  6.887192e+08 -0.001489
718  20230710   160000    195959  ...   37764.713  1.137725e+09  0.004037
719  20230710   200000    235959  ...   62189.014  1.880878e+09  0.002518
720  20230711   000000    035959  ...   91867.895  2.802292e+09  0.017391
721  20230711   040000    075959  ...  157092.883  4.807923e+09 -0.013875

[5 rows x 11 columns]
2023-07-11 08:00:03,182:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230710   120000    155959  1688975999  ...    717  0.361744  0.391610     NaN
718  20230710   160000    195959  1688990399  ...    718  0.289137  0.062660     NaN
719  20230710   200000    235959  1689004799  ...    719  0.000017 -1.233220    -1.0
720  20230711   000000    035959  1689019199  ...    720  0.047909 -1.006761    -1.0
721  20230711   040000    075959  1689033599  ...    721  0.028964 -1.074251    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.015', 'enterprice': '30303.5', 'countrevence': '0', 'unrealprofit': '-4951.601', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30396.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


