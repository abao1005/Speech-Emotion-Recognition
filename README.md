# Speech-Emotion-Recognition
首先非常感謝 https://github.com/MITESHPUTHRANNEU/Speech-Emotion-Analyzer 此位網友之語音情緒辨識專案，  
讓踏入此領域的新手得以初步了解資料處理與模型搭建之過程。

但經過多次嘗試，仍無法達到原作者 70% 左右之 val_accuracy，  
使用原程式碼只得約 35% 之 val_accuracy，  
並於約 100 個 epoch 後會開始 overfitting，  
研究得知資料不足或是模型太過複雜皆有可能導致過擬合，  
因此嘗試加入幾層 dropout層與 EarlyStopping 後，val_accuracy來到約 45%(辨識男性、女性各八種情緒，共16個labels)。

未來將持續了解深度學習相關知識，看有沒有辦法再優化模型，並增加資料集數量。
