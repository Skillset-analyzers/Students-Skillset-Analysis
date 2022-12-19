# Anonymizing Datasets
<img src="https://user-images.githubusercontent.com/76547274/208484841-3c28bf04-82fc-4a9c-8d45-cf332224f743.jpg" height=210 align="right">

### What is Anonymization of Data?
Data anonymization refers to the method of preserving private or confidential information by deleting or encoding identifiers that link individuals to the stored data. It is done to protect the private activity of an individual or a corporation while preserving the credibility of the data collected and exchanged.<br>
<br>Data anonymization is one of the techniques that organizations can use to adhere to strict data privacy regulations that require the security of personally identifiable information (PII), such as health reports, contact information, and financial details. <a href="https://corporatefinanceinstitute.com/resources/business-intelligence/data-anonymization/">Read more...</a>
<br>
### Why do we need to anonymize our data?
We need to anonymize our data in order to maintain privacy concerns of particpants of our survey. The survey included questions on personal background, education, skills and achievements of individuals, which can be misused if exposed to users with malicious intent.<br>
<br>To avoid any such experiences, I am anonymizing the dataset so that all such possible activities can be reduced. I expect by this step of mine I'll be able to contribute to positive data experience for all.
<br><br>
<img src="https://user-images.githubusercontent.com/76547274/208498957-d9b73695-9aa6-466e-81b8-1da212d88bc9.png" alt="Sample Anonymization">


#### What work have I done to anonymize data?
To anonymize data, I had the chance to opt either for masking or removing the columns which could be used to track specific contributors. I am removing the fields *Name* and *KIET E-mail ID*.<br> I am also removing the field *I Would like to participate in the Research work in Future* as it is irrelevant to our current scope of analysis.
<br>
### Future Scope
1. Make an automized application which can directly remove the specified columns.
2. Trying masking the *KIET E-mail ID* field or adding the feature to extract domain from the email id.
