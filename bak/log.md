# 20230324 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33724
self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28173.0, self.close=28159.9, self.high=28178.0, self.low=28140.8, self.vol=1294.42, self.amt=36445724.9561 
127.0.0.1 - - [24/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-24 16:20:09,507:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230324   155500    155959  ...         0.0        0.0       0
5952  20230324   160000    160459  ...         0.0        0.0       0
5953  20230324   160500    160959  ...         0.0        0.0       0
5954  20230324   161000    161459  ...         0.0        0.0       0
5955  20230324   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 16:20:09,518:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28173.0, self.close=28159.9, self.high=28178.0, self.low=28140.8, self.vol=1294.42, self.amt=36445724.9561, ukdf['pct'].iloc[-1]=-0.000465 , ukdf['amount'].iloc[-1]=36445724.9561, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-699882.9856', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28159.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=993672.4896432, self.flagDict['side']='sell', self.tradeCount=2, self.count=33725
self.closeSec=1679646299, self.tradeDate='20230324', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28159.9, self.close=28207.7, self.high=28212.4, self.low=28158.8, self.vol=1684.187, self.amt=47472062.4669 
127.0.0.1 - - [24/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-03-24 16:25:01,878:INFO:amihud:main.py:172:handleKline:200676: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230324   160000    160459  ...         0.0        0.0       0
5953  20230324   160500    160959  ...         0.0        0.0       0
5954  20230324   161000    161459  ...         0.0        0.0       0
5955  20230324   161500    161959  ...         0.0        0.0       0
5956  20230324   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 16:25:01,879:INFO:amihud:main.py:175:handleKline:200676: self.closeSec=1679646299, self.tradeDate='20230324', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28159.9, self.close=28207.7, self.high=28212.4, self.low=28158.8, self.vol=1684.187, self.amt=47472062.4669, ukdf['pct'].iloc[-1]=0.001697 , ukdf['amount'].iloc[-1]=47472062.4669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '60.176', 'enterprice': '16529.3', 'countrevence': '0', 'unrealprofit': '-702608.9584', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28205.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28173.0, self.close=28159.9, self.high=28178.0, self.low=28140.8 
127.0.0.1 - - [24/Mar/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-03-24 16:20:07,698:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28173.0, self.close=28159.9, self.high=28178.0, self.low=28140.8   
2023-03-24 16:20:08,838:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230324   155500    155959  1679644799  ...  28258.0 -0.000905   1631    5
1632  20230324   160000    160459  1679645099  ...  28269.9  0.000308   1632    0
1633  20230324   160500    160959  1679645399  ...  28113.2 -0.005764   1633    1
1634  20230324   161000    161459  1679645699  ...  28111.0  0.002042   1634    2
1635  20230324   161500    161959  1679645999  ...  28140.8 -0.000465   1635    3

[5 rows x 11 columns]
2023-03-24 16:20:08,847:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [24/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=332, self.factor=0.38227753765540307, self.count=34291 

self.closeSec=1679646299, self.tradeDate='20230324', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28159.9, self.close=28207.7, self.high=28212.4, self.low=28158.8 
2023-03-24 16:25:01,793:INFO:factorcheck2:main.py:126:handleKline:185239: self.closeSec=1679646299, self.tradeDate='20230324', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28159.9, self.close=28207.7, self.high=28212.4, self.low=28158.8   
2023-03-24 16:25:01,863:INFO:factorcheck2:main.py:127:handleKline:185239: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230324   160000    160459  1679645099  ...  28269.9  0.000308   1632    0
1633  20230324   160500    160959  1679645399  ...  28113.2 -0.005764   1633    1
1634  20230324   161000    161459  1679645699  ...  28111.0  0.002042   1634    2
1635  20230324   161500    161959  1679645999  ...  28140.8 -0.000465   1635    3
1636  20230324   162000    162459  1679646299  ...  28158.8  0.001697   1636    4

[5 rows x 11 columns]
2023-03-24 16:25:01,863:INFO:factorcheck2:main.py:128:handleKline:185239: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-03-24 16:00:35,016:DEBUG:logic:main.py:463:getModel:885513: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230324    132959  28119.9  ...  52.083333  0.527885  0.384626
5787  20230324    135959  28219.9  ...  52.500000  0.532805  0.381263
5788  20230324    142959  28272.3  ...  52.916667  0.537703  0.375819
5789  20230324    145959  28324.6  ...  52.916667  0.529606  0.374031
5790  20230324    152959  28250.0  ...  52.500000  0.524090  0.374619

[5 rows x 33 columns]
0.5479704797047971
acc is : 0.5479704797047971
2023-03-24 16:00:35,192:INFO:logic:main.py:468:getModel:885513: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.554478  0.445522       1  ...  1.125037   1.0    0.0  1.260096
538     0  0.539387  0.460613       1  ...  1.127114   1.0    0.0  1.262423
539     0  0.544706  0.455294       0  ...  1.124145   1.0    0.0  1.259098
540     0  0.502984  0.497016       0  ...  1.122112   1.0    0.0  1.256820
541     0  0.511082  0.488918       1  ...  1.124937   1.0    0.0  1.259985

[5 rows x 10 columns]
2023-03-24 16:00:35,232:INFO:logic:main.py:478:getModel:885513: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.556796  0.443204       1  ...  1.192253   1.0    0.0  1.303212
46     0  0.540029  0.459971       1  ...  1.218785   1.0    0.0  1.296659
47     0  0.544540  0.455460       0  ...  1.205151   1.0    0.0  1.284897
48     0  0.503255  0.496745       0  ...  1.187273   1.0    0.0  1.275489
49     0  0.511082  0.488918       1  ...  1.124937   1.0    0.0  1.259985

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230324   155000    155959  1679644799  28292.2  28269.9 -0.000785
2023-03-24 16:00:02,016:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17144 

self.closeSec=1679645399, self.tradeDate='20230324', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28270', self.close='28115.6'
2023-03-24 16:10:01,614:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679645399, self.tradeDate='20230324', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28270', self.close='28115.6'
127.0.0.1 - - [24/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-24 16:10:01,669:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230324   152000    152959  1679642999  28233.5  28198.9 -0.001222
525  20230324   153000    153959  1679643599  28198.8  28246.1  0.001674
526  20230324   154000    154959  1679644199    28246  28292.1  0.001629
527  20230324   155000    155959  1679644799  28292.2  28269.9 -0.000785
528  20230324   160000    160959  1679645399    28270  28115.6 -0.005458
2023-03-24 16:10:01,669:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17145 

self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28111.1', self.close='28159.9'
127.0.0.1 - - [24/Mar/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-03-24 16:20:08,108:INFO:modifiedmom:main.py:144:handleKline:185213: self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28111.1', self.close='28159.9'
2023-03-24 16:20:08,938:INFO:modifiedmom:main.py:145:handleKline:185213: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230324   153000    153959  1679643599  28198.8  28246.1  0.001674
526  20230324   154000    154959  1679644199    28246  28292.1  0.001629
527  20230324   155000    155959  1679644799  28292.2  28269.9 -0.000785
528  20230324   160000    160959  1679645399    28270  28115.6 -0.005458
529  20230324   161000    161959  1679645999  28111.1  28159.9  0.001576
2023-03-24 16:20:08,938:INFO:modifiedmom:main.py:146:handleKline:185213: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230324   155000    155959  1679644799  28292.2  28269.9
2023-03-24 16:00:02,033:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17145 

self.closeSec=1679645399, self.tradeDate='20230324', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28270', self.close='28115.6'
2023-03-24 16:10:01,598:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679645399, self.tradeDate='20230324', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28270', self.close='28115.6'
127.0.0.1 - - [24/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-24 16:10:01,664:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230324   152000    152959  1679642999  28233.5  28198.9
17517  20230324   153000    153959  1679643599  28198.8  28246.1
17518  20230324   154000    154959  1679644199    28246  28292.1
17519  20230324   155000    155959  1679644799  28292.2  28269.9
17520  20230324   160000    160959  1679645399    28270  28115.6
2023-03-24 16:10:01,664:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17146 

self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28111.1', self.close='28159.9'
127.0.0.1 - - [24/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-24 16:20:11,800:INFO:pyemd2:main.py:125:handleKline:185189: self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28111.1', self.close='28159.9'
2023-03-24 16:20:11,952:INFO:pyemd2:main.py:126:handleKline:185189: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230324   153000    153959  1679643599  28198.8  28246.1
17518  20230324   154000    154959  1679644199    28246  28292.1
17519  20230324   155000    155959  1679644799  28292.2  28269.9
17520  20230324   160000    160959  1679645399    28270  28115.6
17521  20230324   161000    161959  1679645999  28111.1  28159.9
2023-03-24 16:20:11,953:INFO:pyemd2:main.py:127:handleKline:185189: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230324   155000    155959  1679644799  28292.2  28269.9
2023-03-24 16:00:01,981:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17145 

self.closeSec=1679645399, self.tradeDate='20230324', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='28270', self.close='28115.6'
127.0.0.1 - - [24/Mar/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-03-24 16:10:01,660:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679645399, self.tradeDate='20230324', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='28270', self.close='28115.6'
2023-03-24 16:10:01,711:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230324   152000    152959  1679642999  28233.5  28198.9
12189  20230324   153000    153959  1679643599  28198.8  28246.1
12190  20230324   154000    154959  1679644199    28246  28292.1
12191  20230324   155000    155959  1679644799  28292.2  28269.9
12192  20230324   160000    160959  1679645399    28270  28115.6
2023-03-24 16:10:01,712:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=17146 

self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='28111.1', self.close='28159.9'
127.0.0.1 - - [24/Mar/2023 16:20:05] "POST / HTTP/1.1" 200 -
2023-03-24 16:20:11,221:INFO:testStrategy:main.py:101:handleKline:185174: self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='28111.1', self.close='28159.9'
2023-03-24 16:20:11,579:INFO:testStrategy:main.py:102:handleKline:185174: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230324   153000    153959  1679643599  28198.8  28246.1
12190  20230324   154000    154959  1679644199    28246  28292.1
12191  20230324   155000    155959  1679644799  28292.2  28269.9
12192  20230324   160000    160959  1679645399    28270  28115.6
12193  20230324   161000    161959  1679645999  28111.1  28159.9
2023-03-24 16:20:11,579:INFO:testStrategy:main.py:103:handleKline:185174: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29722
self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=28173.0, self.close=28159.9, self.high=28178.0, self.low=28140.8, self.vol=1294.42, self.amt=36445724.9561 
127.0.0.1 - - [24/Mar/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-03-24 16:20:05,958:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230324   155500    155959  ...         0.0        0.0       0
5952  20230324   160000    160459  ...         0.0        0.0       0
5953  20230324   160500    160959  ...         0.0        0.0       0
5954  20230324   161000    161459  ...         0.0        0.0       0
5955  20230324   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 16:20:05,988:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679645999, self.tradeDate='20230324', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=28173.0, self.close=28159.9, self.high=28178.0, self.low=28140.8, self.vol=1294.42, self.amt=36445724.9561, ukdf['pct'].iloc[-1]=-0.000465 , ukdf['amount'].iloc[-1]=36445724.9561, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0
127.0.0.1 - - [24/Mar/2023 16:25:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=0, self.total=1000000.0, self.flagDict['side']='', self.tradeCount=0, self.count=29723
self.closeSec=1679646299, self.tradeDate='20230324', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=28159.9, self.close=28207.7, self.high=28212.4, self.low=28158.8, self.vol=1684.187, self.amt=47472062.4669 
2023-03-24 16:25:01,904:INFO:sr_min:main.py:172:handleKline:449472: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230324   160000    160459  ...         0.0        0.0       0
5953  20230324   160500    160959  ...         0.0        0.0       0
5954  20230324   161000    161459  ...         0.0        0.0       0
5955  20230324   161500    161959  ...         0.0        0.0       0
5956  20230324   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-03-24 16:25:01,905:INFO:sr_min:main.py:175:handleKline:449472: self.closeSec=1679646299, self.tradeDate='20230324', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=28159.9, self.close=28207.7, self.high=28212.4, self.low=28158.8, self.vol=1684.187, self.amt=47472062.4669, ukdf['pct'].iloc[-1]=0.001697 , ukdf['amount'].iloc[-1]=47472062.4669, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': []}
type(curSign)=<class 'int'>, curSign=0, self.sign=0


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230324   040000    075959  1679615999  ...    721  0.017394 -2.254048    -1.0
722  20230324   080000    115959  1679630399  ...    722  0.016544 -2.211430    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-6450.0906', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28211.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1507151.9559834, self.flagDict['side']='sell', self.tradeCount=27, self.count=714
self.closeSec=1679644799, self.tradeDate='20230324', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=28211.3, self.close=28269.9, self.high=28334.0, self.low=28078.4, self.vol=45073.281, self.amt=1272363804.15626 
127.0.0.1 - - [24/Mar/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-03-24 16:00:01,810:INFO:s_rsrs:main.py:141:handleKline:185271: self.closeSec=1679644799, self.tradeDate='20230324', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=28211.3, self.close=28269.9, self.high=28334.0, self.low=28078.4, self.vol=45073.281, self.amt=1272363804.15626 
2023-03-24 16:00:01,857:INFO:s_rsrs:main.py:142:handleKline:185271: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230323   200000    235959  ...  280955.401  7.873060e+09  0.036307
720  20230324   000000    035959  ...  222300.561  6.267989e+09 -0.007419
721  20230324   040000    075959  ...   89487.014  2.524258e+09 -0.002764
722  20230324   080000    115959  ...   44984.892  1.270352e+09 -0.002574
723  20230324   120000    155959  ...   45073.281  1.272364e+09  0.002077

[5 rows x 11 columns]
2023-03-24 16:00:05,289:INFO:s_rsrs:main.py:151:handleKline:185271: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230323   200000    235959  1679587199  ...    719  0.015358 -2.323733    -1.0
720  20230324   000000    035959  1679601599  ...    720  0.014481 -2.293799    -1.0
721  20230324   040000    075959  1679615999  ...    721  0.017394 -2.254048    -1.0
722  20230324   080000    115959  1679630399  ...    722  0.016544 -2.211430    -1.0
723  20230324   120000    155959  1679644799  ...    723  0.015430 -2.159293    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.706', 'enterprice': '28091.1', 'countrevence': '0', 'unrealprofit': '-9602.6328', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '28269.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


