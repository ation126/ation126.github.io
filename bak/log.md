# 20230403 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36508
self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28142.2, self.close=28130.9, self.high=28159.3, self.low=28130.9, self.vol=510.311, self.amt=14362259.1578 
127.0.0.1 - - [03/Apr/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-04-03 08:20:09,049:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230403   075500    075959  ...         0.0        0.0       0
5856  20230403   080000    080459  ...         0.0        0.0       0
5857  20230403   080500    080959  ...         0.0        0.0       0
5858  20230403   081000    081459  ...         0.0        0.0       0
5859  20230403   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 08:20:09,069:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28142.2, self.close=28130.9, self.high=28159.3, self.low=28130.9, self.vol=510.311, self.amt=14362259.1578, ukdf['pct'].iloc[-1]=-0.000402 , ukdf['amount'].iloc[-1]=14362259.1578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-698448.07163837248', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28136.05471348', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=36509
self.closeSec=1680481499, self.tradeDate='20230403', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28130.9, self.close=28085.4, self.high=28134.4, self.low=28081.3, self.vol=1121.216, self.amt=31518415.2386 
127.0.0.1 - - [03/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-04-03 08:25:01,597:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230403   080000    080459  ...         0.0        0.0       0
5857  20230403   080500    080959  ...         0.0        0.0       0
5858  20230403   081000    081459  ...         0.0        0.0       0
5859  20230403   081500    081959  ...         0.0        0.0       0
5860  20230403   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 08:25:01,599:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1680481499, self.tradeDate='20230403', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28130.9, self.close=28085.4, self.high=28134.4, self.low=28081.3, self.vol=1121.216, self.amt=31518415.2386, ukdf['pct'].iloc[-1]=-0.001617 , ukdf['amount'].iloc[-1]=31518415.2386, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-695451.38043542576', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28086.25593651', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28142.2, self.close=28130.9, self.high=28159.3, self.low=28130.9 
127.0.0.1 - - [03/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-03 08:20:05,349:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28142.2, self.close=28130.9, self.high=28159.3, self.low=28130.9   
2023-04-03 08:20:06,860:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230403   075500    075959  1680479999  ...  28153.8 -0.000490   1535    5
1536  20230403   080000    080459  1680480299  ...  28135.4 -0.000589   1536    0
1537  20230403   080500    080959  1680480599  ...  28131.1  0.000401   1537    1
1538  20230403   081000    081459  1680480899  ...  28135.0 -0.000487   1538    2
1539  20230403   081500    081959  1680481199  ...  28130.9 -0.000402   1539    3

[5 rows x 11 columns]
2023-04-03 08:20:06,874:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6252469258068026, self.count=37075 

self.closeSec=1680481499, self.tradeDate='20230403', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28130.9, self.close=28085.4, self.high=28134.4, self.low=28081.3 
2023-04-03 08:25:01,500:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1680481499, self.tradeDate='20230403', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28130.9, self.close=28085.4, self.high=28134.4, self.low=28081.3   
2023-04-03 08:25:01,522:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230403   080000    080459  1680480299  ...  28135.4 -0.000589   1536    0
1537  20230403   080500    080959  1680480599  ...  28131.1  0.000401   1537    1
1538  20230403   081000    081459  1680480899  ...  28135.0 -0.000487   1538    2
1539  20230403   081500    081959  1680481199  ...  28130.9 -0.000402   1539    3
1540  20230403   082000    082459  1680481499  ...  28081.3 -0.001617   1540    4

[5 rows x 11 columns]
2023-04-03 08:25:01,522:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-04-03 08:00:34,934:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230403    052959  28042.1  ...  52.916667  0.458057  0.649802
5771  20230403    055959  28096.7  ...  52.916667  0.439527  0.655996
5772  20230403    062959  27999.2  ...  52.500000  0.429419  0.667099
5773  20230403    065959  27943.6  ...  52.500000  0.463328  0.663133
5774  20230403    072959  28093.4  ...  52.500000  0.464392  0.658962

[5 rows x 33 columns]
0.5489833641404805
acc is : 0.5489833641404805
2023-04-03 08:00:35,106:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.524051  0.475949       0  ...  0.936449   1.0    0.0  0.986853
537     1  0.493381  0.506619       0  ...  0.934589   1.0    0.0  0.984894
538     0  0.510787  0.489213       1  ...  0.939596   1.0    0.0  0.990170
539     0  0.550186  0.449814       1  ...  0.939760   1.0    0.0  0.990343
540     0  0.523442  0.476558       1  ...  0.941867   1.0    0.0  0.992563

[5 rows x 10 columns]
2023-04-03 08:00:35,133:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.524627  0.475373       0  ...  0.936449   1.0    0.0  0.979466
46     1  0.493455  0.506545       0  ...  0.934589   1.0    0.0  0.977056
47     0  0.510217  0.489783       1  ...  0.939596   1.0    0.0  0.981028
48     0  0.549671  0.450329       1  ...  0.939760   1.0    0.0  0.990343
49     0  0.523442  0.476558       1  ...  0.941867   1.0    0.0  0.992563

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230403   075000    075959  1680479999  28159.9  28161.2  0.000043
2023-04-03 08:00:02,108:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18536 

self.closeSec=1680480599, self.tradeDate='20230403', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28161.3', self.close='28155.9'
2023-04-03 08:10:01,608:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680480599, self.tradeDate='20230403', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28161.3', self.close='28155.9'
2023-04-03 08:10:01,649:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230403   072000    072959  1680478199  28039.9  28098.2  0.002079
621  20230403   073000    073959  1680478799  28098.2  28143.3  0.001605
622  20230403   074000    074959  1680479399  28143.3    28160  0.000593
623  20230403   075000    075959  1680479999  28159.9  28161.2  0.000043
624  20230403   080000    080959  1680480599  28161.3  28155.9 -0.000188
2023-04-03 08:10:01,649:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18537 

self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28155.8', self.close='28130.9'
127.0.0.1 - - [03/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-03 08:20:08,489:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28155.8', self.close='28130.9'
2023-04-03 08:20:09,189:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230403   073000    073959  1680478799  28098.2  28143.3  0.001605
622  20230403   074000    074959  1680479399  28143.3    28160  0.000593
623  20230403   075000    075959  1680479999  28159.9  28161.2  0.000043
624  20230403   080000    080959  1680480599  28161.3  28155.9 -0.000188
625  20230403   081000    081959  1680481199  28155.8  28130.9 -0.000888
2023-04-03 08:20:09,190:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230403   075000    075959  1680479999  28159.9  28161.2
2023-04-03 08:00:02,135:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18537 

self.closeSec=1680480599, self.tradeDate='20230403', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28161.3', self.close='28155.9'
2023-04-03 08:10:01,659:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680480599, self.tradeDate='20230403', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28161.3', self.close='28155.9'
2023-04-03 08:10:01,695:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230403   072000    072959  1680478199  28039.9  28098.2
17469  20230403   073000    073959  1680478799  28098.2  28143.3
17470  20230403   074000    074959  1680479399  28143.3    28160
17471  20230403   075000    075959  1680479999  28159.9  28161.2
17472  20230403   080000    080959  1680480599  28161.3  28155.9
2023-04-03 08:10:01,695:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18538 

self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28155.8', self.close='28130.9'
127.0.0.1 - - [03/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-03 08:20:11,190:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28155.8', self.close='28130.9'
2023-04-03 08:20:11,335:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230403   073000    073959  1680478799  28098.2  28143.3
17470  20230403   074000    074959  1680479399  28143.3    28160
17471  20230403   075000    075959  1680479999  28159.9  28161.2
17472  20230403   080000    080959  1680480599  28161.3  28155.9
17473  20230403   081000    081959  1680481199  28155.8  28130.9
2023-04-03 08:20:11,336:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230403   075000    075959  1680479999  28159.9  28161.2
2023-04-03 08:00:02,126:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [03/Apr/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18537 

self.closeSec=1680480599, self.tradeDate='20230403', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28161.3', self.close='28155.9'
2023-04-03 08:10:01,615:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680480599, self.tradeDate='20230403', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28161.3', self.close='28155.9'
2023-04-03 08:10:01,657:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230403   072000    072959  1680478199  28039.9  28098.2
12141  20230403   073000    073959  1680478799  28098.2  28143.3
12142  20230403   074000    074959  1680479399  28143.3    28160
12143  20230403   075000    075959  1680479999  28159.9  28161.2
12144  20230403   080000    080959  1680480599  28161.3  28155.9
2023-04-03 08:10:01,657:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=18538 

self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28155.8', self.close='28130.9'
127.0.0.1 - - [03/Apr/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-04-03 08:20:10,691:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28155.8', self.close='28130.9'
2023-04-03 08:20:11,008:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230403   073000    073959  1680478799  28098.2  28143.3
12142  20230403   074000    074959  1680479399  28143.3    28160
12143  20230403   075000    075959  1680479999  28159.9  28161.2
12144  20230403   080000    080959  1680480599  28161.3  28155.9
12145  20230403   081000    081959  1680481199  28155.8  28130.9
2023-04-03 08:20:11,008:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32506
self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28142.2, self.close=28130.9, self.high=28159.3, self.low=28130.9, self.vol=510.311, self.amt=14362259.1578 
127.0.0.1 - - [03/Apr/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-04-03 08:20:07,628:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230403   075500    075959  ...         0.0        0.0       0
5856  20230403   080000    080459  ...         0.0        0.0       0
5857  20230403   080500    080959  ...         0.0        0.0       0
5858  20230403   081000    081459  ...         0.0        0.0       0
5859  20230403   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 08:20:07,689:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680481199, self.tradeDate='20230403', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28142.2, self.close=28130.9, self.high=28159.3, self.low=28130.9, self.vol=510.311, self.amt=14362259.1578, ukdf['pct'].iloc[-1]=-0.000402 , ukdf['amount'].iloc[-1]=14362259.1578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [03/Apr/2023 08:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=32507
self.closeSec=1680481499, self.tradeDate='20230403', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28130.9, self.close=28085.4, self.high=28134.4, self.low=28081.3, self.vol=1121.216, self.amt=31518415.2386 
2023-04-03 08:25:01,585:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230403   080000    080459  ...         0.0        0.0       0
5857  20230403   080500    080959  ...         0.0        0.0       0
5858  20230403   081000    081459  ...         0.0        0.0       0
5859  20230403   081500    081959  ...         0.0        0.0       0
5860  20230403   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-04-03 08:25:01,588:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1680481499, self.tradeDate='20230403', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28130.9, self.close=28085.4, self.high=28134.4, self.low=28081.3, self.vol=1121.216, self.amt=31518415.2386, ukdf['pct'].iloc[-1]=-0.001617 , ukdf['amount'].iloc[-1]=31518415.2386, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230402   200000    235959  1680451199  ...    719  0.088071 -0.911072    -1.0
720  20230403   000000    035959  1680465599  ...    720  0.102683 -0.849219    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '24731.18417599072', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27924.00380556', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1477757.4577056, self.flagDict['side']='sell', self.tradeCount=29, self.count=772
self.closeSec=1680479999, self.tradeDate='20230403', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27933.7, self.close=28161.2, self.high=28197.6, self.low=27825.2, self.vol=59221.178, self.amt=1659290812.94486 
127.0.0.1 - - [03/Apr/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-04-03 08:00:01,922:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1680479999, self.tradeDate='20230403', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27933.7, self.close=28161.2, self.high=28197.6, self.low=27825.2, self.vol=59221.178, self.amt=1659290812.94486 
2023-04-03 08:00:01,953:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230402   120000    155959  ...  21969.846  6.245725e+08 -0.002168
718  20230402   160000    195959  ...  30770.077  8.728521e+08 -0.001986
719  20230402   200000    235959  ...  92591.724  2.610223e+09 -0.008280
720  20230403   000000    035959  ...  83183.919  2.334075e+09 -0.006279
721  20230403   040000    075959  ...  59221.178  1.659291e+09  0.008144

[5 rows x 11 columns]
2023-04-03 08:00:04,540:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230402   120000    155959  1680422399  ...    717  0.086417 -0.958243    -1.0
718  20230402   160000    195959  1680436799  ...    718  0.076166 -0.966467    -1.0
719  20230402   200000    235959  1680451199  ...    719  0.088071 -0.911072    -1.0
720  20230403   000000    035959  1680465599  ...    720  0.102683 -0.849219    -1.0
721  20230403   040000    075959  1680479999  ...    721  0.119203 -0.783243    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.088', 'enterprice': '28398.8', 'countrevence': '0', 'unrealprofit': '12370.9', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28161.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


