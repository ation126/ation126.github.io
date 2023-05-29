# 20230529 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4288
self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28184.4, self.close=28351.0, self.high=28370.0, self.low=28181.0, self.vol=13306.114, self.amt=376277928.78463 
127.0.0.1 - - [29/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 08:20:06,172:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230529   075500    075959  ...         0.0        0.0       0
5856  20230529   080000    080459  ...         0.0        0.0       0
5857  20230529   080500    080959  ...         0.0        0.0       0
5858  20230529   081000    081459  ...         0.0        0.0       0
5859  20230529   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 08:20:06,202:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28184.4, self.close=28351.0, self.high=28370.0, self.low=28181.0, self.vol=13306.114, self.amt=376277928.78463, ukdf['pct'].iloc[-1]=0.005908 , ukdf['amount'].iloc[-1]=376277928.78463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-20308.67458161168', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28323.22791768', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4289
self.closeSec=1685319899, self.tradeDate='20230529', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28340.0, self.close=28382.3, self.high=28442.0, self.low=28304.0, self.vol=10502.951, self.amt=298082439.2334 
2023-05-29 08:25:00,887:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230529   080000    080459  ...         0.0        0.0       0
5857  20230529   080500    080959  ...         0.0        0.0       0
5858  20230529   081000    081459  ...         0.0        0.0       0
5859  20230529   081500    081959  ...         0.0        0.0       0
5860  20230529   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 08:25:00,889:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685319899, self.tradeDate='20230529', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28340.0, self.close=28382.3, self.high=28442.0, self.low=28304.0, self.vol=10502.951, self.amt=298082439.2334, ukdf['pct'].iloc[-1]=0.001104 , ukdf['amount'].iloc[-1]=298082439.2334, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-21228.85159603164', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28389.30410714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28184.4, self.close=28351.0, self.high=28370.0, self.low=28181.0 
127.0.0.1 - - [29/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 08:20:03,831:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28184.4, self.close=28351.0, self.high=28370.0, self.low=28181.0   
2023-05-29 08:20:05,082:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230529   075500    075959  1685318399  ...  28050.0 -0.001292   1535    5
1536  20230529   080000    080459  1685318699  ...  28055.7  0.002598   1536    0
1537  20230529   080500    080959  1685318999  ...  28099.9  0.000551   1537    1
1538  20230529   081000    081459  1685319299  ...  28140.0  0.001435   1538    2
1539  20230529   081500    081959  1685319599  ...  28181.0  0.005908   1539    3

[5 rows x 11 columns]
2023-05-29 08:20:05,091:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [29/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=115, self.factor=0.15028113026427029, self.count=4291 

self.closeSec=1685319899, self.tradeDate='20230529', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28340.0, self.close=28382.3, self.high=28442.0, self.low=28304.0 
2023-05-29 08:25:00,781:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685319899, self.tradeDate='20230529', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28340.0, self.close=28382.3, self.high=28442.0, self.low=28304.0   
2023-05-29 08:25:00,861:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230529   080000    080459  1685318699  ...  28055.7  0.002598   1536    0
1537  20230529   080500    080959  1685318999  ...  28099.9  0.000551   1537    1
1538  20230529   081000    081459  1685319299  ...  28140.0  0.001435   1538    2
1539  20230529   081500    081959  1685319599  ...  28181.0  0.005908   1539    3
1540  20230529   082000    082459  1685319899  ...  28304.0  0.001104   1540    4

[5 rows x 11 columns]
2023-05-29 08:25:00,861:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-29 08:00:32,373:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230529    052959  27546.1  ...  48.750000  0.678357  0.223913
5771  20230529    055959  27621.0  ...  49.166667  0.713037  0.220538
5772  20230529    062959  27828.5  ...  49.166667  0.745132  0.212746
5773  20230529    065959  28066.0  ...  49.583333  0.746762  0.204806
5774  20230529    072959  28079.4  ...  49.583333  0.747218  0.200813

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-05-29 08:00:32,535:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.505093  0.494907       1  ...  0.944718   1.0    0.0  1.034817
537     0  0.541962  0.458038       1  ...  0.952780   1.0    0.0  1.043648
538     0  0.570526  0.429474       1  ...  0.953235   1.0    0.0  1.044147
539     0  0.530006  0.469994       1  ...  0.953361   1.0    0.0  1.044284
540     0  0.528629  0.471371       0  ...  0.952431   1.0    0.0  1.043265

[5 rows x 10 columns]
2023-05-29 08:00:32,565:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504871  0.495129       1  ...  0.944718   1.0    0.0  1.038842
46     0  0.542280  0.457720       1  ...  0.952780   1.0    0.0  1.048217
47     0  0.570614  0.429386       1  ...  0.953235   1.0    0.0  1.044162
48     0  0.530006  0.469994       1  ...  0.953361   1.0    0.0  1.044284
49     0  0.528629  0.471371       0  ...  0.952431   1.0    0.0  1.043265

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '33257.9776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28075.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230529   075000    075959  1685318399  28118.4  28055.7 -0.002226
2023-05-29 08:00:02,239:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2144 

self.closeSec=1685318999, self.tradeDate='20230529', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28055.8', self.close='28155.5'
2023-05-29 08:10:01,131:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685318999, self.tradeDate='20230529', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28055.8', self.close='28155.5'
127.0.0.1 - - [29/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-29 08:10:01,142:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230529   072000    072959  1685316599  28093.1    28083 -0.000363
621  20230529   073000    073959  1685317199    28083  28054.9 -0.001001
622  20230529   074000    074959  1685317799    28055  28118.3  0.002260
623  20230529   075000    075959  1685318399  28118.4  28055.7 -0.002226
624  20230529   080000    080959  1685318999  28055.8  28155.5  0.003557
2023-05-29 08:10:01,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2145 

self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28153.9', self.close='28340'
127.0.0.1 - - [29/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-29 08:20:06,102:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28153.9', self.close='28340'
2023-05-29 08:20:06,982:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230529   073000    073959  1685317199    28083  28054.9 -0.001001
622  20230529   074000    074959  1685317799    28055  28118.3  0.002260
623  20230529   075000    075959  1685318399  28118.4  28055.7 -0.002226
624  20230529   080000    080959  1685318999  28055.8  28155.5  0.003557
625  20230529   081000    081959  1685319599  28153.9    28340  0.006553
2023-05-29 08:20:06,992:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230529   075000    075959  1685318399  28118.4  28055.7
2023-05-29 08:00:02,233:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2147 

self.closeSec=1685318999, self.tradeDate='20230529', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28055.8', self.close='28155.5'
2023-05-29 08:10:01,124:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685318999, self.tradeDate='20230529', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28055.8', self.close='28155.5'
127.0.0.1 - - [29/May/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-05-29 08:10:01,161:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230529   072000    072959  1685316599  28093.1    28083
17469  20230529   073000    073959  1685317199    28083  28054.9
17470  20230529   074000    074959  1685317799    28055  28118.3
17471  20230529   075000    075959  1685318399  28118.4  28055.7
17472  20230529   080000    080959  1685318999  28055.8  28155.5
2023-05-29 08:10:01,162:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2148 

self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28153.9', self.close='28340'
127.0.0.1 - - [29/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-29 08:20:07,943:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28153.9', self.close='28340'
2023-05-29 08:20:08,059:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230529   073000    073959  1685317199    28083  28054.9
17470  20230529   074000    074959  1685317799    28055  28118.3
17471  20230529   075000    075959  1685318399  28118.4  28055.7
17472  20230529   080000    080959  1685318999  28055.8  28155.5
17473  20230529   081000    081959  1685319599  28153.9    28340
2023-05-29 08:20:08,060:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230529   075000    075959  1685318399  28118.4  28055.7
2023-05-29 08:00:02,222:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [29/May/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2147 

self.closeSec=1685318999, self.tradeDate='20230529', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='28055.8', self.close='28155.5'
2023-05-29 08:10:01,150:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685318999, self.tradeDate='20230529', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='28055.8', self.close='28155.5'
2023-05-29 08:10:01,171:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230529   072000    072959  1685316599  28093.1    28083
12141  20230529   073000    073959  1685317199    28083  28054.9
12142  20230529   074000    074959  1685317799    28055  28118.3
12143  20230529   075000    075959  1685318399  28118.4  28055.7
12144  20230529   080000    080959  1685318999  28055.8  28155.5
2023-05-29 08:10:01,171:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2148 

self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='28153.9', self.close='28340'
127.0.0.1 - - [29/May/2023 08:20:03] "POST / HTTP/1.1" 200 -
2023-05-29 08:20:07,675:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='28153.9', self.close='28340'
2023-05-29 08:20:07,892:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230529   073000    073959  1685317199    28083  28054.9
12142  20230529   074000    074959  1685317799    28055  28118.3
12143  20230529   075000    075959  1685318399  28118.4  28055.7
12144  20230529   080000    080959  1685318999  28055.8  28155.5
12145  20230529   081000    081959  1685319599  28153.9    28340
2023-05-29 08:20:07,892:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4288
self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=28184.4, self.close=28351.0, self.high=28370.0, self.low=28181.0, self.vol=13306.114, self.amt=376277928.78463 
127.0.0.1 - - [29/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-29 08:20:06,171:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230529   075500    075959  ...         0.0        0.0       0
5856  20230529   080000    080459  ...         0.0        0.0       0
5857  20230529   080500    080959  ...         0.0        0.0       0
5858  20230529   081000    081459  ...         0.0        0.0       0
5859  20230529   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 08:20:06,211:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685319599, self.tradeDate='20230529', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=28184.4, self.close=28351.0, self.high=28370.0, self.low=28181.0, self.vol=13306.114, self.amt=376277928.78463, ukdf['pct'].iloc[-1]=0.005908 , ukdf['amount'].iloc[-1]=376277928.78463, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '54940.00409055288', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28323.22791768', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4289
self.closeSec=1685319899, self.tradeDate='20230529', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=28340.0, self.close=28382.3, self.high=28442.0, self.low=28304.0, self.vol=10502.951, self.amt=298082439.2334 
127.0.0.1 - - [29/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-29 08:25:00,799:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230529   080000    080459  ...         0.0        0.0       0
5857  20230529   080500    080959  ...         0.0        0.0       0
5858  20230529   081000    081459  ...         0.0        0.0       0
5859  20230529   081500    081959  ...         0.0        0.0       0
5860  20230529   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-29 08:25:00,799:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685319899, self.tradeDate='20230529', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=28340.0, self.close=28382.3, self.high=28442.0, self.low=28304.0, self.vol=10502.951, self.amt=298082439.2334, ukdf['pct'].iloc[-1]=0.001104 , ukdf['amount'].iloc[-1]=298082439.2334, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '57394.13984328674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28389.30410714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230528   200000    235959  1685289599  ...    719  0.490371  0.530561     NaN
720  20230529   000000    035959  1685303999  ...    720  0.747217  1.936988     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '77442.5233', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27529.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [29/May/2023 08:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=89
self.closeSec=1685318399, self.tradeDate='20230529', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=27518.5, self.close=28055.7, self.high=28252.8, self.low=27515.1, self.vol=116480.961, self.amt=3257901993.47048 
2023-05-29 08:00:01,763:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685318399, self.tradeDate='20230529', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=27518.5, self.close=28055.7, self.high=28252.8, self.low=27515.1, self.vol=116480.961, self.amt=3257901993.47048 
2023-05-29 08:00:01,822:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230528   120000    155959  ...   40838.873  1.110311e+09  0.001638
718  20230528   160000    195959  ...   42170.252  1.147435e+09 -0.002678
719  20230528   200000    235959  ...   37541.126  1.020329e+09  0.004351
720  20230529   000000    035959  ...  113292.894  3.113995e+09  0.009327
721  20230529   040000    075959  ...  116480.961  3.257902e+09  0.019525

[5 rows x 11 columns]
2023-05-29 08:00:03,732:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230528   120000    155959  1685260799  ...    717  0.365024 -0.185390     NaN
718  20230528   160000    195959  1685275199  ...    718  0.452764  0.315743     NaN
719  20230528   200000    235959  1685289599  ...    719  0.490371  0.530561     NaN
720  20230529   000000    035959  1685303999  ...    720  0.747217  1.936988     1.0
721  20230529   040000    075959  1685318399  ...    721  0.981724  3.044001     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '106989.6885', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '28064.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


