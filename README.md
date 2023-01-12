# AtoumGPT

AtoumGPT is a customizable version of ChatGPT, an advanced language model developed by OpenAI. Using the OpenAI API, it allows users to select a specific model and adjust its temperature, providing a more tailored and personalized experience.

This software is still under development and new features are constantly being added. We welcome contributions and suggestions from the open-source community.

## Features
- Select from a variety of pre-trained OpenAI models
- Adjust the temperature of the selected model to control the results
- Generate human-like text responses

## How to Use
1. Clone the repository
```
git clone https://github.com/moatoum/AtoumGPT.git
```

2. Install npm
```
npm install -g npm
```

3. Add your OpenAI API key in ./index.js file, as follows:
```
const configuration = new Configuration({
    organization: "YOUR_ORG_ID",
    apiKey: "YOUR_API_KEY",
});
```

4. To start the web app, have two terminals open at the same time.
  * In the root directory, run:
```
node index.js
```
  * In the /client directory, run:
```
npm start
```

## License
AtoumGPT is released under the MIT License. This means that the software is free to use, modify, and distribute.

## Contributions & Support
We welcome contributions from the open-source community. If you have any ideas, suggestions or questions, please feel free to open an issue in this repository.