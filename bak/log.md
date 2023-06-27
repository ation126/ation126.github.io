# 20230627 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12640
self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30236.2, self.close=30283.0, self.high=30290.0, self.low=30236.1, self.vol=1002.763, self.amt=30355415.9513 
127.0.0.1 - - [27/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-27 08:20:07,970:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230627   075500    075959  ...         0.0        0.0       0
5856  20230627   080000    080459  ...         0.0        0.0       0
5857  20230627   080500    080959  ...         0.0        0.0       0
5858  20230627   081000    081459  ...         0.0        0.0       0
5859  20230627   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 08:20:08,009:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30236.2, self.close=30283.0, self.high=30290.0, self.low=30236.1, self.vol=1002.763, self.amt=30355415.9513, ukdf['pct'].iloc[-1]=0.001548 , ukdf['amount'].iloc[-1]=30355415.9513, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47591.770776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30282.376', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12641
self.closeSec=1687825499, self.tradeDate='20230627', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30283.1, self.close=30265.1, self.high=30289.5, self.low=30261.6, self.vol=661.199, self.amt=20017993.7514 
127.0.0.1 - - [27/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-27 08:25:00,811:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230627   080000    080459  ...         0.0        0.0       0
5857  20230627   080500    080959  ...         0.0        0.0       0
5858  20230627   081000    081459  ...         0.0        0.0       0
5859  20230627   081500    081959  ...         0.0        0.0       0
5860  20230627   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 08:25:00,811:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687825499, self.tradeDate='20230627', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30283.1, self.close=30265.1, self.high=30289.5, self.low=30261.6, self.vol=661.199, self.amt=20017993.7514, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=20017993.7514, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-47396.86958699484', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30268.38051034', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30236.2, self.close=30283.0, self.high=30290.0, self.low=30236.1 
127.0.0.1 - - [27/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-27 08:20:05,219:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30236.2, self.close=30283.0, self.high=30290.0, self.low=30236.1   
2023-06-27 08:20:06,840:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230627   075500    075959  1687823999  ...  30256.4 -0.000126   1535    5
1536  20230627   080000    080459  1687824299  ...  30233.0 -0.000268   1536    0
1537  20230627   080500    080959  1687824599  ...  30220.0 -0.000261   1537    1
1538  20230627   081000    081459  1687824899  ...  30223.2 -0.000261   1538    2
1539  20230627   081500    081959  1687825199  ...  30236.1  0.001548   1539    3

[5 rows x 11 columns]
2023-06-27 08:20:06,850:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6465515034849921, self.count=12643 

self.closeSec=1687825499, self.tradeDate='20230627', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30283.1, self.close=30265.1, self.high=30289.5, self.low=30261.6 
127.0.0.1 - - [27/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-27 08:25:00,740:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687825499, self.tradeDate='20230627', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30283.1, self.close=30265.1, self.high=30289.5, self.low=30261.6   
2023-06-27 08:25:00,766:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230627   080000    080459  1687824299  ...  30233.0 -0.000268   1536    0
1537  20230627   080500    080959  1687824599  ...  30220.0 -0.000261   1537    1
1538  20230627   081000    081459  1687824899  ...  30223.2 -0.000261   1538    2
1539  20230627   081500    081959  1687825199  ...  30236.1  0.001548   1539    3
1540  20230627   082000    082459  1687825499  ...  30261.6 -0.000591   1540    4

[5 rows x 11 columns]
2023-06-27 08:25:00,766:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-27 08:00:18,522:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...  alpha58   alpha67   alpha72
5770  20230627    052959  30150.1  ...     47.5  0.470420  0.559182
5771  20230627    055959  30196.3  ...     47.5  0.462838  0.566602
5772  20230627    062959  30146.2  ...     47.5  0.466906  0.571538
5773  20230627    065959  30169.4  ...     47.5  0.475896  0.571727
5774  20230627    072959  30220.9  ...     47.5  0.477154  0.571285

[5 rows x 33 columns]
0.5415896487985212
acc is : 0.5415896487985212
2023-06-27 08:00:18,620:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.500511  0.499489       0  ...  1.141728  -1.0    0.0  1.205347
537     1  0.492465  0.507535       1  ...  1.140849  -1.0    0.0  1.206274
538     1  0.495583  0.504417       1  ...  1.138901  -1.0    0.0  1.208333
539     0  0.502833  0.497167       1  ...  1.138630  -1.0    0.0  1.208621
540     0  0.503225  0.496775       1  ...  1.137425  -1.0    0.0  1.209901

[5 rows x 10 columns]
2023-06-27 08:00:18,640:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500521  0.499479       0  ...  1.141728  -1.0    0.0  1.208342
46     1  0.492500  0.507500       1  ...  1.140849  -1.0    0.0  1.207080
47     1  0.495591  0.504409       1  ...  1.138901  -1.0    0.0  1.209266
48     0  0.502833  0.497167       1  ...  1.138630  -1.0    0.0  1.208621
49     0  0.503225  0.496775       1  ...  1.137425  -1.0    0.0  1.209901

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.381', 'enterprice': '30103.1', 'countrevence': '0', 'unrealprofit': '-4359.0552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30262.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230627   075000    075959  1687823999  30276.4  30260.1 -0.000542
2023-06-27 08:00:02,144:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6320 

self.closeSec=1687824599, self.tradeDate='20230627', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30260.1', self.close='30244.1'
2023-06-27 08:10:01,123:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687824599, self.tradeDate='20230627', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30260.1', self.close='30244.1'
127.0.0.1 - - [27/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-27 08:10:01,145:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230627   072000    072959  1687822199  30200.6  30228.1  0.000911
621  20230627   073000    073959  1687822799  30228.1  30234.9  0.000225
622  20230627   074000    074959  1687823399    30235  30276.5  0.001376
623  20230627   075000    075959  1687823999  30276.4  30260.1 -0.000542
624  20230627   080000    080959  1687824599  30260.1  30244.1 -0.000529
2023-06-27 08:10:01,149:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6321 

self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30244.1', self.close='30283'
127.0.0.1 - - [27/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-27 08:20:07,639:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30244.1', self.close='30283'
2023-06-27 08:20:08,399:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230627   073000    073959  1687822799  30228.1  30234.9  0.000225
622  20230627   074000    074959  1687823399    30235  30276.5  0.001376
623  20230627   075000    075959  1687823999  30276.4  30260.1 -0.000542
624  20230627   080000    080959  1687824599  30260.1  30244.1 -0.000529
625  20230627   081000    081959  1687825199  30244.1    30283  0.001286
2023-06-27 08:20:08,399:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230627   075000    075959  1687823999  30276.4  30260.1
2023-06-27 08:00:02,158:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6323 

self.closeSec=1687824599, self.tradeDate='20230627', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30260.1', self.close='30244.1'
2023-06-27 08:10:01,142:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687824599, self.tradeDate='20230627', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30260.1', self.close='30244.1'
127.0.0.1 - - [27/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-27 08:10:01,156:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230627   072000    072959  1687822199  30200.6  30228.1
17469  20230627   073000    073959  1687822799  30228.1  30234.9
17470  20230627   074000    074959  1687823399    30235  30276.5
17471  20230627   075000    075959  1687823999  30276.4  30260.1
17472  20230627   080000    080959  1687824599  30260.1  30244.1
2023-06-27 08:10:01,156:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6324 

self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30244.1', self.close='30283'
127.0.0.1 - - [27/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-27 08:20:09,920:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30244.1', self.close='30283'
2023-06-27 08:20:10,053:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230627   073000    073959  1687822799  30228.1  30234.9
17470  20230627   074000    074959  1687823399    30235  30276.5
17471  20230627   075000    075959  1687823999  30276.4  30260.1
17472  20230627   080000    080959  1687824599  30260.1  30244.1
17473  20230627   081000    081959  1687825199  30244.1    30283
2023-06-27 08:20:10,055:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230627   075000    075959  1687823999  30276.4  30260.1
2023-06-27 08:00:02,091:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [27/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6323 

self.closeSec=1687824599, self.tradeDate='20230627', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30260.1', self.close='30244.1'
2023-06-27 08:10:01,122:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687824599, self.tradeDate='20230627', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30260.1', self.close='30244.1'
2023-06-27 08:10:01,159:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230627   072000    072959  1687822199  30200.6  30228.1
12141  20230627   073000    073959  1687822799  30228.1  30234.9
12142  20230627   074000    074959  1687823399    30235  30276.5
12143  20230627   075000    075959  1687823999  30276.4  30260.1
12144  20230627   080000    080959  1687824599  30260.1  30244.1
2023-06-27 08:10:01,160:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6324 

self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30244.1', self.close='30283'
127.0.0.1 - - [27/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-27 08:20:09,374:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30244.1', self.close='30283'
2023-06-27 08:20:09,732:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230627   073000    073959  1687822799  30228.1  30234.9
12142  20230627   074000    074959  1687823399    30235  30276.5
12143  20230627   075000    075959  1687823999  30276.4  30260.1
12144  20230627   080000    080959  1687824599  30260.1  30244.1
12145  20230627   081000    081959  1687825199  30244.1    30283
2023-06-27 08:20:09,739:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12640
self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30236.2, self.close=30283.0, self.high=30290.0, self.low=30236.1, self.vol=1002.763, self.amt=30355415.9513 
127.0.0.1 - - [27/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-27 08:20:07,961:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230627   075500    075959  ...         0.0        0.0       0
5856  20230627   080000    080459  ...         0.0        0.0       0
5857  20230627   080500    080959  ...         0.0        0.0       0
5858  20230627   081000    081459  ...         0.0        0.0       0
5859  20230627   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 08:20:08,010:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687825199, self.tradeDate='20230627', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30236.2, self.close=30283.0, self.high=30290.0, self.low=30236.1, self.vol=1002.763, self.amt=30355415.9513, ukdf['pct'].iloc[-1]=0.001548 , ukdf['amount'].iloc[-1]=30355415.9513, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127704.723016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30282.376', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12641
self.closeSec=1687825499, self.tradeDate='20230627', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30283.1, self.close=30265.1, self.high=30289.5, self.low=30261.6, self.vol=661.199, self.amt=20017993.7514 
127.0.0.1 - - [27/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-27 08:25:00,797:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230627   080000    080459  ...         0.0        0.0       0
5857  20230627   080500    080959  ...         0.0        0.0       0
5858  20230627   081000    081459  ...         0.0        0.0       0
5859  20230627   081500    081959  ...         0.0        0.0       0
5860  20230627   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-27 08:25:00,797:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687825499, self.tradeDate='20230627', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30283.1, self.close=30265.1, self.high=30289.5, self.low=30261.6, self.vol=661.199, self.amt=20017993.7514, ukdf['pct'].iloc[-1]=-0.000591 , ukdf['amount'].iloc[-1]=20017993.7514, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '127184.91653453794', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30268.38051034', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230626   200000    235959  1687795199  ...    719  0.179621 -1.091527    -1.0
720  20230627   000000    035959  1687809599  ...    720  0.227606 -0.948147    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '25217.0712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30233.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [27/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=263
self.closeSec=1687823999, self.tradeDate='20230627', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30233.9, self.close=30260.1, self.high=30283.8, self.low=30086.1, self.vol=28608.033, self.amt=863849375.7464 
2023-06-27 08:00:01,718:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687823999, self.tradeDate='20230627', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30233.9, self.close=30260.1, self.high=30283.8, self.low=30086.1, self.vol=28608.033, self.amt=863849375.7464 
2023-06-27 08:00:01,729:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230626   120000    155959  ...   60412.330  1.834276e+09  0.003652
718  20230626   160000    195959  ...   45961.531  1.391983e+09 -0.002648
719  20230626   200000    235959  ...   86040.677  2.618050e+09  0.002817
720  20230627   000000    035959  ...  106775.619  3.216007e+09 -0.005480
721  20230627   040000    075959  ...   28608.033  8.638494e+08  0.000867

[5 rows x 11 columns]
2023-06-27 08:00:02,834:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230626   120000    155959  1687766399  ...    717  0.211291 -1.035406    -1.0
718  20230626   160000    195959  1687780799  ...    718  0.203232 -1.043268    -1.0
719  20230626   200000    235959  1687795199  ...    719  0.179621 -1.091527    -1.0
720  20230627   000000    035959  1687809599  ...    720  0.227606 -0.948147    -1.0
721  20230627   040000    075959  1687823999  ...    721  0.210680 -0.981612    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '23805.4692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30260.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


