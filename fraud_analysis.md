
### By identifying vendors with an irregular frequency of leading digits, I am hoping to identify fraudulent vendor payments.
<br/>

Below is a graph of the expected frequency of each leading digit based on Benford's Law.
![](https://github.com/mrkjhsn/City-of-Phoenix-Vendor-Payments/blob/master/visualizations/benfords_law.png)
<br/>
<br/>

Below is a graph of the frequency of leading digits of all vendors with at least 50 payments throughout all years of data.  The consesus is consistent with the percentages outlined by Benford's Law.
![](https://github.com/mrkjhsn/City-of-Phoenix-Vendor-Payments/blob/master/visualizations/leading_digit_frequencies_for_vendors_with_at_least_50_payments.png)
<br/>
<br/>

Below is a graph of the frequency of leading digits for vendors I have identified as anomalies bases on the irregular frequencies of their leading digits:
1. Vendors with a leading digit of 1 that made up 20% or less of that vendors total leading digits.
1. Vendors with a leading digit of 2 that made up 12% or less of that vendors total leading digits.
1. Vendors with a leading digit of 9 that made up 10% or more of that vendors total leading digits.

The thick red line indicates expected frequencies outlined by Benford's Law.
![](https://github.com/mrkjhsn/City-of-Phoenix-Vendor-Payments/blob/master/visualizations/Anomaly%20Vendors%20Based%20on%20Benford's%20Law.png)
<br/>
<br/>
