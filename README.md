# Funfacts website link 
https://ajay7760.github.io/Funfacts/
# Amazon Rainforest Fun Facts App

This is a simple single-page web application that displays random Amazon Rainforest fun facts. The background color of the page adapts based on certain keywords (e.g., “oxygen,” “dolphin,” “river,” “climate”) in the displayed fact. It’s built with HTML, CSS, JavaScript, and Bootstrap.

---

## Features

1. Random Fact Generation  
   • Each click of “Generate Fun Fact” pulls a random fact from the array embedded in [index.html](file:///Users/username/project/index.html).  

2. Keyword-Based Color Scheme  
   • The background and text colors change dynamically for certain keywords.  
   • Example triggers include “oxygen” (pale green), “dolphin” (pale pink), “river” (pale blue), and “climate” (pale yellow).

3. Responsive Design with Bootstrap  
   • Built using the Bootstrap 5.3 CDN for an attractive layout.  
   • Automatic resizing on mobile, tablet, or desktop.

---

## Getting Started

1. Clone or Download the Repository  
   • Place all files in one folder, making sure [index.html](file:///Users/username/project/index.html) has the code from the example or your own version.

2. Review/Customize the Fun Facts  
   • In [index.html](file:///Users/username/project/index.html), you’ll find the JSON object named “amazonFacts.”  
   • Modify the array to include your own facts or additional keywords.

3. Local Preview  
   • Open [index.html](file:///Users/username/project/index.html) in your web browser.  
   • Click the “Generate Fun Fact” button to see a new random fact.

---

## Deployment on GitHub Pages

1. Commit and Push  
   • Make sure [index.html](file:///Users/username/project/index.html) is present in the main branch of your repository.  

2. Enable GitHub Pages  
   1. Go to your repository’s "Settings" → "Pages."  
   2. Under "Source," select the main branch.  
   3. (Optional) If your file is in the root folder, select “/(root)” under the folder dropdown.  
   4. Click "Save."

3. Access Your Live Site  
   • GitHub Pages will generate a URL like:
     https://<YourGitHubUsername>.github.io/<YourRepoName>  
   • After a few moments, your site will be live.

---

## How It Works

1. Click Event  
   • Clicking the “Generate Fun Fact” button calls showRandomFact(), which picks a random fact from the array.

2. Color Updating  
   • The selected fact is passed to updateColorScheme(), which checks for keywords.  
   • The page’s background and the fact container style adjust according to which keyword is found.

3. Default Style  
   • If no keyword is matched, the design defaults to a white container on a gray background.

---

## Contributing

• Fork the project, make changes, and submit a pull request.  
• Feel free to add more keywords or new color themes.

---

## License

This project is open-source and available under the [MIT License](https://opensource.org/licenses/MIT).  

---

### Questions or Feedback?

If you have questions, feel free to open an issue or reach out via GitHub. Enjoy customizing your color scheme and sharing your site on GitHub Pages!
