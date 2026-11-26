# Fiona (Yi Fei) Chen

**Master of Data Science student, University of Sydney** · Sydney, Australia
fionachen0811@gmail.com · [GitHub](https://github.com/yche9837) · [Project code](https://github.com/yche9837/Portfolio)

I build reproducible data pipelines and models, and I write up the results for the people who have to act on them. My background combines computing and commerce, with front-line experience in banking.

## Skills
- **Languages:** Python (pandas, scikit-learn, statsmodels), SQL (PostgreSQL, PostGIS), R, Java, TypeScript
- **Data & cloud:** data cleaning and modelling, machine learning, time series forecasting, data visualisation, AWS
- **Tools:** Git/GitHub, Jupyter, Jira, Gradle, Jenkins, Next.js, Prisma, MS Office, SAP CRM
- **Certifications:** AWS Certified Cloud Practitioner (CLF-C02, Jan 2026) · Working with Children Check
- **Languages spoken:** English, Mandarin

---

## Projects

### Hotel Booking Cancellation Prediction | University of Sydney (2026)
[Link to the project](https://github.com/yche9837/comp5310PeerAsm2) · COMP5310 · group of 2 · **19.22/20**
- Predicted which confirmed hotel bookings would be cancelled or end in a no-show, so a revenue manager could follow up with at-risk guests before arrival.
- Built the data pipeline: cleaned ~120k raw bookings to 87,114 records, used chi-squared tests to decide how each column's missing values should be handled, removed fields that would leak the outcome, and wrote a data dictionary.
- Designed leakage-safe scikit-learn pipelines with stratified 10-fold cross-validation, and tuned logistic regression and random forest models against two baselines.
- The final random forest reached **F1 0.672, recall 0.751** on a held-out test set, against 0.490 for a one-rule baseline.
- Ran error analysis by booking group and a time-based robustness check, and presented the results as a decision report for a non-technical manager.
- Fully reproducible: pinned requirements, a fixed seed, and notebooks that regenerate every table and figure.

### Spatial Analysis of the Liveability of Sydney | University of Sydney (2022)
[Link to the project](https://github.com/yche9837/Portfolio/tree/main/liveability-of-sydney-sql-postgis) · team of 3 (team lead) · High Distinction
- Designed a PostgreSQL/PostGIS schema of 10+ tables and loaded cleaned business, transport, school, polling-place, population and income data into it.
- Added GiST spatial indexes and calculated liveability metrics with spatial joins in SQL.
- Combined the metrics into a z-score and sigmoid liveability score for each SA2 region, then extended it with three more datasets (JSON, spatial and CSV).
- Delegated tasks across the team and was the main presenter.

### Capstone: CRISP-DM Approach to Boost BIGW Sales Units with Bundling | University of Sydney & BIGW (2024)
(Confidential project, so no link is available.)
- Designed a bundle strategy that pairs high-demand products with underperforming ones, using price elasticity and seasonality insights.
- Compared linear regression, ridge and random forest models, using PCA to handle multicollinearity; random forest performed best on RMSE and MAE.
- Chosen as one of the top two groups to present to BIGW executives.

### Time Series Analysis of Solar Power Production | University of Sydney (2023)
[Link to the project](https://github.com/yche9837/Portfolio/tree/main/solar-power-forecasting) · High Distinction
- Forecast household solar production for the next 24 hours, 7 days and 12 months from half-hourly data.
- Compared random walk, seasonal random walk, Holt-Winters, damped Holt and ARIMA models by MAE, with residual diagnostics.

### Data-Driven Predictive Model for Wine Expenditure | University of Sydney (2023)
[Link to the project](https://github.com/yche9837/Portfolio/tree/main/wine-expenditure-prediction) · High Distinction
- Predicted customer wine spending from 2,240 customers and 28 variables, comparing linear regression, KNN and random forest by MAE.
- Checked the final model for fairness using statistical parity and disparate impact.

### Agile Scrum Software Development | University of Sydney (2023)
[Order Management](https://github.com/yche9837/Portfolio/tree/main/order-management-java-agile) · [Scroll Management](https://github.com/yche9837/Portfolio/tree/main/scroll-management-java-scrum) · Distinction
- Built two Java applications with a team of 4 using Kanban and Scrum. I was Scrum Master and a developer.
- Used Jira, Git, Gradle, Jenkins CI, JUnit and JaCoCo, and was the main presenter to the client.

---

## Experience

**Customer Banking Specialist | Commonwealth Bank of Australia (Mar 2026 – present)**
- Provide front-line banking support in a high-volume Sydney CBD branch, handling transactions, account enquiries and day-to-day banking needs.
- Apply Tier 2 product and service knowledge to resolve more complex requests, while maintaining compliance standards.

**Web Developer Intern | Next Step Education (Nov 2025 – Feb 2026)**
- Built a full-stack education platform (Next.js, TypeScript, PostgreSQL) with role-based portals for 100+ students, parents and administrators.
- Designed the database schema and RESTful APIs with Prisma ORM, and built dashboards for tracking student progress.
- Added secure authentication with role-based access control, and English/Chinese language support.

**Full-Stack Web Developer Intern | Snow Point Collectibles (Nov 2025 – Jan 2026)**
- Delivered an e-commerce platform (Next.js, React, TypeScript, PostgreSQL) with a product catalogue, cart and checkout.
- Built the order processing pipeline, Square and PayPal payments, real-time shipping quotes through the Easyship API, and an admin dashboard with revenue analytics and inventory alerts.

**Dyson Expert | Dyson Appliances (Aust.) Pty Limited (Jun 2024 – Aug 2026)**
- Ranked 1st salesperson at the Moore Park demo store, generating $900k in annual revenue as of 2025.
- Placed 2nd among all Dyson retail store employees in APAC's July–August Recognition Program.

**Academic Tutor | Self-employed, OLA Tutoring & Art of Smart Education (Nov 2020 – Oct 2024)**
- Tutored Year 11/12 Economics, EAL/D, Biology and Mathematics students, many of whom reached top-10 internal rankings and Band 5/6 HSC results.
- Nominated for the Student Success (Secondary) and Coach of the Year (1-on-1 Tutoring) awards.

**Other experience**
- **STEM Industry Challenge, Practera (2023):** recommended ways for Resteel Recycling to source industrial scrap within a $12k budget. The client rated the report "outstanding quality".
- **Study Australia Industry Experience Program (2022):** built a funding strategy for the non-profit FreedomForHumanity.
- **Test Administrator, Pearson (2023):** administered ACARA item trials for Years 3–7.
- **Election Official, Australian Electoral Commission (2023):** issued ballot papers and counted votes.
- **Volunteer Mentor, Practera (2024):** mentored ANU student teams on a 3-week consulting project.

---

## Education

**Master of Data Science | University of Sydney (2026 – present)**
- Mentee in the Dell Technologies STEM Aspire Mentorship Program.

**Bachelor of Advanced Computing (Data Science) / Bachelor of Commerce (Business Analytics) | University of Sydney (2021 – 2025)**
- Mentee in the Lucy Mentoring Program (Levi's) and the E12 Professional Mentoring Program (Sydney Metro).
- Member of the Business Analytics Association and the Mandarin Debating Society.

**HSC | Cheltenham Girls' High School (2020)**
- ATAR 98.45 · ranked 1st at school in EAL/D and Economics.

## Other
- **Piano:** AMEB 8th Grade Practice of Music (Credit); 5th Grade Theory of Music.
- **Event Staff, Sydney Robotics Competition (2018)**
