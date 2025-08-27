# Customizing the User Interface by Managing List Views, Home Page Layout, and Apps

**Duration:** 30 minutes
**Mark as completed**
**Next**

## Objective

To gain hands-on experience with customizing the Salesforce user interface to enhance productivity and tailor it to business needs.

## Lab Instructions

### 1. Create a Custom List View for Opportunities

Go to the Opportunities tab.

Create a new list view:

* Name: Deals Closing This Quarter
* Filter Criteria:

  * Stage ≠ Closed Lost
  * Close Date = Current Fiscal Quarter
* Add Columns: Opportunity Name, Stage, Amount, Close Date

Save and pin the view.

### 2. Clone and Customize the Home Page

Go to Setup → Lightning App Builder.

Clone the Home Page, name it **Sales Custom Home**.

Add these components:

* Recent Items: Display recently accessed Opportunities
* Today’s Tasks: Show upcoming tasks
* Rich Text Component: Write a message like:
  *Focus on high-value deals closing this quarter!*

Save and activate it for the Sales App and all users.

### 3. Customize Navigation in the Sales App

Go to Setup → App Manager.

Edit the Sales App:

* Add new tabs: Tasks, Opportunities, Files
* Arrange them so Opportunities is listed first

Save changes and verify the tab order from the Lightning UI.

## Expected Outcome / Deliverables

* A filtered Opportunity List View reflecting current quarter deals
* A cloned and customized Home Page with functional components
* A modified Sales App Navigation reflecting practical usage needs

---
