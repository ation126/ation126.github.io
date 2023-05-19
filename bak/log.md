# 20230519 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [19/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1504
self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26860.1, self.close=26865.9, self.high=26867.8, self.low=26860.1, self.vol=263.321, self.amt=7074104.2572 
2023-05-19 16:20:00,597:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230519   155500    155959  ...    0.366664   0.320505       0
5952  20230519   160000    160459  ...    0.366546   0.320562       0
5953  20230519   160500    160959  ...    0.366426   0.320618       0
5954  20230519   161000    161459  ...    0.366313   0.320675       0
5955  20230519   161500    161959  ...    0.366198   0.320733       0

[5 rows x 18 columns]
2023-05-19 16:20:00,601:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26860.1, self.close=26865.9, self.high=26867.8, self.low=26860.1, self.vol=263.321, self.amt=7074104.2572, ukdf['pct'].iloc[-1]=0.000212 , ukdf['amount'].iloc[-1]=7074104.2572, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.36619811866223906, signal=0, value_std=0.32073251928547697 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33.25447179714', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26867.28794139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1505
self.closeSec=1684484699, self.tradeDate='20230519', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26865.8, self.close=26866.6, self.high=26870.0, self.low=26862.3, self.vol=347.589, self.amt=9338570.8095 
2023-05-19 16:25:00,416:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230519   160000    160459  ...    0.366546   0.320562       0
5953  20230519   160500    160959  ...    0.366426   0.320618       0
5954  20230519   161000    161459  ...    0.366313   0.320675       0
5955  20230519   161500    161959  ...    0.366198   0.320733       0
5956  20230519   162000    162459  ...    0.366085   0.320790       0

[5 rows x 18 columns]
2023-05-19 16:25:00,417:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684484699, self.tradeDate='20230519', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26865.8, self.close=26866.6, self.high=26870.0, self.low=26862.3, self.vol=347.589, self.amt=9338570.8095, ukdf['pct'].iloc[-1]=2.6e-05 , ukdf['amount'].iloc[-1]=9338570.8095, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.36608480424201656, signal=0, value_std=0.3207898105829849 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-31.63239248466', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26867.17146291', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26860.1, self.close=26865.9, self.high=26867.8, self.low=26860.1 
127.0.0.1 - - [19/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-19 16:20:00,442:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26860.1, self.close=26865.9, self.high=26867.8, self.low=26860.1   
2023-05-19 16:20:00,506:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230519   155500    155959  1684483199  ...  26841.1 -0.000123   1631    5
1632  20230519   160000    160459  1684483499  ...  26818.9  0.000294   1632    0
1633  20230519   160500    160959  1684483799  ...  26849.8  0.000086   1633    1
1634  20230519   161000    161459  1684484099  ...  26852.1  0.000302   1634    2
1635  20230519   161500    161959  1684484399  ...  26860.1  0.000212   1635    3

[5 rows x 11 columns]
2023-05-19 16:20:00,506:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=24, self.factor=0.4981287526008, self.count=1507 

self.closeSec=1684484699, self.tradeDate='20230519', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26865.8, self.close=26866.6, self.high=26870.0, self.low=26862.3 
2023-05-19 16:25:00,357:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684484699, self.tradeDate='20230519', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26865.8, self.close=26866.6, self.high=26870.0, self.low=26862.3   
2023-05-19 16:25:00,396:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230519   160000    160459  1684483499  ...  26818.9  0.000294   1632    0
1633  20230519   160500    160959  1684483799  ...  26849.8  0.000086   1633    1
1634  20230519   161000    161459  1684484099  ...  26852.1  0.000302   1634    2
1635  20230519   161500    161959  1684484399  ...  26860.1  0.000212   1635    3
1636  20230519   162000    162459  1684484699  ...  26862.3  0.000026   1636    4

[5 rows x 11 columns]
2023-05-19 16:25:00,396:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-19 16:00:18,825:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230519    132959  26863.7  ...  48.333333  0.463616  0.560484
5787  20230519    135959  26835.8  ...  48.333333  0.469727  0.558757
5788  20230519    142959  26864.1  ...  48.333333  0.474818  0.555761
5789  20230519    145959  26887.6  ...  48.750000  0.475537  0.552771
5790  20230519    152959  26891.0  ...  48.750000  0.473115  0.550691

[5 rows x 33 columns]
0.5295202952029521
acc is : 0.5295202952029521
2023-05-19 16:00:18,933:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.504599  0.495401       1  ...  0.928023  -1.0    0.0  0.940504
538     0  0.509351  0.490649       1  ...  0.927207  -1.0    0.0  0.941331
539     0  0.513202  0.486798       1  ...  0.927094  -1.0    0.0  0.941446
540     0  0.509476  0.490524       0  ...  0.927511  -1.0    0.0  0.941023
541     0  0.501989  0.498011       0  ...  0.928788  -1.0    0.0  0.939727

[5 rows x 10 columns]
2023-05-19 16:00:18,951:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.504567  0.495433       1  ...  0.988968  -1.0    0.0  0.935132
46     0  0.509076  0.490924       1  ...  0.988099  -1.0    0.0  0.935914
47     0  0.513071  0.486929       1  ...  0.987978  -1.0    0.0  0.946220
48     0  0.509342  0.490658       0  ...  0.927511  -1.0    0.0  0.940713
49     0  0.501989  0.498011       0  ...  0.928788  -1.0    0.0  0.939727

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-6951.90874118126', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26830.64703297', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230519   155000    155959  1684483199  26850.9  26841.9 -0.000339
2023-05-19 16:00:00,487:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [19/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=752 

self.closeSec=1684483799, self.tradeDate='20230519', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26842', self.close='26852.1'
2023-05-19 16:10:00,360:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684483799, self.tradeDate='20230519', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26842', self.close='26852.1'
2023-05-19 16:10:00,421:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230519   152000    152959  1684481399  26925.8  26878.9 -0.001742
525  20230519   153000    153959  1684481999    26879  26847.6 -0.001164
526  20230519   154000    154959  1684482599  26847.6    26851  0.000127
527  20230519   155000    155959  1684483199  26850.9  26841.9 -0.000339
528  20230519   160000    160959  1684483799    26842  26852.1  0.000380
2023-05-19 16:10:00,421:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--: 127.0.0.1 - - [19/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=753 

self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26852.1', self.close='26865.9'
2023-05-19 16:20:00,549:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26852.1', self.close='26865.9'
2023-05-19 16:20:00,578:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230519   153000    153959  1684481999    26879  26847.6 -0.001164
526  20230519   154000    154959  1684482599  26847.6    26851  0.000127
527  20230519   155000    155959  1684483199  26850.9  26841.9 -0.000339
528  20230519   160000    160959  1684483799    26842  26852.1  0.000380
529  20230519   161000    161959  1684484399  26852.1  26865.9  0.000514
2023-05-19 16:20:00,578:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230519   155000    155959  1684483199  26850.9  26841.9
2023-05-19 16:00:00,508:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=755 

self.closeSec=1684483799, self.tradeDate='20230519', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26842', self.close='26852.1'
127.0.0.1 - - [19/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-19 16:10:00,395:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684483799, self.tradeDate='20230519', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26842', self.close='26852.1'
2023-05-19 16:10:00,439:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230519   152000    152959  1684481399  26925.8  26878.9
17517  20230519   153000    153959  1684481999    26879  26847.6
17518  20230519   154000    154959  1684482599  26847.6    26851
17519  20230519   155000    155959  1684483199  26850.9  26841.9
17520  20230519   160000    160959  1684483799    26842  26852.1
2023-05-19 16:10:00,439:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=756 

self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26852.1', self.close='26865.9'
2023-05-19 16:20:00,707:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26852.1', self.close='26865.9'
2023-05-19 16:20:00,741:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230519   153000    153959  1684481999    26879  26847.6
17518  20230519   154000    154959  1684482599  26847.6    26851
17519  20230519   155000    155959  1684483199  26850.9  26841.9
17520  20230519   160000    160959  1684483799    26842  26852.1
17521  20230519   161000    161959  1684484399  26852.1  26865.9
2023-05-19 16:20:00,742:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230519   155000    155959  1684483199  26850.9  26841.9
2023-05-19 16:00:00,403:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=755 

self.closeSec=1684483799, self.tradeDate='20230519', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26842', self.close='26852.1'
2023-05-19 16:10:00,370:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684483799, self.tradeDate='20230519', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26842', self.close='26852.1'
2023-05-19 16:10:00,431:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230519   152000    152959  1684481399  26925.8  26878.9
12189  20230519   153000    153959  1684481999    26879  26847.6
12190  20230519   154000    154959  1684482599  26847.6    26851
12191  20230519   155000    155959  1684483199  26850.9  26841.9
12192  20230519   160000    160959  1684483799    26842  26852.1
2023-05-19 16:10:00,432:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/May/2023 16:20:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=756 

self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26852.1', self.close='26865.9'
2023-05-19 16:20:00,586:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26852.1', self.close='26865.9'
2023-05-19 16:20:00,608:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230519   153000    153959  1684481999    26879  26847.6
12190  20230519   154000    154959  1684482599  26847.6    26851
12191  20230519   155000    155959  1684483199  26850.9  26841.9
12192  20230519   160000    160959  1684483799    26842  26852.1
12193  20230519   161000    161959  1684484399  26852.1  26865.9
2023-05-19 16:20:00,609:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1504
self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26860.1, self.close=26865.9, self.high=26867.8, self.low=26860.1, self.vol=263.321, self.amt=7074104.2572 
2023-05-19 16:20:00,565:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230519   155500    155959  ...    0.187595   0.293160       0
5952  20230519   160000    160459  ...    0.187313   0.293080       0
5953  20230519   160500    160959  ...    0.187033   0.293002       0
5954  20230519   161000    161459  ...    0.186753   0.292924       0
5955  20230519   161500    161959  ...    0.186476   0.292849       0

[5 rows x 18 columns]
2023-05-19 16:20:00,568:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684484399, self.tradeDate='20230519', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26860.1, self.close=26865.9, self.high=26867.8, self.low=26860.1, self.vol=263.321, self.amt=7074104.2572, ukdf['pct'].iloc[-1]=0.000212 , ukdf['amount'].iloc[-1]=7074104.2572, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.18647577994458675, signal=0, value_std=0.2928488312554901 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '864.93743116599', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26867.28794139', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1505
self.closeSec=1684484699, self.tradeDate='20230519', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26865.8, self.close=26866.6, self.high=26870.0, self.low=26862.3, self.vol=347.589, self.amt=9338570.8095 
127.0.0.1 - - [19/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-05-19 16:25:00,415:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230519   160000    160459  ...    0.187313   0.293080       0
5953  20230519   160500    160959  ...    0.187033   0.293002       0
5954  20230519   161000    161459  ...    0.186753   0.292924       0
5955  20230519   161500    161959  ...    0.186476   0.292849       0
5956  20230519   162000    162459  ...    0.186196   0.292770       0

[5 rows x 18 columns]
2023-05-19 16:25:00,415:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684484699, self.tradeDate='20230519', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26865.8, self.close=26866.6, self.high=26870.0, self.low=26862.3, self.vol=347.589, self.amt=9338570.8095, ukdf['pct'].iloc[-1]=2.6e-05 , ukdf['amount'].iloc[-1]=9338570.8095, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.1861961444682355, signal=0, value_std=0.2927704116530815 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '860.61130394031', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26867.17146291', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230519   040000    075959  1684454399  ...    721  0.281797 -1.193104    -1.0
722  20230519   080000    115959  1684468799  ...    722  0.298540 -1.075083    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '12606.44928498624', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26825.94725824', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [19/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=31
self.closeSec=1684483199, self.tradeDate='20230519', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26825.0, self.close=26841.9, self.high=26950.0, self.low=26801.5, self.vol=28781.823, self.amt=773466674.8434 
2023-05-19 16:00:00,356:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684483199, self.tradeDate='20230519', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26825.0, self.close=26841.9, self.high=26950.0, self.low=26801.5, self.vol=28781.823, self.amt=773466674.8434 
2023-05-19 16:00:00,373:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230518   200000    235959  ...  145244.456  3.954902e+09 -0.011562
720  20230519   000000    035959  ...  200861.276  5.365861e+09 -0.013145
721  20230519   040000    075959  ...   58949.169  1.583234e+09  0.003368
722  20230519   080000    115959  ...   37542.604  1.006846e+09  0.000586
723  20230519   120000    155959  ...   28781.823  7.734667e+08  0.000630

[5 rows x 11 columns]
2023-05-19 16:00:01,978:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230518   200000    235959  1684425599  ...    719  0.382483 -0.670594    -1.0
720  20230519   000000    035959  1684439999  ...    720  0.277058 -1.246574    -1.0
721  20230519   040000    075959  1684454399  ...    721  0.281797 -1.193104    -1.0
722  20230519   080000    115959  1684468799  ...    722  0.298540 -1.075083    -1.0
723  20230519   120000    155959  1684483199  ...    723  0.342365 -0.811255    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '11751.32388329415', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26842.53585165', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


