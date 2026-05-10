---
title: 3.BDC Data Share
layout: default
parent: Lab 1
nav_order: 3
---

# Sharing SAP Business Data Cloud Data Products to SAP Databricks

{: .warning }
This section cannot be performed within the workshop environment.**HANA Data Like File Storage capacity is a prerequisite.**The steps below are provided for informational purposes to explain the process.

1️⃣ In the side navigation area, go to ‘Data Sharing Cockpit’ → ‘My Data Products’.

<p>
  <img
    src="{{ site.baseurl }}/images/custom_data_product_1.png"
    alt="Data Product 1"
    style="width:180px; cursor:pointer;"
    onclick="document.getElementById('img1').showModal()"
  >
</p>

<dialog id="img1" onclick="if(event.target===this)this.close()">
  <img src="{{ site.baseurl }}/images/custom_data_product_1.png" style="max-width:90vw;">
</dialog>

2️⃣ Search for ‘Sales Order Fact’, add a description, and select ‘Save Changes’.
<p>
  <img
    src="{{ site.baseurl }}/images/custom_data_product_2.png"
    alt="Data Product 2"
    style="width:400px; cursor:pointer;"
    onclick="document.getElementById('img2').showModal()"
  >
</p>

<dialog id="img2" onclick="if(event.target===this)this.close()">
  <img src="{{ site.baseurl }}/images/custom_data_product_2.png" style="max-width:90vw;">
</dialog>

3️⃣ Go to ‘Catalog & Marketplace’ from the navigation bar.

4️⃣ Select ‘Marketplace Data Products’, search for your data product, and open it.

5️⃣ In the ‘Details’ section, review the APIs and select ‘Share’ to share the SAP Data Product with ‘SAP Databricks Unity Catalog’.

6️⃣ In ‘Manage Share Access’, enter the name of the ‘Delta Share’ that appears in the target system.  
Leave ‘Workspace’ as the default workspace and select ‘Share’.

7️⃣ The data product is now shared with ‘SAP Databricks’.

Access the guided tour and follow the steps to share SAP Business Data Cloud data products to SAP Databricks. During the guided tour, you will:

- Search the catalog for a data product
- Share the data product to SAP Databricks

<div style="position: relative; width: 100%; height: 0; padding-bottom: 56.25%;">
  <iframe
    src="https://tour-viewer.platform.saleo.io/d12091f4-9842-4db1-8203-91ae4f657e38"
    title="Saleo Tour"
    allowfullscreen
    loading="lazy"
    style="position: absolute; top:0; left:0; width:100%; height:100%; border:0;">
  </iframe>
</div>

> Source: SAP Workbook Partner Academy.

---

[Lab 2 →](../Lab 2/lab 2.md){: .btn .btn-primary }

