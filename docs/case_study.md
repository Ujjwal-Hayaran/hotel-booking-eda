# Case Study: Hotel Harmony

**Company:** Elite Hotels International (fictional scenario)

## Problem

Elite Hotels International runs hotels in several locations and finds it hard to manage booking patterns while keeping guests happy. Management wants to know how guests book, who they are and why some bookings are cancelled, so they can improve operations, guest satisfaction and revenue.

**Goal:** use the booking data to find insights and recommend actions.

## Who cares about the answers

| Team | What they want |
|---|---|
| Management | Evidence for decisions |
| Operations | Staffing, rooms, parking |
| Marketing | Where and when to run campaigns |
| Customer service | What guests ask for |
| Travel agencies (external) | A reliable partner |

## Data dictionary

32 columns, 119,390 rows (87,396 after removing duplicates).

| Column | What it means |
|---|---|
| hotel | Resort Hotel or City Hotel |
| is_canceled | 1 if cancelled, 0 if not |
| lead_time | Days between booking and arrival |
| arrival_date_year / month / week_number / day_of_month | Arrival date parts |
| stays_in_weekend_nights | Weekend nights (Sat or Sun) booked |
| stays_in_week_nights | Week nights (Mon to Fri) booked |
| adults, children, babies | Number of guests of each type |
| meal | Meal plan (BB, HB, FB, SC/Undefined) |
| country | Country of origin (3-letter code) |
| market_segment | Type of customer segment (Online TA, Direct, Groups...) |
| distribution_channel | Route the booking came through |
| is_repeated_guest | 1 if a repeat guest |
| previous_cancellations | Past bookings this guest cancelled |
| previous_bookings_not_canceled | Past bookings this guest kept |
| reserved_room_type | Room type reserved (letter code) |
| assigned_room_type | Room type actually assigned |
| booking_changes | Changes made after booking |
| deposit_type | No Deposit, Non Refund or Refundable |
| agent | ID of the travel agent (blank if none) |
| company | ID of the company (blank if none) |
| days_in_waiting_list | Days before the booking was confirmed |
| customer_type | Contract, Group, Transient, Transient-party |
| adr | Average daily rate (revenue per night stayed) |
| required_car_parking_spaces | Parking spaces requested |
| total_of_special_requests | Number of special requests |
| reservation_status | Canceled, Check-Out or No-Show |
| reservation_status_date | Date of the last status |

## Questions

**Basic**
1. What is the average lead time?
2. What is the distribution of bookings by hotel type?
3. How many bookings were cancelled?
4. What is the most common arrival month?
5. What is the average number of special requests per booking?
6. Which country has the most bookings?
7. What is the average ADR for each hotel type?
8. What percentage of guests needed parking?
9. What is the average stay in week nights and weekend nights?
10. How many bookings were made through travel agents?

**Medium**
11. What is the cancellation rate for each hotel type?
12. What is the average ADR per market segment?
13. What is the relationship between lead time and cancellation?
14. Which distribution channel has the most bookings?
15. What is the average number of previous cancellations by hotel type?
16. What is the trend of ADR over the years?
17. Which month has the highest revenue?
18. What is the impact of special requests on ADR?
19. What is the average stay for repeated vs new guests?
20. Which room type is booked the most?

**Advanced**
21. What factors significantly affect cancellations?
22. How does ADR vary with the number of adults, children and babies?
23. What is the relationship between booking changes and special requests?
24. What is the seasonal impact on cancellations?
25. How does lead time vary between market segments?

## Final output

A summary of findings, recommendations for management, and areas for further investigation.
