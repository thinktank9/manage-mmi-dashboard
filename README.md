# IBM MAS Manage MMI Dashboard

A simple dashboard to pull Maximo Manage JVM stats using MMI APIs. To be used only for development, not meant for production, works only with the "all" server bundle.

## Setup

- Update Maximo Manage API key and Manage URL in the HTML.
- Set the `mxe.oslc.aclalloworigin` system property in Maximo Manage to *
- Include `apikey` in the existing list of headers in the `mxe.oslc.aclallowheaders` system property in Maximo Manage.
