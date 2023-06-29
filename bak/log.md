# 20230629 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13216
self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30105.6, self.close=30100.6, self.high=30118.0, self.low=30086.2, self.vol=393.679, self.amt=11850862.0706 
127.0.0.1 - - [29/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 08:20:07,865:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230629   075500    075959  ...         0.0        0.0       0
5856  20230629   080000    080459  ...         0.0        0.0       0
5857  20230629   080500    080959  ...         0.0        0.0       0
5858  20230629   081000    081459  ...         0.0        0.0       0
5859  20230629   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 08:20:07,905:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30105.6, self.close=30100.6, self.high=30118.0, self.low=30086.2, self.vol=393.679, self.amt=11850862.0706, ukdf['pct'].iloc[-1]=-0.000166 , ukdf['amount'].iloc[-1]=11850862.0706, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-45060.3582', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30100.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=13217
self.closeSec=1687998299, self.tradeDate='20230629', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30100.6, self.close=30139.9, self.high=30166.4, self.low=30100.5, self.vol=1656.198, self.amt=49925361.7368 
2023-06-29 08:25:00,776:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230629   080000    080459  ...         0.0        0.0       0
5857  20230629   080500    080959  ...         0.0        0.0       0
5858  20230629   081000    081459  ...         0.0        0.0       0
5859  20230629   081500    081959  ...         0.0        0.0       0
5860  20230629   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 08:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687998299, self.tradeDate='20230629', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30100.6, self.close=30139.9, self.high=30166.4, self.low=30100.5, self.vol=1656.198, self.amt=49925361.7368, ukdf['pct'].iloc[-1]=0.001306 , ukdf['amount'].iloc[-1]=49925361.7368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-45609.0426', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30140', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30105.6, self.close=30100.6, self.high=30118.0, self.low=30086.2 
127.0.0.1 - - [29/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 08:20:05,204:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30105.6, self.close=30100.6, self.high=30118.0, self.low=30086.2   
2023-06-29 08:20:06,803:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230629   075500    075959  1687996799  ...  30066.1 -0.000163   1535    5
1536  20230629   080000    080459  1687997099  ...  30064.0  0.000915   1536    0
1537  20230629   080500    080959  1687997399  ...  30071.6 -0.000764   1537    1
1538  20230629   081000    081459  1687997699  ...  30071.6  0.001131   1538    2
1539  20230629   081500    081959  1687997999  ...  30086.2 -0.000166   1539    3

[5 rows x 11 columns]
2023-06-29 08:20:06,814:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6706013874419077, self.count=13219 

self.closeSec=1687998299, self.tradeDate='20230629', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30100.6, self.close=30139.9, self.high=30166.4, self.low=30100.5 
2023-06-29 08:25:00,728:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687998299, self.tradeDate='20230629', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30100.6, self.close=30139.9, self.high=30166.4, self.low=30100.5   
2023-06-29 08:25:00,740:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230629   080000    080459  1687997099  ...  30064.0  0.000915   1536    0
1537  20230629   080500    080959  1687997399  ...  30071.6 -0.000764   1537    1
1538  20230629   081000    081459  1687997699  ...  30071.6  0.001131   1538    2
1539  20230629   081500    081959  1687997999  ...  30086.2 -0.000166   1539    3
1540  20230629   082000    082459  1687998299  ...  30100.5  0.001306   1540    4

[5 rows x 11 columns]
2023-06-29 08:25:00,740:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-29 08:00:21,007:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230629    052959  30090.9  ...  49.166667  0.452921  0.700424
5771  20230629    055959  30085.0  ...  49.583333  0.459727  0.691434
5772  20230629    062959  30121.9  ...  50.000000  0.466009  0.679922
5773  20230629    065959  30156.2  ...  49.583333  0.455654  0.673238
5774  20230629    072959  30090.6  ...  50.000000  0.459768  0.664844

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-06-29 08:00:21,110:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     1  0.495287  0.504713       1  ...  1.062529  -1.0    0.0  1.137904
537     0  0.516783  0.483217       1  ...  1.061323  -1.0    0.0  1.139196
538     0  0.513188  0.486812       0  ...  1.063628  -1.0    0.0  1.136721
539     1  0.495084  0.504916       1  ...  1.062851  -1.0    0.0  1.137552
540     0  0.505057  0.494943       0  ...  1.064481  -1.0    0.0  1.135807

[5 rows x 10 columns]
2023-06-29 08:00:21,138:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.495089  0.504911       1  ...  1.062529  -1.0    0.0  1.140985
46     0  0.516563  0.483437       1  ...  1.061323  -1.0    0.0  1.139876
47     0  0.513012  0.486988       0  ...  1.063628  -1.0    0.0  1.137155
48     1  0.495084  0.504916       1  ...  1.062851  -1.0    0.0  1.137552
49     0  0.505057  0.494943       0  ...  1.064481  -1.0    0.0  1.135807

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.381', 'enterprice': '30103.1', 'countrevence': '0', 'unrealprofit': '1002.1446', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30066.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230629   075000    075959  1687996799  30090.6  30066.3 -0.000811
2023-06-29 08:00:02,127:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6608 

self.closeSec=1687997399, self.tradeDate='20230629', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30066.3', self.close='30071.6'
2023-06-29 08:10:01,155:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687997399, self.tradeDate='20230629', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30066.3', self.close='30071.6'
127.0.0.1 - - [29/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-29 08:10:01,162:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230629   072000    072959  1687994999  30142.1  30112.7 -0.000975
621  20230629   073000    073959  1687995599  30112.6  30063.9 -0.001621
622  20230629   074000    074959  1687996199  30063.9  30090.7  0.000891
623  20230629   075000    075959  1687996799  30090.6  30066.3 -0.000811
624  20230629   080000    080959  1687997399  30066.3  30071.6  0.000176
2023-06-29 08:10:01,164:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6609 

self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30071.7', self.close='30100.6'
127.0.0.1 - - [29/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 08:20:07,875:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30071.7', self.close='30100.6'
2023-06-29 08:20:08,763:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230629   073000    073959  1687995599  30112.6  30063.9 -0.001621
622  20230629   074000    074959  1687996199  30063.9  30090.7  0.000891
623  20230629   075000    075959  1687996799  30090.6  30066.3 -0.000811
624  20230629   080000    080959  1687997399  30066.3  30071.6  0.000176
625  20230629   081000    081959  1687997999  30071.7  30100.6  0.000964
2023-06-29 08:20:08,764:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230629   075000    075959  1687996799  30090.6  30066.3
2023-06-29 08:00:02,138:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6611 

self.closeSec=1687997399, self.tradeDate='20230629', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30066.3', self.close='30071.6'
2023-06-29 08:10:01,178:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687997399, self.tradeDate='20230629', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30066.3', self.close='30071.6'
127.0.0.1 - - [29/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-29 08:10:01,192:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230629   072000    072959  1687994999  30142.1  30112.7
17469  20230629   073000    073959  1687995599  30112.6  30063.9
17470  20230629   074000    074959  1687996199  30063.9  30090.7
17471  20230629   075000    075959  1687996799  30090.6  30066.3
17472  20230629   080000    080959  1687997399  30066.3  30071.6
2023-06-29 08:10:01,192:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6612 

self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30071.7', self.close='30100.6'
127.0.0.1 - - [29/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-29 08:20:10,027:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30071.7', self.close='30100.6'
2023-06-29 08:20:10,169:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230629   073000    073959  1687995599  30112.6  30063.9
17470  20230629   074000    074959  1687996199  30063.9  30090.7
17471  20230629   075000    075959  1687996799  30090.6  30066.3
17472  20230629   080000    080959  1687997399  30066.3  30071.6
17473  20230629   081000    081959  1687997999  30071.7  30100.6
2023-06-29 08:20:10,169:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230629   075000    075959  1687996799  30090.6  30066.3
2023-06-29 08:00:02,134:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6611 

self.closeSec=1687997399, self.tradeDate='20230629', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30066.3', self.close='30071.6'
2023-06-29 08:10:01,169:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687997399, self.tradeDate='20230629', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30066.3', self.close='30071.6'
127.0.0.1 - - [29/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-06-29 08:10:01,189:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230629   072000    072959  1687994999  30142.1  30112.7
12141  20230629   073000    073959  1687995599  30112.6  30063.9
12142  20230629   074000    074959  1687996199  30063.9  30090.7
12143  20230629   075000    075959  1687996799  30090.6  30066.3
12144  20230629   080000    080959  1687997399  30066.3  30071.6
2023-06-29 08:10:01,189:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6612 

self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30071.7', self.close='30100.6'
127.0.0.1 - - [29/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-29 08:20:09,525:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30071.7', self.close='30100.6'
2023-06-29 08:20:09,854:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230629   073000    073959  1687995599  30112.6  30063.9
12142  20230629   074000    074959  1687996199  30063.9  30090.7
12143  20230629   075000    075959  1687996799  30090.6  30066.3
12144  20230629   080000    080959  1687997399  30066.3  30071.6
12145  20230629   081000    081959  1687997999  30071.7  30100.6
2023-06-29 08:20:09,856:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13216
self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30105.6, self.close=30100.6, self.high=30118.0, self.low=30086.2, self.vol=393.679, self.amt=11850862.0706 
127.0.0.1 - - [29/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-29 08:20:07,904:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230629   075500    075959  ...         0.0        0.0       0
5856  20230629   080000    080459  ...         0.0        0.0       0
5857  20230629   080500    080959  ...         0.0        0.0       0
5858  20230629   081000    081459  ...         0.0        0.0       0
5859  20230629   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 08:20:07,924:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687997999, self.tradeDate='20230629', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30105.6, self.close=30100.6, self.high=30118.0, self.low=30086.2, self.vol=393.679, self.amt=11850862.0706, ukdf['pct'].iloc[-1]=-0.000166 , ukdf['amount'].iloc[-1]=11850862.0706, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '120953.3806', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30100.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=13217
self.closeSec=1687998299, self.tradeDate='20230629', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30100.6, self.close=30139.9, self.high=30166.4, self.low=30100.5, self.vol=1656.198, self.amt=49925361.7368 
2023-06-29 08:25:00,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230629   080000    080459  ...         0.0        0.0       0
5857  20230629   080500    080959  ...         0.0        0.0       0
5858  20230629   081000    081459  ...         0.0        0.0       0
5859  20230629   081500    081959  ...         0.0        0.0       0
5860  20230629   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-29 08:25:00,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687998299, self.tradeDate='20230629', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30100.6, self.close=30139.9, self.high=30166.4, self.low=30100.5, self.vol=1656.198, self.amt=49925361.7368, ukdf['pct'].iloc[-1]=0.001306 , ukdf['amount'].iloc[-1]=49925361.7368, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '122416.736', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30140', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230628   200000    235959  1687967999  ...    719  0.322935 -0.594812     NaN
720  20230629   000000    035959  1687982399  ...    720  0.268669 -0.741625    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '33123.19966168236', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30085.17827473', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=275
self.closeSec=1687996799, self.tradeDate='20230629', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30080.5, self.close=30066.3, self.high=30209.6, self.low=29929.2, self.vol=40288.685, self.amt=1211924634.95902 
127.0.0.1 - - [29/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-29 08:00:01,642:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687996799, self.tradeDate='20230629', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30080.5, self.close=30066.3, self.high=30209.6, self.low=29929.2, self.vol=40288.685, self.amt=1211924634.95902 
2023-06-29 08:00:01,682:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230628   120000    155959  ...   53843.360  1.631942e+09 -0.008699
718  20230628   160000    195959  ...   42990.331  1.301075e+09  0.003887
719  20230628   200000    235959  ...  125197.930  3.784724e+09  0.003483
720  20230629   000000    035959  ...  101722.691  3.064347e+09 -0.010507
721  20230629   040000    075959  ...   40288.685  1.211925e+09 -0.000469

[5 rows x 11 columns]
2023-06-29 08:00:03,125:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230628   120000    155959  1687939199  ...    717  0.254736 -0.770019    -1.0
718  20230628   160000    195959  1687953599  ...    718  0.303718 -0.641460    -1.0
719  20230628   200000    235959  1687967999  ...    719  0.322935 -0.594812     NaN
720  20230629   000000    035959  1687982399  ...    720  0.268669 -0.741625    -1.0
721  20230629   040000    075959  1687996799  ...    721  0.331663 -0.588163     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '34128.8076', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30066.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


