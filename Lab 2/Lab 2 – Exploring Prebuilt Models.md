# Lab 2: Exploring Prebuilt Models

## Exercise 1: Working with Contracts Model

### Task 1: Create a contracts model

1.  If you closed the tab in the previous task, on the Lab VM, open a
    new browser tab and sign in to
    ```https://admin.microsoft.com/```. Log in using the admin
    credentials. In **Microsoft 365 admin center**, select **SharePoint** under
    **Admin centers** from left navigation menu.

2.  In **SharePoint admin center**, select **Active sites** from left
    navigation menu. On **Active Sites** page, select **HR Content
    Center** and select **URL** on **HR Content Center** pane.

3.  You’ll be navigated to the SharePoint **HR Content Center** site on
    another tab. Click **+New** and click **Document library**.

> ![A screenshot of a computer Description automatically
> generated](./media/image1.png)

4.  On **Create document library** pane, enter ```Services Agreement
    Contracts``` for **Name** and click **Create**.

> ![A screenshot of a computer Description automatically
> generated](./media/image2.png)

5.  Click **Models**. Click **Create a model** on the top left of **HR
    Content Center** page.

6.  Click **Contract processing** on **Options for model creation**
    pane.

> ![A screenshot of a computer Description automatically
> generated](./media/image3.png)

7.  Click **Next** on **Contract processing: Details** pane.

> ![A screenshot of a computer Description automatically
> generated](./media/image4.png)

8.  On **Create a contract processing model** pane, enter ```Service
    Agreements``` for **Name** and click **Create**.

Stay on the same page and continue to the next task

### Task 2: Upload an example file to analyze

1.  Click **Add a file** under **Add a file to analyze** on **Model** \>
    **Service Agreements** page.

> ![A screenshot of a computer Description automatically
> generated](./media/image5.png)

2.  Click **+Add** on **Files to analyze with the model** pane.

> ![A screenshot of a computer Description automatically
> generated](./media/image6.png)

3.  Click **Upload** and then click **Files** on **Add a file from the
    training files library** dialog.

> ![A screenshot of a computer Description automatically
> generated](./media/image7.png)

4.  Go to **c:\Labfiles\Service Agreement Contracts** and select **Allan
    Deyoung.pdf** then click **Open**. Click check box next to **Allan
    Deyoung.pdf** on **Add a file from the training files library** pane
    and click **Add**.

> ![A screenshot of a computer Description automatically
> generated](./media/image8.png)

5.  Click **Next** on **Files to analyze with the model** pane.

### Task 3: Select extractors for your model

1.  On **View extractor details** page, on **Contracts extractors**
    pane, click check box next to **ContracTitle** and click **Yes** on
    **Select extractor?** dialog.

> ![A screenshot of a computer Description automatically
> generated](./media/image9.png)

2.  Check the selection and mark yes for all the extractors.

> ![A screenshot of a computer Description automatically
> generated](./media/image10.png)

Stay on the same page for next exercise.

### Task 4: Apply the model

1.  Click **Apply model** and on **Apply Model to library** pane, click
    **HR Content Center.**

> ![A screenshot of a computer Description automatically
> generated](./media/image11.png)

2.  Click **Service Agreement Contracts** on **Apply Office expenses to
    library** pane under **Choose the library you would like to add**
    **this model to** section. Once **Service Agreement Contracts** is
    selected, click **Add**.

> ![A screenshot of a computer Description automatically
> generated](./media/image12.png)

3.  On **Apply Office expenses to library** pane, click **Go to
    library**.

> ![A screenshot of a computer Description automatically
> generated](./media/image13.png)

4.  In **Service Agreement Contracts** document Library, click
    **Upload** and then click **Files**. Go to **c:\Labfiles\Service
    Agreement Contracts** and select all files then click **Open**. ­

5.  You will see all the fields listed as the **Columns**. Once the
    processing is complete, the columns will be filled. You might have
    to refresh the page to see the changes after uploading the file.

> ![A screenshot of a computer Description automatically
> generated](./media/image14.png)

## Exercise 2: Working with Invoices Model

### Task 1: Create a prebuilt invoices model

1.  If you closed the tab in the previous task, on the Lab VM, open a
    new browser tab and sign in to
    ```https://admin.microsoft.com/```. Log in using the admin
    credentials.

2.  In **Microsoft 365 admin center**, select **SharePoint** under
    **Admin centers** from left navigation menu.

3. In **SharePoint admin center**, select **Active sites** from left
    navigation menu. On **Active Sites** page, select **HR Content
    Center** and select **URL** on **HR Content Center** pane.

4. You’ll be navigated to the SharePoint **HR Content Center** site on
    another tab. Click **+New** and click **Document library**.

> ![A screenshot of a computer Description automatically
> generated](./media/image15.png)

5. On **Create document library** pane, enter ```Invoice``` for
    **Name** and click **Create**.

> ![A screenshot of a computer Description automatically
> generated](./media/image16.png)

6. Click **Models**. Click **Create a model** on the top left of **HR
    Content Center** page. Click **Invoice processing** on **Options for
    model creation** pane.

> ![A screenshot of a computer Description automatically
> generated](./media/image17.png)

7. Click **Next** on **Invoice processing: Details** pane.

> ![A screenshot of a computer Description automatically
> generated](./media/image18.png)

8. On **Create an invoice processing model** pane, enter ```Office
    expenses``` for **Name** and click **Create**.

> ![A screenshot of a computer Description automatically
> generated](./media/image19.png)

Stay on the same page and continue to the next task

### Task 2: Upload an example file to analyze

1.  Click **Add a file** under **Add a file to analyze** on **Model** \>
    **Office expenses** page.

> ![A screenshot of a computer Description automatically
> generated](./media/image20.png)

2.  Click **+Add** on **Files to analyze with the model** pane.

> ![A screenshot of a computer Description automatically
> generated](./media/image21.png)

3.  Click **Upload** and then click **Files** on **Add a file from the
    training files library** dialog.

> ![A screenshot of a computer Description automatically
> generated](./media/image22.png)

4.  Go to **c:\Labfiles** and select **Sample Invoice.pdf** then click
    **Open**. Click check box next to **sample-invoice.pdf** on **Add a
    file from the training files library** pane and click **Add**.

> ![A screenshot of a computer Description automatically
> generated](./media/image23.png)

5.  Click **Next** on **Files to analyze with the model** pane.

> ![A screenshot of a computer Description automatically
> generated](./media/image24.png)

Stay on the same page for next exercise.

### Task 3: Select extractors for your model

1.  On **View extractor details** page, on **Invoice extractors** pane,
    click check box next to **AmountDue** and click **Yes** on **Select
    extractor?** dialog.

> ![A screenshot of a computer Description automatically
> generated](./media/image25.png)

2.  Click the check box for **BillingAddress** on **Invoice extractors**
    pane and click **Yes** on **Select extractor?** dialog.

3.  Scroll **down** on **Invoice extractors** pane and in the same way
    click the check box for **CustomerId, CustomerName, DueDate,
    InvoiceDate, InvoiceID, InvoiceTotal, PreviousUnpaidBalance** and
    **PurchaseOrder** and click **Yes** on **Select extractor?** dialog,
    if prompted.

> ![A screenshot of a computer Description automatically
> generated](./media/image26.png)

4.  Select **Next**.

Stay on the same page for next exercise.

### Task 4: Apply the model

1.  Click **Apply model** and on **Apply Model to library** pane, click
    **HR Content Center.**

> ![A screenshot of a computer Description automatically
> generated](./media/image27.png)

2.  Click **Invoices** on **Apply Office expenses to library** pane
    under **Choose the library you would like to add** **this model to**
    section.

> ![A screenshot of a computer Description automatically
> generated](./media/image28.png)

3.  Select **Invoices**.

> ![A screenshot of a computer Description automatically
> generated](./media/image29.png)

4.  Once **Invoices** is selected, click **Add**.

> ![A screenshot of a computer Description automatically
> generated](./media/image30.png)

5.  On **Apply Office expenses to library** pane, click **Go to
    library**.

> ![A screenshot of a computer Description automatically
> generated](./media/image31.png)

6.  In **Invoices** document Library, click **Upload** and then click
    **Files**.

> ![A screenshot of a computer Description automatically
> generated](./media/image32.png)

7.  Go to **c:\Labfiles** and **Sample Invoice.pdf** then click
    **Open**. ­

You will see all the fields listed as the **Columns**. Once the
processing is complete, the columns will be filled. You might have to
refresh the page to see the changes after uploading the file.

![A screenshot of a computer Description automatically
generated](./media/image33.png)

## Exercise 3: Working with Sensitive information

To create and configure a sensitive information model, follow these
steps:

1.  If you closed the tab in the previous task, on the Lab VM, open a
    new browser tab and sign in to
    ```https://admin.microsoft.com/```. Log in using the admin
    credentials.

2. In **Microsoft 365 admin center**, select **SharePoint** under
    **Admin centers** from left navigation menu.

3. In **SharePoint admin center**, select **Active sites** from left
    navigation menu. On **Active Sites** page, select **HR Content
    Center** and select **URL** on **HR Content Center** pane.

4. You’ll be navigated to the SharePoint **HR Content Center** site on
    another tab. Click **+New** and click **Document library**. On
    **Create document library** pane, enter ```Sensitive
    Information``` for **Name** and click **Create**.

> ![A screenshot of a computer Description automatically
> generated](./media/image34.png)

5. Click **Models**. Click **Create a model** on the top left of **HR
    Content Center** page.

6. Click **Sensitive information processing** on **Options for model
    creation** pane.

> ![](./media/image35.png)

7. Click **Next** on **Sensitive information processing: Details**
    pane.

> ![](./media/image36.png)

8. On **Create a Sensitive information processing** **model** pane,
    enter ```Sensitive contract information``` for **Name** and
    click **Create**.

> ![](./media/image37.png)

9. You will be redirected to the models home page. From the **Add
    entities to detect card**, select **Add entities**.

> ![A screenshot of a computer Description automatically
> generated](./media/image38.png)

10. On the **Configure detection** page:

    - Select **English** as the language.

    - From the list of supported entities, search for and Select
      **Physical Address**.

    - Then select **Next**.

> ![A screenshot of a computer Description automatically
> generated](./media/image39.png)

11. On the **Configure extraction** page, you see the list of sensitive
    information entities you chose to detect. Select **Physical
    Address**, and then select **Next**.

> ![A screenshot of a computer Description automatically
> generated](./media/image40.png)

12. On the **Test model** page, you test the model to make sure it
    detects and extracts the entities you want. Select **+Add files** \>
    **Upload** \> **Files**. From **c:\Labfiles\Contracts Management**,
    select **Test file.docx**.

> ![A screenshot of a computer Description automatically
> generated](./media/image41.png)

13. Select **Test file.docx** and then click **Add**. Then select
    **Next**.

> ![A screenshot of a computer Description automatically
> generated](./media/image42.png)

14. On the **Apply model** page, select **+Add library**, and choose
    **HR Content Center** \> **Sensitive information**, and then
    select **Add**.

> ![A screenshot of a computer Description automatically
> generated](./media/image43.png)

15. Select **Go to library**.

16. Select **Upload** \> **Files**. Select all the files in
    **c:\Labfiles\Contracts Management** then select **Open**.

You will see all the fields listed as the **Columns**. Once the
processing is complete, the columns will be filled. You might have to
refresh the page to see the changes after uploading the file.

> ![](./media/image44.png)
