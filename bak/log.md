# 20230729 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21952
self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29300.0, self.close=29303.9, self.high=29303.9, self.low=29299.9, self.vol=319.749, self.amt=9369210.7722 
127.0.0.1 - - [29/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 16:20:05,535:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230729   155500    155959  ...         0.0        0.0       0
5952  20230729   160000    160459  ...         0.0        0.0       0
5953  20230729   160500    160959  ...         0.0        0.0       0
5954  20230729   161000    161459  ...         0.0        0.0       0
5955  20230729   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 16:20:05,563:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29300.0, self.close=29303.9, self.high=29303.9, self.low=29299.9, self.vol=319.749, self.amt=9369210.7722, ukdf['pct'].iloc[-1]=0.000133 , ukdf['amount'].iloc[-1]=9369210.7722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-33986.403', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29305.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [29/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=21953
self.closeSec=1690619099, self.tradeDate='20230729', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29303.9, self.close=29321.1, self.high=29321.1, self.low=29303.9, self.vol=723.635, self.amt=21212291.3132 
2023-07-29 16:25:00,824:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230729   160000    160459  ...         0.0        0.0       0
5953  20230729   160500    160959  ...         0.0        0.0       0
5954  20230729   161000    161459  ...         0.0        0.0       0
5955  20230729   161500    161959  ...         0.0        0.0       0
5956  20230729   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 16:25:00,824:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1690619099, self.tradeDate='20230729', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29303.9, self.close=29321.1, self.high=29321.1, self.low=29303.9, self.vol=723.635, self.amt=21212291.3132, ukdf['pct'].iloc[-1]=0.000587 , ukdf['amount'].iloc[-1]=21212291.3132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-34205.0412', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '29321.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29300.0, self.close=29303.9, self.high=29303.9, self.low=29299.9 
127.0.0.1 - - [29/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 16:20:03,533:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29300.0, self.close=29303.9, self.high=29303.9, self.low=29299.9   
2023-07-29 16:20:04,694:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230729   155500    155959  1690617599  ...  29271.7 -0.000133   1631    5
1632  20230729   160000    160459  1690617899  ...  29276.0  0.000181   1632    0
1633  20230729   160500    160959  1690618199  ...  29288.3  0.000434   1633    1
1634  20230729   161000    161459  1690618499  ...  29296.1 -0.000034   1634    2
1635  20230729   161500    161959  1690618799  ...  29299.9  0.000133   1635    3

[5 rows x 11 columns]
2023-07-29 16:20:04,694:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [29/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=34, self.factor=0.5306360735676215, self.count=21955 

self.closeSec=1690619099, self.tradeDate='20230729', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29303.9, self.close=29321.1, self.high=29321.1, self.low=29303.9 
2023-07-29 16:25:00,785:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1690619099, self.tradeDate='20230729', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29303.9, self.close=29321.1, self.high=29321.1, self.low=29303.9   
2023-07-29 16:25:00,802:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230729   160000    160459  1690617899  ...  29276.0  0.000181   1632    0
1633  20230729   160500    160959  1690618199  ...  29288.3  0.000434   1633    1
1634  20230729   161000    161459  1690618499  ...  29296.1 -0.000034   1634    2
1635  20230729   161500    161959  1690618799  ...  29299.9  0.000133   1635    3
1636  20230729   162000    162459  1690619099  ...  29303.9  0.000587   1636    4

[5 rows x 11 columns]
2023-07-29 16:25:00,802:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-29 16:00:18,879:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230729    132959  29367.2  ...  47.083333  0.519937  0.473385
5787  20230729    135959  29350.1  ...  47.500000  0.522246  0.475545
5788  20230729    142959  29356.0  ...  47.500000  0.514959  0.480808
5789  20230729    145959  29338.8  ...  47.500000  0.514029  0.486133
5790  20230729    152959  29336.6  ...  47.083333  0.505887  0.494708

[5 rows x 33 columns]
0.5738007380073801
acc is : 0.5738007380073801
2023-07-29 16:00:18,948:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.502788  0.497212       1  ...  0.909157   1.0    0.0  0.973655
538     0  0.508087  0.491913       0  ...  0.908621   1.0    0.0  0.973082
539     0  0.501984  0.498016       0  ...  0.908553   1.0    0.0  0.973009
540     1  0.499898  0.500102       0  ...  0.907958   1.0    0.0  0.972372
541     1  0.496010  0.503990       0  ...  0.906893   1.0    0.0  0.971231

[5 rows x 10 columns]
2023-07-29 16:00:18,959:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502830  0.497170       1  ...  0.947449   1.0    0.0  0.975402
46     0  0.507958  0.492042       0  ...  0.946890   1.0    0.0  0.974264
47     0  0.501615  0.498385       0  ...  0.946819   1.0    0.0  0.973793
48     1  0.499737  0.500263       0  ...  0.907958   1.0    0.0  0.971528
49     1  0.496010  0.503990       0  ...  0.906893   1.0    0.0  0.971231

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '23.818', 'enterprice': '29478', 'countrevence': '0', 'unrealprofit': '-4720.66548646688', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29279.80260784', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230729   155000    155959  1690617599    29300    29283 -0.000580
2023-07-29 16:00:02,170:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10976 

self.closeSec=1690618199, self.tradeDate='20230729', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29283', self.close='29301'
2023-07-29 16:10:01,119:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690618199, self.tradeDate='20230729', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29283', self.close='29301'
127.0.0.1 - - [29/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-29 16:10:01,134:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230729   152000    152959  1690615799    29330  29318.2 -0.000402
525  20230729   153000    153959  1690616399  29318.2  29327.4  0.000314
526  20230729   154000    154959  1690616999  29327.3    29300 -0.000934
527  20230729   155000    155959  1690617599    29300    29283 -0.000580
528  20230729   160000    160959  1690618199    29283    29301  0.000615
2023-07-29 16:10:01,134:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10977 

self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29301', self.close='29303.9'
127.0.0.1 - - [29/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 16:20:06,385:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29301', self.close='29303.9'
2023-07-29 16:20:06,894:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230729   153000    153959  1690616399  29318.2  29327.4  0.000314
526  20230729   154000    154959  1690616999  29327.3    29300 -0.000934
527  20230729   155000    155959  1690617599    29300    29283 -0.000580
528  20230729   160000    160959  1690618199    29283    29301  0.000615
529  20230729   161000    161959  1690618799    29301  29303.9  0.000099
2023-07-29 16:20:06,895:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230729   155000    155959  1690617599    29300    29283
2023-07-29 16:00:02,167:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10979 

self.closeSec=1690618199, self.tradeDate='20230729', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29283', self.close='29301'
2023-07-29 16:10:01,116:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690618199, self.tradeDate='20230729', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29283', self.close='29301'
127.0.0.1 - - [29/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-07-29 16:10:01,123:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230729   152000    152959  1690615799    29330  29318.2
17517  20230729   153000    153959  1690616399  29318.2  29327.4
17518  20230729   154000    154959  1690616999  29327.3    29300
17519  20230729   155000    155959  1690617599    29300    29283
17520  20230729   160000    160959  1690618199    29283    29301
2023-07-29 16:10:01,123:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10980 

self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29301', self.close='29303.9'
127.0.0.1 - - [29/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 16:20:07,710:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29301', self.close='29303.9'
2023-07-29 16:20:07,818:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230729   153000    153959  1690616399  29318.2  29327.4
17518  20230729   154000    154959  1690616999  29327.3    29300
17519  20230729   155000    155959  1690617599    29300    29283
17520  20230729   160000    160959  1690618199    29283    29301
17521  20230729   161000    161959  1690618799    29301  29303.9
2023-07-29 16:20:07,818:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230729   155000    155959  1690617599    29300    29283
2023-07-29 16:00:02,171:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [29/Jul/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10979 

self.closeSec=1690618199, self.tradeDate='20230729', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='29283', self.close='29301'
2023-07-29 16:10:01,113:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690618199, self.tradeDate='20230729', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='29283', self.close='29301'
2023-07-29 16:10:01,134:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230729   152000    152959  1690615799    29330  29318.2
12189  20230729   153000    153959  1690616399  29318.2  29327.4
12190  20230729   154000    154959  1690616999  29327.3    29300
12191  20230729   155000    155959  1690617599    29300    29283
12192  20230729   160000    160959  1690618199    29283    29301
2023-07-29 16:10:01,135:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=10980 

self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='29301', self.close='29303.9'
127.0.0.1 - - [29/Jul/2023 16:20:04] "POST / HTTP/1.1" 200 -
2023-07-29 16:20:07,556:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='29301', self.close='29303.9'
2023-07-29 16:20:07,711:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230729   153000    153959  1690616399  29318.2  29327.4
12190  20230729   154000    154959  1690616999  29327.3    29300
12191  20230729   155000    155959  1690617599    29300    29283
12192  20230729   160000    160959  1690618199    29283    29301
12193  20230729   161000    161959  1690618799    29301  29303.9
2023-07-29 16:20:07,712:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21952
self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=29300.0, self.close=29303.9, self.high=29303.9, self.low=29299.9, self.vol=319.749, self.amt=9369210.7722 
127.0.0.1 - - [29/Jul/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-07-29 16:20:05,473:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230729   155500    155959  ...         0.0        0.0       0
5952  20230729   160000    160459  ...         0.0        0.0       0
5953  20230729   160500    160959  ...         0.0        0.0       0
5954  20230729   161000    161459  ...         0.0        0.0       0
5955  20230729   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 16:20:05,493:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690618799, self.tradeDate='20230729', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=29300.0, self.close=29303.9, self.high=29303.9, self.low=29299.9, self.vol=319.749, self.amt=9369210.7722, ukdf['pct'].iloc[-1]=0.000133 , ukdf['amount'].iloc[-1]=9369210.7722, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '91418.8574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29305.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [29/Jul/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=21953
self.closeSec=1690619099, self.tradeDate='20230729', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=29303.9, self.close=29321.1, self.high=29321.1, self.low=29303.9, self.vol=723.635, self.amt=21212291.3132 
2023-07-29 16:25:00,826:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230729   160000    160459  ...         0.0        0.0       0
5953  20230729   160500    160959  ...         0.0        0.0       0
5954  20230729   161000    161459  ...         0.0        0.0       0
5955  20230729   161500    161959  ...         0.0        0.0       0
5956  20230729   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-29 16:25:00,827:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1690619099, self.tradeDate='20230729', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=29303.9, self.close=29321.1, self.high=29321.1, self.low=29303.9, self.vol=723.635, self.amt=21212291.3132, ukdf['pct'].iloc[-1]=0.000587 , ukdf['amount'].iloc[-1]=21212291.3132, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '92001.9711', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29321.1', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230729   040000    075959  1690588799  ...    721  0.527794  0.581327     NaN
722  20230729   080000    115959  1690603199  ...    722  0.415546  0.156173     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.079', 'enterprice': '29300.8', 'countrevence': '0', 'unrealprofit': '3151.56092850565', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29359.07698235', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1582973.4052368, self.flagDict['side']='buy', self.tradeCount=15, self.count=457
self.closeSec=1690617599, self.tradeDate='20230729', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=29355.6, self.close=29283.0, self.high=29397.9, self.low=29271.7, self.vol=16468.927, self.amt=483069773.3487 
127.0.0.1 - - [29/Jul/2023 16:00:01] "POST / HTTP/1.1" 200 -
2023-07-29 16:00:01,717:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1690617599, self.tradeDate='20230729', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=29355.6, self.close=29283.0, self.high=29397.9, self.low=29271.7, self.vol=16468.927, self.amt=483069773.3487 
2023-07-29 16:00:01,733:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230728   200000    235959  ...  93071.263  2.735679e+09  0.006292
720  20230729   000000    035959  ...  48155.711  1.410362e+09 -0.002573
721  20230729   040000    075959  ...  12323.584  3.611651e+08 -0.000119
722  20230729   080000    115959  ...  12079.215  3.544538e+08  0.001904
723  20230729   120000    155959  ...  16468.927  4.830698e+08 -0.002477

[5 rows x 11 columns]
2023-07-29 16:00:02,512:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230728   200000    235959  1690559999  ...    719  0.330897 -0.233582     NaN
720  20230729   000000    035959  1690574399  ...    720  0.686406  1.131137     1.0
721  20230729   040000    075959  1690588799  ...    721  0.527794  0.581327     NaN
722  20230729   080000    115959  1690603199  ...    722  0.415546  0.156173     NaN
723  20230729   120000    155959  1690617599  ...    723  0.318044 -0.226289     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '54.079', 'enterprice': '29300.8', 'countrevence': '0', 'unrealprofit': '-968.0141', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '29282.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=1


