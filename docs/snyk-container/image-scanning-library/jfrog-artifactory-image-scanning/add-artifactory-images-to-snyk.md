# Add Artifactory images to Snyk

Snyk tests and monitors your Artifactory container images by evaluating its tags in your repositories.

**To add images to Snyk**:

**Prerequisites:**

* You must have an account with Snyk and be onboarded to your organization by an administrator.
* The integration must be configured between Snyk and your Artifactory environment.

**Steps:**

* Log in to your account and navigate to the relevant group and organization that you want to manage.

![](../../../.gitbook/assets/add-artifactory-images%20%281%29.gif)

* Go to Projects, and click Add projects. The list of integrations already configured on your account opens, similar to the following:

![AddProjectMenu.png](https://support.snyk.io/hc/article_attachments/360007065837/uuid-dd01aab7-482f-0fc2-01de-c2427a14a0e0-en.png)

* The Which images do you want to test? view appears, displaying all of the available images for the registry to which you connected, grouped by each of your repositories, similar to the following:

![AddImages.png](https://support.snyk.io/hc/article_attachments/360007065857/uuid-bd9cf629-f5fb-b28b-1fc1-40df2367a7f9-en.png)

* Select single or multiple images with any or all of the following methods:
  * Type the name of a single image for import in the Image Name field \(\#1 in the image above\),
  * Select any of the repositories if you want to import all of the associated images \(\#2 in the image above\).
  * Expand and collapse repositories to select multiple images \(\#3 in the image above\) across multiple repositories.
* Click Add selected repositories.

  A status bar appears at the top of the page as the images are imported; you can continue working in the meantime.

* When the import ends, notification of success, or failure, appears at the top of the page. Click Refresh to view the Projects page with the newly imported images. Images are grouped by repository and are each linked individually to a detailed Projects page.
* You can now connect your Git repo to this project in order to use your Dockerfile for enriched remediation advice. For more info, see [Adding your Dockerfile and test your base image](https://support.snyk.io/hc/articles/360003916218#UUID-9ab347a6-8af0-ef6c-5ebd-cec21fbfab29).

Images are indicated with a unique icon ![image4.png](https://support.snyk.io/hc/article_attachments/360007147198/uuid-d083d5fe-780a-cf2f-18db-42720db8c5a1-en.png), and you can also filter to view only the Artifactory projects:

![Artifactory\_projects.png](https://support.snyk.io/hc/article_attachments/360007065877/uuid-5c95894c-97d8-a6a9-0969-7c5fee541211-en.png)

Artifactory integration works similarly to our other integrations. To continue to monitor, remediate and manage your projects, see the relevant pages in our docs.
