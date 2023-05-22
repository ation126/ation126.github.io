# 20230522 16:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

127.0.0.1 - - [22/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2368
self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26873.0, self.close=26870.9, self.high=26892.4, self.low=26860.9, self.vol=1309.428, self.amt=35195457.8301 
2023-05-22 16:20:00,803:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230522   155500    155959  ...    0.228031   0.317217       0
5952  20230522   160000    160459  ...    0.227850   0.317162       0
5953  20230522   160500    160959  ...    0.227672   0.317110       0
5954  20230522   161000    161459  ...    0.227495   0.317058       0
5955  20230522   161500    161959  ...    0.227317   0.317007       0

[5 rows x 18 columns]
2023-05-22 16:20:00,806:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26873.0, self.close=26870.9, self.high=26892.4, self.low=26860.9, self.vol=1309.428, self.amt=35195457.8301, ukdf['pct'].iloc[-1]=-8.2e-05 , ukdf['amount'].iloc[-1]=35195457.8301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.22731730375430365, signal=0, value_std=0.3170065829611661 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-83.556', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26870.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [22/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2369
self.closeSec=1684743899, self.tradeDate='20230522', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26870.9, self.close=26860.0, self.high=26877.2, self.low=26858.5, self.vol=402.779, self.amt=10821218.1284 
2023-05-22 16:25:00,382:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230522   160000    160459  ...    0.227850   0.317162       0
5953  20230522   160500    160959  ...    0.227672   0.317110       0
5954  20230522   161000    161459  ...    0.227495   0.317058       0
5955  20230522   161500    161959  ...    0.227317   0.317007       0
5956  20230522   162000    162459  ...    0.227140   0.316955       0

[5 rows x 18 columns]
2023-05-22 16:25:00,388:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684743899, self.tradeDate='20230522', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26870.9, self.close=26860.0, self.high=26877.2, self.low=26858.5, self.vol=402.779, self.amt=10821218.1284, ukdf['pct'].iloc[-1]=-0.000406 , ukdf['amount'].iloc[-1]=10821218.1284, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.22713963621782798, signal=0, value_std=0.31695469577372 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '52.49947268214', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26861.13011111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26873.0, self.close=26870.9, self.high=26892.4, self.low=26860.9 
127.0.0.1 - - [22/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-22 16:20:00,737:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26873.0, self.close=26870.9, self.high=26892.4, self.low=26860.9   
2023-05-22 16:20:00,942:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1631  20230522   155500    155959  1684742399  ...  26826.0 -0.000339   1631    5
1632  20230522   160000    160459  1684742699  ...  26820.1  0.001230   1632    0
1633  20230522   160500    160959  1684742999  ...  26852.6 -0.000305   1633    1
1634  20230522   161000    161459  1684743299  ...  26854.4  0.000655   1634    2
1635  20230522   161500    161959  1684743599  ...  26860.9 -0.000082   1635    3

[5 rows x 11 columns]
2023-05-22 16:20:00,942:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [22/May/2023 16:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=0, self.factor=0.6411029224184618, self.count=2371 

self.closeSec=1684743899, self.tradeDate='20230522', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26870.9, self.close=26860.0, self.high=26877.2, self.low=26858.5 
2023-05-22 16:25:00,352:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684743899, self.tradeDate='20230522', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26870.9, self.close=26860.0, self.high=26877.2, self.low=26858.5   
2023-05-22 16:25:00,445:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1632  20230522   160000    160459  1684742699  ...  26820.1  0.001230   1632    0
1633  20230522   160500    160959  1684742999  ...  26852.6 -0.000305   1633    1
1634  20230522   161000    161459  1684743299  ...  26854.4  0.000655   1634    2
1635  20230522   161500    161959  1684743599  ...  26860.9 -0.000082   1635    3
1636  20230522   162000    162459  1684743899  ...  26858.5 -0.000406   1636    4

[5 rows x 11 columns]
2023-05-22 16:25:00,445:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-22 16:00:31,259:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5786  20230522    132959  26680.6  ...  48.750000  0.451071  0.739341
5787  20230522    135959  26728.1  ...  49.166667  0.456507  0.728676
5788  20230522    142959  26743.1  ...  49.583333  0.503379  0.700771
5789  20230522    145959  26883.0  ...  49.166667  0.481193  0.676753
5790  20230522    152959  26809.7  ...  49.583333  0.488835  0.650872

[5 rows x 33 columns]
0.544280442804428
acc is : 0.544280442804428
2023-05-22 16:00:31,442:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
537     0  0.518396  0.481604       1  ...  0.962263   1.0    0.0  0.972473
538     0  0.512066  0.487934       1  ...  0.967304   1.0    0.0  0.977567
539     0  0.547235  0.452765       0  ...  0.964663   1.0    0.0  0.974898
540     0  0.501346  0.498654       1  ...  0.965541   1.0    0.0  0.975785
541     0  0.519221  0.480779       0  ...  0.965419   1.0    0.0  0.975662

[5 rows x 10 columns]
2023-05-22 16:00:31,467:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518234  0.481766       1  ...  0.991727  -1.0    0.0  0.967005
46     0  0.512280  0.487720       1  ...  0.967304   1.0    0.0  0.973969
47     0  0.547430  0.452570       0  ...  0.964663   1.0    0.0  0.971968
48     0  0.501481  0.498519       1  ...  0.965541   1.0    0.0  0.974609
49     0  0.519221  0.480779       0  ...  0.965419   1.0    0.0  0.975662

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.35', 'enterprice': '26892', 'countrevence': '0', 'unrealprofit': '-1840.525847283', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26824.70472222', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

527  20230522   155000    155959  1684742399    26840  26830.7 -0.000346
2023-05-22 16:00:00,373:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [22/May/2023 16:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1184 

self.closeSec=1684742999, self.tradeDate='20230522', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26830.8', self.close='26855.5'
2023-05-22 16:10:00,361:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684742999, self.tradeDate='20230522', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26830.8', self.close='26855.5'
2023-05-22 16:10:00,400:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
524  20230522   152000    152959  1684740599  26814.8  26834.1  0.000716
525  20230522   153000    153959  1684741199    26834  26847.1  0.000484
526  20230522   154000    154959  1684741799    26847    26840 -0.000264
527  20230522   155000    155959  1684742399    26840  26830.7 -0.000346
528  20230522   160000    160959  1684742999  26830.8  26855.5  0.000924
2023-05-22 16:10:00,401:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}

--handleKline--: 127.0.0.1 - - [22/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
 self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1185 

self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26855.5', self.close='26870.9'
2023-05-22 16:20:00,737:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26855.5', self.close='26870.9'
2023-05-22 16:20:00,891:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
525  20230522   153000    153959  1684741199    26834  26847.1  0.000484
526  20230522   154000    154959  1684741799    26847    26840 -0.000264
527  20230522   155000    155959  1684742399    26840  26830.7 -0.000346
528  20230522   160000    160959  1684742999  26830.8  26855.5  0.000924
529  20230522   161000    161959  1684743599  26855.5  26870.9  0.000573
2023-05-22 16:20:00,899:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True}


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

17519  20230522   155000    155959  1684742399    26840  26830.7
2023-05-22 16:00:00,417:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1187 

self.closeSec=1684742999, self.tradeDate='20230522', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26830.8', self.close='26855.5'
2023-05-22 16:10:00,358:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684742999, self.tradeDate='20230522', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26830.8', self.close='26855.5'
127.0.0.1 - - [22/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-22 16:10:00,423:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17516  20230522   152000    152959  1684740599  26814.8  26834.1
17517  20230522   153000    153959  1684741199    26834  26847.1
17518  20230522   154000    154959  1684741799    26847    26840
17519  20230522   155000    155959  1684742399    26840  26830.7
17520  20230522   160000    160959  1684742999  26830.8  26855.5
2023-05-22 16:10:00,423:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1188 

self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26855.5', self.close='26870.9'
127.0.0.1 - - [22/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-22 16:20:01,062:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26855.5', self.close='26870.9'
2023-05-22 16:20:01,138:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17517  20230522   153000    153959  1684741199    26834  26847.1
17518  20230522   154000    154959  1684741799    26847    26840
17519  20230522   155000    155959  1684742399    26840  26830.7
17520  20230522   160000    160959  1684742999  26830.8  26855.5
17521  20230522   161000    161959  1684743599  26855.5  26870.9
2023-05-22 16:20:01,139:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12191  20230522   155000    155959  1684742399    26840  26830.7
2023-05-22 16:00:00,501:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1187 

self.closeSec=1684742999, self.tradeDate='20230522', self.openTime='160000', self.closeTime='160959', self.symbol='BTCUSDT', self.open='26830.8', self.close='26855.5'
2023-05-22 16:10:00,348:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684742999, self.tradeDate='20230522', self.openTime='160000', self.closeTime='160959',self.symbol='BTCUSDT',self.open='26830.8', self.close='26855.5'
127.0.0.1 - - [22/May/2023 16:10:00] "POST / HTTP/1.1" 200 -
2023-05-22 16:10:00,414:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12188  20230522   152000    152959  1684740599  26814.8  26834.1
12189  20230522   153000    153959  1684741199    26834  26847.1
12190  20230522   154000    154959  1684741799    26847    26840
12191  20230522   155000    155959  1684742399    26840  26830.7
12192  20230522   160000    160959  1684742999  26830.8  26855.5
2023-05-22 16:10:00,414:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1188 

self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161000', self.closeTime='161959', self.symbol='BTCUSDT', self.open='26855.5', self.close='26870.9'
127.0.0.1 - - [22/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-22 16:20:01,012:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161000', self.closeTime='161959',self.symbol='BTCUSDT',self.open='26855.5', self.close='26870.9'
2023-05-22 16:20:01,095:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12189  20230522   153000    153959  1684741199    26834  26847.1
12190  20230522   154000    154959  1684741799    26847    26840
12191  20230522   155000    155959  1684742399    26840  26830.7
12192  20230522   160000    160959  1684742999  26830.8  26855.5
12193  20230522   161000    161959  1684743599  26855.5  26870.9
2023-05-22 16:20:01,096:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2368
self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161500', self.closeTime='161959', self.symbol='BTCUSDT', self.open=26873.0, self.close=26870.9, self.high=26892.4, self.low=26860.9, self.vol=1309.428, self.amt=35195457.8301 
127.0.0.1 - - [22/May/2023 16:20:00] "POST / HTTP/1.1" 200 -
2023-05-22 16:20:00,962:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5951  20230522   155500    155959  ...         0.0        0.0       0
5952  20230522   160000    160459  ...         0.0        0.0       0
5953  20230522   160500    160959  ...         0.0        0.0       0
5954  20230522   161000    161459  ...         0.0        0.0       0
5955  20230522   161500    161959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-22 16:20:00,969:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684743599, self.tradeDate='20230522', self.openTime='161500', self.closeTime='161959',self.symbol='BTCUSDT',self.open=26873.0, self.close=26870.9, self.high=26892.4, self.low=26860.9, self.vol=1309.428, self.amt=35195457.8301, ukdf['pct'].iloc[-1]=-8.2e-05 , ukdf['amount'].iloc[-1]=35195457.8301, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5955, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '999.0929', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26870.9', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [22/May/2023 16:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2369
self.closeSec=1684743899, self.tradeDate='20230522', self.openTime='162000', self.closeTime='162459', self.symbol='BTCUSDT', self.open=26870.9, self.close=26860.0, self.high=26877.2, self.low=26858.5, self.vol=402.779, self.amt=10821218.1284 
2023-05-22 16:25:00,464:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5952  20230522   160000    160459  ...         0.0        0.0       0
5953  20230522   160500    160959  ...         0.0        0.0       0
5954  20230522   161000    161459  ...         0.0        0.0       0
5955  20230522   161500    161959  ...         0.0        0.0       0
5956  20230522   162000    162459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-22 16:25:00,464:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684743899, self.tradeDate='20230522', self.openTime='162000', self.closeTime='162459',self.symbol='BTCUSDT',self.open=26870.9, self.close=26860.0, self.high=26877.2, self.low=26858.5, self.vol=402.779, self.amt=10821218.1284, ukdf['pct'].iloc[-1]=-0.000406 , ukdf['amount'].iloc[-1]=10821218.1284, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5956, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '636.22945673651', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26861.13011111', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

721  20230522   040000    075959  1684713599  ...    721  0.231294 -1.012186    -1.0
722  20230522   080000    115959  1684727999  ...    722  0.206858 -1.122289    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '22305.2523', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26637.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=49
self.closeSec=1684742399, self.tradeDate='20230522', self.openTime='120000', self.closeTime='155959', self.symbol='BTCUSDT', self.open=26637.7, self.close=26830.7, self.high=26898.9, self.low=26630.4, self.vol=46118.467, self.amt=1235245782.35342 
2023-05-22 16:00:00,349:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684742399, self.tradeDate='20230522', self.openTime='120000', self.closeTime='155959',self.symbol='BTCUSDT',self.open=26637.7, self.close=26830.7, self.high=26898.9, self.low=26630.4, self.vol=46118.467, self.amt=1235245782.35342 
127.0.0.1 - - [22/May/2023 16:00:00] "POST / HTTP/1.1" 200 -
2023-05-22 16:00:00,409:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
719  20230521   200000    235959  ...  50401.693  1.354903e+09  0.002495
720  20230522   000000    035959  ...  24421.545  6.562348e+08  0.000156
721  20230522   040000    075959  ...  41970.275  1.122797e+09 -0.005816
722  20230522   080000    115959  ...  60333.993  1.606146e+09 -0.003557
723  20230522   120000    155959  ...  46118.467  1.235246e+09  0.007245

[5 rows x 11 columns]
2023-05-22 16:00:02,777:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
719  20230521   200000    235959  1684684799  ...    719  0.170303 -1.343700    -1.0
720  20230522   000000    035959  1684699199  ...    720  0.146344 -1.440392    -1.0
721  20230522   040000    075959  1684713599  ...    721  0.231294 -1.012186    -1.0
722  20230522   080000    115959  1684727999  ...    722  0.206858 -1.122289    -1.0
723  20230522   120000    155959  1684742399  ...    723  0.151993 -1.376274    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '12356.2953', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26830.8', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


