

##  Extending the Portfolio

To add more queries:

1. Copy an existing `.query-card` block.
2. Update the title, SQL code, sample output table, and description.
3. Add relevant concept badges.
4. Modify the `sendPrompt()` function to integrate with a real backend if needed.

## 📝 Sample Data Note

The sample outputs shown are realistic mock data for illustration. To run these queries against real data:
- Replace the table names with your actual retail schema.
- Adjust date filters and column names as needed.
- The SQL patterns work on PostgreSQL, MySQL 8+, Snowflake, BigQuery, and others with minor syntax adjustments.

##  Contributing Ideas

Suggested query extensions (available via the "Ask AI" buttons):
- Month-over-month revenue growth using `LAG()`
- Customers with zero purchases (`LEFT JOIN` filtering)
- Rolling 90-day average for anomaly detection
- Cohort retention month-by-month
- Discount erosion percentage calculation

## 📄 License

MIT – Free to use, modify, and distribute for learning and commercial purposes.

---

**Built with ❤️ for retail data analysts and  enthusiasts.**
