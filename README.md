# Employee Onboarding – ERPNext Custom App

## 📋 Overview

This custom ERPNext app addresses a common pain point in mid-sized organizations: the lack of structured, automated, and role-based workflows for onboarding new employees. The app streamlines the onboarding process by dynamically assigning tasks, tracking asset needs, and enabling workflow-driven collaboration between IT, Admin, and HR departments.

---

## 🎯 Objective

To provide a centralized, automated, and dynamic onboarding workflow that:
- Enhances inter-departmental visibility.
- Automates asset allocation and procurement steps.
- Adapts onboarding checklists based on job roles.

---

## 🚀 Installation

```bash
# Go to your bench folder
cd frappe-bench

# Get the app from GitHub
bench get-app employee_onboarding https://github.com/ahsan-ali1234/employee_onboarding.git

# Install app on your site
bench --site [your-site-name] install-app employee_onboarding

# Migrate to apply changes
bench --site [your-site-name] migrate
