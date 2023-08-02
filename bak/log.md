# 20230802 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23104
self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29498.3, self.close=29418.1, self.high=29500.0, self.low=29360.0, self.vol=10696.568, self.amt=314812060.7824 
127.0.0.1 - - [02/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 16:20:06,073:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230802   155500    155959  ...         0.0        0.0       0
5952  20230802   160000    160459  ...         0.0        0.0       0
5953  20230802   160500    160959  ...         0.0        0.0       0
5954  20230802   161000    161459  ...         0.0        0.0       0
5955  20230802   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 16:20:06,084:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29498.3, self.close=29418.1, self.high=29500.0, self.low=29360.0, self.vol=10696.568, self.amt=314812060.7824, ukdf['pct'].iloc[-1]=-0.002719 , ukdf['amount'].iloc[-1]=314812060.7824, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-35760.5754', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29432.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=23105
self.closeSec=1690964699, self.tradeDate='20230802', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29418.1, self.close=29454.9, self.high=29462.4, self.low=29390.0, self.vol=4363.442, self.amt=128413621.7301 
127.0.0.1 - - [02/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
2023-08-02 16:25:00,785:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230802   160000    160459  ...         0.0        0.0       0
5953  20230802   160500    160959  ...         0.0        0.0       0
5954  20230802   161000    161459  ...         0.0        0.0       0
5955  20230802   161500    161959  ...         0.0        0.0       0
5956  20230802   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 16:25:00,785:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690964699, self.tradeDate='20230802', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29418.1, self.close=29454.9, self.high=29462.4, self.low=29390.0, self.vol=4363.442, self.amt=128413621.7301, ukdf['pct'].iloc[-1]=0.001251 , ukdf['amount'].iloc[-1]=128413621.7301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-36097.5846', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29457', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29498.3, self.close=29418.1, self.high=29500.0, self.low=29360.0 
127.0.0.1 - - [02/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 16:20:04,199:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29498.3, self.close=29418.1, self.high=29500.0, self.low=29360.0   
2023-08-02 16:20:05,419:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230802   155500    155959  1690963199  ...  29555.5 -0.000352   1631    5
1632  20230802   160000    160459  1690963499  ...  29527.7 -0.000243   1632    0
1633  20230802   160500    160959  1690963799  ...  29525.0 -0.001194   1633    1
1634  20230802   161000    161459  1690964099  ...  29480.0 -0.000996   1634    2
1635  20230802   161500    161959  1690964399  ...  29360.0 -0.002719   1635    3

[5 rows x 11 columns]
2023-08-02 16:20:05,428:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=22, self.factor=0.4239284962427928, self.count=23107 

self.closeSec=1690964699, self.tradeDate='20230802', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29418.1, self.close=29454.9, self.high=29462.4, self.low=29390.0 
2023-08-02 16:25:00,758:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690964699, self.tradeDate='20230802', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29418.1, self.close=29454.9, self.high=29462.4, self.low=29390.0   
2023-08-02 16:25:00,779:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230802   160000    160459  1690963499  ...  29527.7 -0.000243   1632    0
1633  20230802   160500    160959  1690963799  ...  29525.0 -0.001194   1633    1
1634  20230802   161000    161459  1690964099  ...  29480.0 -0.000996   1634    2
1635  20230802   161500    161959  1690964399  ...  29360.0 -0.002719   1635    3
1636  20230802   162000    162459  1690964699  ...  29390.0  0.001251   1636    4

[5 rows x 11 columns]
2023-08-02 16:25:00,779:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-08-02 16:00:18,835:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230802    132959  29667.3  ...  45.833333  0.570206  0.265285
5787  20230802    135959  29606.9  ...  46.250000  0.576841  0.265914
5788  20230802    142959  29645.1  ...  45.833333  0.575232  0.266801
5789  20230802    145959  29638.3  ...  45.416667  0.555249  0.271426
5790  20230802    152959  29552.3  ...  45.416667  0.567010  0.272834

[5 rows x 33 columns]
0.5535055350553506
acc is : 0.5535055350553506
2023-08-02 16:00:18,910:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.467148  0.532852       1  ...  0.966723  -1.0    0.0  0.989202
538     1  0.497296  0.502704       0  ...  0.966945  -1.0    0.0  0.988975
539     1  0.494198  0.505802       0  ...  0.969751  -1.0    0.0  0.986106
540     1  0.467511  0.532489       1  ...  0.967588  -1.0    0.0  0.988304
541     0  0.506619  0.493381       0  ...  0.969160  -1.0    0.0  0.986699

[5 rows x 10 columns]
2023-08-02 16:00:18,922:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.467231  0.532769       1  ...  0.966723  -1.0    0.0  0.991130
46     1  0.497517  0.502483       0  ...  0.966945  -1.0    0.0  0.990717
47     1  0.494618  0.505382       0  ...  0.969751  -1.0    0.0  0.988652
48     1  0.467735  0.532265       1  ...  0.967588  -1.0    0.0  0.989913
49     0  0.506619  0.493381       0  ...  0.969160  -1.0    0.0  0.986699

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.243', 'enterprice': '29666', 'countrevence': '0', 'unrealprofit': '2428.96833734654', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29561.49678022', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230802   155000    155959  1690963199  29604.9  29570.1 -0.001175
2023-08-02 16:00:02,103:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [02/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11552 

self.closeSec=1690963799, self.tradeDate='20230802', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29570.2', self.close='29527.7'
2023-08-02 16:10:01,134:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690963799, self.tradeDate='20230802', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29570.2', self.close='29527.7'
2023-08-02 16:10:01,143:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230802   152000    152959  1690961399  29638.6  29618.2 -0.000685
525  20230802   153000    153959  1690961999  29618.2  29614.9 -0.000111
526  20230802   154000    154959  1690962599    29615  29604.9 -0.000338
527  20230802   155000    155959  1690963199  29604.9  29570.1 -0.001175
528  20230802   160000    160959  1690963799  29570.2  29527.7 -0.001434
2023-08-02 16:10:01,143:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11553 

self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29527.7', self.close='29418'
127.0.0.1 - - [02/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 16:20:06,532:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29527.7', self.close='29418'
2023-08-02 16:20:07,025:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230802   153000    153959  1690961999  29618.2  29614.9 -0.000111
526  20230802   154000    154959  1690962599    29615  29604.9 -0.000338
527  20230802   155000    155959  1690963199  29604.9  29570.1 -0.001175
528  20230802   160000    160959  1690963799  29570.2  29527.7 -0.001434
529  20230802   161000    161959  1690964399  29527.7    29418 -0.003715
2023-08-02 16:20:07,032:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230802   155000    155959  1690963199  29604.9  29570.1
2023-08-02 16:00:02,111:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11555 

self.closeSec=1690963799, self.tradeDate='20230802', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29570.2', self.close='29527.7'
127.0.0.1 - - [02/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-02 16:10:01,138:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690963799, self.tradeDate='20230802', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29570.2', self.close='29527.7'
2023-08-02 16:10:01,144:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230802   152000    152959  1690961399  29638.6  29618.2
17517  20230802   153000    153959  1690961999  29618.2  29614.9
17518  20230802   154000    154959  1690962599    29615  29604.9
17519  20230802   155000    155959  1690963199  29604.9  29570.1
17520  20230802   160000    160959  1690963799  29570.2  29527.7
2023-08-02 16:10:01,144:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11556 

self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29527.7', self.close='29418'
127.0.0.1 - - [02/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 16:20:07,826:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29527.7', self.close='29418'
2023-08-02 16:20:07,909:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230802   153000    153959  1690961999  29618.2  29614.9
17518  20230802   154000    154959  1690962599    29615  29604.9
17519  20230802   155000    155959  1690963199  29604.9  29570.1
17520  20230802   160000    160959  1690963799  29570.2  29527.7
17521  20230802   161000    161959  1690964399  29527.7    29418
2023-08-02 16:20:07,909:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230802   155000    155959  1690963199  29604.9  29570.1
2023-08-02 16:00:02,118:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11555 

self.closeSec=1690963799, self.tradeDate='20230802', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29570.2', self.close='29527.7'
2023-08-02 16:10:01,144:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690963799, self.tradeDate='20230802', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29570.2', self.close='29527.7'
127.0.0.1 - - [02/Aug/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-08-02 16:10:01,150:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230802   152000    152959  1690961399  29638.6  29618.2
12189  20230802   153000    153959  1690961999  29618.2  29614.9
12190  20230802   154000    154959  1690962599    29615  29604.9
12191  20230802   155000    155959  1690963199  29604.9  29570.1
12192  20230802   160000    160959  1690963799  29570.2  29527.7
2023-08-02 16:10:01,151:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=11556 

self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29527.7', self.close='29418'
127.0.0.1 - - [02/Aug/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-08-02 16:20:07,664:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29527.7', self.close='29418'
2023-08-02 16:20:07,828:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230802   153000    153959  1690961999  29618.2  29614.9
12190  20230802   154000    154959  1690962599    29615  29604.9
12191  20230802   155000    155959  1690963199  29604.9  29570.1
12192  20230802   160000    160959  1690963799  29570.2  29527.7
12193  20230802   161000    161959  1690964399  29527.7    29418
2023-08-02 16:20:07,828:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23104
self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29498.3, self.close=29418.1, self.high=29500.0, self.low=29360.0, self.vol=10696.568, self.amt=314812060.7824 
127.0.0.1 - - [02/Aug/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-08-02 16:20:05,998:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230802   155500    155959  ...         0.0        0.0       0
5952  20230802   160000    160459  ...         0.0        0.0       0
5953  20230802   160500    160959  ...         0.0        0.0       0
5954  20230802   161000    161459  ...         0.0        0.0       0
5955  20230802   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 16:20:06,017:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690964399, self.tradeDate='20230802', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29498.3, self.close=29418.1, self.high=29500.0, self.low=29360.0, self.vol=10696.568, self.amt=314812060.7824, ukdf['pct'].iloc[-1]=-0.002719 , ukdf['amount'].iloc[-1]=314812060.7824, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '96150.6208', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29432.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [02/Aug/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=23105
self.closeSec=1690964699, self.tradeDate='20230802', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29418.1, self.close=29454.9, self.high=29462.4, self.low=29390.0, self.vol=4363.442, self.amt=128413621.7301 
2023-08-02 16:25:00,791:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230802   160000    160459  ...         0.0        0.0       0
5953  20230802   160500    160959  ...         0.0        0.0       0
5954  20230802   161000    161459  ...         0.0        0.0       0
5955  20230802   161500    161959  ...         0.0        0.0       0
5956  20230802   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-08-02 16:25:00,792:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690964699, self.tradeDate='20230802', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29418.1, self.close=29454.9, self.high=29462.4, self.low=29390.0, self.vol=4363.442, self.amt=128413621.7301, ukdf['pct'].iloc[-1]=0.001251 , ukdf['amount'].iloc[-1]=128413621.7301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '97049.433', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29457', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230802   040000    075959  1690934399  ...    721  0.106051 -0.705412    -1.0
722  20230802   080000    115959  1690948799  ...    722  0.232552 -0.054862     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-20281.44024385104', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29623.41537546', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [02/Aug/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1578513.8580480001, self.flagDict['side']='sell', self.tradeCount=16, self.count=481
self.closeSec=1690963199, self.tradeDate='20230802', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29622.5, self.close=29570.1, self.high=29719.5, self.low=29550.0, self.vol=45298.47, self.amt=1341809983.6361 
2023-08-02 16:00:01,664:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690963199, self.tradeDate='20230802', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29622.5, self.close=29570.1, self.high=29719.5, self.low=29550.0, self.vol=45298.47, self.amt=1341809983.6361 
2023-08-02 16:00:01,682:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230801   200000    235959  ...   92928.505  2.677332e+09  0.003133
720  20230802   000000    035959  ...   98360.420  2.861812e+09  0.011060
721  20230802   040000    075959  ...   97454.977  2.867119e+09  0.014957
722  20230802   080000    115959  ...  133633.098  3.982644e+09 -0.002650
723  20230802   120000    155959  ...   45298.470  1.341810e+09 -0.001769

[5 rows x 11 columns]
2023-08-02 16:00:02,466:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230801   200000    235959  1690905599  ...    719  0.160942 -0.470313     NaN
720  20230802   000000    035959  1690919999  ...    720  0.128275 -0.612325    -1.0
721  20230802   040000    075959  1690934399  ...    721  0.106051 -0.705412    -1.0
722  20230802   080000    115959  1690948799  ...    722  0.232552 -0.054862     NaN
723  20230802   120000    155959  1690963199  ...    723  0.275701  0.170171     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.024', 'enterprice': '29248', 'countrevence': '0', 'unrealprofit': '-17406.5328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29570.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1


