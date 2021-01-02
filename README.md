# DIP-Final
###%%fcn_responses.m 
.　　此檔案旨在對fcn的數據進行一些前處理 
.　　他將全部的label減去最小值，再除以(Max-Min)，將處理過後的數值加總成sum，再將所有數值除以sum（等於讓label變成機率分布） 
.　　產出物為mat_file/fcn_data_212.mat 
\<br>
###%%compute_max_regions.m 
.　　利用mask找尋最大可以用的天空區域(長方形) 
.　　產出物為mat_files/max_rects.mat 
\<br>
###%%compute_descriptors.m 
.　　`5.Sky Search`中，將FCN後的產物F進行一個average pooling process，變成直方圖H（將圖像分成3x3的網格，提取網格s的直方圖Hs，連結後得到H） 
.　　產出物為mat_files/descriptor_212.mat 
\<br>
#%%replace_sky.m
