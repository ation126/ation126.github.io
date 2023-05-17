# 20230517 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [17/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=832
self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27042.9, self.close=26999.1, self.high=27045.3, self.low=26985.4, self.vol=1080.886, self.amt=29188219.9549 
2023-05-17 08:20:00,504:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230517   075500    075959  ...    0.449074   0.270476       0
5856  20230517   080000    080459  ...    0.448883   0.270551       0
5857  20230517   080500    080959  ...    0.448694   0.270626       0
5858  20230517   081000    081459  ...    0.448503   0.270700       0
5859  20230517   081500    081959  ...    0.448313   0.270775       0

[5 rows x 18 columns]
2023-05-17 08:20:00,506:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27042.9, self.close=26999.1, self.high=27045.3, self.low=26985.4, self.vol=1080.886, self.amt=29188219.9549, ukdf['pct'].iloc[-1]=-0.001623 , ukdf['amount'].iloc[-1]=29188219.9549, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.4483129658057868, signal=0, value_std=0.2707747397140921 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1870.2618', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26999.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [17/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=833
self.closeSec=1684283099, self.tradeDate='20230517', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26999.1, self.close=26983.6, self.high=27001.9, self.low=26975.0, self.vol=545.446, self.amt=14720140.6434 
2023-05-17 08:25:00,439:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230517   080000    080459  ...    0.448883   0.270551       0
5857  20230517   080500    080959  ...    0.448694   0.270626       0
5858  20230517   081000    081459  ...    0.448503   0.270700       0
5859  20230517   081500    081959  ...    0.448313   0.270775       0
5860  20230517   082000    082459  ...    0.448124   0.270850       0

[5 rows x 18 columns]
2023-05-17 08:25:00,440:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684283099, self.tradeDate='20230517', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26999.1, self.close=26983.6, self.high=27001.9, self.low=26975.0, self.vol=545.446, self.amt=14720140.6434, ukdf['pct'].iloc[-1]=-0.000574 , ukdf['amount'].iloc[-1]=14720140.6434, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.4481242051257671, signal=0, value_std=0.2708503306582012 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-1654.4088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26983.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27042.9, self.close=26999.1, self.high=27045.3, self.low=26985.4 
127.0.0.1 - - [17/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-17 08:20:00,403:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27042.9, self.close=26999.1, self.high=27045.3, self.low=26985.4   
2023-05-17 08:20:00,496:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1534  20230517   075500    075959  1684281599  ...  27014.3  0.000385   1534    4
1535  20230517   080000    080459  1684281899  ...  27007.0 -0.000655   1535    5
1536  20230517   080500    080959  1684282199  ...  26998.3  0.000115   1536    0
1537  20230517   081000    081459  1684282499  ...  27010.2  0.001214   1537    1
1538  20230517   081500    081959  1684282799  ...  26985.4 -0.001623   1538    2

[5 rows x 11 columns]
2023-05-17 08:20:00,497:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=138, self.factor=0.5805075801807891, self.count=835 

self.closeSec=1684283099, self.tradeDate='20230517', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26999.1, self.close=26983.6, self.high=27001.9, self.low=26975.0 
2023-05-17 08:25:00,375:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684283099, self.tradeDate='20230517', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26999.1, self.close=26983.6, self.high=27001.9, self.low=26975.0   
127.0.0.1 - - [17/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-17 08:25:00,418:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230517   080000    080459  1684281899  ...  27007.0 -0.000655   1535    5
1536  20230517   080500    080959  1684282199  ...  26998.3  0.000115   1536    0
1537  20230517   081000    081459  1684282499  ...  27010.2  0.001214   1537    1
1538  20230517   081500    081959  1684282799  ...  26985.4 -0.001623   1538    2
1539  20230517   082000    082459  1684283099  ...  26975.0 -0.000574   1539    3

[5 rows x 11 columns]
2023-05-17 08:25:00,418:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': '', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-17 08:00:18,678:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230517    052959  26942.1  ...  50.000000  0.483707  0.662793
5771  20230517    055959  27015.7  ...  50.000000  0.480723  0.662696
5772  20230517    062959  27001.7  ...  49.583333  0.477485  0.665079
5773  20230517    065959  26986.3  ...  50.000000  0.478165  0.666835
5774  20230517    072959  26989.1  ...  50.000000  0.478690  0.668117

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-05-17 08:00:18,807:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.509065  0.490935       0  ...  1.039380  -1.0    0.0  0.913503
537     1  0.493944  0.506056       0  ...  1.039969  -1.0    0.0  0.912986
538     0  0.503606  0.496394       1  ...  1.039858  -1.0    0.0  0.913084
539     0  0.503276  0.496724       1  ...  1.039773  -1.0    0.0  0.913158
540     0  0.505320  0.494680       1  ...  1.038486  -1.0    0.0  0.914288

[5 rows x 10 columns]
2023-05-17 08:00:18,834:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.509095  0.490905       0  ...  1.039380  -1.0    0.0  0.920068
46     1  0.493981  0.506019       0  ...  1.039969  -1.0    0.0  0.914247
47     0  0.503390  0.496610       1  ...  1.039858  -1.0    0.0  0.912414
48     0  0.503583  0.496417       1  ...  1.039773  -1.0    0.0  0.913158
49     0  0.505320  0.494680       1  ...  1.038486  -1.0    0.0  0.914288

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.151', 'enterprice': '26995.7', 'countrevence': '0', 'unrealprofit': '-813.5639', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27024.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230517   075000    075959  1684281599  27027.6  27024.8 -0.000100
2023-05-17 08:00:00,448:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=416 

self.closeSec=1684282199, self.tradeDate='20230517', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27024.7', self.close='27010.2'
2023-05-17 08:10:00,380:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684282199, self.tradeDate='20230517', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27024.7', self.close='27010.2'
2023-05-17 08:10:00,431:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230517   072000    072959  1684279799  26984.6  26991.4  0.000256
621  20230517   073000    073959  1684280399  26991.5  27016.7  0.000937
622  20230517   074000    074959  1684280999  27016.6  27027.5  0.000400
623  20230517   075000    075959  1684281599  27027.6  27024.8 -0.000100
624  20230517   080000    080959  1684282199  27024.7  27010.2 -0.000540
2023-05-17 08:10:00,431:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=417 

self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27010.2', self.close='26999.1'
2023-05-17 08:20:00,416:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27010.2', self.close='26999.1'
127.0.0.1 - - [17/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-17 08:20:00,463:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230517   073000    073959  1684280399  26991.5  27016.7  0.000937
622  20230517   074000    074959  1684280999  27016.6  27027.5  0.000400
623  20230517   075000    075959  1684281599  27027.6  27024.8 -0.000100
624  20230517   080000    080959  1684282199  27024.7  27010.2 -0.000540
625  20230517   081000    081959  1684282799  27010.2  26999.1 -0.000411
2023-05-17 08:20:00,463:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230517   075000    075959  1684281599  27027.6  27024.8
2023-05-17 08:00:00,460:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=419 

self.closeSec=1684282199, self.tradeDate='20230517', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27024.7', self.close='27010.2'
127.0.0.1 - - [17/May/2023 08:10:00] "POST / HTTP/1.1" 200 -
2023-05-17 08:10:00,411:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684282199, self.tradeDate='20230517', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27024.7', self.close='27010.2'
2023-05-17 08:10:00,445:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230517   072000    072959  1684279799  26984.6  26991.4
17469  20230517   073000    073959  1684280399  26991.5  27016.7
17470  20230517   074000    074959  1684280999  27016.6  27027.5
17471  20230517   075000    075959  1684281599  27027.6  27024.8
17472  20230517   080000    080959  1684282199  27024.7  27010.2
2023-05-17 08:10:00,445:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [17/May/2023 08:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=420 

self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27010.2', self.close='26999.1'
2023-05-17 08:20:00,454:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27010.2', self.close='26999.1'
2023-05-17 08:20:00,484:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230517   073000    073959  1684280399  26991.5  27016.7
17470  20230517   074000    074959  1684280999  27016.6  27027.5
17471  20230517   075000    075959  1684281599  27027.6  27024.8
17472  20230517   080000    080959  1684282199  27024.7  27010.2
17473  20230517   081000    081959  1684282799  27010.2  26999.1
2023-05-17 08:20:00,485:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230517   075000    075959  1684281599  27027.6  27024.8
2023-05-17 08:00:00,456:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [17/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=419 

self.closeSec=1684282199, self.tradeDate='20230517', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27024.7', self.close='27010.2'
2023-05-17 08:10:00,404:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684282199, self.tradeDate='20230517', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27024.7', self.close='27010.2'
2023-05-17 08:10:00,440:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230517   072000    072959  1684279799  26984.6  26991.4
12141  20230517   073000    073959  1684280399  26991.5  27016.7
12142  20230517   074000    074959  1684280999  27016.6  27027.5
12143  20230517   075000    075959  1684281599  27027.6  27024.8
12144  20230517   080000    080959  1684282199  27024.7  27010.2
2023-05-17 08:10:00,440:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=420 

self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27010.2', self.close='26999.1'
127.0.0.1 - - [17/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-17 08:20:00,430:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27010.2', self.close='26999.1'
2023-05-17 08:20:00,486:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230517   073000    073959  1684280399  26991.5  27016.7
12142  20230517   074000    074959  1684280999  27016.6  27027.5
12143  20230517   075000    075959  1684281599  27027.6  27024.8
12144  20230517   080000    080959  1684282199  27024.7  27010.2
12145  20230517   081000    081959  1684282799  27010.2  26999.1
2023-05-17 08:20:00,486:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [17/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=832
self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27042.9, self.close=26999.1, self.high=27045.3, self.low=26985.4, self.vol=1080.886, self.amt=29188219.9549 
2023-05-17 08:20:00,523:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230517   075500    075959  ...    0.340530   0.277494       0
5856  20230517   080000    080459  ...    0.340200   0.277523       0
5857  20230517   080500    080959  ...    0.339872   0.277553       0
5858  20230517   081000    081459  ...    0.339544   0.277582       0
5859  20230517   081500    081959  ...    0.339217   0.277611       0

[5 rows x 18 columns]
2023-05-17 08:20:00,523:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684282799, self.tradeDate='20230517', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27042.9, self.close=26999.1, self.high=27045.3, self.low=26985.4, self.vol=1080.886, self.amt=29188219.9549, ukdf['pct'].iloc[-1]=-0.001623 , ukdf['amount'].iloc[-1]=29188219.9549, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.3392165721141667, signal=0, value_std=0.2776113634303561 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '5764.2832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26999.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=833
self.closeSec=1684283099, self.tradeDate='20230517', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26999.1, self.close=26983.6, self.high=27001.9, self.low=26975.0, self.vol=545.446, self.amt=14720140.6434 
127.0.0.1 - - [17/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-17 08:25:00,447:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230517   080000    080459  ...    0.340200   0.277523       0
5857  20230517   080500    080959  ...    0.339872   0.277553       0
5858  20230517   081000    081459  ...    0.339544   0.277582       0
5859  20230517   081500    081959  ...    0.339217   0.277611       0
5860  20230517   082000    082459  ...    0.338886   0.277637       0

[5 rows x 18 columns]
2023-05-17 08:25:00,447:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684283099, self.tradeDate='20230517', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26999.1, self.close=26983.6, self.high=27001.9, self.low=26975.0, self.vol=545.446, self.amt=14720140.6434, ukdf['pct'].iloc[-1]=-0.000574 , ukdf['amount'].iloc[-1]=14720140.6434, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.3388861860464317, signal=0, value_std=0.2776374025563625 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '5188.5977', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26983.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

718  20230516   160000    195959  ...  62608.697  1.697098e+09 -0.007023
719  20230516   200000    235959  ...  89162.317  2.408574e+09 -0.000791
720  20230517   000000    035959  ...  53087.558  1.434175e+09 -0.004070
721  20230517   040000    075959  ...  28799.999  7.769224e+08  0.003971

[5 rows x 11 columns]
2023-05-17 08:00:02,088:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230516   120000    155959  1684223999  ...    717  0.502828  0.089948     NaN
718  20230516   160000    195959  1684238399  ...    718  0.552624  0.358453     NaN
719  20230516   200000    235959  1684252799  ...    719  0.485815 -0.056272     NaN
720  20230517   000000    035959  1684267199  ...    720  0.448909 -0.285992     NaN
721  20230517   040000    075959  1684281599  ...    721  0.625374  0.766509     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-10801.816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27024.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.436', 'enterprice': '26818.7', 'countrevence': '0', 'unrealprofit': '-10801.816', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27024.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-05-17 08:00:09,216:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1398962.3262006', 'total': '1398962.3262006', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-05-17 08:00:09,685:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-05-17 08:00:09,685:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 51.610, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42178F1684281609683I0L65'}
2023-05-17 08:00:09,708:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:5170800, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230517, closeTime:075959, close:27024.8, sign:1, total:1398962.3262006, side:buy  
127.0.0.1 - - [17/May/2023 08:00:09] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [17/May/2023 08:00:09] "POST / HTTP/1.1" 200 -
2023-05-17 08:00:09,712:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42177F1684281604085I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684281604498835, 'quantity': '52.436', 'price': '27024.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684281603013, 'updatetime': 1684281604498, 'tradetype': 'usdt', 'selfid': 42177, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684281604498, 'clientorderid': '42177F1684281604085I0L65', 'price': '27024.7', 'quantity': '52.436', 'commission': '1417.0671692', 'commissionasset': 'USDT', 'tradetime': 1684281604498, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684281604498}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-17 08:00:09,714:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42177F1684281604085I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684281604498835, 'quantity': '52.436', 'price': '27024.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684281603013, 'updatetime': 1684281604498, 'tradetype': 'usdt', 'selfid': 42177, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684281604498, 'clientorderid': '42177F1684281604085I0L65', 'price': '27024.7', 'quantity': '52.436', 'commission': '1417.0671692', 'commissionasset': 'USDT', 'tradetime': 1684281604498, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684281604498}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/May/2023 08:00:10] "POST / HTTP/1.1" 200 -
2023-05-17 08:00:10,135:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42178F1684281609683I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684281610098986, 'quantity': '51.61', 'price': '27024.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684281609228, 'updatetime': 1684281610098, 'tradetype': 'usdt', 'selfid': 42178, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684281610098, 'clientorderid': '42178F1684281609683I0L65', 'price': '27024.7', 'quantity': '51.61', 'commission': '1394.744767', 'commissionasset': 'USDT', 'tradetime': 1684281610098, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684281610098}], 'gatetype': 'simulator', 'handletime': 0}
2023-05-17 08:00:10,377:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42178F1684281609683I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1684281610098986, 'quantity': '51.61', 'price': '27024.7', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1684281609228, 'updatetime': 1684281610098, 'tradetype': 'usdt', 'selfid': 42178, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1684281610098, 'clientorderid': '42178F1684281609683I0L65', 'price': '27024.7', 'quantity': '51.61', 'commission': '1394.744767', 'commissionasset': 'USDT', 'tradetime': 1684281610098, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1684281610098}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [17/May/2023 08:00:10] "POST / HTTP/1.1" 200 -


