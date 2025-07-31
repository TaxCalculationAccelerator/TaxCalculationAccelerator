# Tax Calculation Accelerator - Version 1.0.0

Overview

# Background 
Revenue Cloud hasn’t provided OOTB function to calculate tax without integrating with a 3rd party tax engine.

# Introduction
Tax Calculator is a tool that automatically calculates tax based on the configured shipping or billing address on quotes, orders, or invoices without the need for any third-party integration. 

This solution eliminates dependency on 3rd party tax engine and it uses your own configurable tax rates to apply tax based on geographic criteria.

It suits the country with simple tax scheme. For example: goods and service tax in Australia 10%, New Zealand 15%, Singapore 8% etc

This solution aims to allow the Revenue Cloud customers and partners to have a configurable tax solution for simple tax scheme, without the hassle of 3rd party tax engines, and the costs. Yes, this solution will be free to all Revenue Cloud customers.

Note:

The MVP doesn’t support multiple taxes applied to the same product. (i.e. GST+ stamp duty, CGST+ SGST/UTGST)

# Key Benefits
💡 No External Integration Required – Fewer points of failure, and no third-party costs or maintenance.

🔒 Greater Control & Configuration - Configure and manage tax rates within your own system. Allows for quick updates if tax rates change with future date, without relying on external systems.

📍 Address-Based Logic – Calculate tax dynamically using configured shipping or billing address fields across standard Salesforce objects like Quotes, Orders, and Invoices.

⚙️ Flexible Matching – Match address with tax rate using country/country code, state/state code,Tax Code to support difference combinations of these fields

🚀 Seamless Workflow Integration – Embed directly into your existing quote-to-cash process without disrupting user experience in Revenue Cloud.
