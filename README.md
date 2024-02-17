# AI Course Master Project

AI Course Master is an ambitious project that blends cutting-edge technology with forward-thinking education. This full-stack tutorial explores the latest frontiers of technology and web development, aiming to revolutionize the educational landscape.

## Getting Started

To get a copy of the project up and running on your local machine, follow these steps:

### Prerequisites

Make sure you have Node.js and npm installed on your machine.

### Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Aalok786/ai-course-master.git
   ```

2. Navigate to the project directory:

   ```bash
   cd ai-course-master
   ```

3. Create a `.env` file in the root(project>>src>>app>>api) of the project with the following content:

   ```env
   NEXTAUTH_SECRET=
   GOOGLE_CLIENT_ID=
   GOOGLE_CLIENT_SECRET=
   DATABASE_URL=
   OPENAI_API_KEY=
   YOUTUBE_API_KEY=
   STRIPE_API_KEY=
   NEXTAUTH_URL=http://localhost:3000
   ```

   Fill in the values for each variable:

   - `NEXTAUTH_SECRET`: Secret key for NextAuth.
   - `GOOGLE_CLIENT_ID` and `GOOGLE_CLIENT_SECRET`: Google API credentials for authentication.
   - `DATABASE_URL`: URL for your database.
   - `OPENAI_API_KEY`: API key for OpenAI's ChatGPT.
   - `YOUTUBE_API_KEY`: API key for YouTube integration.
   - `STRIPE_API_KEY`: API key for Stripe payment processing.

### Running the Project

To run the project locally, follow these steps:

1. Install the project dependencies:

   ```bash
   npm install
   ```

2. Start the development server:

   ```bash
   npm run dev
   ```

3. Open your web browser and go to [http://localhost:3000](http://localhost:3000).

## Contributing

If you'd like to contribute to the project, please follow our [Contributing Guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to *Abhishek Chhapani* and *Riya Chaurasia* for leading this ambitious project.
- Inspiration from the transformative journey into the latest technologies.

Happy coding!
```