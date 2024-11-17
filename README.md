# Kanban Board Application

This project is an **interactive Kanban board** built with **ReactJS**. It retrieves task data from an external API and enables users to organize and sort tasks by **Status**, **User**, and **Priority**. Additionally, tasks can be sorted by **Priority** and **Title**. The application closely follows the design and functional requirements provided, ensuring a polished and user-friendly experience.


## Key Features

- **Custom Grouping**: Organize tasks dynamically by **Status**, **User**, or **Priority**.  
- **Sorting Options**: Sort tasks by **Priority** (descending) or **Title** (ascending).  
- **Responsive UI**: Optimized for a seamless experience on devices of all sizes.  
- **Lightweight Styling**: Entirely styled with **pure CSS**, avoiding frameworks like Bootstrap or Tailwind for better performance.  
- **State Retention**: User preferences for grouping and sorting persist even after page refreshes.  

---

## API Integration

The application interacts with the following API to fetch task data:  

**API Endpoint**:  
`https://api.quicksell.co/v1/internal/frontend-assignment`  

The API provides detailed information about tasks, including their **Status**, **Priority**, and the **Assigned User**.

---

## How to Run Locally

Follow these steps to set up and run the project on your local machine:

1. Clone the repository:  
   ```bash
   git clone https://github.com/ayush22667/quicksellFrontEnd.git
    ```

2. Navigate to the project directory:
    ```bash
    cd quicksellFrontEnd
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Start the development server:
    ```bash
    npm start
    ```


