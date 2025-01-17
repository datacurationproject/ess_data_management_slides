# ESS Data Management Slides




### <span style="text-transform: none">BrightnESS</span> Data Management Plan
Gareth Murphy

ESS DMSC

2017-09-14

# Managing and Curating Neutron Data at the European Spallation Source (ESS)

## **Introduction**
The European Spallation Source (ESS) generates vast amounts of neutron data from its state-of-the-art instruments. Managing and curating this data effectively is essential to ensure scientific reproducibility, compliance with FAIR (Findable, Accessible, Interoperable, Reusable) principles, and the facilitation of advanced data analytics and machine learning applications.

This document provides a comprehensive guide to managing and curating neutron data at ESS, covering key processes, tools, and strategies to optimize data workflows.

---

## **1. Data Lifecycle at ESS**

### **1.1. Data Acquisition**
- **Instrumentation:** Neutron instruments at ESS produce raw data from experiments, capturing interactions between neutrons and sample materials.
- **Metadata Capture:** Real-time recording of experimental parameters (e.g., sample ID, beam settings, temperature).
- **Data Formats:** Use standardized formats like NeXus (HDF5-based) for compatibility and interoperability.

### **1.2. Data Processing**
- **Calibration and Correction:** Apply instrument-specific calibration and corrections to raw data.
- **Reduction Pipelines:** Convert raw data into scientifically meaningful units (e.g., scattering intensity, reflectivity).
- **Software Tools:** Use ESS-supported platforms (e.g., Mantid) for data reduction.

### **1.3. Data Storage**
- **Short-term Storage:** Store raw and processed data on high-speed storage systems for immediate access.
- **Long-term Archival:** Migrate data to high-capacity, redundant storage systems for preservation.
- **Backup Policies:** Regularly back up data to ensure recovery in case of system failures.

### **1.4. Data Analysis**
- **Analysis Software:** Provide researchers with robust tools for data visualization and interpretation (e.g., Python libraries, Jupyter Notebooks).
- **Collaboration:** Facilitate collaborative analysis by enabling shared access to data and software environments.

### **1.5. Data Publication**
- **DOI Assignment:** Assign Digital Object Identifiers (DOIs) to datasets to ensure traceability.
- **Publication Repositories:** Deposit datasets in recognized repositories like ESS Dataportal or Zenodo.
- **Supplementary Materials:** Link datasets to related publications, experimental logs, and protocols.

---

## **2. FAIR Data Management Principles**

### **2.1. Findable**
- **Metadata Standards:** Ensure datasets are annotated with rich, standardized metadata.
- **Searchability:** Develop advanced search functionalities to locate datasets using keywords, sample IDs, or experiment parameters.
- **Persistent Identifiers:** Use DOIs or similar identifiers to ensure datasets are uniquely findable.

### **2.2. Accessible**
- **Access Policies:** Define clear access levels (e.g., public, restricted, or embargoed).
- **Authentication Systems:** Implement secure authentication for user-specific access.
- **Data Portals:** Provide intuitive web interfaces for data discovery and download.

### **2.3. Interoperable**
- **Standard Formats:** Adopt NeXus and other widely recognized formats for data sharing.
- **APIs:** Develop RESTful APIs for programmatic access to datasets.
- **Ontologies:** Use domain-specific ontologies to describe data and metadata consistently.

### **2.4. Reusable**
- **Licensing:** Apply clear, permissive licenses (e.g., Creative Commons) to datasets.
- **Documentation:** Provide detailed documentation on data formats, processing pipelines, and analysis methodologies.
- **Quality Assurance:** Implement robust validation processes to ensure data accuracy and reliability.

---

## **3. Data Governance and Policies**

### **3.1. Roles and Responsibilities**
- **Data Stewards:** Ensure compliance with FAIR principles and manage metadata quality.
- **Instrument Scientists:** Oversee data acquisition and provide guidance on processing workflows.
- **IT Teams:** Maintain infrastructure for data storage, backup, and security.

### **3.2. Data Retention Policies**
- **Raw Data:** Retain for a defined period (e.g., 10 years), subject to ESS policies.
- **Processed Data:** Retain indefinitely for reproducibility and reuse.
- **User Data:** Allow users to specify retention preferences for non-critical datasets.

### **3.3. Security and Privacy**
- **Encryption:** Encrypt data during transfer and storage to prevent unauthorized access.
- **Anonymization:** Remove or mask sensitive information from datasets.
- **Monitoring:** Implement systems to detect and respond to potential data breaches.

---

## **4. Tools and Technologies**

### **4.1. Data Management Platforms**
- **ESS Dataportal:** Centralized platform for dataset storage, discovery, and access.
- **ICAT:** Middleware for cataloging and retrieving experimental metadata.

### **4.2. Processing and Analysis Tools**
- **Mantid:** For neutron data reduction and visualization.
- **Python Ecosystem:** Libraries like NumPy, SciPy, and matplotlib for custom analyses.
- **Jupyter Notebooks:** For interactive data analysis and sharing workflows.

### **4.3. Automation and Integration**
- **Workflow Automation:** Use tools like Apache Airflow for automated data processing pipelines.
- **Integration:** Connect ESS systems with external repositories and analysis platforms.

---

## **5. Challenges and Solutions**

### **5.1. Large Data Volumes**
- **Challenge:** Instruments generate terabytes of data daily.
- **Solution:** Use scalable storage solutions and tiered storage architectures.

### **5.2. Metadata Quality**
- **Challenge:** Inconsistent or incomplete metadata can hinder data reuse.
- **Solution:** Develop mandatory metadata templates and validation tools.

### **5.3. User Training**
- **Challenge:** Researchers may lack expertise in data management practices.
- **Solution:** Offer workshops and online resources on data curation and FAIR principles.

---

## **6. Future Directions**

### **6.1. AI and Machine Learning**
- Leverage AI to identify patterns in neutron data and automate routine analyses.
- Develop machine learning models to predict experimental outcomes based on historical data.

### **6.2. Enhanced Collaboration**
- Build platforms for seamless collaboration between ESS researchers and external partners.
- Foster open science by enabling public access to selected datasets.

### **6.3. Sustainability**
- Implement energy-efficient data centers and workflows.
- Regularly review and update data policies to align with emerging standards.

---

## **Conclusion**
Effective management and curation of neutron data at ESS are critical for advancing scientific discovery. By adopting FAIR principles, leveraging state-of-the-art tools, and fostering a culture of collaboration and innovation, ESS can ensure that its data remains a valuable resource for the global research community.

---

**References:**
1. Wilkinson, M. D., et al. (2016). The FAIR Guiding Principles for scientific data management and stewardship.
2. European Spallation Source (ESS) Website: [https://europeanspallationsource.se](https://europeanspallationsource.se)
3. NeXus Data Format: [https://www.nexusformat.org](https://www.nexusformat.org)



---

### Data Management Plan

- Make data available and citeable
- Need metadata
- eg. technical metadata  (experimental setup, detector geometry
and area, pulse width and shape, source type,  derived quantities, if raw or analyzed data,
energy resolution, calibration information, sample type
)
- descriptive metadata (date, investigator details, ORCID etc)
- administrative metadata (date, how created,
Digital object identifier or other persistent ID,
File type
)


--









---?image=assets/catanie.png&size=auto 90%


---

What metadata would you like to have visible?

What services should the data catalogue provide?
