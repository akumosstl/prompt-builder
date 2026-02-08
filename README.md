# 🚀 PromptBuilder

PromptBuilder is an innovative tool to make it easy to create and organize prompts for Artificial Intelligence! 🤖✨

## ✨ Main Features

- 🗂️ **Template Management:**
  - On startup, the project checks for and automatically creates the `.agenti` directory in your home folder (`<user.home>`) if needed.
  - Reads all `.md` templates from the `<user.home>/.agenti/templates` directory.

- 🖥️ **Intuitive Web Interface:**
  - The main page (`index.html`) displays a left column with buttons, each representing a found template.
  - Only `.md` files are considered templates.

- 📝 **Dynamic Prompt Editing:**
  - Textarea for composing and editing your prompt.
  - **Add** button ➕: adds the textarea content to the end of the current prompt.
  - **Show** button 👁️: displays the current prompt in a modal (alert/bootstrap).

- 📚 **Nested Templates:**
  - Clicking a template button loads the `.md` file content as new buttons below the textarea.
  - Clicking these new buttons adds the template content to the textarea.

- 💾 **Edit and Save in Modal:**
  - When showing the prompt in the modal, any edits made in the modal's textarea can be saved to the current prompt by clicking **Save** (button only visible after editing).

## 🛠️ How to Use

1. Clone the repository and run the Java (Spring Boot) project.
2. Access the web interface at `http://localhost:8080`.
3. Manage your templates in `<user.home>/.agenti/templates`.
4. Quickly create, edit, and save prompts visually!

## 📦 Project Structure

```
project-root/
├── src/
│   ├── main/java/io/github/akumosstl/agentic/
│   ├── resources/templates/index.html
│   └── ...
├── environment.bat
├── pom.xml
└── README.md
```

## 🤝 Contributing

Contributions are welcome! Feel free to open issues or pull requests.

## 📄 License

This project is licensed under the MIT License.

---

Made with 💡 by AkumoSTL
