# 20230518 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [18/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1120
self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27369.0, self.close=27439.5, self.high=27482.7, self.low=27369.0, self.vol=2929.1, self.amt=80359674.3627 
2023-05-18 08:20:00,454:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230518   075500    075959  ...    0.413318   0.295909       0
5856  20230518   080000    080459  ...    0.413170   0.295982       0
5857  20230518   080500    080959  ...    0.413022   0.296055       0
5858  20230518   081000    081459  ...    0.412874   0.296129       0
5859  20230518   081500    081959  ...    0.412727   0.296202       0

[5 rows x 18 columns]
2023-05-18 08:20:00,457:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27369.0, self.close=27439.5, self.high=27482.7, self.low=27369.0, self.vol=2929.1, self.amt=80359674.3627, ukdf['pct'].iloc[-1]=0.00258 , ukdf['amount'].iloc[-1]=80359674.3627, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.4127272440618421, signal=0, value_std=0.2962023542057054 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-8080.39819564692', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27445.13827342', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [18/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1121
self.closeSec=1684369499, self.tradeDate='20230518', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27439.5, self.close=27372.2, self.high=27441.0, self.low=27368.5, self.vol=1759.231, self.amt=48190947.2569 
2023-05-18 08:25:00,433:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230518   080000    080459  ...    0.413170   0.295982       0
5857  20230518   080500    080959  ...    0.413022   0.296055       0
5858  20230518   081000    081459  ...    0.412874   0.296129       0
5859  20230518   081500    081959  ...    0.412727   0.296202       0
5860  20230518   082000    082459  ...    0.412580   0.296276       0

[5 rows x 18 columns]
2023-05-18 08:25:00,434:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684369499, self.tradeDate='20230518', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27439.5, self.close=27372.2, self.high=27441.0, self.low=27368.5, self.vol=1759.231, self.amt=48190947.2569, ukdf['pct'].iloc[-1]=-0.002453 , ukdf['amount'].iloc[-1]=48190947.2569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.41258020316874006, signal=0, value_std=0.2962758054479769 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-7159.30887921876', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27378.99657326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27369.0, self.close=27439.5, self.high=27482.7, self.low=27369.0 
127.0.0.1 - - [18/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:20:00,402:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27369.0, self.close=27439.5, self.high=27482.7, self.low=27369.0   
2023-05-18 08:20:00,442:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230518   075500    075959  1684367999  ...  27380.0  0.000405   1535    5
1536  20230518   080000    080459  1684368299  ...  27378.0 -0.000172   1536    0
1537  20230518   080500    080959  1684368599  ...  27353.8 -0.001311   1537    1
1538  20230518   081000    081459  1684368899  ...  27351.7  0.000501   1538    2
1539  20230518   081500    081959  1684369199  ...  27369.0  0.002580   1539    3

[5 rows x 11 columns]
2023-05-18 08:20:00,443:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=9, self.factor=0.49776674825408634, self.count=1123 

self.closeSec=1684369499, self.tradeDate='20230518', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27439.5, self.close=27372.2, self.high=27441.0, self.low=27368.5 
2023-05-18 08:25:00,388:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684369499, self.tradeDate='20230518', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27439.5, self.close=27372.2, self.high=27441.0, self.low=27368.5   
127.0.0.1 - - [18/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:25:00,412:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230518   080000    080459  1684368299  ...  27378.0 -0.000172   1536    0
1537  20230518   080500    080959  1684368599  ...  27353.8 -0.001311   1537    1
1538  20230518   081000    081459  1684368899  ...  27351.7  0.000501   1538    2
1539  20230518   081500    081959  1684369199  ...  27369.0  0.002580   1539    3
1540  20230518   082000    082459  1684369499  ...  27368.5 -0.002453   1540    4

[5 rows x 11 columns]
2023-05-18 08:25:00,412:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-18 08:00:18,427:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230518    052959  27330.4  ...  50.416667  0.578597  0.452136
5771  20230518    055959  27416.0  ...  50.416667  0.565516  0.431803
5772  20230518    062959  27356.9  ...  50.000000  0.557486  0.415355
5773  20230518    065959  27320.1  ...  50.416667  0.557850  0.399860
5774  20230518    072959  27322.2  ...  50.416667  0.572517  0.379524

[5 rows x 33 columns]
0.5415896487985212
acc is : 0.5415896487985212
2023-05-18 08:00:18,520:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.538292  0.461708       0  ...  1.038677   1.0    0.0  0.949718
537     1  0.487628  0.512372       0  ...  1.037276   1.0    0.0  0.948437
538     1  0.482547  0.517453       1  ...  1.037356   1.0    0.0  0.948509
539     1  0.491889  0.508111       1  ...  1.040610   1.0    0.0  0.951485
540     0  0.512196  0.487804       0  ...  1.040154   1.0    0.0  0.951068

[5 rows x 10 columns]
2023-05-18 08:00:18,539:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.537858  0.462142       0  ...  0.981855   1.0    0.0  0.957945
46     1  0.487225  0.512775       0  ...  0.980530   1.0    0.0  0.952630
47     1  0.482262  0.517738       1  ...  1.037356   1.0    0.0  0.952491
48     1  0.491889  0.508111       1  ...  1.040610   1.0    0.0  0.951485
49     0  0.512196  0.487804       0  ...  1.040154   1.0    0.0  0.951068

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.819', 'enterprice': '27153.5', 'countrevence': '0', 'unrealprofit': '6985.3509', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27404.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230518   075000    075959  1684367999  27408.3  27395.8 -0.000456
2023-05-18 08:00:00,430:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=560 

self.closeSec=1684368599, self.tradeDate='20230518', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27395.7', self.close='27355.2'
2023-05-18 08:10:00,400:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684368599, self.tradeDate='20230518', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27395.7', self.close='27355.2'
2023-05-18 08:10:00,444:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230518   072000    072959  1684366199  27383.7  27407.8  0.000884
621  20230518   073000    073959  1684366799  27407.8  27380.7 -0.000989
622  20230518   074000    074959  1684367399  27380.6  27408.3  0.001008
623  20230518   075000    075959  1684367999  27408.3  27395.8 -0.000456
624  20230518   080000    080959  1684368599  27395.7  27355.2 -0.001482
2023-05-18 08:10:00,444:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=561 

self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27355.2', self.close='27439.5'
127.0.0.1 - - [18/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:20:00,682:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27355.2', self.close='27439.5'
2023-05-18 08:20:00,715:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230518   073000    073959  1684366799  27407.8  27380.7 -0.000989
622  20230518   074000    074959  1684367399  27380.6  27408.3  0.001008
623  20230518   075000    075959  1684367999  27408.3  27395.8 -0.000456
624  20230518   080000    080959  1684368599  27395.7  27355.2 -0.001482
625  20230518   081000    081959  1684369199  27355.2  27439.5  0.003082
2023-05-18 08:20:00,715:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230518   075000    075959  1684367999  27408.3  27395.8
2023-05-18 08:00:00,447:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [18/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=563 

self.closeSec=1684368599, self.tradeDate='20230518', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27395.7', self.close='27355.2'
2023-05-18 08:10:00,412:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684368599, self.tradeDate='20230518', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27395.7', self.close='27355.2'
2023-05-18 08:10:00,456:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230518   072000    072959  1684366199  27383.7  27407.8
17469  20230518   073000    073959  1684366799  27407.8  27380.7
17470  20230518   074000    074959  1684367399  27380.6  27408.3
17471  20230518   075000    075959  1684367999  27408.3  27395.8
17472  20230518   080000    080959  1684368599  27395.7  27355.2
2023-05-18 08:10:00,465:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=564 

self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27355.2', self.close='27439.5'
127.0.0.1 - - [18/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:20:00,925:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27355.2', self.close='27439.5'
2023-05-18 08:20:00,978:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230518   073000    073959  1684366799  27407.8  27380.7
17470  20230518   074000    074959  1684367399  27380.6  27408.3
17471  20230518   075000    075959  1684367999  27408.3  27395.8
17472  20230518   080000    080959  1684368599  27395.7  27355.2
17473  20230518   081000    081959  1684369199  27355.2  27439.5
2023-05-18 08:20:00,978:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230518   075000    075959  1684367999  27408.3  27395.8
2023-05-18 08:00:00,419:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [18/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=563 

self.closeSec=1684368599, self.tradeDate='20230518', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27395.7', self.close='27355.2'
2023-05-18 08:10:00,425:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684368599, self.tradeDate='20230518', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27395.7', self.close='27355.2'
2023-05-18 08:10:00,448:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230518   072000    072959  1684366199  27383.7  27407.8
12141  20230518   073000    073959  1684366799  27407.8  27380.7
12142  20230518   074000    074959  1684367399  27380.6  27408.3
12143  20230518   075000    075959  1684367999  27408.3  27395.8
12144  20230518   080000    080959  1684368599  27395.7  27355.2
2023-05-18 08:10:00,448:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=564 

self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27355.2', self.close='27439.5'
127.0.0.1 - - [18/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:20:00,852:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27355.2', self.close='27439.5'
2023-05-18 08:20:00,932:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230518   073000    073959  1684366799  27407.8  27380.7
12142  20230518   074000    074959  1684367399  27380.6  27408.3
12143  20230518   075000    075959  1684367999  27408.3  27395.8
12144  20230518   080000    080959  1684368599  27395.7  27355.2
12145  20230518   081000    081959  1684369199  27355.2  27439.5
2023-05-18 08:20:00,933:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1120
self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27369.0, self.close=27439.5, self.high=27482.7, self.low=27369.0, self.vol=2929.1, self.amt=80359674.3627 
127.0.0.1 - - [18/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:20:00,479:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230518   075500    075959  ...    0.285665   0.296834       0
5856  20230518   080000    080459  ...    0.285468   0.296898       0
5857  20230518   080500    080959  ...    0.285273   0.296962       0
5858  20230518   081000    081459  ...    0.285076   0.297026       0
5859  20230518   081500    081959  ...    0.284879   0.297089       0

[5 rows x 18 columns]
2023-05-18 08:20:00,480:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684369199, self.tradeDate='20230518', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27369.0, self.close=27439.5, self.high=27482.7, self.low=27369.0, self.vol=2929.1, self.amt=80359674.3627, ukdf['pct'].iloc[-1]=0.00258 , ukdf['amount'].iloc[-1]=80359674.3627, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.28487864683208175, signal=0, value_std=0.29708921426485047 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '22326.87661309222', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27445.13827342', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1121
self.closeSec=1684369499, self.tradeDate='20230518', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27439.5, self.close=27372.2, self.high=27441.0, self.low=27368.5, self.vol=1759.231, self.amt=48190947.2569 
127.0.0.1 - - [18/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:25:00,422:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230518   080000    080459  ...    0.285468   0.296898       0
5857  20230518   080500    080959  ...    0.285273   0.296962       0
5858  20230518   081000    081459  ...    0.285076   0.297026       0
5859  20230518   081500    081959  ...    0.284879   0.297089       0
5860  20230518   082000    082459  ...    0.284680   0.297152       0

[5 rows x 18 columns]
2023-05-18 08:25:00,423:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684369499, self.tradeDate='20230518', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27439.5, self.close=27372.2, self.high=27441.0, self.low=27368.5, self.vol=1759.231, self.amt=48190947.2569, ukdf['pct'].iloc[-1]=-0.002453 , ukdf['amount'].iloc[-1]=48190947.2569, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.28467998407591594, signal=0, value_std=0.2971521073285543 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '19870.30772744966', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27378.99657326', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230517   200000    235959  1684339199  ...    719  0.709365  1.165997     1.0
720  20230518   000000    035959  1684353599  ...    720  0.531636  0.148478     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '18146.076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27376.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1393350.022233, self.flagDict['side']='buy', self.tradeCount=1, self.count=23
self.closeSec=1684367999, self.tradeDate='20230518', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27377.0, self.close=27395.8, self.high=27500.0, self.low=27259.5, self.vol=67419.315, self.amt=1844730687.8368 
2023-05-18 08:00:00,344:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684367999, self.tradeDate='20230518', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27377.0, self.close=27395.8, self.high=27500.0, self.low=27259.5, self.vol=67419.315, self.amt=1844730687.8368 
127.0.0.1 - - [18/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-05-18 08:00:00,426:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230517   120000    155959  ...   53789.861  1.448160e+09 -0.008140
718  20230517   160000    195959  ...   84616.009  2.263006e+09 -0.007655
719  20230517   200000    235959  ...  106131.008  2.833126e+09  0.006065
720  20230518   000000    035959  ...  129947.055  3.521987e+09  0.021991
721  20230518   040000    075959  ...   67419.315  1.844731e+09  0.000683

[5 rows x 11 columns]
2023-05-18 08:00:01,716:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230517   120000    155959  1684310399  ...    717  0.786628  1.643496     1.0
718  20230517   160000    195959  1684324799  ...    718  0.722309  1.258142     1.0
719  20230517   200000    235959  1684339199  ...    719  0.709365  1.165997     1.0
720  20230518   000000    035959  1684353599  ...    720  0.531636  0.148478     NaN
721  20230518   040000    075959  1684367999  ...    721  0.532623  0.155524     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.61', 'enterprice': '27024.7', 'countrevence': '0', 'unrealprofit': '19152.471', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27395.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


