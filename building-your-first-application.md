# Creating Your First Application

This guide explains how to create your first application in AppOps Builder.

Before creating an application, you must first create a **Service**, because every application in AppOps Builder belongs to a service.

---

# Step 1 — Create a Service

Open the **Services** section from the left navigation panel.

![Services dashboard](../assets/services-dashboard.svg)

Services act as the primary organizational layer inside AppOps Builder. A service groups related applications, workflows, APIs, and configurations together.

Examples:

* CRM Service
* HR Service
* Blogging Service
* Inventory Service

---

## Create a New Service

Click **Create Service**.

![Create Service screen](../assets/create-service.svg)

The Create Service screen contains the following fields:

### Service Name

Enter the name of your service.

Example:

```text
Blogging Service
```

Rules:

* Minimum 2 characters
* Maximum 50 characters

---

### Category

Enter or search for a category related to the service.

Example categories:

* Blogging
* Ecommerce
* CRM
* HR Management
* Analytics

Categories help organize services inside the workspace.

---

## Create the Service

After entering the required information, click:

```text
Create Service
```

The service will now be added to the Services dashboard.

---

# Step 2 — Create an Application

After creating a service, open the **Apps** section from the sidebar.

Applications are the actual user-facing products, dashboards, portals, or systems built inside a service.

Examples:

* Admin Dashboard
* Blog Manager
* Analytics Portal
* Employee Portal

---

## Create a New App

Click:

```text
Create App
```

![Create App screen](../assets/create-app.svg)

The application creation screen will open.

---

# Step 3 — Configure the Application

## Application Name

Enter the application name.

Example:

```text
Blog Manager
```

Rules:

* Minimum 2 characters
* Maximum 50 characters

---

## Select a Theme

Choose a default theme for the application.

Themes control:

* UI design
* Colors
* Typography
* Layout styling
* Component appearance

Example themes:

* Default Builder Theme
* Blogger Theme

Themes help maintain a consistent design system across the application.

---

# Step 4 — Choose a Service

Click:

```text
Next: Choose Service
```

Select the service under which the application should be created.

Example:

```text
Blogging Service
```

This links the application to the selected service.

---

# Step 5 — Open the App Builder

After the app is created, click:

```text
View App
```

This opens the visual App Builder.

![AppOps Builder editor](../assets/builder-editor.svg)

The builder is the main development environment where pages, components, workflows, and layouts are created visually.

---

# Step 6 — Create Your First Page

Inside the builder:

1. Open the **Pages** panel
2. Click **+ New Page**
3. Enter the page name
4. Click **Confirm**

Example page names:

* home
* dashboard
* login
* blog-list

The page is now created and available inside the editor.

---

# Step 7 — Add Components

From the left component panel, drag elements into the page canvas.

Available components include:

* Text
* Button
* Input
* Form
* Image
* Grid
* Container
* Popup
* Date Picker
* Repeating List

These components allow applications to be built visually without manually writing frontend code.

---

# Step 8 — Configure Styles

Select any component to open the properties panel.

You can configure:

* Width & Height
* Margin & Padding
* Background
* Border
* Position
* Themes
* Variants

This helps customize the appearance and layout of the application.

---

# Step 9 — Add Logic and Events

Inside the Event section, configure:

* Button Actions
* Navigation
* API Calls
* Form Submission
* Dynamic Workflows
* Client Flows

This enables interactive and dynamic application behavior.

---

# Step 10 — Preview and Save

After building the application:

* Preview the UI
* Test interactions
* Validate layouts
* Save configurations

Your first application is now ready for further development and deployment.

---

# Summary

In this guide, you learned how to:

* Create a Service
* Create an Application
* Select Themes
* Open the Visual Builder
* Create Pages
* Add Components
* Configure Styles
* Build Interactive Workflows

This forms the foundation of application development in AppOps Builder.

---

## Navigation

**Previous Page:** [Building for Enterprise Applications](building-for-enterprise-applications.md)

**Next Page:** [Creating and Managing Projects](creating-and-managing-projects.md)

**Related Docs:** [What is AppOps Builder?](whats-appops-builder.md), [The AppOps Builder Editor](appops-builder-editor.md)
