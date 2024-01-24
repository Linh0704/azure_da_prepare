Microsoft Purview: a unified data-governance service

3 main elements:
- Data Map
- Data Catalog
- Data Estate Insights


Source data

Map data:
- Data assets.
- Data lineage.
- Data classifications.
- Business context.

Scan data: 

- run a scan to access their metadata and browse the asset information.
- A **scan rule set** is a container for grouping scan rules together to use the same rules repeatedly. 

Classification:
- Government: Attributes such as government identity cards, driver license numbers, and passport numbers.
- Financial: Attributes such as bank account numbers or credit card numbers.
- Personal: Personal information such as a person's age, date of birth, email address, and phone number.
- Security: Attributes like passwords that can be stored.
- Miscellaneous: Attributes not included in the other categories.


### Browse & Search:

Data lineage

Search assets:
- Data Catalog: Contoso catalog
- Asset:
    + overview
    + schema
    + lineage
    + contacts and related assets

Browse assets
- By Collection
- By source type

Power BI
- Request access to assets
- Build Power BI report
- Scan a Power BI tenant


### Cataglog Artifacts

Collections also provide a security boundary for your metadata in the data map. Access to collections, data sources, and metadata is set up and maintained based on the collection’s hierarchy in Microsoft Purview, following a least-privilege model:

- Users have the minimum amount of access they need to do their jobs.
- Users don't have access to sensitive data that they don't need.

Register data source

Scan data source

Roles & permissions
