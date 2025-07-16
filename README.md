# Recruiting App - Trailhead Project
Trailhead project: Build a Data Model for a Recruiting App

## 🧭 Project Overview
This project is part of Salesforce Trailhead’s hands-on module: **Build a Data Model for a Recruiting App**.  
It focuses on building a custom recruiting system where hiring teams can post jobs, review candidates, and manage job postings using custom Salesforce objects and relationships.

## 🔧 Modules & Features Implemented

### 1️⃣ Create a Custom Object for Reviews
- Created custom object: `Review`
- Set display format: e.g., `REV-{0000}`
- Enabled reports & activities

### 2️⃣ Create a Custom Object for Job Posting Sites
- Created object: `Job Posting Site`
- Fields added:
  - **Job Posting Site URL** (URL)
  - **Active** (Picklist – Active / Inactive)
  - **Technical Site** (Checkbox)
  - **Description** (Text Area)
- Added this object to the **Recruiting App**

### 3️⃣ Create a Custom Junction Object for Job Postings
- Created object: `Job Posting` (Auto Number)
- Master-Detail Relationships:
  - **Position** (MDR)
  - **Job Posting Site** (MDR)
- Used this as a junction object between `Position` and `Job Posting Site`

### 4️⃣ Customize Page Layouts
- Edited page layouts for `Job Posting`, `Review`, and `Job Posting Site`
- Included fields like:
  - **Site Name**
  - **Job Posting Site URL**
  - **Technical Site Description**

### 5️⃣ Enter Sample Data
- Created sample `Position` record:
  - **Title**: Super Sales Rep
  - Associated `Job Posting Site` with site name & URL

### 6️⃣ Create a Self-Relationship on Position Object
- Added **Lookup Relationship** to `Position` itself
- Field Label: `Related Position`
- Set up **Lookup Filters** to control related values
- Created example entry: `Awesome Sales Rep` → related to `Super Sales Rep`

### 7️⃣ Create Custom Fields on Review
- Added:
  - **Picklist Field** (for review rating/status)
  - **Custom Text Field** (for comments or reviewer name)


## 🧠 Learnings

- Master-Detail and Lookup relationships (including self-relationship)
- Junction object design in Salesforce
- Custom field types: picklist, checkbox, text, URL
- Customizing page layouts and app structure
- Lookup filters for better UX
- Working with related data through schema builder



## 📌 Trailhead Module Link
[Trailhead: Build a Data Model for a Recruiting App](https://trailhead.salesforce.com/content/learn/projects/build-a-data-model-for-a-recruiting-app)

## 📸 Screenshots
<img width="1920" height="1080" alt="Screenshot 2025-07-17 002007" src="https://github.com/user-attachments/assets/cdc2da66-088d-4f43-a87b-6c903d915572" />

### 🚧 Status
✅ **Completed** on Trailhead
