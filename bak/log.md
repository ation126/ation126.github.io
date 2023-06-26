# 20230626 08:26:01

## /root/FIL/strategy/amihud/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12352
self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30392.5, self.close=30436.5, self.high=30441.3, self.low=30386.0, self.vol=885.488, self.amt=26934267.4375 
127.0.0.1 - - [26/Jun/2023 08:20:02] "POST / HTTP/1.1" 200 -
2023-06-26 08:20:08,100:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230626   075500    075959  ...         0.0        0.0       0
5856  20230626   080000    080459  ...         0.0        0.0       0
5857  20230626   080500    080959  ...         0.0        0.0       0
5858  20230626   081000    081459  ...         0.0        0.0       0
5859  20230626   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 08:20:08,140:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30392.5, self.close=30436.5, self.high=30441.3, self.low=30386.0, self.vol=885.488, self.amt=26934267.4375, ukdf['pct'].iloc[-1]=0.001448 , ukdf['amount'].iloc[-1]=26934267.4375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-49731.1386', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30436', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1
127.0.0.1 - - [26/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='amihud', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=144, thd=0.8, self.sign=-1, self.total=373746.4768026, self.flagDict['side']='sell', self.tradeCount=2, self.count=12353
self.closeSec=1687739099, self.tradeDate='20230626', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30436.6, self.close=30519.0, self.high=30535.0, self.low=30435.9, self.vol=1734.911, self.amt=52914403.9802 
2023-06-26 08:25:00,795:INFO:amihud:main.py:172:handleKline:2219019: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230626   080000    080459  ...         0.0        0.0       0
5857  20230626   080500    080959  ...         0.0        0.0       0
5858  20230626   081000    081459  ...         0.0        0.0       0
5859  20230626   081500    081959  ...         0.0        0.0       0
5860  20230626   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 08:25:00,795:INFO:amihud:main.py:175:handleKline:2219019: self.closeSec=1687739099, self.tradeDate='20230626', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30436.6, self.close=30519.0, self.high=30535.0, self.low=30435.9, self.vol=1734.911, self.amt=52914403.9802, ukdf['pct'].iloc[-1]=0.002711 , ukdf['amount'].iloc[-1]=52914403.9802, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '13.926', 'enterprice': '26864.9', 'countrevence': '0', 'unrealprofit': '-50930.61615725028', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30522.13223878', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=-1


## /root/FIL/strategy/factorcheck/log.txt ----- -----


self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30392.5, self.close=30436.5, self.high=30441.3, self.low=30386.0 
127.0.0.1 - - [26/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-26 08:20:05,311:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30392.5, self.close=30436.5, self.high=30441.3, self.low=30386.0   
2023-06-26 08:20:06,912:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1535  20230626   075500    075959  1687737599  ...  30446.2  0.000388   1535    5
1536  20230626   080000    080459  1687737899  ...  30418.5 -0.000758   1536    0
1537  20230626   080500    080959  1687738199  ...  30435.9  0.002379   1537    1
1538  20230626   081000    081459  1687738499  ...  30387.7 -0.003763   1538    2
1539  20230626   081500    081959  1687738799  ...  30386.0  0.001448   1539    3

[5 rows x 11 columns]
2023-06-26 08:20:06,920:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  version='2.0.6', self.name='factorcheck2', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=40, wid2=50, thd=0.6, self.factorCnt=437, self.factor=0.5958007175262008, self.count=12355 

self.closeSec=1687739099, self.tradeDate='20230626', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30436.6, self.close=30519.0, self.high=30535.0, self.low=30435.9 
127.0.0.1 - - [26/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
2023-06-26 08:25:00,739:INFO:factorcheck2:main.py:126:handleKline:2218005: self.closeSec=1687739099, self.tradeDate='20230626', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30436.6, self.close=30519.0, self.high=30535.0, self.low=30435.9   
2023-06-26 08:25:00,755:INFO:factorcheck2:main.py:127:handleKline:2218005: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime    closeSec  ...      low       pct  index  idx
1536  20230626   080000    080459  1687737899  ...  30418.5 -0.000758   1536    0
1537  20230626   080500    080959  1687738199  ...  30435.9  0.002379   1537    1
1538  20230626   081000    081459  1687738499  ...  30387.7 -0.003763   1538    2
1539  20230626   081500    081959  1687738799  ...  30386.0  0.001448   1539    3
1540  20230626   082000    082459  1687739099  ...  30435.9  0.002711   1540    4

[5 rows x 11 columns]
2023-06-26 08:25:00,755:INFO:factorcheck2:main.py:128:handleKline:2218005: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/logic/log.txt ----- -----

2023-06-26 08:00:23,798:DEBUG:logic:main.py:463:getModel:2218526: df_s.iloc[-5:,:] :
          date closeTime     open  ...    alpha58   alpha67   alpha72
5770  20230626    052959  30362.8  ...  50.416667  0.489194  0.676862
5771  20230626    055959  30457.7  ...  50.416667  0.487566  0.682133
5772  20230626    062959  30447.9  ...  50.416667  0.502777  0.679775
5773  20230626    065959  30535.4  ...  50.000000  0.495057  0.681322
5774  20230626    072959  30490.5  ...  49.583333  0.488256  0.686096

[5 rows x 33 columns]
0.532347504621072
acc is : 0.532347504621072
2023-06-26 08:00:23,926:INFO:logic:main.py:468:getModel:2218526: df_pred.iloc[-5:,:] :
     pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
536     0  0.518782  0.481218       0  ...  1.179271  -1.0    0.0  1.174053
537     0  0.506974  0.493026       1  ...  1.175886  -1.0    0.0  1.177423
538     0  0.522809  0.477191       0  ...  1.177619  -1.0    0.0  1.175688
539     1  0.495384  0.504616       0  ...  1.179164  -1.0    0.0  1.174145
540     0  0.502743  0.497257       1  ...  1.178869  -1.0    0.0  1.174438

[5 rows x 10 columns]
2023-06-26 08:00:23,944:INFO:logic:main.py:478:getModel:2218526: df_panel.iloc[-5:,:] :
    pred    prob_0    prob_1  actual  ...       nav  sign  cost_        bm
45     0  0.518687  0.481313       0  ...  1.179271  -1.0    0.0  1.172141
46     0  0.506734  0.493266       1  ...  1.175886  -1.0    0.0  1.175750
47     0  0.522753  0.477247       0  ...  1.177619  -1.0    0.0  1.174705
48     1  0.495394  0.504606       0  ...  1.179164  -1.0    0.0  1.174145
49     0  0.502743  0.497257       1  ...  1.178869  -1.0    0.0  1.174438

[5 rows x 10 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '26.697', 'enterprice': '30938.2', 'countrevence': '0', 'unrealprofit': '12822.50788271112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30457.90229304', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}


## /root/FIL/strategy/modifiedmom/log.txt ----- -----

623  20230626   075000    075959  1687737599  30456.7    30458  0.000043
2023-06-26 08:00:02,048:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6176 

self.closeSec=1687738199, self.tradeDate='20230626', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30458', self.close='30507.3'
2023-06-26 08:10:01,137:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687738199, self.tradeDate='20230626', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30458', self.close='30507.3'
2023-06-26 08:10:01,164:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
620  20230626   072000    072959  1687735799  30446.3  30450.4  0.000135
621  20230626   073000    073959  1687736399  30450.3  30431.1 -0.000634
622  20230626   074000    074959  1687736999  30431.1  30456.7  0.000841
623  20230626   075000    075959  1687737599  30456.7    30458  0.000043
624  20230626   080000    080959  1687738199    30458  30507.3  0.001619
2023-06-26 08:10:01,168:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='modifiedmom', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6177 

self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30507.3', self.close='30436.6'
127.0.0.1 - - [26/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 08:20:07,701:INFO:modifiedmom:main.py:144:handleKline:2218259: self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30507.3', self.close='30436.6'
2023-06-26 08:20:08,720:INFO:modifiedmom:main.py:145:handleKline:2218259: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec     open    close       pct
621  20230626   073000    073959  1687736399  30450.3  30431.1 -0.000634
622  20230626   074000    074959  1687736999  30431.1  30456.7  0.000841
623  20230626   075000    075959  1687737599  30456.7    30458  0.000043
624  20230626   080000    080959  1687738199    30458  30507.3  0.001619
625  20230626   081000    081959  1687738799  30507.3  30436.6 -0.002317
2023-06-26 08:20:08,721:INFO:modifiedmom:main.py:146:handleKline:2218259: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': True, 'isOpen': False, 'isClose': True, 'isTrig': False}


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

17471  20230626   075000    075959  1687737599  30456.7    30458
2023-06-26 08:00:02,068:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}
127.0.0.1 - - [26/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6179 

self.closeSec=1687738199, self.tradeDate='20230626', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30458', self.close='30507.3'
2023-06-26 08:10:01,140:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687738199, self.tradeDate='20230626', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30458', self.close='30507.3'
2023-06-26 08:10:01,160:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17468  20230626   072000    072959  1687735799  30446.3  30450.4
17469  20230626   073000    073959  1687736399  30450.3  30431.1
17470  20230626   074000    074959  1687736999  30431.1  30456.7
17471  20230626   075000    075959  1687737599  30456.7    30458
17472  20230626   080000    080959  1687738199    30458  30507.3
2023-06-26 08:10:01,160:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}

--handleKline--:  self.name='pyemd2', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6180 

self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30507.3', self.close='30436.6'
127.0.0.1 - - [26/Jun/2023 08:20:05] "POST / HTTP/1.1" 200 -
2023-06-26 08:20:10,065:INFO:pyemd2:main.py:125:handleKline:2217508: self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30507.3', self.close='30436.6'
2023-06-26 08:20:10,212:INFO:pyemd2:main.py:126:handleKline:2217508: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
17469  20230626   073000    073959  1687736399  30450.3  30431.1
17470  20230626   074000    074959  1687736999  30431.1  30456.7
17471  20230626   075000    075959  1687737599  30456.7    30458
17472  20230626   080000    080959  1687738199    30458  30507.3
17473  20230626   081000    081959  1687738799  30507.3  30436.6
2023-06-26 08:20:10,213:INFO:pyemd2:main.py:127:handleKline:2217508: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': False, 'isCloseBuy': True, 'isCloseSell': False, 'isOpen': False, 'isClose': True, 'isTrig': False}


## /root/FIL/strategy/similarity/log.txt ----- -----

12143  20230626   075000    075959  1687737599  30456.7    30458
2023-06-26 08:00:02,062:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}
127.0.0.1 - - [26/Jun/2023 08:10:01] "POST / HTTP/1.1" 200 -

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6179 

self.closeSec=1687738199, self.tradeDate='20230626', self.openTime='080000', self.closeTime='080959', self.symbol='BTCUSDT', self.open='30458', self.close='30507.3'
2023-06-26 08:10:01,130:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687738199, self.tradeDate='20230626', self.openTime='080000', self.closeTime='080959',self.symbol='BTCUSDT',self.open='30458', self.close='30507.3'
2023-06-26 08:10:01,161:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12140  20230626   072000    072959  1687735799  30446.3  30450.4
12141  20230626   073000    073959  1687736399  30450.3  30431.1
12142  20230626   074000    074959  1687736999  30431.1  30456.7
12143  20230626   075000    075959  1687737599  30456.7    30458
12144  20230626   080000    080959  1687738199    30458  30507.3
2023-06-26 08:10:01,162:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}

--handleKline--:  self.name='testStrategy', self.symbol='BTCUSDT', interval='10m', intervalSec=600, self.count=6180 

self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081000', self.closeTime='081959', self.symbol='BTCUSDT', self.open='30507.3', self.close='30436.6'
127.0.0.1 - - [26/Jun/2023 08:20:04] "POST / HTTP/1.1" 200 -
2023-06-26 08:20:09,540:INFO:testStrategy:main.py:101:handleKline:2217133: self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081000', self.closeTime='081959',self.symbol='BTCUSDT',self.open='30507.3', self.close='30436.6'
2023-06-26 08:20:09,912:INFO:testStrategy:main.py:102:handleKline:2217133: ukdf.iloc[-5:,:] :
      tradeDate openTime closeTime    closeSec     open    close
12141  20230626   073000    073959  1687736399  30450.3  30431.1
12142  20230626   074000    074959  1687736999  30431.1  30456.7
12143  20230626   075000    075959  1687737599  30456.7    30458
12144  20230626   080000    080959  1687738199    30458  30507.3
12145  20230626   081000    081959  1687738799  30507.3  30436.6
2023-06-26 08:20:09,920:INFO:testStrategy:main.py:103:handleKline:2217133: self.flagDict={'side': 'sell', 'posBuy': 0, 'posSell': 0, 'isNewDay': True, 'isOpenBuy': False, 'isOpenSell': True, 'isCloseBuy': False, 'isCloseSell': True, 'isOpen': True, 'isClose': False, 'isTrig': True, 'isCorr': False}


## /root/FIL/strategy/sr_min/log.txt ----- -----

--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12352
self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081500', self.closeTime='081959', self.symbol='BTCUSDT', self.open=30392.5, self.close=30436.5, self.high=30441.3, self.low=30386.0, self.vol=885.488, self.amt=26934267.4375 
127.0.0.1 - - [26/Jun/2023 08:20:01] "POST / HTTP/1.1" 200 -
2023-06-26 08:20:07,912:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5855  20230626   075500    075959  ...         0.0        0.0       0
5856  20230626   080000    080459  ...         0.0        0.0       0
5857  20230626   080500    080959  ...         0.0        0.0       0
5858  20230626   081000    081459  ...         0.0        0.0       0
5859  20230626   081500    081959  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 08:20:07,961:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687738799, self.tradeDate='20230626', self.openTime='081500', self.closeTime='081959',self.symbol='BTCUSDT',self.open=30392.5, self.close=30436.5, self.high=30441.3, self.low=30386.0, self.vol=885.488, self.amt=26934267.4375, ukdf['pct'].iloc[-1]=0.001448 , ukdf['amount'].iloc[-1]=26934267.4375, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5859, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '133410.472', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30436', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1
127.0.0.1 - - [26/Jun/2023 08:25:00] "POST / HTTP/1.1" 200 -
--handleKline--:  version='2.0.0', self.name='sr_min', self.symbol='BTCUSDT', interval='5m', intervalSec=300, wid=192, thd=0.88, self.sign=1, self.total=996015.990996, self.flagDict['side']='buy', self.tradeCount=1, self.count=12353
self.closeSec=1687739099, self.tradeDate='20230626', self.openTime='082000', self.closeTime='082459', self.symbol='BTCUSDT', self.open=30436.6, self.close=30519.0, self.high=30535.0, self.low=30435.9, self.vol=1734.911, self.amt=52914403.9802 
2023-06-26 08:25:00,783:INFO:sr_min:main.py:172:handleKline:2219263: ukdf.iloc[-5:,:] :
     tradeDate openTime closeTime  ...  value_mean  value_std  signal
5856  20230626   080000    080459  ...         0.0        0.0       0
5857  20230626   080500    080959  ...         0.0        0.0       0
5858  20230626   081000    081459  ...         0.0        0.0       0
5859  20230626   081500    081959  ...         0.0        0.0       0
5860  20230626   082000    082459  ...         0.0        0.0       0

[5 rows x 18 columns]
2023-06-26 08:25:00,784:INFO:sr_min:main.py:175:handleKline:2219263: self.closeSec=1687739099, self.tradeDate='20230626', self.openTime='082000', self.closeTime='082459',self.symbol='BTCUSDT',self.open=30436.6, self.close=30519.0, self.high=30535.0, self.low=30435.9, self.vol=1734.911, self.amt=52914403.9802, ukdf['pct'].iloc[-1]=0.002711 , ukdf['amount'].iloc[-1]=52914403.9802, ukdf['indicator'].iloc[-1]=0.0, ukdf['index'].iloc[-1]=5860, value=0.0, value_mean=0.0, signal=0, value_std=0.0 
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '37.141', 'enterprice': '26844', 'countrevence': '0', 'unrealprofit': '136609.50948052798', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'long', 'markprice': '30522.13223878', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'int'>, curSign=0, self.sign=1


## /root/FIL/strategy/s_rsrs/log.txt ----- -----

719  20230625   200000    235959  1687708799  ...    719  0.151870 -1.257836    -1.0
720  20230626   000000    035959  1687723199  ...    720  0.168752 -1.197892    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '14829.8112', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30428.6', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1
--handleKline--:  version='2.0.0', self.name='s_rsrs', self.symbol='BTCUSDT', interval='4h', intervalSec=14400, wid=25, thd=0.6, self.sign=-1, self.total=1634064.775524, self.flagDict['side']='sell', self.tradeCount=8, self.count=257
self.closeSec=1687737599, self.tradeDate='20230626', self.openTime='040000', self.closeTime='075959', self.symbol='BTCUSDT', self.open=30420.0, self.close=30458.0, self.high=30564.0, self.low=30252.6, self.vol=38707.641, self.amt=1178424437.4748 
2023-06-26 08:00:01,641:INFO:s_rsrs:main.py:141:handleKline:2218689: self.closeSec=1687737599, self.tradeDate='20230626', self.openTime='040000', self.closeTime='075959',self.symbol='BTCUSDT',self.open=30420.0, self.close=30458.0, self.high=30564.0, self.low=30252.6, self.vol=38707.641, self.amt=1178424437.4748 
127.0.0.1 - - [26/Jun/2023 08:00:01] "POST / HTTP/1.1" 200 -
2023-06-26 08:00:01,695:INFO:s_rsrs:main.py:142:handleKline:2218689: ukdf.iloc[-5:,:] :
    tradeDate openTime closeTime  ...        vol           amt       pct
717  20230625   120000    155959  ...  79266.773  2.445980e+09 -0.000911
718  20230625   160000    195959  ...  36842.297  1.129452e+09 -0.000130
719  20230625   200000    235959  ...  60922.334  1.864297e+09 -0.004425
720  20230626   000000    035959  ...  49478.271  1.506910e+09 -0.005040
721  20230626   040000    075959  ...  38707.641  1.178424e+09  0.001249

[5 rows x 11 columns]
2023-06-26 08:00:03,355:INFO:s_rsrs:main.py:151:handleKline:2218689: df_s.iloc[-5:,:] :
    tradeDate openTime closeTime    closeSec  ...  index      beta    zscore  signal
717  20230625   120000    155959  1687679999  ...    717  0.469958 -0.369203     NaN
718  20230625   160000    195959  1687694399  ...    718  0.299954 -0.851107    -1.0
719  20230625   200000    235959  1687708799  ...    719  0.151870 -1.257836    -1.0
720  20230626   000000    035959  1687723199  ...    720  0.168752 -1.197892    -1.0
721  20230626   040000    075959  1687737599  ...    721  0.240057 -0.983551    -1.0

[5 rows x 15 columns]
queryPositions: self.symbol='BTCUSDT', positions=PositionsReturn{'result': [PositionType{'sysID': SystemID{'mainID': '', 'subID': '', 'strategyID': ''}, 'symbol': 'BTCUSDT', 'positionAmount': '53.268', 'enterprice': '30707', 'countrevence': '0', 'unrealprofit': '13263.732', 'marginmodel': 0, 'isolatedmargin': '0', 'positionside': 'short', 'markprice': '30458', 'status': 'none', 'closeprice': '0', 'closeamount': '0', 'opentime': 0, 'closetime': 0, 'type': 'AssetType_ucontract'}]}
type(curSign)=<class 'numpy.int64'>, curSign=-1, self.sign=-1


