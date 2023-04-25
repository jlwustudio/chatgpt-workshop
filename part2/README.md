# Part. 2 輔助撰寫研究報告
本階段將透過幾個研究範例，介紹如何利用 ChatGPT 來協助已經**完成研究、具備相關資料以及實驗數據**的師生進行研究報告的撰寫。我們將會提供一些實用的技巧和方法，例如使用 ChatGPT 來判別資料表、生成研究報告等，幫助各位更好地掌握研究報告撰寫的技巧和 ChatGPT 的應用。  

## 研究報告－霸凌因素偵測
### 研究大綱
這個研究是針對 PPT 討論串中的每一句回文偵測是否具有霸凌因素。研究工作主要為**標記資料**以及**建模**。資料總共有約 5,926 筆回文，其中將標記五種不同的霸凌因素：恐嚇、騷擾、侮辱、諷刺以及情緒波動。  

[🔗 01_label_table](https://github.com/jlwustudio/chatgpt-workshop/blob/main/part2/01_label_table.xlsx): 標記資料統計表格  
[🔗 02_model_table](https://github.com/jlwustudio/chatgpt-workshop/blob/main/part2/01_label_table.xlsx): 模型比較表格  

### 使用 ChatGPT 輔助撰寫
#### 📌 Step1. 給定 ChatGPT 人設
> 你現在是一位研究報告撰寫顧問，接下來你將協助我撰寫研究報告。了解的話請回答「是」並且以繁體中文進行回答。  

給予身份以及設定接下來要進行的工作，除此之外也規定使用繁體中文回答以確保閱讀。利用指定回應確保 ChatGPT 有讀懂你的意思。  

#### 📌 Step2. 詳細描述研究工作
> 我想要撰寫一篇有關於「偵測討論串中的文句是否具有霸凌因素」的研究報告。這個研究主要是針對ptt討論串中的每一句回文偵測是否具有霸凌因素。霸凌因素的詳細定義如下：
> * Intimidation is defined as the sentence is mean to intimidate the main ...  

> 這個研究主要有以下幾項工作：
> 1. 收集資料進行標記，標記主要是針對每一句文句判斷是否具有剛剛提到的霸凌因素。
> 2. 使用標記好的資料進行建模並且預測...  

詳細描述研究工作，可以直接複製貼上之前所撰寫過的研究計畫書或任何相關文件，如果文句過長也可以分段描述給 ChatGPT。同樣可以利用指定回應確保 ChatGPT 有讀懂研究內容。  

#### 📌 Step3. 判別表格並產生描述
> 現在，我有一批已經進行完標記的資料，並且經過整理後取得以下統計資料：
> Factors	Yes	No
> 恐嚇	48	5878
> 騷擾	2175	3751
> 侮辱	1603	4323...  

給予現有資料表請 ChatGPT 判別並且產生描述，表格可以直接從 excel 中複製貼上。針對表格進行詳細介紹有助於 ChatGPT 對於研究更加了解，並給予更有效的回覆。可以指定所需要的描述大約需要之字數。


### 參考資料
[Wu, Y. H., Huang, S. W., Chung, W. Y., Yu, C. C., & Wu, J. L. (2022, December). Factor Detection Task of Cyberbullying Using the Deep Learning Model. In 2022 IEEE International Conference on Big Data (Big Data) (pp. 4323-4329). IEEE.
](https://ieeexplore.ieee.org/abstract/document/10020779)