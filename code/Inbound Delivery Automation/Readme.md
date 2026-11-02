
# AI-Powered Inbound Delivery – Package Overview

This package contains the folders and components required to set up the **AI-Powered Inbound Delivery** solution.

## Package Structure

### 1. Connections
Contains the following connections:

- **Outlook Connection:** Used for email-based document processing.
- **Custom MCP Connection:** Used for integration with the MCP server.

### 2. Datatables

Contains the following datatables:

- Delivery Data
- Materials
- PO
- Vendors

### 3. Functions

Contains reusable functions supporting:

- Data processing
- Data validation
- Business logic
- Reusable processing operations

### 4. Genies

Contains:

- Inbound Delivery Genie
- Associated skills for intelligent document processing
- Document validation capabilities

### 5. Recipes

Contains the recipes required for end-to-end workflow execution:

- Email-triggered document processing
- IDP extraction
- Validation orchestration
- Exception handling
- Notifications

### 6. WorkflowApp

Contains the human-in-the-loop application used for:

- Reviewing suggested material matches
- Approving material matches
- Rejecting material matches

---

## Import Order

Import all folders into the **same Workato project** in the following sequence:

1. **WorkflowApp** – Import the human review application.
2. **Connections** – Import and configure Outlook and Custom MCP connections.
3. **Datatables** – Import Delivery Data, Materials, PO, and Vendors.
4. **Functions** – Import reusable processing and validation functions.
5. **Genies** – Import the Inbound Delivery Genie and associated skills.
6. **Recipes** – Import all recipes required for document processing, validation, exception handling, and notifications.

---

## Post-Import Configuration

After importing all folders, complete the following configurations:

1. Configure the required connection credentials.
2. Verify the Outlook and Custom MCP connections.
3. Validate the Datatables and their required fields.
4. Verify Functions and Genie skills.
5. Review recipes and WorkflowApp configurations.
6. Test the complete end-to-end workflow.

---

## Setup Completion

Once all folders have been imported and the required connections, credentials, and configurations have been completed, the **AI-Powered Inbound Delivery** project will be ready for testing and execution.

---

**Project:** AI-Powered Inbound Delivery  
**Platform:** Workato  
**Integration:** Outlook, Custom MCP Server, IDP, and Workato Recipes
