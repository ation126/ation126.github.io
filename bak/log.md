# 20230521 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [21/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1984
self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27062.1, self.close=27064.5, self.high=27064.6, self.low=27050.0, self.vol=390.928, self.amt=10577425.4372 
2023-05-21 08:20:02,236:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230521   075500    075959  ...    0.289657   0.324504       0
5856  20230521   080000    080459  ...    0.289539   0.324532       0
5857  20230521   080500    080959  ...    0.289419   0.324559       0
5858  20230521   081000    081459  ...    0.289298   0.324585       0
5859  20230521   081500    081959  ...    0.289175   0.324611       0

[5 rows x 18 columns]
2023-05-21 08:20:02,250:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27062.1, self.close=27064.5, self.high=27064.6, self.low=27050.0, self.vol=390.928, self.amt=10577425.4372, ukdf['pct'].iloc[-1]=9.2e-05 , ukdf['amount'].iloc[-1]=10577425.4372, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.2891749452376687, signal=0, value_std=0.3246112333214301 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2781.0222', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27064.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1985
self.closeSec=1684628699, self.tradeDate='20230521', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27064.5, self.close=27070.0, self.high=27072.0, self.low=27064.5, self.vol=328.321, self.amt=8887177.5399 
127.0.0.1 - - [21/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:25:00,830:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230521   080000    080459  ...    0.289539   0.324532       0
5857  20230521   080500    080959  ...    0.289419   0.324559       0
5858  20230521   081000    081459  ...    0.289298   0.324585       0
5859  20230521   081500    081959  ...    0.289175   0.324611       0
5860  20230521   082000    082459  ...    0.289052   0.324637       0

[5 rows x 18 columns]
2023-05-21 08:25:00,830:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684628699, self.tradeDate='20230521', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27064.5, self.close=27070.0, self.high=27072.0, self.low=27064.5, self.vol=328.321, self.amt=8887177.5399, ukdf['pct'].iloc[-1]=0.000203 , ukdf['amount'].iloc[-1]=8887177.5399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.28905187776147295, signal=0, value_std=0.32463685795196645 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-2856.2226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27070', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27062.1, self.close=27064.5, self.high=27064.6, self.low=27050.0 
127.0.0.1 - - [21/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:20:00,750:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27062.1, self.close=27064.5, self.high=27064.6, self.low=27050.0   
2023-05-21 08:20:01,331:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230521   075500    075959  1684627199  ...  27087.6 -0.000406   1535    5
1536  20230521   080000    080459  1684627499  ...  27075.9 -0.000292   1536    0
1537  20230521   080500    080959  1684627799  ...  27062.6 -0.000698   1537    1
1538  20230521   081000    081459  1684628099  ...  27050.0 -0.000026   1538    2
1539  20230521   081500    081959  1684628399  ...  27050.0  0.000092   1539    3

[5 rows x 11 columns]
2023-05-21 08:20:01,340:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=24, self.factor=0.4572540926162081, self.count=1987 

self.closeSec=1684628699, self.tradeDate='20230521', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27064.5, self.close=27070.0, self.high=27072.0, self.low=27064.5 
127.0.0.1 - - [21/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:25:00,752:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684628699, self.tradeDate='20230521', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27064.5, self.close=27070.0, self.high=27072.0, self.low=27064.5   
2023-05-21 08:25:00,808:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230521   080000    080459  1684627499  ...  27075.9 -0.000292   1536    0
1537  20230521   080500    080959  1684627799  ...  27062.6 -0.000698   1537    1
1538  20230521   081000    081459  1684628099  ...  27050.0 -0.000026   1538    2
1539  20230521   081500    081959  1684628399  ...  27050.0  0.000092   1539    3
1540  20230521   082000    082459  1684628699  ...  27064.5  0.000203   1540    4

[5 rows x 11 columns]
2023-05-21 08:25:00,809:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-21 08:00:17,743:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230521    052959  27002.2  ...  50.000000  0.535705  0.365572
5771  20230521    055959  27030.1  ...  49.583333  0.533442  0.366061
5772  20230521    062959  27023.8  ...  49.583333  0.534477  0.365858
5773  20230521    065959  27027.0  ...  50.000000  0.543493  0.360137
5774  20230521    072959  27054.8  ...  50.000000  0.542303  0.355443

[5 rows x 33 columns]
0.5452865064695009
acc is : 0.5452865064695009
2023-05-21 08:00:17,833:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.499870  0.500130       0  ...  0.892589  -1.0    0.0  0.978414
537     1  0.492197  0.507803       1  ...  0.892483  -1.0    0.0  0.978530
538     1  0.492113  0.507887       1  ...  0.891562  -1.0    0.0  0.979540
539     0  0.501126  0.498874       0  ...  0.891664  -1.0    0.0  0.979428
540     1  0.498345  0.501655       1  ...  0.890421  -1.0    0.0  0.980793

[5 rows x 10 columns]
2023-05-21 08:00:17,844:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.500016  0.499984       0  ...  0.892353  -1.0    0.0  0.986781
46     1  0.492254  0.507746       1  ...  0.907596  -1.0    0.0  0.984924
47     1  0.492017  0.507983       1  ...  0.906659  -1.0    0.0  0.977022
48     0  0.501436  0.498564       0  ...  0.891664  -1.0    0.0  0.979428
49     1  0.498345  0.501655       1  ...  0.890421  -1.0    0.0  0.980793

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-14395.2988', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27098.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230521   075000    075959  1684627199  27086.9  27089.5  0.000092
2023-05-21 08:00:00,408:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=992 

self.closeSec=1684627799, self.tradeDate='20230521', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27089.6', self.close='27062.7'
2023-05-21 08:10:00,354:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684627799, self.tradeDate='20230521', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27089.6', self.close='27062.7'
2023-05-21 08:10:00,393:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230521   072000    072959  1684625399  27054.9  27051.8 -0.000115
621  20230521   073000    073959  1684625999  27051.8  27063.3  0.000425
622  20230521   074000    074959  1684626599  27063.3    27087  0.000876
623  20230521   075000    075959  1684627199  27086.9  27089.5  0.000092
624  20230521   080000    080959  1684627799  27089.6  27062.7 -0.000989
2023-05-21 08:10:00,393:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=993 

self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27062.7', self.close='27064.5'
127.0.0.1 - - [21/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:20:02,292:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27062.7', self.close='27064.5'
2023-05-21 08:20:02,653:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230521   073000    073959  1684625999  27051.8  27063.3  0.000425
622  20230521   074000    074959  1684626599  27063.3    27087  0.000876
623  20230521   075000    075959  1684627199  27086.9  27089.5  0.000092
624  20230521   080000    080959  1684627799  27089.6  27062.7 -0.000989
625  20230521   081000    081959  1684628399  27062.7  27064.5  0.000067
2023-05-21 08:20:02,654:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230521   075000    075959  1684627199  27086.9  27089.5
2023-05-21 08:00:00,451:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [21/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=995 

self.closeSec=1684627799, self.tradeDate='20230521', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27089.6', self.close='27062.7'
2023-05-21 08:10:00,373:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684627799, self.tradeDate='20230521', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27089.6', self.close='27062.7'
2023-05-21 08:10:00,408:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230521   072000    072959  1684625399  27054.9  27051.8
17469  20230521   073000    073959  1684625999  27051.8  27063.3
17470  20230521   074000    074959  1684626599  27063.3    27087
17471  20230521   075000    075959  1684627199  27086.9  27089.5
17472  20230521   080000    080959  1684627799  27089.6  27062.7
2023-05-21 08:10:00,409:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=996 

self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27062.7', self.close='27064.5'
127.0.0.1 - - [21/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:20:03,074:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27062.7', self.close='27064.5'
2023-05-21 08:20:03,159:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230521   073000    073959  1684625999  27051.8  27063.3
17470  20230521   074000    074959  1684626599  27063.3    27087
17471  20230521   075000    075959  1684627199  27086.9  27089.5
17472  20230521   080000    080959  1684627799  27089.6  27062.7
17473  20230521   081000    081959  1684628399  27062.7  27064.5
2023-05-21 08:20:03,159:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230521   075000    075959  1684627199  27086.9  27089.5
2023-05-21 08:00:00,476:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [21/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=995 

self.closeSec=1684627799, self.tradeDate='20230521', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='27089.6', self.close='27062.7'
2023-05-21 08:10:00,331:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684627799, self.tradeDate='20230521', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='27089.6', self.close='27062.7'
2023-05-21 08:10:00,344:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230521   072000    072959  1684625399  27054.9  27051.8
12141  20230521   073000    073959  1684625999  27051.8  27063.3
12142  20230521   074000    074959  1684626599  27063.3    27087
12143  20230521   075000    075959  1684627199  27086.9  27089.5
12144  20230521   080000    080959  1684627799  27089.6  27062.7
2023-05-21 08:10:00,344:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=996 

self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='27062.7', self.close='27064.5'
127.0.0.1 - - [21/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:20:02,900:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='27062.7', self.close='27064.5'
2023-05-21 08:20:03,030:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230521   073000    073959  1684625999  27051.8  27063.3
12142  20230521   074000    074959  1684626599  27063.3    27087
12143  20230521   075000    075959  1684627199  27086.9  27089.5
12144  20230521   080000    080959  1684627799  27089.6  27062.7
12145  20230521   081000    081959  1684628399  27062.7  27064.5
2023-05-21 08:20:03,040:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [21/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1984
self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=27062.1, self.close=27064.5, self.high=27064.6, self.low=27050.0, self.vol=390.928, self.amt=10577425.4372 
2023-05-21 08:20:02,409:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230521   075500    075959  ...    0.052313   0.204480       0
5856  20230521   080000    080459  ...    0.051993   0.204082       0
5857  20230521   080500    080959  ...    0.051673   0.203681       0
5858  20230521   081000    081459  ...    0.051353   0.203280       0
5859  20230521   081500    081959  ...    0.051033   0.202875       0

[5 rows x 18 columns]
2023-05-21 08:20:02,431:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684628399, self.tradeDate='20230521', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=27062.1, self.close=27064.5, self.high=27064.6, self.low=27050.0, self.vol=390.928, self.amt=10577425.4372, ukdf['pct'].iloc[-1]=9.2e-05 , ukdf['amount'].iloc[-1]=10577425.4372, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.05103279091981201, signal=0, value_std=0.2028751028600013 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8193.3046', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27064.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1985
self.closeSec=1684628699, self.tradeDate='20230521', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=27064.5, self.close=27070.0, self.high=27072.0, self.low=27064.5, self.vol=328.321, self.amt=8887177.5399 
127.0.0.1 - - [21/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:25:00,831:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230521   080000    080459  ...    0.051993   0.204082       0
5857  20230521   080500    080959  ...    0.051673   0.203681       0
5858  20230521   081000    081459  ...    0.051353   0.203280       0
5859  20230521   081500    081959  ...    0.051033   0.202875       0
5860  20230521   082000    082459  ...    0.050719   0.202489       0

[5 rows x 18 columns]
2023-05-21 08:25:00,832:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684628699, self.tradeDate='20230521', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=27064.5, self.close=27070.0, self.high=27072.0, self.low=27064.5, self.vol=328.321, self.amt=8887177.5399, ukdf['pct'].iloc[-1]=0.000203 , ukdf['amount'].iloc[-1]=8887177.5399, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.05071947926331817, signal=0, value_std=0.2024887954433947 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '8393.866', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27070', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230520   200000    235959  1684598399  ...    719  0.175194 -1.504185    -1.0
720  20230521   000000    035959  1684612799  ...    720  0.175379 -1.464862    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '613.4331', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27058.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=41
self.closeSec=1684627199, self.tradeDate='20230521', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27054.3, self.close=27089.5, self.high=27129.9, self.low=26952.8, self.vol=21251.159, self.amt=574474908.9481 
2023-05-21 08:00:00,374:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684627199, self.tradeDate='20230521', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27054.3, self.close=27089.5, self.high=27129.9, self.low=26952.8, self.vol=21251.159, self.amt=574474908.9481 
127.0.0.1 - - [21/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-05-21 08:00:00,439:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230520   120000    155959  ...   9537.697  2.560345e+08 -0.000276
718  20230520   160000    195959  ...  15215.481  4.089376e+08  0.000998
719  20230520   200000    235959  ...  25544.438  6.872793e+08  0.002509
720  20230521   000000    035959  ...  52033.700  1.406918e+09  0.004392
721  20230521   040000    075959  ...  21251.159  5.744749e+08  0.001301

[5 rows x 11 columns]
2023-05-21 08:00:01,935:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230520   120000    155959  1684569599  ...    717  0.198884 -1.451841    -1.0
718  20230520   160000    195959  1684583999  ...    718  0.187873 -1.475185    -1.0
719  20230520   200000    235959  1684598399  ...    719  0.175194 -1.504185    -1.0
720  20230521   000000    035959  1684612799  ...    720  0.175379 -1.464862    -1.0
721  20230521   040000    075959  1684627199  ...    721  0.171653 -1.446670    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '-1169.47726843194', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27093.18671106', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


