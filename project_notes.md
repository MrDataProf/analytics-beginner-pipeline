# Barbershop Analytics Project Notes

## Business Problem

The barbershop has data stored in different CSV files, but it cannot easily answer important business questions.

The goal of this project is to build a simple data engineering pipeline that turns raw CSV files into a clean data warehouse model for reporting.

## Source files

- customer.csv: customer information
- barbers.csv: barber information
- branches.csv: branch/location information
- services.csv: services offered
- booking.csv: appointment booking data
- payments.csv: payment transaction data

## Business Questions

- Which barber generates the most revenue?
- Which branch is the busiest?
- Which services are most important?
- What time of day has the most bookings?
- What is the total revenue over time?
- How many bookings are completed, cancelled, or no-show?
- Are there any missing values that affect reporting? 