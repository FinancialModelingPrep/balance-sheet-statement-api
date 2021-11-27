# [Balance Sheet Statement API Documenatation](https://site.financialmodelingprep.com)
That describes how to use balance sheet statement API on financialmodelingprep.com.
<br />
<br />
**GET YOUR APIKEY IN SECOND ON https://site.financialmodelingprep.com/developer**
<br />
<br />
**Documentation:** https://site.financialmodelingprep.com/developer/docs/financial-statement-free-api#Balance-Sheet-Statement
<br />

**Request Parameters:**

```solidity
String symbol : ex. AAPL
Integer limit : ex., 120
String period : annual | quarter
String datatype : json | csv
```

**Request Example:**
https://financialmodelingprep.com/api/v3/balance-sheet-statement/AAPL?limit=120&apikey=YOUR_API_KEY

**Response Example:**

```json
[ {
    "date" : "2020-10-31",
    "symbol" : "RY.TO",
    "reportedCurrency" : "CAD",
    "fillingDate" : "2020-10-31",
    "acceptedDate" : "2020-10-31",
    "period" : "FY",
    "revenue" : 47104000000,
    "costOfRevenue" : 0.0,
    "grossProfit" : 0.0,
    "grossProfitRatio" : 0.0,
    "researchAndDevelopmentExpenses" : 0.0,
    "generalAndAdministrativeExpenses" : 19924000000,
    "sellingAndMarketingExpenses" : 0.0,
    "sellingGeneralAndAdministrativeExpenses" : 0.0,
    "otherExpenses" : 0.0,
    "operatingExpenses" : 0.0,
    "costAndExpenses" : 0.0,
    "interestExpense" : 14048000000,
    "depreciationAndAmortization" : 1273000000,
    "ebitda" : 0.0,
    "ebitdaratio" : 0.0,
    "operatingIncome" : 0.0,
    "operatingIncomeRatio" : 0.0,
    "totalOtherIncomeExpensesNet" : 0.0,
    "incomeBeforeTax" : 14389000000,
    "incomeBeforeTaxRatio" : 0.305472995923913,
    "incomeTaxExpense" : 2952000000,
    "netIncome" : 11432000000,
    "netIncomeRatio" : 0.24269701086956522,
    "eps" : 7.9677776159255185,
    "epsdiluted" : 7.9677776159255185,
    "weightedAverageShsOut" : 1434779000,
    "weightedAverageShsOutDil" : 1434779000,
    "link" : "https://www.sedar.com/ModifyCompanyDocumentSearchForm.do?lang=EN&company_search=Royal Bank of Canada&document_selection=0&industry_group=A&FromDate=13&FromMonth=05&FromYear=2000&ToDate=13&ToMonth=11&ToYear=2020&Variable=Issuer",
    "finalLink" : "https://www.sedar.com/ModifyCompanyDocumentSearchForm.do?lang=EN&company_search=Royal Bank of Canada&document_selection=0&industry_group=A&FromDate=13&FromMonth=05&FromYear=2000&ToDate=13&ToMonth=11&ToYear=2020&Variable=Issuer"
  }, {"...": "..."}
]
```
