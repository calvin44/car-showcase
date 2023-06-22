# Car Showcase App

Welcome to the Car Showcase App! This is a web application built using Next.js, Tailwind CSS, and TypeScript. It allows users to browse and filter cars from a curated API and display corresponding car images.

## Features

* Browse a collection of cars from the API-Ninjas car database
* Filter cars based on various criteria such as make, model, year, and price
* View detailed information about each car, including specifications and pricing
* Display high-quality images of the cars fetched from the Imagin Studio API

## Installation

To run the Car Showcase App locally, follow these steps:

1. Clone the repository to your local machine using the following command:

   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">git clone https://github.com/your-username/car-showcase-app.git
   </code></div></div></pre>
2. Navigate to the project directory:

   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">cd car-showcase-app
   </code></div></div></pre>
3. Install the dependencies:

   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">npm install
   </code></div></div></pre>
4. Create a `.env.local` file in the root directory of the project and add the following environment variables:

   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>plaintext</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-plaintext">API_NINJAS_API_KEY=your_api_ninjas_api_key
   IMAGIN_STUDIO_API_KEY=your_imagin_studio_api_key
   </code></div></div></pre>

   Make sure to replace `your_api_ninjas_api_key` and `your_imagin_studio_api_key` with your actual API keys. You can obtain these keys by signing up on the respective API provider websites.
5. Start the development server:

   <pre><div class="bg-black rounded-md mb-4"><div class="flex items-center relative text-gray-200 bg-gray-800 px-4 py-2 text-xs font-sans justify-between rounded-t-md"><span>bash</span><button class="flex ml-auto gap-2"><svg stroke="currentColor" fill="none" stroke-width="2" viewBox="0 0 24 24" stroke-linecap="round" stroke-linejoin="round" class="h-4 w-4" height="1em" width="1em" xmlns="http://www.w3.org/2000/svg"><path d="M16 4h2a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2h2"></path><rect x="8" y="2" width="8" height="4" rx="1" ry="1"></rect></svg>Copy code</button></div><div class="p-4 overflow-y-auto"><code class="!whitespace-pre hljs language-bash">npm run dev
   </code></div></div></pre>

   The app will be accessible at `http://localhost:3000`.

## Usage

* Upon launching the Car Showcase App, you will be presented with a list of cars fetched from the API-Ninjas car database.
* Use the provided filters to narrow down your search based on make, model, year, and price.
* Click on a car to view more details, including specifications and pricing information.
* The car images are fetched from the Imagin Studio API and displayed alongside the car details.

## Contributing

Contributions to the Car Showcase App are welcome! If you find any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

Before making any contributions, please review the [contribution guidelines](https://chat.openai.com/CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](https://chat.openai.com/LICENSE).

## Acknowledgments

* The Car Showcase App utilizes the following APIs:
  * [API-Ninjas Car API](https://api-ninjas.com/api/cars)
  * [Imagin Studio API](https://api.imagin.studio/)
* Special thanks to the developers of Next.js, Tailwind CSS, and TypeScript for their amazing tools and libraries.
