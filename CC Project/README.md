# Mood Deterioration Tracker

A simple and interactive **Mood Tracking Web Application** built using **HTML, CSS, JavaScript, and Chart.js**.  
This project helps users monitor their daily mood scores, visualize emotional trends over time, and identify mood deterioration patterns. :contentReference[oaicite:0]{index=0}

---

## Features

- Track daily mood on a scale of **1 to 10**
- Visual mood categories:
  - 8–10 → Very Happy / Happy
  - 6–7 → Neutral
  - 4–5 → Sad
  - 1–3 → Very Sad
- Dynamic **line chart visualization** using Chart.js
- Automatic color-coded graph points based on mood
- Displays **Current Mood Phase**
- Fun emoji popup animation on each mood entry
- **Undo** last action
- **Clear All** saved records
- Data stored using **LocalStorage** (data remains after refresh)

---

## Technologies Used

- **HTML5**
- **CSS3**
- **JavaScript (ES6)**
- **Chart.js**

# DSA Concepts & Algorithms Used in Mood Deterioration Tracker

This project uses basic Data Structures and Algorithms to efficiently manage and process mood data.

- **Array** is used to store mood entries (date and mood score). It allows fast insertion and easy traversal of data.

- **Stack** is used to implement the undo feature. It follows the Last In First Out (LIFO) principle to restore the previous state.

- **Sorting Algorithm** is applied to arrange mood entries in chronological order based on date before displaying them in the graph.

- **Traversal (Iteration)** is used to access each element of the array while updating the chart.

- **Indexing** is used to directly access the most recent mood entry in constant time.

- **Conditional Logic** is used to classify mood values into categories such as Happy, Neutral, Sad, and Very Sad.

Overall, the project demonstrates efficient use of basic DSA concepts like arrays, stack operations, sorting, and traversal to handle dynamic data updates.
