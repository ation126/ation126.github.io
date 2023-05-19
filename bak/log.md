# 20230519 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1408
self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26848.4, self.close=26863.9, self.high=26872.5, self.low=26846.2, self.vol=541.13, self.amt=14535079.5206 
127.0.0.1 - - [19/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-19 08:20:00,698:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230519   075500    075959  ...    0.377719   0.314981       0
5856  20230519   080000    080459  ...    0.377558   0.315026       0
5857  20230519   080500    080959  ...    0.377397   0.315071       0
5858  20230519   081000    081459  ...    0.377237   0.315116       0
5859  20230519   081500    081959  ...    0.377076   0.315161       0

[5 rows x 18 columns]
2023-05-19 08:20:00,706:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26848.4, self.close=26863.9, self.high=26872.5, self.low=26846.2, self.vol=541.13, self.amt=14535079.5206, ukdf['pct'].iloc[-1]=0.000581 , ukdf['amount'].iloc[-1]=14535079.5206, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.37707643074893965, signal=0, value_std=0.3151609044651835 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-19.20135248394', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26866.27881319', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [19/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=1409
self.closeSec=1684455899, self.tradeDate='20230519', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26864.0, self.close=26866.6, self.high=26875.0, self.low=26842.1, self.vol=780.722, self.amt=20970811.2227 
2023-05-19 08:25:00,385:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230519   080000    080459  ...    0.377558   0.315026       0
5857  20230519   080500    080959  ...    0.377397   0.315071       0
5858  20230519   081000    081459  ...    0.377237   0.315116       0
5859  20230519   081500    081959  ...    0.377076   0.315161       0
5860  20230519   082000    082459  ...    0.376926   0.315212       0

[5 rows x 18 columns]
2023-05-19 08:25:00,386:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684455899, self.tradeDate='20230519', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26864.0, self.close=26866.6, self.high=26875.0, self.low=26842.1, self.vol=780.722, self.amt=20970811.2227, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=20970811.2227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.3769258721675565, signal=0, value_std=0.3152115366373162 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-28.19147814054', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26866.92437729', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26848.4, self.close=26863.9, self.high=26872.5, self.low=26846.2 
127.0.0.1 - - [19/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-19 08:20:00,503:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26848.4, self.close=26863.9, self.high=26872.5, self.low=26846.2   
2023-05-19 08:20:00,581:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230519   075500    075959  1684454399  ...  26801.2 -0.000634   1535    5
1536  20230519   080000    080459  1684454699  ...  26786.5  0.000522   1536    0
1537  20230519   080500    080959  1684454999  ...  26805.1 -0.000563   1537    1
1538  20230519   081000    081459  1684455299  ...  26808.2  0.001496   1538    2
1539  20230519   081500    081959  1684455599  ...  26846.2  0.000581   1539    3

[5 rows x 11 columns]
2023-05-19 08:20:00,583:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=8, self.factor=0.4845388101106761, self.count=1411 

self.closeSec=1684455899, self.tradeDate='20230519', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26864.0, self.close=26866.6, self.high=26875.0, self.low=26842.1 
2023-05-19 08:25:00,357:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684455899, self.tradeDate='20230519', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26864.0, self.close=26866.6, self.high=26875.0, self.low=26842.1   
2023-05-19 08:25:00,369:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230519   080000    080459  1684454699  ...  26786.5  0.000522   1536    0
1537  20230519   080500    080959  1684454999  ...  26805.1 -0.000563   1537    1
1538  20230519   081000    081459  1684455299  ...  26808.2  0.001496   1538    2
1539  20230519   081500    081959  1684455599  ...  26846.2  0.000581   1539    3
1540  20230519   082000    082459  1684455899  ...  26842.1  0.000101   1540    4

[5 rows x 11 columns]
2023-05-19 08:25:00,369:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-19 08:00:18,193:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230519    052959  26708.8  ...  47.916667  0.452204  0.568436
5771  20230519    055959  26818.0  ...  48.333333  0.468345  0.563991
5772  20230519    062959  26901.5  ...  48.333333  0.463979  0.561374
5773  20230519    065959  26875.3  ...  48.333333  0.464818  0.558679
5774  20230519    072959  26879.5  ...  48.333333  0.456779  0.558944

[5 rows x 33 columns]
0.5268022181146026
acc is : 0.5268022181146026
2023-05-19 08:00:18,290:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.535788  0.464212       1  ...  0.987624  -1.0    0.0  0.930361
537     0  0.537598  0.462402       0  ...  0.988582  -1.0    0.0  0.929459
538     0  0.507826  0.492174       1  ...  0.988424  -1.0    0.0  0.929607
539     0  0.515693  0.484307       0  ...  0.990167  -1.0    0.0  0.927968
540     0  0.503806  0.496194       0  ...  0.991012  -1.0    0.0  0.927176

[5 rows x 10 columns]
2023-05-19 08:00:18,305:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.535659  0.464341       1  ...  0.987624  -1.0    0.0  0.929779
46     0  0.538037  0.461963       0  ...  0.988582  -1.0    0.0  0.930067
47     0  0.507771  0.492229       1  ...  0.988424  -1.0    0.0  0.928776
48     0  0.516164  0.483836       0  ...  0.990167  -1.0    0.0  0.927968
49     0  0.503806  0.496194       0  ...  0.991012  -1.0    0.0  0.927176

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '27.758', 'enterprice': '26580.2', 'countrevence': '0', 'unrealprofit': '-6398.219', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26810.7', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230519   075000    075959  1684454399    26853  26809.3 -0.001627
2023-05-19 08:00:00,378:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [19/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=704 

self.closeSec=1684454999, self.tradeDate='20230519', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26809.4', self.close='26808.2'
2023-05-19 08:10:00,348:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684454999, self.tradeDate='20230519', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26809.4', self.close='26808.2'
2023-05-19 08:10:00,408:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230519   072000    072959  1684452599  26845.2  26832.2 -0.000481
621  20230519   073000    073959  1684453199  26832.3    26832 -0.000007
622  20230519   074000    074959  1684453799    26832    26853  0.000783
623  20230519   075000    075959  1684454399    26853  26809.3 -0.001627
624  20230519   080000    080959  1684454999  26809.4  26808.2 -0.000041
2023-05-19 08:10:00,408:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=705 

self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26808.2', self.close='26863.9'
127.0.0.1 - - [19/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-19 08:20:00,687:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26808.2', self.close='26863.9'
2023-05-19 08:20:00,773:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230519   073000    073959  1684453199  26832.3    26832 -0.000007
622  20230519   074000    074959  1684453799    26832    26853  0.000783
623  20230519   075000    075959  1684454399    26853  26809.3 -0.001627
624  20230519   080000    080959  1684454999  26809.4  26808.2 -0.000041
625  20230519   081000    081959  1684455599  26808.2  26863.9  0.002078
2023-05-19 08:20:00,773:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230519   075000    075959  1684454399    26853  26809.3
2023-05-19 08:00:00,485:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=707 

self.closeSec=1684454999, self.tradeDate='20230519', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26809.4', self.close='26808.2'
2023-05-19 08:10:00,343:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684454999, self.tradeDate='20230519', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26809.4', self.close='26808.2'
127.0.0.1 - - [19/May/2023 08:10:00] "POST / HTTP/1.1" 200 -
2023-05-19 08:10:00,353:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230519   072000    072959  1684452599  26845.2  26832.2
17469  20230519   073000    073959  1684453199  26832.3    26832
17470  20230519   074000    074959  1684453799    26832    26853
17471  20230519   075000    075959  1684454399    26853  26809.3
17472  20230519   080000    080959  1684454999  26809.4  26808.2
2023-05-19 08:10:00,353:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [19/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=708 

self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26808.2', self.close='26863.9'
2023-05-19 08:20:00,837:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26808.2', self.close='26863.9'
2023-05-19 08:20:00,864:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230519   073000    073959  1684453199  26832.3    26832
17470  20230519   074000    074959  1684453799    26832    26853
17471  20230519   075000    075959  1684454399    26853  26809.3
17472  20230519   080000    080959  1684454999  26809.4  26808.2
17473  20230519   081000    081959  1684455599  26808.2  26863.9
2023-05-19 08:20:00,865:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230519   075000    075959  1684454399    26853  26809.3
2023-05-19 08:00:00,438:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [19/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=707 

self.closeSec=1684454999, self.tradeDate='20230519', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26809.4', self.close='26808.2'
2023-05-19 08:10:00,380:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684454999, self.tradeDate='20230519', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26809.4', self.close='26808.2'
2023-05-19 08:10:00,425:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230519   072000    072959  1684452599  26845.2  26832.2
12141  20230519   073000    073959  1684453199  26832.3    26832
12142  20230519   074000    074959  1684453799    26832    26853
12143  20230519   075000    075959  1684454399    26853  26809.3
12144  20230519   080000    080959  1684454999  26809.4  26808.2
2023-05-19 08:10:00,428:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--: 127.0.0.1 - - [19/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
 self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=708 

self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26808.2', self.close='26863.9'
2023-05-19 08:20:00,801:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26808.2', self.close='26863.9'
2023-05-19 08:20:00,838:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230519   073000    073959  1684453199  26832.3    26832
12142  20230519   074000    074959  1684453799    26832    26853
12143  20230519   075000    075959  1684454399    26853  26809.3
12144  20230519   080000    080959  1684454999  26809.4  26808.2
12145  20230519   081000    081959  1684455599  26808.2  26863.9
2023-05-19 08:20:00,838:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

127.0.0.1 - - [19/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1408
self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26848.4, self.close=26863.9, self.high=26872.5, self.low=26846.2, self.vol=541.13, self.amt=14535079.5206 
2023-05-19 08:20:00,649:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230519   075500    075959  ...    0.214667   0.299609       0
5856  20230519   080000    080459  ...    0.214419   0.299590       0
5857  20230519   080500    080959  ...    0.214168   0.299567       0
5858  20230519   081000    081459  ...    0.213917   0.299544       0
5859  20230519   081500    081959  ...    0.213666   0.299522       0

[5 rows x 18 columns]
2023-05-19 08:20:00,653:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684455599, self.tradeDate='20230519', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26848.4, self.close=26863.9, self.high=26872.5, self.low=26846.2, self.vol=541.13, self.amt=14535079.5206, ukdf['pct'].iloc[-1]=0.000581 , ukdf['amount'].iloc[-1]=14535079.5206, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.21366637442807024, signal=0, value_std=0.29952194636065294 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '827.45740068979', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26866.27881319', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [19/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=1409
self.closeSec=1684455899, self.tradeDate='20230519', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26864.0, self.close=26866.6, self.high=26875.0, self.low=26842.1, self.vol=780.722, self.amt=20970811.2227 
2023-05-19 08:25:00,353:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230519   080000    080459  ...    0.214419   0.299590       0
5857  20230519   080500    080959  ...    0.214168   0.299567       0
5858  20230519   081000    081459  ...    0.213917   0.299544       0
5859  20230519   081500    081959  ...    0.213666   0.299522       0
5860  20230519   082000    082459  ...    0.213415   0.299499       0

[5 rows x 18 columns]
2023-05-19 08:25:00,354:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684455899, self.tradeDate='20230519', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26864.0, self.close=26866.6, self.high=26875.0, self.low=26842.1, self.vol=780.722, self.amt=20970811.2227, ukdf['pct'].iloc[-1]=0.000101 , ukdf['amount'].iloc[-1]=20970811.2227, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.21341542409450778, signal=0, value_std=0.29949901271495794 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '851.43429692789', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26866.92437729', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230518   200000    235959  1684425599  ...    719  0.382483 -0.670594    -1.0
720  20230519   000000    035959  1684439999  ...    720  0.277058 -1.246574    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '17868.35471774388', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26723.87145788', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=29
self.closeSec=1684454399, self.tradeDate='20230519', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26719.3, self.close=26809.3, self.high=27060.0, self.low=26671.1, self.vol=58949.169, self.amt=1583234091.5685 
2023-05-19 08:00:00,339:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684454399, self.tradeDate='20230519', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26719.3, self.close=26809.3, self.high=27060.0, self.low=26671.1, self.vol=58949.169, self.amt=1583234091.5685 
127.0.0.1 - - [19/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
2023-05-19 08:00:00,390:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230518   120000    155959  ...   61937.260  1.689377e+09  0.000651
718  20230518   160000    195959  ...   42133.547  1.153398e+09  0.000614
719  20230518   200000    235959  ...  145244.456  3.954902e+09 -0.011562
720  20230519   000000    035959  ...  200861.276  5.365861e+09 -0.013145
721  20230519   040000    075959  ...   58949.169  1.583234e+09  0.003368

[5 rows x 11 columns]
2023-05-19 08:00:01,822:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230518   120000    155959  1684396799  ...    717  0.476310 -0.157409     NaN
718  20230518   160000    195959  1684411199  ...    718  0.408356 -0.536552     NaN
719  20230518   200000    235959  1684425599  ...    719  0.382483 -0.670594    -1.0
720  20230519   000000    035959  1684439999  ...    720  0.277058 -1.246574    -1.0
721  20230519   040000    075959  1684454399  ...    721  0.281797 -1.193104    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '13408.75291712481', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26810.38335531', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


