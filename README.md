# Firefox Marketplace Legal Documents

This repository contains all legal documents and their applicable translations. The repository is organized within the `docs/` directory, where each subdirectory represents a single legal document. Within a document directory is a series of markdown files, each named for the language the document is written in. For instance, `docs/privacy_policy/de.md` is the German version of the Marketplace privacy policy.

## Editing

### Legal Team

If you're a member of the legal team, it's easy to get started. First, make sure you're logged in with your Github account. When you have a change which you wish to make, simply find the `en-US.md` version of the document that you wish to change. Open it and press the `Edit` button. If you have never gone through this process before, you will be asked to "fork" the repository (you should).

On the edit page, you'll be presented with a "raw" version of the legal document. Edit the text you wish to change. When you are done editing, there will be a section at the bottom of the page to save your work. Under "Commit summary", enter a brief (tweet-length) description of the change(s) you're making. In the "Extended description" field, explain what the changes are and why they're needed. When you're done, commit your changes.

At this point, you'll be presented with a form to submit a pull request. The bottom section of the page will show all of the change you've made to the document, and all you should need to do is press the "Send Pull Request" button.

Once you've submitted a pull request, your colleagues can review the work under the Pull Requests tab on the right-hand side, and a contributor to the repo can merge your changes.

### Markdown

These files are written in the [Markdown syntax](http://daringfireball.net/projects/markdown/syntax). In some languages, the date format contains dots like `15. travnja 2014.` but this may end up as an ordered list according to the syntax. The workaround is using a backslash to escape a dot after the leading digit(s) like `15\. travnja 2014.`

Some Markdown files use the [Attribute Lists extension](https://pythonhosted.org/Markdown/extensions/attr_list.html) of the [Python Markdown library](https://pypi.python.org/pypi/Markdown). This is useful when you'd like to set the ID or class of an element, but the extended syntax may cause an error if your parser doesn't support this extension.

### Localizers

As a localizer, you're encouraged to find and fix translation issues. All document translations should match the precise meaning in the corresponding `en-US.md` version of the document. Additionally, we're always interested in finding errors in markup, broken links, etc.

File a pull request that updates your locale's markdown file to match the `en-US.md` version as closely as possible. When you're done, submit a pull request. Someone at Mozilla will review your changes. If there are no problems, your changes will be merged.

## URL Inventory

Following is a list of directories in this repository and either their URL counterparts on the web or directions to see the document in case it isn't easily linkable.  The URLs below will link to the *English (US)* versions of the document but replacing *en-US* in the URL with an available language code will show alternative languages.

* /firefox_cloud_services_PrivacyNotice
    * https://www.mozilla.org/en-US/privacy/firefox-cloud/
* /firefox_cloud_services_ToS
* /firefox_os_privacy_notice
    * https://www.mozilla.org/en-US/privacy/firefox-os/
* /firefox_privacy_notice
    * https://www.mozilla.org/en-US/privacy/firefox/
* /marketplace_developer_agreement
    * https://marketplace.firefox.com/developers/docs/policies/agreement?lang=en-US
* /marketplace_privacy_policy
    * https://marketplace.firefox.com/privacy-policy?lang=en-US
* /marketplace_terms_of_use
    * https://marketplace.firefox.com/terms-of-use?lang=en-US
* /mozilla_privacy_policy
    * https://www.mozilla.org/en-US/privacy/
* /websites_privacy_notice
    * https://www.mozilla.org/en-US/privacy/websites/
