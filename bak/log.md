# 20230528 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4096
self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27206.4, self.close=27195.0, self.high=27207.4, self.low=27195.0, self.vol=416.231, self.amt=11322814.6905 
127.0.0.1 - - [28/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 16:20:05,574:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230528   155500    155959  ...         0.0        0.0       0
5952  20230528   160000    160459  ...         0.0        0.0       0
5953  20230528   160500    160959  ...         0.0        0.0       0
5954  20230528   161000    161459  ...         0.0        0.0       0
5955  20230528   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 16:20:05,594:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27206.4, self.close=27195.0, self.high=27207.4, self.low=27195.0, self.vol=416.231, self.amt=11322814.6905, ukdf['pct'].iloc[-1]=-0.000419 , ukdf['amount'].iloc[-1]=11322814.6905, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4645.9028167398', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27198.5135873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [28/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=4097
self.closeSec=1685262299, self.tradeDate='20230528', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27195.0, self.close=27171.1, self.high=27198.0, self.low=27171.0, self.vol=1079.561, self.amt=29346333.8937 
2023-05-28 16:25:00,818:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230528   160000    160459  ...         0.0        0.0       0
5953  20230528   160500    160959  ...         0.0        0.0       0
5954  20230528   161000    161459  ...         0.0        0.0       0
5955  20230528   161500    161959  ...         0.0        0.0       0
5956  20230528   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 16:25:00,818:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1685262299, self.tradeDate='20230528', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27195.0, self.close=27171.1, self.high=27198.0, self.low=27171.0, self.vol=1079.561, self.amt=29346333.8937, ukdf['pct'].iloc[-1]=-0.000879 , ukdf['amount'].iloc[-1]=29346333.8937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-4309.4730274662', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '27174.3551937', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27206.4, self.close=27195.0, self.high=27207.4, self.low=27195.0 
127.0.0.1 - - [28/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 16:20:03,784:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27206.4, self.close=27195.0, self.high=27207.4, self.low=27195.0   
2023-05-28 16:20:04,944:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230528   155500    155959  1685260799  ...  27202.4  0.000515   1631    5
1632  20230528   160000    160459  1685261099  ...  27188.0 -0.000794   1632    0
1633  20230528   160500    160959  1685261399  ...  27191.8  0.000456   1633    1
1634  20230528   161000    161459  1685261699  ...  27203.4 -0.000121   1634    2
1635  20230528   161500    161959  1685261999  ...  27195.0 -0.000419   1635    3

[5 rows x 11 columns]
2023-05-28 16:20:04,945:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [28/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=83, self.factor=0.21969372849424132, self.count=4099 

self.closeSec=1685262299, self.tradeDate='20230528', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27195.0, self.close=27171.1, self.high=27198.0, self.low=27171.0 
2023-05-28 16:25:00,720:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1685262299, self.tradeDate='20230528', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27195.0, self.close=27171.1, self.high=27198.0, self.low=27171.0   
2023-05-28 16:25:00,775:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230528   160000    160459  1685261099  ...  27188.0 -0.000794   1632    0
1633  20230528   160500    160959  1685261399  ...  27191.8  0.000456   1633    1
1634  20230528   161000    161459  1685261699  ...  27203.4 -0.000121   1634    2
1635  20230528   161500    161959  1685261999  ...  27195.0 -0.000419   1635    3
1636  20230528   162000    162459  1685262299  ...  27171.0 -0.000879   1636    4

[5 rows x 11 columns]
2023-05-28 16:25:00,775:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-28 16:00:32,765:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230528    132959  27157.0  ...  47.500000  0.616545  0.230372
5787  20230528    135959  27125.0  ...  47.500000  0.623247  0.226092
5788  20230528    142959  27154.3  ...  47.916667  0.629516  0.219628
5789  20230528    145959  27182.1  ...  47.916667  0.627027  0.214172
5790  20230528    152959  27175.5  ...  48.333333  0.629922  0.207961

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-05-28 16:00:32,932:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.488151  0.511849       1  ...  0.921830   1.0    0.0  1.002470
538     1  0.498515  0.501485       1  ...  0.922774   1.0    0.0  1.003496
539     1  0.494710  0.505290       0  ...  0.922553   1.0    0.0  1.003256
540     1  0.487398  0.512602       1  ...  0.922981   1.0    0.0  1.003721
541     1  0.493743  0.506257       1  ...  0.924023   1.0    0.0  1.004855

[5 rows x 10 columns]
2023-05-28 16:00:32,971:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.488222  0.511778       1  ...  0.921830   1.0    0.0  1.006117
46     1  0.498587  0.501413       1  ...  0.922774   1.0    0.0  1.007065
47     1  0.494698  0.505302       0  ...  0.922553   1.0    0.0  1.005580
48     1  0.487903  0.512097       1  ...  0.922981   1.0    0.0  1.007694
49     1  0.493743  0.506257       1  ...  0.924023   1.0    0.0  1.004855

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '25.918', 'enterprice': '26792.4', 'countrevence': '0', 'unrealprofit': '11134.3728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27222', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230528   155000    155959  1685260799  27198.2  27218.9  0.000757
2023-05-28 16:00:02,372:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [28/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2048 

self.closeSec=1685261399, self.tradeDate='20230528', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27219', self.close='27209.7'
2023-05-28 16:10:01,092:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685261399, self.tradeDate='20230528', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27219', self.close='27209.7'
2023-05-28 16:10:01,103:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230528   152000    152959  1685258999  27182.9  27188.2  0.000199
525  20230528   153000    153959  1685259599  27188.2  27195.4  0.000265
526  20230528   154000    154959  1685260199  27195.5  27198.3  0.000107
527  20230528   155000    155959  1685260799  27198.2  27218.9  0.000757
528  20230528   160000    160959  1685261399    27219  27209.7 -0.000338
2023-05-28 16:10:01,103:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2049 

self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27209.7', self.close='27195'
127.0.0.1 - - [28/May/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-05-28 16:20:05,614:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27209.7', self.close='27195'
2023-05-28 16:20:06,025:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230528   153000    153959  1685259599  27188.2  27195.4  0.000265
526  20230528   154000    154959  1685260199  27195.5  27198.3  0.000107
527  20230528   155000    155959  1685260799  27198.2  27218.9  0.000757
528  20230528   160000    160959  1685261399    27219  27209.7 -0.000338
529  20230528   161000    161959  1685261999  27209.7    27195 -0.000540
2023-05-28 16:20:06,034:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230528   155000    155959  1685260799  27198.2  27218.9
2023-05-28 16:00:02,385:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2051 

self.closeSec=1685261399, self.tradeDate='20230528', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27219', self.close='27209.7'
2023-05-28 16:10:01,110:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685261399, self.tradeDate='20230528', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27219', self.close='27209.7'
127.0.0.1 - - [28/May/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-05-28 16:10:01,132:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230528   152000    152959  1685258999  27182.9  27188.2
17517  20230528   153000    153959  1685259599  27188.2  27195.4
17518  20230528   154000    154959  1685260199  27195.5  27198.3
17519  20230528   155000    155959  1685260799  27198.2  27218.9
17520  20230528   160000    160959  1685261399    27219  27209.7
2023-05-28 16:10:01,132:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2052 

self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27209.7', self.close='27195'
127.0.0.1 - - [28/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 16:20:06,826:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27209.7', self.close='27195'
2023-05-28 16:20:06,940:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230528   153000    153959  1685259599  27188.2  27195.4
17518  20230528   154000    154959  1685260199  27195.5  27198.3
17519  20230528   155000    155959  1685260799  27198.2  27218.9
17520  20230528   160000    160959  1685261399    27219  27209.7
17521  20230528   161000    161959  1685261999  27209.7    27195
2023-05-28 16:20:06,941:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230528   155000    155959  1685260799  27198.2  27218.9
2023-05-28 16:00:02,370:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [28/May/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2051 

self.closeSec=1685261399, self.tradeDate='20230528', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='27219', self.close='27209.7'
2023-05-28 16:10:01,063:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685261399, self.tradeDate='20230528', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='27219', self.close='27209.7'
2023-05-28 16:10:01,073:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230528   152000    152959  1685258999  27182.9  27188.2
12189  20230528   153000    153959  1685259599  27188.2  27195.4
12190  20230528   154000    154959  1685260199  27195.5  27198.3
12191  20230528   155000    155959  1685260799  27198.2  27218.9
12192  20230528   160000    160959  1685261399    27219  27209.7
2023-05-28 16:10:01,078:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=2052 

self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='27209.7', self.close='27195'
127.0.0.1 - - [28/May/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-05-28 16:20:06,589:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='27209.7', self.close='27195'
2023-05-28 16:20:06,794:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230528   153000    153959  1685259599  27188.2  27195.4
12190  20230528   154000    154959  1685260199  27195.5  27198.3
12191  20230528   155000    155959  1685260799  27198.2  27218.9
12192  20230528   160000    160959  1685261399    27219  27209.7
12193  20230528   161000    161959  1685261999  27209.7    27195
2023-05-28 16:20:06,794:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4096
self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=27206.4, self.close=27195.0, self.high=27207.4, self.low=27195.0, self.vol=416.231, self.amt=11322814.6905 
127.0.0.1 - - [28/May/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-05-28 16:20:05,555:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230528   155500    155959  ...         0.0        0.0       0
5952  20230528   160000    160459  ...         0.0        0.0       0
5953  20230528   160500    160959  ...         0.0        0.0       0
5954  20230528   161000    161459  ...         0.0        0.0       0
5955  20230528   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 16:20:05,575:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685261999, self.tradeDate='20230528', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=27206.4, self.close=27195.0, self.high=27207.4, self.low=27195.0, self.vol=416.231, self.amt=11322814.6905, ukdf['pct'].iloc[-1]=-0.000419 , ukdf['amount'].iloc[-1]=11322814.6905, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '13166.9891459093', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27198.5135873', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=4097
self.closeSec=1685262299, self.tradeDate='20230528', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=27195.0, self.close=27171.1, self.high=27198.0, self.low=27171.0, self.vol=1079.561, self.amt=29346333.8937 
127.0.0.1 - - [28/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-28 16:25:00,751:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230528   160000    160459  ...         0.0        0.0       0
5953  20230528   160500    160959  ...         0.0        0.0       0
5954  20230528   161000    161459  ...         0.0        0.0       0
5955  20230528   161500    161959  ...         0.0        0.0       0
5956  20230528   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-28 16:25:00,759:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1685262299, self.tradeDate='20230528', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=27195.0, self.close=27171.1, self.high=27198.0, self.low=27171.0, self.vol=1079.561, self.amt=29346333.8937, ukdf['pct'].iloc[-1]=-0.000879 , ukdf['amount'].iloc[-1]=29346333.8937, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '12269.7222492117', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27174.3551937', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230528   040000    075959  1685231999  ...    721  0.320607 -0.451685     NaN
722  20230528   080000    115959  1685246399  ...    722  0.324389 -0.422521     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '58856.7597', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27193.5', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1442113.3648782002, self.flagDict['side']='buy', self.tradeCount=3, self.count=85
self.closeSec=1685260799, self.tradeDate='20230528', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=27174.5, self.close=27218.9, self.high=27279.0, self.low=27113.4, self.vol=40838.873, self.amt=1110311286.1829 
127.0.0.1 - - [28/May/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-05-28 16:00:01,895:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1685260799, self.tradeDate='20230528', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=27174.5, self.close=27218.9, self.high=27279.0, self.low=27113.4, self.vol=40838.873, self.amt=1110311286.1829 
2023-05-28 16:00:01,950:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230527   200000    235959  ...  47080.958  1.255307e+09 -0.000210
720  20230528   000000    035959  ...  38259.082  1.022615e+09  0.001480
721  20230528   040000    075959  ...  21946.952  5.879028e+08  0.004491
722  20230528   080000    115959  ...  89784.520  2.429619e+09  0.012399
723  20230528   120000    155959  ...  40838.873  1.110311e+09  0.001638

[5 rows x 11 columns]
2023-05-28 16:00:04,007:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230527   200000    235959  1685203199  ...    719  0.462421  0.346905     NaN
720  20230528   000000    035959  1685217599  ...    720  0.395964 -0.029926     NaN
721  20230528   040000    075959  1685231999  ...    721  0.320607 -0.451685     NaN
722  20230528   080000    115959  1685246399  ...    722  0.324389 -0.422521     NaN
723  20230528   120000    155959  1685260799  ...    723  0.365024 -0.185390     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.249', 'enterprice': '26128.2', 'countrevence': '0', 'unrealprofit': '60320.8582', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '27220', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


