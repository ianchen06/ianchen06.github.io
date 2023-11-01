Summary of [Setting up a Modern Data Stack for your Startup - A easy 6 step guide](https://www.youtube.com/watch?v=8Ue469PBS-8&list=PLpl37lLtfRJ4PcSm10GolN83nRxzCp0u4&index=2&t=2s&pp=gAQBiAQB)

- The modern data stack needs to make data actionable by reducing time and complexity. Key principles are centralizing data in a data warehouse, using ELT instead of ETL, minimizing engineering effort with no/low code tools, and implementing engineering best practices.

- The first step is hiring a data engineer to set up a cloud data warehouse like BigQuery or Snowflake to store all your data centrally.

- Tag all your data at the source (website, product, etc) using a tool like Segment or open source RudderStack. This provides a single source of truth for customer data.

- Use a data ingestion tool like Fivetran or Airbyte to automatically extract and load raw data from SaaS tools into your data warehouse.

- Transform raw data into usable formats with SQL views and tables using a tool like DBT. Document and test data thoroughly.

- Visualize transformed data with a BI tool like Looker, Google Data Studio, or open source Metabase. Don't build transformation logic here.

- Send transformed data back to SaaS tools via reverse ETL tools like Hightouch and Census to keep teams in sync.

- Orchestrate your entire data stack end-to-end with a tool like Shipyard or open source Airflow. Connect tools, handle errors, fill gaps.

- Once foundation is built, hire data analysts and scientists to generate value from your data.

- Ideal data team makeup is 2-5% of personnel, with data engineer first, then analytics engineer, analyst/scientist, and manager.


Summary of [The Modern Data Stack: Everything You Need to Know (Chris Tabb) - KNN Ep. 139](https://www.youtube.com/watch?v=kNBrk2ZdhNA&list=PLpl37lLtfRJ4PcSm10GolN83nRxzCp0u4&index=8)

- Chris's background is in finance and accounting, but he transitioned into data/analytics at Cognos in the 1990s, learning by taking available training courses. He became knowledgeable by learning how all the pieces fit together - ETL, databases, reporting tools.

- There have been three eras of data architecture:
  - Original data warehouse era - Focused on business needs, simple architecture with few vendors, but not agile or fast moving
  - Big data era - Open source and "data lake" focus, more engineering than business focused, did not emphasize data modeling
  - Modern data stack - Cloud and SaaS based tools, business accessible again, but complex with many niche vendors

- Consolidation is happening again with acquisitions, which provides simplicity but risks backing the wrong vendor. Migrations between vendor stacks can be complex.

- Architectural skills and data modeling are a "lost art" - important to bridge business needs and technical implementation.

- Breaking down domains into subdomains into logical/conceptual/physical models provides context and understanding. Knowing how business needs map to architecture enables flexibility.

- The ability to create reusable data assets and integrate them is key. This comes from good data modeling practices.

- Focus on business capabilities, not technologies. Technologies just enable capabilities.

- Plan changes incrementally, in thin slices focused on highest value. Avoid big bang migrations.

- Selling and communication skills become more important as you move up in organizations. Continuous learning from others is key to avoid arrogance.

- There are some regional differences in practices and vendor popularity, but core problems faced are quite similar.

- Understanding how budgets, accounting rules, capex vs opex influence decisions is important context.
