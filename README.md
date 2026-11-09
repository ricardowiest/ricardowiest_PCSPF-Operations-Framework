PCSPF — Port-Corridor SME Performance Framework
Version 1.0 | Excel-based operational and financial control toolkit

PCSPF is a practical prototype designed to help small and medium-sized businesses involved in freight, bulk-material distribution, and port-adjacent operations organize their operational and financial records.

It brings together shipment tracking, ticket-to-invoice reconciliation, direct-cost analysis, equipment and fuel monitoring, accounts receivable, and basic operational performance indicators in a single workbook.
What it does
- Tracks shipments, dispatch times, quantities, and invoice references.
- Checks consistency between delivery tickets and invoices.
- Calculates revenue, direct costs, and contribution margins by product.
- Records equipment activity and fuel consumption.
- Monitors payment status and outstanding receivables.
- Displays key indicators through a dashboard.
- Includes a data dictionary, technical notes, and quality-assurance checks.
Files
- PCSPF Excel Toolkit: the working spreadsheet containing the dashboard, formulas, controls, and demonstration data.
- User and Implementation Guide: instructions, workbook structure, data definitions, and implementation considerations.
- Technical Validation Report: documented test methodology, reproducible sample results, limitations, and follow-up validation needs.
Quick start
1. Download the latest corrected PCSPF 1.0 Excel workbook from this repository.
2. Open it in Microsoft Excel with automatic calculation enabled.
3. Read the START HERE worksheet and the User and Implementation Guide.
4. Review the sample records and results on the DASHBOARD and QA TESTS worksheets.
5. Before using real records, work from a separate copy and verify the formulas, data mapping, and controls against your own business processes.
Demonstration results
The workbook contains 100 synthetic shipment records used for repeatable testing.
Measure	Baseline scenario	Alternative scenario
Ticket-to-invoice matches	85 / 100	97 / 100
Total dispatch duration	5,885 minutes	5,383 minutes
Median dispatch duration	59.0 minutes	53.5 minutes


The reference dataset passed 13 predefined QA checks. Additional controlled input changes were used to verify that selected data-quality alerts respond to errors.

These scenarios are simulated. The difference between them is a modeled result, not a measured reduction in real-world operating time or a verified financial benefit.
Current status and limitations
Status: Functional demonstration prototype (v1.0).
- The sample data are synthetic and do not represent actual U.S. companies or transactions.
- The toolkit has not yet undergone independent field validation or a live-company pilot.
- Compatibility and recalculation should be checked in the intended Microsoft Excel environment before operational use.
- The contribution-margin calculation is not a full net-profit calculation. Equipment fuel records must not be added to shipment costs without an appropriate cost-allocation method.
- Do not upload confidential company data, personal information, or proprietary records to this public repository.
Project objective
The longer-term objective is to develop a documented, adaptable set of controls that freight-adjacent small businesses can assess and tailor to their own operations. Future work may include practitioner feedback, real-world pilots conducted with permission, additional testing, and documented revisions.
Documentation and feedback
Please consult the User and Implementation Guide and Technical Validation Report before evaluating the workbook. Technical feedback, identified issues, and suggestions for improvement are welcome through GitHub Issues.

Project author: Ricardo Lopes Wiest
