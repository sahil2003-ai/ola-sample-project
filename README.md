# Ola Ride Bookings: SQL Analysis and Power BI Dashboard

A ride-booking analytics portfolio project documenting operational questions around booking outcomes, vehicle types, cancellations, ratings, payment methods, and revenue.

## Repository files

| File | Purpose |
|---|---|
| `Database Ola.docx` | Project brief / documented database questions |
| `ola dashboard.pbix` | Power BI report |
| `README.md` | Project documentation |

## Analysis goals

- Review booking outcomes and cancellation patterns.
- Compare available vehicle types, ratings, and payment methods.
- Inspect the revenue and distance measures available in the report.
- Translate validated metrics into operational questions.

These are intended analysis areas based on the project files, not claims that a particular numerical result has been verified.

## Tools

- SQL concepts described in the project brief
- Microsoft Power BI Desktop

## How to review and reproduce

1. Read `Database Ola.docx` and extract the actual business questions, tables, fields, and KPI definitions.
2. Open `ola dashboard.pbix` in Power BI Desktop.
3. Confirm the source connection, refresh state, model schema, and reporting period.
4. Check how bookings, completed rides, cancellations, ratings, and revenue are defined.
5. Validate the dashboard totals against the underlying source data.
6. Capture dashboard screenshots and add a table of the resulting KPIs.

## Verified results status

The visible repository inventory contains a Word brief and PBIX file, but no standalone dataset or SQL script. The connector review did not expose the PBIX's internal model or the brief's full content in a form that allowed independent recalculation. Therefore, this README intentionally omits booking counts, cancellation rates, customer ratings, and revenue totals instead of guessing them.

## Limitations

- Dataset provenance, schema, currency, and reporting period need explicit documentation.
- Confirm that KPI definitions distinguish all bookings from completed bookings and cancelled bookings.
- Cancellation patterns are descriptive and do not by themselves establish the cause of cancellations.

## Recommended additions

- [ ] Add the data dictionary and dataset source/license.
- [ ] Add SQL scripts used for the analysis, if applicable.
- [ ] Export a verified KPI summary.
- [ ] Add real dashboard screenshots and explain key findings.

## Skills demonstrated

Business-question framing, ride-booking operational analysis, SQL concepts, KPI verification, and Power BI reporting.

## Author

Sahil Gaikwad · [GitHub](https://github.com/sahil2003-ai) · [LinkedIn](https://www.linkedin.com/in/sahil-gaikwad-a76b7224a/)
