# 🎸 Groupie Tracker

**Groupie Tracker** is a web application that fetches, manipulates, and visualizes data from a music-related API.  
The platform allows users to explore artists, bands, their members, concert locations, and dates through an interactive and user-friendly interface.  
It also implements client-server events, search functionality, and filters to enhance the user experience.

---

## 📜 Description

Groupie Tracker integrates data from an API consisting of four parts:

1. **Artists:** Contains information about bands and artists, including names, images, year of formation, first album date, and members.  
2. **Locations:** Stores past and upcoming concert locations.  
3. **Dates:** Stores past and upcoming concert dates.  
4. **Relation:** Connects artists, dates, and locations.

The website allows users to:

- View artist and band information through **cards, tables, lists, pages, or other visualizations**.  
- Interact with events that trigger client-server communication (request-response).  
- Search for artists, members, or other attributes using a **smart search bar with suggestions**.  
- Filter results by creation date, first album date, number of members, or concert locations.

---

## 👤 Authors

- **Abderrahmane Fethi** – Junior Full-Stack Developer  
  🌍 [LinkedIn](https://www.linkedin.com/in/abderrahmane-fethi)

---

## ⚙️ Usage

1. **Clone the repository**:

```bash
git clone https://github.com/A-fethi/groupie-tracker-visualization.git
cd groupie-tracker
```

2. **Run the Go server:**
```bash
go run main.go
```

3. **Open the browser:**
Navigate to http://localhost:8080

4. **Interact with the site:**
- Explore artists and bands via cards or tables.

- Use the search bar to find members, bands, or specific attributes.
 
- Apply filters to refine displayed results.


## 🧰 Technologies Used
- **Backend**: Go (Golang) – HTTP server, JSON handling, client-server events

- **Frontend**: HTML, CSS

- **Data**: JSON API (artists, locations, dates, relations)

- **Packages**: Standard Go library only (net/http, encoding/json, html/template, etc.)

## 🎯 Learning Outcomes

- Fetching, manipulating, and storing JSON data in Go

- Designing dynamic and responsive web interfaces with HTML/CSS

- Implementing client-server communication and event-driven actions

- Creating search functionality with suggestions and type indicators

- Building filter systems with range and checkbox controls

- Visualizing complex data according to usability principles

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).