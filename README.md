# Comparable Company Valuation

## 📌 Project Overview

This project performs a Comparable Company Valuation using trading multiples to benchmark the valuation of selected US technology companies and Indian IT companies.

The analysis covers five US technology companies — Microsoft, Alphabet, Oracle, Salesforce and IBM — and three Indian IT companies — Wipro, Infosys and TCS.

The valuation framework standardizes the peer group using Enterprise Value (EV), calendarized EBITDA, EV/EBITDA multiples and P/E multiples as of 31 July 2026.

## 🎯 Project Objective

The primary objectives of the analysis are to:

- Perform peer-based relative valuation
- Construct a comparable company peer group
- Calculate Enterprise Value using an EV Bridge
- Standardize EBITDA estimates through calendarisation
- Calculate forward EV/EBITDA multiples for 2026E and 2027E
- Compare P/E multiples across the peer group
- Analyse valuation differences between US and Indian technology companies
- Evaluate multiple compression between 2026E and 2027E
- Develop peer-group valuation statistics for benchmarking

## 🏢 Companies Covered

### US Technology Companies

- Microsoft
- Alphabet
- Oracle
- Salesforce
- IBM

### Indian IT Companies

- Wipro
- Infosys
- TCS

## 📅 Valuation Date

**31 July 2026**

All market-based valuation inputs and share prices are considered with reference to the valuation date.

## 💰 Enterprise Value (EV) Bridge

Enterprise Value was calculated for the US peer companies using:

**EV = Market Capitalization + Total Debt + Lease Liabilities + Preferred Stock + Minority Interest − Cash & Cash Equivalents − Non-operating Investments**

The EV Bridge incorporates relevant balance-sheet items to arrive at Enterprise Value for the EV/EBITDA valuation analysis.

## 📆 EBITDA Calendarisation

Since the US peer companies have different fiscal year-end dates, EBITDA estimates were calendarised to align the valuation period to a December calendar year-end.

A **5/12 and 7/12 weighting approach** was used for companies with non-December fiscal year-ends.

Companies with a 31 December fiscal year-end required no calendarisation adjustment.

Calendarised EBITDA was calculated for:

- 2026E
- 2027E

This improves comparability of forward EBITDA estimates across companies with different financial reporting periods.

## 📊 Valuation Multiples

The analysis focuses on two major trading multiples:

### EV/EBITDA

Calculated for:

- 2026E
- 2027E

EV/EBITDA is used to compare the operating valuation of companies while reducing the impact of differences in capital structure, taxes and depreciation policies.

### P/E

P/E multiples are used to compare the market valuation of companies relative to their earnings.

## 📈 Comparable Company Analysis

The final peer comparison brings together:

- Company
- Country
- EV/EBITDA 2026E
- EV/EBITDA 2027E
- P/E

### EV/EBITDA 2026E

| Company | EV/EBITDA 2026E |
|---|---:|
| Microsoft | 13.32x |
| Alphabet | 14.06x |
| Oracle | 9.02x |
| Salesforce | 8.96x |
| IBM | 12.26x |
| Wipro | 8.90x |
| Infosys | 11.80x |
| TCS | 11.30x |

### EV/EBITDA 2027E

| Company | EV/EBITDA 2027E |
|---|---:|
| Microsoft | 10.61x |
| Alphabet | 10.88x |
| Oracle | 6.27x |
| Salesforce | 8.12x |
| IBM | 11.45x |
| Wipro | 7.96x |
| Infosys | 9.49x |
| TCS | 10.60x |

### P/E Multiples

| Company | P/E |
|---|---:|
| Microsoft | 25.71x |
| Alphabet | 25.32x |
| Oracle | 28.17x |
| Salesforce | 13.40x |
| IBM | 22.73x |
| Wipro | 14.56x |
| Infosys | 12.76x |
| TCS | 12.55x |

## 📐 Peer Group Statistics

The project calculates average and median valuation multiples separately for Indian peers, US peers and the overall peer group.

### Average EV/EBITDA

| Metric | India | USA | Overall |
|---|---:|---:|---:|
| 2026E | 10.67x | 11.52x | 11.20x |
| 2027E | 9.35x | 9.47x | 9.42x |

### Median EV/EBITDA

| Metric | India | USA | Overall |
|---|---:|---:|---:|
| 2026E | 11.30x | 12.26x | 11.55x |
| 2027E | 9.49x | 10.61x | 10.05x |

### P/E

| Metric | India | USA | Overall |
|---|---:|---:|---:|
| Average P/E | 13.29x | 23.07x | 19.40x |
| Median P/E | 12.76x | 25.32x | 18.65x |

## 🔍 Key Findings

### 1. US vs Indian Valuation

US technology companies trade at a higher average P/E multiple than Indian IT peers:

- **USA: 23.07x**
- **India: 13.29x**

This indicates a higher earnings valuation premium for the US peer group.

However, the average EV/EBITDA multiples are relatively closer:

- **2026E:** USA 11.52x vs India 10.67x
- **2027E:** USA 9.47x vs India 9.35x

### 2. EV/EBITDA Multiple Compression

EV/EBITDA declines from 2026E to 2027E across all companies.

This indicates that forecast EBITDA is expected to grow faster than Enterprise Value, resulting in multiple compression.

Oracle shows the sharpest compression:

**9.02x → 6.27x**

### 3. Highest-Valued Peers

Alphabet has the highest EV/EBITDA multiple in 2026E at **14.06x**, followed by Microsoft at **13.32x**.

Oracle has the highest P/E multiple at **28.17x**, followed by Microsoft at **25.71x** and Alphabet at **25.32x**.

### 4. Relatively Lower Valuation

Salesforce, Wipro, Infosys and TCS trade at comparatively lower P/E multiples than most US technology peers.

This highlights differences in market valuation across the two peer groups.

## 📊 Valuation Benchmarking Dashboard

The project includes a dedicated dashboard presenting:

- EV/EBITDA 2026E vs 2027E comparison
- P/E comparison
- EV/EBITDA multiple compression analysis
- Average valuation comparison between India and USA

These visualisations help interpret relative valuation differences across the selected peer group.

## 🧮 Methodology

The overall valuation process follows:

- **Market Capitalisation**
- **Enterprise Value Bridge**
- **EBITDA Calendarisation**
- **EV/EBITDA Calculation**
- **P/E Multiple Comparison**
- **Peer Group Statistics**
- **US vs India Valuation Benchmarking**

The methodology was implemented in Microsoft Excel using linked worksheets and formula-driven calculations.

## 🛠️ Tools & Techniques

- Microsoft Excel
- Comparable Company Valuation
- Trading Comparables
- Enterprise Value Analysis
- EV Bridge
- EBITDA Calendarisation
- EV/EBITDA Analysis
- P/E Analysis
- Peer Benchmarking
- Statistical Analysis
- Data Visualisation

## 📁 Project Workbook

The detailed analysis is maintained in the accompanying Excel workbook.

The workbook contains:

- Cover
- US Companies
- Indian Companies
- Calendarisation
- EV Bridge
- Final Comparables
- Peer Statistics
- Valuation Charts & Dashboard

## 🎓 Key Learning Outcomes

Through this project, I developed practical understanding of:

- Comparable company valuation
- Trading comparables methodology
- Enterprise Value calculation
- EV Bridge construction
- EBITDA calendarisation
- Forward valuation multiples
- Peer selection and benchmarking
- Multiple compression analysis
- Cross-country valuation comparison
- Excel-based financial analysis and visualisation

## 📌 Project Type

**Finance Project**

**Domain:** Valuation | Financial Analysis | Corporate Finance | Investment Banking

## ⚠️ Disclaimer

This project demonstrates the application of comparable company valuation techniques using selected market and financial data as of 31 July 2026. It is intended for research and educational purposes and should not be considered personalized investment advice or a direct recommendation to buy or sell any security.
