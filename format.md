# Privacy-sensitive Data Categorization (PsDC)



![Data Categorization and its Relationships into PsDC.](figs/relations.png)


Analyze Payload Data:

    - Plaintext/Cipher: Identify human-readable text or encrypted data.
    - Anonymized/Pseudonymized: Look for patterns indicating anonymization techniques (e.g., hashed values, random identifiers).
    - Metadata: Analyze packet headers and additional information for metadata related to social, technical, operational, and business aspects.


| Level 0          | Level 1           | Description                                                                                       | Example                                                                                      |
| ---------------- | ----------------- | ------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------- |
| Plaintext/Cipher |                   | Textual data in its original or encrypted form                                                    | "Hello, world!"                                                                              |
| Anonymized       |                   | Data that has been processed to remove personally identifiable information (PII)                  | A dataset with names and addresses replaced by unique identifiers                            |
|                  | Re-identification | The process of linking anonymized data to specific individuals                                    | Using external information to identify a person based on their anonymized data               |
|                  | Accuracy          | The degree to which anonymization techniques preserve the original data's statistical properties  | An anonymized dataset that accurately reflects the original data's distribution              |
|                  | Linkability       | The ability to connect different anonymized datasets to identify individuals                      | Linking two anonymized datasets based on common attributes (e.g., age, gender)               |
| Pseudonymized    |                   | Data where PII is replaced with pseudonyms                                                        | Replacing names with unique identifiers (e.g., "User123")                                    |
| Metadata         |                   | Data about data, providing context and information about its creation, collection, and processing | Information about the source of data, collection methods, and data quality standards         |
|                  | Social            | Metadata related to social aspects of data                                                        | cultural context of data, ethical guidelines for data use, and legal compliance requirements |
|                  | Technical         | Metadata related to the technical aspects of data                                                 | format, storage, and security                                                                |
|                  | Operational       | Metadata related to the operational aspects of data                                               | data flow, processing, and analysis                                                          |
|                  | Business          | Metadata related to the business context of data                                                  | purpose, value, and potential risks                                                          |

