# Cross-Market-Patent-Analysis

## Data
- 來自Google Patent 中國美國德國IOT資料

## Steps
1. patent 資料分析 `patent\code\EDA`
2. 資料前處理 `LDA\segment` 將csv檔處理成txt格式方便LDA模型使用
3. LDA模型使用。決定各國patent資料主題
    
    `LDA\lda_brief_us_all.ipynb`,`LDA\lda_brief_cn_all.ipynb`,`LDA\lda_brief_de_all.ipynb`
    
4. 各國Emerging technology analysis (LDA/CPC) 
    
    `patent\code\EDA\lda_scatter_plot.ipynb`, `patent\code\scatter_plot.ipynb`
    
    AGR計算方法參考`emerging technology.xlsx`
    
5. 各國Competitor analysis (LDA/CPC) 
    
    `LDA\competitor_lda_brief_`, `patent\code\依年分\依年分competitor_all_`
