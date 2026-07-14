# 🗡️ Attack on Titan HTML Project

Welcome to my repository! This project is a tribute to **Attack on Titan (Shingeki no Kyojin)**, built entirely using semantic HTML and custom CSS. 

It serves as a hands-on project to master structuring data using **HTML Tables**, styled beautifully to match the dark, gritty aesthetic of the anime.

---

## 🌐 Live Preview
Check out the live page here:
👉 **[View My Attack on Titan Page](https://huzaifaabdulrahman76-crypto.github.io/HTML/)**

---

## 📊 Inside the Project: How Tables are Structured

To display information like the different Military Regiments (Scout Regiment, Garrison, Military Police) and character stats, I used structured HTML tables. 

Here is a quick cheat sheet of the tags I used to build them:

* `<table>` - The wrapper container for the entire grid.
* `<thead>` - Defines the header section of the table.
* `<tbody>` - Houses the main data rows.
* `<tr>` - Creates a table row.
* `<th>` - Creates a bold, centered header cell (like "Regiment Name", "Insignia", "Role").
* `<td>` - Houses the actual data inside the cells (like "Scout Regiment", "Wings of Freedom").

### Quick HTML Table Example Used:
```html
<table>
  <thead>
    <tr>
      <th>Regiment</th>
      <th>Insignia</th>
      <th>Key Characters</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Scout Regiment</td>
      <td>Wings of Freedom</td>
      <td>Eren Yeager, Levi Ackerman</td>
    </tr>
    <tr>
      <td>Military Police</td>
      <td>Unicorn</td>
      <td>Annie Leonhart, Nile Dok</td>
    </tr>
  </tbody>
</table>
