# 🧩 Custom Employee Center Portal Widgets

Custom ServiceNow widgets for the Employee Center Portal that provide employees with an intuitive interface to view and manage their assigned devices and software licenses.

---

## 📌 Overview

This project contains custom-developed widgets designed to enhance the user experience in ServiceNow’s Employee Center by:

- Displaying assigned hardware and software assets
- Allowing asset verification through dynamic forms
- Providing future expandability for detailed lifecycle management

---

## 🎯 Widgets

### 1. **My Devices**

A compact widget ideal for the portal homepage, offering quick access to device details or a list of all assigned hardware.

<img src="images/Employee_Center_My_Devices_Mini_Widget.png" alt="My Devices Mini Widget" width="100%"/>

---

### 2. **My Devices and Software**

A full-page widget showing all assigned devices and software licenses. Each card displays dynamic actions based on status and user role.

<img src="images/Employee_Center_My_Devices_and_Software_1.png" alt="My Devices and Software" width="100%"/>
<img src="images/Employee_Center_My_Devices_and_Software_2.png" alt="My Devices and Software Actions" width="100%"/>

---

### 3. **Verify Asset Page**

A form page that allows employees to verify possession of their assigned devices. The verification prompt appears only if the asset has not been verified in the last 12 months.

<img src="images/Form_Verify_Asset.png" alt="Verify Asset Form" width="100%"/>

---

## 🛠️ Development Process

Here’s a high-level summary of the build process:

1. Clone and review out-of-box Employee Center widgets
2. Create Script Includes/APIs to aggregate device and software data
3. Customize widget controllers and templates for improved UX
4. Update the portal's main header and navigation structure
5. Add new portal pages for:
   - **My Devices and Software**
   - **Verify Asset**

---

## 🚀 Planned Enhancements

Future enhancements include:

- A detailed card view when an employee clicks on a device or software item
- Display of lifecycle dates, warranty status, and guide links
- Additional employee actions (e.g., report issue, request upgrade)

---

## ⚙️ Installation / Setup

> *Coming soon.*  
> A full setup guide will be added here including:
> - Dependencies
> - Portal page configuration
> - How to import the widgets and script includes

---

## 🤝 Contributing

Pull requests are welcome for new features or improvements! If you have suggestions for new functionality or UX tweaks, feel free to open an issue.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

