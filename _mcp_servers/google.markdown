---
layout: how-to
sitemap:
  exclude: 'no'
order: 50
server_type: local

description: "Connect your Google Drive, Docs, Sheets, Slides, Gmail, and Calendar using Model Context Protocol."
title: Google
hero:
  title: Google Workspace
  description: Connect your Google Drive, Docs, Sheets, Slides, Gmail, and Calendar using Model Context Protocol.
  image: /assets/images/marketing/google-workspace-mcp-server-hero.png
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"

how_to:
  items:
    - title: "Step 1: Sign-in to Google Cloud"
      image: /assets/images/marketing/google-workspace-mcp-server-steps/console-sign-in.webp
      description: First, visit **[Google Cloud Console](https://console.cloud.google.com/)** and sign-in.
    - title: "Step 2: Create a Project"
      description: "Next, you'll need to **create a project** in order to enable the APIs and create the credentials so that apps like **ChatterKB** can log in."
      tabs:
        - title: "Search Bar for Create a Project"
          description: Type **Create a project** in the **search bar** at the top of the page. Click on the **Create a project** item in the list.
          image: /assets/images/marketing/google-workspace-mcp-server-steps/console-project.webp
        - title: "Choose a Name"
          description: Choose a name and click on the **Create** button.
          image: /assets/images/marketing/google-workspace-mcp-server-steps/console-project-name.webp
        - title: "Project Dashboard"
          description: Once you see your project name in the **Dashboard** (as seen in this image) you're ready to go!
          image: /assets/images/marketing/google-workspace-mcp-server-steps/console-project-success.webp
    - title: "Step 3: Enable the APIs"
      description: "Next, let's enable all of the APIs you would like to make available. Just follow the guide below, clicking the Next button to help you on your way."
      accordion:
        - title: Google Drive
          tabs:
            - title: "Search for Library"
              description: Type the word **Library** in the **search bar** at the top of the page. Click on the **Library Product Page** item in the list.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library.webp
            - title: "Search for Google Drive"
              description: Next, search for **Google Drive**. You should see **google drive api** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-drive.webp
            - title: "Select the API"
              description: Then, click on the API shown in the image.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-drive-select.webp
            - title: "Enable the API"
              description: Finally, enable the API by clicking on the **Enable** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-drive-enable.webp
        - title: Google Docs
          tabs:
            - title: "Search for Library"
              description: Type the word **Library** in the **search bar** at the top of the page. Click on the **Library Product Page** item in the list.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library.webp
            - title: "Search for Google Docs"
              description: Next, search for **Google Docs**. You should see **google docs api** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-docs.webp
            - title: "Select the API"
              description: Then, click on the API shown in the image.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-docs-select.webp
            - title: "Enable the API"
              description: Finally, enable the API by clicking on the **Enable** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-docs-enable.webp
        - title: Google Sheets
          tabs:
            - title: "Search for Library"
              description: Type the word **Library** in the **search bar** at the top of the page. Click on the **Library Product Page** item in the list.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library.webp
            - title: "Search for Google Sheets"
              description: Next, search for **Google Sheets**. You should see **google sheets api** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-sheets.webp
            - title: "Select the API"
              description: Then, click on the API shown in the image.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-sheets-select.webp
            - title: "Enable the API"
              description: Finally, enable the API by clicking on the **Enable** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-sheets-enable.webp
        - title: Google Slides
          tabs:
            - title: "Search for Library"
              description: Type the word **Library** in the **search bar** at the top of the page. Click on the **Library Product Page** item in the list.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library.webp
            - title: "Search for Google Slides"
              description: Next, search for **Google Slides**. You should see **google slides api** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-slides.webp
            - title: "Select the API"
              description: Then, click on the API shown in the image.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-slides-select.webp
            - title: "Enable the API"
              description: Finally, enable the API by clicking on the **Enable** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-slides-enable.webp
        - title: GMail
          tabs:
            - title: "Search for Library"
              description: Type the word **Library** in the **search bar** at the top of the page. Click on the **Library Product Page** item in the list.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library.webp
            - title: "Search for GMail"
              description: Next, search for **Gmail**. You should see **gmail api** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-gmail.webp
            - title: "Select the API"
              description: Then, click on the API shown in the image.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-gmail-select.webp
            - title: "Enable the API"
              description: Finally, enable the API by clicking on the **Enable** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-gmail-enable.webp
        - title: Calendar
          tabs:
            - title: "Search for Library"
              description: Type the word **Library** in the **search bar** at the top of the page. Click on the **Library Product Page** item in the list.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library.webp
            - title: "Search for Calendar"
              description: Next, search for **Calendar**. You should see **calendar api** in the list below the search bar and press **Enter**.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-calendar.webp
            - title: "Select the API"
              description: Then, click on the API shown in the image.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-calendar-select.webp
            - title: "Enable the API"
              description: Finally, enable the API by clicking on the **Enable** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/library-calendar-enable.webp
    - title: "Step 4: Branding"
      description: Next, we'll start setting up the credentials Google needs to connect with. Find the search bar and type **Credentials** and click on the **Credentials Product Page**. The first step is to set up your **Consent** and **App**.
      tabs:
        - title: Credentials Page
          description: "Find the search bar and type **Credentials** and click on the **Credentials Product Page**."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials.webp
        - title: Consent
          description: "Next, click on the **Configure consent screen**. It should look like a yellow button."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-consent.webp
        - title: Branding
          description: "Then, you'll arrive at the **Branding** page. Click on the **Get started** button."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-branding.webp
        - title: App Info
          description: "Next, you'll need to create an **App**. You can provide a **name** and **email**. It might say user support, but this app is **only for you**!"
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-branding-app-info.webp
        - title: Audience
          description: "Then, you'll need to select **External**. Though this might just be for you, this is the only option available (Internal will be disabled)."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-branding-audience.webp
        - title: Contact Info
          description: "Next, you'll need to specify an **email** so that Google can notify you of any changes."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-branding-contact.webp
        - title: Data Policy Agreement
          description: "Then, agree to the **Google Data Policy**."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-branding-contact.webp
        - title: Finish
          description: "Finally, click on the **Create** button to finish."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-branding-finish.webp
    - title: "Step 5: Credentials"
      description: Next, we'll create a **OAuth client** which will provide the **client id** and **client secret** you'll need to connect to the APIs.
      tabs:
        - title: Create the Client
          description: "Click on the button called **Create OAuth client** or click on the list on the left side where it says **Clients** and find **Create client**."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-oauth.webp
        - title: Web App
          description: "Next, select **Web application** from the dropdown."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-oauth-web-app.webp
        - title: Name & Create
          description: "Then, give it a **name** and click on the **Create** button."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-oauth-create.webp
        - title: IMPORTANT - Credentials
          description: "Finally, and this is **VERY IMPORTANT**, copy the **Client ID** and **Client secret** and save them. You can get back to these values later, but it will save you time if you copy them now. Then, click on **OK**."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-oauth-creds.webp
    - title: "Step 6: Audience"
      description: Now, we need to add you to the app's **audience**. This gives you access without having to go through a verification process.
      tabs:
        - title: Audience Page
          description: "Click on the **Audience** item on the far left side of the window."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-audience.webp
        - title: Add Users
          description: "Next, click on the **Add users** button."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-audience-add.webp
        - title: Add Email
          description: "Then, add your **email** and click on **Save**"
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-audience-add-email.webp
        - title: Verify Email
          description: "Finally, make sure that your email address is shown in the **Test users** section in the **Audience** page."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-audience-added.webp
    - title: "Step 7: Data Access"
      description: Next, we need to tell Google what **data** you want to share through this app.
      tabs:
        - title: Data Access Page
          description: "Find the **Data Access** item in the list on the far left and click on it."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access.webp
        - title: Add Scopes
          description: "Next, click on the **Add or remove scopes** button. You'll do this for each of the following services in **Part 2**."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
    - title: "Step 7: Data Access"
      description: Next, we need to tell Google what **data** you want to share through this app. This will be defined for each **API**.
      accordion:
        - title: Data Access Page
          tabs:
            - title: Data Access Page
              description: "Find the **Data Access** item in the list on the far left and click on it."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access.webp
            - title: Add Scopes
              description: "Next, click on the **Add or remove scopes** button. You'll do this **for each of the APIs**."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
            - title: Saving Scopes
              description: "Once you've added all of the APIs, make sure that they appear in the **Data Access** page and that you have clicked on the **Save** button."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-save.webp

        - title: Google Drive
          tabs:
            - title: Add Scopes
              description: "Click on the **Add or remove scopes** button."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
            - title: "Search for Google Drive"
              description: Next, search for **/auth/drive**. You should see **https://www.googleapis.com/auth/drive** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-drive.webp
            - title: "Select Access"
              description: Verify the access was selected and click the **Update** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-drive-update.webp
        - title: Google Docs
          tabs:
            - title: Add Scopes
              description: "Click on the **Add or remove scopes** button."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
            - title: "Search for Google Docs"
              description: Next, search for **/auth/documents**. You should see **https://www.googleapis.com/auth/documents** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-docs.webp
            - title: "Select Access"
              description: Verify the access was selected and click the **Update** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-docs-update.webp
        - title: Google Sheets
          tabs:
            - title: Add Scopes
              description: "Click on the **Add or remove scopes** button."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
            - title: "Search for Google Sheets"
              description: Next, search for **/auth/spreadsheets**. You should see **https://www.googleapis.com/auth/spreadsheets** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-sheets.webp
            - title: "Select Access"
              description: Verify the access was selected and click the **Update** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-sheets-update.webp
        - title: Google Slides
          tabs:
            - title: Add Scopes
              description: "Click on the **Add or remove scopes** button."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
            - title: "Search for Google Slides"
              description: Next, search for **/auth/presentations**. You should see **https://www.googleapis.com/auth/presentations** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-slides.webp
            - title: "Select Access"
              description: Verify the access was selected and click the **Update** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-slides-update.webp
        - title: GMail
          tabs:
            - title: Add Scopes
              description: "Click on the **Add or remove scopes** button."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
            - title: "Search for GMail"
              description: Next, search for **mail.google.com**. You should see **https://mail.google.com/** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-gmail.webp
            - title: "Select Access"
              description: Verify the access was selected and click the **Update** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-gmail-update.webp
        - title: Calendar
          tabs:
            - title: Add Scopes
              description: "Click on the **Add or remove scopes** button."
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-scope.webp
            - title: "Search for Google Calendar"
              description: Next, search for **/auth/calendar**. You should see **https://www.googleapis.com/auth/calendar** in the list below the search bar. Click on it to continue.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-calendar.webp
            - title: "Select Access"
              description: Verify the access was selected and click the **Update** button.
              image: /assets/images/marketing/google-workspace-mcp-server-steps/credentials-data-access-calendar-update.webp

    - title: "ChatterKB Integration"
      description: Now we can integrate with ChatterKB. You'll just need a few more steps to tie everything together.
      tabs:
        - title: Knowledge Base Settings - MCP
          description: "Visit the settings for your ChatterKB knowledge base and click on the **MCP** item on the left hand side. Then locate the **Google** MCP server settings."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings.webp
        - title: Client ID & Secret
          description: "Next, expand the settings area and take the **client id** and **client secret** you saved from **Step 5** and paste them into each of the fields. Click the **Add Google Integration** button."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client.webp
        - title: Copy URL
          description: "Now, you'll see the MCP server added to your list. Before we connect, copy the **Redirect URL** and return to the **Google Cloud Console**"
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-url.webp
        - title: Back to Google Client
          description: "Then, find your **OAuth client** and click to edit its settings."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-page.webp
        - title: Add Redirect URI
          description: "Finally, add the URL you copied to the list of **Redirect URI's**. Remember to click on the **Save** button before you continue."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-uri.webp

    - title: "Connecting ChatterKB to Google"
      description: Now all we need to do is connect.
      tabs:
        - title: Connect to MCP
          description: "Visit the settings for your ChatterKB knowledge base and click on the **MCP** item on the left hand side. Then locate the **Google** MCP server in the list of added MCP servers. It should currently be **not connected**"
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-connect.webp
        - title: Google - Choose an Account
          description: "Next, choose the account that you had given your app access to."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-account.webp
        - title: Google - Warning
          description: "Now, you'll see a warning that Google hasn't verified the app. It doesn't need to because this is **your** app. You control it and can turn it off whenever you want. Click **continue**."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-not-verified.webp
        - title: Google - Access
          description: "Then, select all of the data you want to let ChatterKB access."
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-api-access.webp
        - title: Connection Confirmation
          description: "Now, Google will send you back to the MCP settings tab where you should see that the MCP server is now **connected**"
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-connected.webp
        - title: Try It
          description: "Finally, try it out for yourself. Open a chat and ask it to do something like **\"List all of my files on Google Drive\"**"
          image: /assets/images/marketing/google-workspace-mcp-server-steps/ckb-mcp-settings-google-client-test.webp


  title: Connect Using MCP Today
  description: Unlock powerful database insights through Airtable MCP integration.
  primary_button:
    text: Try It Free
    url: "https://app.chatterkb.com/auth/signup"
  secondary_button:
    text: Book a Demo
    url: "https://calendar.app.google/oKoqxPxBANh9d9cH9"
--- 

<section id="features" class="mt_features py-5 py-md-7">
  <div class="container">
    <div class="text-center mb-5 pb-3">
      <div class="badge bg-primary text-white mb-3 py-2 px-4 rounded-pill fw-normal">Mangage MCP Server</div>
      <h2 class="display-5 fw-bold">Connecting to Google</h2>
      <p>In order to provide the best experience, we manage this connection directly through ChatterKB. Follow these steps to create your credentials to access your Google account.</p>
    </div>
  </div>
</section>
<hr/>