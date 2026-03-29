# GreenCity Events Page — Test Cases

---

## 🧪 TC-001: Open Events page

**Priority:** High  
**Type:** Positive  

### 🔹 Preconditions:
- Internet connection is available
- Browser is installed

### 🔹 Test Steps:

| Step | Action                | Data                                              | Expected Result                          |
|------|----------------------|--------------------------------------------------|------------------------------------------|
| 1    | Open browser         | Chrome / Firefox                                 | Browser opens successfully               |
| 2    | Go to Events page    | https://www.greencity.cx.ua/#/greenCity/events   | Page loads without errors                |
| 3    | Check page content   | -                                                | Events list is visible                   |

---

## 🧪 TC-002: Check event cards

**Priority:** High  
**Type:** Positive  

### 🔹 Preconditions:
- Events page is opened

### 🔹 Test Steps:

| Step | Action              | Data | Expected Result                          |
|------|--------------------|------|------------------------------------------|
| 1    | Find event cards   | -    | Event cards are displayed                |
| 2    | Check card title   | -    | Title is visible                         |
| 3    | Check image        | -    | Image is displayed                       |
| 4    | Check description  | -    | Description is shown                     |

---

## 🧪 TC-003: Open event details

**Priority:** Medium  
**Type:** Positive  

### 🔹 Preconditions:
- Events page is opened
- At least one event exists

### 🔹 Test Steps:

| Step | Action                | Data | Expected Result                          |
|------|----------------------|------|------------------------------------------|
| 1    | Click on event card  | -    | Event details page opens                 |
| 2    | Check event info     | -    | Event information is displayed           |
| 3    | Check page URL       | -    | URL is changed                           |

---

## 🧪 TC-004: No events available (negative test)

**Priority:** Medium  
**Type:** Negative  

### 🔹 Preconditions:
- No events in system (test case scenario)

### 🔹 Test Steps:

| Step | Action            | Data | Expected Result                          |
|------|------------------|------|------------------------------------------|
| 1    | Open Events page | URL  | Page loads successfully                  |
| 2    | Check content    | -    | Message "No events available" is shown   |
