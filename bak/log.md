# 20230816 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27136
self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29177.6, self.close=29162.6, self.high=29177.7, self.low=29162.6, self.vol=330.685, self.amt=9645872.3068 
127.0.0.1 - - [16/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 16:20:06,706:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230816   155500    155959  ...         0.0        0.0       0
5952  20230816   160000    160459  ...         0.0        0.0       0
5953  20230816   160500    160959  ...         0.0        0.0       0
5954  20230816   161000    161459  ...         0.0        0.0       0
5955  20230816   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 16:20:06,727:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29177.6, self.close=29162.6, self.high=29177.7, self.low=29162.6, self.vol=330.685, self.amt=9645872.3068, ukdf['pct'].iloc[-1]=-0.000514 , ukdf['amount'].iloc[-1]=9645872.3068, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-32029.95402768744', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29164.91106044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [16/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=27137
self.closeSec=1692174299, self.tradeDate='20230816', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29163.7, self.close=29155.5, self.high=29164.5, self.low=29152.5, self.vol=598.343, self.amt=17446274.763 
2023-08-16 16:25:00,777:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230816   160000    160459  ...         0.0        0.0       0
5953  20230816   160500    160959  ...         0.0        0.0       0
5954  20230816   161000    161459  ...         0.0        0.0       0
5955  20230816   161500    161959  ...         0.0        0.0       0
5956  20230816   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 16:25:00,777:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1692174299, self.tradeDate='20230816', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29163.7, self.close=29155.5, self.high=29164.5, self.low=29152.5, self.vol=598.343, self.amt=17446274.763, ukdf['pct'].iloc[-1]=-0.000243 , ukdf['amount'].iloc[-1]=17446274.763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31891.9326', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29155', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29177.6, self.close=29162.6, self.high=29177.7, self.low=29162.6 
127.0.0.1 - - [16/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 16:20:04,386:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29177.6, self.close=29162.6, self.high=29177.7, self.low=29162.6   
2023-08-16 16:20:05,586:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230816   155500    155959  1692172799  ...  29187.0 -0.000390   1631    5
1632  20230816   160000    160459  1692173099  ...  29187.0  0.000113   1632    0
1633  20230816   160500    160959  1692173399  ...  29186.9 -0.000113   1633    1
1634  20230816   161000    161459  1692173699  ...  29177.6 -0.000322   1634    2
1635  20230816   161500    161959  1692173999  ...  29162.6 -0.000514   1635    3

[5 rows x 11 columns]
2023-08-16 16:20:05,597:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.7058579647800506, self.count=27139 

self.closeSec=1692174299, self.tradeDate='20230816', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29163.7, self.close=29155.5, self.high=29164.5, self.low=29152.5 
127.0.0.1 - - [16/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-16 16:25:00,741:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1692174299, self.tradeDate='20230816', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29163.7, self.close=29155.5, self.high=29164.5, self.low=29152.5   
2023-08-16 16:25:00,752:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230816   160000    160459  1692173099  ...  29187.0  0.000113   1632    0
1633  20230816   160500    160959  1692173399  ...  29186.9 -0.000113   1633    1
1634  20230816   161000    161459  1692173699  ...  29177.6 -0.000322   1634    2
1635  20230816   161500    161959  1692173999  ...  29162.6 -0.000514   1635    3
1636  20230816   162000    162459  1692174299  ...  29152.5 -0.000243   1636    4

[5 rows x 11 columns]
2023-08-16 16:25:00,753:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-16 16:00:19,769:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230816    132959  29197.1  ...  47.500000  0.439842  0.643866
5787  20230816    135959  29183.0  ...  47.083333  0.420896  0.655545
5788  20230816    142959  29130.0  ...  47.500000  0.431504  0.663052
5789  20230816    145959  29152.5  ...  47.500000  0.444562  0.665791
5790  20230816    152959  29180.8  ...  47.500000  0.443021  0.668981

[5 rows x 33 columns]
0.551660516605166
acc is : 0.551660516605166
2023-08-16 16:00:19,866:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493477  0.506523       0  ...  1.021916  -1.0    0.0  1.000862
538     1  0.481984  0.518016       1  ...  1.021127  -1.0    0.0  1.001635
539     0  0.501258  0.498742       1  ...  1.020136  -1.0    0.0  1.002608
540     0  0.504439  0.495561       0  ...  1.020282  -1.0    0.0  1.002464
541     1  0.497689  0.502311       1  ...  1.019919  -1.0    0.0  1.002821

[5 rows x 10 columns]
2023-08-16 16:00:19,886:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493434  0.506566       0  ...  1.021916  -1.0    0.0  1.003006
46     1  0.481760  0.518240       1  ...  1.021127  -1.0    0.0  1.003490
47     0  0.500982  0.499018       1  ...  1.020136  -1.0    0.0  1.002739
48     0  0.504307  0.495693       0  ...  1.020282  -1.0    0.0  1.002295
49     1  0.497689  0.502311       1  ...  1.019919  -1.0    0.0  1.002821

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.521', 'enterprice': '29410.3', 'countrevence': '0', 'unrealprofit': '5226.95866200144', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29188.07481136', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230816   155000    155959  1692172799    29204    29187 -0.000579
2023-08-16 16:00:01,960:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [16/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13568 

self.closeSec=1692173399, self.tradeDate='20230816', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29187', self.close='29187'
2023-08-16 16:10:01,157:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692173399, self.tradeDate='20230816', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29187', self.close='29187'
2023-08-16 16:10:01,164:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230816   152000    152959  1692170999  29195.5  29176.6 -0.000647
525  20230816   153000    153959  1692171599  29176.7  29175.4 -0.000041
526  20230816   154000    154959  1692172199  29175.3  29203.9  0.000977
527  20230816   155000    155959  1692172799    29204    29187 -0.000579
528  20230816   160000    160959  1692173399    29187    29187  0.000000
2023-08-16 16:10:01,164:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13569 

self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29186.9', self.close='29163.7'
127.0.0.1 - - [16/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 16:20:06,866:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29186.9', self.close='29163.7'
2023-08-16 16:20:07,496:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230816   153000    153959  1692171599  29176.7  29175.4 -0.000041
526  20230816   154000    154959  1692172199  29175.3  29203.9  0.000977
527  20230816   155000    155959  1692172799    29204    29187 -0.000579
528  20230816   160000    160959  1692173399    29187    29187  0.000000
529  20230816   161000    161959  1692173999  29186.9  29163.7 -0.000798
2023-08-16 16:20:07,496:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230816   155000    155959  1692172799    29204    29187
2023-08-16 16:00:01,970:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13571 

self.closeSec=1692173399, self.tradeDate='20230816', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29187', self.close='29187'
2023-08-16 16:10:01,178:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692173399, self.tradeDate='20230816', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29187', self.close='29187'
127.0.0.1 - - [16/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-16 16:10:01,185:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230816   152000    152959  1692170999  29195.5  29176.6
17517  20230816   153000    153959  1692171599  29176.7  29175.4
17518  20230816   154000    154959  1692172199  29175.3  29203.9
17519  20230816   155000    155959  1692172799    29204    29187
17520  20230816   160000    160959  1692173399    29187    29187
2023-08-16 16:10:01,185:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13572 

self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29186.9', self.close='29163.7'
127.0.0.1 - - [16/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 16:20:08,590:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29186.9', self.close='29163.7'
2023-08-16 16:20:08,651:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230816   153000    153959  1692171599  29176.7  29175.4
17518  20230816   154000    154959  1692172199  29175.3  29203.9
17519  20230816   155000    155959  1692172799    29204    29187
17520  20230816   160000    160959  1692173399    29187    29187
17521  20230816   161000    161959  1692173999  29186.9  29163.7
2023-08-16 16:20:08,651:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230816   155000    155959  1692172799    29204    29187
2023-08-16 16:00:01,937:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13571 

self.closeSec=1692173399, self.tradeDate='20230816', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29187', self.close='29187'
2023-08-16 16:10:01,178:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692173399, self.tradeDate='20230816', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29187', self.close='29187'
127.0.0.1 - - [16/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-16 16:10:01,185:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230816   152000    152959  1692170999  29195.5  29176.6
12189  20230816   153000    153959  1692171599  29176.7  29175.4
12190  20230816   154000    154959  1692172199  29175.3  29203.9
12191  20230816   155000    155959  1692172799    29204    29187
12192  20230816   160000    160959  1692173399    29187    29187
2023-08-16 16:10:01,185:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=13572 

self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29186.9', self.close='29163.7'
127.0.0.1 - - [16/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-16 16:20:08,378:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29186.9', self.close='29163.7'
2023-08-16 16:20:08,559:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230816   153000    153959  1692171599  29176.7  29175.4
12190  20230816   154000    154959  1692172199  29175.3  29203.9
12191  20230816   155000    155959  1692172799    29204    29187
12192  20230816   160000    160959  1692173399    29187    29187
12193  20230816   161000    161959  1692173999  29186.9  29163.7
2023-08-16 16:20:08,565:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27136
self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29177.6, self.close=29162.6, self.high=29177.7, self.low=29162.6, self.vol=330.685, self.amt=9645872.3068 
127.0.0.1 - - [16/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-16 16:20:06,586:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230816   155500    155959  ...         0.0        0.0       0
5952  20230816   160000    160459  ...         0.0        0.0       0
5953  20230816   160500    160959  ...         0.0        0.0       0
5954  20230816   161000    161459  ...         0.0        0.0       0
5955  20230816   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 16:20:06,607:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692173999, self.tradeDate='20230816', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29177.6, self.close=29162.6, self.high=29177.7, self.low=29162.6, self.vol=330.685, self.amt=9645872.3068, ukdf['pct'].iloc[-1]=-0.000514 , ukdf['amount'].iloc[-1]=9645872.3068, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '86200.95769580204', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29164.91106044', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=27137
self.closeSec=1692174299, self.tradeDate='20230816', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29163.7, self.close=29155.5, self.high=29164.5, self.low=29152.5, self.vol=598.343, self.amt=17446274.763 
127.0.0.1 - - [16/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-16 16:25:00,763:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230816   160000    160459  ...         0.0        0.0       0
5953  20230816   160500    160959  ...         0.0        0.0       0
5954  20230816   161000    161459  ...         0.0        0.0       0
5955  20230816   161500    161959  ...         0.0        0.0       0
5956  20230816   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-16 16:25:00,764:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1692174299, self.tradeDate='20230816', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29163.7, self.close=29155.5, self.high=29164.5, self.low=29152.5, self.vol=598.343, self.amt=17446274.763, ukdf['pct'].iloc[-1]=-0.000243 , ukdf['amount'].iloc[-1]=17446274.763, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '85832.851', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29155', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230816   040000    075959  1692143999  ...    721  0.002208 -1.120043    -1.0
722  20230816   080000    115959  1692158399  ...    722  0.009182 -1.104510    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '11035.35104289488', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29217.85431924', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [16/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1510969.9663512, self.flagDict['side']='sell', self.tradeCount=20, self.count=565
self.closeSec=1692172799, self.tradeDate='20230816', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29216.7, self.close=29187.0, self.high=29223.5, self.low=29100.0, self.vol=25778.007, self.amt=751855472.3356 
2023-08-16 16:00:01,530:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1692172799, self.tradeDate='20230816', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29216.7, self.close=29187.0, self.high=29223.5, self.low=29100.0, self.vol=25778.007, self.amt=751855472.3356 
2023-08-16 16:00:01,553:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230815   200000    235959  ...  46749.748  1.373552e+09 -0.001427
720  20230816   000000    035959  ...  71364.668  2.084812e+09 -0.004868
721  20230816   040000    075959  ...  22102.685  6.452457e+08  0.000562
722  20230816   080000    115959  ...  18146.820  5.302372e+08  0.000952
723  20230816   120000    155959  ...  25778.007  7.518555e+08 -0.001017

[5 rows x 11 columns]
2023-08-16 16:00:02,301:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230815   200000    235959  1692115199  ...    719  0.000410 -1.130170    -1.0
720  20230816   000000    035959  1692129599  ...    720  0.000004 -1.128381    -1.0
721  20230816   040000    075959  1692143999  ...    721  0.002208 -1.120043    -1.0
722  20230816   080000    115959  1692158399  ...    722  0.009182 -1.104510    -1.0
723  20230816   120000    155959  1692172799  ...    723  0.030721 -1.054429    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.388', 'enterprice': '29432.6', 'countrevence': '0', 'unrealprofit': '12574.39080135892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29187.90491941', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


