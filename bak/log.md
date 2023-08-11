# 20230811 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25696
self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29430.0, self.close=29441.5, self.high=29441.6, self.low=29430.0, self.vol=286.002, self.amt=8419049.4901 
127.0.0.1 - - [11/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 16:20:06,133:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230811   155500    155959  ...         0.0        0.0       0
5952  20230811   160000    160459  ...         0.0        0.0       0
5953  20230811   160500    160959  ...         0.0        0.0       0
5954  20230811   161000    161459  ...         0.0        0.0       0
5955  20230811   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 16:20:06,153:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29430.0, self.close=29441.5, self.high=29441.6, self.low=29430.0, self.vol=286.002, self.amt=8419049.4901, ukdf['pct'].iloc[-1]=0.000387 , ukdf['amount'].iloc[-1]=8419049.4901, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35890.2044743275', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29442.10842125', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25697
self.closeSec=1691742299, self.tradeDate='20230811', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29441.5, self.close=29428.9, self.high=29441.6, self.low=29427.6, self.vol=386.649, self.amt=11380631.9067 
127.0.0.1 - - [11/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-11 16:25:00,791:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230811   160000    160459  ...         0.0        0.0       0
5953  20230811   160500    160959  ...         0.0        0.0       0
5954  20230811   161000    161459  ...         0.0        0.0       0
5955  20230811   161500    161959  ...         0.0        0.0       0
5956  20230811   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 16:25:00,791:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691742299, self.tradeDate='20230811', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29441.5, self.close=29428.9, self.high=29441.6, self.low=29427.6, self.vol=386.649, self.amt=11380631.9067, ukdf['pct'].iloc[-1]=-0.000428 , ukdf['amount'].iloc[-1]=11380631.9067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35706.264', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29428.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29430.0, self.close=29441.5, self.high=29441.6, self.low=29430.0 
127.0.0.1 - - [11/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-11 16:20:03,758:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29430.0, self.close=29441.5, self.high=29441.6, self.low=29430.0   
2023-08-11 16:20:05,054:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230811   155500    155959  1691740799  ...  29406.7 -0.000354   1631    5
1632  20230811   160000    160459  1691741099  ...  29400.0  0.000422   1632    0
1633  20230811   160500    160959  1691741399  ...  29419.0  0.000282   1633    1
1634  20230811   161000    161459  1691741699  ...  29425.0  0.000092   1634    2
1635  20230811   161500    161959  1691741999  ...  29430.0  0.000387   1635    3

[5 rows x 11 columns]
2023-08-11 16:20:05,063:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [11/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7021530947632265, self.count=25699 

self.closeSec=1691742299, self.tradeDate='20230811', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29441.5, self.close=29428.9, self.high=29441.6, self.low=29427.6 
2023-08-11 16:25:00,751:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691742299, self.tradeDate='20230811', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29441.5, self.close=29428.9, self.high=29441.6, self.low=29427.6   
2023-08-11 16:25:00,763:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230811   160000    160459  1691741099  ...  29400.0  0.000422   1632    0
1633  20230811   160500    160959  1691741399  ...  29419.0  0.000282   1633    1
1634  20230811   161000    161459  1691741699  ...  29425.0  0.000092   1634    2
1635  20230811   161500    161959  1691741999  ...  29430.0  0.000387   1635    3
1636  20230811   162000    162459  1691742299  ...  29427.6 -0.000428   1636    4

[5 rows x 11 columns]
2023-08-11 16:25:00,764:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-11 16:00:17,360:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230811    132959  29405.2  ...  47.916667  0.466453  0.707743
5787  20230811    135959  29398.4  ...  47.916667  0.484273  0.704369
5788  20230811    142959  29449.8  ...  47.916667  0.477729  0.704457
5789  20230811    145959  29429.2  ...  47.916667  0.485272  0.701098
5790  20230811    152959  29451.1  ...  47.500000  0.479490  0.700780

[5 rows x 33 columns]
0.5166051660516605
acc is : 0.5166051660516605
2023-08-11 16:00:17,420:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.503858  0.496142       1  ...  0.962319  -1.0    0.0  1.000003
538     0  0.519854  0.480146       0  ...  0.962995  -1.0    0.0  0.999301
539     1  0.498831  0.501169       1  ...  0.962275  -1.0    0.0  1.000048
540     0  0.509870  0.490130       0  ...  0.962863  -1.0    0.0  0.999436
541     1  0.499041  0.500959       0  ...  0.963727  -1.0    0.0  0.998540

[5 rows x 10 columns]
2023-08-11 16:00:17,431:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504251  0.495749       1  ...  0.962319  -1.0    0.0  1.010430
46     0  0.520480  0.479520       0  ...  0.962995  -1.0    0.0  1.006106
47     1  0.499161  0.500839       1  ...  0.962275  -1.0    0.0  1.006149
48     0  0.510059  0.489941       0  ...  0.962863  -1.0    0.0  1.004941
49     1  0.499041  0.500959       0  ...  0.963727  -1.0    0.0  0.998540

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '1731.528', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29407.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230811   155000    155959  1691740799    29420  29406.7 -0.000452
2023-08-11 16:00:02,044:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12848 

self.closeSec=1691741399, self.tradeDate='20230811', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29406.8', self.close='29426.6'
2023-08-11 16:10:01,168:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691741399, self.tradeDate='20230811', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29406.8', self.close='29426.6'
127.0.0.1 - - [11/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-11 16:10:01,176:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230811   152000    152959  1691738999    29432  29433.1  0.000041
525  20230811   153000    153959  1691739599  29433.1    29422 -0.000377
526  20230811   154000    154959  1691740199    29422    29420 -0.000068
527  20230811   155000    155959  1691740799    29420  29406.7 -0.000452
528  20230811   160000    160959  1691741399  29406.8  29426.6  0.000677
2023-08-11 16:10:01,184:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12849 

self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29426.6', self.close='29441.5'
127.0.0.1 - - [11/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 16:20:06,752:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29426.6', self.close='29441.5'
2023-08-11 16:20:07,223:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230811   153000    153959  1691739599  29433.1    29422 -0.000377
526  20230811   154000    154959  1691740199    29422    29420 -0.000068
527  20230811   155000    155959  1691740799    29420  29406.7 -0.000452
528  20230811   160000    160959  1691741399  29406.8  29426.6  0.000677
529  20230811   161000    161959  1691741999  29426.6  29441.5  0.000506
2023-08-11 16:20:07,223:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230811   155000    155959  1691740799    29420  29406.7
2023-08-11 16:00:02,035:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12851 

self.closeSec=1691741399, self.tradeDate='20230811', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29406.8', self.close='29426.6'
2023-08-11 16:10:01,170:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691741399, self.tradeDate='20230811', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29406.8', self.close='29426.6'
127.0.0.1 - - [11/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-11 16:10:01,176:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230811   152000    152959  1691738999    29432  29433.1
17517  20230811   153000    153959  1691739599  29433.1    29422
17518  20230811   154000    154959  1691740199    29422    29420
17519  20230811   155000    155959  1691740799    29420  29406.7
17520  20230811   160000    160959  1691741399  29406.8  29426.6
2023-08-11 16:10:01,177:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12852 

self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29426.6', self.close='29441.5'
127.0.0.1 - - [11/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 16:20:08,088:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29426.6', self.close='29441.5'
2023-08-11 16:20:08,237:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230811   153000    153959  1691739599  29433.1    29422
17518  20230811   154000    154959  1691740199    29422    29420
17519  20230811   155000    155959  1691740799    29420  29406.7
17520  20230811   160000    160959  1691741399  29406.8  29426.6
17521  20230811   161000    161959  1691741999  29426.6  29441.5
2023-08-11 16:20:08,237:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230811   155000    155959  1691740799    29420  29406.7
2023-08-11 16:00:02,045:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12851 

self.closeSec=1691741399, self.tradeDate='20230811', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29406.8', self.close='29426.6'
127.0.0.1 - - [11/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-11 16:10:01,183:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691741399, self.tradeDate='20230811', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29406.8', self.close='29426.6'
2023-08-11 16:10:01,189:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230811   152000    152959  1691738999    29432  29433.1
12189  20230811   153000    153959  1691739599  29433.1    29422
12190  20230811   154000    154959  1691740199    29422    29420
12191  20230811   155000    155959  1691740799    29420  29406.7
12192  20230811   160000    160959  1691741399  29406.8  29426.6
2023-08-11 16:10:01,190:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12852 

self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29426.6', self.close='29441.5'
127.0.0.1 - - [11/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-11 16:20:07,885:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29426.6', self.close='29441.5'
2023-08-11 16:20:08,072:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230811   153000    153959  1691739599  29433.1    29422
12190  20230811   154000    154959  1691740199    29422    29420
12191  20230811   155000    155959  1691740799    29420  29406.7
12192  20230811   160000    160959  1691741399  29406.8  29426.6
12193  20230811   161000    161959  1691741999  29426.6  29441.5
2023-08-11 16:20:08,074:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25696
self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29430.0, self.close=29441.5, self.high=29441.6, self.low=29430.0, self.vol=286.002, self.amt=8419049.4901 127.0.0.1 - - [11/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -

2023-08-11 16:20:06,152:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230811   155500    155959  ...         0.0        0.0       0
5952  20230811   160000    160459  ...         0.0        0.0       0
5953  20230811   160500    160959  ...         0.0        0.0       0
5954  20230811   161000    161459  ...         0.0        0.0       0
5955  20230811   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 16:20:06,164:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691741999, self.tradeDate='20230811', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29430.0, self.close=29441.5, self.high=29441.6, self.low=29430.0, self.vol=286.002, self.amt=8419049.4901, ukdf['pct'].iloc[-1]=0.000387 , ukdf['amount'].iloc[-1]=8419049.4901, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96496.34487364625', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29442.10842125', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25697
self.closeSec=1691742299, self.tradeDate='20230811', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29441.5, self.close=29428.9, self.high=29441.6, self.low=29427.6, self.vol=386.649, self.amt=11380631.9067 
127.0.0.1 - - [11/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-11 16:25:00,782:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230811   160000    160459  ...         0.0        0.0       0
5953  20230811   160500    160959  ...         0.0        0.0       0
5954  20230811   161000    161459  ...         0.0        0.0       0
5955  20230811   161500    161959  ...         0.0        0.0       0
5956  20230811   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-11 16:25:00,782:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691742299, self.tradeDate='20230811', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29441.5, self.close=29428.9, self.high=29441.6, self.low=29427.6, self.vol=386.649, self.amt=11380631.9067, ukdf['pct'].iloc[-1]=-0.000428 , ukdf['amount'].iloc[-1]=11380631.9067, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96005.7709', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29428.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230811   040000    075959  1691711999  ...    721  0.823996  1.202551     1.0
722  20230811   080000    115959  1691726399  ...    722  0.791911  1.100409     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24900.79538039898', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29400.48536486', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [11/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=535
self.closeSec=1691740799, self.tradeDate='20230811', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29400.7, self.close=29406.7, self.high=29481.9, self.low=29367.3, self.vol=18382.821, self.amt=540901224.801 
2023-08-11 16:00:01,623:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691740799, self.tradeDate='20230811', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29400.7, self.close=29406.7, self.high=29481.9, self.low=29367.3, self.vol=18382.821, self.amt=540901224.801 
2023-08-11 16:00:01,646:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230810   200000    235959  ...  101443.007  2.997258e+09 -0.001261
720  20230811   000000    035959  ...   46278.886  1.361132e+09 -0.000587
721  20230811   040000    075959  ...   13216.051  3.892165e+08  0.000279
722  20230811   080000    115959  ...   19307.071  5.679160e+08 -0.001460
723  20230811   120000    155959  ...   18382.821  5.409012e+08  0.000204

[5 rows x 11 columns]
2023-08-11 16:00:02,328:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230810   200000    235959  1691683199  ...    719  0.947260  1.593051     1.0
720  20230811   000000    035959  1691697599  ...    720  0.899898  1.433502     1.0
721  20230811   040000    075959  1691711999  ...    721  0.823996  1.202551     1.0
722  20230811   080000    115959  1691726399  ...    722  0.791911  1.100409     1.0
723  20230811   120000    155959  1691740799  ...    723  0.760064  1.001768     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24558.84836817531', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29407.13066117', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


