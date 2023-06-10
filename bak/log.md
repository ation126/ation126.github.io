# 20230610 16:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7840
self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25619.1, self.close=25632.5, self.high=25638.8, self.low=25610.5, self.vol=1078.838, self.amt=27649780.0166 
127.0.0.1 - - [10/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 16:20:07,265:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230610   155500    155959  ...         0.0        0.0       0
5952  20230610   160000    160459  ...         0.0        0.0       0
5953  20230610   160500    160959  ...         0.0        0.0       0
5954  20230610   161000    161459  ...         0.0        0.0       0
5955  20230610   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 16:20:07,286:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25619.1, self.close=25632.5, self.high=25638.8, self.low=25610.5, self.vol=1078.838, self.amt=27649780.0166, ukdf['pct'].iloc[-1]=0.000523 , ukdf['amount'].iloc[-1]=27649780.0166, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '17057.9574', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25640', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=7841
self.closeSec=1686385499, self.tradeDate='20230610', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25635.8, self.close=25648.5, self.high=25648.6, self.low=25616.5, self.vol=1228.921, self.amt=31504888.6326 
127.0.0.1 - - [10/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 16:25:04,546:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230610   160000    160459  ...         0.0        0.0       0
5953  20230610   160500    160959  ...         0.0        0.0       0
5954  20230610   161000    161459  ...         0.0        0.0       0
5955  20230610   161500    161959  ...         0.0        0.0       0
5956  20230610   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 16:25:04,551:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1686385499, self.tradeDate='20230610', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25635.8, self.close=25648.5, self.high=25648.6, self.low=25616.5, self.vol=1228.921, self.amt=31504888.6326, ukdf['pct'].iloc[-1]=0.000624 , ukdf['amount'].iloc[-1]=31504888.6326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '16932.6234', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25649', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25619.1, self.close=25632.5, self.high=25638.8, self.low=25610.5 
127.0.0.1 - - [10/Jun/2023 16:20:01] "POST / HTTP/1.1" 200 -
2023-06-10 16:20:05,002:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25619.1, self.close=25632.5, self.high=25638.8, self.low=25610.5   
2023-06-10 16:20:06,634:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230610   155500    155959  1686383999  ...  25618.1 -0.000635   1631    5
1632  20230610   160000    160459  1686384299  ...  25556.4 -0.001389   1632    0
1633  20230610   160500    160959  1686384599  ...  25574.3  0.000180   1633    1
1634  20230610   161000    161459  1686384899  ...  25571.4  0.000500   1634    2
1635  20230610   161500    161959  1686385199  ...  25610.5  0.000523   1635    3

[5 rows x 11 columns]
2023-06-10 16:20:06,642:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6501354466613132, self.count=7843 

self.closeSec=1686385499, self.tradeDate='20230610', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25635.8, self.close=25648.5, self.high=25648.6, self.low=25616.5 
127.0.0.1 - - [10/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 16:25:03,350:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1686385499, self.tradeDate='20230610', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25635.8, self.close=25648.5, self.high=25648.6, self.low=25616.5   
2023-06-10 16:25:04,131:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230610   160000    160459  1686384299  ...  25556.4 -0.001389   1632    0
1633  20230610   160500    160959  1686384599  ...  25574.3  0.000180   1633    1
1634  20230610   161000    161459  1686384899  ...  25571.4  0.000500   1634    2
1635  20230610   161500    161959  1686385199  ...  25610.5  0.000523   1635    3
1636  20230610   162000    162459  1686385499  ...  25616.5  0.000624   1636    4

[5 rows x 11 columns]
2023-06-10 16:25:04,132:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-10 16:00:39,317:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230610    132959  25753.8  ...  49.166667  0.331705  0.722909
5787  20230610    135959  25600.1  ...  49.166667  0.319380  0.738279
5788  20230610    142959  25504.4  ...  49.583333  0.348536  0.746950
5789  20230610    145959  25620.1  ...  49.583333  0.336290  0.759770
5790  20230610    152959  25525.8  ...  49.583333  0.373495  0.763906

[5 rows x 33 columns]
0.503690036900369
acc is : 0.503690036900369
2023-06-10 16:00:39,475:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     1  0.409362  0.590638       0  ...  1.028875  -1.0    0.0  0.920784
538     1  0.409346  0.590654       1  ...  1.024309  -1.0    0.0  0.924870
539     1  0.458489  0.541511       0  ...  1.028079  -1.0    0.0  0.921466
540     1  0.452781  0.547219       1  ...  1.021788  -1.0    0.0  0.927105
541     0  0.521623  0.478377       0  ...  1.023566  -1.0    0.0  0.925491

[5 rows x 10 columns]
2023-06-10 16:00:39,509:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     1  0.409462  0.590538       0  ...  1.028875  -1.0    0.0  0.921535
46     1  0.409486  0.590514       1  ...  1.024309  -1.0    0.0  0.923127
47     1  0.458506  0.541494       0  ...  1.028079  -1.0    0.0  0.920778
48     1  0.453044  0.546956       1  ...  1.021788  -1.0    0.0  0.928428
49     0  0.521623  0.478377       0  ...  1.023566  -1.0    0.0  0.925491

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '28.53', 'enterprice': '25699.9', 'countrevence': '0', 'unrealprofit': '1803.096', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25636.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230610   155000    155959  1686383999  25649.9  25637.3 -0.000495
2023-06-10 16:00:02,296:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [10/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3920 

self.closeSec=1686384599, self.tradeDate='20230610', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25637.3', self.close='25606.3'
2023-06-10 16:10:01,163:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686384599, self.tradeDate='20230610', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25637.3', self.close='25606.3'
2023-06-10 16:10:01,234:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230610   152000    152959  1686382199  25535.4    25682  0.005745
525  20230610   153000    153959  1686382799  25681.2  25694.3  0.000479
526  20230610   154000    154959  1686383399  25694.3    25650 -0.001724
527  20230610   155000    155959  1686383999  25649.9  25637.3 -0.000495
528  20230610   160000    160959  1686384599  25637.3  25606.3 -0.001209
2023-06-10 16:10:01,234:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3921 

self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25606.3', self.close='25635.7'
127.0.0.1 - - [10/Jun/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-06-10 16:20:06,402:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25606.3', self.close='25635.7'
2023-06-10 16:20:07,443:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230610   153000    153959  1686382799  25681.2  25694.3  0.000479
526  20230610   154000    154959  1686383399  25694.3    25650 -0.001724
527  20230610   155000    155959  1686383999  25649.9  25637.3 -0.000495
528  20230610   160000    160959  1686384599  25637.3  25606.3 -0.001209
529  20230610   161000    161959  1686385199  25606.3  25635.7  0.001148
2023-06-10 16:20:07,445:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230610   155000    155959  1686383999  25649.9  25637.3
2023-06-10 16:00:02,383:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3923 

self.closeSec=1686384599, self.tradeDate='20230610', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25637.3', self.close='25606.3'
127.0.0.1 - - [10/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -
2023-06-10 16:10:01,190:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686384599, self.tradeDate='20230610', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25637.3', self.close='25606.3'
2023-06-10 16:10:01,241:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230610   152000    152959  1686382199  25535.4    25682
17517  20230610   153000    153959  1686382799  25681.2  25694.3
17518  20230610   154000    154959  1686383399  25694.3    25650
17519  20230610   155000    155959  1686383999  25649.9  25637.3
17520  20230610   160000    160959  1686384599  25637.3  25606.3
2023-06-10 16:10:01,241:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3924 

self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25606.3', self.close='25635.7'
127.0.0.1 - - [10/Jun/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-06-10 16:20:08,854:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25606.3', self.close='25635.7'
2023-06-10 16:20:09,006:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230610   153000    153959  1686382799  25681.2  25694.3
17518  20230610   154000    154959  1686383399  25694.3    25650
17519  20230610   155000    155959  1686383999  25649.9  25637.3
17520  20230610   160000    160959  1686384599  25637.3  25606.3
17521  20230610   161000    161959  1686385199  25606.3  25635.7
2023-06-10 16:20:09,006:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230610   155000    155959  1686383999  25649.9  25637.3
2023-06-10 16:00:02,323:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [10/Jun/2023 16:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3923 

self.closeSec=1686384599, self.tradeDate='20230610', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='25637.3', self.close='25606.3'
2023-06-10 16:10:01,178:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686384599, self.tradeDate='20230610', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='25637.3', self.close='25606.3'
2023-06-10 16:10:01,241:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230610   152000    152959  1686382199  25535.4    25682
12189  20230610   153000    153959  1686382799  25681.2  25694.3
12190  20230610   154000    154959  1686383399  25694.3    25650
12191  20230610   155000    155959  1686383999  25649.9  25637.3
12192  20230610   160000    160959  1686384599  25637.3  25606.3
2023-06-10 16:10:01,242:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=3924 

self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='25606.3', self.close='25635.7'
127.0.0.1 - - [10/Jun/2023 16:20:03] "POST / HTTP/1.1" 200 -
2023-06-10 16:20:08,487:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='25606.3', self.close='25635.7'
2023-06-10 16:20:08,786:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230610   153000    153959  1686382799  25681.2  25694.3
12190  20230610   154000    154959  1686383399  25694.3    25650
12191  20230610   155000    155959  1686383999  25649.9  25637.3
12192  20230610   160000    160959  1686384599  25637.3  25606.3
12193  20230610   161000    161959  1686385199  25606.3  25635.7
2023-06-10 16:20:08,792:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7840
self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=25619.1, self.close=25632.5, self.high=25638.8, self.low=25610.5, self.vol=1078.838, self.amt=27649780.0166 
127.0.0.1 - - [10/Jun/2023 16:20:02] "POST / HTTP/1.1" 200 -
2023-06-10 16:20:07,302:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230610   155500    155959  ...         0.0        0.0       0
5952  20230610   160000    160459  ...         0.0        0.0       0
5953  20230610   160500    160959  ...         0.0        0.0       0
5954  20230610   161000    161459  ...         0.0        0.0       0
5955  20230610   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 16:20:07,322:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686385199, self.tradeDate='20230610', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=25619.1, self.close=25632.5, self.high=25638.8, self.low=25610.5, self.vol=1078.838, self.amt=27649780.0166, ukdf['pct'].iloc[-1]=0.000523 , ukdf['amount'].iloc[-1]=27649780.0166, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-44717.764', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25640', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=7841
self.closeSec=1686385499, self.tradeDate='20230610', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=25635.8, self.close=25648.5, self.high=25648.6, self.low=25616.5, self.vol=1228.921, self.amt=31504888.6326 
127.0.0.1 - - [10/Jun/2023 16:25:01] "POST / HTTP/1.1" 200 -
2023-06-10 16:25:04,547:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230610   160000    160459  ...         0.0        0.0       0
5953  20230610   160500    160959  ...         0.0        0.0       0
5954  20230610   161000    161459  ...         0.0        0.0       0
5955  20230610   161500    161959  ...         0.0        0.0       0
5956  20230610   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-10 16:25:04,552:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1686385499, self.tradeDate='20230610', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=25635.8, self.close=25648.5, self.high=25648.6, self.low=25616.5, self.vol=1228.921, self.amt=31504888.6326, ukdf['pct'].iloc[-1]=0.000624 , ukdf['amount'].iloc[-1]=31504888.6326, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '-44383.495', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '25649', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230610   040000    075959  1686355199  ...    721  0.589680 -0.064565     NaN
722  20230610   080000    115959  1686369599  ...    722  0.535291 -0.243040     NaN

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '42465.3819867768', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26308.8254652', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-9223372036854775808, self.sign=-1
127.0.0.1 - - [10/Jun/2023 16:00:01] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1492324.2295523998, self.flagDict['side']='sell', self.tradeCount=4, self.count=163
self.closeSec=1686383999, self.tradeDate='20230610', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26312.6, self.close=25637.3, self.high=26340.1, self.low=25445.0, self.vol=239102.737, self.amt=6149956141.69045 
2023-06-10 16:00:01,892:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1686383999, self.tradeDate='20230610', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26312.6, self.close=25637.3, self.high=26340.1, self.low=25445.0, self.vol=239102.737, self.amt=6149956141.69045 
2023-06-10 16:00:01,920:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
719  20230609   200000    235959  ...   78006.116  2.075992e+09 -0.005064
720  20230610   000000    035959  ...   45711.815  1.209032e+09 -0.002460
721  20230610   040000    075959  ...   17679.394  4.676059e+08  0.002580
722  20230610   080000    115959  ...   53810.499  1.419281e+09 -0.005871
723  20230610   120000    155959  ...  239102.737  6.149956e+09 -0.025668

[5 rows x 11 columns]
2023-06-10 16:00:04,063:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230609   200000    235959  1686326399  ...    719  0.527936 -0.271627     NaN
720  20230610   000000    035959  1686340799  ...    720  0.551065 -0.193631     NaN
721  20230610   040000    075959  1686355199  ...    721  0.589680 -0.064565     NaN
722  20230610   080000    115959  1686369599  ...    722  0.535291 -0.243040     NaN
723  20230610   120000    155959  1686383999  ...    723  0.324140 -0.931206    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '55.166', 'enterprice': '27078.6', 'countrevence': '0', 'unrealprofit': '79443.95604802918', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '25638.51088627', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


