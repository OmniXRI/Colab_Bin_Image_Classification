# 利用「深度學習」模型進行影像二元分類範例

歐尼克斯實境互動工作室【OmniXRI Studio】 Jack整理製作 2018.6.14

[參考資料來源](https://colab.research.google.com/github/google/eng-edu/blob/master/ml/pc/exercises/image_classification_part1.ipynb?utm_source=practicum-IC&utm_campaign=colab-external&utm_medium=referral&hl=pt-br&utm_content=imageexercise1-colab)

在這個範例中我們將帶著大家建構一個二分類的影像分類系統，主要包括下面四個步驟：


1.   如何取得及建構訓練數據(Training Dataset)

2.   如何建構一小型深度學習模型(Training Model)

3.   如何訓練及驗證模型準確度(Valication Accuracy)

4.   如何應用深度學習訓練成果進行推論(Inference) 

在執行本範例前請先確認Jupyter筆記本設置是否正確，首先點選主選單的「修改」─「筆記本設置」─「運行類別」，選擇「Python3」，同時將「硬件加速器」下拉式選單由「None」改成「GPU」，再按「保存」。接著可選擇性執行下列指令確認Colaboratory提供的虛擬機的CPU, 磁碟空間、記憶體大小及GPU是否正確啟動。若出現'/device:GPU:0'表示GPU成功啟動。

**註：以下程式範例執行時，請按【Shift+Enter】進行單步執行並自動跳至下一行。若想一次全部運行本範例所有代碼，可按【Ctrl+F9】**

註：以下程式範例執行時，請按【Shift+Enter】進行單步執行並自動跳至下一行。若想一次全部運行本範例所有代碼，可按【Ctrl+F9】
