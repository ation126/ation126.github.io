# 20230810 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25408
self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29499.5, self.close=29489.4, self.high=29500.7, self.low=29482.1, self.vol=456.51, self.amt=13462498.7298 
127.0.0.1 - - [10/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 16:20:05,806:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230810   155500    155959  ...         0.0        0.0       0
5952  20230810   160000    160459  ...         0.0        0.0       0
5953  20230810   160500    160959  ...         0.0        0.0       0
5954  20230810   161000    161459  ...         0.0        0.0       0
5955  20230810   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 16:20:05,825:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29499.5, self.close=29489.4, self.high=29500.7, self.low=29482.1, self.vol=456.51, self.amt=13462498.7298, ukdf['pct'].iloc[-1]=-0.000264 , ukdf['amount'].iloc[-1]=13462498.7298, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36555.75', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29489.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [10/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=25409
self.closeSec=1691655899, self.tradeDate='20230810', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29489.5, self.close=29497.5, self.high=29501.9, self.low=29489.4, self.vol=359.611, self.amt=10607327.5286 
2023-08-10 16:25:00,837:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230810   160000    160459  ...         0.0        0.0       0
5953  20230810   160500    160959  ...         0.0        0.0       0
5954  20230810   161000    161459  ...         0.0        0.0       0
5955  20230810   161500    161959  ...         0.0        0.0       0
5956  20230810   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 16:25:00,838:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1691655899, self.tradeDate='20230810', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29489.5, self.close=29497.5, self.high=29501.9, self.low=29489.4, self.vol=359.611, self.amt=10607327.5286, ukdf['pct'].iloc[-1]=0.000275 , ukdf['amount'].iloc[-1]=10607327.5286, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36671.67803270334', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29498.22457509', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29499.5, self.close=29489.4, self.high=29500.7, self.low=29482.1 
127.0.0.1 - - [10/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 16:20:04,083:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29499.5, self.close=29489.4, self.high=29500.7, self.low=29482.1   
2023-08-10 16:20:05,135:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230810   155500    155959  1691654399  ...  29485.0  0.000583   1631    5
1632  20230810   160000    160459  1691654699  ...  29502.0  0.000346   1632    0
1633  20230810   160500    160959  1691654999  ...  29509.3 -0.000163   1633    1
1634  20230810   161000    161459  1691655299  ...  29495.6 -0.000413   1634    2
1635  20230810   161500    161959  1691655599  ...  29482.1 -0.000264   1635    3

[5 rows x 11 columns]
2023-08-10 16:20:05,135:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [10/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.600541132586876, self.count=25411 

self.closeSec=1691655899, self.tradeDate='20230810', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29489.5, self.close=29497.5, self.high=29501.9, self.low=29489.4 
2023-08-10 16:25:00,819:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1691655899, self.tradeDate='20230810', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29489.5, self.close=29497.5, self.high=29501.9, self.low=29489.4   
2023-08-10 16:25:00,839:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230810   160000    160459  1691654699  ...  29502.0  0.000346   1632    0
1633  20230810   160500    160959  1691654999  ...  29509.3 -0.000163   1633    1
1634  20230810   161000    161459  1691655299  ...  29495.6 -0.000413   1634    2
1635  20230810   161500    161959  1691655599  ...  29482.1 -0.000264   1635    3
1636  20230810   162000    162459  1691655899  ...  29489.4  0.000275   1636    4

[5 rows x 11 columns]
2023-08-10 16:25:00,839:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-10 16:00:19,097:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230810    132959  29530.3  ...  50.833333  0.487215  0.732985
5787  20230810    135959  29510.5  ...  50.833333  0.504757  0.732302
5788  20230810    142959  29580.4  ...  50.833333  0.492587  0.735846
5789  20230810    145959  29531.0  ...  50.833333  0.485932  0.741480
5790  20230810    152959  29503.4  ...  51.250000  0.498625  0.742465

[5 rows x 33 columns]
0.5276752767527675
acc is : 0.5276752767527675
2023-08-10 16:00:19,164:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.492594  0.507406       1  ...  0.958136  -1.0    0.0  1.008297
538     0  0.519959  0.480041       0  ...  0.959736  -1.0    0.0  1.006613
539     1  0.484830  0.515170       0  ...  0.960630  -1.0    0.0  1.005675
540     1  0.491965  0.508035       1  ...  0.958986  -1.0    0.0  1.007397
541     0  0.513518  0.486482       0  ...  0.960608  -1.0    0.0  1.005692

[5 rows x 10 columns]
2023-08-10 16:00:19,176:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.492202  0.507798       1  ...  0.958136  -1.0    0.0  1.008152
46     0  0.519588  0.480412       0  ...  0.959736  -1.0    0.0  1.006469
47     1  0.484783  0.515217       0  ...  0.960630  -1.0    0.0  1.005603
48     1  0.492020  0.507980       1  ...  0.958986  -1.0    0.0  1.008002
49     0  0.513518  0.486482       0  ...  0.960608  -1.0    0.0  1.005692

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.049', 'enterprice': '29479.7', 'countrevence': '0', 'unrealprofit': '-538.6976', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29502.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230810   155000    155959  1691654399    29486    29504  0.000610
2023-08-10 16:00:02,128:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [10/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12704 

self.closeSec=1691654999, self.tradeDate='20230810', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29504', self.close='29509.4'
2023-08-10 16:10:01,148:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691654999, self.tradeDate='20230810', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29504', self.close='29509.4'
2023-08-10 16:10:01,158:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230810   152000    152959  1691652599  29551.6    29554  0.000081
525  20230810   153000    153959  1691653199    29554  29509.3 -0.001512
526  20230810   154000    154959  1691653799  29509.2    29486 -0.000790
527  20230810   155000    155959  1691654399    29486    29504  0.000610
528  20230810   160000    160959  1691654999    29504  29509.4  0.000183
2023-08-10 16:10:01,159:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12705 

self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29509.3', self.close='29489.4'
127.0.0.1 - - [10/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 16:20:06,235:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29509.3', self.close='29489.4'
2023-08-10 16:20:06,724:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230810   153000    153959  1691653199    29554  29509.3 -0.001512
526  20230810   154000    154959  1691653799  29509.2    29486 -0.000790
527  20230810   155000    155959  1691654399    29486    29504  0.000610
528  20230810   160000    160959  1691654999    29504  29509.4  0.000183
529  20230810   161000    161959  1691655599  29509.3  29489.4 -0.000678
2023-08-10 16:20:06,725:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230810   155000    155959  1691654399    29486    29504
2023-08-10 16:00:02,080:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12707 

self.closeSec=1691654999, self.tradeDate='20230810', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29504', self.close='29509.4'
2023-08-10 16:10:01,151:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691654999, self.tradeDate='20230810', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29504', self.close='29509.4'
2023-08-10 16:10:01,157:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230810   152000    152959  1691652599  29551.6    29554
17517  20230810   153000    153959  1691653199    29554  29509.3
17518  20230810   154000    154959  1691653799  29509.2    29486
17519  20230810   155000    155959  1691654399    29486    29504
17520  20230810   160000    160959  1691654999    29504  29509.4
2023-08-10 16:10:01,157:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [10/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12708 

self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29509.3', self.close='29489.4'
127.0.0.1 - - [10/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 16:20:07,596:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29509.3', self.close='29489.4'
2023-08-10 16:20:07,663:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230810   153000    153959  1691653199    29554  29509.3
17518  20230810   154000    154959  1691653799  29509.2    29486
17519  20230810   155000    155959  1691654399    29486    29504
17520  20230810   160000    160959  1691654999    29504  29509.4
17521  20230810   161000    161959  1691655599  29509.3  29489.4
2023-08-10 16:20:07,663:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230810   155000    155959  1691654399    29486    29504
2023-08-10 16:00:02,128:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12707 

self.closeSec=1691654999, self.tradeDate='20230810', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29504', self.close='29509.4'
2023-08-10 16:10:01,143:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691654999, self.tradeDate='20230810', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29504', self.close='29509.4'
2023-08-10 16:10:01,163:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230810   152000    152959  1691652599  29551.6    29554
12189  20230810   153000    153959  1691653199    29554  29509.3
12190  20230810   154000    154959  1691653799  29509.2    29486
12191  20230810   155000    155959  1691654399    29486    29504
12192  20230810   160000    160959  1691654999    29504  29509.4
2023-08-10 16:10:01,163:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=12708 

self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29509.3', self.close='29489.4'
127.0.0.1 - - [10/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-10 16:20:07,457:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29509.3', self.close='29489.4'
2023-08-10 16:20:07,584:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230810   153000    153959  1691653199    29554  29509.3
12190  20230810   154000    154959  1691653799  29509.2    29486
12191  20230810   155000    155959  1691654399    29486    29504
12192  20230810   160000    160959  1691654999    29504  29509.4
12193  20230810   161000    161959  1691655599  29509.3  29489.4
2023-08-10 16:20:07,585:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25408
self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29499.5, self.close=29489.4, self.high=29500.7, self.low=29482.1, self.vol=456.51, self.amt=13462498.7298 
127.0.0.1 - - [10/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-10 16:20:05,815:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230810   155500    155959  ...         0.0        0.0       0
5952  20230810   160000    160459  ...         0.0        0.0       0
5953  20230810   160500    160959  ...         0.0        0.0       0
5954  20230810   161000    161459  ...         0.0        0.0       0
5955  20230810   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 16:20:05,835:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691655599, self.tradeDate='20230810', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29499.5, self.close=29489.4, self.high=29500.7, self.low=29482.1, self.vol=456.51, self.amt=13462498.7298, ukdf['pct'].iloc[-1]=-0.000264 , ukdf['amount'].iloc[-1]=13462498.7298, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '98271.3719', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29489.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [10/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=25409
self.closeSec=1691655899, self.tradeDate='20230810', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29489.5, self.close=29497.5, self.high=29501.9, self.low=29489.4, self.vol=359.611, self.amt=10607327.5286 
2023-08-10 16:25:00,849:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230810   160000    160459  ...         0.0        0.0       0
5953  20230810   160500    160959  ...         0.0        0.0       0
5954  20230810   161000    161459  ...         0.0        0.0       0
5955  20230810   161500    161959  ...         0.0        0.0       0
5956  20230810   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-10 16:25:00,849:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1691655899, self.tradeDate='20230810', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29489.5, self.close=29497.5, self.high=29501.9, self.low=29489.4, self.vol=359.611, self.amt=10607327.5286, ukdf['pct'].iloc[-1]=0.000275 , ukdf['amount'].iloc[-1]=10607327.5286, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '98580.55494341769', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29498.22457509', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230810   040000    075959  1691625599  ...    721  1.191976  2.528315     1.0
722  20230810   080000    115959  1691639999  ...    722  1.098015  2.162763     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-16178.0808', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29570', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
127.0.0.1 - - [10/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1536223.8092292, self.flagDict['side']='buy', self.tradeCount=19, self.count=529
self.closeSec=1691654399, self.tradeDate='20230810', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29568.9, self.close=29504.0, self.high=29613.2, self.low=29477.2, self.vol=26122.949, self.amt=771555622.5106 
2023-08-10 16:00:01,597:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1691654399, self.tradeDate='20230810', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29568.9, self.close=29504.0, self.high=29613.2, self.low=29477.2, self.vol=26122.949, self.amt=771555622.5106 
2023-08-10 16:00:01,615:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230809   200000    235959  ...  112574.075  3.364375e+09 -0.004274
720  20230810   000000    035959  ...   94943.349  2.804365e+09 -0.011604
721  20230810   040000    075959  ...   37603.980  1.109496e+09  0.005734
722  20230810   080000    115959  ...   26398.656  7.812642e+08 -0.000128
723  20230810   120000    155959  ...   26122.949  7.715556e+08 -0.002198

[5 rows x 11 columns]
2023-08-10 16:00:02,344:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230809   200000    235959  1691596799  ...    719  1.205164  2.821489     1.0
720  20230810   000000    035959  1691611199  ...    720  1.211631  2.705132     1.0
721  20230810   040000    075959  1691625599  ...    721  1.191976  2.528315     1.0
722  20230810   080000    115959  1691639999  ...    722  1.098015  2.162763     1.0
723  20230810   120000    155959  1691654399  ...    723  1.035430  1.920660     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.457', 'enterprice': '29884.4', 'countrevence': '0', 'unrealprofit': '-19574.2428', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29504', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


