# 20230803 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23392
self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29059.0, self.close=29028.6, self.high=29059.0, self.low=29025.9, self.vol=910.826, self.amt=26449655.9011 
127.0.0.1 - - [03/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 16:20:06,288:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230803   155500    155959  ...         0.0        0.0       0
5952  20230803   160000    160459  ...         0.0        0.0       0
5953  20230803   160500    160959  ...         0.0        0.0       0
5954  20230803   161000    161459  ...         0.0        0.0       0
5955  20230803   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 16:20:06,308:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29059.0, self.close=29028.6, self.high=29059.0, self.low=29025.9, self.vol=910.826, self.amt=26449655.9011, ukdf['pct'].iloc[-1]=-0.001043 , ukdf['amount'].iloc[-1]=26449655.9011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30154.01521468776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29030.20340476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23393
self.closeSec=1691051099, self.tradeDate='20230803', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29028.5, self.close=29030.5, self.high=29034.3, self.low=28960.2, self.vol=3042.784, self.amt=88257140.9817 
127.0.0.1 - - [03/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-03 16:25:00,765:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230803   160000    160459  ...         0.0        0.0       0
5953  20230803   160500    160959  ...         0.0        0.0       0
5954  20230803   161000    161459  ...         0.0        0.0       0
5955  20230803   161500    161959  ...         0.0        0.0       0
5956  20230803   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 16:25:00,766:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691051099, self.tradeDate='20230803', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29028.5, self.close=29030.5, self.high=29034.3, self.low=28960.2, self.vol=3042.784, self.amt=88257140.9817, ukdf['pct'].iloc[-1]=6.5e-05 , ukdf['amount'].iloc[-1]=88257140.9817, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-30165.1086', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29031', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29059.0, self.close=29028.6, self.high=29059.0, self.low=29025.9 
127.0.0.1 - - [03/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 16:20:04,379:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29059.0, self.close=29028.6, self.high=29059.0, self.low=29025.9   
2023-08-03 16:20:05,639:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230803   155500    155959  1691049599  ...  29032.1 -0.000055   1631    5
1632  20230803   160000    160459  1691049899  ...  29014.1  0.000734   1632    0
1633  20230803   160500    160959  1691050199  ...  29053.8  0.000268   1633    1
1634  20230803   161000    161459  1691050499  ...  29056.8 -0.000141   1634    2
1635  20230803   161500    161959  1691050799  ...  29025.9 -0.001043   1635    3

[5 rows x 11 columns]
2023-08-03 16:20:05,648:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6045226251510524, self.count=23395 

self.closeSec=1691051099, self.tradeDate='20230803', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29028.5, self.close=29030.5, self.high=29034.3, self.low=28960.2 
127.0.0.1 - - [03/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-03 16:25:00,744:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691051099, self.tradeDate='20230803', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29028.5, self.close=29030.5, self.high=29034.3, self.low=28960.2   
2023-08-03 16:25:00,770:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230803   160000    160459  1691049899  ...  29014.1  0.000734   1632    0
1633  20230803   160500    160959  1691050199  ...  29053.8  0.000268   1633    1
1634  20230803   161000    161459  1691050499  ...  29056.8 -0.000141   1634    2
1635  20230803   161500    161959  1691050799  ...  29025.9 -0.001043   1635    3
1636  20230803   162000    162459  1691051099  ...  28960.2  0.000065   1636    4

[5 rows x 11 columns]
2023-08-03 16:25:00,770:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-03 16:00:20,799:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230803    132959  29126.2  ...  45.416667  0.464323  0.667352
5787  20230803    135959  29097.7  ...  45.416667  0.474352  0.667027
5788  20230803    142959  29140.0  ...  45.416667  0.469289  0.669034
5789  20230803    145959  29116.0  ...  45.416667  0.461088  0.674679
5790  20230803    152959  29076.7  ...  45.416667  0.451074  0.684645

[5 rows x 33 columns]
0.559040590405904
acc is : 0.559040590405904
2023-08-03 16:00:20,886:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.485177  0.514823       1  ...  0.979198   1.0    0.0  0.978844
538     1  0.497458  0.502542       0  ...  0.978391   1.0    0.0  0.978038
539     1  0.475889  0.524111       0  ...  0.977074   1.0    0.0  0.976721
540     1  0.471912  0.528088       0  ...  0.975434   1.0    0.0  0.975082
541     1  0.459683  0.540317       1  ...  0.975632   1.0    0.0  0.975280

[5 rows x 10 columns]
2023-08-03 16:00:20,901:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.485169  0.514831       1  ...  0.979198   1.0    0.0  0.978089
46     1  0.497377  0.502623       0  ...  0.938849   1.0    0.0  0.980905
47     1  0.475579  0.524421       0  ...  0.977074   1.0    0.0  0.976226
48     1  0.471866  0.528134       0  ...  0.975434   1.0    0.0  0.974581
49     1  0.459683  0.540317       1  ...  0.975632   1.0    0.0  0.975280

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '-2299.2173822226', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29035.93818029', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230803   155000    155959  1691049599  29044.6    29034 -0.000362
2023-08-03 16:00:02,117:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [03/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11696 

self.closeSec=1691050199, self.tradeDate='20230803', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29034', self.close='29063'
2023-08-03 16:10:01,169:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691050199, self.tradeDate='20230803', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29034', self.close='29063'
2023-08-03 16:10:01,177:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230803   152000    152959  1691047799    29073  29029.1 -0.001510
525  20230803   153000    153959  1691048399  29029.1  29022.7 -0.000220
526  20230803   154000    154959  1691048999  29022.7  29044.5  0.000751
527  20230803   155000    155959  1691049599  29044.6    29034 -0.000362
528  20230803   160000    160959  1691050199    29034    29063  0.000999
2023-08-03 16:10:01,177:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11697 

self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29063.1', self.close='29028.6'
127.0.0.1 - - [03/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 16:20:06,818:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29063.1', self.close='29028.6'
2023-08-03 16:20:07,311:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230803   153000    153959  1691048399  29029.1  29022.7 -0.000220
526  20230803   154000    154959  1691048999  29022.7  29044.5  0.000751
527  20230803   155000    155959  1691049599  29044.6    29034 -0.000362
528  20230803   160000    160959  1691050199    29034    29063  0.000999
529  20230803   161000    161959  1691050799  29063.1  29028.6 -0.001184
2023-08-03 16:20:07,312:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230803   155000    155959  1691049599  29044.6    29034
2023-08-03 16:00:02,139:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [03/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11699 

self.closeSec=1691050199, self.tradeDate='20230803', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29034', self.close='29063'
2023-08-03 16:10:01,183:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691050199, self.tradeDate='20230803', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29034', self.close='29063'
2023-08-03 16:10:01,189:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230803   152000    152959  1691047799    29073  29029.1
17517  20230803   153000    153959  1691048399  29029.1  29022.7
17518  20230803   154000    154959  1691048999  29022.7  29044.5
17519  20230803   155000    155959  1691049599  29044.6    29034
17520  20230803   160000    160959  1691050199    29034    29063
2023-08-03 16:10:01,190:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11700 

self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29063.1', self.close='29028.6'
127.0.0.1 - - [03/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 16:20:08,153:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29063.1', self.close='29028.6'
2023-08-03 16:20:08,264:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230803   153000    153959  1691048399  29029.1  29022.7
17518  20230803   154000    154959  1691048999  29022.7  29044.5
17519  20230803   155000    155959  1691049599  29044.6    29034
17520  20230803   160000    160959  1691050199    29034    29063
17521  20230803   161000    161959  1691050799  29063.1  29028.6
2023-08-03 16:20:08,264:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230803   155000    155959  1691049599  29044.6    29034
2023-08-03 16:00:02,169:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11699 

self.closeSec=1691050199, self.tradeDate='20230803', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29034', self.close='29063'
2023-08-03 16:10:01,170:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691050199, self.tradeDate='20230803', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29034', self.close='29063'
127.0.0.1 - - [03/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-03 16:10:01,176:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230803   152000    152959  1691047799    29073  29029.1
12189  20230803   153000    153959  1691048399  29029.1  29022.7
12190  20230803   154000    154959  1691048999  29022.7  29044.5
12191  20230803   155000    155959  1691049599  29044.6    29034
12192  20230803   160000    160959  1691050199    29034    29063
2023-08-03 16:10:01,176:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11700 

self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29063.1', self.close='29028.6'
127.0.0.1 - - [03/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-03 16:20:07,981:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29063.1', self.close='29028.6'
2023-08-03 16:20:08,158:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230803   153000    153959  1691048399  29029.1  29022.7
12190  20230803   154000    154959  1691048999  29022.7  29044.5
12191  20230803   155000    155959  1691049599  29044.6    29034
12192  20230803   160000    160959  1691050199    29034    29063
12193  20230803   161000    161959  1691050799  29063.1  29028.6
2023-08-03 16:20:08,159:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23392
self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29059.0, self.close=29028.6, self.high=29059.0, self.low=29025.9, self.vol=910.826, self.amt=26449655.9011 
127.0.0.1 - - [03/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-03 16:20:06,211:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230803   155500    155959  ...         0.0        0.0       0
5952  20230803   160000    160459  ...         0.0        0.0       0
5953  20230803   160500    160959  ...         0.0        0.0       0
5954  20230803   161000    161459  ...         0.0        0.0       0
5955  20230803   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 16:20:06,228:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691050799, self.tradeDate='20230803', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29059.0, self.close=29028.6, self.high=29059.0, self.low=29025.9, self.vol=910.826, self.amt=26449655.9011, ukdf['pct'].iloc[-1]=-0.001043 , ukdf['amount'].iloc[-1]=26449655.9011, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '81197.78065619116', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29030.20340476', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23393
self.closeSec=1691051099, self.tradeDate='20230803', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29028.5, self.close=29030.5, self.high=29034.3, self.low=28960.2, self.vol=3042.784, self.amt=88257140.9817 
127.0.0.1 - - [03/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-03 16:25:00,779:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230803   160000    160459  ...         0.0        0.0       0
5953  20230803   160500    160959  ...         0.0        0.0       0
5954  20230803   161000    161459  ...         0.0        0.0       0
5955  20230803   161500    161959  ...         0.0        0.0       0
5956  20230803   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-03 16:25:00,780:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691051099, self.tradeDate='20230803', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29028.5, self.close=29030.5, self.high=29034.3, self.low=28960.2, self.vol=3042.784, self.amt=88257140.9817, ukdf['pct'].iloc[-1]=6.5e-05 , ukdf['amount'].iloc[-1]=88257140.9817, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '81227.367', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29031', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

720  20230803   000000    035959  ...  115887.845  3.373807e+09 -0.005823
721  20230803   040000    075959  ...   23823.330  6.945151e+08  0.000971
722  20230803   080000    115959  ...   24131.103  7.042569e+08  0.000000
723  20230803   120000    155959  ...   28883.917  8.400553e+08 -0.004666

[5 rows x 11 columns]
2023-08-03 16:00:02,762:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230802   200000    235959  1690991999  ...    719  0.292143  0.241824     NaN
720  20230803   000000    035959  1691006399  ...    720  0.280406  0.168011     NaN
721  20230803   040000    075959  1691020799  ...    721  0.304316  0.283613     NaN
722  20230803   080000    115959  1691035199  ...    722  0.332634  0.420824     NaN
723  20230803   120000    155959  1691049599  ...    723  0.370799  0.605461     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '11469.16973790384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29035.70232234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=-1
handlebackTrade > queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '11469.16973790384', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29035.70232234', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
2023-08-03 16:00:09,648:INFO:s_rsrs:main.py:182:queryContractAssets:2218689: queryContractAssets: assets=ContractAssetReturn{'result': [ContractAsset{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'asset': 'USDT', 'free': '1595131.6116365', 'total': '1595131.6116365', 'margin': '0', 'unreal': '0', 'type': 'AssetType_ucontract'}]}
2023-08-03 16:00:10,187:DEBUG:s_rsrs:main.py:253:openBuy:2218689: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': False}
2023-08-03 16:00:10,188:INFO:s_rsrs:main.py:254:openBuy:2218689: ret = self.client.insertMarketUOrder("simulator", "BTCUSDT", 54.775, "buy"), ret=InsertOrderReturn{'result': 'success', 'clientorderid': '42798F1691049610186I0L65'}
2023-08-03 16:00:10,209:INFO:s_rsrs:main.py:176:insertFactor:2218689: curDateTime:8031600, name:s_rsrs, symbol:BTCUSDT, tradeDate:20230803, closeTime:155959, close:29034.0, sign:1, total:1595131.6116365, side:buy  
127.0.0.1 - - [03/Aug/2023 16:00:10] "POST / HTTP/1.1" 200 -
127.0.0.1 - - [03/Aug/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-08-03 16:00:10,213:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42797F1691049604544I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691049604941973, 'quantity': '54.024', 'price': '29034.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691049603610, 'updatetime': 1691049604941, 'tradetype': 'usdt', 'selfid': 42797, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691049604941, 'clientorderid': '42797F1691049604544I0L65', 'price': '29034.3', 'quantity': '54.024', 'commission': '1568.5490232', 'commissionasset': 'USDT', 'tradetime': 1691049604941, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691049604941}], 'gatetype': 'simulator', 'handletime': 0}
2023-08-03 16:00:10,214:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42797F1691049604544I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691049604941973, 'quantity': '54.024', 'price': '29034.3', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691049603610, 'updatetime': 1691049604941, 'tradetype': 'usdt', 'selfid': 42797, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691049604941, 'clientorderid': '42797F1691049604544I0L65', 'price': '29034.3', 'quantity': '54.024', 'commission': '1568.5490232', 'commissionasset': 'USDT', 'tradetime': 1691049604941, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691049604941}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Aug/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-08-03 16:00:10,643:INFO:s_rsrs:main.py:343:handleOrderNew:2218689: handleOrderNew: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42798F1691049610186I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691049610591710, 'quantity': '54.775', 'price': '29034.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691049609665, 'updatetime': 1691049610591, 'tradetype': 'usdt', 'selfid': 42798, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691049610591, 'clientorderid': '42798F1691049610186I0L65', 'price': '29034.8', 'quantity': '54.775', 'commission': '1590.38117', 'commissionasset': 'USDT', 'tradetime': 1691049610591, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691049610591}], 'gatetype': 'simulator', 'handletime': 0}
127.0.0.1 - - [03/Aug/2023 16:00:10] "POST / HTTP/1.1" 200 -
2023-08-03 16:00:10,825:INFO:s_rsrs:main.py:346:handleOrderFilled:2218689: handleOrderFilled: data=OrderType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'clientorderid': '42798F1691049610186I0L65', 'symbol': 'BTCUSDT', 'gatewayorderid': 1691049610591710, 'quantity': '54.775', 'price': '29034.8', 'stopprice': '0', 'ordertype': '', 'side': 'BUY', 'status': 'FILLED', 'positionside': 'LONG', 'createtime': 1691049609665, 'updatetime': 1691049610591, 'tradetype': 'usdt', 'selfid': 42798, 'filltrades': [TradeType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'tradeid': 1691049610591, 'clientorderid': '42798F1691049610186I0L65', 'price': '29034.8', 'quantity': '54.775', 'commission': '1590.38117', 'commissionasset': 'USDT', 'tradetime': 1691049610591, 'tradetype': 'usdt', 'gatetype': 'simulator', 'handletime': 1691049610591}], 'gatetype': 'simulator', 'handletime': 0}


