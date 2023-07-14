# Dependency Management Filenames

This project provides a JSON file containing a list of popular framework dependency management filenames, including language, framework, and extra files.

## Usage

Import the `dmf.json` file in your project and parse it to get the required information about dependency management filenames for various programming languages and frameworks.

## Contributing

We welcome contributions from the community! If you'd like to add a new language, framework, or additional information, feel free to submit a pull request or open an issue for discussion.

## Made with ChatGPT

This project was created with the help of [OpenAI's ChatGPT](https://openai.com/research/chatgpt/), a powerful AI language model. ChatGPT has been utilized to generate the comprehensive list of dependency management filenames for various programming languages and frameworks.

### How ChatGPT was used

We communicated with ChatGPT in a conversational manner to gather information about the popular dependency management filenames for different programming languages and frameworks, as well as to create most of the documentation for this project. By interacting with ChatGPT, we were able to generate an extensive JSON file containing all the necessary details about dependency management filenames and save time compared to traditional manual research.

ChatGPT continues to be an invaluable resource for this project, allowing us to periodically update our JSON file with new languages, frameworks, and up-to-date dependency management information.

## Prompts

During the creation and maintenance of this project, several prompts were used with ChatGPT to gather accurate and up-to-date information about dependency management filenames for various programming languages and frameworks. Examples of the prompts used are as follows:

* System message: As a professional developer with 20 years of experience, provide a JSON file containing popular framework dependency management filenames, including the language, framework, and extra:

below is a few shot example:

```json
[{
 "language": "JavaScript",
 "framework": [{
  "name": "Node.js yarn",
  "dmf": "package.json",
  "extra": [
   "yarn.lock"
  ]
 }]
}, {
 "language": "Java",
 "framework": [{
  "name": "Gradle",
  "dmf": "build.gradle",
  "extra": [
   "settings.gradle",
   "gradle.properties"
  ]
 }]
}]
```

* What are the DMF in Java-based projects using Gradle or Maven?

These prompts are intended to serve as examples for those who wish to interact with ChatGPT for similar purposes or expand the current list of dependency management filenames. Feel free to adapt and modify the above prompts according to your specific needs when using ChatGPT.

## License

This project is released under the [MIT License](LICENSE).
