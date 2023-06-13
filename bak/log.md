# 20230613 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8704
self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26054.0, self.close=26080.1, self.high=26095.0, self.low=26054.0, self.vol=913.775, self.amt=23828904.2578 
127.0.0.1 - - [13/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-13 16:20:07,712:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230613   155500    155959  ...         0.0        0.0       0
5952  20230613   160000    160459  ...         0.0        0.0       0
5953  20230613   160500    160959  ...         0.0        0.0       0
5954  20230613   161000    161459  ...         0.0        0.0       0
5955  20230613   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 16:20:07,742:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26054.0, self.close=26080.1, self.high=26095.0, self.low=26054.0, self.vol=913.775, self.amt=23828904.2578, ukdf['pct'].iloc[-1]=0.001002 , ukdf['amount'].iloc[-1]=23828904.2578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10859.12917871892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26085.12625458', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [13/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=8705
self.closeSec=1686644699, self.tradeDate='20230613', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26080.1, self.close=26103.8, self.high=26114.3, self.low=26080.0, self.vol=963.329, self.amt=25144399.9145 
2023-06-13 16:25:00,836:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230613   160000    160459  ...         0.0        0.0       0
5953  20230613   160500    160959  ...         0.0        0.0       0
5954  20230613   161000    161459  ...         0.0        0.0       0
5955  20230613   161500    161959  ...         0.0        0.0       0
5956  20230613   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 16:25:00,836:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686644699, self.tradeDate='20230613', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26080.1, self.close=26103.8, self.high=26114.3, self.low=26080.0, self.vol=963.329, self.amt=25144399.9145, ukdf['pct'].iloc[-1]=0.000909 , ukdf['amount'].iloc[-1]=25144399.9145, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '10582.3674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26105', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26054.0, self.close=26080.1, self.high=26095.0, self.low=26054.0 
127.0.0.1 - - [13/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 16:20:05,112:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26054.0, self.close=26080.1, self.high=26095.0, self.low=26054.0   
2023-06-13 16:20:06,731:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230613   155500    155959  1686643199  ...  26055.5  0.000084   1631    5
1632  20230613   160000    160459  1686643499  ...  26056.5  0.000035   1632    0
1633  20230613   160500    160959  1686643799  ...  26050.0 -0.000426   1633    1
1634  20230613   161000    161459  1686644099  ...  26044.9  0.000150   1634    2
1635  20230613   161500    161959  1686644399  ...  26054.0  0.001002   1635    3

[5 rows x 11 columns]
2023-06-13 16:20:06,741:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=42, self.factor=0.37576678335751645, self.count=8707 

self.closeSec=1686644699, self.tradeDate='20230613', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26080.1, self.close=26103.8, self.high=26114.3, self.low=26080.0 
127.0.0.1 - - [13/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-13 16:25:00,774:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686644699, self.tradeDate='20230613', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26080.1, self.close=26103.8, self.high=26114.3, self.low=26080.0   
2023-06-13 16:25:00,817:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230613   160000    160459  1686643499  ...  26056.5  0.000035   1632    0
1633  20230613   160500    160959  1686643799  ...  26050.0 -0.000426   1633    1
1634  20230613   161000    161459  1686644099  ...  26044.9  0.000150   1634    2
1635  20230613   161500    161959  1686644399  ...  26054.0  0.001002   1635    3
1636  20230613   162000    162459  1686644699  ...  26080.0  0.000909   1636    4

[5 rows x 11 columns]
2023-06-13 16:25:00,820:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-13 16:00:18,976:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230613    132959  26042.9  ...  47.500000  0.528452  0.362555
5787  20230613    135959  26040.0  ...  47.916667  0.533697  0.349985
5788  20230613    142959  26065.8  ...  48.333333  0.541007  0.333571
5789  20230613    145959  26102.0  ...  47.916667  0.533069  0.322610
5790  20230613    152959  26068.2  ...  47.916667  0.535812  0.310660

[5 rows x 33 columns]
0.5350553505535055
acc is : 0.5350553505535055
2023-06-13 16:00:19,062:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.493537  0.506463       1  ...  0.999694  -1.0    0.0  0.973331
538     0  0.501462  0.498538       1  ...  0.998306  -1.0    0.0  0.974683
539     0  0.511546  0.488454       0  ...  0.999595  -1.0    0.0  0.973424
540     0  0.502154  0.497846       1  ...  0.999085  -1.0    0.0  0.973921
541     0  0.507077  0.492923       0  ...  0.999901  -1.0    0.0  0.973125

[5 rows x 10 columns]
2023-06-13 16:00:19,075:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.493800  0.506200       1  ...  0.999694  -1.0    0.0  0.970092
46     0  0.501752  0.498248       1  ...  0.998306  -1.0    0.0  0.974817
47     0  0.511551  0.488449       0  ...  0.999595  -1.0    0.0  0.972505
48     0  0.502504  0.497496       1  ...  0.999085  -1.0    0.0  0.976737
49     0  0.507077  0.492923       0  ...  0.999901  -1.0    0.0  0.973125

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.898', 'enterprice': '25555.4', 'countrevence': '0', 'unrealprofit': '-14283.776', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26067.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230613   155000    155959  1686643199  26070.9  26060.2 -0.000410
2023-06-13 16:00:02,217:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [13/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4352 

self.closeSec=1686643799, self.tradeDate='20230613', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26060.3', self.close='26050.1'
2023-06-13 16:10:01,123:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686643799, self.tradeDate='20230613', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26060.3', self.close='26050.1'
2023-06-13 16:10:01,152:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230613   152000    152959  1686641399  26077.5  26081.6  0.000157
525  20230613   153000    153959  1686641999  26081.6    26088  0.000245
526  20230613   154000    154959  1686642599    26088  26070.9 -0.000655
527  20230613   155000    155959  1686643199  26070.9  26060.2 -0.000410
528  20230613   160000    160959  1686643799  26060.3  26050.1 -0.000388
2023-06-13 16:10:01,152:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4353 

self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26050', self.close='26080'
127.0.0.1 - - [13/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-13 16:20:07,380:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26050', self.close='26080'
2023-06-13 16:20:08,271:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230613   153000    153959  1686641999  26081.6    26088  0.000245
526  20230613   154000    154959  1686642599    26088  26070.9 -0.000655
527  20230613   155000    155959  1686643199  26070.9  26060.2 -0.000410
528  20230613   160000    160959  1686643799  26060.3  26050.1 -0.000388
529  20230613   161000    161959  1686644399    26050    26080  0.001148
2023-06-13 16:20:08,281:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230613   155000    155959  1686643199  26070.9  26060.2
2023-06-13 16:00:02,225:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4355 

self.closeSec=1686643799, self.tradeDate='20230613', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26060.3', self.close='26050.1'
2023-06-13 16:10:01,147:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686643799, self.tradeDate='20230613', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26060.3', self.close='26050.1'
127.0.0.1 - - [13/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-13 16:10:01,166:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230613   152000    152959  1686641399  26077.5  26081.6
17517  20230613   153000    153959  1686641999  26081.6    26088
17518  20230613   154000    154959  1686642599    26088  26070.9
17519  20230613   155000    155959  1686643199  26070.9  26060.2
17520  20230613   160000    160959  1686643799  26060.3  26050.1
2023-06-13 16:10:01,166:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4356 

self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26050', self.close='26080'
127.0.0.1 - - [13/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-13 16:20:09,598:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26050', self.close='26080'
2023-06-13 16:20:09,751:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230613   153000    153959  1686641999  26081.6    26088
17518  20230613   154000    154959  1686642599    26088  26070.9
17519  20230613   155000    155959  1686643199  26070.9  26060.2
17520  20230613   160000    160959  1686643799  26060.3  26050.1
17521  20230613   161000    161959  1686644399    26050    26080
2023-06-13 16:20:09,752:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230613   155000    155959  1686643199  26070.9  26060.2
2023-06-13 16:00:02,251:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [13/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4355 

self.closeSec=1686643799, self.tradeDate='20230613', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26060.3', self.close='26050.1'
2023-06-13 16:10:01,129:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686643799, self.tradeDate='20230613', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26060.3', self.close='26050.1'
2023-06-13 16:10:01,157:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230613   152000    152959  1686641399  26077.5  26081.6
12189  20230613   153000    153959  1686641999  26081.6    26088
12190  20230613   154000    154959  1686642599    26088  26070.9
12191  20230613   155000    155959  1686643199  26070.9  26060.2
12192  20230613   160000    160959  1686643799  26060.3  26050.1
2023-06-13 16:10:01,157:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=4356 

self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26050', self.close='26080'
127.0.0.1 - - [13/Jun/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-06-13 16:20:09,272:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26050', self.close='26080'
2023-06-13 16:20:09,599:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230613   153000    153959  1686641999  26081.6    26088
12190  20230613   154000    154959  1686642599    26088  26070.9
12191  20230613   155000    155959  1686643199  26070.9  26060.2
12192  20230613   160000    160959  1686643799  26060.3  26050.1
12193  20230613   161000    161959  1686644399    26050    26080
2023-06-13 16:20:09,601:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8704
self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26054.0, self.close=26080.1, self.high=26095.0, self.low=26054.0, self.vol=913.775, self.amt=23828904.2578 
127.0.0.1 - - [13/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-13 16:20:07,531:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230613   155500    155959  ...         0.0        0.0       0
5952  20230613   160000    160459  ...         0.0        0.0       0
5953  20230613   160500    160959  ...         0.0        0.0       0
5954  20230613   161000    161459  ...         0.0        0.0       0
5955  20230613   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 16:20:07,572:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686644399, self.tradeDate='20230613', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26054.0, self.close=26080.1, self.high=26095.0, self.low=26054.0, self.vol=913.775, self.amt=23828904.2578, ukdf['pct'].iloc[-1]=0.001002 , ukdf['amount'].iloc[-1]=23828904.2578, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-28185.32977864422', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26085.12625458', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=8705
self.closeSec=1686644699, self.tradeDate='20230613', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26080.1, self.close=26103.8, self.high=26114.3, self.low=26080.0, self.vol=963.329, self.amt=25144399.9145 
127.0.0.1 - - [13/Jun/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-06-13 16:25:00,844:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230613   160000    160459  ...         0.0        0.0       0
5953  20230613   160500    160959  ...         0.0        0.0       0
5954  20230613   161000    161459  ...         0.0        0.0       0
5955  20230613   161500    161959  ...         0.0        0.0       0
5956  20230613   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-13 16:25:00,844:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686644699, self.tradeDate='20230613', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26080.1, self.close=26103.8, self.high=26114.3, self.low=26080.0, self.vol=963.329, self.amt=25144399.9145, ukdf['pct'].iloc[-1]=0.000909 , ukdf['amount'].iloc[-1]=25144399.9145, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-27447.199', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26105', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230613   040000    075959  1686614399  ...    721  0.422349 -0.556833     NaN
722  20230613   080000    115959  1686628799  ...    722  0.400757 -0.611843    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '56712.91783044636', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26050.55885454', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=181
self.closeSec=1686643199, self.tradeDate='20230613', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26054.7, self.close=26060.2, self.high=26125.0, self.low=25963.7, self.vol=34095.2, self.amt=888387148.4347 
127.0.0.1 - - [13/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-06-13 16:00:01,799:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686643199, self.tradeDate='20230613', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26054.7, self.close=26060.2, self.high=26125.0, self.low=25963.7, self.vol=34095.2, self.amt=888387148.4347 
2023-06-13 16:00:01,823:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230612   200000    235959  ...  55282.739  1.428066e+09 -0.006406
720  20230613   000000    035959  ...  60408.792  1.559081e+09  0.000291
721  20230613   040000    075959  ...  25186.398  6.521044e+08  0.003017
722  20230613   080000    115959  ...  70391.032  1.830381e+09  0.006175
723  20230613   120000    155959  ...  34095.200  8.883871e+08  0.000215

[5 rows x 11 columns]
2023-06-13 16:00:03,270:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230612   200000    235959  1686585599  ...    719  0.487058 -0.369591     NaN
720  20230613   000000    035959  1686599999  ...    720  0.456457 -0.460266     NaN
721  20230613   040000    075959  1686614399  ...    721  0.422349 -0.556833     NaN
722  20230613   080000    115959  1686628799  ...    722  0.400757 -0.611843    -1.0
723  20230613   120000    155959  1686643199  ...    723  0.362114 -0.726321    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '56031.44297007496', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26062.91202244', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


