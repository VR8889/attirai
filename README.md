# Attirai Project 
AttirAI revolutionizes the online shopping journey by introducing an AI-powered digital fitting room. This innovative platform is designed to transform how consumers and retailers approach fashion retail. With AttirAI, shoppers can accurately visualize how clothing items will fit, tailored to their specific body measurements and the unique design features of each garment. This technology not only streamlines the decision-making process, saving valuable time and reducing returns, but also brings a new level of convenience and personalization to e-commerce. Leveraging Web3, AttirAI introduces a tokenized system that rewards participation and encourages the community to engage and share their fashion experiences. This sustainable, forward-thinking approach aims to reshape the online apparel industry, making it more interactive, efficient, and user-centric.


Previous versrion of the project: https://github.com/mrpejker/attirai

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.0.

## R&D: AI Models considered
The AI technologies that allow for the best fitting of outfits in photos, videos, or 3D models of the user include the following:
- Form-fitting algorithms: These AI algorithms create an accurate model of customers' bodies by utilizing information gathered from consumers as well as items to match the product to the person
- Image-recognition algorithms: These algorithms help to recognize objects within a picture to detect what a person looks like, enabling the virtual try-on of clothes and the recognition of body shapes and sizes
- Generative AI models: Generative AI models can produce life-like portrayals of clothing on people, taking into account details such as how the clothing drapes, folds, clings, stretches, and wrinkles. This technology generates high-quality, realistic images of the person wearing the garment
- Body scanning and virtual try-on solutions: AI-powered body scanning and virtual try-on solutions can digitally measure customers' bodies with unmatched accuracy, allowing for the generation of realistic 3D models that accurately represent their body type

Fitting Models tried:

1) TryOnDiffusion by Google Research https://tryondiffusion.github.io/
This implementation is limited is requires further substantial development to leverage proposed AI technologies to enhance the online shopping experience and address common pain points in e-commerce (doesn't work effective on big volumes of images, requires re-training on the brands' data input).

2) Zeekit's latest technology is  not open for general audience. It's built on a combination of real-time image processing, computer vision, deep learning, and other AI technologies to provide a virtual fitting room experience for online shoppers. The platform allows users to virtually "try on" clothing when shopping online by leveraging a simulation that takes into account body dimensions, fit, size, and even the fabric of the garment itself. Acquired by Walmart.

3) Revery.ai: This startup is pioneering in creating an online dressing room experience using computer vision and artificial intelligence. They process over a million garments weekly using existing catalog images, a scale previously challenging for virtual dressing rooms. Revery.ai stands out by using deep learning and computer vision for a more realistic drape of clothing and allows users to customize their clothing model to better resemble their appearance, including skin tone and hair styles. Their technology has shown to significantly increase conversion rates, with reports of a 380% increase in an A/B test for Zalora. Chosen for the demo in Ventureton.

## Demo for proof of concept
Disclaimer: The deployed Demo to showcase idea is using Revery AI API. Conducted research showed that developing an implementation on the basis on TryOn model will take more time than we were having during hackathon. 
<img width="759" alt="image" src="https://github.com/VR8889/attirai/assets/8280427/831c0c44-10ab-4ddf-b5a0-9eeb8bf45c04">

*Website*: https://attirai-meta.web.app/main
Video screencast: <a Demo 1 href = 'https://youtu.be/aiA3NT9ZZCM'>


## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
