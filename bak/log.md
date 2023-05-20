# 20230520 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [20/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1792
self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26853.2, self.close=26860.0, self.high=26869.1, self.low=26853.2, self.vol=638.628, self.amt=17154620.0751 
2023-05-20 16:20:00,712:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230520   155500    155959  ...    0.316317   0.320909       0
5952  20230520   160000    160459  ...    0.316123   0.320889       0
5953  20230520   160500    160959  ...    0.315930   0.320869       0
5954  20230520   161000    161459  ...    0.315735   0.320849       0
5955  20230520   161500    161959  ...    0.315541   0.320828       0

[5 rows x 18 columns]
2023-05-20 16:20:00,720:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26853.2, self.close=26860.0, self.high=26869.1, self.low=26853.2, self.vol=638.628, self.amt=17154620.0751, ukdf['pct'].iloc[-1]=0.00025 , ukdf['amount'].iloc[-1]=17154620.0751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.31554093595758054, signal=0, value_std=0.32082799215684565 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '37.06543059846', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26862.23840079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1793
self.closeSec=1684571099, self.tradeDate='20230520', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26860.0, self.close=26860.0, self.high=26860.1, self.low=26855.9, self.vol=188.0, self.amt=5049250.9819 
127.0.0.1 - - [20/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:25:00,391:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230520   160000    160459  ...    0.316123   0.320889       0
5953  20230520   160500    160959  ...    0.315930   0.320869       0
5954  20230520   161000    161459  ...    0.315735   0.320849       0
5955  20230520   161500    161959  ...    0.315541   0.320828       0
5956  20230520   162000    162459  ...    0.315346   0.320807       0

[5 rows x 18 columns]
2023-05-20 16:25:00,391:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684571099, self.tradeDate='20230520', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26860.0, self.close=26860.0, self.high=26860.1, self.low=26855.9, self.vol=188.0, self.amt=5049250.9819, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=5049250.9819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.31534626968764873, signal=0, value_std=0.3208067816716577 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '68.2374', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26860', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26853.2, self.close=26860.0, self.high=26869.1, self.low=26853.2 
127.0.0.1 - - [20/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:20:00,549:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26853.2, self.close=26860.0, self.high=26869.1, self.low=26853.2   
2023-05-20 16:20:00,658:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230520   155500    155959  1684569599  ...  26840.0 -0.000082   1631    5
1632  20230520   160000    160459  1684569899  ...  26841.8  0.000291   1632    0
1633  20230520   160500    160959  1684570199  ...  26849.6  0.000060   1633    1
1634  20230520   161000    161459  1684570499  ...  26851.1  0.000078   1634    2
1635  20230520   161500    161959  1684570799  ...  26853.2  0.000250   1635    3

[5 rows x 11 columns]
2023-05-20 16:20:00,675:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6113853474236035, self.count=1795 

self.closeSec=1684571099, self.tradeDate='20230520', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26860.0, self.close=26860.0, self.high=26860.1, self.low=26855.9 
127.0.0.1 - - [20/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:25:00,353:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684571099, self.tradeDate='20230520', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26860.0, self.close=26860.0, self.high=26860.1, self.low=26855.9   
2023-05-20 16:25:00,391:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230520   160000    160459  1684569899  ...  26841.8  0.000291   1632    0
1633  20230520   160500    160959  1684570199  ...  26849.6  0.000060   1633    1
1634  20230520   161000    161459  1684570499  ...  26851.1  0.000078   1634    2
1635  20230520   161500    161959  1684570799  ...  26853.2  0.000250   1635    3
1636  20230520   162000    162459  1684571099  ...  26855.9  0.000000   1636    4

[5 rows x 11 columns]
2023-05-20 16:25:00,392:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-20 16:00:22,731:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230520    132959  26862.1  ...  49.166667  0.479465  0.558522
5787  20230520    135959  26849.3  ...  49.166667  0.480868  0.559531
5788  20230520    142959  26853.8  ...  48.750000  0.479460  0.561024
5789  20230520    145959  26849.1  ...  48.750000  0.476912  0.563402
5790  20230520    152959  26840.6  ...  48.750000  0.474889  0.566396

[5 rows x 33 columns]
0.5424354243542435
acc is : 0.5424354243542435
2023-05-20 16:00:22,804:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.496433  0.503567       1  ...  0.954586  -1.0    0.0  0.974082
538     1  0.498807  0.501193       0  ...  0.954753  -1.0    0.0  0.973912
539     1  0.496588  0.503412       0  ...  0.955051  -1.0    0.0  0.973607
540     1  0.495944  0.504056       0  ...  0.955286  -1.0    0.0  0.973368
541     1  0.493929  0.506071       1  ...  0.955009  -1.0    0.0  0.973651

[5 rows x 10 columns]
2023-05-20 16:00:22,816:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.496364  0.503636       1  ...  0.954586  -1.0    0.0  0.971605
46     1  0.498654  0.501346       0  ...  0.954753  -1.0    0.0  0.970834
47     1  0.496304  0.503696       0  ...  0.955051  -1.0    0.0  0.970383
48     1  0.496042  0.503958       0  ...  0.955286  -1.0    0.0  0.972423
49     1  0.493929  0.506071       1  ...  0.955009  -1.0    0.0  0.973651

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-7325.3362', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26844.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230520   155000    155959  1684569599  26844.9  26841.8 -0.000119
2023-05-20 16:00:00,494:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=896 

self.closeSec=1684570199, self.tradeDate='20230520', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26841.9', self.close='26851.2'
2023-05-20 16:10:00,365:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684570199, self.tradeDate='20230520', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26841.9', self.close='26851.2'
127.0.0.1 - - [20/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:10:00,384:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230520   152000    152959  1684567799  26834.1    26834 -0.000004
525  20230520   153000    153959  1684568399    26834    26839  0.000186
526  20230520   154000    154959  1684568999  26838.9    26845  0.000224
527  20230520   155000    155959  1684569599  26844.9  26841.8 -0.000119
528  20230520   160000    160959  1684570199  26841.9  26851.2  0.000350
2023-05-20 16:10:00,384:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=897 

self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26851.1', self.close='26860'
127.0.0.1 - - [20/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:20:00,665:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26851.1', self.close='26860'
2023-05-20 16:20:00,716:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230520   153000    153959  1684568399    26834    26839  0.000186
526  20230520   154000    154959  1684568999  26838.9    26845  0.000224
527  20230520   155000    155959  1684569599  26844.9  26841.8 -0.000119
528  20230520   160000    160959  1684570199  26841.9  26851.2  0.000350
529  20230520   161000    161959  1684570799  26851.1    26860  0.000328
2023-05-20 16:20:00,716:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230520   155000    155959  1684569599  26844.9  26841.8
2023-05-20 16:00:00,515:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=899 

self.closeSec=1684570199, self.tradeDate='20230520', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26841.9', self.close='26851.2'
2023-05-20 16:10:00,391:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684570199, self.tradeDate='20230520', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26841.9', self.close='26851.2'
127.0.0.1 - - [20/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:10:00,429:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230520   152000    152959  1684567799  26834.1    26834
17517  20230520   153000    153959  1684568399    26834    26839
17518  20230520   154000    154959  1684568999  26838.9    26845
17519  20230520   155000    155959  1684569599  26844.9  26841.8
17520  20230520   160000    160959  1684570199  26841.9  26851.2
2023-05-20 16:10:00,429:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=900 

self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26851.1', self.close='26860'
127.0.0.1 - - [20/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:20:00,842:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26851.1', self.close='26860'
2023-05-20 16:20:00,862:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230520   153000    153959  1684568399    26834    26839
17518  20230520   154000    154959  1684568999  26838.9    26845
17519  20230520   155000    155959  1684569599  26844.9  26841.8
17520  20230520   160000    160959  1684570199  26841.9  26851.2
17521  20230520   161000    161959  1684570799  26851.1    26860
2023-05-20 16:20:00,862:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230520   155000    155959  1684569599  26844.9  26841.8
2023-05-20 16:00:00,505:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [20/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=899 

self.closeSec=1684570199, self.tradeDate='20230520', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26841.9', self.close='26851.2'
2023-05-20 16:10:00,336:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684570199, self.tradeDate='20230520', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26841.9', self.close='26851.2'
2023-05-20 16:10:00,355:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230520   152000    152959  1684567799  26834.1    26834
12189  20230520   153000    153959  1684568399    26834    26839
12190  20230520   154000    154959  1684568999  26838.9    26845
12191  20230520   155000    155959  1684569599  26844.9  26841.8
12192  20230520   160000    160959  1684570199  26841.9  26851.2
2023-05-20 16:10:00,355:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=900 

self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26851.1', self.close='26860'
127.0.0.1 - - [20/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:20:00,786:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26851.1', self.close='26860'
2023-05-20 16:20:00,820:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230520   153000    153959  1684568399    26834    26839
12190  20230520   154000    154959  1684568999  26838.9    26845
12191  20230520   155000    155959  1684569599  26844.9  26841.8
12192  20230520   160000    160959  1684570199  26841.9  26851.2
12193  20230520   161000    161959  1684570799  26851.1    26860
2023-05-20 16:20:00,821:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1792
self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26853.2, self.close=26860.0, self.high=26869.1, self.low=26853.2, self.vol=638.628, self.amt=17154620.0751 
127.0.0.1 - - [20/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:20:00,705:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230520   155500    155959  ...    0.116274   0.269398       0
5952  20230520   160000    160459  ...    0.115919   0.269101       0
5953  20230520   160500    160959  ...    0.115561   0.268799       0
5954  20230520   161000    161459  ...    0.115202   0.268492       0
5955  20230520   161500    161959  ...    0.114840   0.268179       0

[5 rows x 18 columns]
2023-05-20 16:20:00,720:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684570799, self.tradeDate='20230520', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26853.2, self.close=26860.0, self.high=26869.1, self.low=26853.2, self.vol=638.628, self.amt=17154620.0751, ukdf['pct'].iloc[-1]=0.00025 , ukdf['amount'].iloc[-1]=17154620.0751, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.11484019722241741, signal=0, value_std=0.26817906572674477 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '677.39244374139', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26862.23840079', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [20/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1793
self.closeSec=1684571099, self.tradeDate='20230520', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26860.0, self.close=26860.0, self.high=26860.1, self.low=26855.9, self.vol=188.0, self.amt=5049250.9819 
2023-05-20 16:25:00,398:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230520   160000    160459  ...    0.115919   0.269101       0
5953  20230520   160500    160959  ...    0.115561   0.268799       0
5954  20230520   161000    161459  ...    0.115202   0.268492       0
5955  20230520   161500    161959  ...    0.114840   0.268179       0
5956  20230520   162000    162459  ...    0.114475   0.267858       0

[5 rows x 18 columns]
2023-05-20 16:25:00,399:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684571099, self.tradeDate='20230520', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26860.0, self.close=26860.0, self.high=26860.1, self.low=26855.9, self.vol=188.0, self.amt=5049250.9819, ukdf['pct'].iloc[-1]=0.0 , ukdf['amount'].iloc[-1]=5049250.9819, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.11447506013902989, signal=0, value_std=0.2678577208634513 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '594.256', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26860', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230520   040000    075959  1684540799  ...    721  0.224054 -1.382607    -1.0
722  20230520   080000    115959  1684555199  ...    722  0.201823 -1.471486    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '11289.80495996874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26851.48886574', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=37
self.closeSec=1684569599, self.tradeDate='20230520', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26849.2, self.close=26841.8, self.high=26862.1, self.low=26824.8, self.vol=9537.697, self.amt=256034546.2044 
127.0.0.1 - - [20/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-05-20 16:00:00,395:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684569599, self.tradeDate='20230520', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26849.2, self.close=26841.8, self.high=26862.1, self.low=26824.8, self.vol=9537.697, self.amt=256034546.2044 
2023-05-20 16:00:00,554:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230519   200000    235959  ...  157634.157  4.238887e+09  0.000972
720  20230520   000000    035959  ...   50110.954  1.346546e+09 -0.001619
721  20230520   040000    075959  ...   17666.894  4.744511e+08  0.001629
722  20230520   080000    115959  ...   13932.879  3.740527e+08 -0.000778
723  20230520   120000    155959  ...    9537.697  2.560345e+08 -0.000276

[5 rows x 11 columns]
2023-05-20 16:00:02,540:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230519   200000    235959  1684511999  ...    719  0.299043 -1.013582    -1.0
720  20230520   000000    035959  1684526399  ...    720  0.282814 -1.081324    -1.0
721  20230520   040000    075959  1684540799  ...    721  0.224054 -1.382607    -1.0
722  20230520   080000    115959  1684555199  ...    722  0.201823 -1.471486    -1.0
723  20230520   120000    155959  1684569599  ...    723  0.198884 -1.451841    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '11789.2563', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26841.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


