# Delta's Wiki

## RFID

<details>
  <summary><b>What is RFID?</b> <br />&nbsp; </summary> 
  
  RFID (**R**adio **F**requency **Id**entification) refers to automatic and contactless communication systems for object recognition.
A system essentially consists of the following components:

**Tag**

  Labels (also called "transponders" or "tags") can be attached to any object. A variety of different types are available. Labels can be attached via stickers, screws or fastened with cable ties or inserted into the existing inventory with epoxy resin.

**Reader incl. Antennas**

  The reader generates the necessary signal and monitors the desired area with the help of the connected antennas. The maximum range for label detection is up to 10 meters.

**Gateway**

  The gateway represents the process and control unit of the system. The data from the RFID reader is filtered here and passed on to the existing warehouse management system/ERP in real time.
  
---
  
  RFID can be seen as a modern barcode alternative. It is not based on optics but radio technology. Therefore, there is no need for a direct line of sight. Reads are recognized up to 6 meters and 200 reads/second are possible. Different from barcodes it enables bulk recognition. That means dozens or hundreds of products can be scanned at the very same moment.
  RFID at the UHF band (Ultra High Frequency, here 867-920 MHz) was introduced around 2005. Only recently the tag costs fell under the critical price of $0.10 per tag. Making it interesting for thousands of companies deeming it to be too expensive before.

</details>

<details>
  <summary><b>What is an ERP?</b> <br />&nbsp; </summary> 
  
  An **E**nterprise **R**essource **P**lanner is a comprehensive management software used by companies to manage their distribution/logistics, customer relations, sales, production, human ressources and many more in one place. It is practically the future of modern companies and seen consistent growth over the last years.
  
  One of the biggest providers are _SAP (HANA)_, _Oracle (Fusion)_, _Microsoft (Dynamics 365)_, _Infor_ and _SAGE (SAGE100, x3)_.
  
  <img src="https://user-images.githubusercontent.com/99175739/173815367-cae1af8f-96b8-435c-9e63-9bd498ffe1f9.png" width=40%>
  
  Anyway, especially small and mid sized companies often still rely on separated systems where warehouse management and other departments use isolated applications.
  
  In order to integrate Delta's platforms and solutions it is part of our service to identify the correct interface of a warehouse management software or ERP. 
  
</details>


<details>
  <summary><b>Who is GS1?</b> <br />&nbsp; </summary> 
  
  GS1 is an international organization developing and maintaining standards in over 100 countries. Those standards include barcodes and numerical guidelines for RFID implementations. Standards such as GTIN and EPC are very common and therefore supported across most hardware manufacturers. Merchants and solution providers have to register with GS1 in order to receive their unique range of numbers.
  
</details>

<details>
  <summary><b>What is the GS1 base number?</b> <br />&nbsp; </summary> 
  
  The base number is part of all GS1 numbers and is assigned to each enterprise individually during registration. It is 7, 8 or 9 digits long. The shorter the base number, the more GTINs can be generated later.
  
</details>

<details>
  <summary><b>What is the GLN?</b> <br />&nbsp; </summary> 
  
  The Global Location Number identifies the individual company including the branch office.
  
  <img src="https://user-images.githubusercontent.com/99175739/173853510-43d61d88-a661-4b4c-b107-59c469f0a426.png" width=40%>
  
</details>

<details>
  <summary><b>What is the GTIN?</b> <br />&nbsp; </summary> 
  
  The GTIN (formerly EAN) is called Global Trade Identification Number and corresponds to the product category. Each product of a category carries the same GTIN.
Example: Shirt with 3x colors and 4x sizes = 12 GTINs
  
  <img src="https://user-images.githubusercontent.com/99175739/173854582-701dea3a-1346-4a86-bcbf-a48a08edeace.png" width=40%>
  
</details>

<details>
  <summary><b>Who assigns the GTIN?</b> <br />&nbsp; </summary> 
  
  The GTIN (formerly EAN) is usually assigned directly by the manufacturer or brand owner of the product. When carrying out the labeling, he is the one who has to register the product.
  
</details>

<details>
  <summary><b>What is the SGTIN?</b> <br />&nbsp; </summary> 
  
  The GTIN (formerly EAN) is called Global Trade Identification Number and corresponds to the product category. Each product of a category carries the same GTIN.
Example: Shirt with 3x colors and 4x sizes = 12 GTINs
  
  <img src="https://user-images.githubusercontent.com/99175739/173854582-701dea3a-1346-4a86-bcbf-a48a08edeace.png" width=40%>
  
</details>


<details>
  <summary><b>What is the SGTIN?</b> <br />&nbsp; </summary> 
  
  In contrast to the normal GTIN, which uniquely identifies a product category, the serialized GTIN (SGTIN) is used when a single product of this category is to be marked.
  For example, the SGTIN is used in technical industries to distinguish individual components of the same type from one another. In this way, components can be unambiguously traced from their manufacture, through the entire supply chain, operation, right up to maintenance and scrapping. This is the basic prerequisite for reliable lifecycle management. 
  Hence unique, a SGTIN can also be converted into an EPC.
  
</details>

<details>
  <summary><b>What is the GRAI?</b> <br />&nbsp; </summary> 
  
  Global Returnable Asset Identifier identifies returnable transport packaging such as beer kegs, pallets, baskets or stairs. 
It consists of the GS1 base number followed by container type and check digit, combined with an optional serial number.
If an optional serial number is provided then GRAIs can be converted into a valid EPC.
  
</details>

<details>
  <summary><b>What is the SSCC?</b> <br />&nbsp; </summary> 
  
  SSCC is the unique number of a shipping unit.
  Example: The products inside of shipping cartons each carry their respective GTINs and/or SGTINs. Once put in a shipping carton and prepared for shipping the carrier assigns a unique SSCC to it.
  
  It is also possible to pack and unpack multiple SSCCs into one.
  For example if 20 different SSCCs were put on a pallet and wrapped with foil, then the whole pallet could be assigned with an additional SSCC.
  SSCCs are mostly important for carriers like UPS, DHL or FedEx in order to allow them and their customers to track and trace transported items.
  SSCCs can be converted into EPCs.
    
  <img src="https://user-images.githubusercontent.com/99175739/173861799-9015dcec-c0bb-4a06-b104-383804dba65e.png" width=40%>
  
</details>


<details>
  <summary><b>What is an EPC?</b> <br />&nbsp; </summary> 
  
  The Electronic Product Code is a universal identifier that provides a unique identity for every physical object. The EPC structure is defined in the open standard _EPCglobal Tag Data Standard_. Most commonly it occurs as 24 hexadecimal characters (96-bits) which can be written into memory banks.
  EPCs are therefore used to encode RFID tags.
  EPCs can be en-/decoded from SGTIN, GRAI, SSCC and other standards carrying enough information.
  Although necessary for encoding memory banks, EPC obviously provides redundant information (being converted from the other GS1 standards). This is why the EPC is mostly used inside middleware applications and not printed in clear text or barcode onto an item. 
  
</details>

