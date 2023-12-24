# Domain Analysis

## Overview

The Company (Mr. Green Landscaping) is a landscape service company that serves hundreds of customers in several municipalities, performing a variety of services, mostly basics like lawn care, but there are also dedicated crews who perform more involved services like tree removal and landscape design/installation. The Company desires to  revamp their paper-based quotation and workorder process to a web-based process with workflow to improve closing of sales.

## Business domain and subdomains

The business domain is landscaping, which involves performing manual work with crews of employees and equipment. 

### Core subdomain

The main competitive advantage the company intends to gain is the better management and faster follow up of customer requests for quotes, as well as followup for annual services. The company intends to build a recurring revenue model around satisfied customers and repeatable services.

An additional future goal is to develop scheduling practices that make the best use of company resources. An example of this would be grouping services on dates in a geographical area to reduce travel. It is not clear whether this this is a core subdomain or an external software service which can be subcontracted.

### Generic subdomains 

The following are off-the-shelf solutions that the company should rent from others as SaaS.

- Accounting
- Email
- SMS/Text messaging


### Supporting subdomains 

The following are solutions the company must do to accomplish the business, but there are no obvious SaaS offerings.

- Integration with Accounting Saas
- Integration with SMS/Text Messaging

## Design Decisions

Based on the above, here is a set of strategic decisions that the project is based upon.

1. Develop the core subdomain functionality as a web application that is centered on Customers and the work that the company performs for them.

2. Review existing Accounting processes and software to ensure suitability. The specific concerns are that the software offers the ability to synchronize quotations and work orders so that the sales and accounting work is up to date.

3. Consider how messaging to customer will happen, and what information is needed. This is part of the project and requires discovery.

4. Consider how workflow will happen. This is part of the project and requires discovery.