.. MSK Blaze documentation master file, created by
   sphinx-quickstart on Tue Jun 18 09:01:27 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

============================================
MSK Blaze FHIR Server Documentation
============================================

Clinical trials attempt to answer questions. To help do this effectively, it’s important to leverage best in class technology to rapidly increase the speed with which research 
data can be shared and tear down barriers that impede this process. Sharing research data faster can lead to better outcomes for patients, less time spent on manual coding and 
redundant data mapping, and reduced costs typically associated with new drug or therapy development. 
By leveraging the HL7 FHIR standard (Fast Healthcare Interoperability Resources), academic sites and clinical trial sponsors can unite to achieve these shared goals.

To this end, Memorial Sloan Kettering (MSK) has developed a FHIR server for clinical research data. This server is named "Blaze." 


Core Features
=============

- Complaince with FHIR version 4.0.0
- OAuth (client_credentials) authentication flow
- Coverage of the following FHIR Resources:

  - Observation (e.g. Laboratory Results)

Guide
=============

.. toctree::
   :maxdepth: 2

   index
   introduction
   getting_started
   core_resources


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
