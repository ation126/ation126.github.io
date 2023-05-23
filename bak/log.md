# 20230523 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2560
self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26844.9, self.close=26846.1, self.high=26846.1, self.low=26842.5, self.vol=168.516, self.amt=4523593.4715 
127.0.0.1 - - [23/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 08:20:03,338:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230523   075500    075959  ...    0.195545   0.307128       0
5856  20230523   080000    080459  ...    0.195358   0.307040       0
5857  20230523   080500    080959  ...    0.195170   0.306953       0
5858  20230523   081000    081459  ...    0.194975   0.306854       0
5859  20230523   081500    081959  ...    0.194784   0.306762       0

[5 rows x 18 columns]
2023-05-23 08:20:03,357:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26844.9, self.close=26846.1, self.high=26846.1, self.low=26842.5, self.vol=168.516, self.amt=4523593.4715, ukdf['pct'].iloc[-1]=4.5e-05 , ukdf['amount'].iloc[-1]=4523593.4715, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.19478412116599345, signal=0, value_std=0.30676190410710164 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '260.4162', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26846.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [23/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=2561
self.closeSec=1684801499, self.tradeDate='20230523', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26846.1, self.close=26849.6, self.high=26851.5, self.low=26846.1, self.vol=266.423, self.amt=7153306.2633 
2023-05-23 08:25:00,442:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230523   080000    080459  ...    0.195358   0.307040       0
5857  20230523   080500    080959  ...    0.195170   0.306953       0
5858  20230523   081000    081459  ...    0.194975   0.306854       0
5859  20230523   081500    081959  ...    0.194784   0.306762       0
5860  20230523   082000    082459  ...    0.194599   0.306678       0

[5 rows x 18 columns]
2023-05-23 08:25:00,443:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1684801499, self.tradeDate='20230523', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26846.1, self.close=26849.6, self.high=26851.5, self.low=26846.1, self.vol=266.423, self.amt=7153306.2633, ukdf['pct'].iloc[-1]=0.00013 , ukdf['amount'].iloc[-1]=7153306.2633, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.19459853597352636, signal=0, value_std=0.30667758111344917 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '199.88534896836', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26850.54660714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26844.9, self.close=26846.1, self.high=26846.1, self.low=26842.5 
127.0.0.1 - - [23/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 08:20:02,248:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26844.9, self.close=26846.1, self.high=26846.1, self.low=26842.5   
2023-05-23 08:20:02,898:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230523   075500    075959  1684799999  ...  26826.9  0.000194   1535    5
1536  20230523   080000    080459  1684800299  ...  26830.8  0.000063   1536    0
1537  20230523   080500    080959  1684800599  ...  26841.9  0.000246   1537    1
1538  20230523   081000    081459  1684800899  ...  26844.1 -0.000134   1538    2
1539  20230523   081500    081959  1684801199  ...  26842.5  0.000045   1539    3

[5 rows x 11 columns]
2023-05-23 08:20:02,908:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [23/May/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=27, self.factor=0.4774366219563984, self.count=2563 

self.closeSec=1684801499, self.tradeDate='20230523', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26846.1, self.close=26849.6, self.high=26851.5, self.low=26846.1 
2023-05-23 08:25:00,328:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1684801499, self.tradeDate='20230523', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26846.1, self.close=26849.6, self.high=26851.5, self.low=26846.1   
2023-05-23 08:25:00,366:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230523   080000    080459  1684800299  ...  26830.8  0.000063   1536    0
1537  20230523   080500    080959  1684800599  ...  26841.9  0.000246   1537    1
1538  20230523   081000    081459  1684800899  ...  26844.1 -0.000134   1538    2
1539  20230523   081500    081959  1684801199  ...  26842.5  0.000045   1539    3
1540  20230523   082000    082459  1684801499  ...  26846.1  0.000130   1540    4

[5 rows x 11 columns]
2023-05-23 08:25:00,366:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-05-23 08:00:33,612:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230523    052959  26879.7  ...  48.750000  0.509807  0.411654
5771  20230523    055959  26897.5  ...  48.750000  0.508509  0.407802
5772  20230523    062959  26892.8  ...  48.750000  0.503691  0.411684
5773  20230523    065959  26875.6  ...  48.333333  0.498674  0.417823
5774  20230523    072959  26857.4  ...  47.916667  0.494238  0.426511

[5 rows x 33 columns]
0.5397412199630314
acc is : 0.5397412199630314
2023-05-23 08:00:33,783:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.502973  0.497027       0  ...  0.968769   1.0    0.0  1.000480
537     0  0.501148  0.498852       0  ...  0.968146   1.0    0.0  0.999836
538     1  0.495657  0.504343       0  ...  0.967498   1.0    0.0  0.999167
539     1  0.497208  0.502792       0  ...  0.966925   1.0    0.0  0.998575
540     1  0.491170  0.508830       0  ...  0.966874   1.0    0.0  0.998523

[5 rows x 10 columns]
2023-05-23 08:00:33,819:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.502837  0.497163       0  ...  0.968769   1.0    0.0  0.989932
46     0  0.501462  0.498538       0  ...  0.958858   1.0    0.0  0.990922
47     1  0.495769  0.504231       0  ...  0.958215   1.0    0.0  0.990500
48     1  0.497426  0.502574       0  ...  0.957648   1.0    0.0  0.998575
49     1  0.491170  0.508830       0  ...  0.966874   1.0    0.0  0.998523

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.741', 'enterprice': '27035', 'countrevence': '0', 'unrealprofit': '-5206.4727', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26840.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230523   075000    075959  1684799999  26836.3  26840.2  0.000149
2023-05-23 08:00:00,478:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1280 

self.closeSec=1684800599, self.tradeDate='20230523', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26840.2', self.close='26848.5'
2023-05-23 08:10:00,361:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684800599, self.tradeDate='20230523', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26840.2', self.close='26848.5'
2023-05-23 08:10:00,398:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230523   072000    072959  1684798199  26829.1  26841.6  0.000466
621  20230523   073000    073959  1684798799  26841.7  26856.4  0.000551
622  20230523   074000    074959  1684799399  26856.4  26836.2 -0.000752
623  20230523   075000    075959  1684799999  26836.3  26840.2  0.000149
624  20230523   080000    080959  1684800599  26840.2  26848.5  0.000309
2023-05-23 08:10:00,398:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1281 

self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26848.6', self.close='26846.1'
127.0.0.1 - - [23/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 08:20:02,868:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26848.6', self.close='26846.1'
2023-05-23 08:20:03,319:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230523   073000    073959  1684798799  26841.7  26856.4  0.000551
622  20230523   074000    074959  1684799399  26856.4  26836.2 -0.000752
623  20230523   075000    075959  1684799999  26836.3  26840.2  0.000149
624  20230523   080000    080959  1684800599  26840.2  26848.5  0.000309
625  20230523   081000    081959  1684801199  26848.6  26846.1 -0.000089
2023-05-23 08:20:03,320:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230523   075000    075959  1684799999  26836.3  26840.2
2023-05-23 08:00:00,485:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [23/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1283 

self.closeSec=1684800599, self.tradeDate='20230523', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26840.2', self.close='26848.5'
2023-05-23 08:10:00,370:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684800599, self.tradeDate='20230523', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26840.2', self.close='26848.5'
2023-05-23 08:10:00,463:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230523   072000    072959  1684798199  26829.1  26841.6
17469  20230523   073000    073959  1684798799  26841.7  26856.4
17470  20230523   074000    074959  1684799399  26856.4  26836.2
17471  20230523   075000    075959  1684799999  26836.3  26840.2
17472  20230523   080000    080959  1684800599  26840.2  26848.5
2023-05-23 08:10:00,463:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1284 

self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26848.6', self.close='26846.1'
127.0.0.1 - - [23/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 08:20:04,324:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26848.6', self.close='26846.1'
2023-05-23 08:20:04,392:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230523   073000    073959  1684798799  26841.7  26856.4
17470  20230523   074000    074959  1684799399  26856.4  26836.2
17471  20230523   075000    075959  1684799999  26836.3  26840.2
17472  20230523   080000    080959  1684800599  26840.2  26848.5
17473  20230523   081000    081959  1684801199  26848.6  26846.1
2023-05-23 08:20:04,393:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230523   075000    075959  1684799999  26836.3  26840.2
2023-05-23 08:00:00,500:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [23/May/2023 08:10:00] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1283 

self.closeSec=1684800599, self.tradeDate='20230523', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='26840.2', self.close='26848.5'
2023-05-23 08:10:00,370:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684800599, self.tradeDate='20230523', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='26840.2', self.close='26848.5'
2023-05-23 08:10:00,405:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230523   072000    072959  1684798199  26829.1  26841.6
12141  20230523   073000    073959  1684798799  26841.7  26856.4
12142  20230523   074000    074959  1684799399  26856.4  26836.2
12143  20230523   075000    075959  1684799999  26836.3  26840.2
12144  20230523   080000    080959  1684800599  26840.2  26848.5
2023-05-23 08:10:00,405:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=1284 

self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='26848.6', self.close='26846.1'
127.0.0.1 - - [23/May/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-05-23 08:20:04,058:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='26848.6', self.close='26846.1'
2023-05-23 08:20:04,210:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230523   073000    073959  1684798799  26841.7  26856.4
12142  20230523   074000    074959  1684799399  26856.4  26836.2
12143  20230523   075000    075959  1684799999  26836.3  26840.2
12144  20230523   080000    080959  1684800599  26840.2  26848.5
12145  20230523   081000    081959  1684801199  26848.6  26846.1
2023-05-23 08:20:04,217:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2560
self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=26844.9, self.close=26846.1, self.high=26846.1, self.low=26842.5, self.vol=168.516, self.amt=4523593.4715 
127.0.0.1 - - [23/May/2023 08:20:00] "POST / HTTP/1.1" 200 -
2023-05-23 08:20:03,558:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230523   075500    075959  ...         0.0        0.0       0
5856  20230523   080000    080459  ...         0.0        0.0       0
5857  20230523   080500    080959  ...         0.0        0.0       0
5858  20230523   081000    081459  ...         0.0        0.0       0
5859  20230523   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-23 08:20:03,577:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684801199, self.tradeDate='20230523', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=26844.9, self.close=26846.1, self.high=26846.1, self.low=26842.5, self.vol=168.516, self.amt=4523593.4715, ukdf['pct'].iloc[-1]=4.5e-05 , ukdf['amount'].iloc[-1]=4523593.4715, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '81.7102', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26846.2', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=2561
self.closeSec=1684801499, self.tradeDate='20230523', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=26846.1, self.close=26849.6, self.high=26851.5, self.low=26846.1, self.vol=266.423, self.amt=7153306.2633 
127.0.0.1 - - [23/May/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-05-23 08:25:00,414:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230523   080000    080459  ...         0.0        0.0       0
5857  20230523   080500    080959  ...         0.0        0.0       0
5858  20230523   081000    081459  ...         0.0        0.0       0
5859  20230523   081500    081959  ...         0.0        0.0       0
5860  20230523   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-05-23 08:25:00,417:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1684801499, self.tradeDate='20230523', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=26846.1, self.close=26849.6, self.high=26851.5, self.low=26846.1, self.vol=266.423, self.amt=7153306.2633, ukdf['pct'].iloc[-1]=0.00013 , ukdf['amount'].iloc[-1]=7153306.2633, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '243.14753578674', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '26850.54660714', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230522   200000    235959  1684771199  ...    719  0.030624 -1.905052    -1.0
720  20230523   000000    035959  1684785599  ...    720  0.006426 -1.987827    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '11061.90747893967', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26855.90985317', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
127.0.0.1 - - [23/May/2023 08:00:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1394061.7472955, self.flagDict['side']='sell', self.tradeCount=2, self.count=53
self.closeSec=1684799999, self.tradeDate='20230523', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=26857.0, self.close=26840.2, self.high=26955.9, self.low=26818.0, self.vol=19533.419, self.amt=525014836.8638 
2023-05-23 08:00:00,352:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1684799999, self.tradeDate='20230523', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=26857.0, self.close=26840.2, self.high=26955.9, self.low=26818.0, self.vol=19533.419, self.amt=525014836.8638 
2023-05-23 08:00:00,506:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230522   120000    155959  ...   46118.467  1.235246e+09  0.007245
718  20230522   160000    195959  ...   31113.301  8.346117e+08 -0.000403
719  20230522   200000    235959  ...  129893.083  3.493352e+09  0.001614
720  20230523   000000    035959  ...   41038.257  1.101761e+09 -0.000231
721  20230523   040000    075959  ...   19533.419  5.250148e+08 -0.000626

[5 rows x 11 columns]
2023-05-23 08:00:02,685:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230522   120000    155959  1684742399  ...    717  0.151993 -1.376274    -1.0
718  20230522   160000    195959  1684756799  ...    718  0.099685 -1.608829    -1.0
719  20230522   200000    235959  1684771199  ...    719  0.030624 -1.905052    -1.0
720  20230523   000000    035959  1684785599  ...    720  0.006426 -1.987827    -1.0
721  20230523   040000    075959  1684799999  ...    721  0.070159 -1.676941    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '51.549', 'enterprice': '27070.5', 'countrevence': '0', 'unrealprofit': '11866.5798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '26840.3', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


