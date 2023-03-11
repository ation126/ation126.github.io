# 20230311 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29884
self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20163.4, self.close=20145.7, self.high=20171.7, self.low=20142.6, self.vol=1140.278, self.amt=22983141.273 
127.0.0.1 - - [11/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-11 08:20:05,662:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230311   075500    075959  ...         0.0        0.0       0
5856  20230311   080000    080459  ...         0.0        0.0       0
5857  20230311   080500    080959  ...         0.0        0.0       0
5858  20230311   081000    081459  ...         0.0        0.0       0
5859  20230311   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 08:20:05,692:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20163.4, self.close=20145.7, self.high=20171.7, self.low=20142.6, self.vol=1140.278, self.amt=22983141.273, ukdf['pct'].iloc[-1]=-0.000873 , ukdf['amount'].iloc[-1]=22983141.273, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-217626.10874537744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20145.79343169', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [11/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29885
self.closeSec=1678494299, self.tradeDate='20230311', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20145.8, self.close=20180.8, self.high=20184.1, self.low=20143.7, self.vol=1074.345, self.amt=21666646.5183 
2023-03-11 08:25:01,554:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230311   080000    080459  ...         0.0        0.0       0
5857  20230311   080500    080959  ...         0.0        0.0       0
5858  20230311   081000    081459  ...         0.0        0.0       0
5859  20230311   081500    081959  ...         0.0        0.0       0
5860  20230311   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 08:25:01,554:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678494299, self.tradeDate='20230311', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20145.8, self.close=20180.8, self.high=20184.1, self.low=20143.7, self.vol=1074.345, self.amt=21666646.5183, ukdf['pct'].iloc[-1]=0.001742 , ukdf['amount'].iloc[-1]=21666646.5183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-219738.6816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20180.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20163.4, self.close=20145.7, self.high=20171.7, self.low=20142.6 
127.0.0.1 - - [11/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-11 08:20:03,392:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20163.4, self.close=20145.7, self.high=20171.7, self.low=20142.6   
2023-03-11 08:20:04,172:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230311   075500    075959  1678492799  ...  20117.8  0.000770   1535    5
1536  20230311   080000    080459  1678493099  ...  20132.3  0.002180   1536    0
1537  20230311   080500    080959  1678493399  ...  20124.8 -0.002552   1537    1
1538  20230311   081000    081459  1678493699  ...  20124.9  0.001520   1538    2
1539  20230311   081500    081959  1678493999  ...  20142.6 -0.000873   1539    3

[5 rows x 11 columns]
2023-03-11 08:20:04,173:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.699343394262834, self.count=30451 

self.closeSec=1678494299, self.tradeDate='20230311', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20145.8, self.close=20180.8, self.high=20184.1, self.low=20143.7 
127.0.0.1 - - [11/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-11 08:25:01,492:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678494299, self.tradeDate='20230311', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20145.8, self.close=20180.8, self.high=20184.1, self.low=20143.7   
2023-03-11 08:25:01,540:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230311   080000    080459  1678493099  ...  20132.3  0.002180   1536    0
1537  20230311   080500    080959  1678493399  ...  20124.8 -0.002552   1537    1
1538  20230311   081000    081459  1678493699  ...  20124.9  0.001520   1538    2
1539  20230311   081500    081959  1678493999  ...  20142.6 -0.000873   1539    3
1540  20230311   082000    082459  1678494299  ...  20143.7  0.001742   1540    4

[5 rows x 11 columns]
2023-03-11 08:25:01,541:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-11 08:00:33,589:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230311    052959  19958.2  ...  42.500000  0.396579  0.660394
5771  20230311    055959  19910.6  ...  42.500000  0.422808  0.636014
5772  20230311    062959  20069.2  ...  42.916667  0.426611  0.611224
5773  20230311    065959  20091.2  ...  42.500000  0.425886  0.588602
5774  20230311    072959  20087.0  ...  42.916667  0.433191  0.563659

[5 rows x 33 columns]
0.5508317929759704
acc is : 0.5508317929759704
2023-03-11 08:00:33,738:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.526117  0.473883       1  ...  0.872467   1.0    0.0  0.860357
537     0  0.633420  0.366580       1  ...  0.873497   1.0    0.0  0.861373
538     0  0.556265  0.443735       0  ...  0.873236   1.0    0.0  0.861116
539     0  0.541071  0.458929       1  ...  0.875175   1.0    0.0  0.863028
540     0  0.578331  0.421669       1  ...  0.875558   1.0    0.0  0.863405

[5 rows x 10 columns]
2023-03-11 08:00:33,776:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.526805  0.473195       1  ...  0.902754   1.0    0.0  0.852326
46     0  0.633110  0.366890       1  ...  0.872885   1.0    0.0  0.861960
47     0  0.556466  0.443534       0  ...  0.873236   1.0    0.0  0.859138
48     0  0.541455  0.458545       1  ...  0.875175   1.0    0.0  0.863028
49     0  0.578331  0.421669       1  ...  0.875558   1.0    0.0  0.863405

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '33.147', 'enterprice': '20165.8', 'countrevence': '0', 'unrealprofit': '-853.88302401489', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '20140.03950813', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230311   075000    075959  1678492799  20197.5  20140.3 -0.002832
2023-03-11 08:00:01,941:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [11/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15224 

self.closeSec=1678493399, self.tradeDate='20230311', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20140.3', self.close='20132.7'
2023-03-11 08:10:01,867:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678493399, self.tradeDate='20230311', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20140.3', self.close='20132.7'
2023-03-11 08:10:01,882:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230311   072000    072959  1678490999  20167.6  20131.5 -0.001795
621  20230311   073000    073959  1678491599  20131.5  20171.2  0.001972
622  20230311   074000    074959  1678492199  20171.2  20197.5  0.001304
623  20230311   075000    075959  1678492799  20197.5  20140.3 -0.002832
624  20230311   080000    080959  1678493399  20140.3  20132.7 -0.000377
2023-03-11 08:10:01,889:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15225 

self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20132.7', self.close='20145.7'
127.0.0.1 - - [11/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-11 08:20:05,203:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20132.7', self.close='20145.7'
2023-03-11 08:20:05,931:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230311   073000    073959  1678491599  20131.5  20171.2  0.001972
622  20230311   074000    074959  1678492199  20171.2  20197.5  0.001304
623  20230311   075000    075959  1678492799  20197.5  20140.3 -0.002832
624  20230311   080000    080959  1678493399  20140.3  20132.7 -0.000377
625  20230311   081000    081959  1678493999  20132.7  20145.7  0.000646
2023-03-11 08:20:05,932:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230311   075000    075959  1678492799  20197.5  20140.3
2023-03-11 08:00:01,953:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15225 

self.closeSec=1678493399, self.tradeDate='20230311', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20140.3', self.close='20132.7'
2023-03-11 08:10:01,888:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678493399, self.tradeDate='20230311', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20140.3', self.close='20132.7'
127.0.0.1 - - [11/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-11 08:10:01,902:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230311   072000    072959  1678490999  20167.6  20131.5
17469  20230311   073000    073959  1678491599  20131.5  20171.2
17470  20230311   074000    074959  1678492199  20171.2  20197.5
17471  20230311   075000    075959  1678492799  20197.5  20140.3
17472  20230311   080000    080959  1678493399  20140.3  20132.7
2023-03-11 08:10:01,902:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15226 

self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20132.7', self.close='20145.7'
127.0.0.1 - - [11/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-11 08:20:07,404:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20132.7', self.close='20145.7'
2023-03-11 08:20:07,611:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230311   073000    073959  1678491599  20131.5  20171.2
17470  20230311   074000    074959  1678492199  20171.2  20197.5
17471  20230311   075000    075959  1678492799  20197.5  20140.3
17472  20230311   080000    080959  1678493399  20140.3  20132.7
17473  20230311   081000    081959  1678493999  20132.7  20145.7
2023-03-11 08:20:07,612:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230311   075000    075959  1678492799  20197.5  20140.3
2023-03-11 08:00:01,951:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [11/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15225 

self.closeSec=1678493399, self.tradeDate='20230311', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='20140.3', self.close='20132.7'
2023-03-11 08:10:01,849:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678493399, self.tradeDate='20230311', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='20140.3', self.close='20132.7'
2023-03-11 08:10:01,859:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230311   072000    072959  1678490999  20167.6  20131.5
12141  20230311   073000    073959  1678491599  20131.5  20171.2
12142  20230311   074000    074959  1678492199  20171.2  20197.5
12143  20230311   075000    075959  1678492799  20197.5  20140.3
12144  20230311   080000    080959  1678493399  20140.3  20132.7
2023-03-11 08:10:01,860:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=15226 

self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='20132.7', self.close='20145.7'
127.0.0.1 - - [11/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-11 08:20:07,261:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='20132.7', self.close='20145.7'
2023-03-11 08:20:07,455:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230311   073000    073959  1678491599  20131.5  20171.2
12142  20230311   074000    074959  1678492199  20171.2  20197.5
12143  20230311   075000    075959  1678492799  20197.5  20140.3
12144  20230311   080000    080959  1678493399  20140.3  20132.7
12145  20230311   081000    081959  1678493999  20132.7  20145.7
2023-03-11 08:20:07,455:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25882
self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=20163.4, self.close=20145.7, self.high=20171.7, self.low=20142.6, self.vol=1140.278, self.amt=22983141.273 
127.0.0.1 - - [11/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-11 08:20:01,615:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230311   075500    075959  ...         0.0        0.0       0
5856  20230311   080000    080459  ...         0.0        0.0       0
5857  20230311   080500    080959  ...         0.0        0.0       0
5858  20230311   081000    081459  ...         0.0        0.0       0
5859  20230311   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 08:20:01,618:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678493999, self.tradeDate='20230311', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=20163.4, self.close=20145.7, self.high=20171.7, self.low=20142.6, self.vol=1140.278, self.amt=22983141.273, ukdf['pct'].iloc[-1]=-0.000873 , ukdf['amount'].iloc[-1]=22983141.273, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25883
self.closeSec=1678494299, self.tradeDate='20230311', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=20145.8, self.close=20180.8, self.high=20184.1, self.low=20143.7, self.vol=1074.345, self.amt=21666646.5183 
127.0.0.1 - - [11/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-11 08:25:01,574:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230311   080000    080459  ...         0.0        0.0       0
5857  20230311   080500    080959  ...         0.0        0.0       0
5858  20230311   081000    081459  ...         0.0        0.0       0
5859  20230311   081500    081959  ...         0.0        0.0       0
5860  20230311   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-11 08:25:01,574:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678494299, self.tradeDate='20230311', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=20145.8, self.close=20180.8, self.high=20184.1, self.low=20143.7, self.vol=1074.345, self.amt=21666646.5183, ukdf['pct'].iloc[-1]=0.001742 , ukdf['amount'].iloc[-1]=21666646.5183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230310   200000    235959  1678463999  ...    719  0.685910  0.452372     NaN
720  20230311   000000    035959  1678478399  ...    720  0.698359  0.488105     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '140575.0005', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20014', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [11/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=634
self.closeSec=1678492799, self.tradeDate='20230311', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=20014.5, self.close=20140.3, self.high=20232.5, self.low=19835.0, self.vol=104598.079, self.amt=2097184222.2481 
2023-03-11 08:00:01,807:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678492799, self.tradeDate='20230311', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=20014.5, self.close=20140.3, self.high=20232.5, self.low=19835.0, self.vol=104598.079, self.amt=2097184222.2481 
2023-03-11 08:00:01,886:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230310   120000    155959  ...  144189.872  2.872943e+09 -0.004950
718  20230310   160000    195959  ...  189712.340  3.747278e+09 -0.009673
719  20230310   200000    235959  ...  377610.370  7.536282e+09  0.012405
720  20230311   000000    035959  ...  193610.159  3.871005e+09  0.000810
721  20230311   040000    075959  ...  104598.079  2.097184e+09  0.006451

[5 rows x 11 columns]
2023-03-11 08:00:04,803:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230310   120000    155959  1678435199  ...    717  0.617270  0.229363     NaN
718  20230310   160000    195959  1678449599  ...    718  0.676288  0.426810     NaN
719  20230310   200000    235959  1678463999  ...    719  0.685910  0.452372     NaN
720  20230311   000000    035959  1678478399  ...    720  0.698359  0.488105     NaN
721  20230311   040000    075959  1678492799  ...    721  0.715669  0.541569     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '135200.22486853965', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '20141.56083141', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


