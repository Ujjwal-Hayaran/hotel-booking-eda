# Short answers

Numbers are from the cleaned data (87,396 bookings, duplicates removed). Full code and charts are in `notebook/hotel_booking_eda.ipynb`.

## Basic

| # | Answer |
|---|---|
| 1 | Mean lead time **79.9 days** (median 49) |
| 2 | City Hotel **53,428** (61%), Resort Hotel **33,968** (39%) |
| 3 | **24,025** cancelled (27.5%) |
| 4 | **August** (11,257 bookings) |
| 5 | **0.70** special requests per booking |
| 6 | **Portugal**, 27,453 bookings (31%) |
| 7 | City Hotel **111.0**, Resort Hotel **99.0** |
| 8 | **8.4%** (Resort 15.9%, City 3.5%) |
| 9 | **2.63** week nights, **1.01** weekend nights (3.63 total) |
| 10 | **75,203** bookings (86%) had a travel agent |

## Medium

| # | Answer |
|---|---|
| 11 | City Hotel **30.0%**, Resort Hotel **23.5%** |
| 12 | Online TA **118.2**, Direct **116.6**, Aviation 100.2, Offline TA/TO 81.8, Groups 74.9, Corporate 68.2 |
| 13 | Cancellation rises with lead time: **8.4%** (0 to 7 days) up to **40.9%** (365+ days). Correlation 0.18 |
| 14 | **TA/TO**, 69,141 bookings (79%) |
| 15 | City Hotel **0.036**, Resort Hotel **0.022** |
| 16 | ADR **92.2 (2015), 101.5 (2016), 118.7 (2017)**. Caution: months covered differ by year |
| 17 | **August**, then July. ADR x nights, cancelled stays excluded |
| 18 | ADR rises with requests (**99.7 with none to 131.1 with four**). Correlation 0.14 |
| 19 | Repeated **1.93 nights**, new **3.70 nights** |
| 20 | Room type **A** (56,552 bookings, about 65%) |

## Advanced

| # | Answer |
|---|---|
| 21 | Strongest drivers: past successful stays (lower risk), past cancellations (higher risk), lead time (higher), ADR (higher), special requests and booking changes (lower). Model accuracy 74.3%, but it catches only 16% of cancellations |
| 22 | Each extra child about **+38**, adult about **+20**, baby about **+7**. R² is only 0.20 |
| 23 | Almost no relationship (correlation **0.016**). Special requests are not a satisfaction measure |
| 24 | Summer highest (**31.6%**), autumn lowest (**23.3%**). Resort swings from 31% (summer) to 17% (winter) |
| 25 | Median lead time: Groups **114**, Offline TA 82, Online TA 55, Direct 15, Corporate 5, Aviation 3 days |
