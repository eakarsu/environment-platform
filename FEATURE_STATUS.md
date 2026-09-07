# Feature status — Environment, water, waste & carbon

| Capability | Status |
| --- | --- |
| Native sidebar and canonical feature registry | Built; 499 pages |
| Shared records, validation, relationships, persistence | Implemented in shared runtime |
| Clickable table rows with centered details popup | Implemented; Edit, Delete, Cancel, keyboard access and mobile layout |
| Domain field forms and source traceability | Imported from static source definitions; historical routes are labeled in mapping |
| CSV exports, attachments, audit and report totals | Implemented |
| At least 15 fictional rows per editable feature | Seeded by startup; measured in reports/seed-verification.json |
| AI question-and-answer workspace | Replaces AI feature tables; questions, context fields, formatted answers, follow-ups and saved history; live provider configuration required |
| Source calculation adapters | Available for explicitly registered calculation variants only |
| Source business-rule and state-machine parity | Incomplete beyond registered adapters and native records; verify each source journey |
| Original account/business data migration | Not performed; source data preserved |
| Provider integrations and external delivery | Not connected; request preparation only |
| Hosted authentication, independent-review roles and tenant isolation | Not migrated; local single-user boundary |

A successful build or populated table is not evidence of full source workflow parity. The source-to-feature map records every extracted definition and route, with explicit exclusions and migration warnings. Test/build reports distinguish checked behavior from remaining work.

| Canonical feature | Native mode | Source entries | Calculators | Status |
| --- | --- | ---: | ---: | --- |
| Clients & customers | records | 2 | 0 | Native records/view |
| Work items & projects | records | 1 | 0 | Native records/view |
| Contacts & parties | records | 2 | 0 | Native records/view |
| Tasks | records | 0 | 0 | Native records/view |
| Calendar | records | 0 | 0 | Native records/view |
| Deadlines & reminders | records | 0 | 0 | Native records/view |
| Notes | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Documents | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Templates | records | 0 | 0 | AI question-and-answer workspace; records available as context |
| Invoices & billing | records | 0 | 0 | Native records/view |
| Time tracking | records | 0 | 0 | Native records/view |
| Messages & communications | records | 4 | 0 | Native records/view |
| Reports & analytics | report | 10 | 0 | Native records/view |
| Activity & audit trail | audit | 9 | 0 | Native records/view |
| Provider connections | integration | 3 | 0 | Provider request records only |
| Emission Facility | records | 1 | 0 | Native records/view |
| Emission Unit | records | 1 | 0 | Native records/view |
| Permit Condition | records | 1 | 0 | Native records/view |
| Activity Reading | records | 1 | 0 | Native records/view |
| Emission Factor | records | 1 | 0 | Native records/view |
| Stack Test | records | 1 | 0 | Native records/view |
| Control Device | records | 1 | 0 | Native records/view |
| Deviation Event | records | 1 | 0 | Native records/view |
| Emission Report | records | 1 | 0 | Native records/view |
| Operational Task | records | 9 | 0 | Native records/view |
| Rule Version | records | 9 | 0 | Native records/view |
| Document Requirement | records | 9 | 0 | Native records/view |
| Permit condition extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Activity evidence reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stack test comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Deviation narrative draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Control-device maintenance brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Annual report narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Evidence completeness review | records | 9 | 0 | AI question-and-answer workspace; records available as context |
| Operations handoff draft | records | 9 | 0 | AI question-and-answer workspace; records available as context |
| Protected Property | records | 1 | 0 | Native records/view |
| Easement Term | records | 1 | 0 | Native records/view |
| Baseline Report | records | 1 | 0 | Native records/view |
| Stewardship Visit | records | 1 | 0 | Native records/view |
| Landowner Contact | records | 1 | 0 | Native records/view |
| Use Request | records | 1 | 0 | Native records/view |
| Potential Violation | records | 1 | 0 | Native records/view |
| Restoration Action | records | 1 | 0 | Native records/view |
| Stewardship Expense | records | 1 | 0 | Native records/view |
| Easement term extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Visit versus baseline comparison | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Landowner letter draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Use request evidence summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Violation chronology draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Annual stewardship narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Safety Asset | records | 1 | 0 | Native records/view |
| Engineering Inspection | records | 1 | 0 | Native records/view |
| Instrument | records | 1 | 0 | Native records/view |
| Instrument Reading | records | 1 | 0 | Native records/view |
| Action Threshold | records | 1 | 0 | Native records/view |
| Corrective Action | records | 1 | 0 | Native records/view |
| Emergency Plan | records | 1 | 0 | Native records/view |
| Emergency Exercise | records | 1 | 0 | Native records/view |
| Asset Maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Engineer observation summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Instrument anomaly explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Corrective action draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency plan completeness review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Exercise lessons summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Annual safety program narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Discharge Facility | records | 1 | 0 | Native records/view |
| Discharge Point | records | 1 | 0 | Native records/view |
| Effluent Limit | records | 1 | 0 | Native records/view |
| Effluent Sample | records | 1 | 0 | Native records/view |
| Flow Reading | records | 1 | 0 | Native records/view |
| Lab Custody | records | 1 | 0 | Native records/view |
| Pretreatment Asset | records | 1 | 0 | Native records/view |
| Discharge Incident | records | 1 | 0 | Native records/view |
| Discharge Report | records | 1 | 0 | Native records/view |
| Permit limit extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sample discrepancy review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Custody completeness check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Pretreatment maintenance summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Discharge incident narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Monitoring report draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dosimetry Program | records | 1 | 0 | Native records/view |
| Monitored Worker | records | 1 | 0 | Native records/view |
| Dosimeter Badge | records | 1 | 0 | Native records/view |
| Dose Result | records | 1 | 0 | Native records/view |
| Prior Exposure | records | 1 | 0 | Native records/view |
| Dose Threshold | records | 1 | 0 | Native records/view |
| Dose Investigation | records | 1 | 0 | Native records/view |
| Worker Acknowledgement | records | 1 | 0 | Native records/view |
| Vendor Reconciliation | records | 1 | 0 | Native records/view |
| Vendor report extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Badge assignment reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cumulative exposure record summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing report follow-up | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investigation narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Worker report explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waste Program | records | 1 | 0 | Native records/view |
| Waste Package | records | 1 | 0 | Native records/view |
| Waste Addition | records | 1 | 0 | Native records/view |
| Storage Survey | records | 1 | 0 | Native records/view |
| Package Inspection | records | 1 | 0 | Native records/view |
| Waste Transfer | records | 1 | 0 | Native records/view |
| Waste Manifest | records | 1 | 0 | Native records/view |
| Disposal Receipt | records | 1 | 0 | Native records/view |
| Waste Incident | records | 1 | 0 | Native records/view |
| Manifest extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Package inventory reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Survey evidence completeness | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer packet preparation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident chronology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waste program report draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recycler contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commodity grade registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Container pickup tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scale ticket ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Gross tare net validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Moisture deduction audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contamination deduction audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Commodity index pricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recovery percentage validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hauling fee audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Floor price control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Settlement matching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missing pickup detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recycler claim workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Plant commodity analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recycling Vessel | records | 1 | 0 | Native records/view |
| Vessel Component | records | 1 | 0 | Native records/view |
| Material Declaration | records | 1 | 0 | Native records/view |
| Supplier Declaration | records | 1 | 0 | Native records/view |
| Hazard Sample | records | 1 | 0 | Native records/view |
| Ihm Survey | records | 1 | 0 | Native records/view |
| Recycling Facility | records | 1 | 0 | Native records/view |
| Recycling Plan | records | 1 | 0 | Native records/view |
| Recycling Transfer | records | 1 | 0 | Native records/view |
| Material declaration extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supplier evidence gap review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| IHM discrepancy summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Survey preparation draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recycling plan evidence review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Material handoff narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hauling contract library | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Location container registry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scheduled service calendar | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service event ingestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Missed pickup credit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Haul charge calculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Weight ticket validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Disposal rate audit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contamination evidence | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Fuel surcharge validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Environmental fee control | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Invoice recalculation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hauler dispute workflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Location waste analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Water Account | records | 1 | 0 | Native records/view |
| Water Entitlement | records | 1 | 0 | Native records/view |
| Diversion Point | records | 1 | 0 | Native records/view |
| Meter Reading | records | 1 | 0 | Native records/view |
| Water Transfer | records | 1 | 0 | Native records/view |
| Water Delivery | records | 1 | 0 | Native records/view |
| Curtailment Notice | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Water Order | records | 1 | 0 | Native records/view |
| Season Reconciliation | records | 1 | 0 | Native records/view |
| Permit restriction extraction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Diversion reading reconciliation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transfer packet review | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Curtailment summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Delivery variance explanation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Season reconciliation narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Mitigation Bank | records | 1 | 0 | Native records/view |
| Mitigation Parcel | records | 1 | 0 | Native records/view |
| Credit Release | records | 1 | 0 | Native records/view |
| Credit Sale | records | 1 | 0 | Native records/view |
| Monitoring Plot | records | 1 | 0 | Native records/view |
| Plot Observation | records | 1 | 0 | Native records/view |
| Performance Criterion | records | 1 | 0 | Native records/view |
| Adaptive Action | records | 1 | 0 | Native records/view |
| Financial Assurance | records | 1 | 0 | Native records/view |
| Monitoring evidence mapping | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit ledger discrepancy brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Performance observation summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Adaptive management draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Release packet gap analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stewardship report draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Biochar soil carbon sequestration tracker work | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Carbon Credits | records | 2 | 0 | Native records/view |
| Transactions | records | 2 | 0 | Native records/view |
| Offset Projects | records | 1 | 0 | Native records/view |
| Verifications | records | 1 | 0 | Native records/view |
| Emissions Tracker | records | 1 | 0 | Native records/view |
| Market Analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit Retirements | records | 1 | 0 | Native records/view |
| Compliance Reports | records | 1 | 0 | Native records/view |
| Audit Trail | records | 1 | 0 | Native records/view |
| Offset Recommendations | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Sustainability Reports | records | 1 | 0 | Native records/view |
| Dashboard AI Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Credit Quality Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Price Suggestion | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Transaction Risk Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project Impact Evaluation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Auto-Verification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Carbon Calculator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Reduction Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Market Prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retirement Impact Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Certificate Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Compliance Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Security Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Pattern Detection | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI Sustainability Insights | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Additionality Validator | records | 1 | 0 | Native records/view |
| Vintage Maturity Analyzer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Market Price Predictor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance Reporter | records | 1 | 0 | Native records/view |
| Certification Tracker | records | 1 | 0 | Native records/view |
| Impact Verifier | records | 1 | 0 | Native records/view |
| Supply Chain Tracer | records | 1 | 0 | Native records/view |
| Buyer Portal Recommender | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retirements | records | 2 | 0 | Native records/view |
| Credits | records | 1 | 0 | Native records/view |
| Holders | records | 1 | 0 | Native records/view |
| Verifiers | records | 1 | 0 | Native records/view |
| Audits | records | 1 | 0 | Native records/view |
| Methodologies | records | 1 | 0 | Native records/view |
| Issuances | records | 1 | 0 | Native records/view |
| Beneficiaries | records | 1 | 0 | Native records/view |
| Scopes emissions | records | 1 | 0 | Native records/view |
| Scoreboard | records | 1 | 0 | Native records/view |
| Jurisdictional baselines | records | 1 | 0 | Native records/view |
| Satellite imagery | records | 1 | 0 | Native records/view |
| Smr reports | records | 1 | 0 | Native records/view |
| Claims | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Biodiversity cobenefits | records | 1 | 0 | Native records/view |
| Finance ledger | records | 1 | 0 | Native records/view |
| Verify project | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Synthesize mrv | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Detect fraud | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Analyze pricing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Map methodology | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Draft disclosure | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Leakage modeler | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Satellite mrv | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Double counting detect | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Additionality scorer | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Registry arbitrage | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Price discovery | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Biodiversity co benefit | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Climate claim validator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Supply cap forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scope 3 attributor | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Webhooks | integration | 5 | 0 | Provider request records only |
| Bulk import | records | 1 | 0 | Native records/view |
| Mrv document validate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Narrative evidence reconcile | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Aml screen transaction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Project rating | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Corresponding adjustments | records | 1 | 0 | Native records/view |
| Project ratings | records | 1 | 0 | Native records/view |
| Registry interop | records | 1 | 0 | Native records/view |
| Issuance chain | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Retirement certificate pack | records | 1 | 0 | Native records/view |
| Climate patterns | records | 1 | 0 | Native records/view |
| Alerts | records | 2 | 0 | Native records/view |
| Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Community risk matrix | records | 1 | 0 | Native records/view |
| Reef Sites | records | 1 | 0 | Native records/view |
| Nurseries | records | 1 | 0 | Native records/view |
| Fragments | records | 1 | 0 | Native records/view |
| Outplants | records | 1 | 0 | Native records/view |
| Monitoring Visits | records | 1 | 0 | Native records/view |
| Bleaching Events | records | 1 | 0 | Native records/view |
| Water Quality | records | 3 | 0 | Native records/view |
| Fish Counts | records | 1 | 0 | Native records/view |
| Divers | records | 1 | 0 | Native records/view |
| Equipment | records | 2 | 0 | Native records/view |
| Weather Logs | records | 1 | 0 | Native records/view |
| Vessels | records | 1 | 0 | Native records/view |
| Propagation Runs | records | 1 | 0 | Native records/view |
| Partners | records | 1 | 0 | Native records/view |
| Grants | records | 1 | 0 | Native records/view |
| Publications | records | 1 | 0 | Native records/view |
| Training Sessions | records | 1 | 0 | Native records/view |
| AI · Bleaching Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Fragment Health | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Survival Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Restoration Priority | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Executive Brief | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| AI · Water Anomaly | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Diver Safety | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Partner Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Grant Draft | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Propagation Success | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vessel Routing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Dive Window | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Species ID | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI · Publication Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Training Gap | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI · Donor Narrative | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Reef heat stress plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Species mix recommend | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Growth rate model | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Genotype rescue match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Dive logs | records | 1 | 0 | Native records/view |
| Citizen submissions | records | 1 | 0 | Native records/view |
| Citizen portal | records | 1 | 0 | Native records/view |
| Fragment lineage | records | 1 | 0 | Native records/view |
| Noaa crw | records | 1 | 0 | Native records/view |
| Weather Impact | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Carbon Footprint | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| Recycling Sorter | records | 2 | 0 | Native records/view |
| Energy Optimizer | records | 3 | 0 | AI question-and-answer workspace; records available as context |
| AI Goals | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Map | records | 1 | 0 | Native records/view |
| AI Insights | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| AI Results | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Feedback | records | 2 | 0 | Native records/view |
| Admin Panel | records | 1 | 0 | Native records/view |
| AI Water Quality Monitor | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Community carbon budget | records | 1 | 0 | Native records/view |
| Backlog | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| ESG Composite Score | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory Deadline Check | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Peer Benchmarking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Materiality Analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Certification Roadmap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Scope 3 Automation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Investor Relations Update | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory Tracker | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Circular Economy Optimization | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Net-Zero Roadmap (Agentic Sustainability Officer) | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Assurance readiness | records | 1 | 0 | Native records/view |
| Esg reports | records | 1 | 0 | Native records/view |
| Carbon footprints | records | 1 | 0 | Native records/view |
| Sustainability metrics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Regulatory compliance | records | 1 | 0 | Native records/view |
| Supply chain | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Risk assessments | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Greenwashing | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Stakeholder reports | records | 1 | 0 | Native records/view |
| Data validations | records | 1 | 0 | Native records/view |
| Climate scenarios | records | 1 | 0 | Native records/view |
| Biodiversity | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Water usage | records | 1 | 0 | Native records/view |
| Energy audits | records | 1 | 0 | Native records/view |
| Social impact | records | 1 | 0 | Native records/view |
| Governance | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Esg report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sustainability | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Risk | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Stakeholder | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Data validation | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Climate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Social | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Loads In | records | 1 | 0 | Native records/view |
| Contamination Logs | records | 1 | 0 | Native records/view |
| Bales | records | 1 | 0 | Native records/view |
| Loads Out | records | 1 | 0 | Native records/view |
| Contracts | records | 1 | 0 | Native records/view |
| Commodities | records | 1 | 0 | Native records/view |
| Prices | records | 1 | 0 | Native records/view |
| Drivers | records | 2 | 0 | Native records/view |
| Vehicles | records | 3 | 0 | Native records/view |
| Sortation Lines | records | 1 | 0 | Native records/view |
| Downtime Events | records | 1 | 0 | Native records/view |
| Operators | records | 1 | 0 | Native records/view |
| Safety Incidents | records | 1 | 0 | Native records/view |
| Training Records | records | 2 | 0 | Native records/view |
| Vendors | records | 1 | 0 | Native records/view |
| AI · Contamination Vision | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Price Forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Sortation Balance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Downtime RCA | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Customer Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Quote Compare | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Route / Pickup | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Safety Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Training Needs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Hauler Recon | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Capacity Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Equipment Prognostic | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Bale Quality Grade | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Regulatory Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Scrap Market Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Producers | records | 1 | 0 | Native records/view |
| Sku obligations | records | 1 | 0 | Native records/view |
| Epr filings | records | 1 | 0 | Native records/view |
| Scale tickets | records | 1 | 0 | Native records/view |
| Routes | records | 2 | 0 | Native records/view |
| Route stops | records | 1 | 0 | Native records/view |
| Buyers | records | 1 | 0 | Native records/view |
| Buyer specs | records | 1 | 0 | Native records/view |
| Line camera anomaly narrate | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Throughput forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| End market match | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Contamination report card | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly completion | records | 1 | 0 | Native records/view |
| Dynamic pricing | records | 1 | 0 | Native records/view |
| Driver leaderboard | records | 1 | 0 | Native records/view |
| Contamination detect | records | 1 | 0 | Native records/view |
| Predictive overflow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Compliance check | records | 1 | 0 | Native records/view |
| Bins | records | 1 | 0 | Native records/view |
| Schedules | records | 1 | 0 | Native records/view |
| Zones | records | 1 | 0 | Native records/view |
| Waste prediction | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Waste classification | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Cost analysis | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Environmental impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Recycling analytics | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Anomaly detection | records | 2 | 0 | AI question-and-answer workspace; records available as context |
| Demand forecasting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Predict vehicle maintenance | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver coaching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real time anomaly detection on collection completion | records | 1 | 0 | Native records/view |
| Dynamic pricing by neighborhood demand and waste stream | records | 1 | 0 | Native records/view |
| Driver performance leaderboard with ai coaching | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Smart contamination detection in recycling streams vision io | records | 1 | 0 | Native records/view |
| Predictive bin overflow with proactive scheduling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Municipal regulation compliance automation | records | 1 | 0 | Native records/view |
| Carbon credit marketplace integration | integration | 1 | 0 | Provider request records only |
| Predictive vehicle maintenance from telemetry | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Powered driver route coaching and fuel efficiency feedbac | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Computer vision bin condition assessment | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customerresident portal for service requests | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Billinginvoicing for commercial accounts | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Complaint and missed pickup ticketing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Real time gps tracking dashboard with live etas | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Hazardous waste manifest tracking | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Driver mobile app endpoints | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Sensor fusion | records | 1 | 0 | Native records/view |
| Demand nowcast | records | 1 | 0 | Native records/view |
| Conservation incentives | records | 1 | 0 | Native records/view |
| Main break response | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Public quality snapshot | records | 1 | 0 | Native records/view |
| Smart meter rollout | records | 1 | 0 | Native records/view |
| Leak detection | records | 1 | 0 | Native records/view |
| Demand forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Infrastructure aging | records | 1 | 0 | Native records/view |
| Treatment optimization | records | 1 | 0 | Native records/view |
| Meter readings | records | 1 | 0 | Native records/view |
| Work orders | records | 1 | 0 | Native records/view |
| Pipe inventory | records | 1 | 0 | Native records/view |
| Pump stations | records | 1 | 0 | Native records/view |
| Reservoirs | records | 1 | 0 | Native records/view |
| Emergency response | records | 1 | 0 | Native records/view |
| Real time multi sensor fusion flow pressure chlorine turbidi | records | 1 | 0 | Native records/view |
| Water demand nowcasting from weather events time of day | records | 1 | 0 | Native records/view |
| Meter analytics driving conservation incentive programs | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Emergency response integration for main breaks | integration | 1 | 0 | Provider request records only |
| Public water quality dashboard | records | 1 | 0 | Native records/view |
| Smart meter rollout orchestration with hand off to billing | records | 1 | 0 | Native records/view |
| Preventive maintenance scheduling ai | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer segment demand modeling | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Computer vision pipe inspection from camera feeds | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Customer billing and meter to cash flow | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Service disruption notification smsemail | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Full gis map integration for pipe network | integration | 1 | 0 | Provider request records only |
| Permitregulatory tracking and reporting | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Public facing transparency portal | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Rangers | records | 1 | 0 | Native records/view |
| Patrols | records | 1 | 0 | Native records/view |
| Camera Traps | records | 1 | 0 | Native records/view |
| Snare Finds | records | 1 | 0 | Native records/view |
| Animal Sightings | records | 1 | 0 | Native records/view |
| Species Profiles | records | 1 | 0 | Native records/view |
| Poacher Incidents | records | 1 | 0 | Native records/view |
| Weapons Recovered | records | 1 | 0 | Native records/view |
| Court Cases | records | 1 | 0 | Native records/view |
| Ranger Shifts | records | 1 | 0 | Native records/view |
| Drones | records | 1 | 0 | Native records/view |
| Comms Devices | records | 1 | 0 | Native records/view |
| Supplies | records | 1 | 0 | Native records/view |
| Parks | records | 1 | 0 | Native records/view |
| Gates | records | 1 | 0 | Native records/view |
| AI · Patrol Dispatch | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Hot-Zone Predict | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Snare Heatmap | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Pattern Analyze | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Safety Brief | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Court Case Summary | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Drone Flight Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vehicle Routing | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Comms Plan | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Weather Impact | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Supply Resupply | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Vendor Quality | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| AI · Donor Impact Report | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Intel report summarize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Incident narrator | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Snare prevalence forecast | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Multi patrol optimize | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Camera trap image classify | records | 1 | 0 | AI question-and-answer workspace; records available as context |
| Community reports | records | 1 | 0 | Native records/view |
| Anonymous tips | records | 1 | 0 | Native records/view |
| Partner integrations | integration | 1 | 0 | Provider request records only |
| Rules & Jobs | records | 2 | 0 | Native records/view |

Row popup verification passed: dashboard and feature rows, keyboard/focus, editing and persistence, delete confirmation/cancellation, centered mobile layout and full-record navigation. See `reports/row-popup-verification.json`.

## Verified local build

Build, API, browser and actual `start.sh` checks passed. All 499 feature pages were visited in the browser; 497 editable tables contain at least 15 fictional rows each. CRUD persistence and mobile layout were checked. Evidence is in `reports/verification.json`, `reports/browser-verification.json` and `reports/startup-verification.json`.

These checks cover the native local workspace. Full source-specific business rules, authentication and live provider operations remain incomplete as described above. Test servers were stopped after verification.

## AI workspace verification

All 255 AI feature routes were checked in the browser and show questions and formatted answers instead of the original record table. Existing records are retained as optional context. Questions, follow-ups, saved history across restart, Markdown tables, safe rendering, downloads, provider-failure recovery and mobile layout passed with a mocked provider. See `reports/ai-workspace-verification.json`.

Live answers require `OPENROUTER_API_KEY` and `OPENROUTER_MODEL` in this app's `.env` and an app restart. No live provider call was made during verification. Conversational answers do not execute unmigrated specialist engines, read record attachments automatically or perform external actions.


## AI word limits

Questions support up to 5,000 words with a live counter and server validation. AI responses and record drafts have a 16,000-token output budget and a default 180-second timeout to support answers up to 5,000 words; actual length depends on the request and model. Answers show their word count, and long questions can be expanded. Browser checks passed for 5,000-word questions and answers, saved history, full downloads, mobile layout and rejection of 5,001-word questions. See `reports/word-limit-verification.json` (mock-provider boundary checks).

## Merged AI assistants

255 original AI entries are now grouped into **6 assistants** in the sidebar. Choose up to 8 related capabilities and add up to 10 questions for one provider request and one saved response. Shared context is sent once; repeated questions are removed after trimming and whitespace/case normalization. The total question limit is 5,000 words and the combined answer target is up to 5,000 words.

Original feature URLs still open the appropriate assistant with that capability selected. Existing records and answers stay in place; the assistant history includes answers saved under its member features. Non-AI record tables retain their popup actions. This merges the assistant workflow and navigation; it does not implement previously missing external integrations or specialist engines. See `reports/assistant-merge-map.json` and `reports/assistant-merge-verification.json`.

## Floating Ask AI assistant

Implemented across this workspace. The bottom-right **Ask AI** button opens a persistent chat panel on every page. Use **Ask AI about item** in a row popup or record view, or **Use current item** inside the panel, to supply the selected record.

- Questions about the page, any explicitly chosen app record, and general topics.
- Formatted answers, comparison tables, follow-ups, copy and Markdown download.
- Conversation and question drafts stay intact during in-app navigation. Saved answers persist in SQLite; the last conversation restores in the same browser tab after reload. The latest 50 saved answers are listed; restoring one displays up to 20 turns. Up to four preceding turns are sent as AI context.
- Up to 5,000 input words and a response budget of up to 5,000 words. Output length remains dependent on the provider and the question.
- Page title and description are supplied automatically; record fields and notes are sent only for a selected item. Attachments and unselected records are not included. **New chat** starts without earlier conversation context.
- Existing AI provider configuration, timeout, rate limit and safe response renderer are reused. The assistant answers and drafts; it does not execute record changes or external actions.

Validation: shared backend tests, all 64 app builds/API checks, and all 64 browser checks passed with an injected test provider. Browser checks cover item context, navigation, saved history/reload, follow-ups, new-chat isolation, error recovery, word limits, keyboard controls, mobile bounds, safe Markdown rendering and attachment refresh. See [verification](reports/floating-ai-verification.json).
