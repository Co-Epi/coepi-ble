# coepi-ble
## Home of status, plans, tasks, etc.  associated with Bluetooth LE and its use by iOS and Android CoEpi Mobile Apps

## Under Construction :construction:

Bluetooth LE is a core technology for contact tracing on its own, but its use is deeply entwined with a collection of other technologies: smartphone hardware, operating systems (primarily iOS and Android), SDKs, app development, UX, RF propagation, ranging, contact detection, etc. This repo is a collection point for these interdisciplinary issues, not source control for a unified body of code, but a central organization point for a rapidly changing set of related concerns.

### Sequence of BLE implementations in CoEpi Mobile Apps
Given the Apple/Google announcement today (April 10, 2020), the following sequence of BLE implementations is proposed:

* **Current implementation:** Based on @Zsombor Szabo’s work, as implemented in the current iOS and Android test apps (V??) using a combination of Advertising and Connection techniques.
* **Interim implementation:** Optimized to use Advertising and Scanning BLE modes, without full connections, with the goal of better operation with apps in background mode, based on reverse engineering of BLE capabilities already widely deployed in the installed iOS and Android device base.
* **Future Implementation:** Based on the release of the official “Contract Tracing Services” from Google and Apple.

### Issues:
* **Timing:** Not sure when Apple or Google will release their respective Contact Tracing SDKs to the Developer Community
* **Wide Distribution:** Don’t know when the Contract Tracing services will be rolled out to the user community in OS updates (assuming OS changes are needed, beyond just the SDK for developers) and what the statistics for user adoption will be.
* **Interoperability:** Because of the above issues, interoperability between our implementations and migration between them will have to be supported.

### Mindmap for discussing and proposing issues:
At the top level of the repo, you’ll find a MindMap, (the CoEpi BLE issues.smmx file, directly editable with the free SimpleMind desktop app and a PDF file for simple viewing, see below).
If you have knowledge and verified facts to contribute, update a copy directly and send the result to me for updating the repo copy. Or if you’d like to sign up for a task to research or experimentally determine the facts. let me know and I’ll create task in the Github Project for you.


Suggestions welcome.






### \<to be continued\>





