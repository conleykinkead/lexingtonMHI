# Final assignment: Map critique exercise, final map submission, and updated portfolio

<!-- TOC -->

- [Final assignment: Map critique exercise, final map submission, and updated portfolio](#final-assignment-map-critique-exercise-final-map-submission-and-updated-portfolio)
    - [Part I. Map Critique Exercise (2.5 pts)](#part-i-map-critique-exercise-25-pts)
    - [Part II. Polishing your final map and updating your online mapping portfolio (9 pts)](#part-ii-polishing-your-final-map-and-updating-your-online-mapping-portfolio-9-pts)
    - [Part III: Add metadata about project (1 pt)](#part-iii-add-metadata-about-project-1-pt)
    - [Bonus: share to the NMP Slack forum (+2 pts)](#bonus-share-to-the-nmp-slack-forum-2-pts)

<!-- /TOC -->

We're now quickly moving forward through the final weeks of the course and working primarily on the final map projects.

First create a new GitHub repository for your map project **on your GitHub account** and work within that repo. Give the repo a short, descriptive name related to your map (e.g., https://github.com/annaleebard/language-and-autism). You should also include a README.md file at the root level of the repository.

Make the repository public (so people can see/share your awesome code), and add the instructor as a collaborator for pull requests, etc. (Verify your instructor's GitHub user name.) Please submit a link to this repository for the final assignment for the course in Canvas Assignments.

Also, note that you can go into the Settings of your repository in GitHub and select the main branch under GitHub Pages. This will allow your map to be served from that branch for viewing and sharing. You'll then go to [https://username.github.io/repo-name](https://username.github.io/repo-name).

**Important:** GitHub will only serve files that use the secure protocol https, so make sure your CDN for additional libraries or font resources and map tiles are using this protocol.

We're aiming to have functional prototypes working by the end of this week. This means:

* ALL data collected/processed/formatted
* Data are being loaded into the script (either from a local file or a remote database) and parsed or bound to geometries
* Data are being symbolized in the appropriate thematic way (choropleth, proportional symbols, etc)
* Interaction operators (e.g., overlays, retrieve) are being developed, tested, working (or kinda broken).
* Basic page layout and UI elements are prototyped (e.g., headers, menus, sidebars, info windows).

## Part I. Map Critique Exercise (2.5 pts)

Post the URL to your GitHub Pages final project prototype to the Discuss Forum. With the post, include a 5-minute screen recording of your map for sharing with your instructor and colleagues. There are many free/open source screen-casting video software options, but consider [ShareX](https://getsharex.com/) or [Jing](https://www.techsmith.com/jing-tool.html).

The presentation should cover the following:

* Minute 1: Introduce your topic and your motivation for the project.
* Minute 2: Briefly describe your target user, their goals and objectives for using the map.
* Minutes 3 - 4: Walk us through a live use case scenario using the map. Explain the various interface components and how the user will use them.
* Minute 5: Conclude with any features, functionality, or design aspects you'd like to attend to or improve upon for the final week (a "wish list").

Please take the time to examine your peers' maps and presentations and offer useful map critique and suggestions for improvement. This can take a variety of forms, but consider these guidelines:

* **Kick the positive:** "Critique" often has a negative connotation, but it doesn't mean we're out to celebrate faults or problems with a map. Begin your feedback by focusing on what you like about the map. Describe what works for you, and *how* it does so.

    For example, the map may be effective at showing seasonal drought patterns because the sequential color scheme is appropriate and there is a UI slider element allowing one to sequence through data values using a consistent set of class breaks. The map may be enjoyable to view because there is an overall good visual balance, a clean modern typeface, and effective use of complimentary colors.

* **Identify aspects of the design that inhibit the use of the map:** Pretend that you are the intended user of the map. Consider again the work you want this map to do for you, and identify the design elements that are detracting from this goal. For example, the map may take a long time to initially load, making me think there is an error or problem with the map. I may be confused where my "call to action" is on the map, and how I'm am supposed to use it. I may be confused as to the selected state of a filter button and am unsure if the data is currently being filtered or not. What units do these numbers on a choropleth map represent?

* **Offer suggestions for improving the map:** Consider possible solutions pointing back toward the challenges you've identified (possibly even a couple different solutions for a single issue). For example, I can suggest that putting a spinning loader on the map until the data is downloaded and ready will tell the user to wait. I may suggest that a button or drop-down menu crucial to the use of the map be made larger and more prominent within a sidebar. I may suggest the "selected" state of a UI element be highlighted when activated.

Additionally, you may consider some of the following:

* is the purpose and topic of the map clear? do you know what it's trying to tell you or what the story is?
* does the map have a good title that includes what (car sales), where (in the US, by state), and when (2015)?
* does the map need a different or better legend for interpreting the mapped data?
* does the choice of thematic representation appropriately fit the mapped phenomena?
* are the user interactions effective for 1. engaging with the map and 2. giving the user feedback and affordances that they are working?
* are important map elements labeled (perhaps through interactive popups)?
* is there a clear figure-ground hierarchy (i.e., can you distinguish the thematic map elements from the basemap)?
* are the data classified or aggregated appropriately?
* does the page/map feel too cramped needs more whitespace? is there an "economy of design"?
* is the page/map and elements too busy or noisy? are you confused about where your "point of entry" is for the map?
* is the choice of typography appropriate for the map and subject matter?
* are the data sources clear (and even linkable through the map)?
* is it clear who the author of the map is? is there a link back to the author's portfolio or GitHub account?

After viewing your peers' maps, select those that you think you can help the most and:

1. Give comments in the discussion forum created in the previous module. Keep your critique and feedback brief. (And, it never hurts to end with a positive statement as well e.g., "this map allows me to see XYZ that I could not have otherwise.")

## Part II. Polishing your final map and updating your online mapping portfolio (9 pts)

Given the feedback from your instructor and your peers, spend the final hours of the course polishing the design and improving the usability of your final map. When you have finished working on your final project, make sure you:

1. Update your final project's README.md with content from your project proposal that explains your methodology, data sources, technology stack, and any conclusions and insights you would like to share. In the README.md, add a URL to your GitHub Pages site (the `.io` domain). Similarly, in your GitHub Pages site, you can add a link to the README.md on the GitHub code side (the `.com` domain).

2. Update your web portfolio created in our first assignment with your final project. To include additional maps created in MAP673, create new and separate GitHub repositories on your own account for hosting and serving these maps via GitHub Pages. This is your portfolio, so feel free to add anything you like.

3. Place a link to your portfolio on your final project page. The link can exist on the README.md file and/or the GitHub Pages file.

## Part III: Add metadata about project (1 pt)

Create a `publish.json` that gives important metadata about your project. This file supports sharing your work with the world and controlling what information you present in a marker popup. The marker will be [placed on this map](https://newmapsplus.github.io/projects/). 

The template file [can be found here](templates/publish.json) and it must be placed in the root directory of your final project repository. Before you alter this file, look at the following properties that you need to change:

  ```js
  {
    // Required properties
    "title": "Title of Project", // Give your project a good title
    "info": "Add info about project", // A short blurb about your project
    "coordinates": [38, -84.5], // IMPORTANT: the lat, long centerpoint of your project

    // Optional properties
    // If you don't want to use these, use the value null without quotes.
    "author": "Do you want to add your name?", // What handle do you want to use?
    "link": "https://nnewmapsplus.github.io/projects/" // What's the link to the project to the GitHub Pages site? The URL with the .io domain.
  }
  ```

  Note: comments are not supported in the JSON format. Let's consider an example of a properly formatted `publish.json` file: 

  ```json
  {
    "title": "A map of NMP student projects",
    "info": "Students publish many public projects each semester. Let's show them!", 
    "coordinates": [34.5, -94.5],
    "author": "Folks at NMP",
    "link": "http://newmapsplus.github.io/projects/"
  }
  ```

When you have finished the `publish.json` for the final project:

1. Submit a URL to your final project's `publish.json` on the Github Pages site in Canvas, e.g, https://\<your-username\>.github.io/\<final-project-name\>/publish.json 

## Bonus: share to the NMP Slack forum (+2 pts)

Post the URL to your final project on our [Slack Forum](https://join.slack.com/t/newmapsplus/signup) channel called `#final-projects`. The private forum is visited by alumni and those currently enrolled in New Maps Plus. This new channel is an experiment to share final projects from all New Maps Plus courses.


