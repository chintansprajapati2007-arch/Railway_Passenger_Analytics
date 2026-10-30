# Railway Passenger & Ticket Booking Analysis Dashboard

## Project overview
An interactive browser-based dashboard for analyzing passenger bookings and ticket transactions. It includes:
- KPI cards: total bookings, total passengers, booking revenue, confirmed booking rate
- Pie/doughnut chart: ticket class distribution
- Horizontal bar chart: routes with the highest passenger counts
- Column chart: monthly ticket bookings
- Filters: ticket class, route, booking status, and month
- CSV download button inside the dashboard

## Files
- `railway_analytics_dashboard.html` — interactive dashboard
- `railway_bookings_50000.csv` — 50,000 sample booking records for Power BI / Excel
- `README.md` — project instructions

## How to run
1. Extract the ZIP file.
2. Open `railway_analytics_dashboard.html` in Chrome, Edge, or Firefox.
3. Internet access is required to load Chart.js from its CDN.
4. Use the dropdown filters to update the KPIs and charts.
5. Click **Download CSV dataset** to export a CSV from the dashboard.

## Dataset fields
`Booking_ID`, `Booking_Date`, `Month`, `Route`, `Origin`, `Destination`, `Ticket_Class`, `Passengers`, `Booking_Amount_INR`, `Booking_Status`, `Booking_Channel`

## Open in Power BI
1. Open Power BI Desktop.
2. Select **Get Data → Text/CSV**.
3. Choose `railway_bookings_50000.csv`.
4. Select **Load**.
5. Use the fields above to recreate the visuals or build additional reports.

## Important data disclaimer
The 50,000 records are synthetic sample data generated for educational/demo purposes. They are not live, official, or historical Indian Railways / IRCTC transactions. The dashboard is interactive, but the dataset itself is static sample data. It does not connect to a railway booking system or show real-time train availability.
