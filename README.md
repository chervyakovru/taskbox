## Intro to Storybook

![](https://353a23c500dde3b2ad58-c49fe7e7355d384845270f4a7a0a7aa1.ssl.cf2.rackcdn.com/5e85040d4041f504470e9f3e/screenshot.png)

[![Netlify Status](https://api.netlify.com/api/v1/badges/17945cc6-6085-4d91-a556-aa672a5a8a22/deploy-status)](https://app.netlify.com/sites/chervyakovru-taskbox/deploys)

This repository is my first touch of Storybook with [Intro to Storybook at learnstorybook.com](https://www.learnstorybook.com/ ). Along the way i learned how to build, compose, test, and deploy UI components.

### Used technologes
- Configured controlled environment with [Knobs addon](https://github.com/storybookjs/storybook/tree/master/addons/knobs)
- Snapshot tests with [Storyshots](https://github.com/storybookjs/storybook/tree/master/addons/storyshots/storyshots-core)
- Unit tests with [Jest](https://jestjs.io/)
- Visual regression testing with [Chromatic](https://www.chromaticqa.com/)
- Сontinuous deployment with [Netlify](https://www.netlify.com/)

Use the following commands for local startup:

    clone https://github.com/chervyakovru/taskbox.git
    cd taskbox
    npm i
	npm run storybook
