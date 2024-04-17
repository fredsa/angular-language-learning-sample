# Angular Language Learning Sample
A developer sample demonstrating the use of [angular](http://angular.dev) and [Gemini API](http://ai.google.dev) to create dynamic quiz questions for languages supported by Gemini.

## Setup & Getting Started

### Before you start
Your system needs to be configured to run [angular](https://angular.dev/tools/cli/setup-local#dependencies).

You need Gemini API key in order to run this demo. Here's how:
1. Launch [Google AI Studio](https://aistudio.google.com/)
1. Click "Get API Key"

> Caution: **Using the Google AI SDK for JavaScript directly from a client-side
app is recommended for prototyping only.** For non-prototyping use cases, we
strongly recommend that you call the Google AI Gemini API only server-side to
keep your API key safe. If you embed your API key directly in your JavaScript
app or fetch it remotely at runtime, you risk potentially exposing your API key
to malicious actors.

### Getting the code
You have two options to get this code:
* [Open it in IDX](https://idx.google.com/import?url=https://github.com/google-gemini/angular-language-learning-sample)
* Clone this repo to your local machine.

### Configure your environment
To run this application, you can either
* hard code your API key in `server.ts`
* set it as an environment variable called `API_KEY`


### Starting the application
1. Build the example with `ng build`
1. Run the demo with `npm start`
1. Navigate to `http://localhost:4000/`

That's it, have fun!