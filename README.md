DecodeLabs Data Analytics Internship Project 1: Data Cleaning & Preparation 
Objective: The objective of this data cleaning process was to prepare the E-Commerce dataset for analysis by identifying and correcting errors, inconsistencies, missing values, and invalid entries.

Dataset Information: 
The dataset contains the following columns: OrderID Date CustomerID Product Quantity UnitPrice ShippingAddress PaymentMethod OrderStatus TrackingNumber ItemsInCart CouponCode ReferralSource TotalPrice 

Data Cleaning Tasks Performed
1. Removed Duplicate Records Checked for duplicate rows using Excel's Remove Duplicates feature. Ensured that each order record is unique.
2. Handled Missing Values CouponCode Column Missing/null values in the CouponCode column were replaced with: NO_COUPON 
3. Standardized Date Format: Converted all date values into a consistent format: YYYY-MM-DD 
4. The numeric columns (Quantity, UnitPrice, ItemsInCart, and TotalPrice) were validated for negative, missing, and non-numeric values using Excel filters and validation formulas. No invalid or negative values were found.
5. I Created Cleaned Dataset and saved the cleaned version of the dataset in a separate worksheet named: Cleaned Dataset This preserves the original raw data for reference.

Conclusion
The dataset was successfully cleaned and validated. Text values were standardized, numeric columns were verified for invalid entries, and the data is now suitable for exploratory data analysis and visualization.

