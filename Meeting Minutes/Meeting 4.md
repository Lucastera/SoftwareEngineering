# Week 4
# This Week's Summary
1. **Code Review and Compliance:**
   - Review uploaded files to determine if they meet code review standards.
   - Provide a report outlining compliance and detailed suggestions for improvement.
  
2. **Automated Code Modification (Code Beautification):**
   - Similar to Task 1, but directly provide modified code and comparisons with the original.
   - When users submit changes, they should be reviewed by an LLM (e.g., GPT-4).
   - Generate a report on whether changes meet the development team's requirements and suggest improvements.

   **Tasks:**
   - **Task 1:** Generate a comprehensive report considering the entire file, not just changed lines. Potentially utilize ChatGPT or an open-source Llama model hosted on GCP to avoid VPN issues. Start with syntax checks (e.g., line breaks).
   - **Task 2:** Identify potential bugs (e.g., accessing non-existent variables).
   - **Task 3:** Integrate this functionality with VSCode, starting with a CLI program.

3. **Code Explanation and Annotation:**
   - Analyze provided code and explain the function of each line.
   - Useful resources:
     - [Code Using GPT](https://github.com/llmadd/code_using_GPT) - Website for code explanation.
     - [Use OpenAI API to Add Comments to Your Code](https://github.com/RaycarlLei/Use-OpenAI-API-to-add-comments-to-your-code) - Automated commenting based on OpenAI API.
     - [Academic Code Annotator](https://github.com/liuzijian-cs/AcademicCodeAnnotator?tab=readme-ov-file) - Automatically annotate code based on academic papers.
     - [JS Code to SVG Flowchart](https://github.com/Bogdan-Lyashenko/js-code-to-svg-flowchart) - Generate flowcharts from code.
     - [Devoxx Genie](https://github.com/devoxx/DevoxxGenieIDEAPlugin?tab=readme-ov-file) - Plugin for enhanced code review.
     - [Gulp Hijacking Gaze](https://github.com/yiwei1223/gulp-hijacking-gaze) - Automatically inject comments into HTML files.
     - [Easy Javadoc](https://github.com/starcwang/easy_javadoc) - Auto-generate Javadoc comments for Java code.

4. **Code Completion:**
   - Automatic suggestions based on partial code entries to improve coding efficiency and reduce syntax errors.
   - Requirements:
     1. **Automation:** Suggestions should trigger automatically as the developer types.
     2. **Accuracy:** Suggestions must be contextually relevant based on the current file, class, and method.

   **Frontend Requirements:**
   - Code editor for input and display.
   - Input box for code or descriptive text.
   - Component to display suggestions as a list or dropdown.
   
   **Backend Requirements:**
   - Handle requests from the frontend and execute core business logic.
   - Call external services (e.g., ChatGPT API) for data.

5. **Code Translation:**
   - **Objective:** Translate given code into another programming language (C++, Python, Java).
   - **Scope:**
     - Understand the functionality of the original code (Code Explanation and Annotation).
     - Use tools like ChatGPT for translation while maintaining existing functionality and properties (Code Review and Modification).
   - **Functional Requirements:**
     - Maintain syntax and semantics, ensuring equivalent behavior.
     - Preserve language features and functionality.
   - **Non-Functional Requirements:**
     - Ensure readability and maintainability with clear naming and comments.
     - Maintain performance comparable to the original code.
     - Optimize key path operations for efficiency.
     - Achieve greater than 90% test coverage using tools like JaCoCo.
   - **Priority Levels:**
     - High: Core module translation, functionality retention.
     - Medium: Readability and maintainability.
     - Low: Performance, scalability, and test coverage.

   **Examples of C++ Translation Requirements:**
   - Convert C++ data structures (e.g., `std::vector`, `std::map`) to Python equivalents.
   - Translate C++ functions and classes to Python.
   - Handle C++ pointers and references appropriately.

   **Referenced Libraries:**
   - Babel, Transcoder, Rewriter, Code Transformator.


# Next Week's Tasks

1. **Confirm Feasibility:**
   - Assess the feasibility of proposed tasks.
  
2. **Workload Evaluation:**
   - Confirm the workload for each task.

3. **Research Open Source Projects:**
   - Identify corresponding open-source software relevant to tasks.
