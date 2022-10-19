## Detected Typos Diff
```diff
--- ./api_format.md	original
+++ ./api_format.md	fixed
@@ -76 +76 @@
-| DOI | String | No | Optional [Open Funder Registry](http://www.crossref.org/fundingdata/registry.html) DOI uniquely identifing the funding body |
+| DOI | String | No | Optional [Open Funder Registry](http://www.crossref.org/fundingdata/registry.html) DOI uniquely identifying the funding body |
@@ -85 +85 @@
-| registry | String | Yes | DOI of the clinical trial regsitry that assigned the trial number |
+| registry | String | Yes | DOI of the clinical trial registry that assigned the trial number |
--- ./deprecated/scratch.md	original
+++ ./deprecated/scratch.md	fixed
@@ -96 +96 @@
-crawler="subsciber"
+crawler="subscriber"
@@ -118 +118 @@
-What are things we want to distnguish:
+What are things we want to distinguish:
@@ -126 +126 @@
-OPDS has what they call "aquisition links" where rel attribute is set to a URI indicating what is being pointed to. They have the following types:
+OPDS has what they call "acquisition links" where rel attribute is set to a URI indicating what is being pointed to. They have the following types:
--- ./api_tips.md	original
+++ ./api_tips.md	fixed
@@ -26 +26 @@
-What? No, seriously- Crossref periodically releases [public data file](https://www.crossref.org/blog/new-public-data-file-120-million-metadata-records/) of all the metdata that is available via our public API. You can download this file from [Academic Torrents](https://academictorrents.com/) with your favorite torrent client and do a lot of work locally if you want to. At the very least, having the local file will allow you to focus on using the API only for metadata records that have been updated since the last public data file was released.
+What? No, seriously- Crossref periodically releases [public data file](https://www.crossref.org/blog/new-public-data-file-120-million-metadata-records/) of all the metadata that is available via our public API. You can download this file from [Academic Torrents](https://academictorrents.com/) with your favorite torrent client and do a lot of work locally if you want to. At the very least, having the local file will allow you to focus on using the API only for metadata records that have been updated since the last public data file was released.
@@ -80 +80 @@
-Note much to say. We implimented rows/offsets early in the development of the API and regretted it emmediately. So we implimented cursors instead and kept rows/offsets so as to not break existing scripts. But NOBODY should use them.
+Note much to say. We implemented rows/offsets early in the development of the API and regretted it immediately. So we implemented cursors instead and kept rows/offsets so as to not break existing scripts. But NOBODY should use them.
--- ./deprecated/ad_hoc_deposits.md	original
+++ ./deprecated/ad_hoc_deposits.md	fixed
@@ -21 +21 @@
-2. Manually or programatically alter or create deposit XML.
+2. Manually or programmatically alter or create deposit XML.
--- ./deprecated/archive_query_api.md	original
+++ ./deprecated/archive_query_api.md	fixed
@@ -37 +37 @@
-To faciliate archive arrangement verification, a common query API is proposed that
+To facilitate archive arrangement verification, a common query API is proposed that
--- ./deprecated/rest_api_tour.md	original
+++ ./deprecated/rest_api_tour.md	fixed
@@ -183 +183 @@
-What licenses does a reasearcher with a particular ORCID publish under
+What licenses does a researcher with a particular ORCID publish under
--- ./deprecated/deposit_api.md	original
+++ ./deprecated/deposit_api.md	fixed
@@ -18 +18 @@
-- an inability to programatically track the status of a deposit
+- an inability to programmatically track the status of a deposit
@@ -21,2 +21,2 @@
-- no way of programatically querying for a historic list of deposits
-- no way of programatically retrieveing previously deposited XML.
+- no way of programmatically querying for a historic list of deposits
+- no way of programmatically retrieveing previously deposited XML.
@@ -70 +70 @@
-Deposits are modified slightly from the submitted form. This is to faciliate
+Deposits are modified slightly from the submitted form. This is to facilitate
@@ -112 +112 @@
-Set the `test` paramter to `true`, `t` or `1` (any other value is considered false)
+Set the `test` parameter to `true`, `t` or `1` (any other value is considered false)
--- ./funder_kpi_metadata_best_practice.md	original
+++ ./funder_kpi_metadata_best_practice.md	fixed
@@ -22 +22 @@
-		- [Assigning and registering DOIs for manuscripts that the publisher *has* made avaialble online](#assigning-and-registering-dois-for-manuscripts-that-the-publisher-has-made-avaialble-online)
+		- [Assigning and registering DOIs for manuscripts that the publisher *has* made available online](#assigning-and-registering-dois-for-manuscripts-that-the-publisher-has-made-available-online)
@@ -339,3 +339,3 @@
-- __must__ must be replaced with appropriate full metadata using an appropriate schema for the content type when the publisher makes the content publically available
-- __should__ include an "intent to publish statement." If the publisher does not provide an "intent to publish statement" of their own, then Crossref will provide a default statement.
-- __may__ include a logo to diplay at the top of the landing page
+- __must__ must be replaced with appropriate full metadata using an appropriate schema for the content type when the publisher makes the content publicly available
+- __should__ include an "intent to publish statement." If the publisher does not provide an "intent to publish statement" of their own, then Crossref will provide a default statement.
+- __may__ include a logo to display at the top of the landing page
--- ./README.md	original
+++ ./README.md	fixed
@@ -374 +374 @@
-is ANDed with the others:
+is ANDead with the others:
@@ -505 +505 @@
-| `award.number` | `{award_number}` | metadata for records with a matching award nunber. Optionally combine with `award.funder` |
+| `award.number` | `{award_number}` | metadata for records with a matching award number. Optionally combine with `award.funder` |
@@ -565 +565 @@
-Crossref also has member IDs for depositing organisations. A single member may control multiple owner prefixes, which in turn may control a number of DOIs. When looking at works published by a certain organisaton, member IDs and the member routes should be used.
+Crossref also has member IDs for depositing organisations. A single member may control multiple owner prefixes, which in turn may control a number of DOIs. When looking at works published by a certain organisation, member IDs and the member routes should be used.
@@ -744,47 +744,47 @@
-- v23, 2014-09-01, semantics of mutliple filters, dot filters
-- v24, 2014-10-15, added info on license of Crossref metadata itself. Doh.
-- v25, 2015-05-06, added link to issue tracker. Removed Warning section.
-- v26, 2015-10-20, added new filters - `from-created-date`, `until-created-date`, `affiliation`, `has-affiliation`, `assertion-group`, `assertion`, `article-number`, `alternative-id`
-- v27, 2015-10-30, added `cursor` parameter to `/works` resources
-- v28, 2016-05-09, added link to source of category lables
-- v29, 2016-05-24, added field queries
-- v30, 2016-09-26, highlight issue tracker
-- v31, 2016-10-05, document `has-clinical-trial-number` and `has-abstract` filters
-- v32, 2016-10-27, document rate limit headers
-- v33, 2016-11-07, guidance on when to use `offset` vs `cursor`
-- v34, 2017-04-26, document support for HTTPS. Update examples to use HTTPS.
-- v35, 2017-04-26, document use of head reqeusts to determine `existence`
-- v36, 2017-04-27, fixed license route examples to use facet/filter instead
-- v37, 2017-04-27, `query.bibliographic`
-- v38, 2017-04-27, add v1.1 filters and sort fields
-- v39, 2017-04-27, remove mention of dismax
-- v40, 2017-04-27, clarify faceting feature
-- v41, 2017-04-28, document `sample` max = 100, clarify cursors only work on some routes
-- v42, 2017-04-28, life, the universe, and everything
-- v43, 2017-04-28, reminder on the wisdom of url-encoding
-- v44, 2017-04-28, clarify that field queries apply to `/works` route
-- v45, 2017-04-28, document `location` filter for `/funders` route
-- v46, 2017-06-14, minor text changes and new funder registry link
-- v47, 2017-07-04, clarify `query.affiliation`
-- v48, 2017-07-13, correct "first and given" names to "given and family"
-- v49, 2017-07-20, move document version history, add section on libraries
-- v50, 2017-07-20, add TOC, move document history, add etiquet section, add production use section, general formatting + cleanup
-- v51, 2017-07-24, clarified license of the documentation (as opposed to metadata)
-- v52, 2017-07-27, removed service notice and what's new section.
-- v53, 2017-08-11, mention `full-text.application` filter
-- v54, 2017-09-18, add info about new "polite pool"
-- v55, 2017-09-21, document `/member` and `/funder` filters. document `publisher-name` facet. document `select` parameter.
-- v56, 2018-01-26, add info on frequency of indexing
-- v57, 2018-02-01, document ISBN filter
-- v58, 2018-02-13, document `reference-visibility` filter for `/works` and `/members` routes
-- v59, 2018-02-13, added info about Mtedata Plus service. Corrected spelling. Added example of using `reference-visibility` filter.
-- v60, 2018-02-22, added info for "Plus" users on use of token in `Authorization` header.
-- v61, 2018-02-26, add curl example for use of token.
-- v62, 2018-06-18, clarify how to parse `X-Rate-Limit-Limit-Interval`
-- v63, 2018-08-16, remove mistakenly listed `year` facet. `published` is correct facet name.
-- v64, 2018-09-04, add text and link to status page.
-- v65, 2019-07-17, updated Plus token name to new recommendation 
-- v66, 2019-10-16, deprecated query.title for query.bibliographic
-- v67, 2020-04-28, clarify that url-encoding should be applied to all parameters including cursors.
-- v68, 2021-02-22, Added link to Pitaya Julia library
-- v69, 2021-04-30, Update preamble with reading advise
+- v23, 2014-09-01, semantics of multiple filters, dot filters
+- v24, 2014-10-15, added info on license of Crossref metadata itself. Doh.
+- v25, 2015-05-06, added link to issue tracker. Removed Warning section.
+- v26, 2015-10-20, added new filters - `from-created-date`, `until-created-date`, `affiliation`, `has-affiliation`, `assertion-group`, `assertion`, `article-number`, `alternative-id`
+- v27, 2015-10-30, added `cursor` parameter to `/works` resources
+- v28, 2016-05-09, added link to source of category labels
+- v29, 2016-05-24, added field queries
+- v30, 2016-09-26, highlight issue tracker
+- v31, 2016-10-05, document `has-clinical-trial-number` and `has-abstract` filters
+- v32, 2016-10-27, document rate limit headers
+- v33, 2016-11-07, guidance on when to use `offset` vs `cursor`
+- v34, 2017-04-26, document support for HTTPS. Update examples to use HTTPS.
+- v35, 2017-04-26, document use of head requests to determine `existence`
+- v36, 2017-04-27, fixed license route examples to use facet/filter instead
+- v37, 2017-04-27, `query.bibliographic`
+- v38, 2017-04-27, add v1.1 filters and sort fields
+- v39, 2017-04-27, remove mention of dismax
+- v40, 2017-04-27, clarify faceting feature
+- v41, 2017-04-28, document `sample` max = 100, clarify cursors only work on some routes
+- v42, 2017-04-28, life, the universe, and everything
+- v43, 2017-04-28, reminder on the wisdom of url-encoding
+- v44, 2017-04-28, clarify that field queries apply to `/works` route
+- v45, 2017-04-28, document `location` filter for `/funders` route
+- v46, 2017-06-14, minor text changes and new funder registry link
+- v47, 2017-07-04, clarify `query.affiliation`
+- v48, 2017-07-13, correct "first and given" names to "given and family"
+- v49, 2017-07-20, move document version history, add section on libraries
+- v50, 2017-07-20, add TOC, move document history, add etiquet section, add production use section, general formatting + cleanup
+- v51, 2017-07-24, clarified license of the documentation (as opposed to metadata)
+- v52, 2017-07-27, removed service notice and what's new section.
+- v53, 2017-08-11, mention `full-text.application` filter
+- v54, 2017-09-18, add info about new "polite pool"
+- v55, 2017-09-21, document `/member` and `/funder` filters. document `publisher-name` facet. document `select` parameter.
+- v56, 2018-01-26, add info on frequency of indexing
+- v57, 2018-02-01, document ISBN filter
+- v58, 2018-02-13, document `reference-visibility` filter for `/works` and `/members` routes
+- v59, 2018-02-13, added info about Mtedata Plus service. Corrected spelling. Added example of using `reference-visibility` filter.
+- v60, 2018-02-22, added info for "Plus" users on use of token in `Authorization` header.
+- v61, 2018-02-26, add curl example for use of token.
+- v62, 2018-06-18, clarify how to parse `X-Rate-Limit-Limit-Interval`
+- v63, 2018-08-16, remove mistakenly listed `year` facet. `published` is correct facet name.
+- v64, 2018-09-04, add text and link to status page.
+- v65, 2019-07-17, updated Plus token name to new recommendation 
+- v66, 2019-10-16, deprecated query.title for query.bibliographic
+- v67, 2020-04-28, clarify that url-encoding should be applied to all parameters including cursors.
+- v68, 2021-02-22, Added link to Pitaya Julia library
+- v69, 2021-04-30, Update preamble with reading advise
--- ./demos/crossref-api-demo.ipynb	original
+++ ./demos/crossref-api-demo.ipynb	fixed
@@ -44 +44 @@
-    "# If veiwing in pineapple notebook, uncomment the next two lines and then run the cell.\n",
+    "# If viewing in pineapple notebook, uncomment the next two lines and then run the cell.\n",
@@ -156 +156 @@
-    "Note that above I said \"How many Crossref DOIs\". There are several other [DOI registration agencies](https://www.doi.org/registration_agencies.html). Crossref is by far he largest DOI RA, and the other RAs tend to specialize in orthoganal areas (e.g. Music & Video, Local language translations of publications, etc.) but it is important to not that this API will not work with non-Crossref DOIs (though [DataCite](https://www.datacite.org/), another RA, provides a very similar API).\n",
+    "Note that above I said \"How many Crossref DOIs\". There are several other [DOI registration agencies](https://www.doi.org/registration_agencies.html). Crossref is by far he largest DOI RA, and the other RAs tend to specialize in orthogonal areas (e.g. Music & Video, Local language translations of publications, etc.) but it is important to not that this API will not work with non-Crossref DOIs (though [DataCite](https://www.datacite.org/), another RA, provides a very similar API).\n",
@@ -306 +306 @@
-    "**TIP:** Publishers sometimes record information for multiple versions of the content identified by a DOI. These versions should be interchaneable from the point of view of citation, but sometimes one version has more \"features\" than another. For example, it might be typset or have references linked, etc. The two versions might also have different licenses and different URLs. The terminology publishers use for identifying versions comes from the [NISO standard call JAV (Journal Article Version)](http://www.niso.org/publications/rp/RP-8-2008.pdf) and, although this terminology is [sometimes problematic](https://f1000research.com/articles/6-608/v1), you should be aware of it. In particualr, you will see two terms used  in Crossref metadata:\n",
+    "**TIP:** Publishers sometimes record information for multiple versions of the content identified by a DOI. These versions should be interchaneable from the point of view of citation, but sometimes one version has more \"features\" than another. For example, it might be typset or have references linked, etc. The two versions might also have different licenses and different URLs. The terminology publishers use for identifying versions comes from the [NISO standard call JAV (Journal Article Version)](http://www.niso.org/publications/rp/RP-8-2008.pdf) and, although this terminology is [sometimes problematic](https://f1000research.com/articles/6-608/v1), you should be aware of it. In particular, you will see two terms used  in Crossref metadata:\n",
@@ -428 +428 @@
-    "**TIP:** Many people make the mistake of thinking that a \"DOI prefix\" can be used to identify the member responsible for a Crossref DOI. This is not true. DOI prefixes merely serve as a namespace form which a member can create new DOIs without worrying about collisions. But, once created, Crossref DOIs are often transfered between publishers and so a Crossref member will often be responsible for DOIs with a variety of prefixes. So, for example, above, Hindawi is responsible for several prefixes:"
+    "**TIP:** Many people make the mistake of thinking that a \"DOI prefix\" can be used to identify the member responsible for a Crossref DOI. This is not true. DOI prefixes merely serve as a namespace form which a member can create new DOIs without worrying about collisions. But, once created, Crossref DOIs are often transferred between publishers and so a Crossref member will often be responsible for DOIs with a variety of prefixes. So, for example, above, Hindawi is responsible for several prefixes:"
