# 20230331 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35644
self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27994.1, self.close=27946.0, self.high=28003.2, self.low=27924.6, self.vol=1412.944, self.amt=39502362.9182 
127.0.0.1 - - [31/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-31 08:20:08,493:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230331   075500    075959  ...         0.0        0.0       0
5856  20230331   080000    080459  ...         0.0        0.0       0
5857  20230331   080500    080959  ...         0.0        0.0       0
5858  20230331   081000    081459  ...         0.0        0.0       0
5859  20230331   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 08:20:08,511:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27994.1, self.close=27946.0, self.high=28003.2, self.low=27924.6, self.vol=1412.944, self.amt=39502362.9182, ukdf['pct'].iloc[-1]=-0.001715 , ukdf['amount'].iloc[-1]=39502362.9182, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-687486.7296', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27953.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [31/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=35645
self.closeSec=1680222299, self.tradeDate='20230331', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27946.1, self.close=27936.5, self.high=27959.1, self.low=27900.0, self.vol=1326.421, self.amt=37041030.2717 
2023-03-31 08:25:01,577:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230331   080000    080459  ...         0.0        0.0       0
5857  20230331   080500    080959  ...         0.0        0.0       0
5858  20230331   081000    081459  ...         0.0        0.0       0
5859  20230331   081500    081959  ...         0.0        0.0       0
5860  20230331   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 08:25:01,577:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680222299, self.tradeDate='20230331', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27946.1, self.close=27936.5, self.high=27959.1, self.low=27900.0, self.vol=1326.421, self.amt=37041030.2717, ukdf['pct'].iloc[-1]=-0.00034 , ukdf['amount'].iloc[-1]=37041030.2717, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-686439.6672', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27936.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27994.1, self.close=27946.0, self.high=28003.2, self.low=27924.6 
127.0.0.1 - - [31/Mar/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-03-31 08:20:06,382:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27994.1, self.close=27946.0, self.high=28003.2, self.low=27924.6   
2023-03-31 08:20:07,322:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230331   075500    075959  1680220799  ...  28004.1  0.000082   1535    5
1536  20230331   080000    080459  1680221099  ...  28000.5  0.000996   1536    0
1537  20230331   080500    080959  1680221399  ...  27989.7 -0.001198   1537    1
1538  20230331   081000    081459  1680221699  ...  27974.3 -0.000546   1538    2
1539  20230331   081500    081959  1680221999  ...  27924.6 -0.001715   1539    3

[5 rows x 11 columns]
2023-03-31 08:20:07,323:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=56, self.factor=0.5330684708334812, self.count=36211 

self.closeSec=1680222299, self.tradeDate='20230331', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27946.1, self.close=27936.5, self.high=27959.1, self.low=27900.0 
2023-03-31 08:25:01,512:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680222299, self.tradeDate='20230331', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27946.1, self.close=27936.5, self.high=27959.1, self.low=27900.0   
2023-03-31 08:25:01,588:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230331   080000    080459  1680221099  ...  28000.5  0.000996   1536    0
1537  20230331   080500    080959  1680221399  ...  27989.7 -0.001198   1537    1
1538  20230331   081000    081459  1680221699  ...  27974.3 -0.000546   1538    2
1539  20230331   081500    081959  1680221999  ...  27924.6 -0.001715   1539    3
1540  20230331   082000    082459  1680222299  ...  27900.0 -0.000340   1540    4

[5 rows x 11 columns]
2023-03-31 08:25:01,588:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-31 08:00:34,274:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230331    052959  28130.7  ...  50.416667  0.492878  0.676560
5771  20230331    055959  28078.5  ...  50.000000  0.489596  0.680771
5772  20230331    062959  28052.4  ...  50.000000  0.495169  0.682889
5773  20230331    065959  28094.1  ...  50.000000  0.469279  0.692331
5774  20230331    072959  27888.1  ...  50.416667  0.480474  0.693720

[5 rows x 33 columns]
0.5212569316081331
acc is : 0.5212569316081331
2023-03-31 08:00:34,439:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.529876  0.470124       0  ...  0.974734   1.0    0.0  1.006039
537     0  0.523162  0.476838       1  ...  0.976179   1.0    0.0  1.007531
538     0  0.542215  0.457785       0  ...  0.969022   1.0    0.0  1.000143
539     1  0.476594  0.523406       1  ...  0.971912   1.0    0.0  1.003127
540     0  0.529743  0.470257       1  ...  0.973431   1.0    0.0  1.004694

[5 rows x 10 columns]
2023-03-31 08:00:34,473:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.530978  0.469022       0  ...  0.973921   1.0    0.0  1.018820
46     0  0.523537  0.476463       1  ...  0.986607   1.0    0.0  1.018275
47     0  0.541710  0.458290       0  ...  0.967950   1.0    0.0  0.999040
48     1  0.476681  0.523319       1  ...  0.958917   1.0    0.0  1.003127
49     0  0.529743  0.470257       1  ...  0.973431   1.0    0.0  1.004694

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

2023-03-31 08:00:02,273:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [31/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18104 

self.closeSec=1680221399, self.tradeDate='20230331', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28015', self.close='28009.3'
2023-03-31 08:10:01,634:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680221399, self.tradeDate='20230331', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28015', self.close='28009.3'
127.0.0.1 - - [31/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-31 08:10:01,664:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230331   072000    072959  1680218999  27971.3  27971.3  0.000000
621  20230331   073000    073959  1680219599  27971.4  28005.9  0.001237
622  20230331   074000    074959  1680220199  28005.8  27994.2 -0.000418
623  20230331   075000    075959  1680220799  27994.2    28015  0.000743
624  20230331   080000    080959  1680221399    28015  28009.3 -0.000203
2023-03-31 08:10:01,664:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18105 

self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28009.3', self.close='27946.1'
127.0.0.1 - - [31/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 08:20:07,172:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28009.3', self.close='27946.1'
2023-03-31 08:20:08,041:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230331   073000    073959  1680219599  27971.4  28005.9  0.001237
622  20230331   074000    074959  1680220199  28005.8  27994.2 -0.000418
623  20230331   075000    075959  1680220799  27994.2    28015  0.000743
624  20230331   080000    080959  1680221399    28015  28009.3 -0.000203
625  20230331   081000    081959  1680221999  28009.3  27946.1 -0.002256
2023-03-31 08:20:08,042:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230331   075000    075959  1680220799  27994.2    28015
2023-03-31 08:00:02,372:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18105 

self.closeSec=1680221399, self.tradeDate='20230331', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28015', self.close='28009.3'
2023-03-31 08:10:01,623:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680221399, self.tradeDate='20230331', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28015', self.close='28009.3'
127.0.0.1 - - [31/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-31 08:10:01,669:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230331   072000    072959  1680218999  27971.3  27971.3
17469  20230331   073000    073959  1680219599  27971.4  28005.9
17470  20230331   074000    074959  1680220199  28005.8  27994.2
17471  20230331   075000    075959  1680220799  27994.2    28015
17472  20230331   080000    080959  1680221399    28015  28009.3
2023-03-31 08:10:01,677:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18106 

self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28009.3', self.close='27946.1'
127.0.0.1 - - [31/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 08:20:10,075:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28009.3', self.close='27946.1'
2023-03-31 08:20:10,212:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230331   073000    073959  1680219599  27971.4  28005.9
17470  20230331   074000    074959  1680220199  28005.8  27994.2
17471  20230331   075000    075959  1680220799  27994.2    28015
17472  20230331   080000    080959  1680221399    28015  28009.3
17473  20230331   081000    081959  1680221999  28009.3  27946.1
2023-03-31 08:20:10,213:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230331   075000    075959  1680220799  27994.2    28015
2023-03-31 08:00:02,372:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18105 

self.closeSec=1680221399, self.tradeDate='20230331', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28015', self.close='28009.3'
2023-03-31 08:10:01,610:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680221399, self.tradeDate='20230331', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28015', self.close='28009.3'
127.0.0.1 - - [31/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-31 08:10:01,669:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230331   072000    072959  1680218999  27971.3  27971.3
12141  20230331   073000    073959  1680219599  27971.4  28005.9
12142  20230331   074000    074959  1680220199  28005.8  27994.2
12143  20230331   075000    075959  1680220799  27994.2    28015
12144  20230331   080000    080959  1680221399    28015  28009.3
2023-03-31 08:10:01,670:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18106 

self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28009.3', self.close='27946.1'
127.0.0.1 - - [31/Mar/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-03-31 08:20:09,567:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28009.3', self.close='27946.1'
2023-03-31 08:20:09,812:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230331   073000    073959  1680219599  27971.4  28005.9
12142  20230331   074000    074959  1680220199  28005.8  27994.2
12143  20230331   075000    075959  1680220799  27994.2    28015
12144  20230331   080000    080959  1680221399    28015  28009.3
12145  20230331   081000    081959  1680221999  28009.3  27946.1
2023-03-31 08:20:09,813:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31642
self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27994.1, self.close=27946.0, self.high=28003.2, self.low=27924.6, self.vol=1412.944, self.amt=39502362.9182 
127.0.0.1 - - [31/Mar/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-03-31 08:20:07,103:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230331   075500    075959  ...         0.0        0.0       0
5856  20230331   080000    080459  ...         0.0        0.0       0
5857  20230331   080500    080959  ...         0.0        0.0       0
5858  20230331   081000    081459  ...         0.0        0.0       0
5859  20230331   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 08:20:07,143:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680221999, self.tradeDate='20230331', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27994.1, self.close=27946.0, self.high=28003.2, self.low=27924.6, self.vol=1412.944, self.amt=39502362.9182, ukdf['pct'].iloc[-1]=-0.001715 , ukdf['amount'].iloc[-1]=39502362.9182, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [31/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=31643
self.closeSec=1680222299, self.tradeDate='20230331', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27946.1, self.close=27936.5, self.high=27959.1, self.low=27900.0, self.vol=1326.421, self.amt=37041030.2717 
2023-03-31 08:25:01,584:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230331   080000    080459  ...         0.0        0.0       0
5857  20230331   080500    080959  ...         0.0        0.0       0
5858  20230331   081000    081459  ...         0.0        0.0       0
5859  20230331   081500    081959  ...         0.0        0.0       0
5860  20230331   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-31 08:25:01,584:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680222299, self.tradeDate='20230331', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27946.1, self.close=27936.5, self.high=27959.1, self.low=27900.0, self.vol=1326.421, self.amt=37041030.2717, ukdf['pct'].iloc[-1]=-0.00034 , ukdf['amount'].iloc[-1]=37041030.2717, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230330   200000    235959  1680191999  ...    719  0.600231  0.430188     NaN
720  20230331   000000    035959  1680206399  ...    720  0.601653  0.457105     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '5907.66', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27981.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=754
self.closeSec=1680220799, self.tradeDate='20230331', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27971.4, self.close=28015.0, self.high=28187.7, self.low=27762.3, self.vol=73207.708, self.amt=2050604979.50365 
127.0.0.1 - - [31/Mar/2023 08:00:02] "POST / HTTP/1.1" 200 -
2023-03-31 08:00:02,046:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680220799, self.tradeDate='20230331', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27971.4, self.close=28015.0, self.high=28187.7, self.low=27762.3, self.vol=73207.708, self.amt=2050604979.50365 
2023-03-31 08:00:02,118:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230330   120000    155959  ...   79859.667  2.284422e+09  0.008293
718  20230330   160000    195959  ...   63603.014  1.818524e+09 -0.002665
719  20230330   200000    235959  ...  132432.531  3.763736e+09 -0.012068
720  20230331   000000    035959  ...  176918.772  4.948472e+09 -0.011077
721  20230331   040000    075959  ...   73207.708  2.050605e+09  0.001562

[5 rows x 11 columns]
2023-03-31 08:00:04,551:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230330   120000    155959  1680163199  ...    717  0.568499  0.298260     NaN
718  20230330   160000    195959  1680177599  ...    718  0.578144  0.346862     NaN
719  20230330   200000    235959  1680191999  ...    719  0.600231  0.430188     NaN
720  20230331   000000    035959  1680206399  ...    720  0.601653  0.457105     NaN
721  20230331   040000    075959  1680220799  ...    721  0.604340  0.486068     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '4072.92195541212', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28015.26262698', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


