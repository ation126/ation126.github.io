# 20230714 08:26:02

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17536
self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=31466.6, self.close=31390.0, self.high=31477.9, self.low=31370.3, self.vol=1819.512, self.amt=57153321.3471 
127.0.0.1 - - [14/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 08:20:06,953:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230714   075500    075959  ...         0.0        0.0       0
5856  20230714   080000    080459  ...         0.0        0.0       0
5857  20230714   080500    080959  ...         0.0        0.0       0
5858  20230714   081000    081459  ...         0.0        0.0       0
5859  20230714   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 08:20:06,992:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=31466.6, self.close=31390.0, self.high=31477.9, self.low=31370.3, self.vol=1819.512, self.amt=57153321.3471, ukdf['pct'].iloc[-1]=-0.002434 , ukdf['amount'].iloc[-1]=57153321.3471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-63133.521', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31398.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=17537
self.closeSec=1689294299, self.tradeDate='20230714', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=31389.9, self.close=31442.3, self.high=31490.0, self.low=31389.9, self.vol=2199.752, self.amt=69182157.7517 
127.0.0.1 - - [14/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-07-14 08:25:00,781:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230714   080000    080459  ...         0.0        0.0       0
5857  20230714   080500    080959  ...         0.0        0.0       0
5858  20230714   081000    081459  ...         0.0        0.0       0
5859  20230714   081500    081959  ...         0.0        0.0       0
5860  20230714   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 08:25:00,783:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1689294299, self.tradeDate='20230714', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=31389.9, self.close=31442.3, self.high=31490.0, self.low=31389.9, self.vol=2199.752, self.amt=69182157.7517, ukdf['pct'].iloc[-1]=0.001666 , ukdf['amount'].iloc[-1]=69182157.7517, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-63778.27179410874', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31444.69834799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=31466.6, self.close=31390.0, self.high=31477.9, self.low=31370.3 
127.0.0.1 - - [14/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 08:20:04,597:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=31466.6, self.close=31390.0, self.high=31477.9, self.low=31370.3   
2023-07-14 08:20:05,992:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230714   075500    075959  1689292799  ...  31422.1  0.000331   1535    5
1536  20230714   080000    080459  1689293099  ...  31416.0 -0.000693   1536    0
1537  20230714   080500    080959  1689293399  ...  31394.7  0.001222   1537    1
1538  20230714   081000    081459  1689293699  ...  31414.8  0.000343   1538    2
1539  20230714   081500    081959  1689293999  ...  31370.3 -0.002434   1539    3

[5 rows x 11 columns]
2023-07-14 08:20:06,003:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}
127.0.0.1 - - [14/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=24, self.factor=0.4247072802602582, self.count=17539 

self.closeSec=1689294299, self.tradeDate='20230714', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=31389.9, self.close=31442.3, self.high=31490.0, self.low=31389.9 
2023-07-14 08:25:00,738:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1689294299, self.tradeDate='20230714', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=31389.9, self.close=31442.3, self.high=31490.0, self.low=31389.9   
2023-07-14 08:25:00,779:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230714   080000    080459  1689293099  ...  31416.0 -0.000693   1536    0
1537  20230714   080500    080959  1689293399  ...  31394.7  0.001222   1537    1
1538  20230714   081000    081459  1689293699  ...  31414.8  0.000343   1538    2
1539  20230714   081500    081959  1689293999  ...  31370.3 -0.002434   1539    3
1540  20230714   082000    082459  1689294299  ...  31389.9  0.001666   1540    4

[5 rows x 11 columns]
2023-07-14 08:25:00,780:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': False, 'isOpen': True, 'isClose': False, 'isTrig': True}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-07-14 08:00:18,335:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230714    052959  31364.9  ...  52.916667  0.585109  0.342135
5771  20230714    055959  31154.6  ...  53.333333  0.596872  0.344315
5772  20230714    062959  31243.9  ...  53.750000  0.601584  0.344844
5773  20230714    065959  31278.0  ...  53.750000  0.603049  0.344873
5774  20230714    072959  31291.6  ...  53.750000  0.611666  0.342145

[5 rows x 33 columns]
0.5434380776340111
acc is : 0.5434380776340111
2023-07-14 08:00:18,432:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
536     1  0.428510  0.571490       1  ...  1.019558  -1.0 -0.0016  1.023012
537     1  0.469283  0.530717       1  ...  1.018367  -1.0  0.0000  1.024207
538     1  0.471867  0.528133       1  ...  1.017999  -1.0  0.0000  1.024577
539     1  0.470656  0.529344       1  ...  1.015826  -1.0  0.0000  1.026764
540     0  0.515389  0.484611       1  ...  1.013131  -1.0  0.0000  1.029488

[5 rows x 10 columns]
2023-07-14 08:00:18,444:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign   cost_        bm
45     1  0.428059  0.571941       1  ...  1.006252  -1.0 -0.0016  1.024676
46     1  0.467829  0.532171       1  ...  0.978631  -1.0  0.0000  1.023640
47     1  0.470938  0.529062       1  ...  1.004713  -1.0  0.0000  1.023997
48     1  0.470304  0.529696       1  ...  1.015826  -1.0  0.0000  1.026764
49     0  0.515389  0.484611       1  ...  1.013131  -1.0  0.0000  1.029488

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '24.363', 'enterprice': '31246.9', 'countrevence': '0', 'unrealprofit': '-4783.35659075091', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '31443.23692857', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230714   075000    075959  1689292799  31419.9  31441.7  0.000694
2023-07-14 08:00:02,155:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8768 

self.closeSec=1689293399, self.tradeDate='20230714', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='31441.6', self.close='31455.8'
2023-07-14 08:10:01,115:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689293399, self.tradeDate='20230714', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='31441.6', self.close='31455.8'
127.0.0.1 - - [14/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
2023-07-14 08:10:01,142:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230714   072000    072959  1689290999    31360  31358.5 -0.000048
621  20230714   073000    073959  1689291599  31358.5  31376.3  0.000568
622  20230714   074000    074959  1689292199  31376.4  31419.9  0.001390
623  20230714   075000    075959  1689292799  31419.9  31441.7  0.000694
624  20230714   080000    080959  1689293399  31441.6  31455.8  0.000448
2023-07-14 08:10:01,142:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8769 

self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='31452.8', self.close='31390'
127.0.0.1 - - [14/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 08:20:07,012:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='31452.8', self.close='31390'
2023-07-14 08:20:07,792:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230714   073000    073959  1689291599  31358.5  31376.3  0.000568
622  20230714   074000    074959  1689292199  31376.4  31419.9  0.001390
623  20230714   075000    075959  1689292799  31419.9  31441.7  0.000694
624  20230714   080000    080959  1689293399  31441.6  31455.8  0.000448
625  20230714   081000    081959  1689293999  31452.8    31390 -0.002092
2023-07-14 08:20:07,793:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230714   075000    075959  1689292799  31419.9  31441.7
2023-07-14 08:00:02,168:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--: 127.0.0.1 - - [14/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -
 self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8771 

self.closeSec=1689293399, self.tradeDate='20230714', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='31441.6', self.close='31455.8'
2023-07-14 08:10:01,140:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689293399, self.tradeDate='20230714', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='31441.6', self.close='31455.8'
2023-07-14 08:10:01,154:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230714   072000    072959  1689290999    31360  31358.5
17469  20230714   073000    073959  1689291599  31358.5  31376.3
17470  20230714   074000    074959  1689292199  31376.4  31419.9
17471  20230714   075000    075959  1689292799  31419.9  31441.7
17472  20230714   080000    080959  1689293399  31441.6  31455.8
2023-07-14 08:10:01,154:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8772 

self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='31452.8', self.close='31390'
127.0.0.1 - - [14/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 08:20:08,897:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='31452.8', self.close='31390'
2023-07-14 08:20:09,080:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230714   073000    073959  1689291599  31358.5  31376.3
17470  20230714   074000    074959  1689292199  31376.4  31419.9
17471  20230714   075000    075959  1689292799  31419.9  31441.7
17472  20230714   080000    080959  1689293399  31441.6  31455.8
17473  20230714   081000    081959  1689293999  31452.8    31390
2023-07-14 08:20:09,081:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230714   075000    075959  1689292799  31419.9  31441.7
2023-07-14 08:00:02,167:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [14/Jul/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8771 

self.closeSec=1689293399, self.tradeDate='20230714', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='31441.6', self.close='31455.8'
2023-07-14 08:10:01,120:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689293399, self.tradeDate='20230714', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='31441.6', self.close='31455.8'
2023-07-14 08:10:01,145:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230714   072000    072959  1689290999    31360  31358.5
12141  20230714   073000    073959  1689291599  31358.5  31376.3
12142  20230714   074000    074959  1689292199  31376.4  31419.9
12143  20230714   075000    075959  1689292799  31419.9  31441.7
12144  20230714   080000    080959  1689293399  31441.6  31455.8
2023-07-14 08:10:01,145:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=8772 

self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='31452.8', self.close='31390'
127.0.0.1 - - [14/Jul/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-07-14 08:20:08,651:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='31452.8', self.close='31390'
2023-07-14 08:20:08,956:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230714   073000    073959  1689291599  31358.5  31376.3
12142  20230714   074000    074959  1689292199  31376.4  31419.9
12143  20230714   075000    075959  1689292799  31419.9  31441.7
12144  20230714   080000    080959  1689293399  31441.6  31455.8
12145  20230714   081000    081959  1689293999  31452.8    31390
2023-07-14 08:20:08,957:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'buy', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': True, 'isOpenSell': False, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17536
self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=31466.6, self.close=31390.0, self.high=31477.9, self.low=31370.3, self.vol=1819.512, self.amt=57153321.3471 
127.0.0.1 - - [14/Jul/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-07-14 08:20:06,931:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230714   075500    075959  ...         0.0        0.0       0
5856  20230714   080000    080459  ...         0.0        0.0       0
5857  20230714   080500    080959  ...         0.0        0.0       0
5858  20230714   081000    081459  ...         0.0        0.0       0
5859  20230714   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 08:20:06,962:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689293999, self.tradeDate='20230714', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=31466.6, self.close=31390.0, self.high=31477.9, self.low=31370.3, self.vol=1819.512, self.amt=57153321.3471, ukdf['pct'].iloc[-1]=-0.002434 , ukdf['amount'].iloc[-1]=57153321.3471, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '169154.9704', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31398.4', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [14/Jul/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=17537
self.closeSec=1689294299, self.tradeDate='20230714', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=31389.9, self.close=31442.3, self.high=31490.0, self.low=31389.9, self.vol=2199.752, self.amt=69182157.7517 
2023-07-14 08:25:00,777:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230714   080000    080459  ...         0.0        0.0       0
5857  20230714   080500    080959  ...         0.0        0.0       0
5858  20230714   081000    081459  ...         0.0        0.0       0
5859  20230714   081500    081959  ...         0.0        0.0       0
5860  20230714   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-07-14 08:25:00,781:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1689294299, self.tradeDate='20230714', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=31389.9, self.close=31442.3, self.high=31490.0, self.low=31389.9, self.vol=2199.752, self.amt=69182157.7517, ukdf['pct'].iloc[-1]=0.001666 , ukdf['amount'].iloc[-1]=69182157.7517, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '170874.53734269659', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31444.69834799', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230713   200000    235959  1689263999  ...    719  0.416175  0.597722     NaN
720  20230714   000000    035959  1689278399  ...    720  0.909357  2.656956     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '56988.54075863606', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31601.97767766', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=1, self.total=1592336.4447248997, self.flagDict['side']='buy', self.tradeCount=11, self.count=365
self.closeSec=1689292799, self.tradeDate='20230714', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=31600.5, self.close=31441.7, self.high=31693.7, self.low=30993.8, self.vol=113138.84, self.amt=3544202476.95852 
127.0.0.1 - - [14/Jul/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-07-14 08:00:01,730:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1689292799, self.tradeDate='20230714', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=31600.5, self.close=31441.7, self.high=31693.7, self.low=30993.8, self.vol=113138.84, self.amt=3544202476.95852 
2023-07-14 08:00:01,758:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...         vol           amt       pct
717  20230713   120000    155959  ...   29140.810  8.836811e+08  0.002354
718  20230713   160000    195959  ...   59604.531  1.818564e+09  0.005785
719  20230713   200000    235959  ...  176453.536  5.430610e+09  0.012604
720  20230714   000000    035959  ...  291866.546  9.114633e+09  0.022164
721  20230714   040000    075959  ...  113138.840  3.544202e+09 -0.005028

[5 rows x 11 columns]
2023-07-14 08:00:03,031:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230713   120000    155959  1689235199  ...    717  0.333767  0.235954     NaN
718  20230713   160000    195959  1689249599  ...    718  0.333067  0.231303     NaN
719  20230713   200000    235959  1689263999  ...    719  0.416175  0.597722     NaN
720  20230714   000000    035959  1689278399  ...    720  0.909357  2.656956     1.0
721  20230714   040000    075959  1689292799  ...    721  1.170617  3.472242     1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '52.241', 'enterprice': '30511.1', 'countrevence': '0', 'unrealprofit': '48610.2505', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '31441.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=1, self.sign=1


