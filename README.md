
# Generic Test Protocol for the Integration Test of Automated Storage Systems on Rack or Tube Level

Kock-Schoppenhauer, A.K., Wagenzink, S., Stüdemann, M.K., Figge, L., Flügge, F., Simon, F., Maushagen,R., Habermann, J.K., Duhm-Harbeck, P.

IT Center for Clinical Research-Lübeck ([ITCR-L](https://itcr.uni-luebeck.de)), University of Lübeck, Germany <br>
Interdisciplinary Center for Biobanking-Lübeck ([ICB-L](ICB-L)), University of Lübeck, Germany <br>
Section for Translational Surgical Oncology and Biobanking, Department of Surgery, University of Lübeck & University Clinical Center Schleswig-Holstein, Campus Lübeck, Germany Ratzebergerallee 160, 23562 Lübeck

### Background
Automated storage systems (ASS) simplify sample handling and guarantee accurate timestamps and storage positions. However, this information can only be used entirely if there is an interface to the biobank management system. These interfaces are extensively verified by so-called integration tests, which test interconnected components of a complex system.
### Results
At the [ICB-L](ICB-L), we have linked several ASSs from different vendors to our biobank information system. In a jointapproach together with the ICB-L, we defined the workflows for storage and retrieval. Potential errors were considered and defined as generic error cases for device-independent testing. In our test scenario, we only consider operating errors, a technically functioning interface is assumed. 

We identified a total set of 11 test cases and divided the test-cases into three main categories: procedure was expected, procedure was not expected and a conditional error. The general workflows for storing and retrieving samples do not differ fundamentally but in detail. Based on the potential manual error sources, we created a testing protocol, which can be used as a blueprint for the successful integration of ASS. The error protocol is suitable for storage systems which work on rack level as well as on tube level.

### Discussion
The integration test ensures that the different modules, which were arranged together, act as a functional system correctly. We could successfully apply the error protocol at our integration test with the Askion HS200 and the biobank information system CentraXX.
