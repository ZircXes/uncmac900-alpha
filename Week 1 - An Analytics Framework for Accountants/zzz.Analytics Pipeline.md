# Analytics Pipeline

### Learning Objectives
```
1. Understand the system that enables analytics for a business
```

## Analytics Pipeline
[DIAGRAM]
Events --> Captured Events --> Storage --> Monitoring --> Processing --> Reporting and Visualization

### 1. Events
For your business to capture anything, events must occur. An example of an event is a transaction, a website visit, a phone call, mobile logins, etc.

### 2. Captured Events
Not all events are captured by modern businesses. Advanced analytics firms capture as much as possible to provide business value for marketing, product design, and business strategy.
If the event occurs but is not captured into a business data system or data lake, no value can be captured from the event.

### 3. Storage
Storage may differ from captured events as the storage step records what is captured about the event, the format of the data, and any data controls to store that system data.

### 4. Monitoring
Monitoring used to imply operational monitoring of data systems, but now as data capture grows, the vast majority of data is not curated beyond the data model designed by your technology or data lake architects. Monitoring now implies automated curation, quality, and recommendations around your data to improve your analytics capabilities.

### 5. Processing
Data is often stored in multiple locations (redundancy) which is typically due to business requirements or preparation of data marts for end users. Processing moves data across systems for specific business purposes. Redundancy can create control problems and reconciliation problems; however, it is difficult to completely eliminate this problem and so analysts should be aware of this.

### 6. Reporting and Visualization
At the last stage, end-users use data from various curated data sources for production processes, visualization, ad-hoc analytics, modeling, and reporting. Often specialized processes are setup for key financial reporting requirements to reduce manual steps and risk of error.

## Examples

#### Example for multiple reporting processes automated
Banks are required to prepare standard financial reports, but are also required to file various regulatory filings (e.g. call reports, business forecasts, etc.). Often, due to different rules and reporting requirements, including heirarchies and aggregation, these may be pulling from the same systems but have different processing data marts or rules to automate the reporting. Reconciliation between systems can be difficult if these processes are maintained in isolation.

#### Example for Processing and Multiple Data systems
Sample simple organizational data pipeline
1. Data from events are captured in a source system (the interface with customers for example or the tool used by an operations team or a call center).
2. Data is moved to a centralized data environment known as a data lake (or possibly a data warehouse).
3. Data is curated for less-technical end users in the form of a data mart.
4. Multiple data marts may be created which have cross-dependencies (e.g. multiple data marts may have overlapping data from the upstream process) and these may have different requirements or business rules that can create differences.

An example of how data marts can differ might be a GL system vs. a reporting system. The GL system is expected to include all accounting factors which can include amortization, depreciation, accrued interest, fees, etc; however a simple reporting mart for an end user might just have the baseline transaction amount. Alternatively the GL system may be capturing payments in temporary accounts that are unmapped which would lead to differences to a simple reporting data mart.

#### Example for monitoring

## Summary
Understanding the analytics pipeline is important in order to understand how to add business value, where to capture the data, where controls may be required, or how the process can be improved to create business value. As more accounting data feeds into strategic planning and business decision-making, accountants can contribute to the value of analytics at the firm.

## Addendums

#### Addendum: Cost of storage (Strategic Planning on Analytics)
With storage costs approximating $0.02 / GB / Month or $20.00 / TB / Month, storing events is cheap. One TB annually is $240 and would allow a system to capture a billion events (where each event is approximated at 1 KB). Storage is cheap.
*Storage costs retrieved 2020 Q3, frequent access tier. Infrequent access is cheaper.

#### Addendum: Data Validation (IT / Data Control)
Reducing data errors can easily be improved by using data validation at the event stage - data validation ensures data entered by a user, form, API, application, etc. conforms to a set format to ensure consistent and usable data once captured by the system.

#### Addendum: Data / AI Flywheel
The data flywheel (now marketed by Amazon AWS) or the more traditional Artificial Intelligence (AI) flywheel is the concept that core business processes should encourage the creation of new data to increase the value of the analytics pipeline. An example is Netflix, as users interact with the system (events), the system runs experiments and analytics to improve profitability / user experience. These improvements lead to continued use fo the platforms (more events) and the process is self-perpetuating. This is different from a closed analytics pipeline where the process does not have a direct feedback loop that encourage new Events.

### References

