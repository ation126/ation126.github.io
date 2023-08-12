# 20230812 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25984
self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29407.8, self.close=29401.7, self.high=29407.9, self.low=29401.6, self.vol=318.345, self.amt=9361321.2208 
127.0.0.1 - - [12/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 16:20:06,841:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230812   155500    155959  ...         0.0        0.0       0
5952  20230812   160000    160459  ...         0.0        0.0       0
5953  20230812   160500    160959  ...         0.0        0.0       0
5954  20230812   161000    161459  ...         0.0        0.0       0
5955  20230812   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 16:20:06,860:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29407.8, self.close=29401.7, self.high=29407.9, self.low=29401.6, self.vol=318.345, self.amt=9361321.2208, ukdf['pct'].iloc[-1]=-0.000211 , ukdf['amount'].iloc[-1]=9361321.2208, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35372.04', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29404.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [12/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25985
self.closeSec=1691828699, self.tradeDate='20230812', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29402.0, self.close=29404.0, self.high=29405.0, self.low=29402.0, self.vol=78.759, self.amt=2315855.7594 
2023-08-12 16:25:00,812:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230812   160000    160459  ...         0.0        0.0       0
5953  20230812   160500    160959  ...         0.0        0.0       0
5954  20230812   161000    161459  ...         0.0        0.0       0
5955  20230812   161500    161959  ...         0.0        0.0       0
5956  20230812   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 16:25:00,813:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691828699, self.tradeDate='20230812', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29402.0, self.close=29404.0, self.high=29405.0, self.low=29402.0, self.vol=78.759, self.amt=2315855.7594, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=2315855.7594, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35362.25915299968', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29404.19765568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29407.8, self.close=29401.7, self.high=29407.9, self.low=29401.6 
127.0.0.1 - - [12/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 16:20:04,620:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29407.8, self.close=29401.7, self.high=29407.9, self.low=29401.6   
2023-08-12 16:20:05,830:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230812   155500    155959  1691827199  ...  29410.2 -0.000184   1631    5
1632  20230812   160000    160459  1691827499  ...  29410.0  0.000133   1632    0
1633  20230812   160500    160959  1691827799  ...  29409.6 -0.000150   1633    1
1634  20230812   161000    161459  1691828099  ...  29407.8 -0.000061   1634    2
1635  20230812   161500    161959  1691828399  ...  29401.6 -0.000211   1635    3

[5 rows x 11 columns]
2023-08-12 16:20:05,839:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6583295806448997, self.count=25987 

self.closeSec=1691828699, self.tradeDate='20230812', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29402.0, self.close=29404.0, self.high=29405.0, self.low=29402.0 
127.0.0.1 - - [12/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-12 16:25:00,801:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691828699, self.tradeDate='20230812', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29402.0, self.close=29404.0, self.high=29405.0, self.low=29402.0   
2023-08-12 16:25:00,820:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230812   160000    160459  1691827499  ...  29410.0  0.000133   1632    0
1633  20230812   160500    160959  1691827799  ...  29409.6 -0.000150   1633    1
1634  20230812   161000    161459  1691828099  ...  29407.8 -0.000061   1634    2
1635  20230812   161500    161959  1691828399  ...  29401.6 -0.000211   1635    3
1636  20230812   162000    162459  1691828699  ...  29402.0  0.000078   1636    4

[5 rows x 11 columns]
2023-08-12 16:25:00,820:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-12 16:00:17,517:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230812    132959  29404.9  ...  48.750000  0.482463  0.501984
5787  20230812    135959  29400.1  ...  48.750000  0.479566  0.501707
5788  20230812    142959  29393.2  ...  48.750000  0.475921  0.503090
5789  20230812    145959  29384.8  ...  49.166667  0.488021  0.499378
5790  20230812    152959  29410.7  ...  48.750000  0.481971  0.498579

[5 rows x 33 columns]
0.5202952029520295
acc is : 0.5202952029520295
2023-08-12 16:00:17,577:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.504789  0.495211       0  ...  0.982126  -1.0    0.0  1.004134
538     0  0.503894  0.496106       0  ...  0.982410  -1.0    0.0  1.003843
539     1  0.499599  0.500401       1  ...  0.981545  -1.0    0.0  1.004728
540     0  0.509006  0.490994       0  ...  0.982005  -1.0    0.0  1.004257
541     1  0.498844  0.501156       1  ...  0.981561  -1.0    0.0  1.004711

[5 rows x 10 columns]
2023-08-12 16:00:17,588:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.505086  0.494914       0  ...  0.982126  -1.0    0.0  1.006634
46     0  0.504352  0.495648       0  ...  0.982410  -1.0    0.0  1.006870
47     1  0.499489  0.500511       1  ...  0.981545  -1.0    0.0  1.006499
48     0  0.509131  0.490869       0  ...  0.982005  -1.0    0.0  1.005713
49     1  0.498844  0.501156       1  ...  0.981561  -1.0    0.0  1.004711

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '1669.0006', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29410.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230812   155000    155959  1691827199  29406.7  29410.2  0.000119
2023-08-12 16:00:02,090:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [12/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12992 

self.closeSec=1691827799, self.tradeDate='20230812', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29410.2', self.close='29409.7'
2023-08-12 16:10:01,152:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691827799, self.tradeDate='20230812', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29410.2', self.close='29409.7'
2023-08-12 16:10:01,172:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230812   152000    152959  1691825399  29403.9    29397 -0.000231
525  20230812   153000    153959  1691825999    29397  29404.2  0.000245
526  20230812   154000    154959  1691826599  29404.2  29406.7  0.000085
527  20230812   155000    155959  1691827199  29406.7  29410.2  0.000119
528  20230812   160000    160959  1691827799  29410.2  29409.7 -0.000017
2023-08-12 16:10:01,178:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12993 

self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29409.7', self.close='29401.7'
127.0.0.1 - - [12/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 16:20:07,220:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29409.7', self.close='29401.7'
2023-08-12 16:20:07,939:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230812   153000    153959  1691825999    29397  29404.2  0.000245
526  20230812   154000    154959  1691826599  29404.2  29406.7  0.000085
527  20230812   155000    155959  1691827199  29406.7  29410.2  0.000119
528  20230812   160000    160959  1691827799  29410.2  29409.7 -0.000017
529  20230812   161000    161959  1691828399  29409.7  29401.7 -0.000272
2023-08-12 16:20:07,940:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230812   155000    155959  1691827199  29406.7  29410.2
2023-08-12 16:00:02,071:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12995 

self.closeSec=1691827799, self.tradeDate='20230812', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29410.2', self.close='29409.7'
2023-08-12 16:10:01,162:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691827799, self.tradeDate='20230812', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29410.2', self.close='29409.7'
127.0.0.1 - - [12/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-12 16:10:01,173:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230812   152000    152959  1691825399  29403.9    29397
17517  20230812   153000    153959  1691825999    29397  29404.2
17518  20230812   154000    154959  1691826599  29404.2  29406.7
17519  20230812   155000    155959  1691827199  29406.7  29410.2
17520  20230812   160000    160959  1691827799  29410.2  29409.7
2023-08-12 16:10:01,173:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12996 

self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29409.7', self.close='29401.7'
127.0.0.1 - - [12/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 16:20:09,014:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29409.7', self.close='29401.7'
2023-08-12 16:20:09,150:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230812   153000    153959  1691825999    29397  29404.2
17518  20230812   154000    154959  1691826599  29404.2  29406.7
17519  20230812   155000    155959  1691827199  29406.7  29410.2
17520  20230812   160000    160959  1691827799  29410.2  29409.7
17521  20230812   161000    161959  1691828399  29409.7  29401.7
2023-08-12 16:20:09,151:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230812   155000    155959  1691827199  29406.7  29410.2
2023-08-12 16:00:02,097:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [12/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12995 

self.closeSec=1691827799, self.tradeDate='20230812', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29410.2', self.close='29409.7'
2023-08-12 16:10:01,136:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691827799, self.tradeDate='20230812', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29410.2', self.close='29409.7'
2023-08-12 16:10:01,153:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230812   152000    152959  1691825399  29403.9    29397
12189  20230812   153000    153959  1691825999    29397  29404.2
12190  20230812   154000    154959  1691826599  29404.2  29406.7
12191  20230812   155000    155959  1691827199  29406.7  29410.2
12192  20230812   160000    160959  1691827799  29410.2  29409.7
2023-08-12 16:10:01,153:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12996 

self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29409.7', self.close='29401.7'
127.0.0.1 - - [12/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-12 16:20:08,822:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29409.7', self.close='29401.7'
2023-08-12 16:20:09,002:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230812   153000    153959  1691825999    29397  29404.2
12190  20230812   154000    154959  1691826599  29404.2  29406.7
12191  20230812   155000    155959  1691827199  29406.7  29410.2
12192  20230812   160000    160959  1691827799  29410.2  29409.7
12193  20230812   161000    161959  1691828399  29409.7  29401.7
2023-08-12 16:20:09,003:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25984
self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29407.8, self.close=29401.7, self.high=29407.9, self.low=29401.6, self.vol=318.345, self.amt=9361321.2208 
127.0.0.1 - - [12/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-12 16:20:06,770:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230812   155500    155959  ...         0.0        0.0       0
5952  20230812   160000    160459  ...         0.0        0.0       0
5953  20230812   160500    160959  ...         0.0        0.0       0
5954  20230812   161000    161459  ...         0.0        0.0       0
5955  20230812   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 16:20:06,800:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691828399, self.tradeDate='20230812', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29407.8, self.close=29401.7, self.high=29407.9, self.low=29401.6, self.vol=318.345, self.amt=9361321.2208, ukdf['pct'].iloc[-1]=-0.000211 , ukdf['amount'].iloc[-1]=9361321.2208, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95114.3869', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29404.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [12/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25985
self.closeSec=1691828699, self.tradeDate='20230812', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29402.0, self.close=29404.0, self.high=29405.0, self.low=29402.0, self.vol=78.759, self.amt=2315855.7594 
2023-08-12 16:25:00,826:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230812   160000    160459  ...         0.0        0.0       0
5953  20230812   160500    160959  ...         0.0        0.0       0
5954  20230812   161000    161459  ...         0.0        0.0       0
5955  20230812   161500    161959  ...         0.0        0.0       0
5956  20230812   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-12 16:25:00,827:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691828699, self.tradeDate='20230812', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29402.0, self.close=29404.0, self.high=29405.0, self.low=29402.0, self.vol=78.759, self.amt=2315855.7594, ukdf['pct'].iloc[-1]=7.8e-05 , ukdf['amount'].iloc[-1]=2315855.7594, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '95088.30112961088', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29404.19765568', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230812   040000    075959  1691798399  ...    721  1.177032  2.091827     1.0
722  20230812   080000    115959  1691812799  ...    722  1.171680  2.004801     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-25543.2548', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29388', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [12/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=541
self.closeSec=1691827199, self.tradeDate='20230812', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29388.0, self.close=29410.2, self.high=29417.2, self.low=29375.7, self.vol=7457.781, self.amt=219252452.9681 
2023-08-12 16:00:01,663:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691827199, self.tradeDate='20230812', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29388.0, self.close=29410.2, self.high=29417.2, self.low=29375.7, self.vol=7457.781, self.amt=219252452.9681 
2023-08-12 16:00:01,678:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230811   200000    235959  ...  67828.797  1.997330e+09 -0.001767
720  20230812   000000    035959  ...  41293.164  1.211417e+09  0.000163
721  20230812   040000    075959  ...  10294.370  3.027534e+08  0.000943
722  20230812   080000    115959  ...  11511.455  3.384544e+08 -0.000935
723  20230812   120000    155959  ...   7457.781  2.192525e+08  0.000755

[5 rows x 11 columns]
2023-08-12 16:00:02,342:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230811   200000    235959  1691769599  ...    719  0.661498  0.717812     1.0
720  20230812   000000    035959  1691783999  ...    720  0.721001  0.884221     1.0
721  20230812   040000    075959  1691798399  ...    721  1.177032  2.091827     1.0
722  20230812   080000    115959  1691812799  ...    722  1.171680  2.004801     1.0
723  20230812   120000    155959  1691827199  ...    723  1.113365  1.792293     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-24400.9094', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29410.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


