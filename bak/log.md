# 20230408 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37948
self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27877.8, self.close=27861.5, self.high=27895.0, self.low=27858.2, self.vol=1015.104, self.amt=28297054.9259 
127.0.0.1 - - [08/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 08:20:09,851:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230408   075500    075959  ...         0.0        0.0       0
5856  20230408   080000    080459  ...         0.0        0.0       0
5857  20230408   080500    080959  ...         0.0        0.0       0
5858  20230408   081000    081459  ...         0.0        0.0       0
5859  20230408   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 08:20:09,880:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27877.8, self.close=27861.5, self.high=27895.0, self.low=27858.2, self.vol=1015.104, self.amt=28297054.9259, ukdf['pct'].iloc[-1]=-0.000588 , ukdf['amount'].iloc[-1]=28297054.9259, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-682071.21676307152', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27863.90543677', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [08/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37949
self.closeSec=1680913499, self.tradeDate='20230408', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27861.5, self.close=27873.3, self.high=27880.9, self.low=27855.0, self.vol=485.676, self.amt=13532831.563 
2023-04-08 08:25:01,595:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230408   080000    080459  ...         0.0        0.0       0
5857  20230408   080500    080959  ...         0.0        0.0       0
5858  20230408   081000    081459  ...         0.0        0.0       0
5859  20230408   081500    081959  ...         0.0        0.0       0
5860  20230408   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 08:25:01,595:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680913499, self.tradeDate='20230408', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27861.5, self.close=27873.3, self.high=27880.9, self.low=27855.0, self.vol=485.676, self.amt=13532831.563, ukdf['pct'].iloc[-1]=0.000424 , ukdf['amount'].iloc[-1]=13532831.563, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-682680.1458837864', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27874.02457265', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27877.8, self.close=27861.5, self.high=27895.0, self.low=27858.2 
127.0.0.1 - - [08/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 08:20:07,571:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27877.8, self.close=27861.5, self.high=27895.0, self.low=27858.2   
2023-04-08 08:20:08,731:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230408   075500    075959  1680911999  ...  27888.2 -0.000047   1535    5
1536  20230408   080000    080459  1680912299  ...  27885.8  0.000029   1536    0
1537  20230408   080500    080959  1680912599  ...  27879.0 -0.000373   1537    1
1538  20230408   081000    081459  1680912899  ...  27875.0 -0.000115   1538    2
1539  20230408   081500    081959  1680913199  ...  27858.2 -0.000588   1539    3

[5 rows x 11 columns]
2023-04-08 08:20:08,740:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.5721932838923628, self.count=38515 

self.closeSec=1680913499, self.tradeDate='20230408', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27861.5, self.close=27873.3, self.high=27880.9, self.low=27855.0 
2023-04-08 08:25:01,502:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680913499, self.tradeDate='20230408', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27861.5, self.close=27873.3, self.high=27880.9, self.low=27855.0   
2023-04-08 08:25:01,560:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230408   080000    080459  1680912299  ...  27885.8  0.000029   1536    0
1537  20230408   080500    080959  1680912599  ...  27879.0 -0.000373   1537    1
1538  20230408   081000    081459  1680912899  ...  27875.0 -0.000115   1538    2
1539  20230408   081500    081959  1680913199  ...  27858.2 -0.000588   1539    3
1540  20230408   082000    082459  1680913499  ...  27855.0  0.000424   1540    4

[5 rows x 11 columns]
2023-04-08 08:25:01,561:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-08 08:00:33,620:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230408    052959  27852.6  ...  47.500000  0.470731  0.603736
5771  20230408    055959  27864.2  ...  47.916667  0.475206  0.602708
5772  20230408    062959  27881.2  ...  47.916667  0.472864  0.603083
5773  20230408    065959  27871.5  ...  47.916667  0.491905  0.587216
5774  20230408    072959  27943.7  ...  47.500000  0.479941  0.583376

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-04-08 08:00:33,771:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.520337  0.479663       1  ...  0.948200   1.0    0.0  1.033104
537     0  0.522815  0.477185       0  ...  0.947870   1.0    0.0  1.032745
538     0  0.516114  0.483886       1  ...  0.950329   1.0    0.0  1.035424
539     0  0.537755  0.462245       0  ...  0.948666   1.0    0.0  1.033612
540     0  0.511328  0.488672       0  ...  0.948526   1.0    0.0  1.033460

[5 rows x 10 columns]
2023-04-08 08:00:33,807:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520320  0.479680       1  ...  0.941139   1.0    0.0  1.036962
46     0  0.522396  0.477604       0  ...  0.947870   1.0    0.0  1.025936
47     0  0.516139  0.483861       1  ...  0.950329   1.0    0.0  1.029791
48     0  0.538232  0.461768       0  ...  0.948666   1.0    0.0  1.033612
49     0  0.511328  0.488672       0  ...  0.948526   1.0    0.0  1.033460

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230408   075000    075959  1680911999  27903.1  27890.7 -0.000444
2023-04-08 08:00:01,867:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19256 

self.closeSec=1680912599, self.tradeDate='20230408', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27890.7', self.close='27881.1'
2023-04-08 08:10:01,605:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680912599, self.tradeDate='20230408', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27890.7', self.close='27881.1'
2023-04-08 08:10:01,662:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230408   072000    072959  1680910199    27900  27894.8 -0.000186
621  20230408   073000    073959  1680910799  27894.8  27906.7  0.000427
622  20230408   074000    074959  1680911399  27906.7  27903.1 -0.000129
623  20230408   075000    075959  1680911999  27903.1  27890.7 -0.000444
624  20230408   080000    080959  1680912599  27890.7  27881.1 -0.000344
2023-04-08 08:10:01,662:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19257 

self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27881', self.close='27861.5'
127.0.0.1 - - [08/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 08:20:08,341:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27881', self.close='27861.5'
2023-04-08 08:20:09,290:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230408   073000    073959  1680910799  27894.8  27906.7  0.000427
622  20230408   074000    074959  1680911399  27906.7  27903.1 -0.000129
623  20230408   075000    075959  1680911999  27903.1  27890.7 -0.000444
624  20230408   080000    080959  1680912599  27890.7  27881.1 -0.000344
625  20230408   081000    081959  1680913199    27881  27861.5 -0.000703
2023-04-08 08:20:09,291:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230408   075000    075959  1680911999  27903.1  27890.7
2023-04-08 08:00:01,933:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19257 

self.closeSec=1680912599, self.tradeDate='20230408', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27890.7', self.close='27881.1'
2023-04-08 08:10:01,629:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680912599, self.tradeDate='20230408', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27890.7', self.close='27881.1'
2023-04-08 08:10:01,666:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230408   072000    072959  1680910199    27900  27894.8
17469  20230408   073000    073959  1680910799  27894.8  27906.7
17470  20230408   074000    074959  1680911399  27906.7  27903.1
17471  20230408   075000    075959  1680911999  27903.1  27890.7
17472  20230408   080000    080959  1680912599  27890.7  27881.1
2023-04-08 08:10:01,666:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19258 

self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27881', self.close='27861.5'
127.0.0.1 - - [08/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 08:20:11,655:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27881', self.close='27861.5'
2023-04-08 08:20:11,814:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230408   073000    073959  1680910799  27894.8  27906.7
17470  20230408   074000    074959  1680911399  27906.7  27903.1
17471  20230408   075000    075959  1680911999  27903.1  27890.7
17472  20230408   080000    080959  1680912599  27890.7  27881.1
17473  20230408   081000    081959  1680913199    27881  27861.5
2023-04-08 08:20:11,815:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230408   075000    075959  1680911999  27903.1  27890.7
2023-04-08 08:00:01,915:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19257 

self.closeSec=1680912599, self.tradeDate='20230408', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27890.7', self.close='27881.1'
127.0.0.1 - - [08/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-04-08 08:10:01,619:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680912599, self.tradeDate='20230408', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27890.7', self.close='27881.1'
2023-04-08 08:10:01,661:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230408   072000    072959  1680910199    27900  27894.8
12141  20230408   073000    073959  1680910799  27894.8  27906.7
12142  20230408   074000    074959  1680911399  27906.7  27903.1
12143  20230408   075000    075959  1680911999  27903.1  27890.7
12144  20230408   080000    080959  1680912599  27890.7  27881.1
2023-04-08 08:10:01,662:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=19258 

self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27881', self.close='27861.5'
127.0.0.1 - - [08/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-08 08:20:11,113:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27881', self.close='27861.5'
2023-04-08 08:20:11,402:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230408   073000    073959  1680910799  27894.8  27906.7
12142  20230408   074000    074959  1680911399  27906.7  27903.1
12143  20230408   075000    075959  1680911999  27903.1  27890.7
12144  20230408   080000    080959  1680912599  27890.7  27881.1
12145  20230408   081000    081959  1680913199    27881  27861.5
2023-04-08 08:20:11,403:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33946
self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27877.8, self.close=27861.5, self.high=27895.0, self.low=27858.2, self.vol=1015.104, self.amt=28297054.9259 
127.0.0.1 - - [08/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-08 08:20:09,570:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230408   075500    075959  ...         0.0        0.0       0
5856  20230408   080000    080459  ...         0.0        0.0       0
5857  20230408   080500    080959  ...         0.0        0.0       0
5858  20230408   081000    081459  ...         0.0        0.0       0
5859  20230408   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 08:20:09,600:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680913199, self.tradeDate='20230408', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27877.8, self.close=27861.5, self.high=27895.0, self.low=27858.2, self.vol=1015.104, self.amt=28297054.9259, ukdf['pct'].iloc[-1]=-0.000588 , ukdf['amount'].iloc[-1]=28297054.9259, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33947
self.closeSec=1680913499, self.tradeDate='20230408', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27861.5, self.close=27873.3, self.high=27880.9, self.low=27855.0, self.vol=485.676, self.amt=13532831.563 
127.0.0.1 - - [08/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-08 08:25:01,593:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230408   080000    080459  ...         0.0        0.0       0
5857  20230408   080500    080959  ...         0.0        0.0       0
5858  20230408   081000    081459  ...         0.0        0.0       0
5859  20230408   081500    081959  ...         0.0        0.0       0
5860  20230408   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-08 08:25:01,596:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680913499, self.tradeDate='20230408', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27861.5, self.close=27873.3, self.high=27880.9, self.low=27855.0, self.vol=485.676, self.amt=13532831.563, ukdf['pct'].iloc[-1]=0.000424 , ukdf['amount'].iloc[-1]=13532831.563, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230407   200000    235959  1680883199  ...    719  0.126587 -0.494260     NaN
720  20230408   000000    035959  1680897599  ...    720  0.122962 -0.518480     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '26695.1', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27886.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=802
self.closeSec=1680911999, self.tradeDate='20230408', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27886.3, self.close=27890.7, self.high=27975.0, self.low=27822.9, self.vol=21815.597, self.amt=608624852.9104 
127.0.0.1 - - [08/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-08 08:00:01,773:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680911999, self.tradeDate='20230408', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27886.3, self.close=27890.7, self.high=27975.0, self.low=27822.9, self.vol=21815.597, self.amt=608624852.9104 
2023-04-08 08:00:01,840:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230407   120000    155959  ...  43961.294  1.226721e+09 -0.007141
718  20230407   160000    195959  ...  47979.773  1.336970e+09  0.000255
719  20230407   200000    235959  ...  58901.765  1.642831e+09  0.003629
720  20230408   000000    035959  ...  18629.237  5.195600e+08 -0.001568
721  20230408   040000    075959  ...  21815.597  6.086249e+08  0.000154

[5 rows x 11 columns]
2023-04-08 08:00:04,444:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230407   120000    155959  1680854399  ...    717  0.137208 -0.434237     NaN
718  20230407   160000    195959  1680868799  ...    718  0.120385 -0.514724     NaN
719  20230407   200000    235959  1680883199  ...    719  0.126587 -0.494260     NaN
720  20230408   000000    035959  1680897599  ...    720  0.122962 -0.518480     NaN
721  20230408   040000    075959  1680911999  ...    721  0.124757 -0.517900     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '26465.9128', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27890.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


