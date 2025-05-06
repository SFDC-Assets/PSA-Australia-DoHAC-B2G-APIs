![Public Sector Accelerators logo](/docs/Logo_GPSAccelerators_v01.png)

# Australian DoHAC B2G API Integrations

[Required. Show overview of the Accelerator. This should match the approved content used on the Accelerator listing.]

[Accelerator Listing](https://gpsaccelerators.developer.salesforce.com/accelerator/a0wDo0000024oKbIAI/australian-dohac-b2g-api-integrations)


## Description

[Required. Description of the Accelerator. This should match the approved content used on the Accelerator listing, but could include additional content. This can include images/screenshots which must be stored in the /docs/ folder (no external images or images stored elsewhere in the repository.]

Accelerate your connection to the Business to Government (B2G) APIs using this MuleSoft Implementation Template.

This Accelerator provides a reference implementation on how to integrate MuleSoft with the Department of Health & Aged Care (DoHAC) B2G APIs. This includes:
- An example on how to use the authentication mechanism with the B2G [Authentication](https://developer.health.gov.au/s/communityapi/a018t0000010mpwAAA/acmauthenticationapi) to receive an access-token
- An APIkit enabled MuleSoft API to call the [Provider Management API](https://developer.health.gov.au/s/communityapi/a018t0000010mp1AAA/acmprovidermanagementapi) to retrieve Provider and HealthcareService details to use in subsequent B2G APIs.
- An APIkit enabled MuleSoft API which implements the [Quality Indicators (QI) API](https://developer.health.gov.au/s/communityapi/a01OZ000003SfL8YAK/acmqualityindicatorsapi) and [Registered Nurses (RN) API](https://developer.health.gov.au/s/communityapi/a01OZ000003yMDeYAM/acmregisterednursesapi). This asset can be used with MuleSoft AnyPoint Studio to connect to the data sources in your organisation where the data for QI & RN reside and implement any mappings and transformations to comply with the B2G API format specifications.

The B2G APIs will be the primary mechanism for Aged Care Providers to automate their interactions with the department. This accelerator can be used by any Aged Care provider to connect their internal systems to B2G APIs to take advantage of these automations and through MuleSoft connect them to the various internal databases and systems they may use. This is a technical accelerator designed to showcase the ease of integrating the B2G APIs with MuleSoft and provide a starting point for implementations. To use this accelerator in production environments customers will need to [apply for an account](https://developer.health.gov.au/s/organisation-registration) of the B2G Developer portal and undertake their own [conformance](https://developer.health.gov.au/s/conformance) assessment.

We will extend this accelerator as additional B2G APIs become available. As B2G APIs become available that support common aged care CRM workflows such as client, referral or assessment we will also provide pre-built components that extend these functionalities into the Salesforce CRM platform.

### Demo Video
Watch this video first to learn how the DoHAC APIs can be used at an Aged Care Facility to simplify reporting, save time and reduce costs.
[demo-video-stage1](https://drive.google.com/file/d/1Wu07B7EWHACP5BP3Zry9K2L2F65HfzVE/view?usp=drive_link)

### Demo App Showcase
This app can be found online at [demo-website](https://dohac-apis.fly.dev) and shows the live mock up of the Demo Video that you can use as inspiration.

The App showcases Aged Care Provider problems that can be solved via the DoHAC APIs via a web interface.

### Mulesoft Usable Assets
Here is the repository of reusable Mulesoft Assets, please find them in the ```/mulesoft``` folder in this repository.


## Included Assets

[Required. List of the assets included in the Accelerator and where to find them. This can be as detailed as desired, but at a minimum it should be detailed by asset type (unmanaged package, datapack, documentation, and other assets) and the next level metadata type (Salesforce metadata, datapack contents, separate documentation files, etc.) and their counts.]

This Accelerator includes the following assets:
<ol>
  <li>An <strong>unmanaged package</strong> (link below; metadata is also found in the /force-app/main/default/ folder) that includes:
    <ul>
      <li>Apex classes (x2)</li>
      <li>Custom objects (x4)</li>
      <li>Lightning Web Components (LWCs) (x2)</li>
    </ul>
  </li>
  <li><strong>OmniScripts</strong> (x2) located in the /datapacks/ folder</li>
  <li><strong>Documentation</strong>, including:
    <ul>
      <li>This readme file</li>
      <li>White paper providing detailed setup instructions and a data dictionary (located in the /docs/ folder)</li>
    </ul>
  </li>
</ol>


## Before You Install

[Required. Pre-requisites, dependencies, license requirements, and other assumptions and caveats should be declared here. Consider content that's specific to the Accelerator and the type of product or technology involved. The PMO may also add assumptions or notes that more broadly apply to the entire program.]

**License Requirements** [Required]
* Example: License Public Sector Solutions - requires Foundations or Advanced for internal; requires Communities for external

**Accelerator or Technology-Specific Assumptions** [Optional]
* Example: You have installed and configured OmniStudio and provided permission to PSS objects.
* Example: You are using OmniStudio's native runtime.

**General Assumptions** [Optional]
* Example: You are using this Accelerator in a sandbox or test environment. It is recommended that you not install any Accelerator directly into production environments.
* Example: If you do not have a Salesforce org licensed to you, you may try Public Sector Solutions for free with one of our [trial environments](https://developer.salesforce.com/free-trials/comparison/public-sector).
* Example: You are using this Accelerator in conjunction with the Salesforce Lightning Experience (LEX) - not the Classic UI.


## Installation

[Required. Steps necessary for installing the Accelerator. This can include images/screenshots which must be stored in the /docs/ folder (no external images or images stored elsewhere in the repository.]


## Post-Install Setup & Configuration

[Required. Steps necessary for using the Accelerator. This can include images/screenshots which must be stored in the /docs/ folder (no external images or images stored elsewhere in the repository.]


## FAQs

[Optional. Preemptive list of common questions or situations that need to be explained in how the Accelerator works (or doesn't).]

**_Q: Do I really need an FAQ for my Accelerator?_**

A: Great question! Perhaps not, but if you had common misunderstandings or confusion during beta testing with an aspect of setup or use, you may find it helpful to create some related FAQs. You might also wish to use FAQs to reiterate a critical point found in this readme or any other included documentation. An FAQ may also help point out a recommendation or tip about how to use your Accelerator.

## Additional Resources

[Optional. Summary list of additional links and references that you think are useful to. These links should be restricted to official Salesforce web resources and should not include third party references. Use an unordered list.]


## Revision History

[Required. High level description of the Accelerator's versions, with the date it was made publicly available. If more detailed release notes or change log are necessary, create a separate readme in the same folder and link to it from here.]
<strong>1.0 Initial release (30 Oct 2023)</strong> - Short description of the release. For detailed release notes and change logs, provide a link to another readme in the /docs/ folder of this repository.


## Acknowledgements

[Optional. Names of individuals involved in the creation, publication, and maintenance of this Accelerator and a link to their Github user profile.]


## Terms of Use

[Required. Cleared terms of use.  This must match the approved content used on the Accelerator listing.]

Thank you for using Global Public Sector (GPS) Accelerators.  Accelerators are provided by Salesforce.com, Inc., located at 1 Market Street, San Francisco, CA 94105, United States.

By using this site and these accelerators, you are agreeing to these terms. Please read them carefully.

Accelerators are not supported by Salesforce, they are supplied as-is, and are meant to be a starting point for your organization. Salesforce is not liable for the use of accelerators.

For more about the Accelerator program, visit: [https://gpsaccelerators.developer.salesforce.com/](https://gpsaccelerators.developer.salesforce.com/)
