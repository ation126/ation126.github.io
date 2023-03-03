# 20230303 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [03/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27580
self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23421.0, self.close=23425.4, self.high=23430.0, self.low=23413.7, self.vol=885.24, self.amt=20732142.4378 
2023-03-03 08:20:01,683:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230303   075500    075959  ...         0.0        0.0       0
5856  20230303   080000    080459  ...         0.0        0.0       0
5857  20230303   080500    080959  ...         0.0        0.0       0
5858  20230303   081000    081459  ...         0.0        0.0       0
5859  20230303   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 08:20:01,684:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23421.0, self.close=23425.4, self.high=23430.0, self.low=23413.7, self.vol=885.24, self.amt=20732142.4378, ukdf['pct'].iloc[-1]=0.000188 , ukdf['amount'].iloc[-1]=20732142.4378, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-415009.8016', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23425.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [03/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=27581
self.closeSec=1677803099, self.tradeDate='20230303', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23425.4, self.close=23431.2, self.high=23445.0, self.low=23421.6, self.vol=708.539, self.amt=16603081.1025 
2023-03-03 08:25:01,626:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230303   080000    080459  ...         0.0        0.0       0
5857  20230303   080500    080959  ...         0.0        0.0       0
5858  20230303   081000    081459  ...         0.0        0.0       0
5859  20230303   081500    081959  ...         0.0        0.0       0
5860  20230303   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 08:25:01,626:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1677803099, self.tradeDate='20230303', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23425.4, self.close=23431.2, self.high=23445.0, self.low=23421.6, self.vol=708.539, self.amt=16603081.1025, ukdf['pct'].iloc[-1]=0.000248 , ukdf['amount'].iloc[-1]=16603081.1025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-415358.62599275712', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23431.69673612', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6050424426861896, self.count=28146 

self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23421.0, self.close=23425.4, self.high=23430.0, self.low=23413.7 
2023-03-03 08:20:01,622:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23421.0, self.close=23425.4, self.high=23430.0, self.low=23413.7   
2023-03-03 08:20:01,662:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230303   075500    075959  1677801599  ...  23444.1  0.000068   1535    5
1536  20230303   080000    080459  1677801899  ...  23448.3 -0.000375   1536    0
1537  20230303   080500    080959  1677802199  ...  23428.7 -0.000571   1537    1
1538  20230303   081000    081459  1677802499  ...  23421.0 -0.000593   1538    2
1539  20230303   081500    081959  1677802799  ...  23413.7  0.000188   1539    3

[5 rows x 11 columns]
2023-03-03 08:20:01,662:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6050424426861896, self.count=28147 

self.closeSec=1677803099, self.tradeDate='20230303', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23425.4, self.close=23431.2, self.high=23445.0, self.low=23421.6 
2023-03-03 08:25:01,523:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1677803099, self.tradeDate='20230303', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23425.4, self.close=23431.2, self.high=23445.0, self.low=23421.6   
2023-03-03 08:25:01,576:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230303   080000    080459  1677801899  ...  23448.3 -0.000375   1536    0
1537  20230303   080500    080959  1677802199  ...  23428.7 -0.000571   1537    1
1538  20230303   081000    081459  1677802499  ...  23421.0 -0.000593   1538    2
1539  20230303   081500    081959  1677802799  ...  23413.7  0.000188   1539    3
1540  20230303   082000    082459  1677803099  ...  23421.6  0.000248   1540    4

[5 rows x 11 columns]
2023-03-03 08:25:01,578:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-03 08:00:35,039:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230303    052959  23455.3  ...  50.416667  0.499533  0.667939
5771  20230303    055959  23443.3  ...  50.000000  0.488469  0.651703
5772  20230303    062959  23400.1  ...  50.000000  0.519094  0.614976
5773  20230303    065959  23522.4  ...  49.583333  0.501030  0.593430
5774  20230303    072959  23449.9  ...  49.166667  0.498547  0.575105

[5 rows x 33 columns]
0.5545286506469501
acc is : 0.5545286506469501
2023-03-03 08:00:35,210:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.508898  0.491102       0  ...  0.848333   1.0    0.0  0.950551
537     1  0.493023  0.506977       1  ...  0.852756   1.0    0.0  0.955507
538     0  0.543829  0.456171       0  ...  0.850146   1.0    0.0  0.952582
539     1  0.492280  0.507720       0  ...  0.849780   1.0    0.0  0.952172
540     0  0.505613  0.494387       1  ...  0.850404   1.0    0.0  0.952871

[5 rows x 10 columns]
2023-03-03 08:00:35,248:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.508479  0.491521       0  ...  0.827325   1.0    0.0  0.938549
46     1  0.492122  0.507878       1  ...  0.855926   1.0    0.0  0.937905
47     0  0.543701  0.456299       0  ...  0.864964   1.0    0.0  0.946274
48     1  0.492225  0.507775       0  ...  0.849780   1.0    0.0  0.952172
49     0  0.505613  0.494387       1  ...  0.850404   1.0    0.0  0.952871

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '32.245', 'enterprice': '23469.3', 'countrevence': '0', 'unrealprofit': '-232.164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '23462.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230303   075000    075959  1677801599  23442.9  23457.1  0.000606
2023-03-03 08:00:02,025:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14072 

self.closeSec=1677802199, self.tradeDate='20230303', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23457.1', self.close='23434.9'
2023-03-03 08:10:01,772:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677802199, self.tradeDate='20230303', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23457.1', self.close='23434.9'
127.0.0.1 - - [03/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-03 08:10:01,803:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230303   072000    072959  1677799799  23475.6  23439.9 -0.001516
621  20230303   073000    073959  1677800399    23440  23466.4  0.001131
622  20230303   074000    074959  1677800999  23466.4  23442.9 -0.001001
623  20230303   075000    075959  1677801599  23442.9  23457.1  0.000606
624  20230303   080000    080959  1677802199  23457.1  23434.9 -0.000946
2023-03-03 08:10:01,803:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14073 

self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23434.7', self.close='23425.4'
2023-03-03 08:20:01,722:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23434.7', self.close='23425.4'
127.0.0.1 - - [03/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-03 08:20:01,764:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230303   073000    073959  1677800399    23440  23466.4  0.001131
622  20230303   074000    074959  1677800999  23466.4  23442.9 -0.001001
623  20230303   075000    075959  1677801599  23442.9  23457.1  0.000606
624  20230303   080000    080959  1677802199  23457.1  23434.9 -0.000946
625  20230303   081000    081959  1677802799  23434.7  23425.4 -0.000405
2023-03-03 08:20:01,764:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230303   075000    075959  1677801599  23442.9  23457.1
2023-03-03 08:00:02,097:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14073 

self.closeSec=1677802199, self.tradeDate='20230303', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23457.1', self.close='23434.9'
2023-03-03 08:10:01,763:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677802199, self.tradeDate='20230303', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23457.1', self.close='23434.9'
2023-03-03 08:10:01,823:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230303   072000    072959  1677799799  23475.6  23439.9
17469  20230303   073000    073959  1677800399    23440  23466.4
17470  20230303   074000    074959  1677800999  23466.4  23442.9
17471  20230303   075000    075959  1677801599  23442.9  23457.1
17472  20230303   080000    080959  1677802199  23457.1  23434.9
2023-03-03 08:10:01,823:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14074 

self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23434.7', self.close='23425.4'
2023-03-03 08:20:01,751:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23434.7', self.close='23425.4'
127.0.0.1 - - [03/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-03 08:20:01,786:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230303   073000    073959  1677800399    23440  23466.4
17470  20230303   074000    074959  1677800999  23466.4  23442.9
17471  20230303   075000    075959  1677801599  23442.9  23457.1
17472  20230303   080000    080959  1677802199  23457.1  23434.9
17473  20230303   081000    081959  1677802799  23434.7  23425.4
2023-03-03 08:20:01,786:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230303   075000    075959  1677801599  23442.9  23457.1
2023-03-03 08:00:02,105:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14073 

self.closeSec=1677802199, self.tradeDate='20230303', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='23457.1', self.close='23434.9'
2023-03-03 08:10:01,721:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677802199, self.tradeDate='20230303', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='23457.1', self.close='23434.9'
127.0.0.1 - - [03/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-03 08:10:01,827:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230303   072000    072959  1677799799  23475.6  23439.9
12141  20230303   073000    073959  1677800399    23440  23466.4
12142  20230303   074000    074959  1677800999  23466.4  23442.9
12143  20230303   075000    075959  1677801599  23442.9  23457.1
12144  20230303   080000    080959  1677802199  23457.1  23434.9
2023-03-03 08:10:01,827:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14074 

self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='23434.7', self.close='23425.4'
2023-03-03 08:20:01,744:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='23434.7', self.close='23425.4'
127.0.0.1 - - [03/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-03 08:20:01,780:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230303   073000    073959  1677800399    23440  23466.4
12142  20230303   074000    074959  1677800999  23466.4  23442.9
12143  20230303   075000    075959  1677801599  23442.9  23457.1
12144  20230303   080000    080959  1677802199  23457.1  23434.9
12145  20230303   081000    081959  1677802799  23434.7  23425.4
2023-03-03 08:20:01,784:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [03/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23578
self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=23421.0, self.close=23425.4, self.high=23430.0, self.low=23413.7, self.vol=885.24, self.amt=20732142.4378 
2023-03-03 08:20:01,795:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230303   075500    075959  ...         0.0        0.0       0
5856  20230303   080000    080459  ...         0.0        0.0       0
5857  20230303   080500    080959  ...         0.0        0.0       0
5858  20230303   081000    081459  ...         0.0        0.0       0
5859  20230303   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 08:20:01,796:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677802799, self.tradeDate='20230303', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=23421.0, self.close=23425.4, self.high=23430.0, self.low=23413.7, self.vol=885.24, self.amt=20732142.4378, ukdf['pct'].iloc[-1]=0.000188 , ukdf['amount'].iloc[-1]=20732142.4378, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=23579
self.closeSec=1677803099, self.tradeDate='20230303', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=23425.4, self.close=23431.2, self.high=23445.0, self.low=23421.6, self.vol=708.539, self.amt=16603081.1025 
2023-03-03 08:25:01,594:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230303   080000    080459  ...         0.0        0.0       0
5857  20230303   080500    080959  ...         0.0        0.0       0
5858  20230303   081000    081459  ...         0.0        0.0       0
5859  20230303   081500    081959  ...         0.0        0.0       0
5860  20230303   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-03 08:25:01,595:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1677803099, self.tradeDate='20230303', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=23425.4, self.close=23431.2, self.high=23445.0, self.low=23421.6, self.vol=708.539, self.amt=16603081.1025, ukdf['pct'].iloc[-1]=0.000248 , ukdf['amount'].iloc[-1]=16603081.1025, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230302   200000    235959  1677772799  ...    719  0.467245 -0.693599    -1.0
720  20230303   000000    035959  1677787199  ...    720  0.423103 -0.803330    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '-4609.569', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23459.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [03/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=586
self.closeSec=1677801599, self.tradeDate='20230303', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=23456.7, self.close=23457.1, self.high=23560.0, self.low=23372.2, self.vol=52550.701, self.amt=1233292013.0791 
2023-03-03 08:00:01,918:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1677801599, self.tradeDate='20230303', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=23456.7, self.close=23457.1, self.high=23560.0, self.low=23372.2, self.vol=52550.701, self.amt=1233292013.0791 
2023-03-03 08:00:01,957:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230302   120000    155959  ...   49671.496  1.163425e+09 -0.004479
718  20230302   160000    195959  ...   48950.758  1.145241e+09  0.001014
719  20230302   200000    235959  ...  124403.213  2.899906e+09 -0.002363
720  20230303   000000    035959  ...   77176.896  1.803088e+09  0.004552
721  20230303   040000    075959  ...   52550.701  1.233292e+09  0.000021

[5 rows x 11 columns]
2023-03-03 08:00:04,671:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230302   120000    155959  1677743999  ...    717  0.643526 -0.179710     NaN
718  20230302   160000    195959  1677758399  ...    718  0.511077 -0.571254     NaN
719  20230302   200000    235959  1677772799  ...    719  0.467245 -0.693599    -1.0
720  20230303   000000    035959  1677787199  ...    720  0.423103 -0.803330    -1.0
721  20230303   040000    075959  1677801599  ...    721  0.409550 -0.830516    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '-4500.018', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '23457.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


