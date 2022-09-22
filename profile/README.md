# Welcome to the Virtual Dynamic Labs 
Please follow below standards to contribute your code. 

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
👀 Contribution guidelines - how do team members dive in?
👩‍💻 Useful resources - where do you keep your docs? Is there anything else the team should know?
🍪 Fun facts - what is your team's favorite snack?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

1. Do: 

- Keep methods short and single purpose
- Declare variables close to where they are used, preferably where first initialized
- Make your comments terse and informative rather than opinionated and narrative
- Check parameters and return early
- Format code according to Virtual Dynamic Labs coding standards
- When modifying code, leave code better than you found it
- Eliminate all warnings

2. Avoid:

- Using adjectives in method names
- Unnecessary redundant terms
- Meaningless booleans in method arguments
- Writing complex code / objects
- Mutable static fields
- Warnings—kill them off
- Being lazy on setter and getter method generation

Branching Policy: 
1. Every project will have main, testing, and dev branches. main branch is for our production enviroment, testing branch is for our testing enviroment, and dev branch is for development. 
2. All developers need to branch out from the dev branch to their own branch to do development. 
3. After code is completed without errors and bugs, submit a peer review(PR) to github. 
4. At least one approval on each PR before it merge to dev branch. 
5. Everyday we will merge dev branch to testing branch.
6. After merging from dev to testing branch, deploy testing branch to testing instance to do some manual testing. Also, run testing script to against the code. 
7. After testing process is done, merge testing branch to main branch and deploy main branch to production enviroment. 







