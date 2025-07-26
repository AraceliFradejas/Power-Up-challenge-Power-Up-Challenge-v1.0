# Power-Up-challenge-Power-Up-Challenge-v1.0

This project is the final result of the **Microsoft Power Up Challenge**, where I designed and deployed a full parking request and inspection system using the entire Power Platform stack.
---

## ✨ About this solution

The solution simulates how a business or school can manage daily parking requests and inspections using:

- **Dataverse** for structured data (Vehicles, Parking Requests, Inspections)
- **Model-driven App** for admins to manage and review records
- **Canvas App** for inspectors to log parked vehicles in the field
- **Power Automate** to confirm parking requests via email
- **Power BI** to detect unauthorized parking and review usage trends

---

## 📂 Repository structure

```bash
Power-Up-Challenge-Parking-Manager-v1.0/
├── README.md
├── export/
│   └── af_parking_solution.zip                 # Exported managed solution (.zip)
├── powerbi/
│   └── parking_inspections_report.pbix
├── screenshots/
│   ├── canvas-app-home.png
│   ├── model-driven-view.png
│   ├── powerautomate-flow.png
│   └── powerbi-dashboard.png
├── video/
│   └── demo_parking_solution.mp4
├── docs/
│   └── Parking Challenge Instructions v2.3.pdf
```

---

## 🎥 Demo video

Watch the full walkthrough of the working solution in this video:

- 📽️ [Final Parking Challenge Demo](https://youtu.be/6PJfnTFpAUs)

---

## 🧠 Data model

The solution uses 3 custom tables in Dataverse:

- **Vehicles**: stores the car, owner, and image
- **Parking Requests**: logs requests from users for a specific day
- **Parking Inspections**: created at 5pm each day to verify who parked

Relationships:
- Each Parking Request is linked to a Vehicle
- Each Inspection links to a Vehicle (and optionally to a Request)

---

## 🚀 Key Features

- 🌐 Model-driven App for admins
- 📱 Tablet-style Canvas App with modern controls
- 📨 Automated flow to send request confirmation via email
- 📊 Power BI dashboard with cards, bar chart, matrix and filters
- 🎨 VIP customization: special logic for 4 executive Swifties
- 🔐 Smart validations to prevent late requests after inspection

---

## 🎓 What I learned

This was the most complete project in the Power Up journey. I practiced:

- Building clean relational data models in Dataverse
- Designing intuitive UIs in both canvas and model-driven apps
- Creating dynamic emails with expressions in Power Automate
- Crafting analytical dashboards in Power BI with measures and filters
- Managing app logic, user navigation and testing under pressure

---

## 👩‍💻 Author

**Araceli Fradejas Muñoz**  
Power Platform maker · AI & CX enthusiast · Storyteller through tech  
[LinkedIn](https://linkedin.com/in/aracelifradejas) | [Medium](https://medium.com/@araceli.fradejas) | [GitHub](https://github.com/AraceliFradejas)

---

## 💡 Bonus: A Swiftie touch

> “I knew this parking story would end with a getaway car.” 🚘🎶

Check the full story behind the build here:  
📖 https://medium.com/@araceli.fradejas/from-dataverse-to-getaway-car-how-i-built-a-full-parking-system-with-power-platform-and-a-36b13f9c6778

---

## 🏁 Built with 100% Power Platform love — and some Swiftie inspiration.
