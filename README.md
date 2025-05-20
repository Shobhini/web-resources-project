
<div id="top">
<h1 align="center">Web Resource Hub 👨‍💻</h1>


## 🚀 About 
+ [**Web Resource Hub**](https://web-resources-project-dev.vercel.app/) is an open-source project developed for the DevJam Hackathon organized by Social Summer of Code. 
+ It serves as a comprehensive collection of **frontend web resources, including HTML, CSS, JavaScript, and React.** 
+ The project aims to provide developers with a **centralized platform** to access a wide range of frontend tools and resources, making their development process more efficient and productive.






## 📷 Screenshot 

![image](https://github.com/user-attachments/assets/fbbcf99b-b74e-4fef-9a36-ae5d792f18b0)






## 🛠️ Tech Stack
[![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://react.dev/)     [![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://v2.tailwindcss.com/docs)

## ✅ Getting Started
1. Fork the project, Click on create new fork.

2. To clone the repository to your local machine, follow these steps:

1. Click on the "Code" button.

2. Copy the HTTPS Link.

4. Open the terminal or command prompt on your computer.

5. Navigate to the directory where you want to clone the repository.


6. Type the command 
```
git clone https://github.com/<your_github_username>/web-resources-project.git
``` 
(This will download the repository to your local machine).

7. Navigate to the project directory.
```
cd web-resources-project
```

8. Add a reference(remote) to the original repository.
```
git remote add upstream https://github.com/<your_github_username>/web-resources-project.git
```

9. Create a new branch(prefer a branch name that relates to your assigned issue).
```
git remote -v
```

10. Always take a pull from the upstream repository to your main branch to keep it updated as per the main project repository.
```
git checkout -b <YOUR_BRANCH_NAME>
```
11. How to Run the Project is given in the below part 👇🏼.

12. Perform your desired changes to the code base.

13. Check your changes.
```
git status
```
```
git diff
```

14. Stage your changes.
```
git add . <\files_that_you_made_changes>
```

15. Commit your changes.
```
git commit -m "relevant message"
```

16. Push the committed changes in your feature branch to your remote repository.
```
git push -u origin <YOUR_BRANCH_NAME>
```

17. To create a Pull Request, click on ```compare and pull requests```.

18. Add an appropriate title and description to your PR explaining your changes.

19. Click on ```Create pull request```.

Congratulations🎉, you have made a PR to the Web Resources Project. Wait for your submission to be accepted and your PR to be merged by a maintainer.

If you have any doubts please let us know in the comments.

## ⬇️ Prerequisites
  - **Node JS**
  -  **pnpm**

## 👉 Running the Project Locally
1. Open a terminal or command prompt on your computer.
2. Navigate to the directory where the repository was cloned.
3. Run the following command: `pnpm install` (This command installs the project dependencies).
4. After the installation is complete, run the following command: `pnpm run dev` (This command launches the project in your local browser or terminal).

## 💪 Adding new resource 
1. Navigate to the `src/database`.
2. There is a json file for each section.
3. Create a new object for your resource in the appropriate json file.
4. Add the details of your resource: Here's an example
```
{
    "tag" : "css",
    "title": "CodeWell",
    "description": "Improve your HTML and CSS skills by practicing on real design templates.With Codewell, you can browse high quality Figma templates that you can use to sharpen your HTML and CSS skills.",
    "link": "https://www.codewell.cc/",
    "img": "https://user-images.githubusercontent.com/100681165/238244473-00725538-ef4d-4ece-8fd7-11e6b999b895.png"
  },

```
## 🖼️ Adding images
The size of the image should be less than **300 Kb**
1. Navigate to the `public/Card Images`
3. There you will find folders of all the sections, navigate to the appropriate folder.
4. Each folder has a **.md file**
5. **Drag and drop your image** in the .md file in the appropriate position.

Note: The size of the image should be less than 300 KB.

<!-- ## 🎥 Watch this Video  -->
<!-- [![Youtube Video](https://i.ytimg.com/vi/eRVFZDIWPj8/hqdefault.jpg?sqp=-oaymwE2CNACELwBSFXyq4qpAygIARUAAIhCGAFwAcABBvABAfgB_gmAAtAFigIMCAAQARhlIFUoVTAP&rs=AOn4CLCvHosmljs19P9PRHlDr7ule1T8AA)](https://www.youtube.com/watch?v=eRVFZDIWPj8) -->

## 🤝 Contributing
We welcome contributions from the community! If you're interested in contributing to this project, please read our [Contributing Guidelines](./CONTRIBUTING.md)
 for more information on how to get started.
 


🌟 **If you find this project helpful or interesting, please consider giving it a star!** 🌟

Starring the repository helps to raise awareness and attract more users. It shows your appreciation for the project and provides motivation for further development and improvements. It's a simple way to show support!

To star this repository, simply click on the **Star** button at the top-right corner of the page. Thank you for your support! 😊






