# 20230809 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25120
self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29786.2, self.close=29765.3, self.high=29787.1, self.low=29760.0, self.vol=1040.66, self.amt=30981487.4316 
127.0.0.1 - - [09/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 16:20:05,977:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230809   155500    155959  ...         0.0        0.0       0
5952  20230809   160000    160459  ...         0.0        0.0       0
5953  20230809   160500    160959  ...         0.0        0.0       0
5954  20230809   161000    161459  ...         0.0        0.0       0
5955  20230809   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 16:20:05,998:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29786.2, self.close=29765.3, self.high=29787.1, self.low=29760.0, self.vol=1040.66, self.amt=30981487.4316, ukdf['pct'].iloc[-1]=-0.000698 , ukdf['amount'].iloc[-1]=30981487.4316, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40389.5778', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29765.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [09/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25121
self.closeSec=1691569499, self.tradeDate='20230809', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29765.2, self.close=29795.1, self.high=29795.1, self.low=29765.2, self.vol=552.723, self.amt=16459772.8183 
2023-08-09 16:25:00,848:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230809   160000    160459  ...         0.0        0.0       0
5953  20230809   160500    160959  ...         0.0        0.0       0
5954  20230809   161000    161459  ...         0.0        0.0       0
5955  20230809   161500    161959  ...         0.0        0.0       0
5956  20230809   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 16:25:00,848:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691569499, self.tradeDate='20230809', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29765.2, self.close=29795.1, self.high=29795.1, self.low=29765.2, self.vol=552.723, self.amt=16459772.8183, ukdf['pct'].iloc[-1]=0.001001 , ukdf['amount'].iloc[-1]=16459772.8183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-40696.08942319008', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29787.21002608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29786.2, self.close=29765.3, self.high=29787.1, self.low=29760.0 
127.0.0.1 - - [09/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 16:20:03,669:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29786.2, self.close=29765.3, self.high=29787.1, self.low=29760.0   
2023-08-09 16:20:04,938:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230809   155500    155959  1691567999  ...  29800.1  0.000094   1631    5
1632  20230809   160000    160459  1691568299  ...  29795.0 -0.000124   1632    0
1633  20230809   160500    160959  1691568599  ...  29798.9  0.000057   1633    1
1634  20230809   161000    161459  1691568899  ...  29786.1 -0.000664   1634    2
1635  20230809   161500    161959  1691569199  ...  29760.0 -0.000698   1635    3

[5 rows x 11 columns]
2023-08-09 16:20:04,948:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=235, self.factor=0.310469825679226, self.count=25123 

self.closeSec=1691569499, self.tradeDate='20230809', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29765.2, self.close=29795.1, self.high=29795.1, self.low=29765.2 
127.0.0.1 - - [09/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-09 16:25:00,798:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691569499, self.tradeDate='20230809', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29765.2, self.close=29795.1, self.high=29795.1, self.low=29765.2   
2023-08-09 16:25:00,820:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230809   160000    160459  1691568299  ...  29795.0 -0.000124   1632    0
1633  20230809   160500    160959  1691568599  ...  29798.9  0.000057   1633    1
1634  20230809   161000    161459  1691568899  ...  29786.1 -0.000664   1634    2
1635  20230809   161500    161959  1691569199  ...  29760.0 -0.000698   1635    3
1636  20230809   162000    162459  1691569499  ...  29765.2  0.001001   1636    4

[5 rows x 11 columns]
2023-08-09 16:25:00,820:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-09 16:00:16,740:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230809    132959  29749.3  ...  50.833333  0.578783  0.358508
5787  20230809    135959  29761.0  ...  50.416667  0.568731  0.367617
5788  20230809    142959  29724.9  ...  50.416667  0.551434  0.381081
5789  20230809    145959  29661.1  ...  50.833333  0.562318  0.392265
5790  20230809    152959  29712.2  ...  51.250000  0.575596  0.399685

[5 rows x 33 columns]
0.5313653136531366
acc is : 0.5313653136531366
2023-08-09 16:00:16,799:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.520352  0.479648       0  ...  0.969503   1.0    0.0  1.014156
538     0  0.502171  0.497829       0  ...  0.967419   1.0    0.0  1.011975
539     1  0.490977  0.509023       1  ...  0.969089   1.0    0.0  1.013722
540     0  0.521044  0.478956       1  ...  0.971199   1.0    0.0  1.015930
541     0  0.533522  0.466478       1  ...  0.972210   1.0    0.0  1.016987

[5 rows x 10 columns]
2023-08-09 16:00:16,810:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.520351  0.479649       0  ...  0.969503   1.0    0.0  1.015098
46     0  0.502049  0.497951       0  ...  0.967419   1.0    0.0  1.012155
47     1  0.490996  0.509004       1  ...  0.969089   1.0    0.0  1.014072
48     0  0.520933  0.479067       1  ...  0.971199   1.0    0.0  1.015687
49     0  0.533522  0.466478       1  ...  0.972210   1.0    0.0  1.016987

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.06', 'enterprice': '29131.5', 'countrevence': '0', 'unrealprofit': '16250.124', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29806.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230809   155000    155959  1691567999  29798.2  29807.9  0.000326
2023-08-09 16:00:02,160:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12560 

self.closeSec=1691568599, self.tradeDate='20230809', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29807.8', self.close='29806'
2023-08-09 16:10:01,158:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691568599, self.tradeDate='20230809', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29807.8', self.close='29806'
127.0.0.1 - - [09/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-09 16:10:01,165:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230809   152000    152959  1691566199    29745  29776.9  0.001072
525  20230809   153000    153959  1691566799    29777    29786  0.000306
526  20230809   154000    154959  1691567399    29786  29798.2  0.000410
527  20230809   155000    155959  1691567999  29798.2  29807.9  0.000326
528  20230809   160000    160959  1691568599  29807.8    29806 -0.000064
2023-08-09 16:10:01,165:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12561 

self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29806', self.close='29765.2'
127.0.0.1 - - [09/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 16:20:06,337:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29806', self.close='29765.2'
2023-08-09 16:20:06,798:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230809   153000    153959  1691566799    29777    29786  0.000306
526  20230809   154000    154959  1691567399    29786  29798.2  0.000410
527  20230809   155000    155959  1691567999  29798.2  29807.9  0.000326
528  20230809   160000    160959  1691568599  29807.8    29806 -0.000064
529  20230809   161000    161959  1691569199    29806  29765.2 -0.001369
2023-08-09 16:20:06,807:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230809   155000    155959  1691567999  29798.2  29807.9
2023-08-09 16:00:02,172:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12563 

self.closeSec=1691568599, self.tradeDate='20230809', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29807.8', self.close='29806'
2023-08-09 16:10:01,161:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691568599, self.tradeDate='20230809', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29807.8', self.close='29806'
127.0.0.1 - - [09/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-09 16:10:01,171:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230809   152000    152959  1691566199    29745  29776.9
17517  20230809   153000    153959  1691566799    29777    29786
17518  20230809   154000    154959  1691567399    29786  29798.2
17519  20230809   155000    155959  1691567999  29798.2  29807.9
17520  20230809   160000    160959  1691568599  29807.8    29806
2023-08-09 16:10:01,171:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12564 

self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29806', self.close='29765.2'
127.0.0.1 - - [09/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 16:20:07,990:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29806', self.close='29765.2'
2023-08-09 16:20:08,079:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230809   153000    153959  1691566799    29777    29786
17518  20230809   154000    154959  1691567399    29786  29798.2
17519  20230809   155000    155959  1691567999  29798.2  29807.9
17520  20230809   160000    160959  1691568599  29807.8    29806
17521  20230809   161000    161959  1691569199    29806  29765.2
2023-08-09 16:20:08,079:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230809   155000    155959  1691567999  29798.2  29807.9
2023-08-09 16:00:02,161:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [09/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12563 

self.closeSec=1691568599, self.tradeDate='20230809', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29807.8', self.close='29806'
2023-08-09 16:10:01,172:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691568599, self.tradeDate='20230809', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29807.8', self.close='29806'
2023-08-09 16:10:01,181:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230809   152000    152959  1691566199    29745  29776.9
12189  20230809   153000    153959  1691566799    29777    29786
12190  20230809   154000    154959  1691567399    29786  29798.2
12191  20230809   155000    155959  1691567999  29798.2  29807.9
12192  20230809   160000    160959  1691568599  29807.8    29806
2023-08-09 16:10:01,181:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12564 

self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29806', self.close='29765.2'
127.0.0.1 - - [09/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-09 16:20:07,791:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29806', self.close='29765.2'
2023-08-09 16:20:07,957:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230809   153000    153959  1691566799    29777    29786
12190  20230809   154000    154959  1691567399    29786  29798.2
12191  20230809   155000    155959  1691567999  29798.2  29807.9
12192  20230809   160000    160959  1691568599  29807.8    29806
12193  20230809   161000    161959  1691569199    29806  29765.2
2023-08-09 16:20:07,959:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25120
self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29786.2, self.close=29765.3, self.high=29787.1, self.low=29760.0, self.vol=1040.66, self.amt=30981487.4316 
127.0.0.1 - - [09/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-09 16:20:05,828:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230809   155500    155959  ...         0.0        0.0       0
5952  20230809   160000    160459  ...         0.0        0.0       0
5953  20230809   160500    160959  ...         0.0        0.0       0
5954  20230809   161000    161459  ...         0.0        0.0       0
5955  20230809   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 16:20:05,847:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691569199, self.tradeDate='20230809', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29786.2, self.close=29765.3, self.high=29787.1, self.low=29760.0, self.vol=1040.66, self.amt=30981487.4316, ukdf['pct'].iloc[-1]=-0.000698 , ukdf['amount'].iloc[-1]=30981487.4316, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '108496.2892', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29765.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [09/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25121
self.closeSec=1691569499, self.tradeDate='20230809', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29765.2, self.close=29795.1, self.high=29795.1, self.low=29765.2, self.vol=552.723, self.amt=16459772.8183 
2023-08-09 16:25:00,838:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230809   160000    160459  ...         0.0        0.0       0
5953  20230809   160500    160959  ...         0.0        0.0       0
5954  20230809   161000    161459  ...         0.0        0.0       0
5955  20230809   161500    161959  ...         0.0        0.0       0
5956  20230809   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-09 16:25:00,838:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691569499, self.tradeDate='20230809', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29765.2, self.close=29795.1, self.high=29795.1, self.low=29765.2, self.vol=552.723, self.amt=16459772.8183, ukdf['pct'].iloc[-1]=0.001001 , ukdf['amount'].iloc[-1]=16459772.8183, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '109313.76357863728', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29787.21002608', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230809   040000    075959  1691539199  ...    721  1.132475  3.295378     1.0
722  20230809   080000    115959  1691553599  ...    722  1.254265  3.491010     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-9066.7234', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29708.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=523
self.closeSec=1691567999, self.tradeDate='20230809', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29710.0, self.close=29807.9, self.high=29809.8, self.low=29650.0, self.vol=33679.663, self.amt=1001344786.5102 
127.0.0.1 - - [09/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-08-09 16:00:01,747:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691567999, self.tradeDate='20230809', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29710.0, self.close=29807.9, self.high=29809.8, self.low=29650.0, self.vol=33679.663, self.amt=1001344786.5102 
2023-08-09 16:00:01,762:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230808   200000    235959  ...  130655.635  3.852245e+09  0.003041
720  20230809   000000    035959  ...  136364.608  4.060005e+09  0.011847
721  20230809   040000    075959  ...   94730.676  2.834461e+09 -0.003623
722  20230809   080000    115959  ...   44098.378  1.311623e+09 -0.001647
723  20230809   120000    155959  ...   33679.663  1.001345e+09  0.003295

[5 rows x 11 columns]
2023-08-09 16:00:02,494:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230808   200000    235959  1691510399  ...    719  0.146329 -0.768183    -1.0
720  20230809   000000    035959  1691524799  ...    720  0.525217  0.887531     1.0
721  20230809   040000    075959  1691539199  ...    721  1.132475  3.295378     1.0
722  20230809   080000    115959  1691553599  ...    722  1.254265  3.491010     1.0
723  20230809   120000    155959  1691567999  ...    723  1.152400  2.924316     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-3977.6261', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29807.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


