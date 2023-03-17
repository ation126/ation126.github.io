# 20230317 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31612
self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24960.1, self.close=24975.2, self.high=24975.2, self.low=24925.0, self.vol=1086.715, self.amt=27113213.16 
127.0.0.1 - - [17/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-17 08:20:09,396:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230317   075500    075959  ...         0.0        0.0       0
5856  20230317   080000    080459  ...         0.0        0.0       0
5857  20230317   080500    080959  ...         0.0        0.0       0
5858  20230317   081000    081459  ...         0.0        0.0       0
5859  20230317   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 08:20:09,426:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24960.1, self.close=24975.2, self.high=24975.2, self.low=24925.0, self.vol=1086.715, self.amt=27113213.16, ukdf['pct'].iloc[-1]=0.000601 , ukdf['amount'].iloc[-1]=27113213.16, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-508071.9856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24972.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--: 127.0.0.1 - - [17/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
 version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=31613
self.closeSec=1679012699, self.tradeDate='20230317', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24975.2, self.close=24980.3, self.high=24980.5, self.low=24951.4, self.vol=929.458, self.amt=23207740.1518 
2023-03-17 08:25:01,648:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230317   080000    080459  ...         0.0        0.0       0
5857  20230317   080500    080959  ...         0.0        0.0       0
5858  20230317   081000    081459  ...         0.0        0.0       0
5859  20230317   081500    081959  ...         0.0        0.0       0
5860  20230317   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 08:25:01,650:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679012699, self.tradeDate='20230317', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24975.2, self.close=24980.3, self.high=24980.5, self.low=24951.4, self.vol=929.458, self.amt=23207740.1518, ukdf['pct'].iloc[-1]=0.000204 , ukdf['amount'].iloc[-1]=23207740.1518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-508547.376', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '24980.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24960.1, self.close=24975.2, self.high=24975.2, self.low=24925.0 
127.0.0.1 - - [17/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-17 08:20:04,490:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24960.1, self.close=24975.2, self.high=24975.2, self.low=24925.0   
2023-03-17 08:20:06,211:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230317   075500    075959  1679011199  ...  24973.6 -0.000464   1535    5
1536  20230317   080000    080459  1679011499  ...  24952.8 -0.000352   1536    0
1537  20230317   080500    080959  1679011799  ...  24952.8 -0.000528   1537    1
1538  20230317   081000    081459  1679012099  ...  24938.4 -0.000328   1538    2
1539  20230317   081500    081959  1679012399  ...  24925.0  0.000601   1539    3

[5 rows x 11 columns]
2023-03-17 08:20:06,220:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [17/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=29, self.factor=0.40602560148731587, self.count=32179 

self.closeSec=1679012699, self.tradeDate='20230317', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24975.2, self.close=24980.3, self.high=24980.5, self.low=24951.4 
2023-03-17 08:25:01,503:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679012699, self.tradeDate='20230317', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24975.2, self.close=24980.3, self.high=24980.5, self.low=24951.4   
2023-03-17 08:25:01,523:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230317   080000    080459  1679011499  ...  24952.8 -0.000352   1536    0
1537  20230317   080500    080959  1679011799  ...  24952.8 -0.000528   1537    1
1538  20230317   081000    081459  1679012099  ...  24938.4 -0.000328   1538    2
1539  20230317   081500    081959  1679012399  ...  24925.0  0.000601   1539    3
1540  20230317   082000    082459  1679012699  ...  24951.4  0.000204   1540    4

[5 rows x 11 columns]
2023-03-17 08:25:01,524:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-17 08:00:37,588:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230317    052959  24680.5  ...  52.500000  0.534517  0.344458
5771  20230317    055959  24830.0  ...  52.500000  0.541515  0.339564
5772  20230317    062959  24899.7  ...  52.083333  0.539837  0.335945
5773  20230317    065959  24885.4  ...  52.500000  0.548295  0.326944
5774  20230317    072959  24968.9  ...  52.083333  0.543522  0.321176

[5 rows x 33 columns]
0.5637707948243993
acc is : 0.5637707948243993
2023-03-17 08:00:37,868:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     0  0.572682  0.427318       1  ...  1.084968   1.0 -0.0016  1.110142
537     0  0.527806  0.472194       0  ...  1.084353   1.0  0.0000  1.109513
538     1  0.498102  0.501898       1  ...  1.087992   1.0  0.0000  1.113236
539     0  0.543309  0.456691       0  ...  1.086288   1.0  0.0000  1.111493
540     0  0.525160  0.474840       1  ...  1.088924   1.0  0.0000  1.114190

[5 rows x 10 columns]
2023-03-17 08:00:37,894:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     0  0.572867  0.427133       1  ...  1.084968   1.0 -0.0016  1.110380
46     0  0.527822  0.472178       0  ...  1.084353   1.0  0.0000  1.109603
47     1  0.497893  0.502107       1  ...  1.097499   1.0  0.0000  1.113033
48     0  0.544030  0.455970       0  ...  1.086288   1.0  0.0000  1.111493
49     0  0.525160  0.474840       1  ...  1.088924   1.0  0.0000  1.114190

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230317   075000    075959  1679011199    24989  24990.4  0.000056
2023-03-17 08:00:02,207:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16088 

self.closeSec=1679011799, self.tradeDate='20230317', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24990.5', self.close='24968.4'
2023-03-17 08:10:01,608:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679011799, self.tradeDate='20230317', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24990.5', self.close='24968.4'
2023-03-17 08:10:01,700:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230317   072000    072959  1679009399    24958  24929.9 -0.001126
621  20230317   073000    073959  1679009999    24930  24987.5  0.002310
622  20230317   074000    074959  1679010599  24987.8    24989  0.000060
623  20230317   075000    075959  1679011199    24989  24990.4  0.000056
624  20230317   080000    080959  1679011799  24990.5  24968.4 -0.000880
2023-03-17 08:10:01,705:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16089 

self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24968.4', self.close='24975.2'
127.0.0.1 - - [17/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-17 08:20:08,445:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24968.4', self.close='24975.2'
2023-03-17 08:20:09,676:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230317   073000    073959  1679009999    24930  24987.5  0.002310
622  20230317   074000    074959  1679010599  24987.8    24989  0.000060
623  20230317   075000    075959  1679011199    24989  24990.4  0.000056
624  20230317   080000    080959  1679011799  24990.5  24968.4 -0.000880
625  20230317   081000    081959  1679012399  24968.4  24975.2  0.000272
2023-03-17 08:20:09,685:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230317   075000    075959  1679011199    24989  24990.4
2023-03-17 08:00:02,225:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16089 

self.closeSec=1679011799, self.tradeDate='20230317', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24990.5', self.close='24968.4'
2023-03-17 08:10:01,636:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679011799, self.tradeDate='20230317', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24990.5', self.close='24968.4'
2023-03-17 08:10:01,677:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230317   072000    072959  1679009399    24958  24929.9
17469  20230317   073000    073959  1679009999    24930  24987.5
17470  20230317   074000    074959  1679010599  24987.8    24989
17471  20230317   075000    075959  1679011199    24989  24990.4
17472  20230317   080000    080959  1679011799  24990.5  24968.4
2023-03-17 08:10:01,679:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16090 

self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24968.4', self.close='24975.2'
127.0.0.1 - - [17/Mar/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-03-17 08:20:12,846:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24968.4', self.close='24975.2'
2023-03-17 08:20:13,030:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230317   073000    073959  1679009999    24930  24987.5
17470  20230317   074000    074959  1679010599  24987.8    24989
17471  20230317   075000    075959  1679011199    24989  24990.4
17472  20230317   080000    080959  1679011799  24990.5  24968.4
17473  20230317   081000    081959  1679012399  24968.4  24975.2
2023-03-17 08:20:13,031:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230317   075000    075959  1679011199    24989  24990.4
2023-03-17 08:00:02,214:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16089 

self.closeSec=1679011799, self.tradeDate='20230317', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='24990.5', self.close='24968.4'
2023-03-17 08:10:01,678:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679011799, self.tradeDate='20230317', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='24990.5', self.close='24968.4'
2023-03-17 08:10:01,713:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230317   072000    072959  1679009399    24958  24929.9
12141  20230317   073000    073959  1679009999    24930  24987.5
12142  20230317   074000    074959  1679010599  24987.8    24989
12143  20230317   075000    075959  1679011199    24989  24990.4
12144  20230317   080000    080959  1679011799  24990.5  24968.4
2023-03-17 08:10:01,713:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=16090 

self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='24968.4', self.close='24975.2'
127.0.0.1 - - [17/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-17 08:20:12,146:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='24968.4', self.close='24975.2'
2023-03-17 08:20:12,539:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230317   073000    073959  1679009999    24930  24987.5
12142  20230317   074000    074959  1679010599  24987.8    24989
12143  20230317   075000    075959  1679011199    24989  24990.4
12144  20230317   080000    080959  1679011799  24990.5  24968.4
12145  20230317   081000    081959  1679012399  24968.4  24975.2
2023-03-17 08:20:12,541:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27610
self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=24960.1, self.close=24975.2, self.high=24975.2, self.low=24925.0, self.vol=1086.715, self.amt=27113213.16 
127.0.0.1 - - [17/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-17 08:20:07,606:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230317   075500    075959  ...         0.0        0.0       0
5856  20230317   080000    080459  ...         0.0        0.0       0
5857  20230317   080500    080959  ...         0.0        0.0       0
5858  20230317   081000    081459  ...         0.0        0.0       0
5859  20230317   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 08:20:07,657:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679012399, self.tradeDate='20230317', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=24960.1, self.close=24975.2, self.high=24975.2, self.low=24925.0, self.vol=1086.715, self.amt=27113213.16, ukdf['pct'].iloc[-1]=0.000601 , ukdf['amount'].iloc[-1]=27113213.16, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=27611
self.closeSec=1679012699, self.tradeDate='20230317', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=24975.2, self.close=24980.3, self.high=24980.5, self.low=24951.4, self.vol=929.458, self.amt=23207740.1518 
127.0.0.1 - - [17/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-17 08:25:01,647:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230317   080000    080459  ...         0.0        0.0       0
5857  20230317   080500    080959  ...         0.0        0.0       0
5858  20230317   081000    081459  ...         0.0        0.0       0
5859  20230317   081500    081959  ...         0.0        0.0       0
5860  20230317   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-17 08:25:01,649:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679012699, self.tradeDate='20230317', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=24975.2, self.close=24980.3, self.high=24980.5, self.low=24951.4, self.vol=929.458, self.amt=23207740.1518, ukdf['pct'].iloc[-1]=0.000204 , ukdf['amount'].iloc[-1]=23207740.1518, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230316   200000    235959  1678982399  ...    719  0.754877  0.400662     NaN
720  20230317   000000    035959  1678996799  ...    720  0.608782 -0.022024     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '271733.37699032525', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24937.59295997', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1119287.34225, self.flagDict['side']='buy', self.tradeCount=24, self.count=670
self.closeSec=1679011199, self.tradeDate='20230317', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=24945.9, self.close=24990.4, self.high=25097.8, self.low=24602.5, self.vol=91673.471, self.amt=2279732825.14702 
127.0.0.1 - - [17/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-17 08:00:02,061:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679011199, self.tradeDate='20230317', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=24945.9, self.close=24990.4, self.high=25097.8, self.low=24602.5, self.vol=91673.471, self.amt=2279732825.14702 
2023-03-17 08:00:02,100:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230316   120000    155959  ...   88010.463  2.152492e+09  0.014115
718  20230316   160000    195959  ...  175784.630  4.349630e+09  0.008406
719  20230316   200000    235959  ...  182794.492  4.529335e+09  0.002385
720  20230317   000000    035959  ...  128630.721  3.194127e+09  0.002625
721  20230317   040000    075959  ...   91673.471  2.279733e+09  0.001784

[5 rows x 11 columns]
2023-03-17 08:00:04,660:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230316   120000    155959  1678953599  ...    717  0.936352  0.935144     1.0
718  20230316   160000    195959  1678967999  ...    718  0.861833  0.712518     1.0
719  20230316   200000    235959  1678982399  ...    719  0.754877  0.400662     NaN
720  20230317   000000    035959  1678996799  ...    720  0.608782 -0.022024     NaN
721  20230317   040000    075959  1679011199  ...    721  0.510269 -0.305711     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.825', 'enterprice': '20070', 'countrevence': '0', 'unrealprofit': '274724.792437634', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '24991.17854792', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


