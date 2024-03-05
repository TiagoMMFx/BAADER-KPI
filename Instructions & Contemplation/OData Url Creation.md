## A step-by-step guide for crafting an OData URL in Microsoft Dynamics NAV 2015.

#### 1. Navigate to the Web Services Page
  1. Open the Dynamics NAV Environment.
  2. Under the search pane, look for the **Web Services** option.
    - Alternatively, you can press (Ctrl + S) to initiate the search.

#### 2. Create a New Web Service Instance
  1. On the **Web Services** page, create a new record by either:
    - Clicking on the "New" button.
    - Pressing Ctrl + N.

#### 3. Specify Object Type, Object ID, and Object Name
##### Set the following values for the new web service instance:
- **Object Type:** Page
- **Object ID:** Choose the ID of the page you want to expose through the web service.
- **Object Name:** The name of the page object.

#### 4. Define a Service Name
1. Enter a meaningful name for your web service in the "Service Name" field. This name is used to identify the service in Dynamics NAV.

#### 5. Mark as Published
1. Set the "Published" field to Yes to make the web service accessible.

#### 6. Generate OData and SOAP URLs
1. After defining the service, Dynamics NAV will automatically generate the following URLs:
   - **OData URL:** Use this in Power BI for connecting to the service.
   - **SOAP URL:**

#### 7. Save the Web Service Instance
1. Save the record by either:
   - Clicking on the "Save" button.
   - Pressing Ctrl + S.

### OData Web Service Instance Created
Now that you have successfully created a new OData web service instance in Dynamics NAV, you can utilize the generated OData URL when connecting to this service in Power BI.
