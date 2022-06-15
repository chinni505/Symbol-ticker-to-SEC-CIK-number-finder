If you want to access SEC EDGAR database to search any filings related to stcok symbol, you need CIK number.
  This module helps to search stock ticker corresponding CIK number for you.
   
   pip install secciksym
    
python snippet:
```python
from secciksym_package import secciksym
ticker = ['SOFI','docn','aapl','jafa']
for i in range(len(ticker)):
    print(secciksym.SECCIKTICKER(ticker[i]))
      
  ```   
      output:
      1818874
      1582961
      320193
      0

  
  If you observe last ticker 'jafa' is not original stock ticker that's why it returns 0.
  
