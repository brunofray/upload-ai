
<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>upload-ai
</h1>
<h3>◦ Accelerating innovation through intelligent uploads!</h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style&logo=JavaScript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style&logo=HTML5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style&logo=PostCSS&logoColor=white" alt="PostCSS" />
<img src="https://img.shields.io/badge/Autoprefixer-DD3735.svg?style&logo=Autoprefixer&logoColor=white" alt="Autoprefixer" />
<img src="https://img.shields.io/badge/Vite-646CFF.svg?style&logo=Vite&logoColor=white" alt="Vite" />
<img src="https://img.shields.io/badge/React-61DAFB.svg?style&logo=React&logoColor=black" alt="React" />
<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style&logo=Axios&logoColor=white" alt="Axios" />

<img src="https://img.shields.io/badge/ESLint-4B32C3.svg?style&logo=ESLint&logoColor=white" alt="ESLint" />
<img src="https://img.shields.io/badge/OpenAI-412991.svg?style&logo=OpenAI&logoColor=white" alt="OpenAI" />
<img src="https://img.shields.io/badge/TypeScript-3178C6.svg?style&logo=TypeScript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/Prisma-2D3748.svg?style&logo=Prisma&logoColor=white" alt="Prisma" />
<img src="https://img.shields.io/badge/JSON-000000.svg?style&logo=JSON&logoColor=white" alt="JSON" />
<img src="https://img.shields.io/badge/Fastify-000000.svg?style&logo=Fastify&logoColor=white" alt="Fastify" />
</p>
<img src="https://img.shields.io/github/languages/top/brunofray/upload-ai?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/brunofray/upload-ai?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/brunofray/upload-ai?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/brunofray/upload-ai?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [🧩 Modules](#modules)
- [🚀 Getting Started](#-getting-started)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The project is a video transcription application that provides core functionalities such as uploading audio/video files, creating transcriptions, generating AI completions, and retrieving prompts for transcriptions. It utilizes technologies like Fastify, React, Tailwind CSS, Prisma, and the OpenAI API. The application's purpose is to provide users with a convenient and efficient way to transcribe videos and generate AI-based summaries, saving them time and effort in manually transcribing and summarizing large amounts of video content. Its value proposition lies in automating the transcription process and leveraging AI for efficient analysis and summarization of video content.

---

## ⚙️ Features

| Feature                | Description                           |
| ---------------------- | ------------------------------------- |
| **⚙️ Architecture**     | The codebase follows a client-server architecture design. The back-end uses Fastify as the server framework and Prisma as the ORM for database operations. The front-end is a React application. The system relies on a REST API for communication between the front-end and back-end components. Limit your response to a maximum of 200 characters.    |
| **📖 Documentation**   | The codebase provides code comments and descriptive commit messages, which enhance readability and understanding. However, there is no separate documentation file included. Additional documentation could be useful for newcomers to understand the codebase more easily. Limit your response to a maximum of 200 characters.    |
| **🔗 Dependencies**    | The codebase relies on external libraries like Fastify and Prisma on the backend, React and Radix UI on the frontend, clsx, tailwind CSS, and Vite for styling and development. It also utilizes the OpenAI API for AI-generated summary. Limit your response to a maximum of 200 characters.    |
| **🧩 Modularity**      | The codebase is organized into several files and folders, each serving a specific purpose. It follows the MVC (Model-View-Controller) pattern. The backend has separate files for routes, ORM, and configuration. The front-end is divided into components responsible for specific UI functionality. This modularity promotes code reuse and maintainability. Limit your response to a maximum of 200 characters.    |
| **✔️ Testing**          | The codebase doesn't include explicit testing files, which makes it difficult to assess the testing strategy and tools employed. To ensure code quality, unit tests, integration tests, and end-to-end tests could be implemented using frameworks such as Jest or Cypress. Limit your response to a maximum of 200 characters.    |
| **⚡️ Performance**      | Performance analysis requires access to runtime data and system resources. Without profiling and benchmarking data, it is challenging to evaluate the system's performance. However, ensuring efficient code implementation and optimizing resource usage can enhance the overall performance. Limit your response to a maximum of 200 characters.    |
| **🔐 Security**        | The codebase doesn't provide explicit information about security measures implemented. Considering the inclusion of third-party libraries, handling of user-uploaded files, and interactions with OpenAI API, measures like sanitizing inputs, file validations, encryption, secure communication (HTTPS), and access control should be considered for secure operations. Limit your response to a maximum of 200 characters.    |
| **🔀 Version Control** | The codebase relies on Git for version control, as evident from the provided GitHub repository. Git is a distributed version control system, which facilitates collaboration, code review, and team coordination. The use of branching and features branching methodologies could provide scalable development and release management strategies. Limit your response to a maximum of 200 characters.    |
| **🔌 Integrations**    | The system interacts with external services like the OpenAI API for AI-generated summaries and the Prisma ORM for database operations.

---

## 🧩 Modules

<details closed><summary>Root</summary>

| File                                                                                                                                           | Summary                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| ---                                                                                                                                            | ---                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| [routes.http](https://github.com/brunofray/upload-ai/blob/main/api\routes.http)                                                                | The code snippet provides core functionalities for a video transcription application:1. Get all prompts: Retrieves a list of prompts for transcriptions.2. Upload audio/video file: Sends a file to be transcribed.3. Create transcriptions: Creates a transcription for a specific video, with a provided prompt.4. Generate AI completion: Requests AI-generated summary for a transcription, based on given parameters.                                                                                                                                 |
| [schema.prisma](https://github.com/brunofray/upload-ai/blob/main/api\prisma\schema.prisma)                                                     | This code snippet includes the configuration for a database and the definition of two models: Video and Prompt. The Video model consists of properties such as ID, name, path, transcription, and createdAt. The Prompt model includes properties like ID, title, and template. The code also specifies the generator client to be used as "prisma-client-js".                                                                                                                                                                                             |
| [seed.ts](https://github.com/brunofray/upload-ai/blob/main/api\prisma\seed.ts)                                                                 | This code snippet utilizes the Prisma client to perform database operations. The main function deletes existing prompt data and creates new prompts with specific titles and templates. The templates include instructions to generate YouTube video titles and descriptions using given transcriptions. The function also includes character/word restrictions, guidelines for attractive content, and the inclusion of hashtags. Finally, the Prisma client is set to disconnect once the main function has been executed, with error handling in place. |
| [migration.sql](https://github.com/brunofray/upload-ai/blob/main/api\prisma\migrations\20230912230613_create_videos_and_prompts\migration.sql) | The code snippet creates two database tables: "Video" and "Prompt". The "Video" table has fields for id, name, path, transcription, and createdAt. The "Prompt" table has fields for id, title, and template. The tables are used to store video information and prompt details, respectively.                                                                                                                                                                                                                                                             |
| [server.ts](https://github.com/brunofray/upload-ai/blob/main/api\src\server.ts)                                                                | This code snippet creates a fastify server and sets up routes for fetching prompts, uploading videos, creating transcriptions, and generating AI completions. It also configures CORS and listens on port 3333.                                                                                                                                                                                                                                                                                                                                            |
| [openai.ts](https://github.com/brunofray/upload-ai/blob/main/api\src\lib\openai.ts)                                                            | The code snippet configures the OpenAI client by importing the necessary packages and initializing it with the provided API key from the environment variables. This allows the client to make requests to the OpenAI API for natural language processing tasks.                                                                                                                                                                                                                                                                                           |
| [prisma.ts](https://github.com/brunofray/upload-ai/blob/main/api\src\lib\prisma.ts)                                                            | The provided code snippet imports the PrismaClient from the "@prisma/client" package. It instantiates an object of PrismaClient class and exports it as "prisma". This object allows interaction with the Prisma ORM for database operations.                                                                                                                                                                                                                                                                                                              |
| [create-transcription.ts](https://github.com/brunofray/upload-ai/blob/main/api\src\routes\create-transcription.ts)                             | This code defines a route for creating transcriptions of videos. It accepts a video ID and a prompt from the request body, retrieves the video's path using the ID, creates a readable stream for the audio file, transcribes the audio using the OpenAI API, and updates the video's transcription in the database. Finally, it returns the transcription as the response.                                                                                                                                                                                |
| [generate-ai-completion.ts](https://github.com/brunofray/upload-ai/blob/main/api\src\routes\generate-ai-completion.ts)                         | This code snippet sets up a route for generating AI completions. It receives a video ID, prompt, and temperature. It fetches the video transcription, validates the input, and creates an AI completion using OpenAI's GPT-3.5 model. The completion is streamed back as a response.                                                                                                                                                                                                                                                                       |
| [get-all-prompts.ts](https://github.com/brunofray/upload-ai/blob/main/api\src\routes\get-all-prompts.ts)                                       | The code exports a function that adds a route to a Fastify server. This route handles the GET request to'/prompts' and retrieves all prompts from a Prisma database. The retrieved prompts are then returned as the response.                                                                                                                                                                                                                                                                                                                              |
| [upload-video.ts](https://github.com/brunofray/upload-ai/blob/main/api\src\routes\upload-video.ts)                                             | The provided code is a route handler function for uploading videos. It uses the Fastify framework and related modules for handling multipart file uploads, while enforcing limits on file size. The code saves the uploaded file to a temporary location on disk, generates a unique filename with a random UUID, and stores the file path and metadata in a database using Prisma. The code then returns the stored video object as a response.                                                                                                           |
| [index.html](https://github.com/brunofray/upload-ai/blob/main/web\index.html)                                                                  | The provided code is an HTML document that includes a JavaScript file. It sets the document's title to "upload.ai" and defines a div element with an id of "root". The JavaScript file "main.tsx" is imported as a module, suggesting it contains the main functionality of the web application.                                                                                                                                                                                                                                                           |
| [postcss.config.js](https://github.com/brunofray/upload-ai/blob/main/web\postcss.config.js)                                                    | This code exports a configuration object that includes two plugins, Tailwind CSS and Autoprefixer, for use in a project.                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| [tailwind.config.js](https://github.com/brunofray/upload-ai/blob/main/web\tailwind.config.js)                                                  | This code snippet defines the configuration for a Tailwind CSS theme. It sets up the dark mode, defines the content files to be processed, configures the container style, extends color palettes and animations, and includes a plugin for animation support.                                                                                                                                                                                                                                                                                             |
| [vite.config.ts](https://github.com/brunofray/upload-ai/blob/main/web\vite.config.ts)                                                          | This code snippet includes core functionalities for a Vite configuration file. It integrates the React plugin, excludes specific dependencies during optimization, and configures an alias for the `src` directory.                                                                                                                                                                                                                                                                                                                                        |
| [app.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\app.tsx)                                                                    | The provided code snippet is part of a React application. It imports various UI components for buttons, separators, text areas, selects, sliders, and forms. It also includes components for video input and prompt selection. There is state management using React's useState hook.The code sets up a form for user input and uses the useCompletion hook to handle API requests for generating AI output.                                                                                                                                               |
| [index.css](https://github.com/brunofray/upload-ai/blob/main/web\src\index.css)                                                                | The code snippet includes a set of predefined values for colors, such as background, foreground, card, primary, etc. It also applies some base styles, like borders and background color, to all elements and the body of the page. These styles are defined using the tailwind CSS framework.                                                                                                                                                                                                                                                             |
| [main.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\main.tsx)                                                                  | The code imports necessary modules from React for rendering, imports the root component from'app.tsx', and a CSS file. It uses ReactDOM's createRoot method to mount the root component to the'root' element in the DOM, wrapped in a React StrictMode component for debugging and development purposes.                                                                                                                                                                                                                                                   |
| [vite-env.d.ts](https://github.com/brunofray/upload-ai/blob/main/web\src\vite-env.d.ts)                                                        | The code snippet includes a reference to the Vite client library.The purpose of this library is to enhance the development experience when using Vite, a build tool for modern web applications.The reference allows accessing and utilizing the various features and functionalities provided by the Vite client library.                                                                                                                                                                                                                                 |
| [prompt-select.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\prompt-select.tsx)                                     | The code defines a React component called PromptSelect that displays a dropdown menu. The component fetches a list of prompts from an API and renders each prompt as an option in the dropdown. When a prompt is selected, it calls a callback function provided in the props and passes the corresponding template as an argument.                                                                                                                                                                                                                        |
| [video-input-form.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\video-input-form.tsx)                               | This code snippet is a React component that represents a form for uploading and processing videos. It allows the user to select a video file, convert it to audio, and upload it to a server. It also includes a prompt for transcription and displays the conversion and upload status. The form includes validations and messaging for each step of the process.                                                                                                                                                                                         |
| [button.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\ui\button.tsx)                                                | This code snippet defines a `Button` component using React and Radix UI. It uses class variance authority to create variant styles for different button types. The component supports different sizes and can be used as a regular button or wrapped with another component. The `buttonVariants` function generates the appropriate class names based on the variant and size props. The `Button` component applies the generated class names and renders either a `button` element or a `Slot` component.                                                |
| [label.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\ui\label.tsx)                                                  | This code snippet defines a React component called "Label" that extends a radix-ui Label component and applies variant styles using class-variance-authority. The Label component passes down props, applies variant styles based on conditions, and renders the LabelPrimitive root element with the appropriate classNames.                                                                                                                                                                                                                              |
| [select.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\ui\select.tsx)                                                | The code snippet exports multiple components for building a customizable select dropdown menu in a React application using the Radix UI library. The components include Select, SelectGroup, SelectValue, SelectTrigger, SelectContent, SelectLabel, SelectItem, and SelectSeparator. These components provide functionality such as rendering the select box, handling trigger events, displaying options, applying styles, and more.                                                                                                                     |
| [separator.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\ui\separator.tsx)                                          | This code snippet defines a reactive separator React component that allows users to create horizontal or vertical dividers. It utilizes the "@radix-ui/react-separator" library, with props for customizing orientation, decorative styles, and className. It exports the Separator component for use in other modules.                                                                                                                                                                                                                                    |
| [slider.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\ui\slider.tsx)                                                | The provided code snippet is a Slider component using the Radix UI library. It renders a slider input element with a track, a range, and a thumb. It also includes various styles and states such as focus and disabled. The component is implemented as a React forwardRef component, allowing it to forward its ref to the underlying slider element.                                                                                                                                                                                                    |
| [textarea.tsx](https://github.com/brunofray/upload-ai/blob/main/web\src\components\ui\textarea.tsx)                                            | This code defines a reusable React component called Textarea. It renders a textarea element with customizable className and other props. It applies CSS styles for various states like focus and disabled, and supports a ref prop.                                                                                                                                                                                                                                                                                                                        |
| [ffmpeg-worker.js](https://github.com/brunofray/upload-ai/blob/main/web\src\ffmpeg\ffmpeg-worker.js)                                           | The provided code snippet is a worker script that can be used in a Node.js environment or within web workers. It handles incoming messages and executes various commands, such as loading a module, running functions, canceling execution, and checking the mailbox. It also provides error handling and logging functionality.                                                                                                                                                                                                                           |
| [axios.ts](https://github.com/brunofray/upload-ai/blob/main/web\src\lib\axios.ts)                                                              | The provided code snippet creates an instance of Axios, a popular HTTP client, and configures it with a base URL of'http://localhost:3333'. This instance can be used to make HTTP requests to the specified base URL.                                                                                                                                                                                                                                                                                                                                     |
| [ffmpeg.ts](https://github.com/brunofray/upload-ai/blob/main/web\src\lib\ffmpeg.ts)                                                            | The provided code imports and initializes an FFmpeg object, which provides functionality for handling multimedia files. The code checks if the FFmpeg object has already been instantiated, and if not, creates a new instance. It then checks if the FFmpeg library has already been loaded, and if not, asynchronously loads the core, wasm, and worker URLs. Finally, it returns the instantiated FFmpeg object.                                                                                                                                        |
| [utils.ts](https://github.com/brunofray/upload-ai/blob/main/web\src\lib\utils.ts)                                                              | The code snippet exports a function called `cn` that takes in multiple class values as inputs. It applies these values to `clsx` function from the "clsx" library. Then, it merges the resulting classes using the `twMerge` function from the "tailwind-merge" library. The `cn` function provides a simpler way to combine and apply class names in a Tailwind CSS project.                                                                                                                                                                              |

</details>

---

## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> - `ℹ️ Create your .env file based in the .env.example and add your OPENAI_KEY inside api/ folder`

### 📦 Installation

1. Clone the upload-ai repository:
```sh
git clone https://github.com/brunofray/upload-ai
```

2. Change to the project directory:
```sh
cd upload-ai
```

3. Install the dependencies:
```sh
cd web/ && pnpm i && cd .. && cd api/ && pnpm i && cd ..
cd api/ && pnpm prisma migrate dev && pnpm prisma db seed && cd ..
```

### 🎮 Using upload-ai

```sh
cd web/ && pnpm run dev
cd api/ && pnpm run dev
```

### 🎬 Using prisma studio
```sh
cd api/ && pnpm prisma studio
```

---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/brunofray/upload-ai/blob/main/LICENSE) file for additional info.

---

## 👏 Acknowledgments

---

> This project was developed with ❤️ by **[@Bruno Fray](https://www.linkedin.com/in/brunofray/)**, with the instructor **[@Diego3g](https://github.com/diego3g)**, during the **[Next Level Week AI](https://rocketseat.com.br/)** from **[Rocketseat](https://www.linkedin.com/school/rocketseat/about/)** 💜. <br>
> If this helped you, give it a ⭐, it will help me too! 😉

---
