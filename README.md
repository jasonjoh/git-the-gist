# Git the Gist

This sample add-in uses the [GitHub Gists API](https://developer.github.com/v3/gists/) to access a user's gist and insert them into a new message.

## Prerequisites

- [Node.js](https://nodejs.org)

## Running the sample

1. Clone or download the repository.
1. Open a command prompt/shell to the root of the repository and run the following command: `npm start`.
    - If your browser indicates that the site's certificate is not trusted, you will need to add the certificate as a trusted certificate. Outlook will not load add-ins if the site is not trusted. See [Adding Self-Signed Certificates as Trusted Root Certificate](https://github.com/OfficeDev/generator-office/blob/master/src/docs/ssl.mdnp) for details.
    - If the browser does not indicate a problem with the certificate, proceed to the next step.
1. Open Outlook 2016. On the **Home** tab in the ribbon, click the **Store** button.
1. In the Store UI, click the text **Click here to add a custom add-in**, and select **Add from file...**. Browse to the `git-the-gist-manifest.xml` file and click **Open**. Click **Install** when prompted.
    ![A screenshot of the "Add from file" menu item in the Outlook 2016 add-in store](readme-images/add-from-file.PNG)
1. Close the Store window. You should now see a new button on the ribbon labeled **Display all properties**. Click this button to open the taskpane. You should see the add-in's welcome page.
    > **Note:** This taskpane is just a placeholder, the functionality in this version is all in the new message window.
1. Compose a new message. You should now see two new buttons on the ribbon: **Insert Gist** and **Insert Default Gist**.

## Copyright

Copyright (c) 2015 Microsoft. All rights reserved.

----------
Connect with me on Twitter [@JasonJohMSFT](https://twitter.com/JasonJohMSFT)

Follow the [Outlook Dev Blog](http://blogs.msdn.microsoft.com/exchangedev)
