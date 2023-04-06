# 20230406 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37372
self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28081.6, self.close=28081.2, self.high=28094.9, self.low=28051.4, self.vol=1305.115, self.amt=36639408.6902 
127.0.0.1 - - [06/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-06 08:20:09,286:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230406   075500    075959  ...         0.0        0.0       0
5856  20230406   080000    080459  ...         0.0        0.0       0
5857  20230406   080500    080959  ...         0.0        0.0       0
5858  20230406   081000    081459  ...         0.0        0.0       0
5859  20230406   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 08:20:09,305:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28081.6, self.close=28081.2, self.high=28094.9, self.low=28051.4, self.vol=1305.115, self.amt=36639408.6902, ukdf['pct'].iloc[-1]=-1.1e-05 , ukdf['amount'].iloc[-1]=36639408.6902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695058.271402588', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28079.72328175', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=37373
self.closeSec=1680740699, self.tradeDate='20230406', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28081.2, self.close=28049.5, self.high=28082.2, self.low=28024.5, self.vol=1071.643, self.amt=30064112.5669 
127.0.0.1 - - [06/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-06 08:25:01,593:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230406   080000    080459  ...         0.0        0.0       0
5857  20230406   080500    080959  ...         0.0        0.0       0
5858  20230406   081000    081459  ...         0.0        0.0       0
5859  20230406   081500    081959  ...         0.0        0.0       0
5860  20230406   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 08:25:01,594:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680740699, self.tradeDate='20230406', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28081.2, self.close=28049.5, self.high=28082.2, self.low=28024.5, self.vol=1071.643, self.amt=30064112.5669, ukdf['pct'].iloc[-1]=-0.001129 , ukdf['amount'].iloc[-1]=30064112.5669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-693239.5552', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28049.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28081.6, self.close=28081.2, self.high=28094.9, self.low=28051.4 
127.0.0.1 - - [06/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-06 08:20:06,540:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28081.6, self.close=28081.2, self.high=28094.9, self.low=28051.4   
2023-04-06 08:20:07,777:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230406   075500    075959  1680739199  ...  28154.0 -0.000249   1535    5
1536  20230406   080000    080459  1680739499  ...  28120.8 -0.000007   1536    0
1537  20230406   080500    080959  1680739799  ...  28008.0 -0.004042   1537    1
1538  20230406   081000    081459  1680740099  ...  28037.4  0.001480   1538    2
1539  20230406   081500    081959  1680740399  ...  28051.4 -0.000011   1539    3

[5 rows x 11 columns]
2023-04-06 08:20:07,785:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=73, self.factor=0.49142196568390994, self.count=37939 

self.closeSec=1680740699, self.tradeDate='20230406', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28081.2, self.close=28049.5, self.high=28082.2, self.low=28024.5 
2023-04-06 08:25:01,508:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680740699, self.tradeDate='20230406', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28081.2, self.close=28049.5, self.high=28082.2, self.low=28024.5   
2023-04-06 08:25:01,570:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230406   080000    080459  1680739499  ...  28120.8 -0.000007   1536    0
1537  20230406   080500    080959  1680739799  ...  28008.0 -0.004042   1537    1
1538  20230406   081000    081459  1680740099  ...  28037.4  0.001480   1538    2
1539  20230406   081500    081959  1680740399  ...  28051.4 -0.000011   1539    3
1540  20230406   082000    082459  1680740699  ...  28024.5 -0.001129   1540    4

[5 rows x 11 columns]
2023-04-06 08:25:01,570:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-06 08:00:33,833:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230406    052959  28136.6  ...  47.916667  0.492786  0.585046
5771  20230406    055959  28178.5  ...  47.500000  0.491144  0.587207
5772  20230406    062959  28167.1  ...  47.083333  0.484232  0.592008
5773  20230406    065959  28124.2  ...  47.083333  0.490370  0.592623
5774  20230406    072959  28160.3  ...  47.083333  0.490354  0.593205

[5 rows x 33 columns]
0.5434380776340111
acc is : 0.5434380776340111
2023-04-06 08:00:34,009:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.531513  0.468487       0  ...  0.960039   1.0    0.0  1.026027
537     0  0.508854  0.491146       0  ...  0.958580   1.0    0.0  1.024468
538     1  0.497417  0.502583       1  ...  0.959804   1.0    0.0  1.025775
539     0  0.517901  0.482099       1  ...  0.959800   1.0    0.0  1.025772
540     0  0.515793  0.484207       0  ...  0.959592   1.0    0.0  1.025549

[5 rows x 10 columns]
2023-04-06 08:00:34,033:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.531241  0.468759       0  ...  0.954113   1.0    0.0  1.019325
46     0  0.508562  0.491438       0  ...  0.958580   1.0    0.0  1.015816
47     1  0.497428  0.502572       1  ...  0.959804   1.0    0.0  1.019861
48     0  0.518375  0.481625       1  ...  0.959800   1.0    0.0  1.025772
49     0  0.515793  0.484207       0  ...  0.959592   1.0    0.0  1.025549

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230406   075000    075959  1680739199  28183.5    28154 -0.001047
2023-04-06 08:00:02,040:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18968 

self.closeSec=1680739799, self.tradeDate='20230406', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28154', self.close='28040'
2023-04-06 08:10:01,576:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680739799, self.tradeDate='20230406', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28154', self.close='28040'
2023-04-06 08:10:01,657:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230406   072000    072959  1680737399  28166.3  28160.1 -0.000220
621  20230406   073000    073959  1680737999  28160.1  28177.9  0.000632
622  20230406   074000    074959  1680738599  28177.8  28183.5  0.000199
623  20230406   075000    075959  1680739199  28183.5    28154 -0.001047
624  20230406   080000    080959  1680739799    28154    28040 -0.004049
2023-04-06 08:10:01,658:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18969 

self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28041.3', self.close='28081.2'
127.0.0.1 - - [06/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-06 08:20:07,826:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28041.3', self.close='28081.2'
2023-04-06 08:20:08,626:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230406   073000    073959  1680737999  28160.1  28177.9  0.000632
622  20230406   074000    074959  1680738599  28177.8  28183.5  0.000199
623  20230406   075000    075959  1680739199  28183.5    28154 -0.001047
624  20230406   080000    080959  1680739799    28154    28040 -0.004049
625  20230406   081000    081959  1680740399  28041.3  28081.2  0.001469
2023-04-06 08:20:08,635:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230406   075000    075959  1680739199  28183.5    28154
2023-04-06 08:00:02,092:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [06/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18969 

self.closeSec=1680739799, self.tradeDate='20230406', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28154', self.close='28040'
2023-04-06 08:10:01,645:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680739799, self.tradeDate='20230406', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28154', self.close='28040'
2023-04-06 08:10:01,670:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230406   072000    072959  1680737399  28166.3  28160.1
17469  20230406   073000    073959  1680737999  28160.1  28177.9
17470  20230406   074000    074959  1680738599  28177.8  28183.5
17471  20230406   075000    075959  1680739199  28183.5    28154
17472  20230406   080000    080959  1680739799    28154    28040
2023-04-06 08:10:01,670:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18970 

self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28041.3', self.close='28081.2'
127.0.0.1 - - [06/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-06 08:20:11,090:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28041.3', self.close='28081.2'
2023-04-06 08:20:11,222:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230406   073000    073959  1680737999  28160.1  28177.9
17470  20230406   074000    074959  1680738599  28177.8  28183.5
17471  20230406   075000    075959  1680739199  28183.5    28154
17472  20230406   080000    080959  1680739799    28154    28040
17473  20230406   081000    081959  1680740399  28041.3  28081.2
2023-04-06 08:20:11,223:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230406   075000    075959  1680739199  28183.5    28154
2023-04-06 08:00:02,085:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [06/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18969 

self.closeSec=1680739799, self.tradeDate='20230406', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28154', self.close='28040'
2023-04-06 08:10:01,625:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680739799, self.tradeDate='20230406', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28154', self.close='28040'
2023-04-06 08:10:01,668:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230406   072000    072959  1680737399  28166.3  28160.1
12141  20230406   073000    073959  1680737999  28160.1  28177.9
12142  20230406   074000    074959  1680738599  28177.8  28183.5
12143  20230406   075000    075959  1680739199  28183.5    28154
12144  20230406   080000    080959  1680739799    28154    28040
2023-04-06 08:10:01,668:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18970 

self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28041.3', self.close='28081.2'
127.0.0.1 - - [06/Apr/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-04-06 08:20:10,543:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28041.3', self.close='28081.2'
2023-04-06 08:20:10,844:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230406   073000    073959  1680737999  28160.1  28177.9
12142  20230406   074000    074959  1680738599  28177.8  28183.5
12143  20230406   075000    075959  1680739199  28183.5    28154
12144  20230406   080000    080959  1680739799    28154    28040
12145  20230406   081000    081959  1680740399  28041.3  28081.2
2023-04-06 08:20:10,844:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33370
self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28081.6, self.close=28081.2, self.high=28094.9, self.low=28051.4, self.vol=1305.115, self.amt=36639408.6902 
127.0.0.1 - - [06/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-06 08:20:08,065:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230406   075500    075959  ...         0.0        0.0       0
5856  20230406   080000    080459  ...         0.0        0.0       0
5857  20230406   080500    080959  ...         0.0        0.0       0
5858  20230406   081000    081459  ...         0.0        0.0       0
5859  20230406   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 08:20:08,086:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680740399, self.tradeDate='20230406', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28081.6, self.close=28081.2, self.high=28094.9, self.low=28051.4, self.vol=1305.115, self.amt=36639408.6902, ukdf['pct'].iloc[-1]=-1.1e-05 , ukdf['amount'].iloc[-1]=36639408.6902, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=33371
self.closeSec=1680740699, self.tradeDate='20230406', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28081.2, self.close=28049.5, self.high=28082.2, self.low=28024.5, self.vol=1071.643, self.amt=30064112.5669 
127.0.0.1 - - [06/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-06 08:25:01,614:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230406   080000    080459  ...         0.0        0.0       0
5857  20230406   080500    080959  ...         0.0        0.0       0
5858  20230406   081000    081459  ...         0.0        0.0       0
5859  20230406   081500    081959  ...         0.0        0.0       0
5860  20230406   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-06 08:25:01,616:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680740699, self.tradeDate='20230406', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28081.2, self.close=28049.5, self.high=28082.2, self.low=28024.5, self.vol=1071.643, self.amt=30064112.5669, ukdf['pct'].iloc[-1]=-0.001129 , ukdf['amount'].iloc[-1]=30064112.5669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230405   200000    235959  1680710399  ...    719  0.119619 -0.602008    -1.0
720  20230406   000000    035959  1680724799  ...    720  0.120090 -0.583035     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '9015.04895414352', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28225.72656746', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=790
self.closeSec=1680739199, self.tradeDate='20230406', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=28229.2, self.close=28154.0, self.high=28290.0, self.low=28110.0, self.vol=34158.218, self.amt=962516602.3259 
127.0.0.1 - - [06/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-06 08:00:01,959:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680739199, self.tradeDate='20230406', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=28229.2, self.close=28154.0, self.high=28290.0, self.low=28110.0, self.vol=34158.218, self.amt=962516602.3259 
2023-04-06 08:00:01,996:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230405   120000    155959  ...   38202.006  1.089692e+09 -0.000715
718  20230405   160000    195959  ...   37263.294  1.062696e+09  0.000992
719  20230405   200000    235959  ...  208759.520  5.901306e+09 -0.018536
720  20230406   000000    035959  ...   99424.748  2.786311e+09  0.007646
721  20230406   040000    075959  ...   34158.218  9.625166e+08 -0.002660

[5 rows x 11 columns]
2023-04-06 08:00:04,445:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230405   120000    155959  1680681599  ...    717  0.171421 -0.410539     NaN
718  20230405   160000    195959  1680695999  ...    718  0.165510 -0.420636     NaN
719  20230405   200000    235959  1680710399  ...    719  0.119619 -0.602008    -1.0
720  20230406   000000    035959  1680724799  ...    720  0.120090 -0.583035     NaN
721  20230406   040000    075959  1680739199  ...    721  0.117422 -0.580183     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '12743.3506967176', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28154.1495873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


