## Detected Typos Diff
```diff
--- ./doc_source/mobile-devices-not-supported.md	original
+++ ./doc_source/mobile-devices-not-supported.md	fixed
@@ -5 +5 @@
-You can set up your CCP to forward the audio portion of the call to your mobile device\. For instructions, see [Forward calls to a mobile device \(iPhone, Android\)](foward-calls-to-mobile-device.md)\. +You can set up your CCP to forward the audio portion of the call to your mobile device\. For instructions, see [Forward calls to a mobile device \(iPhone, Android\)](forward-calls-to-mobile-device.md)\. --- ./doc_source/connect-attrib-list.md	original
+++ ./doc_source/connect-attrib-list.md	fixed
@@ -106 +106 @@
-| Call\-Forwarding\-Indicator | Call Forwarding Indicators \(for example, Diversion header\)\. Indicates domestic or international origin of call\.  Example value: sip:\+15555555555@public\-vip\.us2\.telphony\-provider\.com;reason=unconditional  | System | $\.Media\.Sip\.Headers\.Call\-Forwarding\-Indicator | 
+| Call\-Forwarding\-Indicator | Call Forwarding Indicators \(for example, Diversion header\)\. Indicates domestic or international origin of call\.  Example value: sip:\+15555555555@public\-vip\.us2\.telephony\-provider\.com;reason=unconditional  | System | $\.Media\.Sip\.Headers\.Call\-Forwarding\-Indicator | 
--- ./doc_source/foward-calls-to-mobile-device.md	original
+++ ./doc_source/forward-calls-to-mobile-device.md	fixed
@@ -1 +1 @@
-# Forward calls to a mobile device \(iPhone, Android\)<a name="foward-calls-to-mobile-device"></a>
+# Forward calls to a mobile device \(iPhone, Android\)<a name="forward-calls-to-mobile-device"></a>
--- ./doc_source/troubleshoot-pause-rewind-fastforward-recording.md	original
+++ ./doc_source/troubleshoot-pause-rewind-fastforward-recording.md	fixed
@@ -1 +1 @@
-# Troubleshoot problems pausing, rewinding, or fast\-fowarding recordings<a name="troubleshoot-pause-rewind-fastforward-recording"></a>
+# Troubleshoot problems pausing, rewinding, or fast\-forwarding recordings<a name="troubleshoot-pause-rewind-fastforward-recording"></a>
--- ./doc_source/create-object-type-mapping.md	original
+++ ./doc_source/create-object-type-mapping.md	fixed
@@ -72 +72 @@
-+ **Unique identifier**: You must have a unique identifier for your data in order to avoid an error when it is ingested\. This identifier is also known as the unique key\. Customer Profiles uses it to distinquish this data from other data source objects, and to index for search and update data\. 
++ **Unique identifier**: You must have a unique identifier for your data in order to avoid an error when it is ingested\. This identifier is also known as the unique key\. Customer Profiles uses it to distinguish this data from other data source objects, and to index for search and update data\. 
@@ -79 +79 @@
-  You can have mutliple customer identifiers\. 
+  You can have multiple customer identifiers\. 
@@ -82 +82 @@
-  Customer Profiles uses it to distinquish this data from other customer product purchase data\. It is also used to determine if the data can be associated to an existing profile or used to create a new profile by searching other profiles for this identifier\.
+  Customer Profiles uses it to distinguish this data from other customer product purchase data\. It is also used to determine if the data can be associated to an existing profile or used to create a new profile by searching other profiles for this identifier\.
@@ -87 +87 @@
-  Customer Profiles uses it to distinquish this data from other customer case data\. It is also used to determine if the data can be associated to an existing profile or used to create a new profile by searching other profiles for this identifier\.
+  Customer Profiles uses it to distinguish this data from other customer case data\. It is also used to determine if the data can be associated to an existing profile or used to create a new profile by searching other profiles for this identifier\.
@@ -92 +92 @@
-  Customer Profiles uses it to distinquish this data from other customer order data\. It is also used to determine if the data can be associated to an existing profile or used to create a new profile by searching other profiles for this identifier\.
+  Customer Profiles uses it to distinguish this data from other customer order data\. It is also used to determine if the data can be associated to an existing profile or used to create a new profile by searching other profiles for this identifier\.
--- ./doc_source/customerprofiles-s3-integration.md	original
+++ ./doc_source/customerprofiles-s3-integration.md	fixed
@@ -68 +68 @@
-    "ObjectTypeName": "your objec type",
+    "ObjectTypeName": "your object type",
--- ./doc_source/enable-wisdom.md	original
+++ ./doc_source/enable-wisdom.md	fixed
@@ -103 +103 @@
-If you are going to have mutiple integrations from the same source, we recommend you develop a naming convention to make them easy to distinguish\.
+If you are going to have multiple integrations from the same source, we recommend you develop a naming convention to make them easy to distinguish\.
--- ./doc_source/contact-initiation-methods.md	original
+++ ./doc_source/contact-initiation-methods.md	fixed
@@ -100 +100 @@
-To summarize, for callback contacts, the follwoing contact flow types are played:
+To summarize, for callback contacts, the following contact flow types are played:
--- ./doc_source/encrypt-data.md	original
+++ ./doc_source/encrypt-data.md	fixed
@@ -57 +57 @@
-     * To use, provide the following command line arguments: [path-to-private-key] [key-id] [cyphertext]
+     * To use, provide the following command line arguments: [path-to-private-key] [key-id] [ciphertext]
@@ -61 +61 @@
-     *  cyphertext is the result of the encryption operation from Amazon Connect
+     *  ciphertext is the result of the encryption operation from Amazon Connect
--- ./doc_source/configure-saml.md	original
+++ ./doc_source/configure-saml.md	fixed
@@ -184 +184 @@
-   1. Edit the trust relationship, and replace the signular `SAML:aud` condition with a multivalued condition\. For example:
+   1. Edit the trust relationship, and replace the singular `SAML:aud` condition with a multivalued condition\. For example:
--- ./doc_source/review-recorded-conversations.md	original
+++ ./doc_source/review-recorded-conversations.md	fixed
@@ -32 +32 @@
-## Pause, rewind, or fast\-foward a recording<a name="pause-rewind-fastforward-recording"></a>
+## Pause, rewind, or fast\-forward a recording<a name="pause-rewind-fastforward-recording"></a>
@@ -46 +46 @@
-## Troubleshoot problems pausing, rewinding, or fast\-fowarding<a name="problems-pause-rewind-fastforward-recording"></a>
+## Troubleshoot problems pausing, rewinding, or fast\-forwarding<a name="problems-pause-rewind-fastforward-recording"></a>
--- ./doc_source/browsers.md	original
+++ ./doc_source/browsers.md	fixed
@@ -19 +19 @@
-The Amazon Connect console and Contact Control Panel \(CCP\) do not work on mobile browsers\. However, your agents can forward the audio portion of the call to their mobile device\. For instructions, see [Forward calls to a mobile device \(iPhone, Android\)](foward-calls-to-mobile-device.md)\.
+The Amazon Connect console and Contact Control Panel \(CCP\) do not work on mobile browsers\. However, your agents can forward the audio portion of the call to their mobile device\. For instructions, see [Forward calls to a mobile device \(iPhone, Android\)](forward-calls-to-mobile-device.md)\.
--- ./doc_source/doc-history.md	original
+++ ./doc_source/doc-history.md	fixed
@@ -3 +3 @@
-The following table describes important changes in each release of the Amazon Connect Admininstrator Guide\. For notification about updates to this documentation, you can subscribe to an RSS feed\. 
+The following table describes important changes in each release of the Amazon Connect Administrator Guide\. For notification about updates to this documentation, you can subscribe to an RSS feed\. 
--- ./doc_source/troubleshooting.md	original
+++ ./doc_source/troubleshooting.md	fixed
@@ -16 +16 @@
-+ [Troubleshoot problems pausing, rewinding, or fast\-fowarding recordings](troubleshoot-pause-rewind-fastforward-recording.md)++ [Troubleshoot problems pausing, rewinding, or fast\-forwarding recordings](troubleshoot-pause-rewind-fastforward-recording.md)--- ./doc_source/real-time-metrics-definitions.md	original
+++ ./doc_source/real-time-metrics-definitions.md	fixed
@@ -199 +199 @@
-If a supervisor is using the Manager Monitor feature to monitor a particular agent as they interact with a customer, the superviser’s contact state is Monitoring; the agent’s contact state is Connected\.
+If a supervisor is using the Manager Monitor feature to monitor a particular agent as they interact with a customer, the supervisor’s contact state is Monitoring; the agent’s contact state is Connected\.
--- ./doc_source/index.md	original
+++ ./doc_source/index.md	fixed
@@ -578,38 +578,38 @@
-   + [Forward calls to a mobile device (iPhone, Android)](foward-calls-to-mobile-device.md)
-   + [View your schedule](scheduling-view-schedule-staff.md)
-   + [Set your status to "Available"](set-status-available.md)
-   + [Set your "Next status"](set-next-status.md)
-   + [Chat with contacts](work-with-chats.md)
-   + [Transfer chats to another queue](transfer-chats.md)
-   + [Make a call while on a chat](call-and-chat.md)
-   + [Accept incoming calls](work-with-calls.md)
-   + [Transfer calls to a quick connect or external number](transfers.md)
-   + [Multi-party calls: Add additional participants to an ongoing call](multi-party-calls.md)
-   + [Make outbound calls](make-outbound-calls.md)
-   + [Accept a task](accept-task.md)
-   + [Create a new task](create-task.md)
-   + [Transfer a task](transfer-task.md)
-   + [Accept incoming contacts with Customer Profiles](select-customer-profile.md)
-   + [Create a new customer profile](create-new-customer-profile.md)
-   + [Search for a customer profile](search-customer-profile.md)
-   + [Search for content using Amazon Connect Wisdom](search-for-answers.md)
-   + [Use real-time recommendations](use-realtime-recommendations.md)
-   + [Use Voice ID](use-voiceid.md)
-+ [Troubleshooting Issues with the Contact Control Panel (CCP)](troubleshooting.md)
-   + [Use the Endpoint Test Utility](check-connectivity-tool.md)
-   + [Common Contact Control Panel (CCP) Issues](common-ccp-issues.md)
-   + [Download CCP logs](download-ccp-logs.md)
-   + [Troubleshooting Tools and Information](tools-and-info.md)
-   + [Mobile phones (iPhone, Android) and iPads are not supported](mobile-devices-not-supported.md)
-   + [Microsoft Edge is not supported](microsoft-edge-not-supported.md)
-   + [Can't make an outbound call from the CCP](cant-make-outbound-call.md)
-   + [Attachments are not appearing in chats](attachments-not-appearing.md)
-   + [Humming sound in headset: Verify the headset and browser sample rates](verify-sample-rate.md)
-   + [One-way audio from customers?](one-way-audio-from-customers.md)
-   + [Troubleshoot problems pausing, rewinding, or fast-fowarding recordings](troubleshoot-pause-rewind-fastforward-recording.md)
-+ [Amazon Connect service quotas](amazon-connect-service-limits.md)
-+ [Additional resources for Amazon Connect](additional-resources.md)
-+ [Release notes](amazon-connect-release-notes.md)
-+ [Get administrative support for Amazon Connect](get-admin-support.md)
-+ [Amazon Connect Document history](doc-history.md)
-+ [Amazon Connect Glossary](amazon-connect-glossary.md)+   + [Forward calls to a mobile device (iPhone, Android)](forward-calls-to-mobile-device.md)
+   + [View your schedule](scheduling-view-schedule-staff.md)
+   + [Set your status to "Available"](set-status-available.md)
+   + [Set your "Next status"](set-next-status.md)
+   + [Chat with contacts](work-with-chats.md)
+   + [Transfer chats to another queue](transfer-chats.md)
+   + [Make a call while on a chat](call-and-chat.md)
+   + [Accept incoming calls](work-with-calls.md)
+   + [Transfer calls to a quick connect or external number](transfers.md)
+   + [Multi-party calls: Add additional participants to an ongoing call](multi-party-calls.md)
+   + [Make outbound calls](make-outbound-calls.md)
+   + [Accept a task](accept-task.md)
+   + [Create a new task](create-task.md)
+   + [Transfer a task](transfer-task.md)
+   + [Accept incoming contacts with Customer Profiles](select-customer-profile.md)
+   + [Create a new customer profile](create-new-customer-profile.md)
+   + [Search for a customer profile](search-customer-profile.md)
+   + [Search for content using Amazon Connect Wisdom](search-for-answers.md)
+   + [Use real-time recommendations](use-realtime-recommendations.md)
+   + [Use Voice ID](use-voiceid.md)
++ [Troubleshooting Issues with the Contact Control Panel (CCP)](troubleshooting.md)
+   + [Use the Endpoint Test Utility](check-connectivity-tool.md)
+   + [Common Contact Control Panel (CCP) Issues](common-ccp-issues.md)
+   + [Download CCP logs](download-ccp-logs.md)
+   + [Troubleshooting Tools and Information](tools-and-info.md)
+   + [Mobile phones (iPhone, Android) and iPads are not supported](mobile-devices-not-supported.md)
+   + [Microsoft Edge is not supported](microsoft-edge-not-supported.md)
+   + [Can't make an outbound call from the CCP](cant-make-outbound-call.md)
+   + [Attachments are not appearing in chats](attachments-not-appearing.md)
+   + [Humming sound in headset: Verify the headset and browser sample rates](verify-sample-rate.md)
+   + [One-way audio from customers?](one-way-audio-from-customers.md)
+   + [Troubleshoot problems pausing, rewinding, or fast-forwarding recordings](troubleshoot-pause-rewind-fastforward-recording.md)
++ [Amazon Connect service quotas](amazon-connect-service-limits.md)
++ [Additional resources for Amazon Connect](additional-resources.md)
++ [Release notes](amazon-connect-release-notes.md)
++ [Get administrative support for Amazon Connect](get-admin-support.md)
++ [Amazon Connect Document history](doc-history.md)
++ [Amazon Connect Glossary](amazon-connect-glossary.md)