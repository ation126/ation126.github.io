# 20230308 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29020
self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22236.2, self.close=22244.3, self.high=22248.0, self.low=22221.9, self.vol=1191.95, self.amt=26503209.2538 
127.0.0.1 - - [08/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 08:20:01,889:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230308   075500    075959  ...         0.0        0.0       0
5856  20230308   080000    080459  ...         0.0        0.0       0
5857  20230308   080500    080959  ...         0.0        0.0       0
5858  20230308   081000    081459  ...         0.0        0.0       0
5859  20230308   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 08:20:01,891:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22236.2, self.close=22244.3, self.high=22248.0, self.low=22221.9, self.vol=1191.95, self.amt=26503209.2538, ukdf['pct'].iloc[-1]=0.000364 , ukdf['amount'].iloc[-1]=26503209.2538, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-343863.7168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22243.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=29021
self.closeSec=1678235099, self.tradeDate='20230308', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22243.7, self.close=22236.9, self.high=22256.9, self.low=22235.0, self.vol=898.265, self.amt=19981881.6936 
127.0.0.1 - - [08/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-08 08:25:01,654:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230308   080000    080459  ...         0.0        0.0       0
5857  20230308   080500    080959  ...         0.0        0.0       0
5858  20230308   081000    081459  ...         0.0        0.0       0
5859  20230308   081500    081959  ...         0.0        0.0       0
5860  20230308   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 08:25:01,659:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1678235099, self.tradeDate='20230308', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22243.7, self.close=22236.9, self.high=22256.9, self.low=22235.0, self.vol=898.265, self.amt=19981881.6936, ukdf['pct'].iloc[-1]=-0.000333 , ukdf['amount'].iloc[-1]=19981881.6936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-343465.31971992464', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22236.97946889', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.671709245930877, self.count=29586 

self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22236.2, self.close=22244.3, self.high=22248.0, self.low=22221.9 
2023-03-08 08:20:01,530:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22236.2, self.close=22244.3, self.high=22248.0, self.low=22221.9   
2023-03-08 08:20:01,597:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230308   075500    075959  1678233599  ...  22182.2  0.000063   1535    5
1536  20230308   080000    080459  1678233899  ...  22177.0  0.003083   1536    0
1537  20230308   080500    080959  1678234199  ...  22206.1 -0.001806   1537    1
1538  20230308   081000    081459  1678234499  ...  22214.7  0.000941   1538    2
1539  20230308   081500    081959  1678234799  ...  22221.9  0.000364   1539    3

[5 rows x 11 columns]
2023-03-08 08:20:01,597:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [08/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.671709245930877, self.count=29587 

self.closeSec=1678235099, self.tradeDate='20230308', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22243.7, self.close=22236.9, self.high=22256.9, self.low=22235.0 
2023-03-08 08:25:01,523:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1678235099, self.tradeDate='20230308', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22243.7, self.close=22236.9, self.high=22256.9, self.low=22235.0   
2023-03-08 08:25:01,611:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230308   080000    080459  1678233899  ...  22177.0  0.003083   1536    0
1537  20230308   080500    080959  1678234199  ...  22206.1 -0.001806   1537    1
1538  20230308   081000    081459  1678234499  ...  22214.7  0.000941   1538    2
1539  20230308   081500    081959  1678234799  ...  22221.9  0.000364   1539    3
1540  20230308   082000    082459  1678235099  ...  22235.0 -0.000333   1540    4

[5 rows x 11 columns]
2023-03-08 08:25:01,611:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-08 08:00:34,381:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230308    052959  22047.4  ...  43.750000  0.386089  0.624349
5771  20230308    055959  22011.0  ...  44.166667  0.399878  0.635052
5772  20230308    062959  22046.0  ...  44.166667  0.420464  0.639392
5773  20230308    065959  22100.5  ...  44.166667  0.419788  0.643703
5774  20230308    072959  22098.0  ...  44.583333  0.432838  0.641339

[5 rows x 33 columns]
0.5471349353049908
acc is : 0.5471349353049908
2023-03-08 08:00:34,541:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.469312  0.530688       1  ...  0.953472  -1.0    0.0  0.954211
537     0  0.506844  0.493156       1  ...  0.951119  -1.0    0.0  0.956566
538     0  0.535343  0.464657       0  ...  0.951227  -1.0    0.0  0.956458
539     0  0.525277  0.474723       1  ...  0.949716  -1.0    0.0  0.957977
540     0  0.542234  0.457766       1  ...  0.947399  -1.0    0.0  0.960314

[5 rows x 10 columns]
2023-03-08 08:00:34,576:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.469499  0.530501       1  ...  0.963011  -1.0    0.0  0.944680
46     0  0.506981  0.493019       1  ...  0.921316  -1.0    0.0  0.955499
47     0  0.534695  0.465305       0  ...  0.951227  -1.0    0.0  0.953330
48     0  0.525753  0.474247       1  ...  0.949716  -1.0    0.0  0.957977
49     0  0.542234  0.457766       1  ...  0.947399  -1.0    0.0  0.960314

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '31.561', 'enterprice': '22386.6', 'countrevence': '0', 'unrealprofit': '6265.12521853929', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22188.09154911', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230308   075000    075959  1678233599  22179.7  22187.1  0.000334
2023-03-08 08:00:02,092:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14792 

self.closeSec=1678234199, self.tradeDate='20230308', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22187.1', self.close='22215.3'
2023-03-08 08:10:01,710:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678234199, self.tradeDate='20230308', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22187.1', self.close='22215.3'
2023-03-08 08:10:01,739:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230308   072000    072959  1678231799  22100.3  22133.1  0.001480
621  20230308   073000    073959  1678232399  22133.1  22196.1  0.002846
622  20230308   074000    074959  1678232999  22196.1  22179.7 -0.000739
623  20230308   075000    075959  1678233599  22179.7  22187.1  0.000334
624  20230308   080000    080959  1678234199  22187.1  22215.3  0.001271
2023-03-08 08:10:01,740:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14793 

self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22215.2', self.close='22244.3'
2023-03-08 08:20:01,861:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22215.2', self.close='22244.3'
2023-03-08 08:20:01,913:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230308   073000    073959  1678232399  22133.1  22196.1  0.002846
622  20230308   074000    074959  1678232999  22196.1  22179.7 -0.000739
623  20230308   075000    075959  1678233599  22179.7  22187.1  0.000334
624  20230308   080000    080959  1678234199  22187.1  22215.3  0.001271
625  20230308   081000    081959  1678234799  22215.2  22244.3  0.001305
2023-03-08 08:20:01,914:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230308   075000    075959  1678233599  22179.7  22187.1
2023-03-08 08:00:02,104:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [08/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14793 

self.closeSec=1678234199, self.tradeDate='20230308', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22187.1', self.close='22215.3'
2023-03-08 08:10:01,734:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678234199, self.tradeDate='20230308', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22187.1', self.close='22215.3'
2023-03-08 08:10:01,768:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230308   072000    072959  1678231799  22100.3  22133.1
17469  20230308   073000    073959  1678232399  22133.1  22196.1
17470  20230308   074000    074959  1678232999  22196.1  22179.7
17471  20230308   075000    075959  1678233599  22179.7  22187.1
17472  20230308   080000    080959  1678234199  22187.1  22215.3
2023-03-08 08:10:01,768:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [08/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14794 

self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22215.2', self.close='22244.3'
2023-03-08 08:20:02,092:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22215.2', self.close='22244.3'
2023-03-08 08:20:02,163:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230308   073000    073959  1678232399  22133.1  22196.1
17470  20230308   074000    074959  1678232999  22196.1  22179.7
17471  20230308   075000    075959  1678233599  22179.7  22187.1
17472  20230308   080000    080959  1678234199  22187.1  22215.3
17473  20230308   081000    081959  1678234799  22215.2  22244.3
2023-03-08 08:20:02,163:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230308   075000    075959  1678233599  22179.7  22187.1
2023-03-08 08:00:02,120:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14793 

self.closeSec=1678234199, self.tradeDate='20230308', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='22187.1', self.close='22215.3'
2023-03-08 08:10:01,726:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678234199, self.tradeDate='20230308', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='22187.1', self.close='22215.3'
127.0.0.1 - - [08/Mar/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-03-08 08:10:01,743:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230308   072000    072959  1678231799  22100.3  22133.1
12141  20230308   073000    073959  1678232399  22133.1  22196.1
12142  20230308   074000    074959  1678232999  22196.1  22179.7
12143  20230308   075000    075959  1678233599  22179.7  22187.1
12144  20230308   080000    080959  1678234199  22187.1  22215.3
2023-03-08 08:10:01,743:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=14794 

self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='22215.2', self.close='22244.3'
127.0.0.1 - - [08/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 08:20:02,042:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='22215.2', self.close='22244.3'
2023-03-08 08:20:02,120:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230308   073000    073959  1678232399  22133.1  22196.1
12142  20230308   074000    074959  1678232999  22196.1  22179.7
12143  20230308   075000    075959  1678233599  22179.7  22187.1
12144  20230308   080000    080959  1678234199  22187.1  22215.3
12145  20230308   081000    081959  1678234799  22215.2  22244.3
2023-03-08 08:20:02,121:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25018
self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=22236.2, self.close=22244.3, self.high=22248.0, self.low=22221.9, self.vol=1191.95, self.amt=26503209.2538 
127.0.0.1 - - [08/Mar/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-03-08 08:20:01,617:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230308   075500    075959  ...         0.0        0.0       0
5856  20230308   080000    080459  ...         0.0        0.0       0
5857  20230308   080500    080959  ...         0.0        0.0       0
5858  20230308   081000    081459  ...         0.0        0.0       0
5859  20230308   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 08:20:01,621:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678234799, self.tradeDate='20230308', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=22236.2, self.close=22244.3, self.high=22248.0, self.low=22221.9, self.vol=1191.95, self.amt=26503209.2538, ukdf['pct'].iloc[-1]=0.000364 , ukdf['amount'].iloc[-1]=26503209.2538, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=25019
self.closeSec=1678235099, self.tradeDate='20230308', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=22243.7, self.close=22236.9, self.high=22256.9, self.low=22235.0, self.vol=898.265, self.amt=19981881.6936 
127.0.0.1 - - [08/Mar/2023 08:25:01] "POST / HTTP/1.1" 200 -
2023-03-08 08:25:01,572:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230308   080000    080459  ...         0.0        0.0       0
5857  20230308   080500    080959  ...         0.0        0.0       0
5858  20230308   081000    081459  ...         0.0        0.0       0
5859  20230308   081500    081959  ...         0.0        0.0       0
5860  20230308   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-08 08:25:01,572:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1678235099, self.tradeDate='20230308', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=22243.7, self.close=22236.9, self.high=22256.9, self.low=22235.0, self.vol=898.265, self.amt=19981881.6936, ukdf['pct'].iloc[-1]=-0.000333 , ukdf['amount'].iloc[-1]=19981881.6936, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230307   200000    235959  1678204799  ...    719  0.000088 -1.989372    -1.0
720  20230308   000000    035959  1678219199  ...    720  0.000843 -1.949908    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '52129.422', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22113.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=982881.0256095, self.flagDict['side']='sell', self.tradeCount=23, self.count=616
self.closeSec=1678233599, self.tradeDate='20230308', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=22118.5, self.close=22187.1, self.high=22223.4, self.low=21929.0, self.vol=95482.633, self.amt=2106799682.4225 
2023-03-08 08:00:01,924:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1678233599, self.tradeDate='20230308', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=22118.5, self.close=22187.1, self.high=22223.4, self.low=21929.0, self.vol=95482.633, self.amt=2106799682.4225 
127.0.0.1 - - [08/Mar/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-03-08 08:00:01,969:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230307   120000    155959  ...   18027.295  4.044412e+08 -0.001809
718  20230307   160000    195959  ...   42943.905  9.607982e+08 -0.003066
719  20230307   200000    235959  ...  241400.179  5.364881e+09 -0.001446
720  20230308   000000    035959  ...  111943.438  2.490485e+09 -0.008419
721  20230308   040000    075959  ...   95482.633  2.106800e+09  0.003047

[5 rows x 11 columns]
2023-03-08 08:00:04,576:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230307   120000    155959  1678175999  ...    717  0.003245 -2.049317    -1.0
718  20230307   160000    195959  1678190399  ...    718  0.002246 -2.019326    -1.0
719  20230307   200000    235959  1678204799  ...    719  0.000088 -1.989372    -1.0
720  20230308   000000    035959  1678219199  ...    720  0.000843 -1.949908    -1.0
721  20230308   040000    075959  1678233599  ...    721  0.012961 -1.878141    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '42.135', 'enterprice': '23350.3', 'countrevence': '0', 'unrealprofit': '48994.3628747013', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '22187.50510562', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


