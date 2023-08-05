# 20230805 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23872
self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29097.7, self.close=29088.1, self.high=29098.0, self.low=29088.0, self.vol=342.291, self.amt=9957871.3495 
127.0.0.1 - - [05/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 08:20:06,730:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230805   075500    075959  ...         0.0        0.0       0
5856  20230805   080000    080459  ...         0.0        0.0       0
5857  20230805   080500    080959  ...         0.0        0.0       0
5858  20230805   081000    081459  ...         0.0        0.0       0
5859  20230805   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 08:20:06,741:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29097.7, self.close=29088.1, self.high=29098.0, self.low=29088.0, self.vol=342.291, self.amt=9957871.3495, ukdf['pct'].iloc[-1]=-0.00033 , ukdf['amount'].iloc[-1]=9957871.3495, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30960.2832', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29088.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [05/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23873
self.closeSec=1691195099, self.tradeDate='20230805', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29088.0, self.close=29088.4, self.high=29088.7, self.low=29081.1, self.vol=482.985, self.amt=14048377.0437 
2023-08-05 08:25:00,766:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230805   080000    080459  ...         0.0        0.0       0
5857  20230805   080500    080959  ...         0.0        0.0       0
5858  20230805   081000    081459  ...         0.0        0.0       0
5859  20230805   081500    081959  ...         0.0        0.0       0
5860  20230805   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 08:25:00,766:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691195099, self.tradeDate='20230805', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29088.0, self.close=29088.4, self.high=29088.7, self.low=29081.1, self.vol=482.985, self.amt=14048377.0437, ukdf['pct'].iloc[-1]=1e-05 , ukdf['amount'].iloc[-1]=14048377.0437, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30964.461', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29088.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29097.7, self.close=29088.1, self.high=29098.0, self.low=29088.0 
127.0.0.1 - - [05/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 08:20:04,570:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29097.7, self.close=29088.1, self.high=29098.0, self.low=29088.0   
2023-08-05 08:20:05,790:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230805   075500    075959  1691193599  ...  29099.8  0.000041   1535    5
1536  20230805   080000    080459  1691193899  ...  29097.3  0.000058   1536    0
1537  20230805   080500    080959  1691194199  ...  29102.0  0.000450   1537    1
1538  20230805   081000    081459  1691194499  ...  29097.7 -0.000625   1538    2
1539  20230805   081500    081959  1691194799  ...  29088.0 -0.000330   1539    3

[5 rows x 11 columns]
2023-08-05 08:20:05,791:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=27, self.factor=0.5798618357323785, self.count=23875 

self.closeSec=1691195099, self.tradeDate='20230805', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29088.0, self.close=29088.4, self.high=29088.7, self.low=29081.1 
127.0.0.1 - - [05/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-05 08:25:00,749:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691195099, self.tradeDate='20230805', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29088.0, self.close=29088.4, self.high=29088.7, self.low=29081.1   
2023-08-05 08:25:00,769:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230805   080000    080459  1691193899  ...  29097.3  0.000058   1536    0
1537  20230805   080500    080959  1691194199  ...  29102.0  0.000450   1537    1
1538  20230805   081000    081459  1691194499  ...  29097.7 -0.000625   1538    2
1539  20230805   081500    081959  1691194799  ...  29088.0 -0.000330   1539    3
1540  20230805   082000    082459  1691195099  ...  29081.1  0.000010   1540    4

[5 rows x 11 columns]
2023-08-05 08:25:00,770:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-05 08:00:17,198:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230805    052959  28952.1  ...  45.416667  0.451133  0.582377
5771  20230805    055959  29030.1  ...  45.416667  0.455273  0.578038
5772  20230805    062959  29042.5  ...  45.833333  0.462083  0.571487
5773  20230805    065959  29062.9  ...  45.416667  0.456319  0.567849
5774  20230805    072959  29042.8  ...  45.416667  0.459181  0.563424

[5 rows x 33 columns]
0.5526802218114603
acc is : 0.5526802218114603
2023-08-05 08:00:17,266:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.518244  0.481756       1  ...  0.983474   1.0    0.0  0.998141
537     0  0.502823  0.497177       1  ...  0.984165   1.0    0.0  0.998842
538     0  0.505997  0.494003       0  ...  0.983481   1.0    0.0  0.998148
539     1  0.492170  0.507830       1  ...  0.983765   1.0    0.0  0.998436
540     0  0.507085  0.492915       1  ...  0.985458   1.0    0.0  1.000155

[5 rows x 10 columns]
2023-08-05 08:00:17,279:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518450  0.481550       1  ...  0.983474   1.0    0.0  0.998539
46     0  0.502814  0.497186       1  ...  0.984165   1.0    0.0  0.999137
47     0  0.505793  0.494207       0  ...  0.983481   1.0    0.0  0.998096
48     1  0.492454  0.507546       1  ...  0.983765   1.0    0.0  0.998436
49     0  0.507085  0.492915       1  ...  0.985458   1.0    0.0  1.000155

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-724.957055757', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29101.36878405', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230805   075000    075959  1691193599  29102.2  29101.1 -0.000034
2023-08-05 08:00:02,176:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [05/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11936 

self.closeSec=1691194199, self.tradeDate='20230805', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29101.1', self.close='29115.9'
2023-08-05 08:10:01,176:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691194199, self.tradeDate='20230805', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29101.1', self.close='29115.9'
2023-08-05 08:10:01,189:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230805   072000    072959  1691191799  29061.6  29051.1 -0.000361
621  20230805   073000    073959  1691192399  29051.1    29070  0.000651
622  20230805   074000    074959  1691192999    29070  29102.1  0.001104
623  20230805   075000    075959  1691193599  29102.2  29101.1 -0.000034
624  20230805   080000    080959  1691194199  29101.1  29115.9  0.000509
2023-08-05 08:10:01,189:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11937 

self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29115.8', self.close='29088.1'
127.0.0.1 - - [05/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 08:20:06,991:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29115.8', self.close='29088.1'
2023-08-05 08:20:07,640:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230805   073000    073959  1691192399  29051.1    29070  0.000651
622  20230805   074000    074959  1691192999    29070  29102.1  0.001104
623  20230805   075000    075959  1691193599  29102.2  29101.1 -0.000034
624  20230805   080000    080959  1691194199  29101.1  29115.9  0.000509
625  20230805   081000    081959  1691194799  29115.8  29088.1 -0.000955
2023-08-05 08:20:07,641:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230805   075000    075959  1691193599  29102.2  29101.1
2023-08-05 08:00:02,194:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11939 

self.closeSec=1691194199, self.tradeDate='20230805', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29101.1', self.close='29115.9'
2023-08-05 08:10:01,182:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691194199, self.tradeDate='20230805', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29101.1', self.close='29115.9'
127.0.0.1 - - [05/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-05 08:10:01,191:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230805   072000    072959  1691191799  29061.6  29051.1
17469  20230805   073000    073959  1691192399  29051.1    29070
17470  20230805   074000    074959  1691192999    29070  29102.1
17471  20230805   075000    075959  1691193599  29102.2  29101.1
17472  20230805   080000    080959  1691194199  29101.1  29115.9
2023-08-05 08:10:01,191:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11940 

self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29115.8', self.close='29088.1'
127.0.0.1 - - [05/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 08:20:08,753:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29115.8', self.close='29088.1'
2023-08-05 08:20:08,839:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230805   073000    073959  1691192399  29051.1    29070
17470  20230805   074000    074959  1691192999    29070  29102.1
17471  20230805   075000    075959  1691193599  29102.2  29101.1
17472  20230805   080000    080959  1691194199  29101.1  29115.9
17473  20230805   081000    081959  1691194799  29115.8  29088.1
2023-08-05 08:20:08,840:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230805   075000    075959  1691193599  29102.2  29101.1
2023-08-05 08:00:02,179:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11939 

self.closeSec=1691194199, self.tradeDate='20230805', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='29101.1', self.close='29115.9'
2023-08-05 08:10:01,175:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691194199, self.tradeDate='20230805', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='29101.1', self.close='29115.9'
127.0.0.1 - - [05/Aug/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-08-05 08:10:01,182:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230805   072000    072959  1691191799  29061.6  29051.1
12141  20230805   073000    073959  1691192399  29051.1    29070
12142  20230805   074000    074959  1691192999    29070  29102.1
12143  20230805   075000    075959  1691193599  29102.2  29101.1
12144  20230805   080000    080959  1691194199  29101.1  29115.9
2023-08-05 08:10:01,183:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11940 

self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='29115.8', self.close='29088.1'
127.0.0.1 - - [05/Aug/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-08-05 08:20:08,522:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='29115.8', self.close='29088.1'
2023-08-05 08:20:08,730:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230805   073000    073959  1691192399  29051.1    29070
12142  20230805   074000    074959  1691192999    29070  29102.1
12143  20230805   075000    075959  1691193599  29102.2  29101.1
12144  20230805   080000    080959  1691194199  29101.1  29115.9
12145  20230805   081000    081959  1691194799  29115.8  29088.1
2023-08-05 08:20:08,731:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23872
self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=29097.7, self.close=29088.1, self.high=29098.0, self.low=29088.0, self.vol=342.291, self.amt=9957871.3495 
127.0.0.1 - - [05/Aug/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-08-05 08:20:06,710:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230805   075500    075959  ...         0.0        0.0       0
5856  20230805   080000    080459  ...         0.0        0.0       0
5857  20230805   080500    080959  ...         0.0        0.0       0
5858  20230805   081000    081459  ...         0.0        0.0       0
5859  20230805   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 08:20:06,730:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691194799, self.tradeDate='20230805', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=29097.7, self.close=29088.1, self.high=29098.0, self.low=29088.0, self.vol=342.291, self.amt=9957871.3495, ukdf['pct'].iloc[-1]=-0.00033 , ukdf['amount'].iloc[-1]=9957871.3495, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '83348.1181', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29088.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23873
self.closeSec=1691195099, self.tradeDate='20230805', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=29088.0, self.close=29088.4, self.high=29088.7, self.low=29081.1, self.vol=482.985, self.amt=14048377.0437 
127.0.0.1 - - [05/Aug/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-08-05 08:25:00,779:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230805   080000    080459  ...         0.0        0.0       0
5857  20230805   080500    080959  ...         0.0        0.0       0
5858  20230805   081000    081459  ...         0.0        0.0       0
5859  20230805   081500    081959  ...         0.0        0.0       0
5860  20230805   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-05 08:25:00,780:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691195099, self.tradeDate='20230805', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=29088.0, self.close=29088.4, self.high=29088.7, self.low=29081.1, self.vol=482.985, self.amt=14048377.0437, ukdf['pct'].iloc[-1]=1e-05 , ukdf['amount'].iloc[-1]=14048377.0437, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '83359.2604', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29088.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230804   200000    235959  1691164799  ...    719  0.461738  0.942720     1.0
720  20230805   000000    035959  1691179199  ...    720  0.453520  0.882942     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '-988.74763805475', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29016.74892491', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1588790.78883, self.flagDict['side']='buy', self.tradeCount=17, self.count=497
self.closeSec=1691193599, self.tradeDate='20230805', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=29021.0, self.close=29101.1, self.high=29115.0, self.low=28780.0, self.vol=48349.502, self.amt=1401817326.40889 
127.0.0.1 - - [05/Aug/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-08-05 08:00:01,707:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691193599, self.tradeDate='20230805', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=29021.0, self.close=29101.1, self.high=29115.0, self.low=28780.0, self.vol=48349.502, self.amt=1401817326.40889 
2023-08-05 08:00:01,721:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230804   120000    155959  ...  18873.441  5.509091e+08  0.001681
718  20230804   160000    195959  ...  22514.238  6.569968e+08 -0.001520
719  20230804   200000    235959  ...  53716.396  1.569762e+09  0.003485
720  20230805   000000    035959  ...  61493.335  1.788545e+09 -0.008127
721  20230805   040000    075959  ...  48349.502  1.401817e+09  0.002760

[5 rows x 11 columns]
2023-08-05 08:00:02,439:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230804   120000    155959  1691135999  ...    717  0.406703  0.700907     1.0
718  20230804   160000    195959  1691150399  ...    718  0.428782  0.798047     1.0
719  20230804   200000    235959  1691164799  ...    719  0.461738  0.942720     1.0
720  20230805   000000    035959  1691179199  ...    720  0.453520  0.882942     1.0
721  20230805   040000    075959  1691193599  ...    721  0.470379  0.946624     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.775', 'enterprice': '29034.8', 'countrevence': '0', 'unrealprofit': '3687.15024707225', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29102.11447279', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


