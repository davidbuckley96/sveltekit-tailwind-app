# SvelteKit Tailwind App

This is a SvelteKit project configured with Tailwind CSS. It contains a series of instructions on how to set up and run the project locally on your machine.

## Prerequisites

Make sure you have the following software installed on your machine:

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

## Clone the Repository

To obtain a copy of the project, follow these steps:

1. Open your terminal (or command prompt);
2. Navigate to the directory where you want to clone the repository;
3. Run the following command: `https://github.com/davidbuckley96/sveltekit-tailwind-app.git`;
4. Navigate into the project directory: `cd sveltekit-tailwind-app`;

## Install Dependencies

Before running the project, you need to install the necessary dependencies. Run the following command:
`npm install`

## Run the Project

Now you are ready to run the project. Use the following command to start the development server:

`npm run dev`

After running the command, you will see output in the terminal indicating that your application is running, usually at an address like `http://localhost:5173`.

## Access the Application

Open your browser and go to:
<http://localhost:5173>

You should see the SvelteKit application up and running.

## Project Enhancements

During the project development, I made a decision to introduce more than one input field, specifically adding two password fields. Additionally, I implemented a check to verify that both passwords match, which was not part of the original project proposal. This was introduced to enhance the user experience by preventing inconsistent passwords at the form submission stage.

## Challenges Faced

Despite my experience with web development in Django, this was my first time working with the SvelteKit compiler. This required prior research and study to understand how a SvelteKit project is structured, the importance of reusable components, and how to configure routes.

Initially, I had to thoroughly read the official documentation at [SvelteKit Docs](https://kit.svelte.dev/docs/introduction) to get acquainted with the framework. One of the early challenges I faced was implementing the form validation logic. At first, I tried to call the validation function using an `onclick` event directly in the Button component. However, I soon realized this approach made the button less reusable. It made more sense to leave the Button component generic and add the validation logic explicitly within the form component. This allows for multiple button uses throughout the project, each with its specific processing logic.

Another difficulty I encountered was understanding how routes are defined in SvelteKit. This process differs significantly from Django's routing system, but with the help of the official documentation and user queries on Stack Overflow, I was able to resolve my issues.

Overall, I believe that the experience of learning a new technology in a short amount of time was valuable. It provided insight into the relevance and potential of SvelteKit. If this were a larger project in ongoing development, I believe that with persistence, I would be able to gain greater mastery of the tools that SvelteKit offers, enabling faster and more efficient results.

## Contributions

If you would like to contribute to this project, feel free to fork the repository, create a new branch, and submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).


