# 20230729 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21856
self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29307.1, self.close=29316.5, self.high=29316.5, self.low=29303.2, self.vol=244.887, self.amt=7177421.5261 
127.0.0.1 - - [29/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 08:20:05,163:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230729   075500    075959  ...         0.0        0.0       0
5856  20230729   080000    080459  ...         0.0        0.0       0
5857  20230729   080500    080959  ...         0.0        0.0       0
5858  20230729   081000    081459  ...         0.0        0.0       0
5859  20230729   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 08:20:05,181:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29307.1, self.close=29316.5, self.high=29316.5, self.low=29303.2, self.vol=244.887, self.amt=7177421.5261, ukdf['pct'].iloc[-1]=0.000321 , ukdf['amount'].iloc[-1]=7177421.5261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34140.9816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29316.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21857
self.closeSec=1690590299, self.tradeDate='20230729', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29316.4, self.close=29320.0, self.high=29324.7, self.low=29316.4, self.vol=296.609, self.amt=8696915.794 
127.0.0.1 - - [29/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-29 08:25:00,777:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230729   080000    080459  ...         0.0        0.0       0
5857  20230729   080500    080959  ...         0.0        0.0       0
5858  20230729   081000    081459  ...         0.0        0.0       0
5859  20230729   081500    081959  ...         0.0        0.0       0
5860  20230729   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 08:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690590299, self.tradeDate='20230729', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29316.4, self.close=29320.0, self.high=29324.7, self.low=29316.4, self.vol=296.609, self.amt=8696915.794, ukdf['pct'].iloc[-1]=0.000119 , ukdf['amount'].iloc[-1]=8696915.794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34229.40855982626', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29322.84977451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29307.1, self.close=29316.5, self.high=29316.5, self.low=29303.2 
127.0.0.1 - - [29/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 08:20:03,512:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29307.1, self.close=29316.5, self.high=29316.5, self.low=29303.2   
2023-07-29 08:20:04,552:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230729   075500    075959  1690588799  ...  29298.0 -0.000031   1535    5
1536  20230729   080000    080459  1690589099  ...  29280.6 -0.000314   1536    0
1537  20230729   080500    080959  1690589399  ...  29285.1  0.000072   1537    1
1538  20230729   081000    081459  1690589699  ...  29289.9  0.000485   1538    2
1539  20230729   081500    081959  1690589999  ...  29303.2  0.000321   1539    3

[5 rows x 11 columns]
2023-07-29 08:20:04,562:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=18, self.factor=0.5636607014253942, self.count=21859 

self.closeSec=1690590299, self.tradeDate='20230729', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29316.4, self.close=29320.0, self.high=29324.7, self.low=29316.4 
127.0.0.1 - - [29/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-29 08:25:00,744:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690590299, self.tradeDate='20230729', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29316.4, self.close=29320.0, self.high=29324.7, self.low=29316.4   
2023-07-29 08:25:00,757:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230729   080000    080459  1690589099  ...  29280.6 -0.000314   1536    0
1537  20230729   080500    080959  1690589399  ...  29285.1  0.000072   1537    1
1538  20230729   081000    081459  1690589699  ...  29289.9  0.000485   1538    2
1539  20230729   081500    081959  1690589999  ...  29303.2  0.000321   1539    3
1540  20230729   082000    082459  1690590299  ...  29316.4  0.000119   1540    4

[5 rows x 11 columns]
2023-07-29 08:25:00,757:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-29 08:00:18,033:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230729    052959  29329.9  ...  47.916667  0.525179  0.501787
5771  20230729    055959  29356.7  ...  47.916667  0.503590  0.505917
5772  20230729    062959  29297.4  ...  47.500000  0.502384  0.510307
5773  20230729    065959  29293.9  ...  47.083333  0.498407  0.516154
5774  20230729    072959  29282.8  ...  47.083333  0.506311  0.518143

[5 rows x 33 columns]
0.5711645101663586
acc is : 0.5711645101663586
2023-07-29 08:00:18,123:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.512273  0.487727       0  ...  0.885711   1.0    0.0  0.972951
537     1  0.490185  0.509815       0  ...  0.885609   1.0    0.0  0.972838
538     1  0.499652  0.500348       0  ...  0.885273   1.0    0.0  0.972469
539     1  0.496667  0.503333       1  ...  0.885938   1.0    0.0  0.973200
540     0  0.503560  0.496440       0  ...  0.885790   1.0    0.0  0.973037

[5 rows x 10 columns]
2023-07-29 08:00:18,142:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.512144  0.487856       0  ...  0.923016   1.0    0.0  0.971286
46     1  0.489850  0.510150       0  ...  0.922909   1.0    0.0  0.970768
47     1  0.499537  0.500463       0  ...  0.922559   1.0    0.0  0.972014
48     1  0.496765  0.503235       1  ...  0.885938   1.0    0.0  0.973200
49     0  0.503560  0.496440       0  ...  0.885790   1.0    0.0  0.973037

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-4272.5923503877', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29298.61498235', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230729   075000    075959  1690588799  29303.1  29299.9 -0.000109
2023-07-29 08:00:02,452:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10928 

self.closeSec=1690589399, self.tradeDate='20230729', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29300', self.close='29292.9'
2023-07-29 08:10:01,174:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690589399, self.tradeDate='20230729', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29300', self.close='29292.9'
127.0.0.1 - - [29/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-29 08:10:01,180:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230729   072000    072959  1690586999  29291.2  29304.8  0.000464
621  20230729   073000    073959  1690587599  29304.8  29311.3  0.000222
622  20230729   074000    074959  1690588199  29311.4  29303.1 -0.000280
623  20230729   075000    075959  1690588799  29303.1  29299.9 -0.000109
624  20230729   080000    080959  1690589399    29300  29292.9 -0.000239
2023-07-29 08:10:01,180:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10929 

self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29292.9', self.close='29316.5'
127.0.0.1 - - [29/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 08:20:06,081:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29292.9', self.close='29316.5'
2023-07-29 08:20:06,432:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230729   073000    073959  1690587599  29304.8  29311.3  0.000222
622  20230729   074000    074959  1690588199  29311.4  29303.1 -0.000280
623  20230729   075000    075959  1690588799  29303.1  29299.9 -0.000109
624  20230729   080000    080959  1690589399    29300  29292.9 -0.000239
625  20230729   081000    081959  1690589999  29292.9  29316.5  0.000806
2023-07-29 08:20:06,433:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230729   075000    075959  1690588799  29303.1  29299.9
2023-07-29 08:00:02,473:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10931 

self.closeSec=1690589399, self.tradeDate='20230729', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29300', self.close='29292.9'
2023-07-29 08:10:01,188:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690589399, self.tradeDate='20230729', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29300', self.close='29292.9'
2023-07-29 08:10:01,197:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230729   072000    072959  1690586999  29291.2  29304.8
17469  20230729   073000    073959  1690587599  29304.8  29311.3
17470  20230729   074000    074959  1690588199  29311.4  29303.1
17471  20230729   075000    075959  1690588799  29303.1  29299.9
17472  20230729   080000    080959  1690589399    29300  29292.9
2023-07-29 08:10:01,197:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10932 

self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29292.9', self.close='29316.5'
127.0.0.1 - - [29/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 08:20:07,254:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29292.9', self.close='29316.5'
2023-07-29 08:20:07,391:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230729   073000    073959  1690587599  29304.8  29311.3
17470  20230729   074000    074959  1690588199  29311.4  29303.1
17471  20230729   075000    075959  1690588799  29303.1  29299.9
17472  20230729   080000    080959  1690589399    29300  29292.9
17473  20230729   081000    081959  1690589999  29292.9  29316.5
2023-07-29 08:20:07,392:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230729   075000    075959  1690588799  29303.1  29299.9
2023-07-29 08:00:02,455:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [29/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10931 

self.closeSec=1690589399, self.tradeDate='20230729', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29300', self.close='29292.9'
2023-07-29 08:10:01,178:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690589399, self.tradeDate='20230729', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29300', self.close='29292.9'
2023-07-29 08:10:01,190:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230729   072000    072959  1690586999  29291.2  29304.8
12141  20230729   073000    073959  1690587599  29304.8  29311.3
12142  20230729   074000    074959  1690588199  29311.4  29303.1
12143  20230729   075000    075959  1690588799  29303.1  29299.9
12144  20230729   080000    080959  1690589399    29300  29292.9
2023-07-29 08:10:01,190:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10932 

self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29292.9', self.close='29316.5'
127.0.0.1 - - [29/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 08:20:07,135:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29292.9', self.close='29316.5'
2023-07-29 08:20:07,274:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230729   073000    073959  1690587599  29304.8  29311.3
12142  20230729   074000    074959  1690588199  29311.4  29303.1
12143  20230729   075000    075959  1690588799  29303.1  29299.9
12144  20230729   080000    080959  1690589399    29300  29292.9
12145  20230729   081000    081959  1690589999  29292.9  29316.5
2023-07-29 08:20:07,274:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21856
self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29307.1, self.close=29316.5, self.high=29316.5, self.low=29303.2, self.vol=244.887, self.amt=7177421.5261 
127.0.0.1 - - [29/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 08:20:05,162:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230729   075500    075959  ...         0.0        0.0       0
5856  20230729   080000    080459  ...         0.0        0.0       0
5857  20230729   080500    080959  ...         0.0        0.0       0
5858  20230729   081000    081459  ...         0.0        0.0       0
5859  20230729   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 08:20:05,181:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690589999, self.tradeDate='20230729', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29307.1, self.close=29316.5, self.high=29316.5, self.low=29303.2, self.vol=244.887, self.amt=7177421.5261, ukdf['pct'].iloc[-1]=0.000321 , ukdf['amount'].iloc[-1]=7177421.5261, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '91831.1225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29316.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21857
self.closeSec=1690590299, self.tradeDate='20230729', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29316.4, self.close=29320.0, self.high=29324.7, self.low=29316.4, self.vol=296.609, self.amt=8696915.794 
127.0.0.1 - - [29/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-29 08:25:00,778:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230729   080000    080459  ...         0.0        0.0       0
5857  20230729   080500    080959  ...         0.0        0.0       0
5858  20230729   081000    081459  ...         0.0        0.0       0
5859  20230729   081500    081959  ...         0.0        0.0       0
5860  20230729   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 08:25:00,778:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690590299, self.tradeDate='20230729', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29316.4, self.close=29320.0, self.high=29324.7, self.low=29316.4, self.vol=296.609, self.amt=8696915.794, ukdf['pct'].iloc[-1]=0.000119 , ukdf['amount'].iloc[-1]=8696915.794, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '92066.95947507591', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29322.84977451', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

2023-07-29 04:00:11,110:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42755F1690574405498I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690574405904158, 'quantity': '54.767', 'price': '29296.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690574404596, 'updatetime': 1690574405904, 'tradetype': 'usdt', 'selfid': 42755, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690574405904, 'clientorderid': '42755F1690574405498I0L65', 'price': '29296.3', 'quantity': '54.767', 'commission': '1604.4704621', 'commissionasset': 'USDT', 'tradetime': 1690574405904, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690574405904}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-29 04:00:11,111:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42755F1690574405498I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690574405904158, 'quantity': '54.767', 'price': '29296.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690574404596, 'updatetime': 1690574405904, 'tradetype': 'usdt', 'selfid': 42755, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690574405904, 'clientorderid': '42755F1690574405498I0L65', 'price': '29296.3', 'quantity': '54.767', 'commission': '1604.4704621', 'commissionasset': 'USDT', 'tradetime': 1690574405904, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690574405904}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jul/2023 04:00:11] "POST / HTTP/1.1" 200 -
2023-07-29 04:00:11,511:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42756F1690574411060I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690574411463905, 'quantity': '54.079', 'price': '29300.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690574410586, 'updatetime': 1690574411463, 'tradetype': 'usdt', 'selfid': 42756, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690574411463, 'clientorderid': '42756F1690574411060I0L65', 'price': '29300.8', 'quantity': '54.079', 'commission': '1584.5579632', 'commissionasset': 'USDT', 'tradetime': 1690574411463, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690574411463}], 'gatetype': 'simulator', 'handletime': 0}
2023-07-29 04:00:11,693:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42756F1690574411060I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1690574411463905, 'quantity': '54.079', 'price': '29300.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1690574410586, 'updatetime': 1690574411463, 'tradetype': 'usdt', 'selfid': 42756, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1690574411463, 'clientorderid': '42756F1690574411060I0L65', 'price': '29300.8', 'quantity': '54.079', 'commission': '1584.5579632', 'commissionasset': 'USDT', 'tradetime': 1690574411463, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1690574411463}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [29/Jul/2023 04:00:11] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [29/Jul/2023 08:00:02] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1582973.4052368, self.flagDict['side']='buy', self.tradeCount=15, self.count=455
self.closeSec=1690588799, self.tradeDate='20230729', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29303.5, self.close=29299.9, self.high=29358.0, self.low=29267.3, self.vol=12323.584, self.amt=361165133.4304 
2023-07-29 08:00:02,006:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690588799, self.tradeDate='20230729', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29303.5, self.close=29299.9, self.high=29358.0, self.low=29267.3, self.vol=12323.584, self.amt=361165133.4304 
2023-07-29 08:00:02,019:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230728   120000    155959  ...  19221.001  5.608905e+08 -0.003861
718  20230728   160000    195959  ...  25255.902  7.368084e+08  0.002348
719  20230728   200000    235959  ...  93071.263  2.735679e+09  0.006292
720  20230729   000000    035959  ...  48155.711  1.410362e+09 -0.002573
721  20230729   040000    075959  ...  12323.584  3.611651e+08 -0.000119

[5 rows x 11 columns]
2023-07-29 08:00:02,731:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230728   120000    155959  1690531199  ...    717  0.114819 -1.076804    -1.0
718  20230728   160000    195959  1690545599  ...    718  0.014316 -1.429866    -1.0
719  20230728   200000    235959  1690559999  ...    719  0.330897 -0.233582     NaN
720  20230729   000000    035959  1690574399  ...    720  0.686406  1.131137     1.0
721  20230729   040000    075959  1690588799  ...    721  0.527794  0.581327     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.079', 'enterprice': '29300.8', 'countrevence': '0', 'unrealprofit': '-48.6711', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29299.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


