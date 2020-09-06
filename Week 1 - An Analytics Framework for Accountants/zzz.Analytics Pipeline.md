# Analytics Pipeline

### Learning Objectives
```
1. Understand the system that enables analytics for a business
```

[DIAGRAM]
#### Detailed
Events -->  Captured Events --> Context and Enrichment --> Storage --> Processing --> Available Data Marts --> Reporting and Visualization

#### Simple
Events --> Captured Events --> Storage --> Monitoring --> Processing --> Reporting and Visualization

### 1. Events
For your business to capture anything, events must occur. An example of an event is a transaction, a website visit, a phone call, mobile logins, etc.

### 2. Captured Events
Not all events are captured by modern businesses. Advanced analytics firms capture as much as possible to provide business value for marketing, product design, and business strategy.
If the event occurs but is not captured into a business data system or data lake, no value can be captured from the event.

### 3. Storage
Storage may differ from captured events as the storage step records what is captured about the event, the format of the data, and any data controls to store that system data.


### Example:


#### Addendum: Cost of storage (Strategic Planning on Analytics)
With storage costs approximating $0.02 / GB / Month or $20.00 / TB / Month, storing events is cheap. One TB annually is $240 and would allow a system to capture a billion events (where each event is approximated at 1 KB). Storage is cheap.
*Storage costs retrieved 2020 Q3, frequent access tier. Infrequent access is cheaper.

#### Addendum: Data Validation (IT / Data Control)
Reducing data errors can easily be improved by using data validation at the event stage - data validation ensures data entered by a user, form, API, application, etc. conforms to a set format to ensure consistent and usable data once captured by the system.

