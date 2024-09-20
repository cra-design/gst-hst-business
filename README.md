# GST/HST for Small Business [COP FY2024]

Project to optimize the content related to filing GST/HST returns.

**COP Timeframe:** [July 31, 2024 - February 2025]

## Important links

- Live proto site : [File a GST/HST return, rebate or election electronically](https://cra-proto.github.io/gst-hst-business/en/file-a-gst-hst-return-rebate-election-electronically.html)
- Scoped GST COP page list: [GST/HST for Business - scoping](https://122gc.sharepoint.com/sites/WOSCoordination/Lists/GSTHST%20for%20business%20COP%20%20scoping/AllItems.aspx?env=WebViewList&viewid=1379b8f8-af3b-47fb-ba50-29a24ea1d13d&useFiltersInViewXml=1&OR=Teams-HL&CT=1726666893920&clickparams=eyJBcHBOYW1lIjoiVGVhbXMtRGVza3RvcCIsIkFwcFZlcnNpb24iOiI0OS8yNDA4MTcwMDQxOSIsIkhhc0ZlZGVyYXRlZFVzZXIiOmZhbHNlfQ%3D%3D)
- [Jekyll theme for GCWeb]([https://github.com/cra-proto/gst-hst-business/blob/main/en/page_template-e.html](https://github.com/wet-boew/gcweb-jekyll))
- [User Centered Design Guide](https://design.cra-arc.alpha.canada.ca/en/index.html)
- [Github Canada.ca page template](https://github.com/cra-proto/gst-hst-business/blob/main/en/page_template-e.html)
- [Github Canada.ca page template \(Jekyll\)](https://github.com/cra-proto/gst-hst-business/blob/main/en/page_template_jekyll-en.html)

## Github update procedures:
- Test development files will be have **"_proto#"** appended to the end of the file name.
- Changes will be committed by **create a new branch** and then performing a pull request to merge the content.
- Updates should have comments identifying the change.
- Any path structure changes should be communicated to those updating the repo.
---

## Design phase steps:
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

```mermaid
gantt
    title Design phase timeframe
    dateFormat  YYYY-MM-DD
    section Design
    Create repo and import scoped files :active, a1, 2024-09-18, 3d
    User testing :a2, 2024-09-23, 14d
    Evaluation of user testing :a3, after a2, 14d
    Content and design updates and prototyping :after a3, 60d
```

## Canada.ca path structure: 
https://www.canada.ca/en/revenue-agency/services/e-services/digital-services-businesses/

```mermaid
mindmap
  root((digital-service-business - 8))
    [business-account - 1]
    [gst-hst-filing-remitting  - 3]
    [gst-hst-internet-file-transfer - 11]
    [gst-hst-netfile - 12]
    [gst-hst-telefile - 7]
```

**Updated:**  2024-09-18